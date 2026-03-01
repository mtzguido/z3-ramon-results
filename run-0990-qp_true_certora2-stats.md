# .

* SAT 89
* UNSAT 89
* TIMEOUT 13
* UNKNOWN 0

* UNSET 0

* ERROR 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: quotient_pairs=true inputs/certora2
Job tag: qp_true_certora2
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: 9b30560b617f35b45d3704d99dce09c021636fca
Z3 branch: modgb
Z3 options: "-T:200 smt.arith.nl.grobner_quotient_pairs=true"
Z3 inputs: inputs/certora2
Z3 commit message: nla: add quotient reasoning for equation combinations

Extend grobner quotient propagation to combine pairs and triples
of equations sharing a nonlinear variable. When equations of the
form v*lc_i + r_i = 0 share variable v, their linear combinations
produce v*lc_comb + r_comb = 0. If |v| > |r_comb| > 0 and v does
not divide r_comb, generate a conflict lemma.

This handles mod arithmetic patterns like:
  (mod (- x y) m) = 0 AND (mod x m) != (mod y m)
where the three mod expansions produce equations sharing m as
nonlinear factor, and combining them yields m*(q2-q1+q3) = r2-r3
with |r2-r3| < m, forcing r2 = r3 (contradiction).

Co-authored-by: Copilot <223556219+Copilot@users.noreply.github.com>

