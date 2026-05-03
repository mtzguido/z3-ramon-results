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
Ramon benchmark for cvc5
-
Job description: 
Job tag: CVC5-threads-8-mode-partition-smtcomp2025-QF_LIA-timeout20min
Runner: rise-runner-2
cvc5 repo: cvc5/cvc5
cvc5 commit: e7e5bb6ea37ae6122da5c4f165b73c87089be765
cvc5 branch: main
cvc5 mode: partition
cvc5 portfolio mode: graduated
cvc5 portfolio strategies: "decision-scatter decision-cube"
cvc5 partition budget: 8
cvc5 partitioning options: "--partition-when=tlimit --partition-start-time=3 --partition-time-interval=0.1 --partition-check=standard"
cvc5 portfolio options: ""
cvc5 solver options: ""
cvc5 solver jobs: 8
cvc5 timeout: 1200
cvc5 inputs: inputs/smt_comp_2025_parallel/QF_LIA
cvc5 commit message: Alethe add INTS_LOG2 and INTS_ISPOW2 (#12626)

These two operators do appear in the proofs of bit-vector benchmarks.

Co-authored-by: Haniel Barbosa <hanielbbarbosa@gmail.com>

</pre>
# RHS
<pre>
Ramon benchmark for cvc5
-
Job description: 
Job tag: CVC5-threads-8-mode-partition-smtcomp2025-QF_LIA-timeout20min
Runner: rise-runner-2
cvc5 repo: cvc5/cvc5
cvc5 commit: e7e5bb6ea37ae6122da5c4f165b73c87089be765
cvc5 branch: main
cvc5 mode: partition
cvc5 portfolio mode: graduated
cvc5 portfolio strategies: "decision-scatter decision-cube"
cvc5 partition budget: 8
cvc5 partitioning options: "--partition-when=tlimit --partition-start-time=3 --partition-time-interval=0.1 --partition-check=standard"
cvc5 portfolio options: ""
cvc5 solver options: ""
cvc5 solver jobs: 8
cvc5 timeout: 1200
cvc5 inputs: inputs/smt_comp_2025_parallel/QF_LIA
cvc5 commit message: Alethe add INTS_LOG2 and INTS_ISPOW2 (#12626)

These two operators do appear in the proofs of bit-vector benchmarks.

Co-authored-by: Haniel Barbosa <hanielbbarbosa@gmail.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1200.354s  |1200.354s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.101s  |1200.101s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1200.232s  |1200.232s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1200.422s  |1200.422s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1200.536s  |1200.536s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1200.279s  |1200.279s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |1199.535s  |1199.535s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.266s  |1200.266s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1200.819s  |1200.819s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 318.803s  | 318.803s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |1199.332s  |1199.332s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1199.427s  |1199.427s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1199.380s  |1199.380s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1199.443s  |1199.443s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1199.415s  |1199.415s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.566s  |1200.566s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1200.324s  |1200.324s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |1199.562s  |1199.562s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |1199.411s  |1199.411s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1200.345s  |1200.345s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1200.354s  |1200.354s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.101s  |1200.101s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1200.232s  |1200.232s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1200.422s  |1200.422s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1200.536s  |1200.536s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1200.279s  |1200.279s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |1199.535s  |1199.535s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.266s  |1200.266s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1200.819s  |1200.819s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 318.803s  | 318.803s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |1199.332s  |1199.332s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1199.427s  |1199.427s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1199.380s  |1199.380s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1199.443s  |1199.443s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1199.415s  |1199.415s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.566s  |1200.566s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1200.324s  |1200.324s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |1199.562s  |1199.562s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |1199.411s  |1199.411s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1200.345s  |1200.345s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1200.354s  |1200.354s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.101s  |1200.101s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1200.232s  |1200.232s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1200.422s  |1200.422s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1200.536s  |1200.536s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1200.279s  |1200.279s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |1199.535s  |1199.535s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.266s  |1200.266s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1200.819s  |1200.819s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 318.803s  | 318.803s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |1199.332s  |1199.332s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1199.427s  |1199.427s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1199.380s  |1199.380s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1199.443s  |1199.443s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1199.415s  |1199.415s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.566s  |1200.566s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1200.324s  |1200.324s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |1199.562s  |1199.562s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |1199.411s  |1199.411s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1200.345s  |1200.345s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1200.354s  |1200.354s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.101s  |1200.101s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1200.232s  |1200.232s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1200.422s  |1200.422s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1200.536s  |1200.536s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1200.279s  |1200.279s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |1199.535s  |1199.535s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.266s  |1200.266s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1200.819s  |1200.819s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 318.803s  | 318.803s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |1199.332s  |1199.332s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1199.427s  |1199.427s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1199.380s  |1199.380s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1199.443s  |1199.443s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1199.415s  |1199.415s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.566s  |1200.566s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1200.324s  |1200.324s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |1199.562s  |1199.562s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |1199.411s  |1199.411s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1200.345s  |1200.345s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled4299.smt2                                                                         |1200.937s |5308.0MiB|
|scrambled12042.smt2                                                                        |1200.819s |4249.0MiB|
|scrambled55680.smt2                                                                        |1200.805s |3854.0MiB|
|scrambled94658.smt2                                                                        |1200.728s |4184.0MiB|
|scrambled75189.smt2                                                                        |1200.573s |2974.0MiB|
|scrambled1417.smt2                                                                         |1200.566s |34.982GiB|
|scrambled108840.smt2                                                                       |1200.536s |3459.0MiB|
|scrambled4198.smt2                                                                         |1200.476s |4292.0MiB|
|scrambled107826.smt2                                                                       |1200.422s |3202.0MiB|
|scrambled79760.smt2                                                                        |1200.377s |3177.0MiB|
|scrambled43577.smt2                                                                        |1200.355s |3200.0MiB|
|scrambled102166.smt2                                                                       |1200.354s |3509.0MiB|
|scrambled27843.smt2                                                                        |1200.345s |1804.0MiB|
|scrambled19335.smt2                                                                        |1200.324s |3145.0MiB|
|scrambled68944.smt2                                                                        |1200.316s |3092.0MiB|
|scrambled111627.smt2                                                                       |1200.279s |2258.0MiB|
|scrambled119331.smt2                                                                       |1200.266s |3173.0MiB|
|scrambled107115.smt2                                                                       |1200.232s |2416.0MiB|
|scrambled61922.smt2                                                                        |1200.195s |848.0MiB|
|scrambled51053.smt2                                                                        |1200.139s |393.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled4299.smt2                                                                         |1200.937s |5308.0MiB|
|scrambled12042.smt2                                                                        |1200.819s |4249.0MiB|
|scrambled55680.smt2                                                                        |1200.805s |3854.0MiB|
|scrambled94658.smt2                                                                        |1200.728s |4184.0MiB|
|scrambled75189.smt2                                                                        |1200.573s |2974.0MiB|
|scrambled1417.smt2                                                                         |1200.566s |34.982GiB|
|scrambled108840.smt2                                                                       |1200.536s |3459.0MiB|
|scrambled4198.smt2                                                                         |1200.476s |4292.0MiB|
|scrambled107826.smt2                                                                       |1200.422s |3202.0MiB|
|scrambled79760.smt2                                                                        |1200.377s |3177.0MiB|
|scrambled43577.smt2                                                                        |1200.355s |3200.0MiB|
|scrambled102166.smt2                                                                       |1200.354s |3509.0MiB|
|scrambled27843.smt2                                                                        |1200.345s |1804.0MiB|
|scrambled19335.smt2                                                                        |1200.324s |3145.0MiB|
|scrambled68944.smt2                                                                        |1200.316s |3092.0MiB|
|scrambled111627.smt2                                                                       |1200.279s |2258.0MiB|
|scrambled119331.smt2                                                                       |1200.266s |3173.0MiB|
|scrambled107115.smt2                                                                       |1200.232s |2416.0MiB|
|scrambled61922.smt2                                                                        |1200.195s |848.0MiB|
|scrambled51053.smt2                                                                        |1200.139s |393.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |3509.0MiB|3509.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |141.0MiB|141.0MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |2416.0MiB|2416.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |3202.0MiB|3202.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |3459.0MiB|3459.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |2258.0MiB|2258.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |765.0MiB|765.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |3173.0MiB|3173.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |4249.0MiB|4249.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |744.0MiB|744.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1128.0MiB|1128.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |2636.0MiB|2636.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |2273.0MiB|2273.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |1804.0MiB|1804.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |2896.0MiB|2896.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |34.982GiB|34.982GiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |3145.0MiB|3145.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1159.0MiB|1159.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |3066.0MiB|3066.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |1804.0MiB|1804.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |3509.0MiB|3509.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |141.0MiB|141.0MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |2416.0MiB|2416.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |3202.0MiB|3202.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |3459.0MiB|3459.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |2258.0MiB|2258.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |765.0MiB|765.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |3173.0MiB|3173.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |4249.0MiB|4249.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |744.0MiB|744.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1128.0MiB|1128.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |2636.0MiB|2636.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |2273.0MiB|2273.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |1804.0MiB|1804.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |2896.0MiB|2896.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |34.982GiB|34.982GiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |3145.0MiB|3145.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1159.0MiB|1159.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |3066.0MiB|3066.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |1804.0MiB|1804.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |3509.0MiB|3509.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |141.0MiB|141.0MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |2416.0MiB|2416.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |3202.0MiB|3202.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |3459.0MiB|3459.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |2258.0MiB|2258.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |765.0MiB|765.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |3173.0MiB|3173.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |4249.0MiB|4249.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |744.0MiB|744.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1128.0MiB|1128.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |2636.0MiB|2636.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |2273.0MiB|2273.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |1804.0MiB|1804.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |2896.0MiB|2896.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |34.982GiB|34.982GiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |3145.0MiB|3145.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1159.0MiB|1159.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |3066.0MiB|3066.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |1804.0MiB|1804.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |3509.0MiB|3509.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |141.0MiB|141.0MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |2416.0MiB|2416.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |3202.0MiB|3202.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |3459.0MiB|3459.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |2258.0MiB|2258.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |765.0MiB|765.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |3173.0MiB|3173.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |4249.0MiB|4249.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |744.0MiB|744.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1128.0MiB|1128.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |2636.0MiB|2636.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |2273.0MiB|2273.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |1804.0MiB|1804.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |2896.0MiB|2896.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |34.982GiB|34.982GiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |3145.0MiB|3145.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1159.0MiB|1159.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |3066.0MiB|3066.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |1804.0MiB|1804.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled1417.smt2                                                                         |1200.566s |34.982GiB|
|scrambled4299.smt2                                                                         |1200.937s |5308.0MiB|
|scrambled4198.smt2                                                                         |1200.476s |4292.0MiB|
|scrambled12042.smt2                                                                        |1200.819s |4249.0MiB|
|scrambled94658.smt2                                                                        |1200.728s |4184.0MiB|
|scrambled40621.smt2                                                                        |1199.425s |3958.0MiB|
|scrambled55680.smt2                                                                        |1200.805s |3854.0MiB|
|scrambled7741.smt2                                                                         |1199.512s |3515.0MiB|
|scrambled102166.smt2                                                                       |1200.354s |3509.0MiB|
|scrambled108840.smt2                                                                       |1200.536s |3459.0MiB|
|scrambled107826.smt2                                                                       |1200.422s |3202.0MiB|
|scrambled43577.smt2                                                                        |1200.355s |3200.0MiB|
|scrambled79760.smt2                                                                        |1200.377s |3177.0MiB|
|scrambled119331.smt2                                                                       |1200.266s |3173.0MiB|
|scrambled19335.smt2                                                                        |1200.324s |3145.0MiB|
|scrambled68944.smt2                                                                        |1200.316s |3092.0MiB|
|scrambled25238.smt2                                                                        |1199.411s |3066.0MiB|
|scrambled75189.smt2                                                                        |1200.573s |2974.0MiB|
|scrambled131241.smt2                                                                       |1199.415s |2896.0MiB|
|scrambled128128.smt2                                                                       |1199.427s |2636.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled1417.smt2                                                                         |1200.566s |34.982GiB|
|scrambled4299.smt2                                                                         |1200.937s |5308.0MiB|
|scrambled4198.smt2                                                                         |1200.476s |4292.0MiB|
|scrambled12042.smt2                                                                        |1200.819s |4249.0MiB|
|scrambled94658.smt2                                                                        |1200.728s |4184.0MiB|
|scrambled40621.smt2                                                                        |1199.425s |3958.0MiB|
|scrambled55680.smt2                                                                        |1200.805s |3854.0MiB|
|scrambled7741.smt2                                                                         |1199.512s |3515.0MiB|
|scrambled102166.smt2                                                                       |1200.354s |3509.0MiB|
|scrambled108840.smt2                                                                       |1200.536s |3459.0MiB|
|scrambled107826.smt2                                                                       |1200.422s |3202.0MiB|
|scrambled43577.smt2                                                                        |1200.355s |3200.0MiB|
|scrambled79760.smt2                                                                        |1200.377s |3177.0MiB|
|scrambled119331.smt2                                                                       |1200.266s |3173.0MiB|
|scrambled19335.smt2                                                                        |1200.324s |3145.0MiB|
|scrambled68944.smt2                                                                        |1200.316s |3092.0MiB|
|scrambled25238.smt2                                                                        |1199.411s |3066.0MiB|
|scrambled75189.smt2                                                                        |1200.573s |2974.0MiB|
|scrambled131241.smt2                                                                       |1199.415s |2896.0MiB|
|scrambled128128.smt2                                                                       |1199.427s |2636.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1200.354s  |1200.354s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.101s  |1200.101s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1200.232s  |1200.232s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1200.422s  |1200.422s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1200.536s  |1200.536s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1200.279s  |1200.279s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |1199.535s  |1199.535s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.266s  |1200.266s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1200.819s  |1200.819s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 318.803s  | 318.803s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |1199.332s  |1199.332s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1199.427s  |1199.427s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1199.380s  |1199.380s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1199.443s  |1199.443s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1199.415s  |1199.415s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.566s  |1200.566s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1200.324s  |1200.324s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |1199.562s  |1199.562s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |1199.411s  |1199.411s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1200.345s  |1200.345s  |   0.000s  | 0.0%|
|scrambled32836.smt2                                                                         |1199.410s  |1199.410s  |   0.000s  | 0.0%|
|scrambled3854.smt2                                                                          |1200.061s  |1200.061s  |   0.000s  | 0.0%|
|scrambled39514.smt2                                                                         |1200.073s  |1200.073s  |   0.000s  | 0.0%|
|scrambled40621.smt2                                                                         |1199.425s  |1199.425s  |   0.000s  | 0.0%|
|scrambled4198.smt2                                                                          |1200.476s  |1200.476s  |   0.000s  | 0.0%|
|scrambled4299.smt2                                                                          |1200.937s  |1200.937s  |   0.000s  | 0.0%|
|scrambled43577.smt2                                                                         |1200.355s  |1200.355s  |   0.000s  | 0.0%|
|scrambled44911.smt2                                                                         |1199.901s  |1199.901s  |   0.000s  | 0.0%|
|scrambled45952.smt2                                                                         |1200.063s  |1200.063s  |   0.000s  | 0.0%|
|scrambled51053.smt2                                                                         |1200.139s  |1200.139s  |   0.000s  | 0.0%|
|scrambled55680.smt2                                                                         |1200.805s  |1200.805s  |   0.000s  | 0.0%|
|scrambled55777.smt2                                                                         |1199.636s  |1199.636s  |   0.000s  | 0.0%|
|scrambled59713.smt2                                                                         |1200.064s  |1200.064s  |   0.000s  | 0.0%|
|scrambled61922.smt2                                                                         |1200.195s  |1200.195s  |   0.000s  | 0.0%|
|scrambled65181.smt2                                                                         |1200.061s  |1200.061s  |   0.000s  | 0.0%|
|scrambled68944.smt2                                                                         |1200.316s  |1200.316s  |   0.000s  | 0.0%|
|scrambled72668.smt2                                                                         |1199.892s  |1199.892s  |   0.000s  | 0.0%|
|scrambled75189.smt2                                                                         |1200.573s  |1200.573s  |   0.000s  | 0.0%|
|scrambled7741.smt2                                                                          |1199.512s  |1199.512s  |   0.000s  | 0.0%|
|scrambled79760.smt2                                                                         |1200.377s  |1200.377s  |   0.000s  | 0.0%|
|scrambled79766.smt2                                                                         |1200.070s  |1200.070s  |   0.000s  | 0.0%|
|scrambled79867.smt2                                                                         |1200.072s  |1200.072s  |   0.000s  | 0.0%|
|scrambled94658.smt2                                                                         |1200.728s  |1200.728s  |   0.000s  | 0.0%|
</details>
