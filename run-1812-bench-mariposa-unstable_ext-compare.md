Comparing data and data


# SUMMARY
- LHS tests = 253
- RHS tests = 253
- LHS success = 253  (100.0%)
- RHS success = 253  (100.0%)


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
Z3 commit: bc6c38e7d3424b88a505cacba4b268d0774d4547
Z3 branch: bc6c38e7d3424b88a505cacba4b268d0774d4547
Z3 options: "-T:20"
Z3 inputs: inputs/mariposa/unstable_ext
Z3 commit message: [code-simplifier] Simplify `api_ast.cpp` by removing unreachable branch and stray comment (#9570)

This change simplifies recently touched API code in
`src/api/api_ast.cpp` without altering semantics. It removes an
unreachable error path in `Z3_get_index_value` and deletes an empty
comment in `Z3_mk_rec_func_decl`.

- **`Z3_get_index_value`: remove dead branch**
- After validating `a` is non-null and of kind `AST_VAR`, the conversion
to `var*` is already guaranteed by existing AST casting invariants.
- The redundant null-check/error-return branch was removed, leaving a
direct index return.

- **`Z3_mk_rec_func_decl`: remove noise**
  - Deleted a stray empty `//` line.

```cpp
// before
var* va = to_var(_a);
if (va) {
    return va->get_idx();
}
SET_ERROR_CODE(Z3_INVALID_ARG, nullptr);
return 0;

// after
var* va = to_var(_a);
return va->get_idx();
```

---------

Co-authored-by: copilot-swe-agent[bot] <198982749+Copilot@users.noreply.github.com>
Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: bench-mariposa-unstable_ext
Runner: rise-runner-2
Z3 repo: CanCebeci/z3
Z3 commit: bc6c38e7d3424b88a505cacba4b268d0774d4547
Z3 branch: bc6c38e7d3424b88a505cacba4b268d0774d4547
Z3 options: "-T:20"
Z3 inputs: inputs/mariposa/unstable_ext
Z3 commit message: [code-simplifier] Simplify `api_ast.cpp` by removing unreachable branch and stray comment (#9570)

This change simplifies recently touched API code in
`src/api/api_ast.cpp` without altering semantics. It removes an
unreachable error path in `Z3_get_index_value` and deletes an empty
comment in `Z3_mk_rec_func_decl`.

- **`Z3_get_index_value`: remove dead branch**
- After validating `a` is non-null and of kind `AST_VAR`, the conversion
to `var*` is already guaranteed by existing AST casting invariants.
- The redundant null-check/error-return branch was removed, leaving a
direct index return.

- **`Z3_mk_rec_func_decl`: remove noise**
  - Deleted a stray empty `//` line.

```cpp
// before
var* va = to_var(_a);
if (va) {
    return va->get_idx();
}
SET_ERROR_CODE(Z3_INVALID_ARG, nullptr);
return 0;

// after
var* va = to_var(_a);
return va->get_idx();
```

---------

Co-authored-by: copilot-swe-agent[bot] <198982749+Copilot@users.noreply.github.com>
Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.InitImpliesInv.smt2                |   0.724s  |   0.724s  |   0.000s  | 0.0%|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectPreservesLookups.smt2      |  11.719s  |  11.719s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-JournalInterval.i.dfy.Impl__JournalIntervals.__default.Disk__Journal__append.smt2  |   1.615s  |   1.615s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBlockOfJournalRange.smt2  |   0.542s  |   0.542s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBytesSplit.smt2  |   0.569s  |   0.569s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeEqJournalBlocks.smt2  |   5.366s  |   5.366s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeOfByteSeqGetI.smt2  |   1.059s  |   1.059s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-Marshalling.i.dfy.Impl__Marshalling.__default.pivotTableWeightUpperBound.smt2  |   7.296s  |   7.296s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeeping.smt2    |   9.457s  |   9.457s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeepingNoSuccsUpdate.smt2  |   9.114s  |   9.114s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketGeneratorModel.i.dfy.Impl__BucketGeneratorModel.__default.GenFromBucketStackWithLowerBoundYieldsComposeSeq.smt2  |   3.917s  |   3.917s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.GetSuccessorInBucketStackResult.smt2  |   2.536s  |   2.536s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.ProcessGeneratorResult.smt2  |  20.042s  |  20.042s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterCommitImpl.i.dfy.Impl__CommitterCommitImpl.__default.WriteOutJournal.smt2  |  20.049s  |  20.049s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.CheckWellformed__CommitterCommitModel.__default.WriteOutJournal.smt2  |   2.729s  |   2.729s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.Impl__CommitterCommitModel.__default.WriteOutJournalCorrect.smt2  |   3.463s  |   3.463s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.FindIndirectionTableLocationAndRequestWriteCorrect.smt2  |   6.180s  |   6.180s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.PageInIndirectionTableRespCorrect.smt2   |   4.048s  |   4.048s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.FindRefWithNoLoc.smt2  |  20.065s  |  20.065s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.RemoveRef.smt2  |  20.051s  |  20.051s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.InitImpliesInv.smt2                |   0.724s  |   0.724s  |   0.000s  | 0.0%|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectPreservesLookups.smt2      |  11.719s  |  11.719s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-JournalInterval.i.dfy.Impl__JournalIntervals.__default.Disk__Journal__append.smt2  |   1.615s  |   1.615s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBlockOfJournalRange.smt2  |   0.542s  |   0.542s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBytesSplit.smt2  |   0.569s  |   0.569s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeEqJournalBlocks.smt2  |   5.366s  |   5.366s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeOfByteSeqGetI.smt2  |   1.059s  |   1.059s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-Marshalling.i.dfy.Impl__Marshalling.__default.pivotTableWeightUpperBound.smt2  |   7.296s  |   7.296s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeeping.smt2    |   9.457s  |   9.457s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeepingNoSuccsUpdate.smt2  |   9.114s  |   9.114s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketGeneratorModel.i.dfy.Impl__BucketGeneratorModel.__default.GenFromBucketStackWithLowerBoundYieldsComposeSeq.smt2  |   3.917s  |   3.917s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.GetSuccessorInBucketStackResult.smt2  |   2.536s  |   2.536s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.ProcessGeneratorResult.smt2  |  20.042s  |  20.042s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterCommitImpl.i.dfy.Impl__CommitterCommitImpl.__default.WriteOutJournal.smt2  |  20.049s  |  20.049s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.CheckWellformed__CommitterCommitModel.__default.WriteOutJournal.smt2  |   2.729s  |   2.729s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.Impl__CommitterCommitModel.__default.WriteOutJournalCorrect.smt2  |   3.463s  |   3.463s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.FindIndirectionTableLocationAndRequestWriteCorrect.smt2  |   6.180s  |   6.180s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.PageInIndirectionTableRespCorrect.smt2   |   4.048s  |   4.048s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.FindRefWithNoLoc.smt2  |  20.065s  |  20.065s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.RemoveRef.smt2  |  20.051s  |  20.051s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.InitImpliesInv.smt2                |   0.724s  |   0.724s  |   0.000s  | 0.0%|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectPreservesLookups.smt2      |  11.719s  |  11.719s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-JournalInterval.i.dfy.Impl__JournalIntervals.__default.Disk__Journal__append.smt2  |   1.615s  |   1.615s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBlockOfJournalRange.smt2  |   0.542s  |   0.542s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBytesSplit.smt2  |   0.569s  |   0.569s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeEqJournalBlocks.smt2  |   5.366s  |   5.366s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeOfByteSeqGetI.smt2  |   1.059s  |   1.059s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-Marshalling.i.dfy.Impl__Marshalling.__default.pivotTableWeightUpperBound.smt2  |   7.296s  |   7.296s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeeping.smt2    |   9.457s  |   9.457s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeepingNoSuccsUpdate.smt2  |   9.114s  |   9.114s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketGeneratorModel.i.dfy.Impl__BucketGeneratorModel.__default.GenFromBucketStackWithLowerBoundYieldsComposeSeq.smt2  |   3.917s  |   3.917s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.GetSuccessorInBucketStackResult.smt2  |   2.536s  |   2.536s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.ProcessGeneratorResult.smt2  |  20.042s  |  20.042s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterCommitImpl.i.dfy.Impl__CommitterCommitImpl.__default.WriteOutJournal.smt2  |  20.049s  |  20.049s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.CheckWellformed__CommitterCommitModel.__default.WriteOutJournal.smt2  |   2.729s  |   2.729s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.Impl__CommitterCommitModel.__default.WriteOutJournalCorrect.smt2  |   3.463s  |   3.463s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.FindIndirectionTableLocationAndRequestWriteCorrect.smt2  |   6.180s  |   6.180s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.PageInIndirectionTableRespCorrect.smt2   |   4.048s  |   4.048s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.FindRefWithNoLoc.smt2  |  20.065s  |  20.065s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.RemoveRef.smt2  |  20.051s  |  20.051s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.InitImpliesInv.smt2                |   0.724s  |   0.724s  |   0.000s  | 0.0%|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectPreservesLookups.smt2      |  11.719s  |  11.719s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-JournalInterval.i.dfy.Impl__JournalIntervals.__default.Disk__Journal__append.smt2  |   1.615s  |   1.615s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBlockOfJournalRange.smt2  |   0.542s  |   0.542s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBytesSplit.smt2  |   0.569s  |   0.569s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeEqJournalBlocks.smt2  |   5.366s  |   5.366s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeOfByteSeqGetI.smt2  |   1.059s  |   1.059s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-Marshalling.i.dfy.Impl__Marshalling.__default.pivotTableWeightUpperBound.smt2  |   7.296s  |   7.296s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeeping.smt2    |   9.457s  |   9.457s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeepingNoSuccsUpdate.smt2  |   9.114s  |   9.114s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketGeneratorModel.i.dfy.Impl__BucketGeneratorModel.__default.GenFromBucketStackWithLowerBoundYieldsComposeSeq.smt2  |   3.917s  |   3.917s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.GetSuccessorInBucketStackResult.smt2  |   2.536s  |   2.536s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.ProcessGeneratorResult.smt2  |  20.042s  |  20.042s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterCommitImpl.i.dfy.Impl__CommitterCommitImpl.__default.WriteOutJournal.smt2  |  20.049s  |  20.049s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.CheckWellformed__CommitterCommitModel.__default.WriteOutJournal.smt2  |   2.729s  |   2.729s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.Impl__CommitterCommitModel.__default.WriteOutJournalCorrect.smt2  |   3.463s  |   3.463s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.FindIndirectionTableLocationAndRequestWriteCorrect.smt2  |   6.180s  |   6.180s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.PageInIndirectionTableRespCorrect.smt2   |   4.048s  |   4.048s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.FindRefWithNoLoc.smt2  |  20.065s  |  20.065s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.RemoveRef.smt2  |  20.051s  |  20.051s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|s_komodo-1518.6.smt2                                                                       |  20.561s |3538.0MiB|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.FindRefWithNoLoc.smt2 |  20.065s |179.0MiB|
|d_komodo-verified-verify.gen.dfyImpl___module.__default.va__lemma__compare__memory__to__regs.smt2 |  20.065s |366.0MiB|
|d_komodo-verified-map_common.gen.dfyImpl___module.__default.va__lemma__is__valid__mapping__target.smt2 |  20.062s |231.0MiB|
|d_komodo-verified-sha-hmac.gen.dfyImpl___module.__default.va__lemma__hmac__inner__prep__hash.smt2 |  20.062s |247.0MiB|
|d_komodo-verified-sha-sha256.i.dfyImpl___module.__default.SHA__padding__words2bytes.smt2   |  20.061s |200.0MiB|
|d_komodo-verified-init_l2ptable.gen.dfyImpl___module.__default.va__lemma__init__l2ptable__success.smt2 |  20.061s |237.0MiB|
|d_komodo-verified-attest_helpers.gen.dfyImpl___module.__default.va__lemma__addrspace__va__for__page__va.smt2 |  20.060s |144.0MiB|
|d_komodo-verified-map_utils.gen.dfyCheckWellformed___module.__default.va__lemma__kom__smc__map__measure__hash.smt2 |  20.060s |208.0MiB|
|d_komodo-verified-attest_input.gen.dfyImpl___module.__default.va__lemma__arrange__attestation__input_split0.smt2 |  20.059s |264.0MiB|
|d_komodo-verified-svc_handlers.gen.dfyImpl___module.__default.va__lemma__svc__returning__default.smt2 |  20.059s |192.0MiB|
|d_komodo-verified-svc_handlers.gen.dfyImpl___module.__default.va__lemma__svc__map__data__success.smt2 |  20.059s |195.0MiB|
|d_komodo-verified-entry.i.dfyImpl___module.__default.lemma__userExecutionUpdatesPageDb.smt2 |  20.058s |230.0MiB|
|d_komodo-verified-kom_utils.gen.dfyImpl___module.__default.va__lemma__unstack__nonvolatiles__except__lr.smt2 |  20.058s |157.0MiB|
|d_komodo-verified-attest_input.gen.dfyImpl___module.__default.va__lemma__arrange__real__measurement__in__memory_split0.smt2 |  20.057s |133.0MiB|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__enter__loweq__pdb__not__atkr.smt2 |  20.056s |196.0MiB|
|d_komodo-verified-map_common.gen.dfyImpl___module.__default.va__lemma__is__valid__mapping__target_k__finish.smt2 |  20.055s |190.0MiB|
|d_lvbkv-lib-Buckets-PackedKVMarshalling.i.dfy.Impl__PackedKVMarshalling.__default.SizeOfVPackedStringArrayIsKeyListWeight.smt2 |  20.054s |177.0MiB|
|d_lvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.Impl__PivotBetreeSpecRefinement.__default.MergeChildrenConsistent.smt2 |  20.054s |192.0MiB|
|d_lvbkv-lib-Buckets-LKMBPKVOps.i.dfy.Impl__LKMBPKVOps.__default.IsKeyMessageTreeInheritance.smt2 |  20.054s |199.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|s_komodo-1518.6.smt2                                                                       |  20.561s |3538.0MiB|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.FindRefWithNoLoc.smt2 |  20.065s |179.0MiB|
|d_komodo-verified-verify.gen.dfyImpl___module.__default.va__lemma__compare__memory__to__regs.smt2 |  20.065s |366.0MiB|
|d_komodo-verified-map_common.gen.dfyImpl___module.__default.va__lemma__is__valid__mapping__target.smt2 |  20.062s |231.0MiB|
|d_komodo-verified-sha-hmac.gen.dfyImpl___module.__default.va__lemma__hmac__inner__prep__hash.smt2 |  20.062s |247.0MiB|
|d_komodo-verified-sha-sha256.i.dfyImpl___module.__default.SHA__padding__words2bytes.smt2   |  20.061s |200.0MiB|
|d_komodo-verified-init_l2ptable.gen.dfyImpl___module.__default.va__lemma__init__l2ptable__success.smt2 |  20.061s |237.0MiB|
|d_komodo-verified-attest_helpers.gen.dfyImpl___module.__default.va__lemma__addrspace__va__for__page__va.smt2 |  20.060s |144.0MiB|
|d_komodo-verified-map_utils.gen.dfyCheckWellformed___module.__default.va__lemma__kom__smc__map__measure__hash.smt2 |  20.060s |208.0MiB|
|d_komodo-verified-attest_input.gen.dfyImpl___module.__default.va__lemma__arrange__attestation__input_split0.smt2 |  20.059s |264.0MiB|
|d_komodo-verified-svc_handlers.gen.dfyImpl___module.__default.va__lemma__svc__returning__default.smt2 |  20.059s |192.0MiB|
|d_komodo-verified-svc_handlers.gen.dfyImpl___module.__default.va__lemma__svc__map__data__success.smt2 |  20.059s |195.0MiB|
|d_komodo-verified-entry.i.dfyImpl___module.__default.lemma__userExecutionUpdatesPageDb.smt2 |  20.058s |230.0MiB|
|d_komodo-verified-kom_utils.gen.dfyImpl___module.__default.va__lemma__unstack__nonvolatiles__except__lr.smt2 |  20.058s |157.0MiB|
|d_komodo-verified-attest_input.gen.dfyImpl___module.__default.va__lemma__arrange__real__measurement__in__memory_split0.smt2 |  20.057s |133.0MiB|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__enter__loweq__pdb__not__atkr.smt2 |  20.056s |196.0MiB|
|d_komodo-verified-map_common.gen.dfyImpl___module.__default.va__lemma__is__valid__mapping__target_k__finish.smt2 |  20.055s |190.0MiB|
|d_lvbkv-lib-Buckets-PackedKVMarshalling.i.dfy.Impl__PackedKVMarshalling.__default.SizeOfVPackedStringArrayIsKeyListWeight.smt2 |  20.054s |177.0MiB|
|d_lvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.Impl__PivotBetreeSpecRefinement.__default.MergeChildrenConsistent.smt2 |  20.054s |192.0MiB|
|d_lvbkv-lib-Buckets-LKMBPKVOps.i.dfy.Impl__LKMBPKVOps.__default.IsKeyMessageTreeInheritance.smt2 |  20.054s |199.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.InitImpliesInv.smt2                |50.608MiB|50.608MiB|0B| 0.0%|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectPreservesLookups.smt2      |95.112MiB|95.112MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-JournalInterval.i.dfy.Impl__JournalIntervals.__default.Disk__Journal__append.smt2  |35.276MiB|35.276MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBlockOfJournalRange.smt2  |30.936MiB|30.936MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBytesSplit.smt2  |31.396MiB|31.396MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeEqJournalBlocks.smt2  |57.052MiB|57.052MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeOfByteSeqGetI.smt2  |35.808MiB|35.808MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-Marshalling.i.dfy.Impl__Marshalling.__default.pivotTableWeightUpperBound.smt2  |134.0MiB|134.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeeping.smt2    |169.0MiB|169.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeepingNoSuccsUpdate.smt2  |169.0MiB|169.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketGeneratorModel.i.dfy.Impl__BucketGeneratorModel.__default.GenFromBucketStackWithLowerBoundYieldsComposeSeq.smt2  |58.88MiB|58.88MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.GetSuccessorInBucketStackResult.smt2  |55.676MiB|55.676MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.ProcessGeneratorResult.smt2  |104.0MiB|104.0MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterCommitImpl.i.dfy.Impl__CommitterCommitImpl.__default.WriteOutJournal.smt2  |171.0MiB|171.0MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.CheckWellformed__CommitterCommitModel.__default.WriteOutJournal.smt2  |96.136MiB|96.136MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.Impl__CommitterCommitModel.__default.WriteOutJournalCorrect.smt2  |109.0MiB|109.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.FindIndirectionTableLocationAndRequestWriteCorrect.smt2  |107.0MiB|107.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.PageInIndirectionTableRespCorrect.smt2   |98.0MiB|98.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.FindRefWithNoLoc.smt2  |179.0MiB|179.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.RemoveRef.smt2  |182.0MiB|182.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.InitImpliesInv.smt2                |50.608MiB|50.608MiB|0B| 0.0%|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectPreservesLookups.smt2      |95.112MiB|95.112MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-JournalInterval.i.dfy.Impl__JournalIntervals.__default.Disk__Journal__append.smt2  |35.276MiB|35.276MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBlockOfJournalRange.smt2  |30.936MiB|30.936MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBytesSplit.smt2  |31.396MiB|31.396MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeEqJournalBlocks.smt2  |57.052MiB|57.052MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeOfByteSeqGetI.smt2  |35.808MiB|35.808MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-Marshalling.i.dfy.Impl__Marshalling.__default.pivotTableWeightUpperBound.smt2  |134.0MiB|134.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeeping.smt2    |169.0MiB|169.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeepingNoSuccsUpdate.smt2  |169.0MiB|169.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketGeneratorModel.i.dfy.Impl__BucketGeneratorModel.__default.GenFromBucketStackWithLowerBoundYieldsComposeSeq.smt2  |58.88MiB|58.88MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.GetSuccessorInBucketStackResult.smt2  |55.676MiB|55.676MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.ProcessGeneratorResult.smt2  |104.0MiB|104.0MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterCommitImpl.i.dfy.Impl__CommitterCommitImpl.__default.WriteOutJournal.smt2  |171.0MiB|171.0MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.CheckWellformed__CommitterCommitModel.__default.WriteOutJournal.smt2  |96.136MiB|96.136MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.Impl__CommitterCommitModel.__default.WriteOutJournalCorrect.smt2  |109.0MiB|109.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.FindIndirectionTableLocationAndRequestWriteCorrect.smt2  |107.0MiB|107.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.PageInIndirectionTableRespCorrect.smt2   |98.0MiB|98.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.FindRefWithNoLoc.smt2  |179.0MiB|179.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.RemoveRef.smt2  |182.0MiB|182.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.InitImpliesInv.smt2                |50.608MiB|50.608MiB|0B| 0.0%|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectPreservesLookups.smt2      |95.112MiB|95.112MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-JournalInterval.i.dfy.Impl__JournalIntervals.__default.Disk__Journal__append.smt2  |35.276MiB|35.276MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBlockOfJournalRange.smt2  |30.936MiB|30.936MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBytesSplit.smt2  |31.396MiB|31.396MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeEqJournalBlocks.smt2  |57.052MiB|57.052MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeOfByteSeqGetI.smt2  |35.808MiB|35.808MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-Marshalling.i.dfy.Impl__Marshalling.__default.pivotTableWeightUpperBound.smt2  |134.0MiB|134.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeeping.smt2    |169.0MiB|169.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeepingNoSuccsUpdate.smt2  |169.0MiB|169.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketGeneratorModel.i.dfy.Impl__BucketGeneratorModel.__default.GenFromBucketStackWithLowerBoundYieldsComposeSeq.smt2  |58.88MiB|58.88MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.GetSuccessorInBucketStackResult.smt2  |55.676MiB|55.676MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.ProcessGeneratorResult.smt2  |104.0MiB|104.0MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterCommitImpl.i.dfy.Impl__CommitterCommitImpl.__default.WriteOutJournal.smt2  |171.0MiB|171.0MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.CheckWellformed__CommitterCommitModel.__default.WriteOutJournal.smt2  |96.136MiB|96.136MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.Impl__CommitterCommitModel.__default.WriteOutJournalCorrect.smt2  |109.0MiB|109.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.FindIndirectionTableLocationAndRequestWriteCorrect.smt2  |107.0MiB|107.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.PageInIndirectionTableRespCorrect.smt2   |98.0MiB|98.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.FindRefWithNoLoc.smt2  |179.0MiB|179.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.RemoveRef.smt2  |182.0MiB|182.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.InitImpliesInv.smt2                |50.608MiB|50.608MiB|0B| 0.0%|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectPreservesLookups.smt2      |95.112MiB|95.112MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-JournalInterval.i.dfy.Impl__JournalIntervals.__default.Disk__Journal__append.smt2  |35.276MiB|35.276MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBlockOfJournalRange.smt2  |30.936MiB|30.936MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBytesSplit.smt2  |31.396MiB|31.396MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeEqJournalBlocks.smt2  |57.052MiB|57.052MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeOfByteSeqGetI.smt2  |35.808MiB|35.808MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-Marshalling.i.dfy.Impl__Marshalling.__default.pivotTableWeightUpperBound.smt2  |134.0MiB|134.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeeping.smt2    |169.0MiB|169.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeepingNoSuccsUpdate.smt2  |169.0MiB|169.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketGeneratorModel.i.dfy.Impl__BucketGeneratorModel.__default.GenFromBucketStackWithLowerBoundYieldsComposeSeq.smt2  |58.88MiB|58.88MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.GetSuccessorInBucketStackResult.smt2  |55.676MiB|55.676MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.ProcessGeneratorResult.smt2  |104.0MiB|104.0MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterCommitImpl.i.dfy.Impl__CommitterCommitImpl.__default.WriteOutJournal.smt2  |171.0MiB|171.0MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.CheckWellformed__CommitterCommitModel.__default.WriteOutJournal.smt2  |96.136MiB|96.136MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.Impl__CommitterCommitModel.__default.WriteOutJournalCorrect.smt2  |109.0MiB|109.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.FindIndirectionTableLocationAndRequestWriteCorrect.smt2  |107.0MiB|107.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.PageInIndirectionTableRespCorrect.smt2   |98.0MiB|98.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.FindRefWithNoLoc.smt2  |179.0MiB|179.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.RemoveRef.smt2  |182.0MiB|182.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|s_komodo-1518.6.smt2                                                                       |  20.561s |3538.0MiB|
|d_komodo-verified-verify.gen.dfyImpl___module.__default.va__lemma__compare__memory__to__regs.smt2 |  20.065s |366.0MiB|
|d_komodo-verified-verify_input.gen.dfyImpl___module.__default.va__lemma__arrange__verification__input_split0.smt2 |  11.956s |268.0MiB|
|d_komodo-verified-attest_input.gen.dfyImpl___module.__default.va__lemma__arrange__attestation__input_split0.smt2 |  20.059s |264.0MiB|
|d_komodo-verified-sha-hmac.gen.dfyImpl___module.__default.va__lemma__hmac__inner__prep__hash.smt2 |  20.062s |247.0MiB|
|d_komodo-verified-init_l2ptable.gen.dfyImpl___module.__default.va__lemma__init__l2ptable__success.smt2 |  20.061s |237.0MiB|
|d_komodo-verified-map_common.gen.dfyImpl___module.__default.va__lemma__is__valid__mapping__target.smt2 |  20.062s |231.0MiB|
|d_komodo-verified-entry.i.dfyImpl___module.__default.lemma__userExecutionUpdatesPageDb.smt2 |  20.058s |230.0MiB|
|d_komodo-verified-verify_input.gen.dfyImpl___module.__default.va__lemma__arrange__user__words__in__memory_split0.smt2 |  17.908s |227.0MiB|
|s_komodo-1557.3.smt2                                                                       |  20.051s |221.0MiB|
|d_komodo-verified-init_l2ptable.gen.dfyImpl___module.__default.va__lemma__zero__l2__page.smt2 |  20.051s |218.0MiB|
|d_komodo-verified-map_utils.gen.dfyCheckWellformed___module.__default.va__lemma__kom__smc__map__measure__sha.smt2 |  20.049s |218.0MiB|
|d_komodo-verified-init_addrspace.gen.dfyImpl___module.__default.va__lemma__init__addrspace.smt2 |  20.054s |216.0MiB|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__updateUserPages__conf__not__atkr.smt2 |  20.053s |214.0MiB|
|d_komodo-verified-map_utils.gen.dfyCheckWellformed___module.__default.va__lemma__kom__smc__map__measure__hash.smt2 |  20.060s |208.0MiB|
|d_komodo-verified-sha-sha256.i.dfyImpl___module.__default.SHA__padding__words2bytes.smt2   |  20.061s |200.0MiB|
|d_lvbkv-lib-Buckets-LKMBPKVOps.i.dfy.Impl__LKMBPKVOps.__default.IsKeyMessageTreeInheritance.smt2 |  20.054s |199.0MiB|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__enter__loweq__pdb__not__atkr.smt2 |  20.056s |196.0MiB|
|d_komodo-verified-svc_handlers.gen.dfyImpl___module.__default.va__lemma__svc__map__data__success.smt2 |  20.059s |195.0MiB|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.__default.MergeToChildrenIter.smt2     |  20.051s |195.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|s_komodo-1518.6.smt2                                                                       |  20.561s |3538.0MiB|
|d_komodo-verified-verify.gen.dfyImpl___module.__default.va__lemma__compare__memory__to__regs.smt2 |  20.065s |366.0MiB|
|d_komodo-verified-verify_input.gen.dfyImpl___module.__default.va__lemma__arrange__verification__input_split0.smt2 |  11.956s |268.0MiB|
|d_komodo-verified-attest_input.gen.dfyImpl___module.__default.va__lemma__arrange__attestation__input_split0.smt2 |  20.059s |264.0MiB|
|d_komodo-verified-sha-hmac.gen.dfyImpl___module.__default.va__lemma__hmac__inner__prep__hash.smt2 |  20.062s |247.0MiB|
|d_komodo-verified-init_l2ptable.gen.dfyImpl___module.__default.va__lemma__init__l2ptable__success.smt2 |  20.061s |237.0MiB|
|d_komodo-verified-map_common.gen.dfyImpl___module.__default.va__lemma__is__valid__mapping__target.smt2 |  20.062s |231.0MiB|
|d_komodo-verified-entry.i.dfyImpl___module.__default.lemma__userExecutionUpdatesPageDb.smt2 |  20.058s |230.0MiB|
|d_komodo-verified-verify_input.gen.dfyImpl___module.__default.va__lemma__arrange__user__words__in__memory_split0.smt2 |  17.908s |227.0MiB|
|s_komodo-1557.3.smt2                                                                       |  20.051s |221.0MiB|
|d_komodo-verified-init_l2ptable.gen.dfyImpl___module.__default.va__lemma__zero__l2__page.smt2 |  20.051s |218.0MiB|
|d_komodo-verified-map_utils.gen.dfyCheckWellformed___module.__default.va__lemma__kom__smc__map__measure__sha.smt2 |  20.049s |218.0MiB|
|d_komodo-verified-init_addrspace.gen.dfyImpl___module.__default.va__lemma__init__addrspace.smt2 |  20.054s |216.0MiB|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__updateUserPages__conf__not__atkr.smt2 |  20.053s |214.0MiB|
|d_komodo-verified-map_utils.gen.dfyCheckWellformed___module.__default.va__lemma__kom__smc__map__measure__hash.smt2 |  20.060s |208.0MiB|
|d_komodo-verified-sha-sha256.i.dfyImpl___module.__default.SHA__padding__words2bytes.smt2   |  20.061s |200.0MiB|
|d_lvbkv-lib-Buckets-LKMBPKVOps.i.dfy.Impl__LKMBPKVOps.__default.IsKeyMessageTreeInheritance.smt2 |  20.054s |199.0MiB|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__enter__loweq__pdb__not__atkr.smt2 |  20.056s |196.0MiB|
|d_komodo-verified-svc_handlers.gen.dfyImpl___module.__default.va__lemma__svc__map__data__success.smt2 |  20.059s |195.0MiB|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.__default.MergeToChildrenIter.smt2     |  20.051s |195.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.InitImpliesInv.smt2                |   0.724s  |   0.724s  |   0.000s  | 0.0%|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectPreservesLookups.smt2      |  11.719s  |  11.719s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-JournalInterval.i.dfy.Impl__JournalIntervals.__default.Disk__Journal__append.smt2  |   1.615s  |   1.615s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBlockOfJournalRange.smt2  |   0.542s  |   0.542s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBytesSplit.smt2  |   0.569s  |   0.569s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeEqJournalBlocks.smt2  |   5.366s  |   5.366s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeOfByteSeqGetI.smt2  |   1.059s  |   1.059s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-Marshalling.i.dfy.Impl__Marshalling.__default.pivotTableWeightUpperBound.smt2  |   7.296s  |   7.296s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeeping.smt2    |   9.457s  |   9.457s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeepingNoSuccsUpdate.smt2  |   9.114s  |   9.114s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketGeneratorModel.i.dfy.Impl__BucketGeneratorModel.__default.GenFromBucketStackWithLowerBoundYieldsComposeSeq.smt2  |   3.917s  |   3.917s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.GetSuccessorInBucketStackResult.smt2  |   2.536s  |   2.536s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.ProcessGeneratorResult.smt2  |  20.042s  |  20.042s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterCommitImpl.i.dfy.Impl__CommitterCommitImpl.__default.WriteOutJournal.smt2  |  20.049s  |  20.049s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.CheckWellformed__CommitterCommitModel.__default.WriteOutJournal.smt2  |   2.729s  |   2.729s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.Impl__CommitterCommitModel.__default.WriteOutJournalCorrect.smt2  |   3.463s  |   3.463s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.FindIndirectionTableLocationAndRequestWriteCorrect.smt2  |   6.180s  |   6.180s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.PageInIndirectionTableRespCorrect.smt2   |   4.048s  |   4.048s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.FindRefWithNoLoc.smt2  |  20.065s  |  20.065s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.RemoveRef.smt2  |  20.051s  |  20.051s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.CheckWellformed__IndirectionTableModel.__default.UpdateAndRemoveLoc.smt2  |   6.327s  |   6.327s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.Impl__IndirectionTableModel.__default.LemmaRemoveRefStuff.smt2  |  18.867s  |  18.867s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistImpl.i.dfy.Impl__JournalistImpl.Journalist.parseJournals.smt2        |   1.654s  |   1.654s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.journalRangeFromHasChecksums.smt2  |   0.665s  |   0.665s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.lemma__writeJournalEntries.smt2  |   8.460s  |   8.460s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.parseEntriesFromHasEntriesI.smt2  |   8.203s  |   8.203s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.parsesFromStuff.smt2  |   0.733s  |   0.733s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.freeze.smt2   |   1.240s  |   1.240s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.packageFrozenJournal.smt2  |   1.004s  |   1.004s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.packageInMemoryJournal.smt2  |   1.077s  |   1.077s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistParsingImpl.i.dfy.Impl__JournalistParsingImpl.__default.ParseJournalRangeOfBytes.smt2  |   1.092s  |   1.092s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.strictlySortedKeySeqToVal.smt2  |  16.575s  |  16.575s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-NodeImpl.i.dfy.Impl__NodeImpl.Node.__ctor.smt2                                 |   4.483s  |   4.483s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-NodeModel.i.dfy.Impl__NodeModel.__default.CutoffNodeAndKeepRightCorrect.smt2   |   2.513s  |   2.513s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-SuccImpl.i.dfy.Impl__SuccImpl.__default.getPath.smt2                           |  18.346s  |  18.346s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-SuccModel.i.dfy.Impl__SuccModel.__default.lemmaGetPathResult.smt2              |  13.889s  |  13.889s  |   0.000s  | 0.0%|
|d_fvbkv-MapSpec-TSJ.i.dfy.Impl__TSJ.__default.CrashStepPreservesInv.smt2                    |   0.406s  |   0.406s  |   0.000s  | 0.0%|
|d_fvbkv-MapSpec-TSJ.i.dfy.Impl__TSJ.__default.Move1to2StepPreservesInv.smt2                 |   0.439s  |   0.439s  |   0.000s  | 0.0%|
|d_fvbkv-MapSpec-TSJMap_Refines_ThreeStateVersionedMap.i.dfy.Impl__TSJMap__Refines__ThreeStateVersionedMap.__default.RefinesReplay.smt2  |   6.044s  |   6.044s  |   0.000s  | 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.Impl__PivotBetreeSpec.__default.CutoffNodeCorrect.smt2  |   1.069s  |   1.069s  |   0.000s  | 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.Impl__PivotBetreeSpecRefinement.__default.InUpperBoundAndNot.smt2  |   0.920s  |   0.920s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-Arrays.i.dfy.Impl__Arrays.__default.replace1with2.smt2                     |   0.449s  |   0.449s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.all__in__set__implies__all1s__uint64.smt2  |   8.154s  |   8.154s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-Multisets.i.dfy.Impl__Multisets.__default.ApplyAdditive.smt2               |   1.909s  |   1.909s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-Multisets.i.dfy.Impl__Multisets.__default.FoldSeqRemove.smt2               |   0.301s  |   0.301s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-sequences.i.dfy.Impl__Sequences.__default.DisjointConcatenation.smt2       |   0.242s  |   0.242s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-total_order.i.dfy.Impl__Integer__Order.__default.FlattenStrictlySorted.smt2  |   0.276s  |   0.276s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-total_order_impl.i.dfy.Impl__Total__Order__Impl.__default.ArrayLargestLtePlus1Linear.smt2  |   0.329s  |   0.329s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.CloneSeq.smt2               |  20.044s  |  20.044s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.ISeqInduction.smt2          |   1.025s  |   1.025s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.ISeq__replace1with2.smt2    |  20.050s  |  20.050s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.__default.PartialFlush.smt2           |  20.053s  |  20.053s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.__default.pkvList2BucketList.smt2     |  10.120s  |  10.120s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketModel.i.dfy.Impl__BucketModel.__default.BucketListItemFlush__eq.smt2  |   0.783s  |   0.783s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketModel.i.dfy.Impl__BucketModel.__default.mergeToChildrenIterCorrect.smt2  |  20.050s  |  20.050s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketModel.i.dfy.Impl__BucketModel.__default.mergeToOneOneChild__eq__BucketList.smt2  |   6.512s  |   6.512s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketModel.i.dfy.Impl__BucketModel.__default.mergeToOneOneChild__eq__topBotAccMerge.smt2  |  20.045s  |  20.045s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.ImageEquiv.smt2       |   0.592s  |   0.592s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.ImageIntersect.smt2   |   0.723s  |   0.723s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.ImageSubset.smt2      |   0.570s  |   0.570s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.SplitBucketImage.smt2  |   0.735s  |   0.735s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.WeightBucketListItemFlush.smt2  |   1.057s  |   1.057s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.WeightBucketListItemFlushInner.smt2  |  10.423s  |  10.423s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.WeightSplitBucketInListLe.smt2  |   1.253s  |   1.253s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.WeightWellMarshalledListPointwiseLe.smt2  |   1.592s  |   1.592s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketsLib.i.dfy.Impl__BucketsLib.__default.BInternalPreWFWellMarshalled.smt2  |   4.217s  |   4.217s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketsLib.i.dfy.Impl__BucketsLib.__default.BInternalWFBucket.smt2      |   7.219s  |   7.219s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketsLib.i.dfy.Impl__BucketsLib.__default.GetJoinBucketListEq.smt2    |   3.331s  |   3.331s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketsLib.i.dfy.Impl__BucketsLib.__default.SortedSeqOfKeyValueHasKey.smt2  |   0.603s  |   0.603s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketsLib.i.dfy.Impl__BucketsLib.__default.SplitBucketOnPivotsAt.smt2  |   3.692s  |   3.692s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketsLib.i.dfy.Impl__BucketsLib.__default.WFProperMergeBucketsInList.smt2  |   1.206s  |   1.206s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketsLib.i.dfy.Impl__BucketsLib.__default.WFProperSplitBucketInList.smt2  |   1.231s  |   1.231s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-KMBPKVOps.i.dfy.Impl__KMBPKVOps.__default.FromPkv.smt2                  |  17.156s  |  17.156s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.CheckWellformed__DynamicPkv.__default.PSAPopFrontWeight.smt2  |   0.903s  |   0.903s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.CheckWellformed__DynamicPkv.__default.PSAPopFrontWeightSuffix.smt2  |   0.935s  |   0.935s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.CheckWellformed__PackedKV.__default.subPkv.smt2          |   2.087s  |   2.087s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.DynamicPkv.Append.smt2                  |   6.136s  |   6.136s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.__default.IMessagesSlice.smt2           |   3.098s  |   3.098s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.__default.MergeToChildrenIter.smt2      |  20.051s  |  20.051s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.__default.PSAPopFrontWeight.smt2        |   2.009s  |   2.009s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.__default.PSAPopFrontWeightSuffix.smt2  |   1.309s  |   1.309s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.__default.WeightBucketPkv__eq__WeightPkv.smt2  |   2.207s  |   2.207s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.ComputeIsSorted.smt2            |   0.992s  |   0.992s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.Imaps.smt2                      |   2.416s  |   2.416s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.SplitLeft.smt2                  |   1.966s  |   1.966s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.SplitRight.smt2                 |  10.448s  |  10.448s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKVMarshalling.i.dfy.Impl__PackedKVMarshalling.__default.SizeOfVPackedStringArrayIsMessageListWeight.smt2  |  10.285s  |  10.285s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.CheckWellformed__PackedStringArray.__default.psaSeq.smt2  |   0.413s  |   0.413s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.BinarySearchIndexOfFirstKeyGt.smt2  |   1.194s  |   1.194s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.BinarySearchIndexOfFirstKeyGte.smt2  |   0.875s  |   0.875s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.IndexOfFirstKeyGt.smt2  |   0.505s  |   0.505s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.PsaSuffix.smt2  |   0.430s  |   0.430s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.ToSeq.smt2    |   0.554s  |   0.554s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.psaAppendIAppend.smt2  |   0.499s  |   0.499s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.psaCanAppendI.smt2  |   0.869s  |   0.869s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-KMBtree.i.dfy.Impl__KMBtree.__default.SplitChildOfIndex.smt2     |  20.049s  |  20.049s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-LruImpl.i.dfy.Impl__LruImpl.LruImplQueue.Remove.smt2             |  20.045s  |  20.045s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-LruImpl.i.dfy.Impl__LruImpl.__default.lemmaGetRemoveQueueIndex.smt2  |   0.414s  |   0.414s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__TestMutableBtree.__default.SplitChildOfIndex.smt2  |  20.046s  |  20.046s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtreeBulkOperations.i.dfy.Impl__MutableBtreeBulkOperations.__default.CountElements.smt2  |   3.935s  |   3.935s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtreeBulkOperations.i.dfy.Impl__MutableBtreeBulkOperations.__default.ToSeqSubtree.smt2  |  16.842s  |  16.842s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableMapModel.i.dfy.CheckWellformed__MutableMapModel.__default.SimpleIterInc.smt2  |   2.877s  |   2.877s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableMapModel.i.dfy.Impl__MutableMapModel.__default.LemmaProbeResult.smt2  |  20.035s  |  20.035s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableMapModel.i.dfy.Impl__MutableMapModel.__default.LemmaReallocIterateResult.smt2  |  18.419s  |  18.419s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallArrayContents.smt2  |   6.124s  |   6.124s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallByteArray.smt2  |   1.219s  |   1.219s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallByteArrayInterior.smt2  |   4.586s  |   4.586s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallTupleContents.smt2  |   4.917s  |   4.917s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__add__mul__div.smt2           |   0.234s  |   0.234s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__div__multiples__vanish__fancy.smt2  |   0.223s  |   0.223s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Math-mul.i.dfy.CheckWellformed__Math____mul__i.__default.mul__recursive.smt2    |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Math-mul.i.dfy.Impl__Math____mul__i.__default.lemma__mul__one__to__one.smt2     |   0.200s  |   0.200s  |   0.000s  | 0.0%|
|d_komodo-verified-allocate_page.gen.dfyCheckWellformed___module.__default.va__lemma__allocate__page.smt2  |  11.937s  |  11.937s  |   0.000s  | 0.0%|
|d_komodo-verified-attest_helpers.gen.dfyImpl___module.__default.va__lemma__addrspace__va__for__page__va.smt2  |  20.060s  |  20.060s  |   0.000s  | 0.0%|
|d_komodo-verified-attest_input.gen.dfyCheckWellformed___module.__default.va__lemma__arrange__attestation__input.smt2  |   4.758s  |   4.758s  |   0.000s  | 0.0%|
|d_komodo-verified-attest_input.gen.dfyImpl___module.__default.va__lemma__arrange__attestation__input_split0.smt2  |  20.059s  |  20.059s  |   0.000s  | 0.0%|
|d_komodo-verified-attest_input.gen.dfyImpl___module.__default.va__lemma__arrange__real__measurement__in__memory_split0.smt2  |  20.057s  |  20.057s  |   0.000s  | 0.0%|
|d_komodo-verified-attest_input.gen.dfyImpl___module.__default.va__lemma__arrange__real__measurement__in__memory_split1.smt2  |  20.050s  |  20.050s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.gen.dfyImpl___module.__default.lemma__aligned__sp.smt2              |   7.722s  |   7.722s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.gen.dfyImpl___module.__default.va__lemma__unstack__banked__regs2.smt2  |  20.051s  |  20.051s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.i.dfyCheckWellformed___module.__default.KomExceptionHandlerInvariant.smt2  |   9.791s  |   9.791s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.i.dfyImpl___module.__default.lemma__contentsOfPage__corresponds.smt2  |   3.376s  |   3.376s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.i.dfyImpl___module.__default.lemma__evalMOVSPCLRUC__inner.smt2      |  20.045s  |  20.045s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.i.dfyImpl___module.__default.lemma__onlyDataPagesAreWritable.smt2   |   1.232s  |   1.232s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.i.dfyImpl___module.__default.lemma__userExecutionUpdatesPageDb.smt2  |  20.058s  |  20.058s  |   0.000s  | 0.0%|
|d_komodo-verified-entrybits.i.dfyImpl___module.__default.lemma__sp__bit__helper.smt2        |   0.930s  |   0.930s  |   0.000s  | 0.0%|
|d_komodo-verified-exceptions.i.dfyImpl___module.__default.lemma__PrivInterruptInvariants.smt2  |  20.047s  |  20.047s  |   0.000s  | 0.0%|
|d_komodo-verified-exhandler_state.i.dfyImpl___module.__default.lemma__UserExceptionStateSideEffects.smt2  |  20.049s  |  20.049s  |   0.000s  | 0.0%|
|d_komodo-verified-init_addrspace.gen.dfyImpl___module.__default.va__lemma__init__addrspace.smt2  |  20.054s  |  20.054s  |   0.000s  | 0.0%|
|d_komodo-verified-init_l2ptable.gen.dfyImpl___module.__default.va__lemma__init__l2ptable__success.smt2  |  20.061s  |  20.061s  |   0.000s  | 0.0%|
|d_komodo-verified-init_l2ptable.gen.dfyImpl___module.__default.va__lemma__zero__l2__page.smt2  |  20.051s  |  20.051s  |   0.000s  | 0.0%|
|d_komodo-verified-kom_utils.gen.dfyCheckWellformed___module.__default.va__lemma__stack__nonvolatiles.smt2  |   7.652s  |   7.652s  |   0.000s  | 0.0%|
|d_komodo-verified-kom_utils.gen.dfyImpl___module.__default.va__lemma__load__page__type.smt2  |  10.699s  |  10.699s  |   0.000s  | 0.0%|
|d_komodo-verified-kom_utils.gen.dfyImpl___module.__default.va__lemma__unstack__lr.smt2      |   2.977s  |   2.977s  |   0.000s  | 0.0%|
|d_komodo-verified-kom_utils.gen.dfyImpl___module.__default.va__lemma__unstack__nonvolatiles.smt2  |  20.053s  |  20.053s  |   0.000s  | 0.0%|
|d_komodo-verified-kom_utils.gen.dfyImpl___module.__default.va__lemma__unstack__nonvolatiles__except__lr.smt2  |  20.058s  |  20.058s  |   0.000s  | 0.0%|
|d_komodo-verified-kom_utils.gen.dfyImpl___module.__default.va__lemma__update__pagedb__entry.smt2  |  18.055s  |  18.055s  |   0.000s  | 0.0%|
|d_komodo-verified-map_common.gen.dfyImpl___module.__default.va__lemma__is__valid__mapping__target.smt2  |  20.062s  |  20.062s  |   0.000s  | 0.0%|
|d_komodo-verified-map_common.gen.dfyImpl___module.__default.va__lemma__is__valid__mapping__target_k__finish.smt2  |  20.055s  |  20.055s  |   0.000s  | 0.0%|
|d_komodo-verified-map_utils.gen.dfyCheckWellformed___module.__default.va__lemma__kom__smc__map__measure__hash.smt2  |  20.060s  |  20.060s  |   0.000s  | 0.0%|
|d_komodo-verified-map_utils.gen.dfyCheckWellformed___module.__default.va__lemma__kom__smc__map__measure__sha.smt2  |  20.049s  |  20.049s  |   0.000s  | 0.0%|
|d_komodo-verified-map_utils.gen.dfyImpl___module.__default.va__lemma__fetch__l1pte.smt2     |  17.559s  |  17.559s  |   0.000s  | 0.0%|
|d_komodo-verified-mapping.i.dfyImpl___module.__default.lemma__installL1PTEInPageDb__dataPageRefs.smt2  |   2.480s  |   2.480s  |   0.000s  | 0.0%|
|d_komodo-verified-pagedb.i.dfyImpl___module.__default.extractPageDbToAbstract.smt2          |   2.486s  |   2.486s  |   0.000s  | 0.0%|
|d_komodo-verified-pagedb.i.dfyImpl___module.__default.extractPageDbToAbstractOne.smt2       |   2.249s  |   2.249s  |   0.000s  | 0.0%|
|d_komodo-verified-ptables.i.dfyImpl___module.__default.lemma__WritablePages.smt2            |   2.737s  |   2.737s  |   0.000s  | 0.0%|
|d_komodo-verified-ptables.i.dfyImpl___module.__default.lemma__l2tablesmatch.smt2            |   7.230s  |   7.230s  |   0.000s  | 0.0%|
|d_komodo-verified-ptables.i.dfyImpl___module.__default.lemma__ptablesmatch.smt2             |   9.739s  |   9.739s  |   0.000s  | 0.0%|
|d_komodo-verified-ptables.i.dfyImpl___module.__default.lemma__ptablesmatch_split0.smt2      |   5.121s  |   5.121s  |   0.000s  | 0.0%|
|d_komodo-verified-ptebits.i.dfyImpl___module.__default.lemma__nonexec__mapping.smt2         |   7.261s  |   7.261s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__AllPages.smt2   |   4.481s  |   4.481s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__enter__loweq__pdb__not__atkr.smt2  |  20.056s  |  20.056s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__exceptionHandled__atkr.smt2  |  10.537s  |  10.537s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__updateUserPages__conf__not__atkr.smt2  |  20.053s  |  20.053s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-integ_ni_entry.i.dfyImpl___module.__default.lemma__enter__enc__obs__enter.smt2  |  20.052s  |  20.052s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-integ_ni_entry.i.dfyImpl___module.__default.lemma__enter__loweq__pdb__not__obs.smt2  |  20.054s  |  20.054s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-hmac.gen.dfyImpl___module.__default.va__lemma__hmac__inner__prep__hash.smt2  |  20.062s  |  20.062s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-memory-helpers.i.dfyImpl___module.__default.lemma__AddrMemContentsSeq__adds.smt2  |   2.666s  |   2.666s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-sha256.i.dfyImpl___module.__default.SHA__padding__words2bytes.smt2    |  20.061s  |  20.061s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-sha256.i.dfyImpl___module.__default.lemma__InputHelper.smt2           |   0.562s  |   0.562s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-sha256.s.dfyCheckWellformed___module.__default.K__SHA256.smt2         |   5.171s  |   5.171s  |   0.000s  | 0.0%|
|d_komodo-verified-smcapi.i.dfyImpl___module.__default.kom__smc__map__measure__helper1.smt2  |  20.047s  |  20.047s  |   0.000s  | 0.0%|
|d_komodo-verified-smcapi.i.dfyImpl___module.__default.lemma__sha256__concat.smt2            |   1.573s  |   1.573s  |   0.000s  | 0.0%|
|d_komodo-verified-svc_handlers.gen.dfyCheckWellformed___module.__default.va__lemma__svc__returning__verify__step1.smt2  |  17.482s  |  17.482s  |   0.000s  | 0.0%|
|d_komodo-verified-svc_handlers.gen.dfyImpl___module.__default.va__lemma__svc__map__data__success.smt2  |  20.059s  |  20.059s  |   0.000s  | 0.0%|
|d_komodo-verified-svc_handlers.gen.dfyImpl___module.__default.va__lemma__svc__returning__default.smt2  |  20.059s  |  20.059s  |   0.000s  | 0.0%|
|d_komodo-verified-verify.gen.dfyImpl___module.__default.va__lemma__compare__memory__to__regs.smt2  |  20.065s  |  20.065s  |   0.000s  | 0.0%|
|d_komodo-verified-verify_input.gen.dfyCheckWellformed___module.__default.lemma__grab__measurement.smt2  |   4.553s  |   4.553s  |   0.000s  | 0.0%|
|d_komodo-verified-verify_input.gen.dfyCheckWellformed___module.__default.lemma__grab__user__words.smt2  |   4.265s  |   4.265s  |   0.000s  | 0.0%|
|d_komodo-verified-verify_input.gen.dfyImpl___module.__default.lemma__grab__measurement.smt2  |  20.041s  |  20.041s  |   0.000s  | 0.0%|
|d_komodo-verified-verify_input.gen.dfyImpl___module.__default.lemma__grab__user__words.smt2  |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|d_komodo-verified-verify_input.gen.dfyImpl___module.__default.va__lemma__arrange__user__words__in__memory.smt2  |  13.867s  |  13.867s  |   0.000s  | 0.0%|
|d_komodo-verified-verify_input.gen.dfyImpl___module.__default.va__lemma__arrange__user__words__in__memory_split0.smt2  |  17.908s  |  17.908s  |   0.000s  | 0.0%|
|d_komodo-verified-verify_input.gen.dfyImpl___module.__default.va__lemma__arrange__verification__input_split0.smt2  |  11.956s  |  11.956s  |   0.000s  | 0.0%|
|d_komodo-verified-verify_input.gen.dfyImpl___module.__default.va__lemma__arrange__verify__measurement__in__memory.smt2  |  10.169s  |  10.169s  |   0.000s  | 0.0%|
|d_komodo-verified-verify_input.gen.dfyImpl___module.__default.va__lemma__arrange__verify__measurement__in__memory_split0.smt2  |  15.378s  |  15.378s  |   0.000s  | 0.0%|
|d_lvbkv-Betree-AsyncBetree.i.dfy.Impl__AsyncBetree.__default.QueryAdvanceChangesLookup.smt2  |   6.531s  |   6.531s  |   0.000s  | 0.0%|
|d_lvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.InitImpliesInv.smt2                |   1.269s  |   1.269s  |   0.000s  | 0.0%|
|d_lvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectResultingGraphAfterAllocs.smt2  |   4.067s  |   4.067s  |   0.000s  | 0.0%|
|d_lvbkv-BlockCacheSystem-BetreeCache.i.dfy.Impl__BetreeCache.__default.BetreeMoveStepPreservesInv.smt2  |  20.051s  |  20.051s  |   0.000s  | 0.0%|
|d_lvbkv-BlockCacheSystem-BetreeSystem.i.dfy.Impl__BetreeSystem.__default.BlockCacheMoveStepPreservesInv.smt2  |  20.044s  |  20.044s  |   0.000s  | 0.0%|
|d_lvbkv-BlockCacheSystem-BlockCache.i.dfy.Impl__BlockCache.__default.DirtyStepPreservesInv.smt2  |   8.073s  |   8.073s  |   0.000s  | 0.0%|
|d_lvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.DiskInternalStepPreservesInv.smt2  |   3.374s  |   3.374s  |   0.000s  | 0.0%|
|d_lvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBytesSplit.smt2  |   0.990s  |   0.990s  |   0.000s  | 0.0%|
|d_lvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeEqJournalBlocks.smt2  |   0.977s  |   0.977s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-GrowModel.i.dfy.Impl__GrowModel.__default.growCorrect.smt2                     |  20.045s  |  20.045s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.FindIndirectionTableLocationAndRequestWrite.smt2  |   7.823s  |   7.823s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-JournalistImpl.i.dfy.Impl__JournalistImpl.Journalist.packageFrozenJournal.smt2  |   0.812s  |   0.812s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-JournalistImpl.i.dfy.Impl__JournalistImpl.Journalist.reallocJournalEntries.smt2  |   0.643s  |   0.643s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.journalRangeFromHasChecksums.smt2  |   0.624s  |   0.624s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.lemma__writeJournalEntries.smt2  |  12.343s  |  12.343s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.writeOntoPreservesSlice.smt2  |   0.447s  |   0.447s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-JournalistParsingImpl.i.dfy.Impl__JournalistParsingImpl.__default.ParseJournalRangeOfBytes.smt2  |   2.146s  |   2.146s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.KeyValSeqToPivots.smt2   |   6.039s  |   6.039s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.bucketsToVal.smt2        |  20.046s  |  20.046s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-MarshallingModel.i.dfy.Impl__MarshallingModel.__default.WeightBucketListLteSize.smt2  |   5.007s  |   5.007s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-NodeImpl.i.dfy.Impl__NodeImpl.Node.BucketsWellMarshalled.smt2                  |   1.944s  |   1.944s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-NodeImpl.i.dfy.Impl__NodeImpl.Node.CutoffNodeAndKeepLeft.smt2                  |   3.394s  |   3.394s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-QueryModel.i.dfy.Impl__QueryModel.__default.AugmentLookup.smt2                 |   4.970s  |   4.970s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-SplitModel.i.dfy.Impl__SplitModel.__default.lemmaChildrenConditionsCutoffNode.smt2  |   2.920s  |   2.920s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-SuccImpl.i.dfy.Impl__SuccImpl.__default.getPathInternal.smt2                   |  10.837s  |  10.837s  |   0.000s  | 0.0%|
|d_lvbkv-MapSpec-TSJ.i.dfy.Impl__TSJ.__default.CrashStepPreservesInv.smt2                    |   0.425s  |   0.425s  |   0.000s  | 0.0%|
|d_lvbkv-MapSpec-TSJ.i.dfy.Impl__TSJ.__default.Move1to2StepPreservesInv.smt2                 |   0.400s  |   0.400s  |   0.000s  | 0.0%|
|d_lvbkv-PivotBetree-PivotBetree.i.dfy.Impl__PivotBetree.__default.GCStepRefines.smt2        |   8.079s  |   8.079s  |   0.000s  | 0.0%|
|d_lvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.Impl__PivotBetreeSpecRefinement.__default.InUpperBoundAndNot.smt2  |   0.986s  |   0.986s  |   0.000s  | 0.0%|
|d_lvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.Impl__PivotBetreeSpecRefinement.__default.MergeChildrenConsistent.smt2  |  20.054s  |  20.054s  |   0.000s  | 0.0%|
|d_lvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.Impl__PivotBetreeSpecRefinement.__default.SplitMergeBuffersChildrenEq.smt2  |   3.144s  |   3.144s  |   0.000s  | 0.0%|
|d_lvbkv-PivotBetree-TSJPivotBetree.i.dfy.Impl__TSJPivotBetree.__default.Move3StepPreservesInv.smt2  |   1.669s  |   1.669s  |   0.000s  | 0.0%|
|d_lvbkv-Versions-CompositeView_Refines_TSJMap.i.dfy.Impl__CompositeView__Refines__TSJMap.__default.CrashRefines.smt2  |   1.623s  |   1.623s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-Arrays.i.dfy.Impl__Arrays.__default.replace1with2.smt2                     |   4.657s  |   4.657s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.bit__or__is__union__uint64.smt2  |   0.908s  |   0.908s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-Sequences.i.dfy.Impl__Sequences.__default.DisjointConcatenation.smt2       |   0.242s  |   0.242s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-mathematics.i.dfy.Impl__Mathematics.__default.DivCeilLT.smt2               |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-mathematics.i.dfy.Impl__Mathematics.__default.PosMulPreservesOrder.smt2    |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-total_order.i.dfy.Impl__Total__Preorder.__default.ExistsBiggestInSet.smt2  |   0.263s  |   0.263s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-total_order_impl.i.dfy.Impl__Total__Order__Impl.__default.ArrayLargestLtPlus1.smt2  |   0.357s  |   0.357s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-total_order_impl.i.dfy.Impl__Total__Order__Impl.__default.ArrayLargestLtePlus1.smt2  |   0.363s  |   0.363s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.CloneSeq.smt2               |   2.952s  |   2.952s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.GetLastKey.smt2             |   1.687s  |   1.687s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.ISeq__replace1with2.smt2    |  20.048s  |  20.048s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.SplitOneInList.smt2         |  14.693s  |  14.693s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.WeightBucketIs.smt2         |   1.149s  |   1.149s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.WeightKeyListIs.smt2        |   2.068s  |   2.068s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.computeWeightOfSeq.smt2     |   2.274s  |   2.274s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.WeightSplitBucketAdditive.smt2  |   0.679s  |   0.679s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-LKMBPKVOps.i.dfy.Impl__LKMBPKVOps.__default.IsKeyMessageTreeInheritance.smt2  |  20.054s  |  20.054s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.CheckWellformed__PackedKV.__default.AppendEncodedMessage.smt2  |   1.024s  |   1.024s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.CheckWellformed__PackedKV.__default.psaSeq__Messages.smt2  |   0.878s  |   0.878s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.CheckWellformed__PackedKV.__default.subPkv.smt2          |   1.178s  |   1.178s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.__default.WeightBucketPkv__eq__WeightPkv.smt2  |   8.376s  |   8.376s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.__default.computePivotIndexes.smt2      |   0.947s  |   0.947s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.ComputeValidStringLens.smt2     |   0.817s  |   0.817s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedKVMarshalling.i.dfy.Impl__PackedKVMarshalling.__default.ComputeWF.smt2  |   0.911s  |   0.911s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedKVMarshalling.i.dfy.Impl__PackedKVMarshalling.__default.SizeOfVPackedStringArrayIsKeyListWeight.smt2  |  20.054s  |  20.054s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedStringArray.i.dfy.CheckWellformed__PackedStringArray.__default.psaSeq.smt2  |   0.524s  |   0.524s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.DynamicPsa.appendSeq.smt2  |   8.766s  |   8.766s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.ToSeq.smt2    |   0.551s  |   0.551s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.UniqueRepr.smt2  |   0.607s  |   0.607s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.psaAppendIAppend.smt2  |   0.572s  |   0.572s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.psaAppendSeqAdditive.smt2  |   0.699s  |   0.699s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Checksums-CRC32C_Lemmas.i.dfy.Impl__CRC32C__Lemmas.__default.four__slices.smt2  |   0.346s  |   0.346s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Checksums-CRC32C_Lut.i.dfy.CheckWellformed__CRC32C__Lut.__default.combine.smt2  |   2.868s  |   2.868s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Checksums-CRC32C_Lut.i.dfy.Impl__CRC32C__Lut.__default.reverse__p.smt2          |   0.867s  |   0.867s  |   0.000s  | 0.0%|
|d_lvbkv-lib-DataStructures-KMBtree.i.dfy.Impl__KMBtreeModel.__default.IndexesNonempty.smt2  |   0.516s  |   0.516s  |   0.000s  | 0.0%|
|d_lvbkv-lib-DataStructures-LinearMutableMap.i.dfy.Impl__LinearMutableMap.__default.Probe.smt2  |  20.045s  |  20.045s  |   0.000s  | 0.0%|
|d_lvbkv-lib-DataStructures-MutableMapModel.i.dfy.Impl__MutableMapModel.__default.LemmaReallocIterateResult.smt2  |  20.048s  |  20.048s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallArrayContents.smt2  |   6.053s  |   6.053s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallTupleContents.smt2  |   2.210s  |   2.210s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint32Array.smt2  |   1.380s  |   1.380s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint64Array.smt2  |   1.552s  |   1.552s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Marshalling-Util.i.dfy.Impl__Common____Util__i.__default.seqIntoArrayOpt.smt2   |   0.343s  |   0.343s  |   0.000s  | 0.0%|
|s_komodo-1518.6.smt2                                                                        |  20.561s  |  20.561s  |   0.000s  | 0.0%|
</details>
