Comparing data and data


# SUMMARY
- LHS tests = 189
- RHS tests = 189
- LHS success = 188  (99.47089947089947%)
- RHS success = 188  (99.47089947089947%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: certora2-parallel
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: ed84b14e6c7dfaf6efd1b740119ecb1631e8bdfb
Z3 branch: arie
Z3 options: "-T:30 tactic.default_tactic=smt smt.arith.nl.nra.poly=true smt.threads=4"
Z3 inputs: inputs/certora2
Z3 commit message: fixing coi bug

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: certora2-parallel
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: ed84b14e6c7dfaf6efd1b740119ecb1631e8bdfb
Z3 branch: arie
Z3 options: "-T:30 tactic.default_tactic=smt smt.arith.nl.nra.poly=true smt.threads=4"
Z3 inputs: inputs/certora2
Z3 commit message: fixing coi bug

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|auk-0001.smt2                                                                               |   0.429s  |   0.429s  |   0.000s  | 0.0%|
|auk-0002.smt2                                                                               |   4.365s  |   4.365s  |   0.000s  | 0.0%|
|auk-0003.smt2                                                                               |  30.046s  |  30.046s  |   0.000s  | 0.0%|
|auk-0004.smt2                                                                               |   2.165s  |   2.165s  |   0.000s  | 0.0%|
|auk-0005.smt2                                                                               |  30.038s  |  30.038s  |   0.000s  | 0.0%|
|auk-0006.smt2                                                                               |   1.141s  |   1.141s  |   0.000s  | 0.0%|
|auk-0007.smt2                                                                               |   6.732s  |   6.732s  |   0.000s  | 0.0%|
|auk-0008.smt2                                                                               |  30.046s  |  30.046s  |   0.000s  | 0.0%|
|auk-0009.smt2                                                                               |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|auk-0010.smt2                                                                               |  30.027s  |  30.027s  |   0.000s  | 0.0%|
|auk-0011.smt2                                                                               |  30.055s  |  30.055s  |   0.000s  | 0.0%|
|auk-0012.smt2                                                                               |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|auk-0013.smt2                                                                               |  30.055s  |  30.055s  |   0.000s  | 0.0%|
|auk-0014.smt2                                                                               |  30.048s  |  30.048s  |   0.000s  | 0.0%|
|auk-0015.smt2                                                                               |  30.050s  |  30.050s  |   0.000s  | 0.0%|
|auk-0016.smt2                                                                               |   0.192s  |   0.192s  |   0.000s  | 0.0%|
|auk-0017.smt2                                                                               |   0.249s  |   0.249s  |   0.000s  | 0.0%|
|auk-0018.smt2                                                                               |   0.192s  |   0.192s  |   0.000s  | 0.0%|
|auk-0019.smt2                                                                               |   0.198s  |   0.198s  |   0.000s  | 0.0%|
|auk-0020.smt2                                                                               |   0.185s  |   0.185s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|auk-0001.smt2                                                                               |   0.429s  |   0.429s  |   0.000s  | 0.0%|
|auk-0002.smt2                                                                               |   4.365s  |   4.365s  |   0.000s  | 0.0%|
|auk-0003.smt2                                                                               |  30.046s  |  30.046s  |   0.000s  | 0.0%|
|auk-0004.smt2                                                                               |   2.165s  |   2.165s  |   0.000s  | 0.0%|
|auk-0005.smt2                                                                               |  30.038s  |  30.038s  |   0.000s  | 0.0%|
|auk-0006.smt2                                                                               |   1.141s  |   1.141s  |   0.000s  | 0.0%|
|auk-0007.smt2                                                                               |   6.732s  |   6.732s  |   0.000s  | 0.0%|
|auk-0008.smt2                                                                               |  30.046s  |  30.046s  |   0.000s  | 0.0%|
|auk-0009.smt2                                                                               |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|auk-0010.smt2                                                                               |  30.027s  |  30.027s  |   0.000s  | 0.0%|
|auk-0011.smt2                                                                               |  30.055s  |  30.055s  |   0.000s  | 0.0%|
|auk-0012.smt2                                                                               |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|auk-0013.smt2                                                                               |  30.055s  |  30.055s  |   0.000s  | 0.0%|
|auk-0014.smt2                                                                               |  30.048s  |  30.048s  |   0.000s  | 0.0%|
|auk-0015.smt2                                                                               |  30.050s  |  30.050s  |   0.000s  | 0.0%|
|auk-0016.smt2                                                                               |   0.192s  |   0.192s  |   0.000s  | 0.0%|
|auk-0017.smt2                                                                               |   0.249s  |   0.249s  |   0.000s  | 0.0%|
|auk-0018.smt2                                                                               |   0.192s  |   0.192s  |   0.000s  | 0.0%|
|auk-0019.smt2                                                                               |   0.198s  |   0.198s  |   0.000s  | 0.0%|
|auk-0020.smt2                                                                               |   0.185s  |   0.185s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|auk-0001.smt2                                                                               |   0.429s  |   0.429s  |   0.000s  | 0.0%|
|auk-0002.smt2                                                                               |   4.365s  |   4.365s  |   0.000s  | 0.0%|
|auk-0003.smt2                                                                               |  30.046s  |  30.046s  |   0.000s  | 0.0%|
|auk-0004.smt2                                                                               |   2.165s  |   2.165s  |   0.000s  | 0.0%|
|auk-0005.smt2                                                                               |  30.038s  |  30.038s  |   0.000s  | 0.0%|
|auk-0006.smt2                                                                               |   1.141s  |   1.141s  |   0.000s  | 0.0%|
|auk-0007.smt2                                                                               |   6.732s  |   6.732s  |   0.000s  | 0.0%|
|auk-0008.smt2                                                                               |  30.046s  |  30.046s  |   0.000s  | 0.0%|
|auk-0009.smt2                                                                               |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|auk-0010.smt2                                                                               |  30.027s  |  30.027s  |   0.000s  | 0.0%|
|auk-0011.smt2                                                                               |  30.055s  |  30.055s  |   0.000s  | 0.0%|
|auk-0012.smt2                                                                               |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|auk-0013.smt2                                                                               |  30.055s  |  30.055s  |   0.000s  | 0.0%|
|auk-0014.smt2                                                                               |  30.048s  |  30.048s  |   0.000s  | 0.0%|
|auk-0015.smt2                                                                               |  30.050s  |  30.050s  |   0.000s  | 0.0%|
|auk-0016.smt2                                                                               |   0.192s  |   0.192s  |   0.000s  | 0.0%|
|auk-0017.smt2                                                                               |   0.249s  |   0.249s  |   0.000s  | 0.0%|
|auk-0018.smt2                                                                               |   0.192s  |   0.192s  |   0.000s  | 0.0%|
|auk-0019.smt2                                                                               |   0.198s  |   0.198s  |   0.000s  | 0.0%|
|auk-0020.smt2                                                                               |   0.185s  |   0.185s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|auk-0001.smt2                                                                               |   0.429s  |   0.429s  |   0.000s  | 0.0%|
|auk-0002.smt2                                                                               |   4.365s  |   4.365s  |   0.000s  | 0.0%|
|auk-0003.smt2                                                                               |  30.046s  |  30.046s  |   0.000s  | 0.0%|
|auk-0004.smt2                                                                               |   2.165s  |   2.165s  |   0.000s  | 0.0%|
|auk-0005.smt2                                                                               |  30.038s  |  30.038s  |   0.000s  | 0.0%|
|auk-0006.smt2                                                                               |   1.141s  |   1.141s  |   0.000s  | 0.0%|
|auk-0007.smt2                                                                               |   6.732s  |   6.732s  |   0.000s  | 0.0%|
|auk-0008.smt2                                                                               |  30.046s  |  30.046s  |   0.000s  | 0.0%|
|auk-0009.smt2                                                                               |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|auk-0010.smt2                                                                               |  30.027s  |  30.027s  |   0.000s  | 0.0%|
|auk-0011.smt2                                                                               |  30.055s  |  30.055s  |   0.000s  | 0.0%|
|auk-0012.smt2                                                                               |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|auk-0013.smt2                                                                               |  30.055s  |  30.055s  |   0.000s  | 0.0%|
|auk-0014.smt2                                                                               |  30.048s  |  30.048s  |   0.000s  | 0.0%|
|auk-0015.smt2                                                                               |  30.050s  |  30.050s  |   0.000s  | 0.0%|
|auk-0016.smt2                                                                               |   0.192s  |   0.192s  |   0.000s  | 0.0%|
|auk-0017.smt2                                                                               |   0.249s  |   0.249s  |   0.000s  | 0.0%|
|auk-0018.smt2                                                                               |   0.192s  |   0.192s  |   0.000s  | 0.0%|
|auk-0019.smt2                                                                               |   0.198s  |   0.198s  |   0.000s  | 0.0%|
|auk-0020.smt2                                                                               |   0.185s  |   0.185s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|auk-0098.smt2                                                                              |  30.133s |907.0MiB|
|auk-0099.smt2                                                                              |  30.102s |781.0MiB|
|auk-0188.smt2                                                                              |  30.078s |477.0MiB|
|auk-0186.smt2                                                                              |  30.062s |282.0MiB|
|auk-0181.smt2                                                                              |  30.061s |268.0MiB|
|auk-0085.smt2                                                                              |  30.056s |315.0MiB|
|auk-0088.smt2                                                                              |  30.056s |320.0MiB|
|auk-0011.smt2                                                                              |  30.055s |210.0MiB|
|auk-0013.smt2                                                                              |  30.055s |218.0MiB|
|auk-0086.smt2                                                                              |  30.052s |355.0MiB|
|auk-0015.smt2                                                                              |  30.050s |228.0MiB|
|auk-0014.smt2                                                                              |  30.048s |220.0MiB|
|auk-0008.smt2                                                                              |  30.046s |222.0MiB|
|auk-0003.smt2                                                                              |  30.046s |208.0MiB|
|auk-0147.smt2                                                                              |  30.046s |176.0MiB|
|auk-0184.smt2                                                                              |  30.046s |214.0MiB|
|auk-0139.smt2                                                                              |  30.045s |129.0MiB|
|auk-0189.smt2                                                                              |  30.044s |208.0MiB|
|auk-0092.smt2                                                                              |  30.041s |365.0MiB|
|auk-0005.smt2                                                                              |  30.038s |217.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|auk-0098.smt2                                                                              |  30.133s |907.0MiB|
|auk-0099.smt2                                                                              |  30.102s |781.0MiB|
|auk-0188.smt2                                                                              |  30.078s |477.0MiB|
|auk-0186.smt2                                                                              |  30.062s |282.0MiB|
|auk-0181.smt2                                                                              |  30.061s |268.0MiB|
|auk-0085.smt2                                                                              |  30.056s |315.0MiB|
|auk-0088.smt2                                                                              |  30.056s |320.0MiB|
|auk-0011.smt2                                                                              |  30.055s |210.0MiB|
|auk-0013.smt2                                                                              |  30.055s |218.0MiB|
|auk-0086.smt2                                                                              |  30.052s |355.0MiB|
|auk-0015.smt2                                                                              |  30.050s |228.0MiB|
|auk-0014.smt2                                                                              |  30.048s |220.0MiB|
|auk-0008.smt2                                                                              |  30.046s |222.0MiB|
|auk-0003.smt2                                                                              |  30.046s |208.0MiB|
|auk-0147.smt2                                                                              |  30.046s |176.0MiB|
|auk-0184.smt2                                                                              |  30.046s |214.0MiB|
|auk-0139.smt2                                                                              |  30.045s |129.0MiB|
|auk-0189.smt2                                                                              |  30.044s |208.0MiB|
|auk-0092.smt2                                                                              |  30.041s |365.0MiB|
|auk-0005.smt2                                                                              |  30.038s |217.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|auk-0001.smt2                                                                               |97.236MiB|97.236MiB|0B| 0.0%|
|auk-0002.smt2                                                                               |216.0MiB|216.0MiB|0B| 0.0%|
|auk-0003.smt2                                                                               |208.0MiB|208.0MiB|0B| 0.0%|
|auk-0004.smt2                                                                               |175.0MiB|175.0MiB|0B| 0.0%|
|auk-0005.smt2                                                                               |217.0MiB|217.0MiB|0B| 0.0%|
|auk-0006.smt2                                                                               |170.0MiB|170.0MiB|0B| 0.0%|
|auk-0007.smt2                                                                               |176.0MiB|176.0MiB|0B| 0.0%|
|auk-0008.smt2                                                                               |222.0MiB|222.0MiB|0B| 0.0%|
|auk-0009.smt2                                                                               |96.28MiB|96.28MiB|0B| 0.0%|
|auk-0010.smt2                                                                               |199.0MiB|199.0MiB|0B| 0.0%|
|auk-0011.smt2                                                                               |210.0MiB|210.0MiB|0B| 0.0%|
|auk-0012.smt2                                                                               |96.96MiB|96.96MiB|0B| 0.0%|
|auk-0013.smt2                                                                               |218.0MiB|218.0MiB|0B| 0.0%|
|auk-0014.smt2                                                                               |220.0MiB|220.0MiB|0B| 0.0%|
|auk-0015.smt2                                                                               |228.0MiB|228.0MiB|0B| 0.0%|
|auk-0016.smt2                                                                               |114.0MiB|114.0MiB|0B| 0.0%|
|auk-0017.smt2                                                                               |129.0MiB|129.0MiB|0B| 0.0%|
|auk-0018.smt2                                                                               |122.0MiB|122.0MiB|0B| 0.0%|
|auk-0019.smt2                                                                               |120.0MiB|120.0MiB|0B| 0.0%|
|auk-0020.smt2                                                                               |118.0MiB|118.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|auk-0001.smt2                                                                               |97.236MiB|97.236MiB|0B| 0.0%|
|auk-0002.smt2                                                                               |216.0MiB|216.0MiB|0B| 0.0%|
|auk-0003.smt2                                                                               |208.0MiB|208.0MiB|0B| 0.0%|
|auk-0004.smt2                                                                               |175.0MiB|175.0MiB|0B| 0.0%|
|auk-0005.smt2                                                                               |217.0MiB|217.0MiB|0B| 0.0%|
|auk-0006.smt2                                                                               |170.0MiB|170.0MiB|0B| 0.0%|
|auk-0007.smt2                                                                               |176.0MiB|176.0MiB|0B| 0.0%|
|auk-0008.smt2                                                                               |222.0MiB|222.0MiB|0B| 0.0%|
|auk-0009.smt2                                                                               |96.28MiB|96.28MiB|0B| 0.0%|
|auk-0010.smt2                                                                               |199.0MiB|199.0MiB|0B| 0.0%|
|auk-0011.smt2                                                                               |210.0MiB|210.0MiB|0B| 0.0%|
|auk-0012.smt2                                                                               |96.96MiB|96.96MiB|0B| 0.0%|
|auk-0013.smt2                                                                               |218.0MiB|218.0MiB|0B| 0.0%|
|auk-0014.smt2                                                                               |220.0MiB|220.0MiB|0B| 0.0%|
|auk-0015.smt2                                                                               |228.0MiB|228.0MiB|0B| 0.0%|
|auk-0016.smt2                                                                               |114.0MiB|114.0MiB|0B| 0.0%|
|auk-0017.smt2                                                                               |129.0MiB|129.0MiB|0B| 0.0%|
|auk-0018.smt2                                                                               |122.0MiB|122.0MiB|0B| 0.0%|
|auk-0019.smt2                                                                               |120.0MiB|120.0MiB|0B| 0.0%|
|auk-0020.smt2                                                                               |118.0MiB|118.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|auk-0001.smt2                                                                               |97.236MiB|97.236MiB|0B| 0.0%|
|auk-0002.smt2                                                                               |216.0MiB|216.0MiB|0B| 0.0%|
|auk-0003.smt2                                                                               |208.0MiB|208.0MiB|0B| 0.0%|
|auk-0004.smt2                                                                               |175.0MiB|175.0MiB|0B| 0.0%|
|auk-0005.smt2                                                                               |217.0MiB|217.0MiB|0B| 0.0%|
|auk-0006.smt2                                                                               |170.0MiB|170.0MiB|0B| 0.0%|
|auk-0007.smt2                                                                               |176.0MiB|176.0MiB|0B| 0.0%|
|auk-0008.smt2                                                                               |222.0MiB|222.0MiB|0B| 0.0%|
|auk-0009.smt2                                                                               |96.28MiB|96.28MiB|0B| 0.0%|
|auk-0010.smt2                                                                               |199.0MiB|199.0MiB|0B| 0.0%|
|auk-0011.smt2                                                                               |210.0MiB|210.0MiB|0B| 0.0%|
|auk-0012.smt2                                                                               |96.96MiB|96.96MiB|0B| 0.0%|
|auk-0013.smt2                                                                               |218.0MiB|218.0MiB|0B| 0.0%|
|auk-0014.smt2                                                                               |220.0MiB|220.0MiB|0B| 0.0%|
|auk-0015.smt2                                                                               |228.0MiB|228.0MiB|0B| 0.0%|
|auk-0016.smt2                                                                               |114.0MiB|114.0MiB|0B| 0.0%|
|auk-0017.smt2                                                                               |129.0MiB|129.0MiB|0B| 0.0%|
|auk-0018.smt2                                                                               |122.0MiB|122.0MiB|0B| 0.0%|
|auk-0019.smt2                                                                               |120.0MiB|120.0MiB|0B| 0.0%|
|auk-0020.smt2                                                                               |118.0MiB|118.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|auk-0001.smt2                                                                               |97.236MiB|97.236MiB|0B| 0.0%|
|auk-0002.smt2                                                                               |216.0MiB|216.0MiB|0B| 0.0%|
|auk-0003.smt2                                                                               |208.0MiB|208.0MiB|0B| 0.0%|
|auk-0004.smt2                                                                               |175.0MiB|175.0MiB|0B| 0.0%|
|auk-0005.smt2                                                                               |217.0MiB|217.0MiB|0B| 0.0%|
|auk-0006.smt2                                                                               |170.0MiB|170.0MiB|0B| 0.0%|
|auk-0007.smt2                                                                               |176.0MiB|176.0MiB|0B| 0.0%|
|auk-0008.smt2                                                                               |222.0MiB|222.0MiB|0B| 0.0%|
|auk-0009.smt2                                                                               |96.28MiB|96.28MiB|0B| 0.0%|
|auk-0010.smt2                                                                               |199.0MiB|199.0MiB|0B| 0.0%|
|auk-0011.smt2                                                                               |210.0MiB|210.0MiB|0B| 0.0%|
|auk-0012.smt2                                                                               |96.96MiB|96.96MiB|0B| 0.0%|
|auk-0013.smt2                                                                               |218.0MiB|218.0MiB|0B| 0.0%|
|auk-0014.smt2                                                                               |220.0MiB|220.0MiB|0B| 0.0%|
|auk-0015.smt2                                                                               |228.0MiB|228.0MiB|0B| 0.0%|
|auk-0016.smt2                                                                               |114.0MiB|114.0MiB|0B| 0.0%|
|auk-0017.smt2                                                                               |129.0MiB|129.0MiB|0B| 0.0%|
|auk-0018.smt2                                                                               |122.0MiB|122.0MiB|0B| 0.0%|
|auk-0019.smt2                                                                               |120.0MiB|120.0MiB|0B| 0.0%|
|auk-0020.smt2                                                                               |118.0MiB|118.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|auk-0098.smt2                                                                              |  30.133s |907.0MiB|
|auk-0099.smt2                                                                              |  30.102s |781.0MiB|
|auk-0188.smt2                                                                              |  30.078s |477.0MiB|
|auk-0109.smt2                                                                              |   1.206s |380.0MiB|
|auk-0092.smt2                                                                              |  30.041s |365.0MiB|
|auk-0086.smt2                                                                              |  30.052s |355.0MiB|
|auk-0131.smt2                                                                              |   4.067s |330.0MiB|
|auk-0083.smt2                                                                              |   3.072s |329.0MiB|
|auk-0082.smt2                                                                              |   2.930s |329.0MiB|
|auk-0088.smt2                                                                              |  30.056s |320.0MiB|
|auk-0085.smt2                                                                              |  30.056s |315.0MiB|
|auk-0186.smt2                                                                              |  30.062s |282.0MiB|
|auk-0181.smt2                                                                              |  30.061s |268.0MiB|
|auk-0089.smt2                                                                              |  18.619s |262.0MiB|
|auk-0087.smt2                                                                              |   5.183s |245.0MiB|
|auk-0182.smt2                                                                              |   7.389s |241.0MiB|
|auk-0015.smt2                                                                              |  30.050s |228.0MiB|
|auk-0183.smt2                                                                              |   1.965s |226.0MiB|
|auk-0084.smt2                                                                              |   5.507s |225.0MiB|
|auk-0008.smt2                                                                              |  30.046s |222.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|auk-0098.smt2                                                                              |  30.133s |907.0MiB|
|auk-0099.smt2                                                                              |  30.102s |781.0MiB|
|auk-0188.smt2                                                                              |  30.078s |477.0MiB|
|auk-0109.smt2                                                                              |   1.206s |380.0MiB|
|auk-0092.smt2                                                                              |  30.041s |365.0MiB|
|auk-0086.smt2                                                                              |  30.052s |355.0MiB|
|auk-0131.smt2                                                                              |   4.067s |330.0MiB|
|auk-0083.smt2                                                                              |   3.072s |329.0MiB|
|auk-0082.smt2                                                                              |   2.930s |329.0MiB|
|auk-0088.smt2                                                                              |  30.056s |320.0MiB|
|auk-0085.smt2                                                                              |  30.056s |315.0MiB|
|auk-0186.smt2                                                                              |  30.062s |282.0MiB|
|auk-0181.smt2                                                                              |  30.061s |268.0MiB|
|auk-0089.smt2                                                                              |  18.619s |262.0MiB|
|auk-0087.smt2                                                                              |   5.183s |245.0MiB|
|auk-0182.smt2                                                                              |   7.389s |241.0MiB|
|auk-0015.smt2                                                                              |  30.050s |228.0MiB|
|auk-0183.smt2                                                                              |   1.965s |226.0MiB|
|auk-0084.smt2                                                                              |   5.507s |225.0MiB|
|auk-0008.smt2                                                                              |  30.046s |222.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|auk-0001.smt2                                                                               |   0.429s  |   0.429s  |   0.000s  | 0.0%|
|auk-0002.smt2                                                                               |   4.365s  |   4.365s  |   0.000s  | 0.0%|
|auk-0003.smt2                                                                               |  30.046s  |  30.046s  |   0.000s  | 0.0%|
|auk-0004.smt2                                                                               |   2.165s  |   2.165s  |   0.000s  | 0.0%|
|auk-0005.smt2                                                                               |  30.038s  |  30.038s  |   0.000s  | 0.0%|
|auk-0006.smt2                                                                               |   1.141s  |   1.141s  |   0.000s  | 0.0%|
|auk-0007.smt2                                                                               |   6.732s  |   6.732s  |   0.000s  | 0.0%|
|auk-0008.smt2                                                                               |  30.046s  |  30.046s  |   0.000s  | 0.0%|
|auk-0009.smt2                                                                               |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|auk-0010.smt2                                                                               |  30.027s  |  30.027s  |   0.000s  | 0.0%|
|auk-0011.smt2                                                                               |  30.055s  |  30.055s  |   0.000s  | 0.0%|
|auk-0012.smt2                                                                               |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|auk-0013.smt2                                                                               |  30.055s  |  30.055s  |   0.000s  | 0.0%|
|auk-0014.smt2                                                                               |  30.048s  |  30.048s  |   0.000s  | 0.0%|
|auk-0015.smt2                                                                               |  30.050s  |  30.050s  |   0.000s  | 0.0%|
|auk-0016.smt2                                                                               |   0.192s  |   0.192s  |   0.000s  | 0.0%|
|auk-0017.smt2                                                                               |   0.249s  |   0.249s  |   0.000s  | 0.0%|
|auk-0018.smt2                                                                               |   0.192s  |   0.192s  |   0.000s  | 0.0%|
|auk-0019.smt2                                                                               |   0.198s  |   0.198s  |   0.000s  | 0.0%|
|auk-0020.smt2                                                                               |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|auk-0021.smt2                                                                               |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|auk-0022.smt2                                                                               |   0.203s  |   0.203s  |   0.000s  | 0.0%|
|auk-0023.smt2                                                                               |   0.235s  |   0.235s  |   0.000s  | 0.0%|
|auk-0024.smt2                                                                               |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|auk-0025.smt2                                                                               |   0.340s  |   0.340s  |   0.000s  | 0.0%|
|auk-0026.smt2                                                                               |   0.231s  |   0.231s  |   0.000s  | 0.0%|
|auk-0027.smt2                                                                               |   0.339s  |   0.339s  |   0.000s  | 0.0%|
|auk-0028.smt2                                                                               |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|auk-0029.smt2                                                                               |   0.196s  |   0.196s  |   0.000s  | 0.0%|
|auk-0030.smt2                                                                               |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|auk-0031.smt2                                                                               |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|auk-0032.smt2                                                                               |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|auk-0033.smt2                                                                               |   0.192s  |   0.192s  |   0.000s  | 0.0%|
|auk-0034.smt2                                                                               |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|auk-0035.smt2                                                                               |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|auk-0036.smt2                                                                               |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|auk-0037.smt2                                                                               |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|auk-0038.smt2                                                                               |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|auk-0039.smt2                                                                               |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|auk-0040.smt2                                                                               |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|auk-0041.smt2                                                                               |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|auk-0042.smt2                                                                               |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|auk-0043.smt2                                                                               |   0.192s  |   0.192s  |   0.000s  | 0.0%|
|auk-0044.smt2                                                                               |   0.197s  |   0.197s  |   0.000s  | 0.0%|
|auk-0045.smt2                                                                               |   0.186s  |   0.186s  |   0.000s  | 0.0%|
|auk-0046.smt2                                                                               |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|auk-0047.smt2                                                                               |   0.195s  |   0.195s  |   0.000s  | 0.0%|
|auk-0048.smt2                                                                               |   0.209s  |   0.209s  |   0.000s  | 0.0%|
|auk-0049.smt2                                                                               |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|auk-0050.smt2                                                                               |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|auk-0051.smt2                                                                               |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|auk-0052.smt2                                                                               |   0.197s  |   0.197s  |   0.000s  | 0.0%|
|auk-0053.smt2                                                                               |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|auk-0054.smt2                                                                               |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|auk-0055.smt2                                                                               |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|auk-0056.smt2                                                                               |   0.511s  |   0.511s  |   0.000s  | 0.0%|
|auk-0057.smt2                                                                               |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|auk-0058.smt2                                                                               |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|auk-0059.smt2                                                                               |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|auk-0060.smt2                                                                               |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|auk-0061.smt2                                                                               |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|auk-0062.smt2                                                                               |   0.246s  |   0.246s  |   0.000s  | 0.0%|
|auk-0063.smt2                                                                               |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|auk-0064.smt2                                                                               |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|auk-0065.smt2                                                                               |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|auk-0066.smt2                                                                               |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|auk-0067.smt2                                                                               |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|auk-0068.smt2                                                                               |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|auk-0069.smt2                                                                               |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|auk-0070.smt2                                                                               |   0.381s  |   0.381s  |   0.000s  | 0.0%|
|auk-0071.smt2                                                                               |   1.358s  |   1.358s  |   0.000s  | 0.0%|
|auk-0072.smt2                                                                               |   0.548s  |   0.548s  |   0.000s  | 0.0%|
|auk-0073.smt2                                                                               |   1.363s  |   1.363s  |   0.000s  | 0.0%|
|auk-0074.smt2                                                                               |   0.502s  |   0.502s  |   0.000s  | 0.0%|
|auk-0075.smt2                                                                               |   1.308s  |   1.308s  |   0.000s  | 0.0%|
|auk-0076.smt2                                                                               |   1.352s  |   1.352s  |   0.000s  | 0.0%|
|auk-0077.smt2                                                                               |   1.424s  |   1.424s  |   0.000s  | 0.0%|
|auk-0078.smt2                                                                               |   0.613s  |   0.613s  |   0.000s  | 0.0%|
|auk-0080.smt2                                                                               |   0.547s  |   0.547s  |   0.000s  | 0.0%|
|auk-0081.smt2                                                                               |   0.522s  |   0.522s  |   0.000s  | 0.0%|
|auk-0082.smt2                                                                               |   2.930s  |   2.930s  |   0.000s  | 0.0%|
|auk-0083.smt2                                                                               |   3.072s  |   3.072s  |   0.000s  | 0.0%|
|auk-0084.smt2                                                                               |   5.507s  |   5.507s  |   0.000s  | 0.0%|
|auk-0085.smt2                                                                               |  30.056s  |  30.056s  |   0.000s  | 0.0%|
|auk-0086.smt2                                                                               |  30.052s  |  30.052s  |   0.000s  | 0.0%|
|auk-0087.smt2                                                                               |   5.183s  |   5.183s  |   0.000s  | 0.0%|
|auk-0088.smt2                                                                               |  30.056s  |  30.056s  |   0.000s  | 0.0%|
|auk-0089.smt2                                                                               |  18.619s  |  18.619s  |   0.000s  | 0.0%|
|auk-0090.smt2                                                                               |   6.290s  |   6.290s  |   0.000s  | 0.0%|
|auk-0091.smt2                                                                               |   0.665s  |   0.665s  |   0.000s  | 0.0%|
|auk-0092.smt2                                                                               |  30.041s  |  30.041s  |   0.000s  | 0.0%|
|auk-0093.smt2                                                                               |   0.227s  |   0.227s  |   0.000s  | 0.0%|
|auk-0094.smt2                                                                               |   0.565s  |   0.565s  |   0.000s  | 0.0%|
|auk-0095.smt2                                                                               |   1.626s  |   1.626s  |   0.000s  | 0.0%|
|auk-0096.smt2                                                                               |   0.376s  |   0.376s  |   0.000s  | 0.0%|
|auk-0097.smt2                                                                               |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|auk-0098.smt2                                                                               |  30.133s  |  30.133s  |   0.000s  | 0.0%|
|auk-0099.smt2                                                                               |  30.102s  |  30.102s  |   0.000s  | 0.0%|
|auk-0100.smt2                                                                               |   0.204s  |   0.204s  |   0.000s  | 0.0%|
|auk-0101.smt2                                                                               |   0.755s  |   0.755s  |   0.000s  | 0.0%|
|auk-0102.smt2                                                                               |   0.288s  |   0.288s  |   0.000s  | 0.0%|
|auk-0103.smt2                                                                               |   0.248s  |   0.248s  |   0.000s  | 0.0%|
|auk-0104.smt2                                                                               |   0.193s  |   0.193s  |   0.000s  | 0.0%|
|auk-0105.smt2                                                                               |   0.282s  |   0.282s  |   0.000s  | 0.0%|
|auk-0106.smt2                                                                               |   0.232s  |   0.232s  |   0.000s  | 0.0%|
|auk-0107.smt2                                                                               |   0.257s  |   0.257s  |   0.000s  | 0.0%|
|auk-0108.smt2                                                                               |   0.312s  |   0.312s  |   0.000s  | 0.0%|
|auk-0109.smt2                                                                               |   1.206s  |   1.206s  |   0.000s  | 0.0%|
|auk-0110.smt2                                                                               |   0.210s  |   0.210s  |   0.000s  | 0.0%|
|auk-0111.smt2                                                                               |   0.277s  |   0.277s  |   0.000s  | 0.0%|
|auk-0112.smt2                                                                               |   0.291s  |   0.291s  |   0.000s  | 0.0%|
|auk-0113.smt2                                                                               |   0.310s  |   0.310s  |   0.000s  | 0.0%|
|auk-0114.smt2                                                                               |   0.212s  |   0.212s  |   0.000s  | 0.0%|
|auk-0115.smt2                                                                               |   0.465s  |   0.465s  |   0.000s  | 0.0%|
|auk-0116.smt2                                                                               |   0.349s  |   0.349s  |   0.000s  | 0.0%|
|auk-0117.smt2                                                                               |   0.304s  |   0.304s  |   0.000s  | 0.0%|
|auk-0118.smt2                                                                               |   0.303s  |   0.303s  |   0.000s  | 0.0%|
|auk-0119.smt2                                                                               |   0.394s  |   0.394s  |   0.000s  | 0.0%|
|auk-0120.smt2                                                                               |   0.423s  |   0.423s  |   0.000s  | 0.0%|
|auk-0121.smt2                                                                               |   0.262s  |   0.262s  |   0.000s  | 0.0%|
|auk-0122.smt2                                                                               |   0.342s  |   0.342s  |   0.000s  | 0.0%|
|auk-0123.smt2                                                                               |   0.402s  |   0.402s  |   0.000s  | 0.0%|
|auk-0124.smt2                                                                               |   0.227s  |   0.227s  |   0.000s  | 0.0%|
|auk-0125.smt2                                                                               |   0.269s  |   0.269s  |   0.000s  | 0.0%|
|auk-0126.smt2                                                                               |   0.264s  |   0.264s  |   0.000s  | 0.0%|
|auk-0127.smt2                                                                               |   0.251s  |   0.251s  |   0.000s  | 0.0%|
|auk-0128.smt2                                                                               |   0.354s  |   0.354s  |   0.000s  | 0.0%|
|auk-0129.smt2                                                                               |   0.216s  |   0.216s  |   0.000s  | 0.0%|
|auk-0130.smt2                                                                               |   0.329s  |   0.329s  |   0.000s  | 0.0%|
|auk-0131.smt2                                                                               |   4.067s  |   4.067s  |   0.000s  | 0.0%|
|auk-0132.smt2                                                                               |   2.219s  |   2.219s  |   0.000s  | 0.0%|
|auk-0133.smt2                                                                               |   0.917s  |   0.917s  |   0.000s  | 0.0%|
|auk-0134.smt2                                                                               |   0.488s  |   0.488s  |   0.000s  | 0.0%|
|auk-0135.smt2                                                                               |   0.376s  |   0.376s  |   0.000s  | 0.0%|
|auk-0136.smt2                                                                               |   0.242s  |   0.242s  |   0.000s  | 0.0%|
|auk-0137.smt2                                                                               |  14.776s  |  14.776s  |   0.000s  | 0.0%|
|auk-0138.smt2                                                                               |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|auk-0139.smt2                                                                               |  30.045s  |  30.045s  |   0.000s  | 0.0%|
|auk-0140.smt2                                                                               |   7.909s  |   7.909s  |   0.000s  | 0.0%|
|auk-0141.smt2                                                                               |   7.130s  |   7.130s  |   0.000s  | 0.0%|
|auk-0142.smt2                                                                               |   1.479s  |   1.479s  |   0.000s  | 0.0%|
|auk-0143.smt2                                                                               |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|auk-0144.smt2                                                                               |   1.398s  |   1.398s  |   0.000s  | 0.0%|
|auk-0145.smt2                                                                               |   0.986s  |   0.986s  |   0.000s  | 0.0%|
|auk-0146.smt2                                                                               |   0.760s  |   0.760s  |   0.000s  | 0.0%|
|auk-0147.smt2                                                                               |  30.046s  |  30.046s  |   0.000s  | 0.0%|
|auk-0148.smt2                                                                               |   2.020s  |   2.020s  |   0.000s  | 0.0%|
|auk-0149.smt2                                                                               |   0.833s  |   0.833s  |   0.000s  | 0.0%|
|auk-0150.smt2                                                                               |   0.289s  |   0.289s  |   0.000s  | 0.0%|
|auk-0151.smt2                                                                               |  20.051s  |  20.051s  |   0.000s  | 0.0%|
|auk-0152.smt2                                                                               |   0.203s  |   0.203s  |   0.000s  | 0.0%|
|auk-0153.smt2                                                                               |   0.263s  |   0.263s  |   0.000s  | 0.0%|
|auk-0154.smt2                                                                               |   0.252s  |   0.252s  |   0.000s  | 0.0%|
|auk-0155.smt2                                                                               |   0.229s  |   0.229s  |   0.000s  | 0.0%|
|auk-0156.smt2                                                                               |   0.272s  |   0.272s  |   0.000s  | 0.0%|
|auk-0157.smt2                                                                               |   0.245s  |   0.245s  |   0.000s  | 0.0%|
|auk-0158.smt2                                                                               |   0.209s  |   0.209s  |   0.000s  | 0.0%|
|auk-0159.smt2                                                                               |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|auk-0160.smt2                                                                               |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|auk-0161.smt2                                                                               |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|auk-0162.smt2                                                                               |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|auk-0163.smt2                                                                               |   0.239s  |   0.239s  |   0.000s  | 0.0%|
|auk-0164.smt2                                                                               |   0.205s  |   0.205s  |   0.000s  | 0.0%|
|auk-0165.smt2                                                                               |   0.260s  |   0.260s  |   0.000s  | 0.0%|
|auk-0166.smt2                                                                               |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|auk-0167.smt2                                                                               |   0.240s  |   0.240s  |   0.000s  | 0.0%|
|auk-0168.smt2                                                                               |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|auk-0169.smt2                                                                               |   0.232s  |   0.232s  |   0.000s  | 0.0%|
|auk-0170.smt2                                                                               |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|auk-0171.smt2                                                                               |   0.258s  |   0.258s  |   0.000s  | 0.0%|
|auk-0172.smt2                                                                               |   0.238s  |   0.238s  |   0.000s  | 0.0%|
|auk-0173.smt2                                                                               |   0.237s  |   0.237s  |   0.000s  | 0.0%|
|auk-0174.smt2                                                                               |   0.242s  |   0.242s  |   0.000s  | 0.0%|
|auk-0175.smt2                                                                               |   0.263s  |   0.263s  |   0.000s  | 0.0%|
|auk-0176.smt2                                                                               |   0.238s  |   0.238s  |   0.000s  | 0.0%|
|auk-0177.smt2                                                                               |   0.268s  |   0.268s  |   0.000s  | 0.0%|
|auk-0178.smt2                                                                               |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|auk-0179.smt2                                                                               |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|auk-0180.smt2                                                                               |   0.208s  |   0.208s  |   0.000s  | 0.0%|
|auk-0181.smt2                                                                               |  30.061s  |  30.061s  |   0.000s  | 0.0%|
|auk-0182.smt2                                                                               |   7.389s  |   7.389s  |   0.000s  | 0.0%|
|auk-0183.smt2                                                                               |   1.965s  |   1.965s  |   0.000s  | 0.0%|
|auk-0184.smt2                                                                               |  30.046s  |  30.046s  |   0.000s  | 0.0%|
|auk-0185.smt2                                                                               |   8.165s  |   8.165s  |   0.000s  | 0.0%|
|auk-0186.smt2                                                                               |  30.062s  |  30.062s  |   0.000s  | 0.0%|
|auk-0187.smt2                                                                               |  30.035s  |  30.035s  |   0.000s  | 0.0%|
|auk-0188.smt2                                                                               |  30.078s  |  30.078s  |   0.000s  | 0.0%|
</details>
