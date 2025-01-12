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
Job description: MCM with basic SLS - 60 sec
Job tag: smt-sls-60
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: 9770c005926e2085d4ede18f03d56cb67d762d84
Z3 branch: master
Z3 options: "-T:60 -v:2 -st sls.arith_use_lookahead=true tactic.default_tactic="(then simplify propagate-values solve-eqs simplify sls-smt)" model_validate=true"
Z3 inputs: inputs/QF_NIA_MCM
Z3 commit message: adjust heuristic in random-inc-dec for finite domains

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|12.smt2                                                      |    0.025s | 20.068MiB| sat | 0 |  |  |
|06.smt2                                                      |    0.026s | 20.044MiB| sat | 0 |  |  |
|113.smt2                                                     |    0.055s | 21.604MiB| sat | 0 |  |  |
|107.smt2                                                     |    0.057s | 22.16MiB| sat | 0 |  |  |
|45.smt2                                                      |    0.066s | 20.204MiB| sat | 0 |  |  |
|117.smt2                                                     |    0.069s | 22.308MiB| sat | 0 |  |  |
|109.smt2                                                     |    0.074s | 22.936MiB| sat | 0 |  |  |
|118.smt2                                                     |    0.123s | 22.856MiB| sat | 0 |  |  |
|170.smt2                                                     |    0.262s | 26.596MiB| sat | 0 |  |  |
|43.smt2                                                      |    0.326s | 21.612MiB| sat | 0 |  |  |
|164.smt2                                                     |    0.339s | 26.616MiB| sat | 0 |  |  |
|07.smt2                                                      |    0.434s | 21.612MiB| sat | 0 |  |  |
|166.smt2                                                     |    0.437s | 26.756MiB| sat | 0 |  |  |
|162.smt2                                                     |    0.535s | 26.628MiB| sat | 0 |  |  |
|177.smt2                                                     |    1.528s | 47.484MiB| sat | 0 |  |  |
|115.smt2                                                     |    1.749s | 24.34MiB| sat | 0 |  |  |
|104.smt2                                                     |    3.337s | 24.304MiB| sat | 0 |  |  |
|03.smt2                                                      |    3.461s | 22.176MiB| sat | 0 |  |  |
|152.smt2                                                     |    5.355s | 29.688MiB| sat | 0 |  |  |
|10.smt2                                                      |    5.981s | 21.876MiB| sat | 0 |  |  |
|14.smt2                                                      |    9.580s | 21.512MiB| sat | 0 |  |  |
|139.smt2                                                     |   20.115s | 31.504MiB| sat | 0 |  |  |
|01.smt2                                                      |   29.683s | 22.464MiB| sat | 0 |  |  |
|33.smt2                                                      |   33.962s | 21.976MiB| sat | 0 |  |  |
|123.smt2                                                     |   35.297s | 30.96MiB| sat | 0 |  |  |
|15.smt2                                                      |   54.191s | 21.704MiB| sat | 0 |  |  |
|141.smt2                                                     |   57.588s | 36.288MiB| timeout | 0 |  |  |
|82.smt2                                                      |   58.740s | 24.116MiB| timeout | 0 |  |  |
|148.smt2                                                     |   58.845s | 38.636MiB| timeout | 0 |  |  |
|101.smt2                                                     |   58.952s | 22.48MiB| timeout | 0 |  |  |
|93.smt2                                                      |   59.132s | 21.332MiB| timeout | 0 |  |  |
|37.smt2                                                      |   59.161s | 23.38MiB| timeout | 0 |  |  |
|146.smt2                                                     |   59.225s | 39.248MiB| timeout | 0 |  |  |
|154.smt2                                                     |   59.376s | 38.728MiB| timeout | 0 |  |  |
|89.smt2                                                      |   59.449s | 23.632MiB| timeout | 0 |  |  |
|120.smt2                                                     |   59.478s | 38.596MiB| timeout | 0 |  |  |
|74.smt2                                                      |   59.484s | 24.364MiB| timeout | 0 |  |  |
|126.smt2                                                     |   59.485s | 39.244MiB| timeout | 0 |  |  |
|171.smt2                                                     |   59.497s | 67.732MiB| timeout | 0 |  |  |
|180.smt2                                                     |   59.502s | 179.0MiB| timeout | 0 |  |  |
|127.smt2                                                     |   59.512s | 39.0MiB| timeout | 0 |  |  |
|95.smt2                                                      |   59.518s | 23.608MiB| timeout | 0 |  |  |
|136.smt2                                                     |   59.542s | 38.672MiB| timeout | 0 |  |  |
|24.smt2                                                      |   59.552s | 23.54MiB| timeout | 0 |  |  |
|121.smt2                                                     |   59.554s | 41.364MiB| timeout | 0 |  |  |
|159.smt2                                                     |   59.555s | 63.992MiB| timeout | 0 |  |  |
|72.smt2                                                      |   59.557s | 23.704MiB| timeout | 0 |  |  |
|106.smt2                                                     |   59.559s | 36.932MiB| timeout | 0 |  |  |
|160.smt2                                                     |   59.562s | 67.78MiB| timeout | 0 |  |  |
|80.smt2                                                      |   59.571s | 24.412MiB| timeout | 0 |  |  |
|163.smt2                                                     |   59.578s | 85.916MiB| timeout | 0 |  |  |
|48.smt2                                                      |   59.599s | 22.832MiB| timeout | 0 |  |  |
|90.smt2                                                      |   59.618s | 24.38MiB| timeout | 0 |  |  |
|137.smt2                                                     |   59.623s | 38.684MiB| timeout | 0 |  |  |
|83.smt2                                                      |   59.625s | 22.8MiB| timeout | 0 |  |  |
|76.smt2                                                      |   59.628s | 24.308MiB| timeout | 0 |  |  |
|31.smt2                                                      |   59.634s | 23.28MiB| timeout | 0 |  |  |
|144.smt2                                                     |   59.651s | 41.304MiB| timeout | 0 |  |  |
|173.smt2                                                     |   59.658s | 159.0MiB| timeout | 0 |  |  |
|105.smt2                                                     |   59.667s | 33.492MiB| timeout | 0 |  |  |
|34.smt2                                                      |   59.671s | 21.104MiB| timeout | 0 |  |  |
|73.smt2                                                      |   59.673s | 22.68MiB| timeout | 0 |  |  |
|150.smt2                                                     |   59.677s | 37.508MiB| timeout | 0 |  |  |
|08.smt2                                                      |   59.686s | 21.004MiB| timeout | 0 |  |  |
|84.smt2                                                      |   59.689s | 21.324MiB| timeout | 0 |  |  |
|61.smt2                                                      |   59.689s | 23.46MiB| timeout | 0 |  |  |
|91.smt2                                                      |   59.696s | 23.452MiB| timeout | 0 |  |  |
|54.smt2                                                      |   59.697s | 23.528MiB| timeout | 0 |  |  |
|94.smt2                                                      |   59.701s | 24.376MiB| timeout | 0 |  |  |
|71.smt2                                                      |   59.703s | 23.58MiB| timeout | 0 |  |  |
|69.smt2                                                      |   59.712s | 23.384MiB| timeout | 0 |  |  |
|143.smt2                                                     |   59.713s | 36.332MiB| timeout | 0 |  |  |
|172.smt2                                                     |   59.722s | 176.0MiB| timeout | 0 |  |  |
|147.smt2                                                     |   59.730s | 36.668MiB| timeout | 0 |  |  |
|60.smt2                                                      |   59.740s | 24.252MiB| timeout | 0 |  |  |
|17.smt2                                                      |   59.741s | 23.356MiB| timeout | 0 |  |  |
|66.smt2                                                      |   59.751s | 24.608MiB| timeout | 0 |  |  |
|108.smt2                                                     |   59.751s | 33.832MiB| timeout | 0 |  |  |
|79.smt2                                                      |   59.759s | 24.14MiB| timeout | 0 |  |  |
|36.smt2                                                      |   59.762s | 22.228MiB| timeout | 0 |  |  |
|161.smt2                                                     |   59.767s | 89.052MiB| timeout | 0 |  |  |
|86.smt2                                                      |   59.771s | 21.732MiB| timeout | 0 |  |  |
|21.smt2                                                      |   59.773s | 22.256MiB| timeout | 0 |  |  |
|125.smt2                                                     |   59.774s | 41.332MiB| timeout | 0 |  |  |
|179.smt2                                                     |   59.775s | 179.0MiB| timeout | 0 |  |  |
|186.smt2                                                     |   59.776s | 711.0MiB| timeout | 0 |  |  |
|02.smt2                                                      |   59.777s | 22.252MiB| timeout | 0 |  |  |
|174.smt2                                                     |   59.777s | 152.0MiB| timeout | 0 |  |  |
|50.smt2                                                      |   59.778s | 23.592MiB| timeout | 0 |  |  |
|119.smt2                                                     |   59.785s | 38.764MiB| timeout | 0 |  |  |
|135.smt2                                                     |   59.792s | 41.404MiB| timeout | 0 |  |  |
|25.smt2                                                      |   59.799s | 22.252MiB| timeout | 0 |  |  |
|29.smt2                                                      |   59.800s | 22.804MiB| timeout | 0 |  |  |
|70.smt2                                                      |   59.803s | 24.2MiB| timeout | 0 |  |  |
|131.smt2                                                     |   59.808s | 26.336MiB| timeout | 0 |  |  |
|140.smt2                                                     |   59.811s | 37.708MiB| timeout | 0 |  |  |
|52.smt2                                                      |   59.816s | 24.496MiB| timeout | 0 |  |  |
|77.smt2                                                      |   59.820s | 23.584MiB| timeout | 0 |  |  |
|75.smt2                                                      |   59.820s | 23.488MiB| timeout | 0 |  |  |
|129.smt2                                                     |   59.826s | 39.1MiB| timeout | 0 |  |  |
|99.smt2                                                      |   59.830s | 22.184MiB| timeout | 0 |  |  |
|155.smt2                                                     |   59.836s | 34.22MiB| timeout | 0 |  |  |
|149.smt2                                                     |   59.837s | 39.12MiB| timeout | 0 |  |  |
|39.smt2                                                      |   59.839s | 24.568MiB| timeout | 0 |  |  |
|168.smt2                                                     |   59.839s | 76.724MiB| timeout | 0 |  |  |
|185.smt2                                                     |   59.842s | 690.0MiB| timeout | 0 |  |  |
|102.smt2                                                     |   59.844s | 24.548MiB| timeout | 0 |  |  |
|181.smt2                                                     |   59.845s | 185.0MiB| timeout | 0 |  |  |
|110.smt2                                                     |   59.846s | 37.012MiB| timeout | 0 |  |  |
|156.smt2                                                     |   59.849s | 31.88MiB| timeout | 0 |  |  |
|22.smt2                                                      |   59.850s | 23.368MiB| timeout | 0 |  |  |
|64.smt2                                                      |   59.852s | 24.38MiB| timeout | 0 |  |  |
|169.smt2                                                     |   59.852s | 93.032MiB| timeout | 0 |  |  |
|23.smt2                                                      |   59.853s | 22.576MiB| timeout | 0 |  |  |
|47.smt2                                                      |   59.856s | 23.236MiB| timeout | 0 |  |  |
|128.smt2                                                     |   59.862s | 36.92MiB| timeout | 0 |  |  |
|96.smt2                                                      |   59.864s | 24.46MiB| timeout | 0 |  |  |
|114.smt2                                                     |   59.866s | 31.656MiB| timeout | 0 |  |  |
|68.smt2                                                      |   59.871s | 24.58MiB| timeout | 0 |  |  |
|116.smt2                                                     |   59.872s | 39.14MiB| timeout | 0 |  |  |
|100.smt2                                                     |   59.873s | 23.464MiB| timeout | 0 |  |  |
|97.smt2                                                      |   59.874s | 23.52MiB| timeout | 0 |  |  |
|11.smt2                                                      |   59.891s | 21.304MiB| timeout | 0 |  |  |
|56.smt2                                                      |   59.892s | 25.86MiB| timeout | 0 |  |  |
|53.smt2                                                      |   59.899s | 23.62MiB| timeout | 0 |  |  |
|09.smt2                                                      |   59.900s | 21.364MiB| timeout | 0 |  |  |
|145.smt2                                                     |   59.900s | 38.836MiB| timeout | 0 |  |  |
|81.smt2                                                      |   59.904s | 23.624MiB| timeout | 0 |  |  |
|40.smt2                                                      |   59.908s | 23.364MiB| timeout | 0 |  |  |
|184.smt2                                                     |   59.909s | 473.0MiB| timeout | 0 |  |  |
|44.smt2                                                      |   59.912s | 21.016MiB| timeout | 0 |  |  |
|65.smt2                                                      |   59.912s | 23.576MiB| timeout | 0 |  |  |
|20.smt2                                                      |   59.915s | 23.36MiB| timeout | 0 |  |  |
|26.smt2                                                      |   59.917s | 22.34MiB| timeout | 0 |  |  |
|78.smt2                                                      |   59.918s | 25.608MiB| timeout | 0 |  |  |
|165.smt2                                                     |   59.918s | 93.064MiB| timeout | 0 |  |  |
|28.smt2                                                      |   59.919s | 22.512MiB| timeout | 0 |  |  |
|55.smt2                                                      |   59.924s | 22.312MiB| timeout | 0 |  |  |
|151.smt2                                                     |   59.925s | 36.448MiB| timeout | 0 |  |  |
|182.smt2                                                     |   59.927s | 319.0MiB| timeout | 0 |  |  |
|183.smt2                                                     |   59.928s | 320.0MiB| timeout | 0 |  |  |
|58.smt2                                                      |   59.930s | 24.488MiB| timeout | 0 |  |  |
|133.smt2                                                     |   59.932s | 38.448MiB| timeout | 0 |  |  |
|46.smt2                                                      |   59.940s | 24.136MiB| timeout | 0 |  |  |
|142.smt2                                                     |   59.941s | 38.472MiB| timeout | 0 |  |  |
|157.smt2                                                     |   59.941s | 36.416MiB| timeout | 0 |  |  |
|41.smt2                                                      |   59.941s | 21.78MiB| timeout | 0 |  |  |
|130.smt2                                                     |   59.943s | 36.608MiB| timeout | 0 |  |  |
|59.smt2                                                      |   59.944s | 23.88MiB| timeout | 0 |  |  |
|88.smt2                                                      |   59.944s | 24.608MiB| timeout | 0 |  |  |
|134.smt2                                                     |   59.945s | 38.7MiB| timeout | 0 |  |  |
|63.smt2                                                      |   59.946s | 23.576MiB| timeout | 0 |  |  |
|103.smt2                                                     |   59.950s | 23.476MiB| timeout | 0 |  |  |
|176.smt2                                                     |   59.951s | 176.0MiB| timeout | 0 |  |  |
|158.smt2                                                     |   59.953s | 66.904MiB| timeout | 0 |  |  |
|18.smt2                                                      |   59.953s | 23.672MiB| timeout | 0 |  |  |
|62.smt2                                                      |   59.956s | 24.572MiB| timeout | 0 |  |  |
|38.smt2                                                      |   59.958s | 22.2MiB| timeout | 0 |  |  |
|27.smt2                                                      |   59.961s | 23.596MiB| timeout | 0 |  |  |
|16.smt2                                                      |   59.961s | 24.396MiB| timeout | 0 |  |  |
|153.smt2                                                     |   59.962s | 41.268MiB| timeout | 0 |  |  |
|175.smt2                                                     |   59.964s | 152.0MiB| timeout | 0 |  |  |
|122.smt2                                                     |   59.966s | 38.624MiB| timeout | 0 |  |  |
|124.smt2                                                     |   59.967s | 29.54MiB| timeout | 0 |  |  |
|67.smt2                                                      |   59.980s | 23.892MiB| timeout | 0 |  |  |
|57.smt2                                                      |   59.981s | 24.3MiB| timeout | 0 |  |  |
|42.smt2                                                      |   59.983s | 20.916MiB| timeout | 0 |  |  |
|167.smt2                                                     |   59.983s | 68.376MiB| timeout | 0 |  |  |
|132.smt2                                                     |   59.984s | 40.3MiB| timeout | 0 |  |  |
|35.smt2                                                      |   59.984s | 22.764MiB| timeout | 0 |  |  |
|04.smt2                                                      |   59.984s | 21.324MiB| timeout | 0 |  |  |
|87.smt2                                                      |   59.988s | 21.108MiB| timeout | 0 |  |  |
|13.smt2                                                      |   59.990s | 22.432MiB| timeout | 0 |  |  |
|178.smt2                                                     |   59.991s | 189.0MiB| timeout | 0 |  |  |
|05.smt2                                                      |   59.993s | 22.508MiB| timeout | 0 |  |  |
|30.smt2                                                      |   59.994s | 22.08MiB| timeout | 0 |  |  |
|51.smt2                                                      |   59.996s | 22.484MiB| timeout | 0 |  |  |
|112.smt2                                                     |   59.997s | 33.352MiB| timeout | 0 |  |  |
|138.smt2                                                     |   59.997s | 38.892MiB| timeout | 0 |  |  |
|98.smt2                                                      |   60.000s | 23.312MiB| timeout | 0 |  |  |
|32.smt2                                                      |   60.002s | 22.224MiB| timeout | 0 |  |  |
|92.smt2                                                      |   60.002s | 22.364MiB| timeout | 0 |  |  |
|85.smt2                                                      |   60.003s | 22.656MiB| timeout | 0 |  |  |
|111.smt2                                                     |   60.003s | 33.316MiB| timeout | 0 |  |  |
|19.smt2                                                      |   60.005s | 22.316MiB| timeout | 0 |  |  |
|49.smt2                                                      |   60.024s | 22.192MiB| timeout | 0 |  |  |
