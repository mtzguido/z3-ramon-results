# .

* SAT 1
* UNSAT 0
* TIMEOUT 0
* UNKNOWN 0

* UNSET 0

* ERROR 0

# Meta data

<pre>
Ramon benchmark for cvc5
-
Job description: 
Job tag: cvc5-qflia-onefile-main-decision-cube-20260405a
Runner: rise-runner-2
cvc5 repo: cvc5/cvc5
cvc5 commit: b71a42c4909452401500987a39b1cff64552accb
cvc5 branch: main
cvc5 portfolio mode: graduated
cvc5 portfolio strategies: "decision-cube"
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


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|n6468-problem_2__034.smt2                                    |    1.051s | 7492.0KiB| sat | 0 |  |  |
