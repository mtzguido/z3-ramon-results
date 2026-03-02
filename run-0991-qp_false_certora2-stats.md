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
Job tag: qp_false_certora2
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: 9b30560b617f35b45d3704d99dce09c021636fca
Z3 branch: modgb
Z3 options: "-T:200 smt.arith.nl.grobner_quotient_pairs=false"
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
|auk-0161.smt2                                                |    0.034s | 19.408MiB| sat | 0 |  |  |
|auk-0179.smt2                                                |    0.039s | 20.048MiB| unsat | 0 |  |  |
|auk-0170.smt2                                                |    0.046s | 20.408MiB| unsat | 0 |  |  |
|auk-0057.smt2                                                |    0.048s | 19.744MiB| unsat | 0 |  |  |
|auk-0138.smt2                                                |    0.049s | 20.336MiB| unsat | 0 |  |  |
|auk-0046.smt2                                                |    0.049s | 19.74MiB| unsat | 0 |  |  |
|auk-0042.smt2                                                |    0.053s | 19.992MiB| sat | 0 |  |  |
|auk-0066.smt2                                                |    0.054s | 19.636MiB| sat | 0 |  |  |
|auk-0012.smt2                                                |    0.054s | 20.12MiB| unsat | 0 |  |  |
|auk-0009.smt2                                                |    0.055s | 20.196MiB| sat | 0 |  |  |
|auk-0054.smt2                                                |    0.056s | 18.956MiB| unsat | 0 |  |  |
|auk-0060.smt2                                                |    0.056s | 20.088MiB| unsat | 0 |  |  |
|auk-0040.smt2                                                |    0.056s | 20.264MiB| unsat | 0 |  |  |
|auk-0178.smt2                                                |    0.060s | 19.84MiB| sat | 0 |  |  |
|auk-0038.smt2                                                |    0.062s | 18.92MiB| unsat | 0 |  |  |
|auk-0041.smt2                                                |    0.062s | 20.256MiB| unsat | 0 |  |  |
|auk-0166.smt2                                                |    0.063s | 20.768MiB| sat | 0 |  |  |
|auk-0069.smt2                                                |    0.063s | 20.128MiB| unsat | 0 |  |  |
|auk-0160.smt2                                                |    0.064s | 20.08MiB| unsat | 0 |  |  |
|auk-0168.smt2                                                |    0.069s | 20.304MiB| sat | 0 |  |  |
|auk-0068.smt2                                                |    0.069s | 19.544MiB| unsat | 0 |  |  |
|auk-0035.smt2                                                |    0.071s | 20.228MiB| unsat | 0 |  |  |
|auk-0036.smt2                                                |    0.073s | 20.76MiB| sat | 0 |  |  |
|auk-0067.smt2                                                |    0.073s | 20.432MiB| sat | 0 |  |  |
|auk-0061.smt2                                                |    0.078s | 20.604MiB| unsat | 0 |  |  |
|auk-0031.smt2                                                |    0.083s | 20.228MiB| unsat | 0 |  |  |
|auk-0050.smt2                                                |    0.084s | 20.096MiB| unsat | 0 |  |  |
|auk-0159.smt2                                                |    0.085s | 20.508MiB| unsat | 0 |  |  |
|auk-0032.smt2                                                |    0.088s | 20.376MiB| unsat | 0 |  |  |
|auk-0034.smt2                                                |    0.088s | 20.636MiB| unsat | 0 |  |  |
|auk-0044.smt2                                                |    0.090s | 20.924MiB| unsat | 0 |  |  |
|auk-0043.smt2                                                |    0.097s | 24.164MiB| unsat | 0 |  |  |
|auk-0059.smt2                                                |    0.098s | 22.92MiB| unsat | 0 |  |  |
|auk-0028.smt2                                                |    0.099s | 22.424MiB| unsat | 0 |  |  |
|auk-0064.smt2                                                |    0.100s | 20.668MiB| sat | 0 |  |  |
|auk-0065.smt2                                                |    0.101s | 20.412MiB| unsat | 0 |  |  |
|auk-0039.smt2                                                |    0.105s | 20.532MiB| unsat | 0 |  |  |
|auk-0053.smt2                                                |    0.105s | 21.18MiB| sat | 0 |  |  |
|auk-0051.smt2                                                |    0.106s | 20.944MiB| unsat | 0 |  |  |
|auk-0139.smt2                                                |    0.112s | 21.612MiB| unsat | 0 |  |  |
|auk-0162.smt2                                                |    0.118s | 24.488MiB| sat | 0 |  |  |
|auk-0172.smt2                                                |    0.119s | 25.796MiB| sat | 0 |  |  |
|auk-0058.smt2                                                |    0.122s | 24.908MiB| sat | 0 |  |  |
|auk-0062.smt2                                                |    0.125s | 24.736MiB| unsat | 0 |  |  |
|auk-0104.smt2                                                |    0.126s | 24.172MiB| sat | 0 |  |  |
|auk-0097.smt2                                                |    0.130s | 22.856MiB| sat | 0 |  |  |
|auk-0093.smt2                                                |    0.130s | 23.844MiB| sat | 0 |  |  |
|auk-0063.smt2                                                |    0.131s | 20.928MiB| unsat | 0 |  |  |
|auk-0100.smt2                                                |    0.136s | 24.636MiB| sat | 0 |  |  |
|auk-0048.smt2                                                |    0.139s | 25.196MiB| unsat | 0 |  |  |
|auk-0052.smt2                                                |    0.142s | 24.568MiB| unsat | 0 |  |  |
|auk-0047.smt2                                                |    0.143s | 24.9MiB| unsat | 0 |  |  |
|auk-0055.smt2                                                |    0.143s | 24.908MiB| sat | 0 |  |  |
|auk-0156.smt2                                                |    0.151s | 25.3MiB| sat | 0 |  |  |
|auk-0008.smt2                                                |    0.155s | 28.176MiB| unsat | 0 |  |  |
|auk-0106.smt2                                                |    0.155s | 26.712MiB| sat | 0 |  |  |
|auk-0118.smt2                                                |    0.157s | 27.116MiB| sat | 0 |  |  |
|auk-0176.smt2                                                |    0.157s | 26.376MiB| sat | 0 |  |  |
|auk-0114.smt2                                                |    0.158s | 25.736MiB| sat | 0 |  |  |
|auk-0037.smt2                                                |    0.162s | 25.476MiB| unsat | 0 |  |  |
|auk-0174.smt2                                                |    0.162s | 25.68MiB| sat | 0 |  |  |
|auk-0163.smt2                                                |    0.163s | 25.74MiB| sat | 0 |  |  |
|auk-0029.smt2                                                |    0.163s | 25.648MiB| unsat | 0 |  |  |
|auk-0157.smt2                                                |    0.164s | 24.86MiB| sat | 0 |  |  |
|auk-0167.smt2                                                |    0.167s | 25.264MiB| sat | 0 |  |  |
|auk-0129.smt2                                                |    0.167s | 25.016MiB| sat | 0 |  |  |
|auk-0158.smt2                                                |    0.168s | 25.096MiB| sat | 0 |  |  |
|auk-0045.smt2                                                |    0.169s | 25.192MiB| unsat | 0 |  |  |
|auk-0020.smt2                                                |    0.171s | 25.7MiB| unsat | 0 |  |  |
|auk-0169.smt2                                                |    0.173s | 25.876MiB| unsat | 0 |  |  |
|auk-0026.smt2                                                |    0.173s | 25.032MiB| unsat | 0 |  |  |
|auk-0110.smt2                                                |    0.174s | 24.868MiB| sat | 0 |  |  |
|auk-0030.smt2                                                |    0.177s | 24.868MiB| unsat | 0 |  |  |
|auk-0013.smt2                                                |    0.178s | 28.196MiB| unsat | 0 |  |  |
|auk-0018.smt2                                                |    0.179s | 26.192MiB| unsat | 0 |  |  |
|auk-0014.smt2                                                |    0.183s | 28.292MiB| unsat | 0 |  |  |
|auk-0136.smt2                                                |    0.183s | 20.648MiB| sat | 0 |  |  |
|auk-0126.smt2                                                |    0.186s | 28.48MiB| sat | 0 |  |  |
|auk-0152.smt2                                                |    0.187s | 25.124MiB| sat | 0 |  |  |
|auk-0019.smt2                                                |    0.189s | 25.972MiB| unsat | 0 |  |  |
|auk-0105.smt2                                                |    0.194s | 27.28MiB| sat | 0 |  |  |
|auk-0155.smt2                                                |    0.195s | 25.152MiB| sat | 0 |  |  |
|auk-0033.smt2                                                |    0.196s | 26.08MiB| sat | 0 |  |  |
|auk-0003.smt2                                                |    0.196s | 28.212MiB| unsat | 0 |  |  |
|auk-0171.smt2                                                |    0.196s | 25.648MiB| sat | 0 |  |  |
|auk-0112.smt2                                                |    0.199s | 27.112MiB| sat | 0 |  |  |
|auk-0024.smt2                                                |    0.199s | 25.604MiB| unsat | 0 |  |  |
|auk-0021.smt2                                                |    0.202s | 23.292MiB| unsat | 0 |  |  |
|auk-0154.smt2                                                |    0.202s | 26.364MiB| sat | 0 |  |  |
|auk-0165.smt2                                                |    0.204s | 25.248MiB| sat | 0 |  |  |
|auk-0049.smt2                                                |    0.208s | 21.308MiB| unsat | 0 |  |  |
|auk-0173.smt2                                                |    0.208s | 25.684MiB| sat | 0 |  |  |
|auk-0125.smt2                                                |    0.209s | 26.928MiB| sat | 0 |  |  |
|auk-0175.smt2                                                |    0.210s | 26.456MiB| sat | 0 |  |  |
|auk-0016.smt2                                                |    0.213s | 25.12MiB| unsat | 0 |  |  |
|auk-0017.smt2                                                |    0.219s | 27.244MiB| unsat | 0 |  |  |
|auk-0108.smt2                                                |    0.220s | 28.352MiB| sat | 0 |  |  |
|auk-0124.smt2                                                |    0.220s | 27.156MiB| sat | 0 |  |  |
|auk-0164.smt2                                                |    0.224s | 25.692MiB| sat | 0 |  |  |
|auk-0111.smt2                                                |    0.227s | 28.4MiB| sat | 0 |  |  |
|auk-0102.smt2                                                |    0.231s | 27.048MiB| sat | 0 |  |  |
|auk-0150.smt2                                                |    0.232s | 25.804MiB| unsat | 0 |  |  |
|auk-0121.smt2                                                |    0.237s | 26.536MiB| sat | 0 |  |  |
|auk-0107.smt2                                                |    0.237s | 26.632MiB| sat | 0 |  |  |
|auk-0127.smt2                                                |    0.239s | 26.624MiB| sat | 0 |  |  |
|auk-0153.smt2                                                |    0.240s | 26.868MiB| sat | 0 |  |  |
|auk-0177.smt2                                                |    0.240s | 26.708MiB| sat | 0 |  |  |
|auk-0103.smt2                                                |    0.281s | 27.672MiB| sat | 0 |  |  |
|auk-0122.smt2                                                |    0.299s | 30.04MiB| sat | 0 |  |  |
|auk-0113.smt2                                                |    0.307s | 29.696MiB| sat | 0 |  |  |
|auk-0070.smt2                                                |    0.317s | 31.008MiB| sat | 0 |  |  |
|auk-0143.smt2                                                |    0.342s | 21.4MiB| unsat | 0 |  |  |
|auk-0123.smt2                                                |    0.374s | 31.472MiB| sat | 0 |  |  |
|auk-0128.smt2                                                |    0.416s | 32.612MiB| sat | 0 |  |  |
|auk-0116.smt2                                                |    0.440s | 31.548MiB| sat | 0 |  |  |
|auk-0010.smt2                                                |    0.443s | 33.136MiB| unsat | 0 |  |  |
|auk-0180.smt2                                                |    0.446s | 28.372MiB| unsat | 0 |  |  |
|auk-0005.smt2                                                |    0.455s | 33.076MiB| unsat | 0 |  |  |
|auk-0115.smt2                                                |    0.460s | 36.968MiB| sat | 0 |  |  |
|auk-0120.smt2                                                |    0.467s | 31.448MiB| sat | 0 |  |  |
|auk-0130.smt2                                                |    0.477s | 33.128MiB| sat | 0 |  |  |
|auk-0022.smt2                                                |    0.500s | 29.008MiB| sat | 0 |  |  |
|auk-0023.smt2                                                |    0.523s | 28.74MiB| unsat | 0 |  |  |
|auk-0109.smt2                                                |    0.526s | 44.612MiB| sat | 0 |  |  |
|auk-0002.smt2                                                |    0.535s | 34.808MiB| unsat | 0 |  |  |
|auk-0056.smt2                                                |    0.536s | 27.0MiB| sat | 0 |  |  |
|auk-0119.smt2                                                |    0.600s | 35.372MiB| sat | 0 |  |  |
|auk-0096.smt2                                                |    0.601s | 29.22MiB| sat | 0 |  |  |
|auk-0190.smt2                                                |    0.608s | 33.86MiB| unsat | 0 |  |  |
|auk-0117.smt2                                                |    0.657s | 31.728MiB| sat | 0 |  |  |
|auk-0072.smt2                                                |    0.705s | 32.044MiB| sat | 0 |  |  |
|auk-0134.smt2                                                |    0.713s | 32.384MiB| sat | 0 |  |  |
|auk-0078.smt2                                                |    0.770s | 32.492MiB| sat | 0 |  |  |
|auk-0133.smt2                                                |    0.823s | 42.812MiB| sat | 0 |  |  |
|auk-0006.smt2                                                |    0.828s | 36.092MiB| unsat | 0 |  |  |
|auk-0004.smt2                                                |    0.870s | 35.68MiB| unsat | 0 |  |  |
|auk-0094.smt2                                                |    0.903s | 32.592MiB| sat | 0 |  |  |
|auk-0077.smt2                                                |    1.107s | 43.2MiB| sat | 0 |  |  |
|auk-0071.smt2                                                |    1.166s | 47.308MiB| sat | 0 |  |  |
|auk-0145.smt2                                                |    1.178s | 30.18MiB| unsat | 0 |  |  |
|auk-0073.smt2                                                |    1.199s | 47.34MiB| sat | 0 |  |  |
|auk-0076.smt2                                                |    1.284s | 47.372MiB| sat | 0 |  |  |
|auk-0135.smt2                                                |    1.318s | 28.376MiB| unsat | 0 |  |  |
|auk-0025.smt2                                                |    1.333s | 31.448MiB| unsat | 0 |  |  |
|auk-0132.smt2                                                |    1.355s | 58.86MiB| sat | 0 |  |  |
|auk-0075.smt2                                                |    1.494s | 47.484MiB| sat | 0 |  |  |
|auk-0080.smt2                                                |    1.598s | 34.512MiB| sat | 0 |  |  |
|auk-0144.smt2                                                |    1.606s | 34.22MiB| unsat | 0 |  |  |
|auk-0149.smt2                                                |    1.717s | 29.052MiB| unsat | 0 |  |  |
|auk-0011.smt2                                                |    1.737s | 37.452MiB| unsat | 0 |  |  |
|auk-0131.smt2                                                |    1.747s | 92.768MiB| sat | 0 |  |  |
|auk-0146.smt2                                                |    1.776s | 29.272MiB| unsat | 0 |  |  |
|auk-0027.smt2                                                |    2.168s | 29.032MiB| unsat | 0 |  |  |
|auk-0095.smt2                                                |    2.181s | 38.708MiB| unsat | 0 |  |  |
|auk-0148.smt2                                                |    2.624s | 35.712MiB| unsat | 0 |  |  |
|auk-0083.smt2                                                |    2.830s | 99.0MiB| sat | 0 |  |  |
|auk-0082.smt2                                                |    2.869s | 99.0MiB| sat | 0 |  |  |
|auk-0101.smt2                                                |    2.871s | 33.044MiB| unsat | 0 |  |  |
|auk-0142.smt2                                                |    3.567s | 36.124MiB| unsat | 0 |  |  |
|auk-0182.smt2                                                |    4.662s | 59.1MiB| unsat | 0 |  |  |
|auk-0091.smt2                                                |    5.468s | 47.648MiB| sat | 0 |  |  |
|auk-0140.smt2                                                |   11.039s | 38.884MiB| unsat | 0 |  |  |
|auk-0074.smt2                                                |   13.840s | 31.368MiB| unsat | 0 |  |  |
|auk-0087.smt2                                                |   14.226s | 63.112MiB| unsat | 0 |  |  |
|auk-0079.smt2                                                |   14.254s | 52.416MiB| sat | 0 |  |  |
|auk-0141.smt2                                                |   14.314s | 50.916MiB| unsat | 0 |  |  |
|auk-0181.smt2                                                |   14.409s | 65.732MiB| unsat | 0 |  |  |
|auk-0084.smt2                                                |   14.546s | 59.5MiB| unsat | 0 |  |  |
|auk-0098.smt2                                                |   15.483s | 169.0MiB| unsat | 0 |  |  |
|auk-0186.smt2                                                |   16.187s | 77.252MiB| unsat | 0 |  |  |
|auk-0137.smt2                                                |   22.369s | 38.036MiB| sat | 0 |  |  |
|auk-0184.smt2                                                |   23.013s | 43.34MiB| unsat | 0 |  |  |
|auk-0183.smt2                                                |   29.044s | 79.88MiB| unsat | 0 |  |  |
|auk-0099.smt2                                                |   31.002s | 198.0MiB| unsat | 0 |  |  |
|auk-0090.smt2                                                |   32.799s | 61.744MiB| unsat | 0 |  |  |
|auk-0081.smt2                                                |   75.283s | 36.464MiB| unsat | 0 |  |  |
|auk-0191.smt2                                                |  200.011s | 39.8MiB| timeout | 0 |  |  |
|auk-0007.smt2                                                |  200.016s | 72.652MiB| timeout | 0 |  |  |
|auk-0015.smt2                                                |  200.017s | 78.668MiB| timeout | 0 |  |  |
|auk-0189.smt2                                                |  200.019s | 78.568MiB| timeout | 0 |  |  |
|auk-0088.smt2                                                |  200.020s | 111.0MiB| timeout | 0 |  |  |
|auk-0188.smt2                                                |  200.021s | 90.284MiB| timeout | 0 |  |  |
|auk-0151.smt2                                                |  200.021s | 66.828MiB| timeout | 0 |  |  |
|auk-0089.smt2                                                |  200.021s | 85.48MiB| timeout | 0 |  |  |
|auk-0092.smt2                                                |  200.022s | 124.0MiB| timeout | 0 |  |  |
|auk-0185.smt2                                                |  200.023s | 68.292MiB| timeout | 0 |  |  |
|auk-0085.smt2                                                |  200.024s | 110.0MiB| timeout | 0 |  |  |
|auk-0187.smt2                                                |  200.027s | 94.916MiB| timeout | 0 |  |  |
|auk-0001.smt2                                                |  200.027s | 46.884MiB| timeout | 0 |  |  |
|auk-0147.smt2                                                |  200.027s | 77.416MiB| timeout | 0 |  |  |
|auk-0086.smt2                                                |  200.029s | 118.0MiB| timeout | 0 |  |  |
