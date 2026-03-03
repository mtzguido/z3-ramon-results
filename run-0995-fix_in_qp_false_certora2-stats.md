# .

* SAT 88
* UNSAT 88
* TIMEOUT 15
* UNKNOWN 0

* UNSET 0

* ERROR 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: quotient_pairs=false inputs/certora2
Job tag: fix_in_qp_false_certora2
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: 186ef6a0cd3f0fc8821795515994089cfc4e65db
Z3 branch: modgb
Z3 options: "-T:200 smt.arith.nl.grobner_quotient_pairs=false"
Z3 inputs: inputs/certora2
Z3 commit message: fix unsound grobner-quotient-pair lemma: skip lc with non-integral coefficients

pdd::reduce() can introduce non-integral coefficients via leading-term
division. The quotient lemma reasoning assumed lc_comb = lc_i - lc_j
was always integer-valued, which failed when lc had non-integral coefficients.
Filter out such entries when building var_to_facts.

Co-authored-by: Copilot <223556219+Copilot@users.noreply.github.com>

</pre>


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|auk-0178.smt2                                                |    0.029s | 19.844MiB| sat | 0 |  |  |
|auk-0179.smt2                                                |    0.030s | 20.1MiB| unsat | 0 |  |  |
|auk-0066.smt2                                                |    0.032s | 19.608MiB| sat | 0 |  |  |
|auk-0161.smt2                                                |    0.037s | 19.568MiB| sat | 0 |  |  |
|auk-0046.smt2                                                |    0.042s | 19.788MiB| unsat | 0 |  |  |
|auk-0038.smt2                                                |    0.046s | 18.976MiB| unsat | 0 |  |  |
|auk-0054.smt2                                                |    0.050s | 19.124MiB| unsat | 0 |  |  |
|auk-0067.smt2                                                |    0.050s | 20.256MiB| sat | 0 |  |  |
|auk-0170.smt2                                                |    0.051s | 20.66MiB| unsat | 0 |  |  |
|auk-0060.smt2                                                |    0.052s | 20.032MiB| unsat | 0 |  |  |
|auk-0138.smt2                                                |    0.052s | 20.408MiB| unsat | 0 |  |  |
|auk-0012.smt2                                                |    0.054s | 20.108MiB| unsat | 0 |  |  |
|auk-0160.smt2                                                |    0.059s | 20.116MiB| unsat | 0 |  |  |
|auk-0042.smt2                                                |    0.060s | 20.084MiB| sat | 0 |  |  |
|auk-0068.smt2                                                |    0.060s | 19.492MiB| unsat | 0 |  |  |
|auk-0166.smt2                                                |    0.062s | 20.768MiB| sat | 0 |  |  |
|auk-0041.smt2                                                |    0.062s | 20.256MiB| unsat | 0 |  |  |
|auk-0036.smt2                                                |    0.066s | 20.908MiB| sat | 0 |  |  |
|auk-0065.smt2                                                |    0.072s | 20.452MiB| unsat | 0 |  |  |
|auk-0044.smt2                                                |    0.077s | 20.824MiB| unsat | 0 |  |  |
|auk-0034.smt2                                                |    0.077s | 20.676MiB| unsat | 0 |  |  |
|auk-0069.smt2                                                |    0.078s | 20.152MiB| unsat | 0 |  |  |
|auk-0040.smt2                                                |    0.078s | 20.14MiB| unsat | 0 |  |  |
|auk-0064.smt2                                                |    0.083s | 20.84MiB| sat | 0 |  |  |
|auk-0168.smt2                                                |    0.084s | 20.228MiB| sat | 0 |  |  |
|auk-0057.smt2                                                |    0.085s | 19.936MiB| unsat | 0 |  |  |
|auk-0061.smt2                                                |    0.085s | 20.544MiB| unsat | 0 |  |  |
|auk-0039.smt2                                                |    0.086s | 20.636MiB| unsat | 0 |  |  |
|auk-0032.smt2                                                |    0.086s | 20.536MiB| unsat | 0 |  |  |
|auk-0050.smt2                                                |    0.088s | 20.18MiB| unsat | 0 |  |  |
|auk-0093.smt2                                                |    0.089s | 23.668MiB| sat | 0 |  |  |
|auk-0031.smt2                                                |    0.091s | 20.164MiB| unsat | 0 |  |  |
|auk-0009.smt2                                                |    0.092s | 20.316MiB| sat | 0 |  |  |
|auk-0053.smt2                                                |    0.094s | 21.104MiB| sat | 0 |  |  |
|auk-0159.smt2                                                |    0.095s | 20.66MiB| unsat | 0 |  |  |
|auk-0063.smt2                                                |    0.103s | 20.856MiB| unsat | 0 |  |  |
|auk-0139.smt2                                                |    0.106s | 21.452MiB| unsat | 0 |  |  |
|auk-0028.smt2                                                |    0.107s | 22.324MiB| unsat | 0 |  |  |
|auk-0051.smt2                                                |    0.109s | 20.896MiB| unsat | 0 |  |  |
|auk-0162.smt2                                                |    0.109s | 24.52MiB| sat | 0 |  |  |
|auk-0097.smt2                                                |    0.110s | 22.996MiB| sat | 0 |  |  |
|auk-0035.smt2                                                |    0.114s | 20.072MiB| unsat | 0 |  |  |
|auk-0104.smt2                                                |    0.120s | 24.096MiB| sat | 0 |  |  |
|auk-0062.smt2                                                |    0.128s | 24.632MiB| unsat | 0 |  |  |
|auk-0136.smt2                                                |    0.128s | 20.616MiB| sat | 0 |  |  |
|auk-0059.smt2                                                |    0.132s | 22.968MiB| unsat | 0 |  |  |
|auk-0033.smt2                                                |    0.134s | 25.948MiB| sat | 0 |  |  |
|auk-0043.smt2                                                |    0.135s | 24.284MiB| unsat | 0 |  |  |
|auk-0110.smt2                                                |    0.138s | 24.912MiB| sat | 0 |  |  |
|auk-0058.smt2                                                |    0.140s | 24.696MiB| sat | 0 |  |  |
|auk-0052.smt2                                                |    0.141s | 24.648MiB| unsat | 0 |  |  |
|auk-0055.smt2                                                |    0.141s | 24.768MiB| sat | 0 |  |  |
|auk-0165.smt2                                                |    0.145s | 25.336MiB| sat | 0 |  |  |
|auk-0045.smt2                                                |    0.145s | 25.048MiB| unsat | 0 |  |  |
|auk-0003.smt2                                                |    0.152s | 28.128MiB| unsat | 0 |  |  |
|auk-0048.smt2                                                |    0.153s | 25.24MiB| unsat | 0 |  |  |
|auk-0176.smt2                                                |    0.153s | 26.448MiB| sat | 0 |  |  |
|auk-0152.smt2                                                |    0.156s | 25.14MiB| sat | 0 |  |  |
|auk-0174.smt2                                                |    0.156s | 25.884MiB| sat | 0 |  |  |
|auk-0172.smt2                                                |    0.160s | 25.764MiB| sat | 0 |  |  |
|auk-0021.smt2                                                |    0.161s | 23.268MiB| unsat | 0 |  |  |
|auk-0163.smt2                                                |    0.161s | 25.728MiB| sat | 0 |  |  |
|auk-0105.smt2                                                |    0.163s | 27.268MiB| sat | 0 |  |  |
|auk-0155.smt2                                                |    0.167s | 25.284MiB| sat | 0 |  |  |
|auk-0129.smt2                                                |    0.172s | 24.992MiB| sat | 0 |  |  |
|auk-0037.smt2                                                |    0.173s | 25.42MiB| unsat | 0 |  |  |
|auk-0026.smt2                                                |    0.173s | 24.924MiB| unsat | 0 |  |  |
|auk-0167.smt2                                                |    0.176s | 25.284MiB| sat | 0 |  |  |
|auk-0127.smt2                                                |    0.177s | 26.568MiB| sat | 0 |  |  |
|auk-0100.smt2                                                |    0.178s | 24.5MiB| sat | 0 |  |  |
|auk-0018.smt2                                                |    0.180s | 26.188MiB| unsat | 0 |  |  |
|auk-0158.smt2                                                |    0.181s | 25.052MiB| sat | 0 |  |  |
|auk-0114.smt2                                                |    0.181s | 25.732MiB| sat | 0 |  |  |
|auk-0030.smt2                                                |    0.182s | 24.776MiB| unsat | 0 |  |  |
|auk-0029.smt2                                                |    0.182s | 25.56MiB| unsat | 0 |  |  |
|auk-0008.smt2                                                |    0.185s | 28.112MiB| unsat | 0 |  |  |
|auk-0173.smt2                                                |    0.185s | 25.808MiB| sat | 0 |  |  |
|auk-0164.smt2                                                |    0.186s | 25.696MiB| sat | 0 |  |  |
|auk-0047.smt2                                                |    0.187s | 24.864MiB| unsat | 0 |  |  |
|auk-0102.smt2                                                |    0.189s | 27.04MiB| sat | 0 |  |  |
|auk-0107.smt2                                                |    0.189s | 26.62MiB| sat | 0 |  |  |
|auk-0157.smt2                                                |    0.190s | 25.0MiB| sat | 0 |  |  |
|auk-0169.smt2                                                |    0.190s | 25.748MiB| unsat | 0 |  |  |
|auk-0019.smt2                                                |    0.190s | 26.096MiB| unsat | 0 |  |  |
|auk-0118.smt2                                                |    0.191s | 26.932MiB| sat | 0 |  |  |
|auk-0016.smt2                                                |    0.191s | 25.088MiB| unsat | 0 |  |  |
|auk-0049.smt2                                                |    0.196s | 21.284MiB| unsat | 0 |  |  |
|auk-0020.smt2                                                |    0.201s | 25.748MiB| unsat | 0 |  |  |
|auk-0154.smt2                                                |    0.204s | 26.432MiB| sat | 0 |  |  |
|auk-0171.smt2                                                |    0.205s | 25.624MiB| sat | 0 |  |  |
|auk-0024.smt2                                                |    0.206s | 25.696MiB| unsat | 0 |  |  |
|auk-0014.smt2                                                |    0.210s | 28.256MiB| unsat | 0 |  |  |
|auk-0150.smt2                                                |    0.210s | 25.68MiB| unsat | 0 |  |  |
|auk-0156.smt2                                                |    0.211s | 25.196MiB| sat | 0 |  |  |
|auk-0112.smt2                                                |    0.213s | 27.048MiB| sat | 0 |  |  |
|auk-0103.smt2                                                |    0.214s | 27.56MiB| sat | 0 |  |  |
|auk-0126.smt2                                                |    0.217s | 28.344MiB| sat | 0 |  |  |
|auk-0106.smt2                                                |    0.221s | 26.788MiB| sat | 0 |  |  |
|auk-0125.smt2                                                |    0.223s | 26.82MiB| sat | 0 |  |  |
|auk-0108.smt2                                                |    0.224s | 28.464MiB| sat | 0 |  |  |
|auk-0013.smt2                                                |    0.228s | 28.24MiB| unsat | 0 |  |  |
|auk-0122.smt2                                                |    0.236s | 29.94MiB| sat | 0 |  |  |
|auk-0111.smt2                                                |    0.238s | 28.356MiB| sat | 0 |  |  |
|auk-0177.smt2                                                |    0.244s | 26.748MiB| sat | 0 |  |  |
|auk-0121.smt2                                                |    0.245s | 26.576MiB| sat | 0 |  |  |
|auk-0153.smt2                                                |    0.246s | 26.864MiB| sat | 0 |  |  |
|auk-0124.smt2                                                |    0.248s | 27.02MiB| sat | 0 |  |  |
|auk-0175.smt2                                                |    0.251s | 26.432MiB| sat | 0 |  |  |
|auk-0017.smt2                                                |    0.259s | 27.4MiB| unsat | 0 |  |  |
|auk-0143.smt2                                                |    0.288s | 21.208MiB| unsat | 0 |  |  |
|auk-0070.smt2                                                |    0.322s | 30.96MiB| sat | 0 |  |  |
|auk-0113.smt2                                                |    0.328s | 29.628MiB| sat | 0 |  |  |
|auk-0123.smt2                                                |    0.384s | 31.412MiB| sat | 0 |  |  |
|auk-0180.smt2                                                |    0.386s | 28.264MiB| unsat | 0 |  |  |
|auk-0005.smt2                                                |    0.387s | 33.084MiB| unsat | 0 |  |  |
|auk-0116.smt2                                                |    0.387s | 31.64MiB| sat | 0 |  |  |
|auk-0128.smt2                                                |    0.412s | 32.472MiB| sat | 0 |  |  |
|auk-0130.smt2                                                |    0.418s | 33.008MiB| sat | 0 |  |  |
|auk-0010.smt2                                                |    0.421s | 33.128MiB| unsat | 0 |  |  |
|auk-0022.smt2                                                |    0.455s | 29.032MiB| sat | 0 |  |  |
|auk-0002.smt2                                                |    0.466s | 34.796MiB| unsat | 0 |  |  |
|auk-0056.smt2                                                |    0.478s | 26.948MiB| sat | 0 |  |  |
|auk-0120.smt2                                                |    0.521s | 31.432MiB| sat | 0 |  |  |
|auk-0115.smt2                                                |    0.535s | 37.112MiB| sat | 0 |  |  |
|auk-0109.smt2                                                |    0.560s | 44.58MiB| sat | 0 |  |  |
|auk-0023.smt2                                                |    0.570s | 28.7MiB| unsat | 0 |  |  |
|auk-0096.smt2                                                |    0.603s | 29.184MiB| sat | 0 |  |  |
|auk-0190.smt2                                                |    0.650s | 33.64MiB| unsat | 0 |  |  |
|auk-0119.smt2                                                |    0.668s | 35.204MiB| sat | 0 |  |  |
|auk-0117.smt2                                                |    0.682s | 31.508MiB| sat | 0 |  |  |
|auk-0078.smt2                                                |    0.688s | 32.236MiB| sat | 0 |  |  |
|auk-0072.smt2                                                |    0.690s | 32.204MiB| sat | 0 |  |  |
|auk-0134.smt2                                                |    0.696s | 32.34MiB| sat | 0 |  |  |
|auk-0004.smt2                                                |    0.780s | 35.784MiB| unsat | 0 |  |  |
|auk-0094.smt2                                                |    0.818s | 32.216MiB| sat | 0 |  |  |
|auk-0133.smt2                                                |    0.922s | 42.796MiB| sat | 0 |  |  |
|auk-0006.smt2                                                |    0.975s | 36.1MiB| unsat | 0 |  |  |
|auk-0025.smt2                                                |    1.096s | 31.228MiB| unsat | 0 |  |  |
|auk-0135.smt2                                                |    1.109s | 28.436MiB| unsat | 0 |  |  |
|auk-0073.smt2                                                |    1.156s | 47.224MiB| sat | 0 |  |  |
|auk-0145.smt2                                                |    1.160s | 30.192MiB| unsat | 0 |  |  |
|auk-0071.smt2                                                |    1.161s | 47.408MiB| sat | 0 |  |  |
|auk-0077.smt2                                                |    1.268s | 43.36MiB| sat | 0 |  |  |
|auk-0076.smt2                                                |    1.275s | 47.376MiB| sat | 0 |  |  |
|auk-0075.smt2                                                |    1.276s | 47.392MiB| sat | 0 |  |  |
|auk-0132.smt2                                                |    1.373s | 58.896MiB| sat | 0 |  |  |
|auk-0080.smt2                                                |    1.557s | 34.496MiB| sat | 0 |  |  |
|auk-0146.smt2                                                |    1.567s | 29.144MiB| unsat | 0 |  |  |
|auk-0144.smt2                                                |    1.569s | 34.34MiB| unsat | 0 |  |  |
|auk-0131.smt2                                                |    1.695s | 92.664MiB| sat | 0 |  |  |
|auk-0149.smt2                                                |    1.699s | 29.04MiB| unsat | 0 |  |  |
|auk-0011.smt2                                                |    1.816s | 37.176MiB| unsat | 0 |  |  |
|auk-0027.smt2                                                |    2.137s | 28.988MiB| unsat | 0 |  |  |
|auk-0095.smt2                                                |    2.137s | 38.74MiB| unsat | 0 |  |  |
|auk-0148.smt2                                                |    2.606s | 35.684MiB| unsat | 0 |  |  |
|auk-0083.smt2                                                |    2.859s | 99.0MiB| sat | 0 |  |  |
|auk-0082.smt2                                                |    2.880s | 99.0MiB| sat | 0 |  |  |
|auk-0101.smt2                                                |    2.899s | 32.98MiB| unsat | 0 |  |  |
|auk-0142.smt2                                                |    3.433s | 36.56MiB| unsat | 0 |  |  |
|auk-0182.smt2                                                |    4.830s | 59.404MiB| unsat | 0 |  |  |
|auk-0091.smt2                                                |    5.296s | 47.52MiB| sat | 0 |  |  |
|auk-0140.smt2                                                |   10.561s | 38.896MiB| unsat | 0 |  |  |
|auk-0074.smt2                                                |   13.033s | 31.624MiB| unsat | 0 |  |  |
|auk-0087.smt2                                                |   13.352s | 63.408MiB| unsat | 0 |  |  |
|auk-0141.smt2                                                |   13.838s | 51.004MiB| unsat | 0 |  |  |
|auk-0181.smt2                                                |   13.907s | 65.92MiB| unsat | 0 |  |  |
|auk-0079.smt2                                                |   14.394s | 52.576MiB| sat | 0 |  |  |
|auk-0084.smt2                                                |   15.021s | 59.564MiB| unsat | 0 |  |  |
|auk-0098.smt2                                                |   15.146s | 169.0MiB| unsat | 0 |  |  |
|auk-0186.smt2                                                |   15.918s | 76.752MiB| unsat | 0 |  |  |
|auk-0137.smt2                                                |   22.290s | 38.036MiB| sat | 0 |  |  |
|auk-0184.smt2                                                |   27.196s | 45.608MiB| unsat | 0 |  |  |
|auk-0183.smt2                                                |   28.623s | 80.0MiB| unsat | 0 |  |  |
|auk-0099.smt2                                                |   31.348s | 198.0MiB| unsat | 0 |  |  |
|auk-0090.smt2                                                |   32.934s | 61.436MiB| unsat | 0 |  |  |
|auk-0081.smt2                                                |   72.734s | 36.736MiB| unsat | 0 |  |  |
|auk-0015.smt2                                                |  200.016s | 78.544MiB| timeout | 0 |  |  |
|auk-0191.smt2                                                |  200.017s | 39.756MiB| timeout | 0 |  |  |
|auk-0189.smt2                                                |  200.017s | 78.488MiB| timeout | 0 |  |  |
|auk-0188.smt2                                                |  200.018s | 90.56MiB| timeout | 0 |  |  |
|auk-0151.smt2                                                |  200.018s | 66.612MiB| timeout | 0 |  |  |
|auk-0185.smt2                                                |  200.019s | 68.252MiB| timeout | 0 |  |  |
|auk-0085.smt2                                                |  200.021s | 111.0MiB| timeout | 0 |  |  |
|auk-0187.smt2                                                |  200.023s | 94.612MiB| timeout | 0 |  |  |
|auk-0001.smt2                                                |  200.023s | 46.84MiB| timeout | 0 |  |  |
|auk-0088.smt2                                                |  200.023s | 111.0MiB| timeout | 0 |  |  |
|auk-0086.smt2                                                |  200.023s | 119.0MiB| timeout | 0 |  |  |
|auk-0089.smt2                                                |  200.024s | 85.696MiB| timeout | 0 |  |  |
|auk-0007.smt2                                                |  200.025s | 72.804MiB| timeout | 0 |  |  |
|auk-0092.smt2                                                |  200.026s | 124.0MiB| timeout | 0 |  |  |
|auk-0147.smt2                                                |  200.062s | 77.78MiB| timeout | 0 |  |  |
