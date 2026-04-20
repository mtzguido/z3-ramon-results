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
Job tag: Z3-threads-4-smtcomp2025-QF_LIA-timeout_20min-vsids-bb2
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: c5aca49e70b70d2369035ad83eb4c9ad36027da1
Z3 branch: backbones
Z3 options: "-T:60 -v:0 smt.threads=4 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: change split policy from lightweight proof skeleton to VSIDS. NOTE: enabling local bb will mess with this since we aren't restoring activities right now

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-4-smtcomp2025-QF_LIA-timeout_20min-vsids-bb2
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: c5aca49e70b70d2369035ad83eb4c9ad36027da1
Z3 branch: backbones
Z3 options: "-T:60 -v:0 smt.threads=4 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: change split policy from lightweight proof skeleton to VSIDS. NOTE: enabling local bb will mess with this since we aren't restoring activities right now

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |  60.456s  |  60.456s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |  60.012s  |  60.012s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |  60.655s  |  60.655s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |  60.646s  |  60.646s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |  60.409s  |  60.409s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |  60.511s  |  60.511s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |  60.079s  |  60.079s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |  60.318s  |  60.318s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |  60.560s  |  60.560s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  60.129s  |  60.129s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |  60.188s  |  60.188s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |  60.354s  |  60.354s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |  60.260s  |  60.260s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |  60.338s  |  60.338s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |  60.340s  |  60.340s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |  60.053s  |  60.053s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |  60.707s  |  60.707s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  60.128s  |  60.128s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  60.324s  |  60.324s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |  60.654s  |  60.654s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |  60.456s  |  60.456s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |  60.012s  |  60.012s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |  60.655s  |  60.655s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |  60.646s  |  60.646s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |  60.409s  |  60.409s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |  60.511s  |  60.511s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |  60.079s  |  60.079s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |  60.318s  |  60.318s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |  60.560s  |  60.560s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  60.129s  |  60.129s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |  60.188s  |  60.188s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |  60.354s  |  60.354s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |  60.260s  |  60.260s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |  60.338s  |  60.338s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |  60.340s  |  60.340s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |  60.053s  |  60.053s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |  60.707s  |  60.707s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  60.128s  |  60.128s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  60.324s  |  60.324s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |  60.654s  |  60.654s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |  60.456s  |  60.456s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |  60.012s  |  60.012s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |  60.655s  |  60.655s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |  60.646s  |  60.646s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |  60.409s  |  60.409s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |  60.511s  |  60.511s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |  60.079s  |  60.079s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |  60.318s  |  60.318s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |  60.560s  |  60.560s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  60.129s  |  60.129s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |  60.188s  |  60.188s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |  60.354s  |  60.354s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |  60.260s  |  60.260s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |  60.338s  |  60.338s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |  60.340s  |  60.340s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |  60.053s  |  60.053s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |  60.707s  |  60.707s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  60.128s  |  60.128s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  60.324s  |  60.324s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |  60.654s  |  60.654s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |  60.456s  |  60.456s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |  60.012s  |  60.012s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |  60.655s  |  60.655s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |  60.646s  |  60.646s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |  60.409s  |  60.409s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |  60.511s  |  60.511s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |  60.079s  |  60.079s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |  60.318s  |  60.318s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |  60.560s  |  60.560s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  60.129s  |  60.129s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |  60.188s  |  60.188s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |  60.354s  |  60.354s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |  60.260s  |  60.260s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |  60.338s  |  60.338s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |  60.340s  |  60.340s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |  60.053s  |  60.053s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |  60.707s  |  60.707s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  60.128s  |  60.128s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  60.324s  |  60.324s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |  60.654s  |  60.654s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled75189.smt2                                                                        |  60.952s |7814.0MiB|
|scrambled68944.smt2                                                                        |  60.870s |8226.0MiB|
|scrambled43577.smt2                                                                        |  60.831s |7144.0MiB|
|scrambled79760.smt2                                                                        |  60.781s |7589.0MiB|
|scrambled19335.smt2                                                                        |  60.707s |6723.0MiB|
|scrambled107115.smt2                                                                       |  60.655s |5112.0MiB|
|scrambled27843.smt2                                                                        |  60.654s |5466.0MiB|
|scrambled107826.smt2                                                                       |  60.646s |5938.0MiB|
|scrambled12042.smt2                                                                        |  60.560s |4830.0MiB|
|scrambled111627.smt2                                                                       |  60.511s |4943.0MiB|
|scrambled94658.smt2                                                                        |  60.508s |4700.0MiB|
|scrambled55680.smt2                                                                        |  60.500s |4173.0MiB|
|scrambled4299.smt2                                                                         |  60.494s |3587.0MiB|
|scrambled4198.smt2                                                                         |  60.477s |4458.0MiB|
|scrambled102166.smt2                                                                       |  60.456s |3723.0MiB|
|scrambled61922.smt2                                                                        |  60.446s |3206.0MiB|
|scrambled108840.smt2                                                                       |  60.409s |3224.0MiB|
|scrambled72668.smt2                                                                        |  60.379s |2304.0MiB|
|scrambled40621.smt2                                                                        |  60.373s |2674.0MiB|
|scrambled128128.smt2                                                                       |  60.354s |2016.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled75189.smt2                                                                        |  60.952s |7814.0MiB|
|scrambled68944.smt2                                                                        |  60.870s |8226.0MiB|
|scrambled43577.smt2                                                                        |  60.831s |7144.0MiB|
|scrambled79760.smt2                                                                        |  60.781s |7589.0MiB|
|scrambled19335.smt2                                                                        |  60.707s |6723.0MiB|
|scrambled107115.smt2                                                                       |  60.655s |5112.0MiB|
|scrambled27843.smt2                                                                        |  60.654s |5466.0MiB|
|scrambled107826.smt2                                                                       |  60.646s |5938.0MiB|
|scrambled12042.smt2                                                                        |  60.560s |4830.0MiB|
|scrambled111627.smt2                                                                       |  60.511s |4943.0MiB|
|scrambled94658.smt2                                                                        |  60.508s |4700.0MiB|
|scrambled55680.smt2                                                                        |  60.500s |4173.0MiB|
|scrambled4299.smt2                                                                         |  60.494s |3587.0MiB|
|scrambled4198.smt2                                                                         |  60.477s |4458.0MiB|
|scrambled102166.smt2                                                                       |  60.456s |3723.0MiB|
|scrambled61922.smt2                                                                        |  60.446s |3206.0MiB|
|scrambled108840.smt2                                                                       |  60.409s |3224.0MiB|
|scrambled72668.smt2                                                                        |  60.379s |2304.0MiB|
|scrambled40621.smt2                                                                        |  60.373s |2674.0MiB|
|scrambled128128.smt2                                                                       |  60.354s |2016.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |3723.0MiB|3723.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.44MiB|42.44MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |5112.0MiB|5112.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |5938.0MiB|5938.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |3224.0MiB|3224.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |4943.0MiB|4943.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |528.0MiB|528.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |2829.0MiB|2829.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |4830.0MiB|4830.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |588.0MiB|588.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |914.0MiB|914.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |2016.0MiB|2016.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |1815.0MiB|1815.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |2207.0MiB|2207.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |2178.0MiB|2178.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |173.0MiB|173.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |6723.0MiB|6723.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |922.0MiB|922.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |2417.0MiB|2417.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |5466.0MiB|5466.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |3723.0MiB|3723.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.44MiB|42.44MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |5112.0MiB|5112.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |5938.0MiB|5938.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |3224.0MiB|3224.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |4943.0MiB|4943.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |528.0MiB|528.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |2829.0MiB|2829.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |4830.0MiB|4830.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |588.0MiB|588.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |914.0MiB|914.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |2016.0MiB|2016.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |1815.0MiB|1815.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |2207.0MiB|2207.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |2178.0MiB|2178.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |173.0MiB|173.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |6723.0MiB|6723.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |922.0MiB|922.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |2417.0MiB|2417.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |5466.0MiB|5466.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |3723.0MiB|3723.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.44MiB|42.44MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |5112.0MiB|5112.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |5938.0MiB|5938.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |3224.0MiB|3224.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |4943.0MiB|4943.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |528.0MiB|528.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |2829.0MiB|2829.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |4830.0MiB|4830.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |588.0MiB|588.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |914.0MiB|914.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |2016.0MiB|2016.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |1815.0MiB|1815.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |2207.0MiB|2207.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |2178.0MiB|2178.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |173.0MiB|173.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |6723.0MiB|6723.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |922.0MiB|922.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |2417.0MiB|2417.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |5466.0MiB|5466.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |3723.0MiB|3723.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.44MiB|42.44MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |5112.0MiB|5112.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |5938.0MiB|5938.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |3224.0MiB|3224.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |4943.0MiB|4943.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |528.0MiB|528.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |2829.0MiB|2829.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |4830.0MiB|4830.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |588.0MiB|588.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |914.0MiB|914.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |2016.0MiB|2016.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |1815.0MiB|1815.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |2207.0MiB|2207.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |2178.0MiB|2178.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |173.0MiB|173.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |6723.0MiB|6723.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |922.0MiB|922.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |2417.0MiB|2417.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |5466.0MiB|5466.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled68944.smt2                                                                        |  60.870s |8226.0MiB|
|scrambled75189.smt2                                                                        |  60.952s |7814.0MiB|
|scrambled79760.smt2                                                                        |  60.781s |7589.0MiB|
|scrambled43577.smt2                                                                        |  60.831s |7144.0MiB|
|scrambled19335.smt2                                                                        |  60.707s |6723.0MiB|
|scrambled107826.smt2                                                                       |  60.646s |5938.0MiB|
|scrambled27843.smt2                                                                        |  60.654s |5466.0MiB|
|scrambled107115.smt2                                                                       |  60.655s |5112.0MiB|
|scrambled111627.smt2                                                                       |  60.511s |4943.0MiB|
|scrambled12042.smt2                                                                        |  60.560s |4830.0MiB|
|scrambled94658.smt2                                                                        |  60.508s |4700.0MiB|
|scrambled4198.smt2                                                                         |  60.477s |4458.0MiB|
|scrambled55680.smt2                                                                        |  60.500s |4173.0MiB|
|scrambled102166.smt2                                                                       |  60.456s |3723.0MiB|
|scrambled4299.smt2                                                                         |  60.494s |3587.0MiB|
|scrambled108840.smt2                                                                       |  60.409s |3224.0MiB|
|scrambled61922.smt2                                                                        |  60.446s |3206.0MiB|
|scrambled119331.smt2                                                                       |  60.318s |2829.0MiB|
|scrambled40621.smt2                                                                        |  60.373s |2674.0MiB|
|scrambled25238.smt2                                                                        |  60.324s |2417.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled68944.smt2                                                                        |  60.870s |8226.0MiB|
|scrambled75189.smt2                                                                        |  60.952s |7814.0MiB|
|scrambled79760.smt2                                                                        |  60.781s |7589.0MiB|
|scrambled43577.smt2                                                                        |  60.831s |7144.0MiB|
|scrambled19335.smt2                                                                        |  60.707s |6723.0MiB|
|scrambled107826.smt2                                                                       |  60.646s |5938.0MiB|
|scrambled27843.smt2                                                                        |  60.654s |5466.0MiB|
|scrambled107115.smt2                                                                       |  60.655s |5112.0MiB|
|scrambled111627.smt2                                                                       |  60.511s |4943.0MiB|
|scrambled12042.smt2                                                                        |  60.560s |4830.0MiB|
|scrambled94658.smt2                                                                        |  60.508s |4700.0MiB|
|scrambled4198.smt2                                                                         |  60.477s |4458.0MiB|
|scrambled55680.smt2                                                                        |  60.500s |4173.0MiB|
|scrambled102166.smt2                                                                       |  60.456s |3723.0MiB|
|scrambled4299.smt2                                                                         |  60.494s |3587.0MiB|
|scrambled108840.smt2                                                                       |  60.409s |3224.0MiB|
|scrambled61922.smt2                                                                        |  60.446s |3206.0MiB|
|scrambled119331.smt2                                                                       |  60.318s |2829.0MiB|
|scrambled40621.smt2                                                                        |  60.373s |2674.0MiB|
|scrambled25238.smt2                                                                        |  60.324s |2417.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |  60.456s  |  60.456s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |  60.012s  |  60.012s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |  60.655s  |  60.655s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |  60.646s  |  60.646s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |  60.409s  |  60.409s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |  60.511s  |  60.511s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |  60.079s  |  60.079s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |  60.318s  |  60.318s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |  60.560s  |  60.560s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  60.129s  |  60.129s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |  60.188s  |  60.188s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |  60.354s  |  60.354s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |  60.260s  |  60.260s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |  60.338s  |  60.338s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |  60.340s  |  60.340s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |  60.053s  |  60.053s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |  60.707s  |  60.707s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  60.128s  |  60.128s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  60.324s  |  60.324s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |  60.654s  |  60.654s  |   0.000s  | 0.0%|
|scrambled32836.smt2                                                                         |  60.248s  |  60.248s  |   0.000s  | 0.0%|
|scrambled3854.smt2                                                                          |  60.027s  |  60.027s  |   0.000s  | 0.0%|
|scrambled39514.smt2                                                                         |  60.013s  |  60.013s  |   0.000s  | 0.0%|
|scrambled40621.smt2                                                                         |  60.373s  |  60.373s  |   0.000s  | 0.0%|
|scrambled4198.smt2                                                                          |  60.477s  |  60.477s  |   0.000s  | 0.0%|
|scrambled4299.smt2                                                                          |  60.494s  |  60.494s  |   0.000s  | 0.0%|
|scrambled43577.smt2                                                                         |  60.831s  |  60.831s  |   0.000s  | 0.0%|
|scrambled44911.smt2                                                                         |  60.323s  |  60.323s  |   0.000s  | 0.0%|
|scrambled45952.smt2                                                                         |  60.029s  |  60.029s  |   0.000s  | 0.0%|
|scrambled51053.smt2                                                                         |  60.202s  |  60.202s  |   0.000s  | 0.0%|
|scrambled55680.smt2                                                                         |  60.500s  |  60.500s  |   0.000s  | 0.0%|
|scrambled55777.smt2                                                                         |  60.224s  |  60.224s  |   0.000s  | 0.0%|
|scrambled59713.smt2                                                                         |  60.027s  |  60.027s  |   0.000s  | 0.0%|
|scrambled61922.smt2                                                                         |  60.446s  |  60.446s  |   0.000s  | 0.0%|
|scrambled65181.smt2                                                                         |  60.016s  |  60.016s  |   0.000s  | 0.0%|
|scrambled68944.smt2                                                                         |  60.870s  |  60.870s  |   0.000s  | 0.0%|
|scrambled72668.smt2                                                                         |  60.379s  |  60.379s  |   0.000s  | 0.0%|
|scrambled75189.smt2                                                                         |  60.952s  |  60.952s  |   0.000s  | 0.0%|
|scrambled7741.smt2                                                                          |  60.272s  |  60.272s  |   0.000s  | 0.0%|
|scrambled79760.smt2                                                                         |  60.781s  |  60.781s  |   0.000s  | 0.0%|
|scrambled79766.smt2                                                                         |  60.028s  |  60.028s  |   0.000s  | 0.0%|
|scrambled79867.smt2                                                                         |  60.019s  |  60.019s  |   0.000s  | 0.0%|
|scrambled94658.smt2                                                                         |  60.508s  |  60.508s  |   0.000s  | 0.0%|
</details>
