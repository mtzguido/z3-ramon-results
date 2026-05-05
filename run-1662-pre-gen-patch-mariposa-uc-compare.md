Comparing data and data


# SUMMARY
- LHS tests = 41
- RHS tests = 41
- LHS success = 39  (95.1219512195122%)
- RHS success = 39  (95.1219512195122%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: pre-gen-patch-mariposa-uc
Runner: rise-runner-1
Z3 repo: CanCebeci/z3
Z3 commit: 51cbbe0a0ea3259ec92255e86e5818d1d6a9e523
Z3 branch: 51cbbe0a0ea3259ec92255e86e5818d1d6a9e523
Z3 options: "%OPTIONS2%"
Z3 inputs: inputs/mariposa/unstable_core
Z3 commit message: fix #9293

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: pre-gen-patch-mariposa-uc
Runner: rise-runner-1
Z3 repo: CanCebeci/z3
Z3 commit: 51cbbe0a0ea3259ec92255e86e5818d1d6a9e523
Z3 branch: 51cbbe0a0ea3259ec92255e86e5818d1d6a9e523
Z3 options: "%OPTIONS2%"
Z3 inputs: inputs/mariposa/unstable_core
Z3 commit message: fix #9293

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.FlushPreservesLookups.smt2         |   3.881s  |   3.881s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ReqWrite2StepPreservesInv.smt2  |  18.833s  |  18.833s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesProcessWrite.smt2  |   1.750s  |   1.750s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.PageInNodeResp.smt2                        |  18.098s  |  18.098s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.append.smt2   |   2.472s  |   2.472s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.set__bit__to__0__self__uint64.smt2  |   0.191s  |   0.191s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.set__bit__to__1__self__uint64.smt2  |   0.193s  |   0.193s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.BinarySearchQuery.smt2          |   3.423s  |   3.423s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.UniqueRepr.smt2  |   0.366s  |   0.366s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.SplitIndexAllKeys.smt2  |  23.575s  |  23.575s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-LruImpl.i.dfy.Impl__LruImpl.LruImplQueue.Use.smt2                |  15.046s  |  15.046s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SubIndex.smt2    |   0.628s  |   0.628s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SubReprLowerBound.smt2  |   0.463s  |   0.463s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallArray.smt2  |   2.172s  |   2.172s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint32Array.smt2  |   0.681s  |   0.681s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint64Array.smt2  |   2.719s  |   2.719s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__2toX.smt2                    |   0.708s  |   0.708s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__div__denominator.smt2        |   0.359s  |   0.359s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Math-mod_auto_proofs.i.dfy.Impl__Math____mod__auto__proofs__i.__default.lemma__mod__induction__forall2.smt2  |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|d_komodo-verified-ptebits.i.dfyImpl___module.__default.lemma__l1ptesmatch.smt2              |   3.255s  |   3.255s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.FlushPreservesLookups.smt2         |   3.881s  |   3.881s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ReqWrite2StepPreservesInv.smt2  |  18.833s  |  18.833s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesProcessWrite.smt2  |   1.750s  |   1.750s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.PageInNodeResp.smt2                        |  18.098s  |  18.098s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.append.smt2   |   2.472s  |   2.472s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.set__bit__to__0__self__uint64.smt2  |   0.191s  |   0.191s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.set__bit__to__1__self__uint64.smt2  |   0.193s  |   0.193s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.BinarySearchQuery.smt2          |   3.423s  |   3.423s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.UniqueRepr.smt2  |   0.366s  |   0.366s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.SplitIndexAllKeys.smt2  |  23.575s  |  23.575s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-LruImpl.i.dfy.Impl__LruImpl.LruImplQueue.Use.smt2                |  15.046s  |  15.046s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SubIndex.smt2    |   0.628s  |   0.628s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SubReprLowerBound.smt2  |   0.463s  |   0.463s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallArray.smt2  |   2.172s  |   2.172s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint32Array.smt2  |   0.681s  |   0.681s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint64Array.smt2  |   2.719s  |   2.719s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__2toX.smt2                    |   0.708s  |   0.708s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__div__denominator.smt2        |   0.359s  |   0.359s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Math-mod_auto_proofs.i.dfy.Impl__Math____mod__auto__proofs__i.__default.lemma__mod__induction__forall2.smt2  |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|d_komodo-verified-ptebits.i.dfyImpl___module.__default.lemma__l1ptesmatch.smt2              |   3.255s  |   3.255s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.FlushPreservesLookups.smt2         |   3.881s  |   3.881s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ReqWrite2StepPreservesInv.smt2  |  18.833s  |  18.833s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesProcessWrite.smt2  |   1.750s  |   1.750s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.PageInNodeResp.smt2                        |  18.098s  |  18.098s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.append.smt2   |   2.472s  |   2.472s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.set__bit__to__0__self__uint64.smt2  |   0.191s  |   0.191s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.set__bit__to__1__self__uint64.smt2  |   0.193s  |   0.193s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.BinarySearchQuery.smt2          |   3.423s  |   3.423s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.UniqueRepr.smt2  |   0.366s  |   0.366s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.SplitIndexAllKeys.smt2  |  23.575s  |  23.575s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-LruImpl.i.dfy.Impl__LruImpl.LruImplQueue.Use.smt2                |  15.046s  |  15.046s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SubIndex.smt2    |   0.628s  |   0.628s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SubReprLowerBound.smt2  |   0.463s  |   0.463s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallArray.smt2  |   2.172s  |   2.172s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint32Array.smt2  |   0.681s  |   0.681s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint64Array.smt2  |   2.719s  |   2.719s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__2toX.smt2                    |   0.708s  |   0.708s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__div__denominator.smt2        |   0.359s  |   0.359s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Math-mod_auto_proofs.i.dfy.Impl__Math____mod__auto__proofs__i.__default.lemma__mod__induction__forall2.smt2  |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|d_komodo-verified-ptebits.i.dfyImpl___module.__default.lemma__l1ptesmatch.smt2              |   3.255s  |   3.255s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.FlushPreservesLookups.smt2         |   3.881s  |   3.881s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ReqWrite2StepPreservesInv.smt2  |  18.833s  |  18.833s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesProcessWrite.smt2  |   1.750s  |   1.750s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.PageInNodeResp.smt2                        |  18.098s  |  18.098s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.append.smt2   |   2.472s  |   2.472s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.set__bit__to__0__self__uint64.smt2  |   0.191s  |   0.191s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.set__bit__to__1__self__uint64.smt2  |   0.193s  |   0.193s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.BinarySearchQuery.smt2          |   3.423s  |   3.423s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.UniqueRepr.smt2  |   0.366s  |   0.366s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.SplitIndexAllKeys.smt2  |  23.575s  |  23.575s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-LruImpl.i.dfy.Impl__LruImpl.LruImplQueue.Use.smt2                |  15.046s  |  15.046s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SubIndex.smt2    |   0.628s  |   0.628s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SubReprLowerBound.smt2  |   0.463s  |   0.463s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallArray.smt2  |   2.172s  |   2.172s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint32Array.smt2  |   0.681s  |   0.681s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint64Array.smt2  |   2.719s  |   2.719s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__2toX.smt2                    |   0.708s  |   0.708s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__div__denominator.smt2        |   0.359s  |   0.359s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Math-mod_auto_proofs.i.dfy.Impl__Math____mod__auto__proofs__i.__default.lemma__mod__induction__forall2.smt2  |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|d_komodo-verified-ptebits.i.dfyImpl___module.__default.lemma__l1ptesmatch.smt2              |   3.255s  |   3.255s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|s_komodo-1509.4.smt2                                                                       |  80.299s |5430.0MiB|
|s_komodo-1504.4.smt2                                                                       |  80.257s |4117.0MiB|
|d_komodo-verified-verify.gen.dfyImpl___module.__default.va__lemma__svc__returning__verify__inner.smt2 |  36.793s |409.0MiB|
|d_komodo-verified-secprop-conf_ni.i.dfyImpl___module.__default.lemma__initL2PTable__loweq__pdb.smt2 |  34.982s |334.0MiB|
|d_lvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.Impl__PivotBetreeSpecRefinement.__default.SplitChildrenConsistent.smt2 |  32.003s |202.0MiB|
|d_lvbkv-lib-Buckets-BucketsLib.i.dfy.Impl__BucketsLib.__default.WFProperSplitBucketInList.smt2 |  26.214s |250.0MiB|
|d_komodo-verified-verify.gen.dfyImpl___module.__default.va__lemma__svc__returning__verify.smt2 |  24.329s |227.0MiB|
|d_fvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.SplitIndexAllKeys.smt2 |  23.575s |206.0MiB|
|d_komodo-verified-sha-sha256.i.dfyImpl___module.__default.lemma__SHA256FinalHelper1.smt2   |  20.725s |2323.0MiB|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ReqWrite2StepPreservesInv.smt2 |  18.833s |189.0MiB|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.PageInNodeResp.smt2                       |  18.098s |172.0MiB|
|d_fvbkv-lib-DataStructures-LruImpl.i.dfy.Impl__LruImpl.LruImplQueue.Use.smt2               |  15.046s |170.0MiB|
|d_lvbkv-lib-DataStructures-LinearDList.i.dfy.Impl__DList.DList.InsertBefore.smt2           |   7.591s |117.0MiB|
|d_lvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__LMutableBtree.__default.InsertIndex.smt2 |   6.160s |100.0MiB|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.FlushPreservesLookups.smt2        |   3.881s |93.444MiB|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.BinarySearchQuery.smt2         |   3.423s |63.684MiB|
|d_komodo-verified-ptebits.i.dfyImpl___module.__default.lemma__l1ptesmatch.smt2             |   3.255s |278.0MiB|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint64Array.smt2 |   2.719s |63.856MiB|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.append.smt2  |   2.472s |59.536MiB|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallArray.smt2 |   2.172s |57.556MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|s_komodo-1509.4.smt2                                                                       |  80.299s |5430.0MiB|
|s_komodo-1504.4.smt2                                                                       |  80.257s |4117.0MiB|
|d_komodo-verified-verify.gen.dfyImpl___module.__default.va__lemma__svc__returning__verify__inner.smt2 |  36.793s |409.0MiB|
|d_komodo-verified-secprop-conf_ni.i.dfyImpl___module.__default.lemma__initL2PTable__loweq__pdb.smt2 |  34.982s |334.0MiB|
|d_lvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.Impl__PivotBetreeSpecRefinement.__default.SplitChildrenConsistent.smt2 |  32.003s |202.0MiB|
|d_lvbkv-lib-Buckets-BucketsLib.i.dfy.Impl__BucketsLib.__default.WFProperSplitBucketInList.smt2 |  26.214s |250.0MiB|
|d_komodo-verified-verify.gen.dfyImpl___module.__default.va__lemma__svc__returning__verify.smt2 |  24.329s |227.0MiB|
|d_fvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.SplitIndexAllKeys.smt2 |  23.575s |206.0MiB|
|d_komodo-verified-sha-sha256.i.dfyImpl___module.__default.lemma__SHA256FinalHelper1.smt2   |  20.725s |2323.0MiB|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ReqWrite2StepPreservesInv.smt2 |  18.833s |189.0MiB|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.PageInNodeResp.smt2                       |  18.098s |172.0MiB|
|d_fvbkv-lib-DataStructures-LruImpl.i.dfy.Impl__LruImpl.LruImplQueue.Use.smt2               |  15.046s |170.0MiB|
|d_lvbkv-lib-DataStructures-LinearDList.i.dfy.Impl__DList.DList.InsertBefore.smt2           |   7.591s |117.0MiB|
|d_lvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__LMutableBtree.__default.InsertIndex.smt2 |   6.160s |100.0MiB|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.FlushPreservesLookups.smt2        |   3.881s |93.444MiB|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.BinarySearchQuery.smt2         |   3.423s |63.684MiB|
|d_komodo-verified-ptebits.i.dfyImpl___module.__default.lemma__l1ptesmatch.smt2             |   3.255s |278.0MiB|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint64Array.smt2 |   2.719s |63.856MiB|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.append.smt2  |   2.472s |59.536MiB|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallArray.smt2 |   2.172s |57.556MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.FlushPreservesLookups.smt2         |93.444MiB|93.444MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ReqWrite2StepPreservesInv.smt2  |189.0MiB|189.0MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesProcessWrite.smt2  |96.912MiB|96.912MiB|0B| 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.PageInNodeResp.smt2                        |172.0MiB|172.0MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.append.smt2   |59.536MiB|59.536MiB|0B| 0.0%|
|d_fvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.set__bit__to__0__self__uint64.smt2  |37.296MiB|37.296MiB|0B| 0.0%|
|d_fvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.set__bit__to__1__self__uint64.smt2  |37.072MiB|37.072MiB|0B| 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.BinarySearchQuery.smt2          |63.684MiB|63.684MiB|0B| 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.UniqueRepr.smt2  |30.892MiB|30.892MiB|0B| 0.0%|
|d_fvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.SplitIndexAllKeys.smt2  |206.0MiB|206.0MiB|0B| 0.0%|
|d_fvbkv-lib-DataStructures-LruImpl.i.dfy.Impl__LruImpl.LruImplQueue.Use.smt2                |170.0MiB|170.0MiB|0B| 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SubIndex.smt2    |35.356MiB|35.356MiB|0B| 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SubReprLowerBound.smt2  |31.44MiB|31.44MiB|0B| 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallArray.smt2  |57.556MiB|57.556MiB|0B| 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint32Array.smt2  |38.908MiB|38.908MiB|0B| 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint64Array.smt2  |63.856MiB|63.856MiB|0B| 0.0%|
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__2toX.smt2                    |57.912MiB|57.912MiB|0B| 0.0%|
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__div__denominator.smt2        |24.124MiB|24.124MiB|0B| 0.0%|
|d_fvbkv-lib-Math-mod_auto_proofs.i.dfy.Impl__Math____mod__auto__proofs__i.__default.lemma__mod__induction__forall2.smt2  |22.8MiB|22.8MiB|0B| 0.0%|
|d_komodo-verified-ptebits.i.dfyImpl___module.__default.lemma__l1ptesmatch.smt2              |278.0MiB|278.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.FlushPreservesLookups.smt2         |93.444MiB|93.444MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ReqWrite2StepPreservesInv.smt2  |189.0MiB|189.0MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesProcessWrite.smt2  |96.912MiB|96.912MiB|0B| 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.PageInNodeResp.smt2                        |172.0MiB|172.0MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.append.smt2   |59.536MiB|59.536MiB|0B| 0.0%|
|d_fvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.set__bit__to__0__self__uint64.smt2  |37.296MiB|37.296MiB|0B| 0.0%|
|d_fvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.set__bit__to__1__self__uint64.smt2  |37.072MiB|37.072MiB|0B| 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.BinarySearchQuery.smt2          |63.684MiB|63.684MiB|0B| 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.UniqueRepr.smt2  |30.892MiB|30.892MiB|0B| 0.0%|
|d_fvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.SplitIndexAllKeys.smt2  |206.0MiB|206.0MiB|0B| 0.0%|
|d_fvbkv-lib-DataStructures-LruImpl.i.dfy.Impl__LruImpl.LruImplQueue.Use.smt2                |170.0MiB|170.0MiB|0B| 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SubIndex.smt2    |35.356MiB|35.356MiB|0B| 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SubReprLowerBound.smt2  |31.44MiB|31.44MiB|0B| 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallArray.smt2  |57.556MiB|57.556MiB|0B| 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint32Array.smt2  |38.908MiB|38.908MiB|0B| 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint64Array.smt2  |63.856MiB|63.856MiB|0B| 0.0%|
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__2toX.smt2                    |57.912MiB|57.912MiB|0B| 0.0%|
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__div__denominator.smt2        |24.124MiB|24.124MiB|0B| 0.0%|
|d_fvbkv-lib-Math-mod_auto_proofs.i.dfy.Impl__Math____mod__auto__proofs__i.__default.lemma__mod__induction__forall2.smt2  |22.8MiB|22.8MiB|0B| 0.0%|
|d_komodo-verified-ptebits.i.dfyImpl___module.__default.lemma__l1ptesmatch.smt2              |278.0MiB|278.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.FlushPreservesLookups.smt2         |93.444MiB|93.444MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ReqWrite2StepPreservesInv.smt2  |189.0MiB|189.0MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesProcessWrite.smt2  |96.912MiB|96.912MiB|0B| 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.PageInNodeResp.smt2                        |172.0MiB|172.0MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.append.smt2   |59.536MiB|59.536MiB|0B| 0.0%|
|d_fvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.set__bit__to__0__self__uint64.smt2  |37.296MiB|37.296MiB|0B| 0.0%|
|d_fvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.set__bit__to__1__self__uint64.smt2  |37.072MiB|37.072MiB|0B| 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.BinarySearchQuery.smt2          |63.684MiB|63.684MiB|0B| 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.UniqueRepr.smt2  |30.892MiB|30.892MiB|0B| 0.0%|
|d_fvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.SplitIndexAllKeys.smt2  |206.0MiB|206.0MiB|0B| 0.0%|
|d_fvbkv-lib-DataStructures-LruImpl.i.dfy.Impl__LruImpl.LruImplQueue.Use.smt2                |170.0MiB|170.0MiB|0B| 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SubIndex.smt2    |35.356MiB|35.356MiB|0B| 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SubReprLowerBound.smt2  |31.44MiB|31.44MiB|0B| 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallArray.smt2  |57.556MiB|57.556MiB|0B| 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint32Array.smt2  |38.908MiB|38.908MiB|0B| 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint64Array.smt2  |63.856MiB|63.856MiB|0B| 0.0%|
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__2toX.smt2                    |57.912MiB|57.912MiB|0B| 0.0%|
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__div__denominator.smt2        |24.124MiB|24.124MiB|0B| 0.0%|
|d_fvbkv-lib-Math-mod_auto_proofs.i.dfy.Impl__Math____mod__auto__proofs__i.__default.lemma__mod__induction__forall2.smt2  |22.8MiB|22.8MiB|0B| 0.0%|
|d_komodo-verified-ptebits.i.dfyImpl___module.__default.lemma__l1ptesmatch.smt2              |278.0MiB|278.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.FlushPreservesLookups.smt2         |93.444MiB|93.444MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ReqWrite2StepPreservesInv.smt2  |189.0MiB|189.0MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesProcessWrite.smt2  |96.912MiB|96.912MiB|0B| 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.PageInNodeResp.smt2                        |172.0MiB|172.0MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.append.smt2   |59.536MiB|59.536MiB|0B| 0.0%|
|d_fvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.set__bit__to__0__self__uint64.smt2  |37.296MiB|37.296MiB|0B| 0.0%|
|d_fvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.set__bit__to__1__self__uint64.smt2  |37.072MiB|37.072MiB|0B| 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.BinarySearchQuery.smt2          |63.684MiB|63.684MiB|0B| 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.UniqueRepr.smt2  |30.892MiB|30.892MiB|0B| 0.0%|
|d_fvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.SplitIndexAllKeys.smt2  |206.0MiB|206.0MiB|0B| 0.0%|
|d_fvbkv-lib-DataStructures-LruImpl.i.dfy.Impl__LruImpl.LruImplQueue.Use.smt2                |170.0MiB|170.0MiB|0B| 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SubIndex.smt2    |35.356MiB|35.356MiB|0B| 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SubReprLowerBound.smt2  |31.44MiB|31.44MiB|0B| 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallArray.smt2  |57.556MiB|57.556MiB|0B| 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint32Array.smt2  |38.908MiB|38.908MiB|0B| 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint64Array.smt2  |63.856MiB|63.856MiB|0B| 0.0%|
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__2toX.smt2                    |57.912MiB|57.912MiB|0B| 0.0%|
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__div__denominator.smt2        |24.124MiB|24.124MiB|0B| 0.0%|
|d_fvbkv-lib-Math-mod_auto_proofs.i.dfy.Impl__Math____mod__auto__proofs__i.__default.lemma__mod__induction__forall2.smt2  |22.8MiB|22.8MiB|0B| 0.0%|
|d_komodo-verified-ptebits.i.dfyImpl___module.__default.lemma__l1ptesmatch.smt2              |278.0MiB|278.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|s_komodo-1509.4.smt2                                                                       |  80.299s |5430.0MiB|
|s_komodo-1504.4.smt2                                                                       |  80.257s |4117.0MiB|
|d_komodo-verified-sha-sha256.i.dfyImpl___module.__default.lemma__SHA256FinalHelper1.smt2   |  20.725s |2323.0MiB|
|d_komodo-verified-verify.gen.dfyImpl___module.__default.va__lemma__svc__returning__verify__inner.smt2 |  36.793s |409.0MiB|
|d_komodo-verified-secprop-conf_ni.i.dfyImpl___module.__default.lemma__initL2PTable__loweq__pdb.smt2 |  34.982s |334.0MiB|
|d_komodo-verified-ptebits.i.dfyImpl___module.__default.lemma__l1ptesmatch.smt2             |   3.255s |278.0MiB|
|d_lvbkv-lib-Buckets-BucketsLib.i.dfy.Impl__BucketsLib.__default.WFProperSplitBucketInList.smt2 |  26.214s |250.0MiB|
|d_komodo-verified-verify.gen.dfyImpl___module.__default.va__lemma__svc__returning__verify.smt2 |  24.329s |227.0MiB|
|d_fvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.SplitIndexAllKeys.smt2 |  23.575s |206.0MiB|
|d_lvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.Impl__PivotBetreeSpecRefinement.__default.SplitChildrenConsistent.smt2 |  32.003s |202.0MiB|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ReqWrite2StepPreservesInv.smt2 |  18.833s |189.0MiB|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.PageInNodeResp.smt2                       |  18.098s |172.0MiB|
|d_fvbkv-lib-DataStructures-LruImpl.i.dfy.Impl__LruImpl.LruImplQueue.Use.smt2               |  15.046s |170.0MiB|
|d_lvbkv-lib-DataStructures-LinearDList.i.dfy.Impl__DList.DList.InsertBefore.smt2           |   7.591s |117.0MiB|
|d_lvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__LMutableBtree.__default.InsertIndex.smt2 |   6.160s |100.0MiB|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesProcessWrite.smt2 |   1.750s |96.912MiB|
|d_lvbkv-PivotBetree-PivotBetreeSpecWFNodes.i.dfy.Impl__PivotBetreeSpecWFNodes.__default.ValidSplitWritesInvNodes.smt2 |   2.138s |96.304MiB|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.FlushPreservesLookups.smt2        |   3.881s |93.444MiB|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint64Array.smt2 |   2.719s |63.856MiB|
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.DynamicPkv.Append.smt2                 |   2.022s |63.844MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|s_komodo-1509.4.smt2                                                                       |  80.299s |5430.0MiB|
|s_komodo-1504.4.smt2                                                                       |  80.257s |4117.0MiB|
|d_komodo-verified-sha-sha256.i.dfyImpl___module.__default.lemma__SHA256FinalHelper1.smt2   |  20.725s |2323.0MiB|
|d_komodo-verified-verify.gen.dfyImpl___module.__default.va__lemma__svc__returning__verify__inner.smt2 |  36.793s |409.0MiB|
|d_komodo-verified-secprop-conf_ni.i.dfyImpl___module.__default.lemma__initL2PTable__loweq__pdb.smt2 |  34.982s |334.0MiB|
|d_komodo-verified-ptebits.i.dfyImpl___module.__default.lemma__l1ptesmatch.smt2             |   3.255s |278.0MiB|
|d_lvbkv-lib-Buckets-BucketsLib.i.dfy.Impl__BucketsLib.__default.WFProperSplitBucketInList.smt2 |  26.214s |250.0MiB|
|d_komodo-verified-verify.gen.dfyImpl___module.__default.va__lemma__svc__returning__verify.smt2 |  24.329s |227.0MiB|
|d_fvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.SplitIndexAllKeys.smt2 |  23.575s |206.0MiB|
|d_lvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.Impl__PivotBetreeSpecRefinement.__default.SplitChildrenConsistent.smt2 |  32.003s |202.0MiB|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ReqWrite2StepPreservesInv.smt2 |  18.833s |189.0MiB|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.PageInNodeResp.smt2                       |  18.098s |172.0MiB|
|d_fvbkv-lib-DataStructures-LruImpl.i.dfy.Impl__LruImpl.LruImplQueue.Use.smt2               |  15.046s |170.0MiB|
|d_lvbkv-lib-DataStructures-LinearDList.i.dfy.Impl__DList.DList.InsertBefore.smt2           |   7.591s |117.0MiB|
|d_lvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__LMutableBtree.__default.InsertIndex.smt2 |   6.160s |100.0MiB|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesProcessWrite.smt2 |   1.750s |96.912MiB|
|d_lvbkv-PivotBetree-PivotBetreeSpecWFNodes.i.dfy.Impl__PivotBetreeSpecWFNodes.__default.ValidSplitWritesInvNodes.smt2 |   2.138s |96.304MiB|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.FlushPreservesLookups.smt2        |   3.881s |93.444MiB|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint64Array.smt2 |   2.719s |63.856MiB|
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.DynamicPkv.Append.smt2                 |   2.022s |63.844MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.FlushPreservesLookups.smt2         |   3.881s  |   3.881s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ReqWrite2StepPreservesInv.smt2  |  18.833s  |  18.833s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesProcessWrite.smt2  |   1.750s  |   1.750s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.PageInNodeResp.smt2                        |  18.098s  |  18.098s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.append.smt2   |   2.472s  |   2.472s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.set__bit__to__0__self__uint64.smt2  |   0.191s  |   0.191s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.set__bit__to__1__self__uint64.smt2  |   0.193s  |   0.193s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.BinarySearchQuery.smt2          |   3.423s  |   3.423s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.UniqueRepr.smt2  |   0.366s  |   0.366s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.SplitIndexAllKeys.smt2  |  23.575s  |  23.575s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-LruImpl.i.dfy.Impl__LruImpl.LruImplQueue.Use.smt2                |  15.046s  |  15.046s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SubIndex.smt2    |   0.628s  |   0.628s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SubReprLowerBound.smt2  |   0.463s  |   0.463s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallArray.smt2  |   2.172s  |   2.172s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint32Array.smt2  |   0.681s  |   0.681s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint64Array.smt2  |   2.719s  |   2.719s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__2toX.smt2                    |   0.708s  |   0.708s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__div__denominator.smt2        |   0.359s  |   0.359s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Math-mod_auto_proofs.i.dfy.Impl__Math____mod__auto__proofs__i.__default.lemma__mod__induction__forall2.smt2  |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|d_komodo-verified-ptebits.i.dfyImpl___module.__default.lemma__l1ptesmatch.smt2              |   3.255s  |   3.255s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-conf_ni.i.dfyImpl___module.__default.lemma__initL2PTable__loweq__pdb.smt2  |  34.982s  |  34.982s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-sha256.i.dfyImpl___module.__default.lemma__SHA256FinalHelper1.smt2    |  20.725s  |  20.725s  |   0.000s  | 0.0%|
|d_komodo-verified-verify.gen.dfyImpl___module.__default.va__lemma__svc__returning__verify.smt2  |  24.329s  |  24.329s  |   0.000s  | 0.0%|
|d_komodo-verified-verify.gen.dfyImpl___module.__default.va__lemma__svc__returning__verify__inner.smt2  |  36.793s  |  36.793s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-JournalistImpl.i.dfy.Impl__JournalistImpl.Journalist.append.smt2               |   1.531s  |   1.531s  |   0.000s  | 0.0%|
|d_lvbkv-MapSpec-TSJMap_Refines_ThreeStateVersionedMap.i.dfy.Impl__TSJMap__Refines__ThreeStateVersionedMap.__default.RefinesReplay.smt2  |   0.537s  |   0.537s  |   0.000s  | 0.0%|
|d_lvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.Impl__PivotBetreeSpecRefinement.__default.SplitChildrenConsistent.smt2  |  32.003s  |  32.003s  |   0.000s  | 0.0%|
|d_lvbkv-PivotBetree-PivotBetreeSpecWFNodes.i.dfy.Impl__PivotBetreeSpecWFNodes.__default.ValidSplitWritesInvNodes.smt2  |   2.138s  |   2.138s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-total_order_impl.i.dfy.Impl__Total__Order__Impl.__default.ArrayLargestLtePlus1Linear.smt2  |   0.232s  |   0.232s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-BucketsLib.i.dfy.Impl__BucketsLib.__default.WFProperSplitBucketInList.smt2  |  26.214s  |  26.214s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.DynamicPkv.Append.smt2                  |   2.022s  |   2.022s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Checksums-BitLemmas.i.dfy.Impl__BitLemmas.__default.eq__from__unpack__LittleEndian__Uint32__eq.smt2  |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|d_lvbkv-lib-DataStructures-LinearDList.i.dfy.Impl__DList.DList.InsertBefore.smt2            |   7.591s  |   7.591s  |   0.000s  | 0.0%|
|d_lvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__LMutableBtree.__default.InsertIndex.smt2  |   6.160s  |   6.160s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Lang-LinearSequence.i.dfy.Impl__LinearSequence__i.__default.AllocAndMoveLseq.smt2  |   0.269s  |   0.269s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallArray.smt2  |   0.729s  |   0.729s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallByteArray.smt2  |   0.505s  |   0.505s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallByteArrayInterior.smt2  |   0.904s  |   0.904s  |   0.000s  | 0.0%|
</details>
