Comparing data and data


# SUMMARY
- LHS tests = 280
- RHS tests = 280
- LHS success = 278  (99.28571428571429%)
- RHS success = 278  (99.28571428571429%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: pre-gen-patch-mariposa-ue
Runner: rise-runner-1
Z3 repo: CanCebeci/z3
Z3 commit: 51cbbe0a0ea3259ec92255e86e5818d1d6a9e523
Z3 branch: 51cbbe0a0ea3259ec92255e86e5818d1d6a9e523
Z3 options: "%OPTIONS2%"
Z3 inputs: inputs/mariposa/unstable_ext
Z3 commit message: fix #9293

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: pre-gen-patch-mariposa-ue
Runner: rise-runner-1
Z3 repo: CanCebeci/z3
Z3 commit: 51cbbe0a0ea3259ec92255e86e5818d1d6a9e523
Z3 branch: 51cbbe0a0ea3259ec92255e86e5818d1d6a9e523
Z3 options: "%OPTIONS2%"
Z3 inputs: inputs/mariposa/unstable_ext
Z3 commit message: fix #9293

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.InitImpliesInv.smt2                |   0.531s  |   0.531s  |   0.000s  | 0.0%|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectPreservesLookups.smt2      |   8.914s  |   8.914s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-JournalInterval.i.dfy.Impl__JournalIntervals.__default.Disk__Journal__append.smt2  |   1.147s  |   1.147s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBlockOfJournalRange.smt2  |   0.376s  |   0.376s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBytesSplit.smt2  |   0.382s  |   0.382s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeEqJournalBlocks.smt2  |   2.687s  |   2.687s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeOfByteSeqGetI.smt2  |   0.757s  |   0.757s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-Marshalling.i.dfy.Impl__Marshalling.__default.pivotTableWeightUpperBound.smt2  |   4.743s  |   4.743s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeeping.smt2    |   6.655s  |   6.655s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeepingNoSuccsUpdate.smt2  |   5.951s  |   5.951s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketGeneratorModel.i.dfy.Impl__BucketGeneratorModel.__default.GenFromBucketStackWithLowerBoundYieldsComposeSeq.smt2  |   2.841s  |   2.841s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.GetSuccessorInBucketStackResult.smt2  |   1.557s  |   1.557s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.ProcessGeneratorResult.smt2  |  16.845s  |  16.845s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterCommitImpl.i.dfy.Impl__CommitterCommitImpl.__default.WriteOutJournal.smt2  |  20.381s  |  20.381s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.CheckWellformed__CommitterCommitModel.__default.WriteOutJournal.smt2  |   1.858s  |   1.858s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.Impl__CommitterCommitModel.__default.WriteOutJournalCorrect.smt2  |   3.163s  |   3.163s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-DeallocImpl.i.dfy.Impl__DeallocImpl.__default.Dealloc.smt2                     |  44.879s  |  44.879s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-GrowImpl.i.dfy.Impl__GrowImpl.__default.grow.smt2                              |  33.541s  |  33.541s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.PageInIndirectionTableResp.smt2            |  48.415s  |  48.415s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.FindIndirectionTableLocationAndRequestWriteCorrect.smt2  |   3.578s  |   3.578s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.InitImpliesInv.smt2                |   0.531s  |   0.531s  |   0.000s  | 0.0%|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectPreservesLookups.smt2      |   8.914s  |   8.914s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-JournalInterval.i.dfy.Impl__JournalIntervals.__default.Disk__Journal__append.smt2  |   1.147s  |   1.147s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBlockOfJournalRange.smt2  |   0.376s  |   0.376s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBytesSplit.smt2  |   0.382s  |   0.382s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeEqJournalBlocks.smt2  |   2.687s  |   2.687s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeOfByteSeqGetI.smt2  |   0.757s  |   0.757s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-Marshalling.i.dfy.Impl__Marshalling.__default.pivotTableWeightUpperBound.smt2  |   4.743s  |   4.743s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeeping.smt2    |   6.655s  |   6.655s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeepingNoSuccsUpdate.smt2  |   5.951s  |   5.951s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketGeneratorModel.i.dfy.Impl__BucketGeneratorModel.__default.GenFromBucketStackWithLowerBoundYieldsComposeSeq.smt2  |   2.841s  |   2.841s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.GetSuccessorInBucketStackResult.smt2  |   1.557s  |   1.557s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.ProcessGeneratorResult.smt2  |  16.845s  |  16.845s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterCommitImpl.i.dfy.Impl__CommitterCommitImpl.__default.WriteOutJournal.smt2  |  20.381s  |  20.381s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.CheckWellformed__CommitterCommitModel.__default.WriteOutJournal.smt2  |   1.858s  |   1.858s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.Impl__CommitterCommitModel.__default.WriteOutJournalCorrect.smt2  |   3.163s  |   3.163s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-DeallocImpl.i.dfy.Impl__DeallocImpl.__default.Dealloc.smt2                     |  44.879s  |  44.879s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-GrowImpl.i.dfy.Impl__GrowImpl.__default.grow.smt2                              |  33.541s  |  33.541s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.PageInIndirectionTableResp.smt2            |  48.415s  |  48.415s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.FindIndirectionTableLocationAndRequestWriteCorrect.smt2  |   3.578s  |   3.578s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.InitImpliesInv.smt2                |   0.531s  |   0.531s  |   0.000s  | 0.0%|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectPreservesLookups.smt2      |   8.914s  |   8.914s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-JournalInterval.i.dfy.Impl__JournalIntervals.__default.Disk__Journal__append.smt2  |   1.147s  |   1.147s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBlockOfJournalRange.smt2  |   0.376s  |   0.376s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBytesSplit.smt2  |   0.382s  |   0.382s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeEqJournalBlocks.smt2  |   2.687s  |   2.687s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeOfByteSeqGetI.smt2  |   0.757s  |   0.757s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-Marshalling.i.dfy.Impl__Marshalling.__default.pivotTableWeightUpperBound.smt2  |   4.743s  |   4.743s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeeping.smt2    |   6.655s  |   6.655s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeepingNoSuccsUpdate.smt2  |   5.951s  |   5.951s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketGeneratorModel.i.dfy.Impl__BucketGeneratorModel.__default.GenFromBucketStackWithLowerBoundYieldsComposeSeq.smt2  |   2.841s  |   2.841s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.GetSuccessorInBucketStackResult.smt2  |   1.557s  |   1.557s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.ProcessGeneratorResult.smt2  |  16.845s  |  16.845s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterCommitImpl.i.dfy.Impl__CommitterCommitImpl.__default.WriteOutJournal.smt2  |  20.381s  |  20.381s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.CheckWellformed__CommitterCommitModel.__default.WriteOutJournal.smt2  |   1.858s  |   1.858s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.Impl__CommitterCommitModel.__default.WriteOutJournalCorrect.smt2  |   3.163s  |   3.163s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-DeallocImpl.i.dfy.Impl__DeallocImpl.__default.Dealloc.smt2                     |  44.879s  |  44.879s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-GrowImpl.i.dfy.Impl__GrowImpl.__default.grow.smt2                              |  33.541s  |  33.541s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.PageInIndirectionTableResp.smt2            |  48.415s  |  48.415s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.FindIndirectionTableLocationAndRequestWriteCorrect.smt2  |   3.578s  |   3.578s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.InitImpliesInv.smt2                |   0.531s  |   0.531s  |   0.000s  | 0.0%|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectPreservesLookups.smt2      |   8.914s  |   8.914s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-JournalInterval.i.dfy.Impl__JournalIntervals.__default.Disk__Journal__append.smt2  |   1.147s  |   1.147s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBlockOfJournalRange.smt2  |   0.376s  |   0.376s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBytesSplit.smt2  |   0.382s  |   0.382s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeEqJournalBlocks.smt2  |   2.687s  |   2.687s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeOfByteSeqGetI.smt2  |   0.757s  |   0.757s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-Marshalling.i.dfy.Impl__Marshalling.__default.pivotTableWeightUpperBound.smt2  |   4.743s  |   4.743s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeeping.smt2    |   6.655s  |   6.655s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeepingNoSuccsUpdate.smt2  |   5.951s  |   5.951s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketGeneratorModel.i.dfy.Impl__BucketGeneratorModel.__default.GenFromBucketStackWithLowerBoundYieldsComposeSeq.smt2  |   2.841s  |   2.841s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.GetSuccessorInBucketStackResult.smt2  |   1.557s  |   1.557s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.ProcessGeneratorResult.smt2  |  16.845s  |  16.845s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterCommitImpl.i.dfy.Impl__CommitterCommitImpl.__default.WriteOutJournal.smt2  |  20.381s  |  20.381s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.CheckWellformed__CommitterCommitModel.__default.WriteOutJournal.smt2  |   1.858s  |   1.858s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.Impl__CommitterCommitModel.__default.WriteOutJournalCorrect.smt2  |   3.163s  |   3.163s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-DeallocImpl.i.dfy.Impl__DeallocImpl.__default.Dealloc.smt2                     |  44.879s  |  44.879s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-GrowImpl.i.dfy.Impl__GrowImpl.__default.grow.smt2                              |  33.541s  |  33.541s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.PageInIndirectionTableResp.smt2            |  48.415s  |  48.415s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.FindIndirectionTableLocationAndRequestWriteCorrect.smt2  |   3.578s  |   3.578s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|s_komodo-1518.6.smt2                                                                       |  81.167s |16.224GiB|
|s_komodo-1557.3.smt2                                                                       |  80.036s |278.0MiB|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__svcHandled__loweq__pdb.smt2 |  53.946s |335.0MiB|
|d_komodo-verified-entry.gen.dfyImpl___module.__default.va__lemma__kom__smc__enterresume.smt2 |  50.383s |189.0MiB|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.DynamicPkv.AppendPkv.smt2              |  50.322s |146.0MiB|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.PageInIndirectionTableResp.smt2           |  48.415s |183.0MiB|
|d_lvbkv-Impl-IndirectionTable.i.dfy.Impl__IndirectionTable.IndirectionTable.IndirectionTableToVal.smt2 |  48.267s |192.0MiB|
|d_komodo-verified-sha-sha256-one-block.gen.dfyImpl___module.__default.va__abstract__update__Hs.smt2 |  47.440s |138.0MiB|
|d_komodo-verified-stop.gen.dfyImpl___module.__default.va__lemma__kom__smc__stop.smt2       |  47.099s |258.0MiB|
|d_lvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.GrowStepPreservesInvariant.smt2   |  46.719s |131.0MiB|
|d_komodo-verified-svc_handlers.gen.dfyImpl___module.__default.lemma__svc__returning__verify__step0__helper.smt2 |  46.099s |191.0MiB|
|d_komodo-verified-allocate_page.gen.dfyImpl___module.__default.va__lemma__addrspace__incref.smt2 |  45.677s |204.0MiB|
|d_lvbkv-lib-Buckets-LKMBPKVOps.i.dfy.Impl__LKMBPKVOps.__default.IsKeyMessageTreeInheritance.smt2 |  45.266s |230.0MiB|
|d_fvbkv-Impl-DeallocImpl.i.dfy.Impl__DeallocImpl.__default.Dealloc.smt2                    |  44.879s |184.0MiB|
|d_komodo-verified-map_common.gen.dfyImpl___module.__default.va__lemma__insecure__phys__to__virt.smt2 |  43.380s |189.0MiB|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.__default.MergeToChildrenIter.smt2     |  43.122s |194.0MiB|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__validEnclaveStepPrime__conf__not__atkr__retnondet.smt2 |  40.699s |214.0MiB|
|d_komodo-verified-exceptions.i.dfyImpl___module.__default.lemma__PrivInterruptInvariants.smt2 |  39.706s |194.0MiB|
|d_komodo-verified-sha-sha256-block-data-order.gen.dfyImpl___module.__default.va__refined__sha256__block__data__order_split0.smt2 |  39.157s |135.0MiB|
|d_lvbkv-BlockCacheSystem-BetreeSystem_Refines_StatesViewPivotBetree.i.dfy.Impl__BetreeSystem__Refines__StatesViewPivotBetree.__default.BetreeMoveStepRefines.smt2 |  38.923s |348.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|s_komodo-1518.6.smt2                                                                       |  81.167s |16.224GiB|
|s_komodo-1557.3.smt2                                                                       |  80.036s |278.0MiB|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__svcHandled__loweq__pdb.smt2 |  53.946s |335.0MiB|
|d_komodo-verified-entry.gen.dfyImpl___module.__default.va__lemma__kom__smc__enterresume.smt2 |  50.383s |189.0MiB|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.DynamicPkv.AppendPkv.smt2              |  50.322s |146.0MiB|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.PageInIndirectionTableResp.smt2           |  48.415s |183.0MiB|
|d_lvbkv-Impl-IndirectionTable.i.dfy.Impl__IndirectionTable.IndirectionTable.IndirectionTableToVal.smt2 |  48.267s |192.0MiB|
|d_komodo-verified-sha-sha256-one-block.gen.dfyImpl___module.__default.va__abstract__update__Hs.smt2 |  47.440s |138.0MiB|
|d_komodo-verified-stop.gen.dfyImpl___module.__default.va__lemma__kom__smc__stop.smt2       |  47.099s |258.0MiB|
|d_lvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.GrowStepPreservesInvariant.smt2   |  46.719s |131.0MiB|
|d_komodo-verified-svc_handlers.gen.dfyImpl___module.__default.lemma__svc__returning__verify__step0__helper.smt2 |  46.099s |191.0MiB|
|d_komodo-verified-allocate_page.gen.dfyImpl___module.__default.va__lemma__addrspace__incref.smt2 |  45.677s |204.0MiB|
|d_lvbkv-lib-Buckets-LKMBPKVOps.i.dfy.Impl__LKMBPKVOps.__default.IsKeyMessageTreeInheritance.smt2 |  45.266s |230.0MiB|
|d_fvbkv-Impl-DeallocImpl.i.dfy.Impl__DeallocImpl.__default.Dealloc.smt2                    |  44.879s |184.0MiB|
|d_komodo-verified-map_common.gen.dfyImpl___module.__default.va__lemma__insecure__phys__to__virt.smt2 |  43.380s |189.0MiB|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.__default.MergeToChildrenIter.smt2     |  43.122s |194.0MiB|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__validEnclaveStepPrime__conf__not__atkr__retnondet.smt2 |  40.699s |214.0MiB|
|d_komodo-verified-exceptions.i.dfyImpl___module.__default.lemma__PrivInterruptInvariants.smt2 |  39.706s |194.0MiB|
|d_komodo-verified-sha-sha256-block-data-order.gen.dfyImpl___module.__default.va__refined__sha256__block__data__order_split0.smt2 |  39.157s |135.0MiB|
|d_lvbkv-BlockCacheSystem-BetreeSystem_Refines_StatesViewPivotBetree.i.dfy.Impl__BetreeSystem__Refines__StatesViewPivotBetree.__default.BetreeMoveStepRefines.smt2 |  38.923s |348.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.InitImpliesInv.smt2                |50.032MiB|50.032MiB|0B| 0.0%|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectPreservesLookups.smt2      |94.436MiB|94.436MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-JournalInterval.i.dfy.Impl__JournalIntervals.__default.Disk__Journal__append.smt2  |34.644MiB|34.644MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBlockOfJournalRange.smt2  |30.368MiB|30.368MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBytesSplit.smt2  |30.688MiB|30.688MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeEqJournalBlocks.smt2  |56.912MiB|56.912MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeOfByteSeqGetI.smt2  |35.128MiB|35.128MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-Marshalling.i.dfy.Impl__Marshalling.__default.pivotTableWeightUpperBound.smt2  |133.0MiB|133.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeeping.smt2    |168.0MiB|168.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeepingNoSuccsUpdate.smt2  |168.0MiB|168.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketGeneratorModel.i.dfy.Impl__BucketGeneratorModel.__default.GenFromBucketStackWithLowerBoundYieldsComposeSeq.smt2  |58.444MiB|58.444MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.GetSuccessorInBucketStackResult.smt2  |55.056MiB|55.056MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.ProcessGeneratorResult.smt2  |109.0MiB|109.0MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterCommitImpl.i.dfy.Impl__CommitterCommitImpl.__default.WriteOutJournal.smt2  |182.0MiB|182.0MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.CheckWellformed__CommitterCommitModel.__default.WriteOutJournal.smt2  |95.836MiB|95.836MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.Impl__CommitterCommitModel.__default.WriteOutJournalCorrect.smt2  |108.0MiB|108.0MiB|0B| 0.0%|
|d_fvbkv-Impl-DeallocImpl.i.dfy.Impl__DeallocImpl.__default.Dealloc.smt2                     |184.0MiB|184.0MiB|0B| 0.0%|
|d_fvbkv-Impl-GrowImpl.i.dfy.Impl__GrowImpl.__default.grow.smt2                              |195.0MiB|195.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.PageInIndirectionTableResp.smt2            |183.0MiB|183.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.FindIndirectionTableLocationAndRequestWriteCorrect.smt2  |107.0MiB|107.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.InitImpliesInv.smt2                |50.032MiB|50.032MiB|0B| 0.0%|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectPreservesLookups.smt2      |94.436MiB|94.436MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-JournalInterval.i.dfy.Impl__JournalIntervals.__default.Disk__Journal__append.smt2  |34.644MiB|34.644MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBlockOfJournalRange.smt2  |30.368MiB|30.368MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBytesSplit.smt2  |30.688MiB|30.688MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeEqJournalBlocks.smt2  |56.912MiB|56.912MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeOfByteSeqGetI.smt2  |35.128MiB|35.128MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-Marshalling.i.dfy.Impl__Marshalling.__default.pivotTableWeightUpperBound.smt2  |133.0MiB|133.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeeping.smt2    |168.0MiB|168.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeepingNoSuccsUpdate.smt2  |168.0MiB|168.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketGeneratorModel.i.dfy.Impl__BucketGeneratorModel.__default.GenFromBucketStackWithLowerBoundYieldsComposeSeq.smt2  |58.444MiB|58.444MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.GetSuccessorInBucketStackResult.smt2  |55.056MiB|55.056MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.ProcessGeneratorResult.smt2  |109.0MiB|109.0MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterCommitImpl.i.dfy.Impl__CommitterCommitImpl.__default.WriteOutJournal.smt2  |182.0MiB|182.0MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.CheckWellformed__CommitterCommitModel.__default.WriteOutJournal.smt2  |95.836MiB|95.836MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.Impl__CommitterCommitModel.__default.WriteOutJournalCorrect.smt2  |108.0MiB|108.0MiB|0B| 0.0%|
|d_fvbkv-Impl-DeallocImpl.i.dfy.Impl__DeallocImpl.__default.Dealloc.smt2                     |184.0MiB|184.0MiB|0B| 0.0%|
|d_fvbkv-Impl-GrowImpl.i.dfy.Impl__GrowImpl.__default.grow.smt2                              |195.0MiB|195.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.PageInIndirectionTableResp.smt2            |183.0MiB|183.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.FindIndirectionTableLocationAndRequestWriteCorrect.smt2  |107.0MiB|107.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.InitImpliesInv.smt2                |50.032MiB|50.032MiB|0B| 0.0%|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectPreservesLookups.smt2      |94.436MiB|94.436MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-JournalInterval.i.dfy.Impl__JournalIntervals.__default.Disk__Journal__append.smt2  |34.644MiB|34.644MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBlockOfJournalRange.smt2  |30.368MiB|30.368MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBytesSplit.smt2  |30.688MiB|30.688MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeEqJournalBlocks.smt2  |56.912MiB|56.912MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeOfByteSeqGetI.smt2  |35.128MiB|35.128MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-Marshalling.i.dfy.Impl__Marshalling.__default.pivotTableWeightUpperBound.smt2  |133.0MiB|133.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeeping.smt2    |168.0MiB|168.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeepingNoSuccsUpdate.smt2  |168.0MiB|168.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketGeneratorModel.i.dfy.Impl__BucketGeneratorModel.__default.GenFromBucketStackWithLowerBoundYieldsComposeSeq.smt2  |58.444MiB|58.444MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.GetSuccessorInBucketStackResult.smt2  |55.056MiB|55.056MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.ProcessGeneratorResult.smt2  |109.0MiB|109.0MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterCommitImpl.i.dfy.Impl__CommitterCommitImpl.__default.WriteOutJournal.smt2  |182.0MiB|182.0MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.CheckWellformed__CommitterCommitModel.__default.WriteOutJournal.smt2  |95.836MiB|95.836MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.Impl__CommitterCommitModel.__default.WriteOutJournalCorrect.smt2  |108.0MiB|108.0MiB|0B| 0.0%|
|d_fvbkv-Impl-DeallocImpl.i.dfy.Impl__DeallocImpl.__default.Dealloc.smt2                     |184.0MiB|184.0MiB|0B| 0.0%|
|d_fvbkv-Impl-GrowImpl.i.dfy.Impl__GrowImpl.__default.grow.smt2                              |195.0MiB|195.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.PageInIndirectionTableResp.smt2            |183.0MiB|183.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.FindIndirectionTableLocationAndRequestWriteCorrect.smt2  |107.0MiB|107.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.InitImpliesInv.smt2                |50.032MiB|50.032MiB|0B| 0.0%|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectPreservesLookups.smt2      |94.436MiB|94.436MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-JournalInterval.i.dfy.Impl__JournalIntervals.__default.Disk__Journal__append.smt2  |34.644MiB|34.644MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBlockOfJournalRange.smt2  |30.368MiB|30.368MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBytesSplit.smt2  |30.688MiB|30.688MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeEqJournalBlocks.smt2  |56.912MiB|56.912MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeOfByteSeqGetI.smt2  |35.128MiB|35.128MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-Marshalling.i.dfy.Impl__Marshalling.__default.pivotTableWeightUpperBound.smt2  |133.0MiB|133.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeeping.smt2    |168.0MiB|168.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeepingNoSuccsUpdate.smt2  |168.0MiB|168.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketGeneratorModel.i.dfy.Impl__BucketGeneratorModel.__default.GenFromBucketStackWithLowerBoundYieldsComposeSeq.smt2  |58.444MiB|58.444MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.GetSuccessorInBucketStackResult.smt2  |55.056MiB|55.056MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.ProcessGeneratorResult.smt2  |109.0MiB|109.0MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterCommitImpl.i.dfy.Impl__CommitterCommitImpl.__default.WriteOutJournal.smt2  |182.0MiB|182.0MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.CheckWellformed__CommitterCommitModel.__default.WriteOutJournal.smt2  |95.836MiB|95.836MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.Impl__CommitterCommitModel.__default.WriteOutJournalCorrect.smt2  |108.0MiB|108.0MiB|0B| 0.0%|
|d_fvbkv-Impl-DeallocImpl.i.dfy.Impl__DeallocImpl.__default.Dealloc.smt2                     |184.0MiB|184.0MiB|0B| 0.0%|
|d_fvbkv-Impl-GrowImpl.i.dfy.Impl__GrowImpl.__default.grow.smt2                              |195.0MiB|195.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.PageInIndirectionTableResp.smt2            |183.0MiB|183.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.FindIndirectionTableLocationAndRequestWriteCorrect.smt2  |107.0MiB|107.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|s_komodo-1518.6.smt2                                                                       |  81.167s |16.224GiB|
|d_komodo-verified-entry.i.dfyImpl___module.__default.lemma__userExecutionPreservesPrivState.smt2 |  33.368s |1976.0MiB|
|d_lvbkv-PivotBetree-PivotBetreeSpecWFNodes.i.dfy.Impl__PivotBetreeSpecWFNodes.__default.SplitMaps.smt2 |  34.964s |916.0MiB|
|d_lvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.PageInNodeResp.smt2                       |  38.444s |371.0MiB|
|d_komodo-verified-verify.gen.dfyImpl___module.__default.va__lemma__compare__memory__to__regs.smt2 |  20.005s |366.0MiB|
|d_komodo-verified-svc_handlers.gen.dfyImpl___module.__default.va__lemma__svc__map__data__zeropage.smt2 |  38.405s |355.0MiB|
|d_lvbkv-BlockCacheSystem-BetreeSystem_Refines_StatesViewPivotBetree.i.dfy.Impl__BetreeSystem__Refines__StatesViewPivotBetree.__default.BetreeMoveStepRefines.smt2 |  38.923s |348.0MiB|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__svcHandled__loweq__pdb.smt2 |  53.946s |335.0MiB|
|s_komodo-1557.3.smt2                                                                       |  80.036s |278.0MiB|
|d_komodo-verified-verify_input.gen.dfyImpl___module.__default.va__lemma__arrange__verification__input_split0.smt2 |   9.956s |268.0MiB|
|d_komodo-verified-attest_input.gen.dfyImpl___module.__default.va__lemma__arrange__attestation__input_split0.smt2 |  25.780s |267.0MiB|
|d_komodo-verified-finalise.gen.dfyImpl___module.__default.va__lemma__kom__smc__finalise.smt2 |  37.169s |264.0MiB|
|d_komodo-verified-stop.gen.dfyImpl___module.__default.va__lemma__kom__smc__stop.smt2       |  47.099s |258.0MiB|
|d_komodo-verified-sha-hmac.gen.dfyImpl___module.__default.va__lemma__hmac__inner__prep__hash.smt2 |  28.369s |257.0MiB|
|d_komodo-verified-map_utils.gen.dfyCheckWellformed___module.__default.va__lemma__kom__smc__map__measure__sha.smt2 |  25.152s |243.0MiB|
|d_lvbkv-lib-Buckets-PackedKVMarshalling.i.dfy.Impl__PackedKVMarshalling.__default.SizeOfVPackedStringArrayIsKeyListWeight.smt2 |  17.379s |243.0MiB|
|d_komodo-verified-init_addrspace.gen.dfyImpl___module.__default.va__lemma__init__addrspace.smt2 |  26.592s |242.0MiB|
|d_komodo-verified-secprop-integ_ni_entry.i.dfyImpl___module.__default.lemma__enter__enc__obs__enter.smt2 |  27.221s |241.0MiB|
|d_komodo-verified-init_l2ptable.gen.dfyImpl___module.__default.va__lemma__init__l2ptable__success.smt2 |  34.116s |237.0MiB|
|d_komodo-verified-verify_input.gen.dfyImpl___module.__default.lemma__grab__user__words.smt2 |  27.623s |236.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|s_komodo-1518.6.smt2                                                                       |  81.167s |16.224GiB|
|d_komodo-verified-entry.i.dfyImpl___module.__default.lemma__userExecutionPreservesPrivState.smt2 |  33.368s |1976.0MiB|
|d_lvbkv-PivotBetree-PivotBetreeSpecWFNodes.i.dfy.Impl__PivotBetreeSpecWFNodes.__default.SplitMaps.smt2 |  34.964s |916.0MiB|
|d_lvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.PageInNodeResp.smt2                       |  38.444s |371.0MiB|
|d_komodo-verified-verify.gen.dfyImpl___module.__default.va__lemma__compare__memory__to__regs.smt2 |  20.005s |366.0MiB|
|d_komodo-verified-svc_handlers.gen.dfyImpl___module.__default.va__lemma__svc__map__data__zeropage.smt2 |  38.405s |355.0MiB|
|d_lvbkv-BlockCacheSystem-BetreeSystem_Refines_StatesViewPivotBetree.i.dfy.Impl__BetreeSystem__Refines__StatesViewPivotBetree.__default.BetreeMoveStepRefines.smt2 |  38.923s |348.0MiB|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__svcHandled__loweq__pdb.smt2 |  53.946s |335.0MiB|
|s_komodo-1557.3.smt2                                                                       |  80.036s |278.0MiB|
|d_komodo-verified-verify_input.gen.dfyImpl___module.__default.va__lemma__arrange__verification__input_split0.smt2 |   9.956s |268.0MiB|
|d_komodo-verified-attest_input.gen.dfyImpl___module.__default.va__lemma__arrange__attestation__input_split0.smt2 |  25.780s |267.0MiB|
|d_komodo-verified-finalise.gen.dfyImpl___module.__default.va__lemma__kom__smc__finalise.smt2 |  37.169s |264.0MiB|
|d_komodo-verified-stop.gen.dfyImpl___module.__default.va__lemma__kom__smc__stop.smt2       |  47.099s |258.0MiB|
|d_komodo-verified-sha-hmac.gen.dfyImpl___module.__default.va__lemma__hmac__inner__prep__hash.smt2 |  28.369s |257.0MiB|
|d_komodo-verified-map_utils.gen.dfyCheckWellformed___module.__default.va__lemma__kom__smc__map__measure__sha.smt2 |  25.152s |243.0MiB|
|d_lvbkv-lib-Buckets-PackedKVMarshalling.i.dfy.Impl__PackedKVMarshalling.__default.SizeOfVPackedStringArrayIsKeyListWeight.smt2 |  17.379s |243.0MiB|
|d_komodo-verified-init_addrspace.gen.dfyImpl___module.__default.va__lemma__init__addrspace.smt2 |  26.592s |242.0MiB|
|d_komodo-verified-secprop-integ_ni_entry.i.dfyImpl___module.__default.lemma__enter__enc__obs__enter.smt2 |  27.221s |241.0MiB|
|d_komodo-verified-init_l2ptable.gen.dfyImpl___module.__default.va__lemma__init__l2ptable__success.smt2 |  34.116s |237.0MiB|
|d_komodo-verified-verify_input.gen.dfyImpl___module.__default.lemma__grab__user__words.smt2 |  27.623s |236.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.InitImpliesInv.smt2                |   0.531s  |   0.531s  |   0.000s  | 0.0%|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectPreservesLookups.smt2      |   8.914s  |   8.914s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-JournalInterval.i.dfy.Impl__JournalIntervals.__default.Disk__Journal__append.smt2  |   1.147s  |   1.147s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBlockOfJournalRange.smt2  |   0.376s  |   0.376s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBytesSplit.smt2  |   0.382s  |   0.382s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeEqJournalBlocks.smt2  |   2.687s  |   2.687s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeOfByteSeqGetI.smt2  |   0.757s  |   0.757s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-Marshalling.i.dfy.Impl__Marshalling.__default.pivotTableWeightUpperBound.smt2  |   4.743s  |   4.743s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeeping.smt2    |   6.655s  |   6.655s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeepingNoSuccsUpdate.smt2  |   5.951s  |   5.951s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketGeneratorModel.i.dfy.Impl__BucketGeneratorModel.__default.GenFromBucketStackWithLowerBoundYieldsComposeSeq.smt2  |   2.841s  |   2.841s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.GetSuccessorInBucketStackResult.smt2  |   1.557s  |   1.557s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.ProcessGeneratorResult.smt2  |  16.845s  |  16.845s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterCommitImpl.i.dfy.Impl__CommitterCommitImpl.__default.WriteOutJournal.smt2  |  20.381s  |  20.381s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.CheckWellformed__CommitterCommitModel.__default.WriteOutJournal.smt2  |   1.858s  |   1.858s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.Impl__CommitterCommitModel.__default.WriteOutJournalCorrect.smt2  |   3.163s  |   3.163s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-DeallocImpl.i.dfy.Impl__DeallocImpl.__default.Dealloc.smt2                     |  44.879s  |  44.879s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-GrowImpl.i.dfy.Impl__GrowImpl.__default.grow.smt2                              |  33.541s  |  33.541s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.PageInIndirectionTableResp.smt2            |  48.415s  |  48.415s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.FindIndirectionTableLocationAndRequestWriteCorrect.smt2  |   3.578s  |   3.578s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.PageInIndirectionTableRespCorrect.smt2   |   2.480s  |   2.480s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.FindRefWithNoLoc.smt2  |  14.801s  |  14.801s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.RemoveRef.smt2  |  19.566s  |  19.566s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.CheckWellformed__IndirectionTableModel.__default.UpdateAndRemoveLoc.smt2  |   3.840s  |   3.840s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.Impl__IndirectionTableModel.__default.LemmaRemoveRefStuff.smt2  |  11.171s  |  11.171s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistImpl.i.dfy.Impl__JournalistImpl.Journalist.parseJournals.smt2        |   1.089s  |   1.089s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.journalRangeFromHasChecksums.smt2  |   0.475s  |   0.475s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.lemma__writeJournalEntries.smt2  |   5.019s  |   5.019s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.parseEntriesFromHasEntriesI.smt2  |  13.475s  |  13.475s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.parsesFromStuff.smt2  |   0.497s  |   0.497s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.freeze.smt2   |   0.856s  |   0.856s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.packageFrozenJournal.smt2  |   0.683s  |   0.683s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.packageInMemoryJournal.smt2  |   0.736s  |   0.736s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistParsingImpl.i.dfy.Impl__JournalistParsingImpl.__default.ParseJournalRangeOfBytes.smt2  |   0.738s  |   0.738s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.strictlySortedKeySeqToVal.smt2  |  13.973s  |  13.973s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-NodeImpl.i.dfy.Impl__NodeImpl.Node.__ctor.smt2                                 |   2.717s  |   2.717s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-NodeModel.i.dfy.Impl__NodeModel.__default.CutoffNodeAndKeepRightCorrect.smt2   |   1.678s  |   1.678s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-SuccImpl.i.dfy.Impl__SuccImpl.__default.getPath.smt2                           |  14.172s  |  14.172s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-SuccModel.i.dfy.Impl__SuccModel.__default.lemmaGetPathResult.smt2              |   8.201s  |   8.201s  |   0.000s  | 0.0%|
|d_fvbkv-MapSpec-TSJ.i.dfy.Impl__TSJ.__default.CrashStepPreservesInv.smt2                    |   0.339s  |   0.339s  |   0.000s  | 0.0%|
|d_fvbkv-MapSpec-TSJ.i.dfy.Impl__TSJ.__default.Move1to2StepPreservesInv.smt2                 |   0.287s  |   0.287s  |   0.000s  | 0.0%|
|d_fvbkv-MapSpec-TSJMap_Refines_ThreeStateVersionedMap.i.dfy.Impl__TSJMap__Refines__ThreeStateVersionedMap.__default.RefinesReplay.smt2  |   2.733s  |   2.733s  |   0.000s  | 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.Impl__PivotBetreeSpec.__default.CutoffNodeCorrect.smt2  |   0.809s  |   0.809s  |   0.000s  | 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.Impl__PivotBetreeSpecRefinement.__default.InUpperBoundAndNot.smt2  |   0.646s  |   0.646s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-Arrays.i.dfy.Impl__Arrays.__default.replace1with2.smt2                     |   0.327s  |   0.327s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.all__in__set__implies__all1s__uint64.smt2  |   6.965s  |   6.965s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-Multisets.i.dfy.Impl__Multisets.__default.ApplyAdditive.smt2               |   1.287s  |   1.287s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-Multisets.i.dfy.Impl__Multisets.__default.FoldSeqRemove.smt2               |   0.219s  |   0.219s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-sequences.i.dfy.Impl__Sequences.__default.DisjointConcatenation.smt2       |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-total_order.i.dfy.Impl__Integer__Order.__default.FlattenStrictlySorted.smt2  |   0.222s  |   0.222s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-total_order_impl.i.dfy.Impl__Total__Order__Impl.__default.ArrayLargestLtePlus1Linear.smt2  |   0.244s  |   0.244s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.CloneSeq.smt2               |  13.818s  |  13.818s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.ISeqInduction.smt2          |   0.833s  |   0.833s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.ISeq__replace1with2.smt2    |  38.917s  |  38.917s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.__default.PartialFlush.smt2           |  30.934s  |  30.934s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.__default.pkvList2BucketList.smt2     |   6.338s  |   6.338s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketModel.i.dfy.Impl__BucketModel.__default.BucketListItemFlush__eq.smt2  |   0.526s  |   0.526s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketModel.i.dfy.Impl__BucketModel.__default.mergeToChildrenIterCorrect.smt2  |  13.379s  |  13.379s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketModel.i.dfy.Impl__BucketModel.__default.mergeToOneOneChild__eq__BucketList.smt2  |   3.841s  |   3.841s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketModel.i.dfy.Impl__BucketModel.__default.mergeToOneOneChild__eq__topBotAccMerge.smt2  |  11.551s  |  11.551s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.ImageEquiv.smt2       |   0.411s  |   0.411s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.ImageIntersect.smt2   |   0.429s  |   0.429s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.ImageSubset.smt2      |   0.416s  |   0.416s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.SplitBucketImage.smt2  |   0.418s  |   0.418s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.WeightBucketListItemFlush.smt2  |   0.694s  |   0.694s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.WeightBucketListItemFlushInner.smt2  |   6.010s  |   6.010s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.WeightSplitBucketInListLe.smt2  |   0.837s  |   0.837s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.WeightWellMarshalledListPointwiseLe.smt2  |   1.080s  |   1.080s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketsLib.i.dfy.Impl__BucketsLib.__default.BInternalPreWFWellMarshalled.smt2  |   2.391s  |   2.391s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketsLib.i.dfy.Impl__BucketsLib.__default.BInternalWFBucket.smt2      |   4.656s  |   4.656s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketsLib.i.dfy.Impl__BucketsLib.__default.GetJoinBucketListEq.smt2    |   2.061s  |   2.061s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketsLib.i.dfy.Impl__BucketsLib.__default.SortedSeqOfKeyValueHasKey.smt2  |   0.430s  |   0.430s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketsLib.i.dfy.Impl__BucketsLib.__default.SplitBucketOnPivotsAt.smt2  |   2.211s  |   2.211s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketsLib.i.dfy.Impl__BucketsLib.__default.WFProperMergeBucketsInList.smt2  |   0.802s  |   0.802s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketsLib.i.dfy.Impl__BucketsLib.__default.WFProperSplitBucketInList.smt2  |   0.885s  |   0.885s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-KMBPKVOps.i.dfy.Impl__KMBPKVOps.__default.FromPkv.smt2                  |  11.817s  |  11.817s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.CheckWellformed__DynamicPkv.__default.PSAPopFrontWeight.smt2  |   0.686s  |   0.686s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.CheckWellformed__DynamicPkv.__default.PSAPopFrontWeightSuffix.smt2  |   0.646s  |   0.646s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.CheckWellformed__PackedKV.__default.subPkv.smt2          |   1.300s  |   1.300s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.DynamicPkv.Append.smt2                  |   3.632s  |   3.632s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.DynamicPkv.AppendPkv.smt2               |  50.322s  |  50.322s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.__default.IMessagesSlice.smt2           |   1.760s  |   1.760s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.__default.MergeToChildrenIter.smt2      |  43.122s  |  43.122s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.__default.PSAPopFrontWeight.smt2        |   1.225s  |   1.225s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.__default.PSAPopFrontWeightSuffix.smt2  |   1.074s  |   1.074s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.__default.WeightBucketPkv__eq__WeightPkv.smt2  |   1.370s  |   1.370s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.ComputeIsSorted.smt2            |   0.676s  |   0.676s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.Imaps.smt2                      |   1.685s  |   1.685s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.SplitLeft.smt2                  |   1.208s  |   1.208s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.SplitRight.smt2                 |   6.203s  |   6.203s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKVMarshalling.i.dfy.Impl__PackedKVMarshalling.__default.SizeOfVPackedStringArrayIsMessageListWeight.smt2  |   5.474s  |   5.474s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.CheckWellformed__PackedStringArray.__default.psaSeq.smt2  |   0.310s  |   0.310s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.BinarySearchIndexOfFirstKeyGt.smt2  |   0.917s  |   0.917s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.BinarySearchIndexOfFirstKeyGte.smt2  |   0.615s  |   0.615s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.IndexOfFirstKeyGt.smt2  |   0.370s  |   0.370s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.PsaSuffix.smt2  |   0.315s  |   0.315s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.ToSeq.smt2    |   0.366s  |   0.366s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.psaAppendIAppend.smt2  |   0.381s  |   0.381s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.psaCanAppendI.smt2  |   0.611s  |   0.611s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-KMBtree.i.dfy.Impl__KMBtree.__default.SplitChildOfIndex.smt2     |  24.873s  |  24.873s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-LruImpl.i.dfy.Impl__LruImpl.LruImplQueue.Remove.smt2             |   7.132s  |   7.132s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-LruImpl.i.dfy.Impl__LruImpl.__default.lemmaGetRemoveQueueIndex.smt2  |   0.317s  |   0.317s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__TestMutableBtree.__default.SplitChildOfIndex.smt2  |  31.470s  |  31.470s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtreeBulkOperations.i.dfy.Impl__MutableBtreeBulkOperations.__default.CountElements.smt2  |   2.407s  |   2.407s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtreeBulkOperations.i.dfy.Impl__MutableBtreeBulkOperations.__default.ToSeqSubtree.smt2  |  12.064s  |  12.064s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableMapModel.i.dfy.CheckWellformed__MutableMapModel.__default.SimpleIterInc.smt2  |   1.630s  |   1.630s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableMapModel.i.dfy.Impl__MutableMapModel.__default.LemmaReallocIterateResult.smt2  |  12.916s  |  12.916s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallArrayContents.smt2  |   4.055s  |   4.055s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallByteArray.smt2  |   1.163s  |   1.163s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallByteArrayInterior.smt2  |   4.299s  |   4.299s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallTupleContents.smt2  |   3.399s  |   3.399s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__add__mul__div.smt2           |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__div__multiples__vanish__fancy.smt2  |   0.175s  |   0.175s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Math-mul.i.dfy.CheckWellformed__Math____mul__i.__default.mul__recursive.smt2    |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Math-mul.i.dfy.Impl__Math____mul__i.__default.lemma__mul__one__to__one.smt2     |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|d_komodo-verified-allocate_page.gen.dfyCheckWellformed___module.__default.va__lemma__allocate__page.smt2  |   8.499s  |   8.499s  |   0.000s  | 0.0%|
|d_komodo-verified-allocate_page.gen.dfyImpl___module.__default.va__lemma__addrspace__incref.smt2  |  45.677s  |  45.677s  |   0.000s  | 0.0%|
|d_komodo-verified-attest.gen.dfyImpl___module.__default.va__lemma__compute__hmac.smt2       |  37.794s  |  37.794s  |   0.000s  | 0.0%|
|d_komodo-verified-attest_helpers.gen.dfyImpl___module.__default.va__lemma__addrspace__va__for__page__va.smt2  |  16.578s  |  16.578s  |   0.000s  | 0.0%|
|d_komodo-verified-attest_input.gen.dfyCheckWellformed___module.__default.va__lemma__arrange__attestation__input.smt2  |   2.948s  |   2.948s  |   0.000s  | 0.0%|
|d_komodo-verified-attest_input.gen.dfyImpl___module.__default.va__lemma__arrange__attestation__input_split0.smt2  |  25.780s  |  25.780s  |   0.000s  | 0.0%|
|d_komodo-verified-attest_input.gen.dfyImpl___module.__default.va__lemma__arrange__real__measurement__in__memory_split0.smt2  |  13.203s  |  13.203s  |   0.000s  | 0.0%|
|d_komodo-verified-attest_input.gen.dfyImpl___module.__default.va__lemma__arrange__real__measurement__in__memory_split1.smt2  |  22.382s  |  22.382s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.gen.dfyImpl___module.__default.lemma__aligned__sp.smt2              |   4.363s  |   4.363s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.gen.dfyImpl___module.__default.va__lemma__kom__smc__enterresume.smt2  |  50.383s  |  50.383s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.gen.dfyImpl___module.__default.va__lemma__unstack__banked__regs2.smt2  |  35.824s  |  35.824s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.gen.dfyImpl___module.__default.va__lemma__unstack__banked__regs3.smt2  |  37.249s  |  37.249s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.i.dfyCheckWellformed___module.__default.KomExceptionHandlerInvariant.smt2  |   6.467s  |   6.467s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.i.dfyImpl___module.__default.lemma__contentsOfPage__corresponds.smt2  |   2.117s  |   2.117s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.i.dfyImpl___module.__default.lemma__evalMOVSPCLRUC__inner.smt2      |  18.071s  |  18.071s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.i.dfyImpl___module.__default.lemma__onlyDataPagesAreWritable.smt2   |   0.873s  |   0.873s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.i.dfyImpl___module.__default.lemma__userExecutionPreservesPrivState.smt2  |  33.368s  |  33.368s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.i.dfyImpl___module.__default.lemma__userExecutionUpdatesPageDb.smt2  |  24.769s  |  24.769s  |   0.000s  | 0.0%|
|d_komodo-verified-entrybits.i.dfyImpl___module.__default.lemma__sp__bit__helper.smt2        |   0.664s  |   0.664s  |   0.000s  | 0.0%|
|d_komodo-verified-exceptions.i.dfyImpl___module.__default.lemma__PrivInterruptInvariants.smt2  |  39.706s  |  39.706s  |   0.000s  | 0.0%|
|d_komodo-verified-exhandler_state.i.dfyImpl___module.__default.lemma__UserExceptionStateSideEffects.smt2  |  30.156s  |  30.156s  |   0.000s  | 0.0%|
|d_komodo-verified-finalise.gen.dfyImpl___module.__default.lemma__kom__smc__finalise__success__helper1.smt2  |  38.613s  |  38.613s  |   0.000s  | 0.0%|
|d_komodo-verified-finalise.gen.dfyImpl___module.__default.va__lemma__kom__smc__finalise.smt2  |  37.169s  |  37.169s  |   0.000s  | 0.0%|
|d_komodo-verified-init_addrspace.gen.dfyImpl___module.__default.va__lemma__init__addrspace.smt2  |  26.592s  |  26.592s  |   0.000s  | 0.0%|
|d_komodo-verified-init_l2ptable.gen.dfyImpl___module.__default.va__lemma__init__l2ptable__success.smt2  |  34.116s  |  34.116s  |   0.000s  | 0.0%|
|d_komodo-verified-init_l2ptable.gen.dfyImpl___module.__default.va__lemma__zero__l2__page.smt2  |  30.155s  |  30.155s  |   0.000s  | 0.0%|
|d_komodo-verified-kom_utils.gen.dfyCheckWellformed___module.__default.va__lemma__stack__nonvolatiles.smt2  |   4.814s  |   4.814s  |   0.000s  | 0.0%|
|d_komodo-verified-kom_utils.gen.dfyImpl___module.__default.va__lemma__load__page__type.smt2  |   6.353s  |   6.353s  |   0.000s  | 0.0%|
|d_komodo-verified-kom_utils.gen.dfyImpl___module.__default.va__lemma__unstack__lr.smt2      |   1.861s  |   1.861s  |   0.000s  | 0.0%|
|d_komodo-verified-kom_utils.gen.dfyImpl___module.__default.va__lemma__unstack__nonvolatiles.smt2  |  18.297s  |  18.297s  |   0.000s  | 0.0%|
|d_komodo-verified-kom_utils.gen.dfyImpl___module.__default.va__lemma__unstack__nonvolatiles__except__lr.smt2  |  17.679s  |  17.679s  |   0.000s  | 0.0%|
|d_komodo-verified-kom_utils.gen.dfyImpl___module.__default.va__lemma__update__pagedb__entry.smt2  |  11.509s  |  11.509s  |   0.000s  | 0.0%|
|d_komodo-verified-map_common.gen.dfyImpl___module.__default.va__lemma__insecure__phys__to__virt.smt2  |  43.380s  |  43.380s  |   0.000s  | 0.0%|
|d_komodo-verified-map_common.gen.dfyImpl___module.__default.va__lemma__is__valid__mapping__target.smt2  |  24.720s  |  24.720s  |   0.000s  | 0.0%|
|d_komodo-verified-map_common.gen.dfyImpl___module.__default.va__lemma__is__valid__mapping__target_k__finish.smt2  |  17.987s  |  17.987s  |   0.000s  | 0.0%|
|d_komodo-verified-map_utils.gen.dfyCheckWellformed___module.__default.va__lemma__kom__smc__map__measure__hash.smt2  |  20.802s  |  20.802s  |   0.000s  | 0.0%|
|d_komodo-verified-map_utils.gen.dfyCheckWellformed___module.__default.va__lemma__kom__smc__map__measure__sha.smt2  |  25.152s  |  25.152s  |   0.000s  | 0.0%|
|d_komodo-verified-map_utils.gen.dfyImpl___module.__default.va__lemma__fetch__l1pte.smt2     |  11.623s  |  11.623s  |   0.000s  | 0.0%|
|d_komodo-verified-mapping.i.dfyImpl___module.__default.lemma__installL1PTEInPageDb__dataPageRefs.smt2  |   1.661s  |   1.661s  |   0.000s  | 0.0%|
|d_komodo-verified-pagedb.i.dfyImpl___module.__default.extractPageDbToAbstract.smt2          |   1.837s  |   1.837s  |   0.000s  | 0.0%|
|d_komodo-verified-pagedb.i.dfyImpl___module.__default.extractPageDbToAbstractOne.smt2       |   1.434s  |   1.434s  |   0.000s  | 0.0%|
|d_komodo-verified-ptables.i.dfyImpl___module.__default.lemma__WritablePages.smt2            |   1.768s  |   1.768s  |   0.000s  | 0.0%|
|d_komodo-verified-ptables.i.dfyImpl___module.__default.lemma__l2tablesmatch.smt2            |   4.541s  |   4.541s  |   0.000s  | 0.0%|
|d_komodo-verified-ptables.i.dfyImpl___module.__default.lemma__ptablesmatch.smt2             |   6.687s  |   6.687s  |   0.000s  | 0.0%|
|d_komodo-verified-ptables.i.dfyImpl___module.__default.lemma__ptablesmatch_split0.smt2      |   3.251s  |   3.251s  |   0.000s  | 0.0%|
|d_komodo-verified-ptebits.i.dfyImpl___module.__default.lemma__nonexec__mapping.smt2         |   3.809s  |   3.809s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__AllPages.smt2   |   2.778s  |   2.778s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__enter__loweq__pdb__not__atkr.smt2  |  17.960s  |  17.960s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__exceptionHandled__atkr.smt2  |   6.314s  |   6.314s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__svcHandled__loweq__pdb.smt2  |  53.946s  |  53.946s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__updateUserPages__conf__not__atkr.smt2  |  32.694s  |  32.694s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__validEnclaveStepPrime__conf__not__atkr__retnondet.smt2  |  40.699s  |  40.699s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-integ_ni_entry.i.dfyImpl___module.__default.lemma__enter__enc__obs__enter.smt2  |  27.221s  |  27.221s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-integ_ni_entry.i.dfyImpl___module.__default.lemma__enter__loweq__pdb__not__obs.smt2  |  19.395s  |  19.395s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-hmac.gen.dfyImpl___module.__default.va__lemma__hmac__inner__prep__hash.smt2  |  28.369s  |  28.369s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-memory-helpers.i.dfyImpl___module.__default.lemma__AddrMemContentsSeq__adds.smt2  |   3.296s  |   3.296s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-sha256-block-data-order.gen.dfyImpl___module.__default.va__refined__sha256__block__data__order_split0.smt2  |  39.157s  |  39.157s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-sha256-one-block.gen.dfyImpl___module.__default.va__abstract__update__Hs.smt2  |  47.440s  |  47.440s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-sha256.i.dfyImpl___module.__default.SHA__padding__words2bytes.smt2    |   9.894s  |   9.894s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-sha256.i.dfyImpl___module.__default.lemma__InputHelper.smt2           |   0.411s  |   0.411s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-sha256.s.dfyCheckWellformed___module.__default.K__SHA256.smt2         |   3.008s  |   3.008s  |   0.000s  | 0.0%|
|d_komodo-verified-smcapi.i.dfyImpl___module.__default.kom__smc__map__measure__helper1.smt2  |  22.088s  |  22.088s  |   0.000s  | 0.0%|
|d_komodo-verified-smcapi.i.dfyImpl___module.__default.lemma__sha256__concat.smt2            |   1.066s  |   1.066s  |   0.000s  | 0.0%|
|d_komodo-verified-stop.gen.dfyImpl___module.__default.va__lemma__kom__smc__stop.smt2        |  47.099s  |  47.099s  |   0.000s  | 0.0%|
|d_komodo-verified-svc_handlers.gen.dfyCheckWellformed___module.__default.va__lemma__svc__returning__verify__step1.smt2  |  10.784s  |  10.784s  |   0.000s  | 0.0%|
|d_komodo-verified-svc_handlers.gen.dfyImpl___module.__default.lemma__svc__returning__verify__step0__helper.smt2  |  46.099s  |  46.099s  |   0.000s  | 0.0%|
|d_komodo-verified-svc_handlers.gen.dfyImpl___module.__default.lemma__svc__returning__verify__step1__helper.smt2  |  35.860s  |  35.860s  |   0.000s  | 0.0%|
|d_komodo-verified-svc_handlers.gen.dfyImpl___module.__default.va__lemma__svc__map__data__success.smt2  |  34.478s  |  34.478s  |   0.000s  | 0.0%|
|d_komodo-verified-svc_handlers.gen.dfyImpl___module.__default.va__lemma__svc__map__data__zeropage.smt2  |  38.405s  |  38.405s  |   0.000s  | 0.0%|
|d_komodo-verified-svc_handlers.gen.dfyImpl___module.__default.va__lemma__svc__returning__default.smt2  |  15.012s  |  15.012s  |   0.000s  | 0.0%|
|d_komodo-verified-verify.gen.dfyImpl___module.__default.va__lemma__compare__memory__to__regs.smt2  |  20.005s  |  20.005s  |   0.000s  | 0.0%|
|d_komodo-verified-verify_input.gen.dfyCheckWellformed___module.__default.lemma__grab__measurement.smt2  |   2.722s  |   2.722s  |   0.000s  | 0.0%|
|d_komodo-verified-verify_input.gen.dfyCheckWellformed___module.__default.lemma__grab__user__words.smt2  |   2.734s  |   2.734s  |   0.000s  | 0.0%|
|d_komodo-verified-verify_input.gen.dfyImpl___module.__default.lemma__grab__measurement.smt2  |  36.038s  |  36.038s  |   0.000s  | 0.0%|
|d_komodo-verified-verify_input.gen.dfyImpl___module.__default.lemma__grab__user__words.smt2  |  27.623s  |  27.623s  |   0.000s  | 0.0%|
|d_komodo-verified-verify_input.gen.dfyImpl___module.__default.va__lemma__arrange__user__words__in__memory.smt2  |   8.554s  |   8.554s  |   0.000s  | 0.0%|
|d_komodo-verified-verify_input.gen.dfyImpl___module.__default.va__lemma__arrange__user__words__in__memory_split0.smt2  |  12.862s  |  12.862s  |   0.000s  | 0.0%|
|d_komodo-verified-verify_input.gen.dfyImpl___module.__default.va__lemma__arrange__verification__input_split0.smt2  |   9.956s  |   9.956s  |   0.000s  | 0.0%|
|d_komodo-verified-verify_input.gen.dfyImpl___module.__default.va__lemma__arrange__verify__measurement__in__memory.smt2  |   6.958s  |   6.958s  |   0.000s  | 0.0%|
|d_komodo-verified-verify_input.gen.dfyImpl___module.__default.va__lemma__arrange__verify__measurement__in__memory_split0.smt2  |   9.454s  |   9.454s  |   0.000s  | 0.0%|
|d_lvbkv-Betree-AsyncBetree.i.dfy.Impl__AsyncBetree.__default.QueryAdvanceChangesLookup.smt2  |   3.655s  |   3.655s  |   0.000s  | 0.0%|
|d_lvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.GrowStepPreservesInvariant.smt2    |  46.719s  |  46.719s  |   0.000s  | 0.0%|
|d_lvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.InitImpliesInv.smt2                |   0.965s  |   0.965s  |   0.000s  | 0.0%|
|d_lvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectResultingGraphAfterAllocs.smt2  |   2.538s  |   2.538s  |   0.000s  | 0.0%|
|d_lvbkv-BlockCacheSystem-BetreeCache.i.dfy.Impl__BetreeCache.__default.BetreeMoveStepPreservesInv.smt2  |  38.289s  |  38.289s  |   0.000s  | 0.0%|
|d_lvbkv-BlockCacheSystem-BetreeSystem.i.dfy.Impl__BetreeSystem.__default.BlockCacheMoveStepPreservesInv.smt2  |  15.668s  |  15.668s  |   0.000s  | 0.0%|
|d_lvbkv-BlockCacheSystem-BetreeSystem_Refines_StatesViewPivotBetree.i.dfy.Impl__BetreeSystem__Refines__StatesViewPivotBetree.__default.BetreeMoveStepRefines.smt2  |  38.923s  |  38.923s  |   0.000s  | 0.0%|
|d_lvbkv-BlockCacheSystem-BlockCache.i.dfy.Impl__BlockCache.__default.DirtyStepPreservesInv.smt2  |   4.827s  |   4.827s  |   0.000s  | 0.0%|
|d_lvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.DiskInternalStepPreservesInv.smt2  |   2.230s  |   2.230s  |   0.000s  | 0.0%|
|d_lvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBytesSplit.smt2  |   0.578s  |   0.578s  |   0.000s  | 0.0%|
|d_lvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeEqJournalBlocks.smt2  |   0.634s  |   0.634s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-GrowModel.i.dfy.Impl__GrowModel.__default.growCorrect.smt2                     |  20.984s  |  20.984s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.FindIndirectionTableLocationAndRequestWrite.smt2  |   5.083s  |   5.083s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.PageInNodeResp.smt2                        |  38.444s  |  38.444s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-IndirectionTable.i.dfy.Impl__IndirectionTable.IndirectionTable.IndirectionTableToVal.smt2  |  48.267s  |  48.267s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-JournalistImpl.i.dfy.Impl__JournalistImpl.Journalist.packageFrozenJournal.smt2  |   0.592s  |   0.592s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-JournalistImpl.i.dfy.Impl__JournalistImpl.Journalist.reallocJournalEntries.smt2  |   0.427s  |   0.427s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.journalRangeFromHasChecksums.smt2  |   0.404s  |   0.404s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.lemma__writeJournalEntries.smt2  |  14.247s  |  14.247s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.parseEntriesFromHasEntriesI.smt2  |   1.589s  |   1.589s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.writeOntoPreservesSlice.smt2  |   0.336s  |   0.336s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-JournalistParsingImpl.i.dfy.Impl__JournalistParsingImpl.__default.ParseJournalRangeOfBytes.smt2  |   1.274s  |   1.274s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.KeyValSeqToPivots.smt2   |   3.641s  |   3.641s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.bucketsToVal.smt2        |  13.160s  |  13.160s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-MarshallingModel.i.dfy.Impl__MarshallingModel.__default.WeightBucketListLteSize.smt2  |   3.198s  |   3.198s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-NodeImpl.i.dfy.Impl__NodeImpl.Node.BucketsWellMarshalled.smt2                  |   1.249s  |   1.249s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-NodeImpl.i.dfy.Impl__NodeImpl.Node.CutoffNodeAndKeepLeft.smt2                  |   2.241s  |   2.241s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-QueryModel.i.dfy.Impl__QueryModel.__default.AugmentLookup.smt2                 |   3.323s  |   3.323s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-SplitModel.i.dfy.Impl__SplitModel.__default.lemmaChildrenConditionsCutoffNode.smt2  |   2.033s  |   2.033s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-SuccImpl.i.dfy.Impl__SuccImpl.__default.getPathInternal.smt2                   |  10.822s  |  10.822s  |   0.000s  | 0.0%|
|d_lvbkv-MapSpec-TSJ.i.dfy.Impl__TSJ.__default.CrashStepPreservesInv.smt2                    |   0.320s  |   0.320s  |   0.000s  | 0.0%|
|d_lvbkv-MapSpec-TSJ.i.dfy.Impl__TSJ.__default.Move1to2StepPreservesInv.smt2                 |   0.300s  |   0.300s  |   0.000s  | 0.0%|
|d_lvbkv-PivotBetree-PivotBetree.i.dfy.Impl__PivotBetree.__default.GCStepRefines.smt2        |   4.546s  |   4.546s  |   0.000s  | 0.0%|
|d_lvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.Impl__PivotBetreeSpecRefinement.__default.InUpperBoundAndNot.smt2  |   0.732s  |   0.732s  |   0.000s  | 0.0%|
|d_lvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.Impl__PivotBetreeSpecRefinement.__default.MergeChildrenConsistent.smt2  |  23.666s  |  23.666s  |   0.000s  | 0.0%|
|d_lvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.Impl__PivotBetreeSpecRefinement.__default.SplitMergeBuffersChildrenEq.smt2  |   2.225s  |   2.225s  |   0.000s  | 0.0%|
|d_lvbkv-PivotBetree-PivotBetreeSpecWFNodes.i.dfy.Impl__PivotBetreeSpecWFNodes.__default.SplitMaps.smt2  |  34.964s  |  34.964s  |   0.000s  | 0.0%|
|d_lvbkv-PivotBetree-TSJPivotBetree.i.dfy.Impl__TSJPivotBetree.__default.Move3StepPreservesInv.smt2  |   1.175s  |   1.175s  |   0.000s  | 0.0%|
|d_lvbkv-Versions-CompositeView_Refines_TSJMap.i.dfy.Impl__CompositeView__Refines__TSJMap.__default.CrashRefines.smt2  |   1.029s  |   1.029s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-Arrays.i.dfy.Impl__Arrays.__default.replace1with2.smt2                     |   3.089s  |   3.089s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.bit__or__is__union__uint64.smt2  |   0.613s  |   0.613s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-Sequences.i.dfy.Impl__Sequences.__default.DisjointConcatenation.smt2       |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-mathematics.i.dfy.Impl__Mathematics.__default.DivCeilLT.smt2               |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-mathematics.i.dfy.Impl__Mathematics.__default.PosMulPreservesOrder.smt2    |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-total_order.i.dfy.Impl__Total__Preorder.__default.ExistsBiggestInSet.smt2  |   0.187s  |   0.187s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-total_order_impl.i.dfy.Impl__Total__Order__Impl.__default.ArrayLargestLtPlus1.smt2  |   0.277s  |   0.277s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-total_order_impl.i.dfy.Impl__Total__Order__Impl.__default.ArrayLargestLtePlus1.smt2  |   0.277s  |   0.277s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.CloneSeq.smt2               |   1.872s  |   1.872s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.GetLastKey.smt2             |   0.968s  |   0.968s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.ISeq__replace1with2.smt2    |  19.277s  |  19.277s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.SplitOneInList.smt2         |   8.331s  |   8.331s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.WeightBucketIs.smt2         |   0.804s  |   0.804s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.WeightKeyListIs.smt2        |   1.328s  |   1.328s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.computeWeightOfSeq.smt2     |   1.573s  |   1.573s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.WeightSplitBucketAdditive.smt2  |   0.471s  |   0.471s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-LKMBPKVOps.i.dfy.Impl__LKMBPKVOps.__default.FromPkv.smt2                |   8.937s  |   8.937s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-LKMBPKVOps.i.dfy.Impl__LKMBPKVOps.__default.IsKeyMessageTreeInheritance.smt2  |  45.266s  |  45.266s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.CheckWellformed__PackedKV.__default.AppendEncodedMessage.smt2  |   0.665s  |   0.665s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.CheckWellformed__PackedKV.__default.psaSeq__Messages.smt2  |   0.601s  |   0.601s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.CheckWellformed__PackedKV.__default.subPkv.smt2          |   0.780s  |   0.780s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.__default.WeightBucketPkv__eq__WeightPkv.smt2  |   4.375s  |   4.375s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.__default.computePivotIndexes.smt2      |   0.691s  |   0.691s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.ComputeValidStringLens.smt2     |   0.583s  |   0.583s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedKVMarshalling.i.dfy.Impl__PackedKVMarshalling.__default.ComputeWF.smt2  |   0.685s  |   0.685s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedKVMarshalling.i.dfy.Impl__PackedKVMarshalling.__default.SizeOfVPackedStringArrayIsKeyListWeight.smt2  |  17.379s  |  17.379s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedKVMarshalling.i.dfy.Impl__PackedKVMarshalling.__default.SizeOfVPackedStringArrayIsMessageListWeight.smt2  |  10.051s  |  10.051s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedStringArray.i.dfy.CheckWellformed__PackedStringArray.__default.psaSeq.smt2  |   0.365s  |   0.365s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.DynamicPsa.appendSeq.smt2  |  23.165s  |  23.165s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.ToSeq.smt2    |   0.407s  |   0.407s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.UniqueRepr.smt2  |   0.424s  |   0.424s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.psaAppendIAppend.smt2  |   0.421s  |   0.421s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.psaAppendSeqAdditive.smt2  |   0.503s  |   0.503s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Checksums-CRC32C_Lemmas.i.dfy.Impl__CRC32C__Lemmas.__default.four__slices.smt2  |   0.241s  |   0.241s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Checksums-CRC32C_Lut.i.dfy.CheckWellformed__CRC32C__Lut.__default.combine.smt2  |   2.045s  |   2.045s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Checksums-CRC32C_Lut.i.dfy.Impl__CRC32C__Lut.__default.reverse__p.smt2          |   0.560s  |   0.560s  |   0.000s  | 0.0%|
|d_lvbkv-lib-DataStructures-KMBtree.i.dfy.Impl__KMBtreeModel.__default.IndexesNonempty.smt2  |   0.408s  |   0.408s  |   0.000s  | 0.0%|
|d_lvbkv-lib-DataStructures-LinearMutableMap.i.dfy.Impl__LinearMutableMap.__default.Probe.smt2  |  35.866s  |  35.866s  |   0.000s  | 0.0%|
|d_lvbkv-lib-DataStructures-MutableMapModel.i.dfy.Impl__MutableMapModel.__default.LemmaReallocIterateResult.smt2  |  22.877s  |  22.877s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallArrayContents.smt2  |   2.801s  |   2.801s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallTupleContents.smt2  |   1.397s  |   1.397s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint32Array.smt2  |   0.724s  |   0.724s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint64Array.smt2  |   1.256s  |   1.256s  |   0.000s  | 0.0%|
</details>
