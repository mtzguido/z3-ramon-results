Comparing data and data


# SUMMARY
- LHS tests = 268
- RHS tests = 268
- LHS success = 268  (100.0%)
- RHS success = 268  (100.0%)


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
Z3 commit: bc6c38e7d3424b88a505cacba4b268d0774d4547
Z3 branch: bc6c38e7d3424b88a505cacba4b268d0774d4547
Z3 options: "-T:20"
Z3 inputs: inputs/mariposa/stable_ext
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
Job tag: bench-mariposa-stable_ext
Runner: rise-runner-2
Z3 repo: CanCebeci/z3
Z3 commit: bc6c38e7d3424b88a505cacba4b268d0774d4547
Z3 branch: bc6c38e7d3424b88a505cacba4b268d0774d4547
Z3 options: "-T:20"
Z3 inputs: inputs/mariposa/stable_ext
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
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectResultingGraphAfterAllocs.smt2  |   2.822s  |   2.822s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeCache.i.dfy.Impl__BetreeCache.__default.BetreeMoveStepPreservesInv.smt2  |   3.183s  |   3.183s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeSystem_Refines_StatesViewPivotBetree.i.dfy.Impl__BetreeSystem__Refines__StatesViewPivotBetree.__default.BetreeMoveStepRefines.smt2  |   9.666s  |   9.666s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ProcessWritePreservesInv.smt2  |   7.116s  |   7.116s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesReqWriteOp.smt2  |   8.310s  |   8.310s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenCompose.smt2  |  20.025s  |  20.025s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenFromBucketStackWithLowerBound.smt2  |   3.145s  |   3.145s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterInitImpl.i.dfy.Impl__CommitterInitImpl.__default.FinishLoadingOtherPhase.smt2  |   8.596s  |   8.596s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-EvictImpl.i.dfy.Impl__EvictImpl.__default.Evict.smt2                           |   5.220s  |   5.220s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-HandleReadResponseImpl.i.dfy.Impl__HandleReadResponseImpl.__default.readResponse.smt2  |  20.056s  |  20.056s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.writeNodeResponse.smt2                     |  10.065s  |  10.065s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.InitLocBitmap.smt2  |   6.091s  |   6.091s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.ValToIndirectionTable.smt2  |  20.051s  |  20.051s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.CheckWellformed__IndirectionTableModel.__default.RemoveRef.smt2  |   3.933s  |   3.933s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.Impl__IndirectionTableModel.__default.LemmaComputeRefCountsEntryIterateCorrectPartial.smt2  |   2.706s  |   2.706s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.fillInChecksumsPreserves.smt2  |   3.908s  |   3.908s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.writeOntoResult.smt2  |  10.301s  |  10.301s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.parseJournals.smt2  |   1.135s  |   1.135s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.ValToBuckets.smt2        |   7.518s  |   7.518s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.bucketToVal.smt2         |   2.422s  |   2.422s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectResultingGraphAfterAllocs.smt2  |   2.822s  |   2.822s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeCache.i.dfy.Impl__BetreeCache.__default.BetreeMoveStepPreservesInv.smt2  |   3.183s  |   3.183s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeSystem_Refines_StatesViewPivotBetree.i.dfy.Impl__BetreeSystem__Refines__StatesViewPivotBetree.__default.BetreeMoveStepRefines.smt2  |   9.666s  |   9.666s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ProcessWritePreservesInv.smt2  |   7.116s  |   7.116s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesReqWriteOp.smt2  |   8.310s  |   8.310s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenCompose.smt2  |  20.025s  |  20.025s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenFromBucketStackWithLowerBound.smt2  |   3.145s  |   3.145s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterInitImpl.i.dfy.Impl__CommitterInitImpl.__default.FinishLoadingOtherPhase.smt2  |   8.596s  |   8.596s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-EvictImpl.i.dfy.Impl__EvictImpl.__default.Evict.smt2                           |   5.220s  |   5.220s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-HandleReadResponseImpl.i.dfy.Impl__HandleReadResponseImpl.__default.readResponse.smt2  |  20.056s  |  20.056s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.writeNodeResponse.smt2                     |  10.065s  |  10.065s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.InitLocBitmap.smt2  |   6.091s  |   6.091s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.ValToIndirectionTable.smt2  |  20.051s  |  20.051s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.CheckWellformed__IndirectionTableModel.__default.RemoveRef.smt2  |   3.933s  |   3.933s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.Impl__IndirectionTableModel.__default.LemmaComputeRefCountsEntryIterateCorrectPartial.smt2  |   2.706s  |   2.706s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.fillInChecksumsPreserves.smt2  |   3.908s  |   3.908s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.writeOntoResult.smt2  |  10.301s  |  10.301s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.parseJournals.smt2  |   1.135s  |   1.135s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.ValToBuckets.smt2        |   7.518s  |   7.518s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.bucketToVal.smt2         |   2.422s  |   2.422s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectResultingGraphAfterAllocs.smt2  |   2.822s  |   2.822s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeCache.i.dfy.Impl__BetreeCache.__default.BetreeMoveStepPreservesInv.smt2  |   3.183s  |   3.183s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeSystem_Refines_StatesViewPivotBetree.i.dfy.Impl__BetreeSystem__Refines__StatesViewPivotBetree.__default.BetreeMoveStepRefines.smt2  |   9.666s  |   9.666s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ProcessWritePreservesInv.smt2  |   7.116s  |   7.116s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesReqWriteOp.smt2  |   8.310s  |   8.310s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenCompose.smt2  |  20.025s  |  20.025s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenFromBucketStackWithLowerBound.smt2  |   3.145s  |   3.145s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterInitImpl.i.dfy.Impl__CommitterInitImpl.__default.FinishLoadingOtherPhase.smt2  |   8.596s  |   8.596s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-EvictImpl.i.dfy.Impl__EvictImpl.__default.Evict.smt2                           |   5.220s  |   5.220s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-HandleReadResponseImpl.i.dfy.Impl__HandleReadResponseImpl.__default.readResponse.smt2  |  20.056s  |  20.056s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.writeNodeResponse.smt2                     |  10.065s  |  10.065s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.InitLocBitmap.smt2  |   6.091s  |   6.091s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.ValToIndirectionTable.smt2  |  20.051s  |  20.051s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.CheckWellformed__IndirectionTableModel.__default.RemoveRef.smt2  |   3.933s  |   3.933s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.Impl__IndirectionTableModel.__default.LemmaComputeRefCountsEntryIterateCorrectPartial.smt2  |   2.706s  |   2.706s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.fillInChecksumsPreserves.smt2  |   3.908s  |   3.908s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.writeOntoResult.smt2  |  10.301s  |  10.301s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.parseJournals.smt2  |   1.135s  |   1.135s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.ValToBuckets.smt2        |   7.518s  |   7.518s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.bucketToVal.smt2         |   2.422s  |   2.422s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectResultingGraphAfterAllocs.smt2  |   2.822s  |   2.822s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeCache.i.dfy.Impl__BetreeCache.__default.BetreeMoveStepPreservesInv.smt2  |   3.183s  |   3.183s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeSystem_Refines_StatesViewPivotBetree.i.dfy.Impl__BetreeSystem__Refines__StatesViewPivotBetree.__default.BetreeMoveStepRefines.smt2  |   9.666s  |   9.666s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ProcessWritePreservesInv.smt2  |   7.116s  |   7.116s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesReqWriteOp.smt2  |   8.310s  |   8.310s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenCompose.smt2  |  20.025s  |  20.025s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenFromBucketStackWithLowerBound.smt2  |   3.145s  |   3.145s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterInitImpl.i.dfy.Impl__CommitterInitImpl.__default.FinishLoadingOtherPhase.smt2  |   8.596s  |   8.596s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-EvictImpl.i.dfy.Impl__EvictImpl.__default.Evict.smt2                           |   5.220s  |   5.220s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-HandleReadResponseImpl.i.dfy.Impl__HandleReadResponseImpl.__default.readResponse.smt2  |  20.056s  |  20.056s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.writeNodeResponse.smt2                     |  10.065s  |  10.065s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.InitLocBitmap.smt2  |   6.091s  |   6.091s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.ValToIndirectionTable.smt2  |  20.051s  |  20.051s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.CheckWellformed__IndirectionTableModel.__default.RemoveRef.smt2  |   3.933s  |   3.933s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.Impl__IndirectionTableModel.__default.LemmaComputeRefCountsEntryIterateCorrectPartial.smt2  |   2.706s  |   2.706s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.fillInChecksumsPreserves.smt2  |   3.908s  |   3.908s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.writeOntoResult.smt2  |  10.301s  |  10.301s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.parseJournals.smt2  |   1.135s  |   1.135s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.ValToBuckets.smt2        |   7.518s  |   7.518s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.bucketToVal.smt2         |   2.422s  |   2.422s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|s_komodo-1488.6.smt2                                                                       |  20.754s |6369.0MiB|
|s_komodo-1493.6.smt2                                                                       |  20.733s |6399.0MiB|
|s_komodo-1509.6.smt2                                                                       |  20.667s |6162.0MiB|
|s_komodo-1499.6.smt2                                                                       |  20.600s |5968.0MiB|
|s_komodo-1504.6.smt2                                                                       |  20.569s |5937.0MiB|
|s_komodo-1499.4.smt2                                                                       |  20.471s |3686.0MiB|
|s_komodo-1450.0.smt2                                                                       |  20.319s |2811.0MiB|
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.WriteBackNodeRespStepPreservesGraphs.smt2 |  20.080s |222.0MiB|
|d_komodo-verified-secprop-conf_ni.i.dfyImpl___module.__default.lemma__mapSecure__loweq__pdb__success.smt2 |  20.065s |196.0MiB|
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.AllocStepPreservesInv.smt2 |  20.065s |190.0MiB|
|d_komodo-verified-entry.gen.dfyImpl___module.__default.va__lemma__enclaveexecution__loop.smt2 |  20.062s |181.0MiB|
|d_lvbkv-Impl-SyncImpl.i.dfy.Impl__SyncImpl.__default.sync.smt2                             |  20.059s |204.0MiB|
|d_komodo-verified-entry.gen.dfyImpl___module.__default.va__lemma__stack__banked__regs2.smt2 |  20.057s |186.0MiB|
|d_lvbkv-Impl-SyncImpl.i.dfy.Impl__SyncImpl.__default.TryToWriteBlock.smt2                  |  20.056s |216.0MiB|
|d_fvbkv-Impl-HandleReadResponseImpl.i.dfy.Impl__HandleReadResponseImpl.__default.readResponse.smt2 |  20.056s |180.0MiB|
|d_komodo-verified-sha-sha256-api.gen.dfyImpl___module.__default.va__refined__sha256__one__shot.smt2 |  20.056s |205.0MiB|
|d_komodo-verified-attest_helpers.gen.dfyCheckWellformed___module.__default.va__lemma__load__attestion__key__inner.smt2 |  20.055s |211.0MiB|
|d_lvbkv-Impl-BookkeepingModel.i.dfy.Impl__BookkeepingModel.__default.allocCorrect.smt2     |  20.055s |198.0MiB|
|d_komodo-verified-sha-hmac.gen.dfyImpl___module.__default.va__lemma__hmac__outer.smt2      |  20.053s |229.0MiB|
|d_komodo-verified-sha-sha256-block-data-order.gen.dfyImpl___module.__default.va__abstract__sha256__block__data__order__inner.smt2 |  20.053s |206.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|s_komodo-1488.6.smt2                                                                       |  20.754s |6369.0MiB|
|s_komodo-1493.6.smt2                                                                       |  20.733s |6399.0MiB|
|s_komodo-1509.6.smt2                                                                       |  20.667s |6162.0MiB|
|s_komodo-1499.6.smt2                                                                       |  20.600s |5968.0MiB|
|s_komodo-1504.6.smt2                                                                       |  20.569s |5937.0MiB|
|s_komodo-1499.4.smt2                                                                       |  20.471s |3686.0MiB|
|s_komodo-1450.0.smt2                                                                       |  20.319s |2811.0MiB|
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.WriteBackNodeRespStepPreservesGraphs.smt2 |  20.080s |222.0MiB|
|d_komodo-verified-secprop-conf_ni.i.dfyImpl___module.__default.lemma__mapSecure__loweq__pdb__success.smt2 |  20.065s |196.0MiB|
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.AllocStepPreservesInv.smt2 |  20.065s |190.0MiB|
|d_komodo-verified-entry.gen.dfyImpl___module.__default.va__lemma__enclaveexecution__loop.smt2 |  20.062s |181.0MiB|
|d_lvbkv-Impl-SyncImpl.i.dfy.Impl__SyncImpl.__default.sync.smt2                             |  20.059s |204.0MiB|
|d_komodo-verified-entry.gen.dfyImpl___module.__default.va__lemma__stack__banked__regs2.smt2 |  20.057s |186.0MiB|
|d_lvbkv-Impl-SyncImpl.i.dfy.Impl__SyncImpl.__default.TryToWriteBlock.smt2                  |  20.056s |216.0MiB|
|d_fvbkv-Impl-HandleReadResponseImpl.i.dfy.Impl__HandleReadResponseImpl.__default.readResponse.smt2 |  20.056s |180.0MiB|
|d_komodo-verified-sha-sha256-api.gen.dfyImpl___module.__default.va__refined__sha256__one__shot.smt2 |  20.056s |205.0MiB|
|d_komodo-verified-attest_helpers.gen.dfyCheckWellformed___module.__default.va__lemma__load__attestion__key__inner.smt2 |  20.055s |211.0MiB|
|d_lvbkv-Impl-BookkeepingModel.i.dfy.Impl__BookkeepingModel.__default.allocCorrect.smt2     |  20.055s |198.0MiB|
|d_komodo-verified-sha-hmac.gen.dfyImpl___module.__default.va__lemma__hmac__outer.smt2      |  20.053s |229.0MiB|
|d_komodo-verified-sha-sha256-block-data-order.gen.dfyImpl___module.__default.va__abstract__sha256__block__data__order__inner.smt2 |  20.053s |206.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectResultingGraphAfterAllocs.smt2  |54.088MiB|54.088MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeCache.i.dfy.Impl__BetreeCache.__default.BetreeMoveStepPreservesInv.smt2  |95.216MiB|95.216MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeSystem_Refines_StatesViewPivotBetree.i.dfy.Impl__BetreeSystem__Refines__StatesViewPivotBetree.__default.BetreeMoveStepRefines.smt2  |116.0MiB|116.0MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ProcessWritePreservesInv.smt2  |172.0MiB|172.0MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesReqWriteOp.smt2  |174.0MiB|174.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenCompose.smt2  |171.0MiB|171.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenFromBucketStackWithLowerBound.smt2  |96.512MiB|96.512MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterInitImpl.i.dfy.Impl__CommitterInitImpl.__default.FinishLoadingOtherPhase.smt2  |169.0MiB|169.0MiB|0B| 0.0%|
|d_fvbkv-Impl-EvictImpl.i.dfy.Impl__EvictImpl.__default.Evict.smt2                           |169.0MiB|169.0MiB|0B| 0.0%|
|d_fvbkv-Impl-HandleReadResponseImpl.i.dfy.Impl__HandleReadResponseImpl.__default.readResponse.smt2  |180.0MiB|180.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.writeNodeResponse.smt2                     |171.0MiB|171.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.InitLocBitmap.smt2  |106.0MiB|106.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.ValToIndirectionTable.smt2  |183.0MiB|183.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.CheckWellformed__IndirectionTableModel.__default.RemoveRef.smt2  |97.0MiB|97.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.Impl__IndirectionTableModel.__default.LemmaComputeRefCountsEntryIterateCorrectPartial.smt2  |99.7MiB|99.7MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.fillInChecksumsPreserves.smt2  |68.432MiB|68.432MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.writeOntoResult.smt2  |176.0MiB|176.0MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.parseJournals.smt2  |40.66MiB|40.66MiB|0B| 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.ValToBuckets.smt2        |168.0MiB|168.0MiB|0B| 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.bucketToVal.smt2         |100.0MiB|100.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectResultingGraphAfterAllocs.smt2  |54.088MiB|54.088MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeCache.i.dfy.Impl__BetreeCache.__default.BetreeMoveStepPreservesInv.smt2  |95.216MiB|95.216MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeSystem_Refines_StatesViewPivotBetree.i.dfy.Impl__BetreeSystem__Refines__StatesViewPivotBetree.__default.BetreeMoveStepRefines.smt2  |116.0MiB|116.0MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ProcessWritePreservesInv.smt2  |172.0MiB|172.0MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesReqWriteOp.smt2  |174.0MiB|174.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenCompose.smt2  |171.0MiB|171.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenFromBucketStackWithLowerBound.smt2  |96.512MiB|96.512MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterInitImpl.i.dfy.Impl__CommitterInitImpl.__default.FinishLoadingOtherPhase.smt2  |169.0MiB|169.0MiB|0B| 0.0%|
|d_fvbkv-Impl-EvictImpl.i.dfy.Impl__EvictImpl.__default.Evict.smt2                           |169.0MiB|169.0MiB|0B| 0.0%|
|d_fvbkv-Impl-HandleReadResponseImpl.i.dfy.Impl__HandleReadResponseImpl.__default.readResponse.smt2  |180.0MiB|180.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.writeNodeResponse.smt2                     |171.0MiB|171.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.InitLocBitmap.smt2  |106.0MiB|106.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.ValToIndirectionTable.smt2  |183.0MiB|183.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.CheckWellformed__IndirectionTableModel.__default.RemoveRef.smt2  |97.0MiB|97.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.Impl__IndirectionTableModel.__default.LemmaComputeRefCountsEntryIterateCorrectPartial.smt2  |99.7MiB|99.7MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.fillInChecksumsPreserves.smt2  |68.432MiB|68.432MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.writeOntoResult.smt2  |176.0MiB|176.0MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.parseJournals.smt2  |40.66MiB|40.66MiB|0B| 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.ValToBuckets.smt2        |168.0MiB|168.0MiB|0B| 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.bucketToVal.smt2         |100.0MiB|100.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectResultingGraphAfterAllocs.smt2  |54.088MiB|54.088MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeCache.i.dfy.Impl__BetreeCache.__default.BetreeMoveStepPreservesInv.smt2  |95.216MiB|95.216MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeSystem_Refines_StatesViewPivotBetree.i.dfy.Impl__BetreeSystem__Refines__StatesViewPivotBetree.__default.BetreeMoveStepRefines.smt2  |116.0MiB|116.0MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ProcessWritePreservesInv.smt2  |172.0MiB|172.0MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesReqWriteOp.smt2  |174.0MiB|174.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenCompose.smt2  |171.0MiB|171.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenFromBucketStackWithLowerBound.smt2  |96.512MiB|96.512MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterInitImpl.i.dfy.Impl__CommitterInitImpl.__default.FinishLoadingOtherPhase.smt2  |169.0MiB|169.0MiB|0B| 0.0%|
|d_fvbkv-Impl-EvictImpl.i.dfy.Impl__EvictImpl.__default.Evict.smt2                           |169.0MiB|169.0MiB|0B| 0.0%|
|d_fvbkv-Impl-HandleReadResponseImpl.i.dfy.Impl__HandleReadResponseImpl.__default.readResponse.smt2  |180.0MiB|180.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.writeNodeResponse.smt2                     |171.0MiB|171.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.InitLocBitmap.smt2  |106.0MiB|106.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.ValToIndirectionTable.smt2  |183.0MiB|183.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.CheckWellformed__IndirectionTableModel.__default.RemoveRef.smt2  |97.0MiB|97.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.Impl__IndirectionTableModel.__default.LemmaComputeRefCountsEntryIterateCorrectPartial.smt2  |99.7MiB|99.7MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.fillInChecksumsPreserves.smt2  |68.432MiB|68.432MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.writeOntoResult.smt2  |176.0MiB|176.0MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.parseJournals.smt2  |40.66MiB|40.66MiB|0B| 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.ValToBuckets.smt2        |168.0MiB|168.0MiB|0B| 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.bucketToVal.smt2         |100.0MiB|100.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectResultingGraphAfterAllocs.smt2  |54.088MiB|54.088MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeCache.i.dfy.Impl__BetreeCache.__default.BetreeMoveStepPreservesInv.smt2  |95.216MiB|95.216MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeSystem_Refines_StatesViewPivotBetree.i.dfy.Impl__BetreeSystem__Refines__StatesViewPivotBetree.__default.BetreeMoveStepRefines.smt2  |116.0MiB|116.0MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ProcessWritePreservesInv.smt2  |172.0MiB|172.0MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesReqWriteOp.smt2  |174.0MiB|174.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenCompose.smt2  |171.0MiB|171.0MiB|0B| 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenFromBucketStackWithLowerBound.smt2  |96.512MiB|96.512MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterInitImpl.i.dfy.Impl__CommitterInitImpl.__default.FinishLoadingOtherPhase.smt2  |169.0MiB|169.0MiB|0B| 0.0%|
|d_fvbkv-Impl-EvictImpl.i.dfy.Impl__EvictImpl.__default.Evict.smt2                           |169.0MiB|169.0MiB|0B| 0.0%|
|d_fvbkv-Impl-HandleReadResponseImpl.i.dfy.Impl__HandleReadResponseImpl.__default.readResponse.smt2  |180.0MiB|180.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.writeNodeResponse.smt2                     |171.0MiB|171.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.InitLocBitmap.smt2  |106.0MiB|106.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.ValToIndirectionTable.smt2  |183.0MiB|183.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.CheckWellformed__IndirectionTableModel.__default.RemoveRef.smt2  |97.0MiB|97.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.Impl__IndirectionTableModel.__default.LemmaComputeRefCountsEntryIterateCorrectPartial.smt2  |99.7MiB|99.7MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.fillInChecksumsPreserves.smt2  |68.432MiB|68.432MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.writeOntoResult.smt2  |176.0MiB|176.0MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.parseJournals.smt2  |40.66MiB|40.66MiB|0B| 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.ValToBuckets.smt2        |168.0MiB|168.0MiB|0B| 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.bucketToVal.smt2         |100.0MiB|100.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|s_komodo-1493.6.smt2                                                                       |  20.733s |6399.0MiB|
|s_komodo-1488.6.smt2                                                                       |  20.754s |6369.0MiB|
|s_komodo-1509.6.smt2                                                                       |  20.667s |6162.0MiB|
|s_komodo-1499.6.smt2                                                                       |  20.600s |5968.0MiB|
|s_komodo-1504.6.smt2                                                                       |  20.569s |5937.0MiB|
|s_komodo-1499.4.smt2                                                                       |  20.471s |3686.0MiB|
|s_komodo-1450.0.smt2                                                                       |  20.319s |2811.0MiB|
|d_lvbkv-ByteBlockCacheSystem-ByteSystem_Refines_BetreeJournalSystem.i.dfy.Impl__ByteSystem__Refines__BetreeJournalSystem.__default.RefinesNext.smt2 |  13.117s |402.0MiB|
|d_komodo-verified-attest_helpers.gen.dfyImpl___module.__default.va__lemma__unstack__all__regs.smt2 |  20.053s |238.0MiB|
|d_komodo-verified-sha-hmac.gen.dfyImpl___module.__default.va__lemma__hmac__outer.smt2      |  20.053s |229.0MiB|
|d_komodo-verified-svc_handlers.gen.dfyImpl___module.__default.va__lemma__rng__read.smt2    |  20.030s |224.0MiB|
|d_lvbkv-Impl-CoordinationImpl.i.dfy.Impl__CoordinationImpl.__default.succ.smt2             |  20.053s |223.0MiB|
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.WriteBackNodeRespStepPreservesGraphs.smt2 |  20.080s |222.0MiB|
|d_lvbkv-BlockCacheSystem-BetreeJournalSystem_Refines_ThreeStateVersionedMap.i.dfy.Impl__BetreeJournalSystem__Refines__ThreeStateVersionedMap.__default.RefinesNext.smt2 |   3.305s |218.0MiB|
|d_lvbkv-Impl-SyncImpl.i.dfy.Impl__SyncImpl.__default.TryToWriteBlock.smt2                  |  20.056s |216.0MiB|
|d_komodo-verified-attest_helpers.gen.dfyCheckWellformed___module.__default.va__lemma__load__attestion__key__inner.smt2 |  20.055s |211.0MiB|
|d_komodo-verified-sha-sha256-block-data-order.gen.dfyImpl___module.__default.va__abstract__sha256__block__data__order__inner.smt2 |  20.053s |206.0MiB|
|d_komodo-verified-exception_handlers.gen.dfyImpl___module.__default.va__lemma__CPSID__IAF.smt2 |  20.047s |206.0MiB|
|d_komodo-verified-sha-sha256-api.gen.dfyImpl___module.__default.va__refined__sha256__one__shot.smt2 |  20.056s |205.0MiB|
|d_lvbkv-Impl-SyncImpl.i.dfy.Impl__SyncImpl.__default.sync.smt2                             |  20.059s |204.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|s_komodo-1493.6.smt2                                                                       |  20.733s |6399.0MiB|
|s_komodo-1488.6.smt2                                                                       |  20.754s |6369.0MiB|
|s_komodo-1509.6.smt2                                                                       |  20.667s |6162.0MiB|
|s_komodo-1499.6.smt2                                                                       |  20.600s |5968.0MiB|
|s_komodo-1504.6.smt2                                                                       |  20.569s |5937.0MiB|
|s_komodo-1499.4.smt2                                                                       |  20.471s |3686.0MiB|
|s_komodo-1450.0.smt2                                                                       |  20.319s |2811.0MiB|
|d_lvbkv-ByteBlockCacheSystem-ByteSystem_Refines_BetreeJournalSystem.i.dfy.Impl__ByteSystem__Refines__BetreeJournalSystem.__default.RefinesNext.smt2 |  13.117s |402.0MiB|
|d_komodo-verified-attest_helpers.gen.dfyImpl___module.__default.va__lemma__unstack__all__regs.smt2 |  20.053s |238.0MiB|
|d_komodo-verified-sha-hmac.gen.dfyImpl___module.__default.va__lemma__hmac__outer.smt2      |  20.053s |229.0MiB|
|d_komodo-verified-svc_handlers.gen.dfyImpl___module.__default.va__lemma__rng__read.smt2    |  20.030s |224.0MiB|
|d_lvbkv-Impl-CoordinationImpl.i.dfy.Impl__CoordinationImpl.__default.succ.smt2             |  20.053s |223.0MiB|
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.WriteBackNodeRespStepPreservesGraphs.smt2 |  20.080s |222.0MiB|
|d_lvbkv-BlockCacheSystem-BetreeJournalSystem_Refines_ThreeStateVersionedMap.i.dfy.Impl__BetreeJournalSystem__Refines__ThreeStateVersionedMap.__default.RefinesNext.smt2 |   3.305s |218.0MiB|
|d_lvbkv-Impl-SyncImpl.i.dfy.Impl__SyncImpl.__default.TryToWriteBlock.smt2                  |  20.056s |216.0MiB|
|d_komodo-verified-attest_helpers.gen.dfyCheckWellformed___module.__default.va__lemma__load__attestion__key__inner.smt2 |  20.055s |211.0MiB|
|d_komodo-verified-sha-sha256-block-data-order.gen.dfyImpl___module.__default.va__abstract__sha256__block__data__order__inner.smt2 |  20.053s |206.0MiB|
|d_komodo-verified-exception_handlers.gen.dfyImpl___module.__default.va__lemma__CPSID__IAF.smt2 |  20.047s |206.0MiB|
|d_komodo-verified-sha-sha256-api.gen.dfyImpl___module.__default.va__refined__sha256__one__shot.smt2 |  20.056s |205.0MiB|
|d_lvbkv-Impl-SyncImpl.i.dfy.Impl__SyncImpl.__default.sync.smt2                             |  20.059s |204.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectResultingGraphAfterAllocs.smt2  |   2.822s  |   2.822s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeCache.i.dfy.Impl__BetreeCache.__default.BetreeMoveStepPreservesInv.smt2  |   3.183s  |   3.183s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-BetreeSystem_Refines_StatesViewPivotBetree.i.dfy.Impl__BetreeSystem__Refines__StatesViewPivotBetree.__default.BetreeMoveStepRefines.smt2  |   9.666s  |   9.666s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ProcessWritePreservesInv.smt2  |   7.116s  |   7.116s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesReqWriteOp.smt2  |   8.310s  |   8.310s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenCompose.smt2  |  20.025s  |  20.025s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenFromBucketStackWithLowerBound.smt2  |   3.145s  |   3.145s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterInitImpl.i.dfy.Impl__CommitterInitImpl.__default.FinishLoadingOtherPhase.smt2  |   8.596s  |   8.596s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-EvictImpl.i.dfy.Impl__EvictImpl.__default.Evict.smt2                           |   5.220s  |   5.220s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-HandleReadResponseImpl.i.dfy.Impl__HandleReadResponseImpl.__default.readResponse.smt2  |  20.056s  |  20.056s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.writeNodeResponse.smt2                     |  10.065s  |  10.065s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.InitLocBitmap.smt2  |   6.091s  |   6.091s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.ValToIndirectionTable.smt2  |  20.051s  |  20.051s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.CheckWellformed__IndirectionTableModel.__default.RemoveRef.smt2  |   3.933s  |   3.933s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.Impl__IndirectionTableModel.__default.LemmaComputeRefCountsEntryIterateCorrectPartial.smt2  |   2.706s  |   2.706s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.fillInChecksumsPreserves.smt2  |   3.908s  |   3.908s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.writeOntoResult.smt2  |  10.301s  |  10.301s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.parseJournals.smt2  |   1.135s  |   1.135s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.ValToBuckets.smt2        |   7.518s  |   7.518s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.bucketToVal.smt2         |   2.422s  |   2.422s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.bucketsToVal.smt2        |   5.409s  |   5.409s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.nodeToVal.smt2           |   9.434s  |   9.434s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-QueryModel.i.dfy.Impl__QueryModel.__default.AugmentLookup.smt2                 |   3.285s  |   3.285s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-SplitImpl.i.dfy.Impl__SplitImpl.__default.splitBookkeeping.smt2                |  11.888s  |  11.888s  |   0.000s  | 0.0%|
|d_fvbkv-PivotBetree-PivotBetree.i.dfy.Impl__PivotBetree.__default.BetreeStepRefines.smt2    |   3.360s  |   3.360s  |   0.000s  | 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.Impl__PivotBetreeSpecRefinement.__default.CutoffNodeAndKeepRightAgree.smt2  |   1.106s  |   1.106s  |   0.000s  | 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpecWFNodes.i.dfy.Impl__PivotBetreeSpecWFNodes.__default.ValidMergeWritesInvNodes.smt2  |   3.271s  |   3.271s  |   0.000s  | 0.0%|
|d_fvbkv-Versions-CompositeView_Refines_TSJMap.i.dfy.Impl__CompositeView__Refines__TSJMap.__default.CrashRefines.smt2  |   0.849s  |   0.849s  |   0.000s  | 0.0%|
|d_fvbkv-Versions-CompositeView_Refines_TSJMap.i.dfy.Impl__CompositeView__Refines__TSJMap.__default.JournalInternalRefines.smt2  |   1.341s  |   1.341s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-Multisets.i.dfy.Impl__Multisets.__default.FoldAdditive.smt2                |   2.906s  |   2.906s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-sequences.i.dfy.Impl__Sequences.__default.FlattenAdditive.smt2             |   0.469s  |   0.469s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-sequences.i.dfy.Impl__Sequences.__default.UnflattenFlattenIdentity.smt2    |   0.231s  |   0.231s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-total_order.i.dfy.Impl__Char__Order.__default.FlattenStrictlySorted.smt2   |   0.288s  |   0.288s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-total_order.i.dfy.Impl__Total__Order.__default.FlattenStrictlySorted.smt2  |   0.438s  |   0.438s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-total_order.i.dfy.Impl__Total__Order.__default.strictlySortedInsert.smt2   |   0.503s  |   0.503s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-total_order.i.dfy.Impl__Uint32__Order.__default.FlattenStrictlySorted.smt2  |   0.302s  |   0.302s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-total_order.i.dfy.Impl__Uint64__Order.__default.FlattenStrictlySorted.smt2  |   0.303s  |   0.303s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.SplitOneInList.smt2         |   2.463s  |   2.463s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.WeightKeySeqIs.smt2         |   1.091s  |   1.091s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketModel.i.dfy.Impl__BucketModel.__default.mergeToChildrenIterSlack_split0.smt2  |   1.259s  |   1.259s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.WMWeightBucketListFlush.smt2  |   1.011s  |   1.011s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.WeightBucketListItemFlushSingletonOrEmpty.smt2  |   2.488s  |   2.488s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.WeightMessageListFlatten.smt2  |   0.737s  |   0.737s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.WeightSplitBucketInList.smt2  |   0.631s  |   0.631s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-KMBPKVOps.i.dfy.Impl__KMBPKVOps.__default.IMessagesInverse.smt2         |   0.983s  |   0.983s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-KMBPKVOps.i.dfy.Impl__KMBPKVOps.__default.ToPkv.smt2                    |  10.629s  |  10.629s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-KMBPKVOps.i.dfy.Impl__KMBPKVOps.__default.canAppendMessagesIterate.smt2  |   1.445s  |   1.445s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.CheckWellformed__DynamicPkv.__default.PKVISeq.smt2       |   1.007s  |   1.007s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.psaTotalLengthBound.smt2        |   0.768s  |   0.768s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKVMarshalling.i.dfy.Impl__PackedKVMarshalling.__default.ComputeWF.smt2  |   0.892s  |   0.892s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKVMarshalling.i.dfy.Impl__PackedKVMarshalling.__default.SizeOfVPackedStringArrayIsKeyListWeight.smt2  |   1.407s  |   1.407s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.PivotIndexes.smt2  |   0.528s  |   0.528s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.psaAppendSeqAdditive.smt2  |   0.590s  |   0.590s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-BitmapImpl.i.dfy.Impl__BitmapImpl.Bitmap.Set.smt2                |   0.269s  |   0.269s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-BitmapImpl.i.dfy.Impl__BitmapImpl.Bitmap.Unset.smt2              |   0.238s  |   0.238s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.InsertLeafIsCorrect.smt2  |   2.379s  |   2.379s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.SplitChildOfIndexPreservesInterpretationB.smt2  |   3.614s  |   3.614s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.SplitIndexInterpretation1.smt2  |  20.043s  |  20.043s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.SplitIndexInterpretation2.smt2  |   3.259s  |   3.259s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-KMBtree.i.dfy.Impl__KMBtree.__default.InsertIndexSelectAndPrepareChild.smt2  |   2.031s  |   2.031s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-KMBtree.i.dfy.Impl__KMBtree.__default.SplitIndex.smt2            |  20.043s  |  20.043s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-KMBtree.i.dfy.Impl__KMBtreeModel.__default.InterpretationsDisjointUnion.smt2  |   2.430s  |   2.430s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-KMBtree.i.dfy.Impl__KMBtreeModel.__default.SplitIndexInterpretation1.smt2  |   4.442s  |   4.442s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.InsertIndexChildNotFull.smt2  |   6.644s  |   6.644s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.InsertIndexSelectAndPrepareChild.smt2  |   3.409s  |   3.409s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SplitIndex.smt2  |  20.043s  |  20.043s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__TestBtreeModel.__default.SplitIndexInterpretation1.smt2  |   3.257s  |   3.257s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__TestMutableBtree.__default.SplitIndex.smt2  |  18.480s  |  18.480s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableMapModel.i.dfy.CheckWellformed__MutableMapModel.__default.IterInc.smt2  |   4.079s  |   4.079s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableMapModel.i.dfy.CheckWellformed__MutableMapModel.__default.iterToNext.smt2  |   0.622s  |   0.622s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableMapModel.i.dfy.Impl__MutableMapModel.__default.MapFromStorageProperties.smt2  |   0.707s  |   0.707s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableMapModel.i.dfy.Impl__MutableMapModel.__default.UpdatePreservesSimpleIter.smt2  |   1.749s  |   1.749s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.CheckWellformed__GenericMarshalling.__default.parse__Val.smt2  |   0.504s  |   0.504s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__div__ind.smt2                |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-Util.i.dfy.CheckWellformed__Common____Util__i.__default.Uint64ToSeqByte.smt2  |   2.038s  |   2.038s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Math-mul.i.dfy.Impl__Math____mul__i.__default.lemma__mul__equality__converse.smt2  |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Math-mul.i.dfy.Impl__Math____mul__i.__default.lemma__mul__one__to__one__pos.smt2  |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|d_komodo-verified-alloc_spare.gen.dfyImpl___module.__default.va__lemma__kom__smc__alloc__spare.smt2  |  20.049s  |  20.049s  |   0.000s  | 0.0%|
|d_komodo-verified-allocate_page.gen.dfyCheckWellformed___module.__default.va__lemma__addrspace__incref.smt2  |   3.126s  |   3.126s  |   0.000s  | 0.0%|
|d_komodo-verified-allocate_page.gen.dfyCheckWellformed___module.__default.va__lemma__allocate__page__success.smt2  |   8.043s  |   8.043s  |   0.000s  | 0.0%|
|d_komodo-verified-attest.gen.dfyCheckWellformed___module.__default.va__lemma__compute__hmac.smt2  |   7.141s  |   7.141s  |   0.000s  | 0.0%|
|d_komodo-verified-attest.gen.dfyCheckWellformed___module.__default.va__lemma__svc__returning__attest__inner.smt2  |   2.435s  |   2.435s  |   0.000s  | 0.0%|
|d_komodo-verified-attest_helpers.gen.dfyCheckWellformed___module.__default.va__lemma__load__attestion__key__inner.smt2  |  20.055s  |  20.055s  |   0.000s  | 0.0%|
|d_komodo-verified-attest_helpers.gen.dfyImpl___module.__default.va__lemma__unstack__all__regs.smt2  |  20.053s  |  20.053s  |   0.000s  | 0.0%|
|d_komodo-verified-attest_input.gen.dfyImpl___module.__default.va__lemma__arrange__attestation__input.smt2  |  11.149s  |  11.149s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.gen.dfyCheckWellformed___module.__default.va__lemma__pre__entry__resume.smt2  |   1.668s  |   1.668s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.gen.dfyCheckWellformed___module.__default.va__lemma__stack__banked__regs1.smt2  |   1.350s  |   1.350s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.gen.dfyCheckWellformed___module.__default.va__lemma__stack__banked__regs2.smt2  |   5.026s  |   5.026s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.gen.dfyCheckWellformed___module.__default.va__lemma__stack__banked__regs3.smt2  |   4.684s  |   4.684s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.gen.dfyCheckWellformed___module.__default.va__lemma__switch__addrspace.smt2  |   1.400s  |   1.400s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.gen.dfyCheckWellformed___module.__default.va__lemma__unstack__banked__regs3.smt2  |   5.704s  |   5.704s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.gen.dfyImpl___module.__default.lemma__stackunstack__banked__regs.smt2  |  11.545s  |  11.545s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.gen.dfyImpl___module.__default.va__lemma__enclaveexecution__loop.smt2  |  20.062s  |  20.062s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.gen.dfyImpl___module.__default.va__lemma__stack__banked__regs2.smt2  |  20.057s  |  20.057s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.gen.dfyImpl___module.__default.va__lemma__unstack__banked__regs1.smt2  |  20.049s  |  20.049s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.gen.dfyImpl___module.__default.va__lemma__unstack__banked__regs_split0.smt2  |  20.045s  |  20.045s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.i.dfyCheckWellformed___module.__default.lemma__evalMOVSPCLRUC__inner.smt2  |   1.736s  |   1.736s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.i.dfyImpl___module.__default.lemma__partialEnclaveExecution__append.smt2  |   2.469s  |   2.469s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.i.dfyImpl___module.__default.lemma__partialEnclaveExecution__done.smt2  |   2.613s  |   2.613s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.i.dfyImpl___module.__default.lemma__userExecutionPreservesStack.smt2  |   5.397s  |   5.397s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.i.dfyImpl___module.__default.lemma__userExecutionUpdatesPageDb_split0.smt2  |   1.787s  |   1.787s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.i.dfyImpl___module.__default.lemma__validEnclaveExecutionStep__PageDb.smt2  |   4.725s  |   4.725s  |   0.000s  | 0.0%|
|d_komodo-verified-exception_handlers.gen.dfyCheckWellformed___module.__default.va__lemma__CPSID__IAF.smt2  |   5.282s  |   5.282s  |   0.000s  | 0.0%|
|d_komodo-verified-exception_handlers.gen.dfyCheckWellformed___module.__default.va__lemma__save__disp__context.smt2  |   1.849s  |   1.849s  |   0.000s  | 0.0%|
|d_komodo-verified-exception_handlers.gen.dfyImpl___module.__default.va__lemma__CPSID__IAF.smt2  |  20.047s  |  20.047s  |   0.000s  | 0.0%|
|d_komodo-verified-exception_handlers.gen.dfyImpl___module.__default.va__lemma__switch__to__monitor.smt2  |  10.125s  |  10.125s  |   0.000s  | 0.0%|
|d_komodo-verified-exhandler_state.i.dfyCheckWellformed___module.__default.lemma__SVCFIQNestedExceptionIsCorrect.smt2  |  11.337s  |  11.337s  |   0.000s  | 0.0%|
|d_komodo-verified-exhandler_state.i.dfyImpl___module.__default.lemma__KomUserEntryPrecond__Preserved.smt2  |  18.606s  |  18.606s  |   0.000s  | 0.0%|
|d_komodo-verified-exhandler_state.i.dfyImpl___module.__default.lemma__PrivModeExceptionHandlersAreCorrect.smt2  |  20.053s  |  20.053s  |   0.000s  | 0.0%|
|d_komodo-verified-finalise.gen.dfyCheckWellformed___module.__default.lemma__kom__smc__finalise__success__helper1.smt2  |  10.347s  |  10.347s  |   0.000s  | 0.0%|
|d_komodo-verified-init_l2ptable.gen.dfyCheckWellformed___module.__default.va__lemma__init__l2ptable__success.smt2  |   2.401s  |   2.401s  |   0.000s  | 0.0%|
|d_komodo-verified-init_l2ptable.gen.dfyCheckWellformed___module.__default.va__lemma__zero__l2__page.smt2  |   8.830s  |   8.830s  |   0.000s  | 0.0%|
|d_komodo-verified-init_l2ptable.gen.dfyImpl___module.__default.lemma__SecurePage.smt2       |   3.331s  |   3.331s  |   0.000s  | 0.0%|
|d_komodo-verified-init_l2ptable.gen.dfyImpl___module.__default.va__lemma__init__l2ptable__success_split0.smt2  |  12.000s  |  12.000s  |   0.000s  | 0.0%|
|d_komodo-verified-kom_utils.gen.dfyImpl___module.__default.va__abstract__load__32__bit__const.smt2  |  20.036s  |  20.036s  |   0.000s  | 0.0%|
|d_komodo-verified-map_common.gen.dfyCheckWellformed___module.__default.lemma__update__l2pte__helper1.smt2  |   8.716s  |   8.716s  |   0.000s  | 0.0%|
|d_komodo-verified-map_common.gen.dfyImpl___module.__default.lemma__update__l2pte__helper1.smt2  |  13.286s  |  13.286s  |   0.000s  | 0.0%|
|d_komodo-verified-map_common.gen.dfyImpl___module.__default.va__lemma__mkL2Pte__secure.smt2  |   8.979s  |   8.979s  |   0.000s  | 0.0%|
|d_komodo-verified-map_insecure.gen.dfyImpl___module.__default.va__lemma__mkl2pte__insecure.smt2  |   5.737s  |   5.737s  |   0.000s  | 0.0%|
|d_komodo-verified-map_insecure.gen.dfyImpl___module.__default.va__lemma__phys__page__is__insecure__ram.smt2  |  20.044s  |  20.044s  |   0.000s  | 0.0%|
|d_komodo-verified-map_secure.gen.dfyImpl___module.__default.lemma__preserve__contentsOfPhysPage.smt2  |   4.728s  |   4.728s  |   0.000s  | 0.0%|
|d_komodo-verified-memset.gen.dfyCheckWellformed___module.__default.va__lemma__memcpy.smt2   |   7.281s  |   7.281s  |   0.000s  | 0.0%|
|d_komodo-verified-memset.gen.dfyCheckWellformed___module.__default.va__lemma__memcpy__bare.smt2  |   6.783s  |   6.783s  |   0.000s  | 0.0%|
|d_komodo-verified-memset.gen.dfyImpl___module.__default.va__lemma__memcpy.smt2              |   3.183s  |   3.183s  |   0.000s  | 0.0%|
|d_komodo-verified-pagedb.i.dfyImpl___module.__default.AllButOnePagePreserving.smt2          |   6.820s  |   6.820s  |   0.000s  | 0.0%|
|d_komodo-verified-psrbits.i.dfyImpl___module.__default.lemma__update__psr__f.smt2           |   2.410s  |   2.410s  |   0.000s  | 0.0%|
|d_komodo-verified-ptables.i.dfyImpl___module.__default.lemma__OnlyPTPagesInHwPTable.smt2    |   7.567s  |   7.567s  |   0.000s  | 0.0%|
|d_komodo-verified-ptables.i.dfyImpl___module.__default.lemma__memstatecontainspage.smt2     |   1.821s  |   1.821s  |   0.000s  | 0.0%|
|d_komodo-verified-ptables.i.dfyImpl___module.__default.lemma__ptablesmatch_split11.smt2     |   1.897s  |   1.897s  |   0.000s  | 0.0%|
|d_komodo-verified-ptebits.i.dfyImpl___module.__default.lemma__ARM__L2PTE_split0.smt2        |   0.671s  |   0.671s  |   0.000s  | 0.0%|
|d_komodo-verified-ptebits.i.dfyImpl___module.__default.lemma__l2indexFromMapping__shifts.smt2  |   0.824s  |   0.824s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-conf_ni.i.dfyImpl___module.__default.lemma__conf__ni.smt2         |   3.751s  |   3.751s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-conf_ni.i.dfyImpl___module.__default.lemma__initAddrspace__loweq__pdb.smt2  |   5.733s  |   5.733s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-conf_ni.i.dfyImpl___module.__default.lemma__mapSecure__loweq__pdb__success.smt2  |  20.065s  |  20.065s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyCheckWellformed___module.__default.lemma__svcHandled__conf__not__atkr.smt2  |  20.043s  |  20.043s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__data__eqpdb__to__addrs.smt2  |   4.681s  |   4.681s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__data__page__eqdb__to__addrs.smt2  |   1.892s  |   1.892s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__svcHandled__conf__not__atkr.smt2  |  20.047s  |  20.047s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__userMemEquiv__atkr.smt2  |   7.542s  |   7.542s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__userStatesEquiv__atkr.smt2  |   5.835s  |   5.835s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-integ_ni.i.dfyImpl___module.__default.lemma__enc__ni.smt2         |   1.550s  |   1.550s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-integ_ni_entry.i.dfyImpl___module.__default.lemma__enter__enc__ni.smt2  |   3.972s  |   3.972s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-sec_prop_util.i.dfyImpl___module.__default.lemma__maybeContents__insec__ni.smt2  |   1.509s  |   1.509s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-bit-vector-lemmas.i.dfyImpl___module.__default.lemma__Ch.smt2         |   0.558s  |   0.558s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-bit-vector-lemmas.i.dfyImpl___module.__default.lemma__Maj.smt2        |   0.627s  |   0.627s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-hmac.gen.dfyCheckWellformed___module.__default.va__lemma__hmac__inner.smt2  |   1.972s  |   1.972s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-hmac.gen.dfyImpl___module.__default.va__lemma__hmac__inner__prep__input.smt2  |   4.911s  |   4.911s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-hmac.gen.dfyImpl___module.__default.va__lemma__hmac__outer.smt2       |  20.053s  |  20.053s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-sha256-api.gen.dfyImpl___module.__default.va__abstract__sha256__init.smt2  |   8.571s  |   8.571s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-sha256-api.gen.dfyImpl___module.__default.va__refined__sha256__finalize.smt2  |  17.785s  |  17.785s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-sha256-api.gen.dfyImpl___module.__default.va__refined__sha256__one__shot.smt2  |  20.056s  |  20.056s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-sha256-block-data-order.gen.dfyImpl___module.__default.va__abstract__sha256__block__data__order__inner.smt2  |  20.053s  |  20.053s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-sha256.i.dfyImpl___module.__default.lemma__ArrayOffsetConcatenation.smt2  |   0.485s  |   0.485s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-sha256.i.dfyImpl___module.__default.lemma__ConcatenateSeqs__Adds.smt2  |   0.602s  |   0.602s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-sha256.i.dfyImpl___module.__default.lemma__Trace__stitching.smt2      |   0.658s  |   0.658s  |   0.000s  | 0.0%|
|d_komodo-verified-smcapi.i.dfyCheckWellformed___module.__default.kom__smc__map__measure__helper2.smt2  |   3.033s  |   3.033s  |   0.000s  | 0.0%|
|d_komodo-verified-smcapi.i.dfyImpl___module.__default.AllButOnePageOrStackPreserving.smt2   |   7.091s  |   7.091s  |   0.000s  | 0.0%|
|d_komodo-verified-smcapi.i.dfyImpl___module.__default.initDispatcherPreservesPageDBValidity.smt2  |   7.752s  |   7.752s  |   0.000s  | 0.0%|
|d_komodo-verified-smcapi.i.dfyImpl___module.__default.kom__smc__map__measure__helper2.smt2  |   1.870s  |   1.870s  |   0.000s  | 0.0%|
|d_komodo-verified-smcapi.i.dfyImpl___module.__default.lemma__ConcatenateSeqs__Adds_k.smt2   |   1.224s  |   1.224s  |   0.000s  | 0.0%|
|d_komodo-verified-smcapi.i.dfyImpl___module.__default.lemma__validEnclaveExecutionStep__validPageDb.smt2  |   8.048s  |   8.048s  |   0.000s  | 0.0%|
|d_komodo-verified-smcapi.i.dfyImpl___module.__default.mapSecurePreservesPageDBValidity.smt2  |  20.053s  |  20.053s  |   0.000s  | 0.0%|
|d_komodo-verified-svc_handlers.gen.dfyCheckWellformed___module.__default.lemma__svc__returning__verify__step0__helper.smt2  |   3.954s  |   3.954s  |   0.000s  | 0.0%|
|d_komodo-verified-svc_handlers.gen.dfyCheckWellformed___module.__default.va__lemma__svc__map__data__success.smt2  |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|d_komodo-verified-svc_handlers.gen.dfyCheckWellformed___module.__default.va__lemma__svc__returning__verify__step0.smt2  |  13.003s  |  13.003s  |   0.000s  | 0.0%|
|d_komodo-verified-svc_handlers.gen.dfyCheckWellformed___module.__default.va__lemma__svc__unmap__data.smt2  |   2.599s  |   2.599s  |   0.000s  | 0.0%|
|d_komodo-verified-svc_handlers.gen.dfyImpl___module.__default.lemma__svc__returning__WordAlignedStack.smt2  |   7.737s  |   7.737s  |   0.000s  | 0.0%|
|d_komodo-verified-svc_handlers.gen.dfyImpl___module.__default.va__lemma__monvaddr__page__impl.smt2  |  13.884s  |  13.884s  |   0.000s  | 0.0%|
|d_komodo-verified-svc_handlers.gen.dfyImpl___module.__default.va__lemma__rng__read.smt2     |  20.030s  |  20.030s  |   0.000s  | 0.0%|
|d_komodo-verified-valedecls.gen.dfyImpl___module.__default.va__lemma__MSR.smt2              |   1.220s  |   1.220s  |   0.000s  | 0.0%|
|d_komodo-verified-verify.gen.dfyCheckWellformed___module.__default.va__lemma__svc__returning__verify__inner.smt2  |   6.472s  |   6.472s  |   0.000s  | 0.0%|
|d_komodo-verified-verify_input.gen.dfyImpl___module.__default.va__lemma__arrange__verification__input.smt2  |   5.936s  |   5.936s  |   0.000s  | 0.0%|
|d_lvbkv-Betree-AsyncBetree_Refines_AsyncMap.i.dfy.Impl__AsyncBetree__Refines__AsyncMap.__default.RefinesQueryEndStep.smt2  |   7.622s  |   7.622s  |   0.000s  | 0.0%|
|d_lvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.FlushStepPreservesInvariant.smt2   |  20.043s  |  20.043s  |   0.000s  | 0.0%|
|d_lvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.InsertMessagePreservesLookupsPut.smt2  |  11.429s  |  11.429s  |   0.000s  | 0.0%|
|d_lvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectPreservesRootHasNoPred.smt2  |  10.575s  |  10.575s  |   0.000s  | 0.0%|
|d_lvbkv-Betree-Betree_Refines_Map.i.dfy.Impl__Betree__Refines__Map.__default.RefinesNextStep.smt2  |  20.037s  |  20.037s  |   0.000s  | 0.0%|
|d_lvbkv-Betree-Betree_Refines_Map.i.dfy.Impl__Betree__Refines__Map.__default.SuccQueryStepRefinesMap.smt2  |  10.130s  |  10.130s  |   0.000s  | 0.0%|
|d_lvbkv-BlockCacheSystem-BetreeJournalSystem_Refines_ThreeStateVersionedMap.i.dfy.Impl__BetreeJournalSystem__Refines__ThreeStateVersionedMap.__default.RefinesNext.smt2  |   3.305s  |   3.305s  |   0.000s  | 0.0%|
|d_lvbkv-BlockCacheSystem-BetreeSystem_Refines_StatesViewPivotBetree.i.dfy.Impl__BetreeSystem__Refines__StatesViewPivotBetree.__default.CrashStepRefines.smt2  |   2.524s  |   2.524s  |   0.000s  | 0.0%|
|d_lvbkv-BlockCacheSystem-BlockCache.i.dfy.Impl__BlockCache.__default.AllocStepPreservesInv.smt2  |   2.010s  |   2.010s  |   0.000s  | 0.0%|
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.AllocStepPreservesInv.smt2  |  20.065s  |  20.065s  |   0.000s  | 0.0%|
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.WriteBackIndirectionTableReqStepPreservesInv.smt2  |   4.804s  |   4.804s  |   0.000s  | 0.0%|
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.WriteBackNodeRespStepPreservesGraphs.smt2  |  20.080s  |  20.080s  |   0.000s  | 0.0%|
|d_lvbkv-BlockCacheSystem-DiskLayout.i.dfy.Impl__DiskLayout.__default.ValidNodeAddrMul.smt2  |   0.188s  |   0.188s  |   0.000s  | 0.0%|
|d_lvbkv-BlockCacheSystem-JournalInterval.i.dfy.Impl__JournalIntervals.__default.Disk__Journal__Read2.smt2  |   0.389s  |   0.389s  |   0.000s  | 0.0%|
|d_lvbkv-BlockCacheSystem-JournalInterval.i.dfy.Impl__JournalIntervals.__default.concatFoldAdditive.smt2  |   0.588s  |   0.588s  |   0.000s  | 0.0%|
|d_lvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.NextStepPreservesInv.smt2  |   3.184s  |   3.184s  |   0.000s  | 0.0%|
|d_lvbkv-ByteBlockCacheSystem-ByteSystem_Refines_BetreeJournalSystem.i.dfy.Impl__ByteSystem__Refines__BetreeJournalSystem.__default.RefinesNext.smt2  |  13.117s  |  13.117s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-BookkeepingModel.i.dfy.Impl__BookkeepingModel.__default.allocCorrect.smt2      |  20.055s  |  20.055s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-BookkeepingModel.i.dfy.Impl__BookkeepingModel.__default.writeCorrect.smt2      |  11.519s  |  11.519s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-CommitterImpl.i.dfy.Impl__CommitterImpl.Committer.FinishLoadingOtherPhase.smt2  |   4.365s  |   4.365s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-CoordinationImpl.i.dfy.Impl__CoordinationImpl.__default.succ.smt2              |  20.053s  |  20.053s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.writeNodeResponse.smt2                     |  11.217s  |  11.217s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-InsertImpl.i.dfy.Impl__InsertImpl.__default.insert.smt2                        |   7.512s  |   7.512s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-JournalistImpl.i.dfy.Impl__JournalistImpl.Journalist.freeze.smt2               |   1.247s  |   1.247s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-JournalistImpl.i.dfy.Impl__JournalistImpl.Journalist.packageInMemoryJournal.smt2  |   0.745s  |   0.745s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-JournalistImpl.i.dfy.Impl__JournalistImpl.Journalist.parseJournals.smt2        |   0.889s  |   0.889s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.parsesFromStuff.smt2  |   0.600s  |   0.600s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.nodeToVal.smt2           |   8.302s  |   8.302s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-NodeImpl.i.dfy.Impl__NodeImpl.Node.UpdateSlot.smt2                             |   1.445s  |   1.445s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-SyncImpl.i.dfy.Impl__SyncImpl.__default.TryToWriteBlock.smt2                   |  20.056s  |  20.056s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-SyncImpl.i.dfy.Impl__SyncImpl.__default.sync.smt2                              |  20.059s  |  20.059s  |   0.000s  | 0.0%|
|d_lvbkv-MapSpec-TSJ.i.dfy.Impl__TSJ.__default.ExtendLog2StepPreservesInv.smt2               |   1.018s  |   1.018s  |   0.000s  | 0.0%|
|d_lvbkv-MapSpec-TSJMap_Refines_ThreeStateVersionedMap.i.dfy.Impl__TSJMap__Refines__ThreeStateVersionedMap.__default.RefinesMove3.smt2  |   0.536s  |   0.536s  |   0.000s  | 0.0%|
|d_lvbkv-MapSpec-TSJMap_Refines_ThreeStateVersionedMap.i.dfy.Impl__TSJMap__Refines__ThreeStateVersionedMap.__default.RefinesStutter.smt2  |   1.013s  |   1.013s  |   0.000s  | 0.0%|
|d_lvbkv-MapSpec-TSJMap_Refines_ThreeStateVersionedMap.i.dfy.Impl__TSJMap__Refines__ThreeStateVersionedMap.__default.apply__eq__apply__uiops.smt2  |   0.452s  |   0.452s  |   0.000s  | 0.0%|
|d_lvbkv-PivotBetree-PivotBetree.i.dfy.Impl__PivotBetree.__default.StutterStepRefines.smt2   |   2.398s  |   2.398s  |   0.000s  | 0.0%|
|d_lvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.Impl__PivotBetreeSpecRefinement.__default.RefinesLookup.smt2  |   8.065s  |   8.065s  |   0.000s  | 0.0%|
|d_lvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.Impl__PivotBetreeSpecRefinement.__default.RefinesValidFlush.smt2  |   9.674s  |   9.674s  |   0.000s  | 0.0%|
|d_lvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.Impl__PivotBetreeSpecRefinement.__default.SplitRouteNewChild.smt2  |   7.801s  |   7.801s  |   0.000s  | 0.0%|
|d_lvbkv-PivotBetree-PivotBetreeSpecWFNodes.i.dfy.Impl__PivotBetreeSpecWFNodes.__default.WFApplyRepivot.smt2  |   0.852s  |   0.852s  |   0.000s  | 0.0%|
|d_lvbkv-PivotBetree-TSJPivotBetree.i.dfy.Impl__TSJPivotBetree.__default.NextStepPreservesInv.smt2  |   1.340s  |   1.340s  |   0.000s  | 0.0%|
|d_lvbkv-Versions-CompositeView.i.dfy.Impl__CompositeView.__default.AdvancePreservesInv.smt2  |   1.080s  |   1.080s  |   0.000s  | 0.0%|
|d_lvbkv-Versions-CompositeView.i.dfy.Impl__CompositeView.__default.FreezePreservesInv.smt2  |   0.686s  |   0.686s  |   0.000s  | 0.0%|
|d_lvbkv-Versions-CompositeView_Refines_TSJMap.i.dfy.Impl__CompositeView__Refines__TSJMap.__default.JournalInternalRefines.smt2  |   1.802s  |   1.802s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-Multisets.i.dfy.Impl__Multisets.__default.ApplySeq.smt2                    |   3.570s  |   3.570s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-Multisets.i.dfy.Impl__Multisets.__default.FoldAdditive.smt2                |  12.180s  |  12.180s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-Sequences.i.dfy.CheckWellformed__Sequences.__default.RemoveOneValue.smt2   |   0.377s  |   0.377s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-Sequences.i.dfy.Impl__Sequences.__default.UnflattenIndexIsCorrect.smt2     |   0.293s  |   0.293s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-total_order.i.dfy.Impl__Total__Order.__default.FlattenStrictlySorted.smt2  |   0.676s  |   0.676s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-total_order.i.dfy.Impl__Total__Order.__default.strictlySortedInsert.smt2   |   2.649s  |   2.649s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.GetMiddleKey.smt2           |   1.245s  |   1.245s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.WeightKeyListFlatten.smt2  |   0.844s  |   0.844s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.WeightSplitBucketInList.smt2  |   1.177s  |   1.177s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-BucketsLib.i.dfy.Impl__BucketsLib.__default.WFProperMergeBucketsInList.smt2  |   3.849s  |   3.849s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-BucketsLib.i.dfy.Impl__BucketsLib.__default.WFSplitBucketInList.smt2    |   0.741s  |   0.741s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-LKMBPKVOps.i.dfy.Impl__LKMBPKVOps.__default.IMessagesInverse.smt2       |   1.083s  |   1.083s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-LKMBPKVOps.i.dfy.Impl__LKMBPKVOps.__default.LeafFillDpkv.smt2           |  11.589s  |  11.589s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-LKMBPKVOps.i.dfy.Impl__LKMBPKVOps.__default.ToPkv.smt2                  |   1.771s  |   1.771s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-LKMBPKVOps.i.dfy.Impl__LKMBPKVOps.__default.canAppendKeysIterate.smt2   |   2.216s  |   2.216s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-LKMBPKVOps.i.dfy.Impl__LKMBPKVOps.__default.canAppendMessagesIterate.smt2  |   2.513s  |   2.513s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.CheckWellformed__DynamicPkv.__default.PKVISeq.smt2       |   1.019s  |   1.019s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.CheckWellformed__PackedKV.__default.LastKey.smt2         |   0.810s  |   0.810s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.__default.MergeToChildren.smt2          |   3.726s  |   3.726s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.__default.PartialFlush.smt2             |   2.178s  |   2.178s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.DefineIMessage.smt2             |   0.778s  |   0.778s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.SplitRight.smt2                 |   1.270s  |   1.270s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.psaTotalLengthBound.smt2        |   0.871s  |   0.871s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedStringArray.i.dfy.CheckWellformed__PackedStringArray.__default.psaAppendSeq.smt2  |   0.987s  |   0.987s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.DynamicPsa.FromSeq.smt2  |   0.771s  |   0.771s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.PsaSuffix.smt2  |   0.547s  |   0.547s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Checksums-CRC32CArrayImpl.i.dfy.Impl__CRC32__C__Array__Impl.__default.advanced__of__iterated__intrinsic.smt2  |   0.473s  |   0.473s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Checksums-CRC32CImpl.i.dfy.Impl__CRC32__C__Impl.__default.advanced__of__iterated__intrinsic.smt2  |   0.375s  |   0.375s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Checksums-CRC32C_Lemmas.i.dfy.Impl__CRC32C__Lemmas.__default.advances__bytes__refl.smt2  |   0.335s  |   0.335s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Checksums-F2_X_Lemmas.i.dfy.Impl__F2__X__Lemmas.__default.p__qr__partial.smt2   |  12.869s  |  12.869s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Checksums-F2_X_Lemmas.i.dfy.Impl__F2__X__Lemmas.__default.pq__r__partial.smt2   |   6.745s  |   6.745s  |   0.000s  | 0.0%|
|d_lvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.InterpretationDelegation.smt2  |   0.487s  |   0.487s  |   0.000s  | 0.0%|
|d_lvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.InterpretationInheritance.smt2  |   0.472s  |   0.472s  |   0.000s  | 0.0%|
|d_lvbkv-lib-DataStructures-KMBtree.i.dfy.Impl__KMBtreeModel.__default.InterpretationDelegation.smt2  |   0.539s  |   0.539s  |   0.000s  | 0.0%|
|d_lvbkv-lib-DataStructures-KMBtree.i.dfy.Impl__KMBtreeModel.__default.InterpretationInheritance.smt2  |   6.977s  |   6.977s  |   0.000s  | 0.0%|
|d_lvbkv-lib-DataStructures-KMBtree.i.dfy.Impl__KMBtreeModel.__default.InterpretationsDisjointUnion.smt2  |   1.047s  |   1.047s  |   0.000s  | 0.0%|
|d_lvbkv-lib-DataStructures-KMBtree.i.dfy.Impl__LKMBtree.__default.InsertLeaf.smt2           |   2.155s  |   2.155s  |   0.000s  | 0.0%|
|d_lvbkv-lib-DataStructures-LinearContentMutableMap.i.dfy.Impl__LinearContentMutableMap.__default.FixedSizeInsertEntry.smt2  |  20.043s  |  20.043s  |   0.000s  | 0.0%|
|d_lvbkv-lib-DataStructures-LinearContentMutableMap.i.dfy.Impl__LinearContentMutableMap.__default.Probe.smt2  |  11.672s  |  11.672s  |   0.000s  | 0.0%|
|d_lvbkv-lib-DataStructures-LinearMutableMap.i.dfy.Impl__LinearMutableMap.__default.UpdateByIter.smt2  |  20.045s  |  20.045s  |   0.000s  | 0.0%|
|d_lvbkv-lib-DataStructures-MutableMapModel.i.dfy.Impl__MutableMapModel.__default.IndexSetMatchesContents.smt2  |  16.590s  |  16.590s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.lemma__parse__Val__view__ByteArray.smt2  |   0.533s  |   0.533s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Marshalling-Util.i.dfy.Impl__Common____Util__i.__default.seqIntoArrayChar.smt2  |   0.345s  |   0.345s  |   0.000s  | 0.0%|
|s_komodo-1435.3.smt2                                                                        |   7.151s  |   7.151s  |   0.000s  | 0.0%|
|s_komodo-1450.0.smt2                                                                        |  20.319s  |  20.319s  |   0.000s  | 0.0%|
|s_komodo-1488.6.smt2                                                                        |  20.754s  |  20.754s  |   0.000s  | 0.0%|
|s_komodo-1493.6.smt2                                                                        |  20.733s  |  20.733s  |   0.000s  | 0.0%|
|s_komodo-1499.4.smt2                                                                        |  20.471s  |  20.471s  |   0.000s  | 0.0%|
|s_komodo-1499.6.smt2                                                                        |  20.600s  |  20.600s  |   0.000s  | 0.0%|
|s_komodo-1504.6.smt2                                                                        |  20.569s  |  20.569s  |   0.000s  | 0.0%|
|s_komodo-1509.6.smt2                                                                        |  20.667s  |  20.667s  |   0.000s  | 0.0%|
</details>
