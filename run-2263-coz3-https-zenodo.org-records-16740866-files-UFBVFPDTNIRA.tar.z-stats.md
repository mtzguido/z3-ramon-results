# .

* SAT 0
* UNSAT 21
* TIMEOUT 68
* UNKNOWN 0

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/UFBVFPDTNIRA.tar.zst?download=1 | Source list: quantifier_benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-UFBVFPDTNIRA.tar.z
Runner: rise-runner-1
Z3 repo: Z3Prover/z3
Z3 commit: c3f5365a95a7eac2419a2f95ff240909f275cc08
Z3 branch: c3f5365a95a7eac2419a2f95ff240909f275cc08
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/UFBVFPDTNIRA.tar.zst?download=1
Z3 commit message: Update generation number of already-internalized enodes (#9628)

Below are the effects on Mariposa's unsat core:

| Query | Unsats before | Unknowns before | Timeouts before | Unsats
after | Unknowns after | Timeouts after | Delta Unsat | Delta Unknown |
Delta Timeout |
|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|
|
d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.FlushPreservesLookups.smt2
| 94 | 5 | 1 | 99 | 0 | 1 | +5 | -5 | +0 |
|
d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ReqWrite2StepPreservesInv.smt2
| 41 | 0 | 59 | 44 | 0 | 56 | +3 | +0 | -3 |
|
d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesProcessWrite.smt2
| 75 | 25 | 0 | 99 | 1 | 0 | +24 | -24 | +0 |
|
d_fvbkv-Impl-FlushPolicyImpl.i.dfy.Impl__FlushPolicyImpl.__default.runFlushPolicy.smt2
| 12 | 0 | 88 | 6 | 0 | 94 | -6 | +0 | +6 |
| d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.PageInNodeResp.smt2 |
84 | 0 | 16 | 81 | 0 | 19 | -3 | +0 | +3 |
|
d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.append.smt2
| 88 | 12 | 0 | 99 | 1 | 0 | +11 | -11 | +0 |
|
d_fvbkv-Impl-QueryImpl.i.dfy.Impl__QueryImpl.__default.queryIterate.smt2
| 48 | 0 | 52 | 43 | 0 | 57 | -5 | +0 | +5 |
|
d_fvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.set__bit__to__0__self__uint64.smt2
| 100 | 0 | 0 | 100 | 0 | 0 | +0 | +0 | +0 |
|
d_fvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.set__bit__to__1__self__uint64.smt2
| 100 | 0 | 0 | 100 | 0 | 0 | +0 | +0 | +0 |
|
d_fvbkv-lib-Buckets-KMBPKVOps.i.dfy.Impl__KMBPKVOps.__default.IndexFillDpkv.smt2
| 42 | 0 | 58 | 41 | 0 | 59 | -1 | +0 | +1 |
|
d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.BinarySearchQuery.smt2
| 78 | 5 | 17 | 92 | 1 | 7 | +14 | -4 | -10 |
|
d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.UniqueRepr.smt2
| 100 | 0 | 0 | 100 | 0 | 0 | +0 | +0 | +0 |
|
d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.WFpsaSubSeq.smt2
| 90 | 1 | 9 | 82 | 0 | 18 | -8 | -1 | +9 |
|
d_fvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.SplitIndexAllKeys.smt2
| 8 | 0 | 92 | 9 | 0 | 91 | +1 | +0 | -1 |
|
d_fvbkv-lib-DataStructures-LruImpl.i.dfy.Impl__LruImpl.LruImplQueue.Use.smt2
| 92 | 5 | 3 | 97 | 0 | 3 | +5 | -5 | +0 |
|
d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SubIndex.smt2
| 44 | 28 | 28 | 50 | 2 | 48 | +6 | -26 | +20 |
|
d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SubReprLowerBound.smt2
| 96 | 4 | 0 | 98 | 2 | 0 | +2 | -2 | +0 |
|
d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallArray.smt2
| 46 | 54 | 0 | 76 | 24 | 0 | +30 | -30 | +0 |
|
d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint32Array.smt2
| 81 | 19 | 0 | 96 | 3 | 1 | +15 | -16 | +1 |
|
d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint64Array.smt2
| 85 | 15 | 0 | 95 | 5 | 0 | +10 | -10 | +0 |
|
d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__2toX.smt2
| 74 | 26 | 0 | 100 | 0 | 0 | +26 | -26 | +0 |
|
d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__div__denominator.smt2
| 93 | 0 | 7 | 99 | 0 | 1 | +6 | +0 | -6 |
|
d_fvbkv-lib-Math-mod_auto_proofs.i.dfy.Impl__Math____mod__auto__proofs__i.__default.lemma__mod__induction__forall2.smt2
| 67 | 0 | 33 | 67 | 0 | 33 | +0 | +0 | +0 |
|
d_fvbkv-lib-Math-mod_auto_proofs.i.dfy.Impl__Math____mod__auto__proofs__i.__default.lemma__mod__induction__forall.smt2
| 0 | 0 | 100 | 0 | 0 | 100 | +0 | +0 | +0 |
|
d_fvbkv-lib-Math-mul.i.dfy.Impl__Math____mul__i.__default.lemma__mul__nonnegative.smt2
| 0 | 0 | 100 | 0 | 0 | 100 | +0 | +0 | +0 |
|
d_komodo-verified-ptebits.i.dfyImpl___module.__default.lemma__l1ptesmatch.smt2
| 59 | 0 | 41 | 68 | 0 | 32 | +9 | +0 | -9 |
|
d_komodo-verified-secprop-conf_ni.i.dfyImpl___module.__default.lemma__initL2PTable__loweq__pdb.smt2
| 81 | 0 | 19 | 85 | 0 | 15 | +4 | +0 | -4 |
|
d_komodo-verified-sha-sha256-body-00-15.gen.dfyImpl___module.__default.va__refined__Body__00__15UnrolledRecursive.smt2
| 0 | 0 | 100 | 0 | 0 | 100 | +0 | +0 | +0 |
|
d_komodo-verified-sha-sha256-body-16-xx.gen.dfyImpl___module.__default.va__refined__Body__16__XXUnroller.smt2
| 8 | 0 | 92 | 9 | 0 | 91 | +1 | +0 | -1 |
|
d_komodo-verified-sha-sha256.i.dfyImpl___module.__default.lemma__SHA256FinalHelper1.smt2
| 95 | 0 | 5 | 95 | 1 | 4 | +0 | +1 | -1 |
|
d_komodo-verified-verify.gen.dfyImpl___module.__default.va__lemma__svc__returning__verify__inner_k.smt2
| 9 | 0 | 91 | 6 | 0 | 94 | -3 | +0 | +3 |
|
d_komodo-verified-verify.gen.dfyImpl___module.__default.va__lemma__svc__returning__verify__inner.smt2
| 69 | 0 | 31 | 61 | 0 | 39 | -8 | +0 | +8 |
|
d_komodo-verified-verify.gen.dfyImpl___module.__default.va__lemma__svc__returning__verify.smt2
| 85 | 0 | 15 | 78 | 0 | 22 | -7 | +0 | +7 |
|
d_lvbkv-Impl-BucketGeneratorModel.i.dfy.Impl__BucketGeneratorModel.__default.GenComposeIsCompose.smt2
| 53 | 0 | 47 | 53 | 0 | 47 | +0 | +0 | +0 |
|
d_lvbkv-Impl-JournalistImpl.i.dfy.Impl__JournalistImpl.Journalist.append.smt2
| 93 | 4 | 3 | 96 | 0 | 4 | +3 | -4 | +1 |
|
d_lvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.strictlySortedPivotsToVal.smt2
| 5 | 0 | 95 | 0 | 0 | 100 | -5 | +0 | +5 |
|
d_lvbkv-lib-Base-total_order_impl.i.dfy.Impl__Total__Order__Impl.__default.ArrayLargestLtePlus1Linear.smt2
| 48 | 52 | 0 | 99 | 1 | 0 | +51 | -51 | +0 |
|
d_lvbkv-lib-Buckets-BucketsLib.i.dfy.Impl__BucketsLib.__default.WFProperSplitBucketInList.smt2
| 39 | 22 | 39 | 40 | 15 | 45 | +1 | -7 | +6 |
|
d_lvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.DynamicPkv.Append.smt2
| 80 | 0 | 20 | 80 | 0 | 20 | +0 | +0 | +0 |
|
d_lvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.BinarySearchQuery.smt2
| 15 | 5 | 80 | 11 | 0 | 89 | -4 | -5 | +9 |
|
d_lvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.psaCanAppendI.smt2
| 61 | 0 | 39 | 70 | 0 | 30 | +9 | +0 | -9 |
|
d_lvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.DynamicPsa.AppendSeq.smt2
| 2 | 0 | 98 | 4 | 0 | 96 | +2 | +0 | -2 |
|
d_lvbkv-lib-Checksums-BitLemmas.i.dfy.Impl__BitLemmas.__default.eq__from__unpack__LittleEndian__Uint32__eq.smt2
| 99 | 0 | 1 | 99 | 0 | 1 | +0 | +0 | +0 |
|
d_lvbkv-lib-DataStructures-LinearContentMutableMap.i.dfy.Impl__LinearContentMutableMap.__default.Realloc.smt2
| 1 | 0 | 99 | 0 | 0 | 100 | -1 | +0 | +1 |
|
d_lvbkv-lib-DataStructures-LinearDList.i.dfy.Impl__DList.DList.InsertAfter.smt2
| 0 | 0 | 100 | 0 | 0 | 100 | +0 | +0 | +0 |
|
d_lvbkv-lib-DataStructures-LinearDList.i.dfy.Impl__DList.DList.InsertBefore.smt2
| 0 | 2 | 98 | 0 | 1 | 99 | +0 | -1 | +1 |
|
d_lvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__LMutableBtree.__default.InsertIndex.smt2
| 98 | 0 | 2 | 83 | 0 | 17 | -15 | +0 | +15 |
|
d_lvbkv-lib-Lang-LinearSequence.i.dfy.Impl__LinearSequence__i.__default.AllocAndMoveLseq.smt2
| 97 | 3 | 0 | 100 | 0 | 0 | +3 | -3 | +0 |
|
d_lvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallArray.smt2
| 79 | 21 | 0 | 77 | 23 | 0 | -2 | +2 | +0 |
|
d_lvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallByteArrayInterior.smt2
| 100 | 0 | 0 | 100 | 0 | 0 | +0 | +0 | +0 |
|
d_lvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallByteArray.smt2
| 94 | 6 | 0 | 98 | 2 | 0 | +4 | -4 | +0 |
|
d_lvbkv-lib-Math-Nonlinear.i.dfy.Impl__NonlinearLemmas.__default.div__denom__ge__1.smt2
| 91 | 9 | 0 | 97 | 3 | 0 | +6 | -6 | +0 |
|
d_lvbkv-MapSpec-TSJMap_Refines_ThreeStateVersionedMap.i.dfy.Impl__TSJMap__Refines__ThreeStateVersionedMap.__default.RefinesReplay.smt2
| 69 | 0 | 31 | 66 | 0 | 34 | -3 | +0 | +3 |
|
d_lvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.Impl__PivotBetreeSpecRefinement.__default.SplitChildrenConsistent.smt2
| 31 | 0 | 69 | 28 | 0 | 72 | -3 | +0 | +3 |
|
d_lvbkv-PivotBetree-PivotBetreeSpecWFNodes.i.dfy.Impl__PivotBetreeSpecWFNodes.__default.ValidSplitWritesInvNodes.smt2
| 100 | 0 | 0 | 99 | 0 | 1 | -1 | +0 | +1 |
| fs_dice-queries-ASN1.Low.Base-3.smt2 | 1 | 32 | 0 | 1 | 32 | 0 | +0 |
+0 | +0 |
| fs_dice-queries-L0.X509.AliasKeyTBS.Issuer-7.smt2 | 33 | 0 | 0 | 33 |
0 | 0 | +0 | +0 | +0 |
| fs_dice-queries-L0.X509.AliasKeyTBS.Subject-7.smt2 | 33 | 0 | 0 | 33 |
0 | 0 | +0 | +0 | +0 |
| s_komodo-1504.4.smt2 | 0 | 0 | 100 | 0 | 0 | 100 | +0 | +0 | +0 |

---------

Co-authored-by: Can Cebeci <t-cancebeci@microsoft.com>
Co-authored-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__errorexample.ads_26_14_postcondition___00.smt2 |    0.017s | 19.136MiB| unsat | 1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC01-041__float_range__q.adb_14_27_division_check___00.smt2 |    0.018s | 19.428MiB| unsat | 1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__errorexample.adb_28_22_assert___00.smt2 |    0.030s | 19.244MiB| unsat | 1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__errorexample.ads_26_77_division_check___00.smt2 |    0.031s | 19.26MiB| unsat | 1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_577_26_precondition___00.smt2 |    0.034s | 21.344MiB| unsat | 1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC01-041__float_range__q.adb_21_14_division_check___00.smt2 |    0.101s | 35.792MiB| unsat | 1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC03-013__float_division__a.adb_27_28_assert___00.smt2 |    0.124s | 52.664MiB| unsat | 1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_587_27_precondition___00.smt2 |    0.125s | 22.656MiB| unsat | 1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC03-013__float_division__a.adb_28_30_range_check___00.smt2 |    0.134s | 53.06MiB| unsat | 1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC03-013__float_division__a.adb_21_25_assert___00.smt2 |    0.153s | 23.364MiB| unsat | 1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_577_26_range_check___00.smt2 |    0.156s | 23.9MiB| unsat | 1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC03-013__float_division__a.adb_22_17_division_check___00.smt2 |    0.175s | 23.284MiB| unsat | 1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_587_27_range_check___00.smt2 |    0.212s | 25.132MiB| unsat | 1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_597_27_range_check___00.smt2 |    0.292s | 27.856MiB| unsat | 1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_597_27_precondition___00.smt2 |    0.387s | 25.464MiB| unsat | 1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/O227-007__float_double_inconsistency__wibble.adb_45_17_postcondition___00.smt2 |    0.574s | 32.62MiB| unsat | 1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC01-041__float_range__q.adb_28_31_range_check___00.smt2 |    1.668s | 65.564MiB| unsat | 1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/O227-007__float_double_inconsistency__wibble.adb_55_17_postcondition___00.smt2 |    1.698s | 41.48MiB| unsat | 1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC03-013__float_division__a.adb_22_17_fp_overflow_check___00.smt2 |    2.171s | 52.848MiB| unsat | 1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC01-041__float_range__q.adb_17_17_fp_overflow_check___00.smt2 |    7.106s | 42.092MiB| unsat | 1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC01-041__float_range__q.adb_21_14_fp_overflow_check___00.smt2 |    9.538s | 66.276MiB| unsat | 1 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__simple_trajectory.adb_34_22_assert___00.smt2 |   20.007s | 23.312MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory_overflow.adb_46_22_assert___00.smt2 |   20.007s | 23.272MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_71_22_assert___00.smt2 |   20.007s | 23.288MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_283_64_fp_overflow_check___00.smt2 |   20.007s | 23.208MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_226_39_overflow_check___00.smt2 |   20.007s | 23.184MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_197_46_overflow_check___00.smt2 |   20.007s | 23.16MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_51_22_assert___00.smt2 |   20.007s | 23.22MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_210_48_overflow_check___00.smt2 |   20.007s | 23.376MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_40_22_assert___00.smt2 |   20.007s | 23.388MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_205_45_overflow_check___00.smt2 |   20.007s | 23.036MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_69_22_assert___00.smt2 |   20.007s | 23.116MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/O220-024__floats__wibble.adb_11_3_precondition___00.smt2 |   20.008s | 38.844MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_214_48_overflow_check___00.smt2 |   20.008s | 23.1MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_48_25_assert___00.smt2 |   20.008s | 23.272MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.ads_48_32_range_check___00.smt2 |   20.008s | 23.292MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_201_41_overflow_check___00.smt2 |   20.008s | 23.196MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory_overflow.adb_28_22_assert___00.smt2 |   20.008s | 23.172MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_287_69_division_check___00.smt2 |   20.008s | 23.192MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory_overflow.adb_35_22_assert___00.smt2 |   20.008s | 23.228MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_46_25_assert___00.smt2 |   20.008s | 23.276MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__simple_trajectory.adb_38_22_assert___00.smt2 |   20.008s | 23.328MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_44_22_assert___00.smt2 |   20.009s | 23.276MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory_overflow.adb_39_22_assert___00.smt2 |   20.009s | 23.236MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_313_40_division_check___00.smt2 |   20.009s | 23.56MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__simple_trajectory.adb_27_22_assert___00.smt2 |   20.010s | 23.268MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC01-041__float_range__test.adb_28_19_assert___00.smt2 |   20.010s | 30.532MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__simple_trajectory.ads_41_32_range_check___00.smt2 |   20.010s | 23.28MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/O227-007__float_double_inconsistency__wibble.adb_35_17_postcondition___00.smt2 |   20.010s | 53.772MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/O227-007__float_double_inconsistency__wibble.adb_15_17_postcondition___00.smt2 |   20.011s | 54.096MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_287_69_fp_overflow_check___00.smt2 |   20.011s | 23.116MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_60_22_assert___00.smt2 |   20.011s | 23.268MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_279_47_range_check___00.smt2 |   20.011s | 23.176MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_39_22_assert___00.smt2 |   20.011s | 23.184MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_52_22_assert___00.smt2 |   20.011s | 23.276MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_67_22_assert___00.smt2 |   20.012s | 23.28MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_234_41_overflow_check___00.smt2 |   20.012s | 23.208MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_35_22_assert___00.smt2 |   20.012s | 23.24MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC01-041__float_range__q.adb_20_22_assert___00.smt2 |   20.012s | 52.104MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_72_22_assert___00.smt2 |   20.012s | 23.196MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__errorexample.adb_47_22_assert___00.smt2 |   20.013s | 36.768MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_273_22_assert___00.smt2 |   20.013s | 23.176MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__simple_trajectory.adb_36_22_assert___00.smt2 |   20.013s | 23.072MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_54_22_assert___00.smt2 |   20.013s | 23.272MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory_overflow.adb_37_22_assert___00.smt2 |   20.014s | 23.264MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__simple_trajectory.adb_39_22_assert___00.smt2 |   20.015s | 23.216MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/M919-035__floating_point__zero_and_min.adb_14_25_zero_and_min.adb_26_4_assert___00.smt2 |   20.015s | 22.512MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_28_22_assert___00.smt2 |   20.015s | 23.208MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__simple_trajectory.ads_41_19_postcondition___00.smt2 |   20.017s | 23.06MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_275_47_range_check___00.smt2 |   20.017s | 23.18MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_313_40_fp_overflow_check___00.smt2 |   20.017s | 23.56MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_53_22_assert___00.smt2 |   20.017s | 23.24MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory_overflow.ads_42_32_range_check___00.smt2 |   20.017s | 23.26MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory_overflow.adb_40_22_assert___00.smt2 |   20.018s | 23.276MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__simple_trajectory.adb_37_22_assert___00.smt2 |   20.018s | 23.26MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/O227-007__float_double_inconsistency__wibble.adb_25_17_postcondition___00.smt2 |   20.018s | 70.328MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/M919-035__floating_point__zero_and_unchecked.adb_14_22_zero_and_unchecked.adb_27_4_division_check___00.smt2 |   20.018s | 22.416MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC01-041__float_range__test.adb_22_19_assert___00.smt2 |   20.019s | 28.004MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_230_41_overflow_check___00.smt2 |   20.019s | 22.864MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_218_45_overflow_check___00.smt2 |   20.020s | 23.048MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_38_22_assert___00.smt2 |   20.021s | 23.264MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_50_22_assert___00.smt2 |   20.023s | 23.212MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.adb_37_22_assert___00.smt2 |   20.024s | 23.14MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory.ads_48_19_postcondition___00.smt2 |   20.027s | 23.14MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_193_42_overflow_check___00.smt2 |   20.028s | 23.164MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory_overflow.ads_42_19_postcondition___00.smt2 |   20.032s | 23.208MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/N127-048__cvc4__nose_gear.adb_270_45_range_check___00.smt2 |   20.033s | 23.204MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/trajectory_computation__complex_trajectory_overflow.adb_38_22_assert___00.smt2 |   20.035s | 23.28MiB| timeout | 0 |  |  |
|non-incremental/UFBVFPDTNIRA/20200306-Kanig/spark2014bench/NC01-041__float_range__test.adb_16_19_assert___00.smt2 |   20.035s | 28.428MiB| timeout | 0 |  |  |