</pre>


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|auk-0046.smt2                                                |    0.031s | 19.576MiB| unsat | 0 |  |  |
|auk-0060.smt2                                                |    0.039s | 20.12MiB| unsat | 0 |  |  |
|auk-0179.smt2                                                |    0.040s | 19.948MiB| unsat | 0 |  |  |
|auk-0068.smt2                                                |    0.045s | 19.488MiB| unsat | 0 |  |  |
|auk-0041.smt2                                                |    0.045s | 20.26MiB| unsat | 0 |  |  |
|auk-0057.smt2                                                |    0.046s | 20.072MiB| unsat | 0 |  |  |
|auk-0012.smt2                                                |    0.047s | 20.244MiB| unsat | 0 |  |  |
|auk-0042.smt2                                                |    0.048s | 20.016MiB| sat | 0 |  |  |
|auk-0066.smt2                                                |    0.051s | 19.748MiB| sat | 0 |  |  |
|auk-0178.smt2                                                |    0.051s | 19.612MiB| sat | 0 |  |  |
|auk-0040.smt2                                                |    0.055s | 20.288MiB| unsat | 0 |  |  |
|auk-0168.smt2                                                |    0.057s | 20.144MiB| sat | 0 |  |  |
|auk-0067.smt2                                                |    0.063s | 20.216MiB| sat | 0 |  |  |
|auk-0054.smt2                                                |    0.065s | 18.928MiB| unsat | 0 |  |  |
|auk-0161.smt2                                                |    0.065s | 19.42MiB| sat | 0 |  |  |
|auk-0009.smt2                                                |    0.066s | 20.212MiB| sat | 0 |  |  |
|auk-0050.smt2                                                |    0.068s | 20.188MiB| unsat | 0 |  |  |
|auk-0038.smt2                                                |    0.070s | 18.956MiB| unsat | 0 |  |  |
|auk-0170.smt2                                                |    0.076s | 20.616MiB| unsat | 0 |  |  |
|auk-0160.smt2                                                |    0.081s | 20.02MiB| unsat | 0 |  |  |
|auk-0028.smt2                                                |    0.084s | 22.388MiB| unsat | 0 |  |  |
|auk-0069.smt2                                                |    0.084s | 20.144MiB| unsat | 0 |  |  |
|auk-0061.smt2                                                |    0.085s | 20.468MiB| unsat | 0 |  |  |
|auk-0138.smt2                                                |    0.086s | 20.432MiB| unsat | 0 |  |  |
|auk-0166.smt2                                                |    0.089s | 20.932MiB| sat | 0 |  |  |
|auk-0031.smt2                                                |    0.089s | 20.032MiB| unsat | 0 |  |  |
|auk-0159.smt2                                                |    0.090s | 20.452MiB| unsat | 0 |  |  |
|auk-0065.smt2                                                |    0.091s | 20.548MiB| unsat | 0 |  |  |
|auk-0097.smt2                                                |    0.093s | 23.016MiB| sat | 0 |  |  |
|auk-0059.smt2                                                |    0.094s | 22.996MiB| unsat | 0 |  |  |
|auk-0053.smt2                                                |    0.097s | 21.144MiB| sat | 0 |  |  |
|auk-0032.smt2                                                |    0.098s | 20.576MiB| unsat | 0 |  |  |
|auk-0064.smt2                                                |    0.100s | 20.708MiB| sat | 0 |  |  |
|auk-0036.smt2                                                |    0.102s | 20.7MiB| sat | 0 |  |  |
|auk-0034.smt2                                                |    0.102s | 20.688MiB| unsat | 0 |  |  |
|auk-0139.smt2                                                |    0.108s | 21.48MiB| unsat | 0 |  |  |
|auk-0035.smt2                                                |    0.108s | 20.22MiB| unsat | 0 |  |  |
|auk-0039.smt2                                                |    0.109s | 20.488MiB| unsat | 0 |  |  |
|auk-0063.smt2                                                |    0.115s | 20.728MiB| unsat | 0 |  |  |
|auk-0158.smt2                                                |    0.122s | 25.064MiB| sat | 0 |  |  |
|auk-0051.smt2                                                |    0.127s | 21.012MiB| unsat | 0 |  |  |
|auk-0048.smt2                                                |    0.127s | 25.096MiB| unsat | 0 |  |  |
|auk-0058.smt2                                                |    0.127s | 24.868MiB| sat | 0 |  |  |
|auk-0052.smt2                                                |    0.129s | 24.716MiB| unsat | 0 |  |  |
|auk-0016.smt2                                                |    0.137s | 25.28MiB| unsat | 0 |  |  |
|auk-0030.smt2                                                |    0.138s | 24.78MiB| unsat | 0 |  |  |
|auk-0093.smt2                                                |    0.139s | 23.828MiB| sat | 0 |  |  |
|auk-0033.smt2                                                |    0.141s | 25.988MiB| sat | 0 |  |  |
|auk-0136.smt2                                                |    0.144s | 20.772MiB| sat | 0 |  |  |
|auk-0062.smt2                                                |    0.148s | 24.66MiB| unsat | 0 |  |  |
|auk-0026.smt2                                                |    0.148s | 24.932MiB| unsat | 0 |  |  |
|auk-0104.smt2                                                |    0.152s | 24.064MiB| sat | 0 |  |  |
|auk-0174.smt2                                                |    0.152s | 25.872MiB| sat | 0 |  |  |
|auk-0044.smt2                                                |    0.154s | 20.72MiB| unsat | 0 |  |  |
|auk-0100.smt2                                                |    0.154s | 24.684MiB| sat | 0 |  |  |
|auk-0155.smt2                                                |    0.156s | 25.284MiB| sat | 0 |  |  |
|auk-0171.smt2                                                |    0.156s | 25.64MiB| sat | 0 |  |  |
|auk-0029.smt2                                                |    0.156s | 25.636MiB| unsat | 0 |  |  |
|auk-0107.smt2                                                |    0.157s | 26.796MiB| sat | 0 |  |  |
|auk-0163.smt2                                                |    0.157s | 25.676MiB| sat | 0 |  |  |
|auk-0112.smt2                                                |    0.158s | 27.016MiB| sat | 0 |  |  |
|auk-0157.smt2                                                |    0.160s | 25.02MiB| sat | 0 |  |  |
|auk-0055.smt2                                                |    0.160s | 24.824MiB| sat | 0 |  |  |
|auk-0172.smt2                                                |    0.168s | 25.844MiB| sat | 0 |  |  |
|auk-0045.smt2                                                |    0.170s | 25.18MiB| unsat | 0 |  |  |
|auk-0014.smt2                                                |    0.171s | 28.092MiB| unsat | 0 |  |  |
|auk-0020.smt2                                                |    0.173s | 25.588MiB| unsat | 0 |  |  |
|auk-0043.smt2                                                |    0.173s | 24.268MiB| unsat | 0 |  |  |
|auk-0121.smt2                                                |    0.175s | 26.6MiB| sat | 0 |  |  |
|auk-0019.smt2                                                |    0.176s | 26.052MiB| unsat | 0 |  |  |
|auk-0154.smt2                                                |    0.177s | 26.272MiB| sat | 0 |  |  |
|auk-0102.smt2                                                |    0.179s | 27.088MiB| sat | 0 |  |  |
|auk-0165.smt2                                                |    0.179s | 25.268MiB| sat | 0 |  |  |
|auk-0162.smt2                                                |    0.179s | 24.632MiB| sat | 0 |  |  |
|auk-0176.smt2                                                |    0.182s | 26.364MiB| sat | 0 |  |  |
|auk-0110.smt2                                                |    0.184s | 24.7MiB| sat | 0 |  |  |
|auk-0164.smt2                                                |    0.185s | 25.728MiB| sat | 0 |  |  |
|auk-0150.smt2                                                |    0.189s | 25.796MiB| unsat | 0 |  |  |
|auk-0013.smt2                                                |    0.191s | 28.096MiB| unsat | 0 |  |  |
|auk-0156.smt2                                                |    0.191s | 25.188MiB| sat | 0 |  |  |
|auk-0129.smt2                                                |    0.192s | 24.956MiB| sat | 0 |  |  |
|auk-0169.smt2                                                |    0.193s | 25.944MiB| unsat | 0 |  |  |
|auk-0173.smt2                                                |    0.193s | 25.732MiB| sat | 0 |  |  |
|auk-0047.smt2                                                |    0.194s | 24.936MiB| unsat | 0 |  |  |
|auk-0152.smt2                                                |    0.196s | 25.216MiB| sat | 0 |  |  |
|auk-0037.smt2                                                |    0.200s | 25.652MiB| unsat | 0 |  |  |
|auk-0125.smt2                                                |    0.203s | 26.808MiB| sat | 0 |  |  |
|auk-0024.smt2                                                |    0.204s | 25.764MiB| unsat | 0 |  |  |
|auk-0008.smt2                                                |    0.204s | 28.244MiB| unsat | 0 |  |  |
|auk-0003.smt2                                                |    0.204s | 28.196MiB| unsat | 0 |  |  |
|auk-0175.smt2                                                |    0.204s | 26.408MiB| sat | 0 |  |  |
|auk-0167.smt2                                                |    0.207s | 25.228MiB| sat | 0 |  |  |
|auk-0126.smt2                                                |    0.209s | 28.416MiB| sat | 0 |  |  |
|auk-0114.smt2                                                |    0.211s | 25.732MiB| sat | 0 |  |  |
|auk-0177.smt2                                                |    0.211s | 26.62MiB| sat | 0 |  |  |
|auk-0118.smt2                                                |    0.212s | 27.028MiB| sat | 0 |  |  |
|auk-0106.smt2                                                |    0.220s | 26.788MiB| sat | 0 |  |  |
|auk-0108.smt2                                                |    0.226s | 28.444MiB| sat | 0 |  |  |
|auk-0018.smt2                                                |    0.229s | 26.196MiB| unsat | 0 |  |  |
|auk-0111.smt2                                                |    0.233s | 28.504MiB| sat | 0 |  |  |
|auk-0153.smt2                                                |    0.235s | 26.804MiB| sat | 0 |  |  |
|auk-0105.smt2                                                |    0.235s | 27.104MiB| sat | 0 |  |  |
|auk-0021.smt2                                                |    0.238s | 23.404MiB| unsat | 0 |  |  |
|auk-0070.smt2                                                |    0.245s | 31.032MiB| sat | 0 |  |  |
|auk-0127.smt2                                                |    0.246s | 26.608MiB| sat | 0 |  |  |
|auk-0049.smt2                                                |    0.254s | 21.296MiB| unsat | 0 |  |  |
|auk-0124.smt2                                                |    0.270s | 27.132MiB| sat | 0 |  |  |
|auk-0017.smt2                                                |    0.274s | 27.388MiB| unsat | 0 |  |  |
|auk-0122.smt2                                                |    0.274s | 30.04MiB| sat | 0 |  |  |
|auk-0103.smt2                                                |    0.297s | 27.624MiB| sat | 0 |  |  |
|auk-0128.smt2                                                |    0.325s | 32.556MiB| sat | 0 |  |  |
|auk-0180.smt2                                                |    0.327s | 28.308MiB| unsat | 0 |  |  |
|auk-0116.smt2                                                |    0.331s | 31.452MiB| sat | 0 |  |  |
|auk-0010.smt2                                                |    0.336s | 33.004MiB| unsat | 0 |  |  |
|auk-0143.smt2                                                |    0.340s | 21.288MiB| unsat | 0 |  |  |
|auk-0123.smt2                                                |    0.343s | 31.532MiB| sat | 0 |  |  |
|auk-0113.smt2                                                |    0.358s | 29.584MiB| sat | 0 |  |  |
|auk-0005.smt2                                                |    0.415s | 33.128MiB| unsat | 0 |  |  |
|auk-0130.smt2                                                |    0.437s | 33.156MiB| sat | 0 |  |  |
|auk-0056.smt2                                                |    0.439s | 27.156MiB| sat | 0 |  |  |
|auk-0022.smt2                                                |    0.451s | 29.056MiB| sat | 0 |  |  |
|auk-0120.smt2                                                |    0.452s | 31.444MiB| sat | 0 |  |  |
|auk-0002.smt2                                                |    0.518s | 36.536MiB| unsat | 0 |  |  |
|auk-0115.smt2                                                |    0.533s | 37.16MiB| sat | 0 |  |  |
|auk-0023.smt2                                                |    0.549s | 28.824MiB| unsat | 0 |  |  |
|auk-0190.smt2                                                |    0.563s | 33.844MiB| unsat | 0 |  |  |
|auk-0119.smt2                                                |    0.602s | 35.308MiB| sat | 0 |  |  |
|auk-0109.smt2                                                |    0.658s | 44.548MiB| sat | 0 |  |  |
|auk-0078.smt2                                                |    0.668s | 32.216MiB| sat | 0 |  |  |
|auk-0117.smt2                                                |    0.685s | 31.692MiB| sat | 0 |  |  |
|auk-0096.smt2                                                |    0.726s | 29.04MiB| sat | 0 |  |  |
|auk-0006.smt2                                                |    0.727s | 36.344MiB| unsat | 0 |  |  |
|auk-0134.smt2                                                |    0.740s | 32.292MiB| sat | 0 |  |  |
|auk-0133.smt2                                                |    0.834s | 42.92MiB| sat | 0 |  |  |
|auk-0094.smt2                                                |    0.881s | 32.412MiB| sat | 0 |  |  |
|auk-0072.smt2                                                |    0.927s | 32.144MiB| sat | 0 |  |  |
|auk-0145.smt2                                                |    1.109s | 30.28MiB| unsat | 0 |  |  |
|auk-0077.smt2                                                |    1.133s | 43.088MiB| sat | 0 |  |  |
|auk-0149.smt2                                                |    1.137s | 30.116MiB| unsat | 0 |  |  |
|auk-0073.smt2                                                |    1.151s | 47.144MiB| sat | 0 |  |  |
|auk-0071.smt2                                                |    1.156s | 47.24MiB| sat | 0 |  |  |
|auk-0004.smt2                                                |    1.190s | 36.36MiB| unsat | 0 |  |  |
|auk-0076.smt2                                                |    1.196s | 47.468MiB| sat | 0 |  |  |
|auk-0135.smt2                                                |    1.202s | 28.444MiB| unsat | 0 |  |  |
|auk-0075.smt2                                                |    1.330s | 47.316MiB| sat | 0 |  |  |
|auk-0132.smt2                                                |    1.361s | 59.068MiB| sat | 0 |  |  |
|auk-0080.smt2                                                |    1.594s | 34.616MiB| sat | 0 |  |  |
|auk-0144.smt2                                                |    1.648s | 34.224MiB| unsat | 0 |  |  |
|auk-0131.smt2                                                |    1.681s | 92.692MiB| sat | 0 |  |  |
|auk-0025.smt2                                                |    1.816s | 31.98MiB| unsat | 0 |  |  |
|auk-0101.smt2                                                |    1.843s | 32.52MiB| unsat | 0 |  |  |
|auk-0146.smt2                                                |    1.916s | 29.316MiB| unsat | 0 |  |  |
|auk-0095.smt2                                                |    2.052s | 38.692MiB| unsat | 0 |  |  |
|auk-0148.smt2                                                |    2.577s | 35.728MiB| unsat | 0 |  |  |
|auk-0083.smt2                                                |    2.818s | 99.0MiB| sat | 0 |  |  |
|auk-0082.smt2                                                |    2.884s | 99.0MiB| sat | 0 |  |  |
|auk-0137.smt2                                                |    3.137s | 27.608MiB| sat | 0 |  |  |
|auk-0142.smt2                                                |    3.579s | 36.208MiB| unsat | 0 |  |  |
|auk-0183.smt2                                                |    3.747s | 59.516MiB| unsat | 0 |  |  |
|auk-0182.smt2                                                |    3.780s | 59.732MiB| unsat | 0 |  |  |
|auk-0091.smt2                                                |    5.292s | 47.48MiB| sat | 0 |  |  |
|auk-0084.smt2                                                |    8.141s | 57.084MiB| unsat | 0 |  |  |
|auk-0140.smt2                                                |   11.407s | 41.132MiB| unsat | 0 |  |  |
|auk-0186.smt2                                                |   12.355s | 69.816MiB| unsat | 0 |  |  |
|auk-0074.smt2                                                |   13.370s | 31.448MiB| unsat | 0 |  |  |
|auk-0090.smt2                                                |   13.921s | 59.0MiB| unsat | 0 |  |  |
|auk-0079.smt2                                                |   14.304s | 52.416MiB| sat | 0 |  |  |
|auk-0098.smt2                                                |   15.748s | 169.0MiB| unsat | 0 |  |  |
|auk-0181.smt2                                                |   16.283s | 69.688MiB| unsat | 0 |  |  |
|auk-0027.smt2                                                |   19.211s | 31.832MiB| unsat | 0 |  |  |
|auk-0141.smt2                                                |   21.408s | 54.616MiB| unsat | 0 |  |  |
|auk-0007.smt2                                                |   23.307s | 47.472MiB| sat | 0 |  |  |
|auk-0099.smt2                                                |   32.108s | 198.0MiB| unsat | 0 |  |  |
|auk-0088.smt2                                                |   43.318s | 91.508MiB| unsat | 0 |  |  |
|auk-0085.smt2                                                |   53.130s | 93.396MiB| unsat | 0 |  |  |
|auk-0087.smt2                                                |   60.111s | 77.872MiB| unsat | 0 |  |  |
|auk-0081.smt2                                                |   75.902s | 36.508MiB| unsat | 0 |  |  |
|auk-0089.smt2                                                |  122.520s | 84.076MiB| unsat | 0 |  |  |
|auk-0151.smt2                                                |  200.015s | 63.536MiB| timeout | 0 |  |  |
|auk-0001.smt2                                                |  200.015s | 46.684MiB| timeout | 0 |  |  |
|auk-0189.smt2                                                |  200.019s | 76.836MiB| timeout | 0 |  |  |
|auk-0185.smt2                                                |  200.022s | 62.328MiB| timeout | 0 |  |  |
|auk-0015.smt2                                                |  200.023s | 62.732MiB| timeout | 0 |  |  |
|auk-0147.smt2                                                |  200.023s | 73.564MiB| timeout | 0 |  |  |
|auk-0184.smt2                                                |  200.023s | 64.392MiB| timeout | 0 |  |  |
|auk-0191.smt2                                                |  200.024s | 39.62MiB| timeout | 0 |  |  |
|auk-0187.smt2                                                |  200.026s | 96.084MiB| timeout | 0 |  |  |
|auk-0092.smt2                                                |  200.030s | 115.0MiB| timeout | 0 |  |  |
|auk-0086.smt2                                                |  200.030s | 118.0MiB| timeout | 0 |  |  |
|auk-0188.smt2                                                |  200.031s | 86.912MiB| timeout | 0 |  |  |
|auk-0011.smt2                                                |  200.032s | 70.468MiB| timeout | 0 |  |  |
