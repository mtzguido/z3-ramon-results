# .

* SAT 0
* UNSAT 1
* TIMEOUT 183
* UNKNOWN 0

* ERRORS 24 (unreachable:16, segfault:8)

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/UFBVLIA.tar.zst?download=1 | Source list: quantifier_benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-UFBVLIA.tar.zst-do
Runner: rise-runner-1
Z3 repo: Z3Prover/z3
Z3 commit: 30c74fccee4d195424588e28574ecaf0f9335f2c
Z3 branch: 30c74fccee4d195424588e28574ecaf0f9335f2c
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/UFBVLIA.tar.zst?download=1
Z3 commit message: Go bindings: extract CGo slice-conversion helpers to eliminate boilerplate (#9465)

* Initial plan

* simplify Go bindings: extract CGo slice conversion helpers in z3.go

Agent-Logs-Url: https://github.com/Z3Prover/z3/sessions/eb6e05d8-f45a-40fb-b61f-17d4058bccb6

Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

---------

Co-authored-by: copilot-swe-agent[bot] <198982749+Copilot@users.noreply.github.com>
Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

</pre>


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-181.smt2    |    0.187s | 28.336MiB| unsat | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-115.smt2    |    1.615s | 88.552MiB| unreachable | 114 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-099.smt2    |    1.638s | 79.304MiB| unreachable | 114 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-122.smt2    |    1.638s | 61.488MiB| unreachable | 114 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-155.smt2    |    1.753s | 83.476MiB| segfault | 139 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-071.smt2    |    2.018s | 54.296MiB| segfault | 139 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-147.smt2    |    2.167s | 98.0MiB| unreachable | 114 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-052.smt2    |    2.291s | 53.604MiB| unreachable | 114 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-120.smt2    |    2.807s | 83.952MiB| unreachable | 114 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-136.smt2    |    3.124s | 90.52MiB| unreachable | 114 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-036.smt2    |    4.032s | 52.344MiB| unreachable | 114 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-125.smt2    |    4.386s | 63.64MiB| unreachable | 114 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-138.smt2    |    4.554s | 91.28MiB| segfault | 139 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-095.smt2    |    5.082s | 62.82MiB| segfault | 139 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-174.smt2    |    5.321s | 101.0MiB| segfault | 139 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-113.smt2    |    7.167s | 96.184MiB| unreachable | 114 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-111.smt2    |    7.753s | 128.0MiB| segfault | 139 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-143.smt2    |    8.636s | 92.652MiB| segfault | 139 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-066.smt2    |    8.880s | 58.512MiB| unreachable | 114 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-154.smt2    |   10.319s | 89.492MiB| unreachable | 114 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-169.smt2    |   16.056s | 98.0MiB| segfault | 139 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-156.smt2    |   17.011s | 98.648MiB| unreachable | 114 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-133.smt2    |   17.982s | 84.684MiB| unreachable | 114 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-114.smt2    |   18.675s | 84.872MiB| unreachable | 114 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-165.smt2    |   19.466s | 107.0MiB| unreachable | 114 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-075.smt2    |   20.010s | 60.624MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-197.smt2    |   20.011s | 51.28MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-032.smt2    |   20.011s | 57.24MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-021.smt2    |   20.012s | 111.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-199.smt2    |   20.012s | 50.12MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-128.smt2    |   20.013s | 96.672MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-186.smt2    |   20.013s | 110.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-127.smt2    |   20.014s | 81.028MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-060.smt2    |   20.015s | 58.852MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-187.smt2    |   20.015s | 51.072MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-191.smt2    |   20.015s | 52.1MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-093.smt2    |   20.015s | 61.452MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-166.smt2    |   20.016s | 114.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-189.smt2    |   20.016s | 123.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-005.smt2    |   20.016s | 51.56MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-107.smt2    |   20.016s | 137.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-106.smt2    |   20.017s | 153.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-086.smt2    |   20.019s | 156.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-079.smt2    |   20.019s | 154.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-044.smt2    |   20.020s | 58.836MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-040.smt2    |   20.020s | 130.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-002.smt2    |   20.020s | 208.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-082.smt2    |   20.021s | 65.9MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-130.smt2    |   20.022s | 90.872MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-013.smt2    |   20.022s | 51.636MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-144.smt2    |   20.022s | 94.7MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-078.smt2    |   20.022s | 225.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-010.smt2    |   20.022s | 49.136MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-152.smt2    |   20.022s | 104.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-162.smt2    |   20.023s | 99.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-105.smt2    |   20.024s | 81.188MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-150.smt2    |   20.024s | 96.208MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-003.smt2    |   20.024s | 53.576MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-085.smt2    |   20.025s | 61.088MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-098.smt2    |   20.025s | 65.468MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-124.smt2    |   20.025s | 83.912MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-035.smt2    |   20.026s | 146.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-077.smt2    |   20.027s | 59.84MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-061.smt2    |   20.027s | 59.6MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-051.smt2    |   20.027s | 148.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-059.smt2    |   20.028s | 136.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-064.smt2    |   20.028s | 59.288MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-142.smt2    |   20.028s | 80.58MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-057.smt2    |   20.028s | 56.984MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-042.smt2    |   20.028s | 53.756MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-102.smt2    |   20.028s | 159.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-202.smt2    |   20.029s | 149.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-017.smt2    |   20.029s | 138.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-104.smt2    |   20.029s | 78.968MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-141.smt2    |   20.029s | 90.344MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-026.smt2    |   20.029s | 138.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-198.smt2    |   20.029s | 50.576MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-121.smt2    |   20.029s | 82.008MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-034.smt2    |   20.029s | 53.544MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-129.smt2    |   20.029s | 144.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-004.smt2    |   20.029s | 119.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-126.smt2    |   20.029s | 80.912MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-039.smt2    |   20.030s | 126.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-204.smt2    |   20.030s | 132.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-045.smt2    |   20.030s | 141.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-055.smt2    |   20.030s | 97.872MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-008.smt2    |   20.030s | 52.564MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-161.smt2    |   20.030s | 111.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-024.smt2    |   20.030s | 53.716MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-148.smt2    |   20.030s | 158.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-043.smt2    |   20.031s | 137.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-112.smt2    |   20.031s | 80.268MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-047.smt2    |   20.031s | 142.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-083.smt2    |   20.031s | 159.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-146.smt2    |   20.031s | 154.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-175.smt2    |   20.032s | 131.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-074.smt2    |   20.032s | 147.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-020.smt2    |   20.032s | 130.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-185.smt2    |   20.032s | 50.892MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-069.smt2    |   20.032s | 61.428MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-164.smt2    |   20.033s | 89.248MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-014.smt2    |   20.033s | 111.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-170.smt2    |   20.033s | 105.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-145.smt2    |   20.033s | 94.952MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-009.smt2    |   20.033s | 122.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-081.smt2    |   20.033s | 80.94MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-072.smt2    |   20.033s | 60.768MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-183.smt2    |   20.033s | 145.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-031.smt2    |   20.034s | 132.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-097.smt2    |   20.034s | 171.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-058.smt2    |   20.034s | 151.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-200.smt2    |   20.034s | 151.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-049.smt2    |   20.034s | 55.82MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-195.smt2    |   20.034s | 51.5MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-118.smt2    |   20.035s | 83.692MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-068.smt2    |   20.035s | 150.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-153.smt2    |   20.035s | 99.824MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-167.smt2    |   20.035s | 91.6MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-001.smt2    |   20.035s | 224.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-196.smt2    |   20.035s | 111.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-030.smt2    |   20.036s | 153.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-135.smt2    |   20.036s | 85.892MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-054.smt2    |   20.036s | 60.652MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-201.smt2    |   20.037s | 127.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-015.smt2    |   20.037s | 126.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-134.smt2    |   20.037s | 95.812MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-019.smt2    |   20.037s | 116.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-205.smt2    |   20.037s | 226.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-101.smt2    |   20.037s | 168.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-076.smt2    |   20.038s | 138.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-067.smt2    |   20.038s | 224.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-168.smt2    |   20.038s | 150.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-050.smt2    |   20.038s | 157.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-163.smt2    |   20.038s | 148.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-184.smt2    |   20.039s | 226.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-087.smt2    |   20.039s | 81.32MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-073.smt2    |   20.040s | 79.4MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-028.smt2    |   20.040s | 140.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-132.smt2    |   20.041s | 91.888MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-091.smt2    |   20.042s | 154.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-100.smt2    |   20.042s | 139.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-027.smt2    |   20.042s | 133.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-203.smt2    |   20.043s | 207.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-110.smt2    |   20.043s | 79.384MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-063.smt2    |   20.043s | 140.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-149.smt2    |   20.043s | 157.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-038.smt2    |   20.043s | 145.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-007.smt2    |   20.043s | 49.136MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-080.smt2    |   20.043s | 167.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-119.smt2    |   20.044s | 169.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-018.smt2    |   20.044s | 117.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-000.smt2    |   20.044s | 150.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-192.smt2    |   20.045s | 138.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-041.smt2    |   20.045s | 141.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-140.smt2    |   20.045s | 80.856MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-182.smt2    |   20.046s | 80.804MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-023.smt2    |   20.046s | 54.684MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-123.smt2    |   20.046s | 171.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-089.smt2    |   20.046s | 142.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-048.smt2    |   20.046s | 148.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-090.smt2    |   20.047s | 165.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-158.smt2    |   20.047s | 97.02MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-012.smt2    |   20.048s | 146.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-207.smt2    |   20.050s | 228.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-016.smt2    |   20.050s | 223.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-157.smt2    |   20.050s | 101.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-046.smt2    |   20.050s | 241.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-139.smt2    |   20.052s | 91.932MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-171.smt2    |   20.052s | 124.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-022.smt2    |   20.053s | 118.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-177.smt2    |   20.054s | 126.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-056.smt2    |   20.054s | 233.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-088.smt2    |   20.055s | 243.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-137.smt2    |   20.055s | 84.428MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-206.smt2    |   20.055s | 393.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-117.smt2    |   20.056s | 79.824MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-173.smt2    |   20.056s | 114.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-096.smt2    |   20.057s | 252.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-053.smt2    |   20.057s | 130.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-179.smt2    |   20.058s | 349.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-194.smt2    |   20.059s | 49.288MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-176.smt2    |   20.062s | 192.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-070.smt2    |   20.065s | 155.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-062.smt2    |   20.065s | 143.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-159.smt2    |   20.065s | 256.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-092.smt2    |   20.066s | 166.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-131.smt2    |   20.066s | 142.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-084.smt2    |   20.067s | 157.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-103.smt2    |   20.067s | 84.252MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-037.smt2    |   20.067s | 127.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-109.smt2    |   20.068s | 151.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-116.smt2    |   20.068s | 151.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-172.smt2    |   20.068s | 269.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-193.smt2    |   20.070s | 134.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-160.smt2    |   20.071s | 268.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-180.smt2    |   20.071s | 245.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-011.smt2    |   20.072s | 129.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-029.smt2    |   20.072s | 136.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-065.smt2    |   20.072s | 140.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-033.smt2    |   20.076s | 148.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-025.smt2    |   20.076s | 142.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-190.smt2    |   20.076s | 205.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-178.smt2    |   20.076s | 344.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-108.smt2    |   20.079s | 171.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-094.smt2    |   20.081s | 151.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-188.smt2    |   20.086s | 253.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-151.smt2    |   20.089s | 262.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-006.smt2    |   20.282s | 4473.0MiB| timeout | 0 |  |  |
