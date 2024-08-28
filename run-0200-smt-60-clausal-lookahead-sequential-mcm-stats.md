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
Job tag: smt-60-clausal-lookahead-sequential-mcm
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: ce615ee116aefdd08e12c5dc7e63ba7c69b2315e
Z3 branch: master
Z3 options: "-T:60 -v:2 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify smt)" smt.sls.enable=true smt.sls.parallel=false model_validate=true sls.arith_use_clausal_lookahead=true"
Z3 inputs: inputs/QF_NIA_MCM
Z3 commit message: avoid repeated clauses during scoring function

</pre>


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|12.smt2                                                      |    0.109s | 57.424MiB| sat | 0 |  |  |
|113.smt2                                                     |    0.121s | 61.04MiB| sat | 0 |  |  |
|118.smt2                                                     |    0.174s | 64.492MiB| sat | 0 |  |  |
|45.smt2                                                      |    0.319s | 60.628MiB| sat | 0 |  |  |
|06.smt2                                                      |    0.320s | 58.368MiB| sat | 0 |  |  |
|33.smt2                                                      |    0.439s | 65.696MiB| sat | 0 |  |  |
|170.smt2                                                     |    0.444s | 76.924MiB| sat | 0 |  |  |
|14.smt2                                                      |    0.521s | 62.932MiB| sat | 0 |  |  |
|117.smt2                                                     |    0.538s | 68.928MiB| sat | 0 |  |  |
|166.smt2                                                     |    0.594s | 77.832MiB| sat | 0 |  |  |
|109.smt2                                                     |    0.598s | 67.1MiB| sat | 0 |  |  |
|15.smt2                                                      |    0.604s | 63.348MiB| sat | 0 |  |  |
|07.smt2                                                      |    0.716s | 64.74MiB| sat | 0 |  |  |
|13.smt2                                                      |    0.856s | 66.192MiB| sat | 0 |  |  |
|115.smt2                                                     |    1.397s | 76.264MiB| sat | 0 |  |  |
|43.smt2                                                      |    1.634s | 64.24MiB| sat | 0 |  |  |
|107.smt2                                                     |    1.990s | 75.236MiB| sat | 0 |  |  |
|104.smt2                                                     |    2.236s | 76.068MiB| sat | 0 |  |  |
|162.smt2                                                     |    2.772s | 93.648MiB| sat | 0 |  |  |
|03.smt2                                                      |    2.828s | 68.848MiB| sat | 0 |  |  |
|164.smt2                                                     |    3.206s | 100.0MiB| sat | 0 |  |  |
|10.smt2                                                      |    5.073s | 70.792MiB| sat | 0 |  |  |
|152.smt2                                                     |    5.912s | 90.364MiB| sat | 0 |  |  |
|112.smt2                                                     |    8.260s | 98.0MiB| sat | 0 |  |  |
|123.smt2                                                     |    8.306s | 98.648MiB| sat | 0 |  |  |
|177.smt2                                                     |    9.756s | 146.0MiB| sat | 0 |  |  |
|44.smt2                                                      |   59.413s | 109.0MiB| timeout | 0 |  |  |
|46.smt2                                                      |   59.632s | 163.0MiB| timeout | 0 |  |  |
|111.smt2                                                     |   59.645s | 230.0MiB| timeout | 0 |  |  |
|92.smt2                                                      |   59.688s | 133.0MiB| timeout | 0 |  |  |
|186.smt2                                                     |   59.770s | 1078.0MiB| timeout | 0 |  |  |
|42.smt2                                                      |   59.781s | 242.0MiB| timeout | 0 |  |  |
|38.smt2                                                      |   59.790s | 194.0MiB| timeout | 0 |  |  |
|69.smt2                                                      |   59.796s | 178.0MiB| timeout | 0 |  |  |
|119.smt2                                                     |   59.817s | 223.0MiB| timeout | 0 |  |  |
|140.smt2                                                     |   59.840s | 192.0MiB| timeout | 0 |  |  |
|120.smt2                                                     |   59.844s | 192.0MiB| timeout | 0 |  |  |
|40.smt2                                                      |   59.851s | 187.0MiB| timeout | 0 |  |  |
|133.smt2                                                     |   59.852s | 183.0MiB| timeout | 0 |  |  |
|28.smt2                                                      |   59.862s | 159.0MiB| timeout | 0 |  |  |
|90.smt2                                                      |   59.867s | 185.0MiB| timeout | 0 |  |  |
|80.smt2                                                      |   59.872s | 177.0MiB| timeout | 0 |  |  |
|54.smt2                                                      |   59.875s | 181.0MiB| timeout | 0 |  |  |
|58.smt2                                                      |   59.882s | 185.0MiB| timeout | 0 |  |  |
|63.smt2                                                      |   59.892s | 187.0MiB| timeout | 0 |  |  |
|99.smt2                                                      |   59.895s | 195.0MiB| timeout | 0 |  |  |
|131.smt2                                                     |   59.897s | 128.0MiB| timeout | 0 |  |  |
|149.smt2                                                     |   59.899s | 204.0MiB| timeout | 0 |  |  |
|83.smt2                                                      |   59.913s | 166.0MiB| timeout | 0 |  |  |
|02.smt2                                                      |   59.916s | 158.0MiB| timeout | 0 |  |  |
|52.smt2                                                      |   59.927s | 178.0MiB| timeout | 0 |  |  |
|81.smt2                                                      |   59.930s | 180.0MiB| timeout | 0 |  |  |
|71.smt2                                                      |   59.939s | 175.0MiB| timeout | 0 |  |  |
|156.smt2                                                     |   59.939s | 151.0MiB| timeout | 0 |  |  |
|76.smt2                                                      |   59.943s | 182.0MiB| timeout | 0 |  |  |
|77.smt2                                                      |   59.946s | 187.0MiB| timeout | 0 |  |  |
|134.smt2                                                     |   59.948s | 228.0MiB| timeout | 0 |  |  |
|138.smt2                                                     |   59.949s | 209.0MiB| timeout | 0 |  |  |
|108.smt2                                                     |   59.949s | 226.0MiB| timeout | 0 |  |  |
|129.smt2                                                     |   59.952s | 230.0MiB| timeout | 0 |  |  |
|27.smt2                                                      |   59.960s | 180.0MiB| timeout | 0 |  |  |
|32.smt2                                                      |   59.962s | 181.0MiB| timeout | 0 |  |  |
|75.smt2                                                      |   59.962s | 177.0MiB| timeout | 0 |  |  |
|36.smt2                                                      |   59.963s | 177.0MiB| timeout | 0 |  |  |
|157.smt2                                                     |   59.966s | 205.0MiB| timeout | 0 |  |  |
|178.smt2                                                     |   59.966s | 471.0MiB| timeout | 0 |  |  |
|150.smt2                                                     |   59.966s | 180.0MiB| timeout | 0 |  |  |
|62.smt2                                                      |   59.967s | 183.0MiB| timeout | 0 |  |  |
|121.smt2                                                     |   59.968s | 216.0MiB| timeout | 0 |  |  |
|100.smt2                                                     |   59.968s | 195.0MiB| timeout | 0 |  |  |
|165.smt2                                                     |   59.968s | 309.0MiB| timeout | 0 |  |  |
|09.smt2                                                      |   59.970s | 139.0MiB| timeout | 0 |  |  |
|11.smt2                                                      |   59.970s | 120.0MiB| timeout | 0 |  |  |
|26.smt2                                                      |   59.971s | 186.0MiB| timeout | 0 |  |  |
|50.smt2                                                      |   59.972s | 180.0MiB| timeout | 0 |  |  |
|55.smt2                                                      |   59.972s | 222.0MiB| timeout | 0 |  |  |
|78.smt2                                                      |   59.974s | 189.0MiB| timeout | 0 |  |  |
|86.smt2                                                      |   59.974s | 142.0MiB| timeout | 0 |  |  |
|72.smt2                                                      |   59.975s | 178.0MiB| timeout | 0 |  |  |
|64.smt2                                                      |   59.976s | 176.0MiB| timeout | 0 |  |  |
|70.smt2                                                      |   59.979s | 171.0MiB| timeout | 0 |  |  |
|24.smt2                                                      |   59.980s | 163.0MiB| timeout | 0 |  |  |
|125.smt2                                                     |   59.980s | 233.0MiB| timeout | 0 |  |  |
|91.smt2                                                      |   59.981s | 191.0MiB| timeout | 0 |  |  |
|169.smt2                                                     |   59.981s | 270.0MiB| timeout | 0 |  |  |
|146.smt2                                                     |   59.982s | 225.0MiB| timeout | 0 |  |  |
|136.smt2                                                     |   59.983s | 212.0MiB| timeout | 0 |  |  |
|57.smt2                                                      |   59.984s | 174.0MiB| timeout | 0 |  |  |
|68.smt2                                                      |   59.985s | 168.0MiB| timeout | 0 |  |  |
|87.smt2                                                      |   59.985s | 122.0MiB| timeout | 0 |  |  |
|174.smt2                                                     |   59.985s | 332.0MiB| timeout | 0 |  |  |
|65.smt2                                                      |   59.988s | 194.0MiB| timeout | 0 |  |  |
|30.smt2                                                      |   59.988s | 179.0MiB| timeout | 0 |  |  |
|147.smt2                                                     |   59.989s | 220.0MiB| timeout | 0 |  |  |
|21.smt2                                                      |   59.990s | 204.0MiB| timeout | 0 |  |  |
|08.smt2                                                      |   59.991s | 106.0MiB| timeout | 0 |  |  |
|79.smt2                                                      |   59.992s | 167.0MiB| timeout | 0 |  |  |
|148.smt2                                                     |   59.993s | 201.0MiB| timeout | 0 |  |  |
|182.smt2                                                     |   59.993s | 730.0MiB| timeout | 0 |  |  |
|124.smt2                                                     |   59.994s | 142.0MiB| timeout | 0 |  |  |
|151.smt2                                                     |   59.994s | 194.0MiB| timeout | 0 |  |  |
|102.smt2                                                     |   59.994s | 188.0MiB| timeout | 0 |  |  |
|04.smt2                                                      |   59.994s | 131.0MiB| timeout | 0 |  |  |
|56.smt2                                                      |   59.995s | 175.0MiB| timeout | 0 |  |  |
|173.smt2                                                     |   59.995s | 372.0MiB| timeout | 0 |  |  |
|89.smt2                                                      |   59.995s | 174.0MiB| timeout | 0 |  |  |
|19.smt2                                                      |   59.998s | 228.0MiB| timeout | 0 |  |  |
|18.smt2                                                      |   59.998s | 196.0MiB| timeout | 0 |  |  |
|176.smt2                                                     |   59.999s | 359.0MiB| timeout | 0 |  |  |
|137.smt2                                                     |   60.000s | 219.0MiB| timeout | 0 |  |  |
|143.smt2                                                     |   60.000s | 214.0MiB| timeout | 0 |  |  |
|116.smt2                                                     |   60.001s | 201.0MiB| timeout | 0 |  |  |
|66.smt2                                                      |   60.002s | 184.0MiB| timeout | 0 |  |  |
|29.smt2                                                      |   60.002s | 151.0MiB| timeout | 0 |  |  |
|132.smt2                                                     |   60.004s | 221.0MiB| timeout | 0 |  |  |
|59.smt2                                                      |   60.004s | 191.0MiB| timeout | 0 |  |  |
|16.smt2                                                      |   60.004s | 169.0MiB| timeout | 0 |  |  |
|163.smt2                                                     |   60.005s | 273.0MiB| timeout | 0 |  |  |
|82.smt2                                                      |   60.005s | 162.0MiB| timeout | 0 |  |  |
|48.smt2                                                      |   60.006s | 164.0MiB| timeout | 0 |  |  |
|106.smt2                                                     |   60.006s | 213.0MiB| timeout | 0 |  |  |
|101.smt2                                                     |   60.007s | 205.0MiB| timeout | 0 |  |  |
|180.smt2                                                     |   60.007s | 365.0MiB| timeout | 0 |  |  |
|175.smt2                                                     |   60.009s | 329.0MiB| timeout | 0 |  |  |
|93.smt2                                                      |   60.009s | 124.0MiB| timeout | 0 |  |  |
|155.smt2                                                     |   60.009s | 173.0MiB| timeout | 0 |  |  |
|110.smt2                                                     |   60.010s | 225.0MiB| timeout | 0 |  |  |
|88.smt2                                                      |   60.010s | 196.0MiB| timeout | 0 |  |  |
|130.smt2                                                     |   60.011s | 198.0MiB| timeout | 0 |  |  |
|47.smt2                                                      |   60.012s | 165.0MiB| timeout | 0 |  |  |
|172.smt2                                                     |   60.012s | 361.0MiB| timeout | 0 |  |  |
|145.smt2                                                     |   60.012s | 246.0MiB| timeout | 0 |  |  |
|53.smt2                                                      |   60.012s | 189.0MiB| timeout | 0 |  |  |
|73.smt2                                                      |   60.013s | 217.0MiB| timeout | 0 |  |  |
|96.smt2                                                      |   60.013s | 183.0MiB| timeout | 0 |  |  |
|154.smt2                                                     |   60.014s | 223.0MiB| timeout | 0 |  |  |
|168.smt2                                                     |   60.014s | 278.0MiB| timeout | 0 |  |  |
|161.smt2                                                     |   60.015s | 234.0MiB| timeout | 0 |  |  |
|41.smt2                                                      |   60.015s | 189.0MiB| timeout | 0 |  |  |
|171.smt2                                                     |   60.015s | 250.0MiB| timeout | 0 |  |  |
|139.smt2                                                     |   60.015s | 148.0MiB| timeout | 0 |  |  |
|22.smt2                                                      |   60.015s | 177.0MiB| timeout | 0 |  |  |
|184.smt2                                                     |   60.016s | 702.0MiB| timeout | 0 |  |  |
|35.smt2                                                      |   60.016s | 170.0MiB| timeout | 0 |  |  |
|179.smt2                                                     |   60.018s | 388.0MiB| timeout | 0 |  |  |
|181.smt2                                                     |   60.019s | 444.0MiB| timeout | 0 |  |  |
|128.smt2                                                     |   60.022s | 192.0MiB| timeout | 0 |  |  |
|49.smt2                                                      |   60.022s | 173.0MiB| timeout | 0 |  |  |
|34.smt2                                                      |   60.023s | 159.0MiB| timeout | 0 |  |  |
|31.smt2                                                      |   60.023s | 175.0MiB| timeout | 0 |  |  |
|95.smt2                                                      |   60.023s | 186.0MiB| timeout | 0 |  |  |
|183.smt2                                                     |   60.024s | 670.0MiB| timeout | 0 |  |  |
|60.smt2                                                      |   60.024s | 180.0MiB| timeout | 0 |  |  |
|127.smt2                                                     |   60.025s | 220.0MiB| timeout | 0 |  |  |
|37.smt2                                                      |   60.025s | 158.0MiB| timeout | 0 |  |  |
|23.smt2                                                      |   60.026s | 175.0MiB| timeout | 0 |  |  |
|84.smt2                                                      |   60.028s | 127.0MiB| timeout | 0 |  |  |
|103.smt2                                                     |   60.031s | 182.0MiB| timeout | 0 |  |  |
|98.smt2                                                      |   60.032s | 181.0MiB| timeout | 0 |  |  |
|185.smt2                                                     |   60.032s | 1126.0MiB| timeout | 0 |  |  |
|20.smt2                                                      |   60.033s | 168.0MiB| timeout | 0 |  |  |
|160.smt2                                                     |   60.034s | 265.0MiB| timeout | 0 |  |  |
|141.smt2                                                     |   60.034s | 197.0MiB| timeout | 0 |  |  |
|74.smt2                                                      |   60.034s | 186.0MiB| timeout | 0 |  |  |
|25.smt2                                                      |   60.036s | 190.0MiB| timeout | 0 |  |  |
|142.smt2                                                     |   60.037s | 224.0MiB| timeout | 0 |  |  |
|17.smt2                                                      |   60.037s | 165.0MiB| timeout | 0 |  |  |
|158.smt2                                                     |   60.037s | 245.0MiB| timeout | 0 |  |  |
|135.smt2                                                     |   60.039s | 219.0MiB| timeout | 0 |  |  |
|126.smt2                                                     |   60.040s | 217.0MiB| timeout | 0 |  |  |
|94.smt2                                                      |   60.043s | 184.0MiB| timeout | 0 |  |  |
|144.smt2                                                     |   60.044s | 218.0MiB| timeout | 0 |  |  |
|05.smt2                                                      |   60.045s | 199.0MiB| timeout | 0 |  |  |
|114.smt2                                                     |   60.045s | 202.0MiB| timeout | 0 |  |  |
|167.smt2                                                     |   60.045s | 235.0MiB| timeout | 0 |  |  |
|153.smt2                                                     |   60.046s | 235.0MiB| timeout | 0 |  |  |
|85.smt2                                                      |   60.047s | 148.0MiB| timeout | 0 |  |  |
|122.smt2                                                     |   60.047s | 231.0MiB| timeout | 0 |  |  |
|51.smt2                                                      |   60.047s | 219.0MiB| timeout | 0 |  |  |
|159.smt2                                                     |   60.048s | 219.0MiB| timeout | 0 |  |  |
|105.smt2                                                     |   60.068s | 218.0MiB| timeout | 0 |  |  |
|97.smt2                                                      |   60.081s | 179.0MiB| timeout | 0 |  |  |
|01.smt2                                                      |   60.084s | 152.0MiB| timeout | 0 |  |  |
|39.smt2                                                      |   60.105s | 182.0MiB| timeout | 0 |  |  |
|67.smt2                                                      |   60.120s | 183.0MiB| timeout | 0 |  |  |
|61.smt2                                                      |   60.296s | 177.0MiB| timeout | 0 |  |  |
