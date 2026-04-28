Comparing data and data


# SUMMARY
- LHS tests = 44
- RHS tests = 44
- LHS success = 44  (100.0%)
- RHS success = 44  (100.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_NIA-timeout20min-FL2
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 214817d96aa5e7e5ee8209965723f1d886d0f3db
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_fl_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_NIA
Z3 commit message: modify the fallback policies for bb detection in batch mode but also in FL mode

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_NIA-timeout20min-FL2
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 214817d96aa5e7e5ee8209965723f1d886d0f3db
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_fl_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_NIA
Z3 commit message: modify the fallback policies for bb detection in batch mode but also in FL mode

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.180s  |1200.180s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.160s  |1200.160s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  57.815s  |  57.815s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.206s  |1200.206s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.392s  |1200.392s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.180s  |1200.180s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.337s  |1200.337s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.451s  |1200.451s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |   9.020s  |   9.020s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  14.103s  |  14.103s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.257s  |1200.257s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 517.008s  | 517.008s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  70.490s  |  70.490s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |  30.807s  |  30.807s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  27.773s  |  27.773s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   3.634s  |   3.634s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |1200.381s  |1200.381s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.094s  |1200.094s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.165s  |1200.165s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.261s  |1200.261s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.180s  |1200.180s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.160s  |1200.160s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  57.815s  |  57.815s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.206s  |1200.206s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.392s  |1200.392s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.180s  |1200.180s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.337s  |1200.337s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.451s  |1200.451s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |   9.020s  |   9.020s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  14.103s  |  14.103s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.257s  |1200.257s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 517.008s  | 517.008s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  70.490s  |  70.490s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |  30.807s  |  30.807s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  27.773s  |  27.773s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   3.634s  |   3.634s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |1200.381s  |1200.381s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.094s  |1200.094s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.165s  |1200.165s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.261s  |1200.261s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.180s  |1200.180s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.160s  |1200.160s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  57.815s  |  57.815s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.206s  |1200.206s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.392s  |1200.392s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.180s  |1200.180s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.337s  |1200.337s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.451s  |1200.451s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |   9.020s  |   9.020s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  14.103s  |  14.103s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.257s  |1200.257s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 517.008s  | 517.008s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  70.490s  |  70.490s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |  30.807s  |  30.807s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  27.773s  |  27.773s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   3.634s  |   3.634s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |1200.381s  |1200.381s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.094s  |1200.094s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.165s  |1200.165s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.261s  |1200.261s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.180s  |1200.180s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.160s  |1200.160s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  57.815s  |  57.815s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.206s  |1200.206s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.392s  |1200.392s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.180s  |1200.180s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.337s  |1200.337s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.451s  |1200.451s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |   9.020s  |   9.020s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  14.103s  |  14.103s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.257s  |1200.257s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 517.008s  | 517.008s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  70.490s  |  70.490s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |  30.807s  |  30.807s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  27.773s  |  27.773s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   3.634s  |   3.634s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |1200.381s  |1200.381s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.094s  |1200.094s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.165s  |1200.165s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.261s  |1200.261s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1202.037s |23.41GiB|
|scrambled87588.smt2                                                                        |1201.337s |14.849GiB|
|scrambled73755.smt2                                                                        |1200.499s |4908.0MiB|
|scrambled91750.smt2                                                                        |1200.458s |2688.0MiB|
|scrambled122926.smt2                                                                       |1200.451s |3958.0MiB|
|scrambled108663.smt2                                                                       |1200.392s |3244.0MiB|
|scrambled31071.smt2                                                                        |1200.381s |2414.0MiB|
|scrambled12033.smt2                                                                        |1200.337s |2878.0MiB|
|scrambled62032.smt2                                                                        |1200.304s |1766.0MiB|
|scrambled8852.smt2                                                                         |1200.278s |2028.0MiB|
|scrambled36790.smt2                                                                        |1200.261s |1758.0MiB|
|scrambled130111.smt2                                                                       |1200.257s |2086.0MiB|
|scrambled82760.smt2                                                                        |1200.254s |1589.0MiB|
|scrambled39467.smt2                                                                        |1200.250s |1770.0MiB|
|scrambled97386.smt2                                                                        |1200.248s |1633.0MiB|
|scrambled73281.smt2                                                                        |1200.241s |2248.0MiB|
|scrambled38587.smt2                                                                        |1200.223s |1611.0MiB|
|scrambled41135.smt2                                                                        |1200.210s |1687.0MiB|
|scrambled108406.smt2                                                                       |1200.206s |1638.0MiB|
|scrambled58311.smt2                                                                        |1200.205s |1559.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1202.037s |23.41GiB|
|scrambled87588.smt2                                                                        |1201.337s |14.849GiB|
|scrambled73755.smt2                                                                        |1200.499s |4908.0MiB|
|scrambled91750.smt2                                                                        |1200.458s |2688.0MiB|
|scrambled122926.smt2                                                                       |1200.451s |3958.0MiB|
|scrambled108663.smt2                                                                       |1200.392s |3244.0MiB|
|scrambled31071.smt2                                                                        |1200.381s |2414.0MiB|
|scrambled12033.smt2                                                                        |1200.337s |2878.0MiB|
|scrambled62032.smt2                                                                        |1200.304s |1766.0MiB|
|scrambled8852.smt2                                                                         |1200.278s |2028.0MiB|
|scrambled36790.smt2                                                                        |1200.261s |1758.0MiB|
|scrambled130111.smt2                                                                       |1200.257s |2086.0MiB|
|scrambled82760.smt2                                                                        |1200.254s |1589.0MiB|
|scrambled39467.smt2                                                                        |1200.250s |1770.0MiB|
|scrambled97386.smt2                                                                        |1200.248s |1633.0MiB|
|scrambled73281.smt2                                                                        |1200.241s |2248.0MiB|
|scrambled38587.smt2                                                                        |1200.223s |1611.0MiB|
|scrambled41135.smt2                                                                        |1200.210s |1687.0MiB|
|scrambled108406.smt2                                                                       |1200.206s |1638.0MiB|
|scrambled58311.smt2                                                                        |1200.205s |1559.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1237.0MiB|1237.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1373.0MiB|1373.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |424.0MiB|424.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |1638.0MiB|1638.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |3244.0MiB|3244.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1319.0MiB|1319.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2878.0MiB|2878.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3958.0MiB|3958.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |444.0MiB|444.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |439.0MiB|439.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |2086.0MiB|2086.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |6572.0MiB|6572.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |1268.0MiB|1268.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |645.0MiB|645.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |302.0MiB|302.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |245.0MiB|245.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |2414.0MiB|2414.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |584.0MiB|584.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |1175.0MiB|1175.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1758.0MiB|1758.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1237.0MiB|1237.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1373.0MiB|1373.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |424.0MiB|424.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |1638.0MiB|1638.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |3244.0MiB|3244.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1319.0MiB|1319.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2878.0MiB|2878.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3958.0MiB|3958.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |444.0MiB|444.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |439.0MiB|439.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |2086.0MiB|2086.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |6572.0MiB|6572.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |1268.0MiB|1268.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |645.0MiB|645.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |302.0MiB|302.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |245.0MiB|245.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |2414.0MiB|2414.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |584.0MiB|584.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |1175.0MiB|1175.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1758.0MiB|1758.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1237.0MiB|1237.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1373.0MiB|1373.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |424.0MiB|424.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |1638.0MiB|1638.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |3244.0MiB|3244.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1319.0MiB|1319.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2878.0MiB|2878.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3958.0MiB|3958.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |444.0MiB|444.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |439.0MiB|439.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |2086.0MiB|2086.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |6572.0MiB|6572.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |1268.0MiB|1268.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |645.0MiB|645.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |302.0MiB|302.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |245.0MiB|245.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |2414.0MiB|2414.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |584.0MiB|584.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |1175.0MiB|1175.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1758.0MiB|1758.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1237.0MiB|1237.0MiB|0B| 0.0%|
|scrambled101716.smt2                                                                        |1373.0MiB|1373.0MiB|0B| 0.0%|
|scrambled103775.smt2                                                                        |424.0MiB|424.0MiB|0B| 0.0%|
|scrambled108406.smt2                                                                        |1638.0MiB|1638.0MiB|0B| 0.0%|
|scrambled108663.smt2                                                                        |3244.0MiB|3244.0MiB|0B| 0.0%|
|scrambled119582.smt2                                                                        |1319.0MiB|1319.0MiB|0B| 0.0%|
|scrambled12033.smt2                                                                         |2878.0MiB|2878.0MiB|0B| 0.0%|
|scrambled122926.smt2                                                                        |3958.0MiB|3958.0MiB|0B| 0.0%|
|scrambled129467.smt2                                                                        |444.0MiB|444.0MiB|0B| 0.0%|
|scrambled12959.smt2                                                                         |439.0MiB|439.0MiB|0B| 0.0%|
|scrambled130111.smt2                                                                        |2086.0MiB|2086.0MiB|0B| 0.0%|
|scrambled14845.smt2                                                                         |6572.0MiB|6572.0MiB|0B| 0.0%|
|scrambled17293.smt2                                                                         |1268.0MiB|1268.0MiB|0B| 0.0%|
|scrambled28176.smt2                                                                         |645.0MiB|645.0MiB|0B| 0.0%|
|scrambled29780.smt2                                                                         |302.0MiB|302.0MiB|0B| 0.0%|
|scrambled30073.smt2                                                                         |245.0MiB|245.0MiB|0B| 0.0%|
|scrambled31071.smt2                                                                         |2414.0MiB|2414.0MiB|0B| 0.0%|
|scrambled31575.smt2                                                                         |584.0MiB|584.0MiB|0B| 0.0%|
|scrambled35280.smt2                                                                         |1175.0MiB|1175.0MiB|0B| 0.0%|
|scrambled36790.smt2                                                                         |1758.0MiB|1758.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1202.037s |23.41GiB|
|scrambled87588.smt2                                                                        |1201.337s |14.849GiB|
|scrambled14845.smt2                                                                        | 517.008s |6572.0MiB|
|scrambled73755.smt2                                                                        |1200.499s |4908.0MiB|
|scrambled122926.smt2                                                                       |1200.451s |3958.0MiB|
|scrambled108663.smt2                                                                       |1200.392s |3244.0MiB|
|scrambled12033.smt2                                                                        |1200.337s |2878.0MiB|
|scrambled91750.smt2                                                                        |1200.458s |2688.0MiB|
|scrambled31071.smt2                                                                        |1200.381s |2414.0MiB|
|scrambled73281.smt2                                                                        |1200.241s |2248.0MiB|
|scrambled130111.smt2                                                                       |1200.257s |2086.0MiB|
|scrambled8852.smt2                                                                         |1200.278s |2028.0MiB|
|scrambled39467.smt2                                                                        |1200.250s |1770.0MiB|
|scrambled62032.smt2                                                                        |1200.304s |1766.0MiB|
|scrambled47700.smt2                                                                        |1200.203s |1763.0MiB|
|scrambled36790.smt2                                                                        |1200.261s |1758.0MiB|
|scrambled41135.smt2                                                                        |1200.210s |1687.0MiB|
|scrambled96401.smt2                                                                        |1016.453s |1659.0MiB|
|scrambled79354.smt2                                                                        |1200.166s |1640.0MiB|
|scrambled108406.smt2                                                                       |1200.206s |1638.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled85357.smt2                                                                        |1202.037s |23.41GiB|
|scrambled87588.smt2                                                                        |1201.337s |14.849GiB|
|scrambled14845.smt2                                                                        | 517.008s |6572.0MiB|
|scrambled73755.smt2                                                                        |1200.499s |4908.0MiB|
|scrambled122926.smt2                                                                       |1200.451s |3958.0MiB|
|scrambled108663.smt2                                                                       |1200.392s |3244.0MiB|
|scrambled12033.smt2                                                                        |1200.337s |2878.0MiB|
|scrambled91750.smt2                                                                        |1200.458s |2688.0MiB|
|scrambled31071.smt2                                                                        |1200.381s |2414.0MiB|
|scrambled73281.smt2                                                                        |1200.241s |2248.0MiB|
|scrambled130111.smt2                                                                       |1200.257s |2086.0MiB|
|scrambled8852.smt2                                                                         |1200.278s |2028.0MiB|
|scrambled39467.smt2                                                                        |1200.250s |1770.0MiB|
|scrambled62032.smt2                                                                        |1200.304s |1766.0MiB|
|scrambled47700.smt2                                                                        |1200.203s |1763.0MiB|
|scrambled36790.smt2                                                                        |1200.261s |1758.0MiB|
|scrambled41135.smt2                                                                        |1200.210s |1687.0MiB|
|scrambled96401.smt2                                                                        |1016.453s |1659.0MiB|
|scrambled79354.smt2                                                                        |1200.166s |1640.0MiB|
|scrambled108406.smt2                                                                       |1200.206s |1638.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100714.smt2                                                                        |1200.180s  |1200.180s  |   0.000s  | 0.0%|
|scrambled101716.smt2                                                                        |1200.160s  |1200.160s  |   0.000s  | 0.0%|
|scrambled103775.smt2                                                                        |  57.815s  |  57.815s  |   0.000s  | 0.0%|
|scrambled108406.smt2                                                                        |1200.206s  |1200.206s  |   0.000s  | 0.0%|
|scrambled108663.smt2                                                                        |1200.392s  |1200.392s  |   0.000s  | 0.0%|
|scrambled119582.smt2                                                                        |1200.180s  |1200.180s  |   0.000s  | 0.0%|
|scrambled12033.smt2                                                                         |1200.337s  |1200.337s  |   0.000s  | 0.0%|
|scrambled122926.smt2                                                                        |1200.451s  |1200.451s  |   0.000s  | 0.0%|
|scrambled129467.smt2                                                                        |   9.020s  |   9.020s  |   0.000s  | 0.0%|
|scrambled12959.smt2                                                                         |  14.103s  |  14.103s  |   0.000s  | 0.0%|
|scrambled130111.smt2                                                                        |1200.257s  |1200.257s  |   0.000s  | 0.0%|
|scrambled14845.smt2                                                                         | 517.008s  | 517.008s  |   0.000s  | 0.0%|
|scrambled17293.smt2                                                                         |  70.490s  |  70.490s  |   0.000s  | 0.0%|
|scrambled28176.smt2                                                                         |  30.807s  |  30.807s  |   0.000s  | 0.0%|
|scrambled29780.smt2                                                                         |  27.773s  |  27.773s  |   0.000s  | 0.0%|
|scrambled30073.smt2                                                                         |   3.634s  |   3.634s  |   0.000s  | 0.0%|
|scrambled31071.smt2                                                                         |1200.381s  |1200.381s  |   0.000s  | 0.0%|
|scrambled31575.smt2                                                                         |1200.094s  |1200.094s  |   0.000s  | 0.0%|
|scrambled35280.smt2                                                                         |1200.165s  |1200.165s  |   0.000s  | 0.0%|
|scrambled36790.smt2                                                                         |1200.261s  |1200.261s  |   0.000s  | 0.0%|
|scrambled38587.smt2                                                                         |1200.223s  |1200.223s  |   0.000s  | 0.0%|
|scrambled39467.smt2                                                                         |1200.250s  |1200.250s  |   0.000s  | 0.0%|
|scrambled41135.smt2                                                                         |1200.210s  |1200.210s  |   0.000s  | 0.0%|
|scrambled47700.smt2                                                                         |1200.203s  |1200.203s  |   0.000s  | 0.0%|
|scrambled48569.smt2                                                                         |   5.974s  |   5.974s  |   0.000s  | 0.0%|
|scrambled50258.smt2                                                                         |   0.965s  |   0.965s  |   0.000s  | 0.0%|
|scrambled58311.smt2                                                                         |1200.205s  |1200.205s  |   0.000s  | 0.0%|
|scrambled61060.smt2                                                                         | 175.247s  | 175.247s  |   0.000s  | 0.0%|
|scrambled62032.smt2                                                                         |1200.304s  |1200.304s  |   0.000s  | 0.0%|
|scrambled73281.smt2                                                                         |1200.241s  |1200.241s  |   0.000s  | 0.0%|
|scrambled73755.smt2                                                                         |1200.499s  |1200.499s  |   0.000s  | 0.0%|
|scrambled79354.smt2                                                                         |1200.166s  |1200.166s  |   0.000s  | 0.0%|
|scrambled80288.smt2                                                                         | 181.153s  | 181.153s  |   0.000s  | 0.0%|
|scrambled82407.smt2                                                                         |   5.828s  |   5.828s  |   0.000s  | 0.0%|
|scrambled82760.smt2                                                                         |1200.254s  |1200.254s  |   0.000s  | 0.0%|
|scrambled85357.smt2                                                                         |1202.037s  |1202.037s  |   0.000s  | 0.0%|
|scrambled87588.smt2                                                                         |1201.337s  |1201.337s  |   0.000s  | 0.0%|
|scrambled8852.smt2                                                                          |1200.278s  |1200.278s  |   0.000s  | 0.0%|
|scrambled91750.smt2                                                                         |1200.458s  |1200.458s  |   0.000s  | 0.0%|
|scrambled9548.smt2                                                                          |   3.881s  |   3.881s  |   0.000s  | 0.0%|
|scrambled96401.smt2                                                                         |1016.453s  |1016.453s  |   0.000s  | 0.0%|
|scrambled97386.smt2                                                                         |1200.248s  |1200.248s  |   0.000s  | 0.0%|
|scrambled98111.smt2                                                                         |1200.140s  |1200.140s  |   0.000s  | 0.0%|
</details>
