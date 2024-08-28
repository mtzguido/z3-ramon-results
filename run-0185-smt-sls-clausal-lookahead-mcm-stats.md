# data

* SAT 30
* UNSAT 0
* TIMEOUT 156
* UNKNOWN 0

* UNSET 0

* ERROR 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: MCM
Job tag: smt-sls-clausal-lookahead-mcm
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: 22e4054674a291d83f59019273ff0b24f24295bf
Z3 branch: master
Z3 options: "-T:60 -v:2 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify sls-smt)" model_validate=true  sls.arith_use_clausal_lookahead=true"
Z3 inputs: inputs/QF_NIA_MCM
Z3 commit message: add clausal lookahead to arithmetic solver as part of portfolio

have legacy qfbv-sls solver use nnf pre-processing. It relies on it for correctness of the score updates.

</pre>


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|06.smt2                                                      |    0.019s | 20.144MiB| sat | 0 |  |  |
|45.smt2                                                      |    0.027s | 21.192MiB| sat | 0 |  |  |
|113.smt2                                                     |    0.054s | 24.264MiB| sat | 0 |  |  |
|107.smt2                                                     |    0.082s | 25.852MiB| sat | 0 |  |  |
|118.smt2                                                     |    0.096s | 27.052MiB| sat | 0 |  |  |
|109.smt2                                                     |    0.124s | 27.016MiB| sat | 0 |  |  |
|117.smt2                                                     |    0.124s | 26.056MiB| sat | 0 |  |  |
|12.smt2                                                      |    0.125s | 20.632MiB| sat | 0 |  |  |
|115.smt2                                                     |    0.197s | 33.964MiB| sat | 0 |  |  |
|164.smt2                                                     |    0.324s | 47.436MiB| sat | 0 |  |  |
|170.smt2                                                     |    0.355s | 47.236MiB| sat | 0 |  |  |
|166.smt2                                                     |    0.357s | 47.264MiB| sat | 0 |  |  |
|162.smt2                                                     |    0.499s | 47.436MiB| sat | 0 |  |  |
|07.smt2                                                      |    0.792s | 24.052MiB| sat | 0 |  |  |
|10.smt2                                                      |    0.993s | 25.164MiB| sat | 0 |  |  |
|104.smt2                                                     |    1.046s | 33.912MiB| sat | 0 |  |  |
|14.smt2                                                      |    1.296s | 23.532MiB| sat | 0 |  |  |
|177.smt2                                                     |    1.939s | 146.0MiB| sat | 0 |  |  |
|43.smt2                                                      |    1.958s | 24.044MiB| sat | 0 |  |  |
|13.smt2                                                      |    2.117s | 26.38MiB| sat | 0 |  |  |
|03.smt2                                                      |    4.732s | 26.224MiB| sat | 0 |  |  |
|15.smt2                                                      |    5.295s | 24.592MiB| sat | 0 |  |  |
|33.smt2                                                      |    8.136s | 25.296MiB| sat | 0 |  |  |
|152.smt2                                                     |    8.854s | 58.056MiB| sat | 0 |  |  |
|123.smt2                                                     |   16.076s | 75.068MiB| sat | 0 |  |  |
|01.smt2                                                      |   16.816s | 28.02MiB| sat | 0 |  |  |
|41.smt2                                                      |   43.158s | 24.916MiB| sat | 0 |  |  |
|48.smt2                                                      |   45.156s | 29.28MiB| sat | 0 |  |  |
|35.smt2                                                      |   52.309s | 29.084MiB| sat | 0 |  |  |
|26.smt2                                                      |   58.471s | 27.404MiB| sat | 0 |  |  |
|120.smt2                                                     |   59.686s | 146.0MiB| timeout | 0 |  |  |
|54.smt2                                                      |   59.719s | 30.996MiB| timeout | 0 |  |  |
|31.smt2                                                      |   59.754s | 30.008MiB| timeout | 0 |  |  |
|64.smt2                                                      |   59.758s | 35.216MiB| timeout | 0 |  |  |
|55.smt2                                                      |   59.776s | 27.616MiB| timeout | 0 |  |  |
|42.smt2                                                      |   59.816s | 23.028MiB| timeout | 0 |  |  |
|158.smt2                                                     |   59.829s | 599.0MiB| timeout | 0 |  |  |
|46.smt2                                                      |   59.839s | 34.368MiB| timeout | 0 |  |  |
|111.smt2                                                     |   59.839s | 98.292MiB| timeout | 0 |  |  |
|38.smt2                                                      |   59.853s | 26.72MiB| timeout | 0 |  |  |
|108.smt2                                                     |   59.860s | 100.0MiB| timeout | 0 |  |  |
|91.smt2                                                      |   59.869s | 30.976MiB| timeout | 0 |  |  |
|160.smt2                                                     |   59.896s | 622.0MiB| timeout | 0 |  |  |
|04.smt2                                                      |   59.900s | 24.012MiB| timeout | 0 |  |  |
|92.smt2                                                      |   59.903s | 26.376MiB| timeout | 0 |  |  |
|51.smt2                                                      |   59.903s | 27.612MiB| timeout | 0 |  |  |
|147.smt2                                                     |   59.905s | 120.0MiB| timeout | 0 |  |  |
|28.smt2                                                      |   59.911s | 27.636MiB| timeout | 0 |  |  |
|106.smt2                                                     |   59.917s | 119.0MiB| timeout | 0 |  |  |
|56.smt2                                                      |   59.928s | 40.888MiB| timeout | 0 |  |  |
|159.smt2                                                     |   59.928s | 524.0MiB| timeout | 0 |  |  |
|74.smt2                                                      |   59.930s | 37.104MiB| timeout | 0 |  |  |
|140.smt2                                                     |   59.935s | 130.0MiB| timeout | 0 |  |  |
|138.smt2                                                     |   59.936s | 142.0MiB| timeout | 0 |  |  |
|32.smt2                                                      |   59.937s | 26.736MiB| timeout | 0 |  |  |
|145.smt2                                                     |   59.937s | 146.0MiB| timeout | 0 |  |  |
|25.smt2                                                      |   59.939s | 27.408MiB| timeout | 0 |  |  |
|139.smt2                                                     |   59.939s | 75.144MiB| timeout | 0 |  |  |
|24.smt2                                                      |   59.942s | 30.748MiB| timeout | 0 |  |  |
|66.smt2                                                      |   59.943s | 35.228MiB| timeout | 0 |  |  |
|17.smt2                                                      |   59.943s | 30.772MiB| timeout | 0 |  |  |
|81.smt2                                                      |   59.948s | 30.992MiB| timeout | 0 |  |  |
|18.smt2                                                      |   59.948s | 30.748MiB| timeout | 0 |  |  |
|93.smt2                                                      |   59.950s | 23.856MiB| timeout | 0 |  |  |
|67.smt2                                                      |   59.951s | 30.984MiB| timeout | 0 |  |  |
|122.smt2                                                     |   59.953s | 146.0MiB| timeout | 0 |  |  |
|49.smt2                                                      |   59.954s | 26.092MiB| timeout | 0 |  |  |
|70.smt2                                                      |   59.958s | 34.388MiB| timeout | 0 |  |  |
|89.smt2                                                      |   59.959s | 30.988MiB| timeout | 0 |  |  |
|105.smt2                                                     |   59.959s | 98.0MiB| timeout | 0 |  |  |
|134.smt2                                                     |   59.960s | 146.0MiB| timeout | 0 |  |  |
|77.smt2                                                      |   59.961s | 32.9MiB| timeout | 0 |  |  |
|131.smt2                                                     |   59.961s | 41.2MiB| timeout | 0 |  |  |
|19.smt2                                                      |   59.963s | 27.388MiB| timeout | 0 |  |  |
|150.smt2                                                     |   59.963s | 125.0MiB| timeout | 0 |  |  |
|21.smt2                                                      |   59.963s | 27.66MiB| timeout | 0 |  |  |
|72.smt2                                                      |   59.965s | 33.096MiB| timeout | 0 |  |  |
|142.smt2                                                     |   59.967s | 137.0MiB| timeout | 0 |  |  |
|119.smt2                                                     |   59.967s | 146.0MiB| timeout | 0 |  |  |
|121.smt2                                                     |   59.967s | 177.0MiB| timeout | 0 |  |  |
|94.smt2                                                      |   59.968s | 35.256MiB| timeout | 0 |  |  |
|100.smt2                                                     |   59.969s | 30.996MiB| timeout | 0 |  |  |
|08.smt2                                                      |   59.970s | 22.064MiB| timeout | 0 |  |  |
|87.smt2                                                      |   59.970s | 23.088MiB| timeout | 0 |  |  |
|83.smt2                                                      |   59.971s | 29.236MiB| timeout | 0 |  |  |
|57.smt2                                                      |   59.971s | 35.224MiB| timeout | 0 |  |  |
|78.smt2                                                      |   59.972s | 39.888MiB| timeout | 0 |  |  |
|124.smt2                                                     |   59.974s | 57.916MiB| timeout | 0 |  |  |
|69.smt2                                                      |   59.974s | 30.196MiB| timeout | 0 |  |  |
|137.smt2                                                     |   59.975s | 146.0MiB| timeout | 0 |  |  |
|75.smt2                                                      |   59.976s | 30.98MiB| timeout | 0 |  |  |
|116.smt2                                                     |   59.976s | 144.0MiB| timeout | 0 |  |  |
|168.smt2                                                     |   59.976s | 594.0MiB| timeout | 0 |  |  |
|157.smt2                                                     |   59.977s | 113.0MiB| timeout | 0 |  |  |
|68.smt2                                                      |   59.977s | 34.152MiB| timeout | 0 |  |  |
|05.smt2                                                      |   59.977s | 27.432MiB| timeout | 0 |  |  |
|96.smt2                                                      |   59.977s | 35.228MiB| timeout | 0 |  |  |
|146.smt2                                                     |   59.977s | 148.0MiB| timeout | 0 |  |  |
|143.smt2                                                     |   59.977s | 113.0MiB| timeout | 0 |  |  |
|60.smt2                                                      |   59.978s | 35.224MiB| timeout | 0 |  |  |
|44.smt2                                                      |   59.980s | 22.056MiB| timeout | 0 |  |  |
|58.smt2                                                      |   59.980s | 37.096MiB| timeout | 0 |  |  |
|88.smt2                                                      |   59.981s | 35.228MiB| timeout | 0 |  |  |
|20.smt2                                                      |   59.982s | 31.008MiB| timeout | 0 |  |  |
|29.smt2                                                      |   59.982s | 31.212MiB| timeout | 0 |  |  |
|95.smt2                                                      |   59.983s | 32.896MiB| timeout | 0 |  |  |
|36.smt2                                                      |   59.985s | 25.94MiB| timeout | 0 |  |  |
|76.smt2                                                      |   59.985s | 37.18MiB| timeout | 0 |  |  |
|59.smt2                                                      |   59.985s | 30.988MiB| timeout | 0 |  |  |
|09.smt2                                                      |   59.985s | 23.292MiB| timeout | 0 |  |  |
|62.smt2                                                      |   59.986s | 35.196MiB| timeout | 0 |  |  |
|130.smt2                                                     |   59.988s | 114.0MiB| timeout | 0 |  |  |
|84.smt2                                                      |   59.989s | 23.784MiB| timeout | 0 |  |  |
|80.smt2                                                      |   59.990s | 35.236MiB| timeout | 0 |  |  |
|151.smt2                                                     |   59.990s | 120.0MiB| timeout | 0 |  |  |
|98.smt2                                                      |   59.991s | 30.132MiB| timeout | 0 |  |  |
|112.smt2                                                     |   59.991s | 98.308MiB| timeout | 0 |  |  |
|171.smt2                                                     |   59.991s | 625.0MiB| timeout | 0 |  |  |
|50.smt2                                                      |   59.992s | 31.0MiB| timeout | 0 |  |  |
|65.smt2                                                      |   59.992s | 30.98MiB| timeout | 0 |  |  |
|79.smt2                                                      |   59.992s | 34.376MiB| timeout | 0 |  |  |
|141.smt2                                                     |   59.992s | 117.0MiB| timeout | 0 |  |  |
|27.smt2                                                      |   59.992s | 30.688MiB| timeout | 0 |  |  |
|34.smt2                                                      |   59.993s | 23.3MiB| timeout | 0 |  |  |
|101.smt2                                                     |   59.993s | 27.624MiB| timeout | 0 |  |  |
|114.smt2                                                     |   59.995s | 83.008MiB| timeout | 0 |  |  |
|02.smt2                                                      |   59.995s | 25.336MiB| timeout | 0 |  |  |
|99.smt2                                                      |   59.995s | 28.824MiB| timeout | 0 |  |  |
|97.smt2                                                      |   59.995s | 30.984MiB| timeout | 0 |  |  |
|30.smt2                                                      |   59.996s | 27.872MiB| timeout | 0 |  |  |
|63.smt2                                                      |   59.997s | 31.232MiB| timeout | 0 |  |  |
|102.smt2                                                     |   59.997s | 35.32MiB| timeout | 0 |  |  |
|22.smt2                                                      |   59.997s | 30.7MiB| timeout | 0 |  |  |
|40.smt2                                                      |   59.998s | 30.764MiB| timeout | 0 |  |  |
|132.smt2                                                     |   59.998s | 168.0MiB| timeout | 0 |  |  |
|135.smt2                                                     |   59.998s | 177.0MiB| timeout | 0 |  |  |
|47.smt2                                                      |   59.999s | 30.184MiB| timeout | 0 |  |  |
|148.smt2                                                     |   59.999s | 138.0MiB| timeout | 0 |  |  |
|126.smt2                                                     |   59.999s | 147.0MiB| timeout | 0 |  |  |
|52.smt2                                                      |   60.000s | 35.188MiB| timeout | 0 |  |  |
|156.smt2                                                     |   60.000s | 83.084MiB| timeout | 0 |  |  |
|73.smt2                                                      |   60.001s | 27.596MiB| timeout | 0 |  |  |
|85.smt2                                                      |   60.001s | 29.6MiB| timeout | 0 |  |  |
|103.smt2                                                     |   60.001s | 30.98MiB| timeout | 0 |  |  |
|16.smt2                                                      |   60.002s | 35.152MiB| timeout | 0 |  |  |
|53.smt2                                                      |   60.002s | 30.976MiB| timeout | 0 |  |  |
|136.smt2                                                     |   60.004s | 146.0MiB| timeout | 0 |  |  |
|71.smt2                                                      |   60.004s | 30.184MiB| timeout | 0 |  |  |
|155.smt2                                                     |   60.004s | 91.36MiB| timeout | 0 |  |  |
|86.smt2                                                      |   60.005s | 24.688MiB| timeout | 0 |  |  |
|61.smt2                                                      |   60.006s | 30.988MiB| timeout | 0 |  |  |
|82.smt2                                                      |   60.007s | 33.04MiB| timeout | 0 |  |  |
|129.smt2                                                     |   60.009s | 142.0MiB| timeout | 0 |  |  |
|153.smt2                                                     |   60.009s | 177.0MiB| timeout | 0 |  |  |
|110.smt2                                                     |   60.010s | 120.0MiB| timeout | 0 |  |  |
|154.smt2                                                     |   60.011s | 146.0MiB| timeout | 0 |  |  |
|144.smt2                                                     |   60.011s | 177.0MiB| timeout | 0 |  |  |
|128.smt2                                                     |   60.011s | 119.0MiB| timeout | 0 |  |  |
|37.smt2                                                      |   60.013s | 30.016MiB| timeout | 0 |  |  |
|127.smt2                                                     |   60.014s | 146.0MiB| timeout | 0 |  |  |
|161.smt2                                                     |   60.015s | 723.0MiB| timeout | 0 |  |  |
|39.smt2                                                      |   60.016s | 34.896MiB| timeout | 0 |  |  |
|125.smt2                                                     |   60.018s | 176.0MiB| timeout | 0 |  |  |
|172.smt2                                                     |   60.020s | 2036.0MiB| timeout | 0 |  |  |
|133.smt2                                                     |   60.022s | 138.0MiB| timeout | 0 |  |  |
|167.smt2                                                     |   60.023s | 384.0MiB| timeout | 0 |  |  |
|149.smt2                                                     |   60.024s | 152.0MiB| timeout | 0 |  |  |
|169.smt2                                                     |   60.025s | 881.0MiB| timeout | 0 |  |  |
|165.smt2                                                     |   60.042s | 757.0MiB| timeout | 0 |  |  |
|23.smt2                                                      |   60.044s | 27.392MiB| timeout | 0 |  |  |
|163.smt2                                                     |   60.053s | 750.0MiB| timeout | 0 |  |  |
|179.smt2                                                     |   60.085s | 2257.0MiB| timeout | 0 |  |  |
|173.smt2                                                     |   60.103s | 1899.0MiB| timeout | 0 |  |  |
|178.smt2                                                     |   60.117s | 2444.0MiB| timeout | 0 |  |  |
|90.smt2                                                      |   60.127s | 37.068MiB| timeout | 0 |  |  |
|175.smt2                                                     |   60.146s | 1851.0MiB| timeout | 0 |  |  |
|180.smt2                                                     |   60.147s | 2257.0MiB| timeout | 0 |  |  |
|176.smt2                                                     |   60.150s | 2403.0MiB| timeout | 0 |  |  |
|174.smt2                                                     |   60.152s | 2093.0MiB| timeout | 0 |  |  |
|181.smt2                                                     |   60.166s | 3033.0MiB| timeout | 0 |  |  |
|11.smt2                                                      |   60.292s | 23.252MiB| timeout | 0 |  |  |
|183.smt2                                                     |   60.363s | 7048.0MiB| timeout | 0 |  |  |
|182.smt2                                                     |   60.435s | 7047.0MiB| timeout | 0 |  |  |
|184.smt2                                                     |   60.515s | 7895.0MiB| timeout | 0 |  |  |
|186.smt2                                                     |   60.524s | 9662.0MiB| timeout | 0 |  |  |
|185.smt2                                                     |   60.701s | 11.954GiB| timeout | 0 |  |  |
