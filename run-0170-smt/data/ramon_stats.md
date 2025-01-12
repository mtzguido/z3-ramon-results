# data

* SAT 6
* UNSAT 0
* TIMEOUT 180
* UNKNOWN 0

* UNSET 0

* ERROR 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: MCM with basic SMT solver
Job tag: smt
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: 9770c005926e2085d4ede18f03d56cb67d762d84
Z3 branch: master
Z3 options: "-T:20 -v:2 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify smt)" model_validate=true"
Z3 inputs: inputs/QF_NIA_MCM
Z3 commit message: adjust heuristic in random-inc-dec for finite domains

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|113.smt2                                                     |    0.172s | 25.476MiB| sat | 0 |  |  |
|107.smt2                                                     |    1.048s | 32.432MiB| sat | 0 |  |  |
|109.smt2                                                     |    1.531s | 49.956MiB| sat | 0 |  |  |
|06.smt2                                                      |    2.928s | 44.996MiB| sat | 0 |  |  |
|117.smt2                                                     |   10.571s | 77.06MiB| sat | 0 |  |  |
|161.smt2                                                     |   18.956s | 166.0MiB| timeout | 0 |  |  |
|164.smt2                                                     |   19.187s | 63.764MiB| timeout | 0 |  |  |
|61.smt2                                                      |   19.240s | 114.0MiB| timeout | 0 |  |  |
|10.smt2                                                      |   19.385s | 89.052MiB| timeout | 0 |  |  |
|127.smt2                                                     |   19.500s | 130.0MiB| timeout | 0 |  |  |
|121.smt2                                                     |   19.541s | 140.0MiB| timeout | 0 |  |  |
|141.smt2                                                     |   19.544s | 122.0MiB| timeout | 0 |  |  |
|166.smt2                                                     |   19.599s | 88.32MiB| timeout | 0 |  |  |
|136.smt2                                                     |   19.604s | 148.0MiB| timeout | 0 |  |  |
|12.smt2                                                      |   19.605s | 73.332MiB| timeout | 0 |  |  |
|33.smt2                                                      |   19.625s | 101.0MiB| timeout | 0 |  |  |
|118.smt2                                                     |   19.657s | 78.26MiB| timeout | 0 |  |  |
|86.smt2                                                      |   19.666s | 94.648MiB| timeout | 0 |  |  |
|99.smt2                                                      |   19.700s | 114.0MiB| timeout | 0 |  |  |
|42.smt2                                                      |   19.704s | 122.0MiB| timeout | 0 |  |  |
|120.smt2                                                     |   19.704s | 148.0MiB| timeout | 0 |  |  |
|145.smt2                                                     |   19.705s | 124.0MiB| timeout | 0 |  |  |
|69.smt2                                                      |   19.721s | 119.0MiB| timeout | 0 |  |  |
|64.smt2                                                      |   19.725s | 116.0MiB| timeout | 0 |  |  |
|170.smt2                                                     |   19.726s | 85.596MiB| sat | 0 |  |  |
|15.smt2                                                      |   19.726s | 71.432MiB| timeout | 0 |  |  |
|81.smt2                                                      |   19.728s | 116.0MiB| timeout | 0 |  |  |
|126.smt2                                                     |   19.740s | 125.0MiB| timeout | 0 |  |  |
|159.smt2                                                     |   19.768s | 180.0MiB| timeout | 0 |  |  |
|76.smt2                                                      |   19.782s | 110.0MiB| timeout | 0 |  |  |
|139.smt2                                                     |   19.783s | 106.0MiB| timeout | 0 |  |  |
|72.smt2                                                      |   19.794s | 132.0MiB| timeout | 0 |  |  |
|162.smt2                                                     |   19.795s | 86.66MiB| timeout | 0 |  |  |
|71.smt2                                                      |   19.795s | 131.0MiB| timeout | 0 |  |  |
|36.smt2                                                      |   19.803s | 125.0MiB| timeout | 0 |  |  |
|116.smt2                                                     |   19.805s | 136.0MiB| timeout | 0 |  |  |
|128.smt2                                                     |   19.807s | 112.0MiB| timeout | 0 |  |  |
|182.smt2                                                     |   19.809s | 407.0MiB| timeout | 0 |  |  |
|140.smt2                                                     |   19.818s | 108.0MiB| timeout | 0 |  |  |
|87.smt2                                                      |   19.820s | 82.736MiB| timeout | 0 |  |  |
|160.smt2                                                     |   19.822s | 191.0MiB| timeout | 0 |  |  |
|34.smt2                                                      |   19.823s | 79.444MiB| timeout | 0 |  |  |
|37.smt2                                                      |   19.825s | 103.0MiB| timeout | 0 |  |  |
|132.smt2                                                     |   19.832s | 128.0MiB| timeout | 0 |  |  |
|152.smt2                                                     |   19.832s | 98.0MiB| timeout | 0 |  |  |
|124.smt2                                                     |   19.839s | 101.0MiB| timeout | 0 |  |  |
|38.smt2                                                      |   19.841s | 112.0MiB| timeout | 0 |  |  |
|35.smt2                                                      |   19.841s | 115.0MiB| timeout | 0 |  |  |
|131.smt2                                                     |   19.845s | 87.452MiB| timeout | 0 |  |  |
|114.smt2                                                     |   19.850s | 150.0MiB| timeout | 0 |  |  |
|111.smt2                                                     |   19.853s | 134.0MiB| timeout | 0 |  |  |
|27.smt2                                                      |   19.862s | 113.0MiB| timeout | 0 |  |  |
|67.smt2                                                      |   19.871s | 109.0MiB| timeout | 0 |  |  |
|28.smt2                                                      |   19.875s | 102.0MiB| timeout | 0 |  |  |
|157.smt2                                                     |   19.879s | 120.0MiB| timeout | 0 |  |  |
|167.smt2                                                     |   19.889s | 151.0MiB| timeout | 0 |  |  |
|173.smt2                                                     |   19.892s | 289.0MiB| timeout | 0 |  |  |
|44.smt2                                                      |   19.895s | 75.996MiB| timeout | 0 |  |  |
|09.smt2                                                      |   19.897s | 81.792MiB| timeout | 0 |  |  |
|83.smt2                                                      |   19.899s | 93.232MiB| timeout | 0 |  |  |
|73.smt2                                                      |   19.900s | 110.0MiB| timeout | 0 |  |  |
|17.smt2                                                      |   19.903s | 100.0MiB| timeout | 0 |  |  |
|102.smt2                                                     |   19.904s | 136.0MiB| timeout | 0 |  |  |
|186.smt2                                                     |   19.905s | 245.0MiB| timeout | 0 |  |  |
|163.smt2                                                     |   19.910s | 208.0MiB| timeout | 0 |  |  |
|174.smt2                                                     |   19.910s | 268.0MiB| timeout | 0 |  |  |
|180.smt2                                                     |   19.913s | 307.0MiB| timeout | 0 |  |  |
|46.smt2                                                      |   19.915s | 130.0MiB| timeout | 0 |  |  |
|101.smt2                                                     |   19.917s | 110.0MiB| timeout | 0 |  |  |
|142.smt2                                                     |   19.921s | 131.0MiB| timeout | 0 |  |  |
|137.smt2                                                     |   19.922s | 135.0MiB| timeout | 0 |  |  |
|56.smt2                                                      |   19.925s | 119.0MiB| timeout | 0 |  |  |
|79.smt2                                                      |   19.929s | 136.0MiB| timeout | 0 |  |  |
|25.smt2                                                      |   19.931s | 142.0MiB| timeout | 0 |  |  |
|165.smt2                                                     |   19.931s | 181.0MiB| timeout | 0 |  |  |
|176.smt2                                                     |   19.946s | 296.0MiB| timeout | 0 |  |  |
|149.smt2                                                     |   19.955s | 122.0MiB| timeout | 0 |  |  |
|108.smt2                                                     |   19.955s | 160.0MiB| timeout | 0 |  |  |
|96.smt2                                                      |   19.956s | 107.0MiB| timeout | 0 |  |  |
|146.smt2                                                     |   19.956s | 138.0MiB| timeout | 0 |  |  |
|106.smt2                                                     |   19.956s | 135.0MiB| timeout | 0 |  |  |
|148.smt2                                                     |   19.960s | 126.0MiB| timeout | 0 |  |  |
|97.smt2                                                      |   19.961s | 106.0MiB| timeout | 0 |  |  |
|110.smt2                                                     |   19.962s | 123.0MiB| timeout | 0 |  |  |
|62.smt2                                                      |   19.966s | 105.0MiB| timeout | 0 |  |  |
|115.smt2                                                     |   19.970s | 81.776MiB| timeout | 0 |  |  |
|98.smt2                                                      |   19.974s | 122.0MiB| timeout | 0 |  |  |
|16.smt2                                                      |   19.974s | 117.0MiB| timeout | 0 |  |  |
|29.smt2                                                      |   19.976s | 114.0MiB| timeout | 0 |  |  |
|19.smt2                                                      |   19.978s | 120.0MiB| timeout | 0 |  |  |
|01.smt2                                                      |   19.980s | 104.0MiB| timeout | 0 |  |  |
|178.smt2                                                     |   19.981s | 380.0MiB| timeout | 0 |  |  |
|88.smt2                                                      |   19.985s | 138.0MiB| timeout | 0 |  |  |
|80.smt2                                                      |   19.986s | 145.0MiB| timeout | 0 |  |  |
|20.smt2                                                      |   19.986s | 117.0MiB| timeout | 0 |  |  |
|104.smt2                                                     |   19.987s | 79.424MiB| timeout | 0 |  |  |
|129.smt2                                                     |   19.987s | 137.0MiB| timeout | 0 |  |  |
|13.smt2                                                      |   19.990s | 103.0MiB| timeout | 0 |  |  |
|21.smt2                                                      |   19.992s | 109.0MiB| timeout | 0 |  |  |
|70.smt2                                                      |   19.992s | 124.0MiB| timeout | 0 |  |  |
|07.smt2                                                      |   19.993s | 83.604MiB| timeout | 0 |  |  |
|92.smt2                                                      |   19.993s | 93.516MiB| timeout | 0 |  |  |
|14.smt2                                                      |   19.995s | 94.812MiB| timeout | 0 |  |  |
|65.smt2                                                      |   19.995s | 139.0MiB| timeout | 0 |  |  |
|04.smt2                                                      |   19.996s | 87.032MiB| timeout | 0 |  |  |
|147.smt2                                                     |   19.997s | 142.0MiB| timeout | 0 |  |  |
|181.smt2                                                     |   19.997s | 325.0MiB| timeout | 0 |  |  |
|55.smt2                                                      |   19.997s | 110.0MiB| timeout | 0 |  |  |
|31.smt2                                                      |   19.998s | 98.0MiB| timeout | 0 |  |  |
|175.smt2                                                     |   19.999s | 283.0MiB| timeout | 0 |  |  |
|40.smt2                                                      |   19.999s | 112.0MiB| timeout | 0 |  |  |
|172.smt2                                                     |   20.000s | 297.0MiB| timeout | 0 |  |  |
|59.smt2                                                      |   20.000s | 123.0MiB| timeout | 0 |  |  |
|177.smt2                                                     |   20.001s | 88.62MiB| timeout | 0 |  |  |
|171.smt2                                                     |   20.002s | 211.0MiB| timeout | 0 |  |  |
|08.smt2                                                      |   20.003s | 75.264MiB| timeout | 0 |  |  |
|63.smt2                                                      |   20.003s | 138.0MiB| timeout | 0 |  |  |
|103.smt2                                                     |   20.003s | 111.0MiB| timeout | 0 |  |  |
|41.smt2                                                      |   20.003s | 104.0MiB| timeout | 0 |  |  |
|183.smt2                                                     |   20.004s | 409.0MiB| timeout | 0 |  |  |
|85.smt2                                                      |   20.004s | 96.18MiB| timeout | 0 |  |  |
|66.smt2                                                      |   20.005s | 111.0MiB| timeout | 0 |  |  |
|185.smt2                                                     |   20.008s | 245.0MiB| timeout | 0 |  |  |
|58.smt2                                                      |   20.008s | 143.0MiB| timeout | 0 |  |  |
|11.smt2                                                      |   20.008s | 82.44MiB| timeout | 0 |  |  |
|156.smt2                                                     |   20.008s | 85.96MiB| timeout | 0 |  |  |
|03.smt2                                                      |   20.009s | 93.62MiB| timeout | 0 |  |  |
|23.smt2                                                      |   20.009s | 110.0MiB| timeout | 0 |  |  |
|74.smt2                                                      |   20.009s | 110.0MiB| timeout | 0 |  |  |
|77.smt2                                                      |   20.010s | 135.0MiB| timeout | 0 |  |  |
|05.smt2                                                      |   20.011s | 123.0MiB| timeout | 0 |  |  |
|100.smt2                                                     |   20.011s | 110.0MiB| timeout | 0 |  |  |
|84.smt2                                                      |   20.012s | 94.048MiB| timeout | 0 |  |  |
|125.smt2                                                     |   20.012s | 126.0MiB| timeout | 0 |  |  |
|169.smt2                                                     |   20.012s | 236.0MiB| timeout | 0 |  |  |
|48.smt2                                                      |   20.013s | 115.0MiB| timeout | 0 |  |  |
|32.smt2                                                      |   20.014s | 114.0MiB| timeout | 0 |  |  |
|155.smt2                                                     |   20.014s | 90.968MiB| timeout | 0 |  |  |
|133.smt2                                                     |   20.015s | 126.0MiB| timeout | 0 |  |  |
|68.smt2                                                      |   20.016s | 129.0MiB| timeout | 0 |  |  |
|184.smt2                                                     |   20.016s | 703.0MiB| timeout | 0 |  |  |
|43.smt2                                                      |   20.016s | 82.88MiB| timeout | 0 |  |  |
|94.smt2                                                      |   20.016s | 142.0MiB| timeout | 0 |  |  |
|30.smt2                                                      |   20.016s | 115.0MiB| timeout | 0 |  |  |
|179.smt2                                                     |   20.017s | 341.0MiB| timeout | 0 |  |  |
|57.smt2                                                      |   20.017s | 133.0MiB| timeout | 0 |  |  |
|02.smt2                                                      |   20.018s | 114.0MiB| timeout | 0 |  |  |
|91.smt2                                                      |   20.018s | 151.0MiB| timeout | 0 |  |  |
|18.smt2                                                      |   20.018s | 141.0MiB| timeout | 0 |  |  |
|123.smt2                                                     |   20.019s | 78.436MiB| timeout | 0 |  |  |
|78.smt2                                                      |   20.020s | 118.0MiB| timeout | 0 |  |  |
|150.smt2                                                     |   20.020s | 156.0MiB| timeout | 0 |  |  |
|26.smt2                                                      |   20.020s | 114.0MiB| timeout | 0 |  |  |
|89.smt2                                                      |   20.020s | 109.0MiB| timeout | 0 |  |  |
|53.smt2                                                      |   20.020s | 116.0MiB| timeout | 0 |  |  |
|130.smt2                                                     |   20.021s | 149.0MiB| timeout | 0 |  |  |
|50.smt2                                                      |   20.021s | 143.0MiB| timeout | 0 |  |  |
|153.smt2                                                     |   20.021s | 141.0MiB| timeout | 0 |  |  |
|95.smt2                                                      |   20.022s | 109.0MiB| timeout | 0 |  |  |
|39.smt2                                                      |   20.022s | 125.0MiB| timeout | 0 |  |  |
|154.smt2                                                     |   20.023s | 146.0MiB| timeout | 0 |  |  |
|134.smt2                                                     |   20.023s | 121.0MiB| timeout | 0 |  |  |
|22.smt2                                                      |   20.023s | 133.0MiB| timeout | 0 |  |  |
|112.smt2                                                     |   20.024s | 153.0MiB| timeout | 0 |  |  |
|168.smt2                                                     |   20.024s | 158.0MiB| timeout | 0 |  |  |
|24.smt2                                                      |   20.025s | 113.0MiB| timeout | 0 |  |  |
|52.smt2                                                      |   20.025s | 144.0MiB| timeout | 0 |  |  |
|144.smt2                                                     |   20.025s | 140.0MiB| timeout | 0 |  |  |
|93.smt2                                                      |   20.025s | 89.936MiB| timeout | 0 |  |  |
|90.smt2                                                      |   20.025s | 141.0MiB| timeout | 0 |  |  |
|75.smt2                                                      |   20.025s | 126.0MiB| timeout | 0 |  |  |
|105.smt2                                                     |   20.025s | 177.0MiB| timeout | 0 |  |  |
|135.smt2                                                     |   20.026s | 144.0MiB| timeout | 0 |  |  |
|82.smt2                                                      |   20.026s | 123.0MiB| timeout | 0 |  |  |
|151.smt2                                                     |   20.027s | 203.0MiB| timeout | 0 |  |  |
|51.smt2                                                      |   20.027s | 137.0MiB| timeout | 0 |  |  |
|45.smt2                                                      |   20.030s | 72.244MiB| timeout | 0 |  |  |
|60.smt2                                                      |   20.030s | 137.0MiB| timeout | 0 |  |  |
|122.smt2                                                     |   20.031s | 151.0MiB| timeout | 0 |  |  |
|47.smt2                                                      |   20.032s | 123.0MiB| timeout | 0 |  |  |
|138.smt2                                                     |   20.032s | 144.0MiB| timeout | 0 |  |  |
|119.smt2                                                     |   20.033s | 118.0MiB| timeout | 0 |  |  |
|143.smt2                                                     |   20.033s | 138.0MiB| timeout | 0 |  |  |
|54.smt2                                                      |   20.034s | 142.0MiB| timeout | 0 |  |  |
|49.smt2                                                      |   20.034s | 117.0MiB| timeout | 0 |  |  |
|158.smt2                                                     |   20.036s | 167.0MiB| timeout | 0 |  |  |
