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
Job tag: gen-patch-mariposa-se
Runner: rise-runner-1
Z3 repo: CanCebeci/z3
Z3 commit: aec453eb9bad24f44f4f6101b46004389bd16bb0
Z3 branch: master
Z3 options: "%OPTIONS2%"
Z3 inputs: inputs/mariposa/stable_ext
Z3 commit message: Enforce stickiness of max-generation

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: gen-patch-mariposa-se
Runner: rise-runner-1
Z3 repo: CanCebeci/z3
Z3 commit: aec453eb9bad24f44f4f6101b46004389bd16bb0
Z3 branch: master
Z3 options: "%OPTIONS2%"
Z3 inputs: inputs/mariposa/stable_ext
Z3 commit message: Enforce stickiness of max-generation

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectResultingGraphAfterAllocs.smt2  |   1.989s  |   1.989s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeCache.i.dfy.Impl__BetreeCache.__default.BetreeMoveStepPreservesInv.smt2  |   2.672s  |   2.672s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeSystem_Refines_StatesViewPivotBetree.i.dfy.Impl__BetreeSystem__Refines__StatesViewPivotBetree.__default.BetreeMoveStepRefines.smt2  |   9.647s  |   9.647s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ProcessWritePreservesInv.smt2  |   7.320s  |   7.320s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesReqWriteOp.smt2  |   8.697s  |   8.697s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenCompose.smt2  |  25.454s  |  25.454s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenFromBucketStackWithLowerBound.smt2  |   2.203s  |   2.203s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterInitImpl.i.dfy.Impl__CommitterInitImpl.__default.FinishLoadingOtherPhase.smt2  |   8.061s  |   8.061s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-EvictImpl.i.dfy.Impl__EvictImpl.__default.Evict.smt2                           |   5.216s  |   5.216s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-HandleReadResponseImpl.i.dfy.Impl__HandleReadResponseImpl.__default.readResponse.smt2  |  26.724s  |  26.724s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.writeNodeResponse.smt2                     |  12.036s  |  12.036s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.InitLocBitmap.smt2  |   5.364s  |   5.364s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.ValToIndirectionTable.smt2  |  23.753s  |  23.753s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.CheckWellformed__IndirectionTableModel.__default.RemoveRef.smt2  |   2.705s  |   2.705s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.Impl__IndirectionTableModel.__default.LemmaComputeRefCountsEntryIterateCorrectPartial.smt2  |   2.612s  |   2.612s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.fillInChecksumsPreserves.smt2  |   2.855s  |   2.855s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.writeOntoResult.smt2  |  12.054s  |  12.054s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.parseJournals.smt2  |   0.758s  |   0.758s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.ValToBuckets.smt2        |   8.278s  |   8.278s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.bucketToVal.smt2         |   1.927s  |   1.927s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectResultingGraphAfterAllocs.smt2  |   1.989s  |   1.989s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeCache.i.dfy.Impl__BetreeCache.__default.BetreeMoveStepPreservesInv.smt2  |   2.672s  |   2.672s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeSystem_Refines_StatesViewPivotBetree.i.dfy.Impl__BetreeSystem__Refines__StatesViewPivotBetree.__default.BetreeMoveStepRefines.smt2  |   9.647s  |   9.647s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ProcessWritePreservesInv.smt2  |   7.320s  |   7.320s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesReqWriteOp.smt2  |   8.697s  |   8.697s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenCompose.smt2  |  25.454s  |  25.454s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenFromBucketStackWithLowerBound.smt2  |   2.203s  |   2.203s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterInitImpl.i.dfy.Impl__CommitterInitImpl.__default.FinishLoadingOtherPhase.smt2  |   8.061s  |   8.061s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-EvictImpl.i.dfy.Impl__EvictImpl.__default.Evict.smt2                           |   5.216s  |   5.216s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-HandleReadResponseImpl.i.dfy.Impl__HandleReadResponseImpl.__default.readResponse.smt2  |  26.724s  |  26.724s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.writeNodeResponse.smt2                     |  12.036s  |  12.036s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.InitLocBitmap.smt2  |   5.364s  |   5.364s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.ValToIndirectionTable.smt2  |  23.753s  |  23.753s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.CheckWellformed__IndirectionTableModel.__default.RemoveRef.smt2  |   2.705s  |   2.705s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.Impl__IndirectionTableModel.__default.LemmaComputeRefCountsEntryIterateCorrectPartial.smt2  |   2.612s  |   2.612s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.fillInChecksumsPreserves.smt2  |   2.855s  |   2.855s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.writeOntoResult.smt2  |  12.054s  |  12.054s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.parseJournals.smt2  |   0.758s  |   0.758s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.ValToBuckets.smt2        |   8.278s  |   8.278s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.bucketToVal.smt2         |   1.927s  |   1.927s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectResultingGraphAfterAllocs.smt2  |   1.989s  |   1.989s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeCache.i.dfy.Impl__BetreeCache.__default.BetreeMoveStepPreservesInv.smt2  |   2.672s  |   2.672s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeSystem_Refines_StatesViewPivotBetree.i.dfy.Impl__BetreeSystem__Refines__StatesViewPivotBetree.__default.BetreeMoveStepRefines.smt2  |   9.647s  |   9.647s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ProcessWritePreservesInv.smt2  |   7.320s  |   7.320s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesReqWriteOp.smt2  |   8.697s  |   8.697s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenCompose.smt2  |  25.454s  |  25.454s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenFromBucketStackWithLowerBound.smt2  |   2.203s  |   2.203s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterInitImpl.i.dfy.Impl__CommitterInitImpl.__default.FinishLoadingOtherPhase.smt2  |   8.061s  |   8.061s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-EvictImpl.i.dfy.Impl__EvictImpl.__default.Evict.smt2                           |   5.216s  |   5.216s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-HandleReadResponseImpl.i.dfy.Impl__HandleReadResponseImpl.__default.readResponse.smt2  |  26.724s  |  26.724s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.writeNodeResponse.smt2                     |  12.036s  |  12.036s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.InitLocBitmap.smt2  |   5.364s  |   5.364s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.ValToIndirectionTable.smt2  |  23.753s  |  23.753s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.CheckWellformed__IndirectionTableModel.__default.RemoveRef.smt2  |   2.705s  |   2.705s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.Impl__IndirectionTableModel.__default.LemmaComputeRefCountsEntryIterateCorrectPartial.smt2  |   2.612s  |   2.612s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.fillInChecksumsPreserves.smt2  |   2.855s  |   2.855s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.writeOntoResult.smt2  |  12.054s  |  12.054s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.parseJournals.smt2  |   0.758s  |   0.758s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.ValToBuckets.smt2        |   8.278s  |   8.278s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.bucketToVal.smt2         |   1.927s  |   1.927s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectResultingGraphAfterAllocs.smt2  |   1.989s  |   1.989s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeCache.i.dfy.Impl__BetreeCache.__default.BetreeMoveStepPreservesInv.smt2  |   2.672s  |   2.672s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeSystem_Refines_StatesViewPivotBetree.i.dfy.Impl__BetreeSystem__Refines__StatesViewPivotBetree.__default.BetreeMoveStepRefines.smt2  |   9.647s  |   9.647s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ProcessWritePreservesInv.smt2  |   7.320s  |   7.320s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesReqWriteOp.smt2  |   8.697s  |   8.697s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenCompose.smt2  |  25.454s  |  25.454s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenFromBucketStackWithLowerBound.smt2  |   2.203s  |   2.203s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterInitImpl.i.dfy.Impl__CommitterInitImpl.__default.FinishLoadingOtherPhase.smt2  |   8.061s  |   8.061s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-EvictImpl.i.dfy.Impl__EvictImpl.__default.Evict.smt2                           |   5.216s  |   5.216s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-HandleReadResponseImpl.i.dfy.Impl__HandleReadResponseImpl.__default.readResponse.smt2  |  26.724s  |  26.724s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.writeNodeResponse.smt2                     |  12.036s  |  12.036s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.InitLocBitmap.smt2  |   5.364s  |   5.364s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.ValToIndirectionTable.smt2  |  23.753s  |  23.753s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.CheckWellformed__IndirectionTableModel.__default.RemoveRef.smt2  |   2.705s  |   2.705s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.Impl__IndirectionTableModel.__default.LemmaComputeRefCountsEntryIterateCorrectPartial.smt2  |   2.612s  |   2.612s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.fillInChecksumsPreserves.smt2  |   2.855s  |   2.855s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.writeOntoResult.smt2  |  12.054s  |  12.054s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.parseJournals.smt2  |   0.758s  |   0.758s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.ValToBuckets.smt2        |   8.278s  |   8.278s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.bucketToVal.smt2         |   1.927s  |   1.927s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|s_komodo-1488.6.smt2                                                                       |  81.713s |25.108GiB|
|s_komodo-1504.6.smt2                                                                       |  81.523s |24.143GiB|
|s_komodo-1499.6.smt2                                                                       |  81.523s |24.504GiB|
|s_komodo-1509.6.smt2                                                                       |  81.096s |16.263GiB|
|s_komodo-1493.6.smt2                                                                       |  81.064s |16.006GiB|
|s_komodo-1499.4.smt2                                                                       |  80.248s |4024.0MiB|
|s_komodo-1450.0.smt2                                                                       |  80.160s |2935.0MiB|
|s_komodo-1551.3.smt2                                                                       |  65.472s |125.0MiB|
|d_komodo-verified-entry.gen.dfyImpl___module.__default.va__lemma__enclaveexecution__loop.smt2 |  49.961s |190.0MiB|
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.WriteBackNodeRespStepPreservesGraphs.smt2 |  47.674s |354.0MiB|
|d_fvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.SplitIndexInterpretation1.smt2 |  47.285s |127.0MiB|
|d_lvbkv-Impl-SyncImpl.i.dfy.Impl__SyncImpl.__default.sync.smt2                             |  46.917s |231.0MiB|
|d_lvbkv-lib-DataStructures-LinearMutableMap.i.dfy.Impl__LinearMutableMap.__default.UpdateByIter.smt2 |  41.547s |123.0MiB|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SplitIndex.smt2 |  39.535s |190.0MiB|
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.AllocStepPreservesInv.smt2 |  38.576s |339.0MiB|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__svcHandled__conf__not__atkr.smt2 |  36.727s |207.0MiB|
|d_komodo-verified-kom_utils.gen.dfyImpl___module.__default.va__abstract__load__32__bit__const.smt2 |  36.689s |102.0MiB|
|d_lvbkv-lib-DataStructures-LinearContentMutableMap.i.dfy.Impl__LinearContentMutableMap.__default.FixedSizeInsertEntry.smt2 |  35.778s |119.0MiB|
|d_komodo-verified-exception_handlers.gen.dfyImpl___module.__default.va__lemma__CPSID__IAF.smt2 |  35.714s |211.0MiB|
|d_komodo-verified-attest_helpers.gen.dfyCheckWellformed___module.__default.va__lemma__load__attestion__key__inner.smt2 |  35.479s |275.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|s_komodo-1488.6.smt2                                                                       |  81.713s |25.108GiB|
|s_komodo-1504.6.smt2                                                                       |  81.523s |24.143GiB|
|s_komodo-1499.6.smt2                                                                       |  81.523s |24.504GiB|
|s_komodo-1509.6.smt2                                                                       |  81.096s |16.263GiB|
|s_komodo-1493.6.smt2                                                                       |  81.064s |16.006GiB|
|s_komodo-1499.4.smt2                                                                       |  80.248s |4024.0MiB|
|s_komodo-1450.0.smt2                                                                       |  80.160s |2935.0MiB|
|s_komodo-1551.3.smt2                                                                       |  65.472s |125.0MiB|
|d_komodo-verified-entry.gen.dfyImpl___module.__default.va__lemma__enclaveexecution__loop.smt2 |  49.961s |190.0MiB|
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.WriteBackNodeRespStepPreservesGraphs.smt2 |  47.674s |354.0MiB|
|d_fvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.SplitIndexInterpretation1.smt2 |  47.285s |127.0MiB|
|d_lvbkv-Impl-SyncImpl.i.dfy.Impl__SyncImpl.__default.sync.smt2                             |  46.917s |231.0MiB|
|d_lvbkv-lib-DataStructures-LinearMutableMap.i.dfy.Impl__LinearMutableMap.__default.UpdateByIter.smt2 |  41.547s |123.0MiB|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SplitIndex.smt2 |  39.535s |190.0MiB|
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.AllocStepPreservesInv.smt2 |  38.576s |339.0MiB|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__svcHandled__conf__not__atkr.smt2 |  36.727s |207.0MiB|
|d_komodo-verified-kom_utils.gen.dfyImpl___module.__default.va__abstract__load__32__bit__const.smt2 |  36.689s |102.0MiB|
|d_lvbkv-lib-DataStructures-LinearContentMutableMap.i.dfy.Impl__LinearContentMutableMap.__default.FixedSizeInsertEntry.smt2 |  35.778s |119.0MiB|
|d_komodo-verified-exception_handlers.gen.dfyImpl___module.__default.va__lemma__CPSID__IAF.smt2 |  35.714s |211.0MiB|
|d_komodo-verified-attest_helpers.gen.dfyCheckWellformed___module.__default.va__lemma__load__attestion__key__inner.smt2 |  35.479s |275.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectResultingGraphAfterAllocs.smt2  |53.476MiB|53.476MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeCache.i.dfy.Impl__BetreeCache.__default.BetreeMoveStepPreservesInv.smt2  |94.66MiB|94.66MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeSystem_Refines_StatesViewPivotBetree.i.dfy.Impl__BetreeSystem__Refines__StatesViewPivotBetree.__default.BetreeMoveStepRefines.smt2  |115.0MiB|115.0MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ProcessWritePreservesInv.smt2  |171.0MiB|171.0MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesReqWriteOp.smt2  |173.0MiB|173.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenCompose.smt2  |170.0MiB|170.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenFromBucketStackWithLowerBound.smt2  |96.088MiB|96.088MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterInitImpl.i.dfy.Impl__CommitterInitImpl.__default.FinishLoadingOtherPhase.smt2  |168.0MiB|168.0MiB|0B| 0.0%|
|d_fvbkv-Impl-EvictImpl.i.dfy.Impl__EvictImpl.__default.Evict.smt2                           |168.0MiB|168.0MiB|0B| 0.0%|
|d_fvbkv-Impl-HandleReadResponseImpl.i.dfy.Impl__HandleReadResponseImpl.__default.readResponse.smt2  |181.0MiB|181.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.writeNodeResponse.smt2                     |170.0MiB|170.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.InitLocBitmap.smt2  |105.0MiB|105.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.ValToIndirectionTable.smt2  |183.0MiB|183.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.CheckWellformed__IndirectionTableModel.__default.RemoveRef.smt2  |99.48MiB|99.48MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.Impl__IndirectionTableModel.__default.LemmaComputeRefCountsEntryIterateCorrectPartial.smt2  |99.152MiB|99.152MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.fillInChecksumsPreserves.smt2  |67.644MiB|67.644MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.writeOntoResult.smt2  |175.0MiB|175.0MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.parseJournals.smt2  |39.94MiB|39.94MiB|0B| 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.ValToBuckets.smt2        |167.0MiB|167.0MiB|0B| 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.bucketToVal.smt2         |99.0MiB|99.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectResultingGraphAfterAllocs.smt2  |53.476MiB|53.476MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeCache.i.dfy.Impl__BetreeCache.__default.BetreeMoveStepPreservesInv.smt2  |94.66MiB|94.66MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeSystem_Refines_StatesViewPivotBetree.i.dfy.Impl__BetreeSystem__Refines__StatesViewPivotBetree.__default.BetreeMoveStepRefines.smt2  |115.0MiB|115.0MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ProcessWritePreservesInv.smt2  |171.0MiB|171.0MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesReqWriteOp.smt2  |173.0MiB|173.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenCompose.smt2  |170.0MiB|170.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenFromBucketStackWithLowerBound.smt2  |96.088MiB|96.088MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterInitImpl.i.dfy.Impl__CommitterInitImpl.__default.FinishLoadingOtherPhase.smt2  |168.0MiB|168.0MiB|0B| 0.0%|
|d_fvbkv-Impl-EvictImpl.i.dfy.Impl__EvictImpl.__default.Evict.smt2                           |168.0MiB|168.0MiB|0B| 0.0%|
|d_fvbkv-Impl-HandleReadResponseImpl.i.dfy.Impl__HandleReadResponseImpl.__default.readResponse.smt2  |181.0MiB|181.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.writeNodeResponse.smt2                     |170.0MiB|170.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.InitLocBitmap.smt2  |105.0MiB|105.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.ValToIndirectionTable.smt2  |183.0MiB|183.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.CheckWellformed__IndirectionTableModel.__default.RemoveRef.smt2  |99.48MiB|99.48MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.Impl__IndirectionTableModel.__default.LemmaComputeRefCountsEntryIterateCorrectPartial.smt2  |99.152MiB|99.152MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.fillInChecksumsPreserves.smt2  |67.644MiB|67.644MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.writeOntoResult.smt2  |175.0MiB|175.0MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.parseJournals.smt2  |39.94MiB|39.94MiB|0B| 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.ValToBuckets.smt2        |167.0MiB|167.0MiB|0B| 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.bucketToVal.smt2         |99.0MiB|99.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectResultingGraphAfterAllocs.smt2  |53.476MiB|53.476MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeCache.i.dfy.Impl__BetreeCache.__default.BetreeMoveStepPreservesInv.smt2  |94.66MiB|94.66MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeSystem_Refines_StatesViewPivotBetree.i.dfy.Impl__BetreeSystem__Refines__StatesViewPivotBetree.__default.BetreeMoveStepRefines.smt2  |115.0MiB|115.0MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ProcessWritePreservesInv.smt2  |171.0MiB|171.0MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesReqWriteOp.smt2  |173.0MiB|173.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenCompose.smt2  |170.0MiB|170.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenFromBucketStackWithLowerBound.smt2  |96.088MiB|96.088MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterInitImpl.i.dfy.Impl__CommitterInitImpl.__default.FinishLoadingOtherPhase.smt2  |168.0MiB|168.0MiB|0B| 0.0%|
|d_fvbkv-Impl-EvictImpl.i.dfy.Impl__EvictImpl.__default.Evict.smt2                           |168.0MiB|168.0MiB|0B| 0.0%|
|d_fvbkv-Impl-HandleReadResponseImpl.i.dfy.Impl__HandleReadResponseImpl.__default.readResponse.smt2  |181.0MiB|181.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.writeNodeResponse.smt2                     |170.0MiB|170.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.InitLocBitmap.smt2  |105.0MiB|105.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.ValToIndirectionTable.smt2  |183.0MiB|183.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.CheckWellformed__IndirectionTableModel.__default.RemoveRef.smt2  |99.48MiB|99.48MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.Impl__IndirectionTableModel.__default.LemmaComputeRefCountsEntryIterateCorrectPartial.smt2  |99.152MiB|99.152MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.fillInChecksumsPreserves.smt2  |67.644MiB|67.644MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.writeOntoResult.smt2  |175.0MiB|175.0MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.parseJournals.smt2  |39.94MiB|39.94MiB|0B| 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.ValToBuckets.smt2        |167.0MiB|167.0MiB|0B| 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.bucketToVal.smt2         |99.0MiB|99.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectResultingGraphAfterAllocs.smt2  |53.476MiB|53.476MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeCache.i.dfy.Impl__BetreeCache.__default.BetreeMoveStepPreservesInv.smt2  |94.66MiB|94.66MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeSystem_Refines_StatesViewPivotBetree.i.dfy.Impl__BetreeSystem__Refines__StatesViewPivotBetree.__default.BetreeMoveStepRefines.smt2  |115.0MiB|115.0MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ProcessWritePreservesInv.smt2  |171.0MiB|171.0MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesReqWriteOp.smt2  |173.0MiB|173.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenCompose.smt2  |170.0MiB|170.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenFromBucketStackWithLowerBound.smt2  |96.088MiB|96.088MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterInitImpl.i.dfy.Impl__CommitterInitImpl.__default.FinishLoadingOtherPhase.smt2  |168.0MiB|168.0MiB|0B| 0.0%|
|d_fvbkv-Impl-EvictImpl.i.dfy.Impl__EvictImpl.__default.Evict.smt2                           |168.0MiB|168.0MiB|0B| 0.0%|
|d_fvbkv-Impl-HandleReadResponseImpl.i.dfy.Impl__HandleReadResponseImpl.__default.readResponse.smt2  |181.0MiB|181.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.writeNodeResponse.smt2                     |170.0MiB|170.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.InitLocBitmap.smt2  |105.0MiB|105.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.ValToIndirectionTable.smt2  |183.0MiB|183.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.CheckWellformed__IndirectionTableModel.__default.RemoveRef.smt2  |99.48MiB|99.48MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.Impl__IndirectionTableModel.__default.LemmaComputeRefCountsEntryIterateCorrectPartial.smt2  |99.152MiB|99.152MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.fillInChecksumsPreserves.smt2  |67.644MiB|67.644MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.writeOntoResult.smt2  |175.0MiB|175.0MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.parseJournals.smt2  |39.94MiB|39.94MiB|0B| 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.ValToBuckets.smt2        |167.0MiB|167.0MiB|0B| 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.bucketToVal.smt2         |99.0MiB|99.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|s_komodo-1488.6.smt2                                                                       |  81.713s |25.108GiB|
|s_komodo-1499.6.smt2                                                                       |  81.523s |24.504GiB|
|s_komodo-1504.6.smt2                                                                       |  81.523s |24.143GiB|
|s_komodo-1509.6.smt2                                                                       |  81.096s |16.263GiB|
|s_komodo-1493.6.smt2                                                                       |  81.064s |16.006GiB|
|s_komodo-1499.4.smt2                                                                       |  80.248s |4024.0MiB|
|s_komodo-1450.0.smt2                                                                       |  80.160s |2935.0MiB|
|d_lvbkv-ByteBlockCacheSystem-ByteSystem_Refines_BetreeJournalSystem.i.dfy.Impl__ByteSystem__Refines__BetreeJournalSystem.__default.RefinesNext.smt2 |  14.083s |402.0MiB|
|d_komodo-verified-secprop-conf_ni.i.dfyImpl___module.__default.lemma__mapSecure__loweq__pdb__success.smt2 |  33.649s |358.0MiB|
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.WriteBackNodeRespStepPreservesGraphs.smt2 |  47.674s |354.0MiB|
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.AllocStepPreservesInv.smt2 |  38.576s |339.0MiB|
|d_komodo-verified-attest_helpers.gen.dfyCheckWellformed___module.__default.va__lemma__load__attestion__key__inner.smt2 |  35.479s |275.0MiB|
|d_komodo-verified-attest_helpers.gen.dfyImpl___module.__default.va__lemma__unstack__all__regs.smt2 |  26.370s |237.0MiB|
|d_lvbkv-Impl-SyncImpl.i.dfy.Impl__SyncImpl.__default.sync.smt2                             |  46.917s |231.0MiB|
|d_lvbkv-Impl-CoordinationImpl.i.dfy.Impl__CoordinationImpl.__default.succ.smt2             |  31.822s |229.0MiB|
|d_komodo-verified-sha-hmac.gen.dfyImpl___module.__default.va__lemma__hmac__outer.smt2      |  29.594s |228.0MiB|
|d_lvbkv-Impl-SyncImpl.i.dfy.Impl__SyncImpl.__default.TryToWriteBlock.smt2                  |  34.325s |226.0MiB|
|d_komodo-verified-svc_handlers.gen.dfyImpl___module.__default.va__lemma__rng__read.smt2    |  26.704s |223.0MiB|
|d_lvbkv-BlockCacheSystem-BetreeJournalSystem_Refines_ThreeStateVersionedMap.i.dfy.Impl__BetreeJournalSystem__Refines__ThreeStateVersionedMap.__default.RefinesNext.smt2 |   3.085s |217.0MiB|
|d_komodo-verified-exception_handlers.gen.dfyImpl___module.__default.va__lemma__CPSID__IAF.smt2 |  35.714s |211.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|s_komodo-1488.6.smt2                                                                       |  81.713s |25.108GiB|
|s_komodo-1499.6.smt2                                                                       |  81.523s |24.504GiB|
|s_komodo-1504.6.smt2                                                                       |  81.523s |24.143GiB|
|s_komodo-1509.6.smt2                                                                       |  81.096s |16.263GiB|
|s_komodo-1493.6.smt2                                                                       |  81.064s |16.006GiB|
|s_komodo-1499.4.smt2                                                                       |  80.248s |4024.0MiB|
|s_komodo-1450.0.smt2                                                                       |  80.160s |2935.0MiB|
|d_lvbkv-ByteBlockCacheSystem-ByteSystem_Refines_BetreeJournalSystem.i.dfy.Impl__ByteSystem__Refines__BetreeJournalSystem.__default.RefinesNext.smt2 |  14.083s |402.0MiB|
|d_komodo-verified-secprop-conf_ni.i.dfyImpl___module.__default.lemma__mapSecure__loweq__pdb__success.smt2 |  33.649s |358.0MiB|
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.WriteBackNodeRespStepPreservesGraphs.smt2 |  47.674s |354.0MiB|
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.AllocStepPreservesInv.smt2 |  38.576s |339.0MiB|
|d_komodo-verified-attest_helpers.gen.dfyCheckWellformed___module.__default.va__lemma__load__attestion__key__inner.smt2 |  35.479s |275.0MiB|
|d_komodo-verified-attest_helpers.gen.dfyImpl___module.__default.va__lemma__unstack__all__regs.smt2 |  26.370s |237.0MiB|
|d_lvbkv-Impl-SyncImpl.i.dfy.Impl__SyncImpl.__default.sync.smt2                             |  46.917s |231.0MiB|
|d_lvbkv-Impl-CoordinationImpl.i.dfy.Impl__CoordinationImpl.__default.succ.smt2             |  31.822s |229.0MiB|
|d_komodo-verified-sha-hmac.gen.dfyImpl___module.__default.va__lemma__hmac__outer.smt2      |  29.594s |228.0MiB|
|d_lvbkv-Impl-SyncImpl.i.dfy.Impl__SyncImpl.__default.TryToWriteBlock.smt2                  |  34.325s |226.0MiB|
|d_komodo-verified-svc_handlers.gen.dfyImpl___module.__default.va__lemma__rng__read.smt2    |  26.704s |223.0MiB|
|d_lvbkv-BlockCacheSystem-BetreeJournalSystem_Refines_ThreeStateVersionedMap.i.dfy.Impl__BetreeJournalSystem__Refines__ThreeStateVersionedMap.__default.RefinesNext.smt2 |   3.085s |217.0MiB|
|d_komodo-verified-exception_handlers.gen.dfyImpl___module.__default.va__lemma__CPSID__IAF.smt2 |  35.714s |211.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectResultingGraphAfterAllocs.smt2  |   1.989s  |   1.989s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeCache.i.dfy.Impl__BetreeCache.__default.BetreeMoveStepPreservesInv.smt2  |   2.672s  |   2.672s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeSystem_Refines_StatesViewPivotBetree.i.dfy.Impl__BetreeSystem__Refines__StatesViewPivotBetree.__default.BetreeMoveStepRefines.smt2  |   9.647s  |   9.647s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ProcessWritePreservesInv.smt2  |   7.320s  |   7.320s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesReqWriteOp.smt2  |   8.697s  |   8.697s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenCompose.smt2  |  25.454s  |  25.454s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenFromBucketStackWithLowerBound.smt2  |   2.203s  |   2.203s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterInitImpl.i.dfy.Impl__CommitterInitImpl.__default.FinishLoadingOtherPhase.smt2  |   8.061s  |   8.061s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-EvictImpl.i.dfy.Impl__EvictImpl.__default.Evict.smt2                           |   5.216s  |   5.216s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-HandleReadResponseImpl.i.dfy.Impl__HandleReadResponseImpl.__default.readResponse.smt2  |  26.724s  |  26.724s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.writeNodeResponse.smt2                     |  12.036s  |  12.036s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.InitLocBitmap.smt2  |   5.364s  |   5.364s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.ValToIndirectionTable.smt2  |  23.753s  |  23.753s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.CheckWellformed__IndirectionTableModel.__default.RemoveRef.smt2  |   2.705s  |   2.705s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.Impl__IndirectionTableModel.__default.LemmaComputeRefCountsEntryIterateCorrectPartial.smt2  |   2.612s  |   2.612s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.fillInChecksumsPreserves.smt2  |   2.855s  |   2.855s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.writeOntoResult.smt2  |  12.054s  |  12.054s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.parseJournals.smt2  |   0.758s  |   0.758s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.ValToBuckets.smt2        |   8.278s  |   8.278s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.bucketToVal.smt2         |   1.927s  |   1.927s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.bucketsToVal.smt2        |   5.538s  |   5.538s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.nodeToVal.smt2           |  10.367s  |  10.367s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-QueryModel.i.dfy.Impl__QueryModel.__default.AugmentLookup.smt2                 |   2.684s  |   2.684s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-SplitImpl.i.dfy.Impl__SplitImpl.__default.splitBookkeeping.smt2                |  13.018s  |  13.018s  |   0.000s  | 0.0%|
|d_fvbkv-PivotBetree-PivotBetree.i.dfy.Impl__PivotBetree.__default.BetreeStepRefines.smt2    |   3.419s  |   3.419s  |   0.000s  | 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.Impl__PivotBetreeSpecRefinement.__default.CutoffNodeAndKeepRightAgree.smt2  |   0.793s  |   0.793s  |   0.000s  | 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpecWFNodes.i.dfy.Impl__PivotBetreeSpecWFNodes.__default.ValidMergeWritesInvNodes.smt2  |   2.480s  |   2.480s  |   0.000s  | 0.0%|
|d_fvbkv-Versions-CompositeView_Refines_TSJMap.i.dfy.Impl__CompositeView__Refines__TSJMap.__default.CrashRefines.smt2  |   0.593s  |   0.593s  |   0.000s  | 0.0%|
|d_fvbkv-Versions-CompositeView_Refines_TSJMap.i.dfy.Impl__CompositeView__Refines__TSJMap.__default.JournalInternalRefines.smt2  |   0.958s  |   0.958s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-Multisets.i.dfy.Impl__Multisets.__default.FoldAdditive.smt2                |   2.987s  |   2.987s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-sequences.i.dfy.Impl__Sequences.__default.FlattenAdditive.smt2             |   0.328s  |   0.328s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-sequences.i.dfy.Impl__Sequences.__default.UnflattenFlattenIdentity.smt2    |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-total_order.i.dfy.Impl__Char__Order.__default.FlattenStrictlySorted.smt2   |   0.200s  |   0.200s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-total_order.i.dfy.Impl__Total__Order.__default.FlattenStrictlySorted.smt2  |   0.318s  |   0.318s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-total_order.i.dfy.Impl__Total__Order.__default.strictlySortedInsert.smt2   |   0.348s  |   0.348s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-total_order.i.dfy.Impl__Uint32__Order.__default.FlattenStrictlySorted.smt2  |   0.209s  |   0.209s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-total_order.i.dfy.Impl__Uint64__Order.__default.FlattenStrictlySorted.smt2  |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.SplitOneInList.smt2         |   1.755s  |   1.755s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.WeightKeySeqIs.smt2         |   0.793s  |   0.793s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketModel.i.dfy.Impl__BucketModel.__default.mergeToChildrenIterSlack_split0.smt2  |   0.893s  |   0.893s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.WMWeightBucketListFlush.smt2  |   0.750s  |   0.750s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.WeightBucketListItemFlushSingletonOrEmpty.smt2  |   1.730s  |   1.730s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.WeightMessageListFlatten.smt2  |   0.528s  |   0.528s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.WeightSplitBucketInList.smt2  |   0.486s  |   0.486s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-KMBPKVOps.i.dfy.Impl__KMBPKVOps.__default.IMessagesInverse.smt2         |   0.699s  |   0.699s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-KMBPKVOps.i.dfy.Impl__KMBPKVOps.__default.ToPkv.smt2                    |  12.364s  |  12.364s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-KMBPKVOps.i.dfy.Impl__KMBPKVOps.__default.canAppendMessagesIterate.smt2  |   1.002s  |   1.002s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.CheckWellformed__DynamicPkv.__default.PKVISeq.smt2       |   0.764s  |   0.764s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.psaTotalLengthBound.smt2        |   0.569s  |   0.569s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKVMarshalling.i.dfy.Impl__PackedKVMarshalling.__default.ComputeWF.smt2  |   0.643s  |   0.643s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKVMarshalling.i.dfy.Impl__PackedKVMarshalling.__default.SizeOfVPackedStringArrayIsKeyListWeight.smt2  |   0.961s  |   0.961s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.PivotIndexes.smt2  |   0.376s  |   0.376s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.psaAppendSeqAdditive.smt2  |   0.424s  |   0.424s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-BitmapImpl.i.dfy.Impl__BitmapImpl.Bitmap.Set.smt2                |   0.195s  |   0.195s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-BitmapImpl.i.dfy.Impl__BitmapImpl.Bitmap.Unset.smt2              |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.InsertLeafIsCorrect.smt2  |   1.632s  |   1.632s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.SplitChildOfIndexPreservesInterpretationB.smt2  |   3.685s  |   3.685s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.SplitIndexInterpretation1.smt2  |  47.285s  |  47.285s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.SplitIndexInterpretation2.smt2  |   2.294s  |   2.294s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-KMBtree.i.dfy.Impl__KMBtree.__default.InsertIndexSelectAndPrepareChild.smt2  |   1.329s  |   1.329s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-KMBtree.i.dfy.Impl__KMBtree.__default.SplitIndex.smt2            |  24.122s  |  24.122s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-KMBtree.i.dfy.Impl__KMBtreeModel.__default.InterpretationsDisjointUnion.smt2  |   2.446s  |   2.446s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-KMBtree.i.dfy.Impl__KMBtreeModel.__default.SplitIndexInterpretation1.smt2  |   2.980s  |   2.980s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.InsertIndexChildNotFull.smt2  |   6.344s  |   6.344s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.InsertIndexSelectAndPrepareChild.smt2  |   2.283s  |   2.283s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SplitIndex.smt2  |  39.535s  |  39.535s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__TestBtreeModel.__default.SplitIndexInterpretation1.smt2  |   2.277s  |   2.277s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__TestMutableBtree.__default.SplitIndex.smt2  |  23.036s  |  23.036s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableMapModel.i.dfy.CheckWellformed__MutableMapModel.__default.IterInc.smt2  |   3.481s  |   3.481s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableMapModel.i.dfy.CheckWellformed__MutableMapModel.__default.iterToNext.smt2  |   0.449s  |   0.449s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableMapModel.i.dfy.Impl__MutableMapModel.__default.MapFromStorageProperties.smt2  |   0.506s  |   0.506s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableMapModel.i.dfy.Impl__MutableMapModel.__default.UpdatePreservesSimpleIter.smt2  |   1.205s  |   1.205s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.CheckWellformed__GenericMarshalling.__default.parse__Val.smt2  |   0.354s  |   0.354s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__div__ind.smt2                |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-Util.i.dfy.CheckWellformed__Common____Util__i.__default.Uint64ToSeqByte.smt2  |   1.666s  |   1.666s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Math-mul.i.dfy.Impl__Math____mul__i.__default.lemma__mul__equality__converse.smt2  |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Math-mul.i.dfy.Impl__Math____mul__i.__default.lemma__mul__one__to__one__pos.smt2  |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|d_komodo-verified-alloc_spare.gen.dfyImpl___module.__default.va__lemma__kom__smc__alloc__spare.smt2  |  21.649s  |  21.649s  |   0.000s  | 0.0%|
|d_komodo-verified-allocate_page.gen.dfyCheckWellformed___module.__default.va__lemma__addrspace__incref.smt2  |   2.249s  |   2.249s  |   0.000s  | 0.0%|
|d_komodo-verified-allocate_page.gen.dfyCheckWellformed___module.__default.va__lemma__allocate__page__success.smt2  |   8.353s  |   8.353s  |   0.000s  | 0.0%|
|d_komodo-verified-attest.gen.dfyCheckWellformed___module.__default.va__lemma__compute__hmac.smt2  |   5.808s  |   5.808s  |   0.000s  | 0.0%|
|d_komodo-verified-attest.gen.dfyCheckWellformed___module.__default.va__lemma__svc__returning__attest__inner.smt2  |   2.069s  |   2.069s  |   0.000s  | 0.0%|
|d_komodo-verified-attest_helpers.gen.dfyCheckWellformed___module.__default.va__lemma__load__attestion__key__inner.smt2  |  35.479s  |  35.479s  |   0.000s  | 0.0%|
|d_komodo-verified-attest_helpers.gen.dfyImpl___module.__default.va__lemma__unstack__all__regs.smt2  |  26.370s  |  26.370s  |   0.000s  | 0.0%|
|d_komodo-verified-attest_input.gen.dfyImpl___module.__default.va__lemma__arrange__attestation__input.smt2  |  11.621s  |  11.621s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.gen.dfyCheckWellformed___module.__default.va__lemma__pre__entry__resume.smt2  |   1.184s  |   1.184s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.gen.dfyCheckWellformed___module.__default.va__lemma__stack__banked__regs1.smt2  |   0.921s  |   0.921s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.gen.dfyCheckWellformed___module.__default.va__lemma__stack__banked__regs2.smt2  |   4.332s  |   4.332s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.gen.dfyCheckWellformed___module.__default.va__lemma__stack__banked__regs3.smt2  |   3.793s  |   3.793s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.gen.dfyCheckWellformed___module.__default.va__lemma__switch__addrspace.smt2  |   1.003s  |   1.003s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.gen.dfyCheckWellformed___module.__default.va__lemma__unstack__banked__regs3.smt2  |   5.379s  |   5.379s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.gen.dfyImpl___module.__default.lemma__stackunstack__banked__regs.smt2  |  12.689s  |  12.689s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.gen.dfyImpl___module.__default.va__lemma__enclaveexecution__loop.smt2  |  49.961s  |  49.961s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.gen.dfyImpl___module.__default.va__lemma__unstack__banked__regs1.smt2  |  33.699s  |  33.699s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.gen.dfyImpl___module.__default.va__lemma__unstack__banked__regs_split0.smt2  |  30.865s  |  30.865s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.i.dfyCheckWellformed___module.__default.lemma__evalMOVSPCLRUC__inner.smt2  |   1.686s  |   1.686s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.i.dfyImpl___module.__default.lemma__partialEnclaveExecution__append.smt2  |   1.727s  |   1.727s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.i.dfyImpl___module.__default.lemma__partialEnclaveExecution__done.smt2  |   1.727s  |   1.727s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.i.dfyImpl___module.__default.lemma__userExecutionPreservesStack.smt2  |   3.412s  |   3.412s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.i.dfyImpl___module.__default.lemma__userExecutionUpdatesPageDb_split0.smt2  |   1.732s  |   1.732s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.i.dfyImpl___module.__default.lemma__validEnclaveExecutionStep__PageDb.smt2  |   3.890s  |   3.890s  |   0.000s  | 0.0%|
|d_komodo-verified-exception_handlers.gen.dfyCheckWellformed___module.__default.va__lemma__CPSID__IAF.smt2  |   4.716s  |   4.716s  |   0.000s  | 0.0%|
|d_komodo-verified-exception_handlers.gen.dfyCheckWellformed___module.__default.va__lemma__save__disp__context.smt2  |   1.843s  |   1.843s  |   0.000s  | 0.0%|
|d_komodo-verified-exception_handlers.gen.dfyImpl___module.__default.va__lemma__CPSID__IAF.smt2  |  35.714s  |  35.714s  |   0.000s  | 0.0%|
|d_komodo-verified-exception_handlers.gen.dfyImpl___module.__default.va__lemma__switch__to__monitor.smt2  |   9.517s  |   9.517s  |   0.000s  | 0.0%|
|d_komodo-verified-exhandler_state.i.dfyCheckWellformed___module.__default.lemma__SVCFIQNestedExceptionIsCorrect.smt2  |  12.088s  |  12.088s  |   0.000s  | 0.0%|
|d_komodo-verified-exhandler_state.i.dfyImpl___module.__default.lemma__KomUserEntryPrecond__Preserved.smt2  |  20.850s  |  20.850s  |   0.000s  | 0.0%|
|d_komodo-verified-exhandler_state.i.dfyImpl___module.__default.lemma__PrivModeExceptionHandlersAreCorrect.smt2  |  30.914s  |  30.914s  |   0.000s  | 0.0%|
|d_komodo-verified-finalise.gen.dfyCheckWellformed___module.__default.lemma__kom__smc__finalise__success__helper1.smt2  |  11.932s  |  11.932s  |   0.000s  | 0.0%|
|d_komodo-verified-init_l2ptable.gen.dfyCheckWellformed___module.__default.va__lemma__init__l2ptable__success.smt2  |   1.724s  |   1.724s  |   0.000s  | 0.0%|
|d_komodo-verified-init_l2ptable.gen.dfyCheckWellformed___module.__default.va__lemma__zero__l2__page.smt2  |   9.641s  |   9.641s  |   0.000s  | 0.0%|
|d_komodo-verified-init_l2ptable.gen.dfyImpl___module.__default.lemma__SecurePage.smt2       |   2.285s  |   2.285s  |   0.000s  | 0.0%|
|d_komodo-verified-init_l2ptable.gen.dfyImpl___module.__default.va__lemma__init__l2ptable__success_split0.smt2  |  14.396s  |  14.396s  |   0.000s  | 0.0%|
|d_komodo-verified-kom_utils.gen.dfyImpl___module.__default.va__abstract__load__32__bit__const.smt2  |  36.689s  |  36.689s  |   0.000s  | 0.0%|
|d_komodo-verified-map_common.gen.dfyCheckWellformed___module.__default.lemma__update__l2pte__helper1.smt2  |   9.035s  |   9.035s  |   0.000s  | 0.0%|
|d_komodo-verified-map_common.gen.dfyImpl___module.__default.lemma__update__l2pte__helper1.smt2  |  15.237s  |  15.237s  |   0.000s  | 0.0%|
|d_komodo-verified-map_common.gen.dfyImpl___module.__default.va__lemma__mkL2Pte__secure.smt2  |   9.585s  |   9.585s  |   0.000s  | 0.0%|
|d_komodo-verified-map_insecure.gen.dfyImpl___module.__default.va__lemma__mkl2pte__insecure.smt2  |   6.008s  |   6.008s  |   0.000s  | 0.0%|
|d_komodo-verified-map_insecure.gen.dfyImpl___module.__default.va__lemma__phys__page__is__insecure__ram.smt2  |  17.674s  |  17.674s  |   0.000s  | 0.0%|
|d_komodo-verified-map_secure.gen.dfyImpl___module.__default.lemma__preserve__contentsOfPhysPage.smt2  |   3.470s  |   3.470s  |   0.000s  | 0.0%|
|d_komodo-verified-memset.gen.dfyCheckWellformed___module.__default.va__lemma__memcpy.smt2   |   6.654s  |   6.654s  |   0.000s  | 0.0%|
|d_komodo-verified-memset.gen.dfyCheckWellformed___module.__default.va__lemma__memcpy__bare.smt2  |   6.476s  |   6.476s  |   0.000s  | 0.0%|
|d_komodo-verified-memset.gen.dfyImpl___module.__default.va__lemma__memcpy.smt2              |   2.392s  |   2.392s  |   0.000s  | 0.0%|
|d_komodo-verified-pagedb.i.dfyImpl___module.__default.AllButOnePagePreserving.smt2          |   7.134s  |   7.134s  |   0.000s  | 0.0%|
|d_komodo-verified-psrbits.i.dfyImpl___module.__default.lemma__update__psr__f.smt2           |   1.940s  |   1.940s  |   0.000s  | 0.0%|
|d_komodo-verified-ptables.i.dfyImpl___module.__default.lemma__OnlyPTPagesInHwPTable.smt2    |   6.702s  |   6.702s  |   0.000s  | 0.0%|
|d_komodo-verified-ptables.i.dfyImpl___module.__default.lemma__memstatecontainspage.smt2     |   1.270s  |   1.270s  |   0.000s  | 0.0%|
|d_komodo-verified-ptables.i.dfyImpl___module.__default.lemma__ptablesmatch_split11.smt2     |   1.612s  |   1.612s  |   0.000s  | 0.0%|
|d_komodo-verified-ptebits.i.dfyImpl___module.__default.lemma__ARM__L2PTE_split0.smt2        |   0.490s  |   0.490s  |   0.000s  | 0.0%|
|d_komodo-verified-ptebits.i.dfyImpl___module.__default.lemma__l2indexFromMapping__shifts.smt2  |   0.581s  |   0.581s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-conf_ni.i.dfyImpl___module.__default.lemma__conf__ni.smt2         |   3.651s  |   3.651s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-conf_ni.i.dfyImpl___module.__default.lemma__initAddrspace__loweq__pdb.smt2  |   5.733s  |   5.733s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-conf_ni.i.dfyImpl___module.__default.lemma__mapSecure__loweq__pdb__success.smt2  |  33.649s  |  33.649s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyCheckWellformed___module.__default.lemma__svcHandled__conf__not__atkr.smt2  |  24.038s  |  24.038s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__data__eqpdb__to__addrs.smt2  |   4.089s  |   4.089s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__data__page__eqdb__to__addrs.smt2  |   1.669s  |   1.669s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__svcHandled__conf__not__atkr.smt2  |  36.727s  |  36.727s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__userMemEquiv__atkr.smt2  |   8.147s  |   8.147s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__userStatesEquiv__atkr.smt2  |   5.364s  |   5.364s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-integ_ni.i.dfyImpl___module.__default.lemma__enc__ni.smt2         |   1.093s  |   1.093s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-integ_ni_entry.i.dfyImpl___module.__default.lemma__enter__enc__ni.smt2  |   3.648s  |   3.648s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-sec_prop_util.i.dfyImpl___module.__default.lemma__maybeContents__insec__ni.smt2  |   1.517s  |   1.517s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-bit-vector-lemmas.i.dfyImpl___module.__default.lemma__Ch.smt2         |   0.396s  |   0.396s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-bit-vector-lemmas.i.dfyImpl___module.__default.lemma__Maj.smt2        |   0.461s  |   0.461s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-hmac.gen.dfyCheckWellformed___module.__default.va__lemma__hmac__inner.smt2  |   1.448s  |   1.448s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-hmac.gen.dfyImpl___module.__default.va__lemma__hmac__inner__prep__input.smt2  |   5.102s  |   5.102s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-hmac.gen.dfyImpl___module.__default.va__lemma__hmac__outer.smt2       |  29.594s  |  29.594s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-sha256-api.gen.dfyImpl___module.__default.va__abstract__sha256__init.smt2  |   8.911s  |   8.911s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-sha256-api.gen.dfyImpl___module.__default.va__refined__sha256__finalize.smt2  |  23.410s  |  23.410s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-sha256-api.gen.dfyImpl___module.__default.va__refined__sha256__one__shot.smt2  |  31.160s  |  31.160s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-sha256-block-data-order.gen.dfyImpl___module.__default.va__abstract__sha256__block__data__order__inner.smt2  |  27.392s  |  27.392s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-sha256.i.dfyImpl___module.__default.lemma__ArrayOffsetConcatenation.smt2  |   0.357s  |   0.357s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-sha256.i.dfyImpl___module.__default.lemma__ConcatenateSeqs__Adds.smt2  |   0.411s  |   0.411s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-sha256.i.dfyImpl___module.__default.lemma__Trace__stitching.smt2      |   0.490s  |   0.490s  |   0.000s  | 0.0%|
|d_komodo-verified-smcapi.i.dfyCheckWellformed___module.__default.kom__smc__map__measure__helper2.smt2  |   2.077s  |   2.077s  |   0.000s  | 0.0%|
|d_komodo-verified-smcapi.i.dfyImpl___module.__default.AllButOnePageOrStackPreserving.smt2   |   7.243s  |   7.243s  |   0.000s  | 0.0%|
|d_komodo-verified-smcapi.i.dfyImpl___module.__default.initDispatcherPreservesPageDBValidity.smt2  |   8.871s  |   8.871s  |   0.000s  | 0.0%|
|d_komodo-verified-smcapi.i.dfyImpl___module.__default.kom__smc__map__measure__helper2.smt2  |   1.754s  |   1.754s  |   0.000s  | 0.0%|
|d_komodo-verified-smcapi.i.dfyImpl___module.__default.lemma__ConcatenateSeqs__Adds_k.smt2   |   0.851s  |   0.851s  |   0.000s  | 0.0%|
|d_komodo-verified-smcapi.i.dfyImpl___module.__default.lemma__validEnclaveExecutionStep__validPageDb.smt2  |   9.616s  |   9.616s  |   0.000s  | 0.0%|
|d_komodo-verified-smcapi.i.dfyImpl___module.__default.mapSecurePreservesPageDBValidity.smt2  |  29.098s  |  29.098s  |   0.000s  | 0.0%|
|d_komodo-verified-svc_handlers.gen.dfyCheckWellformed___module.__default.lemma__svc__returning__verify__step0__helper.smt2  |   3.277s  |   3.277s  |   0.000s  | 0.0%|
|d_komodo-verified-svc_handlers.gen.dfyCheckWellformed___module.__default.va__lemma__svc__map__data__success.smt2  |  28.733s  |  28.733s  |   0.000s  | 0.0%|
|d_komodo-verified-svc_handlers.gen.dfyCheckWellformed___module.__default.va__lemma__svc__returning__verify__step0.smt2  |  15.117s  |  15.117s  |   0.000s  | 0.0%|
|d_komodo-verified-svc_handlers.gen.dfyCheckWellformed___module.__default.va__lemma__svc__unmap__data.smt2  |   1.815s  |   1.815s  |   0.000s  | 0.0%|
|d_komodo-verified-svc_handlers.gen.dfyImpl___module.__default.lemma__svc__returning__WordAlignedStack.smt2  |   7.822s  |   7.822s  |   0.000s  | 0.0%|
|d_komodo-verified-svc_handlers.gen.dfyImpl___module.__default.va__lemma__monvaddr__page__impl.smt2  |  15.112s  |  15.112s  |   0.000s  | 0.0%|
|d_komodo-verified-svc_handlers.gen.dfyImpl___module.__default.va__lemma__rng__read.smt2     |  26.704s  |  26.704s  |   0.000s  | 0.0%|
|d_komodo-verified-valedecls.gen.dfyImpl___module.__default.va__lemma__MSR.smt2              |   0.807s  |   0.807s  |   0.000s  | 0.0%|
|d_komodo-verified-verify.gen.dfyCheckWellformed___module.__default.va__lemma__svc__returning__verify__inner.smt2  |   6.798s  |   6.798s  |   0.000s  | 0.0%|
|d_komodo-verified-verify_input.gen.dfyImpl___module.__default.va__lemma__arrange__verification__input.smt2  |   6.461s  |   6.461s  |   0.000s  | 0.0%|
|d_lvbkv-Betree-AsyncBetree_Refines_AsyncMap.i.dfy.Impl__AsyncBetree__Refines__AsyncMap.__default.RefinesQueryEndStep.smt2  |   7.648s  |   7.648s  |   0.000s  | 0.0%|
|d_lvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.FlushStepPreservesInvariant.smt2   |  30.951s  |  30.951s  |   0.000s  | 0.0%|
|d_lvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.InsertMessagePreservesLookupsPut.smt2  |  14.757s  |  14.757s  |   0.000s  | 0.0%|
|d_lvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectPreservesRootHasNoPred.smt2  |  12.405s  |  12.405s  |   0.000s  | 0.0%|
|d_lvbkv-Betree-Betree_Refines_Map.i.dfy.Impl__Betree__Refines__Map.__default.RefinesNextStep.smt2  |  22.126s  |  22.126s  |   0.000s  | 0.0%|
|d_lvbkv-Betree-Betree_Refines_Map.i.dfy.Impl__Betree__Refines__Map.__default.SuccQueryStepRefinesMap.smt2  |  11.668s  |  11.668s  |   0.000s  | 0.0%|
|d_lvbkv-BlockCacheSystem-BetreeJournalSystem_Refines_ThreeStateVersionedMap.i.dfy.Impl__BetreeJournalSystem__Refines__ThreeStateVersionedMap.__default.RefinesNext.smt2  |   3.085s  |   3.085s  |   0.000s  | 0.0%|
|d_lvbkv-BlockCacheSystem-BetreeSystem_Refines_StatesViewPivotBetree.i.dfy.Impl__BetreeSystem__Refines__StatesViewPivotBetree.__default.CrashStepRefines.smt2  |   1.867s  |   1.867s  |   0.000s  | 0.0%|
|d_lvbkv-BlockCacheSystem-BlockCache.i.dfy.Impl__BlockCache.__default.AllocStepPreservesInv.smt2  |   1.410s  |   1.410s  |   0.000s  | 0.0%|
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.AllocStepPreservesInv.smt2  |  38.576s  |  38.576s  |   0.000s  | 0.0%|
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.WriteBackIndirectionTableReqStepPreservesInv.smt2  |   4.363s  |   4.363s  |   0.000s  | 0.0%|
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.WriteBackNodeRespStepPreservesGraphs.smt2  |  47.674s  |  47.674s  |   0.000s  | 0.0%|
|d_lvbkv-BlockCacheSystem-DiskLayout.i.dfy.Impl__DiskLayout.__default.ValidNodeAddrMul.smt2  |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|d_lvbkv-BlockCacheSystem-JournalInterval.i.dfy.Impl__JournalIntervals.__default.Disk__Journal__Read2.smt2  |   0.346s  |   0.346s  |   0.000s  | 0.0%|
|d_lvbkv-BlockCacheSystem-JournalInterval.i.dfy.Impl__JournalIntervals.__default.concatFoldAdditive.smt2  |   0.416s  |   0.416s  |   0.000s  | 0.0%|
|d_lvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.NextStepPreservesInv.smt2  |   2.188s  |   2.188s  |   0.000s  | 0.0%|
|d_lvbkv-ByteBlockCacheSystem-ByteSystem_Refines_BetreeJournalSystem.i.dfy.Impl__ByteSystem__Refines__BetreeJournalSystem.__default.RefinesNext.smt2  |  14.083s  |  14.083s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-BookkeepingModel.i.dfy.Impl__BookkeepingModel.__default.allocCorrect.smt2      |  28.738s  |  28.738s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-BookkeepingModel.i.dfy.Impl__BookkeepingModel.__default.writeCorrect.smt2      |  13.427s  |  13.427s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-CommitterImpl.i.dfy.Impl__CommitterImpl.Committer.FinishLoadingOtherPhase.smt2  |   3.171s  |   3.171s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-CoordinationImpl.i.dfy.Impl__CoordinationImpl.__default.succ.smt2              |  31.822s  |  31.822s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.writeNodeResponse.smt2                     |  13.089s  |  13.089s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-InsertImpl.i.dfy.Impl__InsertImpl.__default.insert.smt2                        |   6.919s  |   6.919s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-JournalistImpl.i.dfy.Impl__JournalistImpl.Journalist.freeze.smt2               |   0.896s  |   0.896s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-JournalistImpl.i.dfy.Impl__JournalistImpl.Journalist.packageInMemoryJournal.smt2  |   0.548s  |   0.548s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-JournalistImpl.i.dfy.Impl__JournalistImpl.Journalist.parseJournals.smt2        |   0.636s  |   0.636s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.parsesFromStuff.smt2  |   0.423s  |   0.423s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.nodeToVal.smt2           |   8.421s  |   8.421s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-NodeImpl.i.dfy.Impl__NodeImpl.Node.UpdateSlot.smt2                             |   1.267s  |   1.267s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-SyncImpl.i.dfy.Impl__SyncImpl.__default.TryToWriteBlock.smt2                   |  34.325s  |  34.325s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-SyncImpl.i.dfy.Impl__SyncImpl.__default.sync.smt2                              |  46.917s  |  46.917s  |   0.000s  | 0.0%|
|d_lvbkv-MapSpec-TSJ.i.dfy.Impl__TSJ.__default.ExtendLog2StepPreservesInv.smt2               |   0.720s  |   0.720s  |   0.000s  | 0.0%|
|d_lvbkv-MapSpec-TSJMap_Refines_ThreeStateVersionedMap.i.dfy.Impl__TSJMap__Refines__ThreeStateVersionedMap.__default.RefinesMove3.smt2  |   0.403s  |   0.403s  |   0.000s  | 0.0%|
|d_lvbkv-MapSpec-TSJMap_Refines_ThreeStateVersionedMap.i.dfy.Impl__TSJMap__Refines__ThreeStateVersionedMap.__default.RefinesStutter.smt2  |   0.662s  |   0.662s  |   0.000s  | 0.0%|
|d_lvbkv-MapSpec-TSJMap_Refines_ThreeStateVersionedMap.i.dfy.Impl__TSJMap__Refines__ThreeStateVersionedMap.__default.apply__eq__apply__uiops.smt2  |   0.351s  |   0.351s  |   0.000s  | 0.0%|
|d_lvbkv-PivotBetree-PivotBetree.i.dfy.Impl__PivotBetree.__default.StutterStepRefines.smt2   |   1.692s  |   1.692s  |   0.000s  | 0.0%|
|d_lvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.Impl__PivotBetreeSpecRefinement.__default.RefinesLookup.smt2  |   8.261s  |   8.261s  |   0.000s  | 0.0%|
|d_lvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.Impl__PivotBetreeSpecRefinement.__default.RefinesValidFlush.smt2  |  11.242s  |  11.242s  |   0.000s  | 0.0%|
|d_lvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.Impl__PivotBetreeSpecRefinement.__default.SplitRouteNewChild.smt2  |   6.554s  |   6.554s  |   0.000s  | 0.0%|
|d_lvbkv-PivotBetree-PivotBetreeSpecWFNodes.i.dfy.Impl__PivotBetreeSpecWFNodes.__default.WFApplyRepivot.smt2  |   0.730s  |   0.730s  |   0.000s  | 0.0%|
|d_lvbkv-PivotBetree-TSJPivotBetree.i.dfy.Impl__TSJPivotBetree.__default.NextStepPreservesInv.smt2  |   0.982s  |   0.982s  |   0.000s  | 0.0%|
|d_lvbkv-Versions-CompositeView.i.dfy.Impl__CompositeView.__default.AdvancePreservesInv.smt2  |   0.705s  |   0.705s  |   0.000s  | 0.0%|
|d_lvbkv-Versions-CompositeView.i.dfy.Impl__CompositeView.__default.FreezePreservesInv.smt2  |   0.505s  |   0.505s  |   0.000s  | 0.0%|
|d_lvbkv-Versions-CompositeView_Refines_TSJMap.i.dfy.Impl__CompositeView__Refines__TSJMap.__default.JournalInternalRefines.smt2  |   1.196s  |   1.196s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-Multisets.i.dfy.Impl__Multisets.__default.ApplySeq.smt2                    |   3.508s  |   3.508s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-Multisets.i.dfy.Impl__Multisets.__default.FoldAdditive.smt2                |  14.544s  |  14.544s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-Sequences.i.dfy.CheckWellformed__Sequences.__default.RemoveOneValue.smt2   |   0.275s  |   0.275s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-Sequences.i.dfy.Impl__Sequences.__default.UnflattenIndexIsCorrect.smt2     |   0.207s  |   0.207s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-total_order.i.dfy.Impl__Total__Order.__default.FlattenStrictlySorted.smt2  |   0.493s  |   0.493s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-total_order.i.dfy.Impl__Total__Order.__default.strictlySortedInsert.smt2   |   1.755s  |   1.755s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.GetMiddleKey.smt2           |   0.892s  |   0.892s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.WeightKeyListFlatten.smt2  |   0.632s  |   0.632s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.WeightSplitBucketInList.smt2  |   0.856s  |   0.856s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-BucketsLib.i.dfy.Impl__BucketsLib.__default.WFProperMergeBucketsInList.smt2  |   2.738s  |   2.738s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-BucketsLib.i.dfy.Impl__BucketsLib.__default.WFSplitBucketInList.smt2    |   0.537s  |   0.537s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-LKMBPKVOps.i.dfy.Impl__LKMBPKVOps.__default.IMessagesInverse.smt2       |   0.785s  |   0.785s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-LKMBPKVOps.i.dfy.Impl__LKMBPKVOps.__default.LeafFillDpkv.smt2           |  12.477s  |  12.477s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-LKMBPKVOps.i.dfy.Impl__LKMBPKVOps.__default.ToPkv.smt2                  |   1.209s  |   1.209s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-LKMBPKVOps.i.dfy.Impl__LKMBPKVOps.__default.canAppendKeysIterate.smt2   |   1.564s  |   1.564s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-LKMBPKVOps.i.dfy.Impl__LKMBPKVOps.__default.canAppendMessagesIterate.smt2  |   2.012s  |   2.012s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.CheckWellformed__DynamicPkv.__default.PKVISeq.smt2       |   0.742s  |   0.742s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.CheckWellformed__PackedKV.__default.LastKey.smt2         |   0.577s  |   0.577s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.__default.MergeToChildren.smt2          |   2.673s  |   2.673s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.__default.PartialFlush.smt2             |   1.453s  |   1.453s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.DefineIMessage.smt2             |   0.566s  |   0.566s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.SplitRight.smt2                 |   0.929s  |   0.929s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.psaTotalLengthBound.smt2        |   0.626s  |   0.626s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedStringArray.i.dfy.CheckWellformed__PackedStringArray.__default.psaAppendSeq.smt2  |   0.691s  |   0.691s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.DynamicPsa.FromSeq.smt2  |   0.574s  |   0.574s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.PsaSuffix.smt2  |   0.374s  |   0.374s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Checksums-CRC32CArrayImpl.i.dfy.Impl__CRC32__C__Array__Impl.__default.advanced__of__iterated__intrinsic.smt2  |   0.310s  |   0.310s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Checksums-CRC32CImpl.i.dfy.Impl__CRC32__C__Impl.__default.advanced__of__iterated__intrinsic.smt2  |   0.286s  |   0.286s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Checksums-CRC32C_Lemmas.i.dfy.Impl__CRC32C__Lemmas.__default.advances__bytes__refl.smt2  |   0.259s  |   0.259s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Checksums-F2_X_Lemmas.i.dfy.Impl__F2__X__Lemmas.__default.p__qr__partial.smt2   |  15.100s  |  15.100s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Checksums-F2_X_Lemmas.i.dfy.Impl__F2__X__Lemmas.__default.pq__r__partial.smt2   |   4.890s  |   4.890s  |   0.000s  | 0.0%|
|d_lvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.InterpretationDelegation.smt2  |   0.368s  |   0.368s  |   0.000s  | 0.0%|
|d_lvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.InterpretationInheritance.smt2  |   0.348s  |   0.348s  |   0.000s  | 0.0%|
|d_lvbkv-lib-DataStructures-KMBtree.i.dfy.Impl__KMBtreeModel.__default.InterpretationDelegation.smt2  |   0.399s  |   0.399s  |   0.000s  | 0.0%|
|d_lvbkv-lib-DataStructures-KMBtree.i.dfy.Impl__KMBtreeModel.__default.InterpretationInheritance.smt2  |   5.685s  |   5.685s  |   0.000s  | 0.0%|
|d_lvbkv-lib-DataStructures-KMBtree.i.dfy.Impl__KMBtreeModel.__default.InterpretationsDisjointUnion.smt2  |   0.750s  |   0.750s  |   0.000s  | 0.0%|
|d_lvbkv-lib-DataStructures-KMBtree.i.dfy.Impl__LKMBtree.__default.InsertLeaf.smt2           |   1.841s  |   1.841s  |   0.000s  | 0.0%|
|d_lvbkv-lib-DataStructures-LinearContentMutableMap.i.dfy.Impl__LinearContentMutableMap.__default.FixedSizeInsertEntry.smt2  |  35.778s  |  35.778s  |   0.000s  | 0.0%|
|d_lvbkv-lib-DataStructures-LinearContentMutableMap.i.dfy.Impl__LinearContentMutableMap.__default.Probe.smt2  |  13.590s  |  13.590s  |   0.000s  | 0.0%|
|d_lvbkv-lib-DataStructures-LinearMutableMap.i.dfy.Impl__LinearMutableMap.__default.UpdateByIter.smt2  |  41.547s  |  41.547s  |   0.000s  | 0.0%|
|d_lvbkv-lib-DataStructures-MutableMapModel.i.dfy.Impl__MutableMapModel.__default.IndexSetMatchesContents.smt2  |  22.484s  |  22.484s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.lemma__parse__Val__view__ByteArray.smt2  |   0.391s  |   0.391s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Marshalling-Util.i.dfy.Impl__Common____Util__i.__default.seqIntoArrayChar.smt2  |   0.246s  |   0.246s  |   0.000s  | 0.0%|
|s_komodo-1435.3.smt2                                                                        |   6.042s  |   6.042s  |   0.000s  | 0.0%|
</details>
