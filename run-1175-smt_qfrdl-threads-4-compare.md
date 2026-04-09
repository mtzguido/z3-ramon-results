Comparing data and data


# SUMMARY
- LHS tests = 255
- RHS tests = 255
- LHS success = 255  (100.0%)
- RHS success = 255  (100.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt_qfrdl-threads-4
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: 477a1d817da44f7615fa53a10b4bd03d2cc84e48
Z3 branch: master
Z3 options: "-T:60 smt.threads=4 tactic.default_tactic=smt smt.auto_config=false"
Z3 inputs: inputs/QF_RDL
Z3 commit message: Add mod-factor-propagation lemma to NLA divisions solver (#9235)

When a monic x*y has a factor x with mod(x, p) = 0 (fixed), propagate
mod(x*y, p) = 0. This enables Z3 to prove divisibility properties like
x mod p = 0 => (x*y) mod p = 0, which previously timed out even for
p = 2. The lemma fires in the NLA divisions check and allows Gröbner
basis and LIA to subsequently derive distributivity of div over addition.

Extends division tuples from (q, x, y) to (q, x, y, r) to track the
mod lpvar. Also registers bounded divisions from the mod internalization
path in theory_lra, not just the idiv path.

Co-authored-by: Claude Opus 4.6 (1M context) <noreply@anthropic.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt_qfrdl-threads-4
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: 477a1d817da44f7615fa53a10b4bd03d2cc84e48
Z3 branch: master
Z3 options: "-T:60 smt.threads=4 tactic.default_tactic=smt smt.auto_config=false"
Z3 inputs: inputs/QF_RDL
Z3 commit message: Add mod-factor-propagation lemma to NLA divisions solver (#9235)

When a monic x*y has a factor x with mod(x, p) = 0 (fixed), propagate
mod(x*y, p) = 0. This enables Z3 to prove divisibility properties like
x mod p = 0 => (x*y) mod p = 0, which previously timed out even for
p = 2. The lemma fires in the NLA divisions check and allows Gröbner
basis and LIA to subsequently derive distributivity of div over addition.

Extends division tuples from (q, x, y) to (q, x, y, r) to track the
mod lpvar. Also registers bounded divisions from the mod internalization
path in theory_lra, not just the idiv path.

Co-authored-by: Claude Opus 4.6 (1M context) <noreply@anthropic.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|SMT-Temporal-Planning-Benchmarks/cooking01.smt2                                             |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking02.smt2                                             |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking03.smt2                                             |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking04.smt2                                             |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking05.smt2                                             |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking06.smt2                                             |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking07.smt2                                             |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking08.smt2                                             |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking09.smt2                                             |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking10.smt2                                             |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking11.smt2                                             |   0.191s  |   0.191s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking12.smt2                                             |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking13.smt2                                             |   0.174s  |   0.174s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking14.smt2                                             |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking15.smt2                                             |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking16.smt2                                             |   0.221s  |   0.221s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking17.smt2                                             |   0.228s  |   0.228s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking18.smt2                                             |   0.242s  |   0.242s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking19.smt2                                             |   0.209s  |   0.209s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking20.smt2                                             |   0.224s  |   0.224s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|SMT-Temporal-Planning-Benchmarks/cooking01.smt2                                             |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking02.smt2                                             |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking03.smt2                                             |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking04.smt2                                             |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking05.smt2                                             |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking06.smt2                                             |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking07.smt2                                             |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking08.smt2                                             |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking09.smt2                                             |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking10.smt2                                             |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking11.smt2                                             |   0.191s  |   0.191s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking12.smt2                                             |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking13.smt2                                             |   0.174s  |   0.174s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking14.smt2                                             |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking15.smt2                                             |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking16.smt2                                             |   0.221s  |   0.221s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking17.smt2                                             |   0.228s  |   0.228s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking18.smt2                                             |   0.242s  |   0.242s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking19.smt2                                             |   0.209s  |   0.209s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking20.smt2                                             |   0.224s  |   0.224s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|SMT-Temporal-Planning-Benchmarks/cooking01.smt2                                             |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking02.smt2                                             |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking03.smt2                                             |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking04.smt2                                             |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking05.smt2                                             |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking06.smt2                                             |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking07.smt2                                             |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking08.smt2                                             |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking09.smt2                                             |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking10.smt2                                             |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking11.smt2                                             |   0.191s  |   0.191s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking12.smt2                                             |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking13.smt2                                             |   0.174s  |   0.174s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking14.smt2                                             |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking15.smt2                                             |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking16.smt2                                             |   0.221s  |   0.221s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking17.smt2                                             |   0.228s  |   0.228s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking18.smt2                                             |   0.242s  |   0.242s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking19.smt2                                             |   0.209s  |   0.209s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking20.smt2                                             |   0.224s  |   0.224s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|SMT-Temporal-Planning-Benchmarks/cooking01.smt2                                             |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking02.smt2                                             |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking03.smt2                                             |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking04.smt2                                             |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking05.smt2                                             |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking06.smt2                                             |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking07.smt2                                             |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking08.smt2                                             |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking09.smt2                                             |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking10.smt2                                             |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking11.smt2                                             |   0.191s  |   0.191s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking12.smt2                                             |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking13.smt2                                             |   0.174s  |   0.174s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking14.smt2                                             |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking15.smt2                                             |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking16.smt2                                             |   0.221s  |   0.221s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking17.smt2                                             |   0.228s  |   0.228s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking18.smt2                                             |   0.242s  |   0.242s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking19.smt2                                             |   0.209s  |   0.209s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking20.smt2                                             |   0.224s  |   0.224s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|skdmxa2/skdmxa-3x3-18.base.cvc.smt2                                                        |  60.365s |2034.0MiB|
|skdmxa2/skdmxa-3x3-20.base.cvc.smt2                                                        |  60.310s |2545.0MiB|
|skdmxa2/skdmxa-3x3-19.base.cvc.smt2                                                        |  60.300s |2454.0MiB|
|scheduling/swv12_2972.smt2                                                                 |  60.271s |1043.0MiB|
|skdmxa2/skdmxa-3x3-15.base.cvc.smt2                                                        |  60.265s |1647.0MiB|
|scheduling/swv13_3104.smt2                                                                 |  60.245s |1024.0MiB|
|skdmxa2/skdmxa-3x3-16.base.cvc.smt2                                                        |  60.244s |1897.0MiB|
|skdmxa2/skdmxa-3x3-20.induction.cvc.smt2                                                   |  60.240s |1565.0MiB|
|skdmxa2/skdmxa-3x3-17.base.cvc.smt2                                                        |  60.233s |1792.0MiB|
|skdmxa2/skdmxa-3x3-18.induction.cvc.smt2                                                   |  60.229s |1527.0MiB|
|scheduling/swv11_2900.smt2                                                                 |  60.223s |1047.0MiB|
|scheduling/swv12_3004.smt2                                                                 |  60.220s |1036.0MiB|
|scheduling/swv14_2905.smt2                                                                 |  60.215s |1029.0MiB|
|scheduling/swv11_2988.smt2                                                                 |  60.195s |1041.0MiB|
|scheduling/swv14_3000.smt2                                                                 |  60.193s |1028.0MiB|
|skdmxa2/skdmxa-3x3-12.base.cvc.smt2                                                        |  60.188s |1006.0MiB|
|scheduling/swv13_3200.smt2                                                                 |  60.187s |1032.0MiB|
|scheduling/swv12_2990.smt2                                                                 |  60.187s |1036.0MiB|
|skdmxa2/skdmxa-3x3-14.base.cvc.smt2                                                        |  60.186s |1283.0MiB|
|scheduling/swv11_3050.smt2                                                                 |  60.178s |1036.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|skdmxa2/skdmxa-3x3-18.base.cvc.smt2                                                        |  60.365s |2034.0MiB|
|skdmxa2/skdmxa-3x3-20.base.cvc.smt2                                                        |  60.310s |2545.0MiB|
|skdmxa2/skdmxa-3x3-19.base.cvc.smt2                                                        |  60.300s |2454.0MiB|
|scheduling/swv12_2972.smt2                                                                 |  60.271s |1043.0MiB|
|skdmxa2/skdmxa-3x3-15.base.cvc.smt2                                                        |  60.265s |1647.0MiB|
|scheduling/swv13_3104.smt2                                                                 |  60.245s |1024.0MiB|
|skdmxa2/skdmxa-3x3-16.base.cvc.smt2                                                        |  60.244s |1897.0MiB|
|skdmxa2/skdmxa-3x3-20.induction.cvc.smt2                                                   |  60.240s |1565.0MiB|
|skdmxa2/skdmxa-3x3-17.base.cvc.smt2                                                        |  60.233s |1792.0MiB|
|skdmxa2/skdmxa-3x3-18.induction.cvc.smt2                                                   |  60.229s |1527.0MiB|
|scheduling/swv11_2900.smt2                                                                 |  60.223s |1047.0MiB|
|scheduling/swv12_3004.smt2                                                                 |  60.220s |1036.0MiB|
|scheduling/swv14_2905.smt2                                                                 |  60.215s |1029.0MiB|
|scheduling/swv11_2988.smt2                                                                 |  60.195s |1041.0MiB|
|scheduling/swv14_3000.smt2                                                                 |  60.193s |1028.0MiB|
|skdmxa2/skdmxa-3x3-12.base.cvc.smt2                                                        |  60.188s |1006.0MiB|
|scheduling/swv13_3200.smt2                                                                 |  60.187s |1032.0MiB|
|scheduling/swv12_2990.smt2                                                                 |  60.187s |1036.0MiB|
|skdmxa2/skdmxa-3x3-14.base.cvc.smt2                                                        |  60.186s |1283.0MiB|
|scheduling/swv11_3050.smt2                                                                 |  60.178s |1036.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|SMT-Temporal-Planning-Benchmarks/cooking01.smt2                                             |92.632MiB|92.632MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking02.smt2                                             |93.968MiB|93.968MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking03.smt2                                             |94.936MiB|94.936MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking04.smt2                                             |96.216MiB|96.216MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking05.smt2                                             |97.756MiB|97.756MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking06.smt2                                             |98.112MiB|98.112MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking07.smt2                                             |99.04MiB|99.04MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking08.smt2                                             |97.0MiB|97.0MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking09.smt2                                             |99.0MiB|99.0MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking10.smt2                                             |101.0MiB|101.0MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking11.smt2                                             |102.0MiB|102.0MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking12.smt2                                             |103.0MiB|103.0MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking13.smt2                                             |104.0MiB|104.0MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking14.smt2                                             |104.0MiB|104.0MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking15.smt2                                             |105.0MiB|105.0MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking16.smt2                                             |108.0MiB|108.0MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking17.smt2                                             |109.0MiB|109.0MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking18.smt2                                             |110.0MiB|110.0MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking19.smt2                                             |111.0MiB|111.0MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking20.smt2                                             |112.0MiB|112.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|SMT-Temporal-Planning-Benchmarks/cooking01.smt2                                             |92.632MiB|92.632MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking02.smt2                                             |93.968MiB|93.968MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking03.smt2                                             |94.936MiB|94.936MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking04.smt2                                             |96.216MiB|96.216MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking05.smt2                                             |97.756MiB|97.756MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking06.smt2                                             |98.112MiB|98.112MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking07.smt2                                             |99.04MiB|99.04MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking08.smt2                                             |97.0MiB|97.0MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking09.smt2                                             |99.0MiB|99.0MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking10.smt2                                             |101.0MiB|101.0MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking11.smt2                                             |102.0MiB|102.0MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking12.smt2                                             |103.0MiB|103.0MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking13.smt2                                             |104.0MiB|104.0MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking14.smt2                                             |104.0MiB|104.0MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking15.smt2                                             |105.0MiB|105.0MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking16.smt2                                             |108.0MiB|108.0MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking17.smt2                                             |109.0MiB|109.0MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking18.smt2                                             |110.0MiB|110.0MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking19.smt2                                             |111.0MiB|111.0MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking20.smt2                                             |112.0MiB|112.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|SMT-Temporal-Planning-Benchmarks/cooking01.smt2                                             |92.632MiB|92.632MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking02.smt2                                             |93.968MiB|93.968MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking03.smt2                                             |94.936MiB|94.936MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking04.smt2                                             |96.216MiB|96.216MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking05.smt2                                             |97.756MiB|97.756MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking06.smt2                                             |98.112MiB|98.112MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking07.smt2                                             |99.04MiB|99.04MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking08.smt2                                             |97.0MiB|97.0MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking09.smt2                                             |99.0MiB|99.0MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking10.smt2                                             |101.0MiB|101.0MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking11.smt2                                             |102.0MiB|102.0MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking12.smt2                                             |103.0MiB|103.0MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking13.smt2                                             |104.0MiB|104.0MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking14.smt2                                             |104.0MiB|104.0MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking15.smt2                                             |105.0MiB|105.0MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking16.smt2                                             |108.0MiB|108.0MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking17.smt2                                             |109.0MiB|109.0MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking18.smt2                                             |110.0MiB|110.0MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking19.smt2                                             |111.0MiB|111.0MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking20.smt2                                             |112.0MiB|112.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|SMT-Temporal-Planning-Benchmarks/cooking01.smt2                                             |92.632MiB|92.632MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking02.smt2                                             |93.968MiB|93.968MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking03.smt2                                             |94.936MiB|94.936MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking04.smt2                                             |96.216MiB|96.216MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking05.smt2                                             |97.756MiB|97.756MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking06.smt2                                             |98.112MiB|98.112MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking07.smt2                                             |99.04MiB|99.04MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking08.smt2                                             |97.0MiB|97.0MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking09.smt2                                             |99.0MiB|99.0MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking10.smt2                                             |101.0MiB|101.0MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking11.smt2                                             |102.0MiB|102.0MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking12.smt2                                             |103.0MiB|103.0MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking13.smt2                                             |104.0MiB|104.0MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking14.smt2                                             |104.0MiB|104.0MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking15.smt2                                             |105.0MiB|105.0MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking16.smt2                                             |108.0MiB|108.0MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking17.smt2                                             |109.0MiB|109.0MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking18.smt2                                             |110.0MiB|110.0MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking19.smt2                                             |111.0MiB|111.0MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking20.smt2                                             |112.0MiB|112.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|skdmxa2/skdmxa-3x3-20.base.cvc.smt2                                                        |  60.310s |2545.0MiB|
|skdmxa2/skdmxa-3x3-19.base.cvc.smt2                                                        |  60.300s |2454.0MiB|
|skdmxa2/skdmxa-3x3-18.base.cvc.smt2                                                        |  60.365s |2034.0MiB|
|skdmxa2/skdmxa-3x3-16.base.cvc.smt2                                                        |  60.244s |1897.0MiB|
|skdmxa2/skdmxa-3x3-17.base.cvc.smt2                                                        |  60.233s |1792.0MiB|
|skdmxa2/skdmxa-3x3-19.induction.cvc.smt2                                                   |  53.359s |1674.0MiB|
|skdmxa2/skdmxa-3x3-15.base.cvc.smt2                                                        |  60.265s |1647.0MiB|
|skdmxa2/skdmxa-3x3-20.induction.cvc.smt2                                                   |  60.240s |1565.0MiB|
|skdmxa2/skdmxa-3x3-18.induction.cvc.smt2                                                   |  60.229s |1527.0MiB|
|skdmxa2/skdmxa-3x3-17.induction.cvc.smt2                                                   |  51.076s |1399.0MiB|
|skdmxa2/skdmxa-3x3-14.base.cvc.smt2                                                        |  60.186s |1283.0MiB|
|skdmxa2/skdmxa-3x3-13.base.cvc.smt2                                                        |  60.157s |1118.0MiB|
|skdmxa2/skdmxa-3x3-15.induction.cvc.smt2                                                   |  28.944s |1112.0MiB|
|skdmxa2/skdmxa-3x3-16.induction.cvc.smt2                                                   |  23.810s |1093.0MiB|
|scheduling/swv11_2900.smt2                                                                 |  60.223s |1047.0MiB|
|scheduling/swv14_2800.smt2                                                                 |  60.170s |1047.0MiB|
|scheduling/swv12_3050.smt2                                                                 |  60.156s |1045.0MiB|
|scheduling/swv12_2972.smt2                                                                 |  60.271s |1043.0MiB|
|scheduling/swv11_2988.smt2                                                                 |  60.195s |1041.0MiB|
|scheduling/swv12_3004.smt2                                                                 |  60.220s |1036.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|skdmxa2/skdmxa-3x3-20.base.cvc.smt2                                                        |  60.310s |2545.0MiB|
|skdmxa2/skdmxa-3x3-19.base.cvc.smt2                                                        |  60.300s |2454.0MiB|
|skdmxa2/skdmxa-3x3-18.base.cvc.smt2                                                        |  60.365s |2034.0MiB|
|skdmxa2/skdmxa-3x3-16.base.cvc.smt2                                                        |  60.244s |1897.0MiB|
|skdmxa2/skdmxa-3x3-17.base.cvc.smt2                                                        |  60.233s |1792.0MiB|
|skdmxa2/skdmxa-3x3-19.induction.cvc.smt2                                                   |  53.359s |1674.0MiB|
|skdmxa2/skdmxa-3x3-15.base.cvc.smt2                                                        |  60.265s |1647.0MiB|
|skdmxa2/skdmxa-3x3-20.induction.cvc.smt2                                                   |  60.240s |1565.0MiB|
|skdmxa2/skdmxa-3x3-18.induction.cvc.smt2                                                   |  60.229s |1527.0MiB|
|skdmxa2/skdmxa-3x3-17.induction.cvc.smt2                                                   |  51.076s |1399.0MiB|
|skdmxa2/skdmxa-3x3-14.base.cvc.smt2                                                        |  60.186s |1283.0MiB|
|skdmxa2/skdmxa-3x3-13.base.cvc.smt2                                                        |  60.157s |1118.0MiB|
|skdmxa2/skdmxa-3x3-15.induction.cvc.smt2                                                   |  28.944s |1112.0MiB|
|skdmxa2/skdmxa-3x3-16.induction.cvc.smt2                                                   |  23.810s |1093.0MiB|
|scheduling/swv11_2900.smt2                                                                 |  60.223s |1047.0MiB|
|scheduling/swv14_2800.smt2                                                                 |  60.170s |1047.0MiB|
|scheduling/swv12_3050.smt2                                                                 |  60.156s |1045.0MiB|
|scheduling/swv12_2972.smt2                                                                 |  60.271s |1043.0MiB|
|scheduling/swv11_2988.smt2                                                                 |  60.195s |1041.0MiB|
|scheduling/swv12_3004.smt2                                                                 |  60.220s |1036.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|SMT-Temporal-Planning-Benchmarks/cooking01.smt2                                             |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking02.smt2                                             |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking03.smt2                                             |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking04.smt2                                             |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking05.smt2                                             |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking06.smt2                                             |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking07.smt2                                             |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking08.smt2                                             |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking09.smt2                                             |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking10.smt2                                             |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking11.smt2                                             |   0.191s  |   0.191s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking12.smt2                                             |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking13.smt2                                             |   0.174s  |   0.174s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking14.smt2                                             |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking15.smt2                                             |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking16.smt2                                             |   0.221s  |   0.221s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking17.smt2                                             |   0.228s  |   0.228s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking18.smt2                                             |   0.242s  |   0.242s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking19.smt2                                             |   0.209s  |   0.209s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking20.smt2                                             |   0.224s  |   0.224s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking21.smt2                                             |   0.257s  |   0.257s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking22.smt2                                             |   0.260s  |   0.260s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-depth-2.smt2                                         |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-depth-3.smt2                                         |   0.191s  |   0.191s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-depth-4.smt2                                         |   0.403s  |   0.403s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-depth-5.smt2                                         |   0.749s  |   0.749s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-depth-6.smt2                                         |   1.412s  |   1.412s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-depth-7.smt2                                         |   2.714s  |   2.714s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-matrix1x1.pddl.smt2                                  |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-matrix2x2.pddl.smt2                                  |   4.163s  |   4.163s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-width-1.smt2                                         |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-width-2.smt2                                         |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-width-3.smt2                                         |   0.277s  |   0.277s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-width-4.smt2                                         |   0.856s  |   0.856s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-width-5.smt2                                         |   2.936s  |   2.936s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-width-6.smt2                                         |   9.084s  |   9.084s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-03.smt2                                      |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-04.smt2                                      |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-05.smt2                                      |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-06.smt2                                      |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-07.smt2                                      |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-08.smt2                                      |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-09.smt2                                      |   0.186s  |   0.186s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-10.smt2                                      |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-20.smt2                                      |   0.274s  |   0.274s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-30.smt2                                      |   0.346s  |   0.346s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-40.smt2                                      |   0.481s  |   0.481s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-60.smt2                                      |   0.683s  |   0.683s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-70.smt2                                      |   0.783s  |   0.783s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-80.smt2                                      |   0.855s  |   0.855s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-90.smt2                                      |   0.979s  |   0.979s  |   0.000s  | 0.0%|
|check/bignum_rdl1.smt2                                                                      |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|check/bignum_rdl2.smt2                                                                      |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-1.smt2                                                                   |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-10.smt2                                                                  |   0.693s  |   0.693s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-11.smt2                                                                  |   0.961s  |   0.961s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-12.smt2                                                                  |   1.748s  |   1.748s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-13.smt2                                                                  |   2.979s  |   2.979s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-14.smt2                                                                  |   3.437s  |   3.437s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-15.smt2                                                                  |   3.681s  |   3.681s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-16.smt2                                                                  |   3.951s  |   3.951s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-17.smt2                                                                  |   7.087s  |   7.087s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-18.smt2                                                                  |  12.592s  |  12.592s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-19.smt2                                                                  |  14.451s  |  14.451s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-2.smt2                                                                   |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-20.smt2                                                                  |  17.532s  |  17.532s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-3.smt2                                                                   |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-4.smt2                                                                   |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-5.smt2                                                                   |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-6.smt2                                                                   |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-7.smt2                                                                   |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-8.smt2                                                                   |   0.218s  |   0.218s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-9.smt2                                                                   |   0.353s  |   0.353s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-1.smt2                                                                   |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-10.smt2                                                                  |   7.899s  |   7.899s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-11.smt2                                                                  |  25.852s  |  25.852s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-12.smt2                                                                  |  40.362s  |  40.362s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-13.smt2                                                                  |  60.027s  |  60.027s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-14.smt2                                                                  |  60.031s  |  60.031s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-15.smt2                                                                  |  60.058s  |  60.058s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-16.smt2                                                                  |  60.053s  |  60.053s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-17.smt2                                                                  |  60.069s  |  60.069s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-18.smt2                                                                  |  60.064s  |  60.064s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-19.smt2                                                                  |  60.072s  |  60.072s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-2.smt2                                                                   |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-20.smt2                                                                  |  60.063s  |  60.063s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-3.smt2                                                                   |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-4.smt2                                                                   |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-5.smt2                                                                   |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-6.smt2                                                                   |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-7.smt2                                                                   |   0.246s  |   0.246s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-8.smt2                                                                   |   0.551s  |   0.551s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-9.smt2                                                                   |   2.719s  |   2.719s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-1.smt2                                                                   |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-10.smt2                                                                  |  25.705s  |  25.705s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-11.smt2                                                                  |  58.101s  |  58.101s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-12.smt2                                                                  |  60.058s  |  60.058s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-13.smt2                                                                  |  60.046s  |  60.046s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-14.smt2                                                                  |  60.054s  |  60.054s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-15.smt2                                                                  |  60.072s  |  60.072s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-16.smt2                                                                  |  60.080s  |  60.080s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-17.smt2                                                                  |  60.080s  |  60.080s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-18.smt2                                                                  |  60.043s  |  60.043s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-19.smt2                                                                  |  60.056s  |  60.056s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-2.smt2                                                                   |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-20.smt2                                                                  |  60.075s  |  60.075s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-3.smt2                                                                   |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-4.smt2                                                                   |   0.188s  |   0.188s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-5.smt2                                                                   |   0.239s  |   0.239s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-6.smt2                                                                   |   0.268s  |   0.268s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-7.smt2                                                                   |   0.434s  |   0.434s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-8.smt2                                                                   |   1.113s  |   1.113s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-9.smt2                                                                   |  12.239s  |  12.239s  |   0.000s  | 0.0%|
|scheduling/abz5_1000.smt2                                                                   |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|scheduling/abz5_1200.smt2                                                                   |   3.812s  |   3.812s  |   0.000s  | 0.0%|
|scheduling/abz5_1234.smt2                                                                   |   3.686s  |   3.686s  |   0.000s  | 0.0%|
|scheduling/abz5_1300.smt2                                                                   |   1.387s  |   1.387s  |   0.000s  | 0.0%|
|scheduling/abz5_1400.smt2                                                                   |   0.275s  |   0.275s  |   0.000s  | 0.0%|
|scheduling/abz6_1000.smt2                                                                   |   0.493s  |   0.493s  |   0.000s  | 0.0%|
|scheduling/abz6_1100.smt2                                                                   |   0.388s  |   0.388s  |   0.000s  | 0.0%|
|scheduling/abz6_800.smt2                                                                    |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|scheduling/abz6_900.smt2                                                                    |   0.380s  |   0.380s  |   0.000s  | 0.0%|
|scheduling/abz6_943.smt2                                                                    |   1.409s  |   1.409s  |   0.000s  | 0.0%|
|scheduling/abz7_500.smt2                                                                    |   1.488s  |   1.488s  |   0.000s  | 0.0%|
|scheduling/abz7_600.smt2                                                                    |  60.069s  |  60.069s  |   0.000s  | 0.0%|
|scheduling/abz7_667.smt2                                                                    |  60.090s  |  60.090s  |   0.000s  | 0.0%|
|scheduling/abz7_670.smt2                                                                    |  60.075s  |  60.075s  |   0.000s  | 0.0%|
|scheduling/abz7_691.smt2                                                                    |  60.088s  |  60.088s  |   0.000s  | 0.0%|
|scheduling/abz7_700.smt2                                                                    |  60.082s  |  60.082s  |   0.000s  | 0.0%|
|scheduling/abz7_800.smt2                                                                    |  60.112s  |  60.112s  |   0.000s  | 0.0%|
|scheduling/orb01_1000.smt2                                                                  |  39.129s  |  39.129s  |   0.000s  | 0.0%|
|scheduling/orb01_1059.smt2                                                                  |  60.050s  |  60.050s  |   0.000s  | 0.0%|
|scheduling/orb01_1100.smt2                                                                  |  39.450s  |  39.450s  |   0.000s  | 0.0%|
|scheduling/orb01_1200.smt2                                                                  |   1.962s  |   1.962s  |   0.000s  | 0.0%|
|scheduling/orb01_900.smt2                                                                   |   0.725s  |   0.725s  |   0.000s  | 0.0%|
|scheduling/orb02_1000.smt2                                                                  |   0.396s  |   0.396s  |   0.000s  | 0.0%|
|scheduling/orb02_700.smt2                                                                   |   0.175s  |   0.175s  |   0.000s  | 0.0%|
|scheduling/orb02_800.smt2                                                                   |   0.257s  |   0.257s  |   0.000s  | 0.0%|
|scheduling/orb02_888.smt2                                                                   |   4.788s  |   4.788s  |   0.000s  | 0.0%|
|scheduling/orb02_900.smt2                                                                   |   1.428s  |   1.428s  |   0.000s  | 0.0%|
|scheduling/orb03_1005.smt2                                                                  |  60.036s  |  60.036s  |   0.000s  | 0.0%|
|scheduling/orb03_1100.smt2                                                                  |  20.083s  |  20.083s  |   0.000s  | 0.0%|
|scheduling/orb03_1200.smt2                                                                  |   1.258s  |   1.258s  |   0.000s  | 0.0%|
|scheduling/orb03_850.smt2                                                                   |   0.383s  |   0.383s  |   0.000s  | 0.0%|
|scheduling/orb03_950.smt2                                                                   |  11.397s  |  11.397s  |   0.000s  | 0.0%|
|scheduling/orb04_1005.smt2                                                                  |  14.803s  |  14.803s  |   0.000s  | 0.0%|
|scheduling/orb04_1100.smt2                                                                  |   0.407s  |   0.407s  |   0.000s  | 0.0%|
|scheduling/orb04_1200.smt2                                                                  |   0.266s  |   0.266s  |   0.000s  | 0.0%|
|scheduling/orb04_850.smt2                                                                   |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|scheduling/orb04_950.smt2                                                                   |   0.589s  |   0.589s  |   0.000s  | 0.0%|
|scheduling/orb05_1000.smt2                                                                  |   0.440s  |   0.440s  |   0.000s  | 0.0%|
|scheduling/orb05_700.smt2                                                                   |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|scheduling/orb05_800.smt2                                                                   |   0.515s  |   0.515s  |   0.000s  | 0.0%|
|scheduling/orb05_887.smt2                                                                   |  11.047s  |  11.047s  |   0.000s  | 0.0%|
|scheduling/orb05_900.smt2                                                                   |   1.879s  |   1.879s  |   0.000s  | 0.0%|
|scheduling/orb06_1000.smt2                                                                  |  60.050s  |  60.050s  |   0.000s  | 0.0%|
|scheduling/orb06_1010.smt2                                                                  |  60.067s  |  60.067s  |   0.000s  | 0.0%|
|scheduling/orb06_1100.smt2                                                                  |   2.144s  |   2.144s  |   0.000s  | 0.0%|
|scheduling/orb06_1200.smt2                                                                  |   0.339s  |   0.339s  |   0.000s  | 0.0%|
|scheduling/orb06_900.smt2                                                                   |   0.580s  |   0.580s  |   0.000s  | 0.0%|
|scheduling/orb07_250.smt2                                                                   |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|scheduling/orb07_330.smt2                                                                   |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|scheduling/orb07_397.smt2                                                                   |   7.495s  |   7.495s  |   0.000s  | 0.0%|
|scheduling/orb07_430.smt2                                                                   |   0.536s  |   0.536s  |   0.000s  | 0.0%|
|scheduling/orb07_550.smt2                                                                   |   0.214s  |   0.214s  |   0.000s  | 0.0%|
|scheduling/orb08_1000.smt2                                                                  |   0.870s  |   0.870s  |   0.000s  | 0.0%|
|scheduling/orb08_700.smt2                                                                   |   0.244s  |   0.244s  |   0.000s  | 0.0%|
|scheduling/orb08_830.smt2                                                                   |   0.413s  |   0.413s  |   0.000s  | 0.0%|
|scheduling/orb08_888.smt2                                                                   |  28.323s  |  28.323s  |   0.000s  | 0.0%|
|scheduling/orb08_930.smt2                                                                   |   6.838s  |   6.838s  |   0.000s  | 0.0%|
|scheduling/orb09_1000.smt2                                                                  |   1.307s  |   1.307s  |   0.000s  | 0.0%|
|scheduling/orb09_1100.smt2                                                                  |   0.324s  |   0.324s  |   0.000s  | 0.0%|
|scheduling/orb09_800.smt2                                                                   |   0.273s  |   0.273s  |   0.000s  | 0.0%|
|scheduling/orb09_900.smt2                                                                   |   2.720s  |   2.720s  |   0.000s  | 0.0%|
|scheduling/orb09_934.smt2                                                                   |   9.406s  |   9.406s  |   0.000s  | 0.0%|
|scheduling/orb10_1000.smt2                                                                  |   0.833s  |   0.833s  |   0.000s  | 0.0%|
|scheduling/orb10_1100.smt2                                                                  |   0.367s  |   0.367s  |   0.000s  | 0.0%|
|scheduling/orb10_800.smt2                                                                   |   0.251s  |   0.251s  |   0.000s  | 0.0%|
|scheduling/orb10_900.smt2                                                                   |   1.726s  |   1.726s  |   0.000s  | 0.0%|
|scheduling/orb10_944.smt2                                                                   |   8.776s  |   8.776s  |   0.000s  | 0.0%|
|scheduling/swv11_2900.smt2                                                                  |  60.223s  |  60.223s  |   0.000s  | 0.0%|
|scheduling/swv11_2983.smt2                                                                  |  60.160s  |  60.160s  |   0.000s  | 0.0%|
|scheduling/swv11_2988.smt2                                                                  |  60.195s  |  60.195s  |   0.000s  | 0.0%|
|scheduling/swv11_2992.smt2                                                                  |  60.176s  |  60.176s  |   0.000s  | 0.0%|
|scheduling/swv11_3050.smt2                                                                  |  60.178s  |  60.178s  |   0.000s  | 0.0%|
|scheduling/swv12_2900.smt2                                                                  |  60.171s  |  60.171s  |   0.000s  | 0.0%|
|scheduling/swv12_2972.smt2                                                                  |  60.271s  |  60.271s  |   0.000s  | 0.0%|
|scheduling/swv12_2990.smt2                                                                  |  60.187s  |  60.187s  |   0.000s  | 0.0%|
|scheduling/swv12_3004.smt2                                                                  |  60.220s  |  60.220s  |   0.000s  | 0.0%|
|scheduling/swv12_3050.smt2                                                                  |  60.156s  |  60.156s  |   0.000s  | 0.0%|
|scheduling/swv13_3000.smt2                                                                  |  60.150s  |  60.150s  |   0.000s  | 0.0%|
|scheduling/swv13_3104.smt2                                                                  |  60.245s  |  60.245s  |   0.000s  | 0.0%|
|scheduling/swv13_3150.smt2                                                                  |  60.170s  |  60.170s  |   0.000s  | 0.0%|
|scheduling/swv13_3200.smt2                                                                  |  60.187s  |  60.187s  |   0.000s  | 0.0%|
|scheduling/swv14_2800.smt2                                                                  |  60.170s  |  60.170s  |   0.000s  | 0.0%|
|scheduling/swv14_2885.smt2                                                                  |  60.171s  |  60.171s  |   0.000s  | 0.0%|
|scheduling/swv14_2895.smt2                                                                  |  60.142s  |  60.142s  |   0.000s  | 0.0%|
|scheduling/swv14_2905.smt2                                                                  |  60.215s  |  60.215s  |   0.000s  | 0.0%|
|scheduling/swv14_3000.smt2                                                                  |  60.193s  |  60.193s  |   0.000s  | 0.0%|
|scheduling/yn1_750.smt2                                                                     |   1.852s  |   1.852s  |   0.000s  | 0.0%|
|scheduling/yn1_827.smt2                                                                     |  60.087s  |  60.087s  |   0.000s  | 0.0%|
|scheduling/yn1_850.smt2                                                                     |  60.099s  |  60.099s  |   0.000s  | 0.0%|
|scheduling/yn1_887.smt2                                                                     |  60.116s  |  60.116s  |   0.000s  | 0.0%|
|scheduling/yn1_950.smt2                                                                     |  60.082s  |  60.082s  |   0.000s  | 0.0%|
|scheduling/yn2_750.smt2                                                                     |   2.335s  |   2.335s  |   0.000s  | 0.0%|
|scheduling/yn2_862.smt2                                                                     |  60.092s  |  60.092s  |   0.000s  | 0.0%|
|scheduling/yn2_890.smt2                                                                     |  60.090s  |  60.090s  |   0.000s  | 0.0%|
|scheduling/yn2_910.smt2                                                                     |  60.066s  |  60.066s  |   0.000s  | 0.0%|
|scheduling/yn2_950.smt2                                                                     |  60.095s  |  60.095s  |   0.000s  | 0.0%|
|scheduling/yn3_750.smt2                                                                     |   1.829s  |   1.829s  |   0.000s  | 0.0%|
|scheduling/yn3_828.smt2                                                                     |  60.074s  |  60.074s  |   0.000s  | 0.0%|
|scheduling/yn3_860.smt2                                                                     |  60.068s  |  60.068s  |   0.000s  | 0.0%|
|scheduling/yn3_894.smt2                                                                     |  60.110s  |  60.110s  |   0.000s  | 0.0%|
|scheduling/yn3_950.smt2                                                                     |  60.114s  |  60.114s  |   0.000s  | 0.0%|
|scheduling/yn4_1000.smt2                                                                    |  60.072s  |  60.072s  |   0.000s  | 0.0%|
|scheduling/yn4_850.smt2                                                                     |  60.107s  |  60.107s  |   0.000s  | 0.0%|
|scheduling/yn4_919.smt2                                                                     |  60.078s  |  60.078s  |   0.000s  | 0.0%|
|scheduling/yn4_950.smt2                                                                     |  60.109s  |  60.109s  |   0.000s  | 0.0%|
|scheduling/yn4_969.smt2                                                                     |  60.104s  |  60.104s  |   0.000s  | 0.0%|
|skdmxa/skdmxa-3x3-10.smt2                                                                   |  10.880s  |  10.880s  |   0.000s  | 0.0%|
|skdmxa/skdmxa-3x3-15.smt2                                                                   |  60.106s  |  60.106s  |   0.000s  | 0.0%|
|skdmxa/skdmxa-3x3-20.smt2                                                                   |  60.156s  |  60.156s  |   0.000s  | 0.0%|
|skdmxa/skdmxa-3x3-5.smt2                                                                    |   1.292s  |   1.292s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-10.base.cvc.smt2                                                         |  24.387s  |  24.387s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-10.induction.cvc.smt2                                                    |   7.644s  |   7.644s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-11.base.cvc.smt2                                                         |  45.273s  |  45.273s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-11.induction.cvc.smt2                                                    |  11.868s  |  11.868s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-12.base.cvc.smt2                                                         |  60.188s  |  60.188s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-12.induction.cvc.smt2                                                    |  13.262s  |  13.262s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-13.base.cvc.smt2                                                         |  60.157s  |  60.157s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-13.induction.cvc.smt2                                                    |  22.864s  |  22.864s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-14.base.cvc.smt2                                                         |  60.186s  |  60.186s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-14.induction.cvc.smt2                                                    |  21.785s  |  21.785s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-15.base.cvc.smt2                                                         |  60.265s  |  60.265s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-15.induction.cvc.smt2                                                    |  28.944s  |  28.944s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-16.base.cvc.smt2                                                         |  60.244s  |  60.244s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-16.induction.cvc.smt2                                                    |  23.810s  |  23.810s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-17.base.cvc.smt2                                                         |  60.233s  |  60.233s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-17.induction.cvc.smt2                                                    |  51.076s  |  51.076s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-18.base.cvc.smt2                                                         |  60.365s  |  60.365s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-18.induction.cvc.smt2                                                    |  60.229s  |  60.229s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-19.base.cvc.smt2                                                         |  60.300s  |  60.300s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-19.induction.cvc.smt2                                                    |  53.359s  |  53.359s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-20.base.cvc.smt2                                                         |  60.310s  |  60.310s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-20.induction.cvc.smt2                                                    |  60.240s  |  60.240s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-5.base.cvc.smt2                                                          |   2.068s  |   2.068s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-5.induction.cvc.smt2                                                     |   1.885s  |   1.885s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-6.base.cvc.smt2                                                          |   3.066s  |   3.066s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-6.induction.cvc.smt2                                                     |   2.476s  |   2.476s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-7.base.cvc.smt2                                                          |   5.068s  |   5.068s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-7.induction.cvc.smt2                                                     |   5.179s  |   5.179s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-8.base.cvc.smt2                                                          |   6.273s  |   6.273s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-8.induction.cvc.smt2                                                     |   4.394s  |   4.394s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-9.base.cvc.smt2                                                          |  15.162s  |  15.162s  |   0.000s  | 0.0%|
</details>
