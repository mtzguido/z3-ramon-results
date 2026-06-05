# .

* SAT 0
* UNSAT 775
* TIMEOUT 484
* UNKNOWN 0

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/UFBVDTNIRA.tar.zst?download=1 | Source list: quantifier_benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-UFBVDTNIRA.tar.zst
Runner: rise-runner-1
Z3 repo: Z3Prover/z3
Z3 commit: c3f5365a95a7eac2419a2f95ff240909f275cc08
Z3 branch: c3f5365a95a7eac2419a2f95ff240909f275cc08
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/UFBVDTNIRA.tar.zst?download=1
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
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/R322-003__private_modular__mod_subtypes.ads_7_52_division_check___00.smt2 |    0.015s | 19.12MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.adb_203_29_range_check___00.smt2 |    0.015s | 19.236MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/NC23-020__bitwise__x86.ads_37_14_postcondition___00.smt2 |    0.015s | 19.332MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_17_65_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_range_check___00.smt2 |    0.015s | 19.308MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/NC16-020__bitwise__x86.adb_27_29_range_check___00.smt2 |    0.015s | 19.116MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_90_15_overflow_check___00.smt2 |    0.015s | 19.28MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/NC26-004__bitwise__x86.adb_13_22_assert___00.smt2 |    0.015s | 19.14MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.adb_359_28_range_check___00.smt2 |    0.015s | 19.22MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_129_14_postcondition___00.smt2 |    0.016s | 19.184MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_111_45_range_check___00.smt2 |    0.016s | 19.164MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.adb_317_28_range_check___00.smt2 |    0.016s | 19.112MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_90_14_postcondition___00.smt2 |    0.016s | 19.268MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_68_14_postcondition___00.smt2 |    0.016s | 19.204MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.adb_61_28_range_check___00.smt2 |    0.016s | 19.264MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_371_43_range_check___00.smt2 |    0.016s | 19.292MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_181_42_range_check___00.smt2 |    0.016s | 19.272MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_258_16_postcondition___00.smt2 |    0.016s | 19.42MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/NC23-020__bitwise__x86.adb_17_59_division_check___00.smt2 |    0.016s | 19.12MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/N613-007__shift__my_shift.adb_7_32_division_check___00.smt2 |    0.016s | 19.184MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_72_45_range_check___00.smt2 |    0.016s | 19.048MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/riposte__alpha_launch_examples__alpha_launch_examples.adb_65_22_postcondition___00.smt2 |    0.016s | 19.104MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_371_43_range_check___00.smt2 |    0.016s | 19.24MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-022__bitwise_rotate__test_rotate.adb_25_9_precondition___00.smt2 |    0.016s | 19.072MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/NC16-020__bitwise__x86.ads_37_42_range_check___00.smt2 |    0.016s | 19.148MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_193_16_postcondition___00.smt2 |    0.016s | 19.24MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.adb_275_29_range_check___00.smt2 |    0.016s | 19.264MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_250_42_range_check___00.smt2 |    0.016s | 19.22MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_405_14_postcondition___00.smt2 |    0.016s | 19.284MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P914-008__trivial_test__spark-mod_arithmetic_lemmas.ads_99_51_spark-mod64_arithmetic_lemmas.ads_33_1_division_check___00.smt2 |    0.016s | 19.184MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/N624-030__funcs_on_containers__find_map.ads_23_30_range_check___00.smt2 |    0.016s | 19.072MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/NC23-020__bitwise__x86.adb_27_29_range_check___00.smt2 |    0.016s | 19.272MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_133_72_division_check___00.smt2 |    0.016s | 19.304MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_181_42_range_check___00.smt2 |    0.016s | 19.22MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_94_14_postcondition___00.smt2 |    0.016s | 19.144MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_66_15_overflow_check___00.smt2 |    0.016s | 19.308MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/MC06-019__shift_divide__p.ads_13_29_division_check___00.smt2 |    0.016s | 19.084MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P114-046__invariant__inrange2.adb_19_32_loop_invariant_preserv___00.smt2 |    0.016s | 19.156MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_142_42_range_check___00.smt2 |    0.016s | 19.168MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/NC26-004__bitwise__x86.ads_17_14_postcondition___00.smt2 |    0.016s | 19.24MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_258_16_postcondition___00.smt2 |    0.016s | 19.248MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P113-023__alias_issue__aalias.adb_12_16_postcondition___00.smt2 |    0.016s | 19.236MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P914-008__trivial_test__spark-mod_arithmetic_lemmas.ads_127_32_spark-mod64_arithmetic_lemmas.ads_33_1_division_check___00.smt2 |    0.016s | 19.256MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.adb_251_29_range_check___00.smt2 |    0.016s | 19.256MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/QA31-008__von_neumann_sqrt__p.adb_88_30_range_check___00.smt2 |    0.016s | 19.292MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/NC26-004__bitwise__x86.adb_7_22_assert___00.smt2 |    0.016s | 19.184MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/NC16-020__bitwise__x86.ads_28_72_division_check___00.smt2 |    0.016s | 19.184MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_212_45_range_check___00.smt2 |    0.016s | 19.18MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/NC23-020__bitwise__x86.ads_28_14_postcondition___00.smt2 |    0.016s | 19.284MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/NC16-020__bitwise__x86.ads_45_45_range_check___00.smt2 |    0.016s | 19.06MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/K915-006__modular__pack.adb_27_22_division_check___00.smt2 |    0.016s | 19.152MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_326_14_postcondition___00.smt2 |    0.016s | 19.28MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_47_14_postcondition___00.smt2 |    0.016s | 19.184MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_235_45_range_check___00.smt2 |    0.016s | 19.06MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P114-046__invariant__inrange1.adb_14_32_loop_invariant_preserv___00.smt2 |    0.016s | 19.304MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_326_43_range_check___00.smt2 |    0.016s | 19.152MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_64_14_postcondition___00.smt2 |    0.016s | 19.084MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/NC16-020__bitwise__x86.ads_20_41_range_check___00.smt2 |    0.017s | 19.252MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/NC16-020__bitwise__x86.ads_41_14_postcondition___00.smt2 |    0.017s | 19.24MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P114-046__invariant__inrange4.adb_16_33_loop_invariant_init___00.smt2 |    0.017s | 19.228MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.adb_289_27_range_check___00.smt2 |    0.017s | 19.36MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_185_14_postcondition___00.smt2 |    0.017s | 19.288MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/proofinuse__bitwise__bitwise.adb_38_34_range_check___00.smt2 |    0.017s | 19.224MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/KC02-007__modulo__p.ads_19_20_postcondition___00.smt2 |    0.017s | 19.048MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_360_14_postcondition___00.smt2 |    0.017s | 19.06MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/RB12-066__fixed_point_div_mod__types.ads_16_13_overflow_check___00.smt2 |    0.017s | 19.124MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/R831-037__formal_map__p.ads_31_19_range_check___00.smt2 |    0.017s | 19.204MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_138_8_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_precondition___00.smt2 |    0.017s | 19.336MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.adb_303_27_range_check___00.smt2 |    0.017s | 19.196MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_311_14_postcondition___00.smt2 |    0.017s | 19.276MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_231_14_postcondition___00.smt2 |    0.017s | 19.272MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_273_42_range_check___00.smt2 |    0.017s | 19.208MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/riposte__arrays_multidim__arrays_multidim.adb_52_22_postcondition___00.smt2 |    0.017s | 19.336MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.adb_17_28_range_check___00.smt2 |    0.017s | 19.152MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_281_45_range_check___00.smt2 |    0.017s | 19.188MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_47_41_range_check___00.smt2 |    0.017s | 19.192MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/NC23-020__bitwise__x86.ads_49_16_postcondition___00.smt2 |    0.017s | 19.296MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/N716-019__div__my_div.ads_7_31_division_check___00.smt2 |    0.017s | 19.172MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/N624-030__funcs_on_containers__find_map.ads_24_30_range_check___00.smt2 |    0.017s | 19.164MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_103_42_range_check___00.smt2 |    0.017s | 19.224MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.adb_105_28_range_check___00.smt2 |    0.017s | 19.24MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_48_14_division_check___00.smt2 |    0.017s | 19.26MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.adb_193_29_range_check___00.smt2 |    0.017s | 19.192MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SA16-042__alignment__bug_align.adb_8_48_range_check___00.smt2 |    0.017s | 19.284MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_371_14_postcondition___00.smt2 |    0.017s | 19.172MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P114-046__invariant__inrange6.ads_18_44_range_check___00.smt2 |    0.017s | 19.1MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/NC16-020__bitwise__x86.ads_45_16_postcondition___00.smt2 |    0.017s | 19.296MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/N811-037__bitwise__x86.ads_13_14_postcondition___00.smt2 |    0.017s | 19.28MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_285_16_postcondition___00.smt2 |    0.017s | 19.048MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_115_16_postcondition___00.smt2 |    0.017s | 19.3MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P512-044__exist_on_bv__x86.adb_79_22_x86.adb_99_7_loop_invariant_init___00.smt2 |    0.017s | 19.172MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P114-046__invariant__inrange2.adb_20_33_loop_invariant_preserv___00.smt2 |    0.017s | 19.212MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_227_42_range_check___00.smt2 |    0.017s | 19.292MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_250_14_postcondition___00.smt2 |    0.017s | 19.128MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_273_42_range_check___00.smt2 |    0.017s | 19.136MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P114-046__invariant__inrange3.adb_14_12_loop_invariant_preserv___00.smt2 |    0.017s | 19.136MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.adb_37_29_range_check___00.smt2 |    0.017s | 19.22MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O427-011__non_pow2_modulo__t.adb_16_59_division_check___00.smt2 |    0.017s | 19.42MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_401_43_range_check___00.smt2 |    0.017s | 19.304MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_341_14_postcondition___00.smt2 |    0.017s | 19.128MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.adb_81_29_range_check___00.smt2 |    0.017s | 19.152MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_154_16_postcondition___00.smt2 |    0.017s | 19.252MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/NC23-020__bitwise__x86.ads_37_42_range_check___00.smt2 |    0.017s | 19.252MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P429-003__list_of_bv__a-cfdlli.ads_1478_23_foo.adb_10_4_precondition___00.smt2 |    0.017s | 19.624MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/NC16-020__bitwise__x86.ads_28_14_postcondition___00.smt2 |    0.017s | 19.192MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_401_14_postcondition___00.smt2 |    0.017s | 19.28MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P114-046__invariant__inrange4.adb_17_33_loop_invariant_init___00.smt2 |    0.017s | 19.18MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/NC23-020__bitwise__x86.adb_37_29_range_check___00.smt2 |    0.017s | 19.064MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_96_14_division_check___00.smt2 |    0.017s | 19.236MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.adb_359_28_range_check___00.smt2 |    0.017s | 19.048MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/NC23-020__bitwise__x86.ads_45_45_range_check___00.smt2 |    0.017s | 19.232MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_8_61_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_range_check___00.smt2 |    0.017s | 19.252MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.adb_159_55_range_check___00.smt2 |    0.017s | 19.06MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.adb_373_28_range_check___00.smt2 |    0.017s | 19.232MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/R322-036__ali__a~main.adb_11_14_division_check___00.smt2 |    0.017s | 19.156MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/NC16-020__bitwise__x86.ads_37_14_postcondition___00.smt2 |    0.017s | 19.24MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_98_14_postcondition___00.smt2 |    0.017s | 19.176MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_231_14_postcondition___00.smt2 |    0.017s | 19.316MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_114_15_overflow_check___00.smt2 |    0.017s | 19.124MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P512-044__exist_on_bv__x86.adb_66_19_x86.adb_99_7_loop_invariant_init___00.smt2 |    0.017s | 19.272MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_330_14_postcondition___00.smt2 |    0.017s | 19.192MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/proofinuse__bitwise__bitwise.adb_33_22_assert___00.smt2 |    0.017s | 19.184MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_475_14_postcondition___00.smt2 |    0.017s | 19.292MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/RC17-047__generic_warn__a-timoio.ads_56_40_init.adb_7_4_precondition___00.smt2 |    0.017s | 19.292MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O427-011__non_pow2_modulo__t3.adb_16_59_division_check___00.smt2 |    0.017s | 19.136MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P914-008__trivial_test__spark-mod_arithmetic_lemmas.ads_80_52_spark-mod32_arithmetic_lemmas.ads_33_1_division_check___00.smt2 |    0.017s | 19.1MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O427-011__non_pow2_modulo__t2.adb_35_59_division_check___00.smt2 |    0.017s | 19.256MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_300_14_postcondition___00.smt2 |    0.017s | 19.248MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_296_41_range_check___00.smt2 |    0.017s | 19.096MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/N127-046__mod__mod_bound.ads_6_20_postcondition___00.smt2 |    0.017s | 19.228MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_47_14_postcondition___00.smt2 |    0.017s | 19.216MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.adb_387_28_range_check___00.smt2 |    0.017s | 19.216MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.adb_227_29_range_check___00.smt2 |    0.017s | 19.064MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/RB12-066__fixed_point_div_mod__types.ads_6_12_division_check___00.smt2 |    0.017s | 19.232MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_330_14_postcondition___00.smt2 |    0.017s | 19.188MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_125_14_postcondition___00.smt2 |    0.017s | 19.176MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_181_14_postcondition___00.smt2 |    0.017s | 19.128MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.adb_265_29_range_check___00.smt2 |    0.017s | 19.236MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.adb_135_29_range_check___00.smt2 |    0.017s | 19.104MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_386_14_postcondition___00.smt2 |    0.017s | 19.14MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P914-008__trivial_test__spark-mod_arithmetic_lemmas.ads_119_32_spark-mod64_arithmetic_lemmas.ads_33_1_division_check___00.smt2 |    0.017s | 19.244MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/NC16-020__bitwise__x86.adb_37_29_range_check___00.smt2 |    0.017s | 19.124MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_133_72_division_check___00.smt2 |    0.017s | 19.3MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.adb_227_29_range_check___00.smt2 |    0.017s | 19.068MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.adb_71_59_division_check___00.smt2 |    0.017s | 19.2MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P820-002__protected_out__polyorb_hi-utils.adb_89_20_division_check___00.smt2 |    0.017s | 19.22MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_189_16_postcondition___00.smt2 |    0.017s | 19.116MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_311_14_postcondition___00.smt2 |    0.017s | 19.112MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_72_14_division_check___00.smt2 |    0.017s | 19.28MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.adb_373_28_range_check___00.smt2 |    0.017s | 19.284MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_277_14_postcondition___00.smt2 |    0.017s | 19.172MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.adb_241_29_range_check___00.smt2 |    0.017s | 19.22MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.adb_17_28_range_check___00.smt2 |    0.017s | 19.292MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/RB12-066__fixed_point_div_mod__types.ads_10_12_overflow_check___00.smt2 |    0.017s | 19.22MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_24_14_division_check___00.smt2 |    0.017s | 19.232MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_300_14_postcondition___00.smt2 |    0.017s | 19.224MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_86_14_postcondition___00.smt2 |    0.017s | 19.272MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O318-035__modular__smod.adb_8_30_range_check___00.smt2 |    0.017s | 19.256MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_162_15_overflow_check___00.smt2 |    0.017s | 19.2MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.adb_37_29_range_check___00.smt2 |    0.017s | 19.112MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/N716-019__div__my_div.adb_13_14_division_check___00.smt2 |    0.017s | 19.192MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.adb_317_28_range_check___00.smt2 |    0.017s | 19.3MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.adb_105_28_range_check___00.smt2 |    0.017s | 19.068MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_356_14_postcondition___00.smt2 |    0.017s | 19.188MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_208_14_postcondition___00.smt2 |    0.017s | 19.316MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_281_16_postcondition___00.smt2 |    0.017s | 19.044MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_72_16_postcondition___00.smt2 |    0.017s | 19.056MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/N811-037__bitwise__x86.ads_13_42_range_check___00.smt2 |    0.018s | 19.184MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_153_32_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_precondition___00.smt2 |    0.018s | 19.184MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_125_41_range_check___00.smt2 |    0.018s | 19.18MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_235_45_range_check___00.smt2 |    0.018s | 19.28MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_138_8_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_precondition___00.smt2 |    0.018s | 19.352MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_189_45_range_check___00.smt2 |    0.018s | 19.048MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_44_8_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_precondition___00.smt2 |    0.018s | 19.236MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_204_14_postcondition___00.smt2 |    0.018s | 19.28MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_216_16_postcondition___00.smt2 |    0.018s | 19.184MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_18_15_overflow_check___00.smt2 |    0.018s | 19.156MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_150_45_range_check___00.smt2 |    0.018s | 19.256MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_94_72_division_check___00.smt2 |    0.018s | 19.14MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/MC06-015__contracts_on_intrinsics__p.adb_9_13_precondition___00.smt2 |    0.018s | 19.236MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.adb_387_28_range_check___00.smt2 |    0.018s | 19.264MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P114-046__invariant__inrange1.adb_16_33_loop_invariant_preserv___00.smt2 |    0.018s | 19.148MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_227_14_postcondition___00.smt2 |    0.018s | 19.368MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.adb_149_28_range_check___00.smt2 |    0.018s | 19.26MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_235_16_postcondition___00.smt2 |    0.018s | 19.192MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O427-011__non_pow2_modulo__t3.adb_35_59_division_check___00.smt2 |    0.018s | 19.264MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_208_14_postcondition___00.smt2 |    0.018s | 19.108MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.adb_265_29_range_check___00.smt2 |    0.018s | 19.264MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_212_45_range_check___00.smt2 |    0.018s | 19.32MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_164_41_range_check___00.smt2 |    0.018s | 19.296MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_164_32_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_precondition___00.smt2 |    0.018s | 19.364MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_356_43_range_check___00.smt2 |    0.018s | 19.544MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/NC23-020__bitwise__x86.adb_7_28_range_check___00.smt2 |    0.018s | 19.188MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_326_43_range_check___00.smt2 |    0.018s | 19.236MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_296_14_postcondition___00.smt2 |    0.018s | 19.296MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_164_14_postcondition___00.smt2 |    0.018s | 19.256MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P114-046__invariant__inrange1.adb_16_33_loop_invariant_init___00.smt2 |    0.018s | 19.288MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_277_14_postcondition___00.smt2 |    0.018s | 19.236MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O427-011__non_pow2_modulo__t2.adb_16_59_division_check___00.smt2 |    0.018s | 19.288MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/RB12-066__fixed_point_int_mult__types.ads_28_12_overflow_check___00.smt2 |    0.018s | 19.164MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/R831-037__formal_map__p.ads_32_19_range_check___00.smt2 |    0.018s | 19.028MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_42_15_overflow_check___00.smt2 |    0.018s | 19.124MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_27_16_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_postcondition___00.smt2 |    0.018s | 19.128MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/N613-007__bitwise__sandbox.adb_15_32_range_check___00.smt2 |    0.018s | 19.1MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_10_62_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_range_check___00.smt2 |    0.018s | 19.312MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.adb_169_29_range_check___00.smt2 |    0.018s | 19.44MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_55_72_division_check___00.smt2 |    0.018s | 19.304MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_107_14_postcondition___00.smt2 |    0.018s | 19.136MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/proofinuse__bitwise__bitwise.adb_14_22_assert___00.smt2 |    0.018s | 19.196MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.adb_251_29_range_check___00.smt2 |    0.018s | 19.144MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P429-003__list_of_bv__a-cfdlli.ads_1349_20_foo.adb_10_4_precondition___00.smt2 |    0.018s | 19.624MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P630-037__keccak__keccak-types.ads_136_39_precondition___00.smt2 |    0.018s | 19.74MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_168_14_postcondition___00.smt2 |    0.018s | 19.052MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P512-044__exist_on_bv__x86.ads_16_44_range_check___00.smt2 |    0.018s | 19.268MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O318-035__modular__smod.adb_8_38_range_check___00.smt2 |    0.018s | 19.2MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_212_16_postcondition___00.smt2 |    0.018s | 19.276MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.adb_61_28_range_check___00.smt2 |    0.018s | 19.08MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_74_26_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_precondition___00.smt2 |    0.018s | 19.212MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/Q601-014__abstract_state__achiever.ads_35_6_disjoint_contract_cases___00.smt2 |    0.018s | 19.88MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_15_64_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_range_check___00.smt2 |    0.018s | 19.176MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.adb_81_29_range_check___00.smt2 |    0.018s | 19.224MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.adb_345_28_range_check___00.smt2 |    0.018s | 19.1MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P114-046__invariant__inrange1.adb_14_32_loop_invariant_init___00.smt2 |    0.018s | 19.216MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_189_45_range_check___00.smt2 |    0.018s | 19.256MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/NC23-020__bitwise__x86.ads_24_14_postcondition___00.smt2 |    0.018s | 19.248MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_103_14_postcondition___00.smt2 |    0.018s | 19.3MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_390_14_postcondition___00.smt2 |    0.018s | 19.204MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/proofinuse__bitwise__bitwise.adb_7_22_assert___00.smt2 |    0.018s | 19.228MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_401_14_postcondition___00.smt2 |    0.018s | 19.06MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_172_72_division_check___00.smt2 |    0.018s | 19.272MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_72_45_range_check___00.smt2 |    0.018s | 19.092MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/RC17-047__generic_warn__a-timoio.ads_76_8_init.adb_7_4_precondition___00.smt2 |    0.018s | 19.336MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_345_14_postcondition___00.smt2 |    0.018s | 19.076MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/NC23-020__bitwise__x86.ads_41_14_postcondition___00.smt2 |    0.018s | 19.136MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/J506-016__scaled_value__spark-mod_arithmetic_lemmas.ads_110_54_spark-mod64_arithmetic_lemmas.ads_33_1_division_check___00.smt2 |    0.018s | 19.232MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_86_41_range_check___00.smt2 |    0.018s | 19.264MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O226-018__address__worker_pack.adb_13_91_division_check___00.smt2 |    0.018s | 19.384MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/NC16-020__bitwise__x86.ads_20_14_postcondition___00.smt2 |    0.018s | 19.272MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.adb_115_55_range_check___00.smt2 |    0.018s | 19.288MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_55_72_division_check___00.smt2 |    0.018s | 19.068MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_405_14_postcondition___00.smt2 |    0.018s | 19.196MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_129_14_postcondition___00.smt2 |    0.018s | 19.144MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_401_43_range_check___00.smt2 |    0.018s | 19.104MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_138_15_overflow_check___00.smt2 |    0.018s | 19.304MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_146_14_postcondition___00.smt2 |    0.018s | 19.212MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_113_12_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_postcondition___00.smt2 |    0.018s | 19.296MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_76_16_postcondition___00.smt2 |    0.018s | 19.076MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_250_14_postcondition___00.smt2 |    0.018s | 19.284MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.adb_27_55_division_check___00.smt2 |    0.018s | 19.168MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O630-015__modular_conversion__main.adb_15_32_range_check___00.smt2 |    0.018s | 19.24MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P914-008__trivial_test__spark-mod_arithmetic_lemmas.ads_110_54_spark-mod32_arithmetic_lemmas.ads_33_1_division_check___00.smt2 |    0.018s | 19.268MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/K915-006__modular__pack.ads_18_19_postcondition___00.smt2 |    0.018s | 19.232MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_104_8_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_precondition___00.smt2 |    0.019s | 19.192MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.adb_217_29_range_check___00.smt2 |    0.019s | 19.316MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_150_16_postcondition___00.smt2 |    0.019s | 19.284MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_150_16_postcondition___00.smt2 |    0.019s | 19.188MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P914-008__trivial_test__spark-mod_arithmetic_lemmas.ads_90_32_spark-mod64_arithmetic_lemmas.ads_33_1_division_check___00.smt2 |    0.019s | 19.204MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_135_12_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_postcondition___00.smt2 |    0.019s | 19.24MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_107_12_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_postcondition___00.smt2 |    0.019s | 19.352MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/M603-021__volatile_input_proofs__port.ads_73_34_postcondition___00.smt2 |    0.019s | 19.304MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/L719-025__hashed_maps_equal__a-cfhama.ads_720_20_p.ads_13_4_precondition___00.smt2 |    0.019s | 19.42MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/R511-031__counterexample__saturation.adb_11_6_complete_contract_cases___00.smt2 |    0.019s | 19.416MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_9_62_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_range_check___00.smt2 |    0.019s | 19.28MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_74_26_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_precondition___00.smt2 |    0.019s | 19.284MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_150_45_range_check___00.smt2 |    0.019s | 19.128MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_113_12_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_postcondition___00.smt2 |    0.019s | 19.232MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_153_32_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_precondition___00.smt2 |    0.019s | 19.324MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/RB12-066__fixed_point_int_mult__types.ads_16_13_overflow_check___00.smt2 |    0.019s | 19.324MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.adb_71_55_range_check___00.smt2 |    0.019s | 19.128MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/S329-030__bound_exponentiation__spark-mod_arithmetic_lemmas.ads_127_32_spark-mod32_arithmetic_lemmas.ads_33_1_division_check___00.smt2 |    0.019s | 19.228MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/RB12-066__fixed_point_int_mult__types.ads_10_12_overflow_check___00.smt2 |    0.019s | 19.108MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__dynamicsaturateassert.adb_71_22_assert___00.smt2 |    0.019s | 19.292MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_44_8_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_precondition___00.smt2 |    0.019s | 19.236MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_476_14_postcondition___00.smt2 |    0.019s | 19.244MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P512-044__exist_on_bv__x86.adb_45_37_x86.adb_99_7_assert___00.smt2 |    0.019s | 19.244MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/RB12-066__fixed_point_div_mod__types.ads_6_12_overflow_check___00.smt2 |    0.019s | 19.384MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.adb_303_27_range_check___00.smt2 |    0.019s | 19.276MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.adb_275_29_range_check___00.smt2 |    0.019s | 19.136MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/M603-021__volatile_input_proofs__port.ads_98_34_postcondition___00.smt2 |    0.019s | 19.072MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/L719-025__hashed_maps_equal__a-cfhama.ads_681_39_p.ads_13_4_precondition___00.smt2 |    0.019s | 19.372MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P429-003__list_of_bv__a-cofuve.ads_300_52_a-cfdlli.ads_69_7_foo.adb_10_4_overflow_check___00.smt2 |    0.019s | 19.316MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/J506-016__scaled_value__spark-mod_arithmetic_lemmas.ads_119_32_spark-mod32_arithmetic_lemmas.ads_33_1_division_check___00.smt2 |    0.019s | 19.08MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/S504-004__no_optim__various_no_optim.adb_18_13_precondition___00.smt2 |    0.019s | 19.116MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.adb_115_55_division_check___00.smt2 |    0.019s | 19.184MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/NC23-020__bitwise__x86.ads_45_16_postcondition___00.smt2 |    0.019s | 19.396MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/M603-021__volatile_input_proofs__port.ads_83_34_postcondition___00.smt2 |    0.019s | 19.164MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_390_14_postcondition___00.smt2 |    0.019s | 19.084MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_103_14_postcondition___00.smt2 |    0.019s | 19.128MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_93_30_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_range_check___00.smt2 |    0.019s | 19.32MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P114-046__invariant__inrange1.adb_14_70_range_check___00.smt2 |    0.019s | 19.08MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_113_12_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_postcondition___00.smt2 |    0.019s | 19.332MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_107_14_postcondition___00.smt2 |    0.019s | 19.068MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_386_43_range_check___00.smt2 |    0.019s | 19.24MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P429-003__list_of_bv__a-cfdlli.ads_1394_20_foo.adb_10_4_precondition___00.smt2 |    0.019s | 19.408MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P114-046__invariant__inrange3.adb_14_12_loop_invariant_init___00.smt2 |    0.019s | 19.244MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/J506-016__scaled_value__spark-mod_arithmetic_lemmas.ads_69_26_spark-mod32_arithmetic_lemmas.ads_33_1_division_check___00.smt2 |    0.019s | 19.28MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_181_14_postcondition___00.smt2 |    0.019s | 19.26MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.adb_331_28_range_check___00.smt2 |    0.019s | 19.128MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P114-046__invariant__inrange2.ads_18_44_range_check___00.smt2 |    0.019s | 19.188MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_47_18_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_postcondition___00.smt2 |    0.019s | 19.308MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_176_14_postcondition___00.smt2 |    0.019s | 19.452MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_64_14_postcondition___00.smt2 |    0.019s | 19.244MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/J506-016__scaled_value__spark-mod_arithmetic_lemmas.ads_69_26_spark-mod64_arithmetic_lemmas.ads_33_1_division_check___00.smt2 |    0.019s | 19.092MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/OA20-032__refinement__patris.adb_432_56_division_check___00.smt2 |    0.019s | 19.228MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_254_14_postcondition___00.smt2 |    0.019s | 19.276MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_55_8_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_precondition___00.smt2 |    0.019s | 19.36MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_9_62_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_range_check___00.smt2 |    0.019s | 19.336MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_254_14_postcondition___00.smt2 |    0.019s | 19.128MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_153_32_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_precondition___00.smt2 |    0.019s | 19.336MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_386_14_postcondition___00.smt2 |    0.019s | 19.26MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/NC16-020__bitwise__x86.adb_7_28_range_check___00.smt2 |    0.019s | 19.124MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/RB12-066__fixed_point_div_mod__types.ads_22_13_range_check___01.smt2 |    0.019s | 19.236MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_104_8_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_precondition___00.smt2 |    0.019s | 19.216MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_235_16_postcondition___00.smt2 |    0.019s | 19.128MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.adb_91_29_range_check___00.smt2 |    0.019s | 19.292MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_138_8_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_precondition___00.smt2 |    0.019s | 19.188MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/RB12-066__fixed_point_int_mult__types.ads_6_12_range_check___00.smt2 |    0.019s | 19.204MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_212_16_postcondition___00.smt2 |    0.019s | 19.24MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_189_16_postcondition___00.smt2 |    0.019s | 19.232MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.adb_47_29_range_check___00.smt2 |    0.019s | 19.28MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P512-044__exist_on_bv__x86.adb_66_19_x86.adb_99_7_loop_invariant_preserv___00.smt2 |    0.019s | 19.352MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_15_64_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_range_check___00.smt2 |    0.019s | 19.184MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_155_32_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_precondition___00.smt2 |    0.019s | 19.26MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_375_14_postcondition___00.smt2 |    0.019s | 19.304MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_160_32_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_precondition___00.smt2 |    0.019s | 19.14MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_55_14_postcondition___00.smt2 |    0.019s | 19.116MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/N724-026__discrim__discrimrec.adb_6_45_range_check___00.smt2 |    0.019s | 19.476MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_133_14_postcondition___00.smt2 |    0.019s | 19.232MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_162_32_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_precondition___00.smt2 |    0.019s | 19.24MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P429-003__list_of_bv__a-cfdlli.ads_1379_20_foo.adb_10_4_precondition___00.smt2 |    0.019s | 19.376MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_137_14_postcondition___00.smt2 |    0.019s | 19.588MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/S527-028__size__repro.ads_11_4_range_check___00.smt2 |    0.019s | 19.18MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_162_32_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_precondition___00.smt2 |    0.019s | 19.348MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P429-003__list_of_bv__foo.adb_17_17_range_check___00.smt2 |    0.019s | 19.416MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_192_14_division_check___00.smt2 |    0.019s | 19.316MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_273_14_postcondition___00.smt2 |    0.019s | 19.212MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/proofinuse__bitwise__bitwise.adb_6_53_range_check___00.smt2 |    0.019s | 19.28MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_141_12_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_postcondition___00.smt2 |    0.019s | 19.112MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_8_61_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_range_check___00.smt2 |    0.019s | 19.24MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_55_8_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_precondition___00.smt2 |    0.019s | 19.248MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_162_32_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_precondition___00.smt2 |    0.019s | 19.16MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/L719-025__hashed_sets_equal__a-cfhase.ads_497_18_p.ads_12_4_precondition___00.smt2 |    0.019s | 19.284MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P114-046__invariant__inrange4.adb_17_33_loop_invariant_preserv___00.smt2 |    0.019s | 19.232MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/L719-025__hashed_sets_equal__p.adb_24_10_precondition___00.smt2 |    0.019s | 19.328MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/L719-025__hashed_maps_equal__a-cfhama.ads_735_20_p.ads_13_4_precondition___00.smt2 |    0.019s | 19.22MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_151_32_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_precondition___00.smt2 |    0.019s | 19.128MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.adb_179_29_range_check___00.smt2 |    0.019s | 19.136MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_311_41_range_check___00.smt2 |    0.019s | 19.18MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_164_14_postcondition___00.smt2 |    0.019s | 19.256MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_142_14_postcondition___00.smt2 |    0.019s | 19.144MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_172_14_postcondition___00.smt2 |    0.019s | 19.116MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P512-044__exist_on_bv__x86.adb_92_28_x86.adb_99_7_assert___00.smt2 |    0.020s | 19.308MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_107_12_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_postcondition___00.smt2 |    0.020s | 19.252MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_164_32_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_precondition___00.smt2 |    0.020s | 19.2MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.adb_149_28_range_check___00.smt2 |    0.020s | 19.292MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/L102-013__bitwise__p.adb_3_24_division_check___00.smt2 |    0.020s | 19.236MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P114-046__invariant__inrange1.ads_18_44_range_check___00.smt2 |    0.020s | 19.188MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_168_14_postcondition___00.smt2 |    0.020s | 19.296MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_104_8_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_precondition___00.smt2 |    0.020s | 19.192MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_44_8_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_precondition___00.smt2 |    0.020s | 19.312MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_104_8_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_precondition___00.smt2 |    0.020s | 19.34MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.adb_159_55_division_check___00.smt2 |    0.020s | 19.16MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/L719-025__hashed_maps_equal__p.adb_5_7_precondition___00.smt2 |    0.020s | 19.392MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_239_16_postcondition___00.smt2 |    0.020s | 19.072MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/RB12-066__fixed_point_div_mod__types.ads_16_13_division_check___00.smt2 |    0.020s | 19.148MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_326_14_postcondition___00.smt2 |    0.020s | 19.128MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_262_16_postcondition___00.smt2 |    0.020s | 19.076MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_107_12_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_postcondition___00.smt2 |    0.020s | 19.26MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P114-046__invariant__inrange3.ads_18_44_range_check___00.smt2 |    0.020s | 19.584MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/Q601-014__abstract_state__achiever.ads_35_6_complete_contract_cases___00.smt2 |    0.020s | 19.544MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_250_42_range_check___00.smt2 |    0.020s | 19.124MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/S619-026__equality__a-cfhama.ads_690_17_prim_eq_vect.adb_18_4_precondition___00.smt2 |    0.020s | 19.408MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_27_16_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_postcondition___00.smt2 |    0.020s | 19.312MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_58_18_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_postcondition___00.smt2 |    0.020s | 19.328MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/N724-026__discrim__discrimrec.adb_5_45_range_check___00.smt2 |    0.020s | 19.328MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_345_14_postcondition___00.smt2 |    0.020s | 19.288MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/N811-037__bitwise__x86.ads_17_14_postcondition___00.smt2 |    0.020s | 19.256MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/L719-025__hashed_sets_key__p.adb_4_27_precondition___00.smt2 |    0.020s | 19.36MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_111_45_range_check___00.smt2 |    0.020s | 19.284MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/S329-030__bound_exponentiation__spark-mod_arithmetic_lemmas.ads_111_38_spark-mod64_arithmetic_lemmas.ads_33_1_division_check___00.smt2 |    0.020s | 19.132MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/L719-025__hashed_sets_equal__p.ads_24_12_precondition___00.smt2 |    0.020s | 19.396MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_8_61_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_range_check___00.smt2 |    0.020s | 19.172MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/NC23-020__bitwise__x86.ads_20_14_postcondition___00.smt2 |    0.020s | 19.12MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_17_20_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_postcondition___00.smt2 |    0.020s | 19.276MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O630-015__modular_conversion__main.adb_15_46_range_check___00.smt2 |    0.020s | 19.288MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P429-003__list_of_bv__a-cfdlli.ads_853_39_foo.adb_10_4_precondition___00.smt2 |    0.020s | 19.4MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/NC23-020__bitwise__x86.ads_20_41_range_check___00.smt2 |    0.020s | 19.284MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_70_26_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_precondition___00.smt2 |    0.020s | 19.264MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/S619-026__equality__prim_eq_vect.adb_28_26_precondition___00.smt2 |    0.020s | 19.284MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/L719-025__hashed_sets_equal__p.adb_9_7_precondition___00.smt2 |    0.020s | 19.58MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_186_15_overflow_check___00.smt2 |    0.020s | 19.324MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/S619-026__equality__a-cfhama.ads_720_20_prim_eq_vect.adb_18_4_precondition___00.smt2 |    0.020s | 19.58MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_480_14_postcondition___00.smt2 |    0.020s | 19.28MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_27_16_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_postcondition___00.smt2 |    0.020s | 19.356MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_15_64_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_range_check___00.smt2 |    0.020s | 19.124MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/N724-026__discrim__discrimrec.ads_31_34_range_check___00.smt2 |    0.020s | 19.472MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_141_12_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_postcondition___00.smt2 |    0.020s | 19.36MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_227_14_postcondition___00.smt2 |    0.020s | 19.304MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.adb_193_29_range_check___00.smt2 |    0.020s | 19.076MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/L719-025__hashed_sets_key__a-cfhase.ads_1202_20_p.ads_12_4_precondition___00.smt2 |    0.020s | 19.488MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_164_41_range_check___00.smt2 |    0.020s | 19.236MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.adb_47_29_range_check___00.smt2 |    0.020s | 19.256MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_113_12_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_postcondition___00.smt2 |    0.020s | 19.248MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_72_26_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_precondition___00.smt2 |    0.020s | 19.348MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_151_32_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_precondition___00.smt2 |    0.020s | 19.348MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_151_32_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_precondition___00.smt2 |    0.020s | 19.276MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_341_14_postcondition___00.smt2 |    0.021s | 19.284MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P429-003__list_of_bv__a-cfdlli.ads_1364_20_foo.adb_10_4_precondition___00.smt2 |    0.021s | 19.18MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_258_45_range_check___00.smt2 |    0.021s | 19.22MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_72_26_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_precondition___00.smt2 |    0.021s | 19.56MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_296_14_postcondition___00.smt2 |    0.021s | 19.228MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_55_8_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_precondition___00.smt2 |    0.021s | 19.3MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_70_26_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_precondition___00.smt2 |    0.021s | 19.228MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O427-011__non_pow2_modulo__t.adb_35_59_division_check___00.smt2 |    0.021s | 19.172MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/L719-025__hashed_sets_key__a-cfhase.ads_497_18_p.ads_12_4_precondition___00.smt2 |    0.021s | 19.32MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_132_8_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_precondition___00.smt2 |    0.021s | 19.252MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_142_14_postcondition___00.smt2 |    0.021s | 19.168MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_47_18_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_postcondition___00.smt2 |    0.021s | 19.368MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_125_41_range_check___00.smt2 |    0.021s | 19.252MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_125_14_postcondition___00.smt2 |    0.021s | 19.176MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_74_26_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_precondition___00.smt2 |    0.021s | 19.22MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_132_8_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_precondition___00.smt2 |    0.021s | 19.24MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_110_8_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_precondition___00.smt2 |    0.021s | 19.328MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/J506-016__scaled_value__spark-mod_arithmetic_lemmas.ads_80_52_spark-mod64_arithmetic_lemmas.ads_33_1_division_check___00.smt2 |    0.021s | 19.152MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_17_20_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_postcondition___00.smt2 |    0.021s | 19.284MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P114-046__invariant__inrange2.adb_19_52_range_check___00.smt2 |    0.021s | 19.264MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_479_14_postcondition___00.smt2 |    0.021s | 19.084MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/RB12-066__fixed_point_int_mult__types.ads_22_13_range_check___01.smt2 |    0.021s | 19.124MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_64_42_range_check___00.smt2 |    0.021s | 19.308MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_93_30_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_range_check___00.smt2 |    0.021s | 19.168MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_107_12_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_postcondition___00.smt2 |    0.021s | 19.324MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_185_14_postcondition___00.smt2 |    0.021s | 19.12MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_164_32_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_precondition___00.smt2 |    0.021s | 19.112MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/L719-025__hashed_sets_key__a-cfhase.ads_822_17_p.ads_12_4_precondition___00.smt2 |    0.021s | 19.356MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/NC16-020__bitwise__x86.ads_32_14_postcondition___00.smt2 |    0.021s | 19.544MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/MC06-019__shift_divide__p.ads_10_29_division_check___00.smt2 |    0.021s | 19.212MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_111_16_postcondition___00.smt2 |    0.021s | 19.284MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_132_8_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_precondition___00.smt2 |    0.021s | 19.296MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_47_18_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_postcondition___00.smt2 |    0.021s | 19.316MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/L719-025__hashed_sets_equal__p.ads_31_16_precondition___00.smt2 |    0.021s | 19.336MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.adb_241_29_range_check___00.smt2 |    0.021s | 19.192MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/riposte__arrays_multidim__arrays_multidim.adb_68_22_postcondition___00.smt2 |    0.021s | 20.48MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_64_42_range_check___00.smt2 |    0.021s | 19.172MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P114-046__invariant__inrange2.adb_20_33_loop_invariant_init___00.smt2 |    0.021s | 19.28MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_58_18_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_postcondition___00.smt2 |    0.021s | 19.348MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O427-011__non_pow2_modulo__t2.adb_26_46_contract_case___00.smt2 |    0.021s | 20.024MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_296_41_range_check___00.smt2 |    0.021s | 19.108MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_160_32_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_precondition___00.smt2 |    0.022s | 19.248MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_16_65_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_range_check___00.smt2 |    0.022s | 19.272MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_281_16_postcondition___00.smt2 |    0.022s | 19.284MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_164_32_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_precondition___00.smt2 |    0.022s | 19.328MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/N724-026__discrim__discrimrec.adb_17_40_discriminant_check___00.smt2 |    0.022s | 19.476MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/M603-021__volatile_input_proofs__port.ads_122_34_postcondition___00.smt2 |    0.022s | 19.92MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_135_12_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_postcondition___00.smt2 |    0.022s | 19.284MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/N624-030__funcs_on_containers__a-cfhama.ads_735_20_find_map.ads_15_4_precondition___00.smt2 |    0.022s | 19.396MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/L719-025__hashed_sets_equal__p.adb_16_7_precondition___00.smt2 |    0.022s | 19.424MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_141_12_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_postcondition___00.smt2 |    0.022s | 19.316MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P630-037__keccak__keccak-types.ads_132_39_precondition___00.smt2 |    0.022s | 19.744MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_27_16_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_postcondition___00.smt2 |    0.022s | 19.376MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_111_16_postcondition___00.smt2 |    0.022s | 19.424MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P429-003__list_of_bv__a-cofuve.ads_238_59_a-cfdlli.ads_69_7_foo.adb_10_4_overflow_check___00.smt2 |    0.022s | 19.792MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/N724-026__discrim__discrimrec.adb_11_53_discriminant_check___00.smt2 |    0.022s | 19.424MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_262_17_postcondition___00.smt2 |    0.022s | 19.904MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P429-003__list_of_bv__a-cofuve.ads_239_30_a-cfdlli.ads_69_7_foo.adb_10_4_range_check___00.smt2 |    0.022s | 20.024MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_93_30_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_range_check___00.smt2 |    0.022s | 19.24MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P922-044__fe_simplification_on_modulars__p.adb_8_22_assert___00.smt2 |    0.022s | 19.076MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/L719-025__hashed_sets_equal__a-cfhase.ads_822_17_p.ads_12_4_precondition___00.smt2 |    0.022s | 19.42MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O427-011__non_pow2_modulo__t2.adb_23_46_contract_case___00.smt2 |    0.022s | 19.988MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/R403-031__counterexample__p.adb_29_22_assert___00.smt2 |    0.022s | 19.152MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O401-034__float_pred__safety_pack.ads_44_17_postcondition___00.smt2 |    0.022s | 19.864MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_22_14_overflow_check___00.smt2 |    0.022s | 19.812MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.adb_159_59_division_check___00.smt2 |    0.022s | 19.108MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_162_15_range_check___00.smt2 |    0.022s | 20.02MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/L719-025__hashed_sets_equal__a-cfhase.ads_1202_20_p.ads_12_4_precondition___00.smt2 |    0.022s | 19.436MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_47_41_range_check___00.smt2 |    0.022s | 19.232MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P630-037__keccak__keccak-types.ads_132_62_range_check___00.smt2 |    0.023s | 19.808MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O427-011__non_pow2_modulo__t.adb_24_47_contract_case___00.smt2 |    0.023s | 19.884MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O427-011__non_pow2_modulo__t.adb_23_46_contract_case___00.smt2 |    0.023s | 19.88MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_273_14_postcondition___00.smt2 |    0.023s | 19.284MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_503_14_postcondition___00.smt2 |    0.023s | 19.808MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/L719-025__hashed_sets_key__p.adb_6_7_precondition___00.smt2 |    0.023s | 19.4MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/RB12-066__fixed_point_div_mod__types.ads_22_13_division_check___00.smt2 |    0.023s | 19.052MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O427-011__non_pow2_modulo__t2.adb_9_19_postcondition___00.smt2 |    0.023s | 19.996MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/R511-031__counterexample__saturation.adb_11_6_disjoint_contract_cases___00.smt2 |    0.023s | 19.396MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.adb_125_29_range_check___00.smt2 |    0.023s | 19.12MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P429-003__list_of_bv__a-cofuve.ads_237_63_a-cfdlli.ads_69_7_foo.adb_10_4_range_check___00.smt2 |    0.023s | 19.864MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_155_32_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_precondition___00.smt2 |    0.023s | 19.116MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_117_14_overflow_check___00.smt2 |    0.023s | 19.996MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/L719-025__hashed_sets_equal__p.adb_26_10_precondition___00.smt2 |    0.023s | 19.74MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/proofinuse__bitwise__bitwise.adb_20_30_division_check___00.smt2 |    0.023s | 19.148MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_504_14_postcondition___00.smt2 |    0.023s | 19.94MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_386_43_range_check___00.smt2 |    0.023s | 19.3MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P512-044__exist_on_bv__x86.adb_55_20_x86.adb_99_7_loop_invariant_init___00.smt2 |    0.023s | 19.236MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_74_26_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_precondition___00.smt2 |    0.023s | 19.376MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_110_8_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_precondition___00.smt2 |    0.023s | 19.376MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_59_14_postcondition___00.smt2 |    0.023s | 19.208MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_23_14_overflow_check___00.smt2 |    0.023s | 20.06MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_58_67_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_range_check___00.smt2 |    0.023s | 19.932MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_110_8_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_precondition___00.smt2 |    0.023s | 19.248MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P429-003__list_of_bv__a-cfdlli.ads_1422_23_foo.adb_10_4_precondition___00.smt2 |    0.023s | 19.188MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/L719-025__hashed_maps_equal__p.adb_12_7_precondition___00.smt2 |    0.023s | 19.428MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_135_12_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_postcondition___00.smt2 |    0.023s | 19.196MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O427-011__non_pow2_modulo__t.adb_25_47_contract_case___00.smt2 |    0.023s | 20.068MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_16_65_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_range_check___00.smt2 |    0.023s | 19.304MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_51_15_postcondition___00.smt2 |    0.023s | 20.016MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P512-044__exist_on_bv__x86.adb_36_40_x86.adb_99_7_assert___00.smt2 |    0.023s | 19.396MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_17_20_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_postcondition___00.smt2 |    0.023s | 19.28MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_154_17_postcondition___00.smt2 |    0.023s | 20.296MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_51_14_postcondition___00.smt2 |    0.023s | 19.268MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/L719-025__hashed_sets_equal__a-cfhase.ads_1223_20_p.ads_12_4_precondition___00.smt2 |    0.023s | 19.324MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P429-003__list_of_bv__a-cofuve.ads_232_54_a-cfdlli.ads_69_7_foo.adb_10_4_overflow_check___00.smt2 |    0.023s | 19.812MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_285_17_postcondition___00.smt2 |    0.023s | 20.036MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/NC16-020__bitwise__x86.ads_49_16_postcondition___00.smt2 |    0.023s | 19.244MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/S619-026__equality__a-cfhama.ads_735_20_prim_eq_vect.adb_18_4_precondition___00.smt2 |    0.023s | 19.612MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/NC26-004__bitwise__x86.ads_21_15_postcondition___00.smt2 |    0.024s | 19.788MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O427-011__non_pow2_modulo__t.adb_23_11_disjoint_contract_cases___00.smt2 |    0.024s | 19.908MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/R322-003__private_modular__mod_subtypes.ads_18_38_predicate_check___00.smt2 |    0.024s | 19.88MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/J506-016__scaled_value__sv.adb_13_48_division_check___00.smt2 |    0.024s | 19.32MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_142_14_overflow_check___00.smt2 |    0.024s | 20.072MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_360_14_postcondition___00.smt2 |    0.024s | 19.188MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O427-011__non_pow2_modulo__t2.adb_27_46_contract_case___00.smt2 |    0.024s | 19.944MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O427-011__non_pow2_modulo__t.adb_27_46_contract_case___00.smt2 |    0.024s | 19.96MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_45_14_overflow_check___00.smt2 |    0.024s | 20.052MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/Q601-014__abstract_state__achiever.ads_36_49_contract_case___00.smt2 |    0.024s | 19.992MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_93_14_overflow_check___00.smt2 |    0.024s | 20.416MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/K915-006__modular__pack.ads_6_19_postcondition___00.smt2 |    0.024s | 19.288MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.adb_289_27_range_check___00.smt2 |    0.024s | 19.048MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_46_14_overflow_check___00.smt2 |    0.024s | 20.152MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/N724-026__discrim__discrimrec.adb_18_14_discriminant_check___00.smt2 |    0.024s | 19.528MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/N624-030__funcs_on_containers__a-cfhama.ads_720_20_find_map.ads_15_4_precondition___00.smt2 |    0.024s | 19.46MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_58_67_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_range_check___00.smt2 |    0.024s | 20.16MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/R322-003__private_modular__mod_subtypes.ads_17_31_predicate_check___00.smt2 |    0.024s | 19.816MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_69_14_overflow_check___00.smt2 |    0.024s | 20.12MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_135_12_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_postcondition___00.smt2 |    0.024s | 19.228MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_33_46_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_range_check___00.smt2 |    0.024s | 20.024MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_70_26_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_precondition___00.smt2 |    0.024s | 19.252MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_86_41_range_check___00.smt2 |    0.024s | 19.248MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_315_14_postcondition___00.smt2 |    0.024s | 19.432MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_216_17_postcondition___00.smt2 |    0.024s | 20.052MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/L719-025__hashed_sets_equal__p.adb_7_7_precondition___00.smt2 |    0.024s | 19.256MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_341_43_range_check___00.smt2 |    0.024s | 19.124MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O427-011__non_pow2_modulo__t3.adb_23_11_disjoint_contract_cases___00.smt2 |    0.024s | 19.952MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P630-037__keccak__keccak-types.ads_136_62_range_check___00.smt2 |    0.024s | 19.804MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_165_14_overflow_check___00.smt2 |    0.024s | 20.368MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_509_14_postcondition___00.smt2 |    0.024s | 19.84MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/riposte__arrays_multidim__arrays_multidim.adb_30_22_assert___00.smt2 |    0.024s | 20.04MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/NC23-020__bitwise__x86.ads_57_16_postcondition___00.smt2 |    0.024s | 19.788MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_70_26_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_precondition___00.smt2 |    0.025s | 19.38MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_70_14_overflow_check___00.smt2 |    0.025s | 20.244MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P429-003__list_of_bv__a-cfdlli.ads_469_49_foo.adb_10_4_overflow_check___00.smt2 |    0.025s | 20.08MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_76_15_postcondition___00.smt2 |    0.025s | 20.028MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_120_14_division_check___00.smt2 |    0.025s | 19.96MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/LC17-035__update_attribute_multidim__update_logic_fn.ads_116_14_postcondition___00.smt2 |    0.025s | 20.12MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/riposte__arrays_multidim__arrays_multidim.adb_60_22_postcondition___00.smt2 |    0.025s | 20.184MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/Q601-014__abstract_state__achiever.ads_44_45_contract_case___00.smt2 |    0.025s | 20.124MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_166_14_overflow_check___00.smt2 |    0.025s | 20.516MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_119_14_overflow_check___00.smt2 |    0.025s | 20.044MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/L719-025__hashed_maps_equal__p.adb_10_27_precondition___00.smt2 |    0.025s | 19.664MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/L719-025__hashed_maps_equal__p.adb_21_10_precondition___00.smt2 |    0.025s | 19.46MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O427-011__non_pow2_modulo__t2.adb_25_47_contract_case___00.smt2 |    0.025s | 20.048MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_508_14_postcondition___00.smt2 |    0.025s | 19.808MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O427-011__non_pow2_modulo__t3.adb_24_47_contract_case___00.smt2 |    0.025s | 20.528MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_47_14_overflow_check___00.smt2 |    0.025s | 20.744MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/Q601-014__abstract_state__achiever.ads_47_8_postcondition___00.smt2 |    0.025s | 20.22MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_315_14_postcondition___00.smt2 |    0.025s | 19.372MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_34_47_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_range_check___00.smt2 |    0.025s | 20.192MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_166_14_range_check___00.smt2 |    0.025s | 20.236MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/LC17-035__update_attribute_multidim__update_logic_fn.ads_103_14_postcondition___00.smt2 |    0.025s | 20.14MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_59_80_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_range_check___00.smt2 |    0.025s | 20.04MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_143_14_overflow_check___00.smt2 |    0.026s | 20.88MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_33_46_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_range_check___00.smt2 |    0.026s | 19.872MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/N724-026__discrim__discrimrec.adb_17_14_discriminant_check___00.smt2 |    0.026s | 19.604MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/N724-026__discrim__discrimrec.adb_16_14_discriminant_check___00.smt2 |    0.026s | 19.88MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_141_14_overflow_check___00.smt2 |    0.026s | 19.972MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/L719-025__hashed_sets_equal__p.adb_8_22_assert___00.smt2 |    0.026s | 20.06MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_58_18_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_postcondition___00.smt2 |    0.026s | 19.316MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_58_67_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_range_check___00.smt2 |    0.026s | 20.34MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_34_47_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_range_check___00.smt2 |    0.026s | 19.872MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P114-046__invariant__inrange1.adb_13_10_loop_variant___00.smt2 |    0.026s | 20.656MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_72_26_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_precondition___00.smt2 |    0.026s | 19.248MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/N724-026__discrim__discrimrec.adb_14_37_range_check___00.smt2 |    0.026s | 19.384MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_59_80_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_range_check___00.smt2 |    0.026s | 20.06MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/M603-021__volatile_input_proofs__port.ads_112_34_postcondition___00.smt2 |    0.026s | 19.988MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P429-003__list_of_bv__a-cfdlli.ads_610_49_foo.adb_10_4_overflow_check___00.smt2 |    0.026s | 19.964MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_18_82_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_range_check___00.smt2 |    0.026s | 20.136MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_34_47_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_range_check___00.smt2 |    0.026s | 19.828MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/N724-026__discrim__discrimrec.adb_9_24_discriminant_check___00.smt2 |    0.026s | 19.76MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_144_14_division_check___00.smt2 |    0.026s | 19.308MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_59_80_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_range_check___00.smt2 |    0.026s | 20.3MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P429-003__list_of_bv__a-cfdlli.ads_700_57_foo.adb_10_4_overflow_check___00.smt2 |    0.026s | 20.296MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P429-003__list_of_bv__a-cfdlli.ads_1416_14_foo.adb_10_4_precondition___00.smt2 |    0.026s | 20.192MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_34_47_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_range_check___00.smt2 |    0.026s | 19.972MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O427-011__non_pow2_modulo__t2.adb_24_47_contract_case___00.smt2 |    0.026s | 19.956MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_48_80_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_range_check___00.smt2 |    0.026s | 19.972MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/LC17-035__update_attribute_multidim__update_logic_fn.ads_39_14_postcondition___00.smt2 |    0.027s | 20.12MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P114-046__invariant__inrange2.adb_18_10_loop_variant___00.smt2 |    0.027s | 20.752MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_59_80_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_range_check___00.smt2 |    0.027s | 20.168MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O318-021__modular__fpmod.adb_11_11_range_check___00.smt2 |    0.027s | 20.068MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/N724-026__discrim__discrimrec.adb_11_63_division_check___00.smt2 |    0.027s | 19.476MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P429-003__list_of_bv__a-cfdlli.ads_1210_6_foo.adb_10_4_disjoint_contract_cases___00.smt2 |    0.027s | 20.012MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.adb_27_55_range_check___00.smt2 |    0.027s | 19.432MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/L719-025__hashed_sets_equal__p.adb_18_22_assert___00.smt2 |    0.027s | 20.068MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O427-011__non_pow2_modulo__t3.adb_23_46_contract_case___00.smt2 |    0.027s | 20.576MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/L719-025__hashed_sets_key__a-cfhase.ads_1110_49_p.ads_12_4_overflow_check___00.smt2 |    0.027s | 20.356MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__dynamicsaturateassert.adb_58_22_assert___00.smt2 |    0.027s | 20.212MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/N724-026__discrim__discrimrec.adb_11_63_range_check___00.smt2 |    0.027s | 19.516MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/L719-025__hashed_maps_equal__p.ads_35_22_precondition___00.smt2 |    0.027s | 19.448MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_138_8_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_precondition___00.smt2 |    0.027s | 19.284MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P429-003__list_of_bv__a-cfdlli.ads_853_28_foo.adb_10_4_overflow_check___00.smt2 |    0.027s | 20.304MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_341_43_range_check___00.smt2 |    0.028s | 19.136MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P429-003__list_of_bv__a-cfdlli.ads_1471_14_foo.adb_10_4_precondition___00.smt2 |    0.028s | 20.24MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_190_14_overflow_check___00.smt2 |    0.028s | 20.688MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P429-003__list_of_bv__a-cfdlli.ads_766_57_foo.adb_10_4_overflow_check___00.smt2 |    0.028s | 20.14MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_48_80_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_range_check___00.smt2 |    0.028s | 20.048MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P630-037__keccak__keccak-duplex.adb_37_30_keccak-keccak_1600.ads_66_4_range_check___00.smt2 |    0.028s | 20.176MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/S504-004__no_optim__various_no_optim.adb_48_22_assert___00.smt2 |    0.029s | 19.584MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/L102-013__bitwise__p.adb_3_24_range_check___00.smt2 |    0.029s | 19.04MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_48_80_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_range_check___00.smt2 |    0.029s | 20.532MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_258_45_range_check___00.smt2 |    0.029s | 19.184MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P429-003__list_of_bv__a-cfdlli.ads_1029_43_foo.adb_10_4_overflow_check___00.smt2 |    0.029s | 20.12MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/L719-025__hashed_sets_equal__a-cfhase.ads_892_49_p.ads_12_4_overflow_check___00.smt2 |    0.029s | 20.048MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_21_14_overflow_check___00.smt2 |    0.029s | 20.136MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/thumper__serial_generator.adb_48_33_range_check___00.smt2 |    0.029s | 19.956MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_18_82_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_range_check___00.smt2 |    0.029s | 20.432MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_58_67_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_range_check___00.smt2 |    0.030s | 19.992MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_193_17_postcondition___00.smt2 |    0.030s | 20.06MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/N724-026__discrim__discrimrec.ads_36_20_discriminant_check___00.smt2 |    0.030s | 20.24MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/LC17-035__update_attribute_multidim__update_logic_fn.ads_127_19_postcondition___00.smt2 |    0.030s | 20.348MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_94_14_overflow_check___00.smt2 |    0.030s | 20.604MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O427-011__non_pow2_modulo__t2.adb_23_11_disjoint_contract_cases___00.smt2 |    0.030s | 19.972MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.adb_203_29_range_check___00.smt2 |    0.030s | 19.344MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_165_14_range_check___00.smt2 |    0.030s | 20.312MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O427-011__non_pow2_modulo__t2.adb_35_19_postcondition___00.smt2 |    0.030s | 20.256MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/L719-025__hashed_sets_equal__a-cfhase.ads_1070_26_p.ads_12_4_overflow_check___00.smt2 |    0.030s | 20.4MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P114-046__invariant__inrange3.adb_12_10_loop_variant___00.smt2 |    0.031s | 20.888MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/NA22-017__suppress_check_in_ads__test.ads_15_19_postcondition___00.smt2 |    0.031s | 19.152MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_18_82_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_range_check___00.smt2 |    0.031s | 20.164MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/S619-026__equality__prim_eq_vect.adb_28_59_precondition___00.smt2 |    0.031s | 20.816MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_227_42_range_check___00.smt2 |    0.031s | 19.284MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/L719-025__hashed_sets_key__a-cfhase.ads_892_49_p.ads_12_4_overflow_check___00.smt2 |    0.031s | 20.068MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_204_42_range_check___00.smt2 |    0.031s | 19.112MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_90_14_postcondition___00.smt2 |    0.031s | 19.524MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/L719-025__hashed_sets_key__a-cfhase.ads_1070_26_p.ads_12_4_overflow_check___00.smt2 |    0.031s | 20.272MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_375_14_postcondition___00.smt2 |    0.031s | 19.264MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/L719-025__hashed_sets_equal__a-cfhase.ads_1110_49_p.ads_12_4_overflow_check___00.smt2 |    0.031s | 20.244MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/N811-037__bitwise__x86.adb_6_29_range_check___00.smt2 |    0.031s | 19.264MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/L719-025__hashed_sets_equal__a-cfhase.ads_1069_24_p.ads_12_4_overflow_check___00.smt2 |    0.032s | 20.376MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/riposte__arrays_multidim__arrays_multidim.adb_80_19_postcondition___00.smt2 |    0.032s | 19.34MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_167_14_range_check___00.smt2 |    0.032s | 21.904MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_72_26_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_precondition___00.smt2 |    0.032s | 19.248MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/N716-019__div__my_div.ads_7_20_postcondition___00.smt2 |    0.032s | 19.272MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/L719-025__hashed_maps_equal__p.adb_19_10_precondition___00.smt2 |    0.032s | 19.516MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/K915-006__modular__pack.ads_14_19_postcondition___00.smt2 |    0.032s | 19.26MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/S504-004__no_optim__various_no_optim.adb_32_22_assert___00.smt2 |    0.032s | 20.188MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/RC17-047__generic_warn__a-timoio.ads_74_40_init.adb_7_4_precondition___00.smt2 |    0.032s | 19.576MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/proofinuse__nonlinear__nonlinear.adb_19_22_division_check___00.smt2 |    0.033s | 19.196MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/S329-030__bound_exponentiation__spark-mod_arithmetic_lemmas.ads_90_32_spark-mod32_arithmetic_lemmas.ads_33_1_division_check___00.smt2 |    0.033s | 19.308MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_311_41_range_check___00.smt2 |    0.033s | 19.212MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_93_30_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_range_check___00.smt2 |    0.033s | 19.268MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/L719-025__hashed_sets_key__a-cfhase.ads_844_26_p.ads_12_4_overflow_check___00.smt2 |    0.033s | 20.412MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_110_8_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_precondition___00.smt2 |    0.033s | 19.54MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_204_42_range_check___00.smt2 |    0.033s | 19.264MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.adb_125_29_range_check___00.smt2 |    0.033s | 19.108MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.adb_217_29_range_check___00.smt2 |    0.033s | 19.464MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/M529-013__modular__modular.adb_10_53_range_check___00.smt2 |    0.033s | 19.044MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/L719-025__hashed_maps_equal__p.adb_13_7_precondition___00.smt2 |    0.034s | 20.56MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/proofinuse__bitwise__bitwise.adb_32_22_assert___00.smt2 |    0.034s | 19.148MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/NC16-020__bitwise__x86.ads_24_14_postcondition___00.smt2 |    0.034s | 19.608MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O427-011__non_pow2_modulo__t.adb_16_19_postcondition___00.smt2 |    0.034s | 19.968MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/N811-037__bitwise__x86.ads_21_14_postcondition___00.smt2 |    0.034s | 19.912MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/J506-016__scaled_value__spark-mod_arithmetic_lemmas.ads_99_51_spark-mod32_arithmetic_lemmas.ads_33_1_division_check___00.smt2 |    0.034s | 19.016MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/N724-026__discrim__discrimrec.ads_36_16_postcondition___00.smt2 |    0.034s | 20.904MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P512-044__exist_on_bv__x86.adb_72_52_x86.adb_99_7_range_check___00.smt2 |    0.034s | 19.78MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_204_14_postcondition___00.smt2 |    0.034s | 19.504MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/NC23-020__bitwise__x86.ads_32_14_postcondition___00.smt2 |    0.034s | 19.272MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/L719-025__hashed_sets_equal__a-cfhase.ads_844_26_p.ads_12_4_overflow_check___00.smt2 |    0.034s | 20.38MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/S619-026__equality__prim_eq_vect.adb_28_14_postcondition___00.smt2 |    0.034s | 21.2MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/L719-025__hashed_sets_equal__p.ads_18_14_precondition___00.smt2 |    0.034s | 20.292MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P512-044__exist_on_bv__x86.adb_74_37_x86.adb_99_7_assert___00.smt2 |    0.034s | 19.128MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_44_8_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_precondition___00.smt2 |    0.034s | 19.32MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/proofinuse__ce__counter_examples.adb_17_24_division_check___00.smt2 |    0.034s | 19.116MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.adb_135_29_range_check___00.smt2 |    0.034s | 19.084MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.adb_91_29_range_check___00.smt2 |    0.034s | 19.256MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.adb_179_29_range_check___00.smt2 |    0.034s | 19.456MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_47_18_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_postcondition___00.smt2 |    0.035s | 19.224MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_356_14_postcondition___00.smt2 |    0.035s | 19.316MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_72_16_postcondition___00.smt2 |    0.035s | 19.184MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_356_43_range_check___00.smt2 |    0.035s | 19.144MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_141_12_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_postcondition___00.smt2 |    0.035s | 19.14MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_168_14_division_check___00.smt2 |    0.035s | 22.148MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O427-011__non_pow2_modulo__t.adb_9_19_postcondition___00.smt2 |    0.035s | 20.456MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P114-046__invariant__inrange3.adb_15_37_range_check___00.smt2 |    0.035s | 19.78MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.adb_331_28_range_check___00.smt2 |    0.035s | 19.324MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/K915-006__modular__pack.ads_10_19_postcondition___00.smt2 |    0.036s | 19.16MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_132_8_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_precondition___00.smt2 |    0.036s | 19.748MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/L719-025__hashed_sets_equal__a-cfhase.ads_843_24_p.ads_12_4_overflow_check___00.smt2 |    0.036s | 20.388MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.adb_71_55_division_check___00.smt2 |    0.036s | 19.26MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_68_15_postcondition___00.smt2 |    0.036s | 19.828MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_155_32_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_precondition___00.smt2 |    0.036s | 19.356MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/L719-025__hashed_maps_equal__p.adb_6_7_precondition___00.smt2 |    0.036s | 20.668MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/L719-025__hashed_sets_key__a-cfhase.ads_843_24_p.ads_12_4_overflow_check___00.smt2 |    0.036s | 20.52MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/thumper__serial_generator.adb_51_28_range_check___00.smt2 |    0.036s | 20.208MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_155_32_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_precondition___00.smt2 |    0.037s | 19.56MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_189_14_overflow_check___00.smt2 |    0.037s | 20.336MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/L719-025__hashed_sets_equal__p.ads_18_14_postcondition___00.smt2 |    0.037s | 20.356MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.adb_345_28_range_check___00.smt2 |    0.037s | 19.284MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/M529-013__modular__modular.adb_10_32_division_check___00.smt2 |    0.037s | 19.244MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_239_17_postcondition___00.smt2 |    0.037s | 19.984MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_153_32_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_precondition___00.smt2 |    0.037s | 19.344MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_103_42_range_check___00.smt2 |    0.037s | 19.308MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.adb_169_29_range_check___00.smt2 |    0.037s | 19.184MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_146_14_postcondition___00.smt2 |    0.038s | 19.78MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_151_32_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_precondition___00.smt2 |    0.038s | 19.12MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/L719-025__hashed_sets_equal__p.adb_13_27_precondition___00.smt2 |    0.038s | 19.312MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/L719-025__hashed_maps_equal__p.ads_19_14_postcondition___00.smt2 |    0.038s | 20.716MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O427-011__non_pow2_modulo__t2.adb_16_19_postcondition___00.smt2 |    0.038s | 20.204MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/L719-025__hashed_maps_equal__p.ads_26_12_precondition___00.smt2 |    0.038s | 19.536MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P429-003__list_of_bv__foo.adb_20_7_precondition___00.smt2 |    0.038s | 20.22MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_162_32_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_precondition___00.smt2 |    0.039s | 19.364MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P114-046__invariant__inrange2.adb_19_32_loop_invariant_init___00.smt2 |    0.039s | 19.084MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_17_20_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_postcondition___00.smt2 |    0.039s | 19.54MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_115_17_postcondition___00.smt2 |    0.039s | 19.956MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_33_46_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_range_check___00.smt2 |    0.040s | 20.344MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O427-011__non_pow2_modulo__t3.adb_26_46_contract_case___00.smt2 |    0.040s | 24.584MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_86_14_postcondition___00.smt2 |    0.040s | 19.772MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_33_46_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_range_check___00.smt2 |    0.040s | 20.06MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_167_14_overflow_check___00.smt2 |    0.040s | 24.476MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O427-011__non_pow2_modulo__t.adb_26_46_contract_case___00.smt2 |    0.040s | 19.836MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_153_14_overflow_check___00.smt2 |    0.040s | 24.972MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_118_14_overflow_check___00.smt2 |    0.041s | 20.04MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/L719-025__hashed_sets_equal__p.ads_28_14_postcondition___00.smt2 |    0.041s | 21.2MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-045__modular__x86.ads_142_42_range_check___00.smt2 |    0.041s | 19.188MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/N716-019__div__my_div.adb_8_14_division_check___00.smt2 |    0.041s | 19.144MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/LC17-035__update_attribute_multidim__update_logic_fn.ads_29_14_postcondition___00.smt2 |    0.041s | 20.432MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/N724-026__discrim__discrimrec.adb_19_17_discriminant_check___00.smt2 |    0.041s | 19.996MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_160_32_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_precondition___00.smt2 |    0.042s | 19.18MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/L719-025__hashed_sets_equal__p.ads_22_14_postcondition___00.smt2 |    0.042s | 20.992MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P429-003__list_of_bv__a-cofuve.ads_238_76_a-cfdlli.ads_69_7_foo.adb_10_4_overflow_check___00.smt2 |    0.042s | 19.852MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/L719-025__hashed_maps_equal__p.ads_23_14_postcondition___00.smt2 |    0.042s | 21.064MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_71_14_overflow_check___00.smt2 |    0.042s | 23.86MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_55_8_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_precondition___00.smt2 |    0.042s | 19.6MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/L719-025__hashed_sets_key__a-cfhase.ads_1223_20_p.ads_12_4_precondition___00.smt2 |    0.043s | 19.54MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/S329-030__bound_exponentiation__spark-mod_arithmetic_lemmas.ads_111_38_spark-mod32_arithmetic_lemmas.ads_33_1_division_check___00.smt2 |    0.043s | 19.128MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_160_32_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_precondition___00.smt2 |    0.044s | 19.752MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_58_18_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_postcondition___00.smt2 |    0.044s | 19.524MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/LC17-035__update_attribute_multidim__update_logic_fn.ads_62_14_postcondition___00.smt2 |    0.044s | 20.276MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/N624-030__funcs_on_containers__a-cfhama.ads_681_39_find_map.ads_15_4_precondition___00.smt2 |    0.044s | 19.272MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O427-011__non_pow2_modulo__t3.adb_27_46_contract_case___00.smt2 |    0.044s | 24.452MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O427-011__non_pow2_modulo__t.adb_35_19_postcondition___00.smt2 |    0.045s | 20.404MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/L719-025__hashed_maps_equal__p.ads_30_14_postcondition___00.smt2 |    0.045s | 21.388MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_48_80_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_range_check___00.smt2 |    0.046s | 19.896MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_151_14_overflow_check___00.smt2 |    0.046s | 23.728MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_371_14_postcondition___00.smt2 |    0.049s | 19.528MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/L719-025__hashed_sets_key__a-cfhase.ads_1070_44_p.ads_12_4_overflow_check___00.smt2 |    0.050s | 20.384MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_18_82_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_range_check___00.smt2 |    0.051s | 20.14MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/L719-025__hashed_sets_key__a-cfhase.ads_1069_24_p.ads_12_4_overflow_check___00.smt2 |    0.051s | 20.3MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/L719-025__hashed_sets_equal__a-cfhase.ads_1070_44_p.ads_12_4_overflow_check___00.smt2 |    0.051s | 20.632MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O427-011__non_pow2_modulo__t3.adb_16_19_postcondition___00.smt2 |    0.053s | 20.96MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/L719-025__hashed_sets_equal__p.adb_17_7_precondition___00.smt2 |    0.055s | 20.652MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_168_14_range_check___00.smt2 |    0.057s | 25.344MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/L719-025__hashed_sets_key__p.ads_26_14_postcondition___00.smt2 |    0.058s | 22.716MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_281_45_range_check___00.smt2 |    0.061s | 19.624MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P512-044__exist_on_bv__x86.adb_87_31_x86.adb_99_7_assert___00.smt2 |    0.063s | 19.668MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/S213-012__flow_expr_fun__repro-b.ads_9_16_postcondition___00.smt2 |    0.064s | 19.292MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P630-037__keccak__keccak-duplex.ads_79_14_keccak-keccak_1600.ads_66_4_postcondition___00.smt2 |    0.070s | 20.08MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O427-011__non_pow2_modulo__t3.adb_9_19_postcondition___00.smt2 |    0.080s | 24.584MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O427-011__non_pow2_modulo__t3.adb_25_47_contract_case___00.smt2 |    0.104s | 24.932MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/J506-016__scaled_value__sv.adb_17_40_range_check___00.smt2 |    0.159s | 69.356MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P114-046__invariant__inrange5.ads_20_8_postcondition___00.smt2 |    0.168s | 21.964MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/J506-016__scaled_value__sv.adb_15_7_precondition___00.smt2 |    0.168s | 69.436MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P512-044__exist_on_bv__x86.adb_77_34_x86.adb_99_7_assert___00.smt2 |    0.208s | 23.18MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_191_14_overflow_check___00.smt2 |    0.217s | 36.008MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/J506-016__scaled_value__sv.ads_17_14_postcondition___00.smt2 |    0.260s | 69.1MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_95_14_overflow_check___00.smt2 |    0.268s | 35.884MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O427-011__non_pow2_modulo__t3.adb_35_19_postcondition___00.smt2 |    0.938s | 32.468MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/J506-016__scaled_value__sv.adb_13_48_range_check___00.smt2 |    5.279s | 70.776MiB| unsat | 1 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P114-046__invariant__inrange1.ads_18_14_postcondition___00.smt2 |   20.006s | 27.72MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_122_92_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_range_check___00.smt2 |   20.006s | 25.136MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/RB12-066__fixed_point_div_mod__types.ads_22_13_overflow_check___00.smt2 |   20.006s | 23.692MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_181_21_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_inconsistent_post___00.smt2 |   20.006s | 23.272MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/Q420-007__power_modular__non_binary_mod_power.adb_16_19_assert___00.smt2 |   20.006s | 23.04MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_35_12_overflow_check___00.smt2 |   20.006s | 24.884MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/OA20-032__refinement__patris.adb_434_41_division_check___00.smt2 |   20.006s | 22.624MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_199_29_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_postcondition___00.smt2 |   20.006s | 29.628MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_26_19_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_inconsistent_pre___00.smt2 |   20.007s | 28.284MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/MC06-015__contracts_on_intrinsics__p.ads_10_29_division_check___00.smt2 |   20.007s | 28.568MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_19_84_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_range_check___00.smt2 |   20.007s | 24.42MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/R403-031__counterexample__p.adb_42_25_assert___00.smt2 |   20.007s | 28.22MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_11_36_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_range_check___00.smt2 |   20.007s | 23.364MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/S329-030__bound_exponentiation__unsigned.adb_6_19_assert___00.smt2 |   20.007s | 25.916MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_112_11_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_inconsistent_pre___00.smt2 |   20.007s | 23.912MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/R322-003__private_modular__mod_types.ads_21_19_assert___00.smt2 |   20.007s | 31.896MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_117_13_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_inconsistent_pre___00.smt2 |   20.007s | 26.3MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_29_98_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_range_check___00.smt2 |   20.007s | 27.468MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_31_14_overflow_check___00.smt2 |   20.007s | 24.68MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/MC06-015__contracts_on_intrinsics__p.ads_13_19_postcondition___00.smt2 |   20.007s | 28.452MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_62_74_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_range_check___00.smt2 |   20.007s | 24.344MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_180_28_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_assert___00.smt2 |   20.007s | 22.748MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/Q515-026__sk_simplified__gen.ads_27_14_postcondition___00.smt2 |   20.007s | 23.82MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_82_14_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_postcondition___00.smt2 |   20.007s | 22.184MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_82_14_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_postcondition___00.smt2 |   20.007s | 22.304MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__abs_controller_supplier_with_property.adb_53_82_overflow_check___00.smt2 |   20.007s | 27.744MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_216_31_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_assert___00.smt2 |   20.007s | 26.248MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_28_82_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_range_check___00.smt2 |   20.007s | 28.32MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/KC05-038__modulo__p.adb_6_24_range_check___00.smt2 |   20.007s | 23.044MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/KC02-007__modulo__p.ads_12_14_postcondition___00.smt2 |   20.007s | 26.004MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_57_17_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_inconsistent_pre___00.smt2 |   20.007s | 25.68MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/RB12-066__fixed_point_div_mod__types.ads_22_13_range_check___00.smt2 |   20.007s | 23.468MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_1595_42_range_check___00.smt2 |   20.007s | 25.388MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/L102-013__bitwise__p.adb_4_24_division_check___00.smt2 |   20.007s | 22.92MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/QA31-008__von_neumann_sqrt__p.adb_98_36_loop_invariant_preserv___00.smt2 |   20.007s | 27.06MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_1541_50_range_check___00.smt2 |   20.007s | 22.608MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_29_98_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_range_check___00.smt2 |   20.007s | 28.256MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_207_43_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_loop_invariant_init___00.smt2 |   20.007s | 29.964MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/R403-031__counterexample__p.adb_40_25_assert___00.smt2 |   20.007s | 27.652MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_80_14_division_check___00.smt2 |   20.007s | 32.112MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_176_23_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_inconsistent_pre___00.smt2 |   20.007s | 29.592MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_182_20_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_precondition___00.smt2 |   20.007s | 22.68MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_46_17_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_inconsistent_pre___00.smt2 |   20.007s | 25.58MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/N108-021__unchecked_conversion__port.adb_12_16_range_check___00.smt2 |   20.007s | 33.144MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_176_23_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_inconsistent_pre___00.smt2 |   20.007s | 28.268MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_300_26_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_postcondition___00.smt2 |   20.007s | 22.752MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_19_84_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_range_check___00.smt2 |   20.007s | 27.144MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_81_13_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_inconsistent_pre___00.smt2 |   20.007s | 22.312MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_59_12_overflow_check___00.smt2 |   20.007s | 25.084MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_117_13_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_inconsistent_pre___00.smt2 |   20.007s | 27.536MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_31_75_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_range_check___00.smt2 |   20.007s | 28.328MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_31_75_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_range_check___00.smt2 |   20.007s | 28.268MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/proofinuse__ce__counter_examples.adb_21_25_assert___00.smt2 |   20.007s | 26.18MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_27_20_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_postcondition___00.smt2 |   20.007s | 28.32MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_140_11_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_inconsistent_pre___00.smt2 |   20.007s | 29.508MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O318-021__modular__fpmod.adb_15_11_range_check___00.smt2 |   20.007s | 23.436MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/M529-013__modular__modular.adb_7_66_division_check___00.smt2 |   20.007s | 26.324MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_16_19_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_inconsistent_pre___00.smt2 |   20.007s | 25.552MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_207_43_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_loop_invariant_preserv___00.smt2 |   20.007s | 29.468MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_180_28_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_assert___00.smt2 |   20.007s | 22.68MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/KC05-038__modulo__p.adb_9_25_range_check___00.smt2 |   20.007s | 28.804MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_181_21_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_inconsistent_post___00.smt2 |   20.007s | 23.192MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_98_15_postcondition___00.smt2 |   20.007s | 45.192MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_192_24_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_inconsistent_post___00.smt2 |   20.007s | 25.952MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/L719-025__hashed_maps_equal__p.ads_26_30_precondition___00.smt2 |   20.007s | 24.468MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_199_29_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_postcondition___00.smt2 |   20.007s | 23.788MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_57_17_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_inconsistent_pre___00.smt2 |   20.007s | 27.724MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/MA02-015__flow_attributes__attributes.adb_18_31_range_check___00.smt2 |   20.007s | 28.32MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__abs_controller_supplier_with_property.adb_49_77_range_check___00.smt2 |   20.007s | 27.864MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_158_21_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_inconsistent_post___00.smt2 |   20.007s | 26.132MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_55_14_postcondition___00.smt2 |   20.007s | 32.084MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_51_74_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_range_check___00.smt2 |   20.007s | 24.432MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/Q420-007__power_modular__non_binary_mod_power.adb_15_18_division_check___00.smt2 |   20.007s | 23.052MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/R511-031__counterexample__saturation.adb_14_38_contract_case___00.smt2 |   20.007s | 22.86MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_57_17_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_inconsistent_pre___00.smt2 |   20.007s | 25.896MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_207_43_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_loop_invariant_init___00.smt2 |   20.007s | 23.776MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/Q714-010__address__pixel.adb_14_66_division_check___00.smt2 |   20.007s | 23.284MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/QA31-008__von_neumann_sqrt__p.adb_72_22_assert___00.smt2 |   20.007s | 27.236MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_19_84_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_range_check___00.smt2 |   20.007s | 27.744MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/R514-030__saturation.ads_12_23_postcondition___00.smt2 |   20.007s | 22.852MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_26_19_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_inconsistent_pre___00.smt2 |   20.008s | 28.592MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_62_74_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_range_check___00.smt2 |   20.008s | 27.836MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/MC06-015__contracts_on_intrinsics__p.ads_10_19_postcondition___00.smt2 |   20.008s | 28.4MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_1523_41_range_check___00.smt2 |   20.008s | 25.388MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_222_20_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_precondition___00.smt2 |   20.008s | 25.08MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_180_28_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_assert___00.smt2 |   20.008s | 27.584MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/OA20-032__refinement__patris.adb_432_64_range_check___00.smt2 |   20.008s | 22.628MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_199_29_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_postcondition___00.smt2 |   20.008s | 26.064MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_290_21_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_inconsistent_post___00.smt2 |   20.008s | 27.8MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_303_26_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_postcondition___00.smt2 |   20.008s | 24.92MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/S521-016__unchecked_conv__unchecked_conv.adb_11_19_assert___00.smt2 |   20.008s | 23.06MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/QA31-008__von_neumann_sqrt__p.adb_95_55_division_check___00.smt2 |   20.008s | 27.244MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_98_45_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_division_check___00.smt2 |   20.008s | 22.192MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/RB12-066__fixed_point_div_mod__types.ads_16_13_range_check___00.smt2 |   20.008s | 23.404MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/QA31-008__von_neumann_sqrt__p.adb_81_13_dead_code___00.smt2 |   20.008s | 27.192MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_303_26_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_postcondition___00.smt2 |   20.008s | 26.08MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/MC06-015__contracts_on_intrinsics__p.ads_13_29_division_check___00.smt2 |   20.008s | 28.468MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P114-046__invariant__inrange4.ads_19_8_postcondition___00.smt2 |   20.008s | 26.396MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_126_33_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_loop_invariant_init___00.smt2 |   20.008s | 29.456MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_217_39_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_loop_invariant_init___00.smt2 |   20.008s | 34.872MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/RB12-066__fixed_point_div_mod__types.ads_6_12_range_check___00.smt2 |   20.008s | 23.432MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/M603-021__volatile_input_proofs__port.adb_29_16_range_check___00.smt2 |   20.008s | 33.176MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_26_15_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_inconsistent_pre___00.smt2 |   20.008s | 24.044MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_38_22_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_assert___00.smt2 |   20.008s | 28.008MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P630-037__keccak__keccak-types.ads_132_8_precondition___00.smt2 |   20.008s | 23.136MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/L719-025__hashed_sets_equal__p.ads_31_33_precondition___00.smt2 |   20.008s | 23.776MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_177_14_overflow_check___00.smt2 |   20.008s | 32.376MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/proofinuse__bitwise__bitwise.adb_22_30_division_check___00.smt2 |   20.008s | 26.06MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_218_63_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_range_check___00.smt2 |   20.008s | 26.08MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/OA20-032__refinement__patris.adb_432_64_overflow_check___00.smt2 |   20.008s | 22.628MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_155_12_range_check___00.smt2 |   20.008s | 31.648MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P208-021__modular_subtype__errorexample.adb_9_7_assert___00.smt2 |   20.008s | 22.456MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_207_43_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_loop_invariant_init___00.smt2 |   20.008s | 29.192MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/QA31-008__von_neumann_sqrt__p.adb_96_36_loop_invariant_init___00.smt2 |   20.008s | 27.228MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_144_21_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_inconsistent_post___00.smt2 |   20.008s | 26.492MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_8_14_division_check___00.smt2 |   20.008s | 31.956MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_38_22_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_assert___00.smt2 |   20.008s | 28.576MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa_generic.adb_10_66_overflow_check___00.smt2 |   20.008s | 26.34MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/QA31-008__von_neumann_sqrt__p.adb_87_60_range_check___00.smt2 |   20.008s | 27.228MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_232_21_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_inconsistent_post___00.smt2 |   20.008s | 27.524MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_21_75_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_range_check___00.smt2 |   20.008s | 24.62MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_175_14_overflow_check___00.smt2 |   20.008s | 44.036MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_218_21_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_inconsistent_post___00.smt2 |   20.008s | 23.208MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_57_17_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_inconsistent_pre___00.smt2 |   20.008s | 27.4MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/Q418-004__bitwise_or__bitset.ads_31_15_postcondition___00.smt2 |   20.008s | 25.908MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_151_21_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_inconsistent_post___00.smt2 |   20.008s | 27.208MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_216_31_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_assert___00.smt2 |   20.008s | 34.844MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_220_28_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_assert___00.smt2 |   20.008s | 26.268MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_220_28_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_assert___00.smt2 |   20.008s | 25.064MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_140_11_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_inconsistent_pre___00.smt2 |   20.008s | 33.9MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_122_92_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_range_check___00.smt2 |   20.008s | 27.476MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/N127-046__mod__mod_bound.ads_9_20_postcondition___00.smt2 |   20.008s | 25.992MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/MA25-018__pure_global__p.adb_22_38_range_check___00.smt2 |   20.008s | 23.472MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_38_22_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_assert___00.smt2 |   20.008s | 27.508MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_192_21_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_inconsistent_post___00.smt2 |   20.008s | 23.308MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_188_23_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_inconsistent_pre___00.smt2 |   20.008s | 27.592MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_10_36_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_range_check___00.smt2 |   20.008s | 25.584MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/proofinuse__nonlinear__nonlinear.adb_20_22_assert___00.smt2 |   20.008s | 34.1MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P114-046__invariant__inrange3.ads_18_14_postcondition___00.smt2 |   20.008s | 28.352MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_27_20_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_postcondition___00.smt2 |   20.008s | 29.108MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/N613-007__shift__my_shift.adb_9_22_assert___00.smt2 |   20.008s | 26.044MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/QA31-008__von_neumann_sqrt__p.adb_103_26_range_check___00.smt2 |   20.008s | 27.224MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_28_82_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_range_check___00.smt2 |   20.008s | 29.668MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_62_74_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_range_check___00.smt2 |   20.008s | 27.9MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/QA31-008__von_neumann_sqrt__p.adb_93_36_loop_invariant_preserv___00.smt2 |   20.008s | 27.14MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/QA31-008__von_neumann_sqrt__p.adb_94_36_loop_invariant_init___00.smt2 |   20.008s | 27.124MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_133_14_postcondition___00.smt2 |   20.008s | 33.332MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_98_45_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_division_check___00.smt2 |   20.008s | 22.008MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O318-021__modular__fpmod.adb_13_11_range_check___00.smt2 |   20.008s | 23.168MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/MA25-018__pure_global__p.adb_15_62_overflow_check___00.smt2 |   20.008s | 28.36MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/PC08-045__shift_right__example.adb_7_20_range_check___00.smt2 |   20.008s | 31.024MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/MA25-018__pure_global__p.adb_16_30_range_check___00.smt2 |   20.008s | 31.624MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_19_84_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_range_check___00.smt2 |   20.008s | 27.692MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_218_63_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_range_check___00.smt2 |   20.008s | 30.02MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/QA31-008__von_neumann_sqrt__p.adb_95_36_loop_invariant_preserv___00.smt2 |   20.008s | 27.052MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/R322-003__private_modular__mod_subtypes.ads_19_29_predicate_check___00.smt2 |   20.008s | 23.428MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/R511-031__counterexample__saturation.adb_12_38_contract_case___00.smt2 |   20.008s | 22.796MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_188_23_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_inconsistent_pre___00.smt2 |   20.008s | 28.46MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_134_11_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_inconsistent_pre___00.smt2 |   20.008s | 26.236MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/RB12-066__fixed_point_int_mult__types.ads_22_13_overflow_check___00.smt2 |   20.008s | 23.732MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/proofinuse__bitwise__bitwise.adb_51_22_assert___00.smt2 |   20.008s | 29.984MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_217_39_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_loop_invariant_preserv___00.smt2 |   20.008s | 26.1MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/QA31-008__von_neumann_sqrt__p.adb_103_26_dead_code___00.smt2 |   20.008s | 27.724MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P114-046__invariant__inrange6.ads_18_14_postcondition___00.smt2 |   20.008s | 27.356MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_112_11_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_inconsistent_pre___00.smt2 |   20.008s | 33.944MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_51_74_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_range_check___00.smt2 |   20.008s | 27.808MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/RB12-066__fixed_point_div_mod__types.ads_16_13_range_check___01.smt2 |   20.008s | 23.736MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_154_14_overflow_check___00.smt2 |   20.008s | 29.412MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_126_33_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_loop_invariant_preserv___00.smt2 |   20.008s | 32.62MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_204_21_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_inconsistent_post___00.smt2 |   20.008s | 21.892MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_49_89_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_range_check___00.smt2 |   20.008s | 24.572MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_26_19_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_inconsistent_pre___00.smt2 |   20.008s | 28.116MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P615-019__silver__division_by_zero.adb_23_27_division_check___00.smt2 |   20.008s | 28.168MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_49_89_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_range_check___00.smt2 |   20.008s | 27.872MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_300_26_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_postcondition___00.smt2 |   20.008s | 29.336MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_207_43_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_loop_invariant_preserv___00.smt2 |   20.008s | 26.064MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_131_12_overflow_check___00.smt2 |   20.008s | 24.98MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/R716-044__provide_shift_operators__main.adb_11_19_assert___00.smt2 |   20.008s | 25.864MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_60_93_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_range_check___00.smt2 |   20.008s | 27.9MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/M603-021__volatile_input_proofs__port.adb_54_16_range_check___00.smt2 |   20.008s | 34.624MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_232_21_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_inconsistent_post___00.smt2 |   20.008s | 27.908MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_98_45_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_division_check___00.smt2 |   20.008s | 22.068MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/N613-007__shift__my_shift.adb_9_32_division_check___00.smt2 |   20.008s | 25.96MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O226-018__address__worker_pack.adb_13_85_range_check___00.smt2 |   20.008s | 26.888MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_222_20_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_precondition___00.smt2 |   20.008s | 34.708MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_134_11_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_inconsistent_pre___00.smt2 |   20.008s | 27.824MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/riposte__arrays_multidim__arrays_multidim.adb_21_22_assert___00.smt2 |   20.008s | 23.204MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/QA31-008__von_neumann_sqrt__p.adb_98_36_loop_invariant_init___00.smt2 |   20.008s | 27.264MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O318-035__modular__smod.adb_8_15_range_check___00.smt2 |   20.008s | 34.848MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_49_89_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_range_check___00.smt2 |   20.008s | 27.9MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_222_20_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_precondition___00.smt2 |   20.008s | 23.212MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_106_11_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_inconsistent_pre___00.smt2 |   20.008s | 23.904MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_11_12_overflow_check___00.smt2 |   20.008s | 24.908MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_46_17_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_inconsistent_pre___00.smt2 |   20.009s | 25.436MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_32_14_division_check___00.smt2 |   20.009s | 23.344MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_176_14_division_check___00.smt2 |   20.009s | 31.904MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_286_21_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_inconsistent_post___00.smt2 |   20.009s | 27.444MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/LC17-035__update_attribute_multidim__update_logic_fn.ads_139_19_postcondition___00.smt2 |   20.009s | 25.736MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_82_14_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_postcondition___00.smt2 |   20.009s | 22.212MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_126_33_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_loop_invariant_preserv___00.smt2 |   20.009s | 28.172MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/QA31-008__von_neumann_sqrt__p.adb_91_36_loop_invariant_init___00.smt2 |   20.009s | 27.152MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/riposte__arrays_multidim__arrays_multidim.adb_46_22_assert___00.smt2 |   20.009s | 29.368MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_31_75_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_range_check___00.smt2 |   20.009s | 28.072MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/Q420-007__power_modular__non_binary_mod_power.adb_17_19_assert___00.smt2 |   20.009s | 23.044MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/QA31-008__von_neumann_sqrt__p.adb_79_17_division_check___00.smt2 |   20.009s | 27.104MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_152_14_division_check___00.smt2 |   20.009s | 29.276MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_158_21_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_inconsistent_post___00.smt2 |   20.009s | 26.752MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/Q420-007__power_modular__non_binary_mod_power.adb_15_12_overflow_check___00.smt2 |   20.009s | 23.044MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_182_20_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_precondition___00.smt2 |   20.009s | 22.74MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P512-044__exist_on_bv__x86.adb_55_20_x86.adb_99_7_loop_invariant_preserv___00.smt2 |   20.009s | 31.888MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/QA31-008__von_neumann_sqrt__p.adb_91_36_loop_invariant_preserv___00.smt2 |   20.009s | 27.128MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_118_14_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_postcondition___00.smt2 |   20.009s | 31.056MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/QA31-008__von_neumann_sqrt__p.adb_89_55_range_check___00.smt2 |   20.009s | 27.064MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/R716-044__provide_shift_operators__main.adb_7_19_assert___00.smt2 |   20.009s | 26.028MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_9_36_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_range_check___00.smt2 |   20.009s | 23.468MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_1550_53_range_check___00.smt2 |   20.009s | 26.484MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_214_28_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_assert___00.smt2 |   20.009s | 23.188MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_176_15_postcondition___00.smt2 |   20.009s | 45.084MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_105_66_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_range_check___00.smt2 |   20.009s | 23.012MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_28_82_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_range_check___00.smt2 |   20.009s | 28.564MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/QA31-008__von_neumann_sqrt__p.adb_97_36_loop_invariant_init___00.smt2 |   20.009s | 27.052MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/L719-025__hashed_sets_equal__p.ads_24_29_precondition___00.smt2 |   20.009s | 28.416MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/Q418-004__bitwise_or__bitset.ads_23_15_postcondition___00.smt2 |   20.009s | 25.908MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/QA31-008__von_neumann_sqrt__p.adb_95_36_loop_invariant_init___00.smt2 |   20.009s | 27.248MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_134_11_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_inconsistent_pre___00.smt2 |   20.009s | 34.096MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/QA31-008__von_neumann_sqrt__p.adb_94_36_loop_invariant_preserv___00.smt2 |   20.009s | 27.772MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_26_15_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_inconsistent_pre___00.smt2 |   20.009s | 24.036MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_286_21_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_inconsistent_post___00.smt2 |   20.009s | 27.688MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/R403-031__counterexample__p.adb_53_23_division_check___00.smt2 |   20.009s | 25.908MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_144_21_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_inconsistent_post___00.smt2 |   20.009s | 27.468MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/MC06-019__shift_divide__p.ads_10_19_postcondition___00.smt2 |   20.009s | 25.992MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_106_11_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_inconsistent_pre___00.smt2 |   20.009s | 34.06MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_179_12_overflow_check___00.smt2 |   20.009s | 25.076MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/L102-013__bitwise__p.adb_13_7_dead_code___00.smt2 |   20.009s | 23.1MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/QA31-008__von_neumann_sqrt__p.adb_97_36_loop_invariant_preserv___00.smt2 |   20.009s | 27.78MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_16_19_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_inconsistent_pre___00.smt2 |   20.009s | 25.352MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_27_20_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_postcondition___00.smt2 |   20.009s | 27.964MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_180_28_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_assert___00.smt2 |   20.009s | 22.652MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_46_17_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_inconsistent_pre___00.smt2 |   20.009s | 26.82MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_27_20_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_postcondition___00.smt2 |   20.009s | 27.276MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_290_21_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_inconsistent_post___00.smt2 |   20.009s | 27.592MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_117_13_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_inconsistent_pre___00.smt2 |   20.009s | 27.096MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/M529-013__modular__modular.adb_7_66_range_check___00.smt2 |   20.009s | 26.516MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/L719-025__hashed_maps_equal__p.ads_35_40_precondition___00.smt2 |   20.009s | 24.604MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/M529-013__modular__modular.adb_7_61_overflow_check___00.smt2 |   20.009s | 26.472MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_232_21_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_inconsistent_post___00.smt2 |   20.009s | 27.512MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_118_14_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_postcondition___00.smt2 |   20.009s | 31.24MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_140_11_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_inconsistent_pre___00.smt2 |   20.009s | 26.1MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_137_15_postcondition___00.smt2 |   20.009s | 45.168MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/QA31-008__von_neumann_sqrt__p.adb_92_56_range_check___00.smt2 |   20.009s | 27.072MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/QA31-008__von_neumann_sqrt__p.ads_14_19_postcondition___00.smt2 |   20.009s | 27.016MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/QA31-008__von_neumann_sqrt__p.adb_93_36_loop_invariant_init___00.smt2 |   20.009s | 27.232MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_217_39_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_loop_invariant_init___00.smt2 |   20.009s | 26.24MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/Q418-004__power_modular__overflow_modulus.adb_13_19_assert___00.smt2 |   20.009s | 28.036MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P615-019__silver__division_by_zero.adb_22_27_division_check___00.smt2 |   20.009s | 26.036MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_303_26_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_postcondition___00.smt2 |   20.009s | 34.888MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_192_21_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_inconsistent_post___00.smt2 |   20.009s | 23.26MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-022__bitwise_rotate__test_rotate.adb_13_14_postcondition___00.smt2 |   20.009s | 28.404MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P615-019__silver__range_check.adb_28_12_range_check___00.smt2 |   20.009s | 26.668MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_83_12_overflow_check___00.smt2 |   20.009s | 24.976MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P922-044__fe_simplification_on_modulars__p.adb_7_22_assert___00.smt2 |   20.009s | 26.256MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_105_14_overflow_check___00.smt2 |   20.009s | 29.268MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_217_39_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_loop_invariant_preserv___00.smt2 |   20.009s | 34.868MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_10_14_overflow_check___00.smt2 |   20.009s | 31.876MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_26_19_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_inconsistent_pre___00.smt2 |   20.009s | 27.38MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/MA25-018__pure_global__p.adb_22_38_overflow_check___00.smt2 |   20.009s | 28.46MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/MC06-015__contracts_on_intrinsics__p.adb_16_13_precondition___00.smt2 |   20.009s | 27.032MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_39_56_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_division_check___00.smt2 |   20.009s | 27.356MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_118_14_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_postcondition___00.smt2 |   20.009s | 31.288MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_207_43_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_loop_invariant_init___00.smt2 |   20.009s | 26.048MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_49_89_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_range_check___00.smt2 |   20.009s | 27.224MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/L102-013__bitwise__p.adb_4_24_range_check___00.smt2 |   20.009s | 22.908MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_188_23_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_inconsistent_pre___00.smt2 |   20.009s | 29.376MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__abs_controller_supplier_with_property.adb_49_40_range_check___00.smt2 |   20.009s | 27.74MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_152_14_range_check___00.smt2 |   20.009s | 34.932MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_59_15_postcondition___00.smt2 |   20.009s | 44.992MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O730-002__counterex_bitwise__saturate.adb_4_16_postcondition___00.smt2 |   20.009s | 26.076MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_98_45_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_division_check___00.smt2 |   20.009s | 22.22MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P114-046__invariant__inrange4.adb_16_33_loop_invariant_preserv___00.smt2 |   20.009s | 23.972MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P630-037__keccak__keccak-types.ads_119_63_range_check___00.smt2 |   20.010s | 28.596MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_128_14_division_check___00.smt2 |   20.010s | 23.372MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P630-037__keccak__keccak-types.ads_109_62_range_check___00.smt2 |   20.010s | 26.808MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_1559_53_range_check___00.smt2 |   20.010s | 26.416MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_214_28_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_assert___00.smt2 |   20.010s | 34.908MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_39_56_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_division_check___00.smt2 |   20.010s | 27.752MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_58_14_overflow_check___00.smt2 |   20.010s | 32.44MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P512-044__exist_on_bv__x86.adb_75_37_x86.adb_99_7_assert___00.smt2 |   20.010s | 29.02MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_176_23_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_inconsistent_pre___00.smt2 |   20.010s | 27.908MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_60_93_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_range_check___00.smt2 |   20.010s | 27.736MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_51_74_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_range_check___00.smt2 |   20.010s | 27.22MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_112_11_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_inconsistent_pre___00.smt2 |   20.010s | 26.068MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_256_21_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_inconsistent_post___00.smt2 |   20.010s | 27.456MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O204-022__bitwise_rotate__test_rotate.adb_19_39_range_check___00.smt2 |   20.010s | 28.4MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_222_20_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_precondition___00.smt2 |   20.010s | 26.2MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_55_14_overflow_check___00.smt2 |   20.010s | 32.644MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_16_19_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_inconsistent_pre___00.smt2 |   20.010s | 27.86MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_286_21_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_inconsistent_post___00.smt2 |   20.010s | 27.828MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/LC17-035__update_attribute_multidim__update_logic_fn.ads_49_14_postcondition___00.smt2 |   20.010s | 53.672MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/LC17-035__update_attribute_multidim__update_logic_fn.ads_89_14_postcondition___00.smt2 |   20.010s | 24.552MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/proofinuse__bitwise__bitwise.adb_40_22_assert___00.smt2 |   20.010s | 25.784MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/QA11-003__itp_example__test.adb_47_17_postcondition___00.smt2 |   20.010s | 28.352MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_216_31_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_assert___00.smt2 |   20.010s | 25.052MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_127_14_overflow_check___00.smt2 |   20.010s | 25.308MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_300_26_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_postcondition___00.smt2 |   20.010s | 22.692MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_105_66_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_range_check___00.smt2 |   20.010s | 29.756MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/M529-013__modular__modular.adb_7_23_postcondition___00.smt2 |   20.010s | 26.492MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_151_21_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_inconsistent_post___00.smt2 |   20.010s | 26.62MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/QA31-008__von_neumann_sqrt__p.ads_16_49_overflow_check___00.smt2 |   20.010s | 27.116MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/N613-007__bitwise__sandbox.adb_14_26_range_check___00.smt2 |   20.010s | 31.788MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_106_11_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_inconsistent_pre___00.smt2 |   20.010s | 27.956MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_218_63_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_range_check___00.smt2 |   20.010s | 23.272MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/R514-028__ce__saturation.adb_11_23_postcondition___00.smt2 |   20.010s | 22.848MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/R403-031__counterexample__p.adb_39_25_assert___00.smt2 |   20.010s | 30.472MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P512-044__exist_on_bv__x86.adb_82_19_x86.adb_99_7_assert___00.smt2 |   20.010s | 40.908MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_256_21_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_inconsistent_post___00.smt2 |   20.010s | 27.168MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_188_23_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_inconsistent_pre___00.smt2 |   20.010s | 27.768MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_204_21_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_inconsistent_post___00.smt2 |   20.010s | 21.904MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_81_13_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_inconsistent_pre___00.smt2 |   20.010s | 22.352MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_29_98_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_range_check___00.smt2 |   20.010s | 28.584MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/QA31-008__von_neumann_sqrt__p.adb_88_54_range_check___00.smt2 |   20.010s | 27.9MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_46_17_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_inconsistent_pre___00.smt2 |   20.010s | 29.476MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/proofinuse__ce__counter_examples.adb_19_25_assert___00.smt2 |   20.010s | 23.476MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_192_21_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_inconsistent_post___00.smt2 |   20.010s | 23.228MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/riposte__usergroup_examples__usergroup_examples.adb_59_19_postcondition___00.smt2 |   20.010s | 32.524MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P630-037__keccak__keccak-types.ads_115_63_range_check___00.smt2 |   20.010s | 28.696MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_214_28_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_assert___00.smt2 |   20.010s | 26.384MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/KC05-038__modulo__p.adb_7_24_range_check___00.smt2 |   20.010s | 28.808MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_217_39_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_loop_invariant_preserv___00.smt2 |   20.010s | 25.084MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_29_98_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_range_check___00.smt2 |   20.010s | 28.112MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/QA31-008__von_neumann_sqrt__p.adb_100_17_division_check___00.smt2 |   20.010s | 27.148MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_106_11_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_inconsistent_pre___00.smt2 |   20.010s | 26.236MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_7_14_overflow_check___00.smt2 |   20.010s | 23.596MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_28_82_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_range_check___00.smt2 |   20.010s | 26.968MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/QA31-008__von_neumann_sqrt__p.adb_77_10_dead_code___00.smt2 |   20.010s | 27.216MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_56_14_division_check___00.smt2 |   20.010s | 31.98MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/riposte__arrays_multidim__arrays_multidim.adb_38_22_assert___00.smt2 |   20.010s | 30.252MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_104_14_division_check___00.smt2 |   20.010s | 29.304MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/OA20-014__big_shift__u.adb_13_19_assert___00.smt2 |   20.010s | 26.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_112_11_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_inconsistent_pre___00.smt2 |   20.010s | 27.796MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/LC17-035__update_attribute_multidim__update_logic_fn.ads_75_14_postcondition___00.smt2 |   20.010s | 31.864MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_126_33_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_loop_invariant_init___00.smt2 |   20.011s | 31.256MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_192_24_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_inconsistent_post___00.smt2 |   20.011s | 25.128MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/RB12-066__fixed_point_int_mult__types.ads_22_13_range_check___00.smt2 |   20.011s | 66.46MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_207_43_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_loop_invariant_preserv___00.smt2 |   20.011s | 23.976MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__abs_controller_supplier_with_property.adb_93_22_assert___00.smt2 |   20.011s | 27.648MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_94_14_postcondition___00.smt2 |   20.011s | 32.18MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_81_13_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_inconsistent_pre___00.smt2 |   20.011s | 22.304MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/MA25-018__pure_global__p.adb_15_62_range_check___00.smt2 |   20.011s | 23.492MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_176_23_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_inconsistent_pre___00.smt2 |   20.011s | 27.912MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_256_21_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_inconsistent_post___00.smt2 |   20.011s | 27.156MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/MC06-019__shift_divide__p.ads_13_19_postcondition___00.smt2 |   20.011s | 26.032MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_126_33_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_loop_invariant_init___00.smt2 |   20.011s | 31.156MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/KC05-038__modulo__p.adb_11_22_range_check___00.smt2 |   20.011s | 28.916MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/RB12-066__fixed_point_int_mult__types.ads_6_12_range_check___01.smt2 |   20.011s | 68.368MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_153_14_range_check___00.smt2 |   20.011s | 32.628MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O501-016__array_of_bv__x86.ads_172_14_postcondition___00.smt2 |   20.011s | 31.936MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_11_36_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_range_check___00.smt2 |   20.011s | 23.532MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P512-044__exist_on_bv__x86.adb_60_28_x86.adb_99_7_assert___00.smt2 |   20.011s | 46.1MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_220_28_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_assert___00.smt2 |   20.011s | 34.768MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_26_15_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_inconsistent_pre___00.smt2 |   20.011s | 24.064MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_60_93_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_range_check___00.smt2 |   20.011s | 27.172MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_214_28_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_assert___00.smt2 |   20.011s | 28.08MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_82_14_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_postcondition___00.smt2 |   20.011s | 22.168MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_158_21_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_inconsistent_post___00.smt2 |   20.011s | 28.524MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P512-044__exist_on_bv__x86.adb_79_22_x86.adb_99_7_loop_invariant_preserv___00.smt2 |   20.011s | 27.424MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_39_56_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_division_check___00.smt2 |   20.012s | 29.512MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_11_36_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_range_check___00.smt2 |   20.012s | 25.416MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_218_21_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_inconsistent_post___00.smt2 |   20.012s | 23.268MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_62_74_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_range_check___00.smt2 |   20.012s | 27.02MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/RB12-066__fixed_point_int_mult__types.ads_10_12_range_check___00.smt2 |   20.012s | 68.332MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_140_11_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_inconsistent_pre___00.smt2 |   20.012s | 23.68MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_16_19_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_inconsistent_pre___00.smt2 |   20.012s | 27.02MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_199_29_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_postcondition___00.smt2 |   20.012s | 28.396MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_39_56_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_division_check___00.smt2 |   20.012s | 29.672MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P630-037__keccak__keccak-types.ads_123_63_range_check___00.smt2 |   20.012s | 26.828MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_300_26_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_postcondition___00.smt2 |   20.012s | 22.704MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_129_14_overflow_check___00.smt2 |   20.012s | 23.472MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/KC05-038__modulo__p.adb_10_22_range_check___00.smt2 |   20.012s | 28.816MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_181_21_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_inconsistent_post___00.smt2 |   20.012s | 23.26MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/riposte__alpha_launch_examples__alpha_launch_examples.adb_40_19_postcondition___00.smt2 |   20.012s | 32.584MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_151_21_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_inconsistent_post___00.smt2 |   20.013s | 27.172MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_232_21_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_inconsistent_post___00.smt2 |   20.013s | 27.436MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/Q418-004__power_modular__overflow_modulus.adb_11_19_assert___00.smt2 |   20.013s | 28.108MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_105_66_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_range_check___00.smt2 |   20.013s | 29.48MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/QA31-008__von_neumann_sqrt__p.adb_93_38_division_check___00.smt2 |   20.013s | 27.112MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_158_21_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_inconsistent_post___00.smt2 |   20.013s | 26.052MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P114-046__invariant__inrange2.ads_18_14_postcondition___00.smt2 |   20.013s | 23.748MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_79_14_overflow_check___00.smt2 |   20.014s | 44.048MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_81_13_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_inconsistent_pre___00.smt2 |   20.014s | 22.064MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_38_22_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_assert___00.smt2 |   20.014s | 28.32MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P630-037__keccak__keccak-types.ads_101_62_range_check___00.smt2 |   20.014s | 28.652MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/R716-044__provide_shift_operators__main.adb_9_19_assert___00.smt2 |   20.014s | 25.984MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P512-044__exist_on_bv__x86.ads_22_14_postcondition___00.smt2 |   20.014s | 32.844MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/RB12-066__fixed_point_int_mult__types.ads_16_13_range_check___00.smt2 |   20.015s | 23.716MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_217_39_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_loop_invariant_init___00.smt2 |   20.015s | 25.084MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_154_14_range_check___00.smt2 |   20.015s | 32.496MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_218_21_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_inconsistent_post___00.smt2 |   20.016s | 23.26MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/QA31-008__von_neumann_sqrt__p.adb_92_36_loop_invariant_init___00.smt2 |   20.016s | 26.996MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_218_63_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_range_check___00.smt2 |   20.016s | 25.016MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/Q714-010__address__pixel.adb_21_63_division_check___00.smt2 |   20.016s | 29.064MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SA16-042__alignment__bug_align.adb_11_20_assert___00.smt2 |   20.016s | 23.628MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_117_13_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_inconsistent_pre___00.smt2 |   20.016s | 27.18MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/QA31-008__von_neumann_sqrt__p.ads_14_44_overflow_check___00.smt2 |   20.017s | 27.248MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_21_75_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_range_check___00.smt2 |   20.017s | 27.272MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_216_31_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_assert___00.smt2 |   20.017s | 23.272MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_204_21_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_inconsistent_post___00.smt2 |   20.018s | 21.832MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_82_14_overflow_check___00.smt2 |   20.018s | 32.544MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/MA25-018__pure_global__p.adb_23_30_range_check___00.smt2 |   20.020s | 28.408MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_192_24_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_inconsistent_post___00.smt2 |   20.020s | 25.988MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_1568_52_range_check___00.smt2 |   20.020s | 28.212MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_122_92_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_range_check___00.smt2 |   20.020s | 23.252MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_107_12_overflow_check___00.smt2 |   20.021s | 29.248MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/RB12-066__fixed_point_int_mult__types.ads_28_12_range_check___00.smt2 |   20.021s | 248.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_192_21_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_inconsistent_post___00.smt2 |   20.021s | 23.264MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_9_14_overflow_check___00.smt2 |   20.021s | 23.368MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/proofinuse__bitwise__bitwise.adb_22_22_assert___00.smt2 |   20.021s | 25.912MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_134_11_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_inconsistent_pre___00.smt2 |   20.021s | 23.904MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_118_14_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_postcondition___00.smt2 |   20.021s | 29.376MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P512-044__exist_on_bv__x86.adb_50_22_x86.adb_99_7_assert___00.smt2 |   20.021s | 24.46MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/QA31-008__von_neumann_sqrt__p.adb_92_36_loop_invariant_preserv___00.smt2 |   20.022s | 27.144MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_290_21_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_inconsistent_post___00.smt2 |   20.022s | 27.84MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_151_21_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_inconsistent_post___00.smt2 |   20.022s | 27.472MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O318-035__modular__smod.adb_12_14_range_check___00.smt2 |   20.022s | 34.94MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/QA31-008__von_neumann_sqrt__p.adb_96_36_loop_invariant_preserv___00.smt2 |   20.022s | 27.112MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_60_93_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_range_check___00.smt2 |   20.022s | 24.5MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_122_92_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_range_check___00.smt2 |   20.022s | 27.176MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/KC02-007__modulo__p.ads_7_14_postcondition___00.smt2 |   20.023s | 25.884MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_105_66_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_range_check___00.smt2 |   20.023s | 29.628MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_303_26_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_postcondition___00.smt2 |   20.023s | 23.264MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_290_21_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_inconsistent_post___00.smt2 |   20.023s | 27.852MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/R306-015__touch__bitwise_swap.adb_4_11_postcondition___00.smt2 |   20.023s | 28.48MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_286_21_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_inconsistent_post___00.smt2 |   20.023s | 27.896MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_130_14_overflow_check___00.smt2 |   20.023s | 23.472MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P630-037__keccak__keccak-types.ads_136_8_precondition___00.smt2 |   20.024s | 28.212MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/Q515-026__sk__gen.ads_14_14_test.ads_10_4_postcondition___00.smt2 |   20.024s | 24.028MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P512-044__exist_on_bv__x86.adb_83_31_x86.adb_99_7_assert___00.smt2 |   20.024s | 27.996MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_81_14_overflow_check___00.smt2 |   20.024s | 34.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_192_24_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_inconsistent_post___00.smt2 |   20.024s | 25.98MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_126_33_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_loop_invariant_preserv___00.smt2 |   20.025s | 31.064MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P630-037__keccak__keccak-types.ads_105_62_range_check___00.smt2 |   20.025s | 28.576MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_217_39_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_loop_invariant_preserv___00.smt2 |   20.025s | 23.156MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/QA31-008__von_neumann_sqrt__p.adb_94_58_range_check___00.smt2 |   20.025s | 27.704MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/N811-037__static_pred_modular__t.adb_10_13_predicate_check___00.smt2 |   20.025s | 24.516MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_51_74_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_range_check___00.smt2 |   20.025s | 27.788MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_106_14_overflow_check___00.smt2 |   20.025s | 24.168MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_144_21_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_inconsistent_post___00.smt2 |   20.025s | 27.204MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_155_12_overflow_check___00.smt2 |   20.025s | 33.088MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_220_28_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_assert___00.smt2 |   20.025s | 23.204MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/proofinuse__bitwise__bitwise.adb_39_50_range_check___00.smt2 |   20.026s | 24.276MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_218_21_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_inconsistent_post___00.smt2 |   20.026s | 23.276MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_126_33_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_loop_invariant_preserv___00.smt2 |   20.026s | 31.08MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P615-019__silver__division_by_zero.adb_21_27_division_check___00.smt2 |   20.026s | 25.996MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/L102-013__bitwise__p.adb_7_7_dead_code___00.smt2 |   20.026s | 23.092MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_33_14_overflow_check___00.smt2 |   20.026s | 23.616MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_26_15_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_inconsistent_pre___00.smt2 |   20.026s | 24.048MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_256_21_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_inconsistent_post___00.smt2 |   20.026s | 26.624MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/Q418-004__bitwise_or__bitset.ads_15_15_postcondition___00.smt2 |   20.027s | 25.996MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_151_14_range_check___00.smt2 |   20.027s | 29.208MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_21_75_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_range_check___00.smt2 |   20.027s | 27.728MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_207_43_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_loop_invariant_preserv___00.smt2 |   20.027s | 28.456MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/O203-002__shift__shift_range.adb_16_18_range_check___00.smt2 |   20.027s | 28.524MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_217_39_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_loop_invariant_init___00.smt2 |   20.027s | 23.2MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_126_33_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_loop_invariant_init___00.smt2 |   20.027s | 31.104MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P201-069__simulink__simulink_functions.adb_1532_51_range_check___00.smt2 |   20.027s | 22.784MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_31_75_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_range_check___00.smt2 |   20.027s | 28.552MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_34_14_overflow_check___00.smt2 |   20.027s | 23.584MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_181_21_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_inconsistent_post___00.smt2 |   20.028s | 23.12MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/L102-013__bitwise__p.adb_10_7_dead_code___00.smt2 |   20.028s | 23.1MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/RB12-066__fixed_point_int_mult__types.ads_16_13_range_check___01.smt2 |   20.028s | 59.772MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_10_36_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_range_check___00.smt2 |   20.028s | 23.536MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/R403-031__counterexample__p.adb_43_25_assert___00.smt2 |   20.028s | 29.032MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/N613-007__shift__my_shift.adb_7_22_assert___00.smt2 |   20.028s | 25.912MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_57_14_overflow_check___00.smt2 |   20.029s | 33.392MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/R716-044__provide_shift_operators__main.adb_13_19_assert___00.smt2 |   20.029s | 25.884MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_204_21_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_43_4_inconsistent_post___00.smt2 |   20.031s | 21.98MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/proofinuse__bitwise__bitwise.adb_20_22_assert___00.smt2 |   20.032s | 25.952MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_182_20_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_precondition___00.smt2 |   20.033s | 22.756MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_21_75_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_44_4_range_check___00.smt2 |   20.033s | 27.984MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.ads_144_21_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_42_4_inconsistent_post___00.smt2 |   20.033s | 27.432MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/RB12-066__fixed_point_div_mod__types.ads_10_12_range_check___01.smt2 |   20.033s | 23.376MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_178_14_overflow_check___00.smt2 |   20.034s | 32.528MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P512-044__exist_on_bv__x86.ads_16_14_postcondition___00.smt2 |   20.034s | 25.572MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/SB22-003__no_wrap_around__nwa.adb_103_14_overflow_check___00.smt2 |   20.040s | 29.4MiB| timeout | 0 |  |  |
|non-incremental/UFBVDTNIRA/20200306-Kanig/spark2014bench/P508-001__bits_manipulation__bits_manipulation-functions.adb_182_20_bits_manipulation_unsigned.ads_20_7_bits_manipulation_unsigned.ads_45_4_precondition___00.smt2 |   20.044s | 27.312MiB| timeout | 0 |  |  |
