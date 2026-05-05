Comparing data and data


# SUMMARY
- LHS tests = 267
- RHS tests = 267
- LHS success = 260  (97.37827715355806%)
- RHS success = 260  (97.37827715355806%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: pre-gen-patch-mariposa-se
Runner: rise-runner-1
Z3 repo: CanCebeci/z3
Z3 commit: 51cbbe0a0ea3259ec92255e86e5818d1d6a9e523
Z3 branch: 51cbbe0a0ea3259ec92255e86e5818d1d6a9e523
Z3 options: "%OPTIONS2%"
Z3 inputs: inputs/mariposa/stable_ext
Z3 commit message: fix #9293

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: pre-gen-patch-mariposa-se
Runner: rise-runner-1
Z3 repo: CanCebeci/z3
Z3 commit: 51cbbe0a0ea3259ec92255e86e5818d1d6a9e523
Z3 branch: 51cbbe0a0ea3259ec92255e86e5818d1d6a9e523
Z3 options: "%OPTIONS2%"
Z3 inputs: inputs/mariposa/stable_ext
Z3 commit message: fix #9293

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectResultingGraphAfterAllocs.smt2  |   1.857s  |   1.857s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeCache.i.dfy.Impl__BetreeCache.__default.BetreeMoveStepPreservesInv.smt2  |   2.610s  |   2.610s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeSystem_Refines_StatesViewPivotBetree.i.dfy.Impl__BetreeSystem__Refines__StatesViewPivotBetree.__default.BetreeMoveStepRefines.smt2  |   9.882s  |   9.882s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ProcessWritePreservesInv.smt2  |   7.321s  |   7.321s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesReqWriteOp.smt2  |   9.046s  |   9.046s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenCompose.smt2  |  24.491s  |  24.491s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenFromBucketStackWithLowerBound.smt2  |   2.139s  |   2.139s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterInitImpl.i.dfy.Impl__CommitterInitImpl.__default.FinishLoadingOtherPhase.smt2  |   8.095s  |   8.095s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-EvictImpl.i.dfy.Impl__EvictImpl.__default.Evict.smt2                           |   5.155s  |   5.155s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-HandleReadResponseImpl.i.dfy.Impl__HandleReadResponseImpl.__default.readResponse.smt2  |  25.036s  |  25.036s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.writeNodeResponse.smt2                     |  11.359s  |  11.359s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.InitLocBitmap.smt2  |   5.516s  |   5.516s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.ValToIndirectionTable.smt2  |  23.437s  |  23.437s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.CheckWellformed__IndirectionTableModel.__default.RemoveRef.smt2  |   2.653s  |   2.653s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.Impl__IndirectionTableModel.__default.LemmaComputeRefCountsEntryIterateCorrectPartial.smt2  |   2.653s  |   2.653s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.fillInChecksumsPreserves.smt2  |   2.949s  |   2.949s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.writeOntoResult.smt2  |  12.263s  |  12.263s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.parseJournals.smt2  |   0.774s  |   0.774s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.ValToBuckets.smt2        |   7.984s  |   7.984s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.bucketToVal.smt2         |   1.926s  |   1.926s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectResultingGraphAfterAllocs.smt2  |   1.857s  |   1.857s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeCache.i.dfy.Impl__BetreeCache.__default.BetreeMoveStepPreservesInv.smt2  |   2.610s  |   2.610s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeSystem_Refines_StatesViewPivotBetree.i.dfy.Impl__BetreeSystem__Refines__StatesViewPivotBetree.__default.BetreeMoveStepRefines.smt2  |   9.882s  |   9.882s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ProcessWritePreservesInv.smt2  |   7.321s  |   7.321s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesReqWriteOp.smt2  |   9.046s  |   9.046s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenCompose.smt2  |  24.491s  |  24.491s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenFromBucketStackWithLowerBound.smt2  |   2.139s  |   2.139s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterInitImpl.i.dfy.Impl__CommitterInitImpl.__default.FinishLoadingOtherPhase.smt2  |   8.095s  |   8.095s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-EvictImpl.i.dfy.Impl__EvictImpl.__default.Evict.smt2                           |   5.155s  |   5.155s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-HandleReadResponseImpl.i.dfy.Impl__HandleReadResponseImpl.__default.readResponse.smt2  |  25.036s  |  25.036s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.writeNodeResponse.smt2                     |  11.359s  |  11.359s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.InitLocBitmap.smt2  |   5.516s  |   5.516s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.ValToIndirectionTable.smt2  |  23.437s  |  23.437s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.CheckWellformed__IndirectionTableModel.__default.RemoveRef.smt2  |   2.653s  |   2.653s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.Impl__IndirectionTableModel.__default.LemmaComputeRefCountsEntryIterateCorrectPartial.smt2  |   2.653s  |   2.653s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.fillInChecksumsPreserves.smt2  |   2.949s  |   2.949s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.writeOntoResult.smt2  |  12.263s  |  12.263s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.parseJournals.smt2  |   0.774s  |   0.774s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.ValToBuckets.smt2        |   7.984s  |   7.984s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.bucketToVal.smt2         |   1.926s  |   1.926s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectResultingGraphAfterAllocs.smt2  |   1.857s  |   1.857s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeCache.i.dfy.Impl__BetreeCache.__default.BetreeMoveStepPreservesInv.smt2  |   2.610s  |   2.610s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeSystem_Refines_StatesViewPivotBetree.i.dfy.Impl__BetreeSystem__Refines__StatesViewPivotBetree.__default.BetreeMoveStepRefines.smt2  |   9.882s  |   9.882s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ProcessWritePreservesInv.smt2  |   7.321s  |   7.321s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesReqWriteOp.smt2  |   9.046s  |   9.046s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenCompose.smt2  |  24.491s  |  24.491s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenFromBucketStackWithLowerBound.smt2  |   2.139s  |   2.139s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterInitImpl.i.dfy.Impl__CommitterInitImpl.__default.FinishLoadingOtherPhase.smt2  |   8.095s  |   8.095s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-EvictImpl.i.dfy.Impl__EvictImpl.__default.Evict.smt2                           |   5.155s  |   5.155s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-HandleReadResponseImpl.i.dfy.Impl__HandleReadResponseImpl.__default.readResponse.smt2  |  25.036s  |  25.036s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.writeNodeResponse.smt2                     |  11.359s  |  11.359s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.InitLocBitmap.smt2  |   5.516s  |   5.516s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.ValToIndirectionTable.smt2  |  23.437s  |  23.437s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.CheckWellformed__IndirectionTableModel.__default.RemoveRef.smt2  |   2.653s  |   2.653s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.Impl__IndirectionTableModel.__default.LemmaComputeRefCountsEntryIterateCorrectPartial.smt2  |   2.653s  |   2.653s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.fillInChecksumsPreserves.smt2  |   2.949s  |   2.949s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.writeOntoResult.smt2  |  12.263s  |  12.263s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.parseJournals.smt2  |   0.774s  |   0.774s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.ValToBuckets.smt2        |   7.984s  |   7.984s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.bucketToVal.smt2         |   1.926s  |   1.926s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectResultingGraphAfterAllocs.smt2  |   1.857s  |   1.857s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeCache.i.dfy.Impl__BetreeCache.__default.BetreeMoveStepPreservesInv.smt2  |   2.610s  |   2.610s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeSystem_Refines_StatesViewPivotBetree.i.dfy.Impl__BetreeSystem__Refines__StatesViewPivotBetree.__default.BetreeMoveStepRefines.smt2  |   9.882s  |   9.882s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ProcessWritePreservesInv.smt2  |   7.321s  |   7.321s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesReqWriteOp.smt2  |   9.046s  |   9.046s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenCompose.smt2  |  24.491s  |  24.491s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenFromBucketStackWithLowerBound.smt2  |   2.139s  |   2.139s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterInitImpl.i.dfy.Impl__CommitterInitImpl.__default.FinishLoadingOtherPhase.smt2  |   8.095s  |   8.095s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-EvictImpl.i.dfy.Impl__EvictImpl.__default.Evict.smt2                           |   5.155s  |   5.155s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-HandleReadResponseImpl.i.dfy.Impl__HandleReadResponseImpl.__default.readResponse.smt2  |  25.036s  |  25.036s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.writeNodeResponse.smt2                     |  11.359s  |  11.359s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.InitLocBitmap.smt2  |   5.516s  |   5.516s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.ValToIndirectionTable.smt2  |  23.437s  |  23.437s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.CheckWellformed__IndirectionTableModel.__default.RemoveRef.smt2  |   2.653s  |   2.653s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.Impl__IndirectionTableModel.__default.LemmaComputeRefCountsEntryIterateCorrectPartial.smt2  |   2.653s  |   2.653s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.fillInChecksumsPreserves.smt2  |   2.949s  |   2.949s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.writeOntoResult.smt2  |  12.263s  |  12.263s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.parseJournals.smt2  |   0.774s  |   0.774s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.ValToBuckets.smt2        |   7.984s  |   7.984s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.bucketToVal.smt2         |   1.926s  |   1.926s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|s_komodo-1488.6.smt2                                                                       |  81.729s |25.108GiB|
|s_komodo-1499.6.smt2                                                                       |  81.531s |24.504GiB|
|s_komodo-1504.6.smt2                                                                       |  81.514s |24.143GiB|
|s_komodo-1509.6.smt2                                                                       |  81.070s |16.263GiB|
|s_komodo-1493.6.smt2                                                                       |  81.065s |16.006GiB|
|s_komodo-1499.4.smt2                                                                       |  80.246s |4024.0MiB|
|s_komodo-1450.0.smt2                                                                       |  80.169s |2926.0MiB|
|s_komodo-1551.3.smt2                                                                       |  63.765s |125.0MiB|
|d_komodo-verified-entry.gen.dfyImpl___module.__default.va__lemma__stack__banked__regs2.smt2 |  50.211s |196.0MiB|
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.WriteBackNodeRespStepPreservesGraphs.smt2 |  48.088s |354.0MiB|
|d_lvbkv-Impl-SyncImpl.i.dfy.Impl__SyncImpl.__default.sync.smt2                             |  45.621s |231.0MiB|
|d_komodo-verified-entry.gen.dfyImpl___module.__default.va__lemma__enclaveexecution__loop.smt2 |  44.921s |190.0MiB|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SplitIndex.smt2 |  44.412s |191.0MiB|
|d_lvbkv-lib-DataStructures-LinearMutableMap.i.dfy.Impl__LinearMutableMap.__default.UpdateByIter.smt2 |  41.380s |123.0MiB|
|d_fvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.SplitIndexInterpretation1.smt2 |  37.353s |125.0MiB|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__svcHandled__conf__not__atkr.smt2 |  37.177s |207.0MiB|
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.AllocStepPreservesInv.smt2 |  36.905s |338.0MiB|
|d_lvbkv-lib-DataStructures-LinearContentMutableMap.i.dfy.Impl__LinearContentMutableMap.__default.FixedSizeInsertEntry.smt2 |  36.314s |119.0MiB|
|d_komodo-verified-attest_helpers.gen.dfyCheckWellformed___module.__default.va__lemma__load__attestion__key__inner.smt2 |  35.649s |275.0MiB|
|d_komodo-verified-kom_utils.gen.dfyImpl___module.__default.va__abstract__load__32__bit__const.smt2 |  35.493s |102.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|s_komodo-1488.6.smt2                                                                       |  81.729s |25.108GiB|
|s_komodo-1499.6.smt2                                                                       |  81.531s |24.504GiB|
|s_komodo-1504.6.smt2                                                                       |  81.514s |24.143GiB|
|s_komodo-1509.6.smt2                                                                       |  81.070s |16.263GiB|
|s_komodo-1493.6.smt2                                                                       |  81.065s |16.006GiB|
|s_komodo-1499.4.smt2                                                                       |  80.246s |4024.0MiB|
|s_komodo-1450.0.smt2                                                                       |  80.169s |2926.0MiB|
|s_komodo-1551.3.smt2                                                                       |  63.765s |125.0MiB|
|d_komodo-verified-entry.gen.dfyImpl___module.__default.va__lemma__stack__banked__regs2.smt2 |  50.211s |196.0MiB|
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.WriteBackNodeRespStepPreservesGraphs.smt2 |  48.088s |354.0MiB|
|d_lvbkv-Impl-SyncImpl.i.dfy.Impl__SyncImpl.__default.sync.smt2                             |  45.621s |231.0MiB|
|d_komodo-verified-entry.gen.dfyImpl___module.__default.va__lemma__enclaveexecution__loop.smt2 |  44.921s |190.0MiB|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SplitIndex.smt2 |  44.412s |191.0MiB|
|d_lvbkv-lib-DataStructures-LinearMutableMap.i.dfy.Impl__LinearMutableMap.__default.UpdateByIter.smt2 |  41.380s |123.0MiB|
|d_fvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.SplitIndexInterpretation1.smt2 |  37.353s |125.0MiB|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__svcHandled__conf__not__atkr.smt2 |  37.177s |207.0MiB|
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.AllocStepPreservesInv.smt2 |  36.905s |338.0MiB|
|d_lvbkv-lib-DataStructures-LinearContentMutableMap.i.dfy.Impl__LinearContentMutableMap.__default.FixedSizeInsertEntry.smt2 |  36.314s |119.0MiB|
|d_komodo-verified-attest_helpers.gen.dfyCheckWellformed___module.__default.va__lemma__load__attestion__key__inner.smt2 |  35.649s |275.0MiB|
|d_komodo-verified-kom_utils.gen.dfyImpl___module.__default.va__abstract__load__32__bit__const.smt2 |  35.493s |102.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectResultingGraphAfterAllocs.smt2  |52.944MiB|52.944MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeCache.i.dfy.Impl__BetreeCache.__default.BetreeMoveStepPreservesInv.smt2  |94.744MiB|94.744MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeSystem_Refines_StatesViewPivotBetree.i.dfy.Impl__BetreeSystem__Refines__StatesViewPivotBetree.__default.BetreeMoveStepRefines.smt2  |115.0MiB|115.0MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ProcessWritePreservesInv.smt2  |171.0MiB|171.0MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesReqWriteOp.smt2  |173.0MiB|173.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenCompose.smt2  |170.0MiB|170.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenFromBucketStackWithLowerBound.smt2  |95.868MiB|95.868MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterInitImpl.i.dfy.Impl__CommitterInitImpl.__default.FinishLoadingOtherPhase.smt2  |168.0MiB|168.0MiB|0B| 0.0%|
|d_fvbkv-Impl-EvictImpl.i.dfy.Impl__EvictImpl.__default.Evict.smt2                           |168.0MiB|168.0MiB|0B| 0.0%|
|d_fvbkv-Impl-HandleReadResponseImpl.i.dfy.Impl__HandleReadResponseImpl.__default.readResponse.smt2  |181.0MiB|181.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.writeNodeResponse.smt2                     |170.0MiB|170.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.InitLocBitmap.smt2  |105.0MiB|105.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.ValToIndirectionTable.smt2  |183.0MiB|183.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.CheckWellformed__IndirectionTableModel.__default.RemoveRef.smt2  |99.484MiB|99.484MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.Impl__IndirectionTableModel.__default.LemmaComputeRefCountsEntryIterateCorrectPartial.smt2  |99.22MiB|99.22MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.fillInChecksumsPreserves.smt2  |67.74MiB|67.74MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.writeOntoResult.smt2  |175.0MiB|175.0MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.parseJournals.smt2  |40.1MiB|40.1MiB|0B| 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.ValToBuckets.smt2        |167.0MiB|167.0MiB|0B| 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.bucketToVal.smt2         |99.0MiB|99.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectResultingGraphAfterAllocs.smt2  |52.944MiB|52.944MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeCache.i.dfy.Impl__BetreeCache.__default.BetreeMoveStepPreservesInv.smt2  |94.744MiB|94.744MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeSystem_Refines_StatesViewPivotBetree.i.dfy.Impl__BetreeSystem__Refines__StatesViewPivotBetree.__default.BetreeMoveStepRefines.smt2  |115.0MiB|115.0MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ProcessWritePreservesInv.smt2  |171.0MiB|171.0MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesReqWriteOp.smt2  |173.0MiB|173.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenCompose.smt2  |170.0MiB|170.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenFromBucketStackWithLowerBound.smt2  |95.868MiB|95.868MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterInitImpl.i.dfy.Impl__CommitterInitImpl.__default.FinishLoadingOtherPhase.smt2  |168.0MiB|168.0MiB|0B| 0.0%|
|d_fvbkv-Impl-EvictImpl.i.dfy.Impl__EvictImpl.__default.Evict.smt2                           |168.0MiB|168.0MiB|0B| 0.0%|
|d_fvbkv-Impl-HandleReadResponseImpl.i.dfy.Impl__HandleReadResponseImpl.__default.readResponse.smt2  |181.0MiB|181.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.writeNodeResponse.smt2                     |170.0MiB|170.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.InitLocBitmap.smt2  |105.0MiB|105.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.ValToIndirectionTable.smt2  |183.0MiB|183.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.CheckWellformed__IndirectionTableModel.__default.RemoveRef.smt2  |99.484MiB|99.484MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.Impl__IndirectionTableModel.__default.LemmaComputeRefCountsEntryIterateCorrectPartial.smt2  |99.22MiB|99.22MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.fillInChecksumsPreserves.smt2  |67.74MiB|67.74MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.writeOntoResult.smt2  |175.0MiB|175.0MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.parseJournals.smt2  |40.1MiB|40.1MiB|0B| 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.ValToBuckets.smt2        |167.0MiB|167.0MiB|0B| 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.bucketToVal.smt2         |99.0MiB|99.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectResultingGraphAfterAllocs.smt2  |52.944MiB|52.944MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeCache.i.dfy.Impl__BetreeCache.__default.BetreeMoveStepPreservesInv.smt2  |94.744MiB|94.744MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeSystem_Refines_StatesViewPivotBetree.i.dfy.Impl__BetreeSystem__Refines__StatesViewPivotBetree.__default.BetreeMoveStepRefines.smt2  |115.0MiB|115.0MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ProcessWritePreservesInv.smt2  |171.0MiB|171.0MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesReqWriteOp.smt2  |173.0MiB|173.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenCompose.smt2  |170.0MiB|170.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenFromBucketStackWithLowerBound.smt2  |95.868MiB|95.868MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterInitImpl.i.dfy.Impl__CommitterInitImpl.__default.FinishLoadingOtherPhase.smt2  |168.0MiB|168.0MiB|0B| 0.0%|
|d_fvbkv-Impl-EvictImpl.i.dfy.Impl__EvictImpl.__default.Evict.smt2                           |168.0MiB|168.0MiB|0B| 0.0%|
|d_fvbkv-Impl-HandleReadResponseImpl.i.dfy.Impl__HandleReadResponseImpl.__default.readResponse.smt2  |181.0MiB|181.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.writeNodeResponse.smt2                     |170.0MiB|170.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.InitLocBitmap.smt2  |105.0MiB|105.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.ValToIndirectionTable.smt2  |183.0MiB|183.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.CheckWellformed__IndirectionTableModel.__default.RemoveRef.smt2  |99.484MiB|99.484MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.Impl__IndirectionTableModel.__default.LemmaComputeRefCountsEntryIterateCorrectPartial.smt2  |99.22MiB|99.22MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.fillInChecksumsPreserves.smt2  |67.74MiB|67.74MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.writeOntoResult.smt2  |175.0MiB|175.0MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.parseJournals.smt2  |40.1MiB|40.1MiB|0B| 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.ValToBuckets.smt2        |167.0MiB|167.0MiB|0B| 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.bucketToVal.smt2         |99.0MiB|99.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectResultingGraphAfterAllocs.smt2  |52.944MiB|52.944MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeCache.i.dfy.Impl__BetreeCache.__default.BetreeMoveStepPreservesInv.smt2  |94.744MiB|94.744MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeSystem_Refines_StatesViewPivotBetree.i.dfy.Impl__BetreeSystem__Refines__StatesViewPivotBetree.__default.BetreeMoveStepRefines.smt2  |115.0MiB|115.0MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ProcessWritePreservesInv.smt2  |171.0MiB|171.0MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesReqWriteOp.smt2  |173.0MiB|173.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenCompose.smt2  |170.0MiB|170.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenFromBucketStackWithLowerBound.smt2  |95.868MiB|95.868MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterInitImpl.i.dfy.Impl__CommitterInitImpl.__default.FinishLoadingOtherPhase.smt2  |168.0MiB|168.0MiB|0B| 0.0%|
|d_fvbkv-Impl-EvictImpl.i.dfy.Impl__EvictImpl.__default.Evict.smt2                           |168.0MiB|168.0MiB|0B| 0.0%|
|d_fvbkv-Impl-HandleReadResponseImpl.i.dfy.Impl__HandleReadResponseImpl.__default.readResponse.smt2  |181.0MiB|181.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.writeNodeResponse.smt2                     |170.0MiB|170.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.InitLocBitmap.smt2  |105.0MiB|105.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.ValToIndirectionTable.smt2  |183.0MiB|183.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.CheckWellformed__IndirectionTableModel.__default.RemoveRef.smt2  |99.484MiB|99.484MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.Impl__IndirectionTableModel.__default.LemmaComputeRefCountsEntryIterateCorrectPartial.smt2  |99.22MiB|99.22MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.fillInChecksumsPreserves.smt2  |67.74MiB|67.74MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.writeOntoResult.smt2  |175.0MiB|175.0MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.parseJournals.smt2  |40.1MiB|40.1MiB|0B| 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.ValToBuckets.smt2        |167.0MiB|167.0MiB|0B| 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.bucketToVal.smt2         |99.0MiB|99.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|s_komodo-1488.6.smt2                                                                       |  81.729s |25.108GiB|
|s_komodo-1499.6.smt2                                                                       |  81.531s |24.504GiB|
|s_komodo-1504.6.smt2                                                                       |  81.514s |24.143GiB|
|s_komodo-1509.6.smt2                                                                       |  81.070s |16.263GiB|
|s_komodo-1493.6.smt2                                                                       |  81.065s |16.006GiB|
|s_komodo-1499.4.smt2                                                                       |  80.246s |4024.0MiB|
|s_komodo-1450.0.smt2                                                                       |  80.169s |2926.0MiB|
|d_lvbkv-ByteBlockCacheSystem-ByteSystem_Refines_BetreeJournalSystem.i.dfy.Impl__ByteSystem__Refines__BetreeJournalSystem.__default.RefinesNext.smt2 |  14.278s |402.0MiB|
|d_komodo-verified-secprop-conf_ni.i.dfyImpl___module.__default.lemma__mapSecure__loweq__pdb__success.smt2 |  33.304s |358.0MiB|
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.WriteBackNodeRespStepPreservesGraphs.smt2 |  48.088s |354.0MiB|
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.AllocStepPreservesInv.smt2 |  36.905s |338.0MiB|
|d_lvbkv-lib-Checksums-F2_X_Lemmas.i.dfy.Impl__F2__X__Lemmas.__default.p__qr__partial.smt2  |  22.019s |278.0MiB|
|d_komodo-verified-attest_helpers.gen.dfyCheckWellformed___module.__default.va__lemma__load__attestion__key__inner.smt2 |  35.649s |275.0MiB|
|d_komodo-verified-attest_helpers.gen.dfyImpl___module.__default.va__lemma__unstack__all__regs.smt2 |  24.320s |237.0MiB|
|d_lvbkv-Impl-SyncImpl.i.dfy.Impl__SyncImpl.__default.sync.smt2                             |  45.621s |231.0MiB|
|d_lvbkv-Impl-CoordinationImpl.i.dfy.Impl__CoordinationImpl.__default.succ.smt2             |  30.747s |229.0MiB|
|d_komodo-verified-sha-hmac.gen.dfyImpl___module.__default.va__lemma__hmac__outer.smt2      |  26.020s |228.0MiB|
|d_lvbkv-Impl-SyncImpl.i.dfy.Impl__SyncImpl.__default.TryToWriteBlock.smt2                  |  34.584s |226.0MiB|
|d_komodo-verified-svc_handlers.gen.dfyImpl___module.__default.va__lemma__rng__read.smt2    |  24.755s |223.0MiB|
|d_lvbkv-BlockCacheSystem-BetreeJournalSystem_Refines_ThreeStateVersionedMap.i.dfy.Impl__BetreeJournalSystem__Refines__ThreeStateVersionedMap.__default.RefinesNext.smt2 |   3.217s |217.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|s_komodo-1488.6.smt2                                                                       |  81.729s |25.108GiB|
|s_komodo-1499.6.smt2                                                                       |  81.531s |24.504GiB|
|s_komodo-1504.6.smt2                                                                       |  81.514s |24.143GiB|
|s_komodo-1509.6.smt2                                                                       |  81.070s |16.263GiB|
|s_komodo-1493.6.smt2                                                                       |  81.065s |16.006GiB|
|s_komodo-1499.4.smt2                                                                       |  80.246s |4024.0MiB|
|s_komodo-1450.0.smt2                                                                       |  80.169s |2926.0MiB|
|d_lvbkv-ByteBlockCacheSystem-ByteSystem_Refines_BetreeJournalSystem.i.dfy.Impl__ByteSystem__Refines__BetreeJournalSystem.__default.RefinesNext.smt2 |  14.278s |402.0MiB|
|d_komodo-verified-secprop-conf_ni.i.dfyImpl___module.__default.lemma__mapSecure__loweq__pdb__success.smt2 |  33.304s |358.0MiB|
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.WriteBackNodeRespStepPreservesGraphs.smt2 |  48.088s |354.0MiB|
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.AllocStepPreservesInv.smt2 |  36.905s |338.0MiB|
|d_lvbkv-lib-Checksums-F2_X_Lemmas.i.dfy.Impl__F2__X__Lemmas.__default.p__qr__partial.smt2  |  22.019s |278.0MiB|
|d_komodo-verified-attest_helpers.gen.dfyCheckWellformed___module.__default.va__lemma__load__attestion__key__inner.smt2 |  35.649s |275.0MiB|
|d_komodo-verified-attest_helpers.gen.dfyImpl___module.__default.va__lemma__unstack__all__regs.smt2 |  24.320s |237.0MiB|
|d_lvbkv-Impl-SyncImpl.i.dfy.Impl__SyncImpl.__default.sync.smt2                             |  45.621s |231.0MiB|
|d_lvbkv-Impl-CoordinationImpl.i.dfy.Impl__CoordinationImpl.__default.succ.smt2             |  30.747s |229.0MiB|
|d_komodo-verified-sha-hmac.gen.dfyImpl___module.__default.va__lemma__hmac__outer.smt2      |  26.020s |228.0MiB|
|d_lvbkv-Impl-SyncImpl.i.dfy.Impl__SyncImpl.__default.TryToWriteBlock.smt2                  |  34.584s |226.0MiB|
|d_komodo-verified-svc_handlers.gen.dfyImpl___module.__default.va__lemma__rng__read.smt2    |  24.755s |223.0MiB|
|d_lvbkv-BlockCacheSystem-BetreeJournalSystem_Refines_ThreeStateVersionedMap.i.dfy.Impl__BetreeJournalSystem__Refines__ThreeStateVersionedMap.__default.RefinesNext.smt2 |   3.217s |217.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectResultingGraphAfterAllocs.smt2  |   1.857s  |   1.857s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeCache.i.dfy.Impl__BetreeCache.__default.BetreeMoveStepPreservesInv.smt2  |   2.610s  |   2.610s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeSystem_Refines_StatesViewPivotBetree.i.dfy.Impl__BetreeSystem__Refines__StatesViewPivotBetree.__default.BetreeMoveStepRefines.smt2  |   9.882s  |   9.882s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ProcessWritePreservesInv.smt2  |   7.321s  |   7.321s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesReqWriteOp.smt2  |   9.046s  |   9.046s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenCompose.smt2  |  24.491s  |  24.491s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenFromBucketStackWithLowerBound.smt2  |   2.139s  |   2.139s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterInitImpl.i.dfy.Impl__CommitterInitImpl.__default.FinishLoadingOtherPhase.smt2  |   8.095s  |   8.095s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-EvictImpl.i.dfy.Impl__EvictImpl.__default.Evict.smt2                           |   5.155s  |   5.155s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-HandleReadResponseImpl.i.dfy.Impl__HandleReadResponseImpl.__default.readResponse.smt2  |  25.036s  |  25.036s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.writeNodeResponse.smt2                     |  11.359s  |  11.359s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.InitLocBitmap.smt2  |   5.516s  |   5.516s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.ValToIndirectionTable.smt2  |  23.437s  |  23.437s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.CheckWellformed__IndirectionTableModel.__default.RemoveRef.smt2  |   2.653s  |   2.653s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.Impl__IndirectionTableModel.__default.LemmaComputeRefCountsEntryIterateCorrectPartial.smt2  |   2.653s  |   2.653s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.fillInChecksumsPreserves.smt2  |   2.949s  |   2.949s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.writeOntoResult.smt2  |  12.263s  |  12.263s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.parseJournals.smt2  |   0.774s  |   0.774s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.ValToBuckets.smt2        |   7.984s  |   7.984s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.bucketToVal.smt2         |   1.926s  |   1.926s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.bucketsToVal.smt2        |   4.958s  |   4.958s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.nodeToVal.smt2           |  10.336s  |  10.336s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-QueryModel.i.dfy.Impl__QueryModel.__default.AugmentLookup.smt2                 |   2.627s  |   2.627s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-SplitImpl.i.dfy.Impl__SplitImpl.__default.splitBookkeeping.smt2                |  13.304s  |  13.304s  |   0.000s  | 0.0%|
|d_fvbkv-PivotBetree-PivotBetree.i.dfy.Impl__PivotBetree.__default.BetreeStepRefines.smt2    |   3.410s  |   3.410s  |   0.000s  | 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.Impl__PivotBetreeSpecRefinement.__default.CutoffNodeAndKeepRightAgree.smt2  |   0.817s  |   0.817s  |   0.000s  | 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpecWFNodes.i.dfy.Impl__PivotBetreeSpecWFNodes.__default.ValidMergeWritesInvNodes.smt2  |   3.361s  |   3.361s  |   0.000s  | 0.0%|
|d_fvbkv-Versions-CompositeView_Refines_TSJMap.i.dfy.Impl__CompositeView__Refines__TSJMap.__default.CrashRefines.smt2  |   0.565s  |   0.565s  |   0.000s  | 0.0%|
|d_fvbkv-Versions-CompositeView_Refines_TSJMap.i.dfy.Impl__CompositeView__Refines__TSJMap.__default.JournalInternalRefines.smt2  |   0.938s  |   0.938s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-Multisets.i.dfy.Impl__Multisets.__default.FoldAdditive.smt2                |   2.948s  |   2.948s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-sequences.i.dfy.Impl__Sequences.__default.FlattenAdditive.smt2             |   0.313s  |   0.313s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-sequences.i.dfy.Impl__Sequences.__default.UnflattenFlattenIdentity.smt2    |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-total_order.i.dfy.Impl__Char__Order.__default.FlattenStrictlySorted.smt2   |   0.220s  |   0.220s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-total_order.i.dfy.Impl__Total__Order.__default.FlattenStrictlySorted.smt2  |   0.309s  |   0.309s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-total_order.i.dfy.Impl__Total__Order.__default.strictlySortedInsert.smt2   |   0.347s  |   0.347s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-total_order.i.dfy.Impl__Uint32__Order.__default.FlattenStrictlySorted.smt2  |   0.216s  |   0.216s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-total_order.i.dfy.Impl__Uint64__Order.__default.FlattenStrictlySorted.smt2  |   0.207s  |   0.207s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.SplitOneInList.smt2         |   1.788s  |   1.788s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.WeightKeySeqIs.smt2         |   0.821s  |   0.821s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketModel.i.dfy.Impl__BucketModel.__default.mergeToChildrenIterSlack_split0.smt2  |   0.898s  |   0.898s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.WMWeightBucketListFlush.smt2  |   0.747s  |   0.747s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.WeightBucketListItemFlushSingletonOrEmpty.smt2  |   1.713s  |   1.713s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.WeightMessageListFlatten.smt2  |   0.516s  |   0.516s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.WeightSplitBucketInList.smt2  |   0.467s  |   0.467s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-KMBPKVOps.i.dfy.Impl__KMBPKVOps.__default.IMessagesInverse.smt2         |   0.717s  |   0.717s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-KMBPKVOps.i.dfy.Impl__KMBPKVOps.__default.ToPkv.smt2                    |  22.336s  |  22.336s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-KMBPKVOps.i.dfy.Impl__KMBPKVOps.__default.canAppendMessagesIterate.smt2  |   1.003s  |   1.003s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.CheckWellformed__DynamicPkv.__default.PKVISeq.smt2       |   0.771s  |   0.771s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.psaTotalLengthBound.smt2        |   0.580s  |   0.580s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKVMarshalling.i.dfy.Impl__PackedKVMarshalling.__default.ComputeWF.smt2  |   0.652s  |   0.652s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKVMarshalling.i.dfy.Impl__PackedKVMarshalling.__default.SizeOfVPackedStringArrayIsKeyListWeight.smt2  |   0.997s  |   0.997s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.PivotIndexes.smt2  |   0.381s  |   0.381s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.psaAppendSeqAdditive.smt2  |   0.427s  |   0.427s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-BitmapImpl.i.dfy.Impl__BitmapImpl.Bitmap.Set.smt2                |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-BitmapImpl.i.dfy.Impl__BitmapImpl.Bitmap.Unset.smt2              |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.InsertLeafIsCorrect.smt2  |   1.509s  |   1.509s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.SplitChildOfIndexPreservesInterpretationB.smt2  |   4.088s  |   4.088s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.SplitIndexInterpretation1.smt2  |  37.353s  |  37.353s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.SplitIndexInterpretation2.smt2  |   2.314s  |   2.314s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-KMBtree.i.dfy.Impl__KMBtree.__default.InsertIndexSelectAndPrepareChild.smt2  |   1.335s  |   1.335s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-KMBtree.i.dfy.Impl__KMBtree.__default.SplitIndex.smt2            |  24.246s  |  24.246s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-KMBtree.i.dfy.Impl__KMBtreeModel.__default.InterpretationsDisjointUnion.smt2  |   4.747s  |   4.747s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-KMBtree.i.dfy.Impl__KMBtreeModel.__default.SplitIndexInterpretation1.smt2  |   3.057s  |   3.057s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.InsertIndexChildNotFull.smt2  |   6.368s  |   6.368s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.InsertIndexSelectAndPrepareChild.smt2  |   2.271s  |   2.271s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SplitIndex.smt2  |  44.412s  |  44.412s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__TestBtreeModel.__default.SplitIndexInterpretation1.smt2  |   2.413s  |   2.413s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__TestMutableBtree.__default.SplitIndex.smt2  |  19.054s  |  19.054s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableMapModel.i.dfy.CheckWellformed__MutableMapModel.__default.IterInc.smt2  |   3.390s  |   3.390s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableMapModel.i.dfy.CheckWellformed__MutableMapModel.__default.iterToNext.smt2  |   0.420s  |   0.420s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableMapModel.i.dfy.Impl__MutableMapModel.__default.MapFromStorageProperties.smt2  |   0.491s  |   0.491s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableMapModel.i.dfy.Impl__MutableMapModel.__default.UpdatePreservesSimpleIter.smt2  |   1.201s  |   1.201s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.CheckWellformed__GenericMarshalling.__default.parse__Val.smt2  |   0.343s  |   0.343s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__div__ind.smt2                |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-Util.i.dfy.CheckWellformed__Common____Util__i.__default.Uint64ToSeqByte.smt2  |   1.634s  |   1.634s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Math-mul.i.dfy.Impl__Math____mul__i.__default.lemma__mul__equality__converse.smt2  |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Math-mul.i.dfy.Impl__Math____mul__i.__default.lemma__mul__one__to__one__pos.smt2  |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|d_komodo-verified-alloc_spare.gen.dfyImpl___module.__default.va__lemma__kom__smc__alloc__spare.smt2  |  19.433s  |  19.433s  |   0.000s  | 0.0%|
|d_komodo-verified-allocate_page.gen.dfyCheckWellformed___module.__default.va__lemma__addrspace__incref.smt2  |   2.163s  |   2.163s  |   0.000s  | 0.0%|
|d_komodo-verified-allocate_page.gen.dfyCheckWellformed___module.__default.va__lemma__allocate__page__success.smt2  |   8.160s  |   8.160s  |   0.000s  | 0.0%|
|d_komodo-verified-attest.gen.dfyCheckWellformed___module.__default.va__lemma__compute__hmac.smt2  |   5.589s  |   5.589s  |   0.000s  | 0.0%|
|d_komodo-verified-attest.gen.dfyCheckWellformed___module.__default.va__lemma__svc__returning__attest__inner.smt2  |   1.966s  |   1.966s  |   0.000s  | 0.0%|
|d_komodo-verified-attest_helpers.gen.dfyCheckWellformed___module.__default.va__lemma__load__attestion__key__inner.smt2  |  35.649s  |  35.649s  |   0.000s  | 0.0%|
|d_komodo-verified-attest_helpers.gen.dfyImpl___module.__default.va__lemma__unstack__all__regs.smt2  |  24.320s  |  24.320s  |   0.000s  | 0.0%|
|d_komodo-verified-attest_input.gen.dfyImpl___module.__default.va__lemma__arrange__attestation__input.smt2  |  10.613s  |  10.613s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.gen.dfyCheckWellformed___module.__default.va__lemma__pre__entry__resume.smt2  |   1.189s  |   1.189s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.gen.dfyCheckWellformed___module.__default.va__lemma__stack__banked__regs1.smt2  |   0.936s  |   0.936s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.gen.dfyCheckWellformed___module.__default.va__lemma__stack__banked__regs2.smt2  |   4.216s  |   4.216s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.gen.dfyCheckWellformed___module.__default.va__lemma__stack__banked__regs3.smt2  |   3.446s  |   3.446s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.gen.dfyCheckWellformed___module.__default.va__lemma__switch__addrspace.smt2  |   0.980s  |   0.980s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.gen.dfyCheckWellformed___module.__default.va__lemma__unstack__banked__regs3.smt2  |   5.166s  |   5.166s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.gen.dfyImpl___module.__default.lemma__stackunstack__banked__regs.smt2  |  12.723s  |  12.723s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.gen.dfyImpl___module.__default.va__lemma__enclaveexecution__loop.smt2  |  44.921s  |  44.921s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.gen.dfyImpl___module.__default.va__lemma__stack__banked__regs2.smt2  |  50.211s  |  50.211s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.gen.dfyImpl___module.__default.va__lemma__unstack__banked__regs1.smt2  |  30.640s  |  30.640s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.gen.dfyImpl___module.__default.va__lemma__unstack__banked__regs_split0.smt2  |  25.661s  |  25.661s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.i.dfyCheckWellformed___module.__default.lemma__evalMOVSPCLRUC__inner.smt2  |   1.623s  |   1.623s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.i.dfyImpl___module.__default.lemma__partialEnclaveExecution__append.smt2  |   1.803s  |   1.803s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.i.dfyImpl___module.__default.lemma__partialEnclaveExecution__done.smt2  |   1.875s  |   1.875s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.i.dfyImpl___module.__default.lemma__userExecutionPreservesStack.smt2  |   3.530s  |   3.530s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.i.dfyImpl___module.__default.lemma__userExecutionUpdatesPageDb_split0.smt2  |   1.733s  |   1.733s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.i.dfyImpl___module.__default.lemma__validEnclaveExecutionStep__PageDb.smt2  |   3.705s  |   3.705s  |   0.000s  | 0.0%|
|d_komodo-verified-exception_handlers.gen.dfyCheckWellformed___module.__default.va__lemma__CPSID__IAF.smt2  |   4.512s  |   4.512s  |   0.000s  | 0.0%|
|d_komodo-verified-exception_handlers.gen.dfyCheckWellformed___module.__default.va__lemma__save__disp__context.smt2  |   1.872s  |   1.872s  |   0.000s  | 0.0%|
|d_komodo-verified-exception_handlers.gen.dfyImpl___module.__default.va__lemma__CPSID__IAF.smt2  |  34.500s  |  34.500s  |   0.000s  | 0.0%|
|d_komodo-verified-exception_handlers.gen.dfyImpl___module.__default.va__lemma__switch__to__monitor.smt2  |   9.056s  |   9.056s  |   0.000s  | 0.0%|
|d_komodo-verified-exhandler_state.i.dfyCheckWellformed___module.__default.lemma__SVCFIQNestedExceptionIsCorrect.smt2  |  11.857s  |  11.857s  |   0.000s  | 0.0%|
|d_komodo-verified-exhandler_state.i.dfyImpl___module.__default.lemma__KomUserEntryPrecond__Preserved.smt2  |  18.861s  |  18.861s  |   0.000s  | 0.0%|
|d_komodo-verified-exhandler_state.i.dfyImpl___module.__default.lemma__PrivModeExceptionHandlersAreCorrect.smt2  |  28.851s  |  28.851s  |   0.000s  | 0.0%|
|d_komodo-verified-finalise.gen.dfyCheckWellformed___module.__default.lemma__kom__smc__finalise__success__helper1.smt2  |  11.128s  |  11.128s  |   0.000s  | 0.0%|
|d_komodo-verified-init_l2ptable.gen.dfyCheckWellformed___module.__default.va__lemma__init__l2ptable__success.smt2  |   1.662s  |   1.662s  |   0.000s  | 0.0%|
|d_komodo-verified-init_l2ptable.gen.dfyCheckWellformed___module.__default.va__lemma__zero__l2__page.smt2  |   9.339s  |   9.339s  |   0.000s  | 0.0%|
|d_komodo-verified-init_l2ptable.gen.dfyImpl___module.__default.lemma__SecurePage.smt2       |   2.298s  |   2.298s  |   0.000s  | 0.0%|
|d_komodo-verified-init_l2ptable.gen.dfyImpl___module.__default.va__lemma__init__l2ptable__success_split0.smt2  |  13.725s  |  13.725s  |   0.000s  | 0.0%|
|d_komodo-verified-kom_utils.gen.dfyImpl___module.__default.va__abstract__load__32__bit__const.smt2  |  35.493s  |  35.493s  |   0.000s  | 0.0%|
|d_komodo-verified-map_common.gen.dfyCheckWellformed___module.__default.lemma__update__l2pte__helper1.smt2  |   8.631s  |   8.631s  |   0.000s  | 0.0%|
|d_komodo-verified-map_common.gen.dfyImpl___module.__default.lemma__update__l2pte__helper1.smt2  |  16.074s  |  16.074s  |   0.000s  | 0.0%|
|d_komodo-verified-map_common.gen.dfyImpl___module.__default.va__lemma__mkL2Pte__secure.smt2  |   9.350s  |   9.350s  |   0.000s  | 0.0%|
|d_komodo-verified-map_insecure.gen.dfyImpl___module.__default.va__lemma__mkl2pte__insecure.smt2  |   6.338s  |   6.338s  |   0.000s  | 0.0%|
|d_komodo-verified-map_insecure.gen.dfyImpl___module.__default.va__lemma__phys__page__is__insecure__ram.smt2  |  16.904s  |  16.904s  |   0.000s  | 0.0%|
|d_komodo-verified-map_secure.gen.dfyImpl___module.__default.lemma__preserve__contentsOfPhysPage.smt2  |   3.405s  |   3.405s  |   0.000s  | 0.0%|
|d_komodo-verified-memset.gen.dfyCheckWellformed___module.__default.va__lemma__memcpy.smt2   |   6.187s  |   6.187s  |   0.000s  | 0.0%|
|d_komodo-verified-memset.gen.dfyCheckWellformed___module.__default.va__lemma__memcpy__bare.smt2  |   6.339s  |   6.339s  |   0.000s  | 0.0%|
|d_komodo-verified-memset.gen.dfyImpl___module.__default.va__lemma__memcpy.smt2              |   2.236s  |   2.236s  |   0.000s  | 0.0%|
|d_komodo-verified-pagedb.i.dfyImpl___module.__default.AllButOnePagePreserving.smt2          |   6.757s  |   6.757s  |   0.000s  | 0.0%|
|d_komodo-verified-psrbits.i.dfyImpl___module.__default.lemma__update__psr__f.smt2           |   1.867s  |   1.867s  |   0.000s  | 0.0%|
|d_komodo-verified-ptables.i.dfyImpl___module.__default.lemma__OnlyPTPagesInHwPTable.smt2    |   6.461s  |   6.461s  |   0.000s  | 0.0%|
|d_komodo-verified-ptables.i.dfyImpl___module.__default.lemma__memstatecontainspage.smt2     |   1.342s  |   1.342s  |   0.000s  | 0.0%|
|d_komodo-verified-ptables.i.dfyImpl___module.__default.lemma__ptablesmatch_split11.smt2     |   1.628s  |   1.628s  |   0.000s  | 0.0%|
|d_komodo-verified-ptebits.i.dfyImpl___module.__default.lemma__ARM__L2PTE_split0.smt2        |   0.488s  |   0.488s  |   0.000s  | 0.0%|
|d_komodo-verified-ptebits.i.dfyImpl___module.__default.lemma__l2indexFromMapping__shifts.smt2  |   0.591s  |   0.591s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-conf_ni.i.dfyImpl___module.__default.lemma__conf__ni.smt2         |   3.563s  |   3.563s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-conf_ni.i.dfyImpl___module.__default.lemma__initAddrspace__loweq__pdb.smt2  |   6.207s  |   6.207s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-conf_ni.i.dfyImpl___module.__default.lemma__mapSecure__loweq__pdb__success.smt2  |  33.304s  |  33.304s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyCheckWellformed___module.__default.lemma__svcHandled__conf__not__atkr.smt2  |  24.103s  |  24.103s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__data__eqpdb__to__addrs.smt2  |   3.954s  |   3.954s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__data__page__eqdb__to__addrs.smt2  |   1.659s  |   1.659s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__svcHandled__conf__not__atkr.smt2  |  37.177s  |  37.177s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__userMemEquiv__atkr.smt2  |   8.222s  |   8.222s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__userStatesEquiv__atkr.smt2  |   5.377s  |   5.377s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-integ_ni.i.dfyImpl___module.__default.lemma__enc__ni.smt2         |   1.071s  |   1.071s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-integ_ni_entry.i.dfyImpl___module.__default.lemma__enter__enc__ni.smt2  |   3.538s  |   3.538s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-sec_prop_util.i.dfyImpl___module.__default.lemma__maybeContents__insec__ni.smt2  |   1.535s  |   1.535s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-bit-vector-lemmas.i.dfyImpl___module.__default.lemma__Ch.smt2         |   0.401s  |   0.401s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-bit-vector-lemmas.i.dfyImpl___module.__default.lemma__Maj.smt2        |   0.445s  |   0.445s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-hmac.gen.dfyCheckWellformed___module.__default.va__lemma__hmac__inner.smt2  |   1.446s  |   1.446s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-hmac.gen.dfyImpl___module.__default.va__lemma__hmac__inner__prep__input.smt2  |   5.005s  |   5.005s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-hmac.gen.dfyImpl___module.__default.va__lemma__hmac__outer.smt2       |  26.020s  |  26.020s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-sha256-api.gen.dfyImpl___module.__default.va__abstract__sha256__init.smt2  |   8.407s  |   8.407s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-sha256-api.gen.dfyImpl___module.__default.va__refined__sha256__finalize.smt2  |  23.168s  |  23.168s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-sha256-api.gen.dfyImpl___module.__default.va__refined__sha256__one__shot.smt2  |  30.382s  |  30.382s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-sha256-block-data-order.gen.dfyImpl___module.__default.va__abstract__sha256__block__data__order__inner.smt2  |  28.224s  |  28.224s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-sha256.i.dfyImpl___module.__default.lemma__ArrayOffsetConcatenation.smt2  |   0.347s  |   0.347s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-sha256.i.dfyImpl___module.__default.lemma__ConcatenateSeqs__Adds.smt2  |   0.421s  |   0.421s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-sha256.i.dfyImpl___module.__default.lemma__Trace__stitching.smt2      |   0.493s  |   0.493s  |   0.000s  | 0.0%|
|d_komodo-verified-smcapi.i.dfyCheckWellformed___module.__default.kom__smc__map__measure__helper2.smt2  |   2.340s  |   2.340s  |   0.000s  | 0.0%|
|d_komodo-verified-smcapi.i.dfyImpl___module.__default.AllButOnePageOrStackPreserving.smt2   |   6.759s  |   6.759s  |   0.000s  | 0.0%|
|d_komodo-verified-smcapi.i.dfyImpl___module.__default.initDispatcherPreservesPageDBValidity.smt2  |   8.848s  |   8.848s  |   0.000s  | 0.0%|
|d_komodo-verified-smcapi.i.dfyImpl___module.__default.kom__smc__map__measure__helper2.smt2  |   1.660s  |   1.660s  |   0.000s  | 0.0%|
|d_komodo-verified-smcapi.i.dfyImpl___module.__default.lemma__ConcatenateSeqs__Adds_k.smt2   |   0.875s  |   0.875s  |   0.000s  | 0.0%|
|d_komodo-verified-smcapi.i.dfyImpl___module.__default.lemma__validEnclaveExecutionStep__validPageDb.smt2  |   9.388s  |   9.388s  |   0.000s  | 0.0%|
|d_komodo-verified-smcapi.i.dfyImpl___module.__default.mapSecurePreservesPageDBValidity.smt2  |  28.381s  |  28.381s  |   0.000s  | 0.0%|
|d_komodo-verified-svc_handlers.gen.dfyCheckWellformed___module.__default.lemma__svc__returning__verify__step0__helper.smt2  |   3.206s  |   3.206s  |   0.000s  | 0.0%|
|d_komodo-verified-svc_handlers.gen.dfyCheckWellformed___module.__default.va__lemma__svc__map__data__success.smt2  |  26.911s  |  26.911s  |   0.000s  | 0.0%|
|d_komodo-verified-svc_handlers.gen.dfyCheckWellformed___module.__default.va__lemma__svc__returning__verify__step0.smt2  |  14.468s  |  14.468s  |   0.000s  | 0.0%|
|d_komodo-verified-svc_handlers.gen.dfyCheckWellformed___module.__default.va__lemma__svc__unmap__data.smt2  |   1.806s  |   1.806s  |   0.000s  | 0.0%|
|d_komodo-verified-svc_handlers.gen.dfyImpl___module.__default.lemma__svc__returning__WordAlignedStack.smt2  |   7.140s  |   7.140s  |   0.000s  | 0.0%|
|d_komodo-verified-svc_handlers.gen.dfyImpl___module.__default.va__lemma__monvaddr__page__impl.smt2  |  14.254s  |  14.254s  |   0.000s  | 0.0%|
|d_komodo-verified-svc_handlers.gen.dfyImpl___module.__default.va__lemma__rng__read.smt2     |  24.755s  |  24.755s  |   0.000s  | 0.0%|
|d_komodo-verified-valedecls.gen.dfyImpl___module.__default.va__lemma__MSR.smt2              |   0.824s  |   0.824s  |   0.000s  | 0.0%|
|d_komodo-verified-verify.gen.dfyCheckWellformed___module.__default.va__lemma__svc__returning__verify__inner.smt2  |   6.695s  |   6.695s  |   0.000s  | 0.0%|
|d_komodo-verified-verify_input.gen.dfyImpl___module.__default.va__lemma__arrange__verification__input.smt2  |   5.968s  |   5.968s  |   0.000s  | 0.0%|
|d_lvbkv-Betree-AsyncBetree_Refines_AsyncMap.i.dfy.Impl__AsyncBetree__Refines__AsyncMap.__default.RefinesQueryEndStep.smt2  |   7.534s  |   7.534s  |   0.000s  | 0.0%|
|d_lvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.FlushStepPreservesInvariant.smt2   |  30.215s  |  30.215s  |   0.000s  | 0.0%|
|d_lvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.InsertMessagePreservesLookupsPut.smt2  |  14.924s  |  14.924s  |   0.000s  | 0.0%|
|d_lvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectPreservesRootHasNoPred.smt2  |  11.856s  |  11.856s  |   0.000s  | 0.0%|
|d_lvbkv-Betree-Betree_Refines_Map.i.dfy.Impl__Betree__Refines__Map.__default.RefinesNextStep.smt2  |  22.456s  |  22.456s  |   0.000s  | 0.0%|
|d_lvbkv-Betree-Betree_Refines_Map.i.dfy.Impl__Betree__Refines__Map.__default.SuccQueryStepRefinesMap.smt2  |  11.129s  |  11.129s  |   0.000s  | 0.0%|
|d_lvbkv-BlockCacheSystem-BetreeJournalSystem_Refines_ThreeStateVersionedMap.i.dfy.Impl__BetreeJournalSystem__Refines__ThreeStateVersionedMap.__default.RefinesNext.smt2  |   3.217s  |   3.217s  |   0.000s  | 0.0%|
|d_lvbkv-BlockCacheSystem-BetreeSystem_Refines_StatesViewPivotBetree.i.dfy.Impl__BetreeSystem__Refines__StatesViewPivotBetree.__default.CrashStepRefines.smt2  |   1.870s  |   1.870s  |   0.000s  | 0.0%|
|d_lvbkv-BlockCacheSystem-BlockCache.i.dfy.Impl__BlockCache.__default.AllocStepPreservesInv.smt2  |   1.396s  |   1.396s  |   0.000s  | 0.0%|
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.AllocStepPreservesInv.smt2  |  36.905s  |  36.905s  |   0.000s  | 0.0%|
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.WriteBackIndirectionTableReqStepPreservesInv.smt2  |   4.202s  |   4.202s  |   0.000s  | 0.0%|
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.WriteBackNodeRespStepPreservesGraphs.smt2  |  48.088s  |  48.088s  |   0.000s  | 0.0%|
|d_lvbkv-BlockCacheSystem-DiskLayout.i.dfy.Impl__DiskLayout.__default.ValidNodeAddrMul.smt2  |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|d_lvbkv-BlockCacheSystem-JournalInterval.i.dfy.Impl__JournalIntervals.__default.Disk__Journal__Read2.smt2  |   0.334s  |   0.334s  |   0.000s  | 0.0%|
|d_lvbkv-BlockCacheSystem-JournalInterval.i.dfy.Impl__JournalIntervals.__default.concatFoldAdditive.smt2  |   0.421s  |   0.421s  |   0.000s  | 0.0%|
|d_lvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.NextStepPreservesInv.smt2  |   2.189s  |   2.189s  |   0.000s  | 0.0%|
|d_lvbkv-ByteBlockCacheSystem-ByteSystem_Refines_BetreeJournalSystem.i.dfy.Impl__ByteSystem__Refines__BetreeJournalSystem.__default.RefinesNext.smt2  |  14.278s  |  14.278s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-BookkeepingModel.i.dfy.Impl__BookkeepingModel.__default.allocCorrect.smt2      |  26.825s  |  26.825s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-BookkeepingModel.i.dfy.Impl__BookkeepingModel.__default.writeCorrect.smt2      |  13.251s  |  13.251s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-CommitterImpl.i.dfy.Impl__CommitterImpl.Committer.FinishLoadingOtherPhase.smt2  |   3.023s  |   3.023s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-CoordinationImpl.i.dfy.Impl__CoordinationImpl.__default.succ.smt2              |  30.747s  |  30.747s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.writeNodeResponse.smt2                     |  13.744s  |  13.744s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-InsertImpl.i.dfy.Impl__InsertImpl.__default.insert.smt2                        |   6.714s  |   6.714s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-JournalistImpl.i.dfy.Impl__JournalistImpl.Journalist.freeze.smt2               |   0.858s  |   0.858s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-JournalistImpl.i.dfy.Impl__JournalistImpl.Journalist.packageInMemoryJournal.smt2  |   0.534s  |   0.534s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-JournalistImpl.i.dfy.Impl__JournalistImpl.Journalist.parseJournals.smt2        |   0.651s  |   0.651s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.parsesFromStuff.smt2  |   0.412s  |   0.412s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.nodeToVal.smt2           |  10.503s  |  10.503s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-NodeImpl.i.dfy.Impl__NodeImpl.Node.UpdateSlot.smt2                             |   1.309s  |   1.309s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-SyncImpl.i.dfy.Impl__SyncImpl.__default.TryToWriteBlock.smt2                   |  34.584s  |  34.584s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-SyncImpl.i.dfy.Impl__SyncImpl.__default.sync.smt2                              |  45.621s  |  45.621s  |   0.000s  | 0.0%|
|d_lvbkv-MapSpec-TSJ.i.dfy.Impl__TSJ.__default.ExtendLog2StepPreservesInv.smt2               |   0.625s  |   0.625s  |   0.000s  | 0.0%|
|d_lvbkv-MapSpec-TSJMap_Refines_ThreeStateVersionedMap.i.dfy.Impl__TSJMap__Refines__ThreeStateVersionedMap.__default.RefinesMove3.smt2  |   0.403s  |   0.403s  |   0.000s  | 0.0%|
|d_lvbkv-MapSpec-TSJMap_Refines_ThreeStateVersionedMap.i.dfy.Impl__TSJMap__Refines__ThreeStateVersionedMap.__default.RefinesStutter.smt2  |   0.701s  |   0.701s  |   0.000s  | 0.0%|
|d_lvbkv-MapSpec-TSJMap_Refines_ThreeStateVersionedMap.i.dfy.Impl__TSJMap__Refines__ThreeStateVersionedMap.__default.apply__eq__apply__uiops.smt2  |   0.337s  |   0.337s  |   0.000s  | 0.0%|
|d_lvbkv-PivotBetree-PivotBetree.i.dfy.Impl__PivotBetree.__default.StutterStepRefines.smt2   |   1.673s  |   1.673s  |   0.000s  | 0.0%|
|d_lvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.Impl__PivotBetreeSpecRefinement.__default.RefinesLookup.smt2  |  10.282s  |  10.282s  |   0.000s  | 0.0%|
|d_lvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.Impl__PivotBetreeSpecRefinement.__default.RefinesValidFlush.smt2  |  11.405s  |  11.405s  |   0.000s  | 0.0%|
|d_lvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.Impl__PivotBetreeSpecRefinement.__default.SplitRouteNewChild.smt2  |   5.328s  |   5.328s  |   0.000s  | 0.0%|
|d_lvbkv-PivotBetree-PivotBetreeSpecWFNodes.i.dfy.Impl__PivotBetreeSpecWFNodes.__default.WFApplyRepivot.smt2  |   0.738s  |   0.738s  |   0.000s  | 0.0%|
|d_lvbkv-PivotBetree-TSJPivotBetree.i.dfy.Impl__TSJPivotBetree.__default.NextStepPreservesInv.smt2  |   0.952s  |   0.952s  |   0.000s  | 0.0%|
|d_lvbkv-Versions-CompositeView.i.dfy.Impl__CompositeView.__default.AdvancePreservesInv.smt2  |   0.698s  |   0.698s  |   0.000s  | 0.0%|
|d_lvbkv-Versions-CompositeView.i.dfy.Impl__CompositeView.__default.FreezePreservesInv.smt2  |   0.500s  |   0.500s  |   0.000s  | 0.0%|
|d_lvbkv-Versions-CompositeView_Refines_TSJMap.i.dfy.Impl__CompositeView__Refines__TSJMap.__default.JournalInternalRefines.smt2  |   1.168s  |   1.168s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-Multisets.i.dfy.Impl__Multisets.__default.ApplySeq.smt2                    |   2.231s  |   2.231s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-Multisets.i.dfy.Impl__Multisets.__default.FoldAdditive.smt2                |  13.516s  |  13.516s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-Sequences.i.dfy.CheckWellformed__Sequences.__default.RemoveOneValue.smt2   |   0.286s  |   0.286s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-Sequences.i.dfy.Impl__Sequences.__default.UnflattenIndexIsCorrect.smt2     |   0.206s  |   0.206s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-total_order.i.dfy.Impl__Total__Order.__default.FlattenStrictlySorted.smt2  |   0.484s  |   0.484s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-total_order.i.dfy.Impl__Total__Order.__default.strictlySortedInsert.smt2   |   1.743s  |   1.743s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.GetMiddleKey.smt2           |   0.888s  |   0.888s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.WeightKeyListFlatten.smt2  |   0.604s  |   0.604s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.WeightSplitBucketInList.smt2  |   0.838s  |   0.838s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-BucketsLib.i.dfy.Impl__BucketsLib.__default.WFProperMergeBucketsInList.smt2  |  17.589s  |  17.589s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-BucketsLib.i.dfy.Impl__BucketsLib.__default.WFSplitBucketInList.smt2    |   0.534s  |   0.534s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-LKMBPKVOps.i.dfy.Impl__LKMBPKVOps.__default.IMessagesInverse.smt2       |   0.792s  |   0.792s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-LKMBPKVOps.i.dfy.Impl__LKMBPKVOps.__default.LeafFillDpkv.smt2           |   9.270s  |   9.270s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-LKMBPKVOps.i.dfy.Impl__LKMBPKVOps.__default.ToPkv.smt2                  |   1.190s  |   1.190s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-LKMBPKVOps.i.dfy.Impl__LKMBPKVOps.__default.canAppendKeysIterate.smt2   |   1.557s  |   1.557s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-LKMBPKVOps.i.dfy.Impl__LKMBPKVOps.__default.canAppendMessagesIterate.smt2  |   2.011s  |   2.011s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.CheckWellformed__DynamicPkv.__default.PKVISeq.smt2       |   0.753s  |   0.753s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.CheckWellformed__PackedKV.__default.LastKey.smt2         |   0.557s  |   0.557s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.__default.MergeToChildren.smt2          |   2.528s  |   2.528s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.__default.PartialFlush.smt2             |   1.472s  |   1.472s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.DefineIMessage.smt2             |   0.554s  |   0.554s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.SplitRight.smt2                 |   0.932s  |   0.932s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.psaTotalLengthBound.smt2        |   0.621s  |   0.621s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedStringArray.i.dfy.CheckWellformed__PackedStringArray.__default.psaAppendSeq.smt2  |   0.689s  |   0.689s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.DynamicPsa.FromSeq.smt2  |   0.549s  |   0.549s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.PsaSuffix.smt2  |   0.368s  |   0.368s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Checksums-CRC32CArrayImpl.i.dfy.Impl__CRC32__C__Array__Impl.__default.advanced__of__iterated__intrinsic.smt2  |   0.306s  |   0.306s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Checksums-CRC32CImpl.i.dfy.Impl__CRC32__C__Impl.__default.advanced__of__iterated__intrinsic.smt2  |   0.265s  |   0.265s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Checksums-CRC32C_Lemmas.i.dfy.Impl__CRC32C__Lemmas.__default.advances__bytes__refl.smt2  |   0.244s  |   0.244s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Checksums-F2_X_Lemmas.i.dfy.Impl__F2__X__Lemmas.__default.p__qr__partial.smt2   |  22.019s  |  22.019s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Checksums-F2_X_Lemmas.i.dfy.Impl__F2__X__Lemmas.__default.pq__r__partial.smt2   |   4.322s  |   4.322s  |   0.000s  | 0.0%|
|d_lvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.InterpretationDelegation.smt2  |   0.381s  |   0.381s  |   0.000s  | 0.0%|
|d_lvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.InterpretationInheritance.smt2  |   0.339s  |   0.339s  |   0.000s  | 0.0%|
|d_lvbkv-lib-DataStructures-KMBtree.i.dfy.Impl__KMBtreeModel.__default.InterpretationDelegation.smt2  |   0.387s  |   0.387s  |   0.000s  | 0.0%|
|d_lvbkv-lib-DataStructures-KMBtree.i.dfy.Impl__KMBtreeModel.__default.InterpretationInheritance.smt2  |   5.799s  |   5.799s  |   0.000s  | 0.0%|
|d_lvbkv-lib-DataStructures-KMBtree.i.dfy.Impl__KMBtreeModel.__default.InterpretationsDisjointUnion.smt2  |   0.710s  |   0.710s  |   0.000s  | 0.0%|
|d_lvbkv-lib-DataStructures-KMBtree.i.dfy.Impl__LKMBtree.__default.InsertLeaf.smt2           |   1.773s  |   1.773s  |   0.000s  | 0.0%|
|d_lvbkv-lib-DataStructures-LinearContentMutableMap.i.dfy.Impl__LinearContentMutableMap.__default.FixedSizeInsertEntry.smt2  |  36.314s  |  36.314s  |   0.000s  | 0.0%|
|d_lvbkv-lib-DataStructures-LinearMutableMap.i.dfy.Impl__LinearMutableMap.__default.UpdateByIter.smt2  |  41.380s  |  41.380s  |   0.000s  | 0.0%|
|d_lvbkv-lib-DataStructures-MutableMapModel.i.dfy.Impl__MutableMapModel.__default.IndexSetMatchesContents.smt2  |  21.423s  |  21.423s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.lemma__parse__Val__view__ByteArray.smt2  |   0.393s  |   0.393s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Marshalling-Util.i.dfy.Impl__Common____Util__i.__default.seqIntoArrayChar.smt2  |   0.235s  |   0.235s  |   0.000s  | 0.0%|
|s_komodo-1435.3.smt2                                                                        |   5.924s  |   5.924s  |   0.000s  | 0.0%|
</details>
