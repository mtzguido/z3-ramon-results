# .

* SAT 0
* UNSAT 223
* TIMEOUT 44
* UNKNOWN 1

* ERRORS 34 (not-run:34)

# Meta data

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


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|d_fvbkv-lib-Math-mul.i.dfy.Impl__Math____mul__i.__default.lemma__mul__one__to__one__pos.smt2 |    0.126s | 23.368MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__div__ind.smt2 |    0.142s | 22.996MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Math-mul.i.dfy.Impl__Math____mul__i.__default.lemma__mul__equality__converse.smt2 |    0.178s | 23.736MiB| unsat | 0 |  |  |
|d_lvbkv-BlockCacheSystem-DiskLayout.i.dfy.Impl__DiskLayout.__default.ValidNodeAddrMul.smt2 |    0.188s | 24.46MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Base-sequences.i.dfy.Impl__Sequences.__default.UnflattenFlattenIdentity.smt2 |    0.231s | 26.512MiB| unsat | 0 |  |  |
|d_fvbkv-lib-DataStructures-BitmapImpl.i.dfy.Impl__BitmapImpl.Bitmap.Unset.smt2 |    0.238s | 25.876MiB| unsat | 0 |  |  |
|d_fvbkv-lib-DataStructures-BitmapImpl.i.dfy.Impl__BitmapImpl.Bitmap.Set.smt2 |    0.269s | 25.996MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Base-total_order.i.dfy.Impl__Char__Order.__default.FlattenStrictlySorted.smt2 |    0.288s | 27.512MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Base-Sequences.i.dfy.Impl__Sequences.__default.UnflattenIndexIsCorrect.smt2 |    0.293s | 28.568MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Base-total_order.i.dfy.Impl__Uint32__Order.__default.FlattenStrictlySorted.smt2 |    0.302s | 27.328MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Base-total_order.i.dfy.Impl__Uint64__Order.__default.FlattenStrictlySorted.smt2 |    0.303s | 28.388MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Checksums-CRC32C_Lemmas.i.dfy.Impl__CRC32C__Lemmas.__default.advances__bytes__refl.smt2 |    0.335s | 32.312MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Marshalling-Util.i.dfy.Impl__Common____Util__i.__default.seqIntoArrayChar.smt2 |    0.345s | 32.976MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Checksums-CRC32CImpl.i.dfy.Impl__CRC32__C__Impl.__default.advanced__of__iterated__intrinsic.smt2 |    0.375s | 33.588MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Base-Sequences.i.dfy.CheckWellformed__Sequences.__default.RemoveOneValue.smt2 |    0.377s | 27.776MiB| unsat | 0 |  |  |
|d_lvbkv-BlockCacheSystem-JournalInterval.i.dfy.Impl__JournalIntervals.__default.Disk__Journal__Read2.smt2 |    0.389s | 32.016MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Base-total_order.i.dfy.Impl__Total__Order.__default.FlattenStrictlySorted.smt2 |    0.438s | 29.424MiB| unsat | 0 |  |  |
|d_lvbkv-MapSpec-TSJMap_Refines_ThreeStateVersionedMap.i.dfy.Impl__TSJMap__Refines__ThreeStateVersionedMap.__default.apply__eq__apply__uiops.smt2 |    0.452s | 31.664MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Base-sequences.i.dfy.Impl__Sequences.__default.FlattenAdditive.smt2 |    0.469s | 29.396MiB| unsat | 0 |  |  |
|d_lvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.InterpretationInheritance.smt2 |    0.472s | 30.752MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Checksums-CRC32CArrayImpl.i.dfy.Impl__CRC32__C__Array__Impl.__default.advanced__of__iterated__intrinsic.smt2 |    0.473s | 35.476MiB| unsat | 0 |  |  |
|d_komodo-verified-sha-sha256.i.dfyImpl___module.__default.lemma__ArrayOffsetConcatenation.smt2 |    0.485s | 31.756MiB| unsat | 0 |  |  |
|d_lvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.InterpretationDelegation.smt2 |    0.487s | 31.936MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Base-total_order.i.dfy.Impl__Total__Order.__default.strictlySortedInsert.smt2 |    0.503s | 28.672MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.CheckWellformed__GenericMarshalling.__default.parse__Val.smt2 |    0.504s | 29.296MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.PivotIndexes.smt2 |    0.528s | 31.34MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.lemma__parse__Val__view__ByteArray.smt2 |    0.533s | 30.956MiB| unsat | 0 |  |  |
|d_lvbkv-MapSpec-TSJMap_Refines_ThreeStateVersionedMap.i.dfy.Impl__TSJMap__Refines__ThreeStateVersionedMap.__default.RefinesMove3.smt2 |    0.536s | 35.24MiB| unsat | 0 |  |  |
|d_lvbkv-lib-DataStructures-KMBtree.i.dfy.Impl__KMBtreeModel.__default.InterpretationDelegation.smt2 |    0.539s | 32.228MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.PsaSuffix.smt2 |    0.547s | 31.328MiB| unsat | 0 |  |  |
|d_komodo-verified-sha-bit-vector-lemmas.i.dfyImpl___module.__default.lemma__Ch.smt2 |    0.558s | 32.008MiB| unsat | 0 |  |  |
|d_lvbkv-BlockCacheSystem-JournalInterval.i.dfy.Impl__JournalIntervals.__default.concatFoldAdditive.smt2 |    0.588s | 33.38MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.psaAppendSeqAdditive.smt2 |    0.590s | 34.768MiB| unsat | 0 |  |  |
|d_lvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.parsesFromStuff.smt2 |    0.600s | 34.192MiB| unsat | 0 |  |  |
|d_komodo-verified-sha-sha256.i.dfyImpl___module.__default.lemma__ConcatenateSeqs__Adds.smt2 |    0.602s | 34.872MiB| unsat | 0 |  |  |
|d_fvbkv-lib-DataStructures-MutableMapModel.i.dfy.CheckWellformed__MutableMapModel.__default.iterToNext.smt2 |    0.622s | 32.592MiB| unsat | 0 |  |  |
|d_komodo-verified-sha-bit-vector-lemmas.i.dfyImpl___module.__default.lemma__Maj.smt2 |    0.627s | 32.66MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.WeightSplitBucketInList.smt2 |    0.631s | 35.924MiB| unsat | 0 |  |  |
|d_komodo-verified-sha-sha256.i.dfyImpl___module.__default.lemma__Trace__stitching.smt2 |    0.658s | 52.416MiB| unsat | 0 |  |  |
|d_komodo-verified-ptebits.i.dfyImpl___module.__default.lemma__ARM__L2PTE_split0.smt2 |    0.671s | 46.604MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Base-total_order.i.dfy.Impl__Total__Order.__default.FlattenStrictlySorted.smt2 |    0.676s | 42.136MiB| unsat | 0 |  |  |
|d_lvbkv-Versions-CompositeView.i.dfy.Impl__CompositeView.__default.FreezePreservesInv.smt2 |    0.686s | 36.94MiB| unsat | 0 |  |  |
|d_fvbkv-lib-DataStructures-MutableMapModel.i.dfy.Impl__MutableMapModel.__default.MapFromStorageProperties.smt2 |    0.707s | 37.752MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.WeightMessageListFlatten.smt2 |    0.737s | 54.452MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Buckets-BucketsLib.i.dfy.Impl__BucketsLib.__default.WFSplitBucketInList.smt2 |    0.741s | 36.416MiB| unsat | 0 |  |  |
|d_lvbkv-Impl-JournalistImpl.i.dfy.Impl__JournalistImpl.Journalist.packageInMemoryJournal.smt2 |    0.745s | 37.872MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.psaTotalLengthBound.smt2 |    0.768s | 45.892MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.DynamicPsa.FromSeq.smt2 |    0.771s | 34.828MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.DefineIMessage.smt2 |    0.778s | 44.824MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.CheckWellformed__PackedKV.__default.LastKey.smt2 |    0.810s | 45.468MiB| unsat | 0 |  |  |
|d_komodo-verified-ptebits.i.dfyImpl___module.__default.lemma__l2indexFromMapping__shifts.smt2 |    0.824s | 48.388MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.WeightKeyListFlatten.smt2 |    0.844s | 54.0MiB| unsat | 0 |  |  |
|d_fvbkv-Versions-CompositeView_Refines_TSJMap.i.dfy.Impl__CompositeView__Refines__TSJMap.__default.CrashRefines.smt2 |    0.849s | 39.544MiB| unsat | 0 |  |  |
|d_lvbkv-PivotBetree-PivotBetreeSpecWFNodes.i.dfy.Impl__PivotBetreeSpecWFNodes.__default.WFApplyRepivot.smt2 |    0.852s | 51.528MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.psaTotalLengthBound.smt2 |    0.871s | 46.964MiB| unsat | 0 |  |  |
|d_lvbkv-Impl-JournalistImpl.i.dfy.Impl__JournalistImpl.Journalist.parseJournals.smt2 |    0.889s | 55.248MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Buckets-PackedKVMarshalling.i.dfy.Impl__PackedKVMarshalling.__default.ComputeWF.smt2 |    0.892s | 46.608MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Buckets-KMBPKVOps.i.dfy.Impl__KMBPKVOps.__default.IMessagesInverse.smt2 |    0.983s | 49.924MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Buckets-PackedStringArray.i.dfy.CheckWellformed__PackedStringArray.__default.psaAppendSeq.smt2 |    0.987s | 53.852MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.CheckWellformed__DynamicPkv.__default.PKVISeq.smt2 |    1.007s | 51.36MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.WMWeightBucketListFlush.smt2 |    1.011s | 55.22MiB| unsat | 0 |  |  |
|d_lvbkv-MapSpec-TSJMap_Refines_ThreeStateVersionedMap.i.dfy.Impl__TSJMap__Refines__ThreeStateVersionedMap.__default.RefinesStutter.smt2 |    1.013s | 38.872MiB| unsat | 0 |  |  |
|d_lvbkv-MapSpec-TSJ.i.dfy.Impl__TSJ.__default.ExtendLog2StepPreservesInv.smt2 |    1.018s | 40.316MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.CheckWellformed__DynamicPkv.__default.PKVISeq.smt2 |    1.019s | 51.276MiB| unsat | 0 |  |  |
|d_lvbkv-lib-DataStructures-KMBtree.i.dfy.Impl__KMBtreeModel.__default.InterpretationsDisjointUnion.smt2 |    1.047s | 54.504MiB| unsat | 0 |  |  |
|d_lvbkv-Versions-CompositeView.i.dfy.Impl__CompositeView.__default.AdvancePreservesInv.smt2 |    1.080s | 38.332MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Buckets-LKMBPKVOps.i.dfy.Impl__LKMBPKVOps.__default.IMessagesInverse.smt2 |    1.083s | 51.792MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.WeightKeySeqIs.smt2 |    1.091s | 50.732MiB| unsat | 0 |  |  |
|d_fvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.Impl__PivotBetreeSpecRefinement.__default.CutoffNodeAndKeepRightAgree.smt2 |    1.106s | 51.392MiB| unsat | 0 |  |  |
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.parseJournals.smt2 |    1.135s | 40.66MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.WeightSplitBucketInList.smt2 |    1.177s | 53.276MiB| unsat | 0 |  |  |
|d_komodo-verified-valedecls.gen.dfyImpl___module.__default.va__lemma__MSR.smt2 |    1.220s | 52.908MiB| unsat | 0 |  |  |
|d_komodo-verified-smcapi.i.dfyImpl___module.__default.lemma__ConcatenateSeqs__Adds_k.smt2 |    1.224s | 55.056MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.GetMiddleKey.smt2 |    1.245s | 54.332MiB| unsat | 0 |  |  |
|d_lvbkv-Impl-JournalistImpl.i.dfy.Impl__JournalistImpl.Journalist.freeze.smt2 |    1.247s | 40.416MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Buckets-BucketModel.i.dfy.Impl__BucketModel.__default.mergeToChildrenIterSlack_split0.smt2 |    1.259s | 52.404MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.SplitRight.smt2 |    1.270s | 54.66MiB| unsat | 0 |  |  |
|d_lvbkv-PivotBetree-TSJPivotBetree.i.dfy.Impl__TSJPivotBetree.__default.NextStepPreservesInv.smt2 |    1.340s | 96.252MiB| unsat | 0 |  |  |
|d_fvbkv-Versions-CompositeView_Refines_TSJMap.i.dfy.Impl__CompositeView__Refines__TSJMap.__default.JournalInternalRefines.smt2 |    1.341s | 57.344MiB| unsat | 0 |  |  |
|d_komodo-verified-entry.gen.dfyCheckWellformed___module.__default.va__lemma__stack__banked__regs1.smt2 |    1.350s | 94.232MiB| unsat | 0 |  |  |
|d_komodo-verified-entry.gen.dfyCheckWellformed___module.__default.va__lemma__switch__addrspace.smt2 |    1.400s | 95.008MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Buckets-PackedKVMarshalling.i.dfy.Impl__PackedKVMarshalling.__default.SizeOfVPackedStringArrayIsKeyListWeight.smt2 |    1.407s | 54.536MiB| unsat | 0 |  |  |
|d_lvbkv-Impl-NodeImpl.i.dfy.Impl__NodeImpl.Node.UpdateSlot.smt2 |    1.445s | 79.96MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Buckets-KMBPKVOps.i.dfy.Impl__KMBPKVOps.__default.canAppendMessagesIterate.smt2 |    1.445s | 55.804MiB| unsat | 0 |  |  |
|d_komodo-verified-secprop-sec_prop_util.i.dfyImpl___module.__default.lemma__maybeContents__insec__ni.smt2 |    1.509s | 96.712MiB| unsat | 0 |  |  |
|d_komodo-verified-secprop-integ_ni.i.dfyImpl___module.__default.lemma__enc__ni.smt2 |    1.550s | 94.624MiB| unsat | 0 |  |  |
|d_komodo-verified-entry.gen.dfyCheckWellformed___module.__default.va__lemma__pre__entry__resume.smt2 |    1.668s | 96.448MiB| unsat | 0 |  |  |
|d_komodo-verified-entry.i.dfyCheckWellformed___module.__default.lemma__evalMOVSPCLRUC__inner.smt2 |    1.736s | 99.836MiB| unsat | 0 |  |  |
|d_fvbkv-lib-DataStructures-MutableMapModel.i.dfy.Impl__MutableMapModel.__default.UpdatePreservesSimpleIter.smt2 |    1.749s | 40.392MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Buckets-LKMBPKVOps.i.dfy.Impl__LKMBPKVOps.__default.ToPkv.smt2 |    1.771s | 60.264MiB| unsat | 0 |  |  |
|d_komodo-verified-entry.i.dfyImpl___module.__default.lemma__userExecutionUpdatesPageDb_split0.smt2 |    1.787s | 98.0MiB| unsat | 0 |  |  |
|d_lvbkv-Versions-CompositeView_Refines_TSJMap.i.dfy.Impl__CompositeView__Refines__TSJMap.__default.JournalInternalRefines.smt2 |    1.802s | 56.288MiB| unsat | 0 |  |  |
|d_komodo-verified-ptables.i.dfyImpl___module.__default.lemma__memstatecontainspage.smt2 |    1.821s | 61.08MiB| unsat | 0 |  |  |
|d_komodo-verified-exception_handlers.gen.dfyCheckWellformed___module.__default.va__lemma__save__disp__context.smt2 |    1.849s | 104.0MiB| unsat | 0 |  |  |
|d_komodo-verified-smcapi.i.dfyImpl___module.__default.kom__smc__map__measure__helper2.smt2 |    1.870s | 62.752MiB| unsat | 0 |  |  |
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__data__page__eqdb__to__addrs.smt2 |    1.892s | 97.0MiB| unsat | 0 |  |  |
|d_komodo-verified-ptables.i.dfyImpl___module.__default.lemma__ptablesmatch_split11.smt2 |    1.897s | 59.68MiB| unsat | 0 |  |  |
|d_komodo-verified-sha-hmac.gen.dfyCheckWellformed___module.__default.va__lemma__hmac__inner.smt2 |    1.972s | 98.968MiB| unsat | 0 |  |  |
|d_lvbkv-BlockCacheSystem-BlockCache.i.dfy.Impl__BlockCache.__default.AllocStepPreservesInv.smt2 |    2.010s | 59.284MiB| unsat | 0 |  |  |
|d_fvbkv-lib-DataStructures-KMBtree.i.dfy.Impl__KMBtree.__default.InsertIndexSelectAndPrepareChild.smt2 |    2.031s | 57.616MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Marshalling-Util.i.dfy.CheckWellformed__Common____Util__i.__default.Uint64ToSeqByte.smt2 |    2.038s | 31.0MiB| unsat | 0 |  |  |
|d_lvbkv-lib-DataStructures-KMBtree.i.dfy.Impl__LKMBtree.__default.InsertLeaf.smt2 |    2.155s | 56.96MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.__default.PartialFlush.smt2 |    2.178s | 96.676MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Buckets-LKMBPKVOps.i.dfy.Impl__LKMBPKVOps.__default.canAppendKeysIterate.smt2 |    2.216s | 99.112MiB| unsat | 0 |  |  |
|d_fvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.InsertLeafIsCorrect.smt2 |    2.379s | 53.844MiB| unsat | 0 |  |  |
|d_lvbkv-PivotBetree-PivotBetree.i.dfy.Impl__PivotBetree.__default.StutterStepRefines.smt2 |    2.398s | 63.556MiB| unsat | 0 |  |  |
|d_komodo-verified-init_l2ptable.gen.dfyCheckWellformed___module.__default.va__lemma__init__l2ptable__success.smt2 |    2.401s | 98.656MiB| unsat | 0 |  |  |
|d_komodo-verified-psrbits.i.dfyImpl___module.__default.lemma__update__psr__f.smt2 |    2.410s | 59.672MiB| unsat | 0 |  |  |
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.bucketToVal.smt2 |    2.422s | 100.0MiB| unsat | 0 |  |  |
|d_fvbkv-lib-DataStructures-KMBtree.i.dfy.Impl__KMBtreeModel.__default.InterpretationsDisjointUnion.smt2 |    2.430s | 57.328MiB| unsat | 0 |  |  |
|d_komodo-verified-attest.gen.dfyCheckWellformed___module.__default.va__lemma__svc__returning__attest__inner.smt2 |    2.435s | 102.0MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Buckets-BucketImpl.i.dfy.Impl__BucketImpl.MutBucket.SplitOneInList.smt2 |    2.463s | 99.344MiB| unsat | 0 |  |  |
|d_komodo-verified-entry.i.dfyImpl___module.__default.lemma__partialEnclaveExecution__append.smt2 |    2.469s | 99.416MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Buckets-BucketWeights.i.dfy.Impl__BucketWeights.__default.WeightBucketListItemFlushSingletonOrEmpty.smt2 |    2.488s | 58.124MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Buckets-LKMBPKVOps.i.dfy.Impl__LKMBPKVOps.__default.canAppendMessagesIterate.smt2 |    2.513s | 96.592MiB| unsat | 0 |  |  |
|d_lvbkv-BlockCacheSystem-BetreeSystem_Refines_StatesViewPivotBetree.i.dfy.Impl__BetreeSystem__Refines__StatesViewPivotBetree.__default.CrashStepRefines.smt2 |    2.524s | 89.46MiB| unsat | 0 |  |  |
|d_komodo-verified-svc_handlers.gen.dfyCheckWellformed___module.__default.va__lemma__svc__unmap__data.smt2 |    2.599s | 104.0MiB| unsat | 0 |  |  |
|d_komodo-verified-entry.i.dfyImpl___module.__default.lemma__partialEnclaveExecution__done.smt2 |    2.613s | 97.0MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Base-total_order.i.dfy.Impl__Total__Order.__default.strictlySortedInsert.smt2 |    2.649s | 70.424MiB| unsat | 0 |  |  |
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.Impl__IndirectionTableModel.__default.LemmaComputeRefCountsEntryIterateCorrectPartial.smt2 |    2.706s | 99.7MiB| unsat | 0 |  |  |
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectResultingGraphAfterAllocs.smt2 |    2.822s | 54.088MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Base-Multisets.i.dfy.Impl__Multisets.__default.FoldAdditive.smt2 |    2.906s | 59.48MiB| unsat | 0 |  |  |
|d_komodo-verified-smcapi.i.dfyCheckWellformed___module.__default.kom__smc__map__measure__helper2.smt2 |    3.033s | 98.0MiB| unsat | 0 |  |  |
|d_komodo-verified-allocate_page.gen.dfyCheckWellformed___module.__default.va__lemma__addrspace__incref.smt2 |    3.126s | 95.26MiB| unsat | 0 |  |  |
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenFromBucketStackWithLowerBound.smt2 |    3.145s | 96.512MiB| unsat | 0 |  |  |
|d_fvbkv-BlockCacheSystem-BetreeCache.i.dfy.Impl__BetreeCache.__default.BetreeMoveStepPreservesInv.smt2 |    3.183s | 95.216MiB| unsat | 0 |  |  |
|d_komodo-verified-memset.gen.dfyImpl___module.__default.va__lemma__memcpy.smt2 |    3.183s | 62.484MiB| unsat | 0 |  |  |
|d_lvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.NextStepPreservesInv.smt2 |    3.184s | 109.0MiB| unsat | 0 |  |  |
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__TestBtreeModel.__default.SplitIndexInterpretation1.smt2 |    3.257s | 58.56MiB| unsat | 0 |  |  |
|d_fvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.SplitIndexInterpretation2.smt2 |    3.259s | 57.976MiB| unsat | 0 |  |  |
|d_fvbkv-PivotBetree-PivotBetreeSpecWFNodes.i.dfy.Impl__PivotBetreeSpecWFNodes.__default.ValidMergeWritesInvNodes.smt2 |    3.271s | 64.26MiB| unsat | 0 |  |  |
|d_fvbkv-Impl-QueryModel.i.dfy.Impl__QueryModel.__default.AugmentLookup.smt2 |    3.285s | 98.0MiB| unsat | 0 |  |  |
|d_lvbkv-BlockCacheSystem-BetreeJournalSystem_Refines_ThreeStateVersionedMap.i.dfy.Impl__BetreeJournalSystem__Refines__ThreeStateVersionedMap.__default.RefinesNext.smt2 |    3.305s | 218.0MiB| unsat | 0 |  |  |
|d_komodo-verified-init_l2ptable.gen.dfyImpl___module.__default.lemma__SecurePage.smt2 |    3.331s | 99.62MiB| unsat | 0 |  |  |
|d_fvbkv-PivotBetree-PivotBetree.i.dfy.Impl__PivotBetree.__default.BetreeStepRefines.smt2 |    3.360s | 94.852MiB| unsat | 0 |  |  |
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.InsertIndexSelectAndPrepareChild.smt2 |    3.409s | 57.932MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Base-Multisets.i.dfy.Impl__Multisets.__default.ApplySeq.smt2 |    3.570s | 69.152MiB| unsat | 0 |  |  |
|d_fvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.SplitChildOfIndexPreservesInterpretationB.smt2 |    3.614s | 66.488MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.__default.MergeToChildren.smt2 |    3.726s | 100.0MiB| unsat | 0 |  |  |
|d_komodo-verified-secprop-conf_ni.i.dfyImpl___module.__default.lemma__conf__ni.smt2 |    3.751s | 101.0MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Buckets-BucketsLib.i.dfy.Impl__BucketsLib.__default.WFProperMergeBucketsInList.smt2 |    3.849s | 94.028MiB| unsat | 0 |  |  |
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.fillInChecksumsPreserves.smt2 |    3.908s | 68.432MiB| unsat | 0 |  |  |
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.CheckWellformed__IndirectionTableModel.__default.RemoveRef.smt2 |    3.933s | 97.0MiB| unsat | 0 |  |  |
|d_komodo-verified-svc_handlers.gen.dfyCheckWellformed___module.__default.lemma__svc__returning__verify__step0__helper.smt2 |    3.954s | 105.0MiB| unsat | 0 |  |  |
|d_komodo-verified-secprop-integ_ni_entry.i.dfyImpl___module.__default.lemma__enter__enc__ni.smt2 |    3.972s | 103.0MiB| unsat | 0 |  |  |
|d_fvbkv-lib-DataStructures-MutableMapModel.i.dfy.CheckWellformed__MutableMapModel.__default.IterInc.smt2 |    4.079s | 45.92MiB| unsat | 0 |  |  |
|d_lvbkv-Impl-CommitterImpl.i.dfy.Impl__CommitterImpl.Committer.FinishLoadingOtherPhase.smt2 |    4.365s | 167.0MiB| unsat | 0 |  |  |
|d_fvbkv-lib-DataStructures-KMBtree.i.dfy.Impl__KMBtreeModel.__default.SplitIndexInterpretation1.smt2 |    4.442s | 58.096MiB| unsat | 0 |  |  |
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__data__eqpdb__to__addrs.smt2 |    4.681s | 98.0MiB| unsat | 0 |  |  |
|d_komodo-verified-entry.gen.dfyCheckWellformed___module.__default.va__lemma__stack__banked__regs3.smt2 |    4.684s | 94.392MiB| unsat | 0 |  |  |
|d_komodo-verified-entry.i.dfyImpl___module.__default.lemma__validEnclaveExecutionStep__PageDb.smt2 |    4.725s | 133.0MiB| unsat | 0 |  |  |
|d_komodo-verified-map_secure.gen.dfyImpl___module.__default.lemma__preserve__contentsOfPhysPage.smt2 |    4.728s | 115.0MiB| unsat | 0 |  |  |
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.WriteBackIndirectionTableReqStepPreservesInv.smt2 |    4.804s | 108.0MiB| unsat | 0 |  |  |
|d_komodo-verified-sha-hmac.gen.dfyImpl___module.__default.va__lemma__hmac__inner__prep__input.smt2 |    4.911s | 132.0MiB| unsat | 0 |  |  |
|d_komodo-verified-entry.gen.dfyCheckWellformed___module.__default.va__lemma__stack__banked__regs2.smt2 |    5.026s | 93.948MiB| unsat | 0 |  |  |
|d_fvbkv-Impl-EvictImpl.i.dfy.Impl__EvictImpl.__default.Evict.smt2 |    5.220s | 169.0MiB| unsat | 0 |  |  |
|d_komodo-verified-exception_handlers.gen.dfyCheckWellformed___module.__default.va__lemma__CPSID__IAF.smt2 |    5.282s | 107.0MiB| unsat | 0 |  |  |
|d_komodo-verified-entry.i.dfyImpl___module.__default.lemma__userExecutionPreservesStack.smt2 |    5.397s | 111.0MiB| unsat | 0 |  |  |
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.bucketsToVal.smt2 |    5.409s | 171.0MiB| unsat | 0 |  |  |
|d_komodo-verified-entry.gen.dfyCheckWellformed___module.__default.va__lemma__unstack__banked__regs3.smt2 |    5.704s | 138.0MiB| unsat | 0 |  |  |
|d_komodo-verified-secprop-conf_ni.i.dfyImpl___module.__default.lemma__initAddrspace__loweq__pdb.smt2 |    5.733s | 108.0MiB| unsat | 0 |  |  |
|d_komodo-verified-map_insecure.gen.dfyImpl___module.__default.va__lemma__mkl2pte__insecure.smt2 |    5.737s | 126.0MiB| unsat | 0 |  |  |
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__userStatesEquiv__atkr.smt2 |    5.835s | 118.0MiB| unsat | 0 |  |  |
|d_komodo-verified-verify_input.gen.dfyImpl___module.__default.va__lemma__arrange__verification__input.smt2 |    5.936s | 129.0MiB| unsat | 0 |  |  |
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.InitLocBitmap.smt2 |    6.091s | 106.0MiB| unsat | 0 |  |  |
|d_komodo-verified-verify.gen.dfyCheckWellformed___module.__default.va__lemma__svc__returning__verify__inner.smt2 |    6.472s | 159.0MiB| unsat | 0 |  |  |
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.InsertIndexChildNotFull.smt2 |    6.644s | 98.284MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Checksums-F2_X_Lemmas.i.dfy.Impl__F2__X__Lemmas.__default.pq__r__partial.smt2 |    6.745s | 112.0MiB| unknown | 0 |  |  |
|d_komodo-verified-memset.gen.dfyCheckWellformed___module.__default.va__lemma__memcpy__bare.smt2 |    6.783s | 86.988MiB| unsat | 0 |  |  |
|d_komodo-verified-pagedb.i.dfyImpl___module.__default.AllButOnePagePreserving.smt2 |    6.820s | 115.0MiB| unsat | 0 |  |  |
|d_lvbkv-lib-DataStructures-KMBtree.i.dfy.Impl__KMBtreeModel.__default.InterpretationInheritance.smt2 |    6.977s | 99.0MiB| unsat | 0 |  |  |
|d_komodo-verified-smcapi.i.dfyImpl___module.__default.AllButOnePageOrStackPreserving.smt2 |    7.091s | 107.0MiB| unsat | 0 |  |  |
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ProcessWritePreservesInv.smt2 |    7.116s | 172.0MiB| unsat | 0 |  |  |
|d_komodo-verified-attest.gen.dfyCheckWellformed___module.__default.va__lemma__compute__hmac.smt2 |    7.141s | 112.0MiB| unsat | 0 |  |  |
|s_komodo-1435.3.smt2                                         |    7.151s | 183.0MiB| unsat | 0 |  |  |
|d_komodo-verified-memset.gen.dfyCheckWellformed___module.__default.va__lemma__memcpy.smt2 |    7.281s | 112.0MiB| unsat | 0 |  |  |
|d_lvbkv-Impl-InsertImpl.i.dfy.Impl__InsertImpl.__default.insert.smt2 |    7.512s | 171.0MiB| unsat | 0 |  |  |
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.ValToBuckets.smt2 |    7.518s | 168.0MiB| unsat | 0 |  |  |
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__userMemEquiv__atkr.smt2 |    7.542s | 122.0MiB| unsat | 0 |  |  |
|d_komodo-verified-ptables.i.dfyImpl___module.__default.lemma__OnlyPTPagesInHwPTable.smt2 |    7.567s | 112.0MiB| unsat | 0 |  |  |
|d_lvbkv-Betree-AsyncBetree_Refines_AsyncMap.i.dfy.Impl__AsyncBetree__Refines__AsyncMap.__default.RefinesQueryEndStep.smt2 |    7.622s | 107.0MiB| unsat | 0 |  |  |
|d_komodo-verified-svc_handlers.gen.dfyImpl___module.__default.lemma__svc__returning__WordAlignedStack.smt2 |    7.737s | 130.0MiB| unsat | 0 |  |  |
|d_komodo-verified-smcapi.i.dfyImpl___module.__default.initDispatcherPreservesPageDBValidity.smt2 |    7.752s | 111.0MiB| unsat | 0 |  |  |
|d_lvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.Impl__PivotBetreeSpecRefinement.__default.SplitRouteNewChild.smt2 |    7.801s | 163.0MiB| unsat | 0 |  |  |
|d_komodo-verified-allocate_page.gen.dfyCheckWellformed___module.__default.va__lemma__allocate__page__success.smt2 |    8.043s | 97.0MiB| unsat | 0 |  |  |
|d_komodo-verified-smcapi.i.dfyImpl___module.__default.lemma__validEnclaveExecutionStep__validPageDb.smt2 |    8.048s | 120.0MiB| unsat | 0 |  |  |
|d_lvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.Impl__PivotBetreeSpecRefinement.__default.RefinesLookup.smt2 |    8.065s | 108.0MiB| unsat | 0 |  |  |
|d_lvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.nodeToVal.smt2 |    8.302s | 178.0MiB| unsat | 0 |  |  |
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesReqWriteOp.smt2 |    8.310s | 174.0MiB| unsat | 0 |  |  |
|d_komodo-verified-sha-sha256-api.gen.dfyImpl___module.__default.va__abstract__sha256__init.smt2 |    8.571s | 104.0MiB| unsat | 0 |  |  |
|d_fvbkv-Impl-CommitterInitImpl.i.dfy.Impl__CommitterInitImpl.__default.FinishLoadingOtherPhase.smt2 |    8.596s | 169.0MiB| unsat | 0 |  |  |
|d_komodo-verified-map_common.gen.dfyCheckWellformed___module.__default.lemma__update__l2pte__helper1.smt2 |    8.716s | 153.0MiB| unsat | 0 |  |  |
|d_komodo-verified-init_l2ptable.gen.dfyCheckWellformed___module.__default.va__lemma__zero__l2__page.smt2 |    8.830s | 156.0MiB| unsat | 0 |  |  |
|d_komodo-verified-map_common.gen.dfyImpl___module.__default.va__lemma__mkL2Pte__secure.smt2 |    8.979s | 115.0MiB| unsat | 0 |  |  |
|d_fvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.nodeToVal.smt2 |    9.434s | 176.0MiB| unsat | 0 |  |  |
|d_fvbkv-BlockCacheSystem-BetreeSystem_Refines_StatesViewPivotBetree.i.dfy.Impl__BetreeSystem__Refines__StatesViewPivotBetree.__default.BetreeMoveStepRefines.smt2 |    9.666s | 116.0MiB| unsat | 0 |  |  |
|d_lvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.Impl__PivotBetreeSpecRefinement.__default.RefinesValidFlush.smt2 |    9.674s | 173.0MiB| unsat | 0 |  |  |
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.writeNodeResponse.smt2 |   10.065s | 171.0MiB| unsat | 0 |  |  |
|d_komodo-verified-exception_handlers.gen.dfyImpl___module.__default.va__lemma__switch__to__monitor.smt2 |   10.125s | 120.0MiB| unsat | 0 |  |  |
|d_lvbkv-Betree-Betree_Refines_Map.i.dfy.Impl__Betree__Refines__Map.__default.SuccQueryStepRefinesMap.smt2 |   10.130s | 102.0MiB| unsat | 0 |  |  |
|d_fvbkv-Impl-JournalistMarshallingModel.i.dfy.Impl__JournalistMarshallingModel.__default.writeOntoResult.smt2 |   10.301s | 176.0MiB| unsat | 0 |  |  |
|d_komodo-verified-finalise.gen.dfyCheckWellformed___module.__default.lemma__kom__smc__finalise__success__helper1.smt2 |   10.347s | 135.0MiB| unsat | 0 |  |  |
|d_lvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.RedirectPreservesRootHasNoPred.smt2 |   10.575s | 175.0MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Buckets-KMBPKVOps.i.dfy.Impl__KMBPKVOps.__default.ToPkv.smt2 |   10.629s | 117.0MiB| unsat | 0 |  |  |
|d_komodo-verified-attest_input.gen.dfyImpl___module.__default.va__lemma__arrange__attestation__input.smt2 |   11.149s | 198.0MiB| unsat | 0 |  |  |
|d_lvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.writeNodeResponse.smt2 |   11.217s | 171.0MiB| unsat | 0 |  |  |
|d_komodo-verified-exhandler_state.i.dfyCheckWellformed___module.__default.lemma__SVCFIQNestedExceptionIsCorrect.smt2 |   11.337s | 188.0MiB| unsat | 0 |  |  |
|d_lvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.InsertMessagePreservesLookupsPut.smt2 |   11.429s | 113.0MiB| unsat | 0 |  |  |
|d_lvbkv-Impl-BookkeepingModel.i.dfy.Impl__BookkeepingModel.__default.writeCorrect.smt2 |   11.519s | 172.0MiB| unsat | 0 |  |  |
|d_komodo-verified-entry.gen.dfyImpl___module.__default.lemma__stackunstack__banked__regs.smt2 |   11.545s | 113.0MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Buckets-LKMBPKVOps.i.dfy.Impl__LKMBPKVOps.__default.LeafFillDpkv.smt2 |   11.589s | 124.0MiB| unsat | 0 |  |  |
|d_lvbkv-lib-DataStructures-LinearContentMutableMap.i.dfy.Impl__LinearContentMutableMap.__default.Probe.smt2 |   11.672s | 76.508MiB| unsat | 0 |  |  |
|d_fvbkv-Impl-SplitImpl.i.dfy.Impl__SplitImpl.__default.splitBookkeeping.smt2 |   11.888s | 174.0MiB| unsat | 0 |  |  |
|d_komodo-verified-init_l2ptable.gen.dfyImpl___module.__default.va__lemma__init__l2ptable__success_split0.smt2 |   12.000s | 120.0MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Base-Multisets.i.dfy.Impl__Multisets.__default.FoldAdditive.smt2 |   12.180s | 143.0MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Checksums-F2_X_Lemmas.i.dfy.Impl__F2__X__Lemmas.__default.p__qr__partial.smt2 |   12.869s | 200.0MiB| unsat | 0 |  |  |
|d_komodo-verified-svc_handlers.gen.dfyCheckWellformed___module.__default.va__lemma__svc__returning__verify__step0.smt2 |   13.003s | 186.0MiB| unsat | 0 |  |  |
|d_lvbkv-ByteBlockCacheSystem-ByteSystem_Refines_BetreeJournalSystem.i.dfy.Impl__ByteSystem__Refines__BetreeJournalSystem.__default.RefinesNext.smt2 |   13.117s | 402.0MiB| unsat | 0 |  |  |
|d_komodo-verified-map_common.gen.dfyImpl___module.__default.lemma__update__l2pte__helper1.smt2 |   13.286s | 131.0MiB| unsat | 0 |  |  |
|d_komodo-verified-svc_handlers.gen.dfyImpl___module.__default.va__lemma__monvaddr__page__impl.smt2 |   13.884s | 120.0MiB| unsat | 0 |  |  |
|d_lvbkv-lib-DataStructures-MutableMapModel.i.dfy.Impl__MutableMapModel.__default.IndexSetMatchesContents.smt2 |   16.590s | 110.0MiB| unsat | 0 |  |  |
|d_komodo-verified-sha-sha256-api.gen.dfyImpl___module.__default.va__refined__sha256__finalize.smt2 |   17.785s | 204.0MiB| unsat | 0 |  |  |
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__TestMutableBtree.__default.SplitIndex.smt2 |   18.480s | 117.0MiB| unsat | 0 |  |  |
|d_komodo-verified-exhandler_state.i.dfyImpl___module.__default.lemma__KomUserEntryPrecond__Preserved.smt2 |   18.606s | 187.0MiB| unsat | 0 |  |  |
|s_komodo-1551.3.smt2                                         |   20.024s | 123.0MiB| timeout | 0 |  |  |
|d_fvbkv-Impl-BucketGeneratorImpl.i.dfy.Impl__BucketGeneratorImpl.Generator.GenCompose.smt2 |   20.025s | 171.0MiB| timeout | 0 |  |  |
|d_komodo-verified-svc_handlers.gen.dfyCheckWellformed___module.__default.va__lemma__svc__map__data__success.smt2 |   20.026s | 188.0MiB| timeout | 0 |  |  |
|d_komodo-verified-svc_handlers.gen.dfyImpl___module.__default.va__lemma__rng__read.smt2 |   20.030s | 224.0MiB| timeout | 0 |  |  |
|d_komodo-verified-kom_utils.gen.dfyImpl___module.__default.va__abstract__load__32__bit__const.smt2 |   20.036s | 76.912MiB| timeout | 0 |  |  |
|d_lvbkv-Betree-Betree_Refines_Map.i.dfy.Impl__Betree__Refines__Map.__default.RefinesNextStep.smt2 |   20.037s | 126.0MiB| timeout | 0 |  |  |
|d_komodo-verified-secprop-conf_ni_entry.i.dfyCheckWellformed___module.__default.lemma__svcHandled__conf__not__atkr.smt2 |   20.043s | 120.0MiB| timeout | 0 |  |  |
|d_fvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.SplitIndexInterpretation1.smt2 |   20.043s | 109.0MiB| timeout | 0 |  |  |
|d_lvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.FlushStepPreservesInvariant.smt2 |   20.043s | 113.0MiB| timeout | 0 |  |  |
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SplitIndex.smt2 |   20.043s | 122.0MiB| timeout | 0 |  |  |
|d_lvbkv-lib-DataStructures-LinearContentMutableMap.i.dfy.Impl__LinearContentMutableMap.__default.FixedSizeInsertEntry.smt2 |   20.043s | 110.0MiB| timeout | 0 |  |  |
|d_fvbkv-lib-DataStructures-KMBtree.i.dfy.Impl__KMBtree.__default.SplitIndex.smt2 |   20.043s | 115.0MiB| timeout | 0 |  |  |
|d_komodo-verified-map_insecure.gen.dfyImpl___module.__default.va__lemma__phys__page__is__insecure__ram.smt2 |   20.044s | 186.0MiB| timeout | 0 |  |  |
|d_lvbkv-lib-DataStructures-LinearMutableMap.i.dfy.Impl__LinearMutableMap.__default.UpdateByIter.smt2 |   20.045s | 109.0MiB| timeout | 0 |  |  |
|d_komodo-verified-entry.gen.dfyImpl___module.__default.va__lemma__unstack__banked__regs_split0.smt2 |   20.045s | 188.0MiB| timeout | 0 |  |  |
|d_komodo-verified-secprop-conf_ni_entry.i.dfyImpl___module.__default.lemma__svcHandled__conf__not__atkr.smt2 |   20.047s | 177.0MiB| timeout | 0 |  |  |
|d_komodo-verified-exception_handlers.gen.dfyImpl___module.__default.va__lemma__CPSID__IAF.smt2 |   20.047s | 206.0MiB| timeout | 0 |  |  |
|d_komodo-verified-entry.gen.dfyImpl___module.__default.va__lemma__unstack__banked__regs1.smt2 |   20.049s | 185.0MiB| timeout | 0 |  |  |
|d_komodo-verified-alloc_spare.gen.dfyImpl___module.__default.va__lemma__kom__smc__alloc__spare.smt2 |   20.049s | 186.0MiB| timeout | 0 |  |  |
|d_fvbkv-Impl-IndirectionTableImpl.i.dfy.Impl__IndirectionTableImpl.IndirectionTable.ValToIndirectionTable.smt2 |   20.051s | 183.0MiB| timeout | 0 |  |  |
|d_komodo-verified-sha-hmac.gen.dfyImpl___module.__default.va__lemma__hmac__outer.smt2 |   20.053s | 229.0MiB| timeout | 0 |  |  |
|d_komodo-verified-sha-sha256-block-data-order.gen.dfyImpl___module.__default.va__abstract__sha256__block__data__order__inner.smt2 |   20.053s | 206.0MiB| timeout | 0 |  |  |
|d_komodo-verified-exhandler_state.i.dfyImpl___module.__default.lemma__PrivModeExceptionHandlersAreCorrect.smt2 |   20.053s | 189.0MiB| timeout | 0 |  |  |
|d_komodo-verified-smcapi.i.dfyImpl___module.__default.mapSecurePreservesPageDBValidity.smt2 |   20.053s | 182.0MiB| timeout | 0 |  |  |
|d_lvbkv-Impl-CoordinationImpl.i.dfy.Impl__CoordinationImpl.__default.succ.smt2 |   20.053s | 223.0MiB| timeout | 0 |  |  |
|d_komodo-verified-attest_helpers.gen.dfyImpl___module.__default.va__lemma__unstack__all__regs.smt2 |   20.053s | 238.0MiB| timeout | 0 |  |  |
|d_komodo-verified-attest_helpers.gen.dfyCheckWellformed___module.__default.va__lemma__load__attestion__key__inner.smt2 |   20.055s | 211.0MiB| timeout | 0 |  |  |
|d_lvbkv-Impl-BookkeepingModel.i.dfy.Impl__BookkeepingModel.__default.allocCorrect.smt2 |   20.055s | 198.0MiB| timeout | 0 |  |  |
|d_lvbkv-Impl-SyncImpl.i.dfy.Impl__SyncImpl.__default.TryToWriteBlock.smt2 |   20.056s | 216.0MiB| timeout | 0 |  |  |
|d_komodo-verified-sha-sha256-api.gen.dfyImpl___module.__default.va__refined__sha256__one__shot.smt2 |   20.056s | 205.0MiB| timeout | 0 |  |  |
|d_fvbkv-Impl-HandleReadResponseImpl.i.dfy.Impl__HandleReadResponseImpl.__default.readResponse.smt2 |   20.056s | 180.0MiB| timeout | 0 |  |  |
|d_komodo-verified-entry.gen.dfyImpl___module.__default.va__lemma__stack__banked__regs2.smt2 |   20.057s | 186.0MiB| timeout | 0 |  |  |
|d_lvbkv-Impl-SyncImpl.i.dfy.Impl__SyncImpl.__default.sync.smt2 |   20.059s | 204.0MiB| timeout | 0 |  |  |
|d_komodo-verified-entry.gen.dfyImpl___module.__default.va__lemma__enclaveexecution__loop.smt2 |   20.062s | 181.0MiB| timeout | 0 |  |  |
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.AllocStepPreservesInv.smt2 |   20.065s | 190.0MiB| timeout | 0 |  |  |
|d_komodo-verified-secprop-conf_ni.i.dfyImpl___module.__default.lemma__mapSecure__loweq__pdb__success.smt2 |   20.065s | 196.0MiB| timeout | 0 |  |  |
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.WriteBackNodeRespStepPreservesGraphs.smt2 |   20.080s | 222.0MiB| timeout | 0 |  |  |
|s_komodo-1450.0.smt2                                         |   20.319s | 2811.0MiB| timeout | 0 |  |  |
|s_komodo-1499.4.smt2                                         |   20.471s | 3686.0MiB| timeout | 0 |  |  |
|s_komodo-1504.6.smt2                                         |   20.569s | 5937.0MiB| timeout | 0 |  |  |
|s_komodo-1499.6.smt2                                         |   20.600s | 5968.0MiB| timeout | 0 |  |  |
|s_komodo-1509.6.smt2                                         |   20.667s | 6162.0MiB| timeout | 0 |  |  |
|s_komodo-1493.6.smt2                                         |   20.733s | 6399.0MiB| timeout | 0 |  |  |
|s_komodo-1488.6.smt2                                         |   20.754s | 6369.0MiB| timeout | 0 |  |  |
|d_lvbkv-Impl-FlushImpl.i.dfy.Impl__FlushImpl.__default.doFlush.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-ByteBlockCacheSystem-JournalBytes.i.dfy.Impl__JournalBytes.__default.JournalBlockOfJournalRange.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.CleanUpStepPreservesGraphs.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-lib-Base-Sequences.i.dfy.Impl__Sequences.__default.UnflattenFlattenIdentity.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|fs_dice-queries-X509.ExtFields.ExtendedKeyUsage-25.smt2      | 1000.000s | -1B| not-run | -1 |  |  |
|fs_dice-queries-L0.X509.AliasKeyTBS.Subject-12.smt2          | 1000.000s | -1B| not-run | -1 |  |  |
|fs_dice-queries-L0.X509.DeviceIDCRI.Subject-12.smt2          | 1000.000s | -1B| not-run | -1 |  |  |
|d_fvbkv-Impl-JournalistImpl.i.dfy.Impl__JournalistImpl.Journalist.packageFrozenJournal.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|fs_dice-queries-ASN1.Low.TLV-1.smt2                          | 1000.000s | -1B| not-run | -1 |  |  |
|fs_dice-queries-L0.X509.DeviceIDCRI.Subject-10.smt2          | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.InterpretationsDisjointUnion.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-Impl-IndirectionTable.i.dfy.Impl__IndirectionTable.IndirectionTable.UpdatePredCounts.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|fs_dice-queries-ASN1.Low.Value.BIT_STRING-1.smt2             | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.DirtyStepPreservesInv.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_fvbkv-Impl-IndirectionTableModel.i.dfy.Impl__IndirectionTableModel.__default.InitLocBitmapIterateCorrect.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|fs_dice-queries-X509.ExtFields.BasicConstraints-26.smt2      | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-Impl-IndirectionTable.i.dfy.Impl__IndirectionTable.IndirectionTable.UpdateAndRemoveLoc.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__power2__adds.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|fs_dice-queries-L0.X509.AliasKeyTBS.Subject-10.smt2          | 1000.000s | -1B| not-run | -1 |  |  |
|fs_dice-queries-ASN1.Low.Value.StringCombinator-2.smt2       | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-Impl-GrowImpl.i.dfy.Impl__GrowImpl.__default.doGrow.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_komodo-verified-exhandler_state.i.dfyImpl___module.__default.lemma__evalHandler.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|fs_dice-queries-X509.ExtFields.KeyUsage-18.smt2              | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.WriteBackIndirectionTableReqStepPreservesGraphs.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|fs_dice-queries-L0.X509.AliasKeyTBS.Issuer-12.smt2           | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.PageInNodeRespStepPreservesGraphs.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|fs_dice-queries-L0.X509.AliasKeyTBS.Issuer-10.smt2           | 1000.000s | -1B| not-run | -1 |  |  |
|d_komodo-verified-bitvectors_primitive.i.dfyImpl___module.__default.lemma__ShiftsLeftSum.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|fs_dice-queries-ASN1.Spec.Value.Envelop-20.smt2              | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.GrowPreservesInterpretation.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.SplitLeafInterpretation.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.PageInNodeReqStepPreservesGraphs.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_lvbkv-BlockCacheSystem-BlockSystem.i.dfy.Impl__BlockSystem.__default.EvictStepPreservesGraphs.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
|d_fvbkv-MapSpec-TSJ.i.dfy.Impl__TSJ.__default.Move2to3StepPreservesInv.smt2 | 1000.000s | -1B| not-run | -1 |  |  |
