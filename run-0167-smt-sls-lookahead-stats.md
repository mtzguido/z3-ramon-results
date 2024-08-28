# data

* SAT 21
* UNSAT 0
* TIMEOUT 164
* UNKNOWN 0

* UNSET 1

* ERROR 1

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: with lookahead
Job tag: smt-sls-lookahead
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: fa22b646aa5965a8e4d79eef54e26707fe9931fc
Z3 branch: master
Z3 options: "-T:20 -v:2 -st sls.arith_use_lookahead=true tactic.default_tactic="(then simplify propagate-values solve-eqs simplify sls-smt)" model_validate=true"
Z3 inputs: inputs/QF_NIA_MCM
Z3 commit message: address some build warnings.

</pre>


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|06.smt2                                                      |    0.027s | 20.02MiB| sat | 0 |  |  |
|45.smt2                                                      |    0.030s | 20.288MiB| sat | 0 |  |  |
|107.smt2                                                     |    0.057s | 22.244MiB| sat | 0 |  |  |
|113.smt2                                                     |    0.061s | 21.644MiB| sat | 0 |  |  |
|12.smt2                                                      |    0.062s | 20.072MiB| sat | 0 |  |  |
|117.smt2                                                     |    0.068s | 22.264MiB| sat | 0 |  |  |
|109.smt2                                                     |    0.071s | 22.816MiB| sat | 0 |  |  |
|14.smt2                                                      |    0.105s | 21.22MiB| sat | 0 |  |  |
|118.smt2                                                     |    0.118s | 22.804MiB| sat | 0 |  |  |
|170.smt2                                                     |    0.307s | 26.576MiB| sat | 0 |  |  |
|164.smt2                                                     |    0.323s | 26.736MiB| sat | 0 |  |  |
|166.smt2                                                     |    0.353s | 26.756MiB| sat | 0 |  |  |
|115.smt2                                                     |    0.374s | 24.264MiB| sat | 0 |  |  |
|162.smt2                                                     |    0.536s | 26.688MiB| sat | 0 |  |  |
|104.smt2                                                     |    0.605s | 24.316MiB| sat | 0 |  |  |
|07.smt2                                                      |    0.607s | 21.82MiB| sat | 0 |  |  |
|43.smt2                                                      |    0.656s | 21.516MiB| sat | 0 |  |  |
|03.smt2                                                      |    1.133s | 22.184MiB| sat | 0 |  |  |
|177.smt2                                                     |    2.197s | 47.58MiB| sat | 0 |  |  |
|105.smt2                                                     |    8.888s | 33.452MiB| unset | 139 |  |  |
|152.smt2                                                     |    9.248s | 29.652MiB| sat | 0 |  |  |
|10.smt2                                                      |   11.007s | 22.1MiB| sat | 0 |  |  |
|153.smt2                                                     |   13.700s | 41.092MiB| timeout | 0 |  |  |
|119.smt2                                                     |   14.557s | 38.6MiB| timeout | 0 |  |  |
|30.smt2                                                      |   15.634s | 21.96MiB| timeout | 0 |  |  |
|74.smt2                                                      |   15.747s | 24.42MiB| timeout | 0 |  |  |
|96.smt2                                                      |   16.344s | 24.392MiB| timeout | 0 |  |  |
|60.smt2                                                      |   16.577s | 24.188MiB| timeout | 0 |  |  |
|17.smt2                                                      |   16.617s | 23.508MiB| timeout | 0 |  |  |
|18.smt2                                                      |   16.651s | 23.48MiB| timeout | 0 |  |  |
|36.smt2                                                      |   17.127s | 22.268MiB| timeout | 0 |  |  |
|148.smt2                                                     |   17.639s | 38.492MiB| timeout | 0 |  |  |
|124.smt2                                                     |   17.859s | 29.376MiB| timeout | 0 |  |  |
|09.smt2                                                      |   18.001s | 21.132MiB| timeout | 0 |  |  |
|150.smt2                                                     |   18.055s | 37.476MiB| timeout | 0 |  |  |
|106.smt2                                                     |   18.150s | 36.892MiB| timeout | 0 |  |  |
|173.smt2                                                     |   18.299s | 158.0MiB| timeout | 0 |  |  |
|23.smt2                                                      |   18.345s | 22.264MiB| timeout | 0 |  |  |
|143.smt2                                                     |   18.436s | 36.428MiB| timeout | 0 |  |  |
|42.smt2                                                      |   18.549s | 20.944MiB| timeout | 0 |  |  |
|145.smt2                                                     |   18.654s | 39.296MiB| timeout | 0 |  |  |
|183.smt2                                                     |   18.661s | 320.0MiB| timeout | 0 |  |  |
|99.smt2                                                      |   18.715s | 22.284MiB| timeout | 0 |  |  |
|168.smt2                                                     |   18.788s | 76.912MiB| timeout | 0 |  |  |
|98.smt2                                                      |   18.792s | 23.424MiB| timeout | 0 |  |  |
|11.smt2                                                      |   18.891s | 21.084MiB| timeout | 0 |  |  |
|161.smt2                                                     |   18.929s | 89.944MiB| timeout | 0 |  |  |
|129.smt2                                                     |   18.934s | 38.92MiB| timeout | 0 |  |  |
|94.smt2                                                      |   18.937s | 24.388MiB| timeout | 0 |  |  |
|79.smt2                                                      |   18.956s | 24.064MiB| timeout | 0 |  |  |
|147.smt2                                                     |   18.967s | 36.868MiB| timeout | 0 |  |  |
|165.smt2                                                     |   18.994s | 93.024MiB| timeout | 0 |  |  |
|02.smt2                                                      |   19.006s | 22.0MiB| timeout | 0 |  |  |
|71.smt2                                                      |   19.018s | 23.28MiB| timeout | 0 |  |  |
|91.smt2                                                      |   19.020s | 23.624MiB| timeout | 0 |  |  |
|38.smt2                                                      |   19.031s | 22.092MiB| timeout | 0 |  |  |
|27.smt2                                                      |   19.032s | 23.336MiB| timeout | 0 |  |  |
|49.smt2                                                      |   19.034s | 22.032MiB| timeout | 0 |  |  |
|52.smt2                                                      |   19.066s | 24.592MiB| timeout | 0 |  |  |
|83.smt2                                                      |   19.160s | 22.768MiB| timeout | 0 |  |  |
|64.smt2                                                      |   19.161s | 24.392MiB| timeout | 0 |  |  |
|40.smt2                                                      |   19.162s | 23.776MiB| timeout | 0 |  |  |
|108.smt2                                                     |   19.174s | 33.36MiB| timeout | 0 |  |  |
|138.smt2                                                     |   19.179s | 38.716MiB| timeout | 0 |  |  |
|13.smt2                                                      |   19.195s | 22.24MiB| timeout | 0 |  |  |
|69.smt2                                                      |   19.226s | 23.184MiB| timeout | 0 |  |  |
|157.smt2                                                     |   19.231s | 36.312MiB| timeout | 0 |  |  |
|19.smt2                                                      |   19.258s | 22.48MiB| timeout | 0 |  |  |
|121.smt2                                                     |   19.267s | 41.268MiB| timeout | 0 |  |  |
|08.smt2                                                      |   19.270s | 20.74MiB| timeout | 0 |  |  |
|04.smt2                                                      |   19.298s | 21.336MiB| timeout | 0 |  |  |
|39.smt2                                                      |   19.320s | 24.304MiB| timeout | 0 |  |  |
|144.smt2                                                     |   19.347s | 41.168MiB| timeout | 0 |  |  |
|66.smt2                                                      |   19.369s | 24.516MiB| timeout | 0 |  |  |
|101.smt2                                                     |   19.386s | 22.344MiB| timeout | 0 |  |  |
|179.smt2                                                     |   19.389s | 179.0MiB| timeout | 0 |  |  |
|93.smt2                                                      |   19.395s | 21.332MiB| timeout | 0 |  |  |
|184.smt2                                                     |   19.465s | 136.0MiB| timeout | 0 |  |  |
|178.smt2                                                     |   19.470s | 188.0MiB| timeout | 0 |  |  |
|141.smt2                                                     |   19.474s | 36.132MiB| timeout | 0 |  |  |
|76.smt2                                                      |   19.515s | 24.412MiB| timeout | 0 |  |  |
|82.smt2                                                      |   19.539s | 24.204MiB| timeout | 0 |  |  |
|110.smt2                                                     |   19.568s | 36.912MiB| timeout | 0 |  |  |
|29.smt2                                                      |   19.589s | 22.772MiB| timeout | 0 |  |  |
|159.smt2                                                     |   19.590s | 64.192MiB| timeout | 0 |  |  |
|182.smt2                                                     |   19.591s | 321.0MiB| timeout | 0 |  |  |
|155.smt2                                                     |   19.619s | 33.848MiB| timeout | 0 |  |  |
|20.smt2                                                      |   19.633s | 23.356MiB| timeout | 0 |  |  |
|86.smt2                                                      |   19.636s | 21.808MiB| timeout | 0 |  |  |
|15.smt2                                                      |   19.640s | 21.784MiB| timeout | 0 |  |  |
|53.smt2                                                      |   19.662s | 23.492MiB| timeout | 0 |  |  |
|97.smt2                                                      |   19.674s | 23.324MiB| timeout | 0 |  |  |
|130.smt2                                                     |   19.709s | 36.496MiB| timeout | 0 |  |  |
|128.smt2                                                     |   19.710s | 36.936MiB| timeout | 0 |  |  |
|102.smt2                                                     |   19.737s | 24.384MiB| timeout | 0 |  |  |
|142.smt2                                                     |   19.740s | 38.372MiB| timeout | 0 |  |  |
|132.smt2                                                     |   19.742s | 40.092MiB| timeout | 0 |  |  |
|24.smt2                                                      |   19.743s | 23.46MiB| timeout | 0 |  |  |
|16.smt2                                                      |   19.747s | 24.416MiB| timeout | 0 |  |  |
|90.smt2                                                      |   19.752s | 24.392MiB| timeout | 0 |  |  |
|151.smt2                                                     |   19.756s | 36.896MiB| timeout | 0 |  |  |
|120.smt2                                                     |   19.761s | 38.6MiB| timeout | 0 |  |  |
|33.smt2                                                      |   19.769s | 22.004MiB| timeout | 0 |  |  |
|163.smt2                                                     |   19.770s | 90.96MiB| timeout | 0 |  |  |
|51.smt2                                                      |   19.770s | 22.452MiB| timeout | 0 |  |  |
|65.smt2                                                      |   19.774s | 23.416MiB| timeout | 0 |  |  |
|149.smt2                                                     |   19.776s | 39.06MiB| timeout | 0 |  |  |
|180.smt2                                                     |   19.782s | 179.0MiB| timeout | 0 |  |  |
|59.smt2                                                      |   19.813s | 23.68MiB| timeout | 0 |  |  |
|133.smt2                                                     |   19.823s | 38.508MiB| timeout | 0 |  |  |
|174.smt2                                                     |   19.832s | 152.0MiB| timeout | 0 |  |  |
|127.smt2                                                     |   19.848s | 38.56MiB| timeout | 0 |  |  |
|47.smt2                                                      |   19.858s | 23.424MiB| timeout | 0 |  |  |
|146.smt2                                                     |   19.864s | 38.94MiB| timeout | 0 |  |  |
|62.smt2                                                      |   19.867s | 24.196MiB| timeout | 0 |  |  |
|125.smt2                                                     |   19.873s | 41.268MiB| timeout | 0 |  |  |
|160.smt2                                                     |   19.874s | 67.556MiB| timeout | 0 |  |  |
|50.smt2                                                      |   19.875s | 23.388MiB| timeout | 0 |  |  |
|28.smt2                                                      |   19.879s | 22.448MiB| timeout | 0 |  |  |
|167.smt2                                                     |   19.884s | 68.088MiB| timeout | 0 |  |  |
|186.smt2                                                     |   19.894s | 245.0MiB| timeout | 0 |  |  |
|01.smt2                                                      |   19.899s | 22.572MiB| timeout | 0 |  |  |
|154.smt2                                                     |   19.912s | 38.52MiB| timeout | 0 |  |  |
|70.smt2                                                      |   19.914s | 24.26MiB| timeout | 0 |  |  |
|26.smt2                                                      |   19.914s | 22.292MiB| timeout | 0 |  |  |
|88.smt2                                                      |   19.914s | 24.448MiB| timeout | 0 |  |  |
|181.smt2                                                     |   19.919s | 183.0MiB| timeout | 0 |  |  |
|112.smt2                                                     |   19.925s | 33.352MiB| timeout | 0 |  |  |
|111.smt2                                                     |   19.925s | 33.296MiB| timeout | 0 |  |  |
|156.smt2                                                     |   19.927s | 31.86MiB| timeout | 0 |  |  |
|61.smt2                                                      |   19.928s | 23.36MiB| timeout | 0 |  |  |
|131.smt2                                                     |   19.929s | 26.444MiB| timeout | 0 |  |  |
|05.smt2                                                      |   19.937s | 22.312MiB| timeout | 0 |  |  |
|37.smt2                                                      |   19.938s | 23.42MiB| timeout | 0 |  |  |
|116.smt2                                                     |   19.938s | 39.076MiB| timeout | 0 |  |  |
|103.smt2                                                     |   19.940s | 23.46MiB| timeout | 0 |  |  |
|72.smt2                                                      |   19.944s | 23.324MiB| timeout | 0 |  |  |
|41.smt2                                                      |   19.950s | 21.492MiB| timeout | 0 |  |  |
|122.smt2                                                     |   19.951s | 38.568MiB| timeout | 0 |  |  |
|139.smt2                                                     |   19.952s | 31.212MiB| timeout | 0 |  |  |
|140.smt2                                                     |   19.953s | 37.72MiB| timeout | 0 |  |  |
|114.smt2                                                     |   19.957s | 31.768MiB| timeout | 0 |  |  |
|175.smt2                                                     |   19.960s | 152.0MiB| timeout | 0 |  |  |
|100.smt2                                                     |   19.961s | 23.292MiB| timeout | 0 |  |  |
|92.smt2                                                      |   19.961s | 22.324MiB| timeout | 0 |  |  |
|176.smt2                                                     |   19.965s | 176.0MiB| timeout | 0 |  |  |
|81.smt2                                                      |   19.966s | 23.56MiB| timeout | 0 |  |  |
|75.smt2                                                      |   19.966s | 23.324MiB| timeout | 0 |  |  |
|55.smt2                                                      |   19.967s | 22.444MiB| timeout | 0 |  |  |
|80.smt2                                                      |   19.968s | 24.328MiB| timeout | 0 |  |  |
|84.smt2                                                      |   19.968s | 21.56MiB| timeout | 0 |  |  |
|137.smt2                                                     |   19.969s | 38.6MiB| timeout | 0 |  |  |
|21.smt2                                                      |   19.971s | 22.288MiB| timeout | 0 |  |  |
|34.smt2                                                      |   19.974s | 21.236MiB| timeout | 0 |  |  |
|68.smt2                                                      |   19.976s | 24.14MiB| timeout | 0 |  |  |
|46.smt2                                                      |   19.977s | 24.116MiB| timeout | 0 |  |  |
|63.smt2                                                      |   19.981s | 23.46MiB| timeout | 0 |  |  |
|171.smt2                                                     |   19.981s | 68.516MiB| timeout | 0 |  |  |
|134.smt2                                                     |   19.987s | 38.576MiB| timeout | 0 |  |  |
|126.smt2                                                     |   19.987s | 38.96MiB| timeout | 0 |  |  |
|67.smt2                                                      |   19.989s | 23.372MiB| timeout | 0 |  |  |
|44.smt2                                                      |   19.991s | 20.74MiB| timeout | 0 |  |  |
|48.smt2                                                      |   19.991s | 23.044MiB| timeout | 0 |  |  |
|89.smt2                                                      |   19.991s | 23.372MiB| timeout | 0 |  |  |
|56.smt2                                                      |   19.994s | 25.844MiB| timeout | 0 |  |  |
|77.smt2                                                      |   19.996s | 23.46MiB| timeout | 0 |  |  |
|95.smt2                                                      |   19.996s | 23.456MiB| timeout | 0 |  |  |
|85.smt2                                                      |   19.997s | 22.456MiB| timeout | 0 |  |  |
|22.smt2                                                      |   19.997s | 23.416MiB| timeout | 0 |  |  |
|57.smt2                                                      |   19.997s | 24.396MiB| timeout | 0 |  |  |
|25.smt2                                                      |   19.998s | 22.224MiB| timeout | 0 |  |  |
|54.smt2                                                      |   19.998s | 23.348MiB| timeout | 0 |  |  |
|136.smt2                                                     |   20.000s | 38.592MiB| timeout | 0 |  |  |
|31.smt2                                                      |   20.001s | 23.26MiB| timeout | 0 |  |  |
|78.smt2                                                      |   20.003s | 25.644MiB| timeout | 0 |  |  |
|123.smt2                                                     |   20.003s | 31.132MiB| timeout | 0 |  |  |
|32.smt2                                                      |   20.005s | 22.224MiB| timeout | 0 |  |  |
|158.smt2                                                     |   20.007s | 65.932MiB| timeout | 0 |  |  |
|172.smt2                                                     |   20.008s | 176.0MiB| timeout | 0 |  |  |
|35.smt2                                                      |   20.011s | 22.996MiB| timeout | 0 |  |  |
|169.smt2                                                     |   20.017s | 92.54MiB| timeout | 0 |  |  |
|135.smt2                                                     |   20.017s | 41.232MiB| timeout | 0 |  |  |
|185.smt2                                                     |   20.018s | 245.0MiB| timeout | 0 |  |  |
|58.smt2                                                      |   20.060s | 24.38MiB| timeout | 0 |  |  |
|87.smt2                                                      |   20.061s | 21.08MiB| timeout | 0 |  |  |
|73.smt2                                                      |   20.422s | 22.6MiB| timeout | 0 |  |  |
