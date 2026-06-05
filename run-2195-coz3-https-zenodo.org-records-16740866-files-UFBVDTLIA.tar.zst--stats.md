# .

* SAT 0
* UNSAT 24
* TIMEOUT 0
* UNKNOWN 0

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/UFBVDTLIA.tar.zst?download=1 | Source list: quantifier_benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-UFBVDTLIA.tar.zst-
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: 2c7b256db21f364cf37752e91cf750bf0b570f2c
Z3 branch: 2c7b256db21f364cf37752e91cf750bf0b570f2c
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/UFBVDTLIA.tar.zst?download=1
Z3 commit message: Use the minimum generation number among matching enodes (#9405)

* Compute term generations based on minimal match

* Tidy up get_*_f_app

* Update euf_mam to the minimum generation number among matches

* Update euf_mam.cpp

* Move the UNREACHABLE() test to smt_mam.cpp

* Enforce stickiness of max-generation

* Add current generation tracking to bind structure

* Fix build error

---------

Co-authored-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2page_entry_perm._05.smt2 |    0.026s | 19.652MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.zero_leads_is_empty_page_entry._03.smt2 |    0.026s | 20.112MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2page_entry_perm._01.smt2 |    0.027s | 20.096MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._01.smt2 |    0.027s | 19.888MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTLIA/20241211-verus/verussystems/mimalloc-smt-flagslib_flags.impl_%0.get_retire_expire._01.smt2 |    0.027s | 19.888MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2page_entry_perm._03.smt2 |    0.028s | 19.764MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2page_entry_perm._04.smt2 |    0.028s | 20.1MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._32.smt2 |    0.028s | 19.656MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.zero_leads_is_empty_page_entry._01.smt2 |    0.028s | 19.86MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTLIA/20241211-verus/verussystems/mimalloc-smt-flagslib_flags.impl_%0.set_is_committed._01.smt2 |    0.028s | 20.104MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTLIA/20241211-verus/verussystems/mimalloc-smt-flagslib_flags.impl_%0.set_is_zero_init._03.smt2 |    0.031s | 20.876MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._06.smt2 |    0.034s | 20.892MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._25.smt2 |    0.035s | 21.12MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTLIA/20241211-verus/verussystems/mimalloc-smt-flagslib_flags.impl_%0.set_is_committed._02.smt2 |    0.036s | 20.928MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTLIA/20241211-verus/verussystems/mimalloc-smt-flagslib_flags.impl_%0.set_retire_expire._02.smt2 |    0.036s | 20.912MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTLIA/20241211-verus/verussystems/mimalloc-smt-flagslib_flags.impl_%0.set_in_full._01.smt2 |    0.037s | 21.368MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2pa._01.smt2 |    0.046s | 19.888MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._16.smt2 |    0.047s | 19.848MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._07.smt2 |    0.048s | 20.104MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.zero_leads_is_empty_page_entry._06.smt2 |    0.048s | 19.848MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._35.smt2 |    0.055s | 20.88MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._05.smt2 |    0.055s | 21.16MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._12.smt2 |    0.056s | 20.868MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTLIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_auto._01.smt2 |    0.062s | 21.636MiB| unsat | 0 |  |  |
