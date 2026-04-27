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
Job tag: Z3-threads-8-smtcomp2025-QF_LIA-timeout20min-FL
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 4e9e3413ec6d3ed78d31f91f5c563e3531e9b393
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.failed_literal_backbones=true"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: restore old changes

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_LIA-timeout20min-FL
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 4e9e3413ec6d3ed78d31f91f5c563e3531e9b393
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.failed_literal_backbones=true"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: restore old changes

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1204.322s  |1204.322s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.013s  |1200.013s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.872s  |1201.872s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.398s  |1202.398s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.808s  |1203.808s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.905s  |1203.905s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 115.433s  | 115.433s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.871s  |1200.871s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1204.813s  |1204.813s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 506.134s  | 506.134s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 141.654s  | 141.654s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.641s  |1200.641s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.583s  |1200.583s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.572s  |1200.572s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.957s  |1200.957s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.056s  |1200.056s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1202.974s  |1202.974s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  63.387s  |  63.387s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 210.756s  | 210.756s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.324s  |1202.324s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1204.322s  |1204.322s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.013s  |1200.013s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.872s  |1201.872s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.398s  |1202.398s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.808s  |1203.808s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.905s  |1203.905s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 115.433s  | 115.433s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.871s  |1200.871s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1204.813s  |1204.813s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 506.134s  | 506.134s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 141.654s  | 141.654s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.641s  |1200.641s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.583s  |1200.583s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.572s  |1200.572s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.957s  |1200.957s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.056s  |1200.056s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1202.974s  |1202.974s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  63.387s  |  63.387s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 210.756s  | 210.756s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.324s  |1202.324s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1204.322s  |1204.322s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.013s  |1200.013s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.872s  |1201.872s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.398s  |1202.398s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.808s  |1203.808s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.905s  |1203.905s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 115.433s  | 115.433s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.871s  |1200.871s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1204.813s  |1204.813s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 506.134s  | 506.134s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 141.654s  | 141.654s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.641s  |1200.641s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.583s  |1200.583s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.572s  |1200.572s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.957s  |1200.957s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.056s  |1200.056s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1202.974s  |1202.974s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  63.387s  |  63.387s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 210.756s  | 210.756s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.324s  |1202.324s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1204.322s  |1204.322s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.013s  |1200.013s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.872s  |1201.872s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.398s  |1202.398s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.808s  |1203.808s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.905s  |1203.905s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 115.433s  | 115.433s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.871s  |1200.871s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1204.813s  |1204.813s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 506.134s  | 506.134s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 141.654s  | 141.654s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.641s  |1200.641s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.583s  |1200.583s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.572s  |1200.572s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.957s  |1200.957s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.056s  |1200.056s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1202.974s  |1202.974s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  63.387s  |  63.387s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 210.756s  | 210.756s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.324s  |1202.324s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1206.306s |62.403GiB|
|scrambled4299.smt2                                                                         |1205.107s |56.359GiB|
|scrambled12042.smt2                                                                        |1204.813s |53.559GiB|
|scrambled102166.smt2                                                                       |1204.322s |47.556GiB|
|scrambled55680.smt2                                                                        |1204.253s |50.004GiB|
|scrambled68944.smt2                                                                        |1204.219s |47.225GiB|
|scrambled4198.smt2                                                                         |1204.149s |48.259GiB|
|scrambled79760.smt2                                                                        |1204.118s |43.842GiB|
|scrambled111627.smt2                                                                       |1203.905s |37.34GiB|
|scrambled108840.smt2                                                                       |1203.808s |42.604GiB|
|scrambled43577.smt2                                                                        |1203.047s |33.844GiB|
|scrambled19335.smt2                                                                        |1202.974s |31.988GiB|
|scrambled75189.smt2                                                                        |1202.895s |31.346GiB|
|scrambled107826.smt2                                                                       |1202.398s |27.544GiB|
|scrambled27843.smt2                                                                        |1202.324s |20.784GiB|
|scrambled107115.smt2                                                                       |1201.872s |17.613GiB|
|scrambled61922.smt2                                                                        |1201.087s |10.713GiB|
|scrambled40621.smt2                                                                        |1201.007s |10.06GiB|
|scrambled131241.smt2                                                                       |1200.957s |5835.0MiB|
|scrambled119331.smt2                                                                       |1200.871s |8280.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1206.306s |62.403GiB|
|scrambled4299.smt2                                                                         |1205.107s |56.359GiB|
|scrambled12042.smt2                                                                        |1204.813s |53.559GiB|
|scrambled102166.smt2                                                                       |1204.322s |47.556GiB|
|scrambled55680.smt2                                                                        |1204.253s |50.004GiB|
|scrambled68944.smt2                                                                        |1204.219s |47.225GiB|
|scrambled4198.smt2                                                                         |1204.149s |48.259GiB|
|scrambled79760.smt2                                                                        |1204.118s |43.842GiB|
|scrambled111627.smt2                                                                       |1203.905s |37.34GiB|
|scrambled108840.smt2                                                                       |1203.808s |42.604GiB|
|scrambled43577.smt2                                                                        |1203.047s |33.844GiB|
|scrambled19335.smt2                                                                        |1202.974s |31.988GiB|
|scrambled75189.smt2                                                                        |1202.895s |31.346GiB|
|scrambled107826.smt2                                                                       |1202.398s |27.544GiB|
|scrambled27843.smt2                                                                        |1202.324s |20.784GiB|
|scrambled107115.smt2                                                                       |1201.872s |17.613GiB|
|scrambled61922.smt2                                                                        |1201.087s |10.713GiB|
|scrambled40621.smt2                                                                        |1201.007s |10.06GiB|
|scrambled131241.smt2                                                                       |1200.957s |5835.0MiB|
|scrambled119331.smt2                                                                       |1200.871s |8280.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |47.556GiB|47.556GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.568MiB|42.568MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.613GiB|17.613GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |27.544GiB|27.544GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |42.604GiB|42.604GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.34GiB|37.34GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |861.0MiB|861.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |8280.0MiB|8280.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |53.559GiB|53.559GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |937.0MiB|937.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1454.0MiB|1454.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |5892.0MiB|5892.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |4680.0MiB|4680.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |4694.0MiB|4694.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |5835.0MiB|5835.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |369.0MiB|369.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |31.988GiB|31.988GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1430.0MiB|1430.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |5475.0MiB|5475.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |20.784GiB|20.784GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |47.556GiB|47.556GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.568MiB|42.568MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.613GiB|17.613GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |27.544GiB|27.544GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |42.604GiB|42.604GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.34GiB|37.34GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |861.0MiB|861.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |8280.0MiB|8280.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |53.559GiB|53.559GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |937.0MiB|937.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1454.0MiB|1454.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |5892.0MiB|5892.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |4680.0MiB|4680.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |4694.0MiB|4694.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |5835.0MiB|5835.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |369.0MiB|369.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |31.988GiB|31.988GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1430.0MiB|1430.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |5475.0MiB|5475.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |20.784GiB|20.784GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |47.556GiB|47.556GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.568MiB|42.568MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.613GiB|17.613GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |27.544GiB|27.544GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |42.604GiB|42.604GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.34GiB|37.34GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |861.0MiB|861.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |8280.0MiB|8280.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |53.559GiB|53.559GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |937.0MiB|937.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1454.0MiB|1454.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |5892.0MiB|5892.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |4680.0MiB|4680.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |4694.0MiB|4694.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |5835.0MiB|5835.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |369.0MiB|369.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |31.988GiB|31.988GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1430.0MiB|1430.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |5475.0MiB|5475.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |20.784GiB|20.784GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |47.556GiB|47.556GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.568MiB|42.568MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.613GiB|17.613GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |27.544GiB|27.544GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |42.604GiB|42.604GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.34GiB|37.34GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |861.0MiB|861.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |8280.0MiB|8280.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |53.559GiB|53.559GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |937.0MiB|937.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1454.0MiB|1454.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |5892.0MiB|5892.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |4680.0MiB|4680.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |4694.0MiB|4694.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |5835.0MiB|5835.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |369.0MiB|369.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |31.988GiB|31.988GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1430.0MiB|1430.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |5475.0MiB|5475.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |20.784GiB|20.784GiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1206.306s |62.403GiB|
|scrambled4299.smt2                                                                         |1205.107s |56.359GiB|
|scrambled12042.smt2                                                                        |1204.813s |53.559GiB|
|scrambled55680.smt2                                                                        |1204.253s |50.004GiB|
|scrambled4198.smt2                                                                         |1204.149s |48.259GiB|
|scrambled102166.smt2                                                                       |1204.322s |47.556GiB|
|scrambled68944.smt2                                                                        |1204.219s |47.225GiB|
|scrambled79760.smt2                                                                        |1204.118s |43.842GiB|
|scrambled108840.smt2                                                                       |1203.808s |42.604GiB|
|scrambled111627.smt2                                                                       |1203.905s |37.34GiB|
|scrambled43577.smt2                                                                        |1203.047s |33.844GiB|
|scrambled19335.smt2                                                                        |1202.974s |31.988GiB|
|scrambled75189.smt2                                                                        |1202.895s |31.346GiB|
|scrambled107826.smt2                                                                       |1202.398s |27.544GiB|
|scrambled27843.smt2                                                                        |1202.324s |20.784GiB|
|scrambled107115.smt2                                                                       |1201.872s |17.613GiB|
|scrambled61922.smt2                                                                        |1201.087s |10.713GiB|
|scrambled40621.smt2                                                                        |1201.007s |10.06GiB|
|scrambled119331.smt2                                                                       |1200.871s |8280.0MiB|
|scrambled7741.smt2                                                                         |1200.679s |6185.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1206.306s |62.403GiB|
|scrambled4299.smt2                                                                         |1205.107s |56.359GiB|
|scrambled12042.smt2                                                                        |1204.813s |53.559GiB|
|scrambled55680.smt2                                                                        |1204.253s |50.004GiB|
|scrambled4198.smt2                                                                         |1204.149s |48.259GiB|
|scrambled102166.smt2                                                                       |1204.322s |47.556GiB|
|scrambled68944.smt2                                                                        |1204.219s |47.225GiB|
|scrambled79760.smt2                                                                        |1204.118s |43.842GiB|
|scrambled108840.smt2                                                                       |1203.808s |42.604GiB|
|scrambled111627.smt2                                                                       |1203.905s |37.34GiB|
|scrambled43577.smt2                                                                        |1203.047s |33.844GiB|
|scrambled19335.smt2                                                                        |1202.974s |31.988GiB|
|scrambled75189.smt2                                                                        |1202.895s |31.346GiB|
|scrambled107826.smt2                                                                       |1202.398s |27.544GiB|
|scrambled27843.smt2                                                                        |1202.324s |20.784GiB|
|scrambled107115.smt2                                                                       |1201.872s |17.613GiB|
|scrambled61922.smt2                                                                        |1201.087s |10.713GiB|
|scrambled40621.smt2                                                                        |1201.007s |10.06GiB|
|scrambled119331.smt2                                                                       |1200.871s |8280.0MiB|
|scrambled7741.smt2                                                                         |1200.679s |6185.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1204.322s  |1204.322s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.013s  |1200.013s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.872s  |1201.872s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.398s  |1202.398s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.808s  |1203.808s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.905s  |1203.905s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 115.433s  | 115.433s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.871s  |1200.871s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1204.813s  |1204.813s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 506.134s  | 506.134s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 141.654s  | 141.654s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.641s  |1200.641s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.583s  |1200.583s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.572s  |1200.572s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.957s  |1200.957s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.056s  |1200.056s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1202.974s  |1202.974s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  63.387s  |  63.387s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 210.756s  | 210.756s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.324s  |1202.324s  |   0.000s  | 0.0%|
|scrambled32836.smt2                                                                         |1137.623s  |1137.623s  |   0.000s  | 0.0%|
|scrambled3854.smt2                                                                          |1200.018s  |1200.018s  |   0.000s  | 0.0%|
|scrambled39514.smt2                                                                         |1200.044s  |1200.044s  |   0.000s  | 0.0%|
|scrambled40621.smt2                                                                         |1201.007s  |1201.007s  |   0.000s  | 0.0%|
|scrambled4198.smt2                                                                          |1204.149s  |1204.149s  |   0.000s  | 0.0%|
|scrambled4299.smt2                                                                          |1205.107s  |1205.107s  |   0.000s  | 0.0%|
|scrambled43577.smt2                                                                         |1203.047s  |1203.047s  |   0.000s  | 0.0%|
|scrambled44911.smt2                                                                         |1200.634s  |1200.634s  |   0.000s  | 0.0%|
|scrambled45952.smt2                                                                         |1200.021s  |1200.021s  |   0.000s  | 0.0%|
|scrambled51053.smt2                                                                         |1200.362s  |1200.362s  |   0.000s  | 0.0%|
|scrambled55680.smt2                                                                         |1204.253s  |1204.253s  |   0.000s  | 0.0%|
|scrambled55777.smt2                                                                         |1200.656s  |1200.656s  |   0.000s  | 0.0%|
|scrambled59713.smt2                                                                         |1200.022s  |1200.022s  |   0.000s  | 0.0%|
|scrambled61922.smt2                                                                         |1201.087s  |1201.087s  |   0.000s  | 0.0%|
|scrambled65181.smt2                                                                         |1200.022s  |1200.022s  |   0.000s  | 0.0%|
|scrambled68944.smt2                                                                         |1204.219s  |1204.219s  |   0.000s  | 0.0%|
|scrambled72668.smt2                                                                         |1071.881s  |1071.881s  |   0.000s  | 0.0%|
|scrambled75189.smt2                                                                         |1202.895s  |1202.895s  |   0.000s  | 0.0%|
|scrambled7741.smt2                                                                          |1200.679s  |1200.679s  |   0.000s  | 0.0%|
|scrambled79760.smt2                                                                         |1204.118s  |1204.118s  |   0.000s  | 0.0%|
|scrambled79766.smt2                                                                         |1200.052s  |1200.052s  |   0.000s  | 0.0%|
|scrambled79867.smt2                                                                         |1200.025s  |1200.025s  |   0.000s  | 0.0%|
|scrambled94658.smt2                                                                         |1206.306s  |1206.306s  |   0.000s  | 0.0%|
</details>
