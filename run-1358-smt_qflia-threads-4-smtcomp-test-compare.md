Comparing data and data


# SUMMARY
- LHS tests = 36
- RHS tests = 36
- LHS success = 36  (100.0%)
- RHS success = 36  (100.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt_qflia-threads-4-smtcomp-test
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 6b8cb1099d311aac105cfc6fa658466f4ef6af67
Z3 branch: backbones
Z3 options: "-T:15 -v:0 smt.threads=4 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_threads=1"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: restore unrelated code to master

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt_qflia-threads-4-smtcomp-test
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 6b8cb1099d311aac105cfc6fa658466f4ef6af67
Z3 branch: backbones
Z3 options: "-T:15 -v:0 smt.threads=4 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_threads=1"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: restore unrelated code to master

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |  15.189s  |  15.189s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |  15.319s  |  15.319s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |  15.162s  |  15.162s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |  15.147s  |  15.147s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |  15.191s  |  15.191s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |  15.109s  |  15.109s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |  15.192s  |  15.192s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |  15.166s  |  15.166s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  15.079s  |  15.079s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |  15.107s  |  15.107s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |  15.150s  |  15.150s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |  15.159s  |  15.159s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |  15.165s  |  15.165s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |  15.156s  |  15.156s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |  15.052s  |  15.052s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |  15.167s  |  15.167s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  15.143s  |  15.143s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  15.204s  |  15.204s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |  15.167s  |  15.167s  |   0.000s  | 0.0%|
|scrambled32836.smt2                                                                         |  15.120s  |  15.120s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |  15.189s  |  15.189s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |  15.319s  |  15.319s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |  15.162s  |  15.162s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |  15.147s  |  15.147s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |  15.191s  |  15.191s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |  15.109s  |  15.109s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |  15.192s  |  15.192s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |  15.166s  |  15.166s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  15.079s  |  15.079s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |  15.107s  |  15.107s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |  15.150s  |  15.150s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |  15.159s  |  15.159s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |  15.165s  |  15.165s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |  15.156s  |  15.156s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |  15.052s  |  15.052s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |  15.167s  |  15.167s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  15.143s  |  15.143s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  15.204s  |  15.204s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |  15.167s  |  15.167s  |   0.000s  | 0.0%|
|scrambled32836.smt2                                                                         |  15.120s  |  15.120s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |  15.189s  |  15.189s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |  15.319s  |  15.319s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |  15.162s  |  15.162s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |  15.147s  |  15.147s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |  15.191s  |  15.191s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |  15.109s  |  15.109s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |  15.192s  |  15.192s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |  15.166s  |  15.166s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  15.079s  |  15.079s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |  15.107s  |  15.107s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |  15.150s  |  15.150s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |  15.159s  |  15.159s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |  15.165s  |  15.165s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |  15.156s  |  15.156s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |  15.052s  |  15.052s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |  15.167s  |  15.167s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  15.143s  |  15.143s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  15.204s  |  15.204s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |  15.167s  |  15.167s  |   0.000s  | 0.0%|
|scrambled32836.smt2                                                                         |  15.120s  |  15.120s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |  15.189s  |  15.189s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |  15.319s  |  15.319s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |  15.162s  |  15.162s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |  15.147s  |  15.147s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |  15.191s  |  15.191s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |  15.109s  |  15.109s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |  15.192s  |  15.192s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |  15.166s  |  15.166s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  15.079s  |  15.079s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |  15.107s  |  15.107s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |  15.150s  |  15.150s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |  15.159s  |  15.159s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |  15.165s  |  15.165s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |  15.156s  |  15.156s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |  15.052s  |  15.052s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |  15.167s  |  15.167s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  15.143s  |  15.143s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  15.204s  |  15.204s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |  15.167s  |  15.167s  |   0.000s  | 0.0%|
|scrambled32836.smt2                                                                         |  15.120s  |  15.120s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled107115.smt2                                                                       |  15.319s |3299.0MiB|
|scrambled61922.smt2                                                                        |  15.260s |2177.0MiB|
|scrambled40621.smt2                                                                        |  15.254s |1770.0MiB|
|scrambled94658.smt2                                                                        |  15.218s |1351.0MiB|
|scrambled4198.smt2                                                                         |  15.209s |1407.0MiB|
|scrambled68944.smt2                                                                        |  15.204s |1464.0MiB|
|scrambled25238.smt2                                                                        |  15.204s |1309.0MiB|
|scrambled119331.smt2                                                                       |  15.192s |1508.0MiB|
|scrambled111627.smt2                                                                       |  15.191s |1580.0MiB|
|scrambled102166.smt2                                                                       |  15.189s |1715.0MiB|
|scrambled51053.smt2                                                                        |  15.189s |1278.0MiB|
|scrambled7741.smt2                                                                         |  15.185s |1166.0MiB|
|scrambled43577.smt2                                                                        |  15.185s |1535.0MiB|
|scrambled75189.smt2                                                                        |  15.180s |1712.0MiB|
|scrambled4299.smt2                                                                         |  15.176s |1558.0MiB|
|scrambled27843.smt2                                                                        |  15.167s |1633.0MiB|
|scrambled19335.smt2                                                                        |  15.167s |1498.0MiB|
|scrambled12042.smt2                                                                        |  15.166s |1367.0MiB|
|scrambled44911.smt2                                                                        |  15.165s |1024.0MiB|
|scrambled128874.smt2                                                                       |  15.165s |1253.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled107115.smt2                                                                       |  15.319s |3299.0MiB|
|scrambled61922.smt2                                                                        |  15.260s |2177.0MiB|
|scrambled40621.smt2                                                                        |  15.254s |1770.0MiB|
|scrambled94658.smt2                                                                        |  15.218s |1351.0MiB|
|scrambled4198.smt2                                                                         |  15.209s |1407.0MiB|
|scrambled68944.smt2                                                                        |  15.204s |1464.0MiB|
|scrambled25238.smt2                                                                        |  15.204s |1309.0MiB|
|scrambled119331.smt2                                                                       |  15.192s |1508.0MiB|
|scrambled111627.smt2                                                                       |  15.191s |1580.0MiB|
|scrambled102166.smt2                                                                       |  15.189s |1715.0MiB|
|scrambled51053.smt2                                                                        |  15.189s |1278.0MiB|
|scrambled7741.smt2                                                                         |  15.185s |1166.0MiB|
|scrambled43577.smt2                                                                        |  15.185s |1535.0MiB|
|scrambled75189.smt2                                                                        |  15.180s |1712.0MiB|
|scrambled4299.smt2                                                                         |  15.176s |1558.0MiB|
|scrambled27843.smt2                                                                        |  15.167s |1633.0MiB|
|scrambled19335.smt2                                                                        |  15.167s |1498.0MiB|
|scrambled12042.smt2                                                                        |  15.166s |1367.0MiB|
|scrambled44911.smt2                                                                        |  15.165s |1024.0MiB|
|scrambled128874.smt2                                                                       |  15.165s |1253.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1715.0MiB|1715.0MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |3299.0MiB|3299.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |1556.0MiB|1556.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |1443.0MiB|1443.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |1580.0MiB|1580.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |390.0MiB|390.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |1508.0MiB|1508.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |1367.0MiB|1367.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |477.0MiB|477.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |643.0MiB|643.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |1178.0MiB|1178.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |982.0MiB|982.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |1253.0MiB|1253.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |1297.0MiB|1297.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |141.0MiB|141.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |1498.0MiB|1498.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |631.0MiB|631.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |1309.0MiB|1309.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |1633.0MiB|1633.0MiB|0B| 0.0%|
|scrambled32836.smt2                                                                         |806.0MiB|806.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1715.0MiB|1715.0MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |3299.0MiB|3299.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |1556.0MiB|1556.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |1443.0MiB|1443.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |1580.0MiB|1580.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |390.0MiB|390.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |1508.0MiB|1508.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |1367.0MiB|1367.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |477.0MiB|477.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |643.0MiB|643.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |1178.0MiB|1178.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |982.0MiB|982.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |1253.0MiB|1253.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |1297.0MiB|1297.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |141.0MiB|141.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |1498.0MiB|1498.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |631.0MiB|631.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |1309.0MiB|1309.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |1633.0MiB|1633.0MiB|0B| 0.0%|
|scrambled32836.smt2                                                                         |806.0MiB|806.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1715.0MiB|1715.0MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |3299.0MiB|3299.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |1556.0MiB|1556.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |1443.0MiB|1443.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |1580.0MiB|1580.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |390.0MiB|390.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |1508.0MiB|1508.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |1367.0MiB|1367.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |477.0MiB|477.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |643.0MiB|643.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |1178.0MiB|1178.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |982.0MiB|982.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |1253.0MiB|1253.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |1297.0MiB|1297.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |141.0MiB|141.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |1498.0MiB|1498.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |631.0MiB|631.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |1309.0MiB|1309.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |1633.0MiB|1633.0MiB|0B| 0.0%|
|scrambled32836.smt2                                                                         |806.0MiB|806.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1715.0MiB|1715.0MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |3299.0MiB|3299.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |1556.0MiB|1556.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |1443.0MiB|1443.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |1580.0MiB|1580.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |390.0MiB|390.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |1508.0MiB|1508.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |1367.0MiB|1367.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |477.0MiB|477.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |643.0MiB|643.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |1178.0MiB|1178.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |982.0MiB|982.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |1253.0MiB|1253.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |1297.0MiB|1297.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |141.0MiB|141.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |1498.0MiB|1498.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |631.0MiB|631.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |1309.0MiB|1309.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |1633.0MiB|1633.0MiB|0B| 0.0%|
|scrambled32836.smt2                                                                         |806.0MiB|806.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled107115.smt2                                                                       |  15.319s |3299.0MiB|
|scrambled61922.smt2                                                                        |  15.260s |2177.0MiB|
|scrambled40621.smt2                                                                        |  15.254s |1770.0MiB|
|scrambled102166.smt2                                                                       |  15.189s |1715.0MiB|
|scrambled75189.smt2                                                                        |  15.180s |1712.0MiB|
|scrambled27843.smt2                                                                        |  15.167s |1633.0MiB|
|scrambled111627.smt2                                                                       |  15.191s |1580.0MiB|
|scrambled4299.smt2                                                                         |  15.176s |1558.0MiB|
|scrambled107826.smt2                                                                       |  15.162s |1556.0MiB|
|scrambled43577.smt2                                                                        |  15.185s |1535.0MiB|
|scrambled55680.smt2                                                                        |  15.163s |1515.0MiB|
|scrambled79760.smt2                                                                        |  15.158s |1515.0MiB|
|scrambled119331.smt2                                                                       |  15.192s |1508.0MiB|
|scrambled19335.smt2                                                                        |  15.167s |1498.0MiB|
|scrambled68944.smt2                                                                        |  15.204s |1464.0MiB|
|scrambled108840.smt2                                                                       |  15.147s |1443.0MiB|
|scrambled4198.smt2                                                                         |  15.209s |1407.0MiB|
|scrambled12042.smt2                                                                        |  15.166s |1367.0MiB|
|scrambled94658.smt2                                                                        |  15.218s |1351.0MiB|
|scrambled25238.smt2                                                                        |  15.204s |1309.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled107115.smt2                                                                       |  15.319s |3299.0MiB|
|scrambled61922.smt2                                                                        |  15.260s |2177.0MiB|
|scrambled40621.smt2                                                                        |  15.254s |1770.0MiB|
|scrambled102166.smt2                                                                       |  15.189s |1715.0MiB|
|scrambled75189.smt2                                                                        |  15.180s |1712.0MiB|
|scrambled27843.smt2                                                                        |  15.167s |1633.0MiB|
|scrambled111627.smt2                                                                       |  15.191s |1580.0MiB|
|scrambled4299.smt2                                                                         |  15.176s |1558.0MiB|
|scrambled107826.smt2                                                                       |  15.162s |1556.0MiB|
|scrambled43577.smt2                                                                        |  15.185s |1535.0MiB|
|scrambled55680.smt2                                                                        |  15.163s |1515.0MiB|
|scrambled79760.smt2                                                                        |  15.158s |1515.0MiB|
|scrambled119331.smt2                                                                       |  15.192s |1508.0MiB|
|scrambled19335.smt2                                                                        |  15.167s |1498.0MiB|
|scrambled68944.smt2                                                                        |  15.204s |1464.0MiB|
|scrambled108840.smt2                                                                       |  15.147s |1443.0MiB|
|scrambled4198.smt2                                                                         |  15.209s |1407.0MiB|
|scrambled12042.smt2                                                                        |  15.166s |1367.0MiB|
|scrambled94658.smt2                                                                        |  15.218s |1351.0MiB|
|scrambled25238.smt2                                                                        |  15.204s |1309.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |  15.189s  |  15.189s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |  15.319s  |  15.319s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |  15.162s  |  15.162s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |  15.147s  |  15.147s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |  15.191s  |  15.191s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |  15.109s  |  15.109s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |  15.192s  |  15.192s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |  15.166s  |  15.166s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  15.079s  |  15.079s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |  15.107s  |  15.107s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |  15.150s  |  15.150s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |  15.159s  |  15.159s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |  15.165s  |  15.165s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |  15.156s  |  15.156s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |  15.052s  |  15.052s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |  15.167s  |  15.167s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  15.143s  |  15.143s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  15.204s  |  15.204s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |  15.167s  |  15.167s  |   0.000s  | 0.0%|
|scrambled32836.smt2                                                                         |  15.120s  |  15.120s  |   0.000s  | 0.0%|
|scrambled40621.smt2                                                                         |  15.254s  |  15.254s  |   0.000s  | 0.0%|
|scrambled4198.smt2                                                                          |  15.209s  |  15.209s  |   0.000s  | 0.0%|
|scrambled4299.smt2                                                                          |  15.176s  |  15.176s  |   0.000s  | 0.0%|
|scrambled43577.smt2                                                                         |  15.185s  |  15.185s  |   0.000s  | 0.0%|
|scrambled44911.smt2                                                                         |  15.165s  |  15.165s  |   0.000s  | 0.0%|
|scrambled51053.smt2                                                                         |  15.189s  |  15.189s  |   0.000s  | 0.0%|
|scrambled55680.smt2                                                                         |  15.163s  |  15.163s  |   0.000s  | 0.0%|
|scrambled55777.smt2                                                                         |  15.124s  |  15.124s  |   0.000s  | 0.0%|
|scrambled61922.smt2                                                                         |  15.260s  |  15.260s  |   0.000s  | 0.0%|
|scrambled68944.smt2                                                                         |  15.204s  |  15.204s  |   0.000s  | 0.0%|
|scrambled72668.smt2                                                                         |  15.164s  |  15.164s  |   0.000s  | 0.0%|
|scrambled75189.smt2                                                                         |  15.180s  |  15.180s  |   0.000s  | 0.0%|
|scrambled7741.smt2                                                                          |  15.185s  |  15.185s  |   0.000s  | 0.0%|
|scrambled79760.smt2                                                                         |  15.158s  |  15.158s  |   0.000s  | 0.0%|
|scrambled94658.smt2                                                                         |  15.218s  |  15.218s  |   0.000s  | 0.0%|
</details>
