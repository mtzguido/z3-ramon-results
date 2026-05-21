Comparing data and data


# SUMMARY
- LHS tests = 41
- RHS tests = 41
- LHS success = 41  (100.0%)
- RHS success = 41  (100.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: bench-mariposa-unstable_core
Runner: rise-runner-2
Z3 repo: CanCebeci/z3
Z3 commit: bc6c38e7d3424b88a505cacba4b268d0774d4547
Z3 branch: bc6c38e7d3424b88a505cacba4b268d0774d4547
Z3 options: "-T:20"
Z3 inputs: inputs/mariposa/unstable_core
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
Job tag: bench-mariposa-unstable_core
Runner: rise-runner-2
Z3 repo: CanCebeci/z3
Z3 commit: bc6c38e7d3424b88a505cacba4b268d0774d4547
Z3 branch: bc6c38e7d3424b88a505cacba4b268d0774d4547
Z3 options: "-T:20"
Z3 inputs: inputs/mariposa/unstable_core
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
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.FlushPreservesLookups.smt2         |   4.330s  |   4.330s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ReqWrite2StepPreservesInv.smt2  |  15.620s  |  15.620s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesProcessWrite.smt2  |   1.485s  |   1.485s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.PageInNodeResp.smt2                        |  18.768s  |  18.768s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.append.smt2   |   0.799s  |   0.799s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.set__bit__to__0__self__uint64.smt2  |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.set__bit__to__1__self__uint64.smt2  |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-KMBPKVOps.i.dfy.Impl__KMBPKVOps.__default.IndexFillDpkv.smt2            |  20.054s  |  20.054s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.BinarySearchQuery.smt2          |   2.743s  |   2.743s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.UniqueRepr.smt2  |   0.313s  |   0.313s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.SplitIndexAllKeys.smt2  |  20.054s  |  20.054s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-LruImpl.i.dfy.Impl__LruImpl.LruImplQueue.Use.smt2                |  15.250s  |  15.250s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SubIndex.smt2    |  12.663s  |  12.663s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SubReprLowerBound.smt2  |   0.373s  |   0.373s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallArray.smt2  |   1.646s  |   1.646s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint32Array.smt2  |   1.153s  |   1.153s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint64Array.smt2  |   1.022s  |   1.022s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__2toX.smt2                    |   0.576s  |   0.576s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__div__denominator.smt2        |   0.317s  |   0.317s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Math-mod_auto_proofs.i.dfy.Impl__Math____mod__auto__proofs__i.__default.lemma__mod__induction__forall2.smt2  |   0.081s  |   0.081s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.FlushPreservesLookups.smt2         |   4.330s  |   4.330s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ReqWrite2StepPreservesInv.smt2  |  15.620s  |  15.620s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesProcessWrite.smt2  |   1.485s  |   1.485s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.PageInNodeResp.smt2                        |  18.768s  |  18.768s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.append.smt2   |   0.799s  |   0.799s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.set__bit__to__0__self__uint64.smt2  |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.set__bit__to__1__self__uint64.smt2  |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-KMBPKVOps.i.dfy.Impl__KMBPKVOps.__default.IndexFillDpkv.smt2            |  20.054s  |  20.054s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.BinarySearchQuery.smt2          |   2.743s  |   2.743s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.UniqueRepr.smt2  |   0.313s  |   0.313s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.SplitIndexAllKeys.smt2  |  20.054s  |  20.054s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-LruImpl.i.dfy.Impl__LruImpl.LruImplQueue.Use.smt2                |  15.250s  |  15.250s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SubIndex.smt2    |  12.663s  |  12.663s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SubReprLowerBound.smt2  |   0.373s  |   0.373s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallArray.smt2  |   1.646s  |   1.646s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint32Array.smt2  |   1.153s  |   1.153s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint64Array.smt2  |   1.022s  |   1.022s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__2toX.smt2                    |   0.576s  |   0.576s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__div__denominator.smt2        |   0.317s  |   0.317s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Math-mod_auto_proofs.i.dfy.Impl__Math____mod__auto__proofs__i.__default.lemma__mod__induction__forall2.smt2  |   0.081s  |   0.081s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.FlushPreservesLookups.smt2         |   4.330s  |   4.330s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ReqWrite2StepPreservesInv.smt2  |  15.620s  |  15.620s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesProcessWrite.smt2  |   1.485s  |   1.485s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.PageInNodeResp.smt2                        |  18.768s  |  18.768s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.append.smt2   |   0.799s  |   0.799s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.set__bit__to__0__self__uint64.smt2  |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.set__bit__to__1__self__uint64.smt2  |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-KMBPKVOps.i.dfy.Impl__KMBPKVOps.__default.IndexFillDpkv.smt2            |  20.054s  |  20.054s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.BinarySearchQuery.smt2          |   2.743s  |   2.743s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.UniqueRepr.smt2  |   0.313s  |   0.313s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.SplitIndexAllKeys.smt2  |  20.054s  |  20.054s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-LruImpl.i.dfy.Impl__LruImpl.LruImplQueue.Use.smt2                |  15.250s  |  15.250s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SubIndex.smt2    |  12.663s  |  12.663s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SubReprLowerBound.smt2  |   0.373s  |   0.373s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallArray.smt2  |   1.646s  |   1.646s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint32Array.smt2  |   1.153s  |   1.153s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint64Array.smt2  |   1.022s  |   1.022s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__2toX.smt2                    |   0.576s  |   0.576s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__div__denominator.smt2        |   0.317s  |   0.317s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Math-mod_auto_proofs.i.dfy.Impl__Math____mod__auto__proofs__i.__default.lemma__mod__induction__forall2.smt2  |   0.081s  |   0.081s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.FlushPreservesLookups.smt2         |   4.330s  |   4.330s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ReqWrite2StepPreservesInv.smt2  |  15.620s  |  15.620s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesProcessWrite.smt2  |   1.485s  |   1.485s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.PageInNodeResp.smt2                        |  18.768s  |  18.768s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.append.smt2   |   0.799s  |   0.799s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.set__bit__to__0__self__uint64.smt2  |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.set__bit__to__1__self__uint64.smt2  |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-KMBPKVOps.i.dfy.Impl__KMBPKVOps.__default.IndexFillDpkv.smt2            |  20.054s  |  20.054s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.BinarySearchQuery.smt2          |   2.743s  |   2.743s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.UniqueRepr.smt2  |   0.313s  |   0.313s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.SplitIndexAllKeys.smt2  |  20.054s  |  20.054s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-LruImpl.i.dfy.Impl__LruImpl.LruImplQueue.Use.smt2                |  15.250s  |  15.250s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SubIndex.smt2    |  12.663s  |  12.663s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SubReprLowerBound.smt2  |   0.373s  |   0.373s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallArray.smt2  |   1.646s  |   1.646s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint32Array.smt2  |   1.153s  |   1.153s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint64Array.smt2  |   1.022s  |   1.022s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__2toX.smt2                    |   0.576s  |   0.576s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__div__denominator.smt2        |   0.317s  |   0.317s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Math-mod_auto_proofs.i.dfy.Impl__Math____mod__auto__proofs__i.__default.lemma__mod__induction__forall2.smt2  |   0.081s  |   0.081s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|s_komodo-1509.4.smt2                                                                       |  20.466s |5431.0MiB|
|s_komodo-1504.4.smt2                                                                       |  20.393s |3766.0MiB|
|d_komodo-verified-sha-sha256.i.dfyImpl___module.__default.lemma__SHA256FinalHelper1.smt2   |  20.109s |888.0MiB|
|d_komodo-verified-verify.gen.dfyImpl___module.__default.va__lemma__svc__returning__verify__inner.smt2 |  20.062s |277.0MiB|
|d_fvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.SplitIndexAllKeys.smt2 |  20.054s |207.0MiB|
|d_fvbkv-lib-Buckets-KMBPKVOps.i.dfy.Impl__KMBPKVOps.__default.IndexFillDpkv.smt2           |  20.054s |189.0MiB|
|d_komodo-verified-secprop-conf_ni.i.dfyImpl___module.__default.lemma__initL2PTable__loweq__pdb.smt2 |  20.053s |193.0MiB|
|d_lvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.Impl__PivotBetreeSpecRefinement.__default.SplitChildrenConsistent.smt2 |  20.047s |203.0MiB|
|d_lvbkv-lib-Buckets-BucketsLib.i.dfy.Impl__BucketsLib.__default.WFProperSplitBucketInList.smt2 |  20.042s |123.0MiB|
|d_komodo-verified-verify.gen.dfyImpl___module.__default.va__lemma__svc__returning__verify.smt2 |  20.041s |221.0MiB|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.PageInNodeResp.smt2                       |  18.768s |172.0MiB|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ReqWrite2StepPreservesInv.smt2 |  15.620s |189.0MiB|
|d_fvbkv-lib-DataStructures-LruImpl.i.dfy.Impl__LruImpl.LruImplQueue.Use.smt2               |  15.250s |172.0MiB|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SubIndex.smt2   |  12.663s |107.0MiB|
|d_lvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__LMutableBtree.__default.InsertIndex.smt2 |   5.618s |101.0MiB|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.FlushPreservesLookups.smt2        |   4.330s |94.54MiB|
|d_komodo-verified-ptebits.i.dfyImpl___module.__default.lemma__l1ptesmatch.smt2             |   2.816s |278.0MiB|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.BinarySearchQuery.smt2         |   2.743s |64.488MiB|
|d_lvbkv-Impl-JournalistImpl.i.dfy.Impl__JournalistImpl.Journalist.append.smt2              |   1.983s |61.988MiB|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallArray.smt2 |   1.646s |58.552MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|s_komodo-1509.4.smt2                                                                       |  20.466s |5431.0MiB|
|s_komodo-1504.4.smt2                                                                       |  20.393s |3766.0MiB|
|d_komodo-verified-sha-sha256.i.dfyImpl___module.__default.lemma__SHA256FinalHelper1.smt2   |  20.109s |888.0MiB|
|d_komodo-verified-verify.gen.dfyImpl___module.__default.va__lemma__svc__returning__verify__inner.smt2 |  20.062s |277.0MiB|
|d_fvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.SplitIndexAllKeys.smt2 |  20.054s |207.0MiB|
|d_fvbkv-lib-Buckets-KMBPKVOps.i.dfy.Impl__KMBPKVOps.__default.IndexFillDpkv.smt2           |  20.054s |189.0MiB|
|d_komodo-verified-secprop-conf_ni.i.dfyImpl___module.__default.lemma__initL2PTable__loweq__pdb.smt2 |  20.053s |193.0MiB|
|d_lvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.Impl__PivotBetreeSpecRefinement.__default.SplitChildrenConsistent.smt2 |  20.047s |203.0MiB|
|d_lvbkv-lib-Buckets-BucketsLib.i.dfy.Impl__BucketsLib.__default.WFProperSplitBucketInList.smt2 |  20.042s |123.0MiB|
|d_komodo-verified-verify.gen.dfyImpl___module.__default.va__lemma__svc__returning__verify.smt2 |  20.041s |221.0MiB|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.PageInNodeResp.smt2                       |  18.768s |172.0MiB|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ReqWrite2StepPreservesInv.smt2 |  15.620s |189.0MiB|
|d_fvbkv-lib-DataStructures-LruImpl.i.dfy.Impl__LruImpl.LruImplQueue.Use.smt2               |  15.250s |172.0MiB|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SubIndex.smt2   |  12.663s |107.0MiB|
|d_lvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__LMutableBtree.__default.InsertIndex.smt2 |   5.618s |101.0MiB|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.FlushPreservesLookups.smt2        |   4.330s |94.54MiB|
|d_komodo-verified-ptebits.i.dfyImpl___module.__default.lemma__l1ptesmatch.smt2             |   2.816s |278.0MiB|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.BinarySearchQuery.smt2         |   2.743s |64.488MiB|
|d_lvbkv-Impl-JournalistImpl.i.dfy.Impl__JournalistImpl.Journalist.append.smt2              |   1.983s |61.988MiB|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallArray.smt2 |   1.646s |58.552MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.FlushPreservesLookups.smt2         |94.54MiB|94.54MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ReqWrite2StepPreservesInv.smt2  |189.0MiB|189.0MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesProcessWrite.smt2  |97.748MiB|97.748MiB|0B| 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.PageInNodeResp.smt2                        |172.0MiB|172.0MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.append.smt2   |59.652MiB|59.652MiB|0B| 0.0%|
|d_fvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.set__bit__to__0__self__uint64.smt2  |38.04MiB|38.04MiB|0B| 0.0%|
|d_fvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.set__bit__to__1__self__uint64.smt2  |37.736MiB|37.736MiB|0B| 0.0%|
|d_fvbkv-lib-Buckets-KMBPKVOps.i.dfy.Impl__KMBPKVOps.__default.IndexFillDpkv.smt2            |189.0MiB|189.0MiB|0B| 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.BinarySearchQuery.smt2          |64.488MiB|64.488MiB|0B| 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.UniqueRepr.smt2  |31.8MiB|31.8MiB|0B| 0.0%|
|d_fvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.SplitIndexAllKeys.smt2  |207.0MiB|207.0MiB|0B| 0.0%|
|d_fvbkv-lib-DataStructures-LruImpl.i.dfy.Impl__LruImpl.LruImplQueue.Use.smt2                |172.0MiB|172.0MiB|0B| 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SubIndex.smt2    |107.0MiB|107.0MiB|0B| 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SubReprLowerBound.smt2  |32.032MiB|32.032MiB|0B| 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallArray.smt2  |58.552MiB|58.552MiB|0B| 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint32Array.smt2  |45.788MiB|45.788MiB|0B| 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint64Array.smt2  |44.232MiB|44.232MiB|0B| 0.0%|
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__2toX.smt2                    |58.612MiB|58.612MiB|0B| 0.0%|
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__div__denominator.smt2        |25.252MiB|25.252MiB|0B| 0.0%|
|d_fvbkv-lib-Math-mod_auto_proofs.i.dfy.Impl__Math____mod__auto__proofs__i.__default.lemma__mod__induction__forall2.smt2  |23.436MiB|23.436MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.FlushPreservesLookups.smt2         |94.54MiB|94.54MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ReqWrite2StepPreservesInv.smt2  |189.0MiB|189.0MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesProcessWrite.smt2  |97.748MiB|97.748MiB|0B| 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.PageInNodeResp.smt2                        |172.0MiB|172.0MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.append.smt2   |59.652MiB|59.652MiB|0B| 0.0%|
|d_fvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.set__bit__to__0__self__uint64.smt2  |38.04MiB|38.04MiB|0B| 0.0%|
|d_fvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.set__bit__to__1__self__uint64.smt2  |37.736MiB|37.736MiB|0B| 0.0%|
|d_fvbkv-lib-Buckets-KMBPKVOps.i.dfy.Impl__KMBPKVOps.__default.IndexFillDpkv.smt2            |189.0MiB|189.0MiB|0B| 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.BinarySearchQuery.smt2          |64.488MiB|64.488MiB|0B| 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.UniqueRepr.smt2  |31.8MiB|31.8MiB|0B| 0.0%|
|d_fvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.SplitIndexAllKeys.smt2  |207.0MiB|207.0MiB|0B| 0.0%|
|d_fvbkv-lib-DataStructures-LruImpl.i.dfy.Impl__LruImpl.LruImplQueue.Use.smt2                |172.0MiB|172.0MiB|0B| 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SubIndex.smt2    |107.0MiB|107.0MiB|0B| 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SubReprLowerBound.smt2  |32.032MiB|32.032MiB|0B| 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallArray.smt2  |58.552MiB|58.552MiB|0B| 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint32Array.smt2  |45.788MiB|45.788MiB|0B| 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint64Array.smt2  |44.232MiB|44.232MiB|0B| 0.0%|
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__2toX.smt2                    |58.612MiB|58.612MiB|0B| 0.0%|
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__div__denominator.smt2        |25.252MiB|25.252MiB|0B| 0.0%|
|d_fvbkv-lib-Math-mod_auto_proofs.i.dfy.Impl__Math____mod__auto__proofs__i.__default.lemma__mod__induction__forall2.smt2  |23.436MiB|23.436MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.FlushPreservesLookups.smt2         |94.54MiB|94.54MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ReqWrite2StepPreservesInv.smt2  |189.0MiB|189.0MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesProcessWrite.smt2  |97.748MiB|97.748MiB|0B| 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.PageInNodeResp.smt2                        |172.0MiB|172.0MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.append.smt2   |59.652MiB|59.652MiB|0B| 0.0%|
|d_fvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.set__bit__to__0__self__uint64.smt2  |38.04MiB|38.04MiB|0B| 0.0%|
|d_fvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.set__bit__to__1__self__uint64.smt2  |37.736MiB|37.736MiB|0B| 0.0%|
|d_fvbkv-lib-Buckets-KMBPKVOps.i.dfy.Impl__KMBPKVOps.__default.IndexFillDpkv.smt2            |189.0MiB|189.0MiB|0B| 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.BinarySearchQuery.smt2          |64.488MiB|64.488MiB|0B| 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.UniqueRepr.smt2  |31.8MiB|31.8MiB|0B| 0.0%|
|d_fvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.SplitIndexAllKeys.smt2  |207.0MiB|207.0MiB|0B| 0.0%|
|d_fvbkv-lib-DataStructures-LruImpl.i.dfy.Impl__LruImpl.LruImplQueue.Use.smt2                |172.0MiB|172.0MiB|0B| 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SubIndex.smt2    |107.0MiB|107.0MiB|0B| 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SubReprLowerBound.smt2  |32.032MiB|32.032MiB|0B| 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallArray.smt2  |58.552MiB|58.552MiB|0B| 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint32Array.smt2  |45.788MiB|45.788MiB|0B| 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint64Array.smt2  |44.232MiB|44.232MiB|0B| 0.0%|
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__2toX.smt2                    |58.612MiB|58.612MiB|0B| 0.0%|
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__div__denominator.smt2        |25.252MiB|25.252MiB|0B| 0.0%|
|d_fvbkv-lib-Math-mod_auto_proofs.i.dfy.Impl__Math____mod__auto__proofs__i.__default.lemma__mod__induction__forall2.smt2  |23.436MiB|23.436MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.FlushPreservesLookups.smt2         |94.54MiB|94.54MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ReqWrite2StepPreservesInv.smt2  |189.0MiB|189.0MiB|0B| 0.0%|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesProcessWrite.smt2  |97.748MiB|97.748MiB|0B| 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.PageInNodeResp.smt2                        |172.0MiB|172.0MiB|0B| 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.append.smt2   |59.652MiB|59.652MiB|0B| 0.0%|
|d_fvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.set__bit__to__0__self__uint64.smt2  |38.04MiB|38.04MiB|0B| 0.0%|
|d_fvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.set__bit__to__1__self__uint64.smt2  |37.736MiB|37.736MiB|0B| 0.0%|
|d_fvbkv-lib-Buckets-KMBPKVOps.i.dfy.Impl__KMBPKVOps.__default.IndexFillDpkv.smt2            |189.0MiB|189.0MiB|0B| 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.BinarySearchQuery.smt2          |64.488MiB|64.488MiB|0B| 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.UniqueRepr.smt2  |31.8MiB|31.8MiB|0B| 0.0%|
|d_fvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.SplitIndexAllKeys.smt2  |207.0MiB|207.0MiB|0B| 0.0%|
|d_fvbkv-lib-DataStructures-LruImpl.i.dfy.Impl__LruImpl.LruImplQueue.Use.smt2                |172.0MiB|172.0MiB|0B| 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SubIndex.smt2    |107.0MiB|107.0MiB|0B| 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SubReprLowerBound.smt2  |32.032MiB|32.032MiB|0B| 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallArray.smt2  |58.552MiB|58.552MiB|0B| 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint32Array.smt2  |45.788MiB|45.788MiB|0B| 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint64Array.smt2  |44.232MiB|44.232MiB|0B| 0.0%|
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__2toX.smt2                    |58.612MiB|58.612MiB|0B| 0.0%|
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__div__denominator.smt2        |25.252MiB|25.252MiB|0B| 0.0%|
|d_fvbkv-lib-Math-mod_auto_proofs.i.dfy.Impl__Math____mod__auto__proofs__i.__default.lemma__mod__induction__forall2.smt2  |23.436MiB|23.436MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|s_komodo-1509.4.smt2                                                                       |  20.466s |5431.0MiB|
|s_komodo-1504.4.smt2                                                                       |  20.393s |3766.0MiB|
|d_komodo-verified-sha-sha256.i.dfyImpl___module.__default.lemma__SHA256FinalHelper1.smt2   |  20.109s |888.0MiB|
|d_komodo-verified-ptebits.i.dfyImpl___module.__default.lemma__l1ptesmatch.smt2             |   2.816s |278.0MiB|
|d_komodo-verified-verify.gen.dfyImpl___module.__default.va__lemma__svc__returning__verify__inner.smt2 |  20.062s |277.0MiB|
|d_komodo-verified-verify.gen.dfyImpl___module.__default.va__lemma__svc__returning__verify.smt2 |  20.041s |221.0MiB|
|d_fvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.SplitIndexAllKeys.smt2 |  20.054s |207.0MiB|
|d_lvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.Impl__PivotBetreeSpecRefinement.__default.SplitChildrenConsistent.smt2 |  20.047s |203.0MiB|
|d_komodo-verified-secprop-conf_ni.i.dfyImpl___module.__default.lemma__initL2PTable__loweq__pdb.smt2 |  20.053s |193.0MiB|
|d_fvbkv-lib-Buckets-KMBPKVOps.i.dfy.Impl__KMBPKVOps.__default.IndexFillDpkv.smt2           |  20.054s |189.0MiB|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ReqWrite2StepPreservesInv.smt2 |  15.620s |189.0MiB|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.PageInNodeResp.smt2                       |  18.768s |172.0MiB|
|d_fvbkv-lib-DataStructures-LruImpl.i.dfy.Impl__LruImpl.LruImplQueue.Use.smt2               |  15.250s |172.0MiB|
|d_lvbkv-lib-Buckets-BucketsLib.i.dfy.Impl__BucketsLib.__default.WFProperSplitBucketInList.smt2 |  20.042s |123.0MiB|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SubIndex.smt2   |  12.663s |107.0MiB|
|d_lvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__LMutableBtree.__default.InsertIndex.smt2 |   5.618s |101.0MiB|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesProcessWrite.smt2 |   1.485s |97.748MiB|
|d_lvbkv-PivotBetree-PivotBetreeSpecWFNodes.i.dfy.Impl__PivotBetreeSpecWFNodes.__default.ValidSplitWritesInvNodes.smt2 |   1.386s |96.72MiB|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.FlushPreservesLookups.smt2        |   4.330s |94.54MiB|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.BinarySearchQuery.smt2         |   2.743s |64.488MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|s_komodo-1509.4.smt2                                                                       |  20.466s |5431.0MiB|
|s_komodo-1504.4.smt2                                                                       |  20.393s |3766.0MiB|
|d_komodo-verified-sha-sha256.i.dfyImpl___module.__default.lemma__SHA256FinalHelper1.smt2   |  20.109s |888.0MiB|
|d_komodo-verified-ptebits.i.dfyImpl___module.__default.lemma__l1ptesmatch.smt2             |   2.816s |278.0MiB|
|d_komodo-verified-verify.gen.dfyImpl___module.__default.va__lemma__svc__returning__verify__inner.smt2 |  20.062s |277.0MiB|
|d_komodo-verified-verify.gen.dfyImpl___module.__default.va__lemma__svc__returning__verify.smt2 |  20.041s |221.0MiB|
|d_fvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.SplitIndexAllKeys.smt2 |  20.054s |207.0MiB|
|d_lvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.Impl__PivotBetreeSpecRefinement.__default.SplitChildrenConsistent.smt2 |  20.047s |203.0MiB|
|d_komodo-verified-secprop-conf_ni.i.dfyImpl___module.__default.lemma__initL2PTable__loweq__pdb.smt2 |  20.053s |193.0MiB|
|d_fvbkv-lib-Buckets-KMBPKVOps.i.dfy.Impl__KMBPKVOps.__default.IndexFillDpkv.smt2           |  20.054s |189.0MiB|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ReqWrite2StepPreservesInv.smt2 |  15.620s |189.0MiB|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.PageInNodeResp.smt2                       |  18.768s |172.0MiB|
|d_fvbkv-lib-DataStructures-LruImpl.i.dfy.Impl__LruImpl.LruImplQueue.Use.smt2               |  15.250s |172.0MiB|
|d_lvbkv-lib-Buckets-BucketsLib.i.dfy.Impl__BucketsLib.__default.WFProperSplitBucketInList.smt2 |  20.042s |123.0MiB|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SubIndex.smt2   |  12.663s |107.0MiB|
|d_lvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__LMutableBtree.__default.InsertIndex.smt2 |   5.618s |101.0MiB|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesProcessWrite.smt2 |   1.485s |97.748MiB|
|d_lvbkv-PivotBetree-PivotBetreeSpecWFNodes.i.dfy.Impl__PivotBetreeSpecWFNodes.__default.ValidSplitWritesInvNodes.smt2 |   1.386s |96.72MiB|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.FlushPreservesLookups.smt2        |   4.330s |94.54MiB|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.BinarySearchQuery.smt2         |   2.743s |64.488MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.FlushPreservesLookups.smt2         |   4.330s  |   4.330s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ReqWrite2StepPreservesInv.smt2  |  15.620s  |  15.620s  |   0.000s  | 0.0%|
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesProcessWrite.smt2  |   1.485s  |   1.485s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.PageInNodeResp.smt2                        |  18.768s  |  18.768s  |   0.000s  | 0.0%|
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.append.smt2   |   0.799s  |   0.799s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.set__bit__to__0__self__uint64.smt2  |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.set__bit__to__1__self__uint64.smt2  |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-KMBPKVOps.i.dfy.Impl__KMBPKVOps.__default.IndexFillDpkv.smt2            |  20.054s  |  20.054s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.BinarySearchQuery.smt2          |   2.743s  |   2.743s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.UniqueRepr.smt2  |   0.313s  |   0.313s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.SplitIndexAllKeys.smt2  |  20.054s  |  20.054s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-LruImpl.i.dfy.Impl__LruImpl.LruImplQueue.Use.smt2                |  15.250s  |  15.250s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SubIndex.smt2    |  12.663s  |  12.663s  |   0.000s  | 0.0%|
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SubReprLowerBound.smt2  |   0.373s  |   0.373s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallArray.smt2  |   1.646s  |   1.646s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint32Array.smt2  |   1.153s  |   1.153s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint64Array.smt2  |   1.022s  |   1.022s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__2toX.smt2                    |   0.576s  |   0.576s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__div__denominator.smt2        |   0.317s  |   0.317s  |   0.000s  | 0.0%|
|d_fvbkv-lib-Math-mod_auto_proofs.i.dfy.Impl__Math____mod__auto__proofs__i.__default.lemma__mod__induction__forall2.smt2  |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|d_komodo-verified-ptebits.i.dfyImpl___module.__default.lemma__l1ptesmatch.smt2              |   2.816s  |   2.816s  |   0.000s  | 0.0%|
|d_komodo-verified-secprop-conf_ni.i.dfyImpl___module.__default.lemma__initL2PTable__loweq__pdb.smt2  |  20.053s  |  20.053s  |   0.000s  | 0.0%|
|d_komodo-verified-sha-sha256.i.dfyImpl___module.__default.lemma__SHA256FinalHelper1.smt2    |  20.109s  |  20.109s  |   0.000s  | 0.0%|
|d_komodo-verified-verify.gen.dfyImpl___module.__default.va__lemma__svc__returning__verify.smt2  |  20.041s  |  20.041s  |   0.000s  | 0.0%|
|d_komodo-verified-verify.gen.dfyImpl___module.__default.va__lemma__svc__returning__verify__inner.smt2  |  20.062s  |  20.062s  |   0.000s  | 0.0%|
|d_lvbkv-Impl-JournalistImpl.i.dfy.Impl__JournalistImpl.Journalist.append.smt2               |   1.983s  |   1.983s  |   0.000s  | 0.0%|
|d_lvbkv-MapSpec-TSJMap_Refines_ThreeStateVersionedMap.i.dfy.Impl__TSJMap__Refines__ThreeStateVersionedMap.__default.RefinesReplay.smt2  |   0.403s  |   0.403s  |   0.000s  | 0.0%|
|d_lvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.Impl__PivotBetreeSpecRefinement.__default.SplitChildrenConsistent.smt2  |  20.047s  |  20.047s  |   0.000s  | 0.0%|
|d_lvbkv-PivotBetree-PivotBetreeSpecWFNodes.i.dfy.Impl__PivotBetreeSpecWFNodes.__default.ValidSplitWritesInvNodes.smt2  |   1.386s  |   1.386s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Base-total_order_impl.i.dfy.Impl__Total__Order__Impl.__default.ArrayLargestLtePlus1Linear.smt2  |   0.187s  |   0.187s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-BucketsLib.i.dfy.Impl__BucketsLib.__default.WFProperSplitBucketInList.smt2  |  20.042s  |  20.042s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.DynamicPkv.Append.smt2                  |   1.589s  |   1.589s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Checksums-BitLemmas.i.dfy.Impl__BitLemmas.__default.eq__from__unpack__LittleEndian__Uint32__eq.smt2  |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|d_lvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__LMutableBtree.__default.InsertIndex.smt2  |   5.618s  |   5.618s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Lang-LinearSequence.i.dfy.Impl__LinearSequence__i.__default.AllocAndMoveLseq.smt2  |   0.207s  |   0.207s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallArray.smt2  |   0.789s  |   0.789s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallByteArray.smt2  |   0.399s  |   0.399s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallByteArrayInterior.smt2  |   0.669s  |   0.669s  |   0.000s  | 0.0%|
|d_lvbkv-lib-Math-Nonlinear.i.dfy.Impl__NonlinearLemmas.__default.div__denom__ge__1.smt2     |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|s_komodo-1504.4.smt2                                                                        |  20.393s  |  20.393s  |   0.000s  | 0.0%|
</details>
