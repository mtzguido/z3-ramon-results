# .

* SAT 131
* UNSAT 250
* TIMEOUT 1131
* UNKNOWN 11

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/AUFBV.tar.zst?download=1 | Source list: quantifier_benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-AUFBV.tar.zst-down
Runner: rise-runner-1
Z3 repo: Z3Prover/z3
Z3 commit: c3f5365a95a7eac2419a2f95ff240909f275cc08
Z3 branch: c3f5365a95a7eac2419a2f95ff240909f275cc08
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/AUFBV.tar.zst?download=1
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
|non-incremental/AUFBV/20210301-Alive2/ph7/504_ph7.smt2       |    0.031s | 21.888MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/771_sqlite3.smt2 |    0.031s | 21.416MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/967_sqlite3.smt2 |    0.038s | 22.316MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/291_gcc.smt2 |    0.039s | 22.544MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/681_ph7.smt2       |    0.043s | 20.848MiB| unknown | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/109_gcc.smt2 |    0.048s | 22.092MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gzip/273_gzip.smt2     |    0.051s | 22.148MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/078_gcc.smt2 |    0.053s | 21.252MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/102_gcc.smt2       |    0.056s | 21.864MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/273_gcc.smt2 |    0.057s | 21.068MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/433_oggenc.smt2 |    0.062s | 23.312MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/913_sqlite3.smt2 |    0.062s | 23.108MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/190_gcc.smt2 |    0.066s | 22.776MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/836_sqlite3.smt2 |    0.066s | 21.256MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/068_gcc.smt2       |    0.068s | 22.436MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/284_gcc.smt2 |    0.069s | 22.084MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/227_gcc.smt2       |    0.070s | 24.588MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/936_sqlite3.smt2 |    0.070s | 23.908MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/960_sqlite3.smt2 |    0.072s | 27.904MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/317_oggenc.smt2 |    0.073s | 23.892MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/550_ph7.smt2 |    0.074s | 21.572MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/517_ph7.smt2 |    0.074s | 25.144MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/725_ph7.smt2       |    0.082s | 23.876MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/616_ph7.smt2 |    0.082s | 27.204MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/543_ph7.smt2       |    0.085s | 22.7MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/oggenc/382_oggenc.smt2 |    0.087s | 23.112MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/420_oggenc.smt2 |    0.090s | 24.084MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/bzip2/022_bzip2.smt2 |    0.090s | 23.884MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/280_oggenc.smt2 |    0.091s | 24.776MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/oggenc/389_oggenc.smt2 |    0.092s | 22.808MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/341_oggenc.smt2 |    0.093s | 22.62MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/548_ph7.smt2       |    0.095s | 27.256MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/400_oggenc.smt2 |    0.098s | 27.732MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/549_ph7.smt2       |    0.106s | 30.336MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/851_sqlite3.smt2 |    0.107s | 27.34MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/620_ph7.smt2       |    0.108s | 26.076MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/832_sqlite3.smt2 |    0.117s | 27.052MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/855_sqlite3.smt2 |    0.122s | 24.332MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/419_oggenc.smt2 |    0.125s | 28.792MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gzip/251_gzip.smt2     |    0.126s | 25.628MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/320_oggenc.smt2 |    0.132s | 25.764MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/308_oggenc.smt2 |    0.138s | 25.564MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/757_ph7.smt2 |    0.154s | 32.184MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/883_sqlite3.smt2 |    0.157s | 40.756MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/747_ph7.smt2       |    0.161s | 23.408MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/170_gcc.smt2       |    0.164s | 34.98MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/024_gcc.smt2       |    0.169s | 26.652MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/437_oggenc.smt2 |    0.169s | 28.216MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/657_ph7.smt2       |    0.170s | 29.16MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/444_oggenc.smt2 |    0.171s | 29.412MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/472_ph7.smt2 |    0.175s | 30.884MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/942_sqlite3.smt2 |    0.182s | 23.368MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/999_sqlite3.smt2 |    0.187s | 24.744MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/811_sqlite3.smt2 |    0.194s | 27.244MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/197_gcc.smt2 |    0.195s | 28.196MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/199_gcc.smt2       |    0.205s | 23.74MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/691_ph7.smt2       |    0.211s | 26.836MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/523_ph7.smt2       |    0.215s | 35.536MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/206_gcc.smt2       |    0.215s | 25.736MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/686_ph7.smt2       |    0.225s | 31.536MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/120_gcc.smt2       |    0.225s | 35.58MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/559_ph7.smt2 |    0.225s | 39.816MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/658_ph7.smt2       |    0.240s | 24.336MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/372_oggenc.smt2 |    0.242s | 44.612MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/818_sqlite3.smt2 |    0.244s | 30.872MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/958_sqlite3.smt2 |    0.252s | 21.764MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/992_sqlite3.smt2 |    0.256s | 28.076MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/366_oggenc.smt2 |    0.260s | 32.26MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/839_sqlite3.smt2 |    0.269s | 27.472MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/105_gcc.smt2       |    0.279s | 26.892MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/989_sqlite3.smt2 |    0.279s | 23.768MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/045_gcc.smt2       |    0.280s | 30.568MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/349_oggenc.smt2 |    0.283s | 27.876MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/oggenc/376_oggenc.smt2 |    0.288s | 29.316MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/062_gcc.smt2       |    0.292s | 27.508MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/462_ph7.smt2       |    0.294s | 40.552MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/440_oggenc.smt2 |    0.300s | 45.2MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gzip/320_gzip.smt2 |    0.303s | 25.928MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/983_sqlite3.smt2 |    0.304s | 33.508MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/436_oggenc.smt2 |    0.309s | 54.148MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/915_sqlite3.smt2 |    0.309s | 34.812MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/519_ph7.smt2       |    0.311s | 26.26MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/998_sqlite3.smt2 |    0.312s | 21.964MiB| unknown | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/302_oggenc.smt2 |    0.328s | 30.248MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/723_ph7.smt2       |    0.330s | 26.152MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/474_ph7.smt2       |    0.332s | 25.996MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/722_ph7.smt2       |    0.332s | 31.656MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/215_gcc.smt2       |    0.332s | 34.068MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/781_sqlite3.smt2 |    0.335s | 64.792MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/695_ph7.smt2       |    0.337s | 26.828MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/027_gcc.smt2       |    0.337s | 30.732MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/552_ph7.smt2 |    0.340s | 91.34MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/700_ph7.smt2       |    0.342s | 39.136MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/534_ph7.smt2       |    0.353s | 52.932MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/938_sqlite3.smt2 |    0.362s | 32.732MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/429_ph7.smt2 |    0.369s | 22.736MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/513_ph7.smt2       |    0.372s | 26.8MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/756_ph7.smt2       |    0.375s | 31.72MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/137_gcc.smt2 |    0.380s | 29.252MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/923_sqlite3.smt2 |    0.381s | 27.384MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/451_oggenc.smt2 |    0.382s | 24.916MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/139_gcc.smt2 |    0.383s | 33.848MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/bzip2/033_bzip2.smt2 |    0.391s | 45.68MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/853_sqlite3.smt2 |    0.401s | 40.308MiB| unknown | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/896_sqlite3.smt2 |    0.401s | 27.112MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/907_sqlite3.smt2 |    0.403s | 27.512MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/764_ph7.smt2       |    0.408s | 49.64MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/719_ph7.smt2 |    0.409s | 28.528MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/467_ph7.smt2 |    0.417s | 29.184MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/872_sqlite3.smt2 |    0.418s | 31.452MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/460_oggenc.smt2 |    0.419s | 40.048MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/541_ph7.smt2 |    0.419s | 31.572MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/bzip2/013_bzip2.smt2   |    0.431s | 41.52MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/859_sqlite3.smt2 |    0.432s | 28.336MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/406_oggenc.smt2 |    0.435s | 30.888MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/198_gcc.smt2 |    0.449s | 35.108MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/644_ph7.smt2       |    0.452s | 30.892MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/353_oggenc.smt2 |    0.456s | 30.436MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/043_gcc.smt2       |    0.458s | 29.108MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/631_ph7.smt2       |    0.469s | 55.724MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/842_sqlite3.smt2 |    0.473s | 30.524MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/572_ph7.smt2 |    0.474s | 53.056MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/121_gcc.smt2 |    0.480s | 26.516MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/945_sqlite3.smt2 |    0.483s | 30.592MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/126_gcc.smt2       |    0.485s | 36.124MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/448_oggenc.smt2 |    0.495s | 44.828MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/156_gcc.smt2       |    0.528s | 33.032MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/203_gcc.smt2       |    0.529s | 42.104MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/563_ph7.smt2       |    0.534s | 37.732MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/647_ph7.smt2 |    0.538s | 35.82MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/734_ph7.smt2 |    0.543s | 46.824MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/702_ph7.smt2       |    0.545s | 28.768MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/612_ph7.smt2 |    0.550s | 23.156MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/514_ph7.smt2       |    0.552s | 58.124MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/432_oggenc.smt2 |    0.554s | 49.484MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/676_ph7.smt2 |    0.575s | 28.18MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gzip/249_gzip.smt2     |    0.578s | 39.448MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/698_ph7.smt2 |    0.591s | 26.424MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/239_gcc.smt2       |    0.594s | 36.848MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/900_sqlite3.smt2 |    0.609s | 30.696MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/735_ph7.smt2       |    0.628s | 57.004MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/706_ph7.smt2 |    0.633s | 30.88MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/715_ph7.smt2       |    0.637s | 39.344MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/675_ph7.smt2       |    0.641s | 46.992MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/578_ph7.smt2       |    0.641s | 43.684MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/673_ph7.smt2       |    0.648s | 44.204MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/211_gcc.smt2 |    0.654s | 47.264MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/654_ph7.smt2 |    0.660s | 55.256MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/683_ph7.smt2       |    0.673s | 47.36MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/600_ph7.smt2       |    0.681s | 26.912MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/226_gcc.smt2 |    0.685s | 44.608MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/803_sqlite3.smt2 |    0.687s | 33.616MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/606_ph7.smt2       |    0.697s | 39.052MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/151_gcc.smt2       |    0.697s | 34.668MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/592_ph7.smt2       |    0.703s | 37.5MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/088_gcc.smt2 |    0.718s | 75.876MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/596_ph7.smt2       |    0.719s | 33.252MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/253_gcc.smt2 |    0.728s | 83.176MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/073_gcc.smt2 |    0.738s | 32.944MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/186_gcc.smt2 |    0.739s | 23.492MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/429_oggenc.smt2 |    0.755s | 35.912MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/712_ph7.smt2       |    0.756s | 39.52MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/553_ph7.smt2 |    0.757s | 40.408MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/576_ph7.smt2       |    0.789s | 27.964MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/954_sqlite3.smt2 |    0.858s | 55.208MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/064_gcc.smt2       |    0.870s | 31.5MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/561_ph7.smt2       |    0.874s | 49.844MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/048_gcc.smt2       |    0.885s | 27.22MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/bzip2/018_bzip2.smt2   |    0.887s | 34.56MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/402_oggenc.smt2 |    0.895s | 41.048MiB| unknown | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/691_ph7.smt2 |    0.910s | 62.66MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/240_gcc.smt2 |    0.939s | 28.644MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/817_sqlite3.smt2 |    0.961s | 45.56MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/655_ph7.smt2       |    0.968s | 23.984MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/176_gcc.smt2       |    0.968s | 28.128MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/671_ph7.smt2       |    0.978s | 38.256MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/683_ph7.smt2 |    0.996s | 43.524MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/920_sqlite3.smt2 |    1.029s | 28.16MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/367_oggenc.smt2 |    1.040s | 28.516MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/277_gcc.smt2 |    1.041s | 70.964MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/105_gcc.smt2 |    1.042s | 65.592MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/473_ph7.smt2       |    1.063s | 24.804MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/645_ph7.smt2       |    1.069s | 27.164MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/112_gcc.smt2       |    1.082s | 37.232MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/829_sqlite3.smt2 |    1.101s | 33.828MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/780_ph7.smt2       |    1.122s | 40.944MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/675_ph7.smt2 |    1.127s | 34.416MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/769_sqlite3.smt2 |    1.131s | 25.932MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/715_ph7.smt2 |    1.159s | 51.072MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/oggenc/375_oggenc.smt2 |    1.170s | 64.304MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/621_ph7.smt2 |    1.174s | 47.616MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/565_ph7.smt2 |    1.181s | 64.92MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/375_oggenc.smt2 |    1.196s | 88.064MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/490_ph7.smt2       |    1.202s | 61.368MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/397_ph7.smt2 |    1.223s | 94.852MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/699_ph7.smt2 |    1.227s | 28.248MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/791_sqlite3.smt2 |    1.242s | 190.0MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/449_ph7.smt2 |    1.271s | 56.48MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/150_gcc.smt2 |    1.309s | 31.372MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/096_gcc.smt2       |    1.315s | 28.612MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/527_ph7.smt2       |    1.317s | 26.436MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/233_gcc.smt2 |    1.331s | 189.0MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/471_ph7.smt2       |    1.332s | 43.64MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/256_gcc.smt2 |    1.347s | 194.0MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/786_sqlite3.smt2 |    1.384s | 39.82MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/bzip2/022_bzip2.smt2   |    1.405s | 36.952MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/075_gcc.smt2       |    1.412s | 31.224MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/137_gcc.smt2       |    1.428s | 25.092MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/626_ph7.smt2       |    1.435s | 44.692MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/157_gcc.smt2       |    1.450s | 31.576MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/984_sqlite3.smt2 |    1.471s | 27.988MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/792_sqlite3.smt2 |    1.471s | 25.496MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/330_oggenc.smt2 |    1.487s | 121.0MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/800_sqlite3.smt2 |    1.495s | 31.632MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/139_gcc.smt2       |    1.550s | 30.104MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/646_ph7.smt2       |    1.570s | 32.228MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/964_sqlite3.smt2 |    1.583s | 24.7MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/502_ph7.smt2       |    1.589s | 33.928MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/894_sqlite3.smt2 |    1.599s | 26.668MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/588_ph7.smt2       |    1.600s | 41.16MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/855_sqlite3.smt2 |    1.614s | 24.828MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/853_sqlite3.smt2 |    1.630s | 35.128MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/831_sqlite3.smt2 |    1.643s | 33.088MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/766_sqlite3.smt2 |    1.656s | 93.3MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/389_oggenc.smt2 |    1.676s | 35.9MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/241_gcc.smt2 |    1.677s | 109.0MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/335_oggenc.smt2 |    1.700s | 41.556MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/898_sqlite3.smt2 |    1.712s | 34.172MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/502_ph7.smt2 |    1.714s | 41.364MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/972_sqlite3.smt2 |    1.797s | 31.236MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/751_ph7.smt2 |    1.815s | 41.36MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/348_oggenc.smt2 |    1.885s | 476.0MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/911_sqlite3.smt2 |    1.891s | 35.612MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/866_sqlite3.smt2 |    1.914s | 73.896MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/bzip2/020_bzip2.smt2   |    1.946s | 29.692MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/589_ph7.smt2       |    1.980s | 99.0MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gzip/245_gzip.smt2     |    1.980s | 33.68MiB| unknown | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/874_sqlite3.smt2 |    2.051s | 93.36MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/229_gcc.smt2       |    2.067s | 36.148MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gzip/319_gzip.smt2 |    2.146s | 51.144MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/847_sqlite3.smt2 |    2.211s | 95.56MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/843_sqlite3.smt2 |    2.216s | 43.716MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/990_sqlite3.smt2 |    2.232s | 79.08MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/812_sqlite3.smt2 |    2.246s | 31.66MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/637_ph7.smt2       |    2.290s | 33.148MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/635_ph7.smt2 |    2.299s | 49.744MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/540_ph7.smt2       |    2.314s | 70.14MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/232_gcc.smt2 |    2.342s | 74.988MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/751_ph7.smt2       |    2.390s | 56.764MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/687_ph7.smt2       |    2.407s | 37.02MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/427_oggenc.smt2 |    2.409s | 45.06MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/185_gcc.smt2       |    2.513s | 33.96MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/206_gcc.smt2 |    2.515s | 32.744MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/852_sqlite3.smt2 |    2.585s | 484.0MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/734_ph7.smt2       |    2.611s | 57.488MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/685_ph7.smt2       |    2.648s | 53.4MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/639_ph7.smt2       |    2.686s | 55.72MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/347_oggenc.smt2 |    2.721s | 30.44MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/167_gcc.smt2 |    2.738s | 92.288MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/816_sqlite3.smt2 |    2.782s | 46.916MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/716_ph7.smt2 |    2.783s | 34.044MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/985_sqlite3.smt2 |    2.829s | 41.888MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/597_ph7.smt2       |    2.835s | 58.924MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/141_gcc.smt2       |    2.856s | 188.0MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/205_gcc.smt2       |    2.870s | 86.608MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/819_sqlite3.smt2 |    2.914s | 44.544MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/647_ph7.smt2       |    2.926s | 61.204MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/736_ph7.smt2       |    2.932s | 34.272MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/413_ph7.smt2 |    2.946s | 39.1MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/247_gcc.smt2 |    3.007s | 207.0MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/961_sqlite3.smt2 |    3.071s | 109.0MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/601_ph7.smt2       |    3.086s | 55.584MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/168_gcc.smt2       |    3.116s | 35.152MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/931_sqlite3.smt2 |    3.125s | 64.148MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/881_sqlite3.smt2 |    3.211s | 30.272MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gzip/329_gzip.smt2 |    3.247s | 136.0MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/934_sqlite3.smt2 |    3.275s | 58.672MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/709_ph7.smt2       |    3.319s | 99.0MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/674_ph7.smt2       |    3.353s | 40.292MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/962_sqlite3.smt2 |    3.587s | 72.512MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/952_sqlite3.smt2 |    3.668s | 185.0MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/857_sqlite3.smt2 |    3.781s | 27.176MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/265_gcc.smt2 |    3.783s | 36.26MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/667_ph7.smt2       |    3.811s | 45.196MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/765_ph7.smt2       |    3.858s | 109.0MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/641_ph7.smt2       |    4.009s | 35.916MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/872_sqlite3.smt2 |    4.029s | 85.04MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/979_sqlite3.smt2 |    4.031s | 44.224MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/331_oggenc.smt2 |    4.149s | 399.0MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/184_gcc.smt2       |    4.203s | 74.736MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/172_gcc.smt2       |    4.221s | 170.0MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/177_gcc.smt2       |    4.279s | 36.064MiB| unknown | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/778_ph7.smt2       |    4.296s | 41.284MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/789_ph7.smt2       |    4.438s | 64.64MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/903_sqlite3.smt2 |    4.515s | 80.988MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/236_gcc.smt2       |    4.589s | 43.692MiB| unknown | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/516_ph7.smt2       |    4.803s | 38.388MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/bzip2/017_bzip2.smt2   |    4.940s | 33.308MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/039_gcc.smt2       |    5.100s | 39.32MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/813_sqlite3.smt2 |    5.125s | 91.648MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/098_gcc.smt2 |    5.130s | 45.352MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/426_ph7.smt2 |    5.226s | 147.0MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/104_gcc.smt2       |    5.367s | 74.328MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/091_gcc.smt2 |    5.585s | 193.0MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/500_ph7.smt2       |    5.646s | 50.732MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/925_sqlite3.smt2 |    5.686s | 82.968MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gzip/260_gzip.smt2     |    5.828s | 81.556MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/126_gcc.smt2 |    5.852s | 116.0MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/230_gcc.smt2       |    5.862s | 42.1MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/196_gcc.smt2 |    5.950s | 215.0MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/897_sqlite3.smt2 |    6.281s | 92.764MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/255_gcc.smt2 |    6.309s | 37.184MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/230_gcc.smt2 |    6.417s | 42.36MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/868_sqlite3.smt2 |    6.586s | 30.648MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/876_sqlite3.smt2 |    6.589s | 76.26MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/122_gcc.smt2       |    6.620s | 35.656MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/863_sqlite3.smt2 |    6.670s | 40.076MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/814_sqlite3.smt2 |    6.791s | 40.228MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/464_ph7.smt2       |    6.805s | 49.732MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/633_ph7.smt2       |    7.047s | 99.24MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/809_sqlite3.smt2 |    7.096s | 168.0MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/469_ph7.smt2       |    7.108s | 46.156MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/144_gcc.smt2       |    7.304s | 48.772MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/953_sqlite3.smt2 |    7.544s | 149.0MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/815_sqlite3.smt2 |    7.585s | 161.0MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/845_sqlite3.smt2 |    7.618s | 71.78MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/574_ph7.smt2       |    7.662s | 189.0MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/886_sqlite3.smt2 |    7.994s | 33.86MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/507_ph7.smt2 |    8.186s | 86.892MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/975_sqlite3.smt2 |    8.225s | 49.096MiB| unknown | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/735_ph7.smt2 |    8.264s | 188.0MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/628_ph7.smt2 |    8.300s | 37.124MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/969_sqlite3.smt2 |    8.472s | 42.992MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gzip/265_gzip.smt2     |    8.734s | 93.664MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/148_gcc.smt2 |    8.774s | 96.948MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/945_sqlite3.smt2 |    8.903s | 32.036MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/795_sqlite3.smt2 |    9.031s | 41.612MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gzip/325_gzip.smt2 |    9.316s | 351.0MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/591_ph7.smt2 |    9.488s | 98.0MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/991_sqlite3.smt2 |    9.554s | 46.632MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/522_ph7.smt2 |    9.738s | 126.0MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/bzip2/004_bzip2.smt2   |    9.822s | 82.372MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/990_sqlite3.smt2 |    9.950s | 201.0MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/882_sqlite3.smt2 |   10.087s | 40.964MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/980_sqlite3.smt2 |   10.197s | 462.0MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/307_oggenc.smt2 |   10.205s | 519.0MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/942_sqlite3.smt2 |   10.219s | 159.0MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/584_ph7.smt2       |   10.308s | 62.088MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/511_ph7.smt2       |   10.327s | 55.136MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/bzip2/002_bzip2.smt2   |   10.723s | 40.336MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/452_oggenc.smt2 |   10.955s | 49.688MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/166_gcc.smt2 |   11.088s | 37.492MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/939_sqlite3.smt2 |   11.123s | 43.244MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/130_gcc.smt2       |   11.127s | 164.0MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/729_ph7.smt2       |   11.178s | 88.892MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/119_gcc.smt2       |   11.251s | 92.292MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/640_ph7.smt2 |   11.788s | 137.0MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/291_oggenc.smt2 |   11.862s | 249.0MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/711_ph7.smt2 |   12.545s | 65.932MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/066_gcc.smt2 |   12.650s | 35.236MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/152_gcc.smt2       |   12.740s | 38.096MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/517_ph7.smt2       |   13.097s | 55.656MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/746_ph7.smt2       |   13.244s | 52.452MiB| unknown | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/776_ph7.smt2       |   13.384s | 79.036MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/oggenc/380_oggenc.smt2 |   13.767s | 120.0MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/235_gcc.smt2       |   13.903s | 46.648MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/175_gcc.smt2       |   14.078s | 88.052MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/321_oggenc.smt2 |   14.510s | 72.348MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/744_ph7.smt2       |   14.977s | 64.012MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/125_gcc.smt2       |   15.180s | 74.896MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/739_ph7.smt2       |   15.534s | 90.652MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/239_gcc.smt2 |   15.659s | 42.792MiB| unknown | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/456_ph7.smt2 |   15.814s | 72.928MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/949_sqlite3.smt2 |   15.897s | 56.672MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/694_ph7.smt2       |   15.899s | 54.008MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/292_gcc.smt2 |   16.229s | 514.0MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/813_sqlite3.smt2 |   16.321s | 199.0MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/038_gcc.smt2       |   16.631s | 43.088MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/bzip2/023_bzip2.smt2   |   16.702s | 73.444MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/326_oggenc.smt2 |   16.842s | 37.54MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/509_ph7.smt2       |   16.894s | 78.632MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/797_sqlite3.smt2 |   16.924s | 55.692MiB| unknown | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/164_gcc.smt2       |   17.826s | 45.044MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/980_sqlite3.smt2 |   18.528s | 45.776MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/698_ph7.smt2       |   18.571s | 134.0MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/577_ph7.smt2       |   18.839s | 86.048MiB| sat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/483_ph7.smt2       |   18.928s | 43.78MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/222_gcc.smt2       |   19.088s | 98.0MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/088_gcc.smt2       |   19.471s | 37.084MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/884_sqlite3.smt2 |   19.494s | 51.844MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/oggenc/341_oggenc.smt2 |   19.838s | 32.74MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gzip/246_gzip.smt2     |   19.853s | 156.0MiB| unsat | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/877_sqlite3.smt2 |   20.008s | 26.384MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/950_sqlite3.smt2 |   20.008s | 48.744MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gzip/326_gzip.smt2 |   20.008s | 42.948MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/840_sqlite3.smt2 |   20.009s | 35.62MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/575_ph7.smt2 |   20.009s | 40.604MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/652_ph7.smt2       |   20.010s | 60.796MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/831_sqlite3.smt2 |   20.010s | 57.804MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/664_ph7.smt2       |   20.011s | 48.936MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/947_sqlite3.smt2 |   20.011s | 71.484MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/837_sqlite3.smt2 |   20.011s | 57.016MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/889_sqlite3.smt2 |   20.011s | 52.796MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/523_ph7.smt2 |   20.011s | 54.312MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/701_ph7.smt2       |   20.012s | 57.62MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/766_ph7.smt2       |   20.012s | 71.964MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/076_gcc.smt2       |   20.012s | 52.728MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/999_sqlite3.smt2 |   20.012s | 65.888MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/833_sqlite3.smt2 |   20.012s | 70.136MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/890_sqlite3.smt2 |   20.012s | 43.724MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/117_gcc.smt2 |   20.012s | 52.1MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/717_ph7.smt2       |   20.013s | 65.632MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/599_ph7.smt2       |   20.013s | 53.012MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/072_gcc.smt2       |   20.013s | 53.032MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/136_gcc.smt2       |   20.013s | 78.784MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/913_sqlite3.smt2 |   20.013s | 55.652MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/916_sqlite3.smt2 |   20.013s | 68.504MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/867_sqlite3.smt2 |   20.013s | 55.244MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/818_sqlite3.smt2 |   20.013s | 97.192MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/916_sqlite3.smt2 |   20.013s | 52.168MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/841_sqlite3.smt2 |   20.013s | 63.936MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/867_sqlite3.smt2 |   20.013s | 75.364MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/522_ph7.smt2       |   20.014s | 88.356MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/782_ph7.smt2       |   20.014s | 54.6MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/111_gcc.smt2       |   20.014s | 72.152MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/865_sqlite3.smt2 |   20.014s | 88.252MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/183_gcc.smt2 |   20.014s | 90.58MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/911_sqlite3.smt2 |   20.014s | 67.4MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/984_sqlite3.smt2 |   20.014s | 77.176MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/651_ph7.smt2       |   20.015s | 62.236MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/587_ph7.smt2       |   20.015s | 89.8MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/775_ph7.smt2       |   20.015s | 65.776MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/470_ph7.smt2       |   20.015s | 119.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/792_ph7.smt2       |   20.015s | 79.208MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/194_gcc.smt2       |   20.015s | 91.512MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/069_gcc.smt2       |   20.015s | 80.6MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/051_gcc.smt2       |   20.015s | 108.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/835_sqlite3.smt2 |   20.015s | 48.54MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/978_sqlite3.smt2 |   20.015s | 86.244MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/836_sqlite3.smt2 |   20.015s | 76.256MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/817_sqlite3.smt2 |   20.015s | 110.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/982_sqlite3.smt2 |   20.015s | 84.128MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/384_oggenc.smt2 |   20.015s | 63.256MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/510_ph7.smt2 |   20.015s | 93.924MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/479_ph7.smt2 |   20.015s | 81.372MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/bzip2/031_bzip2.smt2 |   20.015s | 83.32MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/573_ph7.smt2       |   20.016s | 68.46MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/091_gcc.smt2       |   20.016s | 114.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/922_sqlite3.smt2 |   20.016s | 107.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/968_sqlite3.smt2 |   20.016s | 52.472MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/893_sqlite3.smt2 |   20.016s | 58.028MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/726_ph7.smt2 |   20.016s | 76.552MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/529_ph7.smt2 |   20.016s | 73.044MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/458_ph7.smt2 |   20.016s | 63.876MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gzip/334_gzip.smt2 |   20.016s | 92.512MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/295_gcc.smt2 |   20.016s | 99.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/142_gcc.smt2       |   20.017s | 92.888MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/796_sqlite3.smt2 |   20.017s | 56.024MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/887_sqlite3.smt2 |   20.017s | 59.868MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/657_ph7.smt2 |   20.017s | 127.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/403_ph7.smt2 |   20.017s | 77.184MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/092_gcc.smt2 |   20.017s | 81.252MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/770_sqlite3.smt2 |   20.017s | 131.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/679_ph7.smt2       |   20.018s | 117.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/727_ph7.smt2       |   20.018s | 108.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/491_ph7.smt2       |   20.018s | 81.684MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/087_gcc.smt2       |   20.018s | 122.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/995_sqlite3.smt2 |   20.018s | 114.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/971_sqlite3.smt2 |   20.018s | 76.724MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/662_ph7.smt2 |   20.018s | 54.976MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/742_ph7.smt2       |   20.019s | 169.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/714_ph7.smt2       |   20.019s | 152.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/067_gcc.smt2       |   20.019s | 107.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/217_gcc.smt2       |   20.019s | 98.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/202_gcc.smt2       |   20.019s | 137.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/053_gcc.smt2       |   20.019s | 91.864MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/849_sqlite3.smt2 |   20.019s | 102.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/454_oggenc.smt2 |   20.019s | 144.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gzip/323_gzip.smt2 |   20.019s | 61.968MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/315_gcc.smt2 |   20.019s | 51.296MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/954_sqlite3.smt2 |   20.019s | 81.704MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/810_sqlite3.smt2 |   20.020s | 117.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/739_ph7.smt2 |   20.020s | 138.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/100_gcc.smt2 |   20.020s | 82.424MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/764_sqlite3.smt2 |   20.020s | 130.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/845_sqlite3.smt2 |   20.020s | 104.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/696_ph7.smt2       |   20.021s | 129.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/564_ph7.smt2       |   20.021s | 112.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/864_sqlite3.smt2 |   20.021s | 154.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/951_sqlite3.smt2 |   20.021s | 201.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/579_ph7.smt2 |   20.021s | 148.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/772_ph7.smt2       |   20.022s | 167.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/028_gcc.smt2       |   20.022s | 66.688MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/191_gcc.smt2       |   20.022s | 128.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/860_sqlite3.smt2 |   20.022s | 77.912MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/584_ph7.smt2 |   20.022s | 32.128MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/609_ph7.smt2 |   20.022s | 71.036MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/615_ph7.smt2 |   20.022s | 157.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/530_ph7.smt2 |   20.022s | 69.916MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/721_ph7.smt2       |   20.023s | 54.076MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/484_ph7.smt2       |   20.023s | 244.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/079_gcc.smt2       |   20.023s | 54.728MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/973_sqlite3.smt2 |   20.023s | 225.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/828_sqlite3.smt2 |   20.023s | 121.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/993_sqlite3.smt2 |   20.023s | 78.344MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/309_oggenc.smt2 |   20.023s | 70.424MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/545_ph7.smt2 |   20.023s | 94.668MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/bzip2/001_bzip2.smt2 |   20.023s | 38.94MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/298_gcc.smt2 |   20.023s | 152.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/135_gcc.smt2 |   20.023s | 31.732MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/966_sqlite3.smt2 |   20.023s | 113.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/521_ph7.smt2 |   20.024s | 200.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/bzip2/029_bzip2.smt2 |   20.024s | 165.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/279_gcc.smt2 |   20.024s | 102.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/062_gcc.smt2 |   20.024s | 44.852MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/745_ph7.smt2       |   20.025s | 189.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/760_ph7.smt2       |   20.025s | 91.076MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/465_ph7.smt2       |   20.025s | 91.34MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/155_gcc.smt2       |   20.025s | 161.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/212_gcc.smt2       |   20.025s | 59.72MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/498_ph7.smt2 |   20.025s | 57.732MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/287_gcc.smt2 |   20.025s | 33.404MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/848_sqlite3.smt2 |   20.025s | 83.316MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/542_ph7.smt2       |   20.026s | 51.264MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/097_gcc.smt2       |   20.026s | 232.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/895_sqlite3.smt2 |   20.026s | 119.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/577_ph7.smt2 |   20.026s | 30.1MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/768_ph7.smt2       |   20.027s | 67.344MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/481_ph7.smt2       |   20.027s | 98.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/769_ph7.smt2       |   20.027s | 162.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/680_ph7.smt2       |   20.027s | 51.132MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/163_gcc.smt2       |   20.027s | 120.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/873_sqlite3.smt2 |   20.027s | 172.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/820_sqlite3.smt2 |   20.027s | 188.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/313_oggenc.smt2 |   20.027s | 125.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/431_ph7.smt2 |   20.027s | 178.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/549_ph7.smt2 |   20.027s | 76.804MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/bzip2/034_bzip2.smt2 |   20.027s | 23.344MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/220_gcc.smt2 |   20.027s | 32.776MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/076_gcc.smt2 |   20.027s | 157.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/055_gcc.smt2 |   20.027s | 42.608MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/974_sqlite3.smt2 |   20.027s | 184.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/oggenc/342_oggenc.smt2 |   20.027s | 112.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/220_gcc.smt2       |   20.028s | 165.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/600_ph7.smt2 |   20.028s | 76.896MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/673_ph7.smt2 |   20.028s | 81.232MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/645_ph7.smt2 |   20.028s | 78.3MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/113_gcc.smt2 |   20.028s | 54.94MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/941_sqlite3.smt2 |   20.028s | 113.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/968_sqlite3.smt2 |   20.028s | 229.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/521_ph7.smt2       |   20.029s | 122.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/089_gcc.smt2       |   20.029s | 48.796MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/181_gcc.smt2       |   20.029s | 65.812MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/921_sqlite3.smt2 |   20.029s | 142.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/821_sqlite3.smt2 |   20.029s | 204.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/311_oggenc.smt2 |   20.029s | 47.7MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/538_ph7.smt2 |   20.029s | 83.432MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/544_ph7.smt2 |   20.029s | 77.364MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/bzip2/025_bzip2.smt2 |   20.029s | 133.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/231_gcc.smt2 |   20.029s | 72.788MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/283_gcc.smt2 |   20.029s | 129.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/122_gcc.smt2 |   20.029s | 73.716MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/140_gcc.smt2 |   20.029s | 141.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/852_sqlite3.smt2 |   20.029s | 71.896MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/937_sqlite3.smt2 |   20.029s | 84.208MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/890_sqlite3.smt2 |   20.029s | 173.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/oggenc/367_oggenc.smt2 |   20.029s | 36.432MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/oggenc/387_oggenc.smt2 |   20.029s | 28.588MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/767_ph7.smt2       |   20.030s | 86.696MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/779_ph7.smt2       |   20.030s | 79.996MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/bzip2/010_bzip2.smt2   |   20.030s | 93.36MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/241_gcc.smt2       |   20.030s | 87.392MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/095_gcc.smt2       |   20.030s | 139.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/143_gcc.smt2       |   20.030s | 47.644MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/153_gcc.smt2       |   20.030s | 86.62MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/171_gcc.smt2       |   20.030s | 67.816MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/442_oggenc.smt2 |   20.030s | 112.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/703_ph7.smt2 |   20.030s | 39.152MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/bzip2/032_bzip2.smt2 |   20.030s | 165.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/209_gcc.smt2 |   20.030s | 35.408MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/108_gcc.smt2 |   20.030s | 112.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/164_gcc.smt2 |   20.030s | 123.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/881_sqlite3.smt2 |   20.030s | 47.604MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/955_sqlite3.smt2 |   20.030s | 43.132MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/965_sqlite3.smt2 |   20.030s | 207.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/856_sqlite3.smt2 |   20.030s | 34.964MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/733_ph7.smt2       |   20.031s | 122.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/506_ph7.smt2       |   20.031s | 124.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/622_ph7.smt2       |   20.031s | 68.956MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/632_ph7.smt2       |   20.031s | 100.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gzip/275_gzip.smt2     |   20.031s | 138.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/bzip2/015_bzip2.smt2   |   20.031s | 48.868MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/085_gcc.smt2       |   20.031s | 59.408MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/078_gcc.smt2       |   20.031s | 246.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/827_sqlite3.smt2 |   20.031s | 61.22MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/955_sqlite3.smt2 |   20.031s | 92.904MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/839_sqlite3.smt2 |   20.031s | 56.084MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/365_oggenc.smt2 |   20.031s | 206.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/394_oggenc.smt2 |   20.031s | 231.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20231002-nysm/aes_ctr_loop_inductive_invariantLoopInductive.smt2 |   20.031s | 92.86MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/697_ph7.smt2 |   20.031s | 44.716MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/123_gcc.smt2 |   20.031s | 82.024MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/067_gcc.smt2 |   20.031s | 228.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/187_gcc.smt2 |   20.031s | 74.304MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/846_sqlite3.smt2 |   20.031s | 48.592MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/790_sqlite3.smt2 |   20.031s | 87.992MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/869_sqlite3.smt2 |   20.031s | 51.548MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/805_sqlite3.smt2 |   20.031s | 222.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/785_sqlite3.smt2 |   20.031s | 64.724MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/697_ph7.smt2       |   20.032s | 63.284MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/678_ph7.smt2       |   20.032s | 71.064MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/677_ph7.smt2       |   20.032s | 132.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/475_ph7.smt2       |   20.032s | 109.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/788_ph7.smt2       |   20.032s | 62.376MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/713_ph7.smt2       |   20.032s | 82.224MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/bzip2/011_bzip2.smt2   |   20.032s | 87.2MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/bzip2/019_bzip2.smt2   |   20.032s | 81.972MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/211_gcc.smt2       |   20.032s | 278.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/080_gcc.smt2       |   20.032s | 136.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/352_oggenc.smt2 |   20.032s | 72.872MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/554_ph7.smt2 |   20.032s | 250.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/509_ph7.smt2 |   20.032s | 72.78MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/696_ph7.smt2 |   20.032s | 82.2MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/527_ph7.smt2 |   20.032s | 73.116MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/627_ph7.smt2 |   20.032s | 275.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/623_ph7.smt2 |   20.032s | 119.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/644_ph7.smt2 |   20.032s | 85.728MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/461_ph7.smt2 |   20.032s | 43.824MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/bzip2/019_bzip2.smt2 |   20.032s | 148.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/074_gcc.smt2 |   20.032s | 85.06MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/120_gcc.smt2 |   20.032s | 136.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/171_gcc.smt2 |   20.032s | 44.692MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/819_sqlite3.smt2 |   20.032s | 111.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/976_sqlite3.smt2 |   20.032s | 69.436MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/879_sqlite3.smt2 |   20.032s | 76.9MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/654_ph7.smt2       |   20.033s | 112.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/488_ph7.smt2       |   20.033s | 56.816MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/560_ph7.smt2       |   20.033s | 65.264MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/787_ph7.smt2       |   20.033s | 139.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/501_ph7.smt2       |   20.033s | 80.136MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/759_ph7.smt2       |   20.033s | 73.572MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/116_gcc.smt2       |   20.033s | 85.12MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/946_sqlite3.smt2 |   20.033s | 59.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/351_oggenc.smt2 |   20.033s | 186.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/443_oggenc.smt2 |   20.033s | 76.08MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/423_oggenc.smt2 |   20.033s | 127.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/417_ph7.smt2 |   20.033s | 97.488MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/756_ph7.smt2 |   20.033s | 127.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/451_ph7.smt2 |   20.033s | 97.652MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/604_ph7.smt2 |   20.033s | 93.388MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gzip/330_gzip.smt2 |   20.033s | 45.124MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/bzip2/003_bzip2.smt2 |   20.033s | 52.888MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/312_gcc.smt2 |   20.033s | 93.92MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/227_gcc.smt2 |   20.033s | 102.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/146_gcc.smt2 |   20.033s | 124.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/259_gcc.smt2 |   20.033s | 148.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/174_gcc.smt2 |   20.033s | 33.456MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/060_gcc.smt2 |   20.033s | 87.352MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/280_gcc.smt2 |   20.033s | 81.9MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/788_sqlite3.smt2 |   20.033s | 168.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/849_sqlite3.smt2 |   20.033s | 106.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/933_sqlite3.smt2 |   20.033s | 143.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/oggenc/348_oggenc.smt2 |   20.033s | 83.7MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/771_ph7.smt2       |   20.034s | 106.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/529_ph7.smt2       |   20.034s | 42.532MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/518_ph7.smt2       |   20.034s | 49.064MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/634_ph7.smt2       |   20.034s | 329.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/665_ph7.smt2       |   20.034s | 63.804MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/783_ph7.smt2       |   20.034s | 58.592MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/059_gcc.smt2       |   20.034s | 82.976MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/854_sqlite3.smt2 |   20.034s | 463.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/601_ph7.smt2 |   20.034s | 51.164MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/487_ph7.smt2 |   20.034s | 78.244MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/590_ph7.smt2 |   20.034s | 78.564MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/513_ph7.smt2 |   20.034s | 81.164MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/448_ph7.smt2 |   20.034s | 49.704MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/260_gcc.smt2 |   20.034s | 210.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/189_gcc.smt2 |   20.034s | 89.804MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/303_gcc.smt2 |   20.034s | 86.308MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/286_gcc.smt2 |   20.034s | 92.088MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/086_gcc.smt2 |   20.034s | 136.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/132_gcc.smt2 |   20.034s | 81.588MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/163_gcc.smt2 |   20.034s | 136.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/761_sqlite3.smt2 |   20.034s | 94.544MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/607_ph7.smt2       |   20.035s | 135.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/618_ph7.smt2       |   20.035s | 91.868MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/550_ph7.smt2       |   20.035s | 77.704MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/590_ph7.smt2       |   20.035s | 76.828MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/532_ph7.smt2       |   20.035s | 91.376MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/127_gcc.smt2       |   20.035s | 39.612MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/832_sqlite3.smt2 |   20.035s | 343.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/822_sqlite3.smt2 |   20.035s | 254.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/943_sqlite3.smt2 |   20.035s | 92.04MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/880_sqlite3.smt2 |   20.035s | 100.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/927_sqlite3.smt2 |   20.035s | 86.364MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/382_oggenc.smt2 |   20.035s | 92.528MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/594_ph7.smt2 |   20.035s | 29.9MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/664_ph7.smt2 |   20.035s | 113.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/514_ph7.smt2 |   20.035s | 119.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/663_ph7.smt2 |   20.035s | 57.22MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/717_ph7.smt2 |   20.035s | 62.24MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/483_ph7.smt2 |   20.035s | 100.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/684_ph7.smt2 |   20.035s | 63.34MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/470_ph7.smt2 |   20.035s | 60.288MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/401_ph7.smt2 |   20.035s | 166.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/228_gcc.smt2 |   20.035s | 91.4MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/194_gcc.smt2 |   20.035s | 152.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/069_gcc.smt2 |   20.035s | 141.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/142_gcc.smt2 |   20.035s | 182.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/oggenc/363_oggenc.smt2 |   20.035s | 79.764MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/487_ph7.smt2       |   20.036s | 131.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/755_ph7.smt2       |   20.036s | 137.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/489_ph7.smt2       |   20.036s | 112.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/575_ph7.smt2       |   20.036s | 128.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/507_ph7.smt2       |   20.036s | 50.092MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/638_ph7.smt2       |   20.036s | 83.484MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/551_ph7.smt2       |   20.036s | 79.98MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/586_ph7.smt2       |   20.036s | 98.572MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/556_ph7.smt2       |   20.036s | 117.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/615_ph7.smt2       |   20.036s | 89.268MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/957_sqlite3.smt2 |   20.036s | 129.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/802_sqlite3.smt2 |   20.036s | 232.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/794_sqlite3.smt2 |   20.036s | 146.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/935_sqlite3.smt2 |   20.036s | 313.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/312_oggenc.smt2 |   20.036s | 145.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/441_ph7.smt2 |   20.036s | 84.444MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/588_ph7.smt2 |   20.036s | 264.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/506_ph7.smt2 |   20.036s | 99.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/528_ph7.smt2 |   20.036s | 82.084MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/089_gcc.smt2 |   20.036s | 158.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/083_gcc.smt2 |   20.036s | 312.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/861_sqlite3.smt2 |   20.036s | 129.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/957_sqlite3.smt2 |   20.036s | 70.78MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/874_sqlite3.smt2 |   20.036s | 75.62MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/807_sqlite3.smt2 |   20.036s | 215.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/906_sqlite3.smt2 |   20.036s | 46.056MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/oggenc/350_oggenc.smt2 |   20.036s | 42.232MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/oggenc/368_oggenc.smt2 |   20.036s | 78.268MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/763_ph7.smt2       |   20.037s | 120.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/720_ph7.smt2       |   20.037s | 49.044MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/668_ph7.smt2       |   20.037s | 275.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/748_ph7.smt2       |   20.037s | 93.776MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/724_ph7.smt2       |   20.037s | 139.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/558_ph7.smt2       |   20.037s | 83.192MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/536_ph7.smt2       |   20.037s | 140.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/624_ph7.smt2       |   20.037s | 53.224MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/bzip2/003_bzip2.smt2   |   20.037s | 49.792MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/bzip2/009_bzip2.smt2   |   20.037s | 57.592MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/093_gcc.smt2       |   20.037s | 61.12MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/036_gcc.smt2       |   20.037s | 100.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/135_gcc.smt2       |   20.037s | 105.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/041_gcc.smt2       |   20.037s | 99.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/361_oggenc.smt2 |   20.037s | 415.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/420_ph7.smt2 |   20.037s | 135.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/433_ph7.smt2 |   20.037s | 143.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/447_ph7.smt2 |   20.037s | 80.188MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/746_ph7.smt2 |   20.037s | 164.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/563_ph7.smt2 |   20.037s | 138.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/bzip2/013_bzip2.smt2 |   20.037s | 169.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/136_gcc.smt2 |   20.037s | 104.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/169_gcc.smt2 |   20.037s | 81.164MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/288_gcc.smt2 |   20.037s | 121.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/944_sqlite3.smt2 |   20.037s | 98.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/814_sqlite3.smt2 |   20.037s | 107.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/821_sqlite3.smt2 |   20.037s | 143.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/859_sqlite3.smt2 |   20.037s | 76.916MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/830_sqlite3.smt2 |   20.037s | 127.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/571_ph7.smt2       |   20.038s | 163.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/541_ph7.smt2       |   20.038s | 88.508MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/524_ph7.smt2       |   20.038s | 110.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/648_ph7.smt2       |   20.038s | 191.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/643_ph7.smt2       |   20.038s | 105.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/486_ph7.smt2       |   20.038s | 135.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/042_gcc.smt2       |   20.038s | 49.036MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/029_gcc.smt2       |   20.038s | 56.416MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/216_gcc.smt2       |   20.038s | 82.372MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/049_gcc.smt2       |   20.038s | 99.176MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/037_gcc.smt2       |   20.038s | 59.528MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/197_gcc.smt2       |   20.038s | 120.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/055_gcc.smt2       |   20.038s | 216.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/054_gcc.smt2       |   20.038s | 201.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/204_gcc.smt2       |   20.038s | 198.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/801_sqlite3.smt2 |   20.038s | 79.616MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/838_sqlite3.smt2 |   20.038s | 98.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/316_oggenc.smt2 |   20.038s | 93.656MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/629_ph7.smt2 |   20.038s | 173.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/537_ph7.smt2 |   20.038s | 99.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/564_ph7.smt2 |   20.038s | 165.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/582_ph7.smt2 |   20.038s | 73.7MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/264_gcc.smt2 |   20.038s | 68.92MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/153_gcc.smt2 |   20.038s | 94.848MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/165_gcc.smt2 |   20.038s | 87.408MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/068_gcc.smt2 |   20.038s | 106.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/994_sqlite3.smt2 |   20.038s | 141.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/538_ph7.smt2       |   20.039s | 103.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/476_ph7.smt2       |   20.039s | 89.436MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/738_ph7.smt2       |   20.039s | 189.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/493_ph7.smt2       |   20.039s | 79.796MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/114_gcc.smt2       |   20.039s | 97.98MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/044_gcc.smt2       |   20.039s | 113.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/195_gcc.smt2       |   20.039s | 174.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/084_gcc.smt2       |   20.039s | 132.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/065_gcc.smt2       |   20.039s | 100.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/165_gcc.smt2       |   20.039s | 44.296MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/869_sqlite3.smt2 |   20.039s | 106.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/879_sqlite3.smt2 |   20.039s | 156.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/909_sqlite3.smt2 |   20.039s | 137.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/886_sqlite3.smt2 |   20.039s | 64.132MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/745_ph7.smt2 |   20.039s | 117.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/689_ph7.smt2 |   20.039s | 223.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/740_ph7.smt2 |   20.039s | 73.12MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/603_ph7.smt2 |   20.039s | 194.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/680_ph7.smt2 |   20.039s | 248.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/158_gcc.smt2 |   20.039s | 120.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/118_gcc.smt2 |   20.039s | 73.676MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/885_sqlite3.smt2 |   20.039s | 123.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/905_sqlite3.smt2 |   20.039s | 114.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/921_sqlite3.smt2 |   20.039s | 163.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/oggenc/361_oggenc.smt2 |   20.039s | 257.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/oggenc/395_oggenc.smt2 |   20.039s | 148.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/554_ph7.smt2       |   20.040s | 97.76MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/731_ph7.smt2       |   20.040s | 119.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/552_ph7.smt2       |   20.040s | 67.836MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/785_ph7.smt2       |   20.040s | 85.604MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/732_ph7.smt2       |   20.040s | 146.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/719_ph7.smt2       |   20.040s | 105.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/650_ph7.smt2       |   20.040s | 82.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/477_ph7.smt2       |   20.040s | 162.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/178_gcc.smt2       |   20.040s | 53.46MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/100_gcc.smt2       |   20.040s | 66.9MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/098_gcc.smt2       |   20.040s | 127.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/930_sqlite3.smt2 |   20.040s | 91.532MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/798_sqlite3.smt2 |   20.040s | 311.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/413_oggenc.smt2 |   20.040s | 45.352MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/421_oggenc.smt2 |   20.040s | 84.008MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/482_ph7.smt2 |   20.040s | 150.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/526_ph7.smt2 |   20.040s | 55.692MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/bzip2/037_bzip2.smt2 |   20.040s | 184.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/134_gcc.smt2 |   20.040s | 159.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/147_gcc.smt2 |   20.040s | 198.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/258_gcc.smt2 |   20.040s | 213.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/822_sqlite3.smt2 |   20.040s | 82.004MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/914_sqlite3.smt2 |   20.040s | 160.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/823_sqlite3.smt2 |   20.040s | 143.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/778_sqlite3.smt2 |   20.040s | 175.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/768_sqlite3.smt2 |   20.040s | 126.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/oggenc/358_oggenc.smt2 |   20.040s | 37.544MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/466_ph7.smt2       |   20.041s | 100.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/693_ph7.smt2       |   20.041s | 399.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/614_ph7.smt2       |   20.041s | 79.848MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/672_ph7.smt2       |   20.041s | 141.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/547_ph7.smt2       |   20.041s | 152.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/682_ph7.smt2       |   20.041s | 118.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/bzip2/005_bzip2.smt2   |   20.041s | 51.184MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/826_sqlite3.smt2 |   20.041s | 234.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/914_sqlite3.smt2 |   20.041s | 181.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/632_ph7.smt2 |   20.041s | 83.996MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/471_ph7.smt2 |   20.041s | 140.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/438_ph7.smt2 |   20.041s | 392.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/050_gcc.smt2 |   20.041s | 141.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/203_gcc.smt2 |   20.041s | 112.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/276_gcc.smt2 |   20.041s | 155.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/262_gcc.smt2 |   20.041s | 154.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/119_gcc.smt2 |   20.041s | 235.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/922_sqlite3.smt2 |   20.041s | 122.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/909_sqlite3.smt2 |   20.041s | 163.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/767_sqlite3.smt2 |   20.041s | 151.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/537_ph7.smt2       |   20.042s | 75.456MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/758_ph7.smt2       |   20.042s | 103.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/479_ph7.smt2       |   20.042s | 49.844MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/562_ph7.smt2       |   20.042s | 93.708MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/718_ph7.smt2       |   20.042s | 148.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/705_ph7.smt2       |   20.042s | 196.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/598_ph7.smt2       |   20.042s | 185.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/219_gcc.smt2       |   20.042s | 178.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/207_gcc.smt2       |   20.042s | 195.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/154_gcc.smt2       |   20.042s | 62.828MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/885_sqlite3.smt2 |   20.042s | 93.648MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/944_sqlite3.smt2 |   20.042s | 163.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/858_sqlite3.smt2 |   20.042s | 392.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/929_sqlite3.smt2 |   20.042s | 165.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/969_sqlite3.smt2 |   20.042s | 137.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/359_oggenc.smt2 |   20.042s | 129.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/569_ph7.smt2 |   20.042s | 275.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/465_ph7.smt2 |   20.042s | 73.396MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/567_ph7.smt2 |   20.042s | 80.28MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/595_ph7.smt2 |   20.042s | 343.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/531_ph7.smt2 |   20.042s | 63.472MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/480_ph7.smt2 |   20.042s | 47.588MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/301_gcc.smt2 |   20.042s | 162.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/175_gcc.smt2 |   20.042s | 87.32MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/103_gcc.smt2 |   20.042s | 86.18MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/304_gcc.smt2 |   20.042s | 140.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/154_gcc.smt2 |   20.042s | 165.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/268_gcc.smt2 |   20.042s | 90.096MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/048_gcc.smt2 |   20.042s | 138.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/237_gcc.smt2 |   20.042s | 164.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/809_sqlite3.smt2 |   20.042s | 122.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/779_sqlite3.smt2 |   20.042s | 71.036MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/777_ph7.smt2       |   20.043s | 151.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/594_ph7.smt2       |   20.043s | 216.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/472_ph7.smt2       |   20.043s | 305.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/515_ph7.smt2       |   20.043s | 144.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/242_gcc.smt2       |   20.043s | 170.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/131_gcc.smt2       |   20.043s | 57.712MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/856_sqlite3.smt2 |   20.043s | 93.048MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/851_sqlite3.smt2 |   20.043s | 376.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/500_ph7.smt2 |   20.043s | 113.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/666_ph7.smt2 |   20.043s | 130.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/730_ph7.smt2 |   20.043s | 261.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/422_ph7.smt2 |   20.043s | 152.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/624_ph7.smt2 |   20.043s | 52.016MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/157_gcc.smt2 |   20.043s | 262.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/128_gcc.smt2 |   20.043s | 223.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/270_gcc.smt2 |   20.043s | 201.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/116_gcc.smt2 |   20.043s | 172.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/054_gcc.smt2 |   20.043s | 265.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/929_sqlite3.smt2 |   20.043s | 117.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/539_ph7.smt2       |   20.044s | 130.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/689_ph7.smt2       |   20.044s | 218.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/553_ph7.smt2       |   20.044s | 291.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/512_ph7.smt2       |   20.044s | 178.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/741_ph7.smt2       |   20.044s | 102.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/752_ph7.smt2       |   20.044s | 99.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/106_gcc.smt2       |   20.044s | 82.96MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/074_gcc.smt2       |   20.044s | 48.752MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/218_gcc.smt2       |   20.044s | 215.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/086_gcc.smt2       |   20.044s | 244.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/846_sqlite3.smt2 |   20.044s | 334.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/488_ph7.smt2 |   20.044s | 158.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/733_ph7.smt2 |   20.044s | 94.476MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/667_ph7.smt2 |   20.044s | 88.84MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/633_ph7.smt2 |   20.044s | 79.088MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/722_ph7.smt2 |   20.044s | 158.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/749_ph7.smt2 |   20.044s | 127.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/bzip2/006_bzip2.smt2 |   20.044s | 152.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/238_gcc.smt2 |   20.044s | 68.868MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/130_gcc.smt2 |   20.044s | 86.192MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/275_gcc.smt2 |   20.044s | 191.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/040_gcc.smt2 |   20.044s | 144.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/180_gcc.smt2 |   20.044s | 63.184MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/039_gcc.smt2 |   20.044s | 143.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/623_ph7.smt2       |   20.045s | 97.08MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/716_ph7.smt2       |   20.045s | 156.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/703_ph7.smt2       |   20.045s | 153.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/bzip2/007_bzip2.smt2   |   20.045s | 189.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/208_gcc.smt2       |   20.045s | 227.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/201_gcc.smt2       |   20.045s | 395.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/960_sqlite3.smt2 |   20.045s | 280.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/830_sqlite3.smt2 |   20.045s | 235.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/988_sqlite3.smt2 |   20.045s | 186.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/338_oggenc.smt2 |   20.045s | 255.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/738_ph7.smt2 |   20.045s | 124.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/435_ph7.smt2 |   20.045s | 71.216MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/884_sqlite3.smt2 |   20.045s | 518.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/950_sqlite3.smt2 |   20.045s | 304.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/786_ph7.smt2       |   20.046s | 144.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/478_ph7.smt2       |   20.046s | 180.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/492_ph7.smt2       |   20.046s | 286.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/660_ph7.smt2       |   20.046s | 219.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/770_ph7.smt2       |   20.046s | 66.416MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/804_sqlite3.smt2 |   20.046s | 260.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/399_oggenc.smt2 |   20.046s | 273.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/704_ph7.smt2 |   20.046s | 170.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/710_ph7.smt2 |   20.046s | 102.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/bzip2/016_bzip2.smt2 |   20.046s | 261.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/210_gcc.smt2 |   20.046s | 114.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/124_gcc.smt2 |   20.046s | 146.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/308_gcc.smt2 |   20.046s | 347.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/107_gcc.smt2 |   20.046s | 138.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/249_gcc.smt2 |   20.046s | 366.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/903_sqlite3.smt2 |   20.046s | 105.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/956_sqlite3.smt2 |   20.046s | 24.672MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/oggenc/356_oggenc.smt2 |   20.046s | 545.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/669_ph7.smt2       |   20.047s | 54.536MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/bzip2/021_bzip2.smt2   |   20.047s | 70.436MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/188_gcc.smt2       |   20.047s | 387.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/963_sqlite3.smt2 |   20.047s | 82.856MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/981_sqlite3.smt2 |   20.047s | 140.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/932_sqlite3.smt2 |   20.047s | 175.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/976_sqlite3.smt2 |   20.047s | 407.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/406_ph7.smt2 |   20.047s | 106.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/586_ph7.smt2 |   20.047s | 112.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/493_ph7.smt2 |   20.047s | 102.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/536_ph7.smt2 |   20.047s | 122.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/290_gcc.smt2 |   20.047s | 279.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/065_gcc.smt2 |   20.047s | 219.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/961_sqlite3.smt2 |   20.047s | 124.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/964_sqlite3.smt2 |   20.047s | 91.288MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/497_ph7.smt2       |   20.048s | 126.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/625_ph7.smt2       |   20.048s | 127.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/286_oggenc.smt2 |   20.048s | 262.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/679_ph7.smt2 |   20.048s | 208.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/574_ph7.smt2 |   20.048s | 190.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/723_ph7.smt2 |   20.048s | 273.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/721_ph7.smt2 |   20.048s | 256.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/532_ph7.smt2 |   20.048s | 186.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/179_gcc.smt2 |   20.048s | 160.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/977_sqlite3.smt2 |   20.048s | 226.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/833_sqlite3.smt2 |   20.048s | 293.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/777_sqlite3.smt2 |   20.048s | 98.368MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/953_sqlite3.smt2 |   20.048s | 219.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/545_ph7.smt2       |   20.049s | 162.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/661_ph7.smt2       |   20.049s | 170.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/617_ph7.smt2       |   20.049s | 325.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/580_ph7.smt2       |   20.049s | 138.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/706_ph7.smt2       |   20.049s | 145.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/480_ph7.smt2       |   20.049s | 98.904MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/147_gcc.smt2       |   20.049s | 279.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/063_gcc.smt2       |   20.049s | 294.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/924_sqlite3.smt2 |   20.049s | 306.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/996_sqlite3.smt2 |   20.049s | 107.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/458_oggenc.smt2 |   20.049s | 144.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/599_ph7.smt2 |   20.049s | 219.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/650_ph7.smt2 |   20.049s | 82.308MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/250_gcc.smt2 |   20.049s | 377.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/176_gcc.smt2 |   20.049s | 148.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/972_sqlite3.smt2 |   20.049s | 227.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/802_sqlite3.smt2 |   20.049s | 194.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/763_sqlite3.smt2 |   20.049s | 319.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/804_sqlite3.smt2 |   20.049s | 189.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/787_sqlite3.smt2 |   20.049s | 318.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/888_sqlite3.smt2 |   20.049s | 123.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/737_ph7.smt2       |   20.050s | 99.888MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/066_gcc.smt2       |   20.050s | 211.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/026_gcc.smt2       |   20.050s | 78.492MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/878_sqlite3.smt2 |   20.050s | 231.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/904_sqlite3.smt2 |   20.050s | 267.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/965_sqlite3.smt2 |   20.050s | 85.844MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/512_ph7.smt2 |   20.050s | 254.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/705_ph7.smt2 |   20.050s | 145.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/625_ph7.smt2 |   20.050s | 119.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/093_gcc.smt2 |   20.050s | 230.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/302_gcc.smt2 |   20.050s | 185.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/309_gcc.smt2 |   20.050s | 186.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/858_sqlite3.smt2 |   20.050s | 431.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/726_ph7.smt2       |   20.051s | 259.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/496_ph7.smt2       |   20.051s | 327.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/662_ph7.smt2       |   20.051s | 101.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/602_ph7.smt2       |   20.051s | 141.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/528_ph7.smt2       |   20.051s | 156.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/146_gcc.smt2       |   20.051s | 294.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/224_gcc.smt2       |   20.051s | 312.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/060_gcc.smt2       |   20.051s | 320.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/418_oggenc.smt2 |   20.051s | 71.016MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/486_ph7.smt2 |   20.051s | 136.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/141_gcc.smt2 |   20.051s | 515.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/199_gcc.smt2 |   20.051s | 141.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/185_gcc.smt2 |   20.051s | 264.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/797_sqlite3.smt2 |   20.051s | 312.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/920_sqlite3.smt2 |   20.051s | 76.36MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/962_sqlite3.smt2 |   20.051s | 181.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/oggenc/396_oggenc.smt2 |   20.051s | 275.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/499_ph7.smt2       |   20.052s | 395.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/498_ph7.smt2       |   20.052s | 236.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/899_sqlite3.smt2 |   20.052s | 215.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/278_oggenc.smt2 |   20.052s | 499.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/637_ph7.smt2 |   20.052s | 208.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/592_ph7.smt2 |   20.052s | 281.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/556_ph7.smt2 |   20.052s | 153.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/155_gcc.smt2 |   20.052s | 213.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/127_gcc.smt2 |   20.052s | 268.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/948_sqlite3.smt2 |   20.052s | 171.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/939_sqlite3.smt2 |   20.052s | 317.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/798_sqlite3.smt2 |   20.052s | 103.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/754_ph7.smt2       |   20.053s | 237.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/482_ph7.smt2       |   20.053s | 94.876MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/485_ph7.smt2       |   20.053s | 187.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/616_ph7.smt2       |   20.053s | 267.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/030_gcc.smt2       |   20.053s | 264.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/902_sqlite3.smt2 |   20.053s | 322.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/844_sqlite3.smt2 |   20.053s | 278.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/656_ph7.smt2 |   20.053s | 34.344MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/427_ph7.smt2 |   20.053s | 56.848MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/871_sqlite3.smt2 |   20.053s | 93.084MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/796_sqlite3.smt2 |   20.053s | 136.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/820_sqlite3.smt2 |   20.053s | 179.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/772_sqlite3.smt2 |   20.053s | 184.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/880_sqlite3.smt2 |   20.053s | 232.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/531_ph7.smt2       |   20.054s | 172.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/035_gcc.smt2       |   20.054s | 262.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/182_gcc.smt2       |   20.054s | 216.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/434_ph7.smt2 |   20.054s | 269.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/bzip2/005_bzip2.smt2 |   20.054s | 154.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/072_gcc.smt2 |   20.054s | 312.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/104_gcc.smt2 |   20.054s | 220.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/642_ph7.smt2       |   20.055s | 299.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/608_ph7.smt2       |   20.055s | 389.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/688_ph7.smt2       |   20.055s | 265.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/160_gcc.smt2       |   20.055s | 283.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/099_gcc.smt2       |   20.055s | 242.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/868_sqlite3.smt2 |   20.055s | 272.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/474_ph7.smt2 |   20.055s | 172.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/bzip2/020_bzip2.smt2 |   20.055s | 228.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/313_gcc.smt2 |   20.055s | 214.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/229_gcc.smt2 |   20.055s | 134.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/987_sqlite3.smt2 |   20.055s | 262.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/oggenc/347_oggenc.smt2 |   20.055s | 500.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/612_ph7.smt2       |   20.056s | 308.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/740_ph7.smt2       |   20.056s | 308.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/629_ph7.smt2       |   20.056s | 362.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/503_ph7.smt2       |   20.056s | 280.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/948_sqlite3.smt2 |   20.056s | 49.06MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/941_sqlite3.smt2 |   20.056s | 329.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/956_sqlite3.smt2 |   20.056s | 97.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/747_ph7.smt2 |   20.056s | 280.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/424_ph7.smt2 |   20.056s | 54.956MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/221_gcc.smt2 |   20.056s | 446.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/912_sqlite3.smt2 |   20.056s | 279.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/928_sqlite3.smt2 |   20.056s | 178.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/468_ph7.smt2       |   20.057s | 151.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/463_ph7.smt2       |   20.057s | 257.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/690_ph7.smt2       |   20.057s | 372.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/630_ph7.smt2       |   20.057s | 321.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/524_ph7.smt2 |   20.057s | 240.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/578_ph7.smt2 |   20.057s | 440.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gzip/331_gzip.smt2 |   20.057s | 144.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/043_gcc.smt2 |   20.057s | 262.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/070_gcc.smt2 |   20.057s | 354.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/051_gcc.smt2 |   20.057s | 160.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/825_sqlite3.smt2 |   20.057s | 159.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/827_sqlite3.smt2 |   20.057s | 167.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/789_sqlite3.smt2 |   20.057s | 81.376MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/110_gcc.smt2       |   20.058s | 374.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/373_oggenc.smt2 |   20.058s | 570.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/297_oggenc.smt2 |   20.058s | 475.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/428_oggenc.smt2 |   20.058s | 184.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/677_ph7.smt2 |   20.058s | 142.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/639_ph7.smt2 |   20.058s | 213.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/546_ph7.smt2 |   20.058s | 296.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/398_ph7.smt2 |   20.058s | 314.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/087_gcc.smt2 |   20.058s | 264.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/162_gcc.smt2 |   20.058s | 402.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/102_gcc.smt2 |   20.058s | 189.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/604_ph7.smt2       |   20.059s | 288.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/103_gcc.smt2       |   20.059s | 452.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/bzip2/018_bzip2.smt2 |   20.059s | 338.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/085_gcc.smt2 |   20.059s | 264.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/281_gcc.smt2 |   20.059s | 264.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/243_gcc.smt2 |   20.059s | 146.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/052_gcc.smt2 |   20.059s | 261.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/656_ph7.smt2       |   20.060s | 273.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/546_ph7.smt2       |   20.060s | 382.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/393_oggenc.smt2 |   20.060s | 380.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/539_ph7.smt2 |   20.060s | 269.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/446_ph7.smt2 |   20.060s | 116.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/581_ph7.smt2 |   20.060s | 255.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/404_ph7.smt2 |   20.060s | 486.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/728_ph7.smt2 |   20.060s | 216.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/610_ph7.smt2 |   20.060s | 121.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/293_gcc.smt2 |   20.060s | 167.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/844_sqlite3.smt2 |   20.060s | 333.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/899_sqlite3.smt2 |   20.060s | 199.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/876_sqlite3.smt2 |   20.060s | 305.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/210_gcc.smt2       |   20.061s | 292.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/046_gcc.smt2       |   20.061s | 300.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/987_sqlite3.smt2 |   20.061s | 455.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/380_oggenc.smt2 |   20.061s | 64.98MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/464_ph7.smt2 |   20.061s | 177.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/188_gcc.smt2 |   20.061s | 76.732MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/865_sqlite3.smt2 |   20.061s | 326.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/572_ph7.smt2       |   20.062s | 359.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/292_oggenc.smt2 |   20.062s | 511.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/754_ph7.smt2 |   20.062s | 401.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/bzip2/024_bzip2.smt2 |   20.062s | 160.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/923_sqlite3.smt2 |   20.062s | 170.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/oggenc/349_oggenc.smt2 |   20.062s | 391.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/107_gcc.smt2       |   20.063s | 450.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/926_sqlite3.smt2 |   20.063s | 884.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/378_oggenc.smt2 |   20.063s | 105.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/412_ph7.smt2 |   20.063s | 246.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/665_ph7.smt2 |   20.063s | 389.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/177_gcc.smt2 |   20.063s | 340.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/619_ph7.smt2       |   20.064s | 404.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/169_gcc.smt2       |   20.064s | 601.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/162_gcc.smt2       |   20.064s | 512.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/808_sqlite3.smt2 |   20.064s | 492.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/376_oggenc.smt2 |   20.064s | 355.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/364_oggenc.smt2 |   20.064s | 419.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/560_ph7.smt2 |   20.064s | 172.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/605_ph7.smt2 |   20.064s | 146.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/096_gcc.smt2 |   20.064s | 360.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/244_gcc.smt2 |   20.064s | 324.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/057_gcc.smt2 |   20.064s | 51.968MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/919_sqlite3.smt2 |   20.064s | 183.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/150_gcc.smt2       |   20.065s | 678.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/958_sqlite3.smt2 |   20.065s | 423.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/145_gcc.smt2 |   20.065s | 466.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/168_gcc.smt2 |   20.065s | 344.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/274_gcc.smt2 |   20.065s | 536.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/946_sqlite3.smt2 |   20.065s | 325.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/775_sqlite3.smt2 |   20.065s | 96.996MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/oggenc/394_oggenc.smt2 |   20.065s | 478.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/oggenc/370_oggenc.smt2 |   20.065s | 571.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/056_gcc.smt2       |   20.066s | 308.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/285_oggenc.smt2 |   20.066s | 111.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/423_ph7.smt2 |   20.066s | 273.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/543_ph7.smt2 |   20.066s | 283.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/469_ph7.smt2 |   20.066s | 166.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/bzip2/030_bzip2.smt2 |   20.066s | 334.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/bzip2/000_bzip2.smt2 |   20.066s | 230.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/112_gcc.smt2 |   20.066s | 49.52MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/bzip2/016_bzip2.smt2   |   20.067s | 753.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/232_gcc.smt2       |   20.067s | 546.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/709_ph7.smt2 |   20.067s | 502.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/432_ph7.smt2 |   20.067s | 275.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/bzip2/014_bzip2.smt2 |   20.067s | 342.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/257_gcc.smt2 |   20.067s | 182.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/297_gcc.smt2 |   20.067s | 515.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/826_sqlite3.smt2 |   20.067s | 521.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/760_sqlite3.smt2 |   20.067s | 78.444MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/214_gcc.smt2       |   20.068s | 493.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/910_sqlite3.smt2 |   20.068s | 868.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/339_oggenc.smt2 |   20.068s | 87.568MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/439_ph7.smt2 |   20.068s | 66.612MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/686_ph7.smt2 |   20.068s | 605.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/712_ph7.smt2 |   20.068s | 424.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/bzip2/011_bzip2.smt2 |   20.068s | 396.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/205_gcc.smt2 |   20.068s | 393.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/790_ph7.smt2       |   20.069s | 270.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/395_oggenc.smt2 |   20.069s | 325.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/548_ph7.smt2 |   20.069s | 327.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/156_gcc.smt2 |   20.069s | 420.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/oggenc/343_oggenc.smt2 |   20.069s | 454.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/659_ph7.smt2       |   20.070s | 587.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/383_oggenc.smt2 |   20.070s | 178.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/425_oggenc.smt2 |   20.070s | 116.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gzip/327_gzip.smt2 |   20.070s | 771.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/bzip2/010_bzip2.smt2 |   20.070s | 280.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/450_ph7.smt2 |   20.071s | 153.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/596_ph7.smt2 |   20.071s | 385.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/463_ph7.smt2 |   20.072s | 456.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/535_ph7.smt2 |   20.072s | 459.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/551_ph7.smt2 |   20.072s | 505.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/173_gcc.smt2 |   20.072s | 595.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/182_gcc.smt2 |   20.072s | 264.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/246_gcc.smt2 |   20.073s | 573.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/053_gcc.smt2 |   20.073s | 338.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/183_gcc.smt2       |   20.074s | 493.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/179_gcc.smt2       |   20.074s | 653.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/333_oggenc.smt2 |   20.074s | 164.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/310_gcc.smt2 |   20.074s | 602.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/193_gcc.smt2       |   20.075s | 532.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/414_oggenc.smt2 |   20.075s | 169.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/671_ph7.smt2 |   20.075s | 179.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/bzip2/028_bzip2.smt2 |   20.075s | 428.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/209_gcc.smt2       |   20.076s | 896.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/937_sqlite3.smt2 |   20.077s | 873.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/387_oggenc.smt2 |   20.077s | 99.664MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/049_gcc.smt2 |   20.077s | 515.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/226_gcc.smt2       |   20.078s | 557.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/405_oggenc.smt2 |   20.078s | 97.416MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/630_ph7.smt2 |   20.078s | 486.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/780_sqlite3.smt2 |   20.078s | 393.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/825_sqlite3.smt2 |   20.079s | 891.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/782_sqlite3.smt2 |   20.079s | 678.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/765_sqlite3.smt2 |   20.079s | 96.868MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/640_ph7.smt2       |   20.080s | 349.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/oggenc/366_oggenc.smt2 |   20.080s | 703.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/oggenc/362_oggenc.smt2 |   20.080s | 562.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/138_gcc.smt2       |   20.081s | 551.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/587_ph7.smt2 |   20.081s | 523.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/bzip2/026_bzip2.smt2 |   20.081s | 163.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/860_sqlite3.smt2 |   20.081s | 746.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/658_ph7.smt2 |   20.082s | 88.5MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/058_gcc.smt2 |   20.082s | 1016.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/924_sqlite3.smt2 |   20.083s | 598.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/287_oggenc.smt2 |   20.084s | 128.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/bzip2/015_bzip2.smt2 |   20.084s | 333.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/271_gcc.smt2 |   20.084s | 625.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/842_sqlite3.smt2 |   20.084s | 591.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/628_ph7.smt2       |   20.085s | 459.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/355_oggenc.smt2 |   20.085s | 83.588MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/585_ph7.smt2 |   20.085s | 518.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/071_gcc.smt2 |   20.085s | 475.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/707_ph7.smt2 |   20.086s | 83.112MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/947_sqlite3.smt2 |   20.086s | 459.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gzip/263_gzip.smt2     |   20.087s | 137.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/501_ph7.smt2 |   20.087s | 457.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/926_sqlite3.smt2 |   20.087s | 814.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/oggenc/355_oggenc.smt2 |   20.087s | 580.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/213_gcc.smt2       |   20.088s | 785.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/187_gcc.smt2       |   20.088s | 984.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/424_oggenc.smt2 |   20.088s | 175.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/251_gcc.smt2 |   20.088s | 550.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/477_ph7.smt2 |   20.090s | 720.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/161_gcc.smt2 |   20.090s | 1013.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/508_ph7.smt2       |   20.091s | 800.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/090_gcc.smt2       |   20.091s | 900.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/190_gcc.smt2       |   20.091s | 1112.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/032_gcc.smt2       |   20.092s | 1059.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/695_ph7.smt2 |   20.092s | 964.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/857_sqlite3.smt2 |   20.092s | 746.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/444_ph7.smt2 |   20.093s | 699.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/254_gcc.smt2 |   20.093s | 630.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/973_sqlite3.smt2 |   20.094s | 884.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/503_ph7.smt2 |   20.095s | 600.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/bzip2/027_bzip2.smt2 |   20.095s | 609.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/044_gcc.smt2 |   20.095s | 512.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/497_ph7.smt2 |   20.096s | 597.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/835_sqlite3.smt2 |   20.096s | 539.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/084_gcc.smt2 |   20.097s | 181.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/829_sqlite3.smt2 |   20.097s | 846.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/748_ph7.smt2 |   20.098s | 670.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/128_gcc.smt2       |   20.099s | 868.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/963_sqlite3.smt2 |   20.099s | 225.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/081_gcc.smt2       |   20.100s | 904.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/077_gcc.smt2       |   20.101s | 1114.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/237_gcc.smt2       |   20.101s | 789.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/534_ph7.smt2 |   20.101s | 755.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/620_ph7.smt2 |   20.101s | 982.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/752_ph7.smt2 |   20.101s | 711.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gzip/337_gzip.smt2 |   20.101s | 645.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/184_gcc.smt2 |   20.101s | 1019.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/059_gcc.smt2 |   20.101s | 816.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/289_gcc.smt2 |   20.101s | 1012.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/167_gcc.smt2       |   20.102s | 1054.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/687_ph7.smt2 |   20.103s | 940.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/bzip2/035_bzip2.smt2 |   20.103s | 500.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/758_ph7.smt2 |   20.104s | 524.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/672_ph7.smt2 |   20.106s | 136.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/180_gcc.smt2       |   20.107s | 1010.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/bzip2/004_bzip2.smt2 |   20.107s | 466.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/047_gcc.smt2 |   20.107s | 999.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/064_gcc.smt2 |   20.107s | 648.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/296_oggenc.smt2 |   20.108s | 182.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/417_oggenc.smt2 |   20.108s | 495.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/bzip2/021_bzip2.smt2 |   20.108s | 780.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/174_gcc.smt2       |   20.109s | 932.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/117_gcc.smt2       |   20.111s | 984.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/113_gcc.smt2       |   20.111s | 951.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/058_gcc.smt2       |   20.112s | 1032.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/992_sqlite3.smt2 |   20.112s | 793.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/694_ph7.smt2 |   20.114s | 602.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/173_gcc.smt2       |   20.117s | 1012.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/494_ph7.smt2       |   20.118s | 954.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/346_oggenc.smt2 |   20.119s | 223.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/318_oggenc.smt2 |   20.122s | 266.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/561_ph7.smt2 |   20.122s | 1052.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/636_ph7.smt2       |   20.124s | 1262.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/732_ph7.smt2 |   20.124s | 520.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/750_ph7.smt2 |   20.126s | 928.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/337_oggenc.smt2 |   20.128s | 238.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/720_ph7.smt2 |   20.128s | 1015.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/579_ph7.smt2       |   20.130s | 1341.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/118_gcc.smt2       |   20.131s | 1259.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/525_ph7.smt2 |   20.132s | 1123.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/101_gcc.smt2 |   20.135s | 1096.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/235_gcc.smt2 |   20.136s | 997.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/718_ph7.smt2 |   20.137s | 1170.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gzip/253_gzip.smt2     |   20.138s | 317.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/045_gcc.smt2 |   20.140s | 1117.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/991_sqlite3.smt2 |   20.142s | 1178.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/970_sqlite3.smt2 |   20.144s | 1247.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/207_gcc.smt2 |   20.145s | 1907.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/411_ph7.smt2 |   20.146s | 1486.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/441_oggenc.smt2 |   20.147s | 476.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/443_ph7.smt2 |   20.150s | 1184.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/327_oggenc.smt2 |   20.154s | 481.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/841_sqlite3.smt2 |   20.162s | 1990.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/407_oggenc.smt2 |   20.164s | 493.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/oggenc/364_oggenc.smt2 |   20.165s | 1384.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/526_ph7.smt2       |   20.166s | 1510.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/674_ph7.smt2 |   20.174s | 1210.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/222_gcc.smt2 |   20.176s | 1373.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/306_oggenc.smt2 |   20.178s | 436.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/692_ph7.smt2 |   20.178s | 1890.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/609_ph7.smt2       |   20.181s | 1892.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/901_sqlite3.smt2 |   20.182s | 1768.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/943_sqlite3.smt2 |   20.185s | 1537.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/242_gcc.smt2 |   20.186s | 1909.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/336_oggenc.smt2 |   20.187s | 555.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/415_oggenc.smt2 |   20.187s | 456.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/606_ph7.smt2 |   20.188s | 1472.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/307_gcc.smt2 |   20.189s | 1906.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/332_oggenc.smt2 |   20.191s | 512.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/362_oggenc.smt2 |   20.191s | 485.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/892_sqlite3.smt2 |   20.191s | 1247.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/490_ph7.smt2 |   20.193s | 1337.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/236_gcc.smt2 |   20.194s | 1547.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/110_gcc.smt2 |   20.200s | 1612.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/050_gcc.smt2       |   20.201s | 2465.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/oggenc/353_oggenc.smt2 |   20.210s | 2228.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/138_gcc.smt2 |   20.211s | 1930.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/077_gcc.smt2 |   20.212s | 1881.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/298_oggenc.smt2 |   20.213s | 601.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/475_ph7.smt2 |   20.216s | 2070.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/305_gcc.smt2 |   20.221s | 2051.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/882_sqlite3.smt2 |   20.222s | 2038.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/415_ph7.smt2 |   20.230s | 2143.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/oggenc/365_oggenc.smt2 |   20.231s | 2676.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/219_gcc.smt2 |   20.233s | 1931.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/192_gcc.smt2 |   20.236s | 2562.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/201_gcc.smt2 |   20.236s | 2020.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/099_gcc.smt2 |   20.243s | 3741.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/998_sqlite3.smt2 |   20.243s | 2077.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/416_oggenc.smt2 |   20.245s | 761.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/727_ph7.smt2 |   20.250s | 2018.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/519_ph7.smt2 |   20.251s | 1815.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/oggenc/354_oggenc.smt2 |   20.252s | 2806.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/773_ph7.smt2       |   20.259s | 3501.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/993_sqlite3.smt2 |   20.259s | 3777.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/570_ph7.smt2 |   20.260s | 2634.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/743_ph7.smt2       |   20.263s | 3184.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/278_gcc.smt2 |   20.274s | 2757.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/oggenc/390_oggenc.smt2 |   20.284s | 2677.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/660_ph7.smt2 |   20.287s | 2656.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/725_ph7.smt2 |   20.293s | 2534.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/494_ph7.smt2 |   20.307s | 2753.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/467_ph7.smt2       |   20.317s | 3307.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/079_gcc.smt2 |   20.318s | 2686.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/oggenc/378_oggenc.smt2 |   20.318s | 2870.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/613_ph7.smt2       |   20.320s | 3148.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/oggenc/345_oggenc.smt2 |   20.337s | 4169.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/094_gcc.smt2 |   20.340s | 2926.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/377_oggenc.smt2 |   20.345s | 1783.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/784_sqlite3.smt2 |   20.345s | 3621.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/794_sqlite3.smt2 |   20.349s | 3283.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/334_oggenc.smt2 |   20.352s | 1899.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/741_ph7.smt2 |   20.352s | 3531.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/061_gcc.smt2 |   20.362s | 2915.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/959_sqlite3.smt2 |   20.367s | 3682.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/850_sqlite3.smt2 |   20.382s | 4171.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/811_sqlite3.smt2 |   20.390s | 3590.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/581_ph7.smt2       |   20.397s | 3858.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/685_ph7.smt2 |   20.404s | 3432.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/930_sqlite3.smt2 |   20.410s | 3668.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/883_sqlite3.smt2 |   20.416s | 4328.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/898_sqlite3.smt2 |   20.420s | 3725.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/418_ph7.smt2 |   20.421s | 3561.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/936_sqlite3.smt2 |   20.427s | 4371.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/975_sqlite3.smt2 |   20.433s | 3749.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/459_ph7.smt2 |   20.434s | 3790.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/557_ph7.smt2 |   20.434s | 4148.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/918_sqlite3.smt2 |   20.442s | 3689.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/573_ph7.smt2 |   20.456s | 4096.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/568_ph7.smt2 |   20.460s | 3657.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/bzip2/038_bzip2.smt2 |   20.461s | 4652.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/631_ph7.smt2 |   20.470s | 4638.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/213_gcc.smt2 |   20.517s | 4467.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/217_gcc.smt2 |   20.517s | 4624.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/ph7/699_ph7.smt2       |   20.519s | 5114.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/195_gcc.smt2 |   20.522s | 4770.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/614_ph7.smt2 |   20.527s | 4662.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/897_sqlite3.smt2 |   20.533s | 7598.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/593_ph7.smt2 |   20.545s | 4861.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/866_sqlite3.smt2 |   20.557s | 6161.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/917_sqlite3.smt2 |   20.564s | 5565.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/oggenc/393_oggenc.smt2 |   20.564s | 6733.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/oggenc/373_oggenc.smt2 |   20.565s | 5912.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/843_sqlite3.smt2 |   20.569s | 5893.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/oggenc/377_oggenc.smt2 |   20.571s | 5784.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/837_sqlite3.smt2 |   20.573s | 5250.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/159_gcc.smt2 |   20.580s | 5848.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/736_ph7.smt2 |   20.586s | 6014.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/743_ph7.smt2 |   20.596s | 4944.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/299_gcc.smt2 |   20.598s | 5566.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/925_sqlite3.smt2 |   20.601s | 6706.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/437_ph7.smt2 |   20.604s | 6061.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/854_sqlite3.smt2 |   20.604s | 6092.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/082_gcc.smt2 |   20.606s | 5496.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/oggenc/340_oggenc.smt2 |   20.609s | 6855.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/938_sqlite3.smt2 |   20.610s | 6700.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/216_gcc.smt2 |   20.617s | 5192.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/133_gcc.smt2 |   20.619s | 7645.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/795_sqlite3.smt2 |   20.623s | 5955.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/713_ph7.smt2 |   20.625s | 5952.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/oggenc/339_oggenc.smt2 |   20.626s | 6958.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/sqlite3/970_sqlite3.smt2 |   20.628s | 6985.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/440_ph7.smt2 |   20.632s | 5161.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/140_gcc.smt2       |   20.636s | 6496.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/762_sqlite3.smt2 |   20.643s | 7752.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/090_gcc.smt2 |   20.647s | 5355.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/995_sqlite3.smt2 |   20.649s | 6383.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/997_sqlite3.smt2 |   20.649s | 7867.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/983_sqlite3.smt2 |   20.660s | 8314.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/642_ph7.smt2 |   20.661s | 6693.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/178_gcc.smt2 |   20.661s | 5853.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/910_sqlite3.smt2 |   20.666s | 6228.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/952_sqlite3.smt2 |   20.667s | 5966.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/170_gcc.smt2 |   20.669s | 6060.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/900_sqlite3.smt2 |   20.669s | 5980.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/oggenc/359_oggenc.smt2 |   20.672s | 7449.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/607_ph7.smt2 |   20.675s | 6037.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/381_oggenc.smt2 |   20.681s | 5585.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/511_ph7.smt2 |   20.684s | 6248.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/407_ph7.smt2 |   20.695s | 5869.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/063_gcc.smt2 |   20.707s | 6561.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/218_gcc.smt2 |   20.710s | 6394.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/967_sqlite3.smt2 |   20.714s | 6519.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/114_gcc.smt2 |   20.715s | 6297.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/267_gcc.smt2 |   20.718s | 6760.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/399_ph7.smt2 |   20.719s | 6495.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/436_ph7.smt2 |   20.722s | 6491.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/542_ph7.smt2 |   20.725s | 6369.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/622_ph7.smt2 |   20.733s | 6979.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/806_sqlite3.smt2 |   20.737s | 6927.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/314_oggenc.smt2 |   20.738s | 6825.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/978_sqlite3.smt2 |   20.740s | 6685.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/651_ph7.smt2 |   20.741s | 6776.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/gcc/047_gcc.smt2       |   20.748s | 7606.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/649_ph7.smt2 |   20.750s | 6330.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/225_gcc.smt2 |   20.752s | 7107.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/425_ph7.smt2 |   20.755s | 6979.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/996_sqlite3.smt2 |   20.756s | 6595.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/812_sqlite3.smt2 |   20.762s | 7035.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/634_ph7.smt2 |   20.765s | 6868.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/618_ph7.smt2 |   20.776s | 7347.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/589_ph7.smt2 |   20.787s | 7484.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/759_sqlite3.smt2 |   20.813s | 7935.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/681_ph7.smt2 |   20.820s | 6916.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/907_sqlite3.smt2 |   20.820s | 6569.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/bzip2/006_bzip2.smt2   |   20.822s | 8793.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/932_sqlite3.smt2 |   20.825s | 7694.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/462_ph7.smt2 |   20.848s | 7652.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2/oggenc/329_oggenc.smt2 |   20.856s | 7625.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/bzip2/009_bzip2.smt2 |   20.874s | 8393.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/653_ph7.smt2 |   20.875s | 7470.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/gcc/041_gcc.smt2 |   20.879s | 8048.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/ph7/638_ph7.smt2 |   20.906s | 7818.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/979_sqlite3.smt2 |   20.906s | 8016.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/927_sqlite3.smt2 |   21.080s | 8761.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBV/20210301-Alive2-partial-undef/sqlite3/904_sqlite3.smt2 |   21.178s | 9993.0MiB| timeout | 0 |  |  |
