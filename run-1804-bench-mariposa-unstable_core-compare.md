Comparing data and data


# SUMMARY
- LHS tests = 40
- RHS tests = 40
- LHS success = 40  (100.0%)
- RHS success = 40  (100.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: bench-mariposa-unstable_core
Runner: rise-runner-2
Z3 repo: CanCebeci/z3
Z3 commit: 18cb7654b9931442b52ef68bdb2c6643b1b01392
Z3 branch: master-clean
Z3 options: "-T:20"
Z3 inputs: inputs/mariposa/unstable_core
Z3 commit message: Update generation number of already-internalized enodes

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: bench-mariposa-unstable_core
Runner: rise-runner-2
Z3 repo: CanCebeci/z3
Z3 commit: 18cb7654b9931442b52ef68bdb2c6643b1b01392
Z3 branch: master-clean
Z3 options: "-T:20"
Z3 inputs: inputs/mariposa/unstable_core
Z3 commit message: Update generation number of already-internalized enodes

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.FlushPreservesLookups.smt2         |   3.406s  |   3.406s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ReqWrite2StepPreservesInv.smt2  |  16.274s  |  16.274s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesProcessWrite.smt2  |  18.136s  |  18.136s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.PageInNodeResp.smt2                        |  14.701s  |  14.701s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.append.smt2   |   1.552s  |   1.552s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.set__bit__to__0__self__uint64.smt2  |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.set__bit__to__1__self__uint64.smt2  |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-KMBPKVOps.i.dfy.Impl__KMBPKVOps.__default.IndexFillDpkv.smt2            |  20.050s  |  20.050s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.BinarySearchQuery.smt2          |   3.915s  |   3.915s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.UniqueRepr.smt2  |   0.306s  |   0.306s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.SplitIndexAllKeys.smt2  |  20.055s  |  20.055s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-LruImpl.i.dfy.Impl__LruImpl.LruImplQueue.Use.smt2                |  13.181s  |  13.181s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SubIndex.smt2    |  20.049s  |  20.049s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SubReprLowerBound.smt2  |   0.341s  |   0.341s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallArray.smt2  |   2.286s  |   2.286s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint32Array.smt2  |   0.879s  |   0.879s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint64Array.smt2  |   2.056s  |   2.056s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__2toX.smt2                    |   0.554s  |   0.554s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__div__denominator.smt2        |   0.304s  |   0.304s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Math-mod_auto_proofs.i.dfy.Impl__Math____mod__auto__proofs__i.__default.lemma__mod__induction__forall2.smt2  |   0.077s  |   0.077s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.FlushPreservesLookups.smt2         |   3.406s  |   3.406s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ReqWrite2StepPreservesInv.smt2  |  16.274s  |  16.274s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesProcessWrite.smt2  |  18.136s  |  18.136s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.PageInNodeResp.smt2                        |  14.701s  |  14.701s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.append.smt2   |   1.552s  |   1.552s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.set__bit__to__0__self__uint64.smt2  |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.set__bit__to__1__self__uint64.smt2  |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-KMBPKVOps.i.dfy.Impl__KMBPKVOps.__default.IndexFillDpkv.smt2            |  20.050s  |  20.050s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.BinarySearchQuery.smt2          |   3.915s  |   3.915s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.UniqueRepr.smt2  |   0.306s  |   0.306s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.SplitIndexAllKeys.smt2  |  20.055s  |  20.055s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-LruImpl.i.dfy.Impl__LruImpl.LruImplQueue.Use.smt2                |  13.181s  |  13.181s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SubIndex.smt2    |  20.049s  |  20.049s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SubReprLowerBound.smt2  |   0.341s  |   0.341s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallArray.smt2  |   2.286s  |   2.286s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint32Array.smt2  |   0.879s  |   0.879s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint64Array.smt2  |   2.056s  |   2.056s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__2toX.smt2                    |   0.554s  |   0.554s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__div__denominator.smt2        |   0.304s  |   0.304s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Math-mod_auto_proofs.i.dfy.Impl__Math____mod__auto__proofs__i.__default.lemma__mod__induction__forall2.smt2  |   0.077s  |   0.077s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.FlushPreservesLookups.smt2         |   3.406s  |   3.406s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ReqWrite2StepPreservesInv.smt2  |  16.274s  |  16.274s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesProcessWrite.smt2  |  18.136s  |  18.136s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.PageInNodeResp.smt2                        |  14.701s  |  14.701s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.append.smt2   |   1.552s  |   1.552s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.set__bit__to__0__self__uint64.smt2  |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.set__bit__to__1__self__uint64.smt2  |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-KMBPKVOps.i.dfy.Impl__KMBPKVOps.__default.IndexFillDpkv.smt2            |  20.050s  |  20.050s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.BinarySearchQuery.smt2          |   3.915s  |   3.915s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.UniqueRepr.smt2  |   0.306s  |   0.306s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.SplitIndexAllKeys.smt2  |  20.055s  |  20.055s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-LruImpl.i.dfy.Impl__LruImpl.LruImplQueue.Use.smt2                |  13.181s  |  13.181s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SubIndex.smt2    |  20.049s  |  20.049s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SubReprLowerBound.smt2  |   0.341s  |   0.341s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallArray.smt2  |   2.286s  |   2.286s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint32Array.smt2  |   0.879s  |   0.879s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint64Array.smt2  |   2.056s  |   2.056s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__2toX.smt2                    |   0.554s  |   0.554s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__div__denominator.smt2        |   0.304s  |   0.304s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Math-mod_auto_proofs.i.dfy.Impl__Math____mod__auto__proofs__i.__default.lemma__mod__induction__forall2.smt2  |   0.077s  |   0.077s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.FlushPreservesLookups.smt2         |   3.406s  |   3.406s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ReqWrite2StepPreservesInv.smt2  |  16.274s  |  16.274s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesProcessWrite.smt2  |  18.136s  |  18.136s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.PageInNodeResp.smt2                        |  14.701s  |  14.701s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.append.smt2   |   1.552s  |   1.552s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.set__bit__to__0__self__uint64.smt2  |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.set__bit__to__1__self__uint64.smt2  |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-KMBPKVOps.i.dfy.Impl__KMBPKVOps.__default.IndexFillDpkv.smt2            |  20.050s  |  20.050s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.BinarySearchQuery.smt2          |   3.915s  |   3.915s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.UniqueRepr.smt2  |   0.306s  |   0.306s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.SplitIndexAllKeys.smt2  |  20.055s  |  20.055s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-LruImpl.i.dfy.Impl__LruImpl.LruImplQueue.Use.smt2                |  13.181s  |  13.181s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SubIndex.smt2    |  20.049s  |  20.049s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SubReprLowerBound.smt2  |   0.341s  |   0.341s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallArray.smt2  |   2.286s  |   2.286s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint32Array.smt2  |   0.879s  |   0.879s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint64Array.smt2  |   2.056s  |   2.056s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__2toX.smt2                    |   0.554s  |   0.554s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__div__denominator.smt2        |   0.304s  |   0.304s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Math-mod_auto_proofs.i.dfy.Impl__Math____mod__auto__proofs__i.__default.lemma__mod__induction__forall2.smt2  |   0.077s  |   0.077s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|s_komodo-1504.4.smt2                                                                       |  20.600s |6315.0MiB|
|s_komodo-1509.4.smt2                                                                       |  20.554s |5541.0MiB|
|d_komodo-verified-sha-sha256.i.dfyImpl___module.__default.lemma__SHA256FinalHelper1.smt2   |  20.232s |2195.0MiB|
|d_komodo-verified-verify.gen.dfyImpl___module.__default.va__lemma__svc__returning__verify__inner.smt2 |  20.074s |356.0MiB|
|d_lvbkv-lib-Buckets-BucketsLib.i.dfy.Impl__BucketsLib.__default.WFProperSplitBucketInList.smt2 |  20.067s |305.0MiB|
|d_komodo-verified-verify.gen.dfyImpl___module.__default.va__lemma__svc__returning__verify.smt2 |  20.058s |221.0MiB|
|d_fvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.SplitIndexAllKeys.smt2 |  20.055s |207.0MiB|
|d_komodo-verified-secprop-conf_ni.i.dfyImpl___module.__default.lemma__initL2PTable__loweq__pdb.smt2 |  20.054s |193.0MiB|
|d_fvbkv-lib-Buckets-KMBPKVOps.i.dfy.Impl__KMBPKVOps.__default.IndexFillDpkv.smt2           |  20.050s |189.0MiB|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SubIndex.smt2   |  20.049s |122.0MiB|
|d_lvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.Impl__PivotBetreeSpecRefinement.__default.SplitChildrenConsistent.smt2 |  20.042s |131.0MiB|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesProcessWrite.smt2 |  18.136s |179.0MiB|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ReqWrite2StepPreservesInv.smt2 |  16.274s |189.0MiB|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.PageInNodeResp.smt2                       |  14.701s |172.0MiB|
|d_fvbkv-lib-DataStructures-LruImpl.i.dfy.Impl__LruImpl.LruImplQueue.Use.smt2               |  13.181s |107.0MiB|
|d_lvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__LMutableBtree.__default.InsertIndex.smt2 |   5.750s |101.0MiB|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.BinarySearchQuery.smt2         |   3.915s |135.0MiB|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.FlushPreservesLookups.smt2        |   3.406s |94.284MiB|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallArray.smt2 |   2.286s |61.204MiB|
|d_lvbkv-PivotBetree-PivotBetreeSpecWFNodes.i.dfy.Impl__PivotBetreeSpecWFNodes.__default.ValidSplitWritesInvNodes.smt2 |   2.112s |97.472MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|s_komodo-1504.4.smt2                                                                       |  20.600s |6315.0MiB|
|s_komodo-1509.4.smt2                                                                       |  20.554s |5541.0MiB|
|d_komodo-verified-sha-sha256.i.dfyImpl___module.__default.lemma__SHA256FinalHelper1.smt2   |  20.232s |2195.0MiB|
|d_komodo-verified-verify.gen.dfyImpl___module.__default.va__lemma__svc__returning__verify__inner.smt2 |  20.074s |356.0MiB|
|d_lvbkv-lib-Buckets-BucketsLib.i.dfy.Impl__BucketsLib.__default.WFProperSplitBucketInList.smt2 |  20.067s |305.0MiB|
|d_komodo-verified-verify.gen.dfyImpl___module.__default.va__lemma__svc__returning__verify.smt2 |  20.058s |221.0MiB|
|d_fvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.SplitIndexAllKeys.smt2 |  20.055s |207.0MiB|
|d_komodo-verified-secprop-conf_ni.i.dfyImpl___module.__default.lemma__initL2PTable__loweq__pdb.smt2 |  20.054s |193.0MiB|
|d_fvbkv-lib-Buckets-KMBPKVOps.i.dfy.Impl__KMBPKVOps.__default.IndexFillDpkv.smt2           |  20.050s |189.0MiB|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SubIndex.smt2   |  20.049s |122.0MiB|
|d_lvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.Impl__PivotBetreeSpecRefinement.__default.SplitChildrenConsistent.smt2 |  20.042s |131.0MiB|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesProcessWrite.smt2 |  18.136s |179.0MiB|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ReqWrite2StepPreservesInv.smt2 |  16.274s |189.0MiB|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.PageInNodeResp.smt2                       |  14.701s |172.0MiB|
|d_fvbkv-lib-DataStructures-LruImpl.i.dfy.Impl__LruImpl.LruImplQueue.Use.smt2               |  13.181s |107.0MiB|
|d_lvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__LMutableBtree.__default.InsertIndex.smt2 |   5.750s |101.0MiB|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.BinarySearchQuery.smt2         |   3.915s |135.0MiB|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.FlushPreservesLookups.smt2        |   3.406s |94.284MiB|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallArray.smt2 |   2.286s |61.204MiB|
|d_lvbkv-PivotBetree-PivotBetreeSpecWFNodes.i.dfy.Impl__PivotBetreeSpecWFNodes.__default.ValidSplitWritesInvNodes.smt2 |   2.112s |97.472MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.FlushPreservesLookups.smt2         |94.284MiB|94.284MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ReqWrite2StepPreservesInv.smt2  |189.0MiB|189.0MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesProcessWrite.smt2  |179.0MiB|179.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.PageInNodeResp.smt2                        |172.0MiB|172.0MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.append.smt2   |59.876MiB|59.876MiB|0B| 0.0%|
|d_fvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.set__bit__to__0__self__uint64.smt2  |37.88MiB|37.88MiB|0B| 0.0%|
|d_fvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.set__bit__to__1__self__uint64.smt2  |38.092MiB|38.092MiB|0B| 0.0%|
|d_fvbkv-lib-Buckets-KMBPKVOps.i.dfy.Impl__KMBPKVOps.__default.IndexFillDpkv.smt2            |189.0MiB|189.0MiB|0B| 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.BinarySearchQuery.smt2          |135.0MiB|135.0MiB|0B| 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.UniqueRepr.smt2  |31.564MiB|31.564MiB|0B| 0.0%|
|d_fvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.SplitIndexAllKeys.smt2  |207.0MiB|207.0MiB|0B| 0.0%|
|d_fvbkv-lib-DataStructures-LruImpl.i.dfy.Impl__LruImpl.LruImplQueue.Use.smt2                |107.0MiB|107.0MiB|0B| 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SubIndex.smt2    |122.0MiB|122.0MiB|0B| 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SubReprLowerBound.smt2  |32.112MiB|32.112MiB|0B| 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallArray.smt2  |61.204MiB|61.204MiB|0B| 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint32Array.smt2  |43.356MiB|43.356MiB|0B| 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint64Array.smt2  |68.296MiB|68.296MiB|0B| 0.0%|
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__2toX.smt2                    |58.608MiB|58.608MiB|0B| 0.0%|
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__div__denominator.smt2        |24.772MiB|24.772MiB|0B| 0.0%|
|d_fvbkv-lib-Math-mod_auto_proofs.i.dfy.Impl__Math____mod__auto__proofs__i.__default.lemma__mod__induction__forall2.smt2  |23.44MiB|23.44MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.FlushPreservesLookups.smt2         |94.284MiB|94.284MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ReqWrite2StepPreservesInv.smt2  |189.0MiB|189.0MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesProcessWrite.smt2  |179.0MiB|179.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.PageInNodeResp.smt2                        |172.0MiB|172.0MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.append.smt2   |59.876MiB|59.876MiB|0B| 0.0%|
|d_fvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.set__bit__to__0__self__uint64.smt2  |37.88MiB|37.88MiB|0B| 0.0%|
|d_fvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.set__bit__to__1__self__uint64.smt2  |38.092MiB|38.092MiB|0B| 0.0%|
|d_fvbkv-lib-Buckets-KMBPKVOps.i.dfy.Impl__KMBPKVOps.__default.IndexFillDpkv.smt2            |189.0MiB|189.0MiB|0B| 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.BinarySearchQuery.smt2          |135.0MiB|135.0MiB|0B| 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.UniqueRepr.smt2  |31.564MiB|31.564MiB|0B| 0.0%|
|d_fvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.SplitIndexAllKeys.smt2  |207.0MiB|207.0MiB|0B| 0.0%|
|d_fvbkv-lib-DataStructures-LruImpl.i.dfy.Impl__LruImpl.LruImplQueue.Use.smt2                |107.0MiB|107.0MiB|0B| 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SubIndex.smt2    |122.0MiB|122.0MiB|0B| 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SubReprLowerBound.smt2  |32.112MiB|32.112MiB|0B| 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallArray.smt2  |61.204MiB|61.204MiB|0B| 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint32Array.smt2  |43.356MiB|43.356MiB|0B| 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint64Array.smt2  |68.296MiB|68.296MiB|0B| 0.0%|
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__2toX.smt2                    |58.608MiB|58.608MiB|0B| 0.0%|
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__div__denominator.smt2        |24.772MiB|24.772MiB|0B| 0.0%|
|d_fvbkv-lib-Math-mod_auto_proofs.i.dfy.Impl__Math____mod__auto__proofs__i.__default.lemma__mod__induction__forall2.smt2  |23.44MiB|23.44MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.FlushPreservesLookups.smt2         |94.284MiB|94.284MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ReqWrite2StepPreservesInv.smt2  |189.0MiB|189.0MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesProcessWrite.smt2  |179.0MiB|179.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.PageInNodeResp.smt2                        |172.0MiB|172.0MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.append.smt2   |59.876MiB|59.876MiB|0B| 0.0%|
|d_fvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.set__bit__to__0__self__uint64.smt2  |37.88MiB|37.88MiB|0B| 0.0%|
|d_fvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.set__bit__to__1__self__uint64.smt2  |38.092MiB|38.092MiB|0B| 0.0%|
|d_fvbkv-lib-Buckets-KMBPKVOps.i.dfy.Impl__KMBPKVOps.__default.IndexFillDpkv.smt2            |189.0MiB|189.0MiB|0B| 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.BinarySearchQuery.smt2          |135.0MiB|135.0MiB|0B| 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.UniqueRepr.smt2  |31.564MiB|31.564MiB|0B| 0.0%|
|d_fvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.SplitIndexAllKeys.smt2  |207.0MiB|207.0MiB|0B| 0.0%|
|d_fvbkv-lib-DataStructures-LruImpl.i.dfy.Impl__LruImpl.LruImplQueue.Use.smt2                |107.0MiB|107.0MiB|0B| 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SubIndex.smt2    |122.0MiB|122.0MiB|0B| 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SubReprLowerBound.smt2  |32.112MiB|32.112MiB|0B| 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallArray.smt2  |61.204MiB|61.204MiB|0B| 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint32Array.smt2  |43.356MiB|43.356MiB|0B| 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint64Array.smt2  |68.296MiB|68.296MiB|0B| 0.0%|
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__2toX.smt2                    |58.608MiB|58.608MiB|0B| 0.0%|
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__div__denominator.smt2        |24.772MiB|24.772MiB|0B| 0.0%|
|d_fvbkv-lib-Math-mod_auto_proofs.i.dfy.Impl__Math____mod__auto__proofs__i.__default.lemma__mod__induction__forall2.smt2  |23.44MiB|23.44MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.FlushPreservesLookups.smt2         |94.284MiB|94.284MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ReqWrite2StepPreservesInv.smt2  |189.0MiB|189.0MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesProcessWrite.smt2  |179.0MiB|179.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.PageInNodeResp.smt2                        |172.0MiB|172.0MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.append.smt2   |59.876MiB|59.876MiB|0B| 0.0%|
|d_fvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.set__bit__to__0__self__uint64.smt2  |37.88MiB|37.88MiB|0B| 0.0%|
|d_fvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.set__bit__to__1__self__uint64.smt2  |38.092MiB|38.092MiB|0B| 0.0%|
|d_fvbkv-lib-Buckets-KMBPKVOps.i.dfy.Impl__KMBPKVOps.__default.IndexFillDpkv.smt2            |189.0MiB|189.0MiB|0B| 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.BinarySearchQuery.smt2          |135.0MiB|135.0MiB|0B| 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.UniqueRepr.smt2  |31.564MiB|31.564MiB|0B| 0.0%|
|d_fvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.SplitIndexAllKeys.smt2  |207.0MiB|207.0MiB|0B| 0.0%|
|d_fvbkv-lib-DataStructures-LruImpl.i.dfy.Impl__LruImpl.LruImplQueue.Use.smt2                |107.0MiB|107.0MiB|0B| 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SubIndex.smt2    |122.0MiB|122.0MiB|0B| 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SubReprLowerBound.smt2  |32.112MiB|32.112MiB|0B| 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallArray.smt2  |61.204MiB|61.204MiB|0B| 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint32Array.smt2  |43.356MiB|43.356MiB|0B| 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint64Array.smt2  |68.296MiB|68.296MiB|0B| 0.0%|
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__2toX.smt2                    |58.608MiB|58.608MiB|0B| 0.0%|
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__div__denominator.smt2        |24.772MiB|24.772MiB|0B| 0.0%|
|d_fvbkv-lib-Math-mod_auto_proofs.i.dfy.Impl__Math____mod__auto__proofs__i.__default.lemma__mod__induction__forall2.smt2  |23.44MiB|23.44MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|s_komodo-1504.4.smt2                                                                       |  20.600s |6315.0MiB|
|s_komodo-1509.4.smt2                                                                       |  20.554s |5541.0MiB|
|d_komodo-verified-sha-sha256.i.dfyImpl___module.__default.lemma__SHA256FinalHelper1.smt2   |  20.232s |2195.0MiB|
|d_komodo-verified-verify.gen.dfyImpl___module.__default.va__lemma__svc__returning__verify__inner.smt2 |  20.074s |356.0MiB|
|d_lvbkv-lib-Buckets-BucketsLib.i.dfy.Impl__BucketsLib.__default.WFProperSplitBucketInList.smt2 |  20.067s |305.0MiB|
|d_komodo-verified-verify.gen.dfyImpl___module.__default.va__lemma__svc__returning__verify.smt2 |  20.058s |221.0MiB|
|d_fvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.SplitIndexAllKeys.smt2 |  20.055s |207.0MiB|
|d_komodo-verified-secprop-conf_ni.i.dfyImpl___module.__default.lemma__initL2PTable__loweq__pdb.smt2 |  20.054s |193.0MiB|
|d_fvbkv-lib-Buckets-KMBPKVOps.i.dfy.Impl__KMBPKVOps.__default.IndexFillDpkv.smt2           |  20.050s |189.0MiB|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ReqWrite2StepPreservesInv.smt2 |  16.274s |189.0MiB|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesProcessWrite.smt2 |  18.136s |179.0MiB|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.PageInNodeResp.smt2                       |  14.701s |172.0MiB|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.BinarySearchQuery.smt2         |   3.915s |135.0MiB|
|d_lvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.Impl__PivotBetreeSpecRefinement.__default.SplitChildrenConsistent.smt2 |  20.042s |131.0MiB|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SubIndex.smt2   |  20.049s |122.0MiB|
|d_fvbkv-lib-DataStructures-LruImpl.i.dfy.Impl__LruImpl.LruImplQueue.Use.smt2               |  13.181s |107.0MiB|
|d_lvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__LMutableBtree.__default.InsertIndex.smt2 |   5.750s |101.0MiB|
|d_lvbkv-PivotBetree-PivotBetreeSpecWFNodes.i.dfy.Impl__PivotBetreeSpecWFNodes.__default.ValidSplitWritesInvNodes.smt2 |   2.112s |97.472MiB|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.FlushPreservesLookups.smt2        |   3.406s |94.284MiB|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint64Array.smt2 |   2.056s |68.296MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|s_komodo-1504.4.smt2                                                                       |  20.600s |6315.0MiB|
|s_komodo-1509.4.smt2                                                                       |  20.554s |5541.0MiB|
|d_komodo-verified-sha-sha256.i.dfyImpl___module.__default.lemma__SHA256FinalHelper1.smt2   |  20.232s |2195.0MiB|
|d_komodo-verified-verify.gen.dfyImpl___module.__default.va__lemma__svc__returning__verify__inner.smt2 |  20.074s |356.0MiB|
|d_lvbkv-lib-Buckets-BucketsLib.i.dfy.Impl__BucketsLib.__default.WFProperSplitBucketInList.smt2 |  20.067s |305.0MiB|
|d_komodo-verified-verify.gen.dfyImpl___module.__default.va__lemma__svc__returning__verify.smt2 |  20.058s |221.0MiB|
|d_fvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.SplitIndexAllKeys.smt2 |  20.055s |207.0MiB|
|d_komodo-verified-secprop-conf_ni.i.dfyImpl___module.__default.lemma__initL2PTable__loweq__pdb.smt2 |  20.054s |193.0MiB|
|d_fvbkv-lib-Buckets-KMBPKVOps.i.dfy.Impl__KMBPKVOps.__default.IndexFillDpkv.smt2           |  20.050s |189.0MiB|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ReqWrite2StepPreservesInv.smt2 |  16.274s |189.0MiB|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesProcessWrite.smt2 |  18.136s |179.0MiB|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.PageInNodeResp.smt2                       |  14.701s |172.0MiB|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.BinarySearchQuery.smt2         |   3.915s |135.0MiB|
|d_lvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.Impl__PivotBetreeSpecRefinement.__default.SplitChildrenConsistent.smt2 |  20.042s |131.0MiB|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SubIndex.smt2   |  20.049s |122.0MiB|
|d_fvbkv-lib-DataStructures-LruImpl.i.dfy.Impl__LruImpl.LruImplQueue.Use.smt2               |  13.181s |107.0MiB|
|d_lvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__LMutableBtree.__default.InsertIndex.smt2 |   5.750s |101.0MiB|
|d_lvbkv-PivotBetree-PivotBetreeSpecWFNodes.i.dfy.Impl__PivotBetreeSpecWFNodes.__default.ValidSplitWritesInvNodes.smt2 |   2.112s |97.472MiB|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.FlushPreservesLookups.smt2        |   3.406s |94.284MiB|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint64Array.smt2 |   2.056s |68.296MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.FlushPreservesLookups.smt2         |   3.406s  |   3.406s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ReqWrite2StepPreservesInv.smt2  |  16.274s  |  16.274s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesProcessWrite.smt2  |  18.136s  |  18.136s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.PageInNodeResp.smt2                        |  14.701s  |  14.701s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.append.smt2   |   1.552s  |   1.552s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.set__bit__to__0__self__uint64.smt2  |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.set__bit__to__1__self__uint64.smt2  |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-KMBPKVOps.i.dfy.Impl__KMBPKVOps.__default.IndexFillDpkv.smt2            |  20.050s  |  20.050s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.BinarySearchQuery.smt2          |   3.915s  |   3.915s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.UniqueRepr.smt2  |   0.306s  |   0.306s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.SplitIndexAllKeys.smt2  |  20.055s  |  20.055s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-LruImpl.i.dfy.Impl__LruImpl.LruImplQueue.Use.smt2                |  13.181s  |  13.181s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SubIndex.smt2    |  20.049s  |  20.049s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SubReprLowerBound.smt2  |   0.341s  |   0.341s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallArray.smt2  |   2.286s  |   2.286s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint32Array.smt2  |   0.879s  |   0.879s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint64Array.smt2  |   2.056s  |   2.056s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__2toX.smt2                    |   0.554s  |   0.554s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__div__denominator.smt2        |   0.304s  |   0.304s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Math-mod_auto_proofs.i.dfy.Impl__Math____mod__auto__proofs__i.__default.lemma__mod__induction__forall2.smt2  |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-conf_ni.i.dfyImpl___module.__default.lemma__initL2PTable__loweq__pdb.smt2  |  20.054s  |  20.054s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-sha256.i.dfyImpl___module.__default.lemma__SHA256FinalHelper1.smt2    |  20.232s  |  20.232s  |   0.000s  | 0.0%|
|d_komodo-verified-verify.gen.dfyImpl___module.__default.va__lemma__svc__returning__verify.smt2  |  20.058s  |  20.058s  |   0.000s  | 0.0%|
|d_komodo-verified-verify.gen.dfyImpl___module.__default.va__lemma__svc__returning__verify__inner.smt2  |  20.074s  |  20.074s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-JournalistImpl.i.dfy.Impl__JournalistImpl.Journalist.append.smt2               |   2.073s  |   2.073s  |   0.000s  | 0.0%|
|d_lvbkv-MapSpec-TSJMap_Refines_ThreeStateVersionedMap.i.dfy.Impl__TSJMap__Refines__ThreeStateVersionedMap.__default.RefinesReplay.smt2  |   0.449s  |   0.449s  |   0.000s  | 0.0%|
|d_lvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.Impl__PivotBetreeSpecRefinement.__default.SplitChildrenConsistent.smt2  |  20.042s  |  20.042s  |   0.000s  | 0.0%|
|d_lvbkv-PivotBetree-PivotBetreeSpecWFNodes.i.dfy.Impl__PivotBetreeSpecWFNodes.__default.ValidSplitWritesInvNodes.smt2  |   2.112s  |   2.112s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-total_order_impl.i.dfy.Impl__Total__Order__Impl.__default.ArrayLargestLtePlus1Linear.smt2  |   0.212s  |   0.212s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-BucketsLib.i.dfy.Impl__BucketsLib.__default.WFProperSplitBucketInList.smt2  |  20.067s  |  20.067s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.DynamicPkv.Append.smt2                  |   1.662s  |   1.662s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Checksums-BitLemmas.i.dfy.Impl__BitLemmas.__default.eq__from__unpack__LittleEndian__Uint32__eq.smt2  |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|d_lvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__LMutableBtree.__default.InsertIndex.smt2  |   5.750s  |   5.750s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Lang-LinearSequence.i.dfy.Impl__LinearSequence__i.__default.AllocAndMoveLseq.smt2  |   0.206s  |   0.206s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallArray.smt2  |   0.596s  |   0.596s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallByteArray.smt2  |   0.392s  |   0.392s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallByteArrayInterior.smt2  |   0.641s  |   0.641s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Math-Nonlinear.i.dfy.Impl__NonlinearLemmas.__default.div__denom__ge__1.smt2     |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|s_komodo-1504.4.smt2                                                                        |  20.600s  |  20.600s  |   0.000s  | 0.0%|
</details>
