Comparing data and data


# SUMMARY
- LHS tests = 120
- RHS tests = 120
- LHS success = 120  (100.0%)
- RHS success = 120  (100.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: gen-patch-mariposa-sc
Runner: rise-runner-1
Z3 repo: CanCebeci/z3
Z3 commit: aec453eb9bad24f44f4f6101b46004389bd16bb0
Z3 branch: master
Z3 options: "%OPTIONS2%"
Z3 inputs: inputs/mariposa/stable_core
Z3 commit message: Enforce stickiness of max-generation

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: gen-patch-mariposa-sc
Runner: rise-runner-1
Z3 repo: CanCebeci/z3
Z3 commit: aec453eb9bad24f44f4f6101b46004389bd16bb0
Z3 branch: master
Z3 options: "%OPTIONS2%"
Z3 inputs: inputs/mariposa/stable_core
Z3 commit message: Enforce stickiness of max-generation

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BlockInterface.i.dfy.CheckWellformed__BlockInterface.__default.IsStatePath.smt2  |   0.201s  |   0.201s  |   0.000s  | 0.0%|
|d_fvbkv-Betree-Graph.i.dfy.Impl__Graph.__default.AcyclicGraphImpliesSimplePath.smt2         |   0.210s  |   0.210s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.NewRequestReadNodeDoesntOverlap.smt2  |   0.963s  |   0.963s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-DiskLayout.i.dfy.CheckWellformed__DiskLayout.__default.JournalBackLocation.smt2  |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.CheckWellformed__JournalSystem.__default.FreezeStepPreservesJournals.smt2  |   0.598s  |   0.598s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.Impl__JournalSystem.__default.ProcessWriteSuperblockPreservesJournals.smt2  |   0.855s  |   0.855s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-AsyncDiskModel.s.dfy.CheckWellformed__AsyncDisk.__default.AckRead.smt2  |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CacheImpl.i.dfy.CheckWellformed__CacheImpl.MutCache.Remove.smt2                |   1.581s  |   1.581s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterImpl.i.dfy.CheckWellformed__CommitterImpl.Committer.__ctor.smt2       |   0.791s  |   0.791s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CoordinationModel.i.dfy.CheckWellformed__CoordinationModel.__default.initialization.smt2  |   1.696s  |   1.696s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.ReadSectorCorrect.smt2                   |   1.504s  |   1.504s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-InsertModel.i.dfy.CheckWellformed__InsertModel.__default.insertCorrect.smt2    |   1.475s  |   1.475s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.CheckWellformed__JournalistMarshallingModel.__default.hasChecksums.smt2  |   0.314s  |   0.314s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MainHandlers.i.dfy.CheckWellformed__MainHandlers.__default.InitState.smt2      |   2.114s  |   2.114s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-StateModel.i.dfy.CheckWellformed__StateModel.__default.WFSector.smt2           |   1.447s  |   1.447s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-SuccModel.i.dfy.CheckWellformed__SuccModel.__default.getPathInternal.smt2      |   1.640s  |   1.640s  |   0.000s  | 0.0%|
|d_fvbkv-MapSpec-TSJ.i.dfy.Impl__TSJ.__default.PushSyncStepPreservesInv.smt2                 |   0.250s  |   0.250s  |   0.000s  | 0.0%|
|d_fvbkv-MapSpec-TSJMap_Refines_ThreeStateVersionedMap.i.dfy.Impl__TSJMap__Refines__ThreeStateVersionedMap.__default.apply__path.smt2  |   0.277s  |   0.277s  |   0.000s  | 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupUpperBound.smt2  |   0.527s  |   0.527s  |   0.000s  | 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupVisitsWFNodes.smt2  |   0.535s  |   0.535s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BlockInterface.i.dfy.CheckWellformed__BlockInterface.__default.IsStatePath.smt2  |   0.201s  |   0.201s  |   0.000s  | 0.0%|
|d_fvbkv-Betree-Graph.i.dfy.Impl__Graph.__default.AcyclicGraphImpliesSimplePath.smt2         |   0.210s  |   0.210s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.NewRequestReadNodeDoesntOverlap.smt2  |   0.963s  |   0.963s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-DiskLayout.i.dfy.CheckWellformed__DiskLayout.__default.JournalBackLocation.smt2  |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.CheckWellformed__JournalSystem.__default.FreezeStepPreservesJournals.smt2  |   0.598s  |   0.598s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.Impl__JournalSystem.__default.ProcessWriteSuperblockPreservesJournals.smt2  |   0.855s  |   0.855s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-AsyncDiskModel.s.dfy.CheckWellformed__AsyncDisk.__default.AckRead.smt2  |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CacheImpl.i.dfy.CheckWellformed__CacheImpl.MutCache.Remove.smt2                |   1.581s  |   1.581s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterImpl.i.dfy.CheckWellformed__CommitterImpl.Committer.__ctor.smt2       |   0.791s  |   0.791s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CoordinationModel.i.dfy.CheckWellformed__CoordinationModel.__default.initialization.smt2  |   1.696s  |   1.696s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.ReadSectorCorrect.smt2                   |   1.504s  |   1.504s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-InsertModel.i.dfy.CheckWellformed__InsertModel.__default.insertCorrect.smt2    |   1.475s  |   1.475s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.CheckWellformed__JournalistMarshallingModel.__default.hasChecksums.smt2  |   0.314s  |   0.314s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MainHandlers.i.dfy.CheckWellformed__MainHandlers.__default.InitState.smt2      |   2.114s  |   2.114s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-StateModel.i.dfy.CheckWellformed__StateModel.__default.WFSector.smt2           |   1.447s  |   1.447s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-SuccModel.i.dfy.CheckWellformed__SuccModel.__default.getPathInternal.smt2      |   1.640s  |   1.640s  |   0.000s  | 0.0%|
|d_fvbkv-MapSpec-TSJ.i.dfy.Impl__TSJ.__default.PushSyncStepPreservesInv.smt2                 |   0.250s  |   0.250s  |   0.000s  | 0.0%|
|d_fvbkv-MapSpec-TSJMap_Refines_ThreeStateVersionedMap.i.dfy.Impl__TSJMap__Refines__ThreeStateVersionedMap.__default.apply__path.smt2  |   0.277s  |   0.277s  |   0.000s  | 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupUpperBound.smt2  |   0.527s  |   0.527s  |   0.000s  | 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupVisitsWFNodes.smt2  |   0.535s  |   0.535s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BlockInterface.i.dfy.CheckWellformed__BlockInterface.__default.IsStatePath.smt2  |   0.201s  |   0.201s  |   0.000s  | 0.0%|
|d_fvbkv-Betree-Graph.i.dfy.Impl__Graph.__default.AcyclicGraphImpliesSimplePath.smt2         |   0.210s  |   0.210s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.NewRequestReadNodeDoesntOverlap.smt2  |   0.963s  |   0.963s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-DiskLayout.i.dfy.CheckWellformed__DiskLayout.__default.JournalBackLocation.smt2  |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.CheckWellformed__JournalSystem.__default.FreezeStepPreservesJournals.smt2  |   0.598s  |   0.598s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.Impl__JournalSystem.__default.ProcessWriteSuperblockPreservesJournals.smt2  |   0.855s  |   0.855s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-AsyncDiskModel.s.dfy.CheckWellformed__AsyncDisk.__default.AckRead.smt2  |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CacheImpl.i.dfy.CheckWellformed__CacheImpl.MutCache.Remove.smt2                |   1.581s  |   1.581s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterImpl.i.dfy.CheckWellformed__CommitterImpl.Committer.__ctor.smt2       |   0.791s  |   0.791s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CoordinationModel.i.dfy.CheckWellformed__CoordinationModel.__default.initialization.smt2  |   1.696s  |   1.696s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.ReadSectorCorrect.smt2                   |   1.504s  |   1.504s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-InsertModel.i.dfy.CheckWellformed__InsertModel.__default.insertCorrect.smt2    |   1.475s  |   1.475s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.CheckWellformed__JournalistMarshallingModel.__default.hasChecksums.smt2  |   0.314s  |   0.314s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MainHandlers.i.dfy.CheckWellformed__MainHandlers.__default.InitState.smt2      |   2.114s  |   2.114s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-StateModel.i.dfy.CheckWellformed__StateModel.__default.WFSector.smt2           |   1.447s  |   1.447s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-SuccModel.i.dfy.CheckWellformed__SuccModel.__default.getPathInternal.smt2      |   1.640s  |   1.640s  |   0.000s  | 0.0%|
|d_fvbkv-MapSpec-TSJ.i.dfy.Impl__TSJ.__default.PushSyncStepPreservesInv.smt2                 |   0.250s  |   0.250s  |   0.000s  | 0.0%|
|d_fvbkv-MapSpec-TSJMap_Refines_ThreeStateVersionedMap.i.dfy.Impl__TSJMap__Refines__ThreeStateVersionedMap.__default.apply__path.smt2  |   0.277s  |   0.277s  |   0.000s  | 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupUpperBound.smt2  |   0.527s  |   0.527s  |   0.000s  | 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupVisitsWFNodes.smt2  |   0.535s  |   0.535s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BlockInterface.i.dfy.CheckWellformed__BlockInterface.__default.IsStatePath.smt2  |   0.201s  |   0.201s  |   0.000s  | 0.0%|
|d_fvbkv-Betree-Graph.i.dfy.Impl__Graph.__default.AcyclicGraphImpliesSimplePath.smt2         |   0.210s  |   0.210s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.NewRequestReadNodeDoesntOverlap.smt2  |   0.963s  |   0.963s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-DiskLayout.i.dfy.CheckWellformed__DiskLayout.__default.JournalBackLocation.smt2  |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.CheckWellformed__JournalSystem.__default.FreezeStepPreservesJournals.smt2  |   0.598s  |   0.598s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.Impl__JournalSystem.__default.ProcessWriteSuperblockPreservesJournals.smt2  |   0.855s  |   0.855s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-AsyncDiskModel.s.dfy.CheckWellformed__AsyncDisk.__default.AckRead.smt2  |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CacheImpl.i.dfy.CheckWellformed__CacheImpl.MutCache.Remove.smt2                |   1.581s  |   1.581s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterImpl.i.dfy.CheckWellformed__CommitterImpl.Committer.__ctor.smt2       |   0.791s  |   0.791s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CoordinationModel.i.dfy.CheckWellformed__CoordinationModel.__default.initialization.smt2  |   1.696s  |   1.696s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.ReadSectorCorrect.smt2                   |   1.504s  |   1.504s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-InsertModel.i.dfy.CheckWellformed__InsertModel.__default.insertCorrect.smt2    |   1.475s  |   1.475s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.CheckWellformed__JournalistMarshallingModel.__default.hasChecksums.smt2  |   0.314s  |   0.314s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MainHandlers.i.dfy.CheckWellformed__MainHandlers.__default.InitState.smt2      |   2.114s  |   2.114s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-StateModel.i.dfy.CheckWellformed__StateModel.__default.WFSector.smt2           |   1.447s  |   1.447s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-SuccModel.i.dfy.CheckWellformed__SuccModel.__default.getPathInternal.smt2      |   1.640s  |   1.640s  |   0.000s  | 0.0%|
|d_fvbkv-MapSpec-TSJ.i.dfy.Impl__TSJ.__default.PushSyncStepPreservesInv.smt2                 |   0.250s  |   0.250s  |   0.000s  | 0.0%|
|d_fvbkv-MapSpec-TSJMap_Refines_ThreeStateVersionedMap.i.dfy.Impl__TSJMap__Refines__ThreeStateVersionedMap.__default.apply__path.smt2  |   0.277s  |   0.277s  |   0.000s  | 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupUpperBound.smt2  |   0.527s  |   0.527s  |   0.000s  | 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupVisitsWFNodes.smt2  |   0.535s  |   0.535s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.NewRequestReadIndirectionTableIsValid.smt2 |   4.573s |117.0MiB|
|d_komodo-verified-attest_helpers.gen.dfyImpl___module.__default.va__lemma__mem__move__global.smt2 |   2.634s |99.0MiB|
|d_fvbkv-Impl-MainHandlers.i.dfy.CheckWellformed__MainHandlers.__default.InitState.smt2     |   2.114s |145.0MiB|
|d_komodo-verified-sha-sha256-body-16-xx.gen.dfyImpl___module.__default.va__refined__Body__16__XXUnroller_split0.smt2 |   2.036s |100.0MiB|
|d_lvbkv-Impl-CoordinationImpl.i.dfy.Impl__CoordinationImpl.__default.pushSync.smt2         |   1.847s |135.0MiB|
|d_komodo-verified-kom_utils.gen.dfyImpl___module.__default.va__lemma__page__monvaddr__impl.smt2 |   1.740s |63.464MiB|
|d_fvbkv-Impl-CoordinationModel.i.dfy.CheckWellformed__CoordinationModel.__default.initialization.smt2 |   1.696s |99.444MiB|
|d_komodo-verified-kom_common.i.dfyImpl___module.__default.lemma__ValidMemRangeExPageTable__persists.smt2 |   1.687s |64.192MiB|
|d_fvbkv-Impl-SuccModel.i.dfy.CheckWellformed__SuccModel.__default.getPathInternal.smt2     |   1.640s |98.768MiB|
|d_lvbkv-Impl-IOImpl.i.dfy.CheckWellformed__IOImpl.__default.getFreeLoc.smt2                |   1.629s |95.268MiB|
|d_fvbkv-Impl-CacheImpl.i.dfy.CheckWellformed__CacheImpl.MutCache.Remove.smt2               |   1.581s |91.608MiB|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.ReadSectorCorrect.smt2                  |   1.504s |92.928MiB|
|d_fvbkv-Impl-InsertModel.i.dfy.CheckWellformed__InsertModel.__default.insertCorrect.smt2   |   1.475s |93.884MiB|
|d_komodo-verified-finalise.gen.dfyImpl___module.__default.lemma__kom__smc__finalise__success__helper2.smt2 |   1.448s |93.696MiB|
|d_fvbkv-Impl-StateModel.i.dfy.CheckWellformed__StateModel.__default.WFSector.smt2          |   1.447s |88.484MiB|
|d_komodo-verified-map_common.gen.dfyImpl___module.__default.lemma__read__l2pte__zero.smt2  |   1.424s |94.72MiB|
|d_lvbkv-Impl-SplitModel.i.dfy.CheckWellformed__SplitModel.__default.lemmaChildrenConditionsCutoffNode.smt2 |   1.358s |95.452MiB|
|d_lvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.ValToBucket.smt2        |   1.343s |93.34MiB|
|d_lvbkv-Impl-CacheImpl.i.dfy.Impl__CacheImpl.LMutCache.NodePartialFlush.smt2               |   1.340s |87.62MiB|
|d_komodo-verified-verify.gen.dfyCheckWellformed___module.__default.va__code__svc__returning__verify.smt2 |   1.321s |85.812MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.NewRequestReadIndirectionTableIsValid.smt2 |   4.573s |117.0MiB|
|d_komodo-verified-attest_helpers.gen.dfyImpl___module.__default.va__lemma__mem__move__global.smt2 |   2.634s |99.0MiB|
|d_fvbkv-Impl-MainHandlers.i.dfy.CheckWellformed__MainHandlers.__default.InitState.smt2     |   2.114s |145.0MiB|
|d_komodo-verified-sha-sha256-body-16-xx.gen.dfyImpl___module.__default.va__refined__Body__16__XXUnroller_split0.smt2 |   2.036s |100.0MiB|
|d_lvbkv-Impl-CoordinationImpl.i.dfy.Impl__CoordinationImpl.__default.pushSync.smt2         |   1.847s |135.0MiB|
|d_komodo-verified-kom_utils.gen.dfyImpl___module.__default.va__lemma__page__monvaddr__impl.smt2 |   1.740s |63.464MiB|
|d_fvbkv-Impl-CoordinationModel.i.dfy.CheckWellformed__CoordinationModel.__default.initialization.smt2 |   1.696s |99.444MiB|
|d_komodo-verified-kom_common.i.dfyImpl___module.__default.lemma__ValidMemRangeExPageTable__persists.smt2 |   1.687s |64.192MiB|
|d_fvbkv-Impl-SuccModel.i.dfy.CheckWellformed__SuccModel.__default.getPathInternal.smt2     |   1.640s |98.768MiB|
|d_lvbkv-Impl-IOImpl.i.dfy.CheckWellformed__IOImpl.__default.getFreeLoc.smt2                |   1.629s |95.268MiB|
|d_fvbkv-Impl-CacheImpl.i.dfy.CheckWellformed__CacheImpl.MutCache.Remove.smt2               |   1.581s |91.608MiB|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.ReadSectorCorrect.smt2                  |   1.504s |92.928MiB|
|d_fvbkv-Impl-InsertModel.i.dfy.CheckWellformed__InsertModel.__default.insertCorrect.smt2   |   1.475s |93.884MiB|
|d_komodo-verified-finalise.gen.dfyImpl___module.__default.lemma__kom__smc__finalise__success__helper2.smt2 |   1.448s |93.696MiB|
|d_fvbkv-Impl-StateModel.i.dfy.CheckWellformed__StateModel.__default.WFSector.smt2          |   1.447s |88.484MiB|
|d_komodo-verified-map_common.gen.dfyImpl___module.__default.lemma__read__l2pte__zero.smt2  |   1.424s |94.72MiB|
|d_lvbkv-Impl-SplitModel.i.dfy.CheckWellformed__SplitModel.__default.lemmaChildrenConditionsCutoffNode.smt2 |   1.358s |95.452MiB|
|d_lvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.ValToBucket.smt2        |   1.343s |93.34MiB|
|d_lvbkv-Impl-CacheImpl.i.dfy.Impl__CacheImpl.LMutCache.NodePartialFlush.smt2               |   1.340s |87.62MiB|
|d_komodo-verified-verify.gen.dfyCheckWellformed___module.__default.va__code__svc__returning__verify.smt2 |   1.321s |85.812MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BlockInterface.i.dfy.CheckWellformed__BlockInterface.__default.IsStatePath.smt2  |25.416MiB|25.416MiB|0B| 0.0%|
|d_fvbkv-Betree-Graph.i.dfy.Impl__Graph.__default.AcyclicGraphImpliesSimplePath.smt2         |25.82MiB|25.82MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.NewRequestReadNodeDoesntOverlap.smt2  |53.26MiB|53.26MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-DiskLayout.i.dfy.CheckWellformed__DiskLayout.__default.JournalBackLocation.smt2  |24.028MiB|24.028MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.CheckWellformed__JournalSystem.__default.FreezeStepPreservesJournals.smt2  |49.496MiB|49.496MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.Impl__JournalSystem.__default.ProcessWriteSuperblockPreservesJournals.smt2  |55.84MiB|55.84MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-AsyncDiskModel.s.dfy.CheckWellformed__AsyncDisk.__default.AckRead.smt2  |25.324MiB|25.324MiB|0B| 0.0%|
|d_fvbkv-Impl-CacheImpl.i.dfy.CheckWellformed__CacheImpl.MutCache.Remove.smt2                |91.608MiB|91.608MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterImpl.i.dfy.CheckWellformed__CommitterImpl.Committer.__ctor.smt2       |52.892MiB|52.892MiB|0B| 0.0%|
|d_fvbkv-Impl-CoordinationModel.i.dfy.CheckWellformed__CoordinationModel.__default.initialization.smt2  |99.444MiB|99.444MiB|0B| 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.ReadSectorCorrect.smt2                   |92.928MiB|92.928MiB|0B| 0.0%|
|d_fvbkv-Impl-InsertModel.i.dfy.CheckWellformed__InsertModel.__default.insertCorrect.smt2    |93.884MiB|93.884MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.CheckWellformed__JournalistMarshallingModel.__default.hasChecksums.smt2  |30.036MiB|30.036MiB|0B| 0.0%|
|d_fvbkv-Impl-MainHandlers.i.dfy.CheckWellformed__MainHandlers.__default.InitState.smt2      |145.0MiB|145.0MiB|0B| 0.0%|
|d_fvbkv-Impl-StateModel.i.dfy.CheckWellformed__StateModel.__default.WFSector.smt2           |88.484MiB|88.484MiB|0B| 0.0%|
|d_fvbkv-Impl-SuccModel.i.dfy.CheckWellformed__SuccModel.__default.getPathInternal.smt2      |98.768MiB|98.768MiB|0B| 0.0%|
|d_fvbkv-MapSpec-TSJ.i.dfy.Impl__TSJ.__default.PushSyncStepPreservesInv.smt2                 |27.308MiB|27.308MiB|0B| 0.0%|
|d_fvbkv-MapSpec-TSJMap_Refines_ThreeStateVersionedMap.i.dfy.Impl__TSJMap__Refines__ThreeStateVersionedMap.__default.apply__path.smt2  |28.908MiB|28.908MiB|0B| 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupUpperBound.smt2  |43.676MiB|43.676MiB|0B| 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupVisitsWFNodes.smt2  |43.624MiB|43.624MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BlockInterface.i.dfy.CheckWellformed__BlockInterface.__default.IsStatePath.smt2  |25.416MiB|25.416MiB|0B| 0.0%|
|d_fvbkv-Betree-Graph.i.dfy.Impl__Graph.__default.AcyclicGraphImpliesSimplePath.smt2         |25.82MiB|25.82MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.NewRequestReadNodeDoesntOverlap.smt2  |53.26MiB|53.26MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-DiskLayout.i.dfy.CheckWellformed__DiskLayout.__default.JournalBackLocation.smt2  |24.028MiB|24.028MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.CheckWellformed__JournalSystem.__default.FreezeStepPreservesJournals.smt2  |49.496MiB|49.496MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.Impl__JournalSystem.__default.ProcessWriteSuperblockPreservesJournals.smt2  |55.84MiB|55.84MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-AsyncDiskModel.s.dfy.CheckWellformed__AsyncDisk.__default.AckRead.smt2  |25.324MiB|25.324MiB|0B| 0.0%|
|d_fvbkv-Impl-CacheImpl.i.dfy.CheckWellformed__CacheImpl.MutCache.Remove.smt2                |91.608MiB|91.608MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterImpl.i.dfy.CheckWellformed__CommitterImpl.Committer.__ctor.smt2       |52.892MiB|52.892MiB|0B| 0.0%|
|d_fvbkv-Impl-CoordinationModel.i.dfy.CheckWellformed__CoordinationModel.__default.initialization.smt2  |99.444MiB|99.444MiB|0B| 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.ReadSectorCorrect.smt2                   |92.928MiB|92.928MiB|0B| 0.0%|
|d_fvbkv-Impl-InsertModel.i.dfy.CheckWellformed__InsertModel.__default.insertCorrect.smt2    |93.884MiB|93.884MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.CheckWellformed__JournalistMarshallingModel.__default.hasChecksums.smt2  |30.036MiB|30.036MiB|0B| 0.0%|
|d_fvbkv-Impl-MainHandlers.i.dfy.CheckWellformed__MainHandlers.__default.InitState.smt2      |145.0MiB|145.0MiB|0B| 0.0%|
|d_fvbkv-Impl-StateModel.i.dfy.CheckWellformed__StateModel.__default.WFSector.smt2           |88.484MiB|88.484MiB|0B| 0.0%|
|d_fvbkv-Impl-SuccModel.i.dfy.CheckWellformed__SuccModel.__default.getPathInternal.smt2      |98.768MiB|98.768MiB|0B| 0.0%|
|d_fvbkv-MapSpec-TSJ.i.dfy.Impl__TSJ.__default.PushSyncStepPreservesInv.smt2                 |27.308MiB|27.308MiB|0B| 0.0%|
|d_fvbkv-MapSpec-TSJMap_Refines_ThreeStateVersionedMap.i.dfy.Impl__TSJMap__Refines__ThreeStateVersionedMap.__default.apply__path.smt2  |28.908MiB|28.908MiB|0B| 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupUpperBound.smt2  |43.676MiB|43.676MiB|0B| 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupVisitsWFNodes.smt2  |43.624MiB|43.624MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BlockInterface.i.dfy.CheckWellformed__BlockInterface.__default.IsStatePath.smt2  |25.416MiB|25.416MiB|0B| 0.0%|
|d_fvbkv-Betree-Graph.i.dfy.Impl__Graph.__default.AcyclicGraphImpliesSimplePath.smt2         |25.82MiB|25.82MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.NewRequestReadNodeDoesntOverlap.smt2  |53.26MiB|53.26MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-DiskLayout.i.dfy.CheckWellformed__DiskLayout.__default.JournalBackLocation.smt2  |24.028MiB|24.028MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.CheckWellformed__JournalSystem.__default.FreezeStepPreservesJournals.smt2  |49.496MiB|49.496MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.Impl__JournalSystem.__default.ProcessWriteSuperblockPreservesJournals.smt2  |55.84MiB|55.84MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-AsyncDiskModel.s.dfy.CheckWellformed__AsyncDisk.__default.AckRead.smt2  |25.324MiB|25.324MiB|0B| 0.0%|
|d_fvbkv-Impl-CacheImpl.i.dfy.CheckWellformed__CacheImpl.MutCache.Remove.smt2                |91.608MiB|91.608MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterImpl.i.dfy.CheckWellformed__CommitterImpl.Committer.__ctor.smt2       |52.892MiB|52.892MiB|0B| 0.0%|
|d_fvbkv-Impl-CoordinationModel.i.dfy.CheckWellformed__CoordinationModel.__default.initialization.smt2  |99.444MiB|99.444MiB|0B| 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.ReadSectorCorrect.smt2                   |92.928MiB|92.928MiB|0B| 0.0%|
|d_fvbkv-Impl-InsertModel.i.dfy.CheckWellformed__InsertModel.__default.insertCorrect.smt2    |93.884MiB|93.884MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.CheckWellformed__JournalistMarshallingModel.__default.hasChecksums.smt2  |30.036MiB|30.036MiB|0B| 0.0%|
|d_fvbkv-Impl-MainHandlers.i.dfy.CheckWellformed__MainHandlers.__default.InitState.smt2      |145.0MiB|145.0MiB|0B| 0.0%|
|d_fvbkv-Impl-StateModel.i.dfy.CheckWellformed__StateModel.__default.WFSector.smt2           |88.484MiB|88.484MiB|0B| 0.0%|
|d_fvbkv-Impl-SuccModel.i.dfy.CheckWellformed__SuccModel.__default.getPathInternal.smt2      |98.768MiB|98.768MiB|0B| 0.0%|
|d_fvbkv-MapSpec-TSJ.i.dfy.Impl__TSJ.__default.PushSyncStepPreservesInv.smt2                 |27.308MiB|27.308MiB|0B| 0.0%|
|d_fvbkv-MapSpec-TSJMap_Refines_ThreeStateVersionedMap.i.dfy.Impl__TSJMap__Refines__ThreeStateVersionedMap.__default.apply__path.smt2  |28.908MiB|28.908MiB|0B| 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupUpperBound.smt2  |43.676MiB|43.676MiB|0B| 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupVisitsWFNodes.smt2  |43.624MiB|43.624MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BlockInterface.i.dfy.CheckWellformed__BlockInterface.__default.IsStatePath.smt2  |25.416MiB|25.416MiB|0B| 0.0%|
|d_fvbkv-Betree-Graph.i.dfy.Impl__Graph.__default.AcyclicGraphImpliesSimplePath.smt2         |25.82MiB|25.82MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.NewRequestReadNodeDoesntOverlap.smt2  |53.26MiB|53.26MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-DiskLayout.i.dfy.CheckWellformed__DiskLayout.__default.JournalBackLocation.smt2  |24.028MiB|24.028MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.CheckWellformed__JournalSystem.__default.FreezeStepPreservesJournals.smt2  |49.496MiB|49.496MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.Impl__JournalSystem.__default.ProcessWriteSuperblockPreservesJournals.smt2  |55.84MiB|55.84MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-AsyncDiskModel.s.dfy.CheckWellformed__AsyncDisk.__default.AckRead.smt2  |25.324MiB|25.324MiB|0B| 0.0%|
|d_fvbkv-Impl-CacheImpl.i.dfy.CheckWellformed__CacheImpl.MutCache.Remove.smt2                |91.608MiB|91.608MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterImpl.i.dfy.CheckWellformed__CommitterImpl.Committer.__ctor.smt2       |52.892MiB|52.892MiB|0B| 0.0%|
|d_fvbkv-Impl-CoordinationModel.i.dfy.CheckWellformed__CoordinationModel.__default.initialization.smt2  |99.444MiB|99.444MiB|0B| 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.ReadSectorCorrect.smt2                   |92.928MiB|92.928MiB|0B| 0.0%|
|d_fvbkv-Impl-InsertModel.i.dfy.CheckWellformed__InsertModel.__default.insertCorrect.smt2    |93.884MiB|93.884MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.CheckWellformed__JournalistMarshallingModel.__default.hasChecksums.smt2  |30.036MiB|30.036MiB|0B| 0.0%|
|d_fvbkv-Impl-MainHandlers.i.dfy.CheckWellformed__MainHandlers.__default.InitState.smt2      |145.0MiB|145.0MiB|0B| 0.0%|
|d_fvbkv-Impl-StateModel.i.dfy.CheckWellformed__StateModel.__default.WFSector.smt2           |88.484MiB|88.484MiB|0B| 0.0%|
|d_fvbkv-Impl-SuccModel.i.dfy.CheckWellformed__SuccModel.__default.getPathInternal.smt2      |98.768MiB|98.768MiB|0B| 0.0%|
|d_fvbkv-MapSpec-TSJ.i.dfy.Impl__TSJ.__default.PushSyncStepPreservesInv.smt2                 |27.308MiB|27.308MiB|0B| 0.0%|
|d_fvbkv-MapSpec-TSJMap_Refines_ThreeStateVersionedMap.i.dfy.Impl__TSJMap__Refines__ThreeStateVersionedMap.__default.apply__path.smt2  |28.908MiB|28.908MiB|0B| 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupUpperBound.smt2  |43.676MiB|43.676MiB|0B| 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupVisitsWFNodes.smt2  |43.624MiB|43.624MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|d_fvbkv-Impl-MainHandlers.i.dfy.CheckWellformed__MainHandlers.__default.InitState.smt2     |   2.114s |145.0MiB|
|d_lvbkv-Impl-CoordinationImpl.i.dfy.Impl__CoordinationImpl.__default.pushSync.smt2         |   1.847s |135.0MiB|
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.NewRequestReadIndirectionTableIsValid.smt2 |   4.573s |117.0MiB|
|d_komodo-verified-sha-sha256-body-16-xx.gen.dfyImpl___module.__default.va__refined__Body__16__XXUnroller_split0.smt2 |   2.036s |100.0MiB|
|d_fvbkv-Impl-CoordinationModel.i.dfy.CheckWellformed__CoordinationModel.__default.initialization.smt2 |   1.696s |99.444MiB|
|d_komodo-verified-attest_helpers.gen.dfyImpl___module.__default.va__lemma__mem__move__global.smt2 |   2.634s |99.0MiB|
|d_fvbkv-Impl-SuccModel.i.dfy.CheckWellformed__SuccModel.__default.getPathInternal.smt2     |   1.640s |98.768MiB|
|d_lvbkv-Impl-SplitModel.i.dfy.CheckWellformed__SplitModel.__default.lemmaChildrenConditionsCutoffNode.smt2 |   1.358s |95.452MiB|
|d_lvbkv-Impl-IOImpl.i.dfy.CheckWellformed__IOImpl.__default.getFreeLoc.smt2                |   1.629s |95.268MiB|
|d_komodo-verified-map_common.gen.dfyImpl___module.__default.lemma__read__l2pte__zero.smt2  |   1.424s |94.72MiB|
|d_fvbkv-Impl-InsertModel.i.dfy.CheckWellformed__InsertModel.__default.insertCorrect.smt2   |   1.475s |93.884MiB|
|d_komodo-verified-finalise.gen.dfyImpl___module.__default.lemma__kom__smc__finalise__success__helper2.smt2 |   1.448s |93.696MiB|
|d_lvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.ValToBucket.smt2        |   1.343s |93.34MiB|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.ReadSectorCorrect.smt2                  |   1.504s |92.928MiB|
|d_fvbkv-Impl-CacheImpl.i.dfy.CheckWellformed__CacheImpl.MutCache.Remove.smt2               |   1.581s |91.608MiB|
|d_lvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.CheckWellformed__ByteSystem.__default.I.smt2 |   1.259s |89.812MiB|
|d_komodo-verified-exception_handlers.gen.dfyCheckWellformed___module.__default.lemma__pageDbDispatcherVerifyStateCorresponds.smt2 |   1.244s |88.796MiB|
|d_komodo-verified-sha-hmac.gen.dfyCheckWellformed___module.__default.va__lemma__hmac__outer__prep__ctx.smt2 |   1.290s |88.584MiB|
|d_fvbkv-Impl-StateModel.i.dfy.CheckWellformed__StateModel.__default.WFSector.smt2          |   1.447s |88.484MiB|
|d_lvbkv-Impl-CacheImpl.i.dfy.Impl__CacheImpl.LMutCache.NodePartialFlush.smt2               |   1.340s |87.62MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|d_fvbkv-Impl-MainHandlers.i.dfy.CheckWellformed__MainHandlers.__default.InitState.smt2     |   2.114s |145.0MiB|
|d_lvbkv-Impl-CoordinationImpl.i.dfy.Impl__CoordinationImpl.__default.pushSync.smt2         |   1.847s |135.0MiB|
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.NewRequestReadIndirectionTableIsValid.smt2 |   4.573s |117.0MiB|
|d_komodo-verified-sha-sha256-body-16-xx.gen.dfyImpl___module.__default.va__refined__Body__16__XXUnroller_split0.smt2 |   2.036s |100.0MiB|
|d_fvbkv-Impl-CoordinationModel.i.dfy.CheckWellformed__CoordinationModel.__default.initialization.smt2 |   1.696s |99.444MiB|
|d_komodo-verified-attest_helpers.gen.dfyImpl___module.__default.va__lemma__mem__move__global.smt2 |   2.634s |99.0MiB|
|d_fvbkv-Impl-SuccModel.i.dfy.CheckWellformed__SuccModel.__default.getPathInternal.smt2     |   1.640s |98.768MiB|
|d_lvbkv-Impl-SplitModel.i.dfy.CheckWellformed__SplitModel.__default.lemmaChildrenConditionsCutoffNode.smt2 |   1.358s |95.452MiB|
|d_lvbkv-Impl-IOImpl.i.dfy.CheckWellformed__IOImpl.__default.getFreeLoc.smt2                |   1.629s |95.268MiB|
|d_komodo-verified-map_common.gen.dfyImpl___module.__default.lemma__read__l2pte__zero.smt2  |   1.424s |94.72MiB|
|d_fvbkv-Impl-InsertModel.i.dfy.CheckWellformed__InsertModel.__default.insertCorrect.smt2   |   1.475s |93.884MiB|
|d_komodo-verified-finalise.gen.dfyImpl___module.__default.lemma__kom__smc__finalise__success__helper2.smt2 |   1.448s |93.696MiB|
|d_lvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.ValToBucket.smt2        |   1.343s |93.34MiB|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.ReadSectorCorrect.smt2                  |   1.504s |92.928MiB|
|d_fvbkv-Impl-CacheImpl.i.dfy.CheckWellformed__CacheImpl.MutCache.Remove.smt2               |   1.581s |91.608MiB|
|d_lvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.CheckWellformed__ByteSystem.__default.I.smt2 |   1.259s |89.812MiB|
|d_komodo-verified-exception_handlers.gen.dfyCheckWellformed___module.__default.lemma__pageDbDispatcherVerifyStateCorresponds.smt2 |   1.244s |88.796MiB|
|d_komodo-verified-sha-hmac.gen.dfyCheckWellformed___module.__default.va__lemma__hmac__outer__prep__ctx.smt2 |   1.290s |88.584MiB|
|d_fvbkv-Impl-StateModel.i.dfy.CheckWellformed__StateModel.__default.WFSector.smt2          |   1.447s |88.484MiB|
|d_lvbkv-Impl-CacheImpl.i.dfy.Impl__CacheImpl.LMutCache.NodePartialFlush.smt2               |   1.340s |87.62MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BlockInterface.i.dfy.CheckWellformed__BlockInterface.__default.IsStatePath.smt2  |   0.201s  |   0.201s  |   0.000s  | 0.0%|
|d_fvbkv-Betree-Graph.i.dfy.Impl__Graph.__default.AcyclicGraphImpliesSimplePath.smt2         |   0.210s  |   0.210s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.NewRequestReadNodeDoesntOverlap.smt2  |   0.963s  |   0.963s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-DiskLayout.i.dfy.CheckWellformed__DiskLayout.__default.JournalBackLocation.smt2  |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.CheckWellformed__JournalSystem.__default.FreezeStepPreservesJournals.smt2  |   0.598s  |   0.598s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.Impl__JournalSystem.__default.ProcessWriteSuperblockPreservesJournals.smt2  |   0.855s  |   0.855s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-AsyncDiskModel.s.dfy.CheckWellformed__AsyncDisk.__default.AckRead.smt2  |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CacheImpl.i.dfy.CheckWellformed__CacheImpl.MutCache.Remove.smt2                |   1.581s  |   1.581s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterImpl.i.dfy.CheckWellformed__CommitterImpl.Committer.__ctor.smt2       |   0.791s  |   0.791s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CoordinationModel.i.dfy.CheckWellformed__CoordinationModel.__default.initialization.smt2  |   1.696s  |   1.696s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.ReadSectorCorrect.smt2                   |   1.504s  |   1.504s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-InsertModel.i.dfy.CheckWellformed__InsertModel.__default.insertCorrect.smt2    |   1.475s  |   1.475s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.CheckWellformed__JournalistMarshallingModel.__default.hasChecksums.smt2  |   0.314s  |   0.314s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MainHandlers.i.dfy.CheckWellformed__MainHandlers.__default.InitState.smt2      |   2.114s  |   2.114s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-StateModel.i.dfy.CheckWellformed__StateModel.__default.WFSector.smt2           |   1.447s  |   1.447s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-SuccModel.i.dfy.CheckWellformed__SuccModel.__default.getPathInternal.smt2      |   1.640s  |   1.640s  |   0.000s  | 0.0%|
|d_fvbkv-MapSpec-TSJ.i.dfy.Impl__TSJ.__default.PushSyncStepPreservesInv.smt2                 |   0.250s  |   0.250s  |   0.000s  | 0.0%|
|d_fvbkv-MapSpec-TSJMap_Refines_ThreeStateVersionedMap.i.dfy.Impl__TSJMap__Refines__ThreeStateVersionedMap.__default.apply__path.smt2  |   0.277s  |   0.277s  |   0.000s  | 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupUpperBound.smt2  |   0.527s  |   0.527s  |   0.000s  | 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupVisitsWFNodes.smt2  |   0.535s  |   0.535s  |   0.000s  | 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.Impl__PivotBetreeSpecRefinement.__default.InterpretBucketStackEqInterpretLookup.smt2  |   0.694s  |   0.694s  |   0.000s  | 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpecWFNodes.i.dfy.Impl__PivotBetreeSpecWFNodes.__default.ValidRepivotWFNodes.smt2  |   0.538s  |   0.538s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-sequences.i.dfy.Impl__Sequences.__default.FlattenLengthSubSeq.smt2         |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-total_order.i.dfy.CheckWellformed__Total__Order.__default.strictlySortedInsert2.smt2  |   0.203s  |   0.203s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-total_order.i.dfy.Impl__Uint32__Order.__default.LargestLteIsUnique2.smt2   |   0.206s  |   0.206s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-total_order_impl.i.dfy.CheckWellformed__Byte__Order__Impl.__default.ArrayLargestLtePlus1.smt2  |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.CheckWellformed__PackedStringArray.__default.LargestLte.smt2  |   0.281s  |   0.281s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-KMBtree.i.dfy.Impl__KMBtreeModel.__default.SplitIndexInterpretation2.smt2  |   0.341s  |   0.341s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.CheckWellformed__TestMutableBtree.__default.MaxKeysPerLeaf.smt2  |   0.297s  |   0.297s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__TestMutableBtree.__default.SubIndex.smt2  |   0.343s  |   0.343s  |   0.000s  | 0.0%|
|d_komodo-verified-ARMdef.s.dfyCheckWellformed___module.__default.ValidGlobalOffset.smt2     |   0.287s  |   0.287s  |   0.000s  | 0.0%|
|d_komodo-verified-ARMdef.s.dfyCheckWellformed___module.__default.ValidModeEncoding.smt2     |   0.284s  |   0.284s  |   0.000s  | 0.0%|
|d_komodo-verified-ARMprint.s.dfyImpl___module.__default.printGlobal.smt2                    |   0.257s  |   0.257s  |   0.000s  | 0.0%|
|d_komodo-verified-Seq.dfyCheckWellformed___module.__default.MapSeqToSeq.smt2                |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|d_komodo-verified-attest_helpers.gen.dfyImpl___module.__default.va__lemma__mem__move__global.smt2  |   2.634s  |   2.634s  |   0.000s  | 0.0%|
|d_komodo-verified-bitvectors.i.dfyCheckWellformed___module.__default.lemma__LeftShift2.smt2  |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|d_komodo-verified-bitvectors.i.dfyCheckWellformed___module.__default.lemma__RightShift2.smt2  |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.gen.dfyCheckWellformed___module.__default.va__lemma__smc__enter__err.smt2  |   0.819s  |   0.819s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.i.dfyCheckWellformed___module.__default.lemma__singlestep__execution.smt2  |   0.509s  |   0.509s  |   0.000s  | 0.0%|
|d_komodo-verified-exception_handlers.gen.dfyCheckWellformed___module.__default.lemma__pageDbDispatcherVerifyStateCorresponds.smt2  |   1.244s  |   1.244s  |   0.000s  | 0.0%|
|d_komodo-verified-exceptions.i.dfyCheckWellformed___module.__default.lemma__Establish__InterruptContinuationPrecondition.smt2  |   0.573s  |   0.573s  |   0.000s  | 0.0%|
|d_komodo-verified-finalise.gen.dfyImpl___module.__default.lemma__kom__smc__finalise__success__helper2.smt2  |   1.448s  |   1.448s  |   0.000s  | 0.0%|
|d_komodo-verified-kom_common.i.dfyImpl___module.__default.lemma__ValidMemRangeExPageTable__persists.smt2  |   1.687s  |   1.687s  |   0.000s  | 0.0%|
|d_komodo-verified-kom_common.s.dfyCheckWellformed___module.__default.AttestKey.smt2         |   0.317s  |   0.317s  |   0.000s  | 0.0%|
|d_komodo-verified-kom_utils.gen.dfyCheckWellformed___module.__default.va__code__STRx.smt2   |   0.549s  |   0.549s  |   0.000s  | 0.0%|
|d_komodo-verified-kom_utils.gen.dfyImpl___module.__default.va__lemma__page__monvaddr__impl.smt2  |   1.740s  |   1.740s  |   0.000s  | 0.0%|
|d_komodo-verified-map_common.gen.dfyImpl___module.__default.lemma__read__l2pte__zero.smt2   |   1.424s  |   1.424s  |   0.000s  | 0.0%|
|d_komodo-verified-pagedb.s.dfyCheckWellformed___module.__default.validInsecurePageNr.smt2   |   0.380s  |   0.380s  |   0.000s  | 0.0%|
|d_komodo-verified-ptebits.i.dfyCheckWellformed___module.__default.lemma__nonexec__mapping.smt2  |   0.440s  |   0.440s  |   0.000s  | 0.0%|
|d_komodo-verified-ptebits.i.dfyImpl___module.__default.lemma__BitOrNineIsLikePlus.smt2      |   0.655s  |   0.655s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-hmac.gen.dfyCheckWellformed___module.__default.va__lemma__hmac__outer__prep__ctx.smt2  |   1.290s  |   1.290s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-sha256-body-00-15.gen.dfyCheckWellformed___module.__default.va__if__abstract__Body__00__15UnrolledRecursive.smt2  |   0.690s  |   0.690s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-sha256-body-16-xx.gen.dfyImpl___module.__default.va__refined__Body__16__XXUnroller_split0.smt2  |   2.036s  |   2.036s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-sha256-helpers.i.dfyCheckWellformed___module.__default.lemma__BitwiseAdd32Associates5.smt2  |   0.422s  |   0.422s  |   0.000s  | 0.0%|
|d_komodo-verified-stop.gen.dfyCheckWellformed___module.__default.va__lemma__kom__smc__stop.smt2  |   0.642s  |   0.642s  |   0.000s  | 0.0%|
|d_komodo-verified-valedecls.gen.dfyImpl___module.__default.va__lemma__MOVShift.smt2         |   0.378s  |   0.378s  |   0.000s  | 0.0%|
|d_komodo-verified-valesupp.i.dfyCheckWellformed___module.__default.va__lemma__whileTrue.smt2  |   0.325s  |   0.325s  |   0.000s  | 0.0%|
|d_komodo-verified-verify.gen.dfyCheckWellformed___module.__default.va__code__svc__returning__verify.smt2  |   1.321s  |   1.321s  |   0.000s  | 0.0%|
|d_komodo-verified-words_and_bytes.i.dfyImpl___module.__default.lemma__BytesToWord__WordToBytes__inverses.smt2  |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|d_komodo-verified-words_and_bytes.s.dfyCheckWellformed___module.__default.ConcatenateSeqs.smt2  |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|d_lvbkv-Betree-Betree_Refines_Map.i.dfy.CheckWellformed__Betree__Refines__Map.__default.RefinesInit.smt2  |   0.417s  |   0.417s  |   0.000s  | 0.0%|
|d_lvbkv-Betree-BlockInterface.i.dfy.Impl__BlockInterface.__default.Transaction3Steps.smt2   |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.NewRequestReadIndirectionTableIsValid.smt2  |   4.573s  |   4.573s  |   0.000s  | 0.0%|
|d_lvbkv-BlockCacheSystem-DiskLayout.i.dfy.CheckWellformed__DiskLayout.__default.locContainedInCircularJournalRange.smt2  |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|d_lvbkv-BlockCacheSystem-JournalSystem.i.dfy.CheckWellformed__JournalSystem.__default.NoOpStepPreservesJournals.smt2  |   0.687s  |   0.687s  |   0.000s  | 0.0%|
|d_lvbkv-ByteBlockCacheSystem-AsyncDiskModel.s.dfy.CheckWellformed__AsyncDisk.__default.ChecksumChecksOut.smt2  |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|d_lvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.CheckWellformed__ByteSystem.__default.I.smt2  |   1.259s  |   1.259s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-CacheImpl.i.dfy.Impl__CacheImpl.LMutCache.NodePartialFlush.smt2                |   1.340s  |   1.340s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-CoordinationImpl.i.dfy.Impl__CoordinationImpl.__default.pushSync.smt2          |   1.847s  |   1.847s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-IOImpl.i.dfy.CheckWellformed__IOImpl.__default.getFreeLoc.smt2                 |   1.629s  |   1.629s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-JournalistImpl.i.dfy.CheckWellformed__JournalistImpl.__default.MaxPossibleEntries.smt2  |   0.349s  |   0.349s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.ValToBucket.smt2         |   1.343s  |   1.343s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-SplitModel.i.dfy.CheckWellformed__SplitModel.__default.lemmaChildrenConditionsCutoffNode.smt2  |   1.358s  |   1.358s  |   0.000s  | 0.0%|
|d_lvbkv-MapSpec-TSJMap.i.dfy.Impl__TSJMap.__default.Move2to3StepPreservesInv.smt2           |   0.277s  |   0.277s  |   0.000s  | 0.0%|
|d_lvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.CheckWellformed__PivotBetreeSpecRefinement.__default.INode.smt2  |   0.730s  |   0.730s  |   0.000s  | 0.0%|
|d_lvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.CheckWellformed__PivotBetreeSpecRefinement.__default.InterpretBucketStack.smt2  |   0.686s  |   0.686s  |   0.000s  | 0.0%|
|d_lvbkv-PivotBetree-PivotBetreeSpecWFNodes.i.dfy.CheckWellformed__PivotBetreeSpecWFNodes.__default.bucket__msgs__equiv.smt2  |   0.526s  |   0.526s  |   0.000s  | 0.0%|
|d_lvbkv-PivotBetree-StatesViewPivotBetree_Refines_StatesViewMap.i.dfy.CheckWellformed__StatesViewPivotBetree__Refines__StatesViewMap.__default.RefinesNextStep.smt2  |   0.787s  |   0.787s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-BitsetLemmas.i.dfy.CheckWellformed__BitsetLemmas.__default.bit.smt2        |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-BitsetLemmas.i.dfy.CheckWellformed__BitsetLemmas.__default.bit__comp__ne__expanded.smt2  |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-Message.i.dfy.CheckWellformed__ValueMessage.__default.EncodableMessageSeq.smt2  |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-MutableVec.i.dfy.CheckWellformed__MutableVec.Vec.insert.smt2               |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-total_order.i.dfy.Impl__Integer__Order.__default.StrictlySortedImpliesSorted.smt2  |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-total_order_impl.i.dfy.Impl__Byte__Order__Impl.__default.ComputeIsSorted.smt2  |   0.212s  |   0.212s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-total_order_impl.i.dfy.Impl__Uint64__Order__Impl.__default.BatchLargestLte.smt2  |   0.229s  |   0.229s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Checksums-BitLemmas.i.dfy.Impl__BitLemmas.__default.bits__of__int__combine.smt2  |   0.452s  |   0.452s  |   0.000s  | 0.0%|
|d_lvbkv-lib-DataStructures-KMBtree.i.dfy.Impl__KMBtreeModel.__default.SplitChildOfIndexPreservesAllKeys.smt2  |   0.360s  |   0.360s  |   0.000s  | 0.0%|
|d_lvbkv-lib-DataStructures-LinearMutableMap.i.dfy.CheckWellformed__LinearMutableMap.__default.FixedSizeUpdateBySlot.smt2  |   0.286s  |   0.286s  |   0.000s  | 0.0%|
|d_lvbkv-lib-DataStructures-LinearMutableMapBase.i.dfy.CheckWellformed__LinearMutableMapBase.__default.lshift.smt2  |   0.189s  |   0.189s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Math-Math.i.dfy.Impl__Math.__default.lemma__power2__div__is__sub.smt2           |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|s_komodo-1440.0.smt2                                                                        |   0.426s  |   0.426s  |   0.000s  | 0.0%|
|s_komodo-1441.2.smt2                                                                        |   0.252s  |   0.252s  |   0.000s  | 0.0%|
|s_komodo-1456.4.smt2                                                                        |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|s_komodo-1457.2.smt2                                                                        |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|s_komodo-1466.1.smt2                                                                        |   0.279s  |   0.279s  |   0.000s  | 0.0%|
|s_komodo-1469.1.smt2                                                                        |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|s_komodo-1470.0.smt2                                                                        |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|s_komodo-1484.7.smt2                                                                        |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|s_komodo-1486.1.smt2                                                                        |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|s_komodo-1487.4.smt2                                                                        |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|s_komodo-1490.0.smt2                                                                        |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|s_komodo-1493.3.smt2                                                                        |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|s_komodo-1494.5.smt2                                                                        |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|s_komodo-1496.2.smt2                                                                        |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|s_komodo-1500.4.smt2                                                                        |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|s_komodo-1500.6.smt2                                                                        |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|s_komodo-1501.7.smt2                                                                        |   0.774s  |   0.774s  |   0.000s  | 0.0%|
|s_komodo-1502.2.smt2                                                                        |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|s_komodo-1503.6.smt2                                                                        |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|s_komodo-1505.3.smt2                                                                        |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|s_komodo-1506.1.smt2                                                                        |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|s_komodo-1511.8.smt2                                                                        |   0.320s  |   0.320s  |   0.000s  | 0.0%|
|s_komodo-1516.11.smt2                                                                       |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|s_komodo-1516.7.smt2                                                                        |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|s_komodo-1526.0.smt2                                                                        |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|s_komodo-1531.0.smt2                                                                        |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|s_komodo-1533.7.smt2                                                                        |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|s_komodo-1534.9.smt2                                                                        |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|s_komodo-1544.3.smt2                                                                        |   0.046s  |   0.046s  |   0.000s  | 0.0%|
</details>
