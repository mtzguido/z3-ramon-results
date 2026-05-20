Comparing data and data


# SUMMARY
- LHS tests = 245
- RHS tests = 245
- LHS success = 245  (100.0%)
- RHS success = 245  (100.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: bench-mariposa-unstable_ext
Runner: rise-runner-2
Z3 repo: CanCebeci/z3
Z3 commit: 18cb7654b9931442b52ef68bdb2c6643b1b01392
Z3 branch: master-clean
Z3 options: "-T:20"
Z3 inputs: inputs/mariposa/unstable_ext
Z3 commit message: Update generation number of already-internalized enodes

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: bench-mariposa-unstable_ext
Runner: rise-runner-2
Z3 repo: CanCebeci/z3
Z3 commit: 18cb7654b9931442b52ef68bdb2c6643b1b01392
Z3 branch: master-clean
Z3 options: "-T:20"
Z3 inputs: inputs/mariposa/unstable_ext
Z3 commit message: Update generation number of already-internalized enodes

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.InitImpliesInv.smt2                |   0.750s  |   0.750s  |   0.000s  | 0.0%|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectPreservesLookups.smt2      |  16.311s  |  16.311s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-JournalInterval.i.dfy.Impl__JournalIntervals.__default.Disk__Journal__append.smt2  |   1.752s  |   1.752s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBlockOfJournalRange.smt2  |   0.511s  |   0.511s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBytesSplit.smt2  |   0.567s  |   0.567s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeEqJournalBlocks.smt2  |   5.849s  |   5.849s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeOfByteSeqGetI.smt2  |   1.095s  |   1.095s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeeping.smt2    |  10.832s  |  10.832s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeepingNoSuccsUpdate.smt2  |  10.964s  |  10.964s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketGeneratorModel.i.dfy.Impl__BucketGeneratorModel.__default.GenFromBucketStackWithLowerBoundYieldsComposeSeq.smt2  |   3.808s  |   3.808s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.GetSuccessorInBucketStackResult.smt2  |   2.404s  |   2.404s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.ProcessGeneratorResult.smt2  |  20.044s  |  20.044s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterCommitImpl.i.dfy.Impl__CommitterCommitImpl.__default.WriteOutJournal.smt2  |  20.048s  |  20.048s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.CheckWellformed__CommitterCommitModel.__default.WriteOutJournal.smt2  |   2.825s  |   2.825s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.Impl__CommitterCommitModel.__default.WriteOutJournalCorrect.smt2  |   5.346s  |   5.346s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.FindIndirectionTableLocationAndRequestWriteCorrect.smt2  |   5.997s  |   5.997s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.PageInIndirectionTableRespCorrect.smt2   |   3.777s  |   3.777s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.FindRefWithNoLoc.smt2  |  20.058s  |  20.058s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.RemoveRef.smt2  |  20.051s  |  20.051s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.CheckWellformed__IndirectionTableModel.__default.UpdateAndRemoveLoc.smt2  |   6.064s  |   6.064s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.InitImpliesInv.smt2                |   0.750s  |   0.750s  |   0.000s  | 0.0%|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectPreservesLookups.smt2      |  16.311s  |  16.311s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-JournalInterval.i.dfy.Impl__JournalIntervals.__default.Disk__Journal__append.smt2  |   1.752s  |   1.752s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBlockOfJournalRange.smt2  |   0.511s  |   0.511s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBytesSplit.smt2  |   0.567s  |   0.567s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeEqJournalBlocks.smt2  |   5.849s  |   5.849s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeOfByteSeqGetI.smt2  |   1.095s  |   1.095s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeeping.smt2    |  10.832s  |  10.832s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeepingNoSuccsUpdate.smt2  |  10.964s  |  10.964s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketGeneratorModel.i.dfy.Impl__BucketGeneratorModel.__default.GenFromBucketStackWithLowerBoundYieldsComposeSeq.smt2  |   3.808s  |   3.808s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.GetSuccessorInBucketStackResult.smt2  |   2.404s  |   2.404s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.ProcessGeneratorResult.smt2  |  20.044s  |  20.044s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterCommitImpl.i.dfy.Impl__CommitterCommitImpl.__default.WriteOutJournal.smt2  |  20.048s  |  20.048s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.CheckWellformed__CommitterCommitModel.__default.WriteOutJournal.smt2  |   2.825s  |   2.825s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.Impl__CommitterCommitModel.__default.WriteOutJournalCorrect.smt2  |   5.346s  |   5.346s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.FindIndirectionTableLocationAndRequestWriteCorrect.smt2  |   5.997s  |   5.997s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.PageInIndirectionTableRespCorrect.smt2   |   3.777s  |   3.777s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.FindRefWithNoLoc.smt2  |  20.058s  |  20.058s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.RemoveRef.smt2  |  20.051s  |  20.051s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.CheckWellformed__IndirectionTableModel.__default.UpdateAndRemoveLoc.smt2  |   6.064s  |   6.064s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.InitImpliesInv.smt2                |   0.750s  |   0.750s  |   0.000s  | 0.0%|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectPreservesLookups.smt2      |  16.311s  |  16.311s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-JournalInterval.i.dfy.Impl__JournalIntervals.__default.Disk__Journal__append.smt2  |   1.752s  |   1.752s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBlockOfJournalRange.smt2  |   0.511s  |   0.511s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBytesSplit.smt2  |   0.567s  |   0.567s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeEqJournalBlocks.smt2  |   5.849s  |   5.849s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeOfByteSeqGetI.smt2  |   1.095s  |   1.095s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeeping.smt2    |  10.832s  |  10.832s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeepingNoSuccsUpdate.smt2  |  10.964s  |  10.964s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketGeneratorModel.i.dfy.Impl__BucketGeneratorModel.__default.GenFromBucketStackWithLowerBoundYieldsComposeSeq.smt2  |   3.808s  |   3.808s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.GetSuccessorInBucketStackResult.smt2  |   2.404s  |   2.404s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.ProcessGeneratorResult.smt2  |  20.044s  |  20.044s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterCommitImpl.i.dfy.Impl__CommitterCommitImpl.__default.WriteOutJournal.smt2  |  20.048s  |  20.048s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.CheckWellformed__CommitterCommitModel.__default.WriteOutJournal.smt2  |   2.825s  |   2.825s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.Impl__CommitterCommitModel.__default.WriteOutJournalCorrect.smt2  |   5.346s  |   5.346s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.FindIndirectionTableLocationAndRequestWriteCorrect.smt2  |   5.997s  |   5.997s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.PageInIndirectionTableRespCorrect.smt2   |   3.777s  |   3.777s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.FindRefWithNoLoc.smt2  |  20.058s  |  20.058s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.RemoveRef.smt2  |  20.051s  |  20.051s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.CheckWellformed__IndirectionTableModel.__default.UpdateAndRemoveLoc.smt2  |   6.064s  |   6.064s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.InitImpliesInv.smt2                |   0.750s  |   0.750s  |   0.000s  | 0.0%|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectPreservesLookups.smt2      |  16.311s  |  16.311s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-JournalInterval.i.dfy.Impl__JournalIntervals.__default.Disk__Journal__append.smt2  |   1.752s  |   1.752s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBlockOfJournalRange.smt2  |   0.511s  |   0.511s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBytesSplit.smt2  |   0.567s  |   0.567s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeEqJournalBlocks.smt2  |   5.849s  |   5.849s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeOfByteSeqGetI.smt2  |   1.095s  |   1.095s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeeping.smt2    |  10.832s  |  10.832s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeepingNoSuccsUpdate.smt2  |  10.964s  |  10.964s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketGeneratorModel.i.dfy.Impl__BucketGeneratorModel.__default.GenFromBucketStackWithLowerBoundYieldsComposeSeq.smt2  |   3.808s  |   3.808s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.GetSuccessorInBucketStackResult.smt2  |   2.404s  |   2.404s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.ProcessGeneratorResult.smt2  |  20.044s  |  20.044s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterCommitImpl.i.dfy.Impl__CommitterCommitImpl.__default.WriteOutJournal.smt2  |  20.048s  |  20.048s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.CheckWellformed__CommitterCommitModel.__default.WriteOutJournal.smt2  |   2.825s  |   2.825s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.Impl__CommitterCommitModel.__default.WriteOutJournalCorrect.smt2  |   5.346s  |   5.346s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.FindIndirectionTableLocationAndRequestWriteCorrect.smt2  |   5.997s  |   5.997s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.PageInIndirectionTableRespCorrect.smt2   |   3.777s  |   3.777s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.FindRefWithNoLoc.smt2  |  20.058s  |  20.058s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.RemoveRef.smt2  |  20.051s  |  20.051s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.CheckWellformed__IndirectionTableModel.__default.UpdateAndRemoveLoc.smt2  |   6.064s  |   6.064s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|s_komodo-1518.6.smt2                                                                       |  20.633s |3577.0MiB|
|d_komodo-verified-verify.gen.dfyImpl___module.__default.va__lemma__compare__memory__to__regs.smt2 |  20.072s |366.0MiB|
|d_komodo-verified-map_utils.gen.dfyCheckWellformed___module.__default.va__lemma__kom__smc__map__measure__sha.smt2 |  20.066s |244.0MiB|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__enter__loweq__pdb__not__atkr.smt2 |  20.065s |196.0MiB|
|d_komodo-verified-verify_input.gen.dfyImpl___module.__default.va__lemma__arrange__user__words__in__memory_split0.smt2 |  20.065s |223.0MiB|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.__default.MergeToChildrenIter.smt2     |  20.060s |197.0MiB|
|d_komodo-verified-map_common.gen.dfyImpl___module.__default.va__lemma__is__valid__mapping__target_k__finish.smt2 |  20.059s |190.0MiB|
|d_lvbkv-lib-Buckets-PackedKVMarshalling.i.dfy.Impl__PackedKVMarshalling.__default.SizeOfVPackedStringArrayIsKeyListWeight.smt2 |  20.058s |178.0MiB|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.FindRefWithNoLoc.smt2 |  20.058s |179.0MiB|
|d_lvbkv-BlockCacheSystem-BetreeSystem_Refines_StatesViewPivotBetree.i.dfy.Impl__BetreeSystem__Refines__StatesViewPivotBetree.__default.BetreeMoveStepRefines.smt2 |  20.058s |203.0MiB|
|d_komodo-verified-verify_input.gen.dfyImpl___module.__default.lemma__grab__user__words.smt2 |  20.058s |237.0MiB|
|d_fvbkv-Impl-SuccImpl.i.dfy.Impl__SuccImpl.__default.getPath.smt2                          |  20.057s |166.0MiB|
|d_komodo-verified-init_addrspace.gen.dfyImpl___module.__default.va__lemma__init__addrspace.smt2 |  20.057s |218.0MiB|
|d_fvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.ISeq__replace1with2.smt2   |  20.056s |189.0MiB|
|d_komodo-verified-attest_helpers.gen.dfyImpl___module.__default.va__lemma__addrspace__va__for__page__va.smt2 |  20.055s |144.0MiB|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__validEnclaveStepPrime__conf__not__atkr__retnondet.smt2 |  20.054s |188.0MiB|
|d_komodo-verified-kom_utils.gen.dfyImpl___module.__default.va__lemma__update__pagedb__entry.smt2 |  20.053s |121.0MiB|
|d_lvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.Impl__PivotBetreeSpecRefinement.__default.MergeChildrenConsistent.smt2 |  20.053s |192.0MiB|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.strictlySortedKeySeqToVal.smt2 |  20.053s |173.0MiB|
|d_komodo-verified-attest.gen.dfyImpl___module.__default.va__lemma__compute__hmac.smt2      |  20.052s |199.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|s_komodo-1518.6.smt2                                                                       |  20.633s |3577.0MiB|
|d_komodo-verified-verify.gen.dfyImpl___module.__default.va__lemma__compare__memory__to__regs.smt2 |  20.072s |366.0MiB|
|d_komodo-verified-map_utils.gen.dfyCheckWellformed___module.__default.va__lemma__kom__smc__map__measure__sha.smt2 |  20.066s |244.0MiB|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__enter__loweq__pdb__not__atkr.smt2 |  20.065s |196.0MiB|
|d_komodo-verified-verify_input.gen.dfyImpl___module.__default.va__lemma__arrange__user__words__in__memory_split0.smt2 |  20.065s |223.0MiB|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.__default.MergeToChildrenIter.smt2     |  20.060s |197.0MiB|
|d_komodo-verified-map_common.gen.dfyImpl___module.__default.va__lemma__is__valid__mapping__target_k__finish.smt2 |  20.059s |190.0MiB|
|d_lvbkv-lib-Buckets-PackedKVMarshalling.i.dfy.Impl__PackedKVMarshalling.__default.SizeOfVPackedStringArrayIsKeyListWeight.smt2 |  20.058s |178.0MiB|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.FindRefWithNoLoc.smt2 |  20.058s |179.0MiB|
|d_lvbkv-BlockCacheSystem-BetreeSystem_Refines_StatesViewPivotBetree.i.dfy.Impl__BetreeSystem__Refines__StatesViewPivotBetree.__default.BetreeMoveStepRefines.smt2 |  20.058s |203.0MiB|
|d_komodo-verified-verify_input.gen.dfyImpl___module.__default.lemma__grab__user__words.smt2 |  20.058s |237.0MiB|
|d_fvbkv-Impl-SuccImpl.i.dfy.Impl__SuccImpl.__default.getPath.smt2                          |  20.057s |166.0MiB|
|d_komodo-verified-init_addrspace.gen.dfyImpl___module.__default.va__lemma__init__addrspace.smt2 |  20.057s |218.0MiB|
|d_fvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.ISeq__replace1with2.smt2   |  20.056s |189.0MiB|
|d_komodo-verified-attest_helpers.gen.dfyImpl___module.__default.va__lemma__addrspace__va__for__page__va.smt2 |  20.055s |144.0MiB|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__validEnclaveStepPrime__conf__not__atkr__retnondet.smt2 |  20.054s |188.0MiB|
|d_komodo-verified-kom_utils.gen.dfyImpl___module.__default.va__lemma__update__pagedb__entry.smt2 |  20.053s |121.0MiB|
|d_lvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.Impl__PivotBetreeSpecRefinement.__default.MergeChildrenConsistent.smt2 |  20.053s |192.0MiB|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.strictlySortedKeySeqToVal.smt2 |  20.053s |173.0MiB|
|d_komodo-verified-attest.gen.dfyImpl___module.__default.va__lemma__compute__hmac.smt2      |  20.052s |199.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.InitImpliesInv.smt2                |50.792MiB|50.792MiB|0B| 0.0%|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectPreservesLookups.smt2      |94.788MiB|94.788MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-JournalInterval.i.dfy.Impl__JournalIntervals.__default.Disk__Journal__append.smt2  |35.48MiB|35.48MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBlockOfJournalRange.smt2  |30.884MiB|30.884MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBytesSplit.smt2  |31.396MiB|31.396MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeEqJournalBlocks.smt2  |56.692MiB|56.692MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeOfByteSeqGetI.smt2  |35.756MiB|35.756MiB|0B| 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeeping.smt2    |169.0MiB|169.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeepingNoSuccsUpdate.smt2  |169.0MiB|169.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketGeneratorModel.i.dfy.Impl__BucketGeneratorModel.__default.GenFromBucketStackWithLowerBoundYieldsComposeSeq.smt2  |59.06MiB|59.06MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.GetSuccessorInBucketStackResult.smt2  |55.652MiB|55.652MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.ProcessGeneratorResult.smt2  |104.0MiB|104.0MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterCommitImpl.i.dfy.Impl__CommitterCommitImpl.__default.WriteOutJournal.smt2  |169.0MiB|169.0MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.CheckWellformed__CommitterCommitModel.__default.WriteOutJournal.smt2  |96.28MiB|96.28MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.Impl__CommitterCommitModel.__default.WriteOutJournalCorrect.smt2  |109.0MiB|109.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.FindIndirectionTableLocationAndRequestWriteCorrect.smt2  |107.0MiB|107.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.PageInIndirectionTableRespCorrect.smt2   |97.0MiB|97.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.FindRefWithNoLoc.smt2  |179.0MiB|179.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.RemoveRef.smt2  |183.0MiB|183.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.CheckWellformed__IndirectionTableModel.__default.UpdateAndRemoveLoc.smt2  |99.408MiB|99.408MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.InitImpliesInv.smt2                |50.792MiB|50.792MiB|0B| 0.0%|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectPreservesLookups.smt2      |94.788MiB|94.788MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-JournalInterval.i.dfy.Impl__JournalIntervals.__default.Disk__Journal__append.smt2  |35.48MiB|35.48MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBlockOfJournalRange.smt2  |30.884MiB|30.884MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBytesSplit.smt2  |31.396MiB|31.396MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeEqJournalBlocks.smt2  |56.692MiB|56.692MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeOfByteSeqGetI.smt2  |35.756MiB|35.756MiB|0B| 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeeping.smt2    |169.0MiB|169.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeepingNoSuccsUpdate.smt2  |169.0MiB|169.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketGeneratorModel.i.dfy.Impl__BucketGeneratorModel.__default.GenFromBucketStackWithLowerBoundYieldsComposeSeq.smt2  |59.06MiB|59.06MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.GetSuccessorInBucketStackResult.smt2  |55.652MiB|55.652MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.ProcessGeneratorResult.smt2  |104.0MiB|104.0MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterCommitImpl.i.dfy.Impl__CommitterCommitImpl.__default.WriteOutJournal.smt2  |169.0MiB|169.0MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.CheckWellformed__CommitterCommitModel.__default.WriteOutJournal.smt2  |96.28MiB|96.28MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.Impl__CommitterCommitModel.__default.WriteOutJournalCorrect.smt2  |109.0MiB|109.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.FindIndirectionTableLocationAndRequestWriteCorrect.smt2  |107.0MiB|107.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.PageInIndirectionTableRespCorrect.smt2   |97.0MiB|97.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.FindRefWithNoLoc.smt2  |179.0MiB|179.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.RemoveRef.smt2  |183.0MiB|183.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.CheckWellformed__IndirectionTableModel.__default.UpdateAndRemoveLoc.smt2  |99.408MiB|99.408MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.InitImpliesInv.smt2                |50.792MiB|50.792MiB|0B| 0.0%|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectPreservesLookups.smt2      |94.788MiB|94.788MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-JournalInterval.i.dfy.Impl__JournalIntervals.__default.Disk__Journal__append.smt2  |35.48MiB|35.48MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBlockOfJournalRange.smt2  |30.884MiB|30.884MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBytesSplit.smt2  |31.396MiB|31.396MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeEqJournalBlocks.smt2  |56.692MiB|56.692MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeOfByteSeqGetI.smt2  |35.756MiB|35.756MiB|0B| 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeeping.smt2    |169.0MiB|169.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeepingNoSuccsUpdate.smt2  |169.0MiB|169.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketGeneratorModel.i.dfy.Impl__BucketGeneratorModel.__default.GenFromBucketStackWithLowerBoundYieldsComposeSeq.smt2  |59.06MiB|59.06MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.GetSuccessorInBucketStackResult.smt2  |55.652MiB|55.652MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.ProcessGeneratorResult.smt2  |104.0MiB|104.0MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterCommitImpl.i.dfy.Impl__CommitterCommitImpl.__default.WriteOutJournal.smt2  |169.0MiB|169.0MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.CheckWellformed__CommitterCommitModel.__default.WriteOutJournal.smt2  |96.28MiB|96.28MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.Impl__CommitterCommitModel.__default.WriteOutJournalCorrect.smt2  |109.0MiB|109.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.FindIndirectionTableLocationAndRequestWriteCorrect.smt2  |107.0MiB|107.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.PageInIndirectionTableRespCorrect.smt2   |97.0MiB|97.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.FindRefWithNoLoc.smt2  |179.0MiB|179.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.RemoveRef.smt2  |183.0MiB|183.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.CheckWellformed__IndirectionTableModel.__default.UpdateAndRemoveLoc.smt2  |99.408MiB|99.408MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.InitImpliesInv.smt2                |50.792MiB|50.792MiB|0B| 0.0%|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectPreservesLookups.smt2      |94.788MiB|94.788MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-JournalInterval.i.dfy.Impl__JournalIntervals.__default.Disk__Journal__append.smt2  |35.48MiB|35.48MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBlockOfJournalRange.smt2  |30.884MiB|30.884MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBytesSplit.smt2  |31.396MiB|31.396MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeEqJournalBlocks.smt2  |56.692MiB|56.692MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeOfByteSeqGetI.smt2  |35.756MiB|35.756MiB|0B| 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeeping.smt2    |169.0MiB|169.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeepingNoSuccsUpdate.smt2  |169.0MiB|169.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketGeneratorModel.i.dfy.Impl__BucketGeneratorModel.__default.GenFromBucketStackWithLowerBoundYieldsComposeSeq.smt2  |59.06MiB|59.06MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.GetSuccessorInBucketStackResult.smt2  |55.652MiB|55.652MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.ProcessGeneratorResult.smt2  |104.0MiB|104.0MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterCommitImpl.i.dfy.Impl__CommitterCommitImpl.__default.WriteOutJournal.smt2  |169.0MiB|169.0MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.CheckWellformed__CommitterCommitModel.__default.WriteOutJournal.smt2  |96.28MiB|96.28MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.Impl__CommitterCommitModel.__default.WriteOutJournalCorrect.smt2  |109.0MiB|109.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.FindIndirectionTableLocationAndRequestWriteCorrect.smt2  |107.0MiB|107.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.PageInIndirectionTableRespCorrect.smt2   |97.0MiB|97.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.FindRefWithNoLoc.smt2  |179.0MiB|179.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.RemoveRef.smt2  |183.0MiB|183.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.CheckWellformed__IndirectionTableModel.__default.UpdateAndRemoveLoc.smt2  |99.408MiB|99.408MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|s_komodo-1518.6.smt2                                                                       |  20.633s |3577.0MiB|
|d_komodo-verified-verify.gen.dfyImpl___module.__default.va__lemma__compare__memory__to__regs.smt2 |  20.072s |366.0MiB|
|d_komodo-verified-verify_input.gen.dfyImpl___module.__default.va__lemma__arrange__verification__input_split0.smt2 |  15.662s |268.0MiB|
|s_komodo-1557.3.smt2                                                                       |  20.048s |252.0MiB|
|d_komodo-verified-sha-hmac.gen.dfyImpl___module.__default.va__lemma__hmac__inner__prep__hash.smt2 |  20.051s |248.0MiB|
|d_komodo-verified-map_utils.gen.dfyCheckWellformed___module.__default.va__lemma__kom__smc__map__measure__sha.smt2 |  20.066s |244.0MiB|
|d_komodo-verified-verify_input.gen.dfyImpl___module.__default.lemma__grab__user__words.smt2 |  20.058s |237.0MiB|
|d_komodo-verified-verify_input.gen.dfyImpl___module.__default.va__lemma__arrange__user__words__in__memory_split0.smt2 |  20.065s |223.0MiB|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__updateUserPages__conf__not__atkr.smt2 |  20.050s |219.0MiB|
|d_komodo-verified-init_addrspace.gen.dfyImpl___module.__default.va__lemma__init__addrspace.smt2 |  20.057s |218.0MiB|
|d_komodo-verified-map_utils.gen.dfyCheckWellformed___module.__default.va__lemma__kom__smc__map__measure__hash.smt2 |  20.033s |208.0MiB|
|d_lvbkv-BlockCacheSystem-BetreeSystem_Refines_StatesViewPivotBetree.i.dfy.Impl__BetreeSystem__Refines__StatesViewPivotBetree.__default.BetreeMoveStepRefines.smt2 |  20.058s |203.0MiB|
|d_komodo-verified-attest.gen.dfyImpl___module.__default.va__lemma__compute__hmac.smt2      |  20.052s |199.0MiB|
|d_komodo-verified-attest_input.gen.dfyImpl___module.__default.va__lemma__arrange__attestation__input_split0.smt2 |  20.048s |199.0MiB|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.__default.MergeToChildrenIter.smt2     |  20.060s |197.0MiB|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__enter__loweq__pdb__not__atkr.smt2 |  20.065s |196.0MiB|
|d_lvbkv-BlockCacheSystem-BetreeCache.i.dfy.Impl__BetreeCache.__default.BetreeMoveStepPreservesInv.smt2 |  20.049s |195.0MiB|
|d_komodo-verified-attest_input.gen.dfyImpl___module.__default.va__lemma__arrange__real__measurement__in__memory_split1.smt2 |  20.041s |194.0MiB|
|d_lvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.ISeq__replace1with2.smt2   |  19.669s |194.0MiB|
|d_komodo-verified-secprop-integ_ni_entry.i.dfyImpl___module.__default.lemma__enter__loweq__pdb__not__obs.smt2 |  20.028s |193.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|s_komodo-1518.6.smt2                                                                       |  20.633s |3577.0MiB|
|d_komodo-verified-verify.gen.dfyImpl___module.__default.va__lemma__compare__memory__to__regs.smt2 |  20.072s |366.0MiB|
|d_komodo-verified-verify_input.gen.dfyImpl___module.__default.va__lemma__arrange__verification__input_split0.smt2 |  15.662s |268.0MiB|
|s_komodo-1557.3.smt2                                                                       |  20.048s |252.0MiB|
|d_komodo-verified-sha-hmac.gen.dfyImpl___module.__default.va__lemma__hmac__inner__prep__hash.smt2 |  20.051s |248.0MiB|
|d_komodo-verified-map_utils.gen.dfyCheckWellformed___module.__default.va__lemma__kom__smc__map__measure__sha.smt2 |  20.066s |244.0MiB|
|d_komodo-verified-verify_input.gen.dfyImpl___module.__default.lemma__grab__user__words.smt2 |  20.058s |237.0MiB|
|d_komodo-verified-verify_input.gen.dfyImpl___module.__default.va__lemma__arrange__user__words__in__memory_split0.smt2 |  20.065s |223.0MiB|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__updateUserPages__conf__not__atkr.smt2 |  20.050s |219.0MiB|
|d_komodo-verified-init_addrspace.gen.dfyImpl___module.__default.va__lemma__init__addrspace.smt2 |  20.057s |218.0MiB|
|d_komodo-verified-map_utils.gen.dfyCheckWellformed___module.__default.va__lemma__kom__smc__map__measure__hash.smt2 |  20.033s |208.0MiB|
|d_lvbkv-BlockCacheSystem-BetreeSystem_Refines_StatesViewPivotBetree.i.dfy.Impl__BetreeSystem__Refines__StatesViewPivotBetree.__default.BetreeMoveStepRefines.smt2 |  20.058s |203.0MiB|
|d_komodo-verified-attest.gen.dfyImpl___module.__default.va__lemma__compute__hmac.smt2      |  20.052s |199.0MiB|
|d_komodo-verified-attest_input.gen.dfyImpl___module.__default.va__lemma__arrange__attestation__input_split0.smt2 |  20.048s |199.0MiB|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.__default.MergeToChildrenIter.smt2     |  20.060s |197.0MiB|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__enter__loweq__pdb__not__atkr.smt2 |  20.065s |196.0MiB|
|d_lvbkv-BlockCacheSystem-BetreeCache.i.dfy.Impl__BetreeCache.__default.BetreeMoveStepPreservesInv.smt2 |  20.049s |195.0MiB|
|d_komodo-verified-attest_input.gen.dfyImpl___module.__default.va__lemma__arrange__real__measurement__in__memory_split1.smt2 |  20.041s |194.0MiB|
|d_lvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.ISeq__replace1with2.smt2   |  19.669s |194.0MiB|
|d_komodo-verified-secprop-integ_ni_entry.i.dfyImpl___module.__default.lemma__enter__loweq__pdb__not__obs.smt2 |  20.028s |193.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.InitImpliesInv.smt2                |   0.750s  |   0.750s  |   0.000s  | 0.0%|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectPreservesLookups.smt2      |  16.311s  |  16.311s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-JournalInterval.i.dfy.Impl__JournalIntervals.__default.Disk__Journal__append.smt2  |   1.752s  |   1.752s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBlockOfJournalRange.smt2  |   0.511s  |   0.511s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBytesSplit.smt2  |   0.567s  |   0.567s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeEqJournalBlocks.smt2  |   5.849s  |   5.849s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeOfByteSeqGetI.smt2  |   1.095s  |   1.095s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeeping.smt2    |  10.832s  |  10.832s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeepingNoSuccsUpdate.smt2  |  10.964s  |  10.964s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketGeneratorModel.i.dfy.Impl__BucketGeneratorModel.__default.GenFromBucketStackWithLowerBoundYieldsComposeSeq.smt2  |   3.808s  |   3.808s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.GetSuccessorInBucketStackResult.smt2  |   2.404s  |   2.404s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.ProcessGeneratorResult.smt2  |  20.044s  |  20.044s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterCommitImpl.i.dfy.Impl__CommitterCommitImpl.__default.WriteOutJournal.smt2  |  20.048s  |  20.048s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.CheckWellformed__CommitterCommitModel.__default.WriteOutJournal.smt2  |   2.825s  |   2.825s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.Impl__CommitterCommitModel.__default.WriteOutJournalCorrect.smt2  |   5.346s  |   5.346s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.FindIndirectionTableLocationAndRequestWriteCorrect.smt2  |   5.997s  |   5.997s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.PageInIndirectionTableRespCorrect.smt2   |   3.777s  |   3.777s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.FindRefWithNoLoc.smt2  |  20.058s  |  20.058s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.RemoveRef.smt2  |  20.051s  |  20.051s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.CheckWellformed__IndirectionTableModel.__default.UpdateAndRemoveLoc.smt2  |   6.064s  |   6.064s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.Impl__IndirectionTableModel.__default.LemmaRemoveRefStuff.smt2  |  19.015s  |  19.015s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistImpl.i.dfy.Impl__JournalistImpl.Journalist.parseJournals.smt2        |   1.558s  |   1.558s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.journalRangeFromHasChecksums.smt2  |   0.675s  |   0.675s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.lemma__writeJournalEntries.smt2  |   7.563s  |   7.563s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.parseEntriesFromHasEntriesI.smt2  |   7.656s  |   7.656s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.parsesFromStuff.smt2  |   0.689s  |   0.689s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.freeze.smt2   |   1.537s  |   1.537s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.packageFrozenJournal.smt2  |   0.934s  |   0.934s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.packageInMemoryJournal.smt2  |   1.105s  |   1.105s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistParsingImpl.i.dfy.Impl__JournalistParsingImpl.__default.ParseJournalRangeOfBytes.smt2  |   1.181s  |   1.181s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.strictlySortedKeySeqToVal.smt2  |  20.053s  |  20.053s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-NodeImpl.i.dfy.Impl__NodeImpl.Node.__ctor.smt2                                 |   4.198s  |   4.198s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-NodeModel.i.dfy.Impl__NodeModel.__default.CutoffNodeAndKeepRightCorrect.smt2   |   2.498s  |   2.498s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-SuccImpl.i.dfy.Impl__SuccImpl.__default.getPath.smt2                           |  20.057s  |  20.057s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-SuccModel.i.dfy.Impl__SuccModel.__default.lemmaGetPathResult.smt2              |  12.576s  |  12.576s  |   0.000s  | 0.0%|
|d_fvbkv-MapSpec-TSJ.i.dfy.Impl__TSJ.__default.CrashStepPreservesInv.smt2                    |   0.411s  |   0.411s  |   0.000s  | 0.0%|
|d_fvbkv-MapSpec-TSJ.i.dfy.Impl__TSJ.__default.Move1to2StepPreservesInv.smt2                 |   0.445s  |   0.445s  |   0.000s  | 0.0%|
|d_fvbkv-MapSpec-TSJMap_Refines_ThreeStateVersionedMap.i.dfy.Impl__TSJMap__Refines__ThreeStateVersionedMap.__default.RefinesReplay.smt2  |   8.623s  |   8.623s  |   0.000s  | 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.Impl__PivotBetreeSpec.__default.CutoffNodeCorrect.smt2  |   1.236s  |   1.236s  |   0.000s  | 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.Impl__PivotBetreeSpecRefinement.__default.InUpperBoundAndNot.smt2  |   0.896s  |   0.896s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-Arrays.i.dfy.Impl__Arrays.__default.replace1with2.smt2                     |   1.525s  |   1.525s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.all__in__set__implies__all1s__uint64.smt2  |   7.743s  |   7.743s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-Multisets.i.dfy.Impl__Multisets.__default.ApplyAdditive.smt2               |   2.168s  |   2.168s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-Multisets.i.dfy.Impl__Multisets.__default.FoldSeqRemove.smt2               |   0.289s  |   0.289s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-sequences.i.dfy.Impl__Sequences.__default.DisjointConcatenation.smt2       |   0.214s  |   0.214s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-total_order.i.dfy.Impl__Integer__Order.__default.FlattenStrictlySorted.smt2  |   0.317s  |   0.317s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-total_order_impl.i.dfy.Impl__Total__Order__Impl.__default.ArrayLargestLtePlus1Linear.smt2  |   0.325s  |   0.325s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.CloneSeq.smt2               |  20.047s  |  20.047s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.ISeqInduction.smt2          |   1.095s  |   1.095s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.ISeq__replace1with2.smt2    |  20.056s  |  20.056s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.__default.PartialFlush.smt2           |  20.049s  |  20.049s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.__default.pkvList2BucketList.smt2     |  11.112s  |  11.112s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketModel.i.dfy.Impl__BucketModel.__default.BucketListItemFlush__eq.smt2  |   0.782s  |   0.782s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketModel.i.dfy.Impl__BucketModel.__default.mergeToChildrenIterCorrect.smt2  |  20.038s  |  20.038s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketModel.i.dfy.Impl__BucketModel.__default.mergeToOneOneChild__eq__BucketList.smt2  |   7.161s  |   7.161s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketModel.i.dfy.Impl__BucketModel.__default.mergeToOneOneChild__eq__topBotAccMerge.smt2  |  18.092s  |  18.092s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.ImageEquiv.smt2       |   0.581s  |   0.581s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.ImageIntersect.smt2   |   0.696s  |   0.696s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.ImageSubset.smt2      |   0.565s  |   0.565s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.SplitBucketImage.smt2  |   0.608s  |   0.608s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.WeightBucketListItemFlush.smt2  |   1.014s  |   1.014s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.WeightBucketListItemFlushInner.smt2  |   8.443s  |   8.443s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.WeightSplitBucketInListLe.smt2  |   1.204s  |   1.204s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.WeightWellMarshalledListPointwiseLe.smt2  |   1.671s  |   1.671s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketsLib.i.dfy.Impl__BucketsLib.__default.BInternalPreWFWellMarshalled.smt2  |   3.999s  |   3.999s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketsLib.i.dfy.Impl__BucketsLib.__default.BInternalWFBucket.smt2      |   7.738s  |   7.738s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketsLib.i.dfy.Impl__BucketsLib.__default.GetJoinBucketListEq.smt2    |   3.443s  |   3.443s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketsLib.i.dfy.Impl__BucketsLib.__default.SortedSeqOfKeyValueHasKey.smt2  |   0.570s  |   0.570s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketsLib.i.dfy.Impl__BucketsLib.__default.SplitBucketOnPivotsAt.smt2  |   4.357s  |   4.357s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketsLib.i.dfy.Impl__BucketsLib.__default.WFProperMergeBucketsInList.smt2  |   1.195s  |   1.195s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketsLib.i.dfy.Impl__BucketsLib.__default.WFProperSplitBucketInList.smt2  |   1.267s  |   1.267s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-KMBPKVOps.i.dfy.Impl__KMBPKVOps.__default.FromPkv.smt2                  |  17.239s  |  17.239s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.CheckWellformed__DynamicPkv.__default.PSAPopFrontWeight.smt2  |   0.885s  |   0.885s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.CheckWellformed__DynamicPkv.__default.PSAPopFrontWeightSuffix.smt2  |   1.047s  |   1.047s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.CheckWellformed__PackedKV.__default.subPkv.smt2          |   1.973s  |   1.973s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.DynamicPkv.Append.smt2                  |   5.853s  |   5.853s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.__default.IMessagesSlice.smt2           |   2.980s  |   2.980s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.__default.MergeToChildrenIter.smt2      |  20.060s  |  20.060s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.__default.PSAPopFrontWeight.smt2        |   1.973s  |   1.973s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.__default.PSAPopFrontWeightSuffix.smt2  |   1.390s  |   1.390s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.__default.WeightBucketPkv__eq__WeightPkv.smt2  |   2.013s  |   2.013s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.ComputeIsSorted.smt2            |   0.953s  |   0.953s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.Imaps.smt2                      |   2.792s  |   2.792s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.SplitLeft.smt2                  |   1.855s  |   1.855s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.SplitRight.smt2                 |   8.585s  |   8.585s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.CheckWellformed__PackedStringArray.__default.psaSeq.smt2  |   0.410s  |   0.410s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.BinarySearchIndexOfFirstKeyGt.smt2  |   1.252s  |   1.252s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.BinarySearchIndexOfFirstKeyGte.smt2  |   0.893s  |   0.893s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.IndexOfFirstKeyGt.smt2  |   0.534s  |   0.534s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.PsaSuffix.smt2  |   0.423s  |   0.423s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.ToSeq.smt2    |   0.516s  |   0.516s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.psaAppendIAppend.smt2  |   0.536s  |   0.536s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.psaCanAppendI.smt2  |   0.891s  |   0.891s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-LruImpl.i.dfy.Impl__LruImpl.LruImplQueue.Remove.smt2             |  19.486s  |  19.486s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-LruImpl.i.dfy.Impl__LruImpl.__default.lemmaGetRemoveQueueIndex.smt2  |   0.461s  |   0.461s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__TestMutableBtree.__default.SplitChildOfIndex.smt2  |  20.036s  |  20.036s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtreeBulkOperations.i.dfy.Impl__MutableBtreeBulkOperations.__default.CountElements.smt2  |   3.865s  |   3.865s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtreeBulkOperations.i.dfy.Impl__MutableBtreeBulkOperations.__default.ToSeqSubtree.smt2  |  17.981s  |  17.981s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableMapModel.i.dfy.CheckWellformed__MutableMapModel.__default.SimpleIterInc.smt2  |   2.600s  |   2.600s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableMapModel.i.dfy.Impl__MutableMapModel.__default.LemmaReallocIterateResult.smt2  |  16.519s  |  16.519s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallArrayContents.smt2  |   5.596s  |   5.596s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallByteArray.smt2  |   1.661s  |   1.661s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallByteArrayInterior.smt2  |   2.876s  |   2.876s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallTupleContents.smt2  |   4.823s  |   4.823s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__add__mul__div.smt2           |   0.261s  |   0.261s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__div__multiples__vanish__fancy.smt2  |   0.222s  |   0.222s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Math-mul.i.dfy.CheckWellformed__Math____mul__i.__default.mul__recursive.smt2    |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Math-mul.i.dfy.Impl__Math____mul__i.__default.lemma__mul__one__to__one.smt2     |   0.189s  |   0.189s  |   0.000s  | 0.0%|
|d_komodo-verified-allocate_page.gen.dfyCheckWellformed___module.__default.va__lemma__allocate__page.smt2  |  11.376s  |  11.376s  |   0.000s  | 0.0%|
|d_komodo-verified-attest.gen.dfyImpl___module.__default.va__lemma__compute__hmac.smt2       |  20.052s  |  20.052s  |   0.000s  | 0.0%|
|d_komodo-verified-attest_helpers.gen.dfyImpl___module.__default.va__lemma__addrspace__va__for__page__va.smt2  |  20.055s  |  20.055s  |   0.000s  | 0.0%|
|d_komodo-verified-attest_input.gen.dfyCheckWellformed___module.__default.va__lemma__arrange__attestation__input.smt2  |   4.585s  |   4.585s  |   0.000s  | 0.0%|
|d_komodo-verified-attest_input.gen.dfyImpl___module.__default.va__lemma__arrange__attestation__input_split0.smt2  |  20.048s  |  20.048s  |   0.000s  | 0.0%|
|d_komodo-verified-attest_input.gen.dfyImpl___module.__default.va__lemma__arrange__real__measurement__in__memory_split0.smt2  |  20.047s  |  20.047s  |   0.000s  | 0.0%|
|d_komodo-verified-attest_input.gen.dfyImpl___module.__default.va__lemma__arrange__real__measurement__in__memory_split1.smt2  |  20.041s  |  20.041s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.gen.dfyImpl___module.__default.lemma__aligned__sp.smt2              |   7.157s  |   7.157s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.i.dfyCheckWellformed___module.__default.KomExceptionHandlerInvariant.smt2  |   9.417s  |   9.417s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.i.dfyImpl___module.__default.lemma__contentsOfPage__corresponds.smt2  |   3.474s  |   3.474s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.i.dfyImpl___module.__default.lemma__evalMOVSPCLRUC__inner.smt2      |  20.039s  |  20.039s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.i.dfyImpl___module.__default.lemma__onlyDataPagesAreWritable.smt2   |   1.195s  |   1.195s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.i.dfyImpl___module.__default.lemma__userExecutionUpdatesPageDb.smt2  |  20.042s  |  20.042s  |   0.000s  | 0.0%|
|d_komodo-verified-entrybits.i.dfyImpl___module.__default.lemma__sp__bit__helper.smt2        |   0.933s  |   0.933s  |   0.000s  | 0.0%|
|d_komodo-verified-exceptions.i.dfyImpl___module.__default.lemma__PrivInterruptInvariants.smt2  |  20.048s  |  20.048s  |   0.000s  | 0.0%|
|d_komodo-verified-exhandler_state.i.dfyImpl___module.__default.lemma__UserExceptionStateSideEffects.smt2  |  20.049s  |  20.049s  |   0.000s  | 0.0%|
|d_komodo-verified-init_addrspace.gen.dfyImpl___module.__default.va__lemma__init__addrspace.smt2  |  20.057s  |  20.057s  |   0.000s  | 0.0%|
|d_komodo-verified-init_l2ptable.gen.dfyImpl___module.__default.va__lemma__zero__l2__page.smt2  |  20.046s  |  20.046s  |   0.000s  | 0.0%|
|d_komodo-verified-kom_utils.gen.dfyCheckWellformed___module.__default.va__lemma__stack__nonvolatiles.smt2  |   8.217s  |   8.217s  |   0.000s  | 0.0%|
|d_komodo-verified-kom_utils.gen.dfyImpl___module.__default.va__lemma__load__page__type.smt2  |  11.617s  |  11.617s  |   0.000s  | 0.0%|
|d_komodo-verified-kom_utils.gen.dfyImpl___module.__default.va__lemma__unstack__lr.smt2      |   2.920s  |   2.920s  |   0.000s  | 0.0%|
|d_komodo-verified-kom_utils.gen.dfyImpl___module.__default.va__lemma__unstack__nonvolatiles.smt2  |  20.052s  |  20.052s  |   0.000s  | 0.0%|
|d_komodo-verified-kom_utils.gen.dfyImpl___module.__default.va__lemma__unstack__nonvolatiles__except__lr.smt2  |  20.045s  |  20.045s  |   0.000s  | 0.0%|
|d_komodo-verified-kom_utils.gen.dfyImpl___module.__default.va__lemma__update__pagedb__entry.smt2  |  20.053s  |  20.053s  |   0.000s  | 0.0%|
|d_komodo-verified-map_common.gen.dfyImpl___module.__default.va__lemma__is__valid__mapping__target.smt2  |  20.049s  |  20.049s  |   0.000s  | 0.0%|
|d_komodo-verified-map_common.gen.dfyImpl___module.__default.va__lemma__is__valid__mapping__target_k__finish.smt2  |  20.059s  |  20.059s  |   0.000s  | 0.0%|
|d_komodo-verified-map_utils.gen.dfyCheckWellformed___module.__default.va__lemma__kom__smc__map__measure__hash.smt2  |  20.033s  |  20.033s  |   0.000s  | 0.0%|
|d_komodo-verified-map_utils.gen.dfyCheckWellformed___module.__default.va__lemma__kom__smc__map__measure__sha.smt2  |  20.066s  |  20.066s  |   0.000s  | 0.0%|
|d_komodo-verified-map_utils.gen.dfyImpl___module.__default.va__lemma__fetch__l1pte.smt2     |  18.479s  |  18.479s  |   0.000s  | 0.0%|
|d_komodo-verified-mapping.i.dfyImpl___module.__default.lemma__installL1PTEInPageDb__dataPageRefs.smt2  |   2.280s  |   2.280s  |   0.000s  | 0.0%|
|d_komodo-verified-pagedb.i.dfyImpl___module.__default.extractPageDbToAbstract.smt2          |   2.634s  |   2.634s  |   0.000s  | 0.0%|
|d_komodo-verified-pagedb.i.dfyImpl___module.__default.extractPageDbToAbstractOne.smt2       |   3.554s  |   3.554s  |   0.000s  | 0.0%|
|d_komodo-verified-ptables.i.dfyImpl___module.__default.lemma__WritablePages.smt2            |   2.757s  |   2.757s  |   0.000s  | 0.0%|
|d_komodo-verified-ptables.i.dfyImpl___module.__default.lemma__l2tablesmatch.smt2            |   6.743s  |   6.743s  |   0.000s  | 0.0%|
|d_komodo-verified-ptables.i.dfyImpl___module.__default.lemma__ptablesmatch.smt2             |  10.033s  |  10.033s  |   0.000s  | 0.0%|
|d_komodo-verified-ptables.i.dfyImpl___module.__default.lemma__ptablesmatch_split0.smt2      |   5.371s  |   5.371s  |   0.000s  | 0.0%|
|d_komodo-verified-ptebits.i.dfyImpl___module.__default.lemma__nonexec__mapping.smt2         |   7.877s  |   7.877s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__AllPages.smt2   |   4.489s  |   4.489s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__enter__loweq__pdb__not__atkr.smt2  |  20.065s  |  20.065s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__exceptionHandled__atkr.smt2  |  10.468s  |  10.468s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__updateUserPages__conf__not__atkr.smt2  |  20.050s  |  20.050s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__validEnclaveStepPrime__conf__not__atkr__retnondet.smt2  |  20.054s  |  20.054s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-integ_ni_entry.i.dfyImpl___module.__default.lemma__enter__enc__obs__enter.smt2  |  20.032s  |  20.032s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-integ_ni_entry.i.dfyImpl___module.__default.lemma__enter__loweq__pdb__not__obs.smt2  |  20.028s  |  20.028s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-hmac.gen.dfyImpl___module.__default.va__lemma__hmac__inner__prep__hash.smt2  |  20.051s  |  20.051s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-memory-helpers.i.dfyImpl___module.__default.lemma__AddrMemContentsSeq__adds.smt2  |   2.366s  |   2.366s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-sha256.i.dfyImpl___module.__default.lemma__InputHelper.smt2           |   0.575s  |   0.575s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-sha256.s.dfyCheckWellformed___module.__default.K__SHA256.smt2         |   4.658s  |   4.658s  |   0.000s  | 0.0%|
|d_komodo-verified-smcapi.i.dfyImpl___module.__default.kom__smc__map__measure__helper1.smt2  |  20.045s  |  20.045s  |   0.000s  | 0.0%|
|d_komodo-verified-smcapi.i.dfyImpl___module.__default.lemma__sha256__concat.smt2            |   2.482s  |   2.482s  |   0.000s  | 0.0%|
|d_komodo-verified-svc_handlers.gen.dfyCheckWellformed___module.__default.va__lemma__svc__returning__verify__step1.smt2  |  16.590s  |  16.590s  |   0.000s  | 0.0%|
|d_komodo-verified-svc_handlers.gen.dfyImpl___module.__default.va__lemma__svc__returning__default.smt2  |  18.712s  |  18.712s  |   0.000s  | 0.0%|
|d_komodo-verified-verify.gen.dfyImpl___module.__default.va__lemma__compare__memory__to__regs.smt2  |  20.072s  |  20.072s  |   0.000s  | 0.0%|
|d_komodo-verified-verify_input.gen.dfyCheckWellformed___module.__default.lemma__grab__measurement.smt2  |   4.561s  |   4.561s  |   0.000s  | 0.0%|
|d_komodo-verified-verify_input.gen.dfyCheckWellformed___module.__default.lemma__grab__user__words.smt2  |   4.401s  |   4.401s  |   0.000s  | 0.0%|
|d_komodo-verified-verify_input.gen.dfyImpl___module.__default.lemma__grab__measurement.smt2  |  20.050s  |  20.050s  |   0.000s  | 0.0%|
|d_komodo-verified-verify_input.gen.dfyImpl___module.__default.lemma__grab__user__words.smt2  |  20.058s  |  20.058s  |   0.000s  | 0.0%|
|d_komodo-verified-verify_input.gen.dfyImpl___module.__default.va__lemma__arrange__user__words__in__memory.smt2  |  13.490s  |  13.490s  |   0.000s  | 0.0%|
|d_komodo-verified-verify_input.gen.dfyImpl___module.__default.va__lemma__arrange__user__words__in__memory_split0.smt2  |  20.065s  |  20.065s  |   0.000s  | 0.0%|
|d_komodo-verified-verify_input.gen.dfyImpl___module.__default.va__lemma__arrange__verification__input_split0.smt2  |  15.662s  |  15.662s  |   0.000s  | 0.0%|
|d_komodo-verified-verify_input.gen.dfyImpl___module.__default.va__lemma__arrange__verify__measurement__in__memory.smt2  |  10.643s  |  10.643s  |   0.000s  | 0.0%|
|d_komodo-verified-verify_input.gen.dfyImpl___module.__default.va__lemma__arrange__verify__measurement__in__memory_split0.smt2  |  11.199s  |  11.199s  |   0.000s  | 0.0%|
|d_lvbkv-Betree-AsyncBetree.i.dfy.Impl__AsyncBetree.__default.QueryAdvanceChangesLookup.smt2  |   6.181s  |   6.181s  |   0.000s  | 0.0%|
|d_lvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.InitImpliesInv.smt2                |   1.248s  |   1.248s  |   0.000s  | 0.0%|
|d_lvbkv-BlockCacheSystem-BetreeCache.i.dfy.Impl__BetreeCache.__default.BetreeMoveStepPreservesInv.smt2  |  20.049s  |  20.049s  |   0.000s  | 0.0%|
|d_lvbkv-BlockCacheSystem-BetreeSystem.i.dfy.Impl__BetreeSystem.__default.BlockCacheMoveStepPreservesInv.smt2  |  17.502s  |  17.502s  |   0.000s  | 0.0%|
|d_lvbkv-BlockCacheSystem-BetreeSystem_Refines_StatesViewPivotBetree.i.dfy.Impl__BetreeSystem__Refines__StatesViewPivotBetree.__default.BetreeMoveStepRefines.smt2  |  20.058s  |  20.058s  |   0.000s  | 0.0%|
|d_lvbkv-BlockCacheSystem-BlockCache.i.dfy.Impl__BlockCache.__default.DirtyStepPreservesInv.smt2  |   7.395s  |   7.395s  |   0.000s  | 0.0%|
|d_lvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.DiskInternalStepPreservesInv.smt2  |   3.307s  |   3.307s  |   0.000s  | 0.0%|
|d_lvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBytesSplit.smt2  |   0.859s  |   0.859s  |   0.000s  | 0.0%|
|d_lvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeEqJournalBlocks.smt2  |   1.002s  |   1.002s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-GrowModel.i.dfy.Impl__GrowModel.__default.growCorrect.smt2                     |  20.048s  |  20.048s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.FindIndirectionTableLocationAndRequestWrite.smt2  |   9.906s  |   9.906s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-JournalistImpl.i.dfy.Impl__JournalistImpl.Journalist.packageFrozenJournal.smt2  |   0.869s  |   0.869s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-JournalistImpl.i.dfy.Impl__JournalistImpl.Journalist.reallocJournalEntries.smt2  |   0.642s  |   0.642s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.journalRangeFromHasChecksums.smt2  |   0.669s  |   0.669s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.lemma__writeJournalEntries.smt2  |  20.046s  |  20.046s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.writeOntoPreservesSlice.smt2  |   0.457s  |   0.457s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-JournalistParsingImpl.i.dfy.Impl__JournalistParsingImpl.__default.ParseJournalRangeOfBytes.smt2  |   2.230s  |   2.230s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.KeyValSeqToPivots.smt2   |   7.073s  |   7.073s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.bucketsToVal.smt2        |  20.045s  |  20.045s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-MarshallingModel.i.dfy.Impl__MarshallingModel.__default.WeightBucketListLteSize.smt2  |   4.897s  |   4.897s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-NodeImpl.i.dfy.Impl__NodeImpl.Node.BucketsWellMarshalled.smt2                  |   1.796s  |   1.796s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-NodeImpl.i.dfy.Impl__NodeImpl.Node.CutoffNodeAndKeepLeft.smt2                  |   3.474s  |   3.474s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-QueryModel.i.dfy.Impl__QueryModel.__default.AugmentLookup.smt2                 |   4.515s  |   4.515s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-SplitModel.i.dfy.Impl__SplitModel.__default.lemmaChildrenConditionsCutoffNode.smt2  |   2.844s  |   2.844s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-SuccImpl.i.dfy.Impl__SuccImpl.__default.getPathInternal.smt2                   |  17.414s  |  17.414s  |   0.000s  | 0.0%|
|d_lvbkv-MapSpec-TSJ.i.dfy.Impl__TSJ.__default.CrashStepPreservesInv.smt2                    |   0.455s  |   0.455s  |   0.000s  | 0.0%|
|d_lvbkv-MapSpec-TSJ.i.dfy.Impl__TSJ.__default.Move1to2StepPreservesInv.smt2                 |   0.422s  |   0.422s  |   0.000s  | 0.0%|
|d_lvbkv-PivotBetree-PivotBetree.i.dfy.Impl__PivotBetree.__default.GCStepRefines.smt2        |   7.923s  |   7.923s  |   0.000s  | 0.0%|
|d_lvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.Impl__PivotBetreeSpecRefinement.__default.InUpperBoundAndNot.smt2  |   0.999s  |   0.999s  |   0.000s  | 0.0%|
|d_lvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.Impl__PivotBetreeSpecRefinement.__default.MergeChildrenConsistent.smt2  |  20.053s  |  20.053s  |   0.000s  | 0.0%|
|d_lvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.Impl__PivotBetreeSpecRefinement.__default.SplitMergeBuffersChildrenEq.smt2  |   2.893s  |   2.893s  |   0.000s  | 0.0%|
|d_lvbkv-PivotBetree-TSJPivotBetree.i.dfy.Impl__TSJPivotBetree.__default.Move3StepPreservesInv.smt2  |   1.683s  |   1.683s  |   0.000s  | 0.0%|
|d_lvbkv-Versions-CompositeView_Refines_TSJMap.i.dfy.Impl__CompositeView__Refines__TSJMap.__default.CrashRefines.smt2  |   1.623s  |   1.623s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-Arrays.i.dfy.Impl__Arrays.__default.replace1with2.smt2                     |   2.884s  |   2.884s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.bit__or__is__union__uint64.smt2  |   1.033s  |   1.033s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-Sequences.i.dfy.Impl__Sequences.__default.DisjointConcatenation.smt2       |   0.237s  |   0.237s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-mathematics.i.dfy.Impl__Mathematics.__default.DivCeilLT.smt2               |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-mathematics.i.dfy.Impl__Mathematics.__default.PosMulPreservesOrder.smt2    |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-total_order.i.dfy.Impl__Total__Preorder.__default.ExistsBiggestInSet.smt2  |   0.250s  |   0.250s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-total_order_impl.i.dfy.Impl__Total__Order__Impl.__default.ArrayLargestLtPlus1.smt2  |   0.387s  |   0.387s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-total_order_impl.i.dfy.Impl__Total__Order__Impl.__default.ArrayLargestLtePlus1.smt2  |   0.385s  |   0.385s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.CloneSeq.smt2               |   3.186s  |   3.186s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.GetLastKey.smt2             |   1.261s  |   1.261s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.ISeq__replace1with2.smt2    |  19.669s  |  19.669s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.SplitOneInList.smt2         |  14.131s  |  14.131s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.WeightBucketIs.smt2         |   1.332s  |   1.332s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.WeightKeyListIs.smt2        |   2.217s  |   2.217s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.computeWeightOfSeq.smt2     |   2.347s  |   2.347s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.WeightSplitBucketAdditive.smt2  |   0.679s  |   0.679s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-LKMBPKVOps.i.dfy.Impl__LKMBPKVOps.__default.FromPkv.smt2                |  10.042s  |  10.042s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.CheckWellformed__PackedKV.__default.AppendEncodedMessage.smt2  |   0.953s  |   0.953s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.CheckWellformed__PackedKV.__default.psaSeq__Messages.smt2  |   0.838s  |   0.838s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.CheckWellformed__PackedKV.__default.subPkv.smt2          |   1.079s  |   1.079s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.__default.WeightBucketPkv__eq__WeightPkv.smt2  |   7.463s  |   7.463s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.__default.computePivotIndexes.smt2      |   0.997s  |   0.997s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.ComputeValidStringLens.smt2     |   0.871s  |   0.871s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedKVMarshalling.i.dfy.Impl__PackedKVMarshalling.__default.ComputeWF.smt2  |   0.904s  |   0.904s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedKVMarshalling.i.dfy.Impl__PackedKVMarshalling.__default.SizeOfVPackedStringArrayIsKeyListWeight.smt2  |  20.058s  |  20.058s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedStringArray.i.dfy.CheckWellformed__PackedStringArray.__default.psaSeq.smt2  |   0.494s  |   0.494s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.DynamicPsa.appendSeq.smt2  |   6.944s  |   6.944s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.ToSeq.smt2    |   0.517s  |   0.517s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.UniqueRepr.smt2  |   0.621s  |   0.621s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.psaAppendIAppend.smt2  |   0.567s  |   0.567s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.psaAppendSeqAdditive.smt2  |   0.667s  |   0.667s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Checksums-CRC32C_Lemmas.i.dfy.Impl__CRC32C__Lemmas.__default.four__slices.smt2  |   0.359s  |   0.359s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Checksums-CRC32C_Lut.i.dfy.Impl__CRC32C__Lut.__default.reverse__p.smt2          |   3.226s  |   3.226s  |   0.000s  | 0.0%|
|d_lvbkv-lib-DataStructures-KMBtree.i.dfy.Impl__KMBtreeModel.__default.IndexesNonempty.smt2  |   0.550s  |   0.550s  |   0.000s  | 0.0%|
|d_lvbkv-lib-DataStructures-LinearMutableMap.i.dfy.Impl__LinearMutableMap.__default.Probe.smt2  |   9.528s  |   9.528s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallArrayContents.smt2  |   4.636s  |   4.636s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallTupleContents.smt2  |   3.804s  |   3.804s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint32Array.smt2  |   1.017s  |   1.017s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint64Array.smt2  |   1.707s  |   1.707s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Marshalling-Util.i.dfy.Impl__Common____Util__i.__default.seqIntoArrayOpt.smt2   |   0.370s  |   0.370s  |   0.000s  | 0.0%|
|s_komodo-1518.6.smt2                                                                        |  20.633s  |  20.633s  |   0.000s  | 0.0%|
</details>
