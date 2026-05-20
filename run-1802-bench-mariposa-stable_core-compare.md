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
Job tag: bench-mariposa-stable_core
Runner: rise-runner-2
Z3 repo: CanCebeci/z3
Z3 commit: 18cb7654b9931442b52ef68bdb2c6643b1b01392
Z3 branch: master-clean
Z3 options: "-T:20"
Z3 inputs: inputs/mariposa/stable_core
Z3 commit message: Update generation number of already-internalized enodes

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: bench-mariposa-stable_core
Runner: rise-runner-2
Z3 repo: CanCebeci/z3
Z3 commit: 18cb7654b9931442b52ef68bdb2c6643b1b01392
Z3 branch: master-clean
Z3 options: "-T:20"
Z3 inputs: inputs/mariposa/stable_core
Z3 commit message: Update generation number of already-internalized enodes

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BlockInterface.i.dfy.CheckWellformed__BlockInterface.__default.IsStatePath.smt2  |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|d_fvbkv-Betree-Graph.i.dfy.Impl__Graph.__default.AcyclicGraphImpliesSimplePath.smt2         |   0.233s  |   0.233s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.NewRequestReadNodeDoesntOverlap.smt2  |   0.797s  |   0.797s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-DiskLayout.i.dfy.CheckWellformed__DiskLayout.__default.JournalBackLocation.smt2  |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.CheckWellformed__JournalSystem.__default.FreezeStepPreservesJournals.smt2  |   0.535s  |   0.535s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.Impl__JournalSystem.__default.ProcessWriteSuperblockPreservesJournals.smt2  |   0.825s  |   0.825s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-AsyncDiskModel.s.dfy.CheckWellformed__AsyncDisk.__default.AckRead.smt2  |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CacheImpl.i.dfy.CheckWellformed__CacheImpl.MutCache.Remove.smt2                |   1.238s  |   1.238s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterImpl.i.dfy.CheckWellformed__CommitterImpl.Committer.__ctor.smt2       |   0.644s  |   0.644s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CoordinationModel.i.dfy.CheckWellformed__CoordinationModel.__default.initialization.smt2  |   1.480s  |   1.480s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.ReadSectorCorrect.smt2                   |   1.338s  |   1.338s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-InsertModel.i.dfy.CheckWellformed__InsertModel.__default.insertCorrect.smt2    |   1.264s  |   1.264s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.CheckWellformed__JournalistMarshallingModel.__default.hasChecksums.smt2  |   0.243s  |   0.243s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MainHandlers.i.dfy.CheckWellformed__MainHandlers.__default.InitState.smt2      |   1.922s  |   1.922s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-StateModel.i.dfy.CheckWellformed__StateModel.__default.WFSector.smt2           |   1.102s  |   1.102s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-SuccModel.i.dfy.CheckWellformed__SuccModel.__default.getPathInternal.smt2      |   1.557s  |   1.557s  |   0.000s  | 0.0%|
|d_fvbkv-MapSpec-TSJ.i.dfy.Impl__TSJ.__default.PushSyncStepPreservesInv.smt2                 |   0.192s  |   0.192s  |   0.000s  | 0.0%|
|d_fvbkv-MapSpec-TSJMap_Refines_ThreeStateVersionedMap.i.dfy.Impl__TSJMap__Refines__ThreeStateVersionedMap.__default.apply__path.smt2  |   0.222s  |   0.222s  |   0.000s  | 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupUpperBound.smt2  |   0.409s  |   0.409s  |   0.000s  | 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupVisitsWFNodes.smt2  |   0.391s  |   0.391s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BlockInterface.i.dfy.CheckWellformed__BlockInterface.__default.IsStatePath.smt2  |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|d_fvbkv-Betree-Graph.i.dfy.Impl__Graph.__default.AcyclicGraphImpliesSimplePath.smt2         |   0.233s  |   0.233s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.NewRequestReadNodeDoesntOverlap.smt2  |   0.797s  |   0.797s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-DiskLayout.i.dfy.CheckWellformed__DiskLayout.__default.JournalBackLocation.smt2  |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.CheckWellformed__JournalSystem.__default.FreezeStepPreservesJournals.smt2  |   0.535s  |   0.535s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.Impl__JournalSystem.__default.ProcessWriteSuperblockPreservesJournals.smt2  |   0.825s  |   0.825s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-AsyncDiskModel.s.dfy.CheckWellformed__AsyncDisk.__default.AckRead.smt2  |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CacheImpl.i.dfy.CheckWellformed__CacheImpl.MutCache.Remove.smt2                |   1.238s  |   1.238s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterImpl.i.dfy.CheckWellformed__CommitterImpl.Committer.__ctor.smt2       |   0.644s  |   0.644s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CoordinationModel.i.dfy.CheckWellformed__CoordinationModel.__default.initialization.smt2  |   1.480s  |   1.480s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.ReadSectorCorrect.smt2                   |   1.338s  |   1.338s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-InsertModel.i.dfy.CheckWellformed__InsertModel.__default.insertCorrect.smt2    |   1.264s  |   1.264s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.CheckWellformed__JournalistMarshallingModel.__default.hasChecksums.smt2  |   0.243s  |   0.243s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MainHandlers.i.dfy.CheckWellformed__MainHandlers.__default.InitState.smt2      |   1.922s  |   1.922s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-StateModel.i.dfy.CheckWellformed__StateModel.__default.WFSector.smt2           |   1.102s  |   1.102s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-SuccModel.i.dfy.CheckWellformed__SuccModel.__default.getPathInternal.smt2      |   1.557s  |   1.557s  |   0.000s  | 0.0%|
|d_fvbkv-MapSpec-TSJ.i.dfy.Impl__TSJ.__default.PushSyncStepPreservesInv.smt2                 |   0.192s  |   0.192s  |   0.000s  | 0.0%|
|d_fvbkv-MapSpec-TSJMap_Refines_ThreeStateVersionedMap.i.dfy.Impl__TSJMap__Refines__ThreeStateVersionedMap.__default.apply__path.smt2  |   0.222s  |   0.222s  |   0.000s  | 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupUpperBound.smt2  |   0.409s  |   0.409s  |   0.000s  | 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupVisitsWFNodes.smt2  |   0.391s  |   0.391s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BlockInterface.i.dfy.CheckWellformed__BlockInterface.__default.IsStatePath.smt2  |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|d_fvbkv-Betree-Graph.i.dfy.Impl__Graph.__default.AcyclicGraphImpliesSimplePath.smt2         |   0.233s  |   0.233s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.NewRequestReadNodeDoesntOverlap.smt2  |   0.797s  |   0.797s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-DiskLayout.i.dfy.CheckWellformed__DiskLayout.__default.JournalBackLocation.smt2  |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.CheckWellformed__JournalSystem.__default.FreezeStepPreservesJournals.smt2  |   0.535s  |   0.535s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.Impl__JournalSystem.__default.ProcessWriteSuperblockPreservesJournals.smt2  |   0.825s  |   0.825s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-AsyncDiskModel.s.dfy.CheckWellformed__AsyncDisk.__default.AckRead.smt2  |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CacheImpl.i.dfy.CheckWellformed__CacheImpl.MutCache.Remove.smt2                |   1.238s  |   1.238s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterImpl.i.dfy.CheckWellformed__CommitterImpl.Committer.__ctor.smt2       |   0.644s  |   0.644s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CoordinationModel.i.dfy.CheckWellformed__CoordinationModel.__default.initialization.smt2  |   1.480s  |   1.480s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.ReadSectorCorrect.smt2                   |   1.338s  |   1.338s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-InsertModel.i.dfy.CheckWellformed__InsertModel.__default.insertCorrect.smt2    |   1.264s  |   1.264s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.CheckWellformed__JournalistMarshallingModel.__default.hasChecksums.smt2  |   0.243s  |   0.243s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MainHandlers.i.dfy.CheckWellformed__MainHandlers.__default.InitState.smt2      |   1.922s  |   1.922s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-StateModel.i.dfy.CheckWellformed__StateModel.__default.WFSector.smt2           |   1.102s  |   1.102s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-SuccModel.i.dfy.CheckWellformed__SuccModel.__default.getPathInternal.smt2      |   1.557s  |   1.557s  |   0.000s  | 0.0%|
|d_fvbkv-MapSpec-TSJ.i.dfy.Impl__TSJ.__default.PushSyncStepPreservesInv.smt2                 |   0.192s  |   0.192s  |   0.000s  | 0.0%|
|d_fvbkv-MapSpec-TSJMap_Refines_ThreeStateVersionedMap.i.dfy.Impl__TSJMap__Refines__ThreeStateVersionedMap.__default.apply__path.smt2  |   0.222s  |   0.222s  |   0.000s  | 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupUpperBound.smt2  |   0.409s  |   0.409s  |   0.000s  | 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupVisitsWFNodes.smt2  |   0.391s  |   0.391s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BlockInterface.i.dfy.CheckWellformed__BlockInterface.__default.IsStatePath.smt2  |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|d_fvbkv-Betree-Graph.i.dfy.Impl__Graph.__default.AcyclicGraphImpliesSimplePath.smt2         |   0.233s  |   0.233s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.NewRequestReadNodeDoesntOverlap.smt2  |   0.797s  |   0.797s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-DiskLayout.i.dfy.CheckWellformed__DiskLayout.__default.JournalBackLocation.smt2  |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.CheckWellformed__JournalSystem.__default.FreezeStepPreservesJournals.smt2  |   0.535s  |   0.535s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.Impl__JournalSystem.__default.ProcessWriteSuperblockPreservesJournals.smt2  |   0.825s  |   0.825s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-AsyncDiskModel.s.dfy.CheckWellformed__AsyncDisk.__default.AckRead.smt2  |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CacheImpl.i.dfy.CheckWellformed__CacheImpl.MutCache.Remove.smt2                |   1.238s  |   1.238s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterImpl.i.dfy.CheckWellformed__CommitterImpl.Committer.__ctor.smt2       |   0.644s  |   0.644s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CoordinationModel.i.dfy.CheckWellformed__CoordinationModel.__default.initialization.smt2  |   1.480s  |   1.480s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.ReadSectorCorrect.smt2                   |   1.338s  |   1.338s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-InsertModel.i.dfy.CheckWellformed__InsertModel.__default.insertCorrect.smt2    |   1.264s  |   1.264s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.CheckWellformed__JournalistMarshallingModel.__default.hasChecksums.smt2  |   0.243s  |   0.243s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MainHandlers.i.dfy.CheckWellformed__MainHandlers.__default.InitState.smt2      |   1.922s  |   1.922s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-StateModel.i.dfy.CheckWellformed__StateModel.__default.WFSector.smt2           |   1.102s  |   1.102s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-SuccModel.i.dfy.CheckWellformed__SuccModel.__default.getPathInternal.smt2      |   1.557s  |   1.557s  |   0.000s  | 0.0%|
|d_fvbkv-MapSpec-TSJ.i.dfy.Impl__TSJ.__default.PushSyncStepPreservesInv.smt2                 |   0.192s  |   0.192s  |   0.000s  | 0.0%|
|d_fvbkv-MapSpec-TSJMap_Refines_ThreeStateVersionedMap.i.dfy.Impl__TSJMap__Refines__ThreeStateVersionedMap.__default.apply__path.smt2  |   0.222s  |   0.222s  |   0.000s  | 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupUpperBound.smt2  |   0.409s  |   0.409s  |   0.000s  | 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupVisitsWFNodes.smt2  |   0.391s  |   0.391s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.NewRequestReadIndirectionTableIsValid.smt2 |   4.319s |118.0MiB|
|d_komodo-verified-attest_helpers.gen.dfyImpl___module.__default.va__lemma__mem__move__global.smt2 |   2.624s |99.0MiB|
|d_komodo-verified-kom_common.i.dfyImpl___module.__default.lemma__ValidMemRangeExPageTable__persists.smt2 |   2.548s |98.364MiB|
|d_komodo-verified-sha-sha256-body-16-xx.gen.dfyImpl___module.__default.va__refined__Body__16__XXUnroller_split0.smt2 |   2.149s |100.0MiB|
|d_fvbkv-Impl-MainHandlers.i.dfy.CheckWellformed__MainHandlers.__default.InitState.smt2     |   1.922s |146.0MiB|
|d_lvbkv-Impl-CoordinationImpl.i.dfy.Impl__CoordinationImpl.__default.pushSync.smt2         |   1.786s |136.0MiB|
|d_komodo-verified-kom_utils.gen.dfyImpl___module.__default.va__lemma__page__monvaddr__impl.smt2 |   1.561s |64.36MiB|
|d_fvbkv-Impl-SuccModel.i.dfy.CheckWellformed__SuccModel.__default.getPathInternal.smt2     |   1.557s |99.436MiB|
|d_fvbkv-Impl-CoordinationModel.i.dfy.CheckWellformed__CoordinationModel.__default.initialization.smt2 |   1.480s |98.0MiB|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.ReadSectorCorrect.smt2                  |   1.338s |93.724MiB|
|d_lvbkv-Impl-SplitModel.i.dfy.CheckWellformed__SplitModel.__default.lemmaChildrenConditionsCutoffNode.smt2 |   1.297s |96.02MiB|
|d_lvbkv-Impl-IOImpl.i.dfy.CheckWellformed__IOImpl.__default.getFreeLoc.smt2                |   1.269s |95.64MiB|
|d_lvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.ValToBucket.smt2        |   1.264s |93.976MiB|
|d_fvbkv-Impl-InsertModel.i.dfy.CheckWellformed__InsertModel.__default.insertCorrect.smt2   |   1.264s |94.48MiB|
|d_fvbkv-Impl-CacheImpl.i.dfy.CheckWellformed__CacheImpl.MutCache.Remove.smt2               |   1.238s |92.968MiB|
|d_komodo-verified-exception_handlers.gen.dfyCheckWellformed___module.__default.lemma__pageDbDispatcherVerifyStateCorresponds.smt2 |   1.129s |89.684MiB|
|d_lvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.CheckWellformed__ByteSystem.__default.I.smt2 |   1.129s |90.404MiB|
|d_fvbkv-Impl-StateModel.i.dfy.CheckWellformed__StateModel.__default.WFSector.smt2          |   1.102s |89.172MiB|
|d_lvbkv-Impl-CacheImpl.i.dfy.Impl__CacheImpl.LMutCache.NodePartialFlush.smt2               |   1.101s |88.452MiB|
|d_komodo-verified-finalise.gen.dfyImpl___module.__default.lemma__kom__smc__finalise__success__helper2.smt2 |   1.098s |94.188MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.NewRequestReadIndirectionTableIsValid.smt2 |   4.319s |118.0MiB|
|d_komodo-verified-attest_helpers.gen.dfyImpl___module.__default.va__lemma__mem__move__global.smt2 |   2.624s |99.0MiB|
|d_komodo-verified-kom_common.i.dfyImpl___module.__default.lemma__ValidMemRangeExPageTable__persists.smt2 |   2.548s |98.364MiB|
|d_komodo-verified-sha-sha256-body-16-xx.gen.dfyImpl___module.__default.va__refined__Body__16__XXUnroller_split0.smt2 |   2.149s |100.0MiB|
|d_fvbkv-Impl-MainHandlers.i.dfy.CheckWellformed__MainHandlers.__default.InitState.smt2     |   1.922s |146.0MiB|
|d_lvbkv-Impl-CoordinationImpl.i.dfy.Impl__CoordinationImpl.__default.pushSync.smt2         |   1.786s |136.0MiB|
|d_komodo-verified-kom_utils.gen.dfyImpl___module.__default.va__lemma__page__monvaddr__impl.smt2 |   1.561s |64.36MiB|
|d_fvbkv-Impl-SuccModel.i.dfy.CheckWellformed__SuccModel.__default.getPathInternal.smt2     |   1.557s |99.436MiB|
|d_fvbkv-Impl-CoordinationModel.i.dfy.CheckWellformed__CoordinationModel.__default.initialization.smt2 |   1.480s |98.0MiB|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.ReadSectorCorrect.smt2                  |   1.338s |93.724MiB|
|d_lvbkv-Impl-SplitModel.i.dfy.CheckWellformed__SplitModel.__default.lemmaChildrenConditionsCutoffNode.smt2 |   1.297s |96.02MiB|
|d_lvbkv-Impl-IOImpl.i.dfy.CheckWellformed__IOImpl.__default.getFreeLoc.smt2                |   1.269s |95.64MiB|
|d_lvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.ValToBucket.smt2        |   1.264s |93.976MiB|
|d_fvbkv-Impl-InsertModel.i.dfy.CheckWellformed__InsertModel.__default.insertCorrect.smt2   |   1.264s |94.48MiB|
|d_fvbkv-Impl-CacheImpl.i.dfy.CheckWellformed__CacheImpl.MutCache.Remove.smt2               |   1.238s |92.968MiB|
|d_komodo-verified-exception_handlers.gen.dfyCheckWellformed___module.__default.lemma__pageDbDispatcherVerifyStateCorresponds.smt2 |   1.129s |89.684MiB|
|d_lvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.CheckWellformed__ByteSystem.__default.I.smt2 |   1.129s |90.404MiB|
|d_fvbkv-Impl-StateModel.i.dfy.CheckWellformed__StateModel.__default.WFSector.smt2          |   1.102s |89.172MiB|
|d_lvbkv-Impl-CacheImpl.i.dfy.Impl__CacheImpl.LMutCache.NodePartialFlush.smt2               |   1.101s |88.452MiB|
|d_komodo-verified-finalise.gen.dfyImpl___module.__default.lemma__kom__smc__finalise__success__helper2.smt2 |   1.098s |94.188MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BlockInterface.i.dfy.CheckWellformed__BlockInterface.__default.IsStatePath.smt2  |25.988MiB|25.988MiB|0B| 0.0%|
|d_fvbkv-Betree-Graph.i.dfy.Impl__Graph.__default.AcyclicGraphImpliesSimplePath.smt2         |26.532MiB|26.532MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.NewRequestReadNodeDoesntOverlap.smt2  |53.76MiB|53.76MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-DiskLayout.i.dfy.CheckWellformed__DiskLayout.__default.JournalBackLocation.smt2  |24.52MiB|24.52MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.CheckWellformed__JournalSystem.__default.FreezeStepPreservesJournals.smt2  |50.06MiB|50.06MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.Impl__JournalSystem.__default.ProcessWriteSuperblockPreservesJournals.smt2  |56.352MiB|56.352MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-AsyncDiskModel.s.dfy.CheckWellformed__AsyncDisk.__default.AckRead.smt2  |26.056MiB|26.056MiB|0B| 0.0%|
|d_fvbkv-Impl-CacheImpl.i.dfy.CheckWellformed__CacheImpl.MutCache.Remove.smt2                |92.968MiB|92.968MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterImpl.i.dfy.CheckWellformed__CommitterImpl.Committer.__ctor.smt2       |53.412MiB|53.412MiB|0B| 0.0%|
|d_fvbkv-Impl-CoordinationModel.i.dfy.CheckWellformed__CoordinationModel.__default.initialization.smt2  |98.0MiB|98.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.ReadSectorCorrect.smt2                   |93.724MiB|93.724MiB|0B| 0.0%|
|d_fvbkv-Impl-InsertModel.i.dfy.CheckWellformed__InsertModel.__default.insertCorrect.smt2    |94.48MiB|94.48MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.CheckWellformed__JournalistMarshallingModel.__default.hasChecksums.smt2  |30.596MiB|30.596MiB|0B| 0.0%|
|d_fvbkv-Impl-MainHandlers.i.dfy.CheckWellformed__MainHandlers.__default.InitState.smt2      |146.0MiB|146.0MiB|0B| 0.0%|
|d_fvbkv-Impl-StateModel.i.dfy.CheckWellformed__StateModel.__default.WFSector.smt2           |89.172MiB|89.172MiB|0B| 0.0%|
|d_fvbkv-Impl-SuccModel.i.dfy.CheckWellformed__SuccModel.__default.getPathInternal.smt2      |99.436MiB|99.436MiB|0B| 0.0%|
|d_fvbkv-MapSpec-TSJ.i.dfy.Impl__TSJ.__default.PushSyncStepPreservesInv.smt2                 |27.856MiB|27.856MiB|0B| 0.0%|
|d_fvbkv-MapSpec-TSJMap_Refines_ThreeStateVersionedMap.i.dfy.Impl__TSJMap__Refines__ThreeStateVersionedMap.__default.apply__path.smt2  |29.508MiB|29.508MiB|0B| 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupUpperBound.smt2  |44.488MiB|44.488MiB|0B| 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupVisitsWFNodes.smt2  |44.188MiB|44.188MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BlockInterface.i.dfy.CheckWellformed__BlockInterface.__default.IsStatePath.smt2  |25.988MiB|25.988MiB|0B| 0.0%|
|d_fvbkv-Betree-Graph.i.dfy.Impl__Graph.__default.AcyclicGraphImpliesSimplePath.smt2         |26.532MiB|26.532MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.NewRequestReadNodeDoesntOverlap.smt2  |53.76MiB|53.76MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-DiskLayout.i.dfy.CheckWellformed__DiskLayout.__default.JournalBackLocation.smt2  |24.52MiB|24.52MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.CheckWellformed__JournalSystem.__default.FreezeStepPreservesJournals.smt2  |50.06MiB|50.06MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.Impl__JournalSystem.__default.ProcessWriteSuperblockPreservesJournals.smt2  |56.352MiB|56.352MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-AsyncDiskModel.s.dfy.CheckWellformed__AsyncDisk.__default.AckRead.smt2  |26.056MiB|26.056MiB|0B| 0.0%|
|d_fvbkv-Impl-CacheImpl.i.dfy.CheckWellformed__CacheImpl.MutCache.Remove.smt2                |92.968MiB|92.968MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterImpl.i.dfy.CheckWellformed__CommitterImpl.Committer.__ctor.smt2       |53.412MiB|53.412MiB|0B| 0.0%|
|d_fvbkv-Impl-CoordinationModel.i.dfy.CheckWellformed__CoordinationModel.__default.initialization.smt2  |98.0MiB|98.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.ReadSectorCorrect.smt2                   |93.724MiB|93.724MiB|0B| 0.0%|
|d_fvbkv-Impl-InsertModel.i.dfy.CheckWellformed__InsertModel.__default.insertCorrect.smt2    |94.48MiB|94.48MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.CheckWellformed__JournalistMarshallingModel.__default.hasChecksums.smt2  |30.596MiB|30.596MiB|0B| 0.0%|
|d_fvbkv-Impl-MainHandlers.i.dfy.CheckWellformed__MainHandlers.__default.InitState.smt2      |146.0MiB|146.0MiB|0B| 0.0%|
|d_fvbkv-Impl-StateModel.i.dfy.CheckWellformed__StateModel.__default.WFSector.smt2           |89.172MiB|89.172MiB|0B| 0.0%|
|d_fvbkv-Impl-SuccModel.i.dfy.CheckWellformed__SuccModel.__default.getPathInternal.smt2      |99.436MiB|99.436MiB|0B| 0.0%|
|d_fvbkv-MapSpec-TSJ.i.dfy.Impl__TSJ.__default.PushSyncStepPreservesInv.smt2                 |27.856MiB|27.856MiB|0B| 0.0%|
|d_fvbkv-MapSpec-TSJMap_Refines_ThreeStateVersionedMap.i.dfy.Impl__TSJMap__Refines__ThreeStateVersionedMap.__default.apply__path.smt2  |29.508MiB|29.508MiB|0B| 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupUpperBound.smt2  |44.488MiB|44.488MiB|0B| 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupVisitsWFNodes.smt2  |44.188MiB|44.188MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BlockInterface.i.dfy.CheckWellformed__BlockInterface.__default.IsStatePath.smt2  |25.988MiB|25.988MiB|0B| 0.0%|
|d_fvbkv-Betree-Graph.i.dfy.Impl__Graph.__default.AcyclicGraphImpliesSimplePath.smt2         |26.532MiB|26.532MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.NewRequestReadNodeDoesntOverlap.smt2  |53.76MiB|53.76MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-DiskLayout.i.dfy.CheckWellformed__DiskLayout.__default.JournalBackLocation.smt2  |24.52MiB|24.52MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.CheckWellformed__JournalSystem.__default.FreezeStepPreservesJournals.smt2  |50.06MiB|50.06MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.Impl__JournalSystem.__default.ProcessWriteSuperblockPreservesJournals.smt2  |56.352MiB|56.352MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-AsyncDiskModel.s.dfy.CheckWellformed__AsyncDisk.__default.AckRead.smt2  |26.056MiB|26.056MiB|0B| 0.0%|
|d_fvbkv-Impl-CacheImpl.i.dfy.CheckWellformed__CacheImpl.MutCache.Remove.smt2                |92.968MiB|92.968MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterImpl.i.dfy.CheckWellformed__CommitterImpl.Committer.__ctor.smt2       |53.412MiB|53.412MiB|0B| 0.0%|
|d_fvbkv-Impl-CoordinationModel.i.dfy.CheckWellformed__CoordinationModel.__default.initialization.smt2  |98.0MiB|98.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.ReadSectorCorrect.smt2                   |93.724MiB|93.724MiB|0B| 0.0%|
|d_fvbkv-Impl-InsertModel.i.dfy.CheckWellformed__InsertModel.__default.insertCorrect.smt2    |94.48MiB|94.48MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.CheckWellformed__JournalistMarshallingModel.__default.hasChecksums.smt2  |30.596MiB|30.596MiB|0B| 0.0%|
|d_fvbkv-Impl-MainHandlers.i.dfy.CheckWellformed__MainHandlers.__default.InitState.smt2      |146.0MiB|146.0MiB|0B| 0.0%|
|d_fvbkv-Impl-StateModel.i.dfy.CheckWellformed__StateModel.__default.WFSector.smt2           |89.172MiB|89.172MiB|0B| 0.0%|
|d_fvbkv-Impl-SuccModel.i.dfy.CheckWellformed__SuccModel.__default.getPathInternal.smt2      |99.436MiB|99.436MiB|0B| 0.0%|
|d_fvbkv-MapSpec-TSJ.i.dfy.Impl__TSJ.__default.PushSyncStepPreservesInv.smt2                 |27.856MiB|27.856MiB|0B| 0.0%|
|d_fvbkv-MapSpec-TSJMap_Refines_ThreeStateVersionedMap.i.dfy.Impl__TSJMap__Refines__ThreeStateVersionedMap.__default.apply__path.smt2  |29.508MiB|29.508MiB|0B| 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupUpperBound.smt2  |44.488MiB|44.488MiB|0B| 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupVisitsWFNodes.smt2  |44.188MiB|44.188MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BlockInterface.i.dfy.CheckWellformed__BlockInterface.__default.IsStatePath.smt2  |25.988MiB|25.988MiB|0B| 0.0%|
|d_fvbkv-Betree-Graph.i.dfy.Impl__Graph.__default.AcyclicGraphImpliesSimplePath.smt2         |26.532MiB|26.532MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.NewRequestReadNodeDoesntOverlap.smt2  |53.76MiB|53.76MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-DiskLayout.i.dfy.CheckWellformed__DiskLayout.__default.JournalBackLocation.smt2  |24.52MiB|24.52MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.CheckWellformed__JournalSystem.__default.FreezeStepPreservesJournals.smt2  |50.06MiB|50.06MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.Impl__JournalSystem.__default.ProcessWriteSuperblockPreservesJournals.smt2  |56.352MiB|56.352MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-AsyncDiskModel.s.dfy.CheckWellformed__AsyncDisk.__default.AckRead.smt2  |26.056MiB|26.056MiB|0B| 0.0%|
|d_fvbkv-Impl-CacheImpl.i.dfy.CheckWellformed__CacheImpl.MutCache.Remove.smt2                |92.968MiB|92.968MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterImpl.i.dfy.CheckWellformed__CommitterImpl.Committer.__ctor.smt2       |53.412MiB|53.412MiB|0B| 0.0%|
|d_fvbkv-Impl-CoordinationModel.i.dfy.CheckWellformed__CoordinationModel.__default.initialization.smt2  |98.0MiB|98.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.ReadSectorCorrect.smt2                   |93.724MiB|93.724MiB|0B| 0.0%|
|d_fvbkv-Impl-InsertModel.i.dfy.CheckWellformed__InsertModel.__default.insertCorrect.smt2    |94.48MiB|94.48MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.CheckWellformed__JournalistMarshallingModel.__default.hasChecksums.smt2  |30.596MiB|30.596MiB|0B| 0.0%|
|d_fvbkv-Impl-MainHandlers.i.dfy.CheckWellformed__MainHandlers.__default.InitState.smt2      |146.0MiB|146.0MiB|0B| 0.0%|
|d_fvbkv-Impl-StateModel.i.dfy.CheckWellformed__StateModel.__default.WFSector.smt2           |89.172MiB|89.172MiB|0B| 0.0%|
|d_fvbkv-Impl-SuccModel.i.dfy.CheckWellformed__SuccModel.__default.getPathInternal.smt2      |99.436MiB|99.436MiB|0B| 0.0%|
|d_fvbkv-MapSpec-TSJ.i.dfy.Impl__TSJ.__default.PushSyncStepPreservesInv.smt2                 |27.856MiB|27.856MiB|0B| 0.0%|
|d_fvbkv-MapSpec-TSJMap_Refines_ThreeStateVersionedMap.i.dfy.Impl__TSJMap__Refines__ThreeStateVersionedMap.__default.apply__path.smt2  |29.508MiB|29.508MiB|0B| 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupUpperBound.smt2  |44.488MiB|44.488MiB|0B| 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupVisitsWFNodes.smt2  |44.188MiB|44.188MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|d_fvbkv-Impl-MainHandlers.i.dfy.CheckWellformed__MainHandlers.__default.InitState.smt2     |   1.922s |146.0MiB|
|d_lvbkv-Impl-CoordinationImpl.i.dfy.Impl__CoordinationImpl.__default.pushSync.smt2         |   1.786s |136.0MiB|
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.NewRequestReadIndirectionTableIsValid.smt2 |   4.319s |118.0MiB|
|d_komodo-verified-sha-sha256-body-16-xx.gen.dfyImpl___module.__default.va__refined__Body__16__XXUnroller_split0.smt2 |   2.149s |100.0MiB|
|d_fvbkv-Impl-SuccModel.i.dfy.CheckWellformed__SuccModel.__default.getPathInternal.smt2     |   1.557s |99.436MiB|
|d_komodo-verified-attest_helpers.gen.dfyImpl___module.__default.va__lemma__mem__move__global.smt2 |   2.624s |99.0MiB|
|d_komodo-verified-kom_common.i.dfyImpl___module.__default.lemma__ValidMemRangeExPageTable__persists.smt2 |   2.548s |98.364MiB|
|d_fvbkv-Impl-CoordinationModel.i.dfy.CheckWellformed__CoordinationModel.__default.initialization.smt2 |   1.480s |98.0MiB|
|d_lvbkv-Impl-SplitModel.i.dfy.CheckWellformed__SplitModel.__default.lemmaChildrenConditionsCutoffNode.smt2 |   1.297s |96.02MiB|
|d_lvbkv-Impl-IOImpl.i.dfy.CheckWellformed__IOImpl.__default.getFreeLoc.smt2                |   1.269s |95.64MiB|
|d_komodo-verified-map_common.gen.dfyImpl___module.__default.lemma__read__l2pte__zero.smt2  |   1.077s |95.264MiB|
|d_fvbkv-Impl-InsertModel.i.dfy.CheckWellformed__InsertModel.__default.insertCorrect.smt2   |   1.264s |94.48MiB|
|d_komodo-verified-finalise.gen.dfyImpl___module.__default.lemma__kom__smc__finalise__success__helper2.smt2 |   1.098s |94.188MiB|
|d_lvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.ValToBucket.smt2        |   1.264s |93.976MiB|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.ReadSectorCorrect.smt2                  |   1.338s |93.724MiB|
|d_fvbkv-Impl-CacheImpl.i.dfy.CheckWellformed__CacheImpl.MutCache.Remove.smt2               |   1.238s |92.968MiB|
|d_lvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.CheckWellformed__ByteSystem.__default.I.smt2 |   1.129s |90.404MiB|
|d_komodo-verified-exception_handlers.gen.dfyCheckWellformed___module.__default.lemma__pageDbDispatcherVerifyStateCorresponds.smt2 |   1.129s |89.684MiB|
|d_fvbkv-Impl-StateModel.i.dfy.CheckWellformed__StateModel.__default.WFSector.smt2          |   1.102s |89.172MiB|
|d_komodo-verified-sha-hmac.gen.dfyCheckWellformed___module.__default.va__lemma__hmac__outer__prep__ctx.smt2 |   1.002s |89.048MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|d_fvbkv-Impl-MainHandlers.i.dfy.CheckWellformed__MainHandlers.__default.InitState.smt2     |   1.922s |146.0MiB|
|d_lvbkv-Impl-CoordinationImpl.i.dfy.Impl__CoordinationImpl.__default.pushSync.smt2         |   1.786s |136.0MiB|
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.NewRequestReadIndirectionTableIsValid.smt2 |   4.319s |118.0MiB|
|d_komodo-verified-sha-sha256-body-16-xx.gen.dfyImpl___module.__default.va__refined__Body__16__XXUnroller_split0.smt2 |   2.149s |100.0MiB|
|d_fvbkv-Impl-SuccModel.i.dfy.CheckWellformed__SuccModel.__default.getPathInternal.smt2     |   1.557s |99.436MiB|
|d_komodo-verified-attest_helpers.gen.dfyImpl___module.__default.va__lemma__mem__move__global.smt2 |   2.624s |99.0MiB|
|d_komodo-verified-kom_common.i.dfyImpl___module.__default.lemma__ValidMemRangeExPageTable__persists.smt2 |   2.548s |98.364MiB|
|d_fvbkv-Impl-CoordinationModel.i.dfy.CheckWellformed__CoordinationModel.__default.initialization.smt2 |   1.480s |98.0MiB|
|d_lvbkv-Impl-SplitModel.i.dfy.CheckWellformed__SplitModel.__default.lemmaChildrenConditionsCutoffNode.smt2 |   1.297s |96.02MiB|
|d_lvbkv-Impl-IOImpl.i.dfy.CheckWellformed__IOImpl.__default.getFreeLoc.smt2                |   1.269s |95.64MiB|
|d_komodo-verified-map_common.gen.dfyImpl___module.__default.lemma__read__l2pte__zero.smt2  |   1.077s |95.264MiB|
|d_fvbkv-Impl-InsertModel.i.dfy.CheckWellformed__InsertModel.__default.insertCorrect.smt2   |   1.264s |94.48MiB|
|d_komodo-verified-finalise.gen.dfyImpl___module.__default.lemma__kom__smc__finalise__success__helper2.smt2 |   1.098s |94.188MiB|
|d_lvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.ValToBucket.smt2        |   1.264s |93.976MiB|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.ReadSectorCorrect.smt2                  |   1.338s |93.724MiB|
|d_fvbkv-Impl-CacheImpl.i.dfy.CheckWellformed__CacheImpl.MutCache.Remove.smt2               |   1.238s |92.968MiB|
|d_lvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.CheckWellformed__ByteSystem.__default.I.smt2 |   1.129s |90.404MiB|
|d_komodo-verified-exception_handlers.gen.dfyCheckWellformed___module.__default.lemma__pageDbDispatcherVerifyStateCorresponds.smt2 |   1.129s |89.684MiB|
|d_fvbkv-Impl-StateModel.i.dfy.CheckWellformed__StateModel.__default.WFSector.smt2          |   1.102s |89.172MiB|
|d_komodo-verified-sha-hmac.gen.dfyCheckWellformed___module.__default.va__lemma__hmac__outer__prep__ctx.smt2 |   1.002s |89.048MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BlockInterface.i.dfy.CheckWellformed__BlockInterface.__default.IsStatePath.smt2  |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|d_fvbkv-Betree-Graph.i.dfy.Impl__Graph.__default.AcyclicGraphImpliesSimplePath.smt2         |   0.233s  |   0.233s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.NewRequestReadNodeDoesntOverlap.smt2  |   0.797s  |   0.797s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-DiskLayout.i.dfy.CheckWellformed__DiskLayout.__default.JournalBackLocation.smt2  |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.CheckWellformed__JournalSystem.__default.FreezeStepPreservesJournals.smt2  |   0.535s  |   0.535s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.Impl__JournalSystem.__default.ProcessWriteSuperblockPreservesJournals.smt2  |   0.825s  |   0.825s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-AsyncDiskModel.s.dfy.CheckWellformed__AsyncDisk.__default.AckRead.smt2  |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CacheImpl.i.dfy.CheckWellformed__CacheImpl.MutCache.Remove.smt2                |   1.238s  |   1.238s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterImpl.i.dfy.CheckWellformed__CommitterImpl.Committer.__ctor.smt2       |   0.644s  |   0.644s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CoordinationModel.i.dfy.CheckWellformed__CoordinationModel.__default.initialization.smt2  |   1.480s  |   1.480s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.ReadSectorCorrect.smt2                   |   1.338s  |   1.338s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-InsertModel.i.dfy.CheckWellformed__InsertModel.__default.insertCorrect.smt2    |   1.264s  |   1.264s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.CheckWellformed__JournalistMarshallingModel.__default.hasChecksums.smt2  |   0.243s  |   0.243s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MainHandlers.i.dfy.CheckWellformed__MainHandlers.__default.InitState.smt2      |   1.922s  |   1.922s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-StateModel.i.dfy.CheckWellformed__StateModel.__default.WFSector.smt2           |   1.102s  |   1.102s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-SuccModel.i.dfy.CheckWellformed__SuccModel.__default.getPathInternal.smt2      |   1.557s  |   1.557s  |   0.000s  | 0.0%|
|d_fvbkv-MapSpec-TSJ.i.dfy.Impl__TSJ.__default.PushSyncStepPreservesInv.smt2                 |   0.192s  |   0.192s  |   0.000s  | 0.0%|
|d_fvbkv-MapSpec-TSJMap_Refines_ThreeStateVersionedMap.i.dfy.Impl__TSJMap__Refines__ThreeStateVersionedMap.__default.apply__path.smt2  |   0.222s  |   0.222s  |   0.000s  | 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupUpperBound.smt2  |   0.409s  |   0.409s  |   0.000s  | 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupVisitsWFNodes.smt2  |   0.391s  |   0.391s  |   0.000s  | 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.Impl__PivotBetreeSpecRefinement.__default.InterpretBucketStackEqInterpretLookup.smt2  |   0.523s  |   0.523s  |   0.000s  | 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpecWFNodes.i.dfy.Impl__PivotBetreeSpecWFNodes.__default.ValidRepivotWFNodes.smt2  |   0.420s  |   0.420s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-sequences.i.dfy.Impl__Sequences.__default.FlattenLengthSubSeq.smt2         |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-total_order.i.dfy.CheckWellformed__Total__Order.__default.strictlySortedInsert2.smt2  |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-total_order.i.dfy.Impl__Uint32__Order.__default.LargestLteIsUnique2.smt2   |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-total_order_impl.i.dfy.CheckWellformed__Byte__Order__Impl.__default.ArrayLargestLtePlus1.smt2  |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.CheckWellformed__PackedStringArray.__default.LargestLte.smt2  |   0.221s  |   0.221s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-KMBtree.i.dfy.Impl__KMBtreeModel.__default.SplitIndexInterpretation2.smt2  |   0.255s  |   0.255s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.CheckWellformed__TestMutableBtree.__default.MaxKeysPerLeaf.smt2  |   0.232s  |   0.232s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__TestMutableBtree.__default.SubIndex.smt2  |   0.256s  |   0.256s  |   0.000s  | 0.0%|
|d_komodo-verified-ARMdef.s.dfyCheckWellformed___module.__default.ValidGlobalOffset.smt2     |   0.249s  |   0.249s  |   0.000s  | 0.0%|
|d_komodo-verified-ARMdef.s.dfyCheckWellformed___module.__default.ValidModeEncoding.smt2     |   0.221s  |   0.221s  |   0.000s  | 0.0%|
|d_komodo-verified-ARMprint.s.dfyImpl___module.__default.printGlobal.smt2                    |   0.206s  |   0.206s  |   0.000s  | 0.0%|
|d_komodo-verified-Seq.dfyCheckWellformed___module.__default.MapSeqToSeq.smt2                |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|d_komodo-verified-attest_helpers.gen.dfyImpl___module.__default.va__lemma__mem__move__global.smt2  |   2.624s  |   2.624s  |   0.000s  | 0.0%|
|d_komodo-verified-bitvectors.i.dfyCheckWellformed___module.__default.lemma__LeftShift2.smt2  |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|d_komodo-verified-bitvectors.i.dfyCheckWellformed___module.__default.lemma__RightShift2.smt2  |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.gen.dfyCheckWellformed___module.__default.va__lemma__smc__enter__err.smt2  |   0.615s  |   0.615s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.i.dfyCheckWellformed___module.__default.lemma__singlestep__execution.smt2  |   0.466s  |   0.466s  |   0.000s  | 0.0%|
|d_komodo-verified-exception_handlers.gen.dfyCheckWellformed___module.__default.lemma__pageDbDispatcherVerifyStateCorresponds.smt2  |   1.129s  |   1.129s  |   0.000s  | 0.0%|
|d_komodo-verified-exceptions.i.dfyCheckWellformed___module.__default.lemma__Establish__InterruptContinuationPrecondition.smt2  |   0.440s  |   0.440s  |   0.000s  | 0.0%|
|d_komodo-verified-finalise.gen.dfyImpl___module.__default.lemma__kom__smc__finalise__success__helper2.smt2  |   1.098s  |   1.098s  |   0.000s  | 0.0%|
|d_komodo-verified-kom_common.i.dfyImpl___module.__default.lemma__ValidMemRangeExPageTable__persists.smt2  |   2.548s  |   2.548s  |   0.000s  | 0.0%|
|d_komodo-verified-kom_common.s.dfyCheckWellformed___module.__default.AttestKey.smt2         |   0.234s  |   0.234s  |   0.000s  | 0.0%|
|d_komodo-verified-kom_utils.gen.dfyCheckWellformed___module.__default.va__code__STRx.smt2   |   0.438s  |   0.438s  |   0.000s  | 0.0%|
|d_komodo-verified-kom_utils.gen.dfyImpl___module.__default.va__lemma__page__monvaddr__impl.smt2  |   1.561s  |   1.561s  |   0.000s  | 0.0%|
|d_komodo-verified-map_common.gen.dfyImpl___module.__default.lemma__read__l2pte__zero.smt2   |   1.077s  |   1.077s  |   0.000s  | 0.0%|
|d_komodo-verified-pagedb.s.dfyCheckWellformed___module.__default.validInsecurePageNr.smt2   |   0.315s  |   0.315s  |   0.000s  | 0.0%|
|d_komodo-verified-ptebits.i.dfyCheckWellformed___module.__default.lemma__nonexec__mapping.smt2  |   0.339s  |   0.339s  |   0.000s  | 0.0%|
|d_komodo-verified-ptebits.i.dfyImpl___module.__default.lemma__BitOrNineIsLikePlus.smt2      |   0.490s  |   0.490s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-hmac.gen.dfyCheckWellformed___module.__default.va__lemma__hmac__outer__prep__ctx.smt2  |   1.002s  |   1.002s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-sha256-body-00-15.gen.dfyCheckWellformed___module.__default.va__if__abstract__Body__00__15UnrolledRecursive.smt2  |   0.552s  |   0.552s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-sha256-body-16-xx.gen.dfyImpl___module.__default.va__refined__Body__16__XXUnroller_split0.smt2  |   2.149s  |   2.149s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-sha256-helpers.i.dfyCheckWellformed___module.__default.lemma__BitwiseAdd32Associates5.smt2  |   0.325s  |   0.325s  |   0.000s  | 0.0%|
|d_komodo-verified-stop.gen.dfyCheckWellformed___module.__default.va__lemma__kom__smc__stop.smt2  |   0.619s  |   0.619s  |   0.000s  | 0.0%|
|d_komodo-verified-valedecls.gen.dfyImpl___module.__default.va__lemma__MOVShift.smt2         |   0.296s  |   0.296s  |   0.000s  | 0.0%|
|d_komodo-verified-valesupp.i.dfyCheckWellformed___module.__default.va__lemma__whileTrue.smt2  |   0.243s  |   0.243s  |   0.000s  | 0.0%|
|d_komodo-verified-verify.gen.dfyCheckWellformed___module.__default.va__code__svc__returning__verify.smt2  |   0.986s  |   0.986s  |   0.000s  | 0.0%|
|d_komodo-verified-words_and_bytes.i.dfyImpl___module.__default.lemma__BytesToWord__WordToBytes__inverses.smt2  |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|d_komodo-verified-words_and_bytes.s.dfyCheckWellformed___module.__default.ConcatenateSeqs.smt2  |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|d_lvbkv-Betree-Betree_Refines_Map.i.dfy.CheckWellformed__Betree__Refines__Map.__default.RefinesInit.smt2  |   0.359s  |   0.359s  |   0.000s  | 0.0%|
|d_lvbkv-Betree-BlockInterface.i.dfy.Impl__BlockInterface.__default.Transaction3Steps.smt2   |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.NewRequestReadIndirectionTableIsValid.smt2  |   4.319s  |   4.319s  |   0.000s  | 0.0%|
|d_lvbkv-BlockCacheSystem-DiskLayout.i.dfy.CheckWellformed__DiskLayout.__default.locContainedInCircularJournalRange.smt2  |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|d_lvbkv-BlockCacheSystem-JournalSystem.i.dfy.CheckWellformed__JournalSystem.__default.NoOpStepPreservesJournals.smt2  |   0.508s  |   0.508s  |   0.000s  | 0.0%|
|d_lvbkv-ByteBlockCacheSystem-AsyncDiskModel.s.dfy.CheckWellformed__AsyncDisk.__default.ChecksumChecksOut.smt2  |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|d_lvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.CheckWellformed__ByteSystem.__default.I.smt2  |   1.129s  |   1.129s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-CacheImpl.i.dfy.Impl__CacheImpl.LMutCache.NodePartialFlush.smt2                |   1.101s  |   1.101s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-CoordinationImpl.i.dfy.Impl__CoordinationImpl.__default.pushSync.smt2          |   1.786s  |   1.786s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-IOImpl.i.dfy.CheckWellformed__IOImpl.__default.getFreeLoc.smt2                 |   1.269s  |   1.269s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-JournalistImpl.i.dfy.CheckWellformed__JournalistImpl.__default.MaxPossibleEntries.smt2  |   0.277s  |   0.277s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.ValToBucket.smt2         |   1.264s  |   1.264s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-SplitModel.i.dfy.CheckWellformed__SplitModel.__default.lemmaChildrenConditionsCutoffNode.smt2  |   1.297s  |   1.297s  |   0.000s  | 0.0%|
|d_lvbkv-MapSpec-TSJMap.i.dfy.Impl__TSJMap.__default.Move2to3StepPreservesInv.smt2           |   0.224s  |   0.224s  |   0.000s  | 0.0%|
|d_lvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.CheckWellformed__PivotBetreeSpecRefinement.__default.INode.smt2  |   0.556s  |   0.556s  |   0.000s  | 0.0%|
|d_lvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.CheckWellformed__PivotBetreeSpecRefinement.__default.InterpretBucketStack.smt2  |   0.521s  |   0.521s  |   0.000s  | 0.0%|
|d_lvbkv-PivotBetree-PivotBetreeSpecWFNodes.i.dfy.CheckWellformed__PivotBetreeSpecWFNodes.__default.bucket__msgs__equiv.smt2  |   0.433s  |   0.433s  |   0.000s  | 0.0%|
|d_lvbkv-PivotBetree-StatesViewPivotBetree_Refines_StatesViewMap.i.dfy.CheckWellformed__StatesViewPivotBetree__Refines__StatesViewMap.__default.RefinesNextStep.smt2  |   0.616s  |   0.616s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-BitsetLemmas.i.dfy.CheckWellformed__BitsetLemmas.__default.bit.smt2        |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-BitsetLemmas.i.dfy.CheckWellformed__BitsetLemmas.__default.bit__comp__ne__expanded.smt2  |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-Message.i.dfy.CheckWellformed__ValueMessage.__default.EncodableMessageSeq.smt2  |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-MutableVec.i.dfy.CheckWellformed__MutableVec.Vec.insert.smt2               |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-total_order.i.dfy.Impl__Integer__Order.__default.StrictlySortedImpliesSorted.smt2  |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-total_order_impl.i.dfy.Impl__Byte__Order__Impl.__default.ComputeIsSorted.smt2  |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-total_order_impl.i.dfy.Impl__Uint64__Order__Impl.__default.BatchLargestLte.smt2  |   0.230s  |   0.230s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Checksums-BitLemmas.i.dfy.Impl__BitLemmas.__default.bits__of__int__combine.smt2  |   0.368s  |   0.368s  |   0.000s  | 0.0%|
|d_lvbkv-lib-DataStructures-KMBtree.i.dfy.Impl__KMBtreeModel.__default.SplitChildOfIndexPreservesAllKeys.smt2  |   0.281s  |   0.281s  |   0.000s  | 0.0%|
|d_lvbkv-lib-DataStructures-LinearMutableMap.i.dfy.CheckWellformed__LinearMutableMap.__default.FixedSizeUpdateBySlot.smt2  |   0.206s  |   0.206s  |   0.000s  | 0.0%|
|d_lvbkv-lib-DataStructures-LinearMutableMapBase.i.dfy.CheckWellformed__LinearMutableMapBase.__default.lshift.smt2  |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Math-Math.i.dfy.Impl__Math.__default.lemma__power2__div__is__sub.smt2           |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|s_komodo-1440.0.smt2                                                                        |   0.390s  |   0.390s  |   0.000s  | 0.0%|
|s_komodo-1441.2.smt2                                                                        |   0.249s  |   0.249s  |   0.000s  | 0.0%|
|s_komodo-1456.4.smt2                                                                        |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|s_komodo-1457.2.smt2                                                                        |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|s_komodo-1466.1.smt2                                                                        |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|s_komodo-1469.1.smt2                                                                        |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|s_komodo-1470.0.smt2                                                                        |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|s_komodo-1484.7.smt2                                                                        |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|s_komodo-1486.1.smt2                                                                        |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|s_komodo-1487.4.smt2                                                                        |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|s_komodo-1490.0.smt2                                                                        |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|s_komodo-1493.3.smt2                                                                        |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|s_komodo-1494.5.smt2                                                                        |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|s_komodo-1496.2.smt2                                                                        |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|s_komodo-1500.4.smt2                                                                        |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|s_komodo-1500.6.smt2                                                                        |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|s_komodo-1501.7.smt2                                                                        |   0.615s  |   0.615s  |   0.000s  | 0.0%|
|s_komodo-1502.2.smt2                                                                        |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|s_komodo-1503.6.smt2                                                                        |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|s_komodo-1505.3.smt2                                                                        |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|s_komodo-1506.1.smt2                                                                        |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|s_komodo-1511.8.smt2                                                                        |   0.313s  |   0.313s  |   0.000s  | 0.0%|
|s_komodo-1516.11.smt2                                                                       |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|s_komodo-1516.7.smt2                                                                        |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|s_komodo-1526.0.smt2                                                                        |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|s_komodo-1531.0.smt2                                                                        |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|s_komodo-1533.7.smt2                                                                        |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|s_komodo-1534.9.smt2                                                                        |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|s_komodo-1544.3.smt2                                                                        |   0.054s  |   0.054s  |   0.000s  | 0.0%|
</details>
