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
Z3 commit: bc6c38e7d3424b88a505cacba4b268d0774d4547
Z3 branch: bc6c38e7d3424b88a505cacba4b268d0774d4547
Z3 options: "-T:20"
Z3 inputs: inputs/mariposa/stable_core
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
Job tag: bench-mariposa-stable_core
Runner: rise-runner-2
Z3 repo: CanCebeci/z3
Z3 commit: bc6c38e7d3424b88a505cacba4b268d0774d4547
Z3 branch: bc6c38e7d3424b88a505cacba4b268d0774d4547
Z3 options: "-T:20"
Z3 inputs: inputs/mariposa/stable_core
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
|d_fvbkv-Betree-BlockInterface.i.dfy.CheckWellformed__BlockInterface.__default.IsStatePath.smt2  |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|d_fvbkv-Betree-Graph.i.dfy.Impl__Graph.__default.AcyclicGraphImpliesSimplePath.smt2         |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.NewRequestReadNodeDoesntOverlap.smt2  |   0.763s  |   0.763s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-DiskLayout.i.dfy.CheckWellformed__DiskLayout.__default.JournalBackLocation.smt2  |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.CheckWellformed__JournalSystem.__default.FreezeStepPreservesJournals.smt2  |   0.512s  |   0.512s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.Impl__JournalSystem.__default.ProcessWriteSuperblockPreservesJournals.smt2  |   0.799s  |   0.799s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-AsyncDiskModel.s.dfy.CheckWellformed__AsyncDisk.__default.AckRead.smt2  |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CacheImpl.i.dfy.CheckWellformed__CacheImpl.MutCache.Remove.smt2                |   1.238s  |   1.238s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterImpl.i.dfy.CheckWellformed__CommitterImpl.Committer.__ctor.smt2       |   0.687s  |   0.687s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CoordinationModel.i.dfy.CheckWellformed__CoordinationModel.__default.initialization.smt2  |   1.481s  |   1.481s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.ReadSectorCorrect.smt2                   |   1.351s  |   1.351s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-InsertModel.i.dfy.CheckWellformed__InsertModel.__default.insertCorrect.smt2    |   1.288s  |   1.288s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.CheckWellformed__JournalistMarshallingModel.__default.hasChecksums.smt2  |   0.242s  |   0.242s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MainHandlers.i.dfy.CheckWellformed__MainHandlers.__default.InitState.smt2      |   1.954s  |   1.954s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-StateModel.i.dfy.CheckWellformed__StateModel.__default.WFSector.smt2           |   1.141s  |   1.141s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-SuccModel.i.dfy.CheckWellformed__SuccModel.__default.getPathInternal.smt2      |   1.600s  |   1.600s  |   0.000s  | 0.0%|
|d_fvbkv-MapSpec-TSJ.i.dfy.Impl__TSJ.__default.PushSyncStepPreservesInv.smt2                 |   0.187s  |   0.187s  |   0.000s  | 0.0%|
|d_fvbkv-MapSpec-TSJMap_Refines_ThreeStateVersionedMap.i.dfy.Impl__TSJMap__Refines__ThreeStateVersionedMap.__default.apply__path.smt2  |   0.220s  |   0.220s  |   0.000s  | 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupUpperBound.smt2  |   0.416s  |   0.416s  |   0.000s  | 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupVisitsWFNodes.smt2  |   0.410s  |   0.410s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BlockInterface.i.dfy.CheckWellformed__BlockInterface.__default.IsStatePath.smt2  |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|d_fvbkv-Betree-Graph.i.dfy.Impl__Graph.__default.AcyclicGraphImpliesSimplePath.smt2         |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.NewRequestReadNodeDoesntOverlap.smt2  |   0.763s  |   0.763s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-DiskLayout.i.dfy.CheckWellformed__DiskLayout.__default.JournalBackLocation.smt2  |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.CheckWellformed__JournalSystem.__default.FreezeStepPreservesJournals.smt2  |   0.512s  |   0.512s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.Impl__JournalSystem.__default.ProcessWriteSuperblockPreservesJournals.smt2  |   0.799s  |   0.799s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-AsyncDiskModel.s.dfy.CheckWellformed__AsyncDisk.__default.AckRead.smt2  |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CacheImpl.i.dfy.CheckWellformed__CacheImpl.MutCache.Remove.smt2                |   1.238s  |   1.238s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterImpl.i.dfy.CheckWellformed__CommitterImpl.Committer.__ctor.smt2       |   0.687s  |   0.687s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CoordinationModel.i.dfy.CheckWellformed__CoordinationModel.__default.initialization.smt2  |   1.481s  |   1.481s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.ReadSectorCorrect.smt2                   |   1.351s  |   1.351s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-InsertModel.i.dfy.CheckWellformed__InsertModel.__default.insertCorrect.smt2    |   1.288s  |   1.288s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.CheckWellformed__JournalistMarshallingModel.__default.hasChecksums.smt2  |   0.242s  |   0.242s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MainHandlers.i.dfy.CheckWellformed__MainHandlers.__default.InitState.smt2      |   1.954s  |   1.954s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-StateModel.i.dfy.CheckWellformed__StateModel.__default.WFSector.smt2           |   1.141s  |   1.141s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-SuccModel.i.dfy.CheckWellformed__SuccModel.__default.getPathInternal.smt2      |   1.600s  |   1.600s  |   0.000s  | 0.0%|
|d_fvbkv-MapSpec-TSJ.i.dfy.Impl__TSJ.__default.PushSyncStepPreservesInv.smt2                 |   0.187s  |   0.187s  |   0.000s  | 0.0%|
|d_fvbkv-MapSpec-TSJMap_Refines_ThreeStateVersionedMap.i.dfy.Impl__TSJMap__Refines__ThreeStateVersionedMap.__default.apply__path.smt2  |   0.220s  |   0.220s  |   0.000s  | 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupUpperBound.smt2  |   0.416s  |   0.416s  |   0.000s  | 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupVisitsWFNodes.smt2  |   0.410s  |   0.410s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BlockInterface.i.dfy.CheckWellformed__BlockInterface.__default.IsStatePath.smt2  |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|d_fvbkv-Betree-Graph.i.dfy.Impl__Graph.__default.AcyclicGraphImpliesSimplePath.smt2         |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.NewRequestReadNodeDoesntOverlap.smt2  |   0.763s  |   0.763s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-DiskLayout.i.dfy.CheckWellformed__DiskLayout.__default.JournalBackLocation.smt2  |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.CheckWellformed__JournalSystem.__default.FreezeStepPreservesJournals.smt2  |   0.512s  |   0.512s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.Impl__JournalSystem.__default.ProcessWriteSuperblockPreservesJournals.smt2  |   0.799s  |   0.799s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-AsyncDiskModel.s.dfy.CheckWellformed__AsyncDisk.__default.AckRead.smt2  |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CacheImpl.i.dfy.CheckWellformed__CacheImpl.MutCache.Remove.smt2                |   1.238s  |   1.238s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterImpl.i.dfy.CheckWellformed__CommitterImpl.Committer.__ctor.smt2       |   0.687s  |   0.687s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CoordinationModel.i.dfy.CheckWellformed__CoordinationModel.__default.initialization.smt2  |   1.481s  |   1.481s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.ReadSectorCorrect.smt2                   |   1.351s  |   1.351s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-InsertModel.i.dfy.CheckWellformed__InsertModel.__default.insertCorrect.smt2    |   1.288s  |   1.288s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.CheckWellformed__JournalistMarshallingModel.__default.hasChecksums.smt2  |   0.242s  |   0.242s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MainHandlers.i.dfy.CheckWellformed__MainHandlers.__default.InitState.smt2      |   1.954s  |   1.954s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-StateModel.i.dfy.CheckWellformed__StateModel.__default.WFSector.smt2           |   1.141s  |   1.141s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-SuccModel.i.dfy.CheckWellformed__SuccModel.__default.getPathInternal.smt2      |   1.600s  |   1.600s  |   0.000s  | 0.0%|
|d_fvbkv-MapSpec-TSJ.i.dfy.Impl__TSJ.__default.PushSyncStepPreservesInv.smt2                 |   0.187s  |   0.187s  |   0.000s  | 0.0%|
|d_fvbkv-MapSpec-TSJMap_Refines_ThreeStateVersionedMap.i.dfy.Impl__TSJMap__Refines__ThreeStateVersionedMap.__default.apply__path.smt2  |   0.220s  |   0.220s  |   0.000s  | 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupUpperBound.smt2  |   0.416s  |   0.416s  |   0.000s  | 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupVisitsWFNodes.smt2  |   0.410s  |   0.410s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BlockInterface.i.dfy.CheckWellformed__BlockInterface.__default.IsStatePath.smt2  |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|d_fvbkv-Betree-Graph.i.dfy.Impl__Graph.__default.AcyclicGraphImpliesSimplePath.smt2         |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.NewRequestReadNodeDoesntOverlap.smt2  |   0.763s  |   0.763s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-DiskLayout.i.dfy.CheckWellformed__DiskLayout.__default.JournalBackLocation.smt2  |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.CheckWellformed__JournalSystem.__default.FreezeStepPreservesJournals.smt2  |   0.512s  |   0.512s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.Impl__JournalSystem.__default.ProcessWriteSuperblockPreservesJournals.smt2  |   0.799s  |   0.799s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-AsyncDiskModel.s.dfy.CheckWellformed__AsyncDisk.__default.AckRead.smt2  |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CacheImpl.i.dfy.CheckWellformed__CacheImpl.MutCache.Remove.smt2                |   1.238s  |   1.238s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterImpl.i.dfy.CheckWellformed__CommitterImpl.Committer.__ctor.smt2       |   0.687s  |   0.687s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CoordinationModel.i.dfy.CheckWellformed__CoordinationModel.__default.initialization.smt2  |   1.481s  |   1.481s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.ReadSectorCorrect.smt2                   |   1.351s  |   1.351s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-InsertModel.i.dfy.CheckWellformed__InsertModel.__default.insertCorrect.smt2    |   1.288s  |   1.288s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.CheckWellformed__JournalistMarshallingModel.__default.hasChecksums.smt2  |   0.242s  |   0.242s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MainHandlers.i.dfy.CheckWellformed__MainHandlers.__default.InitState.smt2      |   1.954s  |   1.954s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-StateModel.i.dfy.CheckWellformed__StateModel.__default.WFSector.smt2           |   1.141s  |   1.141s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-SuccModel.i.dfy.CheckWellformed__SuccModel.__default.getPathInternal.smt2      |   1.600s  |   1.600s  |   0.000s  | 0.0%|
|d_fvbkv-MapSpec-TSJ.i.dfy.Impl__TSJ.__default.PushSyncStepPreservesInv.smt2                 |   0.187s  |   0.187s  |   0.000s  | 0.0%|
|d_fvbkv-MapSpec-TSJMap_Refines_ThreeStateVersionedMap.i.dfy.Impl__TSJMap__Refines__ThreeStateVersionedMap.__default.apply__path.smt2  |   0.220s  |   0.220s  |   0.000s  | 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupUpperBound.smt2  |   0.416s  |   0.416s  |   0.000s  | 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupVisitsWFNodes.smt2  |   0.410s  |   0.410s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.NewRequestReadIndirectionTableIsValid.smt2 |   4.312s |118.0MiB|
|d_komodo-verified-attest_helpers.gen.dfyImpl___module.__default.va__lemma__mem__move__global.smt2 |   2.706s |100.0MiB|
|d_komodo-verified-sha-sha256-body-16-xx.gen.dfyImpl___module.__default.va__refined__Body__16__XXUnroller_split0.smt2 |   2.097s |100.0MiB|
|d_fvbkv-Impl-MainHandlers.i.dfy.CheckWellformed__MainHandlers.__default.InitState.smt2     |   1.954s |146.0MiB|
|d_komodo-verified-kom_common.i.dfyImpl___module.__default.lemma__ValidMemRangeExPageTable__persists.smt2 |   1.681s |64.984MiB|
|d_lvbkv-Impl-CoordinationImpl.i.dfy.Impl__CoordinationImpl.__default.pushSync.smt2         |   1.679s |136.0MiB|
|d_fvbkv-Impl-SuccModel.i.dfy.CheckWellformed__SuccModel.__default.getPathInternal.smt2     |   1.600s |99.408MiB|
|d_komodo-verified-kom_utils.gen.dfyImpl___module.__default.va__lemma__page__monvaddr__impl.smt2 |   1.546s |64.508MiB|
|d_fvbkv-Impl-CoordinationModel.i.dfy.CheckWellformed__CoordinationModel.__default.initialization.smt2 |   1.481s |98.0MiB|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.ReadSectorCorrect.smt2                  |   1.351s |93.716MiB|
|d_lvbkv-Impl-SplitModel.i.dfy.CheckWellformed__SplitModel.__default.lemmaChildrenConditionsCutoffNode.smt2 |   1.300s |96.28MiB|
|d_lvbkv-Impl-IOImpl.i.dfy.CheckWellformed__IOImpl.__default.getFreeLoc.smt2                |   1.290s |95.808MiB|
|d_fvbkv-Impl-InsertModel.i.dfy.CheckWellformed__InsertModel.__default.insertCorrect.smt2   |   1.288s |94.492MiB|
|d_lvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.ValToBucket.smt2        |   1.239s |93.972MiB|
|d_fvbkv-Impl-CacheImpl.i.dfy.CheckWellformed__CacheImpl.MutCache.Remove.smt2               |   1.238s |92.956MiB|
|d_lvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.CheckWellformed__ByteSystem.__default.I.smt2 |   1.179s |90.532MiB|
|d_fvbkv-Impl-StateModel.i.dfy.CheckWellformed__StateModel.__default.WFSector.smt2          |   1.141s |89.088MiB|
|d_komodo-verified-exception_handlers.gen.dfyCheckWellformed___module.__default.lemma__pageDbDispatcherVerifyStateCorresponds.smt2 |   1.100s |89.768MiB|
|d_komodo-verified-map_common.gen.dfyImpl___module.__default.lemma__read__l2pte__zero.smt2  |   1.091s |95.26MiB|
|d_komodo-verified-finalise.gen.dfyImpl___module.__default.lemma__kom__smc__finalise__success__helper2.smt2 |   1.088s |94.204MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.NewRequestReadIndirectionTableIsValid.smt2 |   4.312s |118.0MiB|
|d_komodo-verified-attest_helpers.gen.dfyImpl___module.__default.va__lemma__mem__move__global.smt2 |   2.706s |100.0MiB|
|d_komodo-verified-sha-sha256-body-16-xx.gen.dfyImpl___module.__default.va__refined__Body__16__XXUnroller_split0.smt2 |   2.097s |100.0MiB|
|d_fvbkv-Impl-MainHandlers.i.dfy.CheckWellformed__MainHandlers.__default.InitState.smt2     |   1.954s |146.0MiB|
|d_komodo-verified-kom_common.i.dfyImpl___module.__default.lemma__ValidMemRangeExPageTable__persists.smt2 |   1.681s |64.984MiB|
|d_lvbkv-Impl-CoordinationImpl.i.dfy.Impl__CoordinationImpl.__default.pushSync.smt2         |   1.679s |136.0MiB|
|d_fvbkv-Impl-SuccModel.i.dfy.CheckWellformed__SuccModel.__default.getPathInternal.smt2     |   1.600s |99.408MiB|
|d_komodo-verified-kom_utils.gen.dfyImpl___module.__default.va__lemma__page__monvaddr__impl.smt2 |   1.546s |64.508MiB|
|d_fvbkv-Impl-CoordinationModel.i.dfy.CheckWellformed__CoordinationModel.__default.initialization.smt2 |   1.481s |98.0MiB|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.ReadSectorCorrect.smt2                  |   1.351s |93.716MiB|
|d_lvbkv-Impl-SplitModel.i.dfy.CheckWellformed__SplitModel.__default.lemmaChildrenConditionsCutoffNode.smt2 |   1.300s |96.28MiB|
|d_lvbkv-Impl-IOImpl.i.dfy.CheckWellformed__IOImpl.__default.getFreeLoc.smt2                |   1.290s |95.808MiB|
|d_fvbkv-Impl-InsertModel.i.dfy.CheckWellformed__InsertModel.__default.insertCorrect.smt2   |   1.288s |94.492MiB|
|d_lvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.ValToBucket.smt2        |   1.239s |93.972MiB|
|d_fvbkv-Impl-CacheImpl.i.dfy.CheckWellformed__CacheImpl.MutCache.Remove.smt2               |   1.238s |92.956MiB|
|d_lvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.CheckWellformed__ByteSystem.__default.I.smt2 |   1.179s |90.532MiB|
|d_fvbkv-Impl-StateModel.i.dfy.CheckWellformed__StateModel.__default.WFSector.smt2          |   1.141s |89.088MiB|
|d_komodo-verified-exception_handlers.gen.dfyCheckWellformed___module.__default.lemma__pageDbDispatcherVerifyStateCorresponds.smt2 |   1.100s |89.768MiB|
|d_komodo-verified-map_common.gen.dfyImpl___module.__default.lemma__read__l2pte__zero.smt2  |   1.091s |95.26MiB|
|d_komodo-verified-finalise.gen.dfyImpl___module.__default.lemma__kom__smc__finalise__success__helper2.smt2 |   1.088s |94.204MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BlockInterface.i.dfy.CheckWellformed__BlockInterface.__default.IsStatePath.smt2  |25.888MiB|25.888MiB|0B| 0.0%|
|d_fvbkv-Betree-Graph.i.dfy.Impl__Graph.__default.AcyclicGraphImpliesSimplePath.smt2         |26.332MiB|26.332MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.NewRequestReadNodeDoesntOverlap.smt2  |53.756MiB|53.756MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-DiskLayout.i.dfy.CheckWellformed__DiskLayout.__default.JournalBackLocation.smt2  |24.656MiB|24.656MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.CheckWellformed__JournalSystem.__default.FreezeStepPreservesJournals.smt2  |50.032MiB|50.032MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.Impl__JournalSystem.__default.ProcessWriteSuperblockPreservesJournals.smt2  |56.572MiB|56.572MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-AsyncDiskModel.s.dfy.CheckWellformed__AsyncDisk.__default.AckRead.smt2  |25.94MiB|25.94MiB|0B| 0.0%|
|d_fvbkv-Impl-CacheImpl.i.dfy.CheckWellformed__CacheImpl.MutCache.Remove.smt2                |92.956MiB|92.956MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterImpl.i.dfy.CheckWellformed__CommitterImpl.Committer.__ctor.smt2       |53.528MiB|53.528MiB|0B| 0.0%|
|d_fvbkv-Impl-CoordinationModel.i.dfy.CheckWellformed__CoordinationModel.__default.initialization.smt2  |98.0MiB|98.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.ReadSectorCorrect.smt2                   |93.716MiB|93.716MiB|0B| 0.0%|
|d_fvbkv-Impl-InsertModel.i.dfy.CheckWellformed__InsertModel.__default.insertCorrect.smt2    |94.492MiB|94.492MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.CheckWellformed__JournalistMarshallingModel.__default.hasChecksums.smt2  |30.616MiB|30.616MiB|0B| 0.0%|
|d_fvbkv-Impl-MainHandlers.i.dfy.CheckWellformed__MainHandlers.__default.InitState.smt2      |146.0MiB|146.0MiB|0B| 0.0%|
|d_fvbkv-Impl-StateModel.i.dfy.CheckWellformed__StateModel.__default.WFSector.smt2           |89.088MiB|89.088MiB|0B| 0.0%|
|d_fvbkv-Impl-SuccModel.i.dfy.CheckWellformed__SuccModel.__default.getPathInternal.smt2      |99.408MiB|99.408MiB|0B| 0.0%|
|d_fvbkv-MapSpec-TSJ.i.dfy.Impl__TSJ.__default.PushSyncStepPreservesInv.smt2                 |27.924MiB|27.924MiB|0B| 0.0%|
|d_fvbkv-MapSpec-TSJMap_Refines_ThreeStateVersionedMap.i.dfy.Impl__TSJMap__Refines__ThreeStateVersionedMap.__default.apply__path.smt2  |29.576MiB|29.576MiB|0B| 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupUpperBound.smt2  |44.368MiB|44.368MiB|0B| 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupVisitsWFNodes.smt2  |44.28MiB|44.28MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BlockInterface.i.dfy.CheckWellformed__BlockInterface.__default.IsStatePath.smt2  |25.888MiB|25.888MiB|0B| 0.0%|
|d_fvbkv-Betree-Graph.i.dfy.Impl__Graph.__default.AcyclicGraphImpliesSimplePath.smt2         |26.332MiB|26.332MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.NewRequestReadNodeDoesntOverlap.smt2  |53.756MiB|53.756MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-DiskLayout.i.dfy.CheckWellformed__DiskLayout.__default.JournalBackLocation.smt2  |24.656MiB|24.656MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.CheckWellformed__JournalSystem.__default.FreezeStepPreservesJournals.smt2  |50.032MiB|50.032MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.Impl__JournalSystem.__default.ProcessWriteSuperblockPreservesJournals.smt2  |56.572MiB|56.572MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-AsyncDiskModel.s.dfy.CheckWellformed__AsyncDisk.__default.AckRead.smt2  |25.94MiB|25.94MiB|0B| 0.0%|
|d_fvbkv-Impl-CacheImpl.i.dfy.CheckWellformed__CacheImpl.MutCache.Remove.smt2                |92.956MiB|92.956MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterImpl.i.dfy.CheckWellformed__CommitterImpl.Committer.__ctor.smt2       |53.528MiB|53.528MiB|0B| 0.0%|
|d_fvbkv-Impl-CoordinationModel.i.dfy.CheckWellformed__CoordinationModel.__default.initialization.smt2  |98.0MiB|98.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.ReadSectorCorrect.smt2                   |93.716MiB|93.716MiB|0B| 0.0%|
|d_fvbkv-Impl-InsertModel.i.dfy.CheckWellformed__InsertModel.__default.insertCorrect.smt2    |94.492MiB|94.492MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.CheckWellformed__JournalistMarshallingModel.__default.hasChecksums.smt2  |30.616MiB|30.616MiB|0B| 0.0%|
|d_fvbkv-Impl-MainHandlers.i.dfy.CheckWellformed__MainHandlers.__default.InitState.smt2      |146.0MiB|146.0MiB|0B| 0.0%|
|d_fvbkv-Impl-StateModel.i.dfy.CheckWellformed__StateModel.__default.WFSector.smt2           |89.088MiB|89.088MiB|0B| 0.0%|
|d_fvbkv-Impl-SuccModel.i.dfy.CheckWellformed__SuccModel.__default.getPathInternal.smt2      |99.408MiB|99.408MiB|0B| 0.0%|
|d_fvbkv-MapSpec-TSJ.i.dfy.Impl__TSJ.__default.PushSyncStepPreservesInv.smt2                 |27.924MiB|27.924MiB|0B| 0.0%|
|d_fvbkv-MapSpec-TSJMap_Refines_ThreeStateVersionedMap.i.dfy.Impl__TSJMap__Refines__ThreeStateVersionedMap.__default.apply__path.smt2  |29.576MiB|29.576MiB|0B| 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupUpperBound.smt2  |44.368MiB|44.368MiB|0B| 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupVisitsWFNodes.smt2  |44.28MiB|44.28MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BlockInterface.i.dfy.CheckWellformed__BlockInterface.__default.IsStatePath.smt2  |25.888MiB|25.888MiB|0B| 0.0%|
|d_fvbkv-Betree-Graph.i.dfy.Impl__Graph.__default.AcyclicGraphImpliesSimplePath.smt2         |26.332MiB|26.332MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.NewRequestReadNodeDoesntOverlap.smt2  |53.756MiB|53.756MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-DiskLayout.i.dfy.CheckWellformed__DiskLayout.__default.JournalBackLocation.smt2  |24.656MiB|24.656MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.CheckWellformed__JournalSystem.__default.FreezeStepPreservesJournals.smt2  |50.032MiB|50.032MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.Impl__JournalSystem.__default.ProcessWriteSuperblockPreservesJournals.smt2  |56.572MiB|56.572MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-AsyncDiskModel.s.dfy.CheckWellformed__AsyncDisk.__default.AckRead.smt2  |25.94MiB|25.94MiB|0B| 0.0%|
|d_fvbkv-Impl-CacheImpl.i.dfy.CheckWellformed__CacheImpl.MutCache.Remove.smt2                |92.956MiB|92.956MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterImpl.i.dfy.CheckWellformed__CommitterImpl.Committer.__ctor.smt2       |53.528MiB|53.528MiB|0B| 0.0%|
|d_fvbkv-Impl-CoordinationModel.i.dfy.CheckWellformed__CoordinationModel.__default.initialization.smt2  |98.0MiB|98.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.ReadSectorCorrect.smt2                   |93.716MiB|93.716MiB|0B| 0.0%|
|d_fvbkv-Impl-InsertModel.i.dfy.CheckWellformed__InsertModel.__default.insertCorrect.smt2    |94.492MiB|94.492MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.CheckWellformed__JournalistMarshallingModel.__default.hasChecksums.smt2  |30.616MiB|30.616MiB|0B| 0.0%|
|d_fvbkv-Impl-MainHandlers.i.dfy.CheckWellformed__MainHandlers.__default.InitState.smt2      |146.0MiB|146.0MiB|0B| 0.0%|
|d_fvbkv-Impl-StateModel.i.dfy.CheckWellformed__StateModel.__default.WFSector.smt2           |89.088MiB|89.088MiB|0B| 0.0%|
|d_fvbkv-Impl-SuccModel.i.dfy.CheckWellformed__SuccModel.__default.getPathInternal.smt2      |99.408MiB|99.408MiB|0B| 0.0%|
|d_fvbkv-MapSpec-TSJ.i.dfy.Impl__TSJ.__default.PushSyncStepPreservesInv.smt2                 |27.924MiB|27.924MiB|0B| 0.0%|
|d_fvbkv-MapSpec-TSJMap_Refines_ThreeStateVersionedMap.i.dfy.Impl__TSJMap__Refines__ThreeStateVersionedMap.__default.apply__path.smt2  |29.576MiB|29.576MiB|0B| 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupUpperBound.smt2  |44.368MiB|44.368MiB|0B| 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupVisitsWFNodes.smt2  |44.28MiB|44.28MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BlockInterface.i.dfy.CheckWellformed__BlockInterface.__default.IsStatePath.smt2  |25.888MiB|25.888MiB|0B| 0.0%|
|d_fvbkv-Betree-Graph.i.dfy.Impl__Graph.__default.AcyclicGraphImpliesSimplePath.smt2         |26.332MiB|26.332MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.NewRequestReadNodeDoesntOverlap.smt2  |53.756MiB|53.756MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-DiskLayout.i.dfy.CheckWellformed__DiskLayout.__default.JournalBackLocation.smt2  |24.656MiB|24.656MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.CheckWellformed__JournalSystem.__default.FreezeStepPreservesJournals.smt2  |50.032MiB|50.032MiB|0B| 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.Impl__JournalSystem.__default.ProcessWriteSuperblockPreservesJournals.smt2  |56.572MiB|56.572MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-AsyncDiskModel.s.dfy.CheckWellformed__AsyncDisk.__default.AckRead.smt2  |25.94MiB|25.94MiB|0B| 0.0%|
|d_fvbkv-Impl-CacheImpl.i.dfy.CheckWellformed__CacheImpl.MutCache.Remove.smt2                |92.956MiB|92.956MiB|0B| 0.0%|
|d_fvbkv-Impl-CommitterImpl.i.dfy.CheckWellformed__CommitterImpl.Committer.__ctor.smt2       |53.528MiB|53.528MiB|0B| 0.0%|
|d_fvbkv-Impl-CoordinationModel.i.dfy.CheckWellformed__CoordinationModel.__default.initialization.smt2  |98.0MiB|98.0MiB|0B| 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.ReadSectorCorrect.smt2                   |93.716MiB|93.716MiB|0B| 0.0%|
|d_fvbkv-Impl-InsertModel.i.dfy.CheckWellformed__InsertModel.__default.insertCorrect.smt2    |94.492MiB|94.492MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.CheckWellformed__JournalistMarshallingModel.__default.hasChecksums.smt2  |30.616MiB|30.616MiB|0B| 0.0%|
|d_fvbkv-Impl-MainHandlers.i.dfy.CheckWellformed__MainHandlers.__default.InitState.smt2      |146.0MiB|146.0MiB|0B| 0.0%|
|d_fvbkv-Impl-StateModel.i.dfy.CheckWellformed__StateModel.__default.WFSector.smt2           |89.088MiB|89.088MiB|0B| 0.0%|
|d_fvbkv-Impl-SuccModel.i.dfy.CheckWellformed__SuccModel.__default.getPathInternal.smt2      |99.408MiB|99.408MiB|0B| 0.0%|
|d_fvbkv-MapSpec-TSJ.i.dfy.Impl__TSJ.__default.PushSyncStepPreservesInv.smt2                 |27.924MiB|27.924MiB|0B| 0.0%|
|d_fvbkv-MapSpec-TSJMap_Refines_ThreeStateVersionedMap.i.dfy.Impl__TSJMap__Refines__ThreeStateVersionedMap.__default.apply__path.smt2  |29.576MiB|29.576MiB|0B| 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupUpperBound.smt2  |44.368MiB|44.368MiB|0B| 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupVisitsWFNodes.smt2  |44.28MiB|44.28MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|d_fvbkv-Impl-MainHandlers.i.dfy.CheckWellformed__MainHandlers.__default.InitState.smt2     |   1.954s |146.0MiB|
|d_lvbkv-Impl-CoordinationImpl.i.dfy.Impl__CoordinationImpl.__default.pushSync.smt2         |   1.679s |136.0MiB|
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.NewRequestReadIndirectionTableIsValid.smt2 |   4.312s |118.0MiB|
|d_komodo-verified-attest_helpers.gen.dfyImpl___module.__default.va__lemma__mem__move__global.smt2 |   2.706s |100.0MiB|
|d_komodo-verified-sha-sha256-body-16-xx.gen.dfyImpl___module.__default.va__refined__Body__16__XXUnroller_split0.smt2 |   2.097s |100.0MiB|
|d_fvbkv-Impl-SuccModel.i.dfy.CheckWellformed__SuccModel.__default.getPathInternal.smt2     |   1.600s |99.408MiB|
|d_fvbkv-Impl-CoordinationModel.i.dfy.CheckWellformed__CoordinationModel.__default.initialization.smt2 |   1.481s |98.0MiB|
|d_lvbkv-Impl-SplitModel.i.dfy.CheckWellformed__SplitModel.__default.lemmaChildrenConditionsCutoffNode.smt2 |   1.300s |96.28MiB|
|d_lvbkv-Impl-IOImpl.i.dfy.CheckWellformed__IOImpl.__default.getFreeLoc.smt2                |   1.290s |95.808MiB|
|d_komodo-verified-map_common.gen.dfyImpl___module.__default.lemma__read__l2pte__zero.smt2  |   1.091s |95.26MiB|
|d_fvbkv-Impl-InsertModel.i.dfy.CheckWellformed__InsertModel.__default.insertCorrect.smt2   |   1.288s |94.492MiB|
|d_komodo-verified-finalise.gen.dfyImpl___module.__default.lemma__kom__smc__finalise__success__helper2.smt2 |   1.088s |94.204MiB|
|d_lvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.ValToBucket.smt2        |   1.239s |93.972MiB|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.ReadSectorCorrect.smt2                  |   1.351s |93.716MiB|
|d_fvbkv-Impl-CacheImpl.i.dfy.CheckWellformed__CacheImpl.MutCache.Remove.smt2               |   1.238s |92.956MiB|
|d_lvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.CheckWellformed__ByteSystem.__default.I.smt2 |   1.179s |90.532MiB|
|d_komodo-verified-exception_handlers.gen.dfyCheckWellformed___module.__default.lemma__pageDbDispatcherVerifyStateCorresponds.smt2 |   1.100s |89.768MiB|
|d_komodo-verified-sha-hmac.gen.dfyCheckWellformed___module.__default.va__lemma__hmac__outer__prep__ctx.smt2 |   0.997s |89.272MiB|
|d_fvbkv-Impl-StateModel.i.dfy.CheckWellformed__StateModel.__default.WFSector.smt2          |   1.141s |89.088MiB|
|d_lvbkv-Impl-CacheImpl.i.dfy.Impl__CacheImpl.LMutCache.NodePartialFlush.smt2               |   1.080s |88.088MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|d_fvbkv-Impl-MainHandlers.i.dfy.CheckWellformed__MainHandlers.__default.InitState.smt2     |   1.954s |146.0MiB|
|d_lvbkv-Impl-CoordinationImpl.i.dfy.Impl__CoordinationImpl.__default.pushSync.smt2         |   1.679s |136.0MiB|
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.NewRequestReadIndirectionTableIsValid.smt2 |   4.312s |118.0MiB|
|d_komodo-verified-attest_helpers.gen.dfyImpl___module.__default.va__lemma__mem__move__global.smt2 |   2.706s |100.0MiB|
|d_komodo-verified-sha-sha256-body-16-xx.gen.dfyImpl___module.__default.va__refined__Body__16__XXUnroller_split0.smt2 |   2.097s |100.0MiB|
|d_fvbkv-Impl-SuccModel.i.dfy.CheckWellformed__SuccModel.__default.getPathInternal.smt2     |   1.600s |99.408MiB|
|d_fvbkv-Impl-CoordinationModel.i.dfy.CheckWellformed__CoordinationModel.__default.initialization.smt2 |   1.481s |98.0MiB|
|d_lvbkv-Impl-SplitModel.i.dfy.CheckWellformed__SplitModel.__default.lemmaChildrenConditionsCutoffNode.smt2 |   1.300s |96.28MiB|
|d_lvbkv-Impl-IOImpl.i.dfy.CheckWellformed__IOImpl.__default.getFreeLoc.smt2                |   1.290s |95.808MiB|
|d_komodo-verified-map_common.gen.dfyImpl___module.__default.lemma__read__l2pte__zero.smt2  |   1.091s |95.26MiB|
|d_fvbkv-Impl-InsertModel.i.dfy.CheckWellformed__InsertModel.__default.insertCorrect.smt2   |   1.288s |94.492MiB|
|d_komodo-verified-finalise.gen.dfyImpl___module.__default.lemma__kom__smc__finalise__success__helper2.smt2 |   1.088s |94.204MiB|
|d_lvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.ValToBucket.smt2        |   1.239s |93.972MiB|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.ReadSectorCorrect.smt2                  |   1.351s |93.716MiB|
|d_fvbkv-Impl-CacheImpl.i.dfy.CheckWellformed__CacheImpl.MutCache.Remove.smt2               |   1.238s |92.956MiB|
|d_lvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.CheckWellformed__ByteSystem.__default.I.smt2 |   1.179s |90.532MiB|
|d_komodo-verified-exception_handlers.gen.dfyCheckWellformed___module.__default.lemma__pageDbDispatcherVerifyStateCorresponds.smt2 |   1.100s |89.768MiB|
|d_komodo-verified-sha-hmac.gen.dfyCheckWellformed___module.__default.va__lemma__hmac__outer__prep__ctx.smt2 |   0.997s |89.272MiB|
|d_fvbkv-Impl-StateModel.i.dfy.CheckWellformed__StateModel.__default.WFSector.smt2          |   1.141s |89.088MiB|
|d_lvbkv-Impl-CacheImpl.i.dfy.Impl__CacheImpl.LMutCache.NodePartialFlush.smt2               |   1.080s |88.088MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BlockInterface.i.dfy.CheckWellformed__BlockInterface.__default.IsStatePath.smt2  |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|d_fvbkv-Betree-Graph.i.dfy.Impl__Graph.__default.AcyclicGraphImpliesSimplePath.smt2         |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.NewRequestReadNodeDoesntOverlap.smt2  |   0.763s  |   0.763s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-DiskLayout.i.dfy.CheckWellformed__DiskLayout.__default.JournalBackLocation.smt2  |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.CheckWellformed__JournalSystem.__default.FreezeStepPreservesJournals.smt2  |   0.512s  |   0.512s  |   0.000s  | 0.0%|
|d_fvbkv-BlockCacheSystem-JournalSystem.i.dfy.Impl__JournalSystem.__default.ProcessWriteSuperblockPreservesJournals.smt2  |   0.799s  |   0.799s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-AsyncDiskModel.s.dfy.CheckWellformed__AsyncDisk.__default.AckRead.smt2  |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CacheImpl.i.dfy.CheckWellformed__CacheImpl.MutCache.Remove.smt2                |   1.238s  |   1.238s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CommitterImpl.i.dfy.CheckWellformed__CommitterImpl.Committer.__ctor.smt2       |   0.687s  |   0.687s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-CoordinationModel.i.dfy.CheckWellformed__CoordinationModel.__default.initialization.smt2  |   1.481s  |   1.481s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.ReadSectorCorrect.smt2                   |   1.351s  |   1.351s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-InsertModel.i.dfy.CheckWellformed__InsertModel.__default.insertCorrect.smt2    |   1.288s  |   1.288s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.CheckWellformed__JournalistMarshallingModel.__default.hasChecksums.smt2  |   0.242s  |   0.242s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-MainHandlers.i.dfy.CheckWellformed__MainHandlers.__default.InitState.smt2      |   1.954s  |   1.954s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-StateModel.i.dfy.CheckWellformed__StateModel.__default.WFSector.smt2           |   1.141s  |   1.141s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-SuccModel.i.dfy.CheckWellformed__SuccModel.__default.getPathInternal.smt2      |   1.600s  |   1.600s  |   0.000s  | 0.0%|
|d_fvbkv-MapSpec-TSJ.i.dfy.Impl__TSJ.__default.PushSyncStepPreservesInv.smt2                 |   0.187s  |   0.187s  |   0.000s  | 0.0%|
|d_fvbkv-MapSpec-TSJMap_Refines_ThreeStateVersionedMap.i.dfy.Impl__TSJMap__Refines__ThreeStateVersionedMap.__default.apply__path.smt2  |   0.220s  |   0.220s  |   0.000s  | 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupUpperBound.smt2  |   0.416s  |   0.416s  |   0.000s  | 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.LookupVisitsWFNodes.smt2  |   0.410s  |   0.410s  |   0.000s  | 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.Impl__PivotBetreeSpecRefinement.__default.InterpretBucketStackEqInterpretLookup.smt2  |   0.533s  |   0.533s  |   0.000s  | 0.0%|
|d_fvbkv-PivotBetree-PivotBetreeSpecWFNodes.i.dfy.Impl__PivotBetreeSpecWFNodes.__default.ValidRepivotWFNodes.smt2  |   0.424s  |   0.424s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-sequences.i.dfy.Impl__Sequences.__default.FlattenLengthSubSeq.smt2         |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-total_order.i.dfy.CheckWellformed__Total__Order.__default.strictlySortedInsert2.smt2  |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-total_order.i.dfy.Impl__Uint32__Order.__default.LargestLteIsUnique2.smt2   |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-total_order_impl.i.dfy.CheckWellformed__Byte__Order__Impl.__default.ArrayLargestLtePlus1.smt2  |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.CheckWellformed__PackedStringArray.__default.LargestLte.smt2  |   0.216s  |   0.216s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-KMBtree.i.dfy.Impl__KMBtreeModel.__default.SplitIndexInterpretation2.smt2  |   0.262s  |   0.262s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.CheckWellformed__TestMutableBtree.__default.MaxKeysPerLeaf.smt2  |   0.238s  |   0.238s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__TestMutableBtree.__default.SubIndex.smt2  |   0.252s  |   0.252s  |   0.000s  | 0.0%|
|d_komodo-verified-ARMdef.s.dfyCheckWellformed___module.__default.ValidGlobalOffset.smt2     |   0.220s  |   0.220s  |   0.000s  | 0.0%|
|d_komodo-verified-ARMdef.s.dfyCheckWellformed___module.__default.ValidModeEncoding.smt2     |   0.224s  |   0.224s  |   0.000s  | 0.0%|
|d_komodo-verified-ARMprint.s.dfyImpl___module.__default.printGlobal.smt2                    |   0.207s  |   0.207s  |   0.000s  | 0.0%|
|d_komodo-verified-Seq.dfyCheckWellformed___module.__default.MapSeqToSeq.smt2                |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|d_komodo-verified-attest_helpers.gen.dfyImpl___module.__default.va__lemma__mem__move__global.smt2  |   2.706s  |   2.706s  |   0.000s  | 0.0%|
|d_komodo-verified-bitvectors.i.dfyCheckWellformed___module.__default.lemma__LeftShift2.smt2  |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|d_komodo-verified-bitvectors.i.dfyCheckWellformed___module.__default.lemma__RightShift2.smt2  |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.gen.dfyCheckWellformed___module.__default.va__lemma__smc__enter__err.smt2  |   0.655s  |   0.655s  |   0.000s  | 0.0%|
|d_komodo-verified-entry.i.dfyCheckWellformed___module.__default.lemma__singlestep__execution.smt2  |   0.449s  |   0.449s  |   0.000s  | 0.0%|
|d_komodo-verified-exception_handlers.gen.dfyCheckWellformed___module.__default.lemma__pageDbDispatcherVerifyStateCorresponds.smt2  |   1.100s  |   1.100s  |   0.000s  | 0.0%|
|d_komodo-verified-exceptions.i.dfyCheckWellformed___module.__default.lemma__Establish__InterruptContinuationPrecondition.smt2  |   0.440s  |   0.440s  |   0.000s  | 0.0%|
|d_komodo-verified-finalise.gen.dfyImpl___module.__default.lemma__kom__smc__finalise__success__helper2.smt2  |   1.088s  |   1.088s  |   0.000s  | 0.0%|
|d_komodo-verified-kom_common.i.dfyImpl___module.__default.lemma__ValidMemRangeExPageTable__persists.smt2  |   1.681s  |   1.681s  |   0.000s  | 0.0%|
|d_komodo-verified-kom_common.s.dfyCheckWellformed___module.__default.AttestKey.smt2         |   0.233s  |   0.233s  |   0.000s  | 0.0%|
|d_komodo-verified-kom_utils.gen.dfyCheckWellformed___module.__default.va__code__STRx.smt2   |   0.419s  |   0.419s  |   0.000s  | 0.0%|
|d_komodo-verified-kom_utils.gen.dfyImpl___module.__default.va__lemma__page__monvaddr__impl.smt2  |   1.546s  |   1.546s  |   0.000s  | 0.0%|
|d_komodo-verified-map_common.gen.dfyImpl___module.__default.lemma__read__l2pte__zero.smt2   |   1.091s  |   1.091s  |   0.000s  | 0.0%|
|d_komodo-verified-pagedb.s.dfyCheckWellformed___module.__default.validInsecurePageNr.smt2   |   0.286s  |   0.286s  |   0.000s  | 0.0%|
|d_komodo-verified-ptebits.i.dfyCheckWellformed___module.__default.lemma__nonexec__mapping.smt2  |   0.333s  |   0.333s  |   0.000s  | 0.0%|
|d_komodo-verified-ptebits.i.dfyImpl___module.__default.lemma__BitOrNineIsLikePlus.smt2      |   0.485s  |   0.485s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-hmac.gen.dfyCheckWellformed___module.__default.va__lemma__hmac__outer__prep__ctx.smt2  |   0.997s  |   0.997s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-sha256-body-00-15.gen.dfyCheckWellformed___module.__default.va__if__abstract__Body__00__15UnrolledRecursive.smt2  |   0.535s  |   0.535s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-sha256-body-16-xx.gen.dfyImpl___module.__default.va__refined__Body__16__XXUnroller_split0.smt2  |   2.097s  |   2.097s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-sha256-helpers.i.dfyCheckWellformed___module.__default.lemma__BitwiseAdd32Associates5.smt2  |   0.314s  |   0.314s  |   0.000s  | 0.0%|
|d_komodo-verified-stop.gen.dfyCheckWellformed___module.__default.va__lemma__kom__smc__stop.smt2  |   0.628s  |   0.628s  |   0.000s  | 0.0%|
|d_komodo-verified-valedecls.gen.dfyImpl___module.__default.va__lemma__MOVShift.smt2         |   0.295s  |   0.295s  |   0.000s  | 0.0%|
|d_komodo-verified-valesupp.i.dfyCheckWellformed___module.__default.va__lemma__whileTrue.smt2  |   0.243s  |   0.243s  |   0.000s  | 0.0%|
|d_komodo-verified-verify.gen.dfyCheckWellformed___module.__default.va__code__svc__returning__verify.smt2  |   1.004s  |   1.004s  |   0.000s  | 0.0%|
|d_komodo-verified-words_and_bytes.i.dfyImpl___module.__default.lemma__BytesToWord__WordToBytes__inverses.smt2  |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|d_komodo-verified-words_and_bytes.s.dfyCheckWellformed___module.__default.ConcatenateSeqs.smt2  |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|d_lvbkv-Betree-Betree_Refines_Map.i.dfy.CheckWellformed__Betree__Refines__Map.__default.RefinesInit.smt2  |   0.320s  |   0.320s  |   0.000s  | 0.0%|
|d_lvbkv-Betree-BlockInterface.i.dfy.Impl__BlockInterface.__default.Transaction3Steps.smt2   |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.NewRequestReadIndirectionTableIsValid.smt2  |   4.312s  |   4.312s  |   0.000s  | 0.0%|
|d_lvbkv-BlockCacheSystem-DiskLayout.i.dfy.CheckWellformed__DiskLayout.__default.locContainedInCircularJournalRange.smt2  |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|d_lvbkv-BlockCacheSystem-JournalSystem.i.dfy.CheckWellformed__JournalSystem.__default.NoOpStepPreservesJournals.smt2  |   0.499s  |   0.499s  |   0.000s  | 0.0%|
|d_lvbkv-ByteBlockCacheSystem-AsyncDiskModel.s.dfy.CheckWellformed__AsyncDisk.__default.ChecksumChecksOut.smt2  |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|d_lvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.CheckWellformed__ByteSystem.__default.I.smt2  |   1.179s  |   1.179s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-CacheImpl.i.dfy.Impl__CacheImpl.LMutCache.NodePartialFlush.smt2                |   1.080s  |   1.080s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-CoordinationImpl.i.dfy.Impl__CoordinationImpl.__default.pushSync.smt2          |   1.679s  |   1.679s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-IOImpl.i.dfy.CheckWellformed__IOImpl.__default.getFreeLoc.smt2                 |   1.290s  |   1.290s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-JournalistImpl.i.dfy.CheckWellformed__JournalistImpl.__default.MaxPossibleEntries.smt2  |   0.269s  |   0.269s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.ValToBucket.smt2         |   1.239s  |   1.239s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-SplitModel.i.dfy.CheckWellformed__SplitModel.__default.lemmaChildrenConditionsCutoffNode.smt2  |   1.300s  |   1.300s  |   0.000s  | 0.0%|
|d_lvbkv-MapSpec-TSJMap.i.dfy.Impl__TSJMap.__default.Move2to3StepPreservesInv.smt2           |   0.224s  |   0.224s  |   0.000s  | 0.0%|
|d_lvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.CheckWellformed__PivotBetreeSpecRefinement.__default.INode.smt2  |   0.550s  |   0.550s  |   0.000s  | 0.0%|
|d_lvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.CheckWellformed__PivotBetreeSpecRefinement.__default.InterpretBucketStack.smt2  |   0.540s  |   0.540s  |   0.000s  | 0.0%|
|d_lvbkv-PivotBetree-PivotBetreeSpecWFNodes.i.dfy.CheckWellformed__PivotBetreeSpecWFNodes.__default.bucket__msgs__equiv.smt2  |   0.429s  |   0.429s  |   0.000s  | 0.0%|
|d_lvbkv-PivotBetree-StatesViewPivotBetree_Refines_StatesViewMap.i.dfy.CheckWellformed__StatesViewPivotBetree__Refines__StatesViewMap.__default.RefinesNextStep.smt2  |   0.608s  |   0.608s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-BitsetLemmas.i.dfy.CheckWellformed__BitsetLemmas.__default.bit.smt2        |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-BitsetLemmas.i.dfy.CheckWellformed__BitsetLemmas.__default.bit__comp__ne__expanded.smt2  |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-Message.i.dfy.CheckWellformed__ValueMessage.__default.EncodableMessageSeq.smt2  |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-MutableVec.i.dfy.CheckWellformed__MutableVec.Vec.insert.smt2               |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-total_order.i.dfy.Impl__Integer__Order.__default.StrictlySortedImpliesSorted.smt2  |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-total_order_impl.i.dfy.Impl__Byte__Order__Impl.__default.ComputeIsSorted.smt2  |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-total_order_impl.i.dfy.Impl__Uint64__Order__Impl.__default.BatchLargestLte.smt2  |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Checksums-BitLemmas.i.dfy.Impl__BitLemmas.__default.bits__of__int__combine.smt2  |   0.397s  |   0.397s  |   0.000s  | 0.0%|
|d_lvbkv-lib-DataStructures-KMBtree.i.dfy.Impl__KMBtreeModel.__default.SplitChildOfIndexPreservesAllKeys.smt2  |   0.279s  |   0.279s  |   0.000s  | 0.0%|
|d_lvbkv-lib-DataStructures-LinearMutableMap.i.dfy.CheckWellformed__LinearMutableMap.__default.FixedSizeUpdateBySlot.smt2  |   0.209s  |   0.209s  |   0.000s  | 0.0%|
|d_lvbkv-lib-DataStructures-LinearMutableMapBase.i.dfy.CheckWellformed__LinearMutableMapBase.__default.lshift.smt2  |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Math-Math.i.dfy.Impl__Math.__default.lemma__power2__div__is__sub.smt2           |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|s_komodo-1440.0.smt2                                                                        |   0.362s  |   0.362s  |   0.000s  | 0.0%|
|s_komodo-1441.2.smt2                                                                        |   0.283s  |   0.283s  |   0.000s  | 0.0%|
|s_komodo-1456.4.smt2                                                                        |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|s_komodo-1457.2.smt2                                                                        |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|s_komodo-1466.1.smt2                                                                        |   0.268s  |   0.268s  |   0.000s  | 0.0%|
|s_komodo-1469.1.smt2                                                                        |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|s_komodo-1470.0.smt2                                                                        |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|s_komodo-1484.7.smt2                                                                        |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|s_komodo-1486.1.smt2                                                                        |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|s_komodo-1487.4.smt2                                                                        |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|s_komodo-1490.0.smt2                                                                        |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|s_komodo-1493.3.smt2                                                                        |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|s_komodo-1494.5.smt2                                                                        |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|s_komodo-1496.2.smt2                                                                        |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|s_komodo-1500.4.smt2                                                                        |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|s_komodo-1500.6.smt2                                                                        |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|s_komodo-1501.7.smt2                                                                        |   0.705s  |   0.705s  |   0.000s  | 0.0%|
|s_komodo-1502.2.smt2                                                                        |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|s_komodo-1503.6.smt2                                                                        |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|s_komodo-1505.3.smt2                                                                        |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|s_komodo-1506.1.smt2                                                                        |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|s_komodo-1511.8.smt2                                                                        |   0.291s  |   0.291s  |   0.000s  | 0.0%|
|s_komodo-1516.11.smt2                                                                       |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|s_komodo-1516.7.smt2                                                                        |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|s_komodo-1526.0.smt2                                                                        |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|s_komodo-1531.0.smt2                                                                        |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|s_komodo-1533.7.smt2                                                                        |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|s_komodo-1534.9.smt2                                                                        |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|s_komodo-1544.3.smt2                                                                        |   0.067s  |   0.067s  |   0.000s  | 0.0%|
</details>
