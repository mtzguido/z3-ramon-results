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
Job tag: pre-gen-patch-mariposa-sc
Runner: rise-runner-1
Z3 repo: CanCebeci/z3
Z3 commit: 51cbbe0a0ea3259ec92255e86e5818d1d6a9e523
Z3 branch: 51cbbe0a0ea3259ec92255e86e5818d1d6a9e523
Z3 options: "%OPTIONS2%"
Z3 inputs: inputs/mariposa/stable_core
Z3 commit message: fix #9293

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: pre-gen-patch-mariposa-sc
Runner: rise-runner-1
Z3 repo: CanCebeci/z3
Z3 commit: 51cbbe0a0ea3259ec92255e86e5818d1d6a9e523
Z3 branch: 51cbbe0a0ea3259ec92255e86e5818d1d6a9e523
Z3 options: "%OPTIONS2%"
Z3 inputs: inputs/mariposa/stable_core
Z3 commit message: fix #9293

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BlockInterface.i.dfy.CheckWellformed__BlockInterface.__default.IsStatePath.smt2  |   0.222s  |   0.222s  |   0.000s  | 0.0%|
|d_fvbkv-Betree-Graph.i.dfy.Impl__Graph.__default.AcyclicGraphImpliesSimplePath.smt2         |   0.208s  |   0.208s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.NewRequestReadNodeDoesntOverlap.smt2  |   1.008s  |   1.008s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-DiskLayout.i.dfy.CheckWellformed__DiskLayout.__default.JournalBackLocation.smt2  |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.CheckWellformed__JournalSystem.__default.FreezeStepPreservesJournals.smt2  |   0.587s  |   0.587s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.Impl__JournalSystem.__default.ProcessWriteSuperblockPreservesJournals.smt2  |   0.900s  |   0.900s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-AsyncDiskModel.s.dfy.CheckWellformed__AsyncDisk.__default.AckRead.smt2  |   0.211s  |   0.211s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CacheImpl.i.dfy.CheckWellformed__CacheImpl.MutCache.Remove.smt2                |   1.562s  |   1.562s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterImpl.i.dfy.CheckWellformed__CommitterImpl.Committer.__ctor.smt2       |   0.784s  |   0.784s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CoordinationModel.i.dfy.CheckWellformed__CoordinationModel.__default.initialization.smt2  |   1.728s  |   1.728s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.ReadSectorCorrect.smt2                   |   1.485s  |   1.485s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-InsertModel.i.dfy.CheckWellformed__InsertModel.__default.insertCorrect.smt2    |   1.472s  |   1.472s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.CheckWellformed__JournalistMarshallingModel.__default.hasChecksums.smt2  |   0.338s  |   0.338s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MainHandlers.i.dfy.CheckWellformed__MainHandlers.__default.InitState.smt2      |   2.099s  |   2.099s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-StateModel.i.dfy.CheckWellformed__StateModel.__default.WFSector.smt2           |   1.468s  |   1.468s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-SuccModel.i.dfy.CheckWellformed__SuccModel.__default.getPathInternal.smt2      |   1.669s  |   1.669s  |   0.000s  | 0.0%|
|d_fvbkv-MapSpec-TSJ.i.dfy.Impl__TSJ.__default.PushSyncStepPreservesInv.smt2                 |   0.238s  |   0.238s  |   0.000s  | 0.0%|
|d_fvbkv-MapSpec-TSJMap_Refines_ThreeStateVersionedMap.i.dfy.Impl__TSJMap__Refines__ThreeStateVersionedMap.__default.apply__path.smt2  |   0.275s  |   0.275s  |   0.000s  | 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupUpperBound.smt2  |   0.523s  |   0.523s  |   0.000s  | 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupVisitsWFNodes.smt2  |   0.539s  |   0.539s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BlockInterface.i.dfy.CheckWellformed__BlockInterface.__default.IsStatePath.smt2  |   0.222s  |   0.222s  |   0.000s  | 0.0%|
|d_fvbkv-Betree-Graph.i.dfy.Impl__Graph.__default.AcyclicGraphImpliesSimplePath.smt2         |   0.208s  |   0.208s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.NewRequestReadNodeDoesntOverlap.smt2  |   1.008s  |   1.008s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-DiskLayout.i.dfy.CheckWellformed__DiskLayout.__default.JournalBackLocation.smt2  |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.CheckWellformed__JournalSystem.__default.FreezeStepPreservesJournals.smt2  |   0.587s  |   0.587s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.Impl__JournalSystem.__default.ProcessWriteSuperblockPreservesJournals.smt2  |   0.900s  |   0.900s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-AsyncDiskModel.s.dfy.CheckWellformed__AsyncDisk.__default.AckRead.smt2  |   0.211s  |   0.211s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CacheImpl.i.dfy.CheckWellformed__CacheImpl.MutCache.Remove.smt2                |   1.562s  |   1.562s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterImpl.i.dfy.CheckWellformed__CommitterImpl.Committer.__ctor.smt2       |   0.784s  |   0.784s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CoordinationModel.i.dfy.CheckWellformed__CoordinationModel.__default.initialization.smt2  |   1.728s  |   1.728s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.ReadSectorCorrect.smt2                   |   1.485s  |   1.485s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-InsertModel.i.dfy.CheckWellformed__InsertModel.__default.insertCorrect.smt2    |   1.472s  |   1.472s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.CheckWellformed__JournalistMarshallingModel.__default.hasChecksums.smt2  |   0.338s  |   0.338s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MainHandlers.i.dfy.CheckWellformed__MainHandlers.__default.InitState.smt2      |   2.099s  |   2.099s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-StateModel.i.dfy.CheckWellformed__StateModel.__default.WFSector.smt2           |   1.468s  |   1.468s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-SuccModel.i.dfy.CheckWellformed__SuccModel.__default.getPathInternal.smt2      |   1.669s  |   1.669s  |   0.000s  | 0.0%|
|d_fvbkv-MapSpec-TSJ.i.dfy.Impl__TSJ.__default.PushSyncStepPreservesInv.smt2                 |   0.238s  |   0.238s  |   0.000s  | 0.0%|
|d_fvbkv-MapSpec-TSJMap_Refines_ThreeStateVersionedMap.i.dfy.Impl__TSJMap__Refines__ThreeStateVersionedMap.__default.apply__path.smt2  |   0.275s  |   0.275s  |   0.000s  | 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupUpperBound.smt2  |   0.523s  |   0.523s  |   0.000s  | 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupVisitsWFNodes.smt2  |   0.539s  |   0.539s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BlockInterface.i.dfy.CheckWellformed__BlockInterface.__default.IsStatePath.smt2  |   0.222s  |   0.222s  |   0.000s  | 0.0%|
|d_fvbkv-Betree-Graph.i.dfy.Impl__Graph.__default.AcyclicGraphImpliesSimplePath.smt2         |   0.208s  |   0.208s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.NewRequestReadNodeDoesntOverlap.smt2  |   1.008s  |   1.008s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-DiskLayout.i.dfy.CheckWellformed__DiskLayout.__default.JournalBackLocation.smt2  |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.CheckWellformed__JournalSystem.__default.FreezeStepPreservesJournals.smt2  |   0.587s  |   0.587s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.Impl__JournalSystem.__default.ProcessWriteSuperblockPreservesJournals.smt2  |   0.900s  |   0.900s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-AsyncDiskModel.s.dfy.CheckWellformed__AsyncDisk.__default.AckRead.smt2  |   0.211s  |   0.211s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CacheImpl.i.dfy.CheckWellformed__CacheImpl.MutCache.Remove.smt2                |   1.562s  |   1.562s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterImpl.i.dfy.CheckWellformed__CommitterImpl.Committer.__ctor.smt2       |   0.784s  |   0.784s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CoordinationModel.i.dfy.CheckWellformed__CoordinationModel.__default.initialization.smt2  |   1.728s  |   1.728s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.ReadSectorCorrect.smt2                   |   1.485s  |   1.485s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-InsertModel.i.dfy.CheckWellformed__InsertModel.__default.insertCorrect.smt2    |   1.472s  |   1.472s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.CheckWellformed__JournalistMarshallingModel.__default.hasChecksums.smt2  |   0.338s  |   0.338s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MainHandlers.i.dfy.CheckWellformed__MainHandlers.__default.InitState.smt2      |   2.099s  |   2.099s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-StateModel.i.dfy.CheckWellformed__StateModel.__default.WFSector.smt2           |   1.468s  |   1.468s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-SuccModel.i.dfy.CheckWellformed__SuccModel.__default.getPathInternal.smt2      |   1.669s  |   1.669s  |   0.000s  | 0.0%|
|d_fvbkv-MapSpec-TSJ.i.dfy.Impl__TSJ.__default.PushSyncStepPreservesInv.smt2                 |   0.238s  |   0.238s  |   0.000s  | 0.0%|
|d_fvbkv-MapSpec-TSJMap_Refines_ThreeStateVersionedMap.i.dfy.Impl__TSJMap__Refines__ThreeStateVersionedMap.__default.apply__path.smt2  |   0.275s  |   0.275s  |   0.000s  | 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupUpperBound.smt2  |   0.523s  |   0.523s  |   0.000s  | 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupVisitsWFNodes.smt2  |   0.539s  |   0.539s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BlockInterface.i.dfy.CheckWellformed__BlockInterface.__default.IsStatePath.smt2  |   0.222s  |   0.222s  |   0.000s  | 0.0%|
|d_fvbkv-Betree-Graph.i.dfy.Impl__Graph.__default.AcyclicGraphImpliesSimplePath.smt2         |   0.208s  |   0.208s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.NewRequestReadNodeDoesntOverlap.smt2  |   1.008s  |   1.008s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-DiskLayout.i.dfy.CheckWellformed__DiskLayout.__default.JournalBackLocation.smt2  |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.CheckWellformed__JournalSystem.__default.FreezeStepPreservesJournals.smt2  |   0.587s  |   0.587s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.Impl__JournalSystem.__default.ProcessWriteSuperblockPreservesJournals.smt2  |   0.900s  |   0.900s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-AsyncDiskModel.s.dfy.CheckWellformed__AsyncDisk.__default.AckRead.smt2  |   0.211s  |   0.211s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CacheImpl.i.dfy.CheckWellformed__CacheImpl.MutCache.Remove.smt2                |   1.562s  |   1.562s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterImpl.i.dfy.CheckWellformed__CommitterImpl.Committer.__ctor.smt2       |   0.784s  |   0.784s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CoordinationModel.i.dfy.CheckWellformed__CoordinationModel.__default.initialization.smt2  |   1.728s  |   1.728s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.ReadSectorCorrect.smt2                   |   1.485s  |   1.485s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-InsertModel.i.dfy.CheckWellformed__InsertModel.__default.insertCorrect.smt2    |   1.472s  |   1.472s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.CheckWellformed__JournalistMarshallingModel.__default.hasChecksums.smt2  |   0.338s  |   0.338s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MainHandlers.i.dfy.CheckWellformed__MainHandlers.__default.InitState.smt2      |   2.099s  |   2.099s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-StateModel.i.dfy.CheckWellformed__StateModel.__default.WFSector.smt2           |   1.468s  |   1.468s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-SuccModel.i.dfy.CheckWellformed__SuccModel.__default.getPathInternal.smt2      |   1.669s  |   1.669s  |   0.000s  | 0.0%|
|d_fvbkv-MapSpec-TSJ.i.dfy.Impl__TSJ.__default.PushSyncStepPreservesInv.smt2                 |   0.238s  |   0.238s  |   0.000s  | 0.0%|
|d_fvbkv-MapSpec-TSJMap_Refines_ThreeStateVersionedMap.i.dfy.Impl__TSJMap__Refines__ThreeStateVersionedMap.__default.apply__path.smt2  |   0.275s  |   0.275s  |   0.000s  | 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupUpperBound.smt2  |   0.523s  |   0.523s  |   0.000s  | 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupVisitsWFNodes.smt2  |   0.539s  |   0.539s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.NewRequestReadIndirectionTableIsValid.smt2 |   4.484s |117.0MiB|
|d_komodo-verified-attest_helpers.gen.dfyImpl___module.__default.va__lemma__mem__move__global.smt2 |   2.530s |99.0MiB|
|d_fvbkv-Impl-MainHandlers.i.dfy.CheckWellformed__MainHandlers.__default.InitState.smt2     |   2.099s |145.0MiB|
|d_komodo-verified-sha-sha256-body-16-xx.gen.dfyImpl___module.__default.va__refined__Body__16__XXUnroller_split0.smt2 |   2.048s |100.0MiB|
|d_lvbkv-Impl-CoordinationImpl.i.dfy.Impl__CoordinationImpl.__default.pushSync.smt2         |   1.834s |135.0MiB|
|d_fvbkv-Impl-CoordinationModel.i.dfy.CheckWellformed__CoordinationModel.__default.initialization.smt2 |   1.728s |99.6MiB|
|d_komodo-verified-kom_common.i.dfyImpl___module.__default.lemma__ValidMemRangeExPageTable__persists.smt2 |   1.679s |64.16MiB|
|d_fvbkv-Impl-SuccModel.i.dfy.CheckWellformed__SuccModel.__default.getPathInternal.smt2     |   1.669s |98.72MiB|
|d_komodo-verified-kom_utils.gen.dfyImpl___module.__default.va__lemma__page__monvaddr__impl.smt2 |   1.656s |63.52MiB|
|d_lvbkv-Impl-IOImpl.i.dfy.CheckWellformed__IOImpl.__default.getFreeLoc.smt2                |   1.607s |95.048MiB|
|d_fvbkv-Impl-CacheImpl.i.dfy.CheckWellformed__CacheImpl.MutCache.Remove.smt2               |   1.562s |91.576MiB|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.ReadSectorCorrect.smt2                  |   1.485s |92.888MiB|
|d_fvbkv-Impl-InsertModel.i.dfy.CheckWellformed__InsertModel.__default.insertCorrect.smt2   |   1.472s |93.788MiB|
|d_fvbkv-Impl-StateModel.i.dfy.CheckWellformed__StateModel.__default.WFSector.smt2          |   1.468s |88.492MiB|
|d_komodo-verified-finalise.gen.dfyImpl___module.__default.lemma__kom__smc__finalise__success__helper2.smt2 |   1.448s |93.664MiB|
|d_komodo-verified-map_common.gen.dfyImpl___module.__default.lemma__read__l2pte__zero.smt2  |   1.427s |94.7MiB|
|d_lvbkv-Impl-SplitModel.i.dfy.CheckWellformed__SplitModel.__default.lemmaChildrenConditionsCutoffNode.smt2 |   1.404s |95.784MiB|
|d_lvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.ValToBucket.smt2        |   1.399s |93.148MiB|
|d_lvbkv-Impl-CacheImpl.i.dfy.Impl__CacheImpl.LMutCache.NodePartialFlush.smt2               |   1.341s |87.696MiB|
|d_komodo-verified-verify.gen.dfyCheckWellformed___module.__default.va__code__svc__returning__verify.smt2 |   1.327s |85.724MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.NewRequestReadIndirectionTableIsValid.smt2 |   4.484s |117.0MiB|
|d_komodo-verified-attest_helpers.gen.dfyImpl___module.__default.va__lemma__mem__move__global.smt2 |   2.530s |99.0MiB|
|d_fvbkv-Impl-MainHandlers.i.dfy.CheckWellformed__MainHandlers.__default.InitState.smt2     |   2.099s |145.0MiB|
|d_komodo-verified-sha-sha256-body-16-xx.gen.dfyImpl___module.__default.va__refined__Body__16__XXUnroller_split0.smt2 |   2.048s |100.0MiB|
|d_lvbkv-Impl-CoordinationImpl.i.dfy.Impl__CoordinationImpl.__default.pushSync.smt2         |   1.834s |135.0MiB|
|d_fvbkv-Impl-CoordinationModel.i.dfy.CheckWellformed__CoordinationModel.__default.initialization.smt2 |   1.728s |99.6MiB|
|d_komodo-verified-kom_common.i.dfyImpl___module.__default.lemma__ValidMemRangeExPageTable__persists.smt2 |   1.679s |64.16MiB|
|d_fvbkv-Impl-SuccModel.i.dfy.CheckWellformed__SuccModel.__default.getPathInternal.smt2     |   1.669s |98.72MiB|
|d_komodo-verified-kom_utils.gen.dfyImpl___module.__default.va__lemma__page__monvaddr__impl.smt2 |   1.656s |63.52MiB|
|d_lvbkv-Impl-IOImpl.i.dfy.CheckWellformed__IOImpl.__default.getFreeLoc.smt2                |   1.607s |95.048MiB|
|d_fvbkv-Impl-CacheImpl.i.dfy.CheckWellformed__CacheImpl.MutCache.Remove.smt2               |   1.562s |91.576MiB|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.ReadSectorCorrect.smt2                  |   1.485s |92.888MiB|
|d_fvbkv-Impl-InsertModel.i.dfy.CheckWellformed__InsertModel.__default.insertCorrect.smt2   |   1.472s |93.788MiB|
|d_fvbkv-Impl-StateModel.i.dfy.CheckWellformed__StateModel.__default.WFSector.smt2          |   1.468s |88.492MiB|
|d_komodo-verified-finalise.gen.dfyImpl___module.__default.lemma__kom__smc__finalise__success__helper2.smt2 |   1.448s |93.664MiB|
|d_komodo-verified-map_common.gen.dfyImpl___module.__default.lemma__read__l2pte__zero.smt2  |   1.427s |94.7MiB|
|d_lvbkv-Impl-SplitModel.i.dfy.CheckWellformed__SplitModel.__default.lemmaChildrenConditionsCutoffNode.smt2 |   1.404s |95.784MiB|
|d_lvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.ValToBucket.smt2        |   1.399s |93.148MiB|
|d_lvbkv-Impl-CacheImpl.i.dfy.Impl__CacheImpl.LMutCache.NodePartialFlush.smt2               |   1.341s |87.696MiB|
|d_komodo-verified-verify.gen.dfyCheckWellformed___module.__default.va__code__svc__returning__verify.smt2 |   1.327s |85.724MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BlockInterface.i.dfy.CheckWellformed__BlockInterface.__default.IsStatePath.smt2  |25.232MiB|25.232MiB|0B| 0.0%|
|d_fvbkv-Betree-Graph.i.dfy.Impl__Graph.__default.AcyclicGraphImpliesSimplePath.smt2         |25.668MiB|25.668MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.NewRequestReadNodeDoesntOverlap.smt2  |53.32MiB|53.32MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-DiskLayout.i.dfy.CheckWellformed__DiskLayout.__default.JournalBackLocation.smt2  |24.004MiB|24.004MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.CheckWellformed__JournalSystem.__default.FreezeStepPreservesJournals.smt2  |49.4MiB|49.4MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.Impl__JournalSystem.__default.ProcessWriteSuperblockPreservesJournals.smt2  |55.892MiB|55.892MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-AsyncDiskModel.s.dfy.CheckWellformed__AsyncDisk.__default.AckRead.smt2  |25.384MiB|25.384MiB|0B| 0.0%|
|d_fvbkv-Impl-CacheImpl.i.dfy.CheckWellformed__CacheImpl.MutCache.Remove.smt2                |91.576MiB|91.576MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterImpl.i.dfy.CheckWellformed__CommitterImpl.Committer.__ctor.smt2       |52.804MiB|52.804MiB|0B| 0.0%|
|d_fvbkv-Impl-CoordinationModel.i.dfy.CheckWellformed__CoordinationModel.__default.initialization.smt2  |99.6MiB|99.6MiB|0B| 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.ReadSectorCorrect.smt2                   |92.888MiB|92.888MiB|0B| 0.0%|
|d_fvbkv-Impl-InsertModel.i.dfy.CheckWellformed__InsertModel.__default.insertCorrect.smt2    |93.788MiB|93.788MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.CheckWellformed__JournalistMarshallingModel.__default.hasChecksums.smt2  |30.112MiB|30.112MiB|0B| 0.0%|
|d_fvbkv-Impl-MainHandlers.i.dfy.CheckWellformed__MainHandlers.__default.InitState.smt2      |145.0MiB|145.0MiB|0B| 0.0%|
|d_fvbkv-Impl-StateModel.i.dfy.CheckWellformed__StateModel.__default.WFSector.smt2           |88.492MiB|88.492MiB|0B| 0.0%|
|d_fvbkv-Impl-SuccModel.i.dfy.CheckWellformed__SuccModel.__default.getPathInternal.smt2      |98.72MiB|98.72MiB|0B| 0.0%|
|d_fvbkv-MapSpec-TSJ.i.dfy.Impl__TSJ.__default.PushSyncStepPreservesInv.smt2                 |27.216MiB|27.216MiB|0B| 0.0%|
|d_fvbkv-MapSpec-TSJMap_Refines_ThreeStateVersionedMap.i.dfy.Impl__TSJMap__Refines__ThreeStateVersionedMap.__default.apply__path.smt2  |29.028MiB|29.028MiB|0B| 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupUpperBound.smt2  |43.636MiB|43.636MiB|0B| 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupVisitsWFNodes.smt2  |43.692MiB|43.692MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BlockInterface.i.dfy.CheckWellformed__BlockInterface.__default.IsStatePath.smt2  |25.232MiB|25.232MiB|0B| 0.0%|
|d_fvbkv-Betree-Graph.i.dfy.Impl__Graph.__default.AcyclicGraphImpliesSimplePath.smt2         |25.668MiB|25.668MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.NewRequestReadNodeDoesntOverlap.smt2  |53.32MiB|53.32MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-DiskLayout.i.dfy.CheckWellformed__DiskLayout.__default.JournalBackLocation.smt2  |24.004MiB|24.004MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.CheckWellformed__JournalSystem.__default.FreezeStepPreservesJournals.smt2  |49.4MiB|49.4MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.Impl__JournalSystem.__default.ProcessWriteSuperblockPreservesJournals.smt2  |55.892MiB|55.892MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-AsyncDiskModel.s.dfy.CheckWellformed__AsyncDisk.__default.AckRead.smt2  |25.384MiB|25.384MiB|0B| 0.0%|
|d_fvbkv-Impl-CacheImpl.i.dfy.CheckWellformed__CacheImpl.MutCache.Remove.smt2                |91.576MiB|91.576MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterImpl.i.dfy.CheckWellformed__CommitterImpl.Committer.__ctor.smt2       |52.804MiB|52.804MiB|0B| 0.0%|
|d_fvbkv-Impl-CoordinationModel.i.dfy.CheckWellformed__CoordinationModel.__default.initialization.smt2  |99.6MiB|99.6MiB|0B| 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.ReadSectorCorrect.smt2                   |92.888MiB|92.888MiB|0B| 0.0%|
|d_fvbkv-Impl-InsertModel.i.dfy.CheckWellformed__InsertModel.__default.insertCorrect.smt2    |93.788MiB|93.788MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.CheckWellformed__JournalistMarshallingModel.__default.hasChecksums.smt2  |30.112MiB|30.112MiB|0B| 0.0%|
|d_fvbkv-Impl-MainHandlers.i.dfy.CheckWellformed__MainHandlers.__default.InitState.smt2      |145.0MiB|145.0MiB|0B| 0.0%|
|d_fvbkv-Impl-StateModel.i.dfy.CheckWellformed__StateModel.__default.WFSector.smt2           |88.492MiB|88.492MiB|0B| 0.0%|
|d_fvbkv-Impl-SuccModel.i.dfy.CheckWellformed__SuccModel.__default.getPathInternal.smt2      |98.72MiB|98.72MiB|0B| 0.0%|
|d_fvbkv-MapSpec-TSJ.i.dfy.Impl__TSJ.__default.PushSyncStepPreservesInv.smt2                 |27.216MiB|27.216MiB|0B| 0.0%|
|d_fvbkv-MapSpec-TSJMap_Refines_ThreeStateVersionedMap.i.dfy.Impl__TSJMap__Refines__ThreeStateVersionedMap.__default.apply__path.smt2  |29.028MiB|29.028MiB|0B| 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupUpperBound.smt2  |43.636MiB|43.636MiB|0B| 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupVisitsWFNodes.smt2  |43.692MiB|43.692MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BlockInterface.i.dfy.CheckWellformed__BlockInterface.__default.IsStatePath.smt2  |25.232MiB|25.232MiB|0B| 0.0%|
|d_fvbkv-Betree-Graph.i.dfy.Impl__Graph.__default.AcyclicGraphImpliesSimplePath.smt2         |25.668MiB|25.668MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.NewRequestReadNodeDoesntOverlap.smt2  |53.32MiB|53.32MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-DiskLayout.i.dfy.CheckWellformed__DiskLayout.__default.JournalBackLocation.smt2  |24.004MiB|24.004MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.CheckWellformed__JournalSystem.__default.FreezeStepPreservesJournals.smt2  |49.4MiB|49.4MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.Impl__JournalSystem.__default.ProcessWriteSuperblockPreservesJournals.smt2  |55.892MiB|55.892MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-AsyncDiskModel.s.dfy.CheckWellformed__AsyncDisk.__default.AckRead.smt2  |25.384MiB|25.384MiB|0B| 0.0%|
|d_fvbkv-Impl-CacheImpl.i.dfy.CheckWellformed__CacheImpl.MutCache.Remove.smt2                |91.576MiB|91.576MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterImpl.i.dfy.CheckWellformed__CommitterImpl.Committer.__ctor.smt2       |52.804MiB|52.804MiB|0B| 0.0%|
|d_fvbkv-Impl-CoordinationModel.i.dfy.CheckWellformed__CoordinationModel.__default.initialization.smt2  |99.6MiB|99.6MiB|0B| 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.ReadSectorCorrect.smt2                   |92.888MiB|92.888MiB|0B| 0.0%|
|d_fvbkv-Impl-InsertModel.i.dfy.CheckWellformed__InsertModel.__default.insertCorrect.smt2    |93.788MiB|93.788MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.CheckWellformed__JournalistMarshallingModel.__default.hasChecksums.smt2  |30.112MiB|30.112MiB|0B| 0.0%|
|d_fvbkv-Impl-MainHandlers.i.dfy.CheckWellformed__MainHandlers.__default.InitState.smt2      |145.0MiB|145.0MiB|0B| 0.0%|
|d_fvbkv-Impl-StateModel.i.dfy.CheckWellformed__StateModel.__default.WFSector.smt2           |88.492MiB|88.492MiB|0B| 0.0%|
|d_fvbkv-Impl-SuccModel.i.dfy.CheckWellformed__SuccModel.__default.getPathInternal.smt2      |98.72MiB|98.72MiB|0B| 0.0%|
|d_fvbkv-MapSpec-TSJ.i.dfy.Impl__TSJ.__default.PushSyncStepPreservesInv.smt2                 |27.216MiB|27.216MiB|0B| 0.0%|
|d_fvbkv-MapSpec-TSJMap_Refines_ThreeStateVersionedMap.i.dfy.Impl__TSJMap__Refines__ThreeStateVersionedMap.__default.apply__path.smt2  |29.028MiB|29.028MiB|0B| 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupUpperBound.smt2  |43.636MiB|43.636MiB|0B| 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupVisitsWFNodes.smt2  |43.692MiB|43.692MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BlockInterface.i.dfy.CheckWellformed__BlockInterface.__default.IsStatePath.smt2  |25.232MiB|25.232MiB|0B| 0.0%|
|d_fvbkv-Betree-Graph.i.dfy.Impl__Graph.__default.AcyclicGraphImpliesSimplePath.smt2         |25.668MiB|25.668MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.NewRequestReadNodeDoesntOverlap.smt2  |53.32MiB|53.32MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-DiskLayout.i.dfy.CheckWellformed__DiskLayout.__default.JournalBackLocation.smt2  |24.004MiB|24.004MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.CheckWellformed__JournalSystem.__default.FreezeStepPreservesJournals.smt2  |49.4MiB|49.4MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.Impl__JournalSystem.__default.ProcessWriteSuperblockPreservesJournals.smt2  |55.892MiB|55.892MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-AsyncDiskModel.s.dfy.CheckWellformed__AsyncDisk.__default.AckRead.smt2  |25.384MiB|25.384MiB|0B| 0.0%|
|d_fvbkv-Impl-CacheImpl.i.dfy.CheckWellformed__CacheImpl.MutCache.Remove.smt2                |91.576MiB|91.576MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterImpl.i.dfy.CheckWellformed__CommitterImpl.Committer.__ctor.smt2       |52.804MiB|52.804MiB|0B| 0.0%|
|d_fvbkv-Impl-CoordinationModel.i.dfy.CheckWellformed__CoordinationModel.__default.initialization.smt2  |99.6MiB|99.6MiB|0B| 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.ReadSectorCorrect.smt2                   |92.888MiB|92.888MiB|0B| 0.0%|
|d_fvbkv-Impl-InsertModel.i.dfy.CheckWellformed__InsertModel.__default.insertCorrect.smt2    |93.788MiB|93.788MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.CheckWellformed__JournalistMarshallingModel.__default.hasChecksums.smt2  |30.112MiB|30.112MiB|0B| 0.0%|
|d_fvbkv-Impl-MainHandlers.i.dfy.CheckWellformed__MainHandlers.__default.InitState.smt2      |145.0MiB|145.0MiB|0B| 0.0%|
|d_fvbkv-Impl-StateModel.i.dfy.CheckWellformed__StateModel.__default.WFSector.smt2           |88.492MiB|88.492MiB|0B| 0.0%|
|d_fvbkv-Impl-SuccModel.i.dfy.CheckWellformed__SuccModel.__default.getPathInternal.smt2      |98.72MiB|98.72MiB|0B| 0.0%|
|d_fvbkv-MapSpec-TSJ.i.dfy.Impl__TSJ.__default.PushSyncStepPreservesInv.smt2                 |27.216MiB|27.216MiB|0B| 0.0%|
|d_fvbkv-MapSpec-TSJMap_Refines_ThreeStateVersionedMap.i.dfy.Impl__TSJMap__Refines__ThreeStateVersionedMap.__default.apply__path.smt2  |29.028MiB|29.028MiB|0B| 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupUpperBound.smt2  |43.636MiB|43.636MiB|0B| 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupVisitsWFNodes.smt2  |43.692MiB|43.692MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|d_fvbkv-Impl-MainHandlers.i.dfy.CheckWellformed__MainHandlers.__default.InitState.smt2     |   2.099s |145.0MiB|
|d_lvbkv-Impl-CoordinationImpl.i.dfy.Impl__CoordinationImpl.__default.pushSync.smt2         |   1.834s |135.0MiB|
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.NewRequestReadIndirectionTableIsValid.smt2 |   4.484s |117.0MiB|
|d_komodo-verified-sha-sha256-body-16-xx.gen.dfyImpl___module.__default.va__refined__Body__16__XXUnroller_split0.smt2 |   2.048s |100.0MiB|
|d_fvbkv-Impl-CoordinationModel.i.dfy.CheckWellformed__CoordinationModel.__default.initialization.smt2 |   1.728s |99.6MiB|
|d_komodo-verified-attest_helpers.gen.dfyImpl___module.__default.va__lemma__mem__move__global.smt2 |   2.530s |99.0MiB|
|d_fvbkv-Impl-SuccModel.i.dfy.CheckWellformed__SuccModel.__default.getPathInternal.smt2     |   1.669s |98.72MiB|
|d_lvbkv-Impl-SplitModel.i.dfy.CheckWellformed__SplitModel.__default.lemmaChildrenConditionsCutoffNode.smt2 |   1.404s |95.784MiB|
|d_lvbkv-Impl-IOImpl.i.dfy.CheckWellformed__IOImpl.__default.getFreeLoc.smt2                |   1.607s |95.048MiB|
|d_komodo-verified-map_common.gen.dfyImpl___module.__default.lemma__read__l2pte__zero.smt2  |   1.427s |94.7MiB|
|d_fvbkv-Impl-InsertModel.i.dfy.CheckWellformed__InsertModel.__default.insertCorrect.smt2   |   1.472s |93.788MiB|
|d_komodo-verified-finalise.gen.dfyImpl___module.__default.lemma__kom__smc__finalise__success__helper2.smt2 |   1.448s |93.664MiB|
|d_lvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.ValToBucket.smt2        |   1.399s |93.148MiB|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.ReadSectorCorrect.smt2                  |   1.485s |92.888MiB|
|d_fvbkv-Impl-CacheImpl.i.dfy.CheckWellformed__CacheImpl.MutCache.Remove.smt2               |   1.562s |91.576MiB|
|d_lvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.CheckWellformed__ByteSystem.__default.I.smt2 |   1.243s |89.784MiB|
|d_komodo-verified-exception_handlers.gen.dfyCheckWellformed___module.__default.lemma__pageDbDispatcherVerifyStateCorresponds.smt2 |   1.249s |88.7MiB|
|d_komodo-verified-sha-hmac.gen.dfyCheckWellformed___module.__default.va__lemma__hmac__outer__prep__ctx.smt2 |   1.304s |88.532MiB|
|d_fvbkv-Impl-StateModel.i.dfy.CheckWellformed__StateModel.__default.WFSector.smt2          |   1.468s |88.492MiB|
|d_lvbkv-Impl-CacheImpl.i.dfy.Impl__CacheImpl.LMutCache.NodePartialFlush.smt2               |   1.341s |87.696MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|d_fvbkv-Impl-MainHandlers.i.dfy.CheckWellformed__MainHandlers.__default.InitState.smt2     |   2.099s |145.0MiB|
|d_lvbkv-Impl-CoordinationImpl.i.dfy.Impl__CoordinationImpl.__default.pushSync.smt2         |   1.834s |135.0MiB|
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.NewRequestReadIndirectionTableIsValid.smt2 |   4.484s |117.0MiB|
|d_komodo-verified-sha-sha256-body-16-xx.gen.dfyImpl___module.__default.va__refined__Body__16__XXUnroller_split0.smt2 |   2.048s |100.0MiB|
|d_fvbkv-Impl-CoordinationModel.i.dfy.CheckWellformed__CoordinationModel.__default.initialization.smt2 |   1.728s |99.6MiB|
|d_komodo-verified-attest_helpers.gen.dfyImpl___module.__default.va__lemma__mem__move__global.smt2 |   2.530s |99.0MiB|
|d_fvbkv-Impl-SuccModel.i.dfy.CheckWellformed__SuccModel.__default.getPathInternal.smt2     |   1.669s |98.72MiB|
|d_lvbkv-Impl-SplitModel.i.dfy.CheckWellformed__SplitModel.__default.lemmaChildrenConditionsCutoffNode.smt2 |   1.404s |95.784MiB|
|d_lvbkv-Impl-IOImpl.i.dfy.CheckWellformed__IOImpl.__default.getFreeLoc.smt2                |   1.607s |95.048MiB|
|d_komodo-verified-map_common.gen.dfyImpl___module.__default.lemma__read__l2pte__zero.smt2  |   1.427s |94.7MiB|
|d_fvbkv-Impl-InsertModel.i.dfy.CheckWellformed__InsertModel.__default.insertCorrect.smt2   |   1.472s |93.788MiB|
|d_komodo-verified-finalise.gen.dfyImpl___module.__default.lemma__kom__smc__finalise__success__helper2.smt2 |   1.448s |93.664MiB|
|d_lvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.ValToBucket.smt2        |   1.399s |93.148MiB|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.ReadSectorCorrect.smt2                  |   1.485s |92.888MiB|
|d_fvbkv-Impl-CacheImpl.i.dfy.CheckWellformed__CacheImpl.MutCache.Remove.smt2               |   1.562s |91.576MiB|
|d_lvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.CheckWellformed__ByteSystem.__default.I.smt2 |   1.243s |89.784MiB|
|d_komodo-verified-exception_handlers.gen.dfyCheckWellformed___module.__default.lemma__pageDbDispatcherVerifyStateCorresponds.smt2 |   1.249s |88.7MiB|
|d_komodo-verified-sha-hmac.gen.dfyCheckWellformed___module.__default.va__lemma__hmac__outer__prep__ctx.smt2 |   1.304s |88.532MiB|
|d_fvbkv-Impl-StateModel.i.dfy.CheckWellformed__StateModel.__default.WFSector.smt2          |   1.468s |88.492MiB|
|d_lvbkv-Impl-CacheImpl.i.dfy.Impl__CacheImpl.LMutCache.NodePartialFlush.smt2               |   1.341s |87.696MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BlockInterface.i.dfy.CheckWellformed__BlockInterface.__default.IsStatePath.smt2  |   0.222s  |   0.222s  |   0.000s  | 0.0%|
|d_fvbkv-Betree-Graph.i.dfy.Impl__Graph.__default.AcyclicGraphImpliesSimplePath.smt2         |   0.208s  |   0.208s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.NewRequestReadNodeDoesntOverlap.smt2  |   1.008s  |   1.008s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-DiskLayout.i.dfy.CheckWellformed__DiskLayout.__default.JournalBackLocation.smt2  |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.CheckWellformed__JournalSystem.__default.FreezeStepPreservesJournals.smt2  |   0.587s  |   0.587s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.Impl__JournalSystem.__default.ProcessWriteSuperblockPreservesJournals.smt2  |   0.900s  |   0.900s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-AsyncDiskModel.s.dfy.CheckWellformed__AsyncDisk.__default.AckRead.smt2  |   0.211s  |   0.211s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CacheImpl.i.dfy.CheckWellformed__CacheImpl.MutCache.Remove.smt2                |   1.562s  |   1.562s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterImpl.i.dfy.CheckWellformed__CommitterImpl.Committer.__ctor.smt2       |   0.784s  |   0.784s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CoordinationModel.i.dfy.CheckWellformed__CoordinationModel.__default.initialization.smt2  |   1.728s  |   1.728s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.ReadSectorCorrect.smt2                   |   1.485s  |   1.485s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-InsertModel.i.dfy.CheckWellformed__InsertModel.__default.insertCorrect.smt2    |   1.472s  |   1.472s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.CheckWellformed__JournalistMarshallingModel.__default.hasChecksums.smt2  |   0.338s  |   0.338s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MainHandlers.i.dfy.CheckWellformed__MainHandlers.__default.InitState.smt2      |   2.099s  |   2.099s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-StateModel.i.dfy.CheckWellformed__StateModel.__default.WFSector.smt2           |   1.468s  |   1.468s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-SuccModel.i.dfy.CheckWellformed__SuccModel.__default.getPathInternal.smt2      |   1.669s  |   1.669s  |   0.000s  | 0.0%|
|d_fvbkv-MapSpec-TSJ.i.dfy.Impl__TSJ.__default.PushSyncStepPreservesInv.smt2                 |   0.238s  |   0.238s  |   0.000s  | 0.0%|
|d_fvbkv-MapSpec-TSJMap_Refines_ThreeStateVersionedMap.i.dfy.Impl__TSJMap__Refines__ThreeStateVersionedMap.__default.apply__path.smt2  |   0.275s  |   0.275s  |   0.000s  | 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupUpperBound.smt2  |   0.523s  |   0.523s  |   0.000s  | 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupVisitsWFNodes.smt2  |   0.539s  |   0.539s  |   0.000s  | 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.Impl__PivotBetreeSpecRefinement.__default.InterpretBucketStackEqInterpretLookup.smt2  |   0.692s  |   0.692s  |   0.000s  | 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpecWFNodes.i.dfy.Impl__PivotBetreeSpecWFNodes.__default.ValidRepivotWFNodes.smt2  |   0.538s  |   0.538s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-sequences.i.dfy.Impl__Sequences.__default.FlattenLengthSubSeq.smt2         |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-total_order.i.dfy.CheckWellformed__Total__Order.__default.strictlySortedInsert2.smt2  |   0.208s  |   0.208s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-total_order.i.dfy.Impl__Uint32__Order.__default.LargestLteIsUnique2.smt2   |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-total_order_impl.i.dfy.CheckWellformed__Byte__Order__Impl.__default.ArrayLargestLtePlus1.smt2  |   0.256s  |   0.256s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.CheckWellformed__PackedStringArray.__default.LargestLte.smt2  |   0.284s  |   0.284s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-KMBtree.i.dfy.Impl__KMBtreeModel.__default.SplitIndexInterpretation2.smt2  |   0.331s  |   0.331s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.CheckWellformed__TestMutableBtree.__default.MaxKeysPerLeaf.smt2  |   0.299s  |   0.299s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__TestMutableBtree.__default.SubIndex.smt2  |   0.347s  |   0.347s  |   0.000s  | 0.0%|
|d_komodo-verified-ARMdef.s.dfyCheckWellformed___module.__default.ValidGlobalOffset.smt2     |   0.290s  |   0.290s  |   0.000s  | 0.0%|
|d_komodo-verified-ARMdef.s.dfyCheckWellformed___module.__default.ValidModeEncoding.smt2     |   0.283s  |   0.283s  |   0.000s  | 0.0%|
|d_komodo-verified-ARMprint.s.dfyImpl___module.__default.printGlobal.smt2                    |   0.252s  |   0.252s  |   0.000s  | 0.0%|
|d_komodo-verified-Seq.dfyCheckWellformed___module.__default.MapSeqToSeq.smt2                |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|d_komodo-verified-attest_helpers.gen.dfyImpl___module.__default.va__lemma__mem__move__global.smt2  |   2.530s  |   2.530s  |   0.000s  | 0.0%|
|d_komodo-verified-bitvectors.i.dfyCheckWellformed___module.__default.lemma__LeftShift2.smt2  |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|d_komodo-verified-bitvectors.i.dfyCheckWellformed___module.__default.lemma__RightShift2.smt2  |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.gen.dfyCheckWellformed___module.__default.va__lemma__smc__enter__err.smt2  |   0.834s  |   0.834s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.i.dfyCheckWellformed___module.__default.lemma__singlestep__execution.smt2  |   0.517s  |   0.517s  |   0.000s  | 0.0%|
|d_komodo-verified-exception_handlers.gen.dfyCheckWellformed___module.__default.lemma__pageDbDispatcherVerifyStateCorresponds.smt2  |   1.249s  |   1.249s  |   0.000s  | 0.0%|
|d_komodo-verified-exceptions.i.dfyCheckWellformed___module.__default.lemma__Establish__InterruptContinuationPrecondition.smt2  |   0.577s  |   0.577s  |   0.000s  | 0.0%|
|d_komodo-verified-finalise.gen.dfyImpl___module.__default.lemma__kom__smc__finalise__success__helper2.smt2  |   1.448s  |   1.448s  |   0.000s  | 0.0%|
|d_komodo-verified-kom_common.i.dfyImpl___module.__default.lemma__ValidMemRangeExPageTable__persists.smt2  |   1.679s  |   1.679s  |   0.000s  | 0.0%|
|d_komodo-verified-kom_common.s.dfyCheckWellformed___module.__default.AttestKey.smt2         |   0.298s  |   0.298s  |   0.000s  | 0.0%|
|d_komodo-verified-kom_utils.gen.dfyCheckWellformed___module.__default.va__code__STRx.smt2   |   0.531s  |   0.531s  |   0.000s  | 0.0%|
|d_komodo-verified-kom_utils.gen.dfyImpl___module.__default.va__lemma__page__monvaddr__impl.smt2  |   1.656s  |   1.656s  |   0.000s  | 0.0%|
|d_komodo-verified-map_common.gen.dfyImpl___module.__default.lemma__read__l2pte__zero.smt2   |   1.427s  |   1.427s  |   0.000s  | 0.0%|
|d_komodo-verified-pagedb.s.dfyCheckWellformed___module.__default.validInsecurePageNr.smt2   |   0.372s  |   0.372s  |   0.000s  | 0.0%|
|d_komodo-verified-ptebits.i.dfyCheckWellformed___module.__default.lemma__nonexec__mapping.smt2  |   0.446s  |   0.446s  |   0.000s  | 0.0%|
|d_komodo-verified-ptebits.i.dfyImpl___module.__default.lemma__BitOrNineIsLikePlus.smt2      |   0.664s  |   0.664s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-hmac.gen.dfyCheckWellformed___module.__default.va__lemma__hmac__outer__prep__ctx.smt2  |   1.304s  |   1.304s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-sha256-body-00-15.gen.dfyCheckWellformed___module.__default.va__if__abstract__Body__00__15UnrolledRecursive.smt2  |   0.710s  |   0.710s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-sha256-body-16-xx.gen.dfyImpl___module.__default.va__refined__Body__16__XXUnroller_split0.smt2  |   2.048s  |   2.048s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-sha256-helpers.i.dfyCheckWellformed___module.__default.lemma__BitwiseAdd32Associates5.smt2  |   0.421s  |   0.421s  |   0.000s  | 0.0%|
|d_komodo-verified-stop.gen.dfyCheckWellformed___module.__default.va__lemma__kom__smc__stop.smt2  |   0.636s  |   0.636s  |   0.000s  | 0.0%|
|d_komodo-verified-valedecls.gen.dfyImpl___module.__default.va__lemma__MOVShift.smt2         |   0.376s  |   0.376s  |   0.000s  | 0.0%|
|d_komodo-verified-valesupp.i.dfyCheckWellformed___module.__default.va__lemma__whileTrue.smt2  |   0.315s  |   0.315s  |   0.000s  | 0.0%|
|d_komodo-verified-verify.gen.dfyCheckWellformed___module.__default.va__code__svc__returning__verify.smt2  |   1.327s  |   1.327s  |   0.000s  | 0.0%|
|d_komodo-verified-words_and_bytes.i.dfyImpl___module.__default.lemma__BytesToWord__WordToBytes__inverses.smt2  |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|d_komodo-verified-words_and_bytes.s.dfyCheckWellformed___module.__default.ConcatenateSeqs.smt2  |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|d_lvbkv-Betree-Betree_Refines_Map.i.dfy.CheckWellformed__Betree__Refines__Map.__default.RefinesInit.smt2  |   0.422s  |   0.422s  |   0.000s  | 0.0%|
|d_lvbkv-Betree-BlockInterface.i.dfy.Impl__BlockInterface.__default.Transaction3Steps.smt2   |   0.189s  |   0.189s  |   0.000s  | 0.0%|
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.NewRequestReadIndirectionTableIsValid.smt2  |   4.484s  |   4.484s  |   0.000s  | 0.0%|
|d_lvbkv-BlockCacheSystem-DiskLayout.i.dfy.CheckWellformed__DiskLayout.__default.locContainedInCircularJournalRange.smt2  |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|d_lvbkv-BlockCacheSystem-JournalSystem.i.dfy.CheckWellformed__JournalSystem.__default.NoOpStepPreservesJournals.smt2  |   0.687s  |   0.687s  |   0.000s  | 0.0%|
|d_lvbkv-ByteBlockCacheSystem-AsyncDiskModel.s.dfy.CheckWellformed__AsyncDisk.__default.ChecksumChecksOut.smt2  |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|d_lvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.CheckWellformed__ByteSystem.__default.I.smt2  |   1.243s  |   1.243s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-CacheImpl.i.dfy.Impl__CacheImpl.LMutCache.NodePartialFlush.smt2                |   1.341s  |   1.341s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-CoordinationImpl.i.dfy.Impl__CoordinationImpl.__default.pushSync.smt2          |   1.834s  |   1.834s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-IOImpl.i.dfy.CheckWellformed__IOImpl.__default.getFreeLoc.smt2                 |   1.607s  |   1.607s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-JournalistImpl.i.dfy.CheckWellformed__JournalistImpl.__default.MaxPossibleEntries.smt2  |   0.350s  |   0.350s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.ValToBucket.smt2         |   1.399s  |   1.399s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-SplitModel.i.dfy.CheckWellformed__SplitModel.__default.lemmaChildrenConditionsCutoffNode.smt2  |   1.404s  |   1.404s  |   0.000s  | 0.0%|
|d_lvbkv-MapSpec-TSJMap.i.dfy.Impl__TSJMap.__default.Move2to3StepPreservesInv.smt2           |   0.276s  |   0.276s  |   0.000s  | 0.0%|
|d_lvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.CheckWellformed__PivotBetreeSpecRefinement.__default.INode.smt2  |   0.714s  |   0.714s  |   0.000s  | 0.0%|
|d_lvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.CheckWellformed__PivotBetreeSpecRefinement.__default.InterpretBucketStack.smt2  |   0.707s  |   0.707s  |   0.000s  | 0.0%|
|d_lvbkv-PivotBetree-PivotBetreeSpecWFNodes.i.dfy.CheckWellformed__PivotBetreeSpecWFNodes.__default.bucket__msgs__equiv.smt2  |   0.504s  |   0.504s  |   0.000s  | 0.0%|
|d_lvbkv-PivotBetree-StatesViewPivotBetree_Refines_StatesViewMap.i.dfy.CheckWellformed__StatesViewPivotBetree__Refines__StatesViewMap.__default.RefinesNextStep.smt2  |   0.769s  |   0.769s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-BitsetLemmas.i.dfy.CheckWellformed__BitsetLemmas.__default.bit.smt2        |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-BitsetLemmas.i.dfy.CheckWellformed__BitsetLemmas.__default.bit__comp__ne__expanded.smt2  |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-Message.i.dfy.CheckWellformed__ValueMessage.__default.EncodableMessageSeq.smt2  |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-MutableVec.i.dfy.CheckWellformed__MutableVec.Vec.insert.smt2               |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-total_order.i.dfy.Impl__Integer__Order.__default.StrictlySortedImpliesSorted.smt2  |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-total_order_impl.i.dfy.Impl__Byte__Order__Impl.__default.ComputeIsSorted.smt2  |   0.208s  |   0.208s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-total_order_impl.i.dfy.Impl__Uint64__Order__Impl.__default.BatchLargestLte.smt2  |   0.230s  |   0.230s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Checksums-BitLemmas.i.dfy.Impl__BitLemmas.__default.bits__of__int__combine.smt2  |   0.449s  |   0.449s  |   0.000s  | 0.0%|
|d_lvbkv-lib-DataStructures-KMBtree.i.dfy.Impl__KMBtreeModel.__default.SplitChildOfIndexPreservesAllKeys.smt2  |   0.355s  |   0.355s  |   0.000s  | 0.0%|
|d_lvbkv-lib-DataStructures-LinearMutableMap.i.dfy.CheckWellformed__LinearMutableMap.__default.FixedSizeUpdateBySlot.smt2  |   0.264s  |   0.264s  |   0.000s  | 0.0%|
|d_lvbkv-lib-DataStructures-LinearMutableMapBase.i.dfy.CheckWellformed__LinearMutableMapBase.__default.lshift.smt2  |   0.189s  |   0.189s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Math-Math.i.dfy.Impl__Math.__default.lemma__power2__div__is__sub.smt2           |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|s_komodo-1440.0.smt2                                                                        |   0.424s  |   0.424s  |   0.000s  | 0.0%|
|s_komodo-1441.2.smt2                                                                        |   0.240s  |   0.240s  |   0.000s  | 0.0%|
|s_komodo-1456.4.smt2                                                                        |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|s_komodo-1457.2.smt2                                                                        |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|s_komodo-1466.1.smt2                                                                        |   0.277s  |   0.277s  |   0.000s  | 0.0%|
|s_komodo-1469.1.smt2                                                                        |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|s_komodo-1470.0.smt2                                                                        |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|s_komodo-1484.7.smt2                                                                        |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|s_komodo-1486.1.smt2                                                                        |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|s_komodo-1487.4.smt2                                                                        |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|s_komodo-1490.0.smt2                                                                        |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|s_komodo-1493.3.smt2                                                                        |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|s_komodo-1494.5.smt2                                                                        |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|s_komodo-1496.2.smt2                                                                        |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|s_komodo-1500.4.smt2                                                                        |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|s_komodo-1500.6.smt2                                                                        |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|s_komodo-1501.7.smt2                                                                        |   0.790s  |   0.790s  |   0.000s  | 0.0%|
|s_komodo-1502.2.smt2                                                                        |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|s_komodo-1503.6.smt2                                                                        |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|s_komodo-1505.3.smt2                                                                        |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|s_komodo-1506.1.smt2                                                                        |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|s_komodo-1511.8.smt2                                                                        |   0.327s  |   0.327s  |   0.000s  | 0.0%|
|s_komodo-1516.11.smt2                                                                       |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|s_komodo-1516.7.smt2                                                                        |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|s_komodo-1526.0.smt2                                                                        |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|s_komodo-1531.0.smt2                                                                        |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|s_komodo-1533.7.smt2                                                                        |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|s_komodo-1534.9.smt2                                                                        |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|s_komodo-1544.3.smt2                                                                        |   0.041s  |   0.041s  |   0.000s  | 0.0%|
</details>
