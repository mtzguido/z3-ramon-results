# .

* SAT 37
* UNSAT 101
* TIMEOUT 55
* UNKNOWN 0

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/UFBV.tar.zst?download=1 | Source list: quantifier_benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-UFBV.tar.zst-downl
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: 2c7b256db21f364cf37752e91cf750bf0b570f2c
Z3 branch: 2c7b256db21f364cf37752e91cf750bf0b570f2c
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/UFBV.tar.zst?download=1
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
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-swap2-fixpoint-9.smt2 |    0.027s | 19.856MiB| sat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-synabs-fixpoint-1.smt2 |    0.027s | 19.744MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-swap2-fixpoint-4.smt2 |    0.028s | 19.808MiB| sat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-swap2-fixpoint-2.smt2 |    0.028s | 19.836MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-synabs-fixpoint-5.smt2 |    0.030s | 19.716MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-synabs-fixpoint-7.smt2 |    0.031s | 19.796MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-pipeline-fixpoint-1.smt2 |    0.032s | 20.864MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-swap1-fixpoint-1.smt2 |    0.032s | 19.588MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-seq-fixpoint-7.smt2 |    0.041s | 19.904MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-synabs-fixpoint-4.smt2 |    0.042s | 19.88MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-swap1-fixpoint-5.smt2 |    0.043s | 19.748MiB| sat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-swap1-fixpoint-2.smt2 |    0.046s | 19.712MiB| sat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-swap1-fixpoint-8.smt2 |    0.046s | 19.856MiB| sat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-seq-fixpoint-5.smt2 |    0.047s | 19.876MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/itc-b13-fixpoint-1.smt2 |    0.047s | 19.908MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-seq-fixpoint-10.smt2 |    0.048s | 19.852MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-swap1-fixpoint-4.smt2 |    0.048s | 20.232MiB| sat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/AR-fixpoint-4.smt2 |    0.049s | 20.276MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-dyn-partition-fixpoint-1.smt2 |    0.050s | 19.596MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-seq-fixpoint-8.smt2 |    0.051s | 19.82MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/AR-fixpoint-8.smt2 |    0.051s | 20.396MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-swap1-fixpoint-10.smt2 |    0.051s | 19.988MiB| sat | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/sqlite3/776_sqlite3.smt2 |    0.055s | 21.952MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-seq-fixpoint-3.smt2 |    0.057s | 19.604MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-dyn-partition-fixpoint-3.smt2 |    0.057s | 19.868MiB| unsat | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/ph7/652_ph7.smt2 |    0.058s | 21.804MiB| unsat | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/sqlite3/847_sqlite3.smt2 |    0.058s | 21.644MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-swap1-fixpoint-7.smt2 |    0.058s | 19.76MiB| sat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-seq-fixpoint-1.smt2 |    0.058s | 19.844MiB| unsat | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/ph7/408_ph7.smt2 |    0.059s | 21.072MiB| unsat | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/ph7/473_ph7.smt2 |    0.059s | 22.16MiB| unsat | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/ph7/409_ph7.smt2 |    0.059s | 21.132MiB| unsat | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/sqlite3/951_sqlite3.smt2 |    0.060s | 24.192MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-swap1-fixpoint-6.smt2 |    0.060s | 19.676MiB| sat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-swap2-fixpoint-7.smt2 |    0.060s | 19.852MiB| sat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-dyn-partition-fixpoint-4.smt2 |    0.060s | 19.904MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-swap2-fixpoint-5.smt2 |    0.060s | 19.588MiB| sat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-swap2-fixpoint-1.smt2 |    0.061s | 19.744MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/AR-fixpoint-5.smt2 |    0.061s | 20.58MiB| unsat | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/ph7/533_ph7.smt2 |    0.062s | 21.392MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-synabs-fixpoint-3.smt2 |    0.062s | 19.752MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-dyn-partition-fixpoint-7.smt2 |    0.062s | 20.148MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-dyn-partition-fixpoint-2.smt2 |    0.063s | 19.616MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-synabs-fixpoint-9.smt2 |    0.063s | 19.864MiB| unsat | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/ph7/547_ph7.smt2 |    0.064s | 21.148MiB| unsat | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/gcc/248_gcc.smt2 |    0.064s | 22.252MiB| unsat | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/sqlite3/940_sqlite3.smt2 |    0.064s | 21.844MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-synabs-fixpoint-8.smt2 |    0.064s | 20.116MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-synabs-fixpoint-10.smt2 |    0.064s | 19.848MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-dyn-partition-fixpoint-9.smt2 |    0.064s | 20.104MiB| unsat | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2/ph7/570_ph7.smt2        |    0.065s | 22.3MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/AR-fixpoint-1.smt2 |    0.065s | 20.368MiB| unsat | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/sqlite3/931_sqlite3.smt2 |    0.066s | 21.136MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-dyn-partition-fixpoint-8.smt2 |    0.066s | 19.864MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/sdlx-fixpoint-1.smt2 |    0.066s | 20.404MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-equiv-fixpoint-1.smt2 |    0.066s | 20.976MiB| sat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-synabs-fixpoint-2.smt2 |    0.068s | 19.616MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-dyn-partition-fixpoint-10.smt2 |    0.070s | 20.116MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-synabs-fixpoint-6.smt2 |    0.070s | 19.796MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/AR-fixpoint-6.smt2 |    0.071s | 20.42MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-swap2-fixpoint-3.smt2 |    0.071s | 19.752MiB| sat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-swap2-fixpoint-6.smt2 |    0.071s | 19.84MiB| sat | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2/gcc/231_gcc.smt2        |    0.072s | 21.264MiB| unsat | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/ph7/402_ph7.smt2 |    0.072s | 22.128MiB| unsat | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/ph7/701_ph7.smt2 |    0.073s | 23.76MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-seq-fixpoint-6.smt2 |    0.074s | 19.796MiB| unsat | 0 |  |  |
|non-incremental/UFBV/20210330-PEak/uf_sat/easy3.smt2         |    0.075s | 23.536MiB| sat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/cache-coherence-2-fixpoint-1.smt2 |    0.078s | 21.632MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-dyn-partition-fixpoint-5.smt2 |    0.078s | 19.768MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-dyn-partition-fixpoint-6.smt2 |    0.079s | 19.856MiB| unsat | 0 |  |  |
|non-incremental/UFBV/20210330-PEak/uf_sat/easy0.smt2         |    0.080s | 23.5MiB| sat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-swap2-fixpoint-8.smt2 |    0.080s | 19.712MiB| sat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-swap1-fixpoint-3.smt2 |    0.081s | 19.864MiB| sat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/AR-fixpoint-3.smt2 |    0.082s | 20.356MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/AR-fixpoint-2.smt2 |    0.083s | 20.364MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-seq-fixpoint-9.smt2 |    0.085s | 19.728MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/AR-fixpoint-9.smt2 |    0.088s | 20.324MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-seq-fixpoint-4.smt2 |    0.088s | 19.744MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-swap2-fixpoint-10.smt2 |    0.090s | 19.88MiB| sat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-seq-fixpoint-2.smt2 |    0.091s | 19.812MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/itc-b13-fixpoint-2.smt2 |    0.091s | 20.224MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-swap1-fixpoint-9.smt2 |    0.092s | 19.892MiB| sat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/AR-fixpoint-7.smt2 |    0.092s | 20.344MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-pipeline-fixpoint-2.smt2 |    0.094s | 21.2MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/AR-fixpoint-10.smt2 |    0.096s | 20.412MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-pipeline-fixpoint-3.smt2 |    0.104s | 22.036MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/itc-b13-fixpoint-4.smt2 |    0.120s | 21.296MiB| sat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/itc-b13-fixpoint-3.smt2 |    0.120s | 20.944MiB| sat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/pi-bus-fixpoint-1.smt2 |    0.125s | 23.868MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/cache-coherence-3-fixpoint-1.smt2 |    0.129s | 23.116MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/usb-phy-fixpoint-1.smt2 |    0.129s | 21.68MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/ethernet-fixpoint-1.smt2 |    0.131s | 22.932MiB| unsat | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/gcc/131_gcc.smt2 |    0.133s | 24.444MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/itc-b13-fixpoint-5.smt2 |    0.152s | 22.656MiB| sat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/sdlx-fixpoint-2.smt2 |    0.164s | 22.28MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/itc-b13-fixpoint-6.smt2 |    0.188s | 22.532MiB| sat | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2/gzip/258_gzip.smt2      |    0.191s | 23.216MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/sdlx-fixpoint-3.smt2 |    0.223s | 23.796MiB| unsat | 0 |  |  |
|non-incremental/UFBV/20210330-PEak/uf_sat/easy2.smt2         |    0.233s | 31.04MiB| sat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/cache-coherence-2-fixpoint-2.smt2 |    0.248s | 25.276MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/itc-b13-fixpoint-7.smt2 |    0.249s | 23.196MiB| sat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/usb-phy-fixpoint-2.smt2 |    0.299s | 26.044MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/itc-b13-fixpoint-8.smt2 |    0.322s | 24.74MiB| sat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/itc-b13-fixpoint-9.smt2 |    0.343s | 25.08MiB| sat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/itc-b13-fixpoint-10.smt2 |    0.402s | 25.712MiB| sat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/cache-coherence-3-fixpoint-2.smt2 |    0.420s | 30.224MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/sdlx-fixpoint-4.smt2 |    0.443s | 25.288MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/ethernet-fixpoint-2.smt2 |    0.475s | 29.388MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/cache-coherence-2-fixpoint-3.smt2 |    0.546s | 30.62MiB| unsat | 0 |  |  |
|non-incremental/UFBV/20210330-PEak/uf_sat/easy1.smt2         |    0.557s | 39.94MiB| sat | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/ph7/678_ph7.smt2 |    0.559s | 28.924MiB| unsat | 0 |  |  |
|non-incremental/UFBV/20210330-PEak/uf_sat/hard4.smt2         |    0.614s | 51.448MiB| sat | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/ph7/492_ph7.smt2 |    0.624s | 64.888MiB| unsat | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/gcc/152_gcc.smt2 |    0.663s | 65.188MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/pi-bus-fixpoint-2.smt2 |    0.671s | 32.184MiB| unsat | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2/sqlite3/977_sqlite3.smt2 |    0.676s | 22.692MiB| unsat | 0 |  |  |
|non-incremental/UFBV/20210330-PEak/uf_sat/easy4.smt2         |    0.705s | 48.104MiB| sat | 0 |  |  |
|non-incremental/UFBV/20210330-PEak/uf_sat/hard0.smt2         |    0.760s | 47.444MiB| sat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/cache-coherence-2-fixpoint-4.smt2 |    0.879s | 37.372MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/usb-phy-fixpoint-3.smt2 |    0.881s | 40.88MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/cache-coherence-3-fixpoint-3.smt2 |    0.970s | 40.94MiB| unsat | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/ph7/496_ph7.smt2 |    1.255s | 57.156MiB| unsat | 0 |  |  |
|non-incremental/UFBV/20210330-PEak/uf_sat/medium1.smt2       |    1.334s | 70.444MiB| sat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/cache-coherence-2-fixpoint-5.smt2 |    1.432s | 47.104MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/pi-bus-fixpoint-3.smt2 |    1.483s | 44.736MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/ethernet-fixpoint-3.smt2 |    1.509s | 43.836MiB| unsat | 0 |  |  |
|non-incremental/UFBV/20210330-PEak/uf_sat/medium5.smt2       |    1.662s | 53.176MiB| sat | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/ph7/504_ph7.smt2 |    2.157s | 99.0MiB| unsat | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/gcc/212_gcc.smt2 |    2.362s | 179.0MiB| unsat | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2/oggenc/345_oggenc.smt2  |    2.414s | 89.684MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/usb-phy-fixpoint-4.smt2 |    2.435s | 59.236MiB| unsat | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/oggenc/379_oggenc.smt2 |    2.888s | 169.0MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/cache-coherence-2-fixpoint-6.smt2 |    2.893s | 70.668MiB| unsat | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/sqlite3/887_sqlite3.smt2 |    2.897s | 168.0MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/ethernet-fixpoint-4.smt2 |    3.192s | 60.276MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/usb-phy-fixpoint-5.smt2 |    3.891s | 71.964MiB| unsat | 0 |  |  |
|non-incremental/UFBV/20210330-PEak/uf_sat/medium2.smt2       |    4.710s | 56.376MiB| sat | 0 |  |  |
|non-incremental/UFBV/20210330-PEak/uf_sat/hard1.smt2         |    7.459s | 147.0MiB| sat | 0 |  |  |
|non-incremental/UFBV/20210330-PEak/uf_unsat/easy.smt2        |   20.023s | 137.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/sdlx-fixpoint-10.smt2 |   20.029s | 93.784MiB| timeout | 0 |  |  |
|non-incremental/UFBV/20210330-PEak/uf_unsat/hard.smt2        |   20.031s | 248.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/oggenc/388_oggenc.smt2 |   20.037s | 66.984MiB| timeout | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/ph7/442_ph7.smt2 |   20.042s | 64.084MiB| timeout | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-pipeline-fixpoint-6.smt2 |   20.045s | 118.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-equiv-fixpoint-4.smt2 |   20.046s | 166.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/20210330-PEak/uf_sat/medium4.smt2       |   20.047s | 132.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-pipeline-fixpoint-9.smt2 |   20.048s | 107.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/20210330-PEak/uf_sat/hard3.smt2         |   20.051s | 84.708MiB| timeout | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/ph7/613_ph7.smt2 |   20.051s | 86.808MiB| timeout | 0 |  |  |
|non-incremental/UFBV/20210330-PEak/uf_unsat/medium.smt2      |   20.053s | 243.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/20210330-PEak/uf_sat/hard2.smt2         |   20.055s | 126.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-pipeline-fixpoint-8.smt2 |   20.056s | 98.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/ph7/668_ph7.smt2 |   20.057s | 42.52MiB| timeout | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-equiv-fixpoint-2.smt2 |   20.058s | 31.436MiB| timeout | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-pipeline-fixpoint-5.smt2 |   20.060s | 146.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/20210330-PEak/uf_sat/medium3.smt2       |   20.063s | 241.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-equiv-fixpoint-6.smt2 |   20.063s | 177.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-pipeline-fixpoint-7.smt2 |   20.064s | 154.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/20210330-PEak/uf_sat/easy5.smt2         |   20.070s | 245.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-equiv-fixpoint-3.smt2 |   20.076s | 163.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/20210330-PEak/uf_sat/medium0.smt2       |   20.078s | 245.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-equiv-fixpoint-9.smt2 |   20.078s | 235.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-equiv-fixpoint-8.smt2 |   20.085s | 166.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-equiv-fixpoint-5.smt2 |   20.087s | 168.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-pipeline-fixpoint-10.smt2 |   20.088s | 98.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/sdlx-fixpoint-9.smt2 |   20.092s | 296.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-pipeline-fixpoint-4.smt2 |   20.093s | 173.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-equiv-fixpoint-10.smt2 |   20.104s | 206.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-equiv-fixpoint-7.smt2 |   20.105s | 192.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/sdlx-fixpoint-7.smt2 |   20.110s | 305.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/sdlx-fixpoint-5.smt2 |   20.120s | 593.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/sdlx-fixpoint-8.smt2 |   20.133s | 547.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/20230314-Jaroslav-Bendik-Certora/52759_b3ecd2335fd16ec2eee2_9_UFBV.smt2 |   20.133s | 619.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/sdlx-fixpoint-6.smt2 |   20.154s | 561.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/ph7/405_ph7.smt2 |   20.164s | 637.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2/gcc/108_gcc.smt2        |   20.230s | 1173.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/ph7/445_ph7.smt2 |   20.366s | 2057.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/ph7/643_ph7.smt2 |   20.542s | 2739.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/sqlite3/935_sqlite3.smt2 |   20.667s | 4864.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/oggenc/385_oggenc.smt2 |   20.737s | 4393.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/gcc/144_gcc.smt2 |   20.746s | 5263.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/ph7/731_ph7.smt2 |   20.776s | 4475.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/sqlite3/808_sqlite3.smt2 |   20.783s | 4700.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/ph7/646_ph7.smt2 |   20.798s | 5854.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/ph7/566_ph7.smt2 |   20.807s | 8353.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/sqlite3/971_sqlite3.smt2 |   20.905s | 7160.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/oggenc/369_oggenc.smt2 |   20.942s | 8224.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/gcc/095_gcc.smt2 |   20.984s | 7427.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/ph7/655_ph7.smt2 |   21.040s | 8781.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/sqlite3/783_sqlite3.smt2 |   21.074s | 7710.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/ph7/562_ph7.smt2 |   21.079s | 8339.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/ph7/617_ph7.smt2 |   21.114s | 8300.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/ph7/491_ph7.smt2 |   21.179s | 8781.0MiB| timeout | 0 |  |  |
