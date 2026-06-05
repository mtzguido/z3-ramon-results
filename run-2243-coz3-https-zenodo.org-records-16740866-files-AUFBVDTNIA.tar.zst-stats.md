# .

* SAT 1
* UNSAT 237
* TIMEOUT 314
* UNKNOWN 0

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/AUFBVDTNIA.tar.zst?download=1 | Source list: quantifier_benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-AUFBVDTNIA.tar.zst
Runner: rise-runner-1
Z3 repo: Z3Prover/z3
Z3 commit: c3f5365a95a7eac2419a2f95ff240909f275cc08
Z3 branch: c3f5365a95a7eac2419a2f95ff240909f275cc08
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/AUFBVDTNIA.tar.zst?download=1
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
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1542_36_loop_invariant_init_1.smt2 |    0.014s | 19.236MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_640_36_mlkem.adb_1022_7_division_check_1.smt2 |    0.015s | 19.26MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_623_62_mlkem.adb_866_7_division_check_1.smt2 |    0.016s | 18.976MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_230_30_division_check_1.smt2 |    0.016s | 19.152MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_262_25_assert_1.smt2 |    0.016s | 19.176MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_989_15_index_check_1.smt2 |    0.016s | 19.188MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_638_35_mlkem.adb_1511_7_division_check_1.smt2 |    0.016s | 19.028MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_439_21_mlkem.adb_1511_7_postcondition_1.smt2 |    0.016s | 19.368MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_439_21_mlkem.adb_1062_7_postcondition_1.smt2 |    0.016s | 19.388MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_2012_13_range_check_1.smt2 |    0.016s | 19.028MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_638_35_mlkem.adb_1096_7_division_check_1.smt2 |    0.016s | 19.028MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_2070_27_range_check_1.smt2 |    0.016s | 18.996MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_423_21_mlkem.adb_985_7_postcondition_1.smt2 |    0.016s | 19.172MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_638_35_mlkem.adb_1022_7_division_check_1.smt2 |    0.017s | 19.156MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_623_62_mlkem.adb_906_7_division_check_1.smt2 |    0.017s | 19.164MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_932_54_length_check_1.smt2 |    0.017s | 19.024MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_932_54_length_check2_1.smt2 |    0.017s | 19.18MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_2011_25_range_check_1.smt2 |    0.017s | 19.236MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_640_36_mlkem.adb_1062_7_division_check_1.smt2 |    0.017s | 19.056MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1930_13_range_check_1.smt2 |    0.017s | 19.112MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1957_26_range_check_1.smt2 |    0.017s | 19.248MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1026_26_predicate_check_2.smt2 |    0.017s | 19.088MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_2074_58_range_check_1.smt2 |    0.017s | 19.144MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1950_51_index_check_1.smt2 |    0.017s | 19.544MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_239_52_division_check_1.smt2 |    0.017s | 19.2MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_2064_37_range_check_1.smt2 |    0.017s | 19.02MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_439_21_mlkem.adb_1096_7_postcondition_1.smt2 |    0.017s | 19.16MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_233_25_assert_1.smt2 |    0.017s | 19.28MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_989_15_index_check2_1.smt2 |    0.017s | 19.16MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_249_25_assert_1.smt2 |    0.017s | 19.1MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_640_36_mlkem.adb_1039_7_division_check_1.smt2 |    0.017s | 19.084MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_623_62_mlkem.adb_985_7_division_check_1.smt2 |    0.017s | 19.032MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_2067_27_range_check_1.smt2 |    0.018s | 19.108MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1821_37_range_check_1.smt2 |    0.018s | 19.276MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_889_33_division_check_1.smt2 |    0.018s | 19.184MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_989_30_index_check_1.smt2 |    0.018s | 19.124MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_989_10_range_check_1.smt2 |    0.018s | 19.184MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_990_41_range_check_1.smt2 |    0.018s | 19.312MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_2037_14_complete_contract_cases_1.smt2 |    0.018s | 19.468MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1011_21_index_check_1.smt2 |    0.018s | 19.024MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1820_37_range_check_1.smt2 |    0.018s | 19.292MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1011_44_index_check2_1.smt2 |    0.018s | 19.208MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_2013_52_range_check_1.smt2 |    0.018s | 19.104MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1880_14_range_check_1.smt2 |    0.018s | 19.228MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_640_36_mlkem.adb_1511_7_division_check_1.smt2 |    0.018s | 19.236MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_537_49_range_check_1.smt2 |    0.018s | 19.156MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_664_14_division_check_1.smt2 |    0.018s | 19.232MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_989_36_length_check_1.smt2 |    0.018s | 19.276MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1528_36_loop_invariant_init_1.smt2 |    0.018s | 19.28MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_932_51_length_check2_1.smt2 |    0.018s | 19.108MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_638_35_mlkem.adb_1454_7_division_check_1.smt2 |    0.018s | 19.188MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_423_21_mlkem.adb_906_7_postcondition_1.smt2 |    0.018s | 19.168MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1011_54_length_check_1.smt2 |    0.018s | 19.172MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1471_36_loop_invariant_init_1.smt2 |    0.018s | 19.088MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_2037_14_disjoint_contract_cases_1.smt2 |    0.018s | 19.32MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_989_39_length_check2_1.smt2 |    0.019s | 19.272MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_2000_14_precondition_1.smt2 |    0.019s | 19.172MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_254_25_assert_1.smt2 |    0.019s | 19.056MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1615_33_loop_invariant_init_1.smt2 |    0.019s | 19.544MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_993_36_overflow_check2_1.smt2 |    0.019s | 19.192MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_699_14_division_check_1.smt2 |    0.019s | 19.028MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_915_33_division_check_1.smt2 |    0.019s | 19.016MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1485_36_loop_invariant_init_1.smt2 |    0.019s | 19.156MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_638_35_mlkem.adb_1062_7_division_check_1.smt2 |    0.019s | 19.108MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_2043_38_range_check_1.smt2 |    0.019s | 19.176MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_940_14_initialization_1.smt2 |    0.019s | 19.168MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_932_10_range_check_1.smt2 |    0.019s | 19.116MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1011_21_index_check2_1.smt2 |    0.019s | 19.364MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_933_33_range_check_1.smt2 |    0.019s | 19.296MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_2081_33_precondition_1.smt2 |    0.019s | 19.152MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_592_15_precondition_1.smt2 |    0.019s | 19.38MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1016_14_initialization_1.smt2 |    0.019s | 19.168MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_246_19_division_check_1.smt2 |    0.019s | 19.152MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_592_50_range_check_1.smt2 |    0.019s | 19.284MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1615_33_loop_invariant_preserv_1.smt2 |    0.019s | 19.692MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_937_22_range_check_1.smt2 |    0.019s | 19.192MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1879_30_range_check_1.smt2 |    0.019s | 18.996MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_593_15_precondition_1.smt2 |    0.019s | 19.172MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_550_50_range_check_2.smt2 |    0.019s | 19.128MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_2065_37_range_check_1.smt2 |    0.019s | 19.192MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_423_21_mlkem.adb_866_7_postcondition_1.smt2 |    0.019s | 19.024MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-SumAndMax.scala-10.smt2 |    0.019s | 19.864MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1012_33_range_check_1.smt2 |    0.020s | 19.192MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1011_54_length_check2_1.smt2 |    0.020s | 19.2MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1127_33_range_check_1.smt2 |    0.020s | 19.848MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1011_51_length_check_1.smt2 |    0.020s | 19.124MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_536_50_range_check_2.smt2 |    0.020s | 19.34MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_640_36_mlkem.adb_1096_7_division_check_1.smt2 |    0.020s | 19.048MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1957_60_index_check2_1.smt2 |    0.020s | 19.532MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_244_25_assert_1.smt2 |    0.020s | 19.02MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_989_36_length_check2_1.smt2 |    0.020s | 19.052MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-SumAndMax.scala-10.smt2 |    0.020s | 19.82MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_423_21_mlkem.adb_880_7_postcondition_1.smt2 |    0.021s | 19.168MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1601_46_overflow_check_1.smt2 |    0.021s | 19.452MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_2011_13_precondition_1.smt2 |    0.021s | 19.94MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_576_15_precondition_1.smt2 |    0.021s | 19.272MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_887_27_division_check_1.smt2 |    0.021s | 19.236MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1011_44_index_check_1.smt2 |    0.021s | 19.256MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1527_36_loop_invariant_init_1.smt2 |    0.021s | 19.212MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1990_55_range_check_1.smt2 |    0.021s | 19.196MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_989_39_length_check_1.smt2 |    0.021s | 19.048MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_964_22_assert_1.smt2 |    0.021s | 19.812MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1470_36_loop_invariant_init_1.smt2 |    0.021s | 19.032MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1087_33_range_check_1.smt2 |    0.022s | 20.024MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_914_39_range_check_1.smt2 |    0.022s | 19.2MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1431_47_division_check_1.smt2 |    0.022s | 19.276MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1599_14_range_check_1.smt2 |    0.022s | 19.564MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_439_21_mlkem.adb_1454_7_postcondition_1.smt2 |    0.022s | 19.032MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_608_15_precondition_1.smt2 |    0.022s | 19.344MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1673_42_overflow_check_1.smt2 |    0.022s | 19.568MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1026_26_predicate_check_1.smt2 |    0.022s | 19.732MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_551_49_range_check_1.smt2 |    0.022s | 19.376MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_439_21_mlkem.adb_1039_7_postcondition_1.smt2 |    0.022s | 19.028MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1422_52_range_check_1.smt2 |    0.022s | 19.284MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_992_21_range_check2_1.smt2 |    0.023s | 19.64MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1030_33_loop_invariant_init_1.smt2 |    0.023s | 19.776MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_989_30_index_check2_1.smt2 |    0.023s | 19.072MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1431_52_range_check_1.smt2 |    0.023s | 19.352MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1601_36_loop_invariant_init_1.smt2 |    0.023s | 19.476MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1484_36_loop_invariant_init_1.smt2 |    0.023s | 19.024MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1601_39_overflow_check_1.smt2 |    0.023s | 19.52MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1950_59_index_check_1.smt2 |    0.023s | 19.724MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_932_51_length_check_1.smt2 |    0.024s | 19.184MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1957_68_index_check_1.smt2 |    0.024s | 19.816MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_609_51_range_check_1.smt2 |    0.024s | 19.164MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_623_62_mlkem.adb_880_7_division_check_1.smt2 |    0.024s | 19.216MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1673_38_overflow_check_1.smt2 |    0.024s | 19.464MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_640_36_mlkem.adb_1454_7_division_check_1.smt2 |    0.024s | 19.008MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1430_69_division_check_1.smt2 |    0.024s | 19.252MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1957_60_index_check_1.smt2 |    0.024s | 19.728MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_2066_27_range_check_1.smt2 |    0.024s | 19.164MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1541_36_loop_invariant_init_1.smt2 |    0.024s | 19.068MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1012_33_range_check2_1.smt2 |    0.024s | 19.832MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_439_21_mlkem.adb_1022_7_postcondition_1.smt2 |    0.024s | 19.204MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1819_37_precondition_1.smt2 |    0.025s | 19.968MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1977_33_range_check_1.smt2 |    0.025s | 19.856MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_2072_22_range_check_1.smt2 |    0.025s | 19.288MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1812_14_initialization_1.smt2 |    0.025s | 19.024MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_992_21_range_check_1.smt2 |    0.025s | 19.084MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_638_35_mlkem.adb_1039_7_division_check_1.smt2 |    0.025s | 19.064MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1029_10_predicate_check_1.smt2 |    0.025s | 20.02MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_998_28_range_check_1.smt2 |    0.025s | 19.504MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1671_14_range_check_1.smt2 |    0.025s | 19.316MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1949_21_postcondition_1.smt2 |    0.025s | 19.88MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1032_22_assert_1.smt2 |    0.025s | 19.836MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1011_10_range_check_1.smt2 |    0.025s | 19.048MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_730_14_division_check_1.smt2 |    0.025s | 19.06MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_784_40_range_check_1.smt2 |    0.026s | 19.84MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1015_22_assert_1.smt2 |    0.026s | 20.036MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1957_13_loop_invariant_preserv_1.smt2 |    0.026s | 19.992MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1087_33_length_check_1.smt2 |    0.026s | 19.9MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_550_15_precondition_1.smt2 |    0.026s | 19.888MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1030_59_index_check_1.smt2 |    0.026s | 19.8MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1955_33_index_check_1.smt2 |    0.026s | 19.6MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1957_68_index_check2_1.smt2 |    0.026s | 20.044MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_236_46_division_check_1.smt2 |    0.026s | 19.44MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_2072_17_precondition_1.smt2 |    0.026s | 19.864MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_2076_17_range_check_1.smt2 |    0.026s | 19.196MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_2011_27_precondition_1.smt2 |    0.026s | 19.836MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_244_40_division_check_1.smt2 |    0.026s | 19.2MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1655_39_index_check_1.smt2 |    0.026s | 20.0MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1012_33_loop_invariant_init_1.smt2 |    0.027s | 19.988MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1978_33_range_check_1.smt2 |    0.027s | 20.136MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1011_10_range_check2_1.smt2 |    0.027s | 19.76MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1957_26_range_check2_1.smt2 |    0.027s | 19.896MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_932_21_index_check_1.smt2 |    0.027s | 19.2MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1955_33_index_check2_1.smt2 |    0.027s | 19.792MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_536_15_precondition_1.smt2 |    0.027s | 19.796MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1655_39_overflow_check_1.smt2 |    0.027s | 19.988MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_933_33_range_check2_1.smt2 |    0.027s | 19.968MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1957_13_loop_invariant_init_1.smt2 |    0.027s | 19.88MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_990_41_range_check2_1.smt2 |    0.028s | 19.896MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1011_51_length_check2_1.smt2 |    0.028s | 19.284MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1012_33_loop_invariant_preserv_1.smt2 |    0.028s | 20.084MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1673_36_loop_invariant_init_1.smt2 |    0.028s | 19.564MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_932_10_range_check2_1.smt2 |    0.028s | 19.928MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1030_33_loop_invariant_preserv_1.smt2 |    0.028s | 20.168MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_933_33_loop_invariant_preserv_1.smt2 |    0.028s | 20.052MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_576_50_range_check_1.smt2 |    0.029s | 19.28MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1654_25_index_check_1.smt2 |    0.029s | 20.064MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_577_15_precondition_1.smt2 |    0.029s | 19.288MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1428_52_range_check_1.smt2 |    0.029s | 19.756MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_993_31_range_check_1.smt2 |    0.030s | 19.86MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_933_33_loop_invariant_init_1.smt2 |    0.030s | 19.804MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_888_39_range_check_1.smt2 |    0.030s | 19.244MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1979_17_range_check_1.smt2 |    0.030s | 20.32MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1976_14_precondition_1.smt2 |    0.030s | 19.996MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_2070_17_precondition_1.smt2 |    0.031s | 19.788MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_913_27_division_check_1.smt2 |    0.031s | 19.444MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1979_17_length_check_1.smt2 |    0.032s | 20.392MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1029_10_predicate_check2_1.smt2 |    0.032s | 20.108MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1653_14_range_check_1.smt2 |    0.033s | 20.044MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_937_22_assert_1.smt2 |    0.033s | 20.052MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_932_21_index_check2_1.smt2 |    0.033s | 19.268MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_993_31_range_check2_1.smt2 |    0.033s | 20.14MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_550_50_range_check_1.smt2 |    0.033s | 20.46MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_233_40_division_check_1.smt2 |    0.034s | 19.04MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_990_41_length_check_1.smt2 |    0.034s | 20.4MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_230_25_assert_1.smt2 |    0.034s | 20.052MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_536_50_range_check_1.smt2 |    0.034s | 20.58MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_608_50_range_check_1.smt2 |    0.035s | 19.176MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1581_14_range_check_1.smt2 |    0.035s | 20.128MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1030_59_index_check2_1.smt2 |    0.036s | 19.988MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1929_13_range_check_1.smt2 |    0.036s | 19.06MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1434_44_range_check_1.smt2 |    0.036s | 20.596MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1422_56_range_check_1.smt2 |    0.036s | 20.552MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1422_15_precondition_1.smt2 |    0.036s | 19.8MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1127_33_length_check_1.smt2 |    0.037s | 20.048MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_957_19_postcondition_1.smt2 |    0.037s | 20.468MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_932_46_index_check_1.smt2 |    0.039s | 19.684MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1422_56_range_check_2.smt2 |    0.039s | 20.488MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_932_46_index_check2_1.smt2 |    0.039s | 19.132MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_181_25_assert_1.smt2 |    0.041s | 19.028MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1439_25_overflow_check_1.smt2 |    0.041s | 20.776MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1434_30_range_check_1.smt2 |    0.041s | 20.828MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1435_25_overflow_check_1.smt2 |    0.041s | 20.908MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_993_46_overflow_check_1.smt2 |    0.042s | 20.848MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_993_36_overflow_check_1.smt2 |    0.042s | 19.244MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1438_44_range_check_1.smt2 |    0.042s | 20.628MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_993_51_overflow_check_1.smt2 |    0.043s | 20.708MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_992_13_loop_invariant_init_1.smt2 |    0.045s | 21.58MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1670_20_predicate_check_1.smt2 |    0.045s | 21.236MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1602_51_overflow_check_1.smt2 |    0.045s | 20.84MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_989_10_range_check2_1.smt2 |    0.048s | 21.14MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_236_25_assert_1.smt2 |    0.049s | 20.304MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1438_30_range_check_1.smt2 |    0.049s | 21.072MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_998_28_length_check_1.smt2 |    0.054s | 22.072MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_993_31_length_check_1.smt2 |    0.055s | 21.828MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_993_46_overflow_check2_1.smt2 |    0.055s | 21.6MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_990_41_length_check2_1.smt2 |    0.056s | 22.516MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_993_51_overflow_check2_1.smt2 |    0.057s | 21.512MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_990_25_assert2_1.smt2 |    0.067s | 23.068MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_993_31_length_check2_1.smt2 |    0.068s | 23.204MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_990_25_assert_1.smt2 |    0.074s | 21.944MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1598_20_predicate_check_1.smt2 |    0.118s | 32.24MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_239_25_assert_1.smt2 |    0.423s | 22.024MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_257_25_assert_1.smt2 |    0.954s | 23.616MiB| unsat | 1 |  |  |
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Prime.scala-2.smt2-3.smt2 |    6.399s | 34.92MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_2053_27_index_check3_1.smt2 |   20.006s | 21.78MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_94_25_assert_1.smt2 |   20.006s | 23.64MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.ads_152_23_postcondition_1.smt2 |   20.006s | 23.592MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1807_22_assert_1.smt2 |   20.007s | 22.54MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1603_44_index_check2_1.smt2 |   20.007s | 22.876MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1672_36_loop_invariant_preserv2_1.smt2 |   20.007s | 26.52MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.ads_152_66_division_check_1.smt2 |   20.007s | 23.488MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1603_13_precondition_1.smt2 |   20.007s | 26.308MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_2054_27_index_check3_1.smt2 |   20.007s | 21.824MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_2053_46_index_check3_1.smt2 |   20.007s | 21.684MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_2038_26_contract_case_1.smt2 |   20.007s | 23.86MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_184_70_range_check_1.smt2 |   20.007s | 23.592MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1796_36_loop_invariant_init2_1.smt2 |   20.007s | 22.672MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1605_20_range_check2_1.smt2 |   20.007s | 22.748MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_2053_27_index_check_1.smt2 |   20.007s | 21.796MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_463_107_index_check_1.smt2 |   20.007s | 28.56MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1656_49_overflow_check_1.smt2 |   20.007s | 27.512MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_174_65_division_check_1.smt2 |   20.007s | 23.624MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1604_43_overflow_check2_1.smt2 |   20.007s | 22.636MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1527_36_loop_invariant_preserv_1.smt2 |   20.007s | 23.344MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1613_25_assert_1.smt2 |   20.007s | 22.796MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1849_22_assert_1.smt2 |   20.007s | 31.616MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1604_43_range_check2_1.smt2 |   20.007s | 22.868MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_2052_27_range_check2_1.smt2 |   20.007s | 21.816MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_91_17_overflow_check_1.smt2 |   20.007s | 23.632MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_960_19_postcondition_1.smt2 |   20.007s | 22.764MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1672_36_loop_invariant_init2_1.smt2 |   20.007s | 26.364MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_218_25_assert_1.smt2 |   20.007s | 23.644MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.ads_157_66_range_check_1.smt2 |   20.007s | 23.62MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1671_14_range_check2_1.smt2 |   20.007s | 26.372MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1484_36_loop_invariant_preserv_1.smt2 |   20.007s | 23.344MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_2058_27_index_check2_1.smt2 |   20.007s | 21.828MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1601_36_loop_invariant_preserv4_1.smt2 |   20.007s | 22.856MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_2058_46_index_check_1.smt2 |   20.007s | 21.728MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_194_77_division_check_1.smt2 |   20.007s | 23.504MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1601_36_loop_invariant_preserv_1.smt2 |   20.007s | 26.592MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1797_36_range_check_1.smt2 |   20.007s | 27.372MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1610_25_assert2_1.smt2 |   20.007s | 22.872MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1470_36_loop_invariant_preserv_1.smt2 |   20.007s | 23.384MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_463_14_loop_invariant_preserv3_1.smt2 |   20.008s | 28.564MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1613_25_assert2_1.smt2 |   20.008s | 22.868MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_111_27_overflow_check_1.smt2 |   20.008s | 23.432MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_155_25_assert_1.smt2 |   20.008s | 23.628MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1598_20_predicate_check2_1.smt2 |   20.008s | 22.86MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_268_25_assert_1.smt2 |   20.008s | 32.124MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1670_20_predicate_check2_1.smt2 |   20.008s | 26.216MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1796_36_loop_invariant_preserv_1.smt2 |   20.008s | 22.688MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_219_25_assert_1.smt2 |   20.008s | 23.64MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_970_56_range_check_1.smt2 |   20.008s | 27.156MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_800_22_assert_1.smt2 |   20.008s | 34.576MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_107_25_assert_1.smt2 |   20.008s | 23.572MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_622_28_mlkem.adb_985_7_division_check_1.smt2 |   20.008s | 27.888MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_622_55_mlkem.adb_866_7_division_check_1.smt2 |   20.008s | 27.748MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_971_56_range_check_1.smt2 |   20.008s | 27.068MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_2058_46_index_check3_1.smt2 |   20.008s | 21.796MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_209_18_overflow_check_1.smt2 |   20.008s | 23.608MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_2056_27_range_check3_1.smt2 |   20.008s | 21.824MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_2051_16_loop_invariant_preserv_1.smt2 |   20.008s | 21.812MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1604_36_overflow_check2_1.smt2 |   20.008s | 22.876MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_202_19_overflow_check_1.smt2 |   20.008s | 23.616MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_967_56_range_check_1.smt2 |   20.008s | 27.024MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1844_33_loop_invariant_init_1.smt2 |   20.008s | 31.7MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_829_22_assert_1.smt2 |   20.008s | 23.624MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_2052_27_range_check_1.smt2 |   20.008s | 21.828MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_220_20_range_check_1.smt2 |   20.008s | 23.632MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_670_14_division_check_1.smt2 |   20.008s | 26.972MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.ads_152_66_range_check_1.smt2 |   20.008s | 23.58MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1604_43_overflow_check_1.smt2 |   20.008s | 26.196MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_272_38_range_check_1.smt2 |   20.008s | 32.204MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1602_36_loop_invariant_init2_1.smt2 |   20.008s | 22.644MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1796_36_range_check4_1.smt2 |   20.008s | 22.628MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_281_20_range_check_1.smt2 |   20.008s | 25.796MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.ads_157_23_postcondition_1.smt2 |   20.008s | 23.56MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1887_33_loop_invariant_preserv_1.smt2 |   20.008s | 31.964MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_205_25_assert_1.smt2 |   20.008s | 23.588MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_272_38_division_check_1.smt2 |   20.008s | 31.928MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1601_36_loop_invariant_preserv2_1.smt2 |   20.008s | 22.86MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1541_36_loop_invariant_preserv_1.smt2 |   20.008s | 23.396MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_2058_27_index_check_1.smt2 |   20.008s | 21.8MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1673_38_overflow_check4_1.smt2 |   20.008s | 26.488MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_972_56_range_check_1.smt2 |   20.008s | 27.052MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1672_36_loop_invariant_preserv_1.smt2 |   20.008s | 26.16MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_2057_46_index_check3_1.smt2 |   20.008s | 21.824MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_2054_46_index_check3_1.smt2 |   20.008s | 21.676MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1529_20_range_check_1.smt2 |   20.008s | 23.364MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.ads_173_44_range_check_1.smt2 |   20.008s | 32.132MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_177_25_assert_1.smt2 |   20.008s | 23.6MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1677_43_overflow_check_1.smt2 |   20.008s | 26.54MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1797_36_range_check2_1.smt2 |   20.008s | 22.692MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_622_28_mlkem.adb_880_7_division_check_1.smt2 |   20.008s | 27.908MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_969_56_range_check_1.smt2 |   20.008s | 27.144MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_187_70_range_check_1.smt2 |   20.008s | 23.604MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1542_36_loop_invariant_preserv_1.smt2 |   20.008s | 23.376MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.ads_162_66_range_check_1.smt2 |   20.008s | 23.644MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1797_36_range_check3_1.smt2 |   20.008s | 22.812MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_187_25_assert_1.smt2 |   20.008s | 23.628MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.ads_162_23_postcondition_1.smt2 |   20.008s | 23.404MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_219_39_division_check_1.smt2 |   20.008s | 23.544MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1844_33_loop_invariant_preserv_1.smt2 |   20.008s | 31.572MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1602_51_overflow_check4_1.smt2 |   20.008s | 22.856MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_197_24_division_check_1.smt2 |   20.008s | 23.648MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_98_20_range_check_1.smt2 |   20.008s | 23.544MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_463_80_initialization2_1.smt2 |   20.008s | 28.536MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1602_36_loop_invariant_preserv_1.smt2 |   20.008s | 26.308MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1601_39_overflow_check2_1.smt2 |   20.008s | 26.428MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_200_25_assert_1.smt2 |   20.008s | 23.648MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_116_25_assert_1.smt2 |   20.008s | 23.6MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_114_25_assert_1.smt2 |   20.008s | 23.64MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1678_20_range_check_1.smt2 |   20.008s | 26.324MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1677_39_overflow_check2_1.smt2 |   20.008s | 26.456MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_2051_16_loop_invariant_preserv4_1.smt2 |   20.009s | 21.792MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_826_14_division_check_1.smt2 |   20.009s | 23.628MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_184_89_division_check_1.smt2 |   20.009s | 23.612MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_463_22_range_check_1.smt2 |   20.009s | 28.556MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1604_36_overflow_check_1.smt2 |   20.009s | 26.244MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_178_25_assert_1.smt2 |   20.009s | 23.516MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1677_39_overflow_check_1.smt2 |   20.009s | 26.532MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_111_17_overflow_check_1.smt2 |   20.009s | 23.624MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1797_36_range_check4_1.smt2 |   20.009s | 22.596MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_463_95_index_check_1.smt2 |   20.009s | 31.472MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1612_25_assert_1.smt2 |   20.009s | 22.836MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_2054_27_index_check_1.smt2 |   20.009s | 21.808MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_2058_46_index_check2_1.smt2 |   20.009s | 21.804MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1796_36_range_check_1.smt2 |   20.009s | 28.448MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1583_22_index_check_1.smt2 |   20.009s | 27.556MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_671_22_range_check_1.smt2 |   20.009s | 26.928MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1656_22_overflow_check_1.smt2 |   20.009s | 27.26MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1887_33_loop_invariant_init_1.smt2 |   20.009s | 31.816MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1601_39_overflow_check4_1.smt2 |   20.009s | 22.86MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1841_22_assert_1.smt2 |   20.009s | 31.716MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1601_46_overflow_check2_1.smt2 |   20.009s | 26.44MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_200_70_overflow_check_1.smt2 |   20.009s | 23.608MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1674_36_loop_invariant_init_1.smt2 |   20.009s | 26.556MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_178_64_division_check_1.smt2 |   20.009s | 23.644MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_2053_46_index_check2_1.smt2 |   20.009s | 21.812MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1600_36_loop_invariant_preserv2_1.smt2 |   20.009s | 22.852MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1472_20_range_check_1.smt2 |   20.009s | 23.364MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_622_55_mlkem.adb_985_7_division_check_1.smt2 |   20.009s | 27.792MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1656_49_index_check_1.smt2 |   20.009s | 27.556MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_463_95_index_check2_1.smt2 |   20.009s | 28.392MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1603_44_index_check_1.smt2 |   20.009s | 26.528MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1612_25_assert2_1.smt2 |   20.009s | 22.876MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_197_24_range_check_1.smt2 |   20.009s | 23.66MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1802_33_range_check_1.smt2 |   20.009s | 22.696MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_463_83_index_check2_1.smt2 |   20.009s | 28.36MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1676_13_precondition3_1.smt2 |   20.009s | 26.48MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1601_36_loop_invariant_init2_1.smt2 |   20.009s | 22.696MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_622_28_mlkem.adb_866_7_division_check_1.smt2 |   20.009s | 27.904MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_463_14_loop_invariant_preserv2_1.smt2 |   20.009s | 31.64MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_973_56_range_check_1.smt2 |   20.009s | 26.972MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1601_36_loop_invariant_preserv3_1.smt2 |   20.009s | 22.86MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1796_36_range_check2_1.smt2 |   20.009s | 22.64MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_91_27_overflow_check_1.smt2 |   20.009s | 23.624MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_2058_27_index_check3_1.smt2 |   20.009s | 21.828MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1656_22_index_check_1.smt2 |   20.009s | 27.48MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_463_56_index_check_1.smt2 |   20.009s | 28.512MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1892_22_assert_1.smt2 |   20.009s | 32.052MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1528_36_loop_invariant_preserv_1.smt2 |   20.009s | 23.304MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1896_33_loop_invariant_init_1.smt2 |   20.009s | 31.808MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1796_36_loop_invariant_preserv2_1.smt2 |   20.009s | 22.64MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_171_65_division_check_1.smt2 |   20.009s | 23.636MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1602_36_loop_invariant_init_1.smt2 |   20.009s | 26.348MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1601_46_overflow_check4_1.smt2 |   20.009s | 22.844MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_218_72_range_check_1.smt2 |   20.009s | 23.628MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_206_25_assert_1.smt2 |   20.009s | 23.612MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_2051_16_loop_invariant_init2_1.smt2 |   20.009s | 21.796MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_2057_46_index_check2_1.smt2 |   20.009s | 21.828MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1674_36_loop_invariant_init2_1.smt2 |   20.009s | 26.484MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_194_70_range_check_1.smt2 |   20.009s | 23.44MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1605_20_range_check_1.smt2 |   20.009s | 26.548MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_184_25_assert_1.smt2 |   20.009s | 23.436MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.ads_173_25_postcondition_1.smt2 |   20.009s | 31.816MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Prime.scala-2.smt2-1.smt2 |   20.009s | 42.472MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_218_61_range_check_1.smt2 |   20.010s | 23.636MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_828_22_assert_1.smt2 |   20.010s | 23.64MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1673_36_loop_invariant_init2_1.smt2 |   20.010s | 26.504MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_2057_46_index_check_1.smt2 |   20.010s | 21.708MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_463_56_index_check2_1.smt2 |   20.010s | 28.42MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_463_14_loop_invariant_preserv_1.smt2 |   20.010s | 28.552MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_87_25_assert_1.smt2 |   20.010s | 23.504MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_2052_27_range_check3_1.smt2 |   20.010s | 21.72MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_211_25_assert_1.smt2 |   20.010s | 23.468MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_187_95_division_check_1.smt2 |   20.010s | 23.632MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1584_20_index_check_1.smt2 |   20.010s | 27.48MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_96_25_assert_1.smt2 |   20.010s | 23.616MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_463_107_index_check2_1.smt2 |   20.010s | 28.548MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_463_22_range_check2_1.smt2 |   20.010s | 28.44MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1836_33_loop_invariant_preserv_1.smt2 |   20.010s | 31.712MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1655_20_index_check_1.smt2 |   20.010s | 27.512MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1688_22_assert_1.smt2 |   20.010s | 26.56MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1052_36_loop_invariant_preserv_1.smt2 |   20.010s | 22.756MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_219_39_range_check_1.smt2 |   20.010s | 23.628MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_273_20_range_check_1.smt2 |   20.010s | 31.636MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_463_80_initialization_1.smt2 |   20.010s | 28.548MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1802_33_loop_invariant_init_1.smt2 |   20.010s | 22.708MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1678_20_range_check2_1.smt2 |   20.010s | 26.34MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_830_20_range_check_1.smt2 |   20.010s | 23.632MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_2054_46_index_check_1.smt2 |   20.010s | 21.828MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1802_33_range_check2_1.smt2 |   20.010s | 22.584MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1485_36_loop_invariant_preserv_1.smt2 |   20.010s | 23.336MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_622_55_mlkem.adb_880_7_division_check_1.smt2 |   20.010s | 27.9MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1669_20_predicate_check_1.smt2 |   20.010s | 28.504MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_2056_27_range_check_1.smt2 |   20.010s | 21.596MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1471_36_loop_invariant_preserv_1.smt2 |   20.010s | 23.384MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1603_13_precondition3_1.smt2 |   20.010s | 26.3MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_2051_16_loop_invariant_preserv3_1.smt2 |   20.010s | 21.808MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1601_39_overflow_check3_1.smt2 |   20.010s | 22.852MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1913_17_length_check_1.smt2 |   20.010s | 28.472MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_96_56_division_check_1.smt2 |   20.010s | 23.62MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_2051_16_loop_invariant_preserv2_1.smt2 |   20.010s | 21.82MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_2054_27_index_check2_1.smt2 |   20.010s | 21.832MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1673_42_overflow_check4_1.smt2 |   20.010s | 26.268MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1674_36_loop_invariant_preserv_1.smt2 |   20.010s | 26.236MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_2053_46_index_check_1.smt2 |   20.010s | 21.584MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_200_76_overflow_check_1.smt2 |   20.011s | 23.576MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.ads_157_66_division_check_1.smt2 |   20.011s | 23.436MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1602_51_overflow_check3_1.smt2 |   20.011s | 22.884MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_801_22_assert_1.smt2 |   20.011s | 34.816MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1836_33_loop_invariant_init_1.smt2 |   20.011s | 31.636MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1673_38_overflow_check3_1.smt2 |   20.011s | 26.48MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_206_70_overflow_check_1.smt2 |   20.011s | 23.612MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_210_25_assert_1.smt2 |   20.011s | 23.4MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.ads_173_44_division_check_1.smt2 |   20.011s | 32.16MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1603_13_precondition4_1.smt2 |   20.011s | 26.152MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1602_36_loop_invariant_preserv2_1.smt2 |   20.011s | 22.86MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_2057_27_index_check2_1.smt2 |   20.011s | 21.792MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_798_14_division_check_1.smt2 |   20.011s | 34.548MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1583_39_index_check_1.smt2 |   20.011s | 27.272MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_272_28_range_check_1.smt2 |   20.011s | 32.212MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_155_30_division_check_1.smt2 |   20.011s | 23.536MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1601_46_overflow_check3_1.smt2 |   20.011s | 22.884MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1802_33_loop_invariant_preserv_1.smt2 |   20.011s | 22.704MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_968_56_range_check_1.smt2 |   20.011s | 27.14MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1076_24_range_check_1.smt2 |   20.011s | 21.956MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Prime.scala-1.smt2 |   20.011s | 60.3MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Prime.scala-2.smt2-3.smt2 |   20.011s | 47.992MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_217_25_assert_1.smt2 |   20.012s | 23.604MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_997_10_assert_1.smt2 |   20.012s | 34.1MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_2054_46_index_check2_1.smt2 |   20.012s | 21.828MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1600_36_loop_invariant_init2_1.smt2 |   20.012s | 22.88MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_466_14_initialization_1.smt2 |   20.012s | 28.54MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_454_19_postcondition_1.smt2 |   20.012s | 25.368MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_966_56_range_check_1.smt2 |   20.012s | 27.04MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_622_55_mlkem.adb_906_7_division_check_1.smt2 |   20.012s | 27.86MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1913_17_range_check_1.smt2 |   20.012s | 26.8MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1052_36_loop_invariant_init_1.smt2 |   20.012s | 22.8MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_737_14_division_check_1.smt2 |   20.012s | 31.884MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1673_36_loop_invariant_preserv_1.smt2 |   20.012s | 26.2MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1597_20_predicate_check_1.smt2 |   20.012s | 28.564MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_272_25_assert_1.smt2 |   20.012s | 32.032MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_463_14_loop_invariant_init_1.smt2 |   20.012s | 28.476MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1856_34_range_check_1.smt2 |   20.012s | 22.832MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1676_13_precondition2_1.smt2 |   20.012s | 26.504MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Prime.scala-2.smt2-2.smt2 |   20.012s | 37.832MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1676_13_precondition4_1.smt2 |   20.013s | 26.392MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1673_42_overflow_check3_1.smt2 |   20.013s | 26.504MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1602_51_overflow_check2_1.smt2 |   20.013s | 26.444MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1673_42_overflow_check2_1.smt2 |   20.013s | 26.48MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Prime.scala-2.smt2 |   20.013s | 52.108MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_116_56_division_check_1.smt2 |   20.014s | 23.648MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1677_43_range_check_1.smt2 |   20.014s | 26.136MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_622_28_mlkem.adb_906_7_division_check_1.smt2 |   20.014s | 27.872MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_2057_27_index_check_1.smt2 |   20.014s | 21.792MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_174_25_assert_1.smt2 |   20.014s | 23.432MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1674_36_loop_invariant_preserv2_1.smt2 |   20.014s | 26.336MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1856_34_length_check_1.smt2 |   20.014s | 27.808MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1543_20_range_check_1.smt2 |   20.015s | 23.32MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1074_36_loop_invariant_preserv_1.smt2 |   20.015s | 22.12MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1807_22_range_check_1.smt2 |   20.015s | 22.664MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_463_83_index_check_1.smt2 |   20.016s | 28.772MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1600_36_loop_invariant_preserv_1.smt2 |   20.016s | 26.276MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.ads_162_66_division_check_1.smt2 |   20.016s | 23.62MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1603_13_precondition2_1.smt2 |   20.016s | 22.696MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_181_69_division_check_1.smt2 |   20.016s | 23.632MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1054_24_range_check_1.smt2 |   20.017s | 22.776MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_213_25_assert_1.smt2 |   20.017s | 23.516MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1610_25_assert_1.smt2 |   20.017s | 22.82MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_976_57_range_check_1.smt2 |   20.017s | 26.916MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1684_33_loop_invariant_init_1.smt2 |   20.017s | 26.248MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1896_33_loop_invariant_preserv_1.smt2 |   20.017s | 31.648MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1901_22_assert_1.smt2 |   20.019s | 31.716MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_219_28_range_check_1.smt2 |   20.020s | 23.636MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_992_13_loop_invariant_preserv_1.smt2 |   20.020s | 41.652MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1604_43_range_check_1.smt2 |   20.021s | 26.508MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_2051_16_loop_invariant_init_1.smt2 |   20.022s | 21.716MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_2053_27_index_check2_1.smt2 |   20.023s | 21.792MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1584_39_index_check_1.smt2 |   20.023s | 27.548MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1684_33_loop_invariant_preserv_1.smt2 |   20.023s | 26.26MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_194_25_assert_1.smt2 |   20.024s | 23.544MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_218_72_division_check_1.smt2 |   20.024s | 23.644MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1486_20_range_check_1.smt2 |   20.025s | 23.344MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_2039_26_contract_case_1.smt2 |   20.025s | 23.836MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_2057_27_index_check3_1.smt2 |   20.025s | 21.796MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_2056_27_range_check2_1.smt2 |   20.025s | 21.82MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1796_36_loop_invariant_init_1.smt2 |   20.025s | 22.572MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1599_14_range_check2_1.smt2 |   20.026s | 22.888MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1676_13_precondition_1.smt2 |   20.027s | 26.192MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1583_22_overflow_check_1.smt2 |   20.028s | 27.392MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_118_20_range_check_1.smt2 |   20.028s | 23.632MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_802_20_range_check_1.smt2 |   20.029s | 35.06MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_707_19_range_check_1.smt2 |   20.030s | 26.948MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_974_56_range_check_1.smt2 |   20.030s | 27.144MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1673_38_overflow_check2_1.smt2 |   20.030s | 26.368MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1796_36_range_check3_1.smt2 |   20.031s | 22.576MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_738_19_range_check_1.smt2 |   20.031s | 31.74MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1074_36_loop_invariant_init_1.smt2 |   20.033s | 21.988MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_975_57_range_check_1.smt2 |   20.033s | 26.92MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_706_14_division_check_1.smt2 |   20.034s | 26.856MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1617_22_assert_1.smt2 |   20.036s | 26.592MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_965_39_range_check_1.smt2 |   20.053s | 27.008MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1600_36_loop_invariant_init_1.smt2 |   20.218s | 3001.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1672_36_loop_invariant_init_1.smt2 |   20.241s | 3155.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1582_48_index_check_1.smt2 |   20.311s | 4352.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTNIA/20240618-LibMLKEM/mlkem.adb_1582_48_overflow_check_1.smt2 |   20.346s | 4353.0MiB| timeout | 0 |  |  |
