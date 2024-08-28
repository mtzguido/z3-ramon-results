# data

* SAT 22
* UNSAT 0
* TIMEOUT 164
* UNKNOWN 0

* UNSET 0

* ERROR 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: with lookahead
Job tag: smt-sls-lookahead
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: 9770c005926e2085d4ede18f03d56cb67d762d84
Z3 branch: master
Z3 options: "-T:20 -v:2 -st sls.arith_use_lookahead=true tactic.default_tactic="(then simplify propagate-values solve-eqs simplify sls-smt)" model_validate=true"
Z3 inputs: inputs/QF_NIA_MCM
Z3 commit message: adjust heuristic in random-inc-dec for finite domains

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|12.smt2                                                      |    0.024s | 20.276MiB| sat | 0 |  |  |
|06.smt2                                                      |    0.026s | 19.764MiB| sat | 0 |  |  |
|113.smt2                                                     |    0.056s | 21.58MiB| sat | 0 |  |  |
|107.smt2                                                     |    0.057s | 22.22MiB| sat | 0 |  |  |
|45.smt2                                                      |    0.058s | 20.188MiB| sat | 0 |  |  |
|109.smt2                                                     |    0.074s | 22.86MiB| sat | 0 |  |  |
|117.smt2                                                     |    0.081s | 22.252MiB| sat | 0 |  |  |
|118.smt2                                                     |    0.139s | 22.696MiB| sat | 0 |  |  |
|170.smt2                                                     |    0.302s | 26.72MiB| sat | 0 |  |  |
|43.smt2                                                      |    0.321s | 21.572MiB| sat | 0 |  |  |
|164.smt2                                                     |    0.340s | 26.616MiB| sat | 0 |  |  |
|07.smt2                                                      |    0.420s | 21.78MiB| sat | 0 |  |  |
|166.smt2                                                     |    0.450s | 26.624MiB| sat | 0 |  |  |
|162.smt2                                                     |    0.551s | 26.6MiB| sat | 0 |  |  |
|177.smt2                                                     |    1.572s | 47.388MiB| sat | 0 |  |  |
|115.smt2                                                     |    1.741s | 24.332MiB| sat | 0 |  |  |
|104.smt2                                                     |    3.230s | 24.3MiB| sat | 0 |  |  |
|03.smt2                                                      |    3.288s | 22.168MiB| sat | 0 |  |  |
|14.smt2                                                      |    5.132s | 21.312MiB| sat | 0 |  |  |
|152.smt2                                                     |    5.322s | 29.524MiB| sat | 0 |  |  |
|10.smt2                                                      |    5.755s | 21.932MiB| sat | 0 |  |  |
|139.smt2                                                     |   18.970s | 31.48MiB| sat | 0 |  |  |
|156.smt2                                                     |   19.278s | 31.94MiB| timeout | 0 |  |  |
|102.smt2                                                     |   19.617s | 24.48MiB| timeout | 0 |  |  |
|68.smt2                                                      |   19.631s | 24.396MiB| timeout | 0 |  |  |
|82.smt2                                                      |   19.642s | 24.196MiB| timeout | 0 |  |  |
|142.smt2                                                     |   19.657s | 38.652MiB| timeout | 0 |  |  |
|111.smt2                                                     |   19.685s | 33.5MiB| timeout | 0 |  |  |
|182.smt2                                                     |   19.697s | 320.0MiB| timeout | 0 |  |  |
|90.smt2                                                      |   19.751s | 24.296MiB| timeout | 0 |  |  |
|25.smt2                                                      |   19.758s | 22.252MiB| timeout | 0 |  |  |
|33.smt2                                                      |   19.766s | 22.276MiB| timeout | 0 |  |  |
|93.smt2                                                      |   19.768s | 21.328MiB| timeout | 0 |  |  |
|32.smt2                                                      |   19.770s | 22.156MiB| timeout | 0 |  |  |
|158.smt2                                                     |   19.782s | 66.408MiB| timeout | 0 |  |  |
|81.smt2                                                      |   19.792s | 23.464MiB| timeout | 0 |  |  |
|147.smt2                                                     |   19.795s | 36.872MiB| timeout | 0 |  |  |
|122.smt2                                                     |   19.815s | 38.82MiB| timeout | 0 |  |  |
|64.smt2                                                      |   19.823s | 24.404MiB| timeout | 0 |  |  |
|91.smt2                                                      |   19.823s | 23.856MiB| timeout | 0 |  |  |
|159.smt2                                                     |   19.834s | 65.664MiB| timeout | 0 |  |  |
|153.smt2                                                     |   19.843s | 41.304MiB| timeout | 0 |  |  |
|39.smt2                                                      |   19.846s | 24.68MiB| timeout | 0 |  |  |
|178.smt2                                                     |   19.848s | 188.0MiB| timeout | 0 |  |  |
|34.smt2                                                      |   19.865s | 21.112MiB| timeout | 0 |  |  |
|131.smt2                                                     |   19.874s | 26.28MiB| timeout | 0 |  |  |
|77.smt2                                                      |   19.875s | 23.42MiB| timeout | 0 |  |  |
|28.smt2                                                      |   19.875s | 22.26MiB| timeout | 0 |  |  |
|171.smt2                                                     |   19.875s | 69.4MiB| timeout | 0 |  |  |
|163.smt2                                                     |   19.881s | 85.916MiB| timeout | 0 |  |  |
|30.smt2                                                      |   19.888s | 22.656MiB| timeout | 0 |  |  |
|18.smt2                                                      |   19.900s | 23.46MiB| timeout | 0 |  |  |
|97.smt2                                                      |   19.903s | 23.86MiB| timeout | 0 |  |  |
|31.smt2                                                      |   19.910s | 23.26MiB| timeout | 0 |  |  |
|150.smt2                                                     |   19.914s | 37.448MiB| timeout | 0 |  |  |
|146.smt2                                                     |   19.918s | 39.22MiB| timeout | 0 |  |  |
|05.smt2                                                      |   19.920s | 22.352MiB| timeout | 0 |  |  |
|160.smt2                                                     |   19.920s | 69.204MiB| timeout | 0 |  |  |
|151.smt2                                                     |   19.921s | 37.144MiB| timeout | 0 |  |  |
|124.smt2                                                     |   19.924s | 29.416MiB| timeout | 0 |  |  |
|13.smt2                                                      |   19.926s | 22.2MiB| timeout | 0 |  |  |
|132.smt2                                                     |   19.929s | 41.0MiB| timeout | 0 |  |  |
|105.smt2                                                     |   19.930s | 33.528MiB| timeout | 0 |  |  |
|36.smt2                                                      |   19.931s | 22.048MiB| timeout | 0 |  |  |
|112.smt2                                                     |   19.935s | 33.524MiB| timeout | 0 |  |  |
|79.smt2                                                      |   19.935s | 24.136MiB| timeout | 0 |  |  |
|51.smt2                                                      |   19.935s | 22.496MiB| timeout | 0 |  |  |
|57.smt2                                                      |   19.935s | 24.308MiB| timeout | 0 |  |  |
|02.smt2                                                      |   19.937s | 22.228MiB| timeout | 0 |  |  |
|78.smt2                                                      |   19.938s | 25.996MiB| timeout | 0 |  |  |
|23.smt2                                                      |   19.942s | 22.336MiB| timeout | 0 |  |  |
|86.smt2                                                      |   19.944s | 21.804MiB| timeout | 0 |  |  |
|87.smt2                                                      |   19.944s | 21.104MiB| timeout | 0 |  |  |
|108.smt2                                                     |   19.945s | 33.804MiB| timeout | 0 |  |  |
|17.smt2                                                      |   19.947s | 23.6MiB| timeout | 0 |  |  |
|168.smt2                                                     |   19.947s | 76.96MiB| timeout | 0 |  |  |
|175.smt2                                                     |   19.949s | 152.0MiB| timeout | 0 |  |  |
|149.smt2                                                     |   19.951s | 39.232MiB| timeout | 0 |  |  |
|09.smt2                                                      |   19.951s | 21.112MiB| timeout | 0 |  |  |
|123.smt2                                                     |   19.953s | 31.156MiB| timeout | 0 |  |  |
|100.smt2                                                     |   19.954s | 23.384MiB| timeout | 0 |  |  |
|01.smt2                                                      |   19.955s | 22.724MiB| timeout | 0 |  |  |
|38.smt2                                                      |   19.957s | 22.2MiB| timeout | 0 |  |  |
|98.smt2                                                      |   19.958s | 23.436MiB| timeout | 0 |  |  |
|21.smt2                                                      |   19.962s | 22.412MiB| timeout | 0 |  |  |
|157.smt2                                                     |   19.964s | 36.5MiB| timeout | 0 |  |  |
|20.smt2                                                      |   19.964s | 23.608MiB| timeout | 0 |  |  |
|94.smt2                                                      |   19.964s | 24.372MiB| timeout | 0 |  |  |
|59.smt2                                                      |   19.964s | 23.58MiB| timeout | 0 |  |  |
|137.smt2                                                     |   19.965s | 38.66MiB| timeout | 0 |  |  |
|116.smt2                                                     |   19.965s | 39.168MiB| timeout | 0 |  |  |
|48.smt2                                                      |   19.966s | 22.836MiB| timeout | 0 |  |  |
|106.smt2                                                     |   19.966s | 36.944MiB| timeout | 0 |  |  |
|125.smt2                                                     |   19.966s | 41.364MiB| timeout | 0 |  |  |
|73.smt2                                                      |   19.967s | 22.492MiB| timeout | 0 |  |  |
|179.smt2                                                     |   19.970s | 180.0MiB| timeout | 0 |  |  |
|66.smt2                                                      |   19.972s | 24.608MiB| timeout | 0 |  |  |
|135.smt2                                                     |   19.972s | 41.424MiB| timeout | 0 |  |  |
|148.smt2                                                     |   19.973s | 38.696MiB| timeout | 0 |  |  |
|173.smt2                                                     |   19.974s | 159.0MiB| timeout | 0 |  |  |
|138.smt2                                                     |   19.978s | 38.88MiB| timeout | 0 |  |  |
|37.smt2                                                      |   19.980s | 23.468MiB| timeout | 0 |  |  |
|167.smt2                                                     |   19.980s | 69.26MiB| timeout | 0 |  |  |
|184.smt2                                                     |   19.981s | 137.0MiB| timeout | 0 |  |  |
|101.smt2                                                     |   19.981s | 22.312MiB| timeout | 0 |  |  |
|50.smt2                                                      |   19.982s | 23.832MiB| timeout | 0 |  |  |
|24.smt2                                                      |   19.982s | 23.468MiB| timeout | 0 |  |  |
|186.smt2                                                     |   19.982s | 245.0MiB| timeout | 0 |  |  |
|08.smt2                                                      |   19.983s | 20.908MiB| timeout | 0 |  |  |
|154.smt2                                                     |   19.984s | 38.632MiB| timeout | 0 |  |  |
|70.smt2                                                      |   19.984s | 24.264MiB| timeout | 0 |  |  |
|04.smt2                                                      |   19.986s | 21.312MiB| timeout | 0 |  |  |
|56.smt2                                                      |   19.987s | 26.1MiB| timeout | 0 |  |  |
|65.smt2                                                      |   19.987s | 23.576MiB| timeout | 0 |  |  |
|119.smt2                                                     |   19.988s | 38.812MiB| timeout | 0 |  |  |
|71.smt2                                                      |   19.988s | 23.412MiB| timeout | 0 |  |  |
|49.smt2                                                      |   19.988s | 22.14MiB| timeout | 0 |  |  |
|145.smt2                                                     |   19.988s | 38.672MiB| timeout | 0 |  |  |
|60.smt2                                                      |   19.988s | 24.296MiB| timeout | 0 |  |  |
|141.smt2                                                     |   19.989s | 36.332MiB| timeout | 0 |  |  |
|114.smt2                                                     |   19.990s | 31.848MiB| timeout | 0 |  |  |
|40.smt2                                                      |   19.990s | 23.564MiB| timeout | 0 |  |  |
|69.smt2                                                      |   19.990s | 23.396MiB| timeout | 0 |  |  |
|165.smt2                                                     |   19.990s | 92.952MiB| timeout | 0 |  |  |
|15.smt2                                                      |   19.990s | 21.848MiB| timeout | 0 |  |  |
|42.smt2                                                      |   19.991s | 20.96MiB| timeout | 0 |  |  |
|52.smt2                                                      |   19.991s | 24.48MiB| timeout | 0 |  |  |
|128.smt2                                                     |   19.992s | 36.916MiB| timeout | 0 |  |  |
|27.smt2                                                      |   19.992s | 23.348MiB| timeout | 0 |  |  |
|161.smt2                                                     |   19.993s | 89.336MiB| timeout | 0 |  |  |
|63.smt2                                                      |   19.993s | 23.476MiB| timeout | 0 |  |  |
|176.smt2                                                     |   19.993s | 177.0MiB| timeout | 0 |  |  |
|53.smt2                                                      |   19.993s | 23.628MiB| timeout | 0 |  |  |
|19.smt2                                                      |   19.994s | 22.696MiB| timeout | 0 |  |  |
|84.smt2                                                      |   19.994s | 21.324MiB| timeout | 0 |  |  |
|99.smt2                                                      |   19.994s | 22.192MiB| timeout | 0 |  |  |
|181.smt2                                                     |   19.994s | 183.0MiB| timeout | 0 |  |  |
|136.smt2                                                     |   19.995s | 38.604MiB| timeout | 0 |  |  |
|67.smt2                                                      |   19.995s | 23.52MiB| timeout | 0 |  |  |
|103.smt2                                                     |   19.996s | 23.428MiB| timeout | 0 |  |  |
|129.smt2                                                     |   19.996s | 38.848MiB| timeout | 0 |  |  |
|133.smt2                                                     |   19.997s | 38.428MiB| timeout | 0 |  |  |
|41.smt2                                                      |   19.997s | 21.756MiB| timeout | 0 |  |  |
|76.smt2                                                      |   19.997s | 24.48MiB| timeout | 0 |  |  |
|44.smt2                                                      |   19.998s | 20.932MiB| timeout | 0 |  |  |
|80.smt2                                                      |   19.998s | 24.36MiB| timeout | 0 |  |  |
|88.smt2                                                      |   19.998s | 24.632MiB| timeout | 0 |  |  |
|143.smt2                                                     |   19.999s | 36.532MiB| timeout | 0 |  |  |
|22.smt2                                                      |   19.999s | 23.544MiB| timeout | 0 |  |  |
|110.smt2                                                     |   20.000s | 36.992MiB| timeout | 0 |  |  |
|46.smt2                                                      |   20.000s | 24.156MiB| timeout | 0 |  |  |
|92.smt2                                                      |   20.000s | 22.316MiB| timeout | 0 |  |  |
|29.smt2                                                      |   20.000s | 22.796MiB| timeout | 0 |  |  |
|172.smt2                                                     |   20.000s | 177.0MiB| timeout | 0 |  |  |
|89.smt2                                                      |   20.000s | 23.492MiB| timeout | 0 |  |  |
|54.smt2                                                      |   20.001s | 23.604MiB| timeout | 0 |  |  |
|121.smt2                                                     |   20.001s | 41.332MiB| timeout | 0 |  |  |
|95.smt2                                                      |   20.001s | 23.376MiB| timeout | 0 |  |  |
|83.smt2                                                      |   20.002s | 22.796MiB| timeout | 0 |  |  |
|72.smt2                                                      |   20.002s | 23.524MiB| timeout | 0 |  |  |
|55.smt2                                                      |   20.002s | 22.464MiB| timeout | 0 |  |  |
|58.smt2                                                      |   20.002s | 24.676MiB| timeout | 0 |  |  |
|16.smt2                                                      |   20.002s | 24.236MiB| timeout | 0 |  |  |
|130.smt2                                                     |   20.003s | 36.448MiB| timeout | 0 |  |  |
|85.smt2                                                      |   20.003s | 22.464MiB| timeout | 0 |  |  |
|47.smt2                                                      |   20.003s | 23.296MiB| timeout | 0 |  |  |
|26.smt2                                                      |   20.003s | 22.324MiB| timeout | 0 |  |  |
|96.smt2                                                      |   20.004s | 24.348MiB| timeout | 0 |  |  |
|174.smt2                                                     |   20.004s | 152.0MiB| timeout | 0 |  |  |
|120.smt2                                                     |   20.005s | 38.732MiB| timeout | 0 |  |  |
|62.smt2                                                      |   20.005s | 24.396MiB| timeout | 0 |  |  |
|140.smt2                                                     |   20.005s | 37.844MiB| timeout | 0 |  |  |
|74.smt2                                                      |   20.005s | 24.46MiB| timeout | 0 |  |  |
|183.smt2                                                     |   20.006s | 321.0MiB| timeout | 0 |  |  |
|134.smt2                                                     |   20.006s | 38.676MiB| timeout | 0 |  |  |
|144.smt2                                                     |   20.006s | 41.372MiB| timeout | 0 |  |  |
|127.smt2                                                     |   20.006s | 38.58MiB| timeout | 0 |  |  |
|169.smt2                                                     |   20.006s | 92.12MiB| timeout | 0 |  |  |
|75.smt2                                                      |   20.007s | 23.572MiB| timeout | 0 |  |  |
|35.smt2                                                      |   20.008s | 22.764MiB| timeout | 0 |  |  |
|126.smt2                                                     |   20.008s | 39.264MiB| timeout | 0 |  |  |
|11.smt2                                                      |   20.011s | 21.112MiB| timeout | 0 |  |  |
|61.smt2                                                      |   20.012s | 23.856MiB| timeout | 0 |  |  |
|180.smt2                                                     |   20.012s | 179.0MiB| timeout | 0 |  |  |
|155.smt2                                                     |   20.013s | 34.188MiB| timeout | 0 |  |  |
|185.smt2                                                     |   20.035s | 245.0MiB| timeout | 0 |  |  |
