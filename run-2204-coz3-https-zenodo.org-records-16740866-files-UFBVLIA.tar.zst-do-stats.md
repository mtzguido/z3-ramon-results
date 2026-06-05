# .

* SAT 0
* UNSAT 1
* TIMEOUT 186
* UNKNOWN 0

* ERRORS 21 (unreachable:13, segfault:8)

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/UFBVLIA.tar.zst?download=1 | Source list: quantifier_benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-UFBVLIA.tar.zst-do
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: 2c7b256db21f364cf37752e91cf750bf0b570f2c
Z3 branch: 2c7b256db21f364cf37752e91cf750bf0b570f2c
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/UFBVLIA.tar.zst?download=1
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
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-181.smt2    |    0.229s | 28.844MiB| unsat | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-099.smt2    |    2.191s | 79.872MiB| unreachable | 114 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-115.smt2    |    2.570s | 89.1MiB| unreachable | 114 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-155.smt2    |    2.818s | 83.976MiB| segfault | 139 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-122.smt2    |    2.957s | 61.848MiB| unreachable | 114 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-071.smt2    |    3.218s | 54.832MiB| segfault | 139 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-052.smt2    |    3.542s | 54.312MiB| unreachable | 114 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-147.smt2    |    3.750s | 99.0MiB| unreachable | 114 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-136.smt2    |    4.685s | 91.076MiB| unreachable | 114 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-036.smt2    |    4.911s | 52.96MiB| unreachable | 114 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-120.smt2    |    4.913s | 84.42MiB| unreachable | 114 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-138.smt2    |    7.459s | 91.688MiB| segfault | 139 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-125.smt2    |    7.782s | 64.012MiB| unreachable | 114 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-095.smt2    |    7.798s | 63.468MiB| segfault | 139 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-174.smt2    |    8.736s | 102.0MiB| segfault | 139 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-113.smt2    |    9.160s | 96.9MiB| unreachable | 114 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-143.smt2    |   12.243s | 93.404MiB| segfault | 139 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-111.smt2    |   12.714s | 128.0MiB| segfault | 139 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-066.smt2    |   13.835s | 59.04MiB| unreachable | 114 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-154.smt2    |   16.672s | 89.936MiB| unreachable | 114 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-169.smt2    |   19.716s | 98.0MiB| segfault | 139 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-187.smt2    |   20.017s | 45.336MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-156.smt2    |   20.020s | 99.332MiB| unreachable | 114 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-164.smt2    |   20.021s | 88.872MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-130.smt2    |   20.022s | 87.644MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-112.smt2    |   20.023s | 80.916MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-193.smt2    |   20.029s | 134.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-027.smt2    |   20.040s | 133.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-093.smt2    |   20.048s | 59.292MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-126.smt2    |   20.048s | 81.344MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-106.smt2    |   20.050s | 145.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-097.smt2    |   20.054s | 158.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-198.smt2    |   20.057s | 48.888MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-034.smt2    |   20.058s | 50.964MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-060.smt2    |   20.059s | 57.28MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-134.smt2    |   20.059s | 95.4MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-204.smt2    |   20.060s | 132.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-068.smt2    |   20.061s | 149.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-116.smt2    |   20.062s | 148.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-042.smt2    |   20.063s | 52.144MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-150.smt2    |   20.065s | 95.636MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-145.smt2    |   20.065s | 92.916MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-019.smt2    |   20.065s | 48.104MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-045.smt2    |   20.066s | 57.608MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-103.smt2    |   20.066s | 82.908MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-016.smt2    |   20.067s | 221.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-194.smt2    |   20.068s | 47.224MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-197.smt2    |   20.069s | 50.22MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-077.smt2    |   20.070s | 58.296MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-005.smt2    |   20.071s | 49.244MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-003.smt2    |   20.072s | 53.796MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-023.smt2    |   20.072s | 49.608MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-049.smt2    |   20.073s | 52.328MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-044.smt2    |   20.074s | 55.744MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-201.smt2    |   20.075s | 127.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-191.smt2    |   20.075s | 49.124MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-075.smt2    |   20.076s | 57.272MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-100.smt2    |   20.077s | 138.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-054.smt2    |   20.077s | 57.836MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-131.smt2    |   20.077s | 138.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-033.smt2    |   20.078s | 145.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-076.smt2    |   20.079s | 139.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-010.smt2    |   20.079s | 48.728MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-176.smt2    |   20.080s | 171.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-166.smt2    |   20.081s | 113.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-022.smt2    |   20.081s | 116.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-104.smt2    |   20.082s | 62.628MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-063.smt2    |   20.082s | 138.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-029.smt2    |   20.082s | 133.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-139.smt2    |   20.082s | 91.98MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-089.smt2    |   20.082s | 139.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-168.smt2    |   20.083s | 94.076MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-127.smt2    |   20.084s | 81.404MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-158.smt2    |   20.084s | 97.448MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-087.smt2    |   20.084s | 60.98MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-133.smt2    |   20.085s | 85.188MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-171.smt2    |   20.085s | 121.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-114.smt2    |   20.086s | 85.504MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-009.smt2    |   20.087s | 48.812MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-124.smt2    |   20.087s | 79.748MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-148.smt2    |   20.087s | 98.928MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-144.smt2    |   20.088s | 89.224MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-159.smt2    |   20.088s | 108.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-041.smt2    |   20.089s | 141.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-195.smt2    |   20.089s | 49.304MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-062.smt2    |   20.089s | 142.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-141.smt2    |   20.090s | 89.708MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-153.smt2    |   20.090s | 97.18MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-098.smt2    |   20.090s | 62.748MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-024.smt2    |   20.090s | 49.484MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-057.smt2    |   20.090s | 53.256MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-105.smt2    |   20.091s | 81.788MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-039.smt2    |   20.091s | 123.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-199.smt2    |   20.091s | 48.796MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-090.smt2    |   20.091s | 162.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-128.smt2    |   20.092s | 96.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-182.smt2    |   20.092s | 79.864MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-081.smt2    |   20.092s | 80.34MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-132.smt2    |   20.092s | 90.784MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-002.smt2    |   20.092s | 208.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-064.smt2    |   20.094s | 56.504MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-170.smt2    |   20.094s | 102.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-149.smt2    |   20.094s | 150.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-021.smt2    |   20.095s | 109.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-020.smt2    |   20.095s | 128.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-205.smt2    |   20.095s | 226.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-119.smt2    |   20.096s | 163.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-186.smt2    |   20.096s | 45.808MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-175.smt2    |   20.096s | 125.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-051.smt2    |   20.096s | 144.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-073.smt2    |   20.097s | 61.356MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-061.smt2    |   20.097s | 58.016MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-129.smt2    |   20.097s | 140.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-152.smt2    |   20.097s | 103.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-083.smt2    |   20.097s | 156.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-085.smt2    |   20.098s | 61.44MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-040.smt2    |   20.098s | 130.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-015.smt2    |   20.098s | 126.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-070.smt2    |   20.098s | 145.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-047.smt2    |   20.098s | 139.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-059.smt2    |   20.099s | 135.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-030.smt2    |   20.099s | 151.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-012.smt2    |   20.099s | 145.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-080.smt2    |   20.099s | 159.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-078.smt2    |   20.100s | 151.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-110.smt2    |   20.100s | 79.904MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-178.smt2    |   20.100s | 343.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-200.smt2    |   20.101s | 143.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-035.smt2    |   20.101s | 144.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-072.smt2    |   20.102s | 60.436MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-007.smt2    |   20.102s | 47.792MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-091.smt2    |   20.103s | 148.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-067.smt2    |   20.103s | 153.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-013.smt2    |   20.104s | 49.704MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-180.smt2    |   20.104s | 245.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-190.smt2    |   20.104s | 206.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-069.smt2    |   20.104s | 61.572MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-206.smt2    |   20.104s | 235.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-086.smt2    |   20.105s | 152.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-001.smt2    |   20.105s | 213.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-117.smt2    |   20.106s | 80.124MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-188.smt2    |   20.106s | 217.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-008.smt2    |   20.106s | 51.632MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-056.smt2    |   20.106s | 227.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-079.smt2    |   20.106s | 151.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-177.smt2    |   20.107s | 126.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-185.smt2    |   20.108s | 45.296MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-055.smt2    |   20.109s | 94.648MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-037.smt2    |   20.109s | 123.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-014.smt2    |   20.111s | 112.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-046.smt2    |   20.111s | 131.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-151.smt2    |   20.112s | 262.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-173.smt2    |   20.112s | 113.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-017.smt2    |   20.113s | 135.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-162.smt2    |   20.113s | 99.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-101.smt2    |   20.114s | 165.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-123.smt2    |   20.114s | 92.784MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-082.smt2    |   20.116s | 65.512MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-142.smt2    |   20.116s | 80.404MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-157.smt2    |   20.116s | 99.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-163.smt2    |   20.117s | 105.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-102.smt2    |   20.118s | 154.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-179.smt2    |   20.120s | 145.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-107.smt2    |   20.120s | 80.064MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-167.smt2    |   20.121s | 91.852MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-161.smt2    |   20.122s | 106.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-004.smt2    |   20.122s | 115.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-196.smt2    |   20.124s | 53.124MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-031.smt2    |   20.125s | 128.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-032.smt2    |   20.126s | 56.044MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-202.smt2    |   20.127s | 134.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-026.smt2    |   20.135s | 135.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-043.smt2    |   20.137s | 135.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-172.smt2    |   20.137s | 178.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-065.smt2    |   20.137s | 138.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-092.smt2    |   20.138s | 161.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-108.smt2    |   20.138s | 166.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-184.smt2    |   20.138s | 210.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-000.smt2    |   20.138s | 145.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-192.smt2    |   20.139s | 137.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-096.smt2    |   20.140s | 232.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-146.smt2    |   20.140s | 100.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-025.smt2    |   20.141s | 142.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-121.smt2    |   20.142s | 79.104MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-118.smt2    |   20.144s | 81.076MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-165.smt2    |   20.149s | 101.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-160.smt2    |   20.149s | 253.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-084.smt2    |   20.150s | 156.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-011.smt2    |   20.151s | 129.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-135.smt2    |   20.157s | 86.384MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-140.smt2    |   20.157s | 78.688MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-058.smt2    |   20.159s | 139.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-018.smt2    |   20.160s | 115.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-088.smt2    |   20.161s | 151.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-189.smt2    |   20.162s | 121.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-137.smt2    |   20.164s | 84.16MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-074.smt2    |   20.166s | 146.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-183.smt2    |   20.166s | 137.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-038.smt2    |   20.167s | 143.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-109.smt2    |   20.168s | 148.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-094.smt2    |   20.168s | 151.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-053.smt2    |   20.168s | 127.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-050.smt2    |   20.170s | 157.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-207.smt2    |   20.173s | 206.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-048.smt2    |   20.173s | 145.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-028.smt2    |   20.174s | 140.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-203.smt2    |   20.181s | 208.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-006.smt2    |   20.302s | 2285.0MiB| timeout | 0 |  |  |
