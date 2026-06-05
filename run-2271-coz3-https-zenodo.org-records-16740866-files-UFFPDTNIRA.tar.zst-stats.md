# .

* SAT 59
* UNSAT 559
* TIMEOUT 176
* UNKNOWN 1

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/UFFPDTNIRA.tar.zst?download=1 | Source list: quantifier_benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-UFFPDTNIRA.tar.zst
Runner: rise-runner-1
Z3 repo: Z3Prover/z3
Z3 commit: c3f5365a95a7eac2419a2f95ff240909f275cc08
Z3 branch: c3f5365a95a7eac2419a2f95ff240909f275cc08
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/UFFPDTNIRA.tar.zst?download=1
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
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/K720-019__floats__pack.adb_10_52_precondition___00.smt2 |    0.014s | 19.312MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/OB23-014__float_literal__u.adb_13_20_assert___00.smt2 |    0.015s | 19.28MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O401-034__float_pred__safety_pack.adb_71_17_predicate_check___00.smt2 |    0.015s | 19.152MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/N116-016__floating_point__precise.adb_12_11_division_check___00.smt2 |    0.015s | 19.08MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/N703-010__float_conversion__foo.adb_23_15_range_check___00.smt2 |    0.015s | 18.988MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O205-003__dynamic_float__test_dynamic_property.adb_22_20_fp_overflow_check___00.smt2 |    0.016s | 19.176MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O205-003__dynamic_float__test_dynamic_property.adb_45_17_fp_overflow_check___00.smt2 |    0.016s | 19.012MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/KC20-033__in_range__p.adb_51_19_precondition___00.smt2 |    0.016s | 19.084MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M603-018__float__testfloat.adb_46_19_assert___00.smt2 |    0.016s | 19.228MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P310-021__proof_float_remainder__foo.adb_9_17_division_check___00.smt2 |    0.016s | 19.092MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M603-018__float__testfloat.adb_41_19_assert___00.smt2 |    0.016s | 19.248MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M603-018__float__testfloat.adb_39_19_assert___00.smt2 |    0.016s | 19.036MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/Q208-056__no_denorm_on_target__compute.adb_4_20_overflow_check___00.smt2 |    0.016s | 18.972MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/OB23-014__float_literal__u.adb_12_20_assert___00.smt2 |    0.016s | 19.276MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P912-012__float_zero_numerics__numerics.ads_13_142_fp_overflow_check___00.smt2 |    0.016s | 19.072MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/N122-021__succ_floats__succ_floats.adb_8_31_overflow_check___00.smt2 |    0.016s | 19.1MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M603-018__float__testfloat.adb_31_22_assert___00.smt2 |    0.016s | 19.404MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O512-022__number_theory__number_theory.adb_19_50_range_check___00.smt2 |    0.016s | 19.48MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PB23-014__float_monotonicity__add.adb_10_16_postcondition___00.smt2 |    0.016s | 19.028MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PB16-052__float_invariant__attempt_3.adb_64_54_overflow_check___00.smt2 |    0.017s | 19.08MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O512-022__number_theory__number_theory.ads_23_47_division_check___00.smt2 |    0.017s | 19.2MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/N122-021__succ_floats__succ_floats.adb_5_31_overflow_check___00.smt2 |    0.017s | 19.024MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P830-027__flow_variables_in_float__f.adb_3_12_range_check___00.smt2 |    0.017s | 19.06MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M122-006__assign2__p.adb_8_9_discriminant_check___00.smt2 |    0.017s | 19.216MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O512-022__number_theory__number_theory.adb_19_74_range_check___00.smt2 |    0.017s | 19.04MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/KC20-033__in_range__p.adb_50_19_precondition___00.smt2 |    0.017s | 19.304MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__abs_controller_oem_with_property.adb_33_22_assert___00.smt2 |    0.017s | 19.256MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PA20-061__flow_variable_constant__basic_contracts.adb_12_18_fp_overflow_check___00.smt2 |    0.017s | 19.044MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M919-035__floating_point__dynamic_float.adb_6_18_range_check___00.smt2 |    0.017s | 19.196MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M603-018__float__testfloat.adb_23_22_assert___00.smt2 |    0.017s | 19.088MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PA20-061__flow_variable_constant__basic_contracts.adb_6_17_postcondition___00.smt2 |    0.017s | 19.148MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PB16-052__float_invariant__attempt_3.adb_62_32_overflow_check___00.smt2 |    0.017s | 19.016MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P912-012__float_zero_numerics__numerics.ads_19_150_fp_overflow_check___00.smt2 |    0.017s | 19.04MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/NC05-005__float_division__pi_euler.adb_11_33_loop_invariant_init2___00.smt2 |    0.017s | 19.388MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_ec718c_generic_float_tests-T-defqtvc__00.smt2 |    0.017s | 19.348MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/N116-016__floating_point__precise.adb_7_19_assert___00.smt2 |    0.017s | 18.892MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M603-018__float__testfloat.adb_42_19_assert___00.smt2 |    0.017s | 19.096MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M603-018__float__testfloat.adb_37_19_assert___00.smt2 |    0.017s | 19.224MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O715-033__level2__hard_stuff.adb_20_52_division_check___00.smt2 |    0.018s | 19.18MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O416-002__dyn_pred_rte__pred.adb_29_22_discriminant_check___00.smt2 |    0.018s | 19.2MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O401-034__float_pred__safety_pack.adb_67_17_predicate_check___00.smt2 |    0.018s | 18.996MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P912-012__float_zero_numerics__run.adb_8_15_precondition___00.smt2 |    0.018s | 19.616MiB| sat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O826-006__float_exponential__float_expon.adb_10_17_division_check___00.smt2 |    0.018s | 18.968MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/N709-001__tagged_discr__tagged_discr.ads_19_28_discriminant_check___00.smt2 |    0.018s | 19.256MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/KB04-017__float__p.adb_3_9_range_check___00.smt2 |    0.018s | 19.056MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/N709-018__spurious_discr__useless_discr.adb_16_10_range_check___00.smt2 |    0.018s | 19.208MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_577336_generic_float_tests-T-defqtvc__00.smt2 |    0.018s | 19.284MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/NC05-005__float_division__pi_euler_2.adb_16_25_assert2___00.smt2 |    0.018s | 19.14MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/MC17-036__gnatVa__protectedfloat.adb_14_29_division_check___00.smt2 |    0.018s | 18.976MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PA20-061__flow_variable_constant__basic_contracts.adb_12_18_division_check___00.smt2 |    0.018s | 19.16MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O416-002__dyn_pred_rte__pred.adb_29_21_unreachable_branch___00.smt2 |    0.018s | 19.252MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P912-012__float_zero_numerics__numerics.ads_19_150_division_check___00.smt2 |    0.018s | 19.54MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/Q424-012__succ_floats_copy_z3__succ_floats.adb_6_31_overflow_check___00.smt2 |    0.018s | 19.336MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/Q424-012__succ_floats_copy_z3__succ_floats.adb_7_31_overflow_check___00.smt2 |    0.018s | 18.992MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P620-034__float_out_subtype__get_out_subtype.adb_27_58_range_check___00.smt2 |    0.018s | 19.184MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/Q424-012__succ_floats_copy_z3__succ_floats.adb_13_31_overflow_check___00.smt2 |    0.018s | 18.984MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_475293_generic_float_tests-T-defqtvc__00.smt2 |    0.019s | 19.38MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P912-012__float_zero_numerics__numerics.ads_16_142_fp_overflow_check___00.smt2 |    0.019s | 19.012MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_199_14_precondition___00.smt2 |    0.019s | 20.472MiB| sat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/Q607-007__floats__normalize.adb_20_12_postcondition___00.smt2 |    0.019s | 19.116MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PB23-014__float_monotonicity__add.adb_13_4_precondition___00.smt2 |    0.019s | 19.94MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/Q607-007__floats__normalize.adb_133_22_assert___00.smt2 |    0.019s | 19.468MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_1077_52_precondition___00.smt2 |    0.019s | 19.028MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/MC17-036__gnatVa__protectedfloat.adb_17_24_division_check___00.smt2 |    0.019s | 19.664MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P405-006__arithmetic_from_dafny__div_lemmas.adb_45_16_division_check___00.smt2 |    0.019s | 19.668MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/K719-019__flight_mgr__flight_manager.ads_12_23_fp_overflow_check___00.smt2 |    0.019s | 19.192MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O401-034__float_pred__safety_pack.adb_73_17_predicate_check___00.smt2 |    0.019s | 19.664MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_bbb756_generic_float_tests-T-defqtvc__00.smt2 |    0.019s | 19.344MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/R123-048__tasks__psu_monitoring.ads_92_132_fp_overflow_check___00.smt2 |    0.019s | 19.296MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/N116-016__floating_point__precise.adb_12_11_fp_overflow_check___00.smt2 |    0.020s | 19.116MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_1032_47_precondition___00.smt2 |    0.020s | 20.592MiB| sat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/KC20-033__in_range__p.adb_52_19_precondition___00.smt2 |    0.020s | 19.188MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__biaseddivide.ads_19_20_fp_overflow_check___00.smt2 |    0.020s | 19.052MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M422-023__from_int__sgs.adb_10_22_assert___00.smt2 |    0.020s | 19.944MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/Q424-012__succ_floats_copy_z3__succ_floats.adb_12_31_overflow_check___00.smt2 |    0.020s | 19.028MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O303-041__flow_pure_implies_null_global__foo.adb_5_9_precondition___00.smt2 |    0.020s | 20.332MiB| sat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/N122-021__succ_floats__succ_floats.adb_13_19_assert___00.smt2 |    0.020s | 20.024MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_9b412c_generic_float_tests-T-defqtvc__00.smt2 |    0.020s | 19.784MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O205-003__dynamic_float__test_dynamic_property.adb_34_17_range_check___00.smt2 |    0.021s | 20.148MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_8c6282_generic_float_tests-T-defqtvc__00.smt2 |    0.021s | 19.816MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O429-046__flow_tasking_contracts__watchdog.ads_6_9_ceiling__priority_protocol___00.smt2 |    0.021s | 19.08MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_1050_47_precondition___00.smt2 |    0.021s | 20.304MiB| sat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M422-023__from_int__sgs.adb_15_22_assert___00.smt2 |    0.021s | 20.052MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/L402-004__exp__p.adb_4_14_overflow_check___00.smt2 |    0.021s | 20.208MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_796bf2_generic_float_tests-T-defqtvc__00.smt2 |    0.021s | 19.724MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O205-003__dynamic_float__test_dynamic_property.adb_6_29_range_check___00.smt2 |    0.021s | 19.844MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/L402-004__exp__p.adb_3_7_overflow_check___00.smt2 |    0.021s | 20.452MiB| sat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/Q522-022__codepeer__proof.adb_11_15_precondition___00.smt2 |    0.021s | 20.18MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P405-006__arithmetic_from_dafny__div_lemmas.adb_60_18_range_check___00.smt2 |    0.021s | 19.264MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/K720-019__floats__pack.ads_15_37_fp_overflow_check___00.smt2 |    0.021s | 19.012MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P830-027__flow_variables_in_float__f.adb_4_12_range_check___00.smt2 |    0.022s | 19.204MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/Q522-022__codepeer__proof.adb_25_15_precondition___00.smt2 |    0.022s | 20.164MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_208_47_precondition___00.smt2 |    0.022s | 20.636MiB| sat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_471921_generic_float_tests-T-defqtvc__00.smt2 |    0.022s | 20.196MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M422-023__from_int__sgs.adb_22_22_assert___00.smt2 |    0.022s | 19.072MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P912-012__float_zero_numerics__numerics.ads_10_100_postcondition___00.smt2 |    0.022s | 19.396MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/OB16-021__float_range__test_float.adb_6_19_assert___00.smt2 |    0.022s | 20.252MiB| sat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_1059_52_precondition___00.smt2 |    0.022s | 20.552MiB| sat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O205-003__dynamic_float__test_dynamic_property.adb_57_24_range_check___01.smt2 |    0.022s | 20.58MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P912-012__float_zero_numerics__numerics.ads_10_142_fp_overflow_check___00.smt2 |    0.022s | 19.012MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_16abab_generic_float_tests-T-defqtvc__00.smt2 |    0.022s | 27.584MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O512-022__number_theory__number_theory.adb_19_38_loop_invariant_init___00.smt2 |    0.023s | 19.624MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_579cc3_generic_float_tests-T-defqtvc__00.smt2 |    0.023s | 20.356MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/N122-021__succ_floats__succ_floats.adb_20_22_assert___00.smt2 |    0.023s | 20.324MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PB23-014__float_monotonicity__mul.adb_13_4_precondition___00.smt2 |    0.023s | 19.92MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_b9c8dc_generic_float_tests-T-defqtvc__00.smt2 |    0.023s | 19.76MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_1209_31_division_check___00.smt2 |    0.023s | 20.052MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/R123-048__tasks__psu_monitoring.ads_92_7_complete_contract_cases___00.smt2 |    0.023s | 20.192MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_34db83_generic_float_tests-T-defqtvc__00.smt2 |    0.024s | 20.076MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O205-003__dynamic_float__test_dynamic_property.adb_11_28_range_check___00.smt2 |    0.024s | 20.148MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_1185_52_precondition___00.smt2 |    0.024s | 20.508MiB| sat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O416-002__dyn_pred_rte__pred.adb_30_21_unreachable_branch___00.smt2 |    0.024s | 19.316MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M603-018__float__testfloat.adb_47_19_assert___00.smt2 |    0.024s | 19.744MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/L402-004__exp__p.adb_6_12_overflow_check___00.smt2 |    0.024s | 20.512MiB| sat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PB16-038__float_intervals__foo.adb_30_22_assert___00.smt2 |    0.024s | 19.92MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/N709-001__tagged_discr__classwide.ads_53_14_postcondition___00.smt2 |    0.024s | 19.88MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_5f8af6_generic_float_tests-T-defqtvc__00.smt2 |    0.024s | 20.4MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/proofinuse__lat_long__lat_long.ads_39_45_division_check___00.smt2 |    0.024s | 20.4MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P315-010__float__call_sample2.adb_13_7_call_sample2.adb_28_4_precondition___00.smt2 |    0.025s | 19.192MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/N122-021__succ_floats__succ_floats.adb_30_31_overflow_check___00.smt2 |    0.025s | 20.66MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P909-014__numerics__numerics-algo.adb_19_17_precondition___00.smt2 |    0.025s | 20.344MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/N116-016__floating_point__test_float.adb_16_4_precondition___00.smt2 |    0.025s | 19.012MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/proofinuse__lat_long__lat_long.adb_9_58_division_check___00.smt2 |    0.025s | 20.504MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O416-002__dyn_pred_rte__pred.adb_27_8_precondition___00.smt2 |    0.025s | 19.788MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_ca1a1e_generic_float_tests-T-defqtvc__00.smt2 |    0.025s | 20.364MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/N116-016__floating_point__test_float.adb_8_14_postcondition___00.smt2 |    0.026s | 22.344MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M422-023__from_int__sgs.adb_12_22_assert___00.smt2 |    0.026s | 20.076MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M603-018__float__testfloat.adb_7_20_fp_overflow_check___00.smt2 |    0.026s | 18.988MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/K719-019__flight_mgr__flight_manager.adb_13_46_division_check___00.smt2 |    0.026s | 19.16MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PC05-013__interval_overflow__mult.adb_11_55_overflow_check___00.smt2 |    0.026s | 20.448MiB| sat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PB16-052__float_invariant__attempt_2.adb_19_18_overflow_check___00.smt2 |    0.026s | 20.272MiB| sat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_5c42fa_generic_interval_tests-T-defqtvc__00.smt2 |    0.026s | 20.808MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/R123-048__tasks__psu_monitoring.adb_98_75_division_check___00.smt2 |    0.027s | 20.528MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O205-003__dynamic_float__test_dynamic_property.adb_60_22_range_check___00.smt2 |    0.027s | 20.9MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_5dd164_generic_float_tests-T-defqtvc__00.smt2 |    0.027s | 20.032MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/N116-016__floating_point__precise.adb_13_19_assert___00.smt2 |    0.027s | 19.164MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_0d36c5_generic_float_tests-T-defqtvc__00.smt2 |    0.027s | 27.552MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O205-003__dynamic_float__test_dynamic_property.adb_53_19_assert___00.smt2 |    0.028s | 20.608MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_b72bc0_generic_interval_tests-T-defqtvc__00.smt2 |    0.028s | 20.692MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_3d969b_generic_float_tests-T-defqtvc__00.smt2 |    0.028s | 19.384MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_8f06c6_generic_interval_tests-T-defqtvc__00.smt2 |    0.028s | 21.92MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_577b67_generic_float_tests-T-defqtvc__00.smt2 |    0.028s | 27.472MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/TU__depends_legal__depends_legal_2.adb_48_12_discriminant_check___00.smt2 |    0.028s | 19.78MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_fd32b1_generic_interval_tests-T-defqtvc__00.smt2 |    0.028s | 21.528MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O205-003__dynamic_float__test_dynamic_property.adb_57_24_range_check___00.smt2 |    0.028s | 20.716MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P405-006__arithmetic_from_dafny__div_lemmas.adb_56_4_precondition___00.smt2 |    0.029s | 19.052MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_72f01f_generic_float_tests-T-defqtvc__00.smt2 |    0.029s | 21.596MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/TU__depends_legal__depends_legal_2.adb_45_15_discriminant_check___00.smt2 |    0.029s | 19.284MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/K719-019__flight_mgr__flight_manager.adb_19_43_division_check___00.smt2 |    0.029s | 19.052MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PB02-004__inherited_sub__main.adb_18_27_range_check___00.smt2 |    0.030s | 19.272MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/N709-001__tagged_discr__tagged_discr.adb_7_9_discriminant_check___00.smt2 |    0.030s | 20.276MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/proofinuse__lat_long__lat_long.ads_15_12_postcondition___00.smt2 |    0.031s | 21.232MiB| sat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_6fdf6d_generic_float_tests-T-defqtvc__00.smt2 |    0.031s | 19.264MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/Q424-012__succ_floats_copy_z3__succ_floats.adb_14_31_overflow_check___00.smt2 |    0.031s | 19.012MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M422-023__from_int__sgs.adb_20_22_assert___00.smt2 |    0.031s | 19.42MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O917-065__unreferenced__unref.adb_5_19_postcondition___00.smt2 |    0.031s | 19.376MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_1068_47_precondition___00.smt2 |    0.031s | 19.032MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O401-034__float_pred__safety_pack.ads_59_38_contract_case___00.smt2 |    0.031s | 19.124MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O723-005__generic_in_entry__a-tiflio.ads_78_8_p.adb_9_10_precondition___00.smt2 |    0.031s | 19.032MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O512-022__number_theory__number_theory.ads_20_45_range_check___00.smt2 |    0.031s | 19.876MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_1041_52_precondition___00.smt2 |    0.032s | 20.732MiB| sat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/Q424-012__succ_floats_copy_z3__succ_floats.adb_11_31_overflow_check___00.smt2 |    0.032s | 19.064MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O205-003__dynamic_float__test_dynamic_property.adb_5_12_range_check___00.smt2 |    0.032s | 19.008MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/S603-051__dimensions__image_golf_hole.adb_16_10_image_golf_hole.adb_32_10_predicate_check_on_default_value___00.smt2 |    0.032s | 20.36MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/KC20-033__in_range__p.adb_48_19_precondition___00.smt2 |    0.032s | 19.072MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_d7746d_generic_float_tests-T-defqtvc__00.smt2 |    0.032s | 19.504MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/OB04-007__float_conversion__floatround.adb_11_15_precondition___00.smt2 |    0.032s | 19.112MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/Q424-012__succ_floats_copy_z3__succ_floats.adb_28_34_overflow_check___00.smt2 |    0.032s | 19.24MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/MC13-026__float_div__protectedfloat.adb_12_29_division_check___00.smt2 |    0.032s | 19.072MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/N116-016__floating_point__precise.adb_8_11_fp_overflow_check___00.smt2 |    0.032s | 19.02MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/K831-006__cmp__max.ads_4_19_postcondition___00.smt2 |    0.033s | 19.684MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/N709-001__tagged_discr__tagged_discr.ads_20_29_discriminant_check___00.smt2 |    0.033s | 19.436MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_b5e7a0_generic_float_tests-T-defqtvc__00.smt2 |    0.033s | 19.444MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_b2d859_generic_float_tests-T-defqtvc__00.smt2 |    0.033s | 19.688MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/N709-001__tagged_discr__tagged_discr.adb_40_8_discriminant_check___00.smt2 |    0.033s | 20.36MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M603-018__float__testfloat.adb_44_19_assert___00.smt2 |    0.033s | 19.304MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_235444_generic_float_tests-T-defqtvc__00.smt2 |    0.034s | 20.7MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O205-003__dynamic_float__test_dynamic_property.adb_52_19_assert___00.smt2 |    0.034s | 19.532MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O205-003__dynamic_float__test_dynamic_property.adb_47_15_range_check___00.smt2 |    0.034s | 22.76MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PC05-013__interval_overflow__mult.adb_10_29_overflow_check___00.smt2 |    0.034s | 19.168MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_9b3454_generic_float_tests-T-defqtvc__00.smt2 |    0.034s | 28.348MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O224-020__constant_aggr__package_1.adb_12_29_fp_overflow_check___00.smt2 |    0.034s | 22.592MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P405-006__arithmetic_from_dafny__div_lemmas.adb_60_4_precondition___00.smt2 |    0.034s | 19.528MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/KC20-033__in_range__p.adb_49_19_precondition___00.smt2 |    0.034s | 19.004MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M422-023__from_int__sgs.adb_13_22_assert___00.smt2 |    0.034s | 20.028MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/KC20-032__succ_pred__p.adb_50_38_overflow_check___00.smt2 |    0.035s | 19.044MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/R123-048__tasks__psu_monitoring.ads_92_70_contract_case___00.smt2 |    0.035s | 19.344MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_db64dc_generic_float_tests-T-defqtvc__00.smt2 |    0.035s | 21.564MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M603-018__float__testfloat.adb_7_25_division_check___00.smt2 |    0.035s | 19.064MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/N709-001__tagged_discr__tagged_discr.ads_59_14_postcondition___00.smt2 |    0.035s | 20.504MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O205-003__dynamic_float__test_dynamic_property.adb_60_22_range_check___01.smt2 |    0.035s | 21.068MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/K720-019__floats__pack.adb_10_42_precondition___00.smt2 |    0.035s | 19.032MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/NC05-005__float_division__pi_euler_2.adb_15_33_loop_invariant_init2___00.smt2 |    0.035s | 19.256MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M122-006__assign2__p.adb_14_9_discriminant_check___00.smt2 |    0.035s | 19.02MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/R123-048__tasks__psu_monitoring.ads_92_7_disjoint_contract_cases___00.smt2 |    0.035s | 20.06MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/N116-016__floating_point__precise.adb_11_19_assert___00.smt2 |    0.035s | 19.528MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/S320-040__flow_blocking__a-tiflio.ads_78_8_p.adb_28_7_precondition___00.smt2 |    0.036s | 19.548MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_219_14_precondition___00.smt2 |    0.036s | 20.2MiB| sat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/MC17-036__gnatVa__protectedfloat.adb_20_21_division_check___00.smt2 |    0.036s | 27.616MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/L402-004__exp__p.adb_7_14_overflow_check___00.smt2 |    0.036s | 19.004MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_1167_52_precondition___00.smt2 |    0.036s | 20.3MiB| sat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O512-022__number_theory__number_theory.adb_18_17_range_check___00.smt2 |    0.036s | 19.028MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/N709-001__tagged_discr__tagged_discr.ads_41_14_postcondition___00.smt2 |    0.036s | 20.128MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O512-022__number_theory__number_theory.ads_23_43_division_check___00.smt2 |    0.036s | 19.4MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P315-010__float__call_sample2.adb_23_7_call_sample2.adb_27_4_precondition___00.smt2 |    0.036s | 19.264MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/N709-001__tagged_discr__classwide.ads_71_14_postcondition___00.smt2 |    0.037s | 19.928MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/N116-016__floating_point__precise.adb_9_19_assert___00.smt2 |    0.037s | 19.228MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O205-003__dynamic_float__test_dynamic_property.adb_22_20_range_check___00.smt2 |    0.037s | 23.004MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__smoothing.adb_46_22_assert___00.smt2 |    0.037s | 19.0MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M603-018__float__testfloat.adb_50_4_precondition___00.smt2 |    0.037s | 19.156MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/N703-010__float_conversion__foo.adb_13_15_range_check___00.smt2 |    0.037s | 20.508MiB| sat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/K720-019__floats__pack.ads_15_19_postcondition___00.smt2 |    0.038s | 19.348MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_1d4733_generic_float_tests-T-defqtvc__00.smt2 |    0.038s | 19.316MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O401-034__float_pred__safety_pack.adb_69_17_predicate_check___00.smt2 |    0.038s | 19.012MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/N313-022__float_range__fr.adb_34_14_division_check___00.smt2 |    0.038s | 19.1MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M422-023__from_int__sgs.adb_21_22_assert___00.smt2 |    0.038s | 19.18MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/TU__depends_legal__depends_legal_2.adb_43_15_discriminant_check___00.smt2 |    0.038s | 19.78MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/K719-019__flight_mgr__flight_manager.ads_10_30_fp_overflow_check___00.smt2 |    0.038s | 19.524MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_ffe5a5_generic_float_tests-T-defqtvc__00.smt2 |    0.038s | 27.976MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M603-018__float__testfloat.adb_36_19_assert___00.smt2 |    0.038s | 19.12MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_5fa6e1_generic_float_tests-T-defqtvc__00.smt2 |    0.038s | 19.576MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P615-019__silver__overflow_check.adb_31_32_division_check___00.smt2 |    0.039s | 19.264MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_1176_47_precondition___00.smt2 |    0.039s | 20.42MiB| sat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/Q424-012__succ_floats_copy_z3__succ_floats.adb_20_34_overflow_check___00.smt2 |    0.039s | 18.996MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_5dc342_generic_float_tests-T-defqtvc__00.smt2 |    0.039s | 29.08MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M603-018__float__testfloat.adb_38_19_assert___00.smt2 |    0.039s | 19.26MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M422-023__from_int__sgs.adb_9_22_assert___00.smt2 |    0.039s | 19.776MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_8f1e69_generic_float_tests-T-defqtvc__00.smt2 |    0.039s | 20.368MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PB02-004__inherited_sub__main.adb_9_24_range_check___00.smt2 |    0.039s | 19.24MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_752865_generic_float_tests-T-defqtvc__00.smt2 |    0.040s | 21.584MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_01f2bc_generic_float_tests-T-defqtvc__00.smt2 |    0.040s | 19.844MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/N709-001__tagged_discr__tagged_discr.adb_17_14_discriminant_check___00.smt2 |    0.040s | 19.328MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/NC04-023__float_conversion__type_conversion.ads_9_21_postcondition___00.smt2 |    0.040s | 29.224MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O205-003__dynamic_float__test_dynamic_property.adb_55_19_assert___00.smt2 |    0.040s | 20.592MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__errorexamplefloat.adb_29_22_assert___00.smt2 |    0.040s | 19.12MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O416-002__dyn_pred_rte__pred.adb_30_22_discriminant_check___00.smt2 |    0.040s | 19.54MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M603-018__float__testfloat.adb_49_4_precondition___00.smt2 |    0.040s | 19.276MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_2b1e11_generic_float_tests-T-defqtvc__00.smt2 |    0.040s | 24.176MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/Q607-007__floats__normalize.adb_134_22_assert___00.smt2 |    0.041s | 18.976MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__assertionproperties.adb_43_22_assert___00.smt2 |    0.041s | 21.06MiB| sat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P615-019__silver__division_by_zero.adb_29_14_division_check___00.smt2 |    0.041s | 19.756MiB| sat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M422-023__from_int__sgs.adb_18_13_range_check___00.smt2 |    0.041s | 20.368MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O401-034__float_pred__safety_pack.ads_15_62_contract_case___00.smt2 |    0.041s | 24.292MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/Q424-012__succ_floats_copy_z3__succ_floats.adb_11_19_assert___00.smt2 |    0.041s | 20.008MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M422-023__from_int__sgs.adb_19_22_assert___00.smt2 |    0.041s | 19.172MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O401-034__float_pred__safety_pack.ads_29_16_postcondition___00.smt2 |    0.041s | 19.64MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P405-006__arithmetic_from_dafny__div_lemmas.adb_53_4_precondition___00.smt2 |    0.041s | 19.02MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_0fa4d6_generic_float_tests-T-defqtvc__00.smt2 |    0.042s | 19.668MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_c12b1d_generic_float_tests-T-defqtvc__00.smt2 |    0.042s | 20.04MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_6ab862_generic_float_tests-T-defqtvc__00.smt2 |    0.042s | 19.792MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_e5185b_generic_float_tests-T-defqtvc__00.smt2 |    0.042s | 24.52MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_cfc699_generic_float_tests-T-defqtvc__00.smt2 |    0.042s | 21.752MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M603-018__float__testfloat.adb_28_22_assert___00.smt2 |    0.042s | 19.232MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/KC22-015__succ_overflow__p.adb_45_31_overflow_check___00.smt2 |    0.043s | 19.94MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/MC13-026__float_div__protectedfloat.adb_15_24_division_check___00.smt2 |    0.043s | 19.608MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O205-003__dynamic_float__test_dynamic_property.adb_4_37_range_check___00.smt2 |    0.043s | 18.996MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_0b989e_generic_float_tests-T-defqtvc__00.smt2 |    0.043s | 20.224MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_b5cd90_generic_float_tests-T-defqtvc__00.smt2 |    0.043s | 19.708MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O205-003__dynamic_float__test_dynamic_property.adb_36_17_range_check___00.smt2 |    0.043s | 20.248MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P912-012__float_zero__run.ads_19_19_postcondition___00.smt2 |    0.043s | 22.524MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PA21-002__floatdiv__basic_contracts.ads_22_20_postcondition___00.smt2 |    0.043s | 19.028MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/N313-022__float_range__fr.adb_33_14_division_check___00.smt2 |    0.043s | 19.78MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P912-012__float_zero__run.ads_29_19_postcondition___00.smt2 |    0.044s | 19.152MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/N122-021__succ_floats__succ_floats.adb_5_19_assert___00.smt2 |    0.044s | 19.78MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P405-006__arithmetic_from_dafny__div_lemmas.adb_60_15_range_check___00.smt2 |    0.044s | 19.068MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_988971_generic_float_tests-T-defqtvc__00.smt2 |    0.044s | 24.396MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PC05-013__interval_overflow__mult.adb_10_42_overflow_check___00.smt2 |    0.044s | 20.332MiB| sat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O430-013__return_unchecked_conversion__prover_crash.adb_14_23_range_check___00.smt2 |    0.044s | 20.4MiB| sat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P912-012__float_zero_numerics__numerics.ads_16_100_postcondition___00.smt2 |    0.044s | 19.72MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/MC13-026__float_div__protectedfloat.adb_18_21_division_check___00.smt2 |    0.044s | 27.68MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_168f5d_generic_float_tests-T-defqtvc__00.smt2 |    0.044s | 20.272MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/OB16-021__float_range__test_float.adb_5_19_assert___00.smt2 |    0.044s | 20.476MiB| sat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M122-006__assign__p.adb_14_9_discriminant_check___00.smt2 |    0.044s | 20.224MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/N709-018__spurious_discr__useless_discr.adb_19_5_discriminant_check___00.smt2 |    0.044s | 19.784MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_1a226b_generic_float_tests-T-defqtvc__00.smt2 |    0.045s | 19.6MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_b33c2b_generic_float_tests-T-defqtvc__00.smt2 |    0.045s | 20.256MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_e9287d_homothetical-T-defqtvc__00.smt2 |    0.045s | 24.82MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PB23-014__float_monotonicity__mul.adb_10_16_postcondition___00.smt2 |    0.045s | 18.976MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/N116-016__floating_point__precise.adb_6_11_fp_overflow_check___00.smt2 |    0.045s | 19.008MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/NC05-005__float_division__pi_euler_2.adb_17_35_division_check2___00.smt2 |    0.045s | 20.528MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/K720-019__floats__pack.adb_10_19_precondition___00.smt2 |    0.045s | 19.28MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PC05-013__interval_overflow__mult.adb_10_24_overflow_check___00.smt2 |    0.045s | 20.04MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_1d5454_generic_float_tests-T-defqtvc__00.smt2 |    0.045s | 20.12MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P315-010__float__call_sample.adb_6_4_precondition___00.smt2 |    0.045s | 19.5MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P310-021__proof_float_remainder__foo.adb_16_17_division_check___00.smt2 |    0.045s | 19.832MiB| sat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O205-003__dynamic_float__test_dynamic_property.adb_61_19_assert___00.smt2 |    0.045s | 20.86MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P912-012__float_zero_numerics__numerics.ads_13_100_postcondition___00.smt2 |    0.045s | 19.492MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/N122-021__succ_floats__succ_floats.adb_28_22_assert___00.smt2 |    0.045s | 20.832MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/N116-016__floating_point__precise.adb_10_11_fp_overflow_check___00.smt2 |    0.046s | 19.004MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_b9e22d_generic_float_tests-T-defqtvc__00.smt2 |    0.046s | 27.48MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_9be82f_generic_float_tests-T-defqtvc__00.smt2 |    0.046s | 24.636MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P912-012__float_zero_numerics__run.ads_30_19_postcondition___00.smt2 |    0.046s | 19.068MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PB16-052__float_invariant__attempt_2.adb_16_18_overflow_check___00.smt2 |    0.046s | 20.356MiB| sat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__assertionproperties.adb_36_22_assert___00.smt2 |    0.046s | 19.044MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_e1269d_generic_float_tests-T-defqtvc__00.smt2 |    0.047s | 19.76MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_a34115_generic_float_tests-T-defqtvc__00.smt2 |    0.047s | 24.544MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_189_47_precondition___00.smt2 |    0.047s | 20.52MiB| sat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O205-003__dynamic_float__test_dynamic_property.adb_24_18_range_check___00.smt2 |    0.047s | 22.612MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/N709-001__tagged_discr__classwide.ads_40_14_postcondition___00.smt2 |    0.047s | 20.048MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/KC20-032__succ_pred__p.adb_50_31_overflow_check___00.smt2 |    0.047s | 20.084MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_283cca_generic_float_tests-T-defqtvc__00.smt2 |    0.047s | 22.648MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_1158_47_precondition___00.smt2 |    0.048s | 20.504MiB| sat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M603-018__float__testfloat.adb_43_19_assert___00.smt2 |    0.048s | 19.292MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O401-034__float_pred__safety_pack.adb_43_21_fp_overflow_check___00.smt2 |    0.048s | 29.544MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_b5915a_generic_float_tests-T-defqtvc__00.smt2 |    0.048s | 20.048MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_f9f0b1_generic_interval_tests-T-defqtvc__00.smt2 |    0.048s | 22.872MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_e70870_generic_float_tests-T-defqtvc__00.smt2 |    0.049s | 21.58MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__smoothing.adb_54_22_assert___00.smt2 |    0.049s | 26.02MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_dc2c61_generic_interval_tests-T-defqtvc__00.smt2 |    0.049s | 22.856MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/N709-001__tagged_discr__tagged_discr.adb_15_14_discriminant_check___00.smt2 |    0.049s | 19.804MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_72685b_generic_float_tests-T-defqtvc__00.smt2 |    0.049s | 24.632MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O401-034__float_pred__safety_pack.ads_60_39_contract_case___00.smt2 |    0.049s | 20.064MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PB16-052__float_invariant__attempt_3.adb_63_40_overflow_check___00.smt2 |    0.049s | 19.28MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/N709-001__tagged_discr__classwide.ads_45_14_postcondition___00.smt2 |    0.050s | 20.04MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P912-012__float_zero_numerics__numerics.ads_19_108_postcondition___00.smt2 |    0.050s | 19.776MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/N122-021__succ_floats__succ_floats.adb_22_31_overflow_check___00.smt2 |    0.050s | 20.584MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_50886f_generic_interval_tests-T-defqtvc__00.smt2 |    0.050s | 20.78MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_b06d51_generic_interval_tests-T-defqtvc__00.smt2 |    0.050s | 21.644MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_99634e_generic_interval_tests-T-defqtvc__00.smt2 |    0.050s | 25.792MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_275c6e_generic_float_tests-T-defqtvc__00.smt2 |    0.051s | 20.048MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_492bd7_generic_float_tests-T-defqtvc__00.smt2 |    0.051s | 21.716MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/N709-001__tagged_discr__tagged_discr.ads_44_14_postcondition___00.smt2 |    0.052s | 20.296MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/N709-001__tagged_discr__tagged_discr.adb_23_8_discriminant_check___00.smt2 |    0.052s | 20.008MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/N116-016__floating_point__test_float.adb_17_19_assert___00.smt2 |    0.052s | 19.748MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O416-002__dyn_pred_rte__pred.adb_31_27_discriminant_check___00.smt2 |    0.052s | 19.156MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_de2268_generic_float_tests-T-defqtvc__00.smt2 |    0.052s | 21.932MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/K719-019__flight_mgr__flight_manager.adb_13_24_fp_overflow_check___00.smt2 |    0.053s | 25.304MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/N709-001__tagged_discr__tagged_discr.ads_24_19_postcondition___00.smt2 |    0.053s | 20.8MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P405-006__arithmetic_from_dafny__div_lemmas.adb_62_4_precondition___00.smt2 |    0.053s | 19.116MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/S603-051__dimensions__image_golf_hole.adb_19_18_image_golf_hole.adb_32_10_predicate_check___00.smt2 |    0.053s | 20.768MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PC05-013__interval_overflow__mult.adb_11_35_overflow_check___00.smt2 |    0.054s | 19.028MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_53b78c_generic_interval_tests-T-defqtvc__00.smt2 |    0.054s | 23.684MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_3b4c73_generic_float_tests-T-defqtvc__00.smt2 |    0.054s | 28.192MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_3ce9bc_generic_interval_tests-T-defqtvc__00.smt2 |    0.054s | 20.744MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O715-033__level1__hard_stuff.adb_6_14_fp_overflow_check___00.smt2 |    0.054s | 21.928MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/N709-001__tagged_discr__classwide.ads_106_14_postcondition___00.smt2 |    0.055s | 20.232MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_bb54cc_generic_float_tests-T-defqtvc__00.smt2 |    0.055s | 23.696MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_d25f13_generic_float_tests-T-defqtvc__00.smt2 |    0.055s | 21.808MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/Q424-012__succ_floats_copy_z3__succ_floats.adb_8_19_assert___00.smt2 |    0.055s | 22.244MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/K720-019__floats__pack.adb_10_14_precondition___00.smt2 |    0.056s | 23.184MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P615-019__silver__range_check.adb_33_12_range_check___00.smt2 |    0.056s | 19.888MiB| sat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_4b6267_generic_interval_tests-T-defqtvc__00.smt2 |    0.057s | 23.112MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/R123-048__tasks__psu_monitoring.adb_106_75_division_check___00.smt2 |    0.057s | 26.728MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O715-033__level2__hard_stuff.adb_7_22_assert___00.smt2 |    0.057s | 21.948MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_f1b856_generic_interval_tests-T-defqtvc__00.smt2 |    0.057s | 27.376MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_3eabed_generic_float_tests-T-defqtvc__00.smt2 |    0.058s | 21.664MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/N122-021__succ_floats__succ_floats.adb_7_19_assert___00.smt2 |    0.058s | 20.256MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O312-037__flow_pure_subprograms__call.adb_22_51_precondition___00.smt2 |    0.059s | 20.392MiB| sat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_218eda_generic_float_tests-T-defqtvc__00.smt2 |    0.059s | 24.284MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P912-012__float_zero_numerics__run.ads_20_19_postcondition___00.smt2 |    0.059s | 22.332MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/Q607-007__floats__normalize.adb_161_13_precondition___00.smt2 |    0.060s | 28.088MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/QA11-003__itp_example__test.adb_56_17_postcondition___00.smt2 |    0.060s | 29.388MiB| sat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/N709-001__tagged_discr__tagged_discr.ads_27_14_postcondition___00.smt2 |    0.060s | 20.836MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O205-003__dynamic_float__test_dynamic_property.adb_58_22_assert___00.smt2 |    0.061s | 20.868MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_8222b5_generic_float_tests-T-defqtvc__00.smt2 |    0.061s | 24.668MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_14d53b_generic_interval_tests-T-defqtvc__00.smt2 |    0.063s | 28.392MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/Q607-007__floats__normalize.adb_132_13_precondition___00.smt2 |    0.063s | 27.952MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/QA11-003__itp_example__test.adb_60_14_fp_overflow_check___00.smt2 |    0.064s | 29.244MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_e30a85_generic_float_tests-T-defqtvc__00.smt2 |    0.064s | 24.124MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/N709-001__tagged_discr__tagged_discr.ads_62_14_postcondition___00.smt2 |    0.064s | 21.136MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_83ffdb_generic_float_tests-T-defqtvc__00.smt2 |    0.065s | 24.684MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_a0c4ad_generic_float_tests-T-defqtvc__00.smt2 |    0.066s | 24.76MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_6a7512_generic_float_tests-T-defqtvc__00.smt2 |    0.067s | 24.188MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_a83df9_generic_interval_tests-T-defqtvc__00.smt2 |    0.067s | 22.872MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/L402-021__float__p.adb_8_20_fp_overflow_check___00.smt2 |    0.068s | 31.356MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O401-034__float_pred__safety_pack.adb_41_21_fp_overflow_check___00.smt2 |    0.068s | 29.684MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_c786f0_generic_interval_tests-T-defqtvc__00.smt2 |    0.069s | 22.836MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_cc6bc3_generic_interval_tests-T-defqtvc__00.smt2 |    0.071s | 28.22MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_4aaffb_generic_float_tests-T-defqtvc__00.smt2 |    0.071s | 20.784MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O205-003__dynamic_float__test_dynamic_property.adb_10_15_range_check___00.smt2 |    0.072s | 19.144MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/K720-019__floats__pack.ads_18_19_postcondition___00.smt2 |    0.073s | 25.424MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_f5b2b3_generic_interval_tests-T-defqtvc__00.smt2 |    0.073s | 22.736MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O224-020__constant_aggr__package_1.adb_11_29_fp_overflow_check___00.smt2 |    0.075s | 23.336MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_7c2c0b_generic_float_tests-T-defqtvc__00.smt2 |    0.076s | 24.492MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_2cfc0a_generic_interval_tests-T-defqtvc__00.smt2 |    0.077s | 22.68MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_e982c9_generic_interval_tests-T-defqtvc__00.smt2 |    0.077s | 25.896MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O205-003__dynamic_float__test_dynamic_property.adb_21_15_fp_overflow_check___00.smt2 |    0.077s | 23.192MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_c522c9_generic_interval_tests-T-defqtvc__00.smt2 |    0.078s | 21.84MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_e2dbad_generic_interval_tests-T-defqtvc__00.smt2 |    0.079s | 26.02MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_6cb1b4_generic_interval_tests-T-defqtvc__00.smt2 |    0.079s | 26.204MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O205-003__dynamic_float__test_dynamic_property.adb_44_12_fp_overflow_check___00.smt2 |    0.080s | 23.108MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O715-033__level1__hard_stuff.adb_17_22_assert___00.smt2 |    0.080s | 30.004MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_904c31_generic_float_tests-T-defqtvc__00.smt2 |    0.083s | 20.904MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_c1c2bc_generic_float_tests-T-defqtvc__00.smt2 |    0.084s | 24.372MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_b64636_generic_float_tests-T-defqtvc__00.smt2 |    0.084s | 28.428MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_8a6cb4_generic_float_tests-T-defqtvc__00.smt2 |    0.084s | 24.22MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_ddd17d_generic_float_tests-T-defqtvc__00.smt2 |    0.084s | 24.508MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/S427-002__inline_dim__challenges.adb_12_48_challenges.adb_24_14_challenges.adb_33_29_challenges.adb_38_10_range_check___00.smt2 |    0.085s | 26.784MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_f00b23_generic_interval_tests-T-defqtvc__00.smt2 |    0.085s | 23.008MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_c6aff8_generic_float_tests-T-defqtvc__00.smt2 |    0.086s | 20.764MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_0354a0_generic_float_tests-T-defqtvc__00.smt2 |    0.086s | 20.848MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_014768_generic_interval_tests-T-defqtvc__00.smt2 |    0.086s | 26.352MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/L402-021__float__p.adb_10_20_fp_overflow_check___00.smt2 |    0.087s | 33.816MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/Q607-007__floats__normalize.adb_103_13_precondition___00.smt2 |    0.087s | 27.908MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_f38e09_generic_float_tests-T-defqtvc__00.smt2 |    0.088s | 24.636MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_475713_generic_interval_tests-T-defqtvc__00.smt2 |    0.088s | 32.48MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/N116-016__floating_point__test_18.adb_7_12_fp_overflow_check___00.smt2 |    0.090s | 22.604MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O401-034__float_pred__safety_pack.ads_20_54_fp_overflow_check___00.smt2 |    0.090s | 25.104MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_a2c713_generic_interval_tests-T-defqtvc__00.smt2 |    0.090s | 22.98MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O205-003__dynamic_float__test_dynamic_property.adb_15_17_postcondition___00.smt2 |    0.090s | 23.416MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_658b29_generic_interval_tests-T-defqtvc__00.smt2 |    0.090s | 26.084MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/OC30-005__crash.adb_10_18_fp_overflow_check___00.smt2 |    0.092s | 22.86MiB| sat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_d30160_generic_interval_tests-T-defqtvc__00.smt2 |    0.093s | 22.772MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_441ad2_generic_float_tests-T-defqtvc__00.smt2 |    0.097s | 30.348MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M919-035__floating_point__dynamic_float.adb_10_25_assert___00.smt2 |    0.097s | 29.744MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_79bf65_generic_interval_tests-T-defqtvc__00.smt2 |    0.097s | 22.764MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P909-014__numerics__numerics-algo.adb_20_17_precondition___00.smt2 |    0.098s | 36.272MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PA21-002__floatdiv__basic_contracts.ads_29_20_postcondition___00.smt2 |    0.099s | 36.332MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O205-003__dynamic_float__test_dynamic_property.adb_45_17_range_check___00.smt2 |    0.099s | 23.544MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_e7ad50_generic_interval_tests-T-defqtvc__00.smt2 |    0.100s | 26.608MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/NC05-005__float_division__pi_euler.adb_13_23_division_check2___00.smt2 |    0.100s | 34.824MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_3176a4_generic_interval_tests-T-defqtvc__00.smt2 |    0.101s | 26.048MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/L402-021__float__p.adb_8_19_assert___00.smt2 |    0.106s | 31.596MiB| sat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/Q607-007__floats__normalize.adb_15_12_postcondition___00.smt2 |    0.116s | 28.704MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/S427-002__inline_dim__challenges.adb_13_48_challenges.adb_24_14_challenges.adb_33_29_challenges.adb_38_10_range_check___00.smt2 |    0.118s | 32.632MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O715-033__level2__hard_stuff.adb_12_22_assert___00.smt2 |    0.119s | 24.608MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M603-018__float__testfloat.adb_21_22_assert___00.smt2 |    0.119s | 35.06MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_f4d109_generic_interval_tests-T-defqtvc__00.smt2 |    0.119s | 26.508MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_29fea4_generic_interval_tests-T-defqtvc__00.smt2 |    0.123s | 26.46MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_22e79d_generic_interval_tests-T-defqtvc__00.smt2 |    0.123s | 26.504MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_90d7ec_generic_interval_tests-T-defqtvc__00.smt2 |    0.127s | 37.996MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_995c50_generic_float_tests-T-defqtvc__00.smt2 |    0.128s | 29.764MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_b94afa_generic_interval_tests-T-defqtvc__00.smt2 |    0.132s | 23.3MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_b9b5ec_generic_interval_tests-T-defqtvc__00.smt2 |    0.133s | 23.08MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_f4b86f_generic_interval_tests-T-defqtvc__00.smt2 |    0.134s | 38.092MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O512-022__number_theory__number_theory.ads_20_32_range_check___00.smt2 |    0.136s | 38.808MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/N116-016__floating_point__test_float.adb_11_14_range_check___00.smt2 |    0.144s | 23.072MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_683e07_generic_float_tests-T-defqtvc__00.smt2 |    0.149s | 30.32MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/proofinuse__ce__counter_examples.adb_8_38_fp_overflow_check___00.smt2 |    0.158s | 23.216MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_1253ee_generic_interval_tests-T-defqtvc__00.smt2 |    0.160s | 23.08MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/L402-021__float__p.adb_7_19_assert___00.smt2 |    0.161s | 29.852MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_726911_generic_float_tests-T-defqtvc__00.smt2 |    0.162s | 29.796MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O401-034__float_pred__safety_pack.ads_18_54_fp_overflow_check___00.smt2 |    0.163s | 24.956MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_f7e0e0_generic_interval_tests-T-defqtvc__00.smt2 |    0.166s | 32.0MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_394d11_generic_interval_tests-T-defqtvc__00.smt2 |    0.168s | 26.488MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_204f1e_generic_interval_tests-T-defqtvc__00.smt2 |    0.168s | 26.764MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/Q424-012__succ_floats_copy_z3__succ_floats.adb_6_19_assert___00.smt2 |    0.170s | 24.004MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_8f72d3_generic_float_tests-T-defqtvc__00.smt2 |    0.173s | 29.936MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O715-033__level3__hard_stuff.adb_21_22_assert___00.smt2 |    0.174s | 49.632MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_028c17_homothetical-T-defqtvc__00.smt2 |    0.175s | 58.864MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/N313-022__float_range__fr.adb_28_17_range_check___00.smt2 |    0.179s | 24.208MiB| sat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M603-018__float__testfloat.adb_26_22_assert___00.smt2 |    0.180s | 37.4MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_6f649f_generic_float_tests-T-defqtvc__00.smt2 |    0.182s | 29.86MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PB16-052__float_invariant__attempt_1.adb_30_32_range_check___00.smt2 |    0.185s | 53.212MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O325-024__abstract_state__stabilizer_pack.adb_21_51_fp_overflow_check___00.smt2 |    0.186s | 23.652MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M603-018__float__testfloat.adb_29_22_assert___00.smt2 |    0.190s | 38.848MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M603-018__float__testfloat.adb_24_22_assert___00.smt2 |    0.191s | 36.976MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O220-024__floats__test_pack.ads_14_42_fp_overflow_check___00.smt2 |    0.195s | 23.58MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PA21-002__floatdiv__basic_contracts.ads_15_10_postcondition___00.smt2 |    0.195s | 56.98MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O715-033__level3__hard_stuff.adb_11_14_fp_overflow_check___00.smt2 |    0.198s | 24.7MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_336b10_generic_interval_tests-T-defqtvc__00.smt2 |    0.198s | 26.816MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_637_21_precondition___00.smt2 |    0.199s | 26.74MiB| sat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_57b4e3_generic_float_tests-T-defqtvc__00.smt2 |    0.201s | 25.34MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PB16-052__float_invariant__attempt_2.adb_32_32_range_check___00.smt2 |    0.203s | 53.236MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_3f27e3_generic_float_tests-T-defqtvc__00.smt2 |    0.208s | 30.224MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_fd3c3b_generic_interval_tests-T-defqtvc__00.smt2 |    0.224s | 32.16MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_6f02ee_generic_float_tests-T-defqtvc__00.smt2 |    0.225s | 26.456MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_bce863_generic_float_tests-T-defqtvc__00.smt2 |    0.241s | 22.08MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_04ae02_generic_float_tests-T-defqtvc__00.smt2 |    0.245s | 30.328MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O220-024__floats__test_pack.ads_12_43_fp_overflow_check___00.smt2 |    0.246s | 23.28MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/N121-026__nonlinear__nonlinear.adb_9_20_fp_overflow_check___00.smt2 |    0.253s | 23.228MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/Q906-010__float_volatile__copy_values.adb_8_25_fp_overflow_check___00.smt2 |    0.255s | 23.328MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/Q607-007__floats__normalize.adb_45_22_range_check___00.smt2 |    0.259s | 31.016MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/K719-019__flight_mgr__flight_manager.adb_19_21_fp_overflow_check___00.smt2 |    0.260s | 26.644MiB| sat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/L402-021__float__p.adb_9_19_assert___00.smt2 |    0.294s | 31.912MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/N116-016__floating_point__test_18.adb_4_16_postcondition___00.smt2 |    0.295s | 26.764MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_b1475f_generic_interval_tests-T-defqtvc__00.smt2 |    0.296s | 26.832MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O401-034__float_pred__safety_pack.ads_19_62_contract_case___00.smt2 |    0.299s | 25.848MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M603-018__float__testfloat.adb_22_22_assert___00.smt2 |    0.304s | 38.64MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PC07-014__float_conversion__simple_trajectory.adb_19_22_assert___00.smt2 |    0.313s | 78.008MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_212f49_generic_interval_tests-T-defqtvc__00.smt2 |    0.316s | 27.06MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PB16-052__float_invariant__attempt_3.adb_54_22_assert___00.smt2 |    0.343s | 82.856MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PC07-014__float_conversion__simple_trajectory.adb_24_22_assert___00.smt2 |    0.344s | 82.888MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O401-034__float_pred__safety_pack.ads_17_62_contract_case___00.smt2 |    0.351s | 25.768MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/L402-021__float__p.adb_10_19_assert___00.smt2 |    0.358s | 33.952MiB| sat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M603-018__float__testfloat.adb_27_22_assert___00.smt2 |    0.359s | 43.436MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/L402-004__exp__p.adb_8_14_fp_overflow_check___00.smt2 |    0.371s | 29.608MiB| sat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_9cfb3a_generic_interval_tests-T-defqtvc__00.smt2 |    0.400s | 26.912MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/NC06-004__init__shapes5.adb_20_36_range_check___00.smt2 |    0.426s | 27.7MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M603-018__float__testfloat.adb_32_22_assert___00.smt2 |    0.430s | 43.828MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_4110a0_generic_interval_tests-T-defqtvc__00.smt2 |    0.438s | 26.576MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P912-012__float_zero_numerics__run.ads_25_19_postcondition___00.smt2 |    0.445s | 23.712MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/L402-021__float__p.adb_12_19_assert___00.smt2 |    0.456s | 33.96MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/N116-016__floating_point__test_18.adb_7_19_fp_overflow_check___00.smt2 |    0.460s | 26.668MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P912-012__float_zero__run.ads_14_19_postcondition___00.smt2 |    0.474s | 24.112MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PB16-052__float_invariant__attempt_4.adb_40_32_range_check___00.smt2 |    0.475s | 135.0MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/S118-010__zeros_counterex__math.adb_16_22_assert___00.smt2 |    0.481s | 31.704MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O325-024__abstract_state__stabilizer_pack.adb_23_26_fp_overflow_check___00.smt2 |    0.493s | 42.628MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/S427-002__inline_dim__challenges.adb_8_37_challenges.adb_15_14_challenges.adb_24_14_challenges.adb_33_29_challenges.adb_38_10_precondition___00.smt2 |    0.505s | 89.932MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__biaseddivide.ads_19_14_postcondition___00.smt2 |    0.512s | 149.0MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__biaseddivide.ads_19_20_division_check___00.smt2 |    0.515s | 149.0MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P912-012__float_zero__run.ads_24_19_postcondition___00.smt2 |    0.516s | 23.624MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P912-012__float_zero_numerics__run.ads_15_19_postcondition___00.smt2 |    0.516s | 23.74MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P405-006__arithmetic_from_dafny__div_lemmas.adb_45_16_fp_overflow_check___00.smt2 |    0.523s | 38.164MiB| sat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/R123-048__tasks__psu_monitoring.adb_91_41_fp_overflow_check___00.smt2 |    0.557s | 24.112MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/R123-048__tasks__psu_monitoring.adb_69_41_fp_overflow_check___00.smt2 |    0.586s | 24.188MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/N313-022__float_range__fr.adb_22_20_range_check___00.smt2 |    0.602s | 28.448MiB| sat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/NC05-005__float_division__pi_euler.adb_11_33_loop_invariant_preserv2___00.smt2 |    0.639s | 159.0MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/L402-021__float__p.adb_11_19_assert___00.smt2 |    0.642s | 33.988MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PB16-052__float_invariant__attempt_3.adb_62_27_overflow_check___00.smt2 |    0.696s | 152.0MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O512-022__number_theory__number_theory.adb_19_38_loop_invariant_preserv___00.smt2 |    0.705s | 143.0MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/L402-004__exp__p.adb_5_14_fp_overflow_check___00.smt2 |    0.717s | 27.008MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/N313-022__float_range__fr.adb_15_24_range_check___00.smt2 |    0.719s | 30.732MiB| sat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P315-010__float__original_sample.ads_59_17_postcondition___00.smt2 |    0.755s | 27.068MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_e5004c_generic_interval_tests-T-defqtvc__00.smt2 |    0.757s | 63.964MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/K719-019__flight_mgr__flight_manager.adb_12_11_postcondition___00.smt2 |    0.813s | 35.824MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O312-037__flow_pure_subprograms__call.adb_22_51_range_check___00.smt2 |    0.823s | 26.564MiB| sat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P315-010__float__sample.ads_57_17_postcondition___00.smt2 |    0.832s | 27.156MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/S118-010__zeros_counterex__math.adb_14_22_assert___00.smt2 |    0.867s | 32.152MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/proofinuse__ce__counter_examples.adb_9_16_fp_overflow_check___00.smt2 |    0.922s | 26.7MiB| sat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/S118-010__zeros_counterex__math.adb_15_22_assert___00.smt2 |    0.945s | 32.472MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PC07-014__float_conversion__simple_trajectory.adb_30_57_range_check___00.smt2 |    0.967s | 248.0MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PC07-014__float_conversion__simple_trajectory.adb_31_47_range_check___00.smt2 |    1.007s | 250.0MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/S118-010__zeros_counterex__math.adb_22_22_assert___00.smt2 |    1.031s | 37.72MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PC07-014__float_conversion__simple_trajectory.adb_36_22_assert___00.smt2 |    1.039s | 251.0MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_457_42_fp_overflow_check___00.smt2 |    1.093s | 80.3MiB| sat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_336_42_fp_overflow_check___00.smt2 |    1.115s | 80.392MiB| sat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/S118-010__zeros_counterex__math.adb_21_22_assert___00.smt2 |    1.125s | 38.372MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/Q607-007__floats__normalize.adb_150_13_precondition___00.smt2 |    1.125s | 29.548MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/Q607-007__floats__normalize.adb_142_14_precondition___00.smt2 |    1.126s | 29.364MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/Q607-007__floats__normalize.adb_92_13_precondition___00.smt2 |    1.148s | 29.416MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/Q607-007__floats__normalize.adb_113_14_precondition___00.smt2 |    1.161s | 29.372MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O512-022__number_theory__number_theory.ads_28_19_postcondition___00.smt2 |    1.177s | 148.0MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/Q607-007__floats__normalize.adb_121_13_precondition___00.smt2 |    1.184s | 29.56MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/Q607-007__floats__normalize.adb_84_14_precondition___00.smt2 |    1.199s | 29.392MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_facb24_generic_interval_tests-T-defqtvc__00.smt2 |    1.202s | 35.612MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_b7f9fd_generic_float_tests-T-defqtvc__00.smt2 |    1.203s | 31.756MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_827c21_generic_float_tests-T-defqtvc__00.smt2 |    1.255s | 25.844MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/NC05-005__float_division__pi_euler_2.adb_15_33_loop_invariant_preserv2___00.smt2 |    1.275s | 283.0MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/NC06-004__init__shapes5.adb_23_17_range_check___00.smt2 |    1.283s | 34.524MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O826-006__float_exponential__float_expon.adb_10_33_fp_overflow_check___00.smt2 |    1.369s | 89.404MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_637_21_range_check___00.smt2 |    1.395s | 36.364MiB| sat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/Q607-007__floats__normalize.adb_46_22_assert___00.smt2 |    1.425s | 32.244MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/proofinuse__lat_long__lat_long.ads_31_58_fp_overflow_check___00.smt2 |    1.486s | 390.0MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/Q607-007__floats__normalize.adb_35_14_range_check___00.smt2 |    1.490s | 32.292MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/N313-022__float_range__fr.adb_34_14_range_check___00.smt2 |    1.566s | 31.432MiB| sat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_cc80a4_generic_float_tests-T-defqtvc__00.smt2 |    1.572s | 25.988MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_41a5f2_generic_float_tests-T-defqtvc__00.smt2 |    1.702s | 26.388MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PC07-014__float_conversion__simple_trajectory.adb_41_55_range_check___00.smt2 |    1.754s | 344.0MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PC07-014__float_conversion__simple_trajectory.ads_38_19_postcondition___00.smt2 |    1.786s | 347.0MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PC07-014__float_conversion__simple_trajectory.adb_31_22_assert___00.smt2 |    1.805s | 250.0MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PC07-014__float_conversion__simple_trajectory.ads_38_32_range_check___00.smt2 |    1.809s | 346.0MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PC07-014__float_conversion__simple_trajectory.adb_42_46_range_check___00.smt2 |    1.810s | 345.0MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_1194_21_range_check___00.smt2 |    1.814s | 37.516MiB| sat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PA20-061__flow_variable_constant__basic_contracts.adb_10_22_assert___00.smt2 |    1.938s | 29.828MiB| unknown | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/N121-026__nonlinear__nonlinear.adb_10_20_fp_overflow_check___00.smt2 |    1.980s | 30.772MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/Q607-007__floats__normalize.adb_162_22_assert___00.smt2 |    2.016s | 35.492MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/proofinuse__lat_long__lat_long.ads_30_101_fp_overflow_check___00.smt2 |    2.093s | 423.0MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PB16-052__float_invariant__attempt_3.adb_70_22_assert___00.smt2 |    2.095s | 247.0MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_1d2077_generic_interval_tests-T-defqtvc__00.smt2 |    2.134s | 35.42MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_a2c9b8_generic_interval_tests-T-defqtvc__00.smt2 |    2.179s | 35.42MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/N121-026__nonlinear__nonlinear.adb_10_16_fp_overflow_check___00.smt2 |    2.194s | 34.476MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PB16-052__float_invariant__attempt_3.adb_38_19_postcondition___00.smt2 |    2.206s | 485.0MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/Q607-007__floats__normalize.adb_151_14_range_check___00.smt2 |    2.214s | 35.5MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/Q607-007__floats__normalize.adb_104_22_assert___00.smt2 |    2.249s | 36.448MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/Q607-007__floats__normalize.adb_84_14_range_check___00.smt2 |    2.336s | 36.624MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/Q607-007__floats__normalize.adb_55_14_range_check___00.smt2 |    2.373s | 36.628MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/Q607-007__floats__normalize.adb_75_22_assert___00.smt2 |    2.400s | 36.664MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/NC05-005__float_division__pi_euler_2.adb_20_37_fp_overflow_check2___00.smt2 |    2.489s | 288.0MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/NC06-004__init__shapes5.adb_42_34_range_check___00.smt2 |    2.546s | 28.704MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/MC13-026__float_div__protectedfloat.adb_18_21_fp_overflow_check___00.smt2 |    2.560s | 78.064MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/MC17-036__gnatVa__protectedfloat.adb_20_21_fp_overflow_check___00.smt2 |    2.591s | 78.32MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PC07-014__float_conversion__simple_trajectory.adb_26_22_assert___00.smt2 |    2.620s | 93.192MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/Q607-007__floats__normalize.adb_142_14_range_check___00.smt2 |    2.686s | 35.876MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/Q607-007__floats__normalize.adb_34_22_range_check___00.smt2 |    2.722s | 32.456MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_ea0c9f_generic_float_tests-T-defqtvc__00.smt2 |    2.745s | 38.464MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/proofinuse__lat_long__lat_long.ads_29_14_postcondition___00.smt2 |    2.762s | 603.0MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/Q607-007__floats__normalize.adb_113_14_range_check___00.smt2 |    2.857s | 42.232MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_16bd7a_generic_float_tests-T-defqtvc__00.smt2 |    2.862s | 38.608MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O715-033__level1__hard_stuff.adb_16_14_fp_overflow_check___00.smt2 |    2.934s | 32.512MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P615-019__silver__division_by_zero.adb_29_14_fp_overflow_check___00.smt2 |    3.423s | 39.068MiB| sat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/NC06-004__init__shapes5.adb_26_36_range_check___00.smt2 |    3.572s | 42.028MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PB16-052__float_invariant__attempt_3.adb_38_32_range_check___00.smt2 |    3.658s | 682.0MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/Q607-007__floats__normalize.adb_64_14_range_check___00.smt2 |    3.788s | 37.54MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O325-024__abstract_state__stabilizer_pack.adb_21_44_fp_overflow_check___00.smt2 |    3.998s | 33.256MiB| sat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/Q607-007__floats__normalize.adb_93_14_range_check___00.smt2 |    4.147s | 37.472MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/Q607-007__floats__normalize.adb_122_14_range_check___00.smt2 |    4.372s | 42.44MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P405-006__arithmetic_from_dafny__div_lemmas.adb_42_14_postcondition___00.smt2 |    4.584s | 39.408MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PB16-052__float_invariant__attempt_3.adb_77_22_assert___00.smt2 |    5.042s | 261.0MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/NC06-004__init__shapes5.adb_43_34_range_check___00.smt2 |    5.746s | 36.348MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O826-006__float_exponential__float_expon.adb_10_28_fp_overflow_check___00.smt2 |    5.768s | 90.892MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_1583cf_generic_float_tests-T-defqtvc__00.smt2 |    6.073s | 64.496MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_ff055b_generic_interval_tests-T-defqtvc__00.smt2 |    6.137s | 68.092MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O325-024__abstract_state__stabilizer_pack.adb_21_22_fp_overflow_check___00.smt2 |    6.159s | 40.228MiB| sat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/Q607-007__floats__normalize.adb_163_22_assert___00.smt2 |    6.366s | 40.9MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_61b4e3_generic_float_tests-T-defqtvc__00.smt2 |    6.499s | 64.484MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PC07-014__float_conversion__simple_trajectory.adb_26_49_fp_overflow_check___00.smt2 |    6.504s | 95.152MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/MC17-036__gnatVa__protectedfloat.adb_17_24_fp_overflow_check___00.smt2 |    7.196s | 91.66MiB| sat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/Q607-007__floats__normalize.adb_47_22_assert___00.smt2 |    7.200s | 37.016MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/MC13-026__float_div__protectedfloat.adb_15_24_fp_overflow_check___00.smt2 |    7.240s | 91.744MiB| sat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P615-019__silver__division_by_zero.adb_39_14_division_check___00.smt2 |    7.298s | 199.0MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PC07-014__float_conversion__simple_trajectory.adb_35_45_fp_overflow_check___00.smt2 |    7.555s | 252.0MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/Q607-007__floats__normalize.adb_105_22_assert___00.smt2 |    8.004s | 41.752MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/Q607-007__floats__normalize.adb_76_22_assert___00.smt2 |    8.493s | 41.672MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/NC06-004__init__shapes5.adb_29_17_range_check___00.smt2 |    8.651s | 48.88MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/S118-010__zeros_counterex__math.adb_25_31_fp_overflow_check___00.smt2 |    8.952s | 53.176MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/S118-010__zeros_counterex__math.adb_26_26_fp_overflow_check___00.smt2 |    9.103s | 48.412MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P906-011__exp_division__expo.adb_6_11_division_check___00.smt2 |    9.139s | 38.648MiB| sat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PB16-052__float_invariant__attempt_3.adb_56_22_assert___00.smt2 |    9.332s | 95.108MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__abs_controller_oem_with_property.adb_56_43_fp_overflow_check___00.smt2 |   10.151s | 176.0MiB| sat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P310-021__proof_float_remainder__foo.adb_16_17_range_check___00.smt2 |   10.949s | 414.0MiB| sat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P615-019__silver__overflow_check.adb_27_32_fp_overflow_check___00.smt2 |   11.561s | 204.0MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O826-006__float_exponential__float_expon.adb_10_21_fp_overflow_check___00.smt2 |   11.663s | 102.0MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PC07-014__float_conversion__simple_trajectory.adb_25_32_fp_overflow_check___00.smt2 |   11.899s | 95.856MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_e5cfc1_generic_float_tests-T-defqtvc__00.smt2 |   12.178s | 36.368MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O826-006__float_exponential__float_expon.adb_10_43_fp_overflow_check___00.smt2 |   12.261s | 109.0MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__smoothing.adb_98_22_assert___00.smt2 |   12.384s | 170.0MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_336_51_fp_overflow_check___00.smt2 |   12.971s | 103.0MiB| sat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_457_51_fp_overflow_check___00.smt2 |   12.985s | 103.0MiB| sat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O826-006__float_exponential__float_expon.adb_10_26_fp_overflow_check___00.smt2 |   14.272s | 97.916MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/S603-051__dimensions__dimensions.ads_377_7_fp_overflow_check___00.smt2 |   14.646s | 76.064MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/proofinuse__lat_long__lat_long.ads_36_14_postcondition___00.smt2 |   15.143s | 37.728MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_0d33ae_generic_float_tests-T-defqtvc__00.smt2 |   15.470s | 34.74MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P615-019__silver__overflow_check.adb_30_32_division_check___00.smt2 |   16.149s | 198.0MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O715-033__level1__hard_stuff.adb_28_25_fp_overflow_check___00.smt2 |   17.333s | 195.0MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_90cfbd_generic_float_tests-T-defqtvc__00.smt2 |   18.688s | 145.0MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PC07-014__float_conversion__simple_trajectory.adb_38_22_assert___00.smt2 |   19.650s | 251.0MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_bee7c4_generic_float_tests-T-defqtvc__00.smt2 |   19.702s | 98.0MiB| unsat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P310-021__proof_float_remainder__foo.adb_9_17_range_check___00.smt2 |   19.922s | 228.0MiB| sat | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/K719-019__flight_mgr__flight_manager.adb_36_53_fp_overflow_check___00.smt2 |   20.009s | 59.756MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PC05-013__interval_overflow__mult.adb_11_22_assert___00.smt2 |   20.009s | 42.44MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PC07-014__float_conversion__simple_trajectory.adb_16_22_assert___00.smt2 |   20.010s | 56.188MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/NC05-005__float_division__pi_euler.adb_12_25_assert2___00.smt2 |   20.010s | 45.052MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M919-035__floating_point__dynamic_float.adb_9_25_assert___00.smt2 |   20.010s | 40.416MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P620-034__float_out_subtype__get_out_subtype.adb_28_33_range_check___00.smt2 |   20.010s | 55.892MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O401-034__float_pred__safety_pack.adb_57_26_range_check___00.smt2 |   20.010s | 37.992MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M122-006__assign__p.adb_8_9_discriminant_check___00.smt2 |   20.010s | 62.164MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_f2780c_generic_float_tests-T-defqtvc__00.smt2 |   20.011s | 31.54MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_647_14_precondition___00.smt2 |   20.011s | 53.16MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/S118-010__zeros_counterex__math.adb_25_26_fp_overflow_check___00.smt2 |   20.011s | 52.456MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O325-024__abstract_state__stabilizer_pack.adb_23_9_fp_overflow_check___00.smt2 |   20.011s | 76.596MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/KB04-017__float__p.adb_4_13_range_check___00.smt2 |   20.012s | 57.06MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P615-019__silver__discriminant_check.adb_19_8_discriminant_check___00.smt2 |   20.012s | 58.824MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PC08-035__missing_range_check_on_out_param__demo.adb_6_7_demo.adb_14_7_range_check___00.smt2 |   20.012s | 95.756MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_391_30_range_check___00.smt2 |   20.012s | 71.448MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PB16-052__float_invariant__attempt_2.adb_32_19_postcondition___00.smt2 |   20.012s | 66.068MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PC07-014__float_conversion__simple_trajectory.adb_17_22_assert___00.smt2 |   20.012s | 57.844MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O416-002__dyn_pred_rte__pred.adb_31_26_unreachable_branch___00.smt2 |   20.012s | 25.1MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_377_30_range_check___00.smt2 |   20.013s | 70.404MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/S427-002__inline_dim__challenges.adb_8_54_challenges.adb_15_14_challenges.adb_24_14_challenges.adb_33_29_challenges.adb_38_10_range_check___00.smt2 |   20.013s | 95.108MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PC07-014__float_conversion__simple_trajectory.adb_23_45_fp_overflow_check___00.smt2 |   20.013s | 92.66MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P620-034__float_out_subtype__get_out_subtype.adb_27_33_range_check___00.smt2 |   20.013s | 56.764MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/R123-048__tasks__psu_monitoring.adb_104_75_range_check___00.smt2 |   20.013s | 81.104MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/Q424-012__succ_floats_copy_z3__succ_floats.adb_22_19_assert___00.smt2 |   20.013s | 99.756MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_1484_19_precondition___00.smt2 |   20.013s | 94.292MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/K719-019__flight_mgr__flight_manager.ads_12_58_fp_overflow_check___00.smt2 |   20.013s | 77.976MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/K719-019__flight_mgr__flight_manager.ads_10_65_fp_overflow_check___00.smt2 |   20.013s | 82.072MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_443_22_overflow_check___00.smt2 |   20.013s | 73.184MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PC07-014__float_conversion__simple_trajectory.adb_23_22_assert___00.smt2 |   20.014s | 99.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_391_69_overflow_check___00.smt2 |   20.014s | 70.316MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/K719-019__flight_mgr__flight_manager.ads_13_18_fp_overflow_check___00.smt2 |   20.014s | 75.88MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/N122-021__succ_floats__succ_floats.adb_18_24_overflow_check___00.smt2 |   20.014s | 97.296MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/KC22-015__succ_overflow__p.adb_45_38_overflow_check___00.smt2 |   20.014s | 97.172MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_444_66_overflow_check___00.smt2 |   20.014s | 71.192MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_363_29_range_check___00.smt2 |   20.014s | 71.544MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O220-024__floats__test_pack.adb_7_32_fp_overflow_check___00.smt2 |   20.014s | 65.48MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_363_68_overflow_check___00.smt2 |   20.015s | 70.576MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PB16-052__float_invariant__attempt_1.adb_30_19_postcondition___00.smt2 |   20.015s | 65.924MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/Q424-012__succ_floats_copy_z3__succ_floats.adb_26_24_overflow_check___00.smt2 |   20.015s | 99.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O826-006__float_exponential__float_expon.adb_10_17_fp_overflow_check___00.smt2 |   20.015s | 97.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PB16-052__float_invariant__attempt_3.adb_55_22_assert___00.smt2 |   20.015s | 98.48MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O416-002__dyn_pred_rte__pred.adb_28_8_unreachable_branch___00.smt2 |   20.016s | 22.848MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/K719-019__flight_mgr__flight_manager.adb_37_53_fp_overflow_check___00.smt2 |   20.016s | 56.324MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O512-022__number_theory__number_theory.ads_23_43_fp_overflow_check___00.smt2 |   20.016s | 127.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/proofinuse__lat_long__lat_long.adb_10_29_fp_overflow_check___00.smt2 |   20.017s | 108.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/proofinuse__lat_long__lat_long.ads_41_14_postcondition___00.smt2 |   20.017s | 73.24MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/KC20-032__succ_pred__p.adb_46_14_postcondition___00.smt2 |   20.018s | 159.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/K719-019__flight_mgr__flight_manager.ads_11_18_fp_overflow_check___00.smt2 |   20.018s | 83.408MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/S427-002__inline_dim__challenges.adb_24_61_challenges.adb_33_29_challenges.adb_38_10_range_check___00.smt2 |   20.018s | 166.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__smoothing.adb_65_44_fp_overflow_check___00.smt2 |   20.018s | 161.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__errorexamplefloat.adb_39_65_fp_overflow_check___00.smt2 |   20.018s | 155.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PB16-052__float_invariant__attempt_3.adb_63_62_overflow_check___00.smt2 |   20.019s | 172.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_1219_33_fp_overflow_check___00.smt2 |   20.019s | 149.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O325-024__abstract_state__stabilizer_pack.adb_21_34_fp_overflow_check___00.smt2 |   20.019s | 49.892MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PC07-014__float_conversion__simple_trajectory.adb_25_22_assert___00.smt2 |   20.019s | 98.02MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PB16-052__float_invariant__attempt_3.adb_62_45_overflow_check___00.smt2 |   20.020s | 174.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P615-019__silver__overflow_check.adb_29_32_fp_overflow_check___00.smt2 |   20.020s | 206.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O512-022__number_theory__number_theory.ads_20_37_overflow_check___00.smt2 |   20.020s | 75.06MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_457_22_fp_overflow_check___00.smt2 |   20.021s | 117.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/proofinuse__lat_long__lat_long.adb_10_41_fp_overflow_check___00.smt2 |   20.021s | 113.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P615-019__silver__discriminant_check.adb_14_15_discriminant_check___00.smt2 |   20.022s | 58.556MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_377_69_overflow_check___00.smt2 |   20.022s | 70.752MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/proofinuse__lat_long__lat_long.adb_9_58_fp_overflow_check___00.smt2 |   20.022s | 72.108MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PC07-014__float_conversion__simple_trajectory.adb_12_30_fp_overflow_check___00.smt2 |   20.022s | 57.864MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PC07-014__float_conversion__simple_trajectory.adb_30_22_assert___00.smt2 |   20.023s | 250.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/NC06-004__init__shapes5.adb_8_8_refined_post___00.smt2 |   20.023s | 57.448MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PC07-014__float_conversion__simple_trajectory.adb_18_22_assert___00.smt2 |   20.024s | 88.428MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/NC05-005__float_division__pi_euler.adb_15_24_overflow_check2___00.smt2 |   20.024s | 169.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PB16-052__float_invariant__attempt_4.adb_40_19_postcondition___00.smt2 |   20.025s | 135.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M919-035__floating_point__dynamic_float.adb_9_35_range_check___00.smt2 |   20.025s | 36.952MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/S427-002__inline_dim__challenges.adb_8_37_challenges.adb_15_14_challenges.adb_24_14_challenges.adb_33_29_challenges.adb_38_10_range_check___00.smt2 |   20.025s | 162.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O826-006__float_exponential__float_expon.adb_10_31_fp_overflow_check___00.smt2 |   20.026s | 105.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/NC06-004__init__shapes5.ads_13_18_postcondition___00.smt2 |   20.026s | 83.748MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P906-011__exp_division__expo.adb_6_11_fp_overflow_check___00.smt2 |   20.026s | 63.132MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_390_22_overflow_check___00.smt2 |   20.027s | 71.26MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_2cf678_generic_float_tests-T-defqtvc__00.smt2 |   20.027s | 281.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_607_25_precondition___00.smt2 |   20.027s | 287.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_349_47_fp_overflow_check___00.smt2 |   20.027s | 371.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_627_26_precondition___00.smt2 |   20.027s | 287.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_b32673_generic_float_tests-T-defqtvc__00.smt2 |   20.027s | 34.168MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O715-033__level1__hard_stuff.adb_28_21_fp_overflow_check___00.smt2 |   20.028s | 188.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P315-010__float__sample.ads_37_17_postcondition___00.smt2 |   20.028s | 96.348MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_376_22_overflow_check___00.smt2 |   20.028s | 71.536MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__smoothing.adb_86_22_assert___00.smt2 |   20.028s | 168.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PC07-014__float_conversion__simple_trajectory.adb_37_54_fp_overflow_check___00.smt2 |   20.028s | 250.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/NC05-005__float_division__pi_euler_2.adb_18_18_fp_overflow_check2___00.smt2 |   20.028s | 288.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PB16-052__float_invariant__attempt_3.adb_76_22_assert___00.smt2 |   20.028s | 286.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O715-033__level0__hard_stuff.adb_28_29_fp_overflow_check___00.smt2 |   20.029s | 328.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/proofinuse__lat_long__lat_long.ads_18_26_precondition___00.smt2 |   20.029s | 50.38MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M422-023__from_int__sgs.ads_13_17_postcondition___00.smt2 |   20.030s | 37.64MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_0f9517_generic_float_tests-T-defqtvc__00.smt2 |   20.030s | 145.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O810-001__predicate__safety_pack.ads_55_21_range_check___00.smt2 |   20.030s | 37.82MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/S427-002__inline_dim__challenges.adb_8_71_challenges.adb_15_14_challenges.adb_24_14_challenges.adb_33_29_challenges.adb_38_10_range_check___00.smt2 |   20.030s | 66.192MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P315-010__float__original_sample.ads_39_17_postcondition___00.smt2 |   20.030s | 96.876MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/R123-048__tasks__psu_monitoring.ads_93_75_contract_case___00.smt2 |   20.030s | 97.8MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P615-019__silver__overflow_check.adb_31_32_fp_overflow_check___00.smt2 |   20.030s | 218.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M227-029__flow_records_and_arrays__message_tests.adb_37_16_fp_overflow_check___00.smt2 |   20.030s | 58.524MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O715-033__level0__hard_stuff.adb_28_17_fp_overflow_check___00.smt2 |   20.031s | 204.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PC07-014__float_conversion__simple_trajectory.adb_42_22_assert___00.smt2 |   20.031s | 359.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PC07-014__float_conversion__simple_trajectory.adb_25_55_fp_overflow_check___00.smt2 |   20.032s | 98.188MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/S427-002__inline_dim__dimensions.ads_377_14_fp_overflow_check___00.smt2 |   20.032s | 50.32MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_444_27_range_check___00.smt2 |   20.032s | 71.508MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PB16-052__float_invariant__attempt_3.adb_65_25_assert___00.smt2 |   20.032s | 337.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P620-034__float_out_subtype__get_out_subtype.adb_27_58_range_check___01.smt2 |   20.032s | 57.196MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PC07-014__float_conversion__simple_trajectory.adb_40_22_assert___00.smt2 |   20.032s | 359.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/K719-019__flight_mgr__flight_manager.ads_10_17_postcondition___00.smt2 |   20.032s | 77.704MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/proofinuse__lat_long__lat_long.adb_10_54_fp_overflow_check___00.smt2 |   20.033s | 75.76MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/N122-021__succ_floats__succ_floats.adb_30_19_assert___00.smt2 |   20.033s | 98.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O826-006__float_exponential__float_expon.adb_10_15_fp_overflow_check___00.smt2 |   20.034s | 100.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O325-024__abstract_state__stabilizer_pack.adb_23_19_fp_overflow_check___00.smt2 |   20.035s | 55.344MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_336_22_fp_overflow_check___00.smt2 |   20.035s | 117.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/NC05-005__float_division__pi_euler_2.adb_19_24_overflow_check2___00.smt2 |   20.035s | 289.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_362_22_overflow_check___00.smt2 |   20.035s | 71.916MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/S427-002__inline_dim__challenges.adb_8_71_challenges.adb_15_14_challenges.adb_24_14_challenges.adb_33_29_challenges.adb_38_10_fp_overflow_check___00.smt2 |   20.035s | 67.488MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O715-033__level3__hard_stuff.adb_29_25_assert___00.smt2 |   20.036s | 122.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O826-006__float_exponential__float_expon.adb_10_36_fp_overflow_check___00.smt2 |   20.036s | 111.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_1209_31_fp_overflow_check___00.smt2 |   20.036s | 149.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/S427-002__inline_dim__challenges.adb_8_54_challenges.adb_15_14_challenges.adb_24_14_challenges.adb_33_29_challenges.adb_38_10_fp_overflow_check___00.smt2 |   20.037s | 92.82MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/N122-021__succ_floats__succ_floats.adb_12_19_assert___00.smt2 |   20.037s | 161.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__smoothing.adb_76_56_fp_overflow_check___00.smt2 |   20.038s | 168.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/proofinuse__lat_long__lat_long.ads_39_45_fp_overflow_check___00.smt2 |   20.038s | 72.344MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O512-022__number_theory__number_theory.adb_23_30_overflow_check___00.smt2 |   20.038s | 224.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_607_25_range_check___00.smt2 |   20.038s | 538.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PC07-014__float_conversion__simple_trajectory.adb_30_36_fp_overflow_check___00.smt2 |   20.039s | 250.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PA21-002__floatdiv__basic_contracts.adb_10_51_range_check___00.smt2 |   20.039s | 530.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/N121-026__nonlinear__nonlinear.adb_11_19_assert___00.smt2 |   20.039s | 49.084MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O512-022__number_theory__number_theory.ads_23_16_postcondition___00.smt2 |   20.039s | 123.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/N709-001__tagged_discr__classwide.ads_49_14_postcondition___00.smt2 |   20.039s | 253.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/O325-024__abstract_state__stabilizer_pack.adb_22_32_fp_overflow_check___00.smt2 |   20.039s | 71.688MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M919-035__floating_point__dynamic_float.adb_7_19_range_check___00.smt2 |   20.040s | 34.904MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PB16-052__float_invariant__attempt_3.adb_53_22_assert___00.smt2 |   20.040s | 97.26MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PC07-014__float_conversion__simple_trajectory.adb_41_35_fp_overflow_check___00.smt2 |   20.040s | 360.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/S603-051__dimensions__dimensions.ads_377_11_fp_overflow_check___00.smt2 |   20.041s | 90.552MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__biaseddivide.adb_24_16_fp_overflow_check___00.smt2 |   20.041s | 158.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__abs_controller_oem_with_property.adb_88_22_assert___00.smt2 |   20.041s | 205.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_843777_generic_float_tests-T-defqtvc__00.smt2 |   20.041s | 345.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_1473_19_precondition___00.smt2 |   20.041s | 90.66MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PC07-014__float_conversion__simple_trajectory.adb_37_22_assert___00.smt2 |   20.042s | 250.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PC07-014__float_conversion__simple_trajectory.adb_35_22_assert___00.smt2 |   20.042s | 250.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P615-019__silver__overflow_check.adb_28_32_fp_overflow_check___00.smt2 |   20.042s | 203.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PC07-014__float_conversion__simple_trajectory.adb_28_22_assert___00.smt2 |   20.042s | 248.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PC07-014__float_conversion__simple_trajectory.adb_37_32_fp_overflow_check___00.smt2 |   20.043s | 250.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_49c130_generic_float_tests-T-defqtvc__00.smt2 |   20.045s | 98.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__errorexamplefloat.adb_48_22_assert___00.smt2 |   20.045s | 157.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_5cf5ea_generic_float_tests-T-defqtvc__00.smt2 |   20.045s | 345.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_627_26_range_check___00.smt2 |   20.046s | 538.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_d5baaf_generic_float_tests-T-defqtvc__00.smt2 |   20.046s | 281.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PC07-014__float_conversion__simple_trajectory.adb_38_48_fp_overflow_check___00.smt2 |   20.046s | 251.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_617_26_precondition___00.smt2 |   20.047s | 287.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/R123-048__tasks__psu_monitoring.adb_100_75_range_check___00.smt2 |   20.047s | 103.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P315-010__float__original_sample.ads_38_35_fp_overflow_check___00.smt2 |   20.047s | 287.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PB16-052__float_invariant__attempt_3.adb_74_22_assert___00.smt2 |   20.048s | 266.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/Q424-012__succ_floats_copy_z3__succ_floats.adb_14_19_assert___00.smt2 |   20.049s | 164.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P615-019__silver__division_by_zero.adb_39_14_fp_overflow_check___00.smt2 |   20.050s | 216.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PB16-052__float_invariant__attempt_3.adb_63_25_assert___00.smt2 |   20.052s | 326.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/N709-001__tagged_discr__classwide.ads_36_14_postcondition___00.smt2 |   20.052s | 275.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PC07-014__float_conversion__simple_trajectory.adb_41_22_assert___00.smt2 |   20.053s | 362.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PB16-052__float_invariant__attempt_3.adb_66_25_assert___00.smt2 |   20.054s | 366.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P615-019__silver__overflow_check.adb_30_32_fp_overflow_check___00.smt2 |   20.057s | 206.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_470_47_fp_overflow_check___00.smt2 |   20.057s | 371.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_349_56_fp_overflow_check___00.smt2 |   20.060s | 486.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_470_56_fp_overflow_check___00.smt2 |   20.060s | 486.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PB16-052__float_invariant__attempt_3.adb_64_25_assert___00.smt2 |   20.061s | 484.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_617_26_range_check___00.smt2 |   20.061s | 534.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PB16-052__float_invariant__attempt_3.adb_65_49_overflow_check___00.smt2 |   20.062s | 484.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PB16-052__float_invariant__attempt_3.adb_81_22_assert___00.smt2 |   20.065s | 545.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/proofinuse__lat_long__lat_long.ads_30_57_fp_overflow_check___00.smt2 |   20.065s | 465.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_470_22_fp_overflow_check___00.smt2 |   20.069s | 531.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/NC05-005__float_division__pi_euler.adb_14_18_fp_overflow_check2___00.smt2 |   20.072s | 401.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/PA21-002__floatdiv__basic_contracts.adb_11_43_range_check___00.smt2 |   20.075s | 536.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_349_22_fp_overflow_check___00.smt2 |   20.078s | 531.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/KB25-022__exp__gp_exp.adb_6_11_overflow_check___00.smt2 |   20.198s | 2420.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/KB25-022__exp__gp_exp.adb_5_14_range_check___00.smt2 |   20.205s | 2529.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/KB25-022__exp__gp_exp.adb_7_11_fp_overflow_check___00.smt2 |   20.211s | 2365.0MiB| timeout | 0 |  |  |
|non-incremental/UFFPDTNIRA/20200306-Kanig/spark2014bench/KB25-022__exp__gp_exp.adb_5_11_overflow_check___00.smt2 |   20.219s | 2515.0MiB| timeout | 0 |  |  |
