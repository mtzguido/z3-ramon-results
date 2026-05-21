# .

* SAT 0
* UNSAT 181
* TIMEOUT 55
* UNKNOWN 17

* ERRORS 140 (not-run:140)

# Meta data

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


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|d_lvbkv-lib-Base-mathematics.i.dfy.Impl__Mathematics.__default.DivCeilLT.smt2 |    0.099s | 21.992MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Base-mathematics.i.dfy.Impl__Mathematics.__default.PosMulPreservesOrder.smt2 |    0.100s | 22.048MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Math-mul.i.dfy.CheckWellformed__Math____mul__i.__default.mul__recursive.smt2 |    0.110s | 22.516MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Math-mul.i.dfy.Impl__Math____mul__i.__default.lemma__mul__one__to__one.smt2 |    0.200s | 27.172MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__div__multiples__vanish__fancy.smt2 |    0.223s | 23.452MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__add__mul__div.smt2 |    0.234s | 23.76MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Base-Sequences.i.dfy.Impl__Sequences.__default.DisjointConcatenation.smt2 |    0.242s | 25.64MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Base-sequences.i.dfy.Impl__Sequences.__default.DisjointConcatenation.smt2 |    0.242s | 24.96MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Base-total_order.i.dfy.Impl__Total__Preorder.__default.ExistsBiggestInSet.smt2 |    0.263s | 26.052MiB| unknown | 0 |  |  |
|d_fvbkv-lib-Base-total_order.i.dfy.Impl__Integer__Order.__default.FlattenStrictlySorted.smt2 |    0.276s | 27.208MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Base-Multisets.i.dfy.Impl__Multisets.__default.FoldSeqRemove.smt2 |    0.301s | 27.364MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Base-total_order_impl.i.dfy.Impl__Total__Order__Impl.__default.ArrayLargestLtePlus1Linear.smt2 |    0.329s | 26.704MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Marshalling-Util.i.dfy.Impl__Common____Util__i.__default.seqIntoArrayOpt.smt2 |    0.343s | 32.78MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Checksums-CRC32C_Lemmas.i.dfy.Impl__CRC32C__Lemmas.__default.four__slices.smt2 |    0.346s | 31.224MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Base-total_order_impl.i.dfy.Impl__Total__Order__Impl.__default.ArrayLargestLtPlus1.smt2 |    0.357s | 28.304MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Base-total_order_impl.i.dfy.Impl__Total__Order__Impl.__default.ArrayLargestLtePlus1.smt2 |    0.363s | 28.5MiB| unsat | 0 |  |  |
|d_lvbkv-MapSpec-TSJ.i.dfy.Impl__TSJ.__default.Move1to2StepPreservesInv.smt2 |    0.400s | 30.968MiB| unsat | 0 |  |  |
|d_fvbkv-MapSpec-TSJ.i.dfy.Impl__TSJ.__default.CrashStepPreservesInv.smt2 |    0.406s | 31.424MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.CheckWellformed__PackedStringArray.__default.psaSeq.smt2 |    0.413s | 28.612MiB| unsat | 0 |  |  |
|d_fvbkv-lib-DataStructures-LruImpl.i.dfy.Impl__LruImpl.__default.lemmaGetRemoveQueueIndex.smt2 |    0.414s | 29.608MiB| unsat | 0 |  |  |
|d_lvbkv-MapSpec-TSJ.i.dfy.Impl__TSJ.__default.CrashStepPreservesInv.smt2 |    0.425s | 31.996MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.PsaSuffix.smt2 |    0.430s | 29.652MiB| unsat | 0 |  |  |
|d_fvbkv-MapSpec-TSJ.i.dfy.Impl__TSJ.__default.Move1to2StepPreservesInv.smt2 |    0.439s | 31.26MiB| unsat | 0 |  |  |
|d_lvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.writeOntoPreservesSlice.smt2 |    0.447s | 31.248MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Base-Arrays.i.dfy.Impl__Arrays.__default.replace1with2.smt2 |    0.449s | 29.712MiB| unknown | 0 |  |  |
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.psaAppendIAppend.smt2 |    0.499s | 30.24MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.IndexOfFirstKeyGt.smt2 |    0.505s | 31.076MiB| unsat | 0 |  |  |
|d_lvbkv-lib-DataStructures-KMBtree.i.dfy.Impl__KMBtreeModel.__default.IndexesNonempty.smt2 |    0.516s | 32.576MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Buckets-PackedStringArray.i.dfy.CheckWellformed__PackedStringArray.__default.psaSeq.smt2 |    0.524s | 30.74MiB| unsat | 0 |  |  |
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBlockOfJournalRange.smt2 |    0.542s | 30.936MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.ToSeq.smt2 |    0.551s | 31.988MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.ToSeq.smt2 |    0.554s | 30.48MiB| unsat | 0 |  |  |
|d_komodo-verified-sha-sha256.i.dfyImpl___module.__default.lemma__InputHelper.smt2 |    0.562s | 34.216MiB| unknown | 0 |  |  |
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBytesSplit.smt2 |    0.569s | 31.396MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.ImageSubset.smt2 |    0.570s | 33.584MiB| unknown | 0 |  |  |
|d_lvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.psaAppendIAppend.smt2 |    0.572s | 32.052MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.ImageEquiv.smt2 |    0.592s | 33.116MiB| unknown | 0 |  |  |
|d_fvbkv-lib-Buckets-BucketsLib.i.dfy.Impl__BucketsLib.__default.SortedSeqOfKeyValueHasKey.smt2 |    0.603s | 33.572MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.UniqueRepr.smt2 |    0.607s | 32.88MiB| unsat | 0 |  |  |
|d_lvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.journalRangeFromHasChecksums.smt2 |    0.624s | 34.492MiB| unsat | 0 |  |  |
|d_lvbkv-Impl-JournalistImpl.i.dfy.Impl__JournalistImpl.Journalist.reallocJournalEntries.smt2 |    0.643s | 34.856MiB| unsat | 0 |  |  |
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.journalRangeFromHasChecksums.smt2 |    0.665s | 34.992MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.WeightSplitBucketAdditive.smt2 |    0.679s | 35.008MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.psaAppendSeqAdditive.smt2 |    0.699s | 36.688MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.ImageIntersect.smt2 |    0.723s | 33.576MiB| unsat | 0 |  |  |
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.InitImpliesInv.smt2 |    0.724s | 50.608MiB| unknown | 0 |  |  |
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.parsesFromStuff.smt2 |    0.733s | 35.524MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.SplitBucketImage.smt2 |    0.735s | 33.948MiB| unknown | 0 |  |  |
|d_fvbkv-lib-Buckets-BucketModel.i.dfy.Impl__BucketModel.__default.BucketListItemFlush__eq.smt2 |    0.783s | 52.984MiB| unknown | 0 |  |  |
|d_lvbkv-Impl-JournalistImpl.i.dfy.Impl__JournalistImpl.Journalist.packageFrozenJournal.smt2 |    0.812s | 37.972MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.ComputeValidStringLens.smt2 |    0.817s | 45.924MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Checksums-CRC32C_Lut.i.dfy.Impl__CRC32C__Lut.__default.reverse__p.smt2 |    0.867s | 57.844MiB| unknown | 0 |  |  |
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.psaCanAppendI.smt2 |    0.869s | 37.344MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.BinarySearchIndexOfFirstKeyGte.smt2 |    0.875s | 33.924MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.CheckWellformed__PackedKV.__default.psaSeq__Messages.smt2 |    0.878s | 45.264MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.CheckWellformed__DynamicPkv.__default.PSAPopFrontWeight.smt2 |    0.903s | 47.8MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.bit__or__is__union__uint64.smt2 |    0.908s | 49.564MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Buckets-PackedKVMarshalling.i.dfy.Impl__PackedKVMarshalling.__default.ComputeWF.smt2 |    0.911s | 48.18MiB| unsat | 0 |  |  |
|d_fvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.Impl__PivotBetreeSpecRefinement.__default.InUpperBoundAndNot.smt2 |    0.920s | 47.228MiB| unknown | 0 |  |  |
|d_komodo-verified-entrybits.i.dfyImpl___module.__default.lemma__sp__bit__helper.smt2 |    0.930s | 51.756MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.CheckWellformed__DynamicPkv.__default.PSAPopFrontWeightSuffix.smt2 |    0.935s | 47.68MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.__default.computePivotIndexes.smt2 |    0.947s | 48.944MiB| unsat | 0 |  |  |
|d_lvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeEqJournalBlocks.smt2 |    0.977s | 38.576MiB| unsat | 0 |  |  |
|d_lvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.Impl__PivotBetreeSpecRefinement.__default.InUpperBoundAndNot.smt2 |    0.986s | 49.592MiB| unknown | 0 |  |  |
|d_lvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBytesSplit.smt2 |    0.990s | 36.348MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.ComputeIsSorted.smt2 |    0.992s | 47.628MiB| unsat | 0 |  |  |
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.packageFrozenJournal.smt2 |    1.004s | 39.992MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.CheckWellformed__PackedKV.__default.AppendEncodedMessage.smt2 |    1.024s | 48.552MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.ISeqInduction.smt2 |    1.025s | 51.372MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.WeightBucketListItemFlush.smt2 |    1.057s | 54.168MiB| unsat | 0 |  |  |
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeOfByteSeqGetI.smt2 |    1.059s | 35.808MiB| unsat | 0 |  |  |
|d_fvbkv-PivotBetree-PivotBetreeSpec.i.dfy.Impl__PivotBetreeSpec.__default.CutoffNodeCorrect.smt2 |    1.069s | 49.984MiB| unsat | 0 |  |  |
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.packageInMemoryJournal.smt2 |    1.077s | 41.312MiB| unsat | 0 |  |  |
|d_fvbkv-Impl-JournalistParsingImpl.i.dfy.Impl__JournalistParsingImpl.__default.ParseJournalRangeOfBytes.smt2 |    1.092s | 36.036MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.WeightBucketIs.smt2 |    1.149s | 51.744MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.CheckWellformed__PackedKV.__default.subPkv.smt2 |    1.178s | 49.728MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.BinarySearchIndexOfFirstKeyGt.smt2 |    1.194s | 36.92MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Buckets-BucketsLib.i.dfy.Impl__BucketsLib.__default.WFProperMergeBucketsInList.smt2 |    1.206s | 53.092MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallByteArray.smt2 |    1.219s | 39.748MiB| unknown | 0 |  |  |
|d_fvbkv-lib-Buckets-BucketsLib.i.dfy.Impl__BucketsLib.__default.WFProperSplitBucketInList.smt2 |    1.231s | 53.46MiB| unknown | 0 |  |  |
|d_komodo-verified-entry.i.dfyImpl___module.__default.lemma__onlyDataPagesAreWritable.smt2 |    1.232s | 62.064MiB| unsat | 0 |  |  |
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.freeze.smt2 |    1.240s | 41.076MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.WeightSplitBucketInListLe.smt2 |    1.253s | 54.316MiB| unsat | 0 |  |  |
|d_lvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.InitImpliesInv.smt2 |    1.269s | 86.164MiB| unknown | 0 |  |  |
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.__default.PSAPopFrontWeightSuffix.smt2 |    1.309s | 51.156MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint32Array.smt2 |    1.380s | 41.496MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint64Array.smt2 |    1.552s | 42.504MiB| unsat | 0 |  |  |
|d_komodo-verified-smcapi.i.dfyImpl___module.__default.lemma__sha256__concat.smt2 |    1.573s | 56.628MiB| unknown | 0 |  |  |
|d_fvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.WeightWellMarshalledListPointwiseLe.smt2 |    1.592s | 68.896MiB| unsat | 0 |  |  |
|d_fvbkv-BlockCacheSystem-JournalInterval.i.dfy.Impl__JournalIntervals.__default.Disk__Journal__append.smt2 |    1.615s | 35.276MiB| unsat | 0 |  |  |
|d_lvbkv-Versions-CompositeView_Refines_TSJMap.i.dfy.Impl__CompositeView__Refines__TSJMap.__default.CrashRefines.smt2 |    1.623s | 56.344MiB| unsat | 0 |  |  |
|d_fvbkv-Impl-JournalistImpl.i.dfy.Impl__JournalistImpl.Journalist.parseJournals.smt2 |    1.654s | 57.128MiB| unsat | 0 |  |  |
|d_lvbkv-PivotBetree-TSJPivotBetree.i.dfy.Impl__TSJPivotBetree.__default.Move3StepPreservesInv.smt2 |    1.669s | 98.176MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.GetLastKey.smt2 |    1.687s | 54.784MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Base-Multisets.i.dfy.Impl__Multisets.__default.ApplyAdditive.smt2 |    1.909s | 66.512MiB| unsat | 0 |  |  |
|d_lvbkv-Impl-NodeImpl.i.dfy.Impl__NodeImpl.Node.BucketsWellMarshalled.smt2 |    1.944s | 79.948MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.SplitLeft.smt2 |    1.966s | 54.66MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.__default.PSAPopFrontWeight.smt2 |    2.009s | 54.792MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.WeightKeyListIs.smt2 |    2.068s | 56.616MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.CheckWellformed__PackedKV.__default.subPkv.smt2 |    2.087s | 53.812MiB| unsat | 0 |  |  |
|d_lvbkv-Impl-JournalistParsingImpl.i.dfy.Impl__JournalistParsingImpl.__default.ParseJournalRangeOfBytes.smt2 |    2.146s | 57.412MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.__default.WeightBucketPkv__eq__WeightPkv.smt2 |    2.207s | 57.028MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallTupleContents.smt2 |    2.210s | 42.388MiB| unsat | 0 |  |  |
|d_komodo-verified-pagedb.i.dfyImpl___module.__default.extractPageDbToAbstractOne.smt2 |    2.249s | 64.5MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.computeWeightOfSeq.smt2 |    2.274s | 62.652MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.Imaps.smt2 |    2.416s | 58.108MiB| unsat | 0 |  |  |
|d_komodo-verified-mapping.i.dfyImpl___module.__default.lemma__installL1PTEInPageDb__dataPageRefs.smt2 |    2.480s | 58.576MiB| unsat | 0 |  |  |
|d_komodo-verified-pagedb.i.dfyImpl___module.__default.extractPageDbToAbstract.smt2 |    2.486s | 67.628MiB| unsat | 0 |  |  |
|d_fvbkv-Impl-NodeModel.i.dfy.Impl__NodeModel.__default.CutoffNodeAndKeepRightCorrect.smt2 |    2.513s | 91.784MiB| unsat | 0 |  |  |
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.GetSuccessorInBucketStackResult.smt2 |    2.536s | 55.676MiB| unknown | 0 |  |  |
|d_komodo-verified-sha-memory-helpers.i.dfyImpl___module.__default.lemma__AddrMemContentsSeq__adds.smt2 |    2.666s | 57.292MiB| unsat | 0 |  |  |
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.CheckWellformed__CommitterCommitModel.__default.WriteOutJournal.smt2 |    2.729s | 96.136MiB| unsat | 0 |  |  |
|d_komodo-verified-ptables.i.dfyImpl___module.__default.lemma__WritablePages.smt2 |    2.737s | 60.308MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Checksums-CRC32C_Lut.i.dfy.CheckWellformed__CRC32C__Lut.__default.combine.smt2 |    2.868s | 83.352MiB| unsat | 0 |  |  |
|d_fvbkv-lib-DataStructures-MutableMapModel.i.dfy.CheckWellformed__MutableMapModel.__default.SimpleIterInc.smt2 |    2.877s | 40.612MiB| unsat | 0 |  |  |
|d_lvbkv-Impl-SplitModel.i.dfy.Impl__SplitModel.__default.lemmaChildrenConditionsCutoffNode.smt2 |    2.920s | 99.0MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.CloneSeq.smt2 |    2.952s | 62.464MiB| unsat | 0 |  |  |
|d_komodo-verified-kom_utils.gen.dfyImpl___module.__default.va__lemma__unstack__lr.smt2 |    2.977s | 69.224MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.__default.IMessagesSlice.smt2 |    3.098s | 58.804MiB| unsat | 0 |  |  |
|d_lvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.Impl__PivotBetreeSpecRefinement.__default.SplitMergeBuffersChildrenEq.smt2 |    3.144s | 93.34MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Buckets-BucketsLib.i.dfy.Impl__BucketsLib.__default.GetJoinBucketListEq.smt2 |    3.331s | 58.608MiB| unsat | 0 |  |  |
|d_lvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.DiskInternalStepPreservesInv.smt2 |    3.374s | 110.0MiB| unsat | 0 |  |  |
|d_komodo-verified-entry.i.dfyImpl___module.__default.lemma__contentsOfPage__corresponds.smt2 |    3.376s | 75.072MiB| unsat | 0 |  |  |
|d_lvbkv-Impl-NodeImpl.i.dfy.Impl__NodeImpl.Node.CutoffNodeAndKeepLeft.smt2 |    3.394s | 90.264MiB| unsat | 0 |  |  |
|d_fvbkv-Impl-CommitterCommitModel.i.dfy.Impl__CommitterCommitModel.__default.WriteOutJournalCorrect.smt2 |    3.463s | 109.0MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Buckets-BucketsLib.i.dfy.Impl__BucketsLib.__default.SplitBucketOnPivotsAt.smt2 |    3.692s | 56.388MiB| unsat | 0 |  |  |
|d_fvbkv-Impl-BucketGeneratorModel.i.dfy.Impl__BucketGeneratorModel.__default.GenFromBucketStackWithLowerBoundYieldsComposeSeq.smt2 |    3.917s | 58.88MiB| unsat | 0 |  |  |
|d_fvbkv-lib-DataStructures-MutableBtreeBulkOperations.i.dfy.Impl__MutableBtreeBulkOperations.__default.CountElements.smt2 |    3.935s | 63.684MiB| unsat | 0 |  |  |
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.PageInIndirectionTableRespCorrect.smt2 |    4.048s | 98.0MiB| unsat | 0 |  |  |
|d_lvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectResultingGraphAfterAllocs.smt2 |    4.067s | 62.36MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Buckets-BucketsLib.i.dfy.Impl__BucketsLib.__default.BInternalPreWFWellMarshalled.smt2 |    4.217s | 64.492MiB| unsat | 0 |  |  |
|d_komodo-verified-verify_input.gen.dfyCheckWellformed___module.__default.lemma__grab__user__words.smt2 |    4.265s | 115.0MiB| unsat | 0 |  |  |
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__AllPages.smt2 |    4.481s | 65.856MiB| unsat | 0 |  |  |
|d_fvbkv-Impl-NodeImpl.i.dfy.Impl__NodeImpl.Node.__ctor.smt2  |    4.483s | 101.0MiB| unsat | 0 |  |  |
|d_komodo-verified-verify_input.gen.dfyCheckWellformed___module.__default.lemma__grab__measurement.smt2 |    4.553s | 119.0MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallByteArrayInterior.smt2 |    4.586s | 61.58MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Base-Arrays.i.dfy.Impl__Arrays.__default.replace1with2.smt2 |    4.657s | 56.152MiB| unsat | 0 |  |  |
|d_komodo-verified-attest_input.gen.dfyCheckWellformed___module.__default.va__lemma__arrange__attestation__input.smt2 |    4.758s | 102.0MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallTupleContents.smt2 |    4.917s | 60.328MiB| unsat | 0 |  |  |
|d_lvbkv-Impl-QueryModel.i.dfy.Impl__QueryModel.__default.AugmentLookup.smt2 |    4.970s | 106.0MiB| unsat | 0 |  |  |
|d_lvbkv-Impl-MarshallingModel.i.dfy.Impl__MarshallingModel.__default.WeightBucketListLteSize.smt2 |    5.007s | 104.0MiB| unsat | 0 |  |  |
|d_komodo-verified-ptables.i.dfyImpl___module.__default.lemma__ptablesmatch_split0.smt2 |    5.121s | 105.0MiB| unsat | 0 |  |  |
|d_komodo-verified-sha-sha256.s.dfyCheckWellformed___module.__default.K__SHA256.smt2 |    5.171s | 53.484MiB| unsat | 0 |  |  |
|d_fvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeEqJournalBlocks.smt2 |    5.366s | 57.052MiB| unknown | 0 |  |  |
|d_lvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.KeyValSeqToPivots.smt2 |    6.039s | 109.0MiB| unsat | 0 |  |  |
|d_fvbkv-MapSpec-TSJMap_Refines_ThreeStateVersionedMap.i.dfy.Impl__TSJMap__Refines__ThreeStateVersionedMap.__default.RefinesReplay.smt2 |    6.044s | 108.0MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallArrayContents.smt2 |    6.053s | 109.0MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallArrayContents.smt2 |    6.124s | 57.304MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.DynamicPkv.Append.smt2 |    6.136s | 65.368MiB| unsat | 0 |  |  |
|d_fvbkv-Impl-IOModel.i.dfy.Impl__IOModel.__default.FindIndirectionTableLocationAndRequestWriteCorrect.smt2 |    6.180s | 107.0MiB| unsat | 0 |  |  |
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.CheckWellformed__IndirectionTableModel.__default.UpdateAndRemoveLoc.smt2 |    6.327s | 99.404MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Buckets-BucketModel.i.dfy.Impl__BucketModel.__default.mergeToOneOneChild__eq__BucketList.smt2 |    6.512s | 59.384MiB| unsat | 0 |  |  |
|d_lvbkv-Betree-AsyncBetree.i.dfy.Impl__AsyncBetree.__default.QueryAdvanceChangesLookup.smt2 |    6.531s | 65.128MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Buckets-BucketsLib.i.dfy.Impl__BucketsLib.__default.BInternalWFBucket.smt2 |    7.219s | 104.0MiB| unsat | 0 |  |  |
|d_komodo-verified-ptables.i.dfyImpl___module.__default.lemma__l2tablesmatch.smt2 |    7.230s | 103.0MiB| unsat | 0 |  |  |
|d_komodo-verified-ptebits.i.dfyImpl___module.__default.lemma__nonexec__mapping.smt2 |    7.261s | 66.808MiB| unsat | 0 |  |  |
|d_fvbkv-ByteBlockCacheSystem-Marshalling.i.dfy.Impl__Marshalling.__default.pivotTableWeightUpperBound.smt2 |    7.296s | 134.0MiB| unsat | 0 |  |  |
|d_komodo-verified-kom_utils.gen.dfyCheckWellformed___module.__default.va__lemma__stack__nonvolatiles.smt2 |    7.652s | 115.0MiB| unsat | 0 |  |  |
|d_komodo-verified-entry.gen.dfyImpl___module.__default.lemma__aligned__sp.smt2 |    7.722s | 104.0MiB| unsat | 0 |  |  |
|d_lvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.FindIndirectionTableLocationAndRequestWrite.smt2 |    7.823s | 170.0MiB| unsat | 0 |  |  |
|d_lvbkv-BlockCacheSystem-BlockCache.i.dfy.Impl__BlockCache.__default.DirtyStepPreservesInv.smt2 |    8.073s | 103.0MiB| unsat | 0 |  |  |
|d_lvbkv-PivotBetree-PivotBetree.i.dfy.Impl__PivotBetree.__default.GCStepRefines.smt2 |    8.079s | 99.044MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.all__in__set__implies__all1s__uint64.smt2 |    8.154s | 29.572MiB| unsat | 0 |  |  |
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.parseEntriesFromHasEntriesI.smt2 |    8.203s | 69.968MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.__default.WeightBucketPkv__eq__WeightPkv.smt2 |    8.376s | 104.0MiB| unsat | 0 |  |  |
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.lemma__writeJournalEntries.smt2 |    8.460s | 67.152MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.DynamicPsa.appendSeq.smt2 |    8.766s | 108.0MiB| unsat | 0 |  |  |
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeepingNoSuccsUpdate.smt2 |    9.114s | 169.0MiB| unsat | 0 |  |  |
|d_fvbkv-Impl-BookkeepingImpl.i.dfy.Impl__BookkeepingImpl.__default.writeBookkeeping.smt2 |    9.457s | 169.0MiB| unsat | 0 |  |  |
|d_komodo-verified-ptables.i.dfyImpl___module.__default.lemma__ptablesmatch.smt2 |    9.739s | 105.0MiB| unsat | 0 |  |  |
|d_komodo-verified-entry.i.dfyCheckWellformed___module.__default.KomExceptionHandlerInvariant.smt2 |    9.791s | 99.808MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.__default.pkvList2BucketList.smt2 |   10.120s | 99.992MiB| unsat | 0 |  |  |
|d_komodo-verified-verify_input.gen.dfyImpl___module.__default.va__lemma__arrange__verify__measurement__in__memory.smt2 |   10.169s | 119.0MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Buckets-PackedKVMarshalling.i.dfy.Impl__PackedKVMarshalling.__default.SizeOfVPackedStringArrayIsMessageListWeight.smt2 |   10.285s | 104.0MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.WeightBucketListItemFlushInner.smt2 |   10.423s | 95.568MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.SplitRight.smt2 |   10.448s | 107.0MiB| unsat | 0 |  |  |
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__exceptionHandled__atkr.smt2 |   10.537s | 109.0MiB| unsat | 0 |  |  |
|d_komodo-verified-kom_utils.gen.dfyImpl___module.__default.va__lemma__load__page__type.smt2 |   10.699s | 133.0MiB| unsat | 0 |  |  |
|d_lvbkv-Impl-SuccImpl.i.dfy.Impl__SuccImpl.__default.getPathInternal.smt2 |   10.837s | 183.0MiB| unsat | 0 |  |  |
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectPreservesLookups.smt2 |   11.719s | 95.112MiB| unsat | 0 |  |  |
|d_komodo-verified-allocate_page.gen.dfyCheckWellformed___module.__default.va__lemma__allocate__page.smt2 |   11.937s | 98.816MiB| unsat | 0 |  |  |
|d_komodo-verified-verify_input.gen.dfyImpl___module.__default.va__lemma__arrange__verification__input_split0.smt2 |   11.956s | 268.0MiB| unsat | 0 |  |  |
|d_lvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.lemma__writeJournalEntries.smt2 |   12.343s | 82.944MiB| unsat | 0 |  |  |
|d_komodo-verified-verify_input.gen.dfyImpl___module.__default.va__lemma__arrange__user__words__in__memory.smt2 |   13.867s | 121.0MiB| unsat | 0 |  |  |
|d_fvbkv-Impl-SuccModel.i.dfy.Impl__SuccModel.__default.lemmaGetPathResult.smt2 |   13.889s | 172.0MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.SplitOneInList.smt2 |   14.693s | 99.0MiB| unsat | 0 |  |  |
|d_komodo-verified-verify_input.gen.dfyImpl___module.__default.va__lemma__arrange__verify__measurement__in__memory_split0.smt2 |   15.378s | 157.0MiB| unsat | 0 |  |  |
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.strictlySortedKeySeqToVal.smt2 |   16.575s | 175.0MiB| unsat | 0 |  |  |
|d_fvbkv-lib-DataStructures-MutableBtreeBulkOperations.i.dfy.Impl__MutableBtreeBulkOperations.__default.ToSeqSubtree.smt2 |   16.842s | 104.0MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Buckets-KMBPKVOps.i.dfy.Impl__KMBPKVOps.__default.FromPkv.smt2 |   17.156s | 100.0MiB| unsat | 0 |  |  |
|d_komodo-verified-svc_handlers.gen.dfyCheckWellformed___module.__default.va__lemma__svc__returning__verify__step1.smt2 |   17.482s | 188.0MiB| unsat | 0 |  |  |
|d_komodo-verified-map_utils.gen.dfyImpl___module.__default.va__lemma__fetch__l1pte.smt2 |   17.559s | 137.0MiB| unsat | 0 |  |  |
|d_komodo-verified-verify_input.gen.dfyImpl___module.__default.va__lemma__arrange__user__words__in__memory_split0.smt2 |   17.908s | 227.0MiB| unsat | 0 |  |  |
|d_komodo-verified-kom_utils.gen.dfyImpl___module.__default.va__lemma__update__pagedb__entry.smt2 |   18.055s | 140.0MiB| unsat | 0 |  |  |
|d_fvbkv-Impl-SuccImpl.i.dfy.Impl__SuccImpl.__default.getPath.smt2 |   18.346s | 176.0MiB| unsat | 0 |  |  |
|d_fvbkv-lib-DataStructures-MutableMapModel.i.dfy.Impl__MutableMapModel.__default.LemmaReallocIterateResult.smt2 |   18.419s | 137.0MiB| unsat | 0 |  |  |
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.Impl__IndirectionTableModel.__default.LemmaRemoveRefStuff.smt2 |   18.867s | 124.0MiB| unsat | 0 |  |  |
|d_komodo-verified-verify_input.gen.dfyImpl___module.__default.lemma__grab__user__words.smt2 |   20.027s | 167.0MiB| timeout | 0 |  |  |
|d_fvbkv-lib-DataStructures-MutableMapModel.i.dfy.Impl__MutableMapModel.__default.LemmaProbeResult.smt2 |   20.035s | 79.604MiB| timeout | 0 |  |  |
|d_komodo-verified-verify_input.gen.dfyImpl___module.__default.lemma__grab__measurement.smt2 |   20.041s | 171.0MiB| timeout | 0 |  |  |
|d_fvbkv-Impl-BucketSuccessorLoopModel.i.dfy.Impl__BucketSuccessorLoopModel.__default.ProcessGeneratorResult.smt2 |   20.042s | 104.0MiB| timeout | 0 |  |  |
|d_fvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.CloneSeq.smt2 |   20.044s | 110.0MiB| timeout | 0 |  |  |
|d_lvbkv-BlockCacheSystem-BetreeSystem.i.dfy.Impl__BetreeSystem.__default.BlockCacheMoveStepPreservesInv.smt2 |   20.044s | 181.0MiB| timeout | 0 |  |  |
|d_komodo-verified-entry.i.dfyImpl___module.__default.lemma__evalMOVSPCLRUC__inner.smt2 |   20.045s | 121.0MiB| timeout | 0 |  |  |
|d_fvbkv-lib-DataStructures-LruImpl.i.dfy.Impl__LruImpl.LruImplQueue.Remove.smt2 |   20.045s | 97.0MiB| timeout | 0 |  |  |
|d_lvbkv-lib-DataStructures-LinearMutableMap.i.dfy.Impl__LinearMutableMap.__default.Probe.smt2 |   20.045s | 117.0MiB| timeout | 0 |  |  |
|d_lvbkv-Impl-GrowModel.i.dfy.Impl__GrowModel.__default.growCorrect.smt2 |   20.045s | 178.0MiB| timeout | 0 |  |  |
|d_fvbkv-lib-Buckets-BucketModel.i.dfy.Impl__BucketModel.__default.mergeToOneOneChild__eq__topBotAccMerge.smt2 |   20.045s | 97.852MiB| timeout | 0 |  |  |
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__TestMutableBtree.__default.SplitChildOfIndex.smt2 |   20.046s | 120.0MiB| timeout | 0 |  |  |
|d_lvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.bucketsToVal.smt2 |   20.046s | 189.0MiB| timeout | 0 |  |  |
|d_komodo-verified-smcapi.i.dfyImpl___module.__default.kom__smc__map__measure__helper1.smt2 |   20.047s | 135.0MiB| timeout | 0 |  |  |
|d_komodo-verified-exceptions.i.dfyImpl___module.__default.lemma__PrivInterruptInvariants.smt2 |   20.047s | 128.0MiB| timeout | 0 |  |  |
|d_lvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.ISeq__replace1with2.smt2 |   20.048s | 194.0MiB| unsat | 0 |  |  |
|d_lvbkv-lib-DataStructures-MutableMapModel.i.dfy.Impl__MutableMapModel.__default.LemmaReallocIterateResult.smt2 |   20.048s | 142.0MiB| timeout | 0 |  |  |
|d_fvbkv-Impl-CommitterCommitImpl.i.dfy.Impl__CommitterCommitImpl.__default.WriteOutJournal.smt2 |   20.049s | 171.0MiB| timeout | 0 |  |  |
|d_fvbkv-lib-DataStructures-KMBtree.i.dfy.Impl__KMBtree.__default.SplitChildOfIndex.smt2 |   20.049s | 104.0MiB| timeout | 0 |  |  |
|d_komodo-verified-exhandler_state.i.dfyImpl___module.__default.lemma__UserExceptionStateSideEffects.smt2 |   20.049s | 187.0MiB| timeout | 0 |  |  |
|d_komodo-verified-map_utils.gen.dfyCheckWellformed___module.__default.va__lemma__kom__smc__map__measure__sha.smt2 |   20.049s | 218.0MiB| timeout | 0 |  |  |
|d_komodo-verified-attest_input.gen.dfyImpl___module.__default.va__lemma__arrange__real__measurement__in__memory_split1.smt2 |   20.050s | 194.0MiB| timeout | 0 |  |  |
|d_fvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.ISeq__replace1with2.smt2 |   20.050s | 189.0MiB| timeout | 0 |  |  |
|d_fvbkv-lib-Buckets-BucketModel.i.dfy.Impl__BucketModel.__default.mergeToChildrenIterCorrect.smt2 |   20.050s | 104.0MiB| timeout | 0 |  |  |
|s_komodo-1557.3.smt2                                         |   20.051s | 221.0MiB| timeout | 0 |  |  |
|d_komodo-verified-entry.gen.dfyImpl___module.__default.va__lemma__unstack__banked__regs2.smt2 |   20.051s | 186.0MiB| timeout | 0 |  |  |
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.__default.MergeToChildrenIter.smt2 |   20.051s | 195.0MiB| timeout | 0 |  |  |
|d_komodo-verified-init_l2ptable.gen.dfyImpl___module.__default.va__lemma__zero__l2__page.smt2 |   20.051s | 218.0MiB| timeout | 0 |  |  |
|d_lvbkv-BlockCacheSystem-BetreeCache.i.dfy.Impl__BetreeCache.__default.BetreeMoveStepPreservesInv.smt2 |   20.051s | 195.0MiB| timeout | 0 |  |  |
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.RemoveRef.smt2 |   20.051s | 182.0MiB| timeout | 0 |  |  |
|d_komodo-verified-secprop-integ_ni_entry.i.dfyImpl___module.__default.lemma__enter__enc__obs__enter.smt2 |   20.052s | 186.0MiB| timeout | 0 |  |  |
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__updateUserPages__conf__not__atkr.smt2 |   20.053s | 214.0MiB| timeout | 0 |  |  |
|d_fvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.__default.PartialFlush.smt2 |   20.053s | 179.0MiB| timeout | 0 |  |  |
|d_komodo-verified-kom_utils.gen.dfyImpl___module.__default.va__lemma__unstack__nonvolatiles.smt2 |   20.053s | 149.0MiB| timeout | 0 |  |  |
|d_lvbkv-lib-Buckets-PackedKVMarshalling.i.dfy.Impl__PackedKVMarshalling.__default.SizeOfVPackedStringArrayIsKeyListWeight.smt2 |   20.054s | 177.0MiB| timeout | 0 |  |  |
|d_komodo-verified-secprop-integ_ni_entry.i.dfyImpl___module.__default.lemma__enter__loweq__pdb__not__obs.smt2 |   20.054s | 193.0MiB| timeout | 0 |  |  |
|d_komodo-verified-init_addrspace.gen.dfyImpl___module.__default.va__lemma__init__addrspace.smt2 |   20.054s | 216.0MiB| timeout | 0 |  |  |
|d_lvbkv-lib-Buckets-LKMBPKVOps.i.dfy.Impl__LKMBPKVOps.__default.IsKeyMessageTreeInheritance.smt2 |   20.054s | 199.0MiB| timeout | 0 |  |  |
|d_lvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.Impl__PivotBetreeSpecRefinement.__default.MergeChildrenConsistent.smt2 |   20.054s | 192.0MiB| timeout | 0 |  |  |
|d_komodo-verified-map_common.gen.dfyImpl___module.__default.va__lemma__is__valid__mapping__target_k__finish.smt2 |   20.055s | 190.0MiB| timeout | 0 |  |  |
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__enter__loweq__pdb__not__atkr.smt2 |   20.056s | 196.0MiB| timeout | 0 |  |  |
|d_komodo-verified-attest_input.gen.dfyImpl___module.__default.va__lemma__arrange__real__measurement__in__memory_split0.smt2 |   20.057s | 133.0MiB| timeout | 0 |  |  |
|d_komodo-verified-entry.i.dfyImpl___module.__default.lemma__userExecutionUpdatesPageDb.smt2 |   20.058s | 230.0MiB| timeout | 0 |  |  |
|d_komodo-verified-kom_utils.gen.dfyImpl___module.__default.va__lemma__unstack__nonvolatiles__except__lr.smt2 |   20.058s | 157.0MiB| timeout | 0 |  |  |
|d_komodo-verified-svc_handlers.gen.dfyImpl___module.__default.va__lemma__svc__returning__default.smt2 |   20.059s | 192.0MiB| timeout | 0 |  |  |
|d_komodo-verified-attest_input.gen.dfyImpl___module.__default.va__lemma__arrange__attestation__input_split0.smt2 |   20.059s | 264.0MiB| timeout | 0 |  |  |
|d_komodo-verified-svc_handlers.gen.dfyImpl___module.__default.va__lemma__svc__map__data__success.smt2 |   20.059s | 195.0MiB| timeout | 0 |  |  |
|d_komodo-verified-attest_helpers.gen.dfyImpl___module.__default.va__lemma__addrspace__va__for__page__va.smt2 |   20.060s | 144.0MiB| timeout | 0 |  |  |
|d_komodo-verified-map_utils.gen.dfyCheckWellformed___module.__default.va__lemma__kom__smc__map__measure__hash.smt2 |   20.060s | 208.0MiB| timeout | 0 |  |  |
|d_komodo-verified-sha-sha256.i.dfyImpl___module.__default.SHA__padding__words2bytes.smt2 |   20.061s | 200.0MiB| timeout | 0 |  |  |
|d_komodo-verified-init_l2ptable.gen.dfyImpl___module.__default.va__lemma__init__l2ptable__success.smt2 |   20.061s | 237.0MiB| timeout | 0 |  |  |
|d_komodo-verified-sha-hmac.gen.dfyImpl___module.__default.va__lemma__hmac__inner__prep__hash.smt2 |   20.062s | 247.0MiB| timeout | 0 |  |  |
|d_komodo-verified-map_common.gen.dfyImpl___module.__default.va__lemma__is__valid__mapping__target.smt2 |   20.062s | 231.0MiB| timeout | 0 |  |  |
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.FindRefWithNoLoc.smt2 |   20.065s | 179.0MiB| timeout | 0 |  |  |
|d_komodo-verified-verify.gen.dfyImpl___module.__default.va__lemma__compare__memory__to__regs.smt2 |   20.065s | 366.0MiB| timeout | 0 |  |  |
|s_komodo-1518.6.smt2                                         |   20.561s | 3538.0MiB| timeout | 0 |  |  |
|d_lvbkv-lib-Buckets-BucketsLib.i.dfy.Impl__BucketsLib.__default.WFSplitBucketListRight.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_komodo-verified-smc_handler.gen.dfyImpl___module.__default.va__lemma__smc__handler__inner.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-lib-Checksums-CRC32CArrayImpl.i.dfy.Impl__CRC32__C__Array__Impl.__default.compute__crc32__main.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|fs_dice-queries-L0.X509.AliasKeyTBS-6.smt2                   | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.WeightMessageListIs.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.IndexOfFirstKeyGte.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_komodo-verified-attest.gen.dfyImpl___module.__default.va__lemma__compute__hmac_split0.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.CheckWellformed__ByteSystem.__default.ReqReadStepPreservesInv.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_komodo-verified-entry.gen.dfyImpl___module.__default.va__lemma__kom__smc__enterresume.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.CheckWellformed__ByteSystem.__default.NextStepPreservesInv.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|fs_dice-queries-L0.Impl.Certificate-6.smt2                   | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-BlockCacheSystem-BetreeSystem_Refines_StatesViewPivotBetree.i.dfy.Impl__BetreeSystem__Refines__StatesViewPivotBetree.__default.BlockCacheMoveStepRefines.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalRangeOfByteSeqGetI.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_komodo-verified-svc_handlers.gen.dfyImpl___module.__default.va__lemma__svc__map__data__zeropage.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.Impl__PivotBetreeSpecRefinement.__default.CutoffNodeAndKeepRightAgree.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-Impl-InsertModel.i.dfy.CheckWellformed__InsertModel.__default.InsertKeyValueCorrect.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-Impl-InsertModel.i.dfy.Impl__InsertModel.__default.InsertKeyValueCorrect.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_komodo-verified-svc_handlers.gen.dfyImpl___module.__default.lemma__svc__returning__verify__step1__helper.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_fvbkv-lib-Base-SetBijectivity.i.dfy.Impl__SetBijectivity.__default.CrossProductCardinality.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.__default.PartialFlush.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_fvbkv-BlockCacheSystem-BlockJournalCache.i.dfy.Impl__BlockJournalCache.__default.NextPreservesInv.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|fs_dice-queries-X509.ExtFields.KeyUsage-30.smt2              | 1000.000s | -1B| not-run | -1 |  |  |
|fs_vwasm-compiler-common-queries-Compiler.Common.Dataflow-40.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_fvbkv-Impl-DeallocImpl.i.dfy.Impl__DeallocImpl.__default.Dealloc.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_komodo-verified-sha-sha256-one-block.gen.dfyImpl___module.__default.va__abstract__update__Hs.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_komodo-verified-stop.gen.dfyImpl___module.__default.va__lemma__kom__smc__stop.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.DynamicPkv.AppendPkv.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_komodo-verified-finalise.gen.dfyImpl___module.__default.lemma__kom__smc__finalise__success__helper1.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_komodo-verified-svc_handlers.gen.dfyImpl___module.__default.va__lemma__existing__va__ok.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.CheckWellformed__ByteSystem.__default.RespReadStepPreservesInv.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-Impl-EvictImpl.i.dfy.Impl__EvictImpl.__default.EvictOrDealloc.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_fvbkv-Impl-GrowImpl.i.dfy.Impl__GrowImpl.__default.grow.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.CheckWellformed__ByteSystem.__default.ReqWriteStepPreservesInv.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__validEnclaveStepPrime__conf__not__atkr__retnondet.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.PageInNodeResp.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|fs_dice-queries-ASN1.Low.Value.INTEGER-7.smt2                | 1000.000s | -1B| not-run | -1 |  |  |
|fs_dice-queries-ASN1.Spec.Value.BIT_STRING-7.smt2            | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-BlockCacheSystem-BetreeJournalSystem_Refines_CompositeView.i.dfy.Impl__BetreeJournalSystem__Refines__CompositeView.__default.RefinesInit.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-Betree-Betree_Refines_Map.i.dfy.Impl__Betree__Refines__Map.__default.GCStepRefinesMap.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.__default.PSAPopFrontWeight.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|fs_dice-queries-L0.Impl.Certificate-8.smt2                   | 1000.000s | -1B| not-run | -1 |  |  |
|fs_dice-queries-ASN1.Spec.Value.INTEGER-25.smt2              | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.ComputeIsSorted.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-Impl-IndirectionTable.i.dfy.Impl__IndirectionTable.IndirectionTable.IndirectionTableToVal.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.NoOpStepPreservesGraphs.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-PivotBetree-PivotBetreeSpec.i.dfy.CheckWellformed__PivotBetreeSpec.__default.CutoffNodeAndKeepRight.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-Impl-LeafModel.i.dfy.Impl__LeafModel.__default.repivotLeafCorrect.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-Impl-NodeImpl.i.dfy.Impl__NodeImpl.Node.CutoffNodeAndKeepRight.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.AllocStepUpdatesGraph.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.DirtyStepUpdatesGraph.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.NoDiskOpStepPreservesInv.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-Impl-SplitModel.i.dfy.Impl__SplitModel.__default.doSplitCorrect.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_fvbkv-Impl-CoordinationImpl.i.dfy.Impl__CoordinationImpl.__default.insert.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-PivotBetree-PivotBetree.i.dfy.Impl__PivotBetree.__default.BetreeStepRefines.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.GrowStepPreservesInvariant.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-Betree-Betree_Refines_Map.i.dfy.Impl__Betree__Refines__Map.__default.RedirectRefinesMap.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|fs_vwasm-semantics-temp-queries-Views-10.smt2                | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.IMessagesSlice.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.CheckWellformed__ByteSystem.__default.DiskInternalStepPreservesInv.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-lib-Buckets-PackedKVMarshalling.i.dfy.Impl__PackedKVMarshalling.__default.SizeOfVPackedStringArrayIsMessageListWeight.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.FlushPreservesLookups.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_komodo-verified-sha-sha256-block-data-order.gen.dfyImpl___module.__default.va__refined__sha256__block__data__order_split0.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_fvbkv-lib-Math-mul.i.dfy.Impl__Math____mul__i.__default.lemma__mul__is__mul__recursive.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_fvbkv-lib-Base-sequences.i.dfy.Impl__Sequences.__default.lemma__concatSeqLen__le__mul.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.parseEntriesFromHasEntriesI.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-Impl-CommitterImpl.i.dfy.Impl__CommitterImpl.Committer.WriteOutJournal.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-BlockCacheSystem-BetreeJournalSystem.i.dfy.Impl__BetreeJournalSystem.__default.OkaySendPersistentLocStep.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_komodo-verified-sha-sha256-api.gen.dfyImpl___module.__default.va__abstract__sha256__one__shot.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_komodo-verified-memset.gen.dfyImpl___module.__default.va__lemma__memcpy__bare.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.InsertLeafIsCorrect.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.__default.PSAPopFrontWeightSuffix.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.CrashStepPreservesInv.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.BinarySearchIndexOfFirstKeyGte.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__svcHandled__loweq__pdb.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|fs_dice-queries-L0.Impl.Certificate-12.smt2                  | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-lib-Buckets-BucketsLib.i.dfy.Impl__BucketsLib.__default.WFProperSplitBucketListRight.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-lib-Base-Sequences.i.dfy.Impl__Sequences.__default.lemma__concatSeqLen__le__mul.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-Betree-Betree_Refines_Map.i.dfy.Impl__Betree__Refines__Map.__default.GrowStepRefinesMap.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.WeightMessageListFlatten.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_komodo-verified-memset.gen.dfyImpl___module.__default.va__lemma__memset.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_komodo-verified-entry.gen.dfyImpl___module.__default.va__lemma__unstack__banked__regs3.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_komodo-verified-sha-sha256-body-16-xx.gen.dfyImpl___module.__default.va__refined__Body__16__XX.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_komodo-verified-attest.gen.dfyImpl___module.__default.va__lemma__compute__hmac.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-lib-DataStructures-LinearDList.i.dfy.Impl__DList.DList.Remove.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_komodo-verified-attest_helpers.gen.dfyImpl___module.__default.va__lemma__zero__pad__memory.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-Betree-Betree_Refines_Map.i.dfy.Impl__Betree__Refines__Map.__default.FlushStepRefinesMap.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-PivotBetree-PivotBetreeSpecWFNodes.i.dfy.Impl__PivotBetreeSpecWFNodes.__default.SplitMaps.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_fvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.set__bit__to__0__other__uint64.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.RespReadStepPreservesInv.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.DynamicPkv.AppendPkv.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ReqWriteStepPreservesInv.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_komodo-verified-map_common.gen.dfyImpl___module.__default.va__lemma__init__secure__page.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-lib-Base-SetBijectivity.i.dfy.Impl__SetBijectivity.__default.CrossProductCardinality.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-Impl-LeafImpl.i.dfy.Impl__LeafImpl.__default.repivotLeafInternal.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-Impl-SuccModel.i.dfy.Impl__SuccModel.__default.lemmaGetPathResult.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-BlockCacheSystem-BetreeSystem.i.dfy.Impl__BetreeSystem.__default.BetreeMoveStepPreservesInv.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-Impl-FlushPolicyImpl.i.dfy.Impl__FlushPolicyImpl.__default.getActionToFlush.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-lib-Checksums-CRC32C_Lut.i.dfy.Impl__CRC32C__Lut.__default.shift1__pow.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.WFpsaSubSeq.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.RespWriteStepPreservesInv.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_komodo-verified-svc_handlers.gen.dfyImpl___module.__default.lemma__svc__returning__verify__step0__helper.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.BinarySearchIndexOfFirstKeyGt.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-ByteBlockCacheSystem-Marshalling.i.dfy.Impl__Marshalling.__default.pivotTableWeightUpperBound.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_komodo-verified-entry.i.dfyImpl___module.__default.lemma__userExecutionPreservesPrivState.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_fvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.set__bit__to__1__other__uint64.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.UnallocStepUpdatesGraph.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|fs_dice-queries-L0.X509.DeviceIDCRI.Subject-7.smt2           | 1000.000s | -1B| not-run | -1 |  |  |
|d_komodo-verified-map_common.gen.dfyImpl___module.__default.va__lemma__insecure__phys__to__virt.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-BlockCacheSystem-BetreeSystem_Refines_StatesViewPivotBetree.i.dfy.Impl__BetreeSystem__Refines__StatesViewPivotBetree.__default.BetreeMoveStepRefines.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-Impl-NodeImpl.i.dfy.Impl__NodeImpl.Node.BoundedBucket.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_komodo-verified-exception_handlers.gen.dfyImpl___module.__default.va__lemma__abort__handler.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.__default.MergeToChildrenIter.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ReqReadStepPreservesInv.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.__default.MergeToOneChild.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectPreservesLookups.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-lib-Buckets-BucketFlushModel.i.dfy.Impl__BucketFlushModel.__default.mergeToOneOneChild__eq__topBotAccMerge.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SplitChildOfIndex.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_komodo-verified-sha-sha256-body-00-15.gen.dfyImpl___module.__default.va__if__abstract__Body__00__15UnrolledRecursive.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.PageInIndirectionTableResp.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-lib-Buckets-LKMBPKVOps.i.dfy.Impl__LKMBPKVOps.__default.FromPkv.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-Betree-AsyncBetree_Refines_AsyncMap.i.dfy.Impl__AsyncBetree__Refines__AsyncMap.__default.RefinesNextStep.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.ComputeRefCounts.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_komodo-verified-init_addrspace.gen.dfyImpl___module.__default.va__lemma__kom__smc__init__addrspace.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-Impl-FlushModel.i.dfy.Impl__FlushModel.__default.flushCorrect.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-lib-Base-Multisets.i.dfy.Impl__Multisets.__default.ApplyAdditive.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_komodo-verified-sha-sha256-body-00-15.gen.dfyImpl___module.__default.va__abstract__Body__00__15.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.ISeqInduction.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_komodo-verified-allocate_page.gen.dfyImpl___module.__default.va__lemma__addrspace__incref.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-lib-Checksums-CRC32CImpl.i.dfy.Impl__CRC32__C__Impl.__default.compute__crc32__main.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.BinarySearchIndexOfFirstKeyGtePivot.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-Betree-Betree_Refines_Map.i.dfy.Impl__Betree__Refines__Map.__default.InsertMessageStepRefinesMap.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_komodo-verified-finalise.gen.dfyImpl___module.__default.va__lemma__kom__smc__finalise.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|fs_vwasm-compiler-common-queries-Compiler.Common.Dataflow-41.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.CheckWellformed__ByteSystem.__default.RespWriteStepPreservesInv.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_komodo-verified-svc_handlers.gen.dfyImpl___module.__default.va__lemma__get__cur__addrspace.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|fs_vwasm-compiler-sandbox-queries-Compiler.Sandbox-264.smt2  | 1000.000s | -1B| not-run | -1 |  |  |
|d_komodo-verified-attest_input.gen.dfyImpl___module.__default.va__lemma__arrange__user__regs__in__memory.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.WriteBackIndirectionTableRespStepPreservesGraphs.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-BlockCacheSystem-JournalRange.i.dfy.Impl__JournalRanges.__default.parseJournalRangeAdditive.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-PivotBetree-PivotBetreeSpecWFNodes.i.dfy.Impl__PivotBetreeSpecWFNodes.__default.BucketListWellMarshalledCutoffNodeAndKeepRight.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
