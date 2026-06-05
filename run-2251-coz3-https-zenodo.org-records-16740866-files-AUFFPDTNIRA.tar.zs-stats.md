# .

* SAT 0
* UNSAT 139
* TIMEOUT 19
* UNKNOWN 8

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/AUFFPDTNIRA.tar.zst?download=1 | Source list: quantifier_benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-AUFFPDTNIRA.tar.zs
Runner: rise-runner-1
Z3 repo: Z3Prover/z3
Z3 commit: c3f5365a95a7eac2419a2f95ff240909f275cc08
Z3 branch: c3f5365a95a7eac2419a2f95ff240909f275cc08
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/AUFFPDTNIRA.tar.zst?download=1
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
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P914-008__trivial_test__a.adb_22_49_range_check___00.smt2 |    0.015s | 19.276MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_40_27_discriminant_check___00.smt2 |    0.015s | 19.232MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_34_24_discriminant_check___00.smt2 |    0.016s | 19.38MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_bc608c_homothetical-T-defqtvc__00.smt2 |    0.016s | 19.12MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_8ff0d3_homothetical-T-defqtvc__00.smt2 |    0.016s | 19.288MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_60_23_index_check___00.smt2 |    0.017s | 19.4MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M227-029__flow_records_and_arrays__untangle_tests.adb_40_10_index_check___00.smt2 |    0.017s | 19.26MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_41_52_discriminant_check___00.smt2 |    0.017s | 19.204MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_60_47_index_check___00.smt2 |    0.017s | 19.332MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_51_27_index_check___00.smt2 |    0.017s | 19.388MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_50_42_index_check___00.smt2 |    0.017s | 19.348MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M227-029__flow_records_and_arrays__untangle_tests.adb_39_10_index_check___00.smt2 |    0.017s | 19.128MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/K210-006__anontype1__anon_type.ads_7_19_postcondition___00.smt2 |    0.017s | 19.16MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_236_39_test_prime_and_coprime_numbers.adb_6_4_loop_invariant_init___00.smt2 |    0.018s | 19.22MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_c64ebb_homothetical-T-defqtvc__00.smt2 |    0.018s | 19.34MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_32_24_discriminant_check___00.smt2 |    0.018s | 19.32MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/O429-046__flow_tasking_cfg__test.adb_6_11_ceiling__priority_protocol___00.smt2 |    0.018s | 19.136MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_64_21_range_check___00.smt2 |    0.018s | 19.396MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_59_23_index_check___00.smt2 |    0.018s | 19.416MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_50_25_index_check___00.smt2 |    0.018s | 19.192MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_51_31_discriminant_check___00.smt2 |    0.019s | 19.28MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_38_32_range_check___00.smt2 |    0.019s | 19.22MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_41_27_discriminant_check___00.smt2 |    0.019s | 19.384MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P828-003__annotate__t.ads_11_58_division_check___00.smt2 |    0.019s | 19.356MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_237_47_test_prime_and_coprime_numbers.adb_6_4_division_check___00.smt2 |    0.019s | 19.312MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_6ce0dc_homothetical-T-defqtvc__00.smt2 |    0.020s | 19.164MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_a146b6_homothetical-T-defqtvc__00.smt2 |    0.020s | 19.34MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_48_29_index_check___00.smt2 |    0.020s | 19.428MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_48_45_index_check___00.smt2 |    0.020s | 19.36MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P914-008__trivial_test__spark-unconstrained_array_lemmas.ads_56_56_a.adb_7_4_index_check___00.smt2 |    0.021s | 19.796MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_dd9334_generic_float_tests-T-defqtvc__00.smt2 |    0.021s | 20.108MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/PB28-028__float_bounds__floats.adb_5_22_assert___00.smt2 |    0.021s | 19.948MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_5fb9ed_homothetical-T-defqtvc__00.smt2 |    0.022s | 20.208MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_71ca97_homothetical-T-defqtvc__00.smt2 |    0.022s | 20.132MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P914-008__trivial_test__a.adb_22_34_range_check___00.smt2 |    0.022s | 19.868MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_c213c3_homothetical-T-defqtvc__00.smt2 |    0.022s | 20.34MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_26_33_discriminant_check___00.smt2 |    0.022s | 19.42MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_60_52_initialization___00.smt2 |    0.022s | 20.04MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_213_56_test_prime_and_coprime_numbers.adb_6_4_index_check___00.smt2 |    0.023s | 19.664MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_be413e_homothetical-T-defqtvc__00.smt2 |    0.023s | 20.132MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S720-001__static_predicate__predicates.ads_10_19_assert___00.smt2 |    0.023s | 19.864MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_50_46_discriminant_check___00.smt2 |    0.023s | 19.28MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_ed87a5_homothetical-T-defqtvc__00.smt2 |    0.023s | 19.14MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P914-008__trivial_test__spark-test_array_lemmas.ads_73_31_index_check___00.smt2 |    0.023s | 19.836MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/PB29-020__float_bounds__floats.adb_13_16_assert___00.smt2 |    0.023s | 19.968MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/PB29-020__float_bounds__floats.adb_12_16_assert___00.smt2 |    0.023s | 20.196MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_131422_homothetical-T-defqtvc__00.smt2 |    0.023s | 19.932MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_211_33_test_prime_and_coprime_numbers.adb_6_4_loop_invariant_init___00.smt2 |    0.024s | 19.144MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/J506-016__scaled_value__spark-test_array_lemmas.ads_73_19_index_check___00.smt2 |    0.024s | 19.764MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_adae78_homothetical-T-defqtvc__00.smt2 |    0.024s | 20.144MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_bec82f_homothetical-T-defqtvc__00.smt2 |    0.024s | 20.516MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_229_62_test_prime_and_coprime_numbers.adb_6_4_index_check___00.smt2 |    0.024s | 19.9MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_26_58_discriminant_check___00.smt2 |    0.024s | 19.324MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S720-001__static_predicate__predicates.ads_11_19_assert___00.smt2 |    0.024s | 20.132MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/K210-006__anontype1__anon_type.ads_7_45_overflow_check___00.smt2 |    0.024s | 19.956MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_233_62_test_prime_and_coprime_numbers.adb_6_4_division_check___00.smt2 |    0.025s | 19.152MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M227-029__flow_records_and_arrays__untangle_tests.adb_37_28_index_check___00.smt2 |    0.025s | 19.304MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_7e45aa_homothetical-T-defqtvc__00.smt2 |    0.025s | 19.416MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_0564ae_homothetical-T-defqtvc__00.smt2 |    0.025s | 19.388MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_217_55_test_prime_and_coprime_numbers.adb_6_4_division_check___00.smt2 |    0.025s | 19.124MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_bd1d22_homothetical-T-defqtvc__00.smt2 |    0.025s | 20.584MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/R123-048__tasks__psu_monitoring.ads_74_9_ceiling__priority_protocol___00.smt2 |    0.025s | 19.7MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_e82fbc_homothetical-T-defqtvc__00.smt2 |    0.026s | 19.396MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/PB02-004__inherited_sub__rec.ads_23_28_range_check___00.smt2 |    0.026s | 20.188MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_ad70de_homothetical-T-defqtvc__00.smt2 |    0.026s | 19.348MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_71_20_assert___00.smt2 |    0.026s | 20.488MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_d9d866_homothetical-T-defqtvc__00.smt2 |    0.026s | 19.36MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P909-014__numerics__main.adb_15_23_range_check___00.smt2 |    0.026s | 20.452MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_60_18_initialization___00.smt2 |    0.027s | 20.22MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S720-001__static_predicate__predicates.ads_21_19_assert___00.smt2 |    0.027s | 20.52MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P909-014__numerics__main.adb_14_23_range_check___00.smt2 |    0.027s | 20.4MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_10cdb1_homothetical-T-defqtvc__00.smt2 |    0.027s | 20.624MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_209_39_test_prime_and_coprime_numbers.adb_6_4_precondition___00.smt2 |    0.027s | 19.072MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/R123-048__tasks__psu_monitoring.ads_75_39_range_check___00.smt2 |    0.027s | 19.644MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/PB28-028__float_bounds__floats.adb_6_22_assert___00.smt2 |    0.027s | 20.144MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P909-014__numerics__main.adb_13_23_range_check___00.smt2 |    0.028s | 20.284MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_ff67ae_homothetical-T-defqtvc__00.smt2 |    0.028s | 19.344MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_46_21_postcondition___00.smt2 |    0.028s | 20.424MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_d741d4_generic_float_tests-T-defqtvc__00.smt2 |    0.028s | 20.136MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_25_33_discriminant_check___00.smt2 |    0.029s | 19.364MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_48_24_initialization___00.smt2 |    0.029s | 20.468MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_58_15_loop_invariant_init___00.smt2 |    0.030s | 20.276MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/O429-046__flow_tasking_cfg__test.adb_8_36_division_check___00.smt2 |    0.030s | 19.284MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_58_15_loop_invariant_preserv___00.smt2 |    0.030s | 20.5MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/PB28-028__float_bounds__floats.adb_4_22_assert___00.smt2 |    0.031s | 20.004MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_63f7dc_homothetical-T-defqtvc__00.smt2 |    0.031s | 19.288MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_a965f2_homothetical-T-defqtvc__00.smt2 |    0.031s | 20.756MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P914-008__trivial_test__spark-unconstrained_array_lemmas.ads_56_39_a.adb_7_4_index_check___00.smt2 |    0.031s | 19.94MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P920-005__inline__access_inline.adb_18_22_access_inline.adb_22_4_range_check___00.smt2 |    0.032s | 22.352MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_47_29_index_check___00.smt2 |    0.033s | 19.264MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P920-005__inline__access_inline.adb_18_22_access_inline.adb_22_4_fp_overflow_check___00.smt2 |    0.033s | 22.428MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_7b9ee6_homothetical-T-defqtvc__00.smt2 |    0.034s | 19.236MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P828-003__annotate__t.ads_11_4_range_check___00.smt2 |    0.034s | 19.108MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_af2921_homothetical-T-defqtvc__00.smt2 |    0.035s | 19.28MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/PB29-020__float_bounds__floats.adb_11_16_assert___00.smt2 |    0.035s | 19.916MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P914-008__trivial_test__a.adb_22_9_precondition___00.smt2 |    0.036s | 20.948MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P909-014__numerics__main.adb_17_23_range_check___00.smt2 |    0.036s | 20.312MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_efd45c_homothetical-T-defqtvc__00.smt2 |    0.036s | 19.068MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P909-014__numerics__main.adb_16_23_range_check___00.smt2 |    0.037s | 20.516MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M227-029__flow_records_and_arrays__untangle_tests.adb_39_19_index_check___00.smt2 |    0.038s | 19.292MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_65_21_range_check___00.smt2 |    0.040s | 19.292MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/PB02-004__inherited_sub__rec.ads_35_7_range_check___00.smt2 |    0.041s | 19.512MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P914-008__trivial_test__a.adb_23_22_assert___00.smt2 |    0.042s | 22.448MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_004a8e_homothetical-T-defqtvc__00.smt2 |    0.042s | 19.948MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_57adbf_homothetical-T-defqtvc__00.smt2 |    0.042s | 19.364MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P914-008__trivial_test__spark-unconstrained_array_lemmas.ads_56_46_a.adb_7_4_overflow_check___00.smt2 |    0.042s | 19.888MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_235_41_test_prime_and_coprime_numbers.adb_6_4_overflow_check___00.smt2 |    0.043s | 23.452MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_48_49_initialization___00.smt2 |    0.043s | 20.192MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_226_30_test_prime_and_coprime_numbers.adb_6_4_index_check___00.smt2 |    0.043s | 19.844MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_235_63_test_prime_and_coprime_numbers.adb_6_4_division_check___00.smt2 |    0.043s | 23.504MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_219_27_test_prime_and_coprime_numbers.adb_6_4_index_check___00.smt2 |    0.043s | 23.348MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P828-003__annotate__t.ads_15_28_length_check___00.smt2 |    0.044s | 20.316MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_232_35_test_prime_and_coprime_numbers.adb_6_4_index_check___00.smt2 |    0.044s | 23.248MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_211_33_test_prime_and_coprime_numbers.adb_6_4_loop_invariant_preserv___00.smt2 |    0.046s | 23.336MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_70_5_precondition___00.smt2 |    0.046s | 20.272MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_236_39_test_prime_and_coprime_numbers.adb_6_4_loop_invariant_preserv___00.smt2 |    0.047s | 23.248MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_239_35_test_prime_and_coprime_numbers.adb_6_4_overflow_check___00.smt2 |    0.047s | 23.708MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S720-001__static_predicate__predicates.ads_20_19_assert___00.smt2 |    0.048s | 20.392MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_215_13_test_prime_and_coprime_numbers.adb_6_4_loop_invariant_init___00.smt2 |    0.050s | 23.288MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_216_29_test_prime_and_coprime_numbers.adb_6_4_index_check___00.smt2 |    0.050s | 23.132MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/R123-048__tasks__psu_monitoring.adb_198_22_assert___00.smt2 |    0.052s | 22.596MiB| unknown | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P920-005__inline__access_inline.adb_18_7_access_inline.adb_22_4_range_check___00.smt2 |    0.053s | 22.224MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_222_26_test_prime_and_coprime_numbers.adb_6_4_overflow_check___00.smt2 |    0.056s | 23.668MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/R123-048__tasks__psu_monitoring.adb_122_22_assert___00.smt2 |    0.059s | 22.612MiB| unknown | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/R123-048__tasks__psu_monitoring.adb_135_16_precondition___00.smt2 |    0.060s | 22.912MiB| unknown | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/R123-048__tasks__psu_monitoring.adb_200_22_assert___00.smt2 |    0.063s | 22.648MiB| unknown | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/R123-048__tasks__psu_monitoring.adb_197_22_assert___00.smt2 |    0.070s | 22.916MiB| unknown | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/R123-048__tasks__psu_monitoring.adb_166_16_precondition___00.smt2 |    0.070s | 22.948MiB| unknown | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/R123-048__tasks__psu_monitoring.adb_158_16_precondition___00.smt2 |    0.073s | 22.724MiB| unknown | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/R123-048__tasks__psu_monitoring.adb_199_22_assert___00.smt2 |    0.080s | 23.224MiB| unknown | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_229_19_test_prime_and_coprime_numbers.adb_6_4_loop_invariant_init___00.smt2 |    0.135s | 24.788MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_213_13_test_prime_and_coprime_numbers.adb_6_4_loop_invariant_init___00.smt2 |    0.137s | 24.26MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_229_19_test_prime_and_coprime_numbers.adb_6_4_loop_invariant_preserv___00.smt2 |    0.158s | 24.936MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_231_19_test_prime_and_coprime_numbers.adb_6_4_loop_invariant_init___00.smt2 |    0.208s | 25.512MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/R123-048__tasks__psu_monitoring.ads_89_15_postcondition___00.smt2 |    0.245s | 26.104MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_231_19_test_prime_and_coprime_numbers.adb_6_4_loop_invariant_preserv___00.smt2 |    0.255s | 25.688MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_237_39_test_prime_and_coprime_numbers.adb_6_4_loop_invariant_init___00.smt2 |    0.293s | 28.248MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_721390_homothetical-T-defqtvc__00.smt2 |    0.344s | 108.0MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_6ba6c3_homothetical-T-defqtvc__00.smt2 |    0.349s | 110.0MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_372ec1_homothetical-T-defqtvc__00.smt2 |    0.378s | 123.0MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_139120_homothetical-T-defqtvc__00.smt2 |    0.428s | 124.0MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_38_15_loop_invariant_init___00.smt2 |    1.429s | 85.988MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_26_58_initialization___00.smt2 |    1.494s | 85.564MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_23_21_postcondition___00.smt2 |    1.685s | 88.128MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_41_52_initialization___00.smt2 |    2.253s | 85.52MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P914-011__expbug__repr.adb_16_30_fp_overflow_check___00.smt2 |    6.223s | 49.516MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_38_15_loop_invariant_preserv___00.smt2 |   10.218s | 280.0MiB| unsat | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_209_39_test_prime_and_coprime_numbers.adb_6_4_range_check___00.smt2 |   20.007s | 31.976MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P828-003__annotate__t.ads_11_52_range_check___00.smt2 |   20.007s | 27.68MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_213_13_test_prime_and_coprime_numbers.adb_6_4_loop_invariant_preserv___00.smt2 |   20.011s | 113.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/K210-006__anontype1__anon_type.adb_33_25_overflow_check___00.smt2 |   20.012s | 110.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_198_16_test_prime_and_coprime_numbers.adb_6_4_postcondition___00.smt2 |   20.014s | 153.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M809-005__float_basics__why_f25daf_homothetical-T-defqtvc__00.smt2 |   20.016s | 124.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M227-029__flow_records_and_arrays__untangle_tests.adb_70_60_fp_overflow_check___00.smt2 |   20.016s | 178.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/NC06-004__init__circle_demo.adb_14_14_precondition___00.smt2 |   20.017s | 183.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M227-029__flow_records_and_arrays__untangle_tests.adb_69_60_fp_overflow_check___00.smt2 |   20.018s | 173.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/PB02-004__inherited_sub__rec.ads_31_7_range_check___00.smt2 |   20.018s | 233.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/M227-029__flow_records_and_arrays__untangle_tests.adb_71_60_fp_overflow_check___00.smt2 |   20.019s | 186.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/P914-011__expbug__repr.adb_16_27_index_check___00.smt2 |   20.021s | 94.332MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_237_39_test_prime_and_coprime_numbers.adb_6_4_loop_invariant_preserv___00.smt2 |   20.023s | 320.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/PB02-004__inherited_sub__rec.ads_17_22_range_check___00.smt2 |   20.024s | 201.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/O512-022__number_theory__number_theory.ads_32_19_postcondition___00.smt2 |   20.030s | 339.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/Q328-034__mut_discr__values.adb_30_10_raise___00.smt2 |   20.033s | 394.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/K210-006__anontype1__anon_type.adb_33_25_range_check___00.smt2 |   20.037s | 195.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/S529-004__update_attr__relaxed_initialization.adb_32_30_range_check___00.smt2 |   20.039s | 538.0MiB| timeout | 0 |  |  |
|non-incremental/AUFFPDTNIRA/20200306-Kanig/spark2014bench/prime_numbers__prime_and_coprime_numbers.adb_215_13_test_prime_and_coprime_numbers.adb_6_4_loop_invariant_preserv___00.smt2 |   20.042s | 332.0MiB| timeout | 0 |  |  |
