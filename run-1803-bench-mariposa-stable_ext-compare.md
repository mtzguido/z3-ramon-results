Comparing data and data


# SUMMARY
- LHS tests = 269
- RHS tests = 269
- LHS success = 269  (100.0%)
- RHS success = 269  (100.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: bench-mariposa-stable_ext
Runner: rise-runner-2
Z3 repo: CanCebeci/z3
Z3 commit: 18cb7654b9931442b52ef68bdb2c6643b1b01392
Z3 branch: master-clean
Z3 options: "-T:20"
Z3 inputs: inputs/mariposa/stable_ext
Z3 commit message: Update generation number of already-internalized enodes

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: bench-mariposa-stable_ext
Runner: rise-runner-2
Z3 repo: CanCebeci/z3
Z3 commit: 18cb7654b9931442b52ef68bdb2c6643b1b01392
Z3 branch: master-clean
Z3 options: "-T:20"
Z3 inputs: inputs/mariposa/stable_ext
Z3 commit message: Update generation number of already-internalized enodes

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectResultingGraphAfterAllocs.smt2  |   2.983s  |   2.983s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeCache.i.dfy.Impl__BetreeCache.__default.BetreeMoveStepPreservesInv.smt2  |   4.045s  |   4.045s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeSystem_Refines_StatesViewPivotBetree.i.dfy.Impl__BetreeSystem__Refines__StatesViewPivotBetree.__default.BetreeMoveStepRefines.smt2  |   9.778s  |   9.778s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ProcessWritePreservesInv.smt2  |   7.353s  |   7.353s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesReqWriteOp.smt2  |   9.354s  |   9.354s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenCompose.smt2  |  20.043s  |  20.043s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenFromBucketStackWithLowerBound.smt2  |   2.337s  |   2.337s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterInitImpl.i.dfy.Impl__CommitterInitImpl.__default.FinishLoadingOtherPhase.smt2  |   8.000s  |   8.000s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-EvictImpl.i.dfy.Impl__EvictImpl.__default.Evict.smt2                           |   5.822s  |   5.822s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-HandleReadResponseImpl.i.dfy.Impl__HandleReadResponseImpl.__default.readResponse.smt2  |  20.060s  |  20.060s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.writeNodeResponse.smt2                     |   9.438s  |   9.438s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.InitLocBitmap.smt2  |   6.027s  |   6.027s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.ValToIndirectionTable.smt2  |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.CheckWellformed__IndirectionTableModel.__default.RemoveRef.smt2  |   2.744s  |   2.744s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.Impl__IndirectionTableModel.__default.LemmaComputeRefCountsEntryIterateCorrectPartial.smt2  |   4.389s  |   4.389s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.fillInChecksumsPreserves.smt2  |   2.883s  |   2.883s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.writeOntoResult.smt2  |  11.237s  |  11.237s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.parseJournals.smt2  |   1.086s  |   1.086s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.ValToBuckets.smt2        |   7.714s  |   7.714s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.bucketToVal.smt2         |   2.482s  |   2.482s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectResultingGraphAfterAllocs.smt2  |   2.983s  |   2.983s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeCache.i.dfy.Impl__BetreeCache.__default.BetreeMoveStepPreservesInv.smt2  |   4.045s  |   4.045s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeSystem_Refines_StatesViewPivotBetree.i.dfy.Impl__BetreeSystem__Refines__StatesViewPivotBetree.__default.BetreeMoveStepRefines.smt2  |   9.778s  |   9.778s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ProcessWritePreservesInv.smt2  |   7.353s  |   7.353s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesReqWriteOp.smt2  |   9.354s  |   9.354s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenCompose.smt2  |  20.043s  |  20.043s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenFromBucketStackWithLowerBound.smt2  |   2.337s  |   2.337s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterInitImpl.i.dfy.Impl__CommitterInitImpl.__default.FinishLoadingOtherPhase.smt2  |   8.000s  |   8.000s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-EvictImpl.i.dfy.Impl__EvictImpl.__default.Evict.smt2                           |   5.822s  |   5.822s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-HandleReadResponseImpl.i.dfy.Impl__HandleReadResponseImpl.__default.readResponse.smt2  |  20.060s  |  20.060s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.writeNodeResponse.smt2                     |   9.438s  |   9.438s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.InitLocBitmap.smt2  |   6.027s  |   6.027s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.ValToIndirectionTable.smt2  |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.CheckWellformed__IndirectionTableModel.__default.RemoveRef.smt2  |   2.744s  |   2.744s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.Impl__IndirectionTableModel.__default.LemmaComputeRefCountsEntryIterateCorrectPartial.smt2  |   4.389s  |   4.389s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.fillInChecksumsPreserves.smt2  |   2.883s  |   2.883s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.writeOntoResult.smt2  |  11.237s  |  11.237s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.parseJournals.smt2  |   1.086s  |   1.086s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.ValToBuckets.smt2        |   7.714s  |   7.714s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.bucketToVal.smt2         |   2.482s  |   2.482s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectResultingGraphAfterAllocs.smt2  |   2.983s  |   2.983s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeCache.i.dfy.Impl__BetreeCache.__default.BetreeMoveStepPreservesInv.smt2  |   4.045s  |   4.045s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeSystem_Refines_StatesViewPivotBetree.i.dfy.Impl__BetreeSystem__Refines__StatesViewPivotBetree.__default.BetreeMoveStepRefines.smt2  |   9.778s  |   9.778s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ProcessWritePreservesInv.smt2  |   7.353s  |   7.353s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesReqWriteOp.smt2  |   9.354s  |   9.354s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenCompose.smt2  |  20.043s  |  20.043s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenFromBucketStackWithLowerBound.smt2  |   2.337s  |   2.337s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterInitImpl.i.dfy.Impl__CommitterInitImpl.__default.FinishLoadingOtherPhase.smt2  |   8.000s  |   8.000s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-EvictImpl.i.dfy.Impl__EvictImpl.__default.Evict.smt2                           |   5.822s  |   5.822s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-HandleReadResponseImpl.i.dfy.Impl__HandleReadResponseImpl.__default.readResponse.smt2  |  20.060s  |  20.060s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.writeNodeResponse.smt2                     |   9.438s  |   9.438s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.InitLocBitmap.smt2  |   6.027s  |   6.027s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.ValToIndirectionTable.smt2  |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.CheckWellformed__IndirectionTableModel.__default.RemoveRef.smt2  |   2.744s  |   2.744s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.Impl__IndirectionTableModel.__default.LemmaComputeRefCountsEntryIterateCorrectPartial.smt2  |   4.389s  |   4.389s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.fillInChecksumsPreserves.smt2  |   2.883s  |   2.883s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.writeOntoResult.smt2  |  11.237s  |  11.237s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.parseJournals.smt2  |   1.086s  |   1.086s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.ValToBuckets.smt2        |   7.714s  |   7.714s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.bucketToVal.smt2         |   2.482s  |   2.482s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectResultingGraphAfterAllocs.smt2  |   2.983s  |   2.983s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeCache.i.dfy.Impl__BetreeCache.__default.BetreeMoveStepPreservesInv.smt2  |   4.045s  |   4.045s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeSystem_Refines_StatesViewPivotBetree.i.dfy.Impl__BetreeSystem__Refines__StatesViewPivotBetree.__default.BetreeMoveStepRefines.smt2  |   9.778s  |   9.778s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ProcessWritePreservesInv.smt2  |   7.353s  |   7.353s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesReqWriteOp.smt2  |   9.354s  |   9.354s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenCompose.smt2  |  20.043s  |  20.043s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenFromBucketStackWithLowerBound.smt2  |   2.337s  |   2.337s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterInitImpl.i.dfy.Impl__CommitterInitImpl.__default.FinishLoadingOtherPhase.smt2  |   8.000s  |   8.000s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-EvictImpl.i.dfy.Impl__EvictImpl.__default.Evict.smt2                           |   5.822s  |   5.822s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-HandleReadResponseImpl.i.dfy.Impl__HandleReadResponseImpl.__default.readResponse.smt2  |  20.060s  |  20.060s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.writeNodeResponse.smt2                     |   9.438s  |   9.438s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.InitLocBitmap.smt2  |   6.027s  |   6.027s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.ValToIndirectionTable.smt2  |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.CheckWellformed__IndirectionTableModel.__default.RemoveRef.smt2  |   2.744s  |   2.744s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.Impl__IndirectionTableModel.__default.LemmaComputeRefCountsEntryIterateCorrectPartial.smt2  |   4.389s  |   4.389s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.fillInChecksumsPreserves.smt2  |   2.883s  |   2.883s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.writeOntoResult.smt2  |  11.237s  |  11.237s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.parseJournals.smt2  |   1.086s  |   1.086s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.ValToBuckets.smt2        |   7.714s  |   7.714s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.bucketToVal.smt2         |   2.482s  |   2.482s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|s_komodo-1488.6.smt2                                                                       |  20.769s |6368.0MiB|
|s_komodo-1499.4.smt2                                                                       |  20.741s |6315.0MiB|
|s_komodo-1509.6.smt2                                                                       |  20.688s |6163.0MiB|
|s_komodo-1499.6.smt2                                                                       |  20.662s |5968.0MiB|
|s_komodo-1504.6.smt2                                                                       |  20.586s |5937.0MiB|
|s_komodo-1493.6.smt2                                                                       |  20.537s |4277.0MiB|
|s_komodo-1450.0.smt2                                                                       |  20.528s |5461.0MiB|
|s_komodo-1435.3.smt2                                                                       |  20.155s |1397.0MiB|
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.WriteBackNodeRespStepPreservesGraphs.smt2 |  20.068s |222.0MiB|
|d_komodo-verified-secprop-conf_ni.i.dfyImpl___module.__default.lemma__mapSecure__loweq__pdb__success.smt2 |  20.063s |201.0MiB|
|d_lvbkv-Impl-SyncImpl.i.dfy.Impl__SyncImpl.__default.TryToWriteBlock.smt2                  |  20.062s |216.0MiB|
|d_komodo-verified-attest_helpers.gen.dfyCheckWellformed___module.__default.va__lemma__load__attestion__key__inner.smt2 |  20.060s |274.0MiB|
|d_fvbkv-Impl-HandleReadResponseImpl.i.dfy.Impl__HandleReadResponseImpl.__default.readResponse.smt2 |  20.060s |181.0MiB|
|d_komodo-verified-entry.gen.dfyImpl___module.__default.va__lemma__stack__banked__regs2.smt2 |  20.059s |187.0MiB|
|d_lvbkv-Impl-SyncImpl.i.dfy.Impl__SyncImpl.__default.sync.smt2                             |  20.056s |204.0MiB|
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.AllocStepPreservesInv.smt2 |  20.055s |191.0MiB|
|d_komodo-verified-svc_handlers.gen.dfyImpl___module.__default.va__lemma__rng__read.smt2    |  20.054s |224.0MiB|
|d_komodo-verified-entry.gen.dfyImpl___module.__default.va__lemma__enclaveexecution__loop.smt2 |  20.054s |181.0MiB|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__svcHandled__conf__not__atkr.smt2 |  20.052s |185.0MiB|
|d_komodo-verified-svc_handlers.gen.dfyCheckWellformed___module.__default.va__lemma__svc__map__data__success.smt2 |  20.052s |188.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|s_komodo-1488.6.smt2                                                                       |  20.769s |6368.0MiB|
|s_komodo-1499.4.smt2                                                                       |  20.741s |6315.0MiB|
|s_komodo-1509.6.smt2                                                                       |  20.688s |6163.0MiB|
|s_komodo-1499.6.smt2                                                                       |  20.662s |5968.0MiB|
|s_komodo-1504.6.smt2                                                                       |  20.586s |5937.0MiB|
|s_komodo-1493.6.smt2                                                                       |  20.537s |4277.0MiB|
|s_komodo-1450.0.smt2                                                                       |  20.528s |5461.0MiB|
|s_komodo-1435.3.smt2                                                                       |  20.155s |1397.0MiB|
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.WriteBackNodeRespStepPreservesGraphs.smt2 |  20.068s |222.0MiB|
|d_komodo-verified-secprop-conf_ni.i.dfyImpl___module.__default.lemma__mapSecure__loweq__pdb__success.smt2 |  20.063s |201.0MiB|
|d_lvbkv-Impl-SyncImpl.i.dfy.Impl__SyncImpl.__default.TryToWriteBlock.smt2                  |  20.062s |216.0MiB|
|d_komodo-verified-attest_helpers.gen.dfyCheckWellformed___module.__default.va__lemma__load__attestion__key__inner.smt2 |  20.060s |274.0MiB|
|d_fvbkv-Impl-HandleReadResponseImpl.i.dfy.Impl__HandleReadResponseImpl.__default.readResponse.smt2 |  20.060s |181.0MiB|
|d_komodo-verified-entry.gen.dfyImpl___module.__default.va__lemma__stack__banked__regs2.smt2 |  20.059s |187.0MiB|
|d_lvbkv-Impl-SyncImpl.i.dfy.Impl__SyncImpl.__default.sync.smt2                             |  20.056s |204.0MiB|
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.AllocStepPreservesInv.smt2 |  20.055s |191.0MiB|
|d_komodo-verified-svc_handlers.gen.dfyImpl___module.__default.va__lemma__rng__read.smt2    |  20.054s |224.0MiB|
|d_komodo-verified-entry.gen.dfyImpl___module.__default.va__lemma__enclaveexecution__loop.smt2 |  20.054s |181.0MiB|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__svcHandled__conf__not__atkr.smt2 |  20.052s |185.0MiB|
|d_komodo-verified-svc_handlers.gen.dfyCheckWellformed___module.__default.va__lemma__svc__map__data__success.smt2 |  20.052s |188.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectResultingGraphAfterAllocs.smt2  |54.064MiB|54.064MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeCache.i.dfy.Impl__BetreeCache.__default.BetreeMoveStepPreservesInv.smt2  |95.224MiB|95.224MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeSystem_Refines_StatesViewPivotBetree.i.dfy.Impl__BetreeSystem__Refines__StatesViewPivotBetree.__default.BetreeMoveStepRefines.smt2  |116.0MiB|116.0MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ProcessWritePreservesInv.smt2  |172.0MiB|172.0MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesReqWriteOp.smt2  |174.0MiB|174.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenCompose.smt2  |171.0MiB|171.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenFromBucketStackWithLowerBound.smt2  |96.604MiB|96.604MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterInitImpl.i.dfy.Impl__CommitterInitImpl.__default.FinishLoadingOtherPhase.smt2  |168.0MiB|168.0MiB|0B| 0.0%|
|d_fvbkv-Impl-EvictImpl.i.dfy.Impl__EvictImpl.__default.Evict.smt2                           |169.0MiB|169.0MiB|0B| 0.0%|
|d_fvbkv-Impl-HandleReadResponseImpl.i.dfy.Impl__HandleReadResponseImpl.__default.readResponse.smt2  |181.0MiB|181.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.writeNodeResponse.smt2                     |171.0MiB|171.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.InitLocBitmap.smt2  |106.0MiB|106.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.ValToIndirectionTable.smt2  |183.0MiB|183.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.CheckWellformed__IndirectionTableModel.__default.RemoveRef.smt2  |97.0MiB|97.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.Impl__IndirectionTableModel.__default.LemmaComputeRefCountsEntryIterateCorrectPartial.smt2  |99.808MiB|99.808MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.fillInChecksumsPreserves.smt2  |68.296MiB|68.296MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.writeOntoResult.smt2  |194.0MiB|194.0MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.parseJournals.smt2  |40.728MiB|40.728MiB|0B| 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.ValToBuckets.smt2        |168.0MiB|168.0MiB|0B| 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.bucketToVal.smt2         |100.0MiB|100.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectResultingGraphAfterAllocs.smt2  |54.064MiB|54.064MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeCache.i.dfy.Impl__BetreeCache.__default.BetreeMoveStepPreservesInv.smt2  |95.224MiB|95.224MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeSystem_Refines_StatesViewPivotBetree.i.dfy.Impl__BetreeSystem__Refines__StatesViewPivotBetree.__default.BetreeMoveStepRefines.smt2  |116.0MiB|116.0MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ProcessWritePreservesInv.smt2  |172.0MiB|172.0MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesReqWriteOp.smt2  |174.0MiB|174.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenCompose.smt2  |171.0MiB|171.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenFromBucketStackWithLowerBound.smt2  |96.604MiB|96.604MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterInitImpl.i.dfy.Impl__CommitterInitImpl.__default.FinishLoadingOtherPhase.smt2  |168.0MiB|168.0MiB|0B| 0.0%|
|d_fvbkv-Impl-EvictImpl.i.dfy.Impl__EvictImpl.__default.Evict.smt2                           |169.0MiB|169.0MiB|0B| 0.0%|
|d_fvbkv-Impl-HandleReadResponseImpl.i.dfy.Impl__HandleReadResponseImpl.__default.readResponse.smt2  |181.0MiB|181.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.writeNodeResponse.smt2                     |171.0MiB|171.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.InitLocBitmap.smt2  |106.0MiB|106.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.ValToIndirectionTable.smt2  |183.0MiB|183.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.CheckWellformed__IndirectionTableModel.__default.RemoveRef.smt2  |97.0MiB|97.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.Impl__IndirectionTableModel.__default.LemmaComputeRefCountsEntryIterateCorrectPartial.smt2  |99.808MiB|99.808MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.fillInChecksumsPreserves.smt2  |68.296MiB|68.296MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.writeOntoResult.smt2  |194.0MiB|194.0MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.parseJournals.smt2  |40.728MiB|40.728MiB|0B| 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.ValToBuckets.smt2        |168.0MiB|168.0MiB|0B| 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.bucketToVal.smt2         |100.0MiB|100.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectResultingGraphAfterAllocs.smt2  |54.064MiB|54.064MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeCache.i.dfy.Impl__BetreeCache.__default.BetreeMoveStepPreservesInv.smt2  |95.224MiB|95.224MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeSystem_Refines_StatesViewPivotBetree.i.dfy.Impl__BetreeSystem__Refines__StatesViewPivotBetree.__default.BetreeMoveStepRefines.smt2  |116.0MiB|116.0MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ProcessWritePreservesInv.smt2  |172.0MiB|172.0MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesReqWriteOp.smt2  |174.0MiB|174.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenCompose.smt2  |171.0MiB|171.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenFromBucketStackWithLowerBound.smt2  |96.604MiB|96.604MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterInitImpl.i.dfy.Impl__CommitterInitImpl.__default.FinishLoadingOtherPhase.smt2  |168.0MiB|168.0MiB|0B| 0.0%|
|d_fvbkv-Impl-EvictImpl.i.dfy.Impl__EvictImpl.__default.Evict.smt2                           |169.0MiB|169.0MiB|0B| 0.0%|
|d_fvbkv-Impl-HandleReadResponseImpl.i.dfy.Impl__HandleReadResponseImpl.__default.readResponse.smt2  |181.0MiB|181.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.writeNodeResponse.smt2                     |171.0MiB|171.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.InitLocBitmap.smt2  |106.0MiB|106.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.ValToIndirectionTable.smt2  |183.0MiB|183.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.CheckWellformed__IndirectionTableModel.__default.RemoveRef.smt2  |97.0MiB|97.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.Impl__IndirectionTableModel.__default.LemmaComputeRefCountsEntryIterateCorrectPartial.smt2  |99.808MiB|99.808MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.fillInChecksumsPreserves.smt2  |68.296MiB|68.296MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.writeOntoResult.smt2  |194.0MiB|194.0MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.parseJournals.smt2  |40.728MiB|40.728MiB|0B| 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.ValToBuckets.smt2        |168.0MiB|168.0MiB|0B| 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.bucketToVal.smt2         |100.0MiB|100.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectResultingGraphAfterAllocs.smt2  |54.064MiB|54.064MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeCache.i.dfy.Impl__BetreeCache.__default.BetreeMoveStepPreservesInv.smt2  |95.224MiB|95.224MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeSystem_Refines_StatesViewPivotBetree.i.dfy.Impl__BetreeSystem__Refines__StatesViewPivotBetree.__default.BetreeMoveStepRefines.smt2  |116.0MiB|116.0MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ProcessWritePreservesInv.smt2  |172.0MiB|172.0MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesReqWriteOp.smt2  |174.0MiB|174.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenCompose.smt2  |171.0MiB|171.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenFromBucketStackWithLowerBound.smt2  |96.604MiB|96.604MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterInitImpl.i.dfy.Impl__CommitterInitImpl.__default.FinishLoadingOtherPhase.smt2  |168.0MiB|168.0MiB|0B| 0.0%|
|d_fvbkv-Impl-EvictImpl.i.dfy.Impl__EvictImpl.__default.Evict.smt2                           |169.0MiB|169.0MiB|0B| 0.0%|
|d_fvbkv-Impl-HandleReadResponseImpl.i.dfy.Impl__HandleReadResponseImpl.__default.readResponse.smt2  |181.0MiB|181.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.writeNodeResponse.smt2                     |171.0MiB|171.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.InitLocBitmap.smt2  |106.0MiB|106.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.ValToIndirectionTable.smt2  |183.0MiB|183.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.CheckWellformed__IndirectionTableModel.__default.RemoveRef.smt2  |97.0MiB|97.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.Impl__IndirectionTableModel.__default.LemmaComputeRefCountsEntryIterateCorrectPartial.smt2  |99.808MiB|99.808MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.fillInChecksumsPreserves.smt2  |68.296MiB|68.296MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.writeOntoResult.smt2  |194.0MiB|194.0MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.parseJournals.smt2  |40.728MiB|40.728MiB|0B| 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.ValToBuckets.smt2        |168.0MiB|168.0MiB|0B| 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.bucketToVal.smt2         |100.0MiB|100.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|s_komodo-1488.6.smt2                                                                       |  20.769s |6368.0MiB|
|s_komodo-1499.4.smt2                                                                       |  20.741s |6315.0MiB|
|s_komodo-1509.6.smt2                                                                       |  20.688s |6163.0MiB|
|s_komodo-1499.6.smt2                                                                       |  20.662s |5968.0MiB|
|s_komodo-1504.6.smt2                                                                       |  20.586s |5937.0MiB|
|s_komodo-1450.0.smt2                                                                       |  20.528s |5461.0MiB|
|s_komodo-1493.6.smt2                                                                       |  20.537s |4277.0MiB|
|s_komodo-1435.3.smt2                                                                       |  20.155s |1397.0MiB|
|d_lvbkv-ByteBlockCacheSystem-ByteSystem_Refines_BetreeJournalSystem.i.dfy.Impl__ByteSystem__Refines__BetreeJournalSystem.__default.RefinesNext.smt2 |  12.672s |402.0MiB|
|d_fvbkv-lib-Buckets-KMBPKVOps.i.dfy.Impl__KMBPKVOps.__default.ToPkv.smt2                   |   9.587s |312.0MiB|
|d_komodo-verified-attest_helpers.gen.dfyCheckWellformed___module.__default.va__lemma__load__attestion__key__inner.smt2 |  20.060s |274.0MiB|
|d_komodo-verified-attest_helpers.gen.dfyImpl___module.__default.va__lemma__unstack__all__regs.smt2 |  20.052s |238.0MiB|
|d_komodo-verified-sha-hmac.gen.dfyImpl___module.__default.va__lemma__hmac__outer.smt2      |  20.047s |228.0MiB|
|d_komodo-verified-svc_handlers.gen.dfyImpl___module.__default.va__lemma__rng__read.smt2    |  20.054s |224.0MiB|
|d_lvbkv-Impl-CoordinationImpl.i.dfy.Impl__CoordinationImpl.__default.succ.smt2             |  20.036s |223.0MiB|
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.WriteBackNodeRespStepPreservesGraphs.smt2 |  20.068s |222.0MiB|
|d_lvbkv-lib-Checksums-F2_X_Lemmas.i.dfy.Impl__F2__X__Lemmas.__default.pq__r__partial.smt2  |  20.050s |220.0MiB|
|d_lvbkv-BlockCacheSystem-BetreeJournalSystem_Refines_ThreeStateVersionedMap.i.dfy.Impl__BetreeJournalSystem__Refines__ThreeStateVersionedMap.__default.RefinesNext.smt2 |   4.565s |218.0MiB|
|d_lvbkv-Impl-SyncImpl.i.dfy.Impl__SyncImpl.__default.TryToWriteBlock.smt2                  |  20.062s |216.0MiB|
|d_komodo-verified-exception_handlers.gen.dfyImpl___module.__default.va__lemma__CPSID__IAF.smt2 |  20.051s |206.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|s_komodo-1488.6.smt2                                                                       |  20.769s |6368.0MiB|
|s_komodo-1499.4.smt2                                                                       |  20.741s |6315.0MiB|
|s_komodo-1509.6.smt2                                                                       |  20.688s |6163.0MiB|
|s_komodo-1499.6.smt2                                                                       |  20.662s |5968.0MiB|
|s_komodo-1504.6.smt2                                                                       |  20.586s |5937.0MiB|
|s_komodo-1450.0.smt2                                                                       |  20.528s |5461.0MiB|
|s_komodo-1493.6.smt2                                                                       |  20.537s |4277.0MiB|
|s_komodo-1435.3.smt2                                                                       |  20.155s |1397.0MiB|
|d_lvbkv-ByteBlockCacheSystem-ByteSystem_Refines_BetreeJournalSystem.i.dfy.Impl__ByteSystem__Refines__BetreeJournalSystem.__default.RefinesNext.smt2 |  12.672s |402.0MiB|
|d_fvbkv-lib-Buckets-KMBPKVOps.i.dfy.Impl__KMBPKVOps.__default.ToPkv.smt2                   |   9.587s |312.0MiB|
|d_komodo-verified-attest_helpers.gen.dfyCheckWellformed___module.__default.va__lemma__load__attestion__key__inner.smt2 |  20.060s |274.0MiB|
|d_komodo-verified-attest_helpers.gen.dfyImpl___module.__default.va__lemma__unstack__all__regs.smt2 |  20.052s |238.0MiB|
|d_komodo-verified-sha-hmac.gen.dfyImpl___module.__default.va__lemma__hmac__outer.smt2      |  20.047s |228.0MiB|
|d_komodo-verified-svc_handlers.gen.dfyImpl___module.__default.va__lemma__rng__read.smt2    |  20.054s |224.0MiB|
|d_lvbkv-Impl-CoordinationImpl.i.dfy.Impl__CoordinationImpl.__default.succ.smt2             |  20.036s |223.0MiB|
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.WriteBackNodeRespStepPreservesGraphs.smt2 |  20.068s |222.0MiB|
|d_lvbkv-lib-Checksums-F2_X_Lemmas.i.dfy.Impl__F2__X__Lemmas.__default.pq__r__partial.smt2  |  20.050s |220.0MiB|
|d_lvbkv-BlockCacheSystem-BetreeJournalSystem_Refines_ThreeStateVersionedMap.i.dfy.Impl__BetreeJournalSystem__Refines__ThreeStateVersionedMap.__default.RefinesNext.smt2 |   4.565s |218.0MiB|
|d_lvbkv-Impl-SyncImpl.i.dfy.Impl__SyncImpl.__default.TryToWriteBlock.smt2                  |  20.062s |216.0MiB|
|d_komodo-verified-exception_handlers.gen.dfyImpl___module.__default.va__lemma__CPSID__IAF.smt2 |  20.051s |206.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectResultingGraphAfterAllocs.smt2  |   2.983s  |   2.983s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeCache.i.dfy.Impl__BetreeCache.__default.BetreeMoveStepPreservesInv.smt2  |   4.045s  |   4.045s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeSystem_Refines_StatesViewPivotBetree.i.dfy.Impl__BetreeSystem__Refines__StatesViewPivotBetree.__default.BetreeMoveStepRefines.smt2  |   9.778s  |   9.778s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ProcessWritePreservesInv.smt2  |   7.353s  |   7.353s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesReqWriteOp.smt2  |   9.354s  |   9.354s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenCompose.smt2  |  20.043s  |  20.043s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenFromBucketStackWithLowerBound.smt2  |   2.337s  |   2.337s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterInitImpl.i.dfy.Impl__CommitterInitImpl.__default.FinishLoadingOtherPhase.smt2  |   8.000s  |   8.000s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-EvictImpl.i.dfy.Impl__EvictImpl.__default.Evict.smt2                           |   5.822s  |   5.822s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-HandleReadResponseImpl.i.dfy.Impl__HandleReadResponseImpl.__default.readResponse.smt2  |  20.060s  |  20.060s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.writeNodeResponse.smt2                     |   9.438s  |   9.438s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.InitLocBitmap.smt2  |   6.027s  |   6.027s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.ValToIndirectionTable.smt2  |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.CheckWellformed__IndirectionTableModel.__default.RemoveRef.smt2  |   2.744s  |   2.744s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.Impl__IndirectionTableModel.__default.LemmaComputeRefCountsEntryIterateCorrectPartial.smt2  |   4.389s  |   4.389s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.fillInChecksumsPreserves.smt2  |   2.883s  |   2.883s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.writeOntoResult.smt2  |  11.237s  |  11.237s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.parseJournals.smt2  |   1.086s  |   1.086s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.ValToBuckets.smt2        |   7.714s  |   7.714s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.bucketToVal.smt2         |   2.482s  |   2.482s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.bucketsToVal.smt2        |   7.209s  |   7.209s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.nodeToVal.smt2           |   9.752s  |   9.752s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-QueryModel.i.dfy.Impl__QueryModel.__default.AugmentLookup.smt2                 |   3.746s  |   3.746s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-SplitImpl.i.dfy.Impl__SplitImpl.__default.splitBookkeeping.smt2                |  11.667s  |  11.667s  |   0.000s  | 0.0%|
|d_fvbkv-PivotBetree-PivotBetree.i.dfy.Impl__PivotBetree.__default.BetreeStepRefines.smt2    |   3.627s  |   3.627s  |   0.000s  | 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.Impl__PivotBetreeSpecRefinement.__default.CutoffNodeAndKeepRightAgree.smt2  |   1.132s  |   1.132s  |   0.000s  | 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpecWFNodes.i.dfy.Impl__PivotBetreeSpecWFNodes.__default.ValidMergeWritesInvNodes.smt2  |   4.124s  |   4.124s  |   0.000s  | 0.0%|
|d_fvbkv-Versions-CompositeView_Refines_TSJMap.i.dfy.Impl__CompositeView__Refines__TSJMap.__default.CrashRefines.smt2  |   0.811s  |   0.811s  |   0.000s  | 0.0%|
|d_fvbkv-Versions-CompositeView_Refines_TSJMap.i.dfy.Impl__CompositeView__Refines__TSJMap.__default.JournalInternalRefines.smt2  |   1.438s  |   1.438s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-Multisets.i.dfy.Impl__Multisets.__default.FoldAdditive.smt2                |   3.245s  |   3.245s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-sequences.i.dfy.Impl__Sequences.__default.FlattenAdditive.smt2             |   0.400s  |   0.400s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-sequences.i.dfy.Impl__Sequences.__default.UnflattenFlattenIdentity.smt2    |   0.239s  |   0.239s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-total_order.i.dfy.Impl__Char__Order.__default.FlattenStrictlySorted.smt2   |   0.288s  |   0.288s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-total_order.i.dfy.Impl__Total__Order.__default.FlattenStrictlySorted.smt2  |   0.433s  |   0.433s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-total_order.i.dfy.Impl__Total__Order.__default.strictlySortedInsert.smt2   |   0.466s  |   0.466s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-total_order.i.dfy.Impl__Uint32__Order.__default.FlattenStrictlySorted.smt2  |   0.281s  |   0.281s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-total_order.i.dfy.Impl__Uint64__Order.__default.FlattenStrictlySorted.smt2  |   0.299s  |   0.299s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.SplitOneInList.smt2         |   2.634s  |   2.634s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.WeightKeySeqIs.smt2         |   1.107s  |   1.107s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketModel.i.dfy.Impl__BucketModel.__default.mergeToChildrenIterSlack_split0.smt2  |   1.260s  |   1.260s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.WMWeightBucketListFlush.smt2  |   1.044s  |   1.044s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.WeightBucketListItemFlushSingletonOrEmpty.smt2  |   2.097s  |   2.097s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.WeightMessageListFlatten.smt2  |   0.742s  |   0.742s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.WeightSplitBucketInList.smt2  |   0.645s  |   0.645s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-KMBPKVOps.i.dfy.Impl__KMBPKVOps.__default.IMessagesInverse.smt2         |   0.995s  |   0.995s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-KMBPKVOps.i.dfy.Impl__KMBPKVOps.__default.ToPkv.smt2                    |   9.587s  |   9.587s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-KMBPKVOps.i.dfy.Impl__KMBPKVOps.__default.canAppendMessagesIterate.smt2  |   1.476s  |   1.476s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.CheckWellformed__DynamicPkv.__default.PKVISeq.smt2       |   1.010s  |   1.010s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.psaTotalLengthBound.smt2        |   0.784s  |   0.784s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKVMarshalling.i.dfy.Impl__PackedKVMarshalling.__default.ComputeWF.smt2  |   0.924s  |   0.924s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKVMarshalling.i.dfy.Impl__PackedKVMarshalling.__default.SizeOfVPackedStringArrayIsKeyListWeight.smt2  |   1.362s  |   1.362s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.PivotIndexes.smt2  |   0.535s  |   0.535s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.psaAppendSeqAdditive.smt2  |   0.566s  |   0.566s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-BitmapImpl.i.dfy.Impl__BitmapImpl.Bitmap.Set.smt2                |   0.258s  |   0.258s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-BitmapImpl.i.dfy.Impl__BitmapImpl.Bitmap.Unset.smt2              |   0.243s  |   0.243s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.InsertLeafIsCorrect.smt2  |   2.376s  |   2.376s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.SplitChildOfIndexPreservesInterpretationB.smt2  |   4.237s  |   4.237s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.SplitIndexInterpretation1.smt2  |   2.113s  |   2.113s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.SplitIndexInterpretation2.smt2  |   5.850s  |   5.850s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-KMBtree.i.dfy.Impl__KMBtree.__default.InsertIndexSelectAndPrepareChild.smt2  |   1.922s  |   1.922s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-KMBtree.i.dfy.Impl__KMBtree.__default.SplitIndex.smt2            |  20.046s  |  20.046s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-KMBtree.i.dfy.Impl__KMBtreeModel.__default.InterpretationsDisjointUnion.smt2  |   3.689s  |   3.689s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-KMBtree.i.dfy.Impl__KMBtreeModel.__default.SplitIndexInterpretation1.smt2  |   2.962s  |   2.962s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.InsertIndexChildNotFull.smt2  |   7.202s  |   7.202s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.InsertIndexSelectAndPrepareChild.smt2  |   2.967s  |   2.967s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SplitIndex.smt2  |  20.049s  |  20.049s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__TestBtreeModel.__default.SplitIndexInterpretation1.smt2  |   3.341s  |   3.341s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__TestMutableBtree.__default.SplitIndex.smt2  |  17.046s  |  17.046s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableMapModel.i.dfy.CheckWellformed__MutableMapModel.__default.IterInc.smt2  |   3.978s  |   3.978s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableMapModel.i.dfy.CheckWellformed__MutableMapModel.__default.iterToNext.smt2  |   0.597s  |   0.597s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableMapModel.i.dfy.Impl__MutableMapModel.__default.MapFromStorageProperties.smt2  |   0.658s  |   0.658s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableMapModel.i.dfy.Impl__MutableMapModel.__default.UpdatePreservesSimpleIter.smt2  |   1.647s  |   1.647s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.CheckWellformed__GenericMarshalling.__default.parse__Val.smt2  |   0.492s  |   0.492s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__div__ind.smt2                |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-Util.i.dfy.CheckWellformed__Common____Util__i.__default.Uint64ToSeqByte.smt2  |   2.312s  |   2.312s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Math-mul.i.dfy.Impl__Math____mul__i.__default.lemma__mul__equality__converse.smt2  |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Math-mul.i.dfy.Impl__Math____mul__i.__default.lemma__mul__one__to__one__pos.smt2  |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|d_komodo-verified-alloc_spare.gen.dfyImpl___module.__default.va__lemma__kom__smc__alloc__spare.smt2  |  20.043s  |  20.043s  |   0.000s  | 0.0%|
|d_komodo-verified-allocate_page.gen.dfyCheckWellformed___module.__default.va__lemma__addrspace__incref.smt2  |   3.203s  |   3.203s  |   0.000s  | 0.0%|
|d_komodo-verified-allocate_page.gen.dfyCheckWellformed___module.__default.va__lemma__allocate__page__success.smt2  |   7.696s  |   7.696s  |   0.000s  | 0.0%|
|d_komodo-verified-attest.gen.dfyCheckWellformed___module.__default.va__lemma__compute__hmac.smt2  |   7.781s  |   7.781s  |   0.000s  | 0.0%|
|d_komodo-verified-attest.gen.dfyCheckWellformed___module.__default.va__lemma__svc__returning__attest__inner.smt2  |   2.465s  |   2.465s  |   0.000s  | 0.0%|
|d_komodo-verified-attest_helpers.gen.dfyCheckWellformed___module.__default.va__lemma__load__attestion__key__inner.smt2  |  20.060s  |  20.060s  |   0.000s  | 0.0%|
|d_komodo-verified-attest_helpers.gen.dfyImpl___module.__default.va__lemma__unstack__all__regs.smt2  |  20.052s  |  20.052s  |   0.000s  | 0.0%|
|d_komodo-verified-attest_input.gen.dfyImpl___module.__default.va__lemma__arrange__attestation__input.smt2  |  12.904s  |  12.904s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.gen.dfyCheckWellformed___module.__default.va__lemma__pre__entry__resume.smt2  |   1.382s  |   1.382s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.gen.dfyCheckWellformed___module.__default.va__lemma__stack__banked__regs1.smt2  |   1.321s  |   1.321s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.gen.dfyCheckWellformed___module.__default.va__lemma__stack__banked__regs2.smt2  |   4.981s  |   4.981s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.gen.dfyCheckWellformed___module.__default.va__lemma__stack__banked__regs3.smt2  |   3.422s  |   3.422s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.gen.dfyCheckWellformed___module.__default.va__lemma__switch__addrspace.smt2  |   1.401s  |   1.401s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.gen.dfyCheckWellformed___module.__default.va__lemma__unstack__banked__regs3.smt2  |   5.456s  |   5.456s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.gen.dfyImpl___module.__default.lemma__stackunstack__banked__regs.smt2  |  12.521s  |  12.521s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.gen.dfyImpl___module.__default.va__lemma__enclaveexecution__loop.smt2  |  20.054s  |  20.054s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.gen.dfyImpl___module.__default.va__lemma__stack__banked__regs2.smt2  |  20.059s  |  20.059s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.gen.dfyImpl___module.__default.va__lemma__unstack__banked__regs1.smt2  |  20.049s  |  20.049s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.gen.dfyImpl___module.__default.va__lemma__unstack__banked__regs_split0.smt2  |  20.052s  |  20.052s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.i.dfyCheckWellformed___module.__default.lemma__evalMOVSPCLRUC__inner.smt2  |   2.120s  |   2.120s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.i.dfyImpl___module.__default.lemma__partialEnclaveExecution__append.smt2  |   2.346s  |   2.346s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.i.dfyImpl___module.__default.lemma__partialEnclaveExecution__done.smt2  |   2.719s  |   2.719s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.i.dfyImpl___module.__default.lemma__userExecutionPreservesStack.smt2  |   3.519s  |   3.519s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.i.dfyImpl___module.__default.lemma__userExecutionUpdatesPageDb_split0.smt2  |   2.485s  |   2.485s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.i.dfyImpl___module.__default.lemma__validEnclaveExecutionStep__PageDb.smt2  |   3.767s  |   3.767s  |   0.000s  | 0.0%|
|d_komodo-verified-exception_handlers.gen.dfyCheckWellformed___module.__default.va__lemma__CPSID__IAF.smt2  |   5.383s  |   5.383s  |   0.000s  | 0.0%|
|d_komodo-verified-exception_handlers.gen.dfyCheckWellformed___module.__default.va__lemma__save__disp__context.smt2  |   1.846s  |   1.846s  |   0.000s  | 0.0%|
|d_komodo-verified-exception_handlers.gen.dfyImpl___module.__default.va__lemma__CPSID__IAF.smt2  |  20.051s  |  20.051s  |   0.000s  | 0.0%|
|d_komodo-verified-exception_handlers.gen.dfyImpl___module.__default.va__lemma__switch__to__monitor.smt2  |  10.413s  |  10.413s  |   0.000s  | 0.0%|
|d_komodo-verified-exhandler_state.i.dfyCheckWellformed___module.__default.lemma__SVCFIQNestedExceptionIsCorrect.smt2  |  11.165s  |  11.165s  |   0.000s  | 0.0%|
|d_komodo-verified-exhandler_state.i.dfyImpl___module.__default.lemma__KomUserEntryPrecond__Preserved.smt2  |  18.031s  |  18.031s  |   0.000s  | 0.0%|
|d_komodo-verified-exhandler_state.i.dfyImpl___module.__default.lemma__PrivModeExceptionHandlersAreCorrect.smt2  |  20.037s  |  20.037s  |   0.000s  | 0.0%|
|d_komodo-verified-finalise.gen.dfyCheckWellformed___module.__default.lemma__kom__smc__finalise__success__helper1.smt2  |  11.007s  |  11.007s  |   0.000s  | 0.0%|
|d_komodo-verified-init_l2ptable.gen.dfyCheckWellformed___module.__default.va__lemma__init__l2ptable__success.smt2  |   2.176s  |   2.176s  |   0.000s  | 0.0%|
|d_komodo-verified-init_l2ptable.gen.dfyCheckWellformed___module.__default.va__lemma__zero__l2__page.smt2  |   8.807s  |   8.807s  |   0.000s  | 0.0%|
|d_komodo-verified-init_l2ptable.gen.dfyImpl___module.__default.lemma__SecurePage.smt2       |   2.221s  |   2.221s  |   0.000s  | 0.0%|
|d_komodo-verified-init_l2ptable.gen.dfyImpl___module.__default.va__lemma__init__l2ptable__success_split0.smt2  |  13.088s  |  13.088s  |   0.000s  | 0.0%|
|d_komodo-verified-kom_utils.gen.dfyImpl___module.__default.va__abstract__load__32__bit__const.smt2  |  20.041s  |  20.041s  |   0.000s  | 0.0%|
|d_komodo-verified-map_common.gen.dfyCheckWellformed___module.__default.lemma__update__l2pte__helper1.smt2  |   9.060s  |   9.060s  |   0.000s  | 0.0%|
|d_komodo-verified-map_common.gen.dfyImpl___module.__default.lemma__update__l2pte__helper1.smt2  |  13.161s  |  13.161s  |   0.000s  | 0.0%|
|d_komodo-verified-map_common.gen.dfyImpl___module.__default.va__lemma__mkL2Pte__secure.smt2  |   8.831s  |   8.831s  |   0.000s  | 0.0%|
|d_komodo-verified-map_insecure.gen.dfyImpl___module.__default.va__lemma__mkl2pte__insecure.smt2  |   6.653s  |   6.653s  |   0.000s  | 0.0%|
|d_komodo-verified-map_insecure.gen.dfyImpl___module.__default.va__lemma__phys__page__is__insecure__ram.smt2  |  19.261s  |  19.261s  |   0.000s  | 0.0%|
|d_komodo-verified-map_secure.gen.dfyImpl___module.__default.lemma__preserve__contentsOfPhysPage.smt2  |   4.100s  |   4.100s  |   0.000s  | 0.0%|
|d_komodo-verified-memset.gen.dfyCheckWellformed___module.__default.va__lemma__memcpy.smt2   |   5.775s  |   5.775s  |   0.000s  | 0.0%|
|d_komodo-verified-memset.gen.dfyCheckWellformed___module.__default.va__lemma__memcpy__bare.smt2  |   6.381s  |   6.381s  |   0.000s  | 0.0%|
|d_komodo-verified-memset.gen.dfyImpl___module.__default.va__lemma__memcpy.smt2              |   2.309s  |   2.309s  |   0.000s  | 0.0%|
|d_komodo-verified-pagedb.i.dfyImpl___module.__default.AllButOnePagePreserving.smt2          |   5.061s  |   5.061s  |   0.000s  | 0.0%|
|d_komodo-verified-psrbits.i.dfyImpl___module.__default.lemma__update__psr__f.smt2           |   2.413s  |   2.413s  |   0.000s  | 0.0%|
|d_komodo-verified-ptables.i.dfyImpl___module.__default.lemma__OnlyPTPagesInHwPTable.smt2    |   6.293s  |   6.293s  |   0.000s  | 0.0%|
|d_komodo-verified-ptables.i.dfyImpl___module.__default.lemma__memstatecontainspage.smt2     |   1.782s  |   1.782s  |   0.000s  | 0.0%|
|d_komodo-verified-ptables.i.dfyImpl___module.__default.lemma__ptablesmatch_split11.smt2     |   2.526s  |   2.526s  |   0.000s  | 0.0%|
|d_komodo-verified-ptebits.i.dfyImpl___module.__default.lemma__ARM__L2PTE_split0.smt2        |   0.666s  |   0.666s  |   0.000s  | 0.0%|
|d_komodo-verified-ptebits.i.dfyImpl___module.__default.lemma__l2indexFromMapping__shifts.smt2  |   0.829s  |   0.829s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-conf_ni.i.dfyImpl___module.__default.lemma__conf__ni.smt2         |   4.696s  |   4.696s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-conf_ni.i.dfyImpl___module.__default.lemma__initAddrspace__loweq__pdb.smt2  |   5.549s  |   5.549s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-conf_ni.i.dfyImpl___module.__default.lemma__mapSecure__loweq__pdb__success.smt2  |  20.063s  |  20.063s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyCheckWellformed___module.__default.lemma__svcHandled__conf__not__atkr.smt2  |  19.616s  |  19.616s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__data__eqpdb__to__addrs.smt2  |   3.920s  |   3.920s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__data__page__eqdb__to__addrs.smt2  |   2.449s  |   2.449s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__svcHandled__conf__not__atkr.smt2  |  20.052s  |  20.052s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__userMemEquiv__atkr.smt2  |   8.107s  |   8.107s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__userStatesEquiv__atkr.smt2  |   5.289s  |   5.289s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-integ_ni.i.dfyImpl___module.__default.lemma__enc__ni.smt2         |   1.607s  |   1.607s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-integ_ni_entry.i.dfyImpl___module.__default.lemma__enter__enc__ni.smt2  |   5.026s  |   5.026s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-sec_prop_util.i.dfyImpl___module.__default.lemma__maybeContents__insec__ni.smt2  |   2.045s  |   2.045s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-bit-vector-lemmas.i.dfyImpl___module.__default.lemma__Ch.smt2         |   0.559s  |   0.559s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-bit-vector-lemmas.i.dfyImpl___module.__default.lemma__Maj.smt2        |   0.644s  |   0.644s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-hmac.gen.dfyCheckWellformed___module.__default.va__lemma__hmac__inner.smt2  |   2.085s  |   2.085s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-hmac.gen.dfyImpl___module.__default.va__lemma__hmac__inner__prep__input.smt2  |   5.104s  |   5.104s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-hmac.gen.dfyImpl___module.__default.va__lemma__hmac__outer.smt2       |  20.047s  |  20.047s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-sha256-api.gen.dfyImpl___module.__default.va__abstract__sha256__init.smt2  |   9.356s  |   9.356s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-sha256-api.gen.dfyImpl___module.__default.va__refined__sha256__finalize.smt2  |  16.819s  |  16.819s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-sha256-api.gen.dfyImpl___module.__default.va__refined__sha256__one__shot.smt2  |  20.048s  |  20.048s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-sha256-block-data-order.gen.dfyImpl___module.__default.va__abstract__sha256__block__data__order__inner.smt2  |  12.386s  |  12.386s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-sha256.i.dfyImpl___module.__default.lemma__ArrayOffsetConcatenation.smt2  |   0.461s  |   0.461s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-sha256.i.dfyImpl___module.__default.lemma__ConcatenateSeqs__Adds.smt2  |   0.581s  |   0.581s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-sha256.i.dfyImpl___module.__default.lemma__Trace__stitching.smt2      |   0.683s  |   0.683s  |   0.000s  | 0.0%|
|d_komodo-verified-smcapi.i.dfyCheckWellformed___module.__default.kom__smc__map__measure__helper2.smt2  |   2.140s  |   2.140s  |   0.000s  | 0.0%|
|d_komodo-verified-smcapi.i.dfyImpl___module.__default.AllButOnePageOrStackPreserving.smt2   |   7.301s  |   7.301s  |   0.000s  | 0.0%|
|d_komodo-verified-smcapi.i.dfyImpl___module.__default.initDispatcherPreservesPageDBValidity.smt2  |   9.583s  |   9.583s  |   0.000s  | 0.0%|
|d_komodo-verified-smcapi.i.dfyImpl___module.__default.kom__smc__map__measure__helper2.smt2  |   2.486s  |   2.486s  |   0.000s  | 0.0%|
|d_komodo-verified-smcapi.i.dfyImpl___module.__default.lemma__ConcatenateSeqs__Adds_k.smt2   |   1.307s  |   1.307s  |   0.000s  | 0.0%|
|d_komodo-verified-smcapi.i.dfyImpl___module.__default.lemma__validEnclaveExecutionStep__validPageDb.smt2  |  10.012s  |  10.012s  |   0.000s  | 0.0%|
|d_komodo-verified-smcapi.i.dfyImpl___module.__default.mapSecurePreservesPageDBValidity.smt2  |  20.042s  |  20.042s  |   0.000s  | 0.0%|
|d_komodo-verified-svc_handlers.gen.dfyCheckWellformed___module.__default.lemma__svc__returning__verify__step0__helper.smt2  |   3.729s  |   3.729s  |   0.000s  | 0.0%|
|d_komodo-verified-svc_handlers.gen.dfyCheckWellformed___module.__default.va__lemma__svc__map__data__success.smt2  |  20.052s  |  20.052s  |   0.000s  | 0.0%|
|d_komodo-verified-svc_handlers.gen.dfyCheckWellformed___module.__default.va__lemma__svc__returning__verify__step0.smt2  |  12.783s  |  12.783s  |   0.000s  | 0.0%|
|d_komodo-verified-svc_handlers.gen.dfyCheckWellformed___module.__default.va__lemma__svc__unmap__data.smt2  |   2.766s  |   2.766s  |   0.000s  | 0.0%|
|d_komodo-verified-svc_handlers.gen.dfyImpl___module.__default.lemma__svc__returning__WordAlignedStack.smt2  |   6.641s  |   6.641s  |   0.000s  | 0.0%|
|d_komodo-verified-svc_handlers.gen.dfyImpl___module.__default.va__lemma__monvaddr__page__impl.smt2  |  12.845s  |  12.845s  |   0.000s  | 0.0%|
|d_komodo-verified-svc_handlers.gen.dfyImpl___module.__default.va__lemma__rng__read.smt2     |  20.054s  |  20.054s  |   0.000s  | 0.0%|
|d_komodo-verified-valedecls.gen.dfyImpl___module.__default.va__lemma__MSR.smt2              |   1.257s  |   1.257s  |   0.000s  | 0.0%|
|d_komodo-verified-verify.gen.dfyCheckWellformed___module.__default.va__lemma__svc__returning__verify__inner.smt2  |   6.294s  |   6.294s  |   0.000s  | 0.0%|
|d_komodo-verified-verify_input.gen.dfyImpl___module.__default.va__lemma__arrange__verification__input.smt2  |   6.830s  |   6.830s  |   0.000s  | 0.0%|
|d_lvbkv-Betree-AsyncBetree_Refines_AsyncMap.i.dfy.Impl__AsyncBetree__Refines__AsyncMap.__default.RefinesQueryEndStep.smt2  |   8.651s  |   8.651s  |   0.000s  | 0.0%|
|d_lvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.FlushStepPreservesInvariant.smt2   |  20.046s  |  20.046s  |   0.000s  | 0.0%|
|d_lvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.InsertMessagePreservesLookupsPut.smt2  |  12.566s  |  12.566s  |   0.000s  | 0.0%|
|d_lvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectPreservesRootHasNoPred.smt2  |  10.974s  |  10.974s  |   0.000s  | 0.0%|
|d_lvbkv-Betree-Betree_Refines_Map.i.dfy.Impl__Betree__Refines__Map.__default.RefinesNextStep.smt2  |  20.048s  |  20.048s  |   0.000s  | 0.0%|
|d_lvbkv-Betree-Betree_Refines_Map.i.dfy.Impl__Betree__Refines__Map.__default.SuccQueryStepRefinesMap.smt2  |  10.215s  |  10.215s  |   0.000s  | 0.0%|
|d_lvbkv-BlockCacheSystem-BetreeJournalSystem_Refines_ThreeStateVersionedMap.i.dfy.Impl__BetreeJournalSystem__Refines__ThreeStateVersionedMap.__default.RefinesNext.smt2  |   4.565s  |   4.565s  |   0.000s  | 0.0%|
|d_lvbkv-BlockCacheSystem-BetreeSystem_Refines_StatesViewPivotBetree.i.dfy.Impl__BetreeSystem__Refines__StatesViewPivotBetree.__default.CrashStepRefines.smt2  |   3.238s  |   3.238s  |   0.000s  | 0.0%|
|d_lvbkv-BlockCacheSystem-BlockCache.i.dfy.Impl__BlockCache.__default.AllocStepPreservesInv.smt2  |   2.080s  |   2.080s  |   0.000s  | 0.0%|
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.AllocStepPreservesInv.smt2  |  20.055s  |  20.055s  |   0.000s  | 0.0%|
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.WriteBackIndirectionTableReqStepPreservesInv.smt2  |   5.192s  |   5.192s  |   0.000s  | 0.0%|
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.WriteBackNodeRespStepPreservesGraphs.smt2  |  20.068s  |  20.068s  |   0.000s  | 0.0%|
|d_lvbkv-BlockCacheSystem-DiskLayout.i.dfy.Impl__DiskLayout.__default.ValidNodeAddrMul.smt2  |   0.181s  |   0.181s  |   0.000s  | 0.0%|
|d_lvbkv-BlockCacheSystem-JournalInterval.i.dfy.Impl__JournalIntervals.__default.Disk__Journal__Read2.smt2  |   0.473s  |   0.473s  |   0.000s  | 0.0%|
|d_lvbkv-BlockCacheSystem-JournalInterval.i.dfy.Impl__JournalIntervals.__default.concatFoldAdditive.smt2  |   0.591s  |   0.591s  |   0.000s  | 0.0%|
|d_lvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.NextStepPreservesInv.smt2  |   3.109s  |   3.109s  |   0.000s  | 0.0%|
|d_lvbkv-ByteBlockCacheSystem-ByteSystem_Refines_BetreeJournalSystem.i.dfy.Impl__ByteSystem__Refines__BetreeJournalSystem.__default.RefinesNext.smt2  |  12.672s  |  12.672s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-BookkeepingModel.i.dfy.Impl__BookkeepingModel.__default.allocCorrect.smt2      |  20.052s  |  20.052s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-BookkeepingModel.i.dfy.Impl__BookkeepingModel.__default.writeCorrect.smt2      |  10.888s  |  10.888s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-CommitterImpl.i.dfy.Impl__CommitterImpl.Committer.FinishLoadingOtherPhase.smt2  |   3.007s  |   3.007s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-CoordinationImpl.i.dfy.Impl__CoordinationImpl.__default.succ.smt2              |  20.036s  |  20.036s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.writeNodeResponse.smt2                     |  11.918s  |  11.918s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-InsertImpl.i.dfy.Impl__InsertImpl.__default.insert.smt2                        |   7.223s  |   7.223s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-JournalistImpl.i.dfy.Impl__JournalistImpl.Journalist.freeze.smt2               |   0.700s  |   0.700s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-JournalistImpl.i.dfy.Impl__JournalistImpl.Journalist.packageInMemoryJournal.smt2  |   0.754s  |   0.754s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-JournalistImpl.i.dfy.Impl__JournalistImpl.Journalist.parseJournals.smt2        |   0.932s  |   0.932s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.parsesFromStuff.smt2  |   0.593s  |   0.593s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.nodeToVal.smt2           |   7.545s  |   7.545s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-NodeImpl.i.dfy.Impl__NodeImpl.Node.UpdateSlot.smt2                             |   1.676s  |   1.676s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-SyncImpl.i.dfy.Impl__SyncImpl.__default.TryToWriteBlock.smt2                   |  20.062s  |  20.062s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-SyncImpl.i.dfy.Impl__SyncImpl.__default.sync.smt2                              |  20.056s  |  20.056s  |   0.000s  | 0.0%|
|d_lvbkv-MapSpec-TSJ.i.dfy.Impl__TSJ.__default.ExtendLog2StepPreservesInv.smt2               |   0.720s  |   0.720s  |   0.000s  | 0.0%|
|d_lvbkv-MapSpec-TSJMap_Refines_ThreeStateVersionedMap.i.dfy.Impl__TSJMap__Refines__ThreeStateVersionedMap.__default.RefinesMove3.smt2  |   0.564s  |   0.564s  |   0.000s  | 0.0%|
|d_lvbkv-MapSpec-TSJMap_Refines_ThreeStateVersionedMap.i.dfy.Impl__TSJMap__Refines__ThreeStateVersionedMap.__default.RefinesStutter.smt2  |   0.994s  |   0.994s  |   0.000s  | 0.0%|
|d_lvbkv-MapSpec-TSJMap_Refines_ThreeStateVersionedMap.i.dfy.Impl__TSJMap__Refines__ThreeStateVersionedMap.__default.apply__eq__apply__uiops.smt2  |   0.488s  |   0.488s  |   0.000s  | 0.0%|
|d_lvbkv-PivotBetree-PivotBetree.i.dfy.Impl__PivotBetree.__default.StutterStepRefines.smt2   |   1.869s  |   1.869s  |   0.000s  | 0.0%|
|d_lvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.Impl__PivotBetreeSpecRefinement.__default.RefinesLookup.smt2  |   6.200s  |   6.200s  |   0.000s  | 0.0%|
|d_lvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.Impl__PivotBetreeSpecRefinement.__default.RefinesValidFlush.smt2  |   9.962s  |   9.962s  |   0.000s  | 0.0%|
|d_lvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.Impl__PivotBetreeSpecRefinement.__default.SplitRouteNewChild.smt2  |   3.373s  |   3.373s  |   0.000s  | 0.0%|
|d_lvbkv-PivotBetree-PivotBetreeSpecWFNodes.i.dfy.Impl__PivotBetreeSpecWFNodes.__default.WFApplyRepivot.smt2  |   1.013s  |   1.013s  |   0.000s  | 0.0%|
|d_lvbkv-PivotBetree-TSJPivotBetree.i.dfy.Impl__TSJPivotBetree.__default.NextStepPreservesInv.smt2  |   1.253s  |   1.253s  |   0.000s  | 0.0%|
|d_lvbkv-Versions-CompositeView.i.dfy.Impl__CompositeView.__default.AdvancePreservesInv.smt2  |   1.038s  |   1.038s  |   0.000s  | 0.0%|
|d_lvbkv-Versions-CompositeView.i.dfy.Impl__CompositeView.__default.FreezePreservesInv.smt2  |   0.705s  |   0.705s  |   0.000s  | 0.0%|
|d_lvbkv-Versions-CompositeView_Refines_TSJMap.i.dfy.Impl__CompositeView__Refines__TSJMap.__default.JournalInternalRefines.smt2  |   1.774s  |   1.774s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-Multisets.i.dfy.Impl__Multisets.__default.ApplySeq.smt2                    |   3.493s  |   3.493s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-Multisets.i.dfy.Impl__Multisets.__default.FoldAdditive.smt2                |  13.019s  |  13.019s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-Sequences.i.dfy.CheckWellformed__Sequences.__default.RemoveOneValue.smt2   |   0.398s  |   0.398s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-Sequences.i.dfy.Impl__Sequences.__default.UnflattenIndexIsCorrect.smt2     |   0.311s  |   0.311s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-total_order.i.dfy.Impl__Total__Order.__default.FlattenStrictlySorted.smt2  |   0.709s  |   0.709s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-total_order.i.dfy.Impl__Total__Order.__default.strictlySortedInsert.smt2   |   1.785s  |   1.785s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.GetMiddleKey.smt2           |   1.258s  |   1.258s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.WeightKeyListFlatten.smt2  |   0.854s  |   0.854s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.WeightSplitBucketInList.smt2  |   1.196s  |   1.196s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-BucketsLib.i.dfy.Impl__BucketsLib.__default.WFProperMergeBucketsInList.smt2  |   2.867s  |   2.867s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-BucketsLib.i.dfy.Impl__BucketsLib.__default.WFSplitBucketInList.smt2    |   0.712s  |   0.712s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-LKMBPKVOps.i.dfy.Impl__LKMBPKVOps.__default.IMessagesInverse.smt2       |   1.079s  |   1.079s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-LKMBPKVOps.i.dfy.Impl__LKMBPKVOps.__default.LeafFillDpkv.smt2           |  15.029s  |  15.029s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-LKMBPKVOps.i.dfy.Impl__LKMBPKVOps.__default.ToPkv.smt2                  |   1.565s  |   1.565s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-LKMBPKVOps.i.dfy.Impl__LKMBPKVOps.__default.canAppendKeysIterate.smt2   |   2.315s  |   2.315s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-LKMBPKVOps.i.dfy.Impl__LKMBPKVOps.__default.canAppendMessagesIterate.smt2  |   2.787s  |   2.787s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.CheckWellformed__DynamicPkv.__default.PKVISeq.smt2       |   1.025s  |   1.025s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.CheckWellformed__PackedKV.__default.LastKey.smt2         |   0.773s  |   0.773s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.__default.MergeToChildren.smt2          |   3.656s  |   3.656s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.__default.PartialFlush.smt2             |   4.795s  |   4.795s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.DefineIMessage.smt2             |   0.742s  |   0.742s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.SplitRight.smt2                 |   1.307s  |   1.307s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.psaTotalLengthBound.smt2        |   0.879s  |   0.879s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedStringArray.i.dfy.CheckWellformed__PackedStringArray.__default.psaAppendSeq.smt2  |   0.923s  |   0.923s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.DynamicPsa.FromSeq.smt2  |   0.846s  |   0.846s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.PsaSuffix.smt2  |   0.510s  |   0.510s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Checksums-CRC32CArrayImpl.i.dfy.Impl__CRC32__C__Array__Impl.__default.advanced__of__iterated__intrinsic.smt2  |   0.474s  |   0.474s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Checksums-CRC32CImpl.i.dfy.Impl__CRC32__C__Impl.__default.advanced__of__iterated__intrinsic.smt2  |   0.386s  |   0.386s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Checksums-CRC32C_Lemmas.i.dfy.Impl__CRC32C__Lemmas.__default.advances__bytes__refl.smt2  |   0.335s  |   0.335s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Checksums-F2_X_Lemmas.i.dfy.Impl__F2__X__Lemmas.__default.p__qr__partial.smt2   |  19.299s  |  19.299s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Checksums-F2_X_Lemmas.i.dfy.Impl__F2__X__Lemmas.__default.pq__r__partial.smt2   |  20.050s  |  20.050s  |   0.000s  | 0.0%|
|d_lvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.InterpretationDelegation.smt2  |   0.538s  |   0.538s  |   0.000s  | 0.0%|
|d_lvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.InterpretationInheritance.smt2  |   0.479s  |   0.479s  |   0.000s  | 0.0%|
|d_lvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.InterpretationsDisjointUnion.smt2  |  10.938s  |  10.938s  |   0.000s  | 0.0%|
|d_lvbkv-lib-DataStructures-KMBtree.i.dfy.Impl__KMBtreeModel.__default.InterpretationDelegation.smt2  |   0.540s  |   0.540s  |   0.000s  | 0.0%|
|d_lvbkv-lib-DataStructures-KMBtree.i.dfy.Impl__KMBtreeModel.__default.InterpretationInheritance.smt2  |   5.570s  |   5.570s  |   0.000s  | 0.0%|
|d_lvbkv-lib-DataStructures-KMBtree.i.dfy.Impl__KMBtreeModel.__default.InterpretationsDisjointUnion.smt2  |   1.064s  |   1.064s  |   0.000s  | 0.0%|
|d_lvbkv-lib-DataStructures-KMBtree.i.dfy.Impl__LKMBtree.__default.InsertLeaf.smt2           |   2.042s  |   2.042s  |   0.000s  | 0.0%|
|d_lvbkv-lib-DataStructures-LinearContentMutableMap.i.dfy.Impl__LinearContentMutableMap.__default.FixedSizeInsertEntry.smt2  |  20.037s  |  20.037s  |   0.000s  | 0.0%|
|d_lvbkv-lib-DataStructures-LinearContentMutableMap.i.dfy.Impl__LinearContentMutableMap.__default.Probe.smt2  |  10.589s  |  10.589s  |   0.000s  | 0.0%|
|d_lvbkv-lib-DataStructures-LinearMutableMap.i.dfy.Impl__LinearMutableMap.__default.UpdateByIter.smt2  |  20.046s  |  20.046s  |   0.000s  | 0.0%|
|d_lvbkv-lib-DataStructures-MutableMapModel.i.dfy.Impl__MutableMapModel.__default.IndexSetMatchesContents.smt2  |  17.069s  |  17.069s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.lemma__parse__Val__view__ByteArray.smt2  |   0.535s  |   0.535s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Marshalling-Util.i.dfy.Impl__Common____Util__i.__default.seqIntoArrayChar.smt2  |   0.346s  |   0.346s  |   0.000s  | 0.0%|
|s_komodo-1435.3.smt2                                                                        |  20.155s  |  20.155s  |   0.000s  | 0.0%|
|s_komodo-1450.0.smt2                                                                        |  20.528s  |  20.528s  |   0.000s  | 0.0%|
|s_komodo-1488.6.smt2                                                                        |  20.769s  |  20.769s  |   0.000s  | 0.0%|
|s_komodo-1493.6.smt2                                                                        |  20.537s  |  20.537s  |   0.000s  | 0.0%|
|s_komodo-1499.4.smt2                                                                        |  20.741s  |  20.741s  |   0.000s  | 0.0%|
|s_komodo-1499.6.smt2                                                                        |  20.662s  |  20.662s  |   0.000s  | 0.0%|
|s_komodo-1504.6.smt2                                                                        |  20.586s  |  20.586s  |   0.000s  | 0.0%|
|s_komodo-1509.6.smt2                                                                        |  20.688s  |  20.688s  |   0.000s  | 0.0%|
</details>
