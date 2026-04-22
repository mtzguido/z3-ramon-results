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
Job tag: Z3-sequential-smtcomp2025-QF_LIA-timeout_20min
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 9da11c1cda9f977649062725d6a41c20038b6577
Z3 branch: backbones
Z3 options: "-T:1200 -v:0 smt.threads=1 tactic.default_tactic=smt smt.auto_config=false"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: epoch is no longer needed, just cancel epoch. remove epoch

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-sequential-smtcomp2025-QF_LIA-timeout_20min
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: 9da11c1cda9f977649062725d6a41c20038b6577
Z3 branch: backbones
Z3 options: "-T:1200 -v:0 smt.threads=1 tactic.default_tactic=smt smt.auto_config=false"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: epoch is no longer needed, just cancel epoch. remove epoch

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1200.850s  |1200.850s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.065s  |1200.065s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1200.353s  |1200.353s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1200.455s  |1200.455s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1200.581s  |1200.581s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1200.653s  |1200.653s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |1200.077s  |1200.077s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.238s  |1200.238s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1200.734s  |1200.734s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 931.595s  | 931.595s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |1162.349s  |1162.349s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.080s  |1200.080s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.142s  |1200.142s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.082s  |1200.082s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.184s  |1200.184s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.067s  |1200.067s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1200.445s  |1200.445s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |1200.112s  |1200.112s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |1200.097s  |1200.097s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1200.386s  |1200.386s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1200.850s  |1200.850s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.065s  |1200.065s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1200.353s  |1200.353s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1200.455s  |1200.455s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1200.581s  |1200.581s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1200.653s  |1200.653s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |1200.077s  |1200.077s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.238s  |1200.238s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1200.734s  |1200.734s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 931.595s  | 931.595s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |1162.349s  |1162.349s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.080s  |1200.080s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.142s  |1200.142s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.082s  |1200.082s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.184s  |1200.184s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.067s  |1200.067s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1200.445s  |1200.445s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |1200.112s  |1200.112s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |1200.097s  |1200.097s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1200.386s  |1200.386s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1200.850s  |1200.850s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.065s  |1200.065s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1200.353s  |1200.353s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1200.455s  |1200.455s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1200.581s  |1200.581s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1200.653s  |1200.653s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |1200.077s  |1200.077s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.238s  |1200.238s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1200.734s  |1200.734s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 931.595s  | 931.595s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |1162.349s  |1162.349s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.080s  |1200.080s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.142s  |1200.142s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.082s  |1200.082s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.184s  |1200.184s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.067s  |1200.067s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1200.445s  |1200.445s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |1200.112s  |1200.112s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |1200.097s  |1200.097s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1200.386s  |1200.386s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1200.850s  |1200.850s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.065s  |1200.065s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1200.353s  |1200.353s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1200.455s  |1200.455s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1200.581s  |1200.581s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1200.653s  |1200.653s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |1200.077s  |1200.077s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.238s  |1200.238s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1200.734s  |1200.734s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 931.595s  | 931.595s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |1162.349s  |1162.349s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.080s  |1200.080s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.142s  |1200.142s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.082s  |1200.082s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.184s  |1200.184s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.067s  |1200.067s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1200.445s  |1200.445s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |1200.112s  |1200.112s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |1200.097s  |1200.097s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1200.386s  |1200.386s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled102166.smt2                                                                       |1200.850s |7346.0MiB|
|scrambled4198.smt2                                                                         |1200.821s |7174.0MiB|
|scrambled12042.smt2                                                                        |1200.734s |6172.0MiB|
|scrambled94658.smt2                                                                        |1200.730s |6802.0MiB|
|scrambled4299.smt2                                                                         |1200.697s |6809.0MiB|
|scrambled55680.smt2                                                                        |1200.692s |6057.0MiB|
|scrambled111627.smt2                                                                       |1200.653s |5803.0MiB|
|scrambled79760.smt2                                                                        |1200.649s |5630.0MiB|
|scrambled108840.smt2                                                                       |1200.581s |5441.0MiB|
|scrambled68944.smt2                                                                        |1200.564s |4741.0MiB|
|scrambled75189.smt2                                                                        |1200.550s |4318.0MiB|
|scrambled43577.smt2                                                                        |1200.472s |4186.0MiB|
|scrambled107826.smt2                                                                       |1200.455s |3503.0MiB|
|scrambled19335.smt2                                                                        |1200.445s |3355.0MiB|
|scrambled27843.smt2                                                                        |1200.386s |2330.0MiB|
|scrambled107115.smt2                                                                       |1200.353s |1957.0MiB|
|scrambled61922.smt2                                                                        |1200.270s |1262.0MiB|
|scrambled119331.smt2                                                                       |1200.238s |971.0MiB|
|scrambled131241.smt2                                                                       |1200.184s |569.0MiB|
|scrambled44911.smt2                                                                        |1200.176s |499.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled102166.smt2                                                                       |1200.850s |7346.0MiB|
|scrambled4198.smt2                                                                         |1200.821s |7174.0MiB|
|scrambled12042.smt2                                                                        |1200.734s |6172.0MiB|
|scrambled94658.smt2                                                                        |1200.730s |6802.0MiB|
|scrambled4299.smt2                                                                         |1200.697s |6809.0MiB|
|scrambled55680.smt2                                                                        |1200.692s |6057.0MiB|
|scrambled111627.smt2                                                                       |1200.653s |5803.0MiB|
|scrambled79760.smt2                                                                        |1200.649s |5630.0MiB|
|scrambled108840.smt2                                                                       |1200.581s |5441.0MiB|
|scrambled68944.smt2                                                                        |1200.564s |4741.0MiB|
|scrambled75189.smt2                                                                        |1200.550s |4318.0MiB|
|scrambled43577.smt2                                                                        |1200.472s |4186.0MiB|
|scrambled107826.smt2                                                                       |1200.455s |3503.0MiB|
|scrambled19335.smt2                                                                        |1200.445s |3355.0MiB|
|scrambled27843.smt2                                                                        |1200.386s |2330.0MiB|
|scrambled107115.smt2                                                                       |1200.353s |1957.0MiB|
|scrambled61922.smt2                                                                        |1200.270s |1262.0MiB|
|scrambled119331.smt2                                                                       |1200.238s |971.0MiB|
|scrambled131241.smt2                                                                       |1200.184s |569.0MiB|
|scrambled44911.smt2                                                                        |1200.176s |499.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |7346.0MiB|7346.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.692MiB|42.692MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |1957.0MiB|1957.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |3503.0MiB|3503.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |5441.0MiB|5441.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |5803.0MiB|5803.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |104.0MiB|104.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |971.0MiB|971.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |6172.0MiB|6172.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |105.0MiB|105.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |165.0MiB|165.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |681.0MiB|681.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |518.0MiB|518.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |490.0MiB|490.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |569.0MiB|569.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |45.432MiB|45.432MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |3355.0MiB|3355.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |174.0MiB|174.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |723.0MiB|723.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |2330.0MiB|2330.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |7346.0MiB|7346.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.692MiB|42.692MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |1957.0MiB|1957.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |3503.0MiB|3503.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |5441.0MiB|5441.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |5803.0MiB|5803.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |104.0MiB|104.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |971.0MiB|971.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |6172.0MiB|6172.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |105.0MiB|105.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |165.0MiB|165.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |681.0MiB|681.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |518.0MiB|518.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |490.0MiB|490.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |569.0MiB|569.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |45.432MiB|45.432MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |3355.0MiB|3355.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |174.0MiB|174.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |723.0MiB|723.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |2330.0MiB|2330.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |7346.0MiB|7346.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.692MiB|42.692MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |1957.0MiB|1957.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |3503.0MiB|3503.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |5441.0MiB|5441.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |5803.0MiB|5803.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |104.0MiB|104.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |971.0MiB|971.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |6172.0MiB|6172.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |105.0MiB|105.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |165.0MiB|165.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |681.0MiB|681.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |518.0MiB|518.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |490.0MiB|490.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |569.0MiB|569.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |45.432MiB|45.432MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |3355.0MiB|3355.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |174.0MiB|174.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |723.0MiB|723.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |2330.0MiB|2330.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |7346.0MiB|7346.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |42.692MiB|42.692MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |1957.0MiB|1957.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |3503.0MiB|3503.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |5441.0MiB|5441.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |5803.0MiB|5803.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |104.0MiB|104.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |971.0MiB|971.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |6172.0MiB|6172.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |105.0MiB|105.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |165.0MiB|165.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |681.0MiB|681.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |518.0MiB|518.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |490.0MiB|490.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |569.0MiB|569.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |45.432MiB|45.432MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |3355.0MiB|3355.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |174.0MiB|174.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |723.0MiB|723.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |2330.0MiB|2330.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled102166.smt2                                                                       |1200.850s |7346.0MiB|
|scrambled4198.smt2                                                                         |1200.821s |7174.0MiB|
|scrambled4299.smt2                                                                         |1200.697s |6809.0MiB|
|scrambled94658.smt2                                                                        |1200.730s |6802.0MiB|
|scrambled12042.smt2                                                                        |1200.734s |6172.0MiB|
|scrambled55680.smt2                                                                        |1200.692s |6057.0MiB|
|scrambled111627.smt2                                                                       |1200.653s |5803.0MiB|
|scrambled79760.smt2                                                                        |1200.649s |5630.0MiB|
|scrambled108840.smt2                                                                       |1200.581s |5441.0MiB|
|scrambled68944.smt2                                                                        |1200.564s |4741.0MiB|
|scrambled75189.smt2                                                                        |1200.550s |4318.0MiB|
|scrambled43577.smt2                                                                        |1200.472s |4186.0MiB|
|scrambled107826.smt2                                                                       |1200.455s |3503.0MiB|
|scrambled19335.smt2                                                                        |1200.445s |3355.0MiB|
|scrambled27843.smt2                                                                        |1200.386s |2330.0MiB|
|scrambled107115.smt2                                                                       |1200.353s |1957.0MiB|
|scrambled61922.smt2                                                                        |1200.270s |1262.0MiB|
|scrambled119331.smt2                                                                       |1200.238s |971.0MiB|
|scrambled40621.smt2                                                                        |1200.174s |762.0MiB|
|scrambled25238.smt2                                                                        |1200.097s |723.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled102166.smt2                                                                       |1200.850s |7346.0MiB|
|scrambled4198.smt2                                                                         |1200.821s |7174.0MiB|
|scrambled4299.smt2                                                                         |1200.697s |6809.0MiB|
|scrambled94658.smt2                                                                        |1200.730s |6802.0MiB|
|scrambled12042.smt2                                                                        |1200.734s |6172.0MiB|
|scrambled55680.smt2                                                                        |1200.692s |6057.0MiB|
|scrambled111627.smt2                                                                       |1200.653s |5803.0MiB|
|scrambled79760.smt2                                                                        |1200.649s |5630.0MiB|
|scrambled108840.smt2                                                                       |1200.581s |5441.0MiB|
|scrambled68944.smt2                                                                        |1200.564s |4741.0MiB|
|scrambled75189.smt2                                                                        |1200.550s |4318.0MiB|
|scrambled43577.smt2                                                                        |1200.472s |4186.0MiB|
|scrambled107826.smt2                                                                       |1200.455s |3503.0MiB|
|scrambled19335.smt2                                                                        |1200.445s |3355.0MiB|
|scrambled27843.smt2                                                                        |1200.386s |2330.0MiB|
|scrambled107115.smt2                                                                       |1200.353s |1957.0MiB|
|scrambled61922.smt2                                                                        |1200.270s |1262.0MiB|
|scrambled119331.smt2                                                                       |1200.238s |971.0MiB|
|scrambled40621.smt2                                                                        |1200.174s |762.0MiB|
|scrambled25238.smt2                                                                        |1200.097s |723.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1200.850s  |1200.850s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.065s  |1200.065s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1200.353s  |1200.353s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1200.455s  |1200.455s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1200.581s  |1200.581s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1200.653s  |1200.653s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |1200.077s  |1200.077s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.238s  |1200.238s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1200.734s  |1200.734s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 931.595s  | 931.595s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |1162.349s  |1162.349s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.080s  |1200.080s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.142s  |1200.142s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.082s  |1200.082s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.184s  |1200.184s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.067s  |1200.067s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1200.445s  |1200.445s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |1200.112s  |1200.112s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |1200.097s  |1200.097s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1200.386s  |1200.386s  |   0.000s  | 0.0%|
|scrambled32836.smt2                                                                         |1200.066s  |1200.066s  |   0.000s  | 0.0%|
|scrambled3854.smt2                                                                          |1200.065s  |1200.065s  |   0.000s  | 0.0%|
|scrambled39514.smt2                                                                         |1200.070s  |1200.070s  |   0.000s  | 0.0%|
|scrambled40621.smt2                                                                         |1200.174s  |1200.174s  |   0.000s  | 0.0%|
|scrambled4198.smt2                                                                          |1200.821s  |1200.821s  |   0.000s  | 0.0%|
|scrambled4299.smt2                                                                          |1200.697s  |1200.697s  |   0.000s  | 0.0%|
|scrambled43577.smt2                                                                         |1200.472s  |1200.472s  |   0.000s  | 0.0%|
|scrambled44911.smt2                                                                         |1200.176s  |1200.176s  |   0.000s  | 0.0%|
|scrambled45952.smt2                                                                         |1200.019s  |1200.019s  |   0.000s  | 0.0%|
|scrambled51053.smt2                                                                         |1200.146s  |1200.146s  |   0.000s  | 0.0%|
|scrambled55680.smt2                                                                         |1200.692s  |1200.692s  |   0.000s  | 0.0%|
|scrambled55777.smt2                                                                         |1200.176s  |1200.176s  |   0.000s  | 0.0%|
|scrambled59713.smt2                                                                         |1200.014s  |1200.014s  |   0.000s  | 0.0%|
|scrambled61922.smt2                                                                         |1200.270s  |1200.270s  |   0.000s  | 0.0%|
|scrambled65181.smt2                                                                         |1200.020s  |1200.020s  |   0.000s  | 0.0%|
|scrambled68944.smt2                                                                         |1200.564s  |1200.564s  |   0.000s  | 0.0%|
|scrambled72668.smt2                                                                         |1200.139s  |1200.139s  |   0.000s  | 0.0%|
|scrambled75189.smt2                                                                         |1200.550s  |1200.550s  |   0.000s  | 0.0%|
|scrambled7741.smt2                                                                          |1200.085s  |1200.085s  |   0.000s  | 0.0%|
|scrambled79760.smt2                                                                         |1200.649s  |1200.649s  |   0.000s  | 0.0%|
|scrambled79766.smt2                                                                         |1200.016s  |1200.016s  |   0.000s  | 0.0%|
|scrambled79867.smt2                                                                         |1200.041s  |1200.041s  |   0.000s  | 0.0%|
|scrambled94658.smt2                                                                         |1200.730s  |1200.730s  |   0.000s  | 0.0%|
</details>
