# .

* SAT 0
* UNSAT 44
* TIMEOUT 73
* UNKNOWN 0

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/AUFBVFPDTNIRA.tar.zst?download=1 | Source list: quantifier_benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-AUFBVFPDTNIRA.tar.
Runner: rise-runner-1
Z3 repo: Z3Prover/z3
Z3 commit: c3f5365a95a7eac2419a2f95ff240909f275cc08
Z3 branch: c3f5365a95a7eac2419a2f95ff240909f275cc08
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/AUFBVFPDTNIRA.tar.zst?download=1
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
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_73_78_range_check___00.smt2 |    0.016s | 19.316MiB| unsat | 1 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/MC12-024__flow_crash__p.ads_27_22_postcondition___00.smt2 |    0.017s | 19.792MiB| unsat | 1 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_18_50_range_check___00.smt2 |    0.017s | 19.196MiB| unsat | 1 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_12_27_range_check___00.smt2 |    0.017s | 19.172MiB| unsat | 1 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_16_28_assert___00.smt2 |    0.018s | 19.2MiB| unsat | 1 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__test_failsafe.adb_13_19_precondition___00.smt2 |    0.018s | 19.136MiB| unsat | 1 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__test_failsafe.adb_12_4_precondition___00.smt2 |    0.018s | 19.348MiB| unsat | 1 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_68_78_range_check___00.smt2 |    0.018s | 19.296MiB| unsat | 1 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_19_61_range_check___00.smt2 |    0.021s | 19.176MiB| unsat | 1 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_22_18_unreachable_branch___00.smt2 |    0.023s | 19.368MiB| unsat | 1 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__test_failsafe.adb_14_4_precondition___00.smt2 |    0.023s | 19.248MiB| unsat | 1 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.ads_62_14_postcondition___00.smt2 |    0.025s | 19.332MiB| unsat | 1 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_38_22_assert___00.smt2 |    0.026s | 20.1MiB| unsat | 1 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__test_failsafe.adb_15_23_precondition___00.smt2 |    0.026s | 19.34MiB| unsat | 1 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_25_22_unreachable_branch___00.smt2 |    0.027s | 19.384MiB| unsat | 1 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/P816-010__prefix_inline__generic_queue.ads_46_32_some_package.adb_8_4_range_check___00.smt2 |    0.027s | 20.18MiB| unsat | 1 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_26_36_loop_invariant_preserv___00.smt2 |    0.027s | 19.356MiB| unsat | 1 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_49_31_range_check___00.smt2 |    0.028s | 20.472MiB| unsat | 1 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/P816-010__prefix_inline__generic_queue.ads_73_32_some_package.adb_8_4_range_check___00.smt2 |    0.028s | 20.312MiB| unsat | 1 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.ads_45_85_range_check___00.smt2 |    0.028s | 19.22MiB| unsat | 1 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_24_61_range_check___00.smt2 |    0.029s | 19.328MiB| unsat | 1 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_26_36_loop_invariant_init___00.smt2 |    0.029s | 19.192MiB| unsat | 1 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__test_failsafe.adb_10_4_precondition___00.smt2 |    0.029s | 19.776MiB| unsat | 1 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_52_25_assert___00.smt2 |    0.030s | 20.476MiB| unsat | 1 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_18_16_loop_invariant_init___00.smt2 |    0.031s | 20.24MiB| unsat | 1 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.ads_25_64_contract_case___00.smt2 |    0.033s | 20.904MiB| unsat | 1 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__test_failsafe.adb_9_23_precondition___00.smt2 |    0.034s | 19.88MiB| unsat | 1 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_50_25_assert___00.smt2 |    0.034s | 20.744MiB| unsat | 1 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.ads_23_9_disjoint_contract_cases___00.smt2 |    0.034s | 20.044MiB| unsat | 1 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__test_failsafe.adb_11_19_precondition___00.smt2 |    0.035s | 19.312MiB| unsat | 1 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_54_25_assert___00.smt2 |    0.035s | 21.128MiB| unsat | 1 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_22_53_unreachable_branch___00.smt2 |    0.036s | 19.276MiB| unsat | 1 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.ads_40_85_range_check___00.smt2 |    0.037s | 19.252MiB| unsat | 1 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.ads_39_73_range_check___00.smt2 |    0.037s | 20.988MiB| unsat | 1 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_67_66_range_check___00.smt2 |    0.038s | 20.98MiB| unsat | 1 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_51_30_unreachable_branch___00.smt2 |    0.038s | 20.692MiB| unsat | 1 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/MC12-026__overlayed_objects__p2.ads_27_22_postcondition___00.smt2 |    0.039s | 19.844MiB| unsat | 1 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.ads_37_76_range_check___00.smt2 |    0.041s | 20.308MiB| unsat | 1 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/P816-010__prefix_inline__generic_queue.ads_65_32_some_package.adb_8_4_range_check___00.smt2 |    0.047s | 20.3MiB| unsat | 1 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.ads_34_19_contract_case___00.smt2 |    0.047s | 20.956MiB| unsat | 1 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_58_25_assert___00.smt2 |    0.050s | 20.88MiB| unsat | 1 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.ads_29_80_contract_case___00.smt2 |    0.051s | 21.168MiB| unsat | 1 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_24_18_unreachable_branch___00.smt2 |    0.058s | 19.276MiB| unsat | 1 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_18_16_loop_invariant_preserv___00.smt2 |    0.090s | 21.476MiB| unsat | 1 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_78_10_dead_code___00.smt2 |   20.006s | 29.036MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_55_54_unreachable_branch___00.smt2 |   20.006s | 23.636MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_39_22_assert___00.smt2 |   20.006s | 29.04MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.ads_61_14_inconsistent_pre___00.smt2 |   20.006s | 23.688MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_59_54_unreachable_branch___00.smt2 |   20.007s | 23.712MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_43_27_unreachable_branch___00.smt2 |   20.007s | 23.8MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_65_27_unreachable_branch___00.smt2 |   20.007s | 29.612MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_14_16_dead_code___00.smt2 |   20.007s | 24.976MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__test_failsafe.adb_15_19_assert___00.smt2 |   20.007s | 23.808MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_28_17_dead_code___00.smt2 |   20.007s | 24.408MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.ads_29_39_unreachable_branch___00.smt2 |   20.007s | 24.044MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.ads_40_17_unreachable_branch___00.smt2 |   20.007s | 23.088MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/MC12-026__overlayed_objects__p.adb_31_28_overflow_check___00.smt2 |   20.007s | 23.064MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__test_failsafe.adb_13_19_assert___00.smt2 |   20.007s | 25.672MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.ads_58_17_unreachable_branch___00.smt2 |   20.007s | 25.436MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_20_22_unreachable_branch___00.smt2 |   20.008s | 23.5MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/MA16-036__flow_missing_globals__logger.adb_39_13_range_check___00.smt2 |   20.008s | 31.48MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_71_30_unreachable_branch___00.smt2 |   20.008s | 24.1MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_42_28_unreachable_branch___00.smt2 |   20.008s | 30.364MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_49_10_dead_code___00.smt2 |   20.008s | 29.084MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_57_28_unreachable_branch___00.smt2 |   20.008s | 30.608MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.ads_45_17_unreachable_branch___00.smt2 |   20.008s | 24.64MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_62_25_assert___00.smt2 |   20.008s | 30.8MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/MA16-036__flow_missing_globals__logger.adb_42_35_length_check___00.smt2 |   20.008s | 31.48MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.ads_46_21_unreachable_branch___00.smt2 |   20.008s | 30.06MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_40_27_unreachable_branch___00.smt2 |   20.008s | 29.044MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_53_30_unreachable_branch___00.smt2 |   20.008s | 29.964MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_19_18_unreachable_branch___00.smt2 |   20.008s | 23.396MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/MA16-036__flow_missing_globals__logger.adb_46_20_range_check___00.smt2 |   20.009s | 31.472MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_69_34_unreachable_branch___00.smt2 |   20.009s | 28.196MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_74_34_unreachable_branch___00.smt2 |   20.009s | 25.58MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_11_16_dead_code___00.smt2 |   20.009s | 24.864MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_42_59_unreachable_branch___00.smt2 |   20.009s | 23.672MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/MA16-036__flow_missing_globals__logger.adb_38_61_range_check___00.smt2 |   20.009s | 31.472MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.ads_63_17_unreachable_branch___00.smt2 |   20.009s | 23.844MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.ads_43_52_unreachable_branch___00.smt2 |   20.010s | 25.544MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/MC12-026__overlayed_objects__p2.adb_39_28_overflow_check___00.smt2 |   20.010s | 22.976MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/MA16-036__flow_missing_globals__logger.adb_46_20_length_check___00.smt2 |   20.010s | 31.472MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/MA16-036__flow_missing_globals__logger.ads_50_55_range_check___00.smt2 |   20.011s | 31.48MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/MA16-036__flow_missing_globals__logger.adb_42_35_range_check___00.smt2 |   20.011s | 31.472MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_41_22_assert___00.smt2 |   20.012s | 23.784MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__test_failsafe.adb_7_7_dead_code___00.smt2 |   20.013s | 29.248MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_39_52_unreachable_branch___00.smt2 |   20.014s | 25.572MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__test_failsafe.adb_9_23_dead_code___00.smt2 |   20.014s | 29.5MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.ads_37_14_unreachable_branch___00.smt2 |   20.014s | 24.856MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/MA16-036__flow_missing_globals__logger.adb_44_23_length_check___00.smt2 |   20.015s | 31.488MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_61_28_unreachable_branch___00.smt2 |   20.015s | 30.728MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.ads_56_14_postcondition___00.smt2 |   20.015s | 29.332MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/MA16-036__flow_missing_globals__logger.adb_42_23_length_check___00.smt2 |   20.015s | 31.492MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.ads_35_14_unreachable_branch___00.smt2 |   20.016s | 24.664MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/MA16-036__flow_missing_globals__logger.ads_50_9_postcondition___00.smt2 |   20.016s | 31.464MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/MA16-036__flow_missing_globals__logger.adb_46_31_range_check___00.smt2 |   20.016s | 31.484MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.ads_57_17_unreachable_branch___00.smt2 |   20.017s | 28.56MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.ads_41_21_unreachable_branch___00.smt2 |   20.017s | 24.424MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/MC12-026__overlayed_objects__p2.adb_40_28_fp_overflow_check___00.smt2 |   20.017s | 27.276MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_12_16_dead_code___00.smt2 |   20.017s | 24.04MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__test_failsafe.adb_7_7_precondition___00.smt2 |   20.017s | 25.648MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_71_65_unreachable_branch___00.smt2 |   20.018s | 29.8MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_73_30_unreachable_branch___00.smt2 |   20.018s | 29.496MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/MA16-036__flow_missing_globals__logger.adb_45_27_range_check___00.smt2 |   20.018s | 31.488MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.ads_55_13_inconsistent_pre___00.smt2 |   20.018s | 28.372MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__test_failsafe.adb_9_19_assert___00.smt2 |   20.018s | 29.576MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.ads_30_14_unreachable_branch___00.smt2 |   20.019s | 24.272MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__test_failsafe.adb_11_19_assert___00.smt2 |   20.019s | 24.344MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.ads_26_14_unreachable_branch___00.smt2 |   20.023s | 23.424MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_67_27_unreachable_branch___00.smt2 |   20.024s | 30.22MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.ads_39_14_unreachable_branch___00.smt2 |   20.024s | 29.776MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_65_69_range_check___00.smt2 |   20.024s | 30.068MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_63_62_unreachable_branch___00.smt2 |   20.024s | 23.768MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_76_25_assert___00.smt2 |   20.025s | 25.356MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.ads_43_17_unreachable_branch___00.smt2 |   20.025s | 24.604MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/OA21-028__failsafe__failsafe.adb_68_30_unreachable_branch___00.smt2 |   20.026s | 30.456MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFPDTNIRA/20200306-Kanig/spark2014bench/MC12-024__flow_crash__p.adb_32_28_fp_overflow_check___00.smt2 |   20.031s | 27.644MiB| timeout | 0 |  |  |
