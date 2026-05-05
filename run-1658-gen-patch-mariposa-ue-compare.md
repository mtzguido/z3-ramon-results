Comparing data and data


# SUMMARY
- LHS tests = 277
- RHS tests = 277
- LHS success = 275  (99.27797833935018%)
- RHS success = 275  (99.27797833935018%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: gen-patch-mariposa-ue
Runner: rise-runner-1
Z3 repo: CanCebeci/z3
Z3 commit: aec453eb9bad24f44f4f6101b46004389bd16bb0
Z3 branch: master
Z3 options: "%OPTIONS2%"
Z3 inputs: inputs/mariposa/unstable_ext
Z3 commit message: Enforce stickiness of max-generation

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: gen-patch-mariposa-ue
Runner: rise-runner-1
Z3 repo: CanCebeci/z3
Z3 commit: aec453eb9bad24f44f4f6101b46004389bd16bb0
Z3 branch: master
Z3 options: "%OPTIONS2%"
Z3 inputs: inputs/mariposa/unstable_ext
Z3 commit message: Enforce stickiness of max-generation

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.InitImpliesInv.smt2                |   0.513s  |   0.513s  |   0.000s  | 0.0%|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectPreservesLookups.smt2      |   8.787s  |   8.787s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-JournalInterval.i.dfy.Impl__JournalIntervals.__default.Disk__Journal__append.smt2  |   1.088s  |   1.088s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBlockOfJournalRange.smt2  |   0.346s  |   0.346s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBytesSplit.smt2  |   0.381s  |   0.381s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeEqJournalBlocks.smt2  |   3.167s  |   3.167s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeOfByteSeqGetI.smt2  |   0.788s  |   0.788s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-Marshalling.i.dfy.Impl__Marshalling.__default.pivotTableWeightUpperBound.smt2  |   4.764s  |   4.764s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeeping.smt2    |   6.737s  |   6.737s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeepingNoSuccsUpdate.smt2  |   6.161s  |   6.161s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketGeneratorModel.i.dfy.Impl__BucketGeneratorModel.__default.GenFromBucketStackWithLowerBoundYieldsComposeSeq.smt2  |   2.159s  |   2.159s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.GetSuccessorInBucketStackResult.smt2  |   1.546s  |   1.546s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.ProcessGeneratorResult.smt2  |  17.247s  |  17.247s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterCommitImpl.i.dfy.Impl__CommitterCommitImpl.__default.WriteOutJournal.smt2  |  20.773s  |  20.773s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.CheckWellformed__CommitterCommitModel.__default.WriteOutJournal.smt2  |   1.951s  |   1.951s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.Impl__CommitterCommitModel.__default.WriteOutJournalCorrect.smt2  |   3.225s  |   3.225s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-DeallocImpl.i.dfy.Impl__DeallocImpl.__default.Dealloc.smt2                     |  47.368s  |  47.368s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-GrowImpl.i.dfy.Impl__GrowImpl.__default.grow.smt2                              |  33.478s  |  33.478s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.PageInIndirectionTableResp.smt2            |  56.749s  |  56.749s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.FindIndirectionTableLocationAndRequestWriteCorrect.smt2  |   3.551s  |   3.551s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.InitImpliesInv.smt2                |   0.513s  |   0.513s  |   0.000s  | 0.0%|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectPreservesLookups.smt2      |   8.787s  |   8.787s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-JournalInterval.i.dfy.Impl__JournalIntervals.__default.Disk__Journal__append.smt2  |   1.088s  |   1.088s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBlockOfJournalRange.smt2  |   0.346s  |   0.346s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBytesSplit.smt2  |   0.381s  |   0.381s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeEqJournalBlocks.smt2  |   3.167s  |   3.167s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeOfByteSeqGetI.smt2  |   0.788s  |   0.788s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-Marshalling.i.dfy.Impl__Marshalling.__default.pivotTableWeightUpperBound.smt2  |   4.764s  |   4.764s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeeping.smt2    |   6.737s  |   6.737s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeepingNoSuccsUpdate.smt2  |   6.161s  |   6.161s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketGeneratorModel.i.dfy.Impl__BucketGeneratorModel.__default.GenFromBucketStackWithLowerBoundYieldsComposeSeq.smt2  |   2.159s  |   2.159s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.GetSuccessorInBucketStackResult.smt2  |   1.546s  |   1.546s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.ProcessGeneratorResult.smt2  |  17.247s  |  17.247s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterCommitImpl.i.dfy.Impl__CommitterCommitImpl.__default.WriteOutJournal.smt2  |  20.773s  |  20.773s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.CheckWellformed__CommitterCommitModel.__default.WriteOutJournal.smt2  |   1.951s  |   1.951s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.Impl__CommitterCommitModel.__default.WriteOutJournalCorrect.smt2  |   3.225s  |   3.225s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-DeallocImpl.i.dfy.Impl__DeallocImpl.__default.Dealloc.smt2                     |  47.368s  |  47.368s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-GrowImpl.i.dfy.Impl__GrowImpl.__default.grow.smt2                              |  33.478s  |  33.478s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.PageInIndirectionTableResp.smt2            |  56.749s  |  56.749s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.FindIndirectionTableLocationAndRequestWriteCorrect.smt2  |   3.551s  |   3.551s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.InitImpliesInv.smt2                |   0.513s  |   0.513s  |   0.000s  | 0.0%|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectPreservesLookups.smt2      |   8.787s  |   8.787s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-JournalInterval.i.dfy.Impl__JournalIntervals.__default.Disk__Journal__append.smt2  |   1.088s  |   1.088s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBlockOfJournalRange.smt2  |   0.346s  |   0.346s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBytesSplit.smt2  |   0.381s  |   0.381s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeEqJournalBlocks.smt2  |   3.167s  |   3.167s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeOfByteSeqGetI.smt2  |   0.788s  |   0.788s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-Marshalling.i.dfy.Impl__Marshalling.__default.pivotTableWeightUpperBound.smt2  |   4.764s  |   4.764s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeeping.smt2    |   6.737s  |   6.737s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeepingNoSuccsUpdate.smt2  |   6.161s  |   6.161s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketGeneratorModel.i.dfy.Impl__BucketGeneratorModel.__default.GenFromBucketStackWithLowerBoundYieldsComposeSeq.smt2  |   2.159s  |   2.159s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.GetSuccessorInBucketStackResult.smt2  |   1.546s  |   1.546s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.ProcessGeneratorResult.smt2  |  17.247s  |  17.247s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterCommitImpl.i.dfy.Impl__CommitterCommitImpl.__default.WriteOutJournal.smt2  |  20.773s  |  20.773s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.CheckWellformed__CommitterCommitModel.__default.WriteOutJournal.smt2  |   1.951s  |   1.951s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.Impl__CommitterCommitModel.__default.WriteOutJournalCorrect.smt2  |   3.225s  |   3.225s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-DeallocImpl.i.dfy.Impl__DeallocImpl.__default.Dealloc.smt2                     |  47.368s  |  47.368s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-GrowImpl.i.dfy.Impl__GrowImpl.__default.grow.smt2                              |  33.478s  |  33.478s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.PageInIndirectionTableResp.smt2            |  56.749s  |  56.749s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.FindIndirectionTableLocationAndRequestWriteCorrect.smt2  |   3.551s  |   3.551s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.InitImpliesInv.smt2                |   0.513s  |   0.513s  |   0.000s  | 0.0%|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectPreservesLookups.smt2      |   8.787s  |   8.787s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-JournalInterval.i.dfy.Impl__JournalIntervals.__default.Disk__Journal__append.smt2  |   1.088s  |   1.088s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBlockOfJournalRange.smt2  |   0.346s  |   0.346s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBytesSplit.smt2  |   0.381s  |   0.381s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeEqJournalBlocks.smt2  |   3.167s  |   3.167s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeOfByteSeqGetI.smt2  |   0.788s  |   0.788s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-Marshalling.i.dfy.Impl__Marshalling.__default.pivotTableWeightUpperBound.smt2  |   4.764s  |   4.764s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeeping.smt2    |   6.737s  |   6.737s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeepingNoSuccsUpdate.smt2  |   6.161s  |   6.161s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketGeneratorModel.i.dfy.Impl__BucketGeneratorModel.__default.GenFromBucketStackWithLowerBoundYieldsComposeSeq.smt2  |   2.159s  |   2.159s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.GetSuccessorInBucketStackResult.smt2  |   1.546s  |   1.546s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.ProcessGeneratorResult.smt2  |  17.247s  |  17.247s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterCommitImpl.i.dfy.Impl__CommitterCommitImpl.__default.WriteOutJournal.smt2  |  20.773s  |  20.773s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.CheckWellformed__CommitterCommitModel.__default.WriteOutJournal.smt2  |   1.951s  |   1.951s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.Impl__CommitterCommitModel.__default.WriteOutJournalCorrect.smt2  |   3.225s  |   3.225s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-DeallocImpl.i.dfy.Impl__DeallocImpl.__default.Dealloc.smt2                     |  47.368s  |  47.368s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-GrowImpl.i.dfy.Impl__GrowImpl.__default.grow.smt2                              |  33.478s  |  33.478s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.PageInIndirectionTableResp.smt2            |  56.749s  |  56.749s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.FindIndirectionTableLocationAndRequestWriteCorrect.smt2  |   3.551s  |   3.551s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|s_komodo-1518.6.smt2                                                                       |  81.141s |16.224GiB|
|s_komodo-1557.3.smt2                                                                       |  80.036s |277.0MiB|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.PageInIndirectionTableResp.smt2           |  56.749s |183.0MiB|
|d_komodo-verified-attest.gen.dfyImpl___module.__default.va__lemma__compute__hmac_split0.smt2 |  52.495s |402.0MiB|
|d_komodo-verified-stop.gen.dfyImpl___module.__default.va__lemma__kom__smc__stop.smt2       |  49.233s |275.0MiB|
|d_lvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.GrowStepPreservesInvariant.smt2   |  49.017s |131.0MiB|
|d_komodo-verified-allocate_page.gen.dfyImpl___module.__default.va__lemma__addrspace__incref.smt2 |  48.733s |204.0MiB|
|d_komodo-verified-map_common.gen.dfyImpl___module.__default.va__lemma__insecure__phys__to__virt.smt2 |  48.670s |189.0MiB|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__svcHandled__loweq__pdb.smt2 |  48.357s |335.0MiB|
|d_komodo-verified-sha-sha256-one-block.gen.dfyImpl___module.__default.va__abstract__update__Hs.smt2 |  47.751s |138.0MiB|
|d_lvbkv-Impl-IndirectionTable.i.dfy.Impl__IndirectionTable.IndirectionTable.IndirectionTableToVal.smt2 |  47.377s |192.0MiB|
|d_fvbkv-Impl-DeallocImpl.i.dfy.Impl__DeallocImpl.__default.Dealloc.smt2                    |  47.368s |184.0MiB|
|d_komodo-verified-svc_handlers.gen.dfyImpl___module.__default.lemma__svc__returning__verify__step0__helper.smt2 |  47.367s |191.0MiB|
|d_komodo-verified-attest.gen.dfyImpl___module.__default.va__lemma__compute__hmac.smt2      |  44.253s |222.0MiB|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.__default.MergeToChildrenIter.smt2     |  42.737s |194.0MiB|
|d_lvbkv-BlockCacheSystem-BetreeSystem_Refines_StatesViewPivotBetree.i.dfy.Impl__BetreeSystem__Refines__StatesViewPivotBetree.__default.BetreeMoveStepRefines.smt2 |  41.913s |348.0MiB|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__validEnclaveStepPrime__conf__not__atkr__retnondet.smt2 |  41.595s |215.0MiB|
|d_komodo-verified-finalise.gen.dfyImpl___module.__default.lemma__kom__smc__finalise__success__helper1.smt2 |  40.616s |220.0MiB|
|d_komodo-verified-svc_handlers.gen.dfyImpl___module.__default.va__lemma__svc__map__data__zeropage.smt2 |  40.589s |354.0MiB|
|d_lvbkv-PivotBetree-PivotBetreeSpecWFNodes.i.dfy.Impl__PivotBetreeSpecWFNodes.__default.SplitMaps.smt2 |  40.349s |929.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|s_komodo-1518.6.smt2                                                                       |  81.141s |16.224GiB|
|s_komodo-1557.3.smt2                                                                       |  80.036s |277.0MiB|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.PageInIndirectionTableResp.smt2           |  56.749s |183.0MiB|
|d_komodo-verified-attest.gen.dfyImpl___module.__default.va__lemma__compute__hmac_split0.smt2 |  52.495s |402.0MiB|
|d_komodo-verified-stop.gen.dfyImpl___module.__default.va__lemma__kom__smc__stop.smt2       |  49.233s |275.0MiB|
|d_lvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.GrowStepPreservesInvariant.smt2   |  49.017s |131.0MiB|
|d_komodo-verified-allocate_page.gen.dfyImpl___module.__default.va__lemma__addrspace__incref.smt2 |  48.733s |204.0MiB|
|d_komodo-verified-map_common.gen.dfyImpl___module.__default.va__lemma__insecure__phys__to__virt.smt2 |  48.670s |189.0MiB|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__svcHandled__loweq__pdb.smt2 |  48.357s |335.0MiB|
|d_komodo-verified-sha-sha256-one-block.gen.dfyImpl___module.__default.va__abstract__update__Hs.smt2 |  47.751s |138.0MiB|
|d_lvbkv-Impl-IndirectionTable.i.dfy.Impl__IndirectionTable.IndirectionTable.IndirectionTableToVal.smt2 |  47.377s |192.0MiB|
|d_fvbkv-Impl-DeallocImpl.i.dfy.Impl__DeallocImpl.__default.Dealloc.smt2                    |  47.368s |184.0MiB|
|d_komodo-verified-svc_handlers.gen.dfyImpl___module.__default.lemma__svc__returning__verify__step0__helper.smt2 |  47.367s |191.0MiB|
|d_komodo-verified-attest.gen.dfyImpl___module.__default.va__lemma__compute__hmac.smt2      |  44.253s |222.0MiB|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.__default.MergeToChildrenIter.smt2     |  42.737s |194.0MiB|
|d_lvbkv-BlockCacheSystem-BetreeSystem_Refines_StatesViewPivotBetree.i.dfy.Impl__BetreeSystem__Refines__StatesViewPivotBetree.__default.BetreeMoveStepRefines.smt2 |  41.913s |348.0MiB|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__validEnclaveStepPrime__conf__not__atkr__retnondet.smt2 |  41.595s |215.0MiB|
|d_komodo-verified-finalise.gen.dfyImpl___module.__default.lemma__kom__smc__finalise__success__helper1.smt2 |  40.616s |220.0MiB|
|d_komodo-verified-svc_handlers.gen.dfyImpl___module.__default.va__lemma__svc__map__data__zeropage.smt2 |  40.589s |354.0MiB|
|d_lvbkv-PivotBetree-PivotBetreeSpecWFNodes.i.dfy.Impl__PivotBetreeSpecWFNodes.__default.SplitMaps.smt2 |  40.349s |929.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.InitImpliesInv.smt2                |50.084MiB|50.084MiB|0B| 0.0%|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectPreservesLookups.smt2      |94.652MiB|94.652MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-JournalInterval.i.dfy.Impl__JournalIntervals.__default.Disk__Journal__append.smt2  |34.672MiB|34.672MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBlockOfJournalRange.smt2  |30.28MiB|30.28MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBytesSplit.smt2  |31.048MiB|31.048MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeEqJournalBlocks.smt2  |56.396MiB|56.396MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeOfByteSeqGetI.smt2  |35.168MiB|35.168MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-Marshalling.i.dfy.Impl__Marshalling.__default.pivotTableWeightUpperBound.smt2  |133.0MiB|133.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeeping.smt2    |168.0MiB|168.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeepingNoSuccsUpdate.smt2  |168.0MiB|168.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketGeneratorModel.i.dfy.Impl__BucketGeneratorModel.__default.GenFromBucketStackWithLowerBoundYieldsComposeSeq.smt2  |58.452MiB|58.452MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.GetSuccessorInBucketStackResult.smt2  |54.944MiB|54.944MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.ProcessGeneratorResult.smt2  |109.0MiB|109.0MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterCommitImpl.i.dfy.Impl__CommitterCommitImpl.__default.WriteOutJournal.smt2  |182.0MiB|182.0MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.CheckWellformed__CommitterCommitModel.__default.WriteOutJournal.smt2  |95.808MiB|95.808MiB|0B| 0.0%|
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
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.InitImpliesInv.smt2                |50.084MiB|50.084MiB|0B| 0.0%|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectPreservesLookups.smt2      |94.652MiB|94.652MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-JournalInterval.i.dfy.Impl__JournalIntervals.__default.Disk__Journal__append.smt2  |34.672MiB|34.672MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBlockOfJournalRange.smt2  |30.28MiB|30.28MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBytesSplit.smt2  |31.048MiB|31.048MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeEqJournalBlocks.smt2  |56.396MiB|56.396MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeOfByteSeqGetI.smt2  |35.168MiB|35.168MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-Marshalling.i.dfy.Impl__Marshalling.__default.pivotTableWeightUpperBound.smt2  |133.0MiB|133.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeeping.smt2    |168.0MiB|168.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeepingNoSuccsUpdate.smt2  |168.0MiB|168.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketGeneratorModel.i.dfy.Impl__BucketGeneratorModel.__default.GenFromBucketStackWithLowerBoundYieldsComposeSeq.smt2  |58.452MiB|58.452MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.GetSuccessorInBucketStackResult.smt2  |54.944MiB|54.944MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.ProcessGeneratorResult.smt2  |109.0MiB|109.0MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterCommitImpl.i.dfy.Impl__CommitterCommitImpl.__default.WriteOutJournal.smt2  |182.0MiB|182.0MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.CheckWellformed__CommitterCommitModel.__default.WriteOutJournal.smt2  |95.808MiB|95.808MiB|0B| 0.0%|
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
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.InitImpliesInv.smt2                |50.084MiB|50.084MiB|0B| 0.0%|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectPreservesLookups.smt2      |94.652MiB|94.652MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-JournalInterval.i.dfy.Impl__JournalIntervals.__default.Disk__Journal__append.smt2  |34.672MiB|34.672MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBlockOfJournalRange.smt2  |30.28MiB|30.28MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBytesSplit.smt2  |31.048MiB|31.048MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeEqJournalBlocks.smt2  |56.396MiB|56.396MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeOfByteSeqGetI.smt2  |35.168MiB|35.168MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-Marshalling.i.dfy.Impl__Marshalling.__default.pivotTableWeightUpperBound.smt2  |133.0MiB|133.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeeping.smt2    |168.0MiB|168.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeepingNoSuccsUpdate.smt2  |168.0MiB|168.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketGeneratorModel.i.dfy.Impl__BucketGeneratorModel.__default.GenFromBucketStackWithLowerBoundYieldsComposeSeq.smt2  |58.452MiB|58.452MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.GetSuccessorInBucketStackResult.smt2  |54.944MiB|54.944MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.ProcessGeneratorResult.smt2  |109.0MiB|109.0MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterCommitImpl.i.dfy.Impl__CommitterCommitImpl.__default.WriteOutJournal.smt2  |182.0MiB|182.0MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.CheckWellformed__CommitterCommitModel.__default.WriteOutJournal.smt2  |95.808MiB|95.808MiB|0B| 0.0%|
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
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.InitImpliesInv.smt2                |50.084MiB|50.084MiB|0B| 0.0%|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectPreservesLookups.smt2      |94.652MiB|94.652MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-JournalInterval.i.dfy.Impl__JournalIntervals.__default.Disk__Journal__append.smt2  |34.672MiB|34.672MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBlockOfJournalRange.smt2  |30.28MiB|30.28MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBytesSplit.smt2  |31.048MiB|31.048MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeEqJournalBlocks.smt2  |56.396MiB|56.396MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeOfByteSeqGetI.smt2  |35.168MiB|35.168MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-Marshalling.i.dfy.Impl__Marshalling.__default.pivotTableWeightUpperBound.smt2  |133.0MiB|133.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeeping.smt2    |168.0MiB|168.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeepingNoSuccsUpdate.smt2  |168.0MiB|168.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketGeneratorModel.i.dfy.Impl__BucketGeneratorModel.__default.GenFromBucketStackWithLowerBoundYieldsComposeSeq.smt2  |58.452MiB|58.452MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.GetSuccessorInBucketStackResult.smt2  |54.944MiB|54.944MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.ProcessGeneratorResult.smt2  |109.0MiB|109.0MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterCommitImpl.i.dfy.Impl__CommitterCommitImpl.__default.WriteOutJournal.smt2  |182.0MiB|182.0MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.CheckWellformed__CommitterCommitModel.__default.WriteOutJournal.smt2  |95.808MiB|95.808MiB|0B| 0.0%|
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
|s_komodo-1518.6.smt2                                                                       |  81.141s |16.224GiB|
|d_komodo-verified-entry.i.dfyImpl___module.__default.lemma__userExecutionPreservesPrivState.smt2 |  34.514s |1976.0MiB|
|d_lvbkv-PivotBetree-PivotBetreeSpecWFNodes.i.dfy.Impl__PivotBetreeSpecWFNodes.__default.SplitMaps.smt2 |  40.349s |929.0MiB|
|d_komodo-verified-attest.gen.dfyImpl___module.__default.va__lemma__compute__hmac_split0.smt2 |  52.495s |402.0MiB|
|d_lvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.PageInNodeResp.smt2                       |  38.538s |371.0MiB|
|d_komodo-verified-verify.gen.dfyImpl___module.__default.va__lemma__compare__memory__to__regs.smt2 |  22.014s |366.0MiB|
|d_komodo-verified-svc_handlers.gen.dfyImpl___module.__default.va__lemma__svc__map__data__zeropage.smt2 |  40.589s |354.0MiB|
|d_lvbkv-BlockCacheSystem-BetreeSystem_Refines_StatesViewPivotBetree.i.dfy.Impl__BetreeSystem__Refines__StatesViewPivotBetree.__default.BetreeMoveStepRefines.smt2 |  41.913s |348.0MiB|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__svcHandled__loweq__pdb.smt2 |  48.357s |335.0MiB|
|s_komodo-1557.3.smt2                                                                       |  80.036s |277.0MiB|
|d_komodo-verified-stop.gen.dfyImpl___module.__default.va__lemma__kom__smc__stop.smt2       |  49.233s |275.0MiB|
|d_komodo-verified-attest_input.gen.dfyImpl___module.__default.va__lemma__arrange__attestation__input_split0.smt2 |  24.069s |267.0MiB|
|d_komodo-verified-verify_input.gen.dfyImpl___module.__default.va__lemma__arrange__verification__input_split0.smt2 |  10.328s |267.0MiB|
|d_komodo-verified-finalise.gen.dfyImpl___module.__default.va__lemma__kom__smc__finalise.smt2 |  39.504s |264.0MiB|
|d_komodo-verified-sha-hmac.gen.dfyImpl___module.__default.va__lemma__hmac__inner__prep__hash.smt2 |  31.103s |257.0MiB|
|d_komodo-verified-map_utils.gen.dfyCheckWellformed___module.__default.va__lemma__kom__smc__map__measure__sha.smt2 |  26.096s |243.0MiB|
|d_lvbkv-lib-Buckets-PackedKVMarshalling.i.dfy.Impl__PackedKVMarshalling.__default.SizeOfVPackedStringArrayIsKeyListWeight.smt2 |  18.134s |243.0MiB|
|d_komodo-verified-init_addrspace.gen.dfyImpl___module.__default.va__lemma__init__addrspace.smt2 |  27.343s |242.0MiB|
|d_komodo-verified-secprop-integ_ni_entry.i.dfyImpl___module.__default.lemma__enter__enc__obs__enter.smt2 |  24.311s |241.0MiB|
|d_komodo-verified-init_l2ptable.gen.dfyImpl___module.__default.va__lemma__init__l2ptable__success.smt2 |  35.025s |237.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|s_komodo-1518.6.smt2                                                                       |  81.141s |16.224GiB|
|d_komodo-verified-entry.i.dfyImpl___module.__default.lemma__userExecutionPreservesPrivState.smt2 |  34.514s |1976.0MiB|
|d_lvbkv-PivotBetree-PivotBetreeSpecWFNodes.i.dfy.Impl__PivotBetreeSpecWFNodes.__default.SplitMaps.smt2 |  40.349s |929.0MiB|
|d_komodo-verified-attest.gen.dfyImpl___module.__default.va__lemma__compute__hmac_split0.smt2 |  52.495s |402.0MiB|
|d_lvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.PageInNodeResp.smt2                       |  38.538s |371.0MiB|
|d_komodo-verified-verify.gen.dfyImpl___module.__default.va__lemma__compare__memory__to__regs.smt2 |  22.014s |366.0MiB|
|d_komodo-verified-svc_handlers.gen.dfyImpl___module.__default.va__lemma__svc__map__data__zeropage.smt2 |  40.589s |354.0MiB|
|d_lvbkv-BlockCacheSystem-BetreeSystem_Refines_StatesViewPivotBetree.i.dfy.Impl__BetreeSystem__Refines__StatesViewPivotBetree.__default.BetreeMoveStepRefines.smt2 |  41.913s |348.0MiB|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__svcHandled__loweq__pdb.smt2 |  48.357s |335.0MiB|
|s_komodo-1557.3.smt2                                                                       |  80.036s |277.0MiB|
|d_komodo-verified-stop.gen.dfyImpl___module.__default.va__lemma__kom__smc__stop.smt2       |  49.233s |275.0MiB|
|d_komodo-verified-attest_input.gen.dfyImpl___module.__default.va__lemma__arrange__attestation__input_split0.smt2 |  24.069s |267.0MiB|
|d_komodo-verified-verify_input.gen.dfyImpl___module.__default.va__lemma__arrange__verification__input_split0.smt2 |  10.328s |267.0MiB|
|d_komodo-verified-finalise.gen.dfyImpl___module.__default.va__lemma__kom__smc__finalise.smt2 |  39.504s |264.0MiB|
|d_komodo-verified-sha-hmac.gen.dfyImpl___module.__default.va__lemma__hmac__inner__prep__hash.smt2 |  31.103s |257.0MiB|
|d_komodo-verified-map_utils.gen.dfyCheckWellformed___module.__default.va__lemma__kom__smc__map__measure__sha.smt2 |  26.096s |243.0MiB|
|d_lvbkv-lib-Buckets-PackedKVMarshalling.i.dfy.Impl__PackedKVMarshalling.__default.SizeOfVPackedStringArrayIsKeyListWeight.smt2 |  18.134s |243.0MiB|
|d_komodo-verified-init_addrspace.gen.dfyImpl___module.__default.va__lemma__init__addrspace.smt2 |  27.343s |242.0MiB|
|d_komodo-verified-secprop-integ_ni_entry.i.dfyImpl___module.__default.lemma__enter__enc__obs__enter.smt2 |  24.311s |241.0MiB|
|d_komodo-verified-init_l2ptable.gen.dfyImpl___module.__default.va__lemma__init__l2ptable__success.smt2 |  35.025s |237.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.InitImpliesInv.smt2                |   0.513s  |   0.513s  |   0.000s  | 0.0%|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectPreservesLookups.smt2      |   8.787s  |   8.787s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-JournalInterval.i.dfy.Impl__JournalIntervals.__default.Disk__Journal__append.smt2  |   1.088s  |   1.088s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBlockOfJournalRange.smt2  |   0.346s  |   0.346s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBytesSplit.smt2  |   0.381s  |   0.381s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeEqJournalBlocks.smt2  |   3.167s  |   3.167s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeOfByteSeqGetI.smt2  |   0.788s  |   0.788s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-Marshalling.i.dfy.Impl__Marshalling.__default.pivotTableWeightUpperBound.smt2  |   4.764s  |   4.764s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeeping.smt2    |   6.737s  |   6.737s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeepingNoSuccsUpdate.smt2  |   6.161s  |   6.161s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketGeneratorModel.i.dfy.Impl__BucketGeneratorModel.__default.GenFromBucketStackWithLowerBoundYieldsComposeSeq.smt2  |   2.159s  |   2.159s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.GetSuccessorInBucketStackResult.smt2  |   1.546s  |   1.546s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.ProcessGeneratorResult.smt2  |  17.247s  |  17.247s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterCommitImpl.i.dfy.Impl__CommitterCommitImpl.__default.WriteOutJournal.smt2  |  20.773s  |  20.773s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.CheckWellformed__CommitterCommitModel.__default.WriteOutJournal.smt2  |   1.951s  |   1.951s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.Impl__CommitterCommitModel.__default.WriteOutJournalCorrect.smt2  |   3.225s  |   3.225s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-DeallocImpl.i.dfy.Impl__DeallocImpl.__default.Dealloc.smt2                     |  47.368s  |  47.368s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-GrowImpl.i.dfy.Impl__GrowImpl.__default.grow.smt2                              |  33.478s  |  33.478s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.PageInIndirectionTableResp.smt2            |  56.749s  |  56.749s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.FindIndirectionTableLocationAndRequestWriteCorrect.smt2  |   3.551s  |   3.551s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.PageInIndirectionTableRespCorrect.smt2   |   2.630s  |   2.630s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.FindRefWithNoLoc.smt2  |  14.571s  |  14.571s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.RemoveRef.smt2  |  19.676s  |  19.676s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.CheckWellformed__IndirectionTableModel.__default.UpdateAndRemoveLoc.smt2  |   4.085s  |   4.085s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.Impl__IndirectionTableModel.__default.LemmaRemoveRefStuff.smt2  |  10.895s  |  10.895s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistImpl.i.dfy.Impl__JournalistImpl.Journalist.parseJournals.smt2        |   0.961s  |   0.961s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.journalRangeFromHasChecksums.smt2  |   0.484s  |   0.484s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.lemma__writeJournalEntries.smt2  |   5.057s  |   5.057s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.parseEntriesFromHasEntriesI.smt2  |   5.152s  |   5.152s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.parsesFromStuff.smt2  |   0.470s  |   0.470s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.freeze.smt2   |   0.856s  |   0.856s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.packageFrozenJournal.smt2  |   0.669s  |   0.669s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.packageInMemoryJournal.smt2  |   0.739s  |   0.739s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistParsingImpl.i.dfy.Impl__JournalistParsingImpl.__default.ParseJournalRangeOfBytes.smt2  |   0.738s  |   0.738s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.strictlySortedKeySeqToVal.smt2  |  13.837s  |  13.837s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-NodeImpl.i.dfy.Impl__NodeImpl.Node.__ctor.smt2                                 |   2.754s  |   2.754s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-NodeModel.i.dfy.Impl__NodeModel.__default.CutoffNodeAndKeepRightCorrect.smt2   |   1.674s  |   1.674s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-SuccImpl.i.dfy.Impl__SuccImpl.__default.getPath.smt2                           |  14.062s  |  14.062s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-SuccModel.i.dfy.Impl__SuccModel.__default.lemmaGetPathResult.smt2              |   8.213s  |   8.213s  |   0.000s  | 0.0%|
|d_fvbkv-MapSpec-TSJ.i.dfy.Impl__TSJ.__default.CrashStepPreservesInv.smt2                    |   0.316s  |   0.316s  |   0.000s  | 0.0%|
|d_fvbkv-MapSpec-TSJ.i.dfy.Impl__TSJ.__default.Move1to2StepPreservesInv.smt2                 |   0.296s  |   0.296s  |   0.000s  | 0.0%|
|d_fvbkv-MapSpec-TSJMap_Refines_ThreeStateVersionedMap.i.dfy.Impl__TSJMap__Refines__ThreeStateVersionedMap.__default.RefinesReplay.smt2  |   3.441s  |   3.441s  |   0.000s  | 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.Impl__PivotBetreeSpec.__default.CutoffNodeCorrect.smt2  |   0.753s  |   0.753s  |   0.000s  | 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.Impl__PivotBetreeSpecRefinement.__default.InUpperBoundAndNot.smt2  |   0.651s  |   0.651s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-Arrays.i.dfy.Impl__Arrays.__default.replace1with2.smt2                     |   0.316s  |   0.316s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.all__in__set__implies__all1s__uint64.smt2  |   6.666s  |   6.666s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-Multisets.i.dfy.Impl__Multisets.__default.ApplyAdditive.smt2               |   1.343s  |   1.343s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-Multisets.i.dfy.Impl__Multisets.__default.FoldSeqRemove.smt2               |   0.227s  |   0.227s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-sequences.i.dfy.Impl__Sequences.__default.DisjointConcatenation.smt2       |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-total_order.i.dfy.Impl__Integer__Order.__default.FlattenStrictlySorted.smt2  |   0.211s  |   0.211s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-total_order_impl.i.dfy.Impl__Total__Order__Impl.__default.ArrayLargestLtePlus1Linear.smt2  |   0.251s  |   0.251s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.CloneSeq.smt2               |  14.926s  |  14.926s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.ISeqInduction.smt2          |   0.777s  |   0.777s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.ISeq__replace1with2.smt2    |  39.718s  |  39.718s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.__default.PartialFlush.smt2           |  33.150s  |  33.150s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.__default.pkvList2BucketList.smt2     |   6.675s  |   6.675s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketModel.i.dfy.Impl__BucketModel.__default.BucketListItemFlush__eq.smt2  |   0.527s  |   0.527s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketModel.i.dfy.Impl__BucketModel.__default.mergeToChildrenIterCorrect.smt2  |  13.010s  |  13.010s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketModel.i.dfy.Impl__BucketModel.__default.mergeToOneOneChild__eq__BucketList.smt2  |   3.765s  |   3.765s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketModel.i.dfy.Impl__BucketModel.__default.mergeToOneOneChild__eq__topBotAccMerge.smt2  |  11.655s  |  11.655s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.ImageEquiv.smt2       |   0.414s  |   0.414s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.ImageIntersect.smt2   |   0.422s  |   0.422s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.ImageSubset.smt2      |   0.417s  |   0.417s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.SplitBucketImage.smt2  |   0.421s  |   0.421s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.WeightBucketListItemFlush.smt2  |   0.662s  |   0.662s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.WeightBucketListItemFlushInner.smt2  |   6.125s  |   6.125s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.WeightSplitBucketInListLe.smt2  |   0.774s  |   0.774s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.WeightWellMarshalledListPointwiseLe.smt2  |   1.163s  |   1.163s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketsLib.i.dfy.Impl__BucketsLib.__default.BInternalPreWFWellMarshalled.smt2  |   2.358s  |   2.358s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketsLib.i.dfy.Impl__BucketsLib.__default.BInternalWFBucket.smt2      |   4.485s  |   4.485s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketsLib.i.dfy.Impl__BucketsLib.__default.GetJoinBucketListEq.smt2    |   2.051s  |   2.051s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketsLib.i.dfy.Impl__BucketsLib.__default.SortedSeqOfKeyValueHasKey.smt2  |   0.431s  |   0.431s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketsLib.i.dfy.Impl__BucketsLib.__default.SplitBucketOnPivotsAt.smt2  |   2.272s  |   2.272s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketsLib.i.dfy.Impl__BucketsLib.__default.WFProperMergeBucketsInList.smt2  |   0.814s  |   0.814s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketsLib.i.dfy.Impl__BucketsLib.__default.WFProperSplitBucketInList.smt2  |   0.841s  |   0.841s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-KMBPKVOps.i.dfy.Impl__KMBPKVOps.__default.FromPkv.smt2                  |  12.098s  |  12.098s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.CheckWellformed__DynamicPkv.__default.PSAPopFrontWeight.smt2  |   0.653s  |   0.653s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.CheckWellformed__DynamicPkv.__default.PSAPopFrontWeightSuffix.smt2  |   0.653s  |   0.653s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.CheckWellformed__PackedKV.__default.subPkv.smt2          |   1.305s  |   1.305s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.DynamicPkv.Append.smt2                  |   3.720s  |   3.720s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.__default.IMessagesSlice.smt2           |   1.769s  |   1.769s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.__default.MergeToChildrenIter.smt2      |  42.737s  |  42.737s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.__default.PSAPopFrontWeight.smt2        |   1.295s  |   1.295s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.__default.PSAPopFrontWeightSuffix.smt2  |   0.923s  |   0.923s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.__default.WeightBucketPkv__eq__WeightPkv.smt2  |   1.381s  |   1.381s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.ComputeIsSorted.smt2            |   0.666s  |   0.666s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.Imaps.smt2                      |   1.467s  |   1.467s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.SplitLeft.smt2                  |   1.293s  |   1.293s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.SplitRight.smt2                 |   6.289s  |   6.289s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKVMarshalling.i.dfy.Impl__PackedKVMarshalling.__default.SizeOfVPackedStringArrayIsMessageListWeight.smt2  |   6.185s  |   6.185s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.CheckWellformed__PackedStringArray.__default.psaSeq.smt2  |   0.318s  |   0.318s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.BinarySearchIndexOfFirstKeyGt.smt2  |   0.824s  |   0.824s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.BinarySearchIndexOfFirstKeyGte.smt2  |   0.623s  |   0.623s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.IndexOfFirstKeyGt.smt2  |   0.372s  |   0.372s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.PsaSuffix.smt2  |   0.320s  |   0.320s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.ToSeq.smt2    |   0.363s  |   0.363s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.psaAppendIAppend.smt2  |   0.380s  |   0.380s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.psaCanAppendI.smt2  |   0.606s  |   0.606s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-KMBtree.i.dfy.Impl__KMBtree.__default.SplitChildOfIndex.smt2     |  18.955s  |  18.955s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-LruImpl.i.dfy.Impl__LruImpl.LruImplQueue.Remove.smt2             |  17.977s  |  17.977s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-LruImpl.i.dfy.Impl__LruImpl.__default.lemmaGetRemoveQueueIndex.smt2  |   0.321s  |   0.321s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__TestMutableBtree.__default.SplitChildOfIndex.smt2  |  33.464s  |  33.464s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtreeBulkOperations.i.dfy.Impl__MutableBtreeBulkOperations.__default.CountElements.smt2  |   2.368s  |   2.368s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtreeBulkOperations.i.dfy.Impl__MutableBtreeBulkOperations.__default.ToSeqSubtree.smt2  |  10.592s  |  10.592s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableMapModel.i.dfy.CheckWellformed__MutableMapModel.__default.SimpleIterInc.smt2  |   1.526s  |   1.526s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableMapModel.i.dfy.Impl__MutableMapModel.__default.LemmaProbeResult.smt2  |  27.935s  |  27.935s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableMapModel.i.dfy.Impl__MutableMapModel.__default.LemmaReallocIterateResult.smt2  |  13.885s  |  13.885s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallArrayContents.smt2  |   3.507s  |   3.507s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallByteArray.smt2  |   0.799s  |   0.799s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallByteArrayInterior.smt2  |   2.957s  |   2.957s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallTupleContents.smt2  |   3.017s  |   3.017s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__add__mul__div.smt2           |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__div__multiples__vanish__fancy.smt2  |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Math-mul.i.dfy.CheckWellformed__Math____mul__i.__default.mul__recursive.smt2    |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Math-mul.i.dfy.Impl__Math____mul__i.__default.lemma__mul__one__to__one.smt2     |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|d_komodo-verified-allocate_page.gen.dfyCheckWellformed___module.__default.va__lemma__allocate__page.smt2  |   7.545s  |   7.545s  |   0.000s  | 0.0%|
|d_komodo-verified-allocate_page.gen.dfyImpl___module.__default.va__lemma__addrspace__incref.smt2  |  48.733s  |  48.733s  |   0.000s  | 0.0%|
|d_komodo-verified-attest.gen.dfyImpl___module.__default.va__lemma__compute__hmac.smt2       |  44.253s  |  44.253s  |   0.000s  | 0.0%|
|d_komodo-verified-attest.gen.dfyImpl___module.__default.va__lemma__compute__hmac_split0.smt2  |  52.495s  |  52.495s  |   0.000s  | 0.0%|
|d_komodo-verified-attest_helpers.gen.dfyImpl___module.__default.va__lemma__addrspace__va__for__page__va.smt2  |  17.843s  |  17.843s  |   0.000s  | 0.0%|
|d_komodo-verified-attest_input.gen.dfyCheckWellformed___module.__default.va__lemma__arrange__attestation__input.smt2  |   2.975s  |   2.975s  |   0.000s  | 0.0%|
|d_komodo-verified-attest_input.gen.dfyImpl___module.__default.va__lemma__arrange__attestation__input_split0.smt2  |  24.069s  |  24.069s  |   0.000s  | 0.0%|
|d_komodo-verified-attest_input.gen.dfyImpl___module.__default.va__lemma__arrange__real__measurement__in__memory_split0.smt2  |  14.649s  |  14.649s  |   0.000s  | 0.0%|
|d_komodo-verified-attest_input.gen.dfyImpl___module.__default.va__lemma__arrange__real__measurement__in__memory_split1.smt2  |  24.710s  |  24.710s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.gen.dfyImpl___module.__default.lemma__aligned__sp.smt2              |   4.290s  |   4.290s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.gen.dfyImpl___module.__default.va__lemma__unstack__banked__regs2.smt2  |  39.953s  |  39.953s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.gen.dfyImpl___module.__default.va__lemma__unstack__banked__regs3.smt2  |  37.882s  |  37.882s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.i.dfyCheckWellformed___module.__default.KomExceptionHandlerInvariant.smt2  |   6.491s  |   6.491s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.i.dfyImpl___module.__default.lemma__contentsOfPage__corresponds.smt2  |   2.111s  |   2.111s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.i.dfyImpl___module.__default.lemma__evalMOVSPCLRUC__inner.smt2      |  17.704s  |  17.704s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.i.dfyImpl___module.__default.lemma__onlyDataPagesAreWritable.smt2   |   0.859s  |   0.859s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.i.dfyImpl___module.__default.lemma__userExecutionPreservesPrivState.smt2  |  34.514s  |  34.514s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.i.dfyImpl___module.__default.lemma__userExecutionUpdatesPageDb.smt2  |  23.848s  |  23.848s  |   0.000s  | 0.0%|
|d_komodo-verified-entrybits.i.dfyImpl___module.__default.lemma__sp__bit__helper.smt2        |   0.667s  |   0.667s  |   0.000s  | 0.0%|
|d_komodo-verified-exceptions.i.dfyImpl___module.__default.lemma__PrivInterruptInvariants.smt2  |  38.952s  |  38.952s  |   0.000s  | 0.0%|
|d_komodo-verified-exhandler_state.i.dfyImpl___module.__default.lemma__UserExceptionStateSideEffects.smt2  |  32.297s  |  32.297s  |   0.000s  | 0.0%|
|d_komodo-verified-finalise.gen.dfyImpl___module.__default.lemma__kom__smc__finalise__success__helper1.smt2  |  40.616s  |  40.616s  |   0.000s  | 0.0%|
|d_komodo-verified-finalise.gen.dfyImpl___module.__default.va__lemma__kom__smc__finalise.smt2  |  39.504s  |  39.504s  |   0.000s  | 0.0%|
|d_komodo-verified-init_addrspace.gen.dfyImpl___module.__default.va__lemma__init__addrspace.smt2  |  27.343s  |  27.343s  |   0.000s  | 0.0%|
|d_komodo-verified-init_l2ptable.gen.dfyImpl___module.__default.va__lemma__init__l2ptable__success.smt2  |  35.025s  |  35.025s  |   0.000s  | 0.0%|
|d_komodo-verified-init_l2ptable.gen.dfyImpl___module.__default.va__lemma__zero__l2__page.smt2  |  28.933s  |  28.933s  |   0.000s  | 0.0%|
|d_komodo-verified-kom_utils.gen.dfyCheckWellformed___module.__default.va__lemma__stack__nonvolatiles.smt2  |   4.730s  |   4.730s  |   0.000s  | 0.0%|
|d_komodo-verified-kom_utils.gen.dfyImpl___module.__default.va__lemma__load__page__type.smt2  |   6.986s  |   6.986s  |   0.000s  | 0.0%|
|d_komodo-verified-kom_utils.gen.dfyImpl___module.__default.va__lemma__unstack__lr.smt2      |   1.840s  |   1.840s  |   0.000s  | 0.0%|
|d_komodo-verified-kom_utils.gen.dfyImpl___module.__default.va__lemma__unstack__nonvolatiles.smt2  |  19.416s  |  19.416s  |   0.000s  | 0.0%|
|d_komodo-verified-kom_utils.gen.dfyImpl___module.__default.va__lemma__unstack__nonvolatiles__except__lr.smt2  |  16.995s  |  16.995s  |   0.000s  | 0.0%|
|d_komodo-verified-kom_utils.gen.dfyImpl___module.__default.va__lemma__update__pagedb__entry.smt2  |  11.943s  |  11.943s  |   0.000s  | 0.0%|
|d_komodo-verified-map_common.gen.dfyImpl___module.__default.va__lemma__insecure__phys__to__virt.smt2  |  48.670s  |  48.670s  |   0.000s  | 0.0%|
|d_komodo-verified-map_common.gen.dfyImpl___module.__default.va__lemma__is__valid__mapping__target.smt2  |  27.519s  |  27.519s  |   0.000s  | 0.0%|
|d_komodo-verified-map_common.gen.dfyImpl___module.__default.va__lemma__is__valid__mapping__target_k__finish.smt2  |  20.102s  |  20.102s  |   0.000s  | 0.0%|
|d_komodo-verified-map_utils.gen.dfyCheckWellformed___module.__default.va__lemma__kom__smc__map__measure__hash.smt2  |  22.824s  |  22.824s  |   0.000s  | 0.0%|
|d_komodo-verified-map_utils.gen.dfyCheckWellformed___module.__default.va__lemma__kom__smc__map__measure__sha.smt2  |  26.096s  |  26.096s  |   0.000s  | 0.0%|
|d_komodo-verified-map_utils.gen.dfyImpl___module.__default.va__lemma__fetch__l1pte.smt2     |  11.832s  |  11.832s  |   0.000s  | 0.0%|
|d_komodo-verified-mapping.i.dfyImpl___module.__default.lemma__installL1PTEInPageDb__dataPageRefs.smt2  |   1.491s  |   1.491s  |   0.000s  | 0.0%|
|d_komodo-verified-pagedb.i.dfyImpl___module.__default.extractPageDbToAbstract.smt2          |   1.593s  |   1.593s  |   0.000s  | 0.0%|
|d_komodo-verified-pagedb.i.dfyImpl___module.__default.extractPageDbToAbstractOne.smt2       |   1.522s  |   1.522s  |   0.000s  | 0.0%|
|d_komodo-verified-ptables.i.dfyImpl___module.__default.lemma__WritablePages.smt2            |   1.756s  |   1.756s  |   0.000s  | 0.0%|
|d_komodo-verified-ptables.i.dfyImpl___module.__default.lemma__l2tablesmatch.smt2            |   4.607s  |   4.607s  |   0.000s  | 0.0%|
|d_komodo-verified-ptables.i.dfyImpl___module.__default.lemma__ptablesmatch.smt2             |   6.646s  |   6.646s  |   0.000s  | 0.0%|
|d_komodo-verified-ptables.i.dfyImpl___module.__default.lemma__ptablesmatch_split0.smt2      |   3.335s  |   3.335s  |   0.000s  | 0.0%|
|d_komodo-verified-ptebits.i.dfyImpl___module.__default.lemma__nonexec__mapping.smt2         |   4.070s  |   4.070s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__AllPages.smt2   |   2.836s  |   2.836s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__enter__loweq__pdb__not__atkr.smt2  |  20.091s  |  20.091s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__exceptionHandled__atkr.smt2  |   5.801s  |   5.801s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__svcHandled__loweq__pdb.smt2  |  48.357s  |  48.357s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__updateUserPages__conf__not__atkr.smt2  |  34.810s  |  34.810s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__validEnclaveStepPrime__conf__not__atkr__retnondet.smt2  |  41.595s  |  41.595s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-integ_ni_entry.i.dfyImpl___module.__default.lemma__enter__enc__obs__enter.smt2  |  24.311s  |  24.311s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-integ_ni_entry.i.dfyImpl___module.__default.lemma__enter__loweq__pdb__not__obs.smt2  |  20.432s  |  20.432s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-hmac.gen.dfyImpl___module.__default.va__lemma__hmac__inner__prep__hash.smt2  |  31.103s  |  31.103s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-memory-helpers.i.dfyImpl___module.__default.lemma__AddrMemContentsSeq__adds.smt2  |   1.565s  |   1.565s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-sha256-block-data-order.gen.dfyImpl___module.__default.va__refined__sha256__block__data__order_split0.smt2  |  38.822s  |  38.822s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-sha256-one-block.gen.dfyImpl___module.__default.va__abstract__update__Hs.smt2  |  47.751s  |  47.751s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-sha256.i.dfyImpl___module.__default.SHA__padding__words2bytes.smt2    |  33.654s  |  33.654s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-sha256.i.dfyImpl___module.__default.lemma__InputHelper.smt2           |   0.410s  |   0.410s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-sha256.s.dfyCheckWellformed___module.__default.K__SHA256.smt2         |   3.040s  |   3.040s  |   0.000s  | 0.0%|
|d_komodo-verified-smcapi.i.dfyImpl___module.__default.kom__smc__map__measure__helper1.smt2  |  24.941s  |  24.941s  |   0.000s  | 0.0%|
|d_komodo-verified-smcapi.i.dfyImpl___module.__default.lemma__sha256__concat.smt2            |   1.027s  |   1.027s  |   0.000s  | 0.0%|
|d_komodo-verified-stop.gen.dfyImpl___module.__default.va__lemma__kom__smc__stop.smt2        |  49.233s  |  49.233s  |   0.000s  | 0.0%|
|d_komodo-verified-svc_handlers.gen.dfyCheckWellformed___module.__default.va__lemma__svc__returning__verify__step1.smt2  |  11.258s  |  11.258s  |   0.000s  | 0.0%|
|d_komodo-verified-svc_handlers.gen.dfyImpl___module.__default.lemma__svc__returning__verify__step0__helper.smt2  |  47.367s  |  47.367s  |   0.000s  | 0.0%|
|d_komodo-verified-svc_handlers.gen.dfyImpl___module.__default.lemma__svc__returning__verify__step1__helper.smt2  |  39.567s  |  39.567s  |   0.000s  | 0.0%|
|d_komodo-verified-svc_handlers.gen.dfyImpl___module.__default.va__lemma__svc__map__data__success.smt2  |  37.103s  |  37.103s  |   0.000s  | 0.0%|
|d_komodo-verified-svc_handlers.gen.dfyImpl___module.__default.va__lemma__svc__map__data__zeropage.smt2  |  40.589s  |  40.589s  |   0.000s  | 0.0%|
|d_komodo-verified-svc_handlers.gen.dfyImpl___module.__default.va__lemma__svc__returning__default.smt2  |  17.745s  |  17.745s  |   0.000s  | 0.0%|
|d_komodo-verified-verify.gen.dfyImpl___module.__default.va__lemma__compare__memory__to__regs.smt2  |  22.014s  |  22.014s  |   0.000s  | 0.0%|
|d_komodo-verified-verify_input.gen.dfyCheckWellformed___module.__default.lemma__grab__measurement.smt2  |   2.853s  |   2.853s  |   0.000s  | 0.0%|
|d_komodo-verified-verify_input.gen.dfyCheckWellformed___module.__default.lemma__grab__user__words.smt2  |   2.798s  |   2.798s  |   0.000s  | 0.0%|
|d_komodo-verified-verify_input.gen.dfyImpl___module.__default.lemma__grab__measurement.smt2  |  34.937s  |  34.937s  |   0.000s  | 0.0%|
|d_komodo-verified-verify_input.gen.dfyImpl___module.__default.lemma__grab__user__words.smt2  |  28.192s  |  28.192s  |   0.000s  | 0.0%|
|d_komodo-verified-verify_input.gen.dfyImpl___module.__default.va__lemma__arrange__user__words__in__memory.smt2  |   9.186s  |   9.186s  |   0.000s  | 0.0%|
|d_komodo-verified-verify_input.gen.dfyImpl___module.__default.va__lemma__arrange__user__words__in__memory_split0.smt2  |  12.308s  |  12.308s  |   0.000s  | 0.0%|
|d_komodo-verified-verify_input.gen.dfyImpl___module.__default.va__lemma__arrange__verification__input_split0.smt2  |  10.328s  |  10.328s  |   0.000s  | 0.0%|
|d_komodo-verified-verify_input.gen.dfyImpl___module.__default.va__lemma__arrange__verify__measurement__in__memory.smt2  |   7.260s  |   7.260s  |   0.000s  | 0.0%|
|d_komodo-verified-verify_input.gen.dfyImpl___module.__default.va__lemma__arrange__verify__measurement__in__memory_split0.smt2  |  10.616s  |  10.616s  |   0.000s  | 0.0%|
|d_lvbkv-Betree-AsyncBetree.i.dfy.Impl__AsyncBetree.__default.QueryAdvanceChangesLookup.smt2  |   3.623s  |   3.623s  |   0.000s  | 0.0%|
|d_lvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.GrowStepPreservesInvariant.smt2    |  49.017s  |  49.017s  |   0.000s  | 0.0%|
|d_lvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.InitImpliesInv.smt2                |   0.846s  |   0.846s  |   0.000s  | 0.0%|
|d_lvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectResultingGraphAfterAllocs.smt2  |   2.355s  |   2.355s  |   0.000s  | 0.0%|
|d_lvbkv-BlockCacheSystem-BetreeCache.i.dfy.Impl__BetreeCache.__default.BetreeMoveStepPreservesInv.smt2  |  39.750s  |  39.750s  |   0.000s  | 0.0%|
|d_lvbkv-BlockCacheSystem-BetreeSystem.i.dfy.Impl__BetreeSystem.__default.BlockCacheMoveStepPreservesInv.smt2  |  16.838s  |  16.838s  |   0.000s  | 0.0%|
|d_lvbkv-BlockCacheSystem-BetreeSystem_Refines_StatesViewPivotBetree.i.dfy.Impl__BetreeSystem__Refines__StatesViewPivotBetree.__default.BetreeMoveStepRefines.smt2  |  41.913s  |  41.913s  |   0.000s  | 0.0%|
|d_lvbkv-BlockCacheSystem-BlockCache.i.dfy.Impl__BlockCache.__default.DirtyStepPreservesInv.smt2  |   4.808s  |   4.808s  |   0.000s  | 0.0%|
|d_lvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.DiskInternalStepPreservesInv.smt2  |   2.248s  |   2.248s  |   0.000s  | 0.0%|
|d_lvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBytesSplit.smt2  |   0.570s  |   0.570s  |   0.000s  | 0.0%|
|d_lvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeEqJournalBlocks.smt2  |   0.621s  |   0.621s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-GrowModel.i.dfy.Impl__GrowModel.__default.growCorrect.smt2                     |  20.689s  |  20.689s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.FindIndirectionTableLocationAndRequestWrite.smt2  |   4.980s  |   4.980s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.PageInNodeResp.smt2                        |  38.538s  |  38.538s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-IndirectionTable.i.dfy.Impl__IndirectionTable.IndirectionTable.IndirectionTableToVal.smt2  |  47.377s  |  47.377s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-JournalistImpl.i.dfy.Impl__JournalistImpl.Journalist.packageFrozenJournal.smt2  |   0.582s  |   0.582s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-JournalistImpl.i.dfy.Impl__JournalistImpl.Journalist.reallocJournalEntries.smt2  |   0.425s  |   0.425s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.journalRangeFromHasChecksums.smt2  |   0.403s  |   0.403s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.lemma__writeJournalEntries.smt2  |   8.009s  |   8.009s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.writeOntoPreservesSlice.smt2  |   0.331s  |   0.331s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-JournalistParsingImpl.i.dfy.Impl__JournalistParsingImpl.__default.ParseJournalRangeOfBytes.smt2  |   1.425s  |   1.425s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.KeyValSeqToPivots.smt2   |   4.006s  |   4.006s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.bucketsToVal.smt2        |  34.624s  |  34.624s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-MarshallingModel.i.dfy.Impl__MarshallingModel.__default.WeightBucketListLteSize.smt2  |   3.175s  |   3.175s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-NodeImpl.i.dfy.Impl__NodeImpl.Node.BucketsWellMarshalled.smt2                  |   1.202s  |   1.202s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-NodeImpl.i.dfy.Impl__NodeImpl.Node.CutoffNodeAndKeepLeft.smt2                  |   2.111s  |   2.111s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-QueryModel.i.dfy.Impl__QueryModel.__default.AugmentLookup.smt2                 |   2.990s  |   2.990s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-SplitModel.i.dfy.Impl__SplitModel.__default.lemmaChildrenConditionsCutoffNode.smt2  |   1.923s  |   1.923s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-SuccImpl.i.dfy.Impl__SuccImpl.__default.getPathInternal.smt2                   |  10.321s  |  10.321s  |   0.000s  | 0.0%|
|d_lvbkv-MapSpec-TSJ.i.dfy.Impl__TSJ.__default.CrashStepPreservesInv.smt2                    |   0.325s  |   0.325s  |   0.000s  | 0.0%|
|d_lvbkv-MapSpec-TSJ.i.dfy.Impl__TSJ.__default.Move1to2StepPreservesInv.smt2                 |   0.292s  |   0.292s  |   0.000s  | 0.0%|
|d_lvbkv-PivotBetree-PivotBetree.i.dfy.Impl__PivotBetree.__default.GCStepRefines.smt2        |   5.356s  |   5.356s  |   0.000s  | 0.0%|
|d_lvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.Impl__PivotBetreeSpecRefinement.__default.InUpperBoundAndNot.smt2  |   0.735s  |   0.735s  |   0.000s  | 0.0%|
|d_lvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.Impl__PivotBetreeSpecRefinement.__default.MergeChildrenConsistent.smt2  |  23.650s  |  23.650s  |   0.000s  | 0.0%|
|d_lvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.Impl__PivotBetreeSpecRefinement.__default.SplitMergeBuffersChildrenEq.smt2  |   1.912s  |   1.912s  |   0.000s  | 0.0%|
|d_lvbkv-PivotBetree-PivotBetreeSpecWFNodes.i.dfy.Impl__PivotBetreeSpecWFNodes.__default.SplitMaps.smt2  |  40.349s  |  40.349s  |   0.000s  | 0.0%|
|d_lvbkv-PivotBetree-TSJPivotBetree.i.dfy.Impl__TSJPivotBetree.__default.Move3StepPreservesInv.smt2  |   1.178s  |   1.178s  |   0.000s  | 0.0%|
|d_lvbkv-Versions-CompositeView_Refines_TSJMap.i.dfy.Impl__CompositeView__Refines__TSJMap.__default.CrashRefines.smt2  |   1.059s  |   1.059s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-Arrays.i.dfy.Impl__Arrays.__default.replace1with2.smt2                     |   2.840s  |   2.840s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.bit__or__is__union__uint64.smt2  |   0.616s  |   0.616s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-Sequences.i.dfy.Impl__Sequences.__default.DisjointConcatenation.smt2       |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-mathematics.i.dfy.Impl__Mathematics.__default.DivCeilLT.smt2               |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-mathematics.i.dfy.Impl__Mathematics.__default.PosMulPreservesOrder.smt2    |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-total_order.i.dfy.Impl__Total__Preorder.__default.ExistsBiggestInSet.smt2  |   0.181s  |   0.181s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-total_order_impl.i.dfy.Impl__Total__Order__Impl.__default.ArrayLargestLtPlus1.smt2  |   0.266s  |   0.266s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-total_order_impl.i.dfy.Impl__Total__Order__Impl.__default.ArrayLargestLtePlus1.smt2  |   0.284s  |   0.284s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.CloneSeq.smt2               |   1.884s  |   1.884s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.GetLastKey.smt2             |   0.950s  |   0.950s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.ISeq__replace1with2.smt2    |  16.549s  |  16.549s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.SplitOneInList.smt2         |   9.614s  |   9.614s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.WeightBucketIs.smt2         |   0.780s  |   0.780s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.WeightKeyListIs.smt2        |   1.308s  |   1.308s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.computeWeightOfSeq.smt2     |   1.567s  |   1.567s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.WeightSplitBucketAdditive.smt2  |   0.476s  |   0.476s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-LKMBPKVOps.i.dfy.Impl__LKMBPKVOps.__default.IsKeyMessageTreeInheritance.smt2  |  31.278s  |  31.278s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.CheckWellformed__PackedKV.__default.AppendEncodedMessage.smt2  |   0.673s  |   0.673s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.CheckWellformed__PackedKV.__default.psaSeq__Messages.smt2  |   0.610s  |   0.610s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.CheckWellformed__PackedKV.__default.subPkv.smt2          |   0.747s  |   0.747s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.__default.WeightBucketPkv__eq__WeightPkv.smt2  |   4.360s  |   4.360s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.__default.computePivotIndexes.smt2      |   0.689s  |   0.689s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.ComputeValidStringLens.smt2     |   0.566s  |   0.566s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedKVMarshalling.i.dfy.Impl__PackedKVMarshalling.__default.ComputeWF.smt2  |   0.656s  |   0.656s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedKVMarshalling.i.dfy.Impl__PackedKVMarshalling.__default.SizeOfVPackedStringArrayIsKeyListWeight.smt2  |  18.134s  |  18.134s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedStringArray.i.dfy.CheckWellformed__PackedStringArray.__default.psaSeq.smt2  |   0.368s  |   0.368s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.DynamicPsa.appendSeq.smt2  |   5.484s  |   5.484s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.ToSeq.smt2    |   0.393s  |   0.393s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.UniqueRepr.smt2  |   0.422s  |   0.422s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.psaAppendIAppend.smt2  |   0.432s  |   0.432s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.psaAppendSeqAdditive.smt2  |   0.515s  |   0.515s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Checksums-CRC32C_Lemmas.i.dfy.Impl__CRC32C__Lemmas.__default.four__slices.smt2  |   0.252s  |   0.252s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Checksums-CRC32C_Lut.i.dfy.CheckWellformed__CRC32C__Lut.__default.combine.smt2  |   1.831s  |   1.831s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Checksums-CRC32C_Lut.i.dfy.Impl__CRC32C__Lut.__default.reverse__p.smt2          |   0.553s  |   0.553s  |   0.000s  | 0.0%|
|d_lvbkv-lib-DataStructures-KMBtree.i.dfy.Impl__KMBtreeModel.__default.IndexesNonempty.smt2  |   0.387s  |   0.387s  |   0.000s  | 0.0%|
|d_lvbkv-lib-DataStructures-LinearMutableMap.i.dfy.Impl__LinearMutableMap.__default.Probe.smt2  |  15.311s  |  15.311s  |   0.000s  | 0.0%|
|d_lvbkv-lib-DataStructures-MutableMapModel.i.dfy.Impl__MutableMapModel.__default.LemmaReallocIterateResult.smt2  |  21.675s  |  21.675s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallArrayContents.smt2  |   3.744s  |   3.744s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallTupleContents.smt2  |   1.543s  |   1.543s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint32Array.smt2  |   0.840s  |   0.840s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint64Array.smt2  |   1.133s  |   1.133s  |   0.000s  | 0.0%|
</details>
