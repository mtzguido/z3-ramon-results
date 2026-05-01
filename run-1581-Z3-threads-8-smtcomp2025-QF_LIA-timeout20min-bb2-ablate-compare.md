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
Job tag: Z3-threads-8-smtcomp2025-QF_LIA-timeout20min-bb2-ablate
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: ae632291327d6cc0ccd360d0d267ddd7b28f703e
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: ablate

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_LIA-timeout20min-bb2-ablate
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: ae632291327d6cc0ccd360d0d267ddd7b28f703e
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: ablate

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1204.397s  |1204.397s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.758s  |1201.758s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.411s  |1202.411s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.670s  |1203.670s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.649s  |1203.649s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 113.557s  | 113.557s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.833s  |1200.833s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1205.037s  |1205.037s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  86.311s  |  86.311s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 148.401s  | 148.401s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.587s  |1200.587s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.711s  |1200.711s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.547s  |1200.547s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.917s  |1200.917s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.085s  |1200.085s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1203.085s  |1203.085s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  51.455s  |  51.455s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 204.714s  | 204.714s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.351s  |1202.351s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1204.397s  |1204.397s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.758s  |1201.758s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.411s  |1202.411s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.670s  |1203.670s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.649s  |1203.649s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 113.557s  | 113.557s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.833s  |1200.833s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1205.037s  |1205.037s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  86.311s  |  86.311s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 148.401s  | 148.401s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.587s  |1200.587s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.711s  |1200.711s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.547s  |1200.547s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.917s  |1200.917s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.085s  |1200.085s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1203.085s  |1203.085s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  51.455s  |  51.455s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 204.714s  | 204.714s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.351s  |1202.351s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1204.397s  |1204.397s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.758s  |1201.758s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.411s  |1202.411s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.670s  |1203.670s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.649s  |1203.649s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 113.557s  | 113.557s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.833s  |1200.833s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1205.037s  |1205.037s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  86.311s  |  86.311s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 148.401s  | 148.401s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.587s  |1200.587s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.711s  |1200.711s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.547s  |1200.547s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.917s  |1200.917s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.085s  |1200.085s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1203.085s  |1203.085s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  51.455s  |  51.455s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 204.714s  | 204.714s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.351s  |1202.351s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1204.397s  |1204.397s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.758s  |1201.758s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.411s  |1202.411s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.670s  |1203.670s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.649s  |1203.649s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 113.557s  | 113.557s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.833s  |1200.833s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1205.037s  |1205.037s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  86.311s  |  86.311s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 148.401s  | 148.401s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.587s  |1200.587s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.711s  |1200.711s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.547s  |1200.547s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.917s  |1200.917s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.085s  |1200.085s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1203.085s  |1203.085s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  51.455s  |  51.455s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 204.714s  | 204.714s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.351s  |1202.351s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1208.508s |63.524GiB|
|scrambled55680.smt2                                                                        |1205.801s |50.699GiB|
|scrambled12042.smt2                                                                        |1205.037s |54.434GiB|
|scrambled4299.smt2                                                                         |1204.844s |56.787GiB|
|scrambled4198.smt2                                                                         |1204.520s |49.189GiB|
|scrambled102166.smt2                                                                       |1204.397s |48.159GiB|
|scrambled68944.smt2                                                                        |1204.380s |47.277GiB|
|scrambled79760.smt2                                                                        |1204.043s |44.268GiB|
|scrambled108840.smt2                                                                       |1203.670s |43.085GiB|
|scrambled111627.smt2                                                                       |1203.649s |37.787GiB|
|scrambled43577.smt2                                                                        |1203.284s |34.327GiB|
|scrambled19335.smt2                                                                        |1203.085s |32.44GiB|
|scrambled75189.smt2                                                                        |1202.728s |31.687GiB|
|scrambled107826.smt2                                                                       |1202.411s |27.988GiB|
|scrambled27843.smt2                                                                        |1202.351s |21.05GiB|
|scrambled107115.smt2                                                                       |1201.758s |17.782GiB|
|scrambled61922.smt2                                                                        |1201.664s |10.832GiB|
|scrambled72668.smt2                                                                        |1201.078s |5302.0MiB|
|scrambled40621.smt2                                                                        |1200.997s |10.546GiB|
|scrambled131241.smt2                                                                       |1200.917s |6443.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1208.508s |63.524GiB|
|scrambled55680.smt2                                                                        |1205.801s |50.699GiB|
|scrambled12042.smt2                                                                        |1205.037s |54.434GiB|
|scrambled4299.smt2                                                                         |1204.844s |56.787GiB|
|scrambled4198.smt2                                                                         |1204.520s |49.189GiB|
|scrambled102166.smt2                                                                       |1204.397s |48.159GiB|
|scrambled68944.smt2                                                                        |1204.380s |47.277GiB|
|scrambled79760.smt2                                                                        |1204.043s |44.268GiB|
|scrambled108840.smt2                                                                       |1203.670s |43.085GiB|
|scrambled111627.smt2                                                                       |1203.649s |37.787GiB|
|scrambled43577.smt2                                                                        |1203.284s |34.327GiB|
|scrambled19335.smt2                                                                        |1203.085s |32.44GiB|
|scrambled75189.smt2                                                                        |1202.728s |31.687GiB|
|scrambled107826.smt2                                                                       |1202.411s |27.988GiB|
|scrambled27843.smt2                                                                        |1202.351s |21.05GiB|
|scrambled107115.smt2                                                                       |1201.758s |17.782GiB|
|scrambled61922.smt2                                                                        |1201.664s |10.832GiB|
|scrambled72668.smt2                                                                        |1201.078s |5302.0MiB|
|scrambled40621.smt2                                                                        |1200.997s |10.546GiB|
|scrambled131241.smt2                                                                       |1200.917s |6443.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |48.159GiB|48.159GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.808MiB|42.808MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.782GiB|17.782GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |27.988GiB|27.988GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |43.085GiB|43.085GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.787GiB|37.787GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |945.0MiB|945.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |9489.0MiB|9489.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |54.434GiB|54.434GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |1006.0MiB|1006.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1604.0MiB|1604.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |6535.0MiB|6535.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |5119.0MiB|5119.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |5166.0MiB|5166.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |6443.0MiB|6443.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |375.0MiB|375.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |32.44GiB|32.44GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1503.0MiB|1503.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |5957.0MiB|5957.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |21.05GiB|21.05GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |48.159GiB|48.159GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.808MiB|42.808MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.782GiB|17.782GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |27.988GiB|27.988GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |43.085GiB|43.085GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.787GiB|37.787GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |945.0MiB|945.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |9489.0MiB|9489.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |54.434GiB|54.434GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |1006.0MiB|1006.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1604.0MiB|1604.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |6535.0MiB|6535.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |5119.0MiB|5119.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |5166.0MiB|5166.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |6443.0MiB|6443.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |375.0MiB|375.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |32.44GiB|32.44GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1503.0MiB|1503.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |5957.0MiB|5957.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |21.05GiB|21.05GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |48.159GiB|48.159GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.808MiB|42.808MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.782GiB|17.782GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |27.988GiB|27.988GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |43.085GiB|43.085GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.787GiB|37.787GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |945.0MiB|945.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |9489.0MiB|9489.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |54.434GiB|54.434GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |1006.0MiB|1006.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1604.0MiB|1604.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |6535.0MiB|6535.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |5119.0MiB|5119.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |5166.0MiB|5166.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |6443.0MiB|6443.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |375.0MiB|375.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |32.44GiB|32.44GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1503.0MiB|1503.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |5957.0MiB|5957.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |21.05GiB|21.05GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |48.159GiB|48.159GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.808MiB|42.808MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.782GiB|17.782GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |27.988GiB|27.988GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |43.085GiB|43.085GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.787GiB|37.787GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |945.0MiB|945.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |9489.0MiB|9489.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |54.434GiB|54.434GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |1006.0MiB|1006.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1604.0MiB|1604.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |6535.0MiB|6535.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |5119.0MiB|5119.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |5166.0MiB|5166.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |6443.0MiB|6443.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |375.0MiB|375.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |32.44GiB|32.44GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1503.0MiB|1503.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |5957.0MiB|5957.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |21.05GiB|21.05GiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1208.508s |63.524GiB|
|scrambled4299.smt2                                                                         |1204.844s |56.787GiB|
|scrambled12042.smt2                                                                        |1205.037s |54.434GiB|
|scrambled55680.smt2                                                                        |1205.801s |50.699GiB|
|scrambled4198.smt2                                                                         |1204.520s |49.189GiB|
|scrambled102166.smt2                                                                       |1204.397s |48.159GiB|
|scrambled68944.smt2                                                                        |1204.380s |47.277GiB|
|scrambled79760.smt2                                                                        |1204.043s |44.268GiB|
|scrambled108840.smt2                                                                       |1203.670s |43.085GiB|
|scrambled111627.smt2                                                                       |1203.649s |37.787GiB|
|scrambled43577.smt2                                                                        |1203.284s |34.327GiB|
|scrambled19335.smt2                                                                        |1203.085s |32.44GiB|
|scrambled75189.smt2                                                                        |1202.728s |31.687GiB|
|scrambled107826.smt2                                                                       |1202.411s |27.988GiB|
|scrambled27843.smt2                                                                        |1202.351s |21.05GiB|
|scrambled107115.smt2                                                                       |1201.758s |17.782GiB|
|scrambled61922.smt2                                                                        |1201.664s |10.832GiB|
|scrambled40621.smt2                                                                        |1200.997s |10.546GiB|
|scrambled119331.smt2                                                                       |1200.833s |9489.0MiB|
|scrambled7741.smt2                                                                         |1200.783s |6845.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1208.508s |63.524GiB|
|scrambled4299.smt2                                                                         |1204.844s |56.787GiB|
|scrambled12042.smt2                                                                        |1205.037s |54.434GiB|
|scrambled55680.smt2                                                                        |1205.801s |50.699GiB|
|scrambled4198.smt2                                                                         |1204.520s |49.189GiB|
|scrambled102166.smt2                                                                       |1204.397s |48.159GiB|
|scrambled68944.smt2                                                                        |1204.380s |47.277GiB|
|scrambled79760.smt2                                                                        |1204.043s |44.268GiB|
|scrambled108840.smt2                                                                       |1203.670s |43.085GiB|
|scrambled111627.smt2                                                                       |1203.649s |37.787GiB|
|scrambled43577.smt2                                                                        |1203.284s |34.327GiB|
|scrambled19335.smt2                                                                        |1203.085s |32.44GiB|
|scrambled75189.smt2                                                                        |1202.728s |31.687GiB|
|scrambled107826.smt2                                                                       |1202.411s |27.988GiB|
|scrambled27843.smt2                                                                        |1202.351s |21.05GiB|
|scrambled107115.smt2                                                                       |1201.758s |17.782GiB|
|scrambled61922.smt2                                                                        |1201.664s |10.832GiB|
|scrambled40621.smt2                                                                        |1200.997s |10.546GiB|
|scrambled119331.smt2                                                                       |1200.833s |9489.0MiB|
|scrambled7741.smt2                                                                         |1200.783s |6845.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1204.397s  |1204.397s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.758s  |1201.758s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.411s  |1202.411s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.670s  |1203.670s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.649s  |1203.649s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 113.557s  | 113.557s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.833s  |1200.833s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1205.037s  |1205.037s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  86.311s  |  86.311s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 148.401s  | 148.401s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.587s  |1200.587s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.711s  |1200.711s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.547s  |1200.547s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.917s  |1200.917s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.085s  |1200.085s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1203.085s  |1203.085s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  51.455s  |  51.455s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 204.714s  | 204.714s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.351s  |1202.351s  |   0.000s  | 0.0%|
|scrambled32836.smt2                                                                         | 574.308s  | 574.308s  |   0.000s  | 0.0%|
|scrambled3854.smt2                                                                          |1200.050s  |1200.050s  |   0.000s  | 0.0%|
|scrambled39514.smt2                                                                         |1200.032s  |1200.032s  |   0.000s  | 0.0%|
|scrambled40621.smt2                                                                         |1200.997s  |1200.997s  |   0.000s  | 0.0%|
|scrambled4198.smt2                                                                          |1204.520s  |1204.520s  |   0.000s  | 0.0%|
|scrambled4299.smt2                                                                          |1204.844s  |1204.844s  |   0.000s  | 0.0%|
|scrambled43577.smt2                                                                         |1203.284s  |1203.284s  |   0.000s  | 0.0%|
|scrambled44911.smt2                                                                         |1200.637s  |1200.637s  |   0.000s  | 0.0%|
|scrambled45952.smt2                                                                         |1200.012s  |1200.012s  |   0.000s  | 0.0%|
|scrambled51053.smt2                                                                         |1200.646s  |1200.646s  |   0.000s  | 0.0%|
|scrambled55680.smt2                                                                         |1205.801s  |1205.801s  |   0.000s  | 0.0%|
|scrambled55777.smt2                                                                         |1200.550s  |1200.550s  |   0.000s  | 0.0%|
|scrambled59713.smt2                                                                         |1200.026s  |1200.026s  |   0.000s  | 0.0%|
|scrambled61922.smt2                                                                         |1201.664s  |1201.664s  |   0.000s  | 0.0%|
|scrambled65181.smt2                                                                         |1200.027s  |1200.027s  |   0.000s  | 0.0%|
|scrambled68944.smt2                                                                         |1204.380s  |1204.380s  |   0.000s  | 0.0%|
|scrambled72668.smt2                                                                         |1201.078s  |1201.078s  |   0.000s  | 0.0%|
|scrambled75189.smt2                                                                         |1202.728s  |1202.728s  |   0.000s  | 0.0%|
|scrambled7741.smt2                                                                          |1200.783s  |1200.783s  |   0.000s  | 0.0%|
|scrambled79760.smt2                                                                         |1204.043s  |1204.043s  |   0.000s  | 0.0%|
|scrambled79766.smt2                                                                         |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled79867.smt2                                                                         |1200.027s  |1200.027s  |   0.000s  | 0.0%|
|scrambled94658.smt2                                                                         |1208.508s  |1208.508s  |   0.000s  | 0.0%|
</details>
