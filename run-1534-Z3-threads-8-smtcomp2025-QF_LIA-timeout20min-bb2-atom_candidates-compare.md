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
Job tag: Z3-threads-8-smtcomp2025-QF_LIA-timeout20min-bb2-atom_candidates
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: cea3155f42fe2ffe6f9a934176262a783e8fcf11
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: bb candidates are atoms, not literals, since we currently test both polarities in parallel.
batch mode retry terminates if we made zero progress after a retry round to avoid resource stress
fix bug about bb ranking being backwards for how we process them

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-smtcomp2025-QF_LIA-timeout20min-bb2-atom_candidates
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: cea3155f42fe2ffe6f9a934176262a783e8fcf11
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LIA
Z3 commit message: bb candidates are atoms, not literals, since we currently test both polarities in parallel.
batch mode retry terminates if we made zero progress after a retry round to avoid resource stress
fix bug about bb ranking being backwards for how we process them

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1204.360s  |1204.360s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.732s  |1201.732s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.511s  |1202.511s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.736s  |1203.736s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.708s  |1203.708s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 199.582s  | 199.582s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.956s  |1200.956s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1204.854s  |1204.854s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 103.871s  | 103.871s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 163.959s  | 163.959s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.600s  |1200.600s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.571s  |1200.571s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.645s  |1200.645s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.721s  |1200.721s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.086s  |1200.086s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1203.924s  |1203.924s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 322.346s  | 322.346s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 205.640s  | 205.640s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.175s  |1202.175s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1204.360s  |1204.360s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.732s  |1201.732s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.511s  |1202.511s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.736s  |1203.736s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.708s  |1203.708s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 199.582s  | 199.582s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.956s  |1200.956s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1204.854s  |1204.854s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 103.871s  | 103.871s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 163.959s  | 163.959s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.600s  |1200.600s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.571s  |1200.571s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.645s  |1200.645s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.721s  |1200.721s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.086s  |1200.086s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1203.924s  |1203.924s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 322.346s  | 322.346s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 205.640s  | 205.640s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.175s  |1202.175s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1204.360s  |1204.360s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.732s  |1201.732s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.511s  |1202.511s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.736s  |1203.736s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.708s  |1203.708s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 199.582s  | 199.582s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.956s  |1200.956s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1204.854s  |1204.854s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 103.871s  | 103.871s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 163.959s  | 163.959s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.600s  |1200.600s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.571s  |1200.571s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.645s  |1200.645s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.721s  |1200.721s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.086s  |1200.086s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1203.924s  |1203.924s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 322.346s  | 322.346s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 205.640s  | 205.640s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.175s  |1202.175s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1204.360s  |1204.360s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.732s  |1201.732s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.511s  |1202.511s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.736s  |1203.736s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.708s  |1203.708s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 199.582s  | 199.582s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.956s  |1200.956s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1204.854s  |1204.854s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 103.871s  | 103.871s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 163.959s  | 163.959s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.600s  |1200.600s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.571s  |1200.571s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.645s  |1200.645s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.721s  |1200.721s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.086s  |1200.086s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1203.924s  |1203.924s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 322.346s  | 322.346s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 205.640s  | 205.640s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.175s  |1202.175s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1205.638s |63.063GiB|
|scrambled4299.smt2                                                                         |1204.905s |56.698GiB|
|scrambled12042.smt2                                                                        |1204.854s |54.546GiB|
|scrambled55680.smt2                                                                        |1204.493s |50.677GiB|
|scrambled68944.smt2                                                                        |1204.457s |46.209GiB|
|scrambled102166.smt2                                                                       |1204.360s |48.154GiB|
|scrambled4198.smt2                                                                         |1204.299s |49.045GiB|
|scrambled79760.smt2                                                                        |1203.963s |44.273GiB|
|scrambled19335.smt2                                                                        |1203.924s |32.359GiB|
|scrambled108840.smt2                                                                       |1203.736s |43.1GiB|
|scrambled111627.smt2                                                                       |1203.708s |37.745GiB|
|scrambled43577.smt2                                                                        |1203.353s |34.249GiB|
|scrambled75189.smt2                                                                        |1202.883s |31.699GiB|
|scrambled107826.smt2                                                                       |1202.511s |27.945GiB|
|scrambled27843.smt2                                                                        |1202.175s |20.922GiB|
|scrambled107115.smt2                                                                       |1201.732s |17.782GiB|
|scrambled61922.smt2                                                                        |1201.559s |10.797GiB|
|scrambled40621.smt2                                                                        |1201.070s |10.791GiB|
|scrambled72668.smt2                                                                        |1200.968s |5318.0MiB|
|scrambled119331.smt2                                                                       |1200.956s |9452.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1205.638s |63.063GiB|
|scrambled4299.smt2                                                                         |1204.905s |56.698GiB|
|scrambled12042.smt2                                                                        |1204.854s |54.546GiB|
|scrambled55680.smt2                                                                        |1204.493s |50.677GiB|
|scrambled68944.smt2                                                                        |1204.457s |46.209GiB|
|scrambled102166.smt2                                                                       |1204.360s |48.154GiB|
|scrambled4198.smt2                                                                         |1204.299s |49.045GiB|
|scrambled79760.smt2                                                                        |1203.963s |44.273GiB|
|scrambled19335.smt2                                                                        |1203.924s |32.359GiB|
|scrambled108840.smt2                                                                       |1203.736s |43.1GiB|
|scrambled111627.smt2                                                                       |1203.708s |37.745GiB|
|scrambled43577.smt2                                                                        |1203.353s |34.249GiB|
|scrambled75189.smt2                                                                        |1202.883s |31.699GiB|
|scrambled107826.smt2                                                                       |1202.511s |27.945GiB|
|scrambled27843.smt2                                                                        |1202.175s |20.922GiB|
|scrambled107115.smt2                                                                       |1201.732s |17.782GiB|
|scrambled61922.smt2                                                                        |1201.559s |10.797GiB|
|scrambled40621.smt2                                                                        |1201.070s |10.791GiB|
|scrambled72668.smt2                                                                        |1200.968s |5318.0MiB|
|scrambled119331.smt2                                                                       |1200.956s |9452.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |48.154GiB|48.154GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |43.032MiB|43.032MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.782GiB|17.782GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |27.945GiB|27.945GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |43.1GiB|43.1GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.745GiB|37.745GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |977.0MiB|977.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |9452.0MiB|9452.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |54.546GiB|54.546GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |1009.0MiB|1009.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1628.0MiB|1628.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |6541.0MiB|6541.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |5224.0MiB|5224.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |5179.0MiB|5179.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |6451.0MiB|6451.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |379.0MiB|379.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |32.359GiB|32.359GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1720.0MiB|1720.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |5855.0MiB|5855.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |20.922GiB|20.922GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |48.154GiB|48.154GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |43.032MiB|43.032MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.782GiB|17.782GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |27.945GiB|27.945GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |43.1GiB|43.1GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.745GiB|37.745GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |977.0MiB|977.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |9452.0MiB|9452.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |54.546GiB|54.546GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |1009.0MiB|1009.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1628.0MiB|1628.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |6541.0MiB|6541.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |5224.0MiB|5224.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |5179.0MiB|5179.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |6451.0MiB|6451.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |379.0MiB|379.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |32.359GiB|32.359GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1720.0MiB|1720.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |5855.0MiB|5855.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |20.922GiB|20.922GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |48.154GiB|48.154GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |43.032MiB|43.032MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.782GiB|17.782GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |27.945GiB|27.945GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |43.1GiB|43.1GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.745GiB|37.745GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |977.0MiB|977.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |9452.0MiB|9452.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |54.546GiB|54.546GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |1009.0MiB|1009.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1628.0MiB|1628.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |6541.0MiB|6541.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |5224.0MiB|5224.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |5179.0MiB|5179.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |6451.0MiB|6451.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |379.0MiB|379.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |32.359GiB|32.359GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1720.0MiB|1720.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |5855.0MiB|5855.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |20.922GiB|20.922GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |48.154GiB|48.154GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |43.032MiB|43.032MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |17.782GiB|17.782GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |27.945GiB|27.945GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |43.1GiB|43.1GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |37.745GiB|37.745GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |977.0MiB|977.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |9452.0MiB|9452.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |54.546GiB|54.546GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |1009.0MiB|1009.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1628.0MiB|1628.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |6541.0MiB|6541.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |5224.0MiB|5224.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |5179.0MiB|5179.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |6451.0MiB|6451.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |379.0MiB|379.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |32.359GiB|32.359GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1720.0MiB|1720.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |5855.0MiB|5855.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |20.922GiB|20.922GiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1205.638s |63.063GiB|
|scrambled4299.smt2                                                                         |1204.905s |56.698GiB|
|scrambled12042.smt2                                                                        |1204.854s |54.546GiB|
|scrambled55680.smt2                                                                        |1204.493s |50.677GiB|
|scrambled4198.smt2                                                                         |1204.299s |49.045GiB|
|scrambled102166.smt2                                                                       |1204.360s |48.154GiB|
|scrambled68944.smt2                                                                        |1204.457s |46.209GiB|
|scrambled79760.smt2                                                                        |1203.963s |44.273GiB|
|scrambled108840.smt2                                                                       |1203.736s |43.1GiB|
|scrambled111627.smt2                                                                       |1203.708s |37.745GiB|
|scrambled43577.smt2                                                                        |1203.353s |34.249GiB|
|scrambled19335.smt2                                                                        |1203.924s |32.359GiB|
|scrambled75189.smt2                                                                        |1202.883s |31.699GiB|
|scrambled107826.smt2                                                                       |1202.511s |27.945GiB|
|scrambled27843.smt2                                                                        |1202.175s |20.922GiB|
|scrambled107115.smt2                                                                       |1201.732s |17.782GiB|
|scrambled61922.smt2                                                                        |1201.559s |10.797GiB|
|scrambled40621.smt2                                                                        |1201.070s |10.791GiB|
|scrambled119331.smt2                                                                       |1200.956s |9452.0MiB|
|scrambled7741.smt2                                                                         |1200.793s |6833.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1205.638s |63.063GiB|
|scrambled4299.smt2                                                                         |1204.905s |56.698GiB|
|scrambled12042.smt2                                                                        |1204.854s |54.546GiB|
|scrambled55680.smt2                                                                        |1204.493s |50.677GiB|
|scrambled4198.smt2                                                                         |1204.299s |49.045GiB|
|scrambled102166.smt2                                                                       |1204.360s |48.154GiB|
|scrambled68944.smt2                                                                        |1204.457s |46.209GiB|
|scrambled79760.smt2                                                                        |1203.963s |44.273GiB|
|scrambled108840.smt2                                                                       |1203.736s |43.1GiB|
|scrambled111627.smt2                                                                       |1203.708s |37.745GiB|
|scrambled43577.smt2                                                                        |1203.353s |34.249GiB|
|scrambled19335.smt2                                                                        |1203.924s |32.359GiB|
|scrambled75189.smt2                                                                        |1202.883s |31.699GiB|
|scrambled107826.smt2                                                                       |1202.511s |27.945GiB|
|scrambled27843.smt2                                                                        |1202.175s |20.922GiB|
|scrambled107115.smt2                                                                       |1201.732s |17.782GiB|
|scrambled61922.smt2                                                                        |1201.559s |10.797GiB|
|scrambled40621.smt2                                                                        |1201.070s |10.791GiB|
|scrambled119331.smt2                                                                       |1200.956s |9452.0MiB|
|scrambled7741.smt2                                                                         |1200.793s |6833.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1204.360s  |1204.360s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1201.732s  |1201.732s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1202.511s  |1202.511s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1203.736s  |1203.736s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1203.708s  |1203.708s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        | 199.582s  | 199.582s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.956s  |1200.956s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1204.854s  |1204.854s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 103.871s  | 103.871s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 163.959s  | 163.959s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.600s  |1200.600s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.571s  |1200.571s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.645s  |1200.645s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.721s  |1200.721s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.086s  |1200.086s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1203.924s  |1203.924s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 322.346s  | 322.346s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 205.640s  | 205.640s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1202.175s  |1202.175s  |   0.000s  | 0.0%|
|scrambled32836.smt2                                                                         |1200.376s  |1200.376s  |   0.000s  | 0.0%|
|scrambled3854.smt2                                                                          |1200.015s  |1200.015s  |   0.000s  | 0.0%|
|scrambled39514.smt2                                                                         |1200.036s  |1200.036s  |   0.000s  | 0.0%|
|scrambled40621.smt2                                                                         |1201.070s  |1201.070s  |   0.000s  | 0.0%|
|scrambled4198.smt2                                                                          |1204.299s  |1204.299s  |   0.000s  | 0.0%|
|scrambled4299.smt2                                                                          |1204.905s  |1204.905s  |   0.000s  | 0.0%|
|scrambled43577.smt2                                                                         |1203.353s  |1203.353s  |   0.000s  | 0.0%|
|scrambled44911.smt2                                                                         |1200.931s  |1200.931s  |   0.000s  | 0.0%|
|scrambled45952.smt2                                                                         |1200.015s  |1200.015s  |   0.000s  | 0.0%|
|scrambled51053.smt2                                                                         |1200.399s  |1200.399s  |   0.000s  | 0.0%|
|scrambled55680.smt2                                                                         |1204.493s  |1204.493s  |   0.000s  | 0.0%|
|scrambled55777.smt2                                                                         |1200.696s  |1200.696s  |   0.000s  | 0.0%|
|scrambled59713.smt2                                                                         |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled61922.smt2                                                                         |1201.559s  |1201.559s  |   0.000s  | 0.0%|
|scrambled65181.smt2                                                                         |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled68944.smt2                                                                         |1204.457s  |1204.457s  |   0.000s  | 0.0%|
|scrambled72668.smt2                                                                         |1200.968s  |1200.968s  |   0.000s  | 0.0%|
|scrambled75189.smt2                                                                         |1202.883s  |1202.883s  |   0.000s  | 0.0%|
|scrambled7741.smt2                                                                          |1200.793s  |1200.793s  |   0.000s  | 0.0%|
|scrambled79760.smt2                                                                         |1203.963s  |1203.963s  |   0.000s  | 0.0%|
|scrambled79766.smt2                                                                         |1200.042s  |1200.042s  |   0.000s  | 0.0%|
|scrambled79867.smt2                                                                         |1200.037s  |1200.037s  |   0.000s  | 0.0%|
|scrambled94658.smt2                                                                         |1205.638s  |1205.638s  |   0.000s  | 0.0%|
</details>
