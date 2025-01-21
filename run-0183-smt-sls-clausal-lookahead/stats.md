# data

* SAT 26
* UNSAT 0
* TIMEOUT 160
* UNKNOWN 0

* UNSET 0

* ERROR 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-sls-clausal-lookahead
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: 22e4054674a291d83f59019273ff0b24f24295bf
Z3 branch: master
Z3 options: "-T:20 -v:2 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify sls-smt)" model_validate=true sls.arith_use_clausal_lookahead=true"
Z3 inputs: inputs/QF_NIA_MCM
Z3 commit message: add clausal lookahead to arithmetic solver as part of portfolio

have legacy qfbv-sls solver use nnf pre-processing. It relies on it for correctness of the score updates.

</pre>


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|45.smt2                                                      |    0.027s | 20.968MiB| sat | 0 |  |  |
|113.smt2                                                     |    0.055s | 23.952MiB| sat | 0 |  |  |
|107.smt2                                                     |    0.084s | 26.296MiB| sat | 0 |  |  |
|06.smt2                                                      |    0.090s | 20.124MiB| sat | 0 |  |  |
|118.smt2                                                     |    0.098s | 26.888MiB| sat | 0 |  |  |
|117.smt2                                                     |    0.115s | 26.264MiB| sat | 0 |  |  |
|109.smt2                                                     |    0.123s | 27.144MiB| sat | 0 |  |  |
|12.smt2                                                      |    0.123s | 20.892MiB| sat | 0 |  |  |
|115.smt2                                                     |    0.213s | 33.612MiB| sat | 0 |  |  |
|164.smt2                                                     |    0.331s | 47.212MiB| sat | 0 |  |  |
|170.smt2                                                     |    0.345s | 47.432MiB| sat | 0 |  |  |
|166.smt2                                                     |    0.353s | 47.44MiB| sat | 0 |  |  |
|162.smt2                                                     |    0.486s | 47.212MiB| sat | 0 |  |  |
|07.smt2                                                      |    0.795s | 23.916MiB| sat | 0 |  |  |
|10.smt2                                                      |    0.922s | 25.172MiB| sat | 0 |  |  |
|104.smt2                                                     |    1.100s | 33.916MiB| sat | 0 |  |  |
|14.smt2                                                      |    1.333s | 23.708MiB| sat | 0 |  |  |
|177.smt2                                                     |    1.817s | 146.0MiB| sat | 0 |  |  |
|43.smt2                                                      |    1.949s | 23.916MiB| sat | 0 |  |  |
|13.smt2                                                      |    2.009s | 26.376MiB| sat | 0 |  |  |
|03.smt2                                                      |    4.777s | 26.224MiB| sat | 0 |  |  |
|15.smt2                                                      |    5.080s | 24.56MiB| sat | 0 |  |  |
|33.smt2                                                      |    7.951s | 25.3MiB| sat | 0 |  |  |
|152.smt2                                                     |    9.170s | 58.056MiB| sat | 0 |  |  |
|123.smt2                                                     |   15.200s | 75.06MiB| sat | 0 |  |  |
|01.smt2                                                      |   17.305s | 28.332MiB| sat | 0 |  |  |
|126.smt2                                                     |   18.867s | 145.0MiB| timeout | 0 |  |  |
|171.smt2                                                     |   19.823s | 548.0MiB| timeout | 0 |  |  |
|92.smt2                                                      |   19.841s | 26.368MiB| timeout | 0 |  |  |
|120.smt2                                                     |   19.856s | 146.0MiB| timeout | 0 |  |  |
|69.smt2                                                      |   19.930s | 30.188MiB| timeout | 0 |  |  |
|24.smt2                                                      |   19.931s | 30.76MiB| timeout | 0 |  |  |
|20.smt2                                                      |   19.936s | 30.756MiB| timeout | 0 |  |  |
|124.smt2                                                     |   19.942s | 58.164MiB| timeout | 0 |  |  |
|100.smt2                                                     |   19.942s | 30.992MiB| timeout | 0 |  |  |
|37.smt2                                                      |   19.956s | 30.02MiB| timeout | 0 |  |  |
|146.smt2                                                     |   19.956s | 145.0MiB| timeout | 0 |  |  |
|96.smt2                                                      |   19.960s | 35.476MiB| timeout | 0 |  |  |
|39.smt2                                                      |   19.960s | 35.156MiB| timeout | 0 |  |  |
|186.smt2                                                     |   19.973s | 245.0MiB| timeout | 0 |  |  |
|02.smt2                                                      |   19.975s | 25.332MiB| timeout | 0 |  |  |
|19.smt2                                                      |   19.976s | 27.392MiB| timeout | 0 |  |  |
|130.smt2                                                     |   19.978s | 113.0MiB| timeout | 0 |  |  |
|53.smt2                                                      |   19.982s | 30.98MiB| timeout | 0 |  |  |
|134.smt2                                                     |   19.983s | 146.0MiB| timeout | 0 |  |  |
|17.smt2                                                      |   19.984s | 30.764MiB| timeout | 0 |  |  |
|119.smt2                                                     |   19.984s | 146.0MiB| timeout | 0 |  |  |
|76.smt2                                                      |   19.984s | 35.22MiB| timeout | 0 |  |  |
|27.smt2                                                      |   19.985s | 30.684MiB| timeout | 0 |  |  |
|67.smt2                                                      |   19.986s | 30.984MiB| timeout | 0 |  |  |
|157.smt2                                                     |   19.987s | 113.0MiB| timeout | 0 |  |  |
|98.smt2                                                      |   19.987s | 30.124MiB| timeout | 0 |  |  |
|151.smt2                                                     |   19.987s | 120.0MiB| timeout | 0 |  |  |
|185.smt2                                                     |   19.988s | 245.0MiB| timeout | 0 |  |  |
|89.smt2                                                      |   19.988s | 30.98MiB| timeout | 0 |  |  |
|36.smt2                                                      |   19.990s | 25.936MiB| timeout | 0 |  |  |
|112.smt2                                                     |   19.990s | 98.316MiB| timeout | 0 |  |  |
|97.smt2                                                      |   19.990s | 30.988MiB| timeout | 0 |  |  |
|78.smt2                                                      |   19.991s | 39.64MiB| timeout | 0 |  |  |
|116.smt2                                                     |   19.991s | 144.0MiB| timeout | 0 |  |  |
|48.smt2                                                      |   19.992s | 29.292MiB| timeout | 0 |  |  |
|74.smt2                                                      |   19.993s | 35.336MiB| timeout | 0 |  |  |
|138.smt2                                                     |   19.994s | 142.0MiB| timeout | 0 |  |  |
|86.smt2                                                      |   19.995s | 24.692MiB| timeout | 0 |  |  |
|70.smt2                                                      |   19.995s | 34.128MiB| timeout | 0 |  |  |
|72.smt2                                                      |   19.995s | 30.984MiB| timeout | 0 |  |  |
|50.smt2                                                      |   19.996s | 30.984MiB| timeout | 0 |  |  |
|05.smt2                                                      |   19.996s | 27.392MiB| timeout | 0 |  |  |
|103.smt2                                                     |   19.996s | 30.98MiB| timeout | 0 |  |  |
|51.smt2                                                      |   19.996s | 27.576MiB| timeout | 0 |  |  |
|22.smt2                                                      |   19.996s | 30.696MiB| timeout | 0 |  |  |
|57.smt2                                                      |   19.996s | 35.216MiB| timeout | 0 |  |  |
|49.smt2                                                      |   19.997s | 26.096MiB| timeout | 0 |  |  |
|99.smt2                                                      |   19.997s | 26.884MiB| timeout | 0 |  |  |
|40.smt2                                                      |   19.998s | 30.748MiB| timeout | 0 |  |  |
|84.smt2                                                      |   19.998s | 23.784MiB| timeout | 0 |  |  |
|32.smt2                                                      |   19.998s | 26.732MiB| timeout | 0 |  |  |
|08.smt2                                                      |   19.999s | 22.052MiB| timeout | 0 |  |  |
|42.smt2                                                      |   19.999s | 23.016MiB| timeout | 0 |  |  |
|41.smt2                                                      |   19.999s | 24.932MiB| timeout | 0 |  |  |
|11.smt2                                                      |   19.999s | 23.032MiB| timeout | 0 |  |  |
|30.smt2                                                      |   19.999s | 25.948MiB| timeout | 0 |  |  |
|77.smt2                                                      |   20.000s | 31.12MiB| timeout | 0 |  |  |
|73.smt2                                                      |   20.000s | 27.6MiB| timeout | 0 |  |  |
|64.smt2                                                      |   20.000s | 35.22MiB| timeout | 0 |  |  |
|95.smt2                                                      |   20.000s | 30.98MiB| timeout | 0 |  |  |
|82.smt2                                                      |   20.000s | 33.04MiB| timeout | 0 |  |  |
|155.smt2                                                     |   20.000s | 91.364MiB| timeout | 0 |  |  |
|83.smt2                                                      |   20.001s | 29.48MiB| timeout | 0 |  |  |
|25.smt2                                                      |   20.001s | 27.396MiB| timeout | 0 |  |  |
|85.smt2                                                      |   20.001s | 27.776MiB| timeout | 0 |  |  |
|34.smt2                                                      |   20.001s | 23.292MiB| timeout | 0 |  |  |
|94.smt2                                                      |   20.001s | 35.256MiB| timeout | 0 |  |  |
|101.smt2                                                     |   20.001s | 27.592MiB| timeout | 0 |  |  |
|79.smt2                                                      |   20.001s | 34.116MiB| timeout | 0 |  |  |
|35.smt2                                                      |   20.001s | 29.084MiB| timeout | 0 |  |  |
|58.smt2                                                      |   20.001s | 35.224MiB| timeout | 0 |  |  |
|59.smt2                                                      |   20.001s | 30.976MiB| timeout | 0 |  |  |
|68.smt2                                                      |   20.002s | 34.148MiB| timeout | 0 |  |  |
|44.smt2                                                      |   20.002s | 22.2MiB| timeout | 0 |  |  |
|63.smt2                                                      |   20.002s | 30.984MiB| timeout | 0 |  |  |
|150.smt2                                                     |   20.002s | 124.0MiB| timeout | 0 |  |  |
|31.smt2                                                      |   20.002s | 30.236MiB| timeout | 0 |  |  |
|131.smt2                                                     |   20.002s | 41.188MiB| timeout | 0 |  |  |
|21.smt2                                                      |   20.002s | 27.416MiB| timeout | 0 |  |  |
|65.smt2                                                      |   20.002s | 30.976MiB| timeout | 0 |  |  |
|91.smt2                                                      |   20.002s | 30.98MiB| timeout | 0 |  |  |
|148.smt2                                                     |   20.002s | 138.0MiB| timeout | 0 |  |  |
|23.smt2                                                      |   20.002s | 27.36MiB| timeout | 0 |  |  |
|81.smt2                                                      |   20.003s | 30.976MiB| timeout | 0 |  |  |
|56.smt2                                                      |   20.003s | 40.88MiB| timeout | 0 |  |  |
|80.smt2                                                      |   20.003s | 35.444MiB| timeout | 0 |  |  |
|184.smt2                                                     |   20.003s | 138.0MiB| timeout | 0 |  |  |
|93.smt2                                                      |   20.003s | 24.032MiB| timeout | 0 |  |  |
|61.smt2                                                      |   20.003s | 30.988MiB| timeout | 0 |  |  |
|62.smt2                                                      |   20.003s | 35.192MiB| timeout | 0 |  |  |
|26.smt2                                                      |   20.003s | 27.496MiB| timeout | 0 |  |  |
|29.smt2                                                      |   20.003s | 29.132MiB| timeout | 0 |  |  |
|16.smt2                                                      |   20.003s | 34.896MiB| timeout | 0 |  |  |
|54.smt2                                                      |   20.004s | 30.988MiB| timeout | 0 |  |  |
|106.smt2                                                     |   20.004s | 119.0MiB| timeout | 0 |  |  |
|09.smt2                                                      |   20.004s | 23.284MiB| timeout | 0 |  |  |
|110.smt2                                                     |   20.005s | 119.0MiB| timeout | 0 |  |  |
|71.smt2                                                      |   20.005s | 30.224MiB| timeout | 0 |  |  |
|143.smt2                                                     |   20.005s | 113.0MiB| timeout | 0 |  |  |
|55.smt2                                                      |   20.005s | 27.62MiB| timeout | 0 |  |  |
|114.smt2                                                     |   20.006s | 82.984MiB| timeout | 0 |  |  |
|38.smt2                                                      |   20.006s | 26.72MiB| timeout | 0 |  |  |
|88.smt2                                                      |   20.006s | 35.224MiB| timeout | 0 |  |  |
|60.smt2                                                      |   20.006s | 35.476MiB| timeout | 0 |  |  |
|125.smt2                                                     |   20.007s | 176.0MiB| timeout | 0 |  |  |
|04.smt2                                                      |   20.007s | 23.78MiB| timeout | 0 |  |  |
|47.smt2                                                      |   20.008s | 30.184MiB| timeout | 0 |  |  |
|137.smt2                                                     |   20.008s | 146.0MiB| timeout | 0 |  |  |
|28.smt2                                                      |   20.008s | 27.388MiB| timeout | 0 |  |  |
|75.smt2                                                      |   20.008s | 30.98MiB| timeout | 0 |  |  |
|87.smt2                                                      |   20.008s | 23.088MiB| timeout | 0 |  |  |
|105.smt2                                                     |   20.008s | 99.0MiB| timeout | 0 |  |  |
|144.smt2                                                     |   20.009s | 177.0MiB| timeout | 0 |  |  |
|108.smt2                                                     |   20.010s | 98.0MiB| timeout | 0 |  |  |
|156.smt2                                                     |   20.010s | 83.092MiB| timeout | 0 |  |  |
|147.smt2                                                     |   20.012s | 120.0MiB| timeout | 0 |  |  |
|127.smt2                                                     |   20.013s | 146.0MiB| timeout | 0 |  |  |
|141.smt2                                                     |   20.013s | 117.0MiB| timeout | 0 |  |  |
|129.smt2                                                     |   20.013s | 142.0MiB| timeout | 0 |  |  |
|122.smt2                                                     |   20.015s | 146.0MiB| timeout | 0 |  |  |
|145.smt2                                                     |   20.015s | 146.0MiB| timeout | 0 |  |  |
|111.smt2                                                     |   20.016s | 98.296MiB| timeout | 0 |  |  |
|46.smt2                                                      |   20.017s | 34.368MiB| timeout | 0 |  |  |
|139.smt2                                                     |   20.017s | 74.88MiB| timeout | 0 |  |  |
|153.smt2                                                     |   20.018s | 177.0MiB| timeout | 0 |  |  |
|142.smt2                                                     |   20.019s | 137.0MiB| timeout | 0 |  |  |
|165.smt2                                                     |   20.019s | 609.0MiB| timeout | 0 |  |  |
|135.smt2                                                     |   20.020s | 177.0MiB| timeout | 0 |  |  |
|128.smt2                                                     |   20.023s | 119.0MiB| timeout | 0 |  |  |
|154.smt2                                                     |   20.025s | 146.0MiB| timeout | 0 |  |  |
|136.smt2                                                     |   20.025s | 146.0MiB| timeout | 0 |  |  |
|121.smt2                                                     |   20.026s | 177.0MiB| timeout | 0 |  |  |
|161.smt2                                                     |   20.027s | 440.0MiB| timeout | 0 |  |  |
|140.smt2                                                     |   20.027s | 129.0MiB| timeout | 0 |  |  |
|132.smt2                                                     |   20.028s | 168.0MiB| timeout | 0 |  |  |
|159.smt2                                                     |   20.029s | 432.0MiB| timeout | 0 |  |  |
|149.smt2                                                     |   20.031s | 152.0MiB| timeout | 0 |  |  |
|133.smt2                                                     |   20.032s | 138.0MiB| timeout | 0 |  |  |
|167.smt2                                                     |   20.033s | 384.0MiB| timeout | 0 |  |  |
|160.smt2                                                     |   20.039s | 566.0MiB| timeout | 0 |  |  |
|169.smt2                                                     |   20.043s | 881.0MiB| timeout | 0 |  |  |
|168.smt2                                                     |   20.047s | 594.0MiB| timeout | 0 |  |  |
|163.smt2                                                     |   20.048s | 599.0MiB| timeout | 0 |  |  |
|102.smt2                                                     |   20.048s | 35.316MiB| timeout | 0 |  |  |
|158.smt2                                                     |   20.063s | 599.0MiB| timeout | 0 |  |  |
|179.smt2                                                     |   20.065s | 2258.0MiB| timeout | 0 |  |  |
|181.smt2                                                     |   20.079s | 3034.0MiB| timeout | 0 |  |  |
|172.smt2                                                     |   20.088s | 2036.0MiB| timeout | 0 |  |  |
|90.smt2                                                      |   20.089s | 35.196MiB| timeout | 0 |  |  |
|175.smt2                                                     |   20.093s | 1649.0MiB| timeout | 0 |  |  |
|173.smt2                                                     |   20.093s | 1685.0MiB| timeout | 0 |  |  |
|176.smt2                                                     |   20.105s | 2402.0MiB| timeout | 0 |  |  |
|174.smt2                                                     |   20.119s | 1649.0MiB| timeout | 0 |  |  |
|180.smt2                                                     |   20.135s | 2257.0MiB| timeout | 0 |  |  |
|183.smt2                                                     |   20.142s | 3247.0MiB| timeout | 0 |  |  |
|178.smt2                                                     |   20.174s | 2441.0MiB| timeout | 0 |  |  |
|52.smt2                                                      |   20.180s | 35.188MiB| timeout | 0 |  |  |
|182.smt2                                                     |   20.193s | 3249.0MiB| timeout | 0 |  |  |
|18.smt2                                                      |   20.345s | 30.932MiB| timeout | 0 |  |  |
|66.smt2                                                      |   20.505s | 35.22MiB| timeout | 0 |  |  |
