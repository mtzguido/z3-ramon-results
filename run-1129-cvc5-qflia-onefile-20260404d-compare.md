Comparing data and data


# SUMMARY
- LHS tests = 1
- RHS tests = 1
- LHS success = 1  (100.0%)
- RHS success = 1  (100.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for cvc5
-
Job description: 
Job tag: cvc5-qflia-onefile-20260404d
Runner: rise-runner-2
cvc5 repo: cvc5/cvc5
cvc5 commit: b71a42c4909452401500987a39b1cff64552accb
cvc5 branch: main
cvc5 portfolio mode: graduated
cvc5 portfolio strategies: "decision-scatter,decision-cube,lemma-cube"
cvc5 partition budget: 8
cvc5 partitioning options: "--partition-when=tlimit --partition-start-time=3 --partition-time-interval=0.1 --partition-check=standard"
cvc5 solver options: ""
cvc5 solver jobs: 8
cvc5 timeout: 30
cvc5 inputs: inputs/QF_LIA/n6468-problem_2__034.smt2
cvc5 commit message: Add full support for proofs with CaDiCaL. (#12279)

When CaDiCaL is enabled as CDCL(T) SAT solver, we log the LRUP proof
produced by CaDiCaL and produce a proof with chain resolution steps when
a proof is requested from the SAT solver. The previous implementation
for proof-based unsat cores was removed in favor of generating full
proofs now.

Note this PR moves the implementation of the IPASIRUP implementation in
a separate file `src/prop/cadical/cdclt_propagator.[h,cpp]`. The
implementation for proof generation and logging is in
`src/prop/cadical/proof_tracer.[h,cpp]`.

Depends on #12284, #12285 and #12286, please review these PRs first.
This PR includes #12286, the commit adding full proof support is
https://github.com/cvc5/cvc5/pull/12279/commits/1986cb263dc2b5d79ab00efcb9438918e5f39384.

</pre>
# RHS
<pre>
Ramon benchmark for cvc5
-
Job description: 
Job tag: cvc5-qflia-onefile-20260404d
Runner: rise-runner-2
cvc5 repo: cvc5/cvc5
cvc5 commit: b71a42c4909452401500987a39b1cff64552accb
cvc5 branch: main
cvc5 portfolio mode: graduated
cvc5 portfolio strategies: "decision-scatter,decision-cube,lemma-cube"
cvc5 partition budget: 8
cvc5 partitioning options: "--partition-when=tlimit --partition-start-time=3 --partition-time-interval=0.1 --partition-check=standard"
cvc5 solver options: ""
cvc5 solver jobs: 8
cvc5 timeout: 30
cvc5 inputs: inputs/QF_LIA/n6468-problem_2__034.smt2
cvc5 commit message: Add full support for proofs with CaDiCaL. (#12279)

When CaDiCaL is enabled as CDCL(T) SAT solver, we log the LRUP proof
produced by CaDiCaL and produce a proof with chain resolution steps when
a proof is requested from the SAT solver. The previous implementation
for proof-based unsat cores was removed in favor of generating full
proofs now.

Note this PR moves the implementation of the IPASIRUP implementation in
a separate file `src/prop/cadical/cdclt_propagator.[h,cpp]`. The
implementation for proof generation and logging is in
`src/prop/cadical/proof_tracer.[h,cpp]`.

Depends on #12284, #12285 and #12286, please review these PRs first.
This PR includes #12286, the commit adding full proof support is
https://github.com/cvc5/cvc5/pull/12279/commits/1986cb263dc2b5d79ab00efcb9438918e5f39384.

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|n6468-problem_2__034.smt2                                                                   |   1.049s  |   1.049s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|n6468-problem_2__034.smt2                                                                   |   1.049s  |   1.049s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|n6468-problem_2__034.smt2                                                                   |   1.049s  |   1.049s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|n6468-problem_2__034.smt2                                                                   |   1.049s  |   1.049s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|n6468-problem_2__034.smt2                                                                  |   1.049s |7404.0KiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|n6468-problem_2__034.smt2                                                                  |   1.049s |7404.0KiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|n6468-problem_2__034.smt2                                                                   |7404.0KiB|7404.0KiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|n6468-problem_2__034.smt2                                                                   |7404.0KiB|7404.0KiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|n6468-problem_2__034.smt2                                                                   |7404.0KiB|7404.0KiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|n6468-problem_2__034.smt2                                                                   |7404.0KiB|7404.0KiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|n6468-problem_2__034.smt2                                                                  |   1.049s |7404.0KiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|n6468-problem_2__034.smt2                                                                  |   1.049s |7404.0KiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>
