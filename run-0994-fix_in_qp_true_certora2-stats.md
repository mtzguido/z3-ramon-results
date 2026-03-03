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
Job tag: fix_in_qp_true_certora2
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: 186ef6a0cd3f0fc8821795515994089cfc4e65db
Z3 branch: modgb
Z3 options: "-T:200 smt.arith.nl.grobner_quotient_pairs=true"
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
|auk-0168.smt2                                                |    0.038s | 20.256MiB| sat | 0 |  |  |
|auk-0066.smt2                                                |    0.042s | 19.748MiB| sat | 0 |  |  |
|auk-0161.smt2                                                |    0.046s | 19.512MiB| sat | 0 |  |  |
|auk-0160.smt2                                                |    0.048s | 19.94MiB| unsat | 0 |  |  |
|auk-0170.smt2                                                |    0.049s | 20.512MiB| unsat | 0 |  |  |
|auk-0038.smt2                                                |    0.052s | 18.94MiB| unsat | 0 |  |  |
|auk-0068.smt2                                                |    0.052s | 19.544MiB| unsat | 0 |  |  |
|auk-0060.smt2                                                |    0.053s | 19.928MiB| unsat | 0 |  |  |
|auk-0138.smt2                                                |    0.053s | 20.44MiB| unsat | 0 |  |  |
|auk-0046.smt2                                                |    0.055s | 19.744MiB| unsat | 0 |  |  |
|auk-0057.smt2                                                |    0.058s | 19.88MiB| unsat | 0 |  |  |
|auk-0040.smt2                                                |    0.058s | 20.252MiB| unsat | 0 |  |  |
|auk-0054.smt2                                                |    0.059s | 19.024MiB| unsat | 0 |  |  |
|auk-0041.smt2                                                |    0.060s | 20.104MiB| unsat | 0 |  |  |
|auk-0178.smt2                                                |    0.063s | 19.836MiB| sat | 0 |  |  |
|auk-0036.smt2                                                |    0.066s | 20.892MiB| sat | 0 |  |  |
|auk-0031.smt2                                                |    0.066s | 20.248MiB| unsat | 0 |  |  |
|auk-0042.smt2                                                |    0.067s | 19.996MiB| sat | 0 |  |  |
|auk-0179.smt2                                                |    0.067s | 19.924MiB| unsat | 0 |  |  |
|auk-0012.smt2                                                |    0.068s | 20.24MiB| unsat | 0 |  |  |
|auk-0050.smt2                                                |    0.074s | 20.164MiB| unsat | 0 |  |  |
|auk-0009.smt2                                                |    0.077s | 20.372MiB| sat | 0 |  |  |
|auk-0059.smt2                                                |    0.080s | 22.924MiB| unsat | 0 |  |  |
|auk-0097.smt2                                                |    0.085s | 22.848MiB| sat | 0 |  |  |
|auk-0069.smt2                                                |    0.087s | 20.14MiB| unsat | 0 |  |  |
|auk-0032.smt2                                                |    0.088s | 20.592MiB| unsat | 0 |  |  |
|auk-0051.smt2                                                |    0.089s | 20.944MiB| unsat | 0 |  |  |
|auk-0159.smt2                                                |    0.090s | 20.504MiB| unsat | 0 |  |  |
|auk-0063.smt2                                                |    0.090s | 20.844MiB| unsat | 0 |  |  |
|auk-0067.smt2                                                |    0.092s | 20.232MiB| sat | 0 |  |  |
|auk-0034.smt2                                                |    0.094s | 20.676MiB| unsat | 0 |  |  |
|auk-0064.smt2                                                |    0.096s | 20.64MiB| sat | 0 |  |  |
|auk-0065.smt2                                                |    0.097s | 20.44MiB| unsat | 0 |  |  |
|auk-0039.smt2                                                |    0.099s | 20.636MiB| unsat | 0 |  |  |
|auk-0166.smt2                                                |    0.103s | 20.996MiB| sat | 0 |  |  |
|auk-0062.smt2                                                |    0.104s | 24.74MiB| unsat | 0 |  |  |
|auk-0061.smt2                                                |    0.104s | 20.504MiB| unsat | 0 |  |  |
|auk-0035.smt2                                                |    0.114s | 20.228MiB| unsat | 0 |  |  |
|auk-0028.smt2                                                |    0.115s | 22.524MiB| unsat | 0 |  |  |
|auk-0053.smt2                                                |    0.116s | 21.176MiB| sat | 0 |  |  |
|auk-0093.smt2                                                |    0.123s | 23.76MiB| sat | 0 |  |  |
|auk-0044.smt2                                                |    0.134s | 20.692MiB| unsat | 0 |  |  |
|auk-0172.smt2                                                |    0.135s | 25.792MiB| sat | 0 |  |  |
|auk-0136.smt2                                                |    0.140s | 20.576MiB| sat | 0 |  |  |
|auk-0052.smt2                                                |    0.145s | 24.6MiB| unsat | 0 |  |  |
|auk-0058.smt2                                                |    0.148s | 24.7MiB| sat | 0 |  |  |
|auk-0152.smt2                                                |    0.151s | 25.268MiB| sat | 0 |  |  |
|auk-0055.smt2                                                |    0.152s | 24.776MiB| sat | 0 |  |  |
|auk-0174.smt2                                                |    0.154s | 25.696MiB| sat | 0 |  |  |
|auk-0169.smt2                                                |    0.155s | 25.932MiB| unsat | 0 |  |  |
|auk-0104.smt2                                                |    0.155s | 24.084MiB| sat | 0 |  |  |
|auk-0167.smt2                                                |    0.157s | 25.284MiB| sat | 0 |  |  |
|auk-0176.smt2                                                |    0.157s | 26.392MiB| sat | 0 |  |  |
|auk-0163.smt2                                                |    0.159s | 25.736MiB| sat | 0 |  |  |
|auk-0030.smt2                                                |    0.159s | 24.816MiB| unsat | 0 |  |  |
|auk-0164.smt2                                                |    0.161s | 25.588MiB| sat | 0 |  |  |
|auk-0157.smt2                                                |    0.162s | 25.024MiB| sat | 0 |  |  |
|auk-0047.smt2                                                |    0.163s | 24.836MiB| unsat | 0 |  |  |
|auk-0139.smt2                                                |    0.163s | 21.508MiB| unsat | 0 |  |  |
|auk-0162.smt2                                                |    0.163s | 24.552MiB| sat | 0 |  |  |
|auk-0024.smt2                                                |    0.165s | 25.712MiB| unsat | 0 |  |  |
|auk-0043.smt2                                                |    0.166s | 24.156MiB| unsat | 0 |  |  |
|auk-0100.smt2                                                |    0.168s | 24.516MiB| sat | 0 |  |  |
|auk-0110.smt2                                                |    0.169s | 24.908MiB| sat | 0 |  |  |
|auk-0129.smt2                                                |    0.172s | 25.0MiB| sat | 0 |  |  |
|auk-0019.smt2                                                |    0.174s | 26.16MiB| unsat | 0 |  |  |
|auk-0045.smt2                                                |    0.174s | 25.184MiB| unsat | 0 |  |  |
|auk-0154.smt2                                                |    0.175s | 26.424MiB| sat | 0 |  |  |
|auk-0033.smt2                                                |    0.178s | 25.912MiB| sat | 0 |  |  |
|auk-0111.smt2                                                |    0.178s | 28.44MiB| sat | 0 |  |  |
|auk-0127.smt2                                                |    0.179s | 26.628MiB| sat | 0 |  |  |
|auk-0049.smt2                                                |    0.179s | 21.248MiB| unsat | 0 |  |  |
|auk-0158.smt2                                                |    0.181s | 25.2MiB| sat | 0 |  |  |
|auk-0150.smt2                                                |    0.181s | 25.704MiB| unsat | 0 |  |  |
|auk-0171.smt2                                                |    0.182s | 25.668MiB| sat | 0 |  |  |
|auk-0048.smt2                                                |    0.185s | 25.248MiB| unsat | 0 |  |  |
|auk-0102.smt2                                                |    0.186s | 27.144MiB| sat | 0 |  |  |
|auk-0118.smt2                                                |    0.186s | 27.076MiB| sat | 0 |  |  |
|auk-0114.smt2                                                |    0.186s | 25.736MiB| sat | 0 |  |  |
|auk-0014.smt2                                                |    0.189s | 28.284MiB| unsat | 0 |  |  |
|auk-0021.smt2                                                |    0.190s | 23.384MiB| unsat | 0 |  |  |
|auk-0026.smt2                                                |    0.190s | 25.148MiB| unsat | 0 |  |  |
|auk-0165.smt2                                                |    0.193s | 25.252MiB| sat | 0 |  |  |
|auk-0029.smt2                                                |    0.193s | 25.656MiB| unsat | 0 |  |  |
|auk-0003.smt2                                                |    0.195s | 28.116MiB| unsat | 0 |  |  |
|auk-0155.smt2                                                |    0.196s | 25.228MiB| sat | 0 |  |  |
|auk-0156.smt2                                                |    0.197s | 25.26MiB| sat | 0 |  |  |
|auk-0126.smt2                                                |    0.198s | 28.432MiB| sat | 0 |  |  |
|auk-0008.smt2                                                |    0.199s | 28.232MiB| unsat | 0 |  |  |
|auk-0121.smt2                                                |    0.206s | 26.532MiB| sat | 0 |  |  |
|auk-0106.smt2                                                |    0.208s | 26.792MiB| sat | 0 |  |  |
|auk-0122.smt2                                                |    0.210s | 30.104MiB| sat | 0 |  |  |
|auk-0107.smt2                                                |    0.210s | 26.752MiB| sat | 0 |  |  |
|auk-0173.smt2                                                |    0.210s | 25.812MiB| sat | 0 |  |  |
|auk-0037.smt2                                                |    0.211s | 25.424MiB| unsat | 0 |  |  |
|auk-0175.smt2                                                |    0.211s | 26.404MiB| sat | 0 |  |  |
|auk-0016.smt2                                                |    0.213s | 25.212MiB| unsat | 0 |  |  |
|auk-0013.smt2                                                |    0.214s | 28.236MiB| unsat | 0 |  |  |
|auk-0020.smt2                                                |    0.215s | 25.796MiB| unsat | 0 |  |  |
|auk-0108.smt2                                                |    0.216s | 28.44MiB| sat | 0 |  |  |
|auk-0125.smt2                                                |    0.218s | 26.824MiB| sat | 0 |  |  |
|auk-0105.smt2                                                |    0.225s | 27.064MiB| sat | 0 |  |  |
|auk-0124.smt2                                                |    0.229s | 27.232MiB| sat | 0 |  |  |
|auk-0018.smt2                                                |    0.229s | 26.212MiB| unsat | 0 |  |  |
|auk-0112.smt2                                                |    0.240s | 27.156MiB| sat | 0 |  |  |
|auk-0153.smt2                                                |    0.261s | 26.836MiB| sat | 0 |  |  |
|auk-0103.smt2                                                |    0.263s | 27.556MiB| sat | 0 |  |  |
|auk-0017.smt2                                                |    0.269s | 27.196MiB| unsat | 0 |  |  |
|auk-0177.smt2                                                |    0.281s | 26.78MiB| sat | 0 |  |  |
|auk-0070.smt2                                                |    0.300s | 31.144MiB| sat | 0 |  |  |
|auk-0113.smt2                                                |    0.303s | 29.692MiB| sat | 0 |  |  |
|auk-0143.smt2                                                |    0.335s | 21.304MiB| unsat | 0 |  |  |
|auk-0010.smt2                                                |    0.336s | 32.964MiB| unsat | 0 |  |  |
|auk-0123.smt2                                                |    0.345s | 31.536MiB| sat | 0 |  |  |
|auk-0128.smt2                                                |    0.380s | 32.576MiB| sat | 0 |  |  |
|auk-0116.smt2                                                |    0.404s | 31.464MiB| sat | 0 |  |  |
|auk-0130.smt2                                                |    0.434s | 33.24MiB| sat | 0 |  |  |
|auk-0180.smt2                                                |    0.438s | 28.264MiB| unsat | 0 |  |  |
|auk-0002.smt2                                                |    0.448s | 34.872MiB| unsat | 0 |  |  |
|auk-0056.smt2                                                |    0.448s | 26.98MiB| sat | 0 |  |  |
|auk-0115.smt2                                                |    0.491s | 36.964MiB| sat | 0 |  |  |
|auk-0005.smt2                                                |    0.534s | 33.244MiB| unsat | 0 |  |  |
|auk-0022.smt2                                                |    0.550s | 29.168MiB| sat | 0 |  |  |
|auk-0109.smt2                                                |    0.556s | 44.428MiB| sat | 0 |  |  |
|auk-0190.smt2                                                |    0.560s | 33.664MiB| unsat | 0 |  |  |
|auk-0120.smt2                                                |    0.567s | 31.472MiB| sat | 0 |  |  |
|auk-0023.smt2                                                |    0.576s | 28.692MiB| unsat | 0 |  |  |
|auk-0078.smt2                                                |    0.653s | 32.236MiB| sat | 0 |  |  |
|auk-0117.smt2                                                |    0.697s | 31.664MiB| sat | 0 |  |  |
|auk-0119.smt2                                                |    0.726s | 35.3MiB| sat | 0 |  |  |
|auk-0134.smt2                                                |    0.750s | 32.288MiB| sat | 0 |  |  |
|auk-0072.smt2                                                |    0.780s | 32.068MiB| sat | 0 |  |  |
|auk-0096.smt2                                                |    0.783s | 29.172MiB| sat | 0 |  |  |
|auk-0133.smt2                                                |    0.823s | 43.02MiB| sat | 0 |  |  |
|auk-0149.smt2                                                |    0.900s | 30.06MiB| unsat | 0 |  |  |
|auk-0006.smt2                                                |    0.911s | 36.54MiB| unsat | 0 |  |  |
|auk-0094.smt2                                                |    0.976s | 32.536MiB| sat | 0 |  |  |
|auk-0004.smt2                                                |    0.994s | 35.66MiB| unsat | 0 |  |  |
|auk-0077.smt2                                                |    1.101s | 43.052MiB| sat | 0 |  |  |
|auk-0145.smt2                                                |    1.120s | 30.192MiB| unsat | 0 |  |  |
|auk-0135.smt2                                                |    1.151s | 28.464MiB| unsat | 0 |  |  |
|auk-0071.smt2                                                |    1.160s | 47.304MiB| sat | 0 |  |  |
|auk-0073.smt2                                                |    1.174s | 47.12MiB| sat | 0 |  |  |
|auk-0076.smt2                                                |    1.271s | 47.444MiB| sat | 0 |  |  |
|auk-0132.smt2                                                |    1.350s | 59.076MiB| sat | 0 |  |  |
|auk-0075.smt2                                                |    1.474s | 47.416MiB| sat | 0 |  |  |
|auk-0144.smt2                                                |    1.569s | 34.272MiB| unsat | 0 |  |  |
|auk-0080.smt2                                                |    1.594s | 34.544MiB| sat | 0 |  |  |
|auk-0025.smt2                                                |    1.640s | 31.78MiB| unsat | 0 |  |  |
|auk-0131.smt2                                                |    1.733s | 92.82MiB| sat | 0 |  |  |
|auk-0101.smt2                                                |    1.753s | 32.6MiB| unsat | 0 |  |  |
|auk-0146.smt2                                                |    1.967s | 29.2MiB| unsat | 0 |  |  |
|auk-0095.smt2                                                |    2.079s | 38.668MiB| unsat | 0 |  |  |
|auk-0027.smt2                                                |    2.225s | 29.156MiB| unsat | 0 |  |  |
|auk-0007.smt2                                                |    2.379s | 38.016MiB| sat | 0 |  |  |
|auk-0148.smt2                                                |    2.530s | 35.688MiB| unsat | 0 |  |  |
|auk-0083.smt2                                                |    2.825s | 99.0MiB| sat | 0 |  |  |
|auk-0082.smt2                                                |    2.870s | 99.0MiB| sat | 0 |  |  |
|auk-0142.smt2                                                |    3.361s | 36.176MiB| unsat | 0 |  |  |
|auk-0183.smt2                                                |    3.383s | 59.124MiB| unsat | 0 |  |  |
|auk-0182.smt2                                                |    3.778s | 59.784MiB| unsat | 0 |  |  |
|auk-0091.smt2                                                |    5.547s | 47.52MiB| sat | 0 |  |  |
|auk-0084.smt2                                                |    9.849s | 57.268MiB| unsat | 0 |  |  |
|auk-0140.smt2                                                |   10.474s | 38.864MiB| unsat | 0 |  |  |
|auk-0141.smt2                                                |   10.612s | 48.372MiB| unsat | 0 |  |  |
|auk-0181.smt2                                                |   10.843s | 67.524MiB| unsat | 0 |  |  |
|auk-0186.smt2                                                |   11.514s | 69.504MiB| unsat | 0 |  |  |
|auk-0074.smt2                                                |   13.560s | 31.336MiB| unsat | 0 |  |  |
|auk-0090.smt2                                                |   13.592s | 59.144MiB| unsat | 0 |  |  |
|auk-0079.smt2                                                |   14.178s | 52.58MiB| sat | 0 |  |  |
|auk-0098.smt2                                                |   14.966s | 169.0MiB| unsat | 0 |  |  |
|auk-0089.smt2                                                |   30.347s | 69.4MiB| unsat | 0 |  |  |
|auk-0099.smt2                                                |   31.425s | 198.0MiB| unsat | 0 |  |  |
|auk-0088.smt2                                                |   33.426s | 92.724MiB| unsat | 0 |  |  |
|auk-0137.smt2                                                |   35.198s | 43.112MiB| sat | 0 |  |  |
|auk-0184.smt2                                                |   42.855s | 50.02MiB| unsat | 0 |  |  |
|auk-0081.smt2                                                |   73.859s | 36.472MiB| unsat | 0 |  |  |
|auk-0087.smt2                                                |  104.517s | 84.236MiB| unsat | 0 |  |  |
|auk-0191.smt2                                                |  200.012s | 39.736MiB| timeout | 0 |  |  |
|auk-0015.smt2                                                |  200.018s | 86.472MiB| timeout | 0 |  |  |
|auk-0189.smt2                                                |  200.018s | 79.492MiB| timeout | 0 |  |  |
|auk-0185.smt2                                                |  200.020s | 63.54MiB| timeout | 0 |  |  |
|auk-0085.smt2                                                |  200.020s | 103.0MiB| timeout | 0 |  |  |
|auk-0147.smt2                                                |  200.020s | 71.76MiB| timeout | 0 |  |  |
|auk-0011.smt2                                                |  200.022s | 74.644MiB| timeout | 0 |  |  |
|auk-0092.smt2                                                |  200.023s | 113.0MiB| timeout | 0 |  |  |
|auk-0001.smt2                                                |  200.023s | 46.764MiB| timeout | 0 |  |  |
|auk-0187.smt2                                                |  200.025s | 96.064MiB| timeout | 0 |  |  |
|auk-0151.smt2                                                |  200.025s | 59.812MiB| timeout | 0 |  |  |
|auk-0086.smt2                                                |  200.025s | 118.0MiB| timeout | 0 |  |  |
|auk-0188.smt2                                                |  200.068s | 565.0MiB| timeout | 0 |  |  |
