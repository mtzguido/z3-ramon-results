Comparing data and data


# SUMMARY
- LHS tests = 922
- RHS tests = 922
- LHS success = 922  (100.0%)
- RHS success = 922  (100.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-QF_LIA_hard-timeout10min-bb2
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: f880fdccee614547c38c19beb7af5a027961646b
Z3 branch: core_min
Z3 options: "-T:600 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: https://zenodo.org/records/16740866/files/QF_LIA.tar.zst?download=1
Z3 commit message: Merge branch 'master' of github.com:Z3Prover/z3 into core_min

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-QF_LIA_hard-timeout10min-bb2
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: f880fdccee614547c38c19beb7af5a027961646b
Z3 branch: core_min
Z3 options: "-T:600 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: https://zenodo.org/records/16740866/files/QF_LIA.tar.zst?download=1
Z3 commit message: Merge branch 'master' of github.com:Z3Prover/z3 into core_min

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_LIA/2019-cmodelsdiff/boundsmodels/dp_10.formula1-s-O2-b9.smo2.smt2       |   0.730s  |   0.730s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/boundsmodels/dp_12.formula1-s-O2-b10.smo2.smt2      |   0.943s  |   0.943s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/boundsmodels/dp_8.formula1-i-O2-b10.smo2.smt2       |   0.720s  |   0.720s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/mutualExclusion/mutex1.smt2                         |   0.514s  |   0.514s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b1.lp.smt2                   |   0.750s  |   0.750s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b10.lp.smt2                  |   0.698s  |   0.698s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b11.lp.smt2                  |   0.679s  |   0.679s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b12.lp.smt2                  |   0.696s  |   0.696s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b13.lp.smt2                  |   0.799s  |   0.799s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b14.lp.smt2                  |   0.710s  |   0.710s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b15.lp.smt2                  |   0.725s  |   0.725s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b16.lp.smt2                  |   0.700s  |   0.700s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b17.lp.smt2                  |   0.668s  |   0.668s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b18.lp.smt2                  |   0.694s  |   0.694s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b19.lp.smt2                  |   0.684s  |   0.684s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b2.lp.smt2                   |   0.740s  |   0.740s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b20.lp.smt2                  |   0.799s  |   0.799s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b3.lp.smt2                   |   0.717s  |   0.717s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b4.lp.smt2                   |   0.715s  |   0.715s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b5.lp.smt2                   |   0.733s  |   0.733s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_LIA/2019-cmodelsdiff/boundsmodels/dp_10.formula1-s-O2-b9.smo2.smt2       |   0.730s  |   0.730s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/boundsmodels/dp_12.formula1-s-O2-b10.smo2.smt2      |   0.943s  |   0.943s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/boundsmodels/dp_8.formula1-i-O2-b10.smo2.smt2       |   0.720s  |   0.720s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/mutualExclusion/mutex1.smt2                         |   0.514s  |   0.514s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b1.lp.smt2                   |   0.750s  |   0.750s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b10.lp.smt2                  |   0.698s  |   0.698s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b11.lp.smt2                  |   0.679s  |   0.679s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b12.lp.smt2                  |   0.696s  |   0.696s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b13.lp.smt2                  |   0.799s  |   0.799s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b14.lp.smt2                  |   0.710s  |   0.710s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b15.lp.smt2                  |   0.725s  |   0.725s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b16.lp.smt2                  |   0.700s  |   0.700s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b17.lp.smt2                  |   0.668s  |   0.668s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b18.lp.smt2                  |   0.694s  |   0.694s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b19.lp.smt2                  |   0.684s  |   0.684s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b2.lp.smt2                   |   0.740s  |   0.740s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b20.lp.smt2                  |   0.799s  |   0.799s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b3.lp.smt2                   |   0.717s  |   0.717s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b4.lp.smt2                   |   0.715s  |   0.715s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b5.lp.smt2                   |   0.733s  |   0.733s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_LIA/2019-cmodelsdiff/boundsmodels/dp_10.formula1-s-O2-b9.smo2.smt2       |   0.730s  |   0.730s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/boundsmodels/dp_12.formula1-s-O2-b10.smo2.smt2      |   0.943s  |   0.943s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/boundsmodels/dp_8.formula1-i-O2-b10.smo2.smt2       |   0.720s  |   0.720s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/mutualExclusion/mutex1.smt2                         |   0.514s  |   0.514s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b1.lp.smt2                   |   0.750s  |   0.750s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b10.lp.smt2                  |   0.698s  |   0.698s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b11.lp.smt2                  |   0.679s  |   0.679s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b12.lp.smt2                  |   0.696s  |   0.696s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b13.lp.smt2                  |   0.799s  |   0.799s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b14.lp.smt2                  |   0.710s  |   0.710s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b15.lp.smt2                  |   0.725s  |   0.725s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b16.lp.smt2                  |   0.700s  |   0.700s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b17.lp.smt2                  |   0.668s  |   0.668s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b18.lp.smt2                  |   0.694s  |   0.694s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b19.lp.smt2                  |   0.684s  |   0.684s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b2.lp.smt2                   |   0.740s  |   0.740s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b20.lp.smt2                  |   0.799s  |   0.799s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b3.lp.smt2                   |   0.717s  |   0.717s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b4.lp.smt2                   |   0.715s  |   0.715s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b5.lp.smt2                   |   0.733s  |   0.733s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_LIA/2019-cmodelsdiff/boundsmodels/dp_10.formula1-s-O2-b9.smo2.smt2       |   0.730s  |   0.730s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/boundsmodels/dp_12.formula1-s-O2-b10.smo2.smt2      |   0.943s  |   0.943s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/boundsmodels/dp_8.formula1-i-O2-b10.smo2.smt2       |   0.720s  |   0.720s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/mutualExclusion/mutex1.smt2                         |   0.514s  |   0.514s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b1.lp.smt2                   |   0.750s  |   0.750s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b10.lp.smt2                  |   0.698s  |   0.698s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b11.lp.smt2                  |   0.679s  |   0.679s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b12.lp.smt2                  |   0.696s  |   0.696s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b13.lp.smt2                  |   0.799s  |   0.799s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b14.lp.smt2                  |   0.710s  |   0.710s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b15.lp.smt2                  |   0.725s  |   0.725s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b16.lp.smt2                  |   0.700s  |   0.700s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b17.lp.smt2                  |   0.668s  |   0.668s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b18.lp.smt2                  |   0.694s  |   0.694s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b19.lp.smt2                  |   0.684s  |   0.684s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b2.lp.smt2                   |   0.740s  |   0.740s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b20.lp.smt2                  |   0.799s  |   0.799s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b3.lp.smt2                   |   0.717s  |   0.717s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b4.lp.smt2                   |   0.715s  |   0.715s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b5.lp.smt2                   |   0.733s  |   0.733s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/QF_LIA/arctic-matrix/constraint-904583.smt2                                | 601.077s |6560.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-777746.smt2                                | 601.030s |5793.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-873799.smt2                                | 601.017s |5809.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-902192.smt2                                | 600.897s |5669.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-968440.smt2                                | 600.870s |6359.0MiB|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-40-50.smt2                         | 600.850s |5129.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-851594.smt2                              | 600.786s |5679.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-983194.smt2                              | 600.762s |6445.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-861420.smt2                              | 600.751s |5851.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-737829.smt2                              | 600.730s |4697.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-804609.smt2                                | 600.723s |5383.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-765743.smt2                                | 600.721s |4858.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-863289.smt2                                | 600.690s |5754.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-569261.smt2                                | 600.663s |3702.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-735583.smt2                              | 600.648s |4839.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-740637.smt2                              | 600.620s |4096.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-655888.smt2                                | 600.611s |4439.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-644402.smt2                                | 600.605s |4235.0MiB|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-10-48.smt2                       | 600.598s |5425.0MiB|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-28-50.smt2                         | 600.597s |5285.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/QF_LIA/arctic-matrix/constraint-904583.smt2                                | 601.077s |6560.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-777746.smt2                                | 601.030s |5793.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-873799.smt2                                | 601.017s |5809.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-902192.smt2                                | 600.897s |5669.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-968440.smt2                                | 600.870s |6359.0MiB|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-40-50.smt2                         | 600.850s |5129.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-851594.smt2                              | 600.786s |5679.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-983194.smt2                              | 600.762s |6445.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-861420.smt2                              | 600.751s |5851.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-737829.smt2                              | 600.730s |4697.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-804609.smt2                                | 600.723s |5383.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-765743.smt2                                | 600.721s |4858.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-863289.smt2                                | 600.690s |5754.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-569261.smt2                                | 600.663s |3702.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-735583.smt2                              | 600.648s |4839.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-740637.smt2                              | 600.620s |4096.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-655888.smt2                                | 600.611s |4439.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-644402.smt2                                | 600.605s |4235.0MiB|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-10-48.smt2                       | 600.598s |5425.0MiB|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-28-50.smt2                         | 600.597s |5285.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_LIA/2019-cmodelsdiff/boundsmodels/dp_10.formula1-s-O2-b9.smo2.smt2       |260.0MiB|260.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/boundsmodels/dp_12.formula1-s-O2-b10.smo2.smt2      |280.0MiB|280.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/boundsmodels/dp_8.formula1-i-O2-b10.smo2.smt2       |258.0MiB|258.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/mutualExclusion/mutex1.smt2                         |250.0MiB|250.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b1.lp.smt2                   |269.0MiB|269.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b10.lp.smt2                  |267.0MiB|267.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b11.lp.smt2                  |267.0MiB|267.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b12.lp.smt2                  |266.0MiB|266.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b13.lp.smt2                  |271.0MiB|271.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b14.lp.smt2                  |268.0MiB|268.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b15.lp.smt2                  |267.0MiB|267.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b16.lp.smt2                  |267.0MiB|267.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b17.lp.smt2                  |263.0MiB|263.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b18.lp.smt2                  |267.0MiB|267.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b19.lp.smt2                  |268.0MiB|268.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b2.lp.smt2                   |268.0MiB|268.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b20.lp.smt2                  |271.0MiB|271.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b3.lp.smt2                   |266.0MiB|266.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b4.lp.smt2                   |267.0MiB|267.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b5.lp.smt2                   |268.0MiB|268.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_LIA/2019-cmodelsdiff/boundsmodels/dp_10.formula1-s-O2-b9.smo2.smt2       |260.0MiB|260.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/boundsmodels/dp_12.formula1-s-O2-b10.smo2.smt2      |280.0MiB|280.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/boundsmodels/dp_8.formula1-i-O2-b10.smo2.smt2       |258.0MiB|258.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/mutualExclusion/mutex1.smt2                         |250.0MiB|250.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b1.lp.smt2                   |269.0MiB|269.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b10.lp.smt2                  |267.0MiB|267.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b11.lp.smt2                  |267.0MiB|267.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b12.lp.smt2                  |266.0MiB|266.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b13.lp.smt2                  |271.0MiB|271.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b14.lp.smt2                  |268.0MiB|268.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b15.lp.smt2                  |267.0MiB|267.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b16.lp.smt2                  |267.0MiB|267.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b17.lp.smt2                  |263.0MiB|263.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b18.lp.smt2                  |267.0MiB|267.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b19.lp.smt2                  |268.0MiB|268.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b2.lp.smt2                   |268.0MiB|268.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b20.lp.smt2                  |271.0MiB|271.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b3.lp.smt2                   |266.0MiB|266.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b4.lp.smt2                   |267.0MiB|267.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b5.lp.smt2                   |268.0MiB|268.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_LIA/2019-cmodelsdiff/boundsmodels/dp_10.formula1-s-O2-b9.smo2.smt2       |260.0MiB|260.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/boundsmodels/dp_12.formula1-s-O2-b10.smo2.smt2      |280.0MiB|280.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/boundsmodels/dp_8.formula1-i-O2-b10.smo2.smt2       |258.0MiB|258.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/mutualExclusion/mutex1.smt2                         |250.0MiB|250.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b1.lp.smt2                   |269.0MiB|269.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b10.lp.smt2                  |267.0MiB|267.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b11.lp.smt2                  |267.0MiB|267.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b12.lp.smt2                  |266.0MiB|266.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b13.lp.smt2                  |271.0MiB|271.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b14.lp.smt2                  |268.0MiB|268.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b15.lp.smt2                  |267.0MiB|267.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b16.lp.smt2                  |267.0MiB|267.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b17.lp.smt2                  |263.0MiB|263.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b18.lp.smt2                  |267.0MiB|267.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b19.lp.smt2                  |268.0MiB|268.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b2.lp.smt2                   |268.0MiB|268.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b20.lp.smt2                  |271.0MiB|271.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b3.lp.smt2                   |266.0MiB|266.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b4.lp.smt2                   |267.0MiB|267.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b5.lp.smt2                   |268.0MiB|268.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_LIA/2019-cmodelsdiff/boundsmodels/dp_10.formula1-s-O2-b9.smo2.smt2       |260.0MiB|260.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/boundsmodels/dp_12.formula1-s-O2-b10.smo2.smt2      |280.0MiB|280.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/boundsmodels/dp_8.formula1-i-O2-b10.smo2.smt2       |258.0MiB|258.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/mutualExclusion/mutex1.smt2                         |250.0MiB|250.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b1.lp.smt2                   |269.0MiB|269.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b10.lp.smt2                  |267.0MiB|267.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b11.lp.smt2                  |267.0MiB|267.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b12.lp.smt2                  |266.0MiB|266.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b13.lp.smt2                  |271.0MiB|271.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b14.lp.smt2                  |268.0MiB|268.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b15.lp.smt2                  |267.0MiB|267.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b16.lp.smt2                  |267.0MiB|267.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b17.lp.smt2                  |263.0MiB|263.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b18.lp.smt2                  |267.0MiB|267.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b19.lp.smt2                  |268.0MiB|268.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b2.lp.smt2                   |268.0MiB|268.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b20.lp.smt2                  |271.0MiB|271.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b3.lp.smt2                   |266.0MiB|266.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b4.lp.smt2                   |267.0MiB|267.0MiB|0B| 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b5.lp.smt2                   |268.0MiB|268.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/QF_LIA/arctic-matrix/constraint-904583.smt2                                | 601.077s |6560.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-983194.smt2                              | 600.762s |6445.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-968440.smt2                                | 600.870s |6359.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-861420.smt2                              | 600.751s |5851.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-873799.smt2                                | 601.017s |5809.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-777746.smt2                                | 601.030s |5793.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-863289.smt2                                | 600.690s |5754.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-851594.smt2                              | 600.786s |5679.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-902192.smt2                                | 600.897s |5669.0MiB|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-10-48.smt2                       | 600.598s |5425.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-804609.smt2                                | 600.723s |5383.0MiB|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-28-50.smt2                         | 600.597s |5285.0MiB|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-40-50.smt2                         | 600.850s |5129.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-928960.smt2                                | 508.173s |5002.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-797738.smt2                              | 600.585s |4981.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-765743.smt2                                | 600.721s |4858.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-735583.smt2                              | 600.648s |4839.0MiB|
|non-incremental/QF_LIA/20220307-SMPT/Referendum-PT-1000/RC-02.smt2                         |   4.558s |4814.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-943653.smt2                                | 153.006s |4790.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-737829.smt2                              | 600.730s |4697.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/QF_LIA/arctic-matrix/constraint-904583.smt2                                | 601.077s |6560.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-983194.smt2                              | 600.762s |6445.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-968440.smt2                                | 600.870s |6359.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-861420.smt2                              | 600.751s |5851.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-873799.smt2                                | 601.017s |5809.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-777746.smt2                                | 601.030s |5793.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-863289.smt2                                | 600.690s |5754.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-851594.smt2                              | 600.786s |5679.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-902192.smt2                                | 600.897s |5669.0MiB|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-10-48.smt2                       | 600.598s |5425.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-804609.smt2                                | 600.723s |5383.0MiB|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-28-50.smt2                         | 600.597s |5285.0MiB|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-40-50.smt2                         | 600.850s |5129.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-928960.smt2                                | 508.173s |5002.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-797738.smt2                              | 600.585s |4981.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-765743.smt2                                | 600.721s |4858.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-735583.smt2                              | 600.648s |4839.0MiB|
|non-incremental/QF_LIA/20220307-SMPT/Referendum-PT-1000/RC-02.smt2                         |   4.558s |4814.0MiB|
|non-incremental/QF_LIA/arctic-matrix/constraint-943653.smt2                                | 153.006s |4790.0MiB|
|non-incremental/QF_LIA/tropical-matrix/constraint-737829.smt2                              | 600.730s |4697.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/QF_LIA/2019-cmodelsdiff/boundsmodels/dp_10.formula1-s-O2-b9.smo2.smt2       |   0.730s  |   0.730s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/boundsmodels/dp_12.formula1-s-O2-b10.smo2.smt2      |   0.943s  |   0.943s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/boundsmodels/dp_8.formula1-i-O2-b10.smo2.smt2       |   0.720s  |   0.720s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/mutualExclusion/mutex1.smt2                         |   0.514s  |   0.514s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b1.lp.smt2                   |   0.750s  |   0.750s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b10.lp.smt2                  |   0.698s  |   0.698s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b11.lp.smt2                  |   0.679s  |   0.679s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b12.lp.smt2                  |   0.696s  |   0.696s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b13.lp.smt2                  |   0.799s  |   0.799s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b14.lp.smt2                  |   0.710s  |   0.710s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b15.lp.smt2                  |   0.725s  |   0.725s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b16.lp.smt2                  |   0.700s  |   0.700s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b17.lp.smt2                  |   0.668s  |   0.668s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b18.lp.smt2                  |   0.694s  |   0.694s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b19.lp.smt2                  |   0.684s  |   0.684s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b2.lp.smt2                   |   0.740s  |   0.740s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b20.lp.smt2                  |   0.799s  |   0.799s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b3.lp.smt2                   |   0.717s  |   0.717s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b4.lp.smt2                   |   0.715s  |   0.715s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b5.lp.smt2                   |   0.733s  |   0.733s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b6.lp.smt2                   |   0.684s  |   0.684s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b7.lp.smt2                   |   0.676s  |   0.676s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b8.lp.smt2                   |   0.731s  |   0.731s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/randomNontight/n40-sat-b9.lp.smt2                   |   0.696s  |   0.696s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-cmodelsdiff/stillLive/0001-still_live-6-1.smt2                  |   1.006s  |   1.006s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/105-incremental_scheduling-17280-0.smt2  |   0.672s  |   0.672s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/115-incremental_scheduling-17280-0.smt2  |   0.858s  |   0.858s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/141-incremental_scheduling-17280-0.smt2  |   0.731s  |   0.731s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/165-incremental_scheduling-18180-0.smt2  |   0.617s  |   0.617s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/214-incremental_scheduling-27000-0.smt2  |  19.033s  |  19.033s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/219-incremental_scheduling-28080-0.smt2  |   0.799s  |   0.799s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/241-incremental_scheduling-28320-0.smt2  |   0.537s  |   0.537s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/251-incremental_scheduling-40518-0.smt2  |   0.550s  |   0.550s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/264-incremental_scheduling-40968-0.smt2  |   0.583s  |   0.583s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/2019-ezsmt/incrementalScheduling/298-incremental_scheduling-40824-0.smt2  |   0.562s  |   0.562s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20210219-Dartagnan/ConcurrencySafety-Main/race-1_2-join-O0.smt2      |   1.095s  |   1.095s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20210219-Dartagnan/ConcurrencySafety-Main/race-1_3-join-O0.smt2      |   1.092s  |   1.092s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20210219-Dartagnan/ReachSafety-Loops/afnp2014-O0.smt2                |   0.864s  |   0.864s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20210219-Dartagnan/ReachSafety-Loops/apache-get-tag.i.v+lhb-reducer-O0.smt2  |   0.770s  |   0.770s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20210219-Dartagnan/ReachSafety-Loops/apache-get-tag.i.v+nlh-reducer-O0.smt2  |   0.725s  |   0.725s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20210219-Dartagnan/ReachSafety-Loops/benchmark02_linear-O0.smt2      |   0.658s  |   0.658s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20210219-Dartagnan/ReachSafety-Loops/benchmark11_linear-O0.smt2      |   0.651s  |   0.651s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20210219-Dartagnan/ReachSafety-Loops/benchmark17_conjunctive-O0.smt2  |   0.724s  |   0.724s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20210219-Dartagnan/ReachSafety-Loops/benchmark25_linear-O0.smt2      |   0.599s  |   0.599s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20210219-Dartagnan/ReachSafety-Loops/count_by_nondet-O0.smt2         |   0.664s  |   0.664s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20210219-Dartagnan/ReachSafety-Loops/eq1-O0.smt2                     |   0.729s  |   0.729s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20210219-Dartagnan/ReachSafety-Loops/fragtest_simple-O0.smt2         |   0.985s  |   0.985s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20210219-Dartagnan/ReachSafety-Loops/gsv2008.c.i.v+lhb-reducer-O0.smt2  |   0.668s  |   0.668s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20210219-Dartagnan/ReachSafety-Loops/id_build.i.v+lhb-reducer-O0.smt2  |   0.698s  |   0.698s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20210219-Dartagnan/ReachSafety-Loops/in-de20-O0.smt2                 |   1.023s  |   1.023s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20210219-Dartagnan/ReachSafety-Loops/in-de51-O0.smt2                 |   0.816s  |   0.816s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20210219-Dartagnan/ReachSafety-Loops/in-de52-O0.smt2                 |   0.893s  |   0.893s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20210219-Dartagnan/ReachSafety-Loops/in-de61-O0.smt2                 |   1.017s  |   1.017s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20210219-Dartagnan/ReachSafety-Loops/in-de62-O0.smt2                 |   1.012s  |   1.012s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20210219-Dartagnan/ReachSafety-Loops/insertion_sort-2-O0.smt2        |   1.362s  |   1.362s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20210219-Dartagnan/ReachSafety-Loops/mono-crafted_1-O0.smt2          |   0.687s  |   0.687s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20210219-Dartagnan/ReachSafety-Loops/mono-crafted_3-O0.smt2          |   0.775s  |   0.775s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20210219-Dartagnan/ReachSafety-Loops/mono-crafted_8-O0.smt2          |   0.848s  |   0.848s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20210219-Dartagnan/ReachSafety-Loops/simple_vardep_2-O0.smt2         |   0.922s  |   0.922s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20210219-Dartagnan/ReachSafety-Loops/sum01_bug02-O0.smt2             |   0.843s  |   0.843s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20210219-Dartagnan/ReachSafety-Loops/sum01_bug02_sum01_bug02_base.case-O0.smt2  |   0.882s  |   0.882s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20210219-Dartagnan/ReachSafety-Loops/sum03-1-O0.smt2                 |   0.913s  |   0.913s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20210219-Dartagnan/ReachSafety-Loops/sum03-2-O0.smt2                 |   0.783s  |   0.783s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/BART-PT-020/RC-00.smt2                                 |   1.625s  |   1.625s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/BART-PT-020/RC-01.smt2                                 |   1.643s  |   1.643s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/BART-PT-020/RC-02.smt2                                 |   1.543s  |   1.543s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/BART-PT-020/RC-03.smt2                                 |   0.611s  |   0.611s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/BART-PT-020/RC-04.smt2                                 |   1.687s  |   1.687s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/BART-PT-020/RC-06.smt2                                 |   1.602s  |   1.602s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/BART-PT-020/RC-07.smt2                                 |   1.637s  |   1.637s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/BART-PT-020/RC-08.smt2                                 |   1.580s  |   1.580s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/BART-PT-020/RC-09.smt2                                 |   1.663s  |   1.663s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/BART-PT-020/RC-11.smt2                                 |   1.780s  |   1.780s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/BART-PT-020/RC-13.smt2                                 |   1.650s  |   1.650s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/BART-PT-020/RC-14.smt2                                 |   1.632s  |   1.632s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/BART-PT-020/RC-15.smt2                                 |   1.603s  |   1.603s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/BART-PT-020/RF-00.smt2                                 |   1.618s  |   1.618s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/BART-PT-020/RF-01.smt2                                 |   1.631s  |   1.631s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/BART-PT-020/RF-02.smt2                                 |   1.570s  |   1.570s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/BART-PT-020/RF-03.smt2                                 |   1.629s  |   1.629s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/BART-PT-020/RF-04.smt2                                 |   1.592s  |   1.592s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/BART-PT-020/RF-05.smt2                                 |   1.608s  |   1.608s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/BART-PT-020/RF-06.smt2                                 |   1.677s  |   1.677s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/BART-PT-020/RF-07.smt2                                 |   1.636s  |   1.636s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/BART-PT-020/RF-08.smt2                                 |   1.646s  |   1.646s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/BART-PT-020/RF-09.smt2                                 |   1.615s  |   1.615s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/BART-PT-020/RF-10.smt2                                 |   1.578s  |   1.578s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/BART-PT-020/RF-11.smt2                                 |   1.647s  |   1.647s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/BART-PT-020/RF-12.smt2                                 |   1.637s  |   1.637s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/BART-PT-020/RF-13.smt2                                 |   1.688s  |   1.688s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/BART-PT-020/RF-14.smt2                                 |   1.631s  |   1.631s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/BART-PT-020/RF-15.smt2                                 |   1.629s  |   1.629s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/BART-PT-030/RC-00.smt2                                 |   2.470s  |   2.470s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/BART-PT-030/RC-02.smt2                                 |   2.807s  |   2.807s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/BART-PT-030/RC-03.smt2                                 |   2.505s  |   2.505s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/BART-PT-030/RC-04.smt2                                 |   2.615s  |   2.615s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/BART-PT-030/RC-06.smt2                                 |   2.648s  |   2.648s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/BART-PT-030/RC-07.smt2                                 |   2.595s  |   2.595s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/BART-PT-030/RC-08.smt2                                 |   2.601s  |   2.601s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/BART-PT-030/RC-09.smt2                                 |   2.614s  |   2.614s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/BART-PT-030/RC-10.smt2                                 |   2.744s  |   2.744s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/BART-PT-030/RC-11.smt2                                 |   2.620s  |   2.620s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/BART-PT-030/RC-12.smt2                                 |   2.663s  |   2.663s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/BART-PT-030/RC-13.smt2                                 |   2.501s  |   2.501s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/BART-PT-030/RC-14.smt2                                 |   2.799s  |   2.799s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/BART-PT-030/RF-00.smt2                                 |   2.694s  |   2.694s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/BART-PT-030/RF-01.smt2                                 |   2.626s  |   2.626s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/BART-PT-030/RF-02.smt2                                 |   2.533s  |   2.533s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/BART-PT-030/RF-03.smt2                                 |   2.694s  |   2.694s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/BART-PT-030/RF-04.smt2                                 |   2.556s  |   2.556s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/BART-PT-030/RF-05.smt2                                 |   2.580s  |   2.580s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/BART-PT-030/RF-06.smt2                                 |   2.597s  |   2.597s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/BART-PT-030/RF-07.smt2                                 |   2.589s  |   2.589s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/BART-PT-030/RF-08.smt2                                 |   2.683s  |   2.683s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/BART-PT-030/RF-09.smt2                                 |   2.629s  |   2.629s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/BART-PT-030/RF-10.smt2                                 |   2.456s  |   2.456s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/BART-PT-030/RF-11.smt2                                 |   2.494s  |   2.494s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/BART-PT-030/RF-12.smt2                                 |   2.751s  |   2.751s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/BART-PT-030/RF-13.smt2                                 |   2.641s  |   2.641s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/BART-PT-030/RF-14.smt2                                 |   2.677s  |   2.677s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/BART-PT-030/RF-15.smt2                                 |   2.671s  |   2.671s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/Referendum-PT-1000/RC-00.smt2                          |   3.046s  |   3.046s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/Referendum-PT-1000/RC-01.smt2                          |   3.687s  |   3.687s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/Referendum-PT-1000/RC-02.smt2                          |   4.558s  |   4.558s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/Referendum-PT-1000/RC-03.smt2                          |   2.814s  |   2.814s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/Referendum-PT-1000/RC-04.smt2                          |   1.341s  |   1.341s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/Referendum-PT-1000/RF-00.smt2                          |   0.627s  |   0.627s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/Referendum-PT-1000/RF-03.smt2                          |   1.487s  |   1.487s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/Referendum-PT-1000/RF-04.smt2                          |   2.539s  |   2.539s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/Referendum-PT-1000/RF-05.smt2                          |   0.621s  |   0.621s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/Referendum-PT-1000/RF-06.smt2                          |   0.621s  |   0.621s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/Referendum-PT-1000/RF-07.smt2                          |   2.605s  |   2.605s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-00.smt2                       |   3.099s  |   3.099s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-01.smt2                       |   4.537s  |   4.537s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-02.smt2                       |   4.420s  |   4.420s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-03.smt2                       |   3.267s  |   3.267s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-04.smt2                       |   4.386s  |   4.386s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-05.smt2                       |   4.390s  |   4.390s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-06.smt2                       |   4.891s  |   4.891s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-07.smt2                       |   4.316s  |   4.316s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-09.smt2                       |   3.853s  |   3.853s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-11.smt2                       |   4.337s  |   4.337s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-12.smt2                       |   4.515s  |   4.515s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-13.smt2                       |   3.507s  |   3.507s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-14.smt2                       |   3.149s  |   3.149s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RC-15.smt2                       |   4.302s  |   4.302s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-00.smt2                       |   5.152s  |   5.152s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-01.smt2                       |   3.727s  |   3.727s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-02.smt2                       |   3.709s  |   3.709s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-03.smt2                       |   4.948s  |   4.948s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-04.smt2                       |   4.259s  |   4.259s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-05.smt2                       |   4.226s  |   4.226s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-06.smt2                       |   4.344s  |   4.344s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-07.smt2                       |   4.692s  |   4.692s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-08.smt2                       |   4.410s  |   4.410s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-09.smt2                       |   3.781s  |   3.781s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-10.smt2                       |   3.679s  |   3.679s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-11.smt2                       |   4.692s  |   4.692s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-12.smt2                       |   4.678s  |   4.678s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-13.smt2                       |   4.321s  |   4.321s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-14.smt2                       |   4.784s  |   4.784s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0010w0500/RF-15.smt2                       |   3.905s  |   3.905s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0500w0010/RC-00.smt2                       |   3.928s  |   3.928s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0500w0010/RC-03.smt2                       |   3.506s  |   3.506s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0500w0010/RC-04.smt2                       |   3.750s  |   3.750s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0500w0010/RC-05.smt2                       |   3.646s  |   3.646s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0500w0010/RC-06.smt2                       |   3.417s  |   3.417s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0500w0010/RC-07.smt2                       |   3.466s  |   3.466s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0500w0010/RC-08.smt2                       |   3.527s  |   3.527s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0500w0010/RC-09.smt2                       |   3.689s  |   3.689s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0500w0010/RC-10.smt2                       |   3.540s  |   3.540s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0500w0010/RC-11.smt2                       |   3.386s  |   3.386s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0500w0010/RC-12.smt2                       |   3.626s  |   3.626s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0500w0010/RC-13.smt2                       |   3.390s  |   3.390s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0500w0010/RC-14.smt2                       |   3.876s  |   3.876s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0500w0010/RC-15.smt2                       |   3.345s  |   3.345s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0500w0010/RF-00.smt2                       |   3.475s  |   3.475s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0500w0010/RF-01.smt2                       |   3.571s  |   3.571s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0500w0010/RF-02.smt2                       |   3.650s  |   3.650s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0500w0010/RF-03.smt2                       |   3.275s  |   3.275s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0500w0010/RF-04.smt2                       |   3.541s  |   3.541s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0500w0010/RF-05.smt2                       |   3.560s  |   3.560s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0500w0010/RF-06.smt2                       |   3.730s  |   3.730s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0500w0010/RF-07.smt2                       |   3.261s  |   3.261s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0500w0010/RF-08.smt2                       |   3.861s  |   3.861s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0500w0010/RF-09.smt2                       |   3.477s  |   3.477s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0500w0010/RF-10.smt2                       |   3.654s  |   3.654s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0500w0010/RF-11.smt2                       |   4.187s  |   4.187s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0500w0010/RF-12.smt2                       |   4.034s  |   4.034s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0500w0010/RF-13.smt2                       |   3.775s  |   3.775s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0500w0010/RF-14.smt2                       |   3.769s  |   3.769s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20220307-SMPT/RwMutex-PT-r0500w0010/RF-15.smt2                       |   3.931s  |   3.931s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/20231117-c_inference/50_50_45_6_sat.smt2                             |   6.938s  |   6.938s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/Averest/parallel_prefix_sum/ParallelPrefixSum_safe_blmc003.smt2      |   0.625s  |   0.625s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/Averest/parallel_prefix_sum/ParallelPrefixSum_safe_blmc004.smt2      |   0.829s  |   0.829s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/RWS/Example_15.txt.smt2                                              | 600.139s  | 600.139s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/RWS/Example_18.txt.smt2                                              | 600.124s  | 600.124s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/RWS/Example_9.txt.smt2                                               | 463.865s  | 463.865s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-1007795.smt2                                |   7.386s  |   7.386s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-1008025.smt2                                |   6.162s  |   6.162s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-487307.smt2                                 | 500.129s  | 500.129s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-506600.smt2                                 | 600.502s  | 600.502s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-518109.smt2                                 |  84.683s  |  84.683s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-533042.smt2                                 | 600.415s  | 600.415s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-551279.smt2                                 | 600.436s  | 600.436s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-569261.smt2                                 | 600.663s  | 600.663s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-605010.smt2                                 |  14.836s  |  14.836s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-618384.smt2                                 |  22.546s  |  22.546s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-644402.smt2                                 | 600.605s  | 600.605s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-644686.smt2                                 |   6.468s  |   6.468s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-649088.smt2                                 |   5.622s  |   5.622s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-654327.smt2                                 | 225.747s  | 225.747s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-655888.smt2                                 | 600.611s  | 600.611s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-687518.smt2                                 | 600.493s  | 600.493s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-689472.smt2                                 |  10.133s  |  10.133s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-706002.smt2                                 |  17.775s  |  17.775s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-764693.smt2                                 |   3.956s  |   3.956s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-765743.smt2                                 | 600.721s  | 600.721s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-772500.smt2                                 |  14.817s  |  14.817s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-777746.smt2                                 | 601.030s  | 601.030s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-804609.smt2                                 | 600.723s  | 600.723s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-808692.smt2                                 |  11.088s  |  11.088s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-863289.smt2                                 | 600.690s  | 600.690s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-864173.smt2                                 |  16.873s  |  16.873s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-873799.smt2                                 | 601.017s  | 601.017s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-882710.smt2                                 |  11.995s  |  11.995s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-901628.smt2                                 |  15.620s  |  15.620s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-902192.smt2                                 | 600.897s  | 600.897s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-904583.smt2                                 | 601.077s  | 601.077s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-906218.smt2                                 |   7.332s  |   7.332s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-916576.smt2                                 |   9.046s  |   9.046s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-928134.smt2                                 |  10.904s  |  10.904s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-928960.smt2                                 | 508.173s  | 508.173s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-943653.smt2                                 | 153.006s  | 153.006s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/arctic-matrix/constraint-968440.smt2                                 | 600.870s  | 600.870s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/mathsat/FISCHER10-10-fair.smt2                                       |   1.697s  |   1.697s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/mathsat/FISCHER10-11-fair.smt2                                       |   2.757s  |   2.757s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/mathsat/FISCHER10-12-fair.smt2                                       |   7.233s  |   7.233s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/mathsat/FISCHER10-13-fair.smt2                                       |  21.752s  |  21.752s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/mathsat/FISCHER10-14-fair.smt2                                       |  57.278s  |  57.278s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/mathsat/FISCHER10-15-fair.smt2                                       |   1.285s  |   1.285s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/mathsat/FISCHER11-10-fair.smt2                                       |   2.179s  |   2.179s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/mathsat/FISCHER11-11-fair.smt2                                       |   3.664s  |   3.664s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/mathsat/FISCHER11-12-fair.smt2                                       |   9.423s  |   9.423s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/mathsat/FISCHER11-13-fair.smt2                                       |  27.890s  |  27.890s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/mathsat/FISCHER11-16-fair.smt2                                       |   2.083s  |   2.083s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/mathsat/FISCHER8-13-fair.smt2                                        |   0.956s  |   0.956s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/mathsat/FISCHER9-12-fair.smt2                                        |   5.690s  |   5.690s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/mathsat/FISCHER9-13-fair.smt2                                        |  20.325s  |  20.325s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/mathsat/FISCHER9-14-fair.smt2                                        |   1.168s  |   1.168s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/miplib2003/harp2.sat.smt2                                            |   1.052s  |   1.052s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/miplib2003/manna81.sat.smt2                                          |   2.017s  |   2.017s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/miplib2003/protfold.sat.smt2                                         | 600.340s  | 600.340s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/miplib2003/seymour.sat.smt2                                          |   1.615s  |   1.615s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-0-47.smt2                              |   1.047s  |   1.047s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-0-50.smt2                              |  11.144s  |  11.144s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-10-46.smt2                             |   6.272s  |   6.272s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-10-47.smt2                             |  12.926s  |  12.926s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-10-48.smt2                             |  16.302s  |  16.302s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-10-49.smt2                             |  21.863s  |  21.863s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-10-50.smt2                             |  33.818s  |  33.818s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-11-47.smt2                             |   0.959s  |   0.959s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-11-48.smt2                             |   1.141s  |   1.141s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-11-50.smt2                             |   1.581s  |   1.581s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-12-46.smt2                             |   0.848s  |   0.848s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-12-47.smt2                             |   1.002s  |   1.002s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-12-48.smt2                             |   1.141s  |   1.141s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-12-50.smt2                             |   1.603s  |   1.603s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-13-46.smt2                             |   0.804s  |   0.804s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-13-47.smt2                             |   1.040s  |   1.040s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-13-48.smt2                             |   1.157s  |   1.157s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-13-49.smt2                             |   1.358s  |   1.358s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-14-46.smt2                             |  10.005s  |  10.005s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-14-47.smt2                             |  13.850s  |  13.850s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-14-48.smt2                             |   9.554s  |   9.554s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-14-49.smt2                             |  22.043s  |  22.043s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-14-50.smt2                             |  26.847s  |  26.847s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-15-46.smt2                             |  10.447s  |  10.447s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-15-47.smt2                             |  14.194s  |  14.194s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-15-49.smt2                             |  18.441s  |  18.441s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-15-50.smt2                             |  23.719s  |  23.719s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-16-46.smt2                             |   0.902s  |   0.902s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-16-47.smt2                             |   0.981s  |   0.981s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-16-48.smt2                             |   1.139s  |   1.139s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-16-49.smt2                             |   1.338s  |   1.338s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-16-50.smt2                             |   1.622s  |   1.622s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-17-46.smt2                             |   0.841s  |   0.841s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-17-47.smt2                             |   1.018s  |   1.018s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-17-49.smt2                             |   1.381s  |   1.381s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-17-50.smt2                             |   1.709s  |   1.709s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-18-47.smt2                             |   0.983s  |   0.983s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-18-48.smt2                             |   1.138s  |   1.138s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-18-50.smt2                             |   1.625s  |   1.625s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-19-47.smt2                             |   7.692s  |   7.692s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-19-48.smt2                             |  16.162s  |  16.162s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-19-49.smt2                             |  22.704s  |  22.704s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-19-50.smt2                             |  29.527s  |  29.527s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-2-48.smt2                              |   1.167s  |   1.167s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-2-49.smt2                              |   1.505s  |   1.505s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-2-50.smt2                              |  11.647s  |  11.647s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-20-46.smt2                             |   9.743s  |   9.743s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-20-48.smt2                             |  16.822s  |  16.822s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-20-49.smt2                             |  18.249s  |  18.249s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-21-46.smt2                             |   0.853s  |   0.853s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-21-48.smt2                             |   1.141s  |   1.141s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-21-50.smt2                             |  36.072s  |  36.072s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-22-47.smt2                             |   0.975s  |   0.975s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-22-48.smt2                             |   1.204s  |   1.204s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-22-49.smt2                             |   1.359s  |   1.359s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-22-50.smt2                             |   1.579s  |   1.579s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-23-46.smt2                             |   9.475s  |   9.475s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-23-47.smt2                             |  14.890s  |  14.890s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-23-48.smt2                             |   9.936s  |   9.936s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-23-49.smt2                             |  23.326s  |  23.326s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-24-47.smt2                             |   0.986s  |   0.986s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-24-49.smt2                             |   1.331s  |   1.331s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-24-50.smt2                             |  29.625s  |  29.625s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-25-46.smt2                             |   0.868s  |   0.868s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-25-48.smt2                             |   1.158s  |   1.158s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-25-50.smt2                             |   1.682s  |   1.682s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-26-46.smt2                             |   0.915s  |   0.915s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-26-47.smt2                             |   1.009s  |   1.009s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-26-48.smt2                             |   1.185s  |   1.185s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-26-50.smt2                             |   1.643s  |   1.643s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-27-46.smt2                             |   6.343s  |   6.343s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-27-47.smt2                             |  13.309s  |  13.309s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-27-48.smt2                             |  17.935s  |  17.935s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-27-49.smt2                             |  19.013s  |  19.013s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-27-50.smt2                             |  27.917s  |  27.917s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-28-46.smt2                             |   9.863s  |   9.863s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-28-48.smt2                             |  18.924s  |  18.924s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-28-49.smt2                             |  22.365s  |  22.365s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-28-50.smt2                             |  31.231s  |  31.231s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-29-46.smt2                             |   0.878s  |   0.878s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-29-47.smt2                             |   0.985s  |   0.985s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-29-48.smt2                             |   1.214s  |   1.214s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-29-50.smt2                             |   1.573s  |   1.573s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-3-46.smt2                              |   0.866s  |   0.866s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-3-47.smt2                              |   0.974s  |   0.974s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-3-48.smt2                              |   1.159s  |   1.159s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-3-49.smt2                              |   1.364s  |   1.364s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-30-46.smt2                             |   0.840s  |   0.840s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-31-46.smt2                             |  10.759s  |  10.759s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-31-47.smt2                             |  16.123s  |  16.123s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-31-48.smt2                             |  17.100s  |  17.100s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-31-50.smt2                             |  31.982s  |  31.982s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-32-46.smt2                             |  11.390s  |  11.390s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-32-47.smt2                             |  16.114s  |  16.114s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-32-49.smt2                             |  23.374s  |  23.374s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-32-50.smt2                             |  23.305s  |  23.305s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-33-46.smt2                             |   0.830s  |   0.830s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-33-47.smt2                             |   0.961s  |   0.961s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-33-48.smt2                             |   1.212s  |   1.212s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-33-49.smt2                             |   1.424s  |   1.424s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-33-50.smt2                             |   1.536s  |   1.536s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-34-46.smt2                             |   6.812s  |   6.812s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-34-47.smt2                             |  12.580s  |  12.580s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-34-49.smt2                             |  24.650s  |  24.650s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-34-50.smt2                             |  30.927s  |  30.927s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-35-49.smt2                             |  25.923s  |  25.923s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-35-50.smt2                             |  21.253s  |  21.253s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-36-47.smt2                             |  13.131s  |  13.131s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-36-48.smt2                             |   9.512s  |   9.512s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-36-49.smt2                             |  22.338s  |  22.338s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-37-50.smt2                             |  28.081s  |  28.081s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-38-47.smt2                             |  13.745s  |  13.745s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-38-50.smt2                             |  31.218s  |  31.218s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-39-49.smt2                             |  23.311s  |  23.311s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-4-46.smt2                              |   0.789s  |   0.789s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-4-47.smt2                              |   6.011s  |   6.011s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-4-48.smt2                              |  16.189s  |  16.189s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-4-50.smt2                              |  22.266s  |  22.266s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-40-45.smt2                             |   8.417s  |   8.417s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-40-46.smt2                             |  11.394s  |  11.394s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-40-47.smt2                             |  14.340s  |  14.340s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-40-49.smt2                             |  20.513s  |  20.513s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-41-44.smt2                             |   6.197s  |   6.197s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-41-50.smt2                             |  26.506s  |  26.506s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-42-46.smt2                             |  10.310s  |  10.310s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-42-47.smt2                             |  15.662s  |  15.662s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-42-48.smt2                             |  17.942s  |  17.942s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-42-49.smt2                             |  21.063s  |  21.063s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-43-44.smt2                             |   5.995s  |   5.995s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-43-49.smt2                             |  25.035s  |  25.035s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-44-46.smt2                             |   0.846s  |   0.846s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-44-47.smt2                             |   1.110s  |   1.110s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-44-48.smt2                             |   1.138s  |   1.138s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-45-44.smt2                             |   6.825s  |   6.825s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-45-47.smt2                             |  11.497s  |  11.497s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-45-48.smt2                             |  18.120s  |  18.120s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-46-46.smt2                             |   9.280s  |   9.280s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-46-48.smt2                             |  17.950s  |  17.950s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-47-46.smt2                             |   0.854s  |   0.854s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-47-48.smt2                             |   1.200s  |   1.200s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-47-49.smt2                             |   1.319s  |   1.319s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-47-50.smt2                             |   1.621s  |   1.621s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-48-47.smt2                             |   0.993s  |   0.993s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-48-48.smt2                             |   1.234s  |   1.234s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-48-49.smt2                             |   1.435s  |   1.435s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-48-50.smt2                             |   1.639s  |   1.639s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-49-46.smt2                             |  10.873s  |  10.873s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-49-49.smt2                             |  22.093s  |  22.093s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-49-50.smt2                             |  24.201s  |  24.201s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-5-47.smt2                              |   1.020s  |   1.020s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-5-48.smt2                              |   1.139s  |   1.139s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-5-49.smt2                              |   1.333s  |   1.333s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-50-46.smt2                             |  10.916s  |  10.916s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-50-48.smt2                             |  19.513s  |  19.513s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-50-49.smt2                             |  25.006s  |  25.006s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-50-50.smt2                             |  29.957s  |  29.957s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-51-48.smt2                             |  16.890s  |  16.890s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-51-49.smt2                             |  18.219s  |  18.219s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-51-50.smt2                             |  27.590s  |  27.590s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-52-45.smt2                             |   7.381s  |   7.381s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-52-49.smt2                             |  25.105s  |  25.105s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-53-45.smt2                             |   7.786s  |   7.786s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-53-47.smt2                             |  15.721s  |  15.721s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-53-49.smt2                             |  18.173s  |  18.173s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-53-50.smt2                             |  23.612s  |  23.612s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-54-45.smt2                             |   8.158s  |   8.158s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-54-47.smt2                             |  15.982s  |  15.982s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-54-48.smt2                             |  17.740s  |  17.740s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-54-49.smt2                             |  19.858s  |  19.858s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-55-45.smt2                             |   0.747s  |   0.747s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-55-46.smt2                             |   0.870s  |   0.870s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-55-47.smt2                             |   1.004s  |   1.004s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-56-46.smt2                             |   0.888s  |   0.888s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-56-47.smt2                             |   0.957s  |   0.957s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-57-46.smt2                             |   0.897s  |   0.897s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-57-47.smt2                             |   1.007s  |   1.007s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-57-48.smt2                             |   1.168s  |   1.168s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-57-49.smt2                             |   1.374s  |   1.374s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-57-50.smt2                             |   1.609s  |   1.609s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-58-46.smt2                             |   0.878s  |   0.878s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-58-47.smt2                             |   0.963s  |   0.963s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-58-48.smt2                             |   1.109s  |   1.109s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-58-50.smt2                             |   1.603s  |   1.603s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-59-46.smt2                             |   0.838s  |   0.838s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-59-47.smt2                             |   0.981s  |   0.981s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-59-48.smt2                             |   1.286s  |   1.286s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-59-49.smt2                             |   1.407s  |   1.407s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-59-50.smt2                             |   1.604s  |   1.604s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-6-46.smt2                              |   0.892s  |   0.892s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-6-47.smt2                              |   0.999s  |   0.999s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-6-49.smt2                              |   1.349s  |   1.349s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-6-50.smt2                              |   1.714s  |   1.714s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-60-49.smt2                             |  23.116s  |  23.116s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-60-50.smt2                             |  30.520s  |  30.520s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-61-46.smt2                             |  11.136s  |  11.136s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-61-49.smt2                             |  22.968s  |  22.968s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-61-50.smt2                             |  24.757s  |  24.757s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-62-48.smt2                             |  17.890s  |  17.890s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-62-49.smt2                             |  20.919s  |  20.919s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-62-50.smt2                             |  27.025s  |  27.025s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-63-46.smt2                             |  12.561s  |  12.561s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-63-49.smt2                             |  24.695s  |  24.695s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-64-46.smt2                             |   9.715s  |   9.715s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-64-47.smt2                             |  13.251s  |  13.251s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-64-48.smt2                             |  22.734s  |  22.734s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-64-50.smt2                             |  26.407s  |  26.407s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-65-46.smt2                             |  11.228s  |  11.228s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-65-47.smt2                             |  12.852s  |  12.852s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-65-48.smt2                             |  19.111s  |  19.111s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-65-49.smt2                             |  16.955s  |  16.955s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-65-50.smt2                             |  27.113s  |  27.113s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-66-46.smt2                             |   0.828s  |   0.828s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-66-47.smt2                             |   0.980s  |   0.980s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-66-48.smt2                             |   1.240s  |   1.240s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-66-49.smt2                             |   1.382s  |   1.382s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-67-46.smt2                             |   0.845s  |   0.845s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-67-47.smt2                             |   0.998s  |   0.998s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-67-48.smt2                             |   1.146s  |   1.146s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-68-47.smt2                             |   0.996s  |   0.996s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-68-48.smt2                             |   1.252s  |   1.252s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-68-50.smt2                             |   1.705s  |   1.705s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-69-46.smt2                             |   0.888s  |   0.888s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-69-47.smt2                             |   0.976s  |   0.976s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-69-48.smt2                             |   1.237s  |   1.237s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-69-49.smt2                             |   1.319s  |   1.319s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-69-50.smt2                             |   1.530s  |   1.530s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-7-46.smt2                              |   0.813s  |   0.813s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-7-47.smt2                              |   1.100s  |   1.100s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-7-48.smt2                              |   1.173s  |   1.173s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-7-49.smt2                              |   1.350s  |   1.350s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-70-48.smt2                             |  17.332s  |  17.332s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-70-50.smt2                             |  30.811s  |  30.811s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-71-48.smt2                             |  18.181s  |  18.181s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-71-49.smt2                             |  22.806s  |  22.806s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-72-48.smt2                             |  12.834s  |  12.834s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-72-50.smt2                             |  31.444s  |  31.444s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-73-48.smt2                             |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-73-50.smt2                             |  25.106s  |  25.106s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-74-48.smt2                             |   1.115s  |   1.115s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-74-49.smt2                             |   1.337s  |   1.337s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-74-50.smt2                             |   1.607s  |   1.607s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-75-49.smt2                             |  24.093s  |  24.093s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-75-50.smt2                             |  33.255s  |  33.255s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-76-50.smt2                             |  27.119s  |  27.119s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-77-50.smt2                             |   1.700s  |   1.700s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-78-49.smt2                             |   1.478s  |   1.478s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-79-50.smt2                             |   1.576s  |   1.576s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-8-47.smt2                              |  10.675s  |  10.675s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-8-48.smt2                              |  15.267s  |  15.267s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-8-49.smt2                              |  14.621s  |  14.621s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-8-50.smt2                              |  24.636s  |  24.636s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-82-50.smt2                             |  33.866s  |  33.866s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-83-50.smt2                             |   1.697s  |   1.697s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-84-50.smt2                             |   1.613s  |   1.613s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-85-50.smt2                             |   1.594s  |   1.594s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-86-50.smt2                             |   1.648s  |   1.648s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-87-50.smt2                             |   1.562s  |   1.562s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-9-47.smt2                              |   0.962s  |   0.962s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-9-48.smt2                              |   1.151s  |   1.151s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/bftpd_login/prp-9-49.smt2                              |   1.348s  |   1.348s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-1-48.smt2                                |   0.330s  |   0.330s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-1-49.smt2                                |   0.384s  |   0.384s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-1-50.smt2                                |   0.407s  |   0.407s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-10-49.smt2                               |   0.387s  |   0.387s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-10-50.smt2                               |   0.425s  |   0.425s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-11-48.smt2                               |   0.330s  |   0.330s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-11-49.smt2                               |   0.368s  |   0.368s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-11-50.smt2                               |   0.414s  |   0.414s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-12-48.smt2                               |   0.346s  |   0.346s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-12-49.smt2                               |   0.346s  |   0.346s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-12-50.smt2                               |   0.407s  |   0.407s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-13-48.smt2                               |   0.343s  |   0.343s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-13-49.smt2                               |   0.365s  |   0.365s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-13-50.smt2                               |   0.416s  |   0.416s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-14-48.smt2                               |   0.338s  |   0.338s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-14-49.smt2                               |   0.371s  |   0.371s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-14-50.smt2                               |   0.414s  |   0.414s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-15-49.smt2                               |   0.379s  |   0.379s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-15-50.smt2                               |   0.409s  |   0.409s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-16-48.smt2                               |   0.338s  |   0.338s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-16-49.smt2                               |   0.375s  |   0.375s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-16-50.smt2                               |   3.543s  |   3.543s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-17-48.smt2                               |   0.337s  |   0.337s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-17-49.smt2                               |   0.363s  |   0.363s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-17-50.smt2                               |   0.428s  |   0.428s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-18-49.smt2                               |   0.393s  |   0.393s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-19-48.smt2                               |   0.344s  |   0.344s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-19-49.smt2                               |   0.379s  |   0.379s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-19-50.smt2                               |   0.426s  |   0.426s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-2-48.smt2                                |   0.342s  |   0.342s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-2-49.smt2                                |   0.384s  |   0.384s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-20-48.smt2                               |   0.341s  |   0.341s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-20-49.smt2                               |   0.365s  |   0.365s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-20-50.smt2                               |   0.426s  |   0.426s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-21-49.smt2                               |   0.363s  |   0.363s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-21-50.smt2                               |   0.410s  |   0.410s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-22-48.smt2                               |   0.336s  |   0.336s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-22-49.smt2                               |   0.345s  |   0.345s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-22-50.smt2                               |   0.403s  |   0.403s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-23-48.smt2                               |   0.340s  |   0.340s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-23-50.smt2                               |   0.419s  |   0.419s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-24-48.smt2                               |   2.035s  |   2.035s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-24-49.smt2                               |   3.478s  |   3.478s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-24-50.smt2                               |   4.796s  |   4.796s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-25-48.smt2                               |   2.903s  |   2.903s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-25-49.smt2                               |   3.558s  |   3.558s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-25-50.smt2                               |   3.412s  |   3.412s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-26-48.smt2                               |   2.318s  |   2.318s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-26-50.smt2                               |   3.059s  |   3.059s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-27-48.smt2                               |   0.336s  |   0.336s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-27-49.smt2                               |   0.380s  |   0.380s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-27-50.smt2                               |   0.418s  |   0.418s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-28-49.smt2                               |   2.601s  |   2.601s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-29-48.smt2                               |   2.119s  |   2.119s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-29-49.smt2                               |   2.307s  |   2.307s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-29-50.smt2                               |   4.446s  |   4.446s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-3-48.smt2                                |   0.351s  |   0.351s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-3-49.smt2                                |   0.374s  |   0.374s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-3-50.smt2                                |   0.428s  |   0.428s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-30-48.smt2                               |   2.163s  |   2.163s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-30-49.smt2                               |   2.601s  |   2.601s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-30-50.smt2                               |   3.159s  |   3.159s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-31-48.smt2                               |   0.330s  |   0.330s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-31-50.smt2                               |   0.408s  |   0.408s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-32-48.smt2                               |   0.339s  |   0.339s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-32-49.smt2                               |   0.367s  |   0.367s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-33-48.smt2                               |   2.085s  |   2.085s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-33-50.smt2                               |   3.529s  |   3.529s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-34-48.smt2                               |   2.236s  |   2.236s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-34-50.smt2                               |   3.407s  |   3.407s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-35-48.smt2                               |   2.303s  |   2.303s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-35-49.smt2                               |   2.679s  |   2.679s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-35-50.smt2                               |   3.570s  |   3.570s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-37-48.smt2                               |   0.323s  |   0.323s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-37-49.smt2                               |   0.352s  |   0.352s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-37-50.smt2                               |   0.409s  |   0.409s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-38-48.smt2                               |   0.338s  |   0.338s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-38-49.smt2                               |   0.361s  |   0.361s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-38-50.smt2                               |   0.406s  |   0.406s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-39-48.smt2                               |   0.343s  |   0.343s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-39-50.smt2                               |   0.395s  |   0.395s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-4-48.smt2                                |   5.474s  |   5.474s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-4-50.smt2                                |  13.606s  |  13.606s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-40-48.smt2                               |   0.338s  |   0.338s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-40-49.smt2                               |   0.364s  |   0.364s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-40-50.smt2                               |   0.417s  |   0.417s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-41-48.smt2                               |   0.335s  |   0.335s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-41-49.smt2                               |   0.394s  |   0.394s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-42-48.smt2                               |   0.342s  |   0.342s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-42-49.smt2                               |   0.363s  |   0.363s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-43-48.smt2                               |   0.340s  |   0.340s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-43-49.smt2                               |   0.376s  |   0.376s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-43-50.smt2                               |   0.417s  |   0.417s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-44-48.smt2                               |   0.337s  |   0.337s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-44-50.smt2                               |   0.413s  |   0.413s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-45-49.smt2                               |   3.056s  |   3.056s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-46-49.smt2                               |   0.375s  |   0.375s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-46-50.smt2                               |   0.428s  |   0.428s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-47-49.smt2                               |   2.899s  |   2.899s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-48-50.smt2                               |   0.403s  |   0.403s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-49-49.smt2                               |   0.386s  |   0.386s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-49-50.smt2                               |   0.396s  |   0.396s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-5-50.smt2                                |   0.423s  |   0.423s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-50-50.smt2                               |   0.399s  |   0.399s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-51-48.smt2                               |   2.213s  |   2.213s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-51-50.smt2                               |   3.518s  |   3.518s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-52-50.smt2                               |   0.412s  |   0.412s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-53-50.smt2                               |   0.390s  |   0.390s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-54-50.smt2                               |   0.417s  |   0.417s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-55-50.smt2                               |   0.410s  |   0.410s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-57-49.smt2                               |   3.187s  |   3.187s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-58-49.smt2                               |   3.174s  |   3.174s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-58-50.smt2                               |   3.367s  |   3.367s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-6-48.smt2                                |   0.332s  |   0.332s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-6-50.smt2                                |   0.414s  |   0.414s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-7-49.smt2                                |   0.339s  |   0.339s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-8-49.smt2                                |   3.168s  |   3.168s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-8-50.smt2                                |   4.111s  |   4.111s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/checkpass/prp-9-49.smt2                                |   0.363s  |   0.363s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-0-47.smt2                           |  36.994s  |  36.994s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-0-48.smt2                           |  39.042s  |  39.042s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-0-49.smt2                           |  49.319s  |  49.319s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-0-50.smt2                           |  56.296s  |  56.296s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-1-47.smt2                           |  58.594s  |  58.594s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-1-48.smt2                           |  43.409s  |  43.409s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-1-49.smt2                           |  50.436s  |  50.436s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-1-50.smt2                           |  60.948s  |  60.948s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-10-47.smt2                          | 298.193s  | 298.193s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-10-48.smt2                          |  74.755s  |  74.755s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-10-49.smt2                          | 196.013s  | 196.013s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-10-50.smt2                          | 576.401s  | 576.401s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-11-47.smt2                          | 433.510s  | 433.510s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-11-49.smt2                          | 368.997s  | 368.997s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-11-50.smt2                          | 413.196s  | 413.196s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-12-47.smt2                          |  35.437s  |  35.437s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-12-48.smt2                          |  43.044s  |  43.044s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-12-49.smt2                          |  51.802s  |  51.802s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-12-50.smt2                          |  66.269s  |  66.269s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-13-47.smt2                          | 158.709s  | 158.709s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-13-48.smt2                          |  67.984s  |  67.984s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-13-50.smt2                          | 249.915s  | 249.915s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-14-47.smt2                          |  36.225s  |  36.225s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-14-48.smt2                          |  43.325s  |  43.325s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-14-49.smt2                          |  42.256s  |  42.256s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-14-50.smt2                          |  60.968s  |  60.968s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-15-47.smt2                          |  32.591s  |  32.591s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-15-48.smt2                          |  45.294s  |  45.294s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-15-49.smt2                          |  52.450s  |  52.450s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-15-50.smt2                          |  55.882s  |  55.882s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-16-47.smt2                          | 249.563s  | 249.563s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-16-48.smt2                          |  65.577s  |  65.577s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-16-50.smt2                          | 440.167s  | 440.167s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-17-47.smt2                          | 205.112s  | 205.112s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-17-48.smt2                          |  62.365s  |  62.365s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-17-49.smt2                          | 600.308s  | 600.308s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-18-47.smt2                          |  53.518s  |  53.518s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-18-48.smt2                          |  46.549s  |  46.549s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-18-49.smt2                          |  70.163s  |  70.163s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-18-50.smt2                          |  61.062s  |  61.062s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-19-48.smt2                          |  66.498s  |  66.498s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-19-49.smt2                          | 387.109s  | 387.109s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-2-47.smt2                           | 204.319s  | 204.319s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-2-48.smt2                           | 110.147s  | 110.147s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-2-50.smt2                           | 600.420s  | 600.420s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-20-47.smt2                          |  36.392s  |  36.392s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-20-48.smt2                          |  45.019s  |  45.019s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-20-49.smt2                          |  53.395s  |  53.395s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-20-50.smt2                          |  54.109s  |  54.109s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-21-47.smt2                          |  44.906s  |  44.906s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-21-48.smt2                          |  46.956s  |  46.956s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-21-49.smt2                          |  58.693s  |  58.693s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-21-50.smt2                          |  84.762s  |  84.762s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-22-49.smt2                          | 506.252s  | 506.252s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-22-50.smt2                          | 600.491s  | 600.491s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-23-47.smt2                          | 235.652s  | 235.652s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-23-49.smt2                          | 468.112s  | 468.112s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-23-50.smt2                          | 600.379s  | 600.379s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-24-47.smt2                          |  36.583s  |  36.583s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-24-48.smt2                          |  55.915s  |  55.915s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-24-49.smt2                          |  58.657s  |  58.657s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-24-50.smt2                          |  79.848s  |  79.848s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-25-47.smt2                          | 239.191s  | 239.191s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-25-49.smt2                          | 566.682s  | 566.682s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-25-50.smt2                          | 343.836s  | 343.836s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-26-47.smt2                          |  53.472s  |  53.472s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-26-48.smt2                          |  57.472s  |  57.472s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-26-49.smt2                          |  74.341s  |  74.341s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-26-50.smt2                          |  64.392s  |  64.392s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-27-47.smt2                          |  68.773s  |  68.773s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-27-48.smt2                          |  87.109s  |  87.109s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-27-49.smt2                          |  58.543s  |  58.543s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-27-50.smt2                          |  91.645s  |  91.645s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-28-47.smt2                          | 501.582s  | 501.582s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-28-48.smt2                          | 600.243s  | 600.243s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-28-49.smt2                          | 600.193s  | 600.193s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-28-50.smt2                          | 600.597s  | 600.597s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-29-47.smt2                          |  66.724s  |  66.724s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-29-48.smt2                          | 333.541s  | 333.541s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-29-49.smt2                          | 600.302s  | 600.302s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-29-50.smt2                          | 600.440s  | 600.440s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-3-48.smt2                           |  77.597s  |  77.597s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-3-49.smt2                           | 497.879s  | 497.879s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-3-50.smt2                           | 421.628s  | 421.628s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-30-47.smt2                          | 490.729s  | 490.729s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-30-49.smt2                          | 600.331s  | 600.331s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-31-47.smt2                          |  61.377s  |  61.377s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-31-48.smt2                          |  65.270s  |  65.270s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-31-49.smt2                          |  88.000s  |  88.000s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-31-50.smt2                          | 102.618s  | 102.618s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-32-47.smt2                          | 157.993s  | 157.993s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-32-48.smt2                          |  50.891s  |  50.891s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-32-49.smt2                          | 277.706s  | 277.706s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-32-50.smt2                          | 273.276s  | 273.276s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-33-47.smt2                          | 199.970s  | 199.970s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-33-49.smt2                          | 507.582s  | 507.582s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-33-50.smt2                          | 600.275s  | 600.275s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-34-47.smt2                          | 322.036s  | 322.036s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-34-48.smt2                          | 274.601s  | 274.601s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-34-49.smt2                          | 110.655s  | 110.655s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-34-50.smt2                          | 600.270s  | 600.270s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-35-47.smt2                          |  83.782s  |  83.782s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-35-48.smt2                          |  80.430s  |  80.430s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-35-49.smt2                          | 113.677s  | 113.677s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-35-50.smt2                          |  91.071s  |  91.071s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-36-47.smt2                          |  79.330s  |  79.330s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-36-48.smt2                          | 119.312s  | 119.312s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-36-49.smt2                          | 139.957s  | 139.957s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-36-50.smt2                          | 187.871s  | 187.871s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-37-47.smt2                          |  17.250s  |  17.250s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-37-48.smt2                          | 391.587s  | 391.587s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-37-49.smt2                          | 600.412s  | 600.412s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-37-50.smt2                          | 600.211s  | 600.211s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-38-47.smt2                          | 179.980s  | 179.980s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-38-48.smt2                          |  50.471s  |  50.471s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-38-49.smt2                          | 352.833s  | 352.833s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-38-50.smt2                          | 452.437s  | 452.437s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-39-47.smt2                          |  64.579s  |  64.579s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-39-50.smt2                          | 141.003s  | 141.003s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-4-47.smt2                           |  33.758s  |  33.758s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-4-48.smt2                           |  40.360s  |  40.360s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-4-49.smt2                           |  51.878s  |  51.878s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-4-50.smt2                           |  70.653s  |  70.653s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-40-48.smt2                          | 381.832s  | 381.832s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-40-49.smt2                          | 516.660s  | 516.660s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-40-50.smt2                          | 600.850s  | 600.850s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-41-47.smt2                          | 275.699s  | 275.699s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-41-48.smt2                          | 506.714s  | 506.714s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-41-50.smt2                          | 600.400s  | 600.400s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-42-47.smt2                          |  14.002s  |  14.002s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-42-48.smt2                          |  17.127s  |  17.127s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-42-49.smt2                          | 479.747s  | 479.747s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-42-50.smt2                          | 600.548s  | 600.548s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-43-47.smt2                          | 189.650s  | 189.650s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-43-48.smt2                          |  71.220s  |  71.220s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-43-49.smt2                          | 384.237s  | 384.237s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-43-50.smt2                          | 246.587s  | 246.587s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-44-47.smt2                          | 230.446s  | 230.446s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-44-48.smt2                          | 165.214s  | 165.214s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-44-49.smt2                          | 210.225s  | 210.225s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-44-50.smt2                          | 505.816s  | 505.816s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-45-50.smt2                          | 214.216s  | 214.216s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-46-47.smt2                          | 152.823s  | 152.823s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-46-49.smt2                          | 261.584s  | 261.584s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-47-47.smt2                          | 138.375s  | 138.375s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-47-48.smt2                          |  85.149s  |  85.149s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-47-49.smt2                          | 313.152s  | 313.152s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-47-50.smt2                          | 408.963s  | 408.963s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-48-48.smt2                          | 238.111s  | 238.111s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-48-49.smt2                          | 258.612s  | 258.612s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-48-50.smt2                          | 319.929s  | 319.929s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-49-47.smt2                          |  94.795s  |  94.795s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-49-48.smt2                          |  53.510s  |  53.510s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-49-49.smt2                          | 234.311s  | 234.311s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-49-50.smt2                          | 262.125s  | 262.125s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-5-47.smt2                           |  35.368s  |  35.368s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-5-48.smt2                           |  45.308s  |  45.308s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-5-49.smt2                           |  50.364s  |  50.364s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-5-50.smt2                           |  57.070s  |  57.070s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-50-47.smt2                          | 162.300s  | 162.300s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-50-48.smt2                          | 142.910s  | 142.910s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-50-50.smt2                          | 259.307s  | 259.307s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-51-47.smt2                          | 110.546s  | 110.546s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-51-50.smt2                          | 285.802s  | 285.802s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-6-47.smt2                           |  34.213s  |  34.213s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-6-48.smt2                           |  37.052s  |  37.052s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-6-49.smt2                           |  42.732s  |  42.732s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-6-50.smt2                           |  51.829s  |  51.829s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-7-47.smt2                           |  38.920s  |  38.920s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-7-48.smt2                           |  45.453s  |  45.453s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-7-49.smt2                           |  46.406s  |  46.406s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-7-50.smt2                           |  56.859s  |  56.859s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-8-47.smt2                           | 191.866s  | 191.866s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-8-48.smt2                           |  96.465s  |  96.465s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-8-50.smt2                           | 600.274s  | 600.274s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/getoption_user/prp-9-47.smt2                           | 169.404s  | 169.404s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-0-48.smt2                         | 170.215s  | 170.215s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-0-49.smt2                         |  37.041s  |  37.041s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-0-50.smt2                         | 162.310s  | 162.310s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-1-48.smt2                         |  87.625s  |  87.625s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-1-49.smt2                         |  86.846s  |  86.846s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-1-50.smt2                         | 129.163s  | 129.163s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-10-48.smt2                        | 600.598s  | 600.598s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-10-49.smt2                        | 600.353s  | 600.353s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-10-50.smt2                        | 600.174s  | 600.174s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-11-48.smt2                        | 197.345s  | 197.345s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-11-49.smt2                        |  69.326s  |  69.326s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-11-50.smt2                        |  90.625s  |  90.625s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-12-48.smt2                        | 191.290s  | 191.290s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-12-49.smt2                        | 354.154s  | 354.154s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-12-50.smt2                        | 215.928s  | 215.928s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-13-48.smt2                        | 235.182s  | 235.182s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-13-49.smt2                        | 230.025s  | 230.025s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-13-50.smt2                        | 308.331s  | 308.331s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-14-48.smt2                        |  94.390s  |  94.390s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-14-49.smt2                        | 238.444s  | 238.444s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-14-50.smt2                        | 350.337s  | 350.337s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-15-48.smt2                        | 343.352s  | 343.352s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-15-49.smt2                        |  74.801s  |  74.801s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-15-50.smt2                        | 165.333s  | 165.333s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-16-48.smt2                        |  52.339s  |  52.339s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-16-49.smt2                        | 230.652s  | 230.652s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-16-50.smt2                        |  99.744s  |  99.744s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-17-48.smt2                        | 130.080s  | 130.080s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-17-49.smt2                        |  42.245s  |  42.245s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-17-50.smt2                        | 173.096s  | 173.096s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-18-48.smt2                        | 160.824s  | 160.824s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-18-49.smt2                        | 144.351s  | 144.351s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-18-50.smt2                        |  73.100s  |  73.100s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-19-48.smt2                        |  90.292s  |  90.292s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-19-49.smt2                        | 155.951s  | 155.951s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-19-50.smt2                        | 380.727s  | 380.727s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-2-48.smt2                         |  58.655s  |  58.655s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-2-49.smt2                         | 384.955s  | 384.955s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-2-50.smt2                         | 412.387s  | 412.387s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-20-48.smt2                        |  87.631s  |  87.631s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-20-49.smt2                        | 263.502s  | 263.502s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-20-50.smt2                        | 172.081s  | 172.081s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-21-48.smt2                        | 113.574s  | 113.574s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-21-49.smt2                        |  67.767s  |  67.767s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-21-50.smt2                        | 275.142s  | 275.142s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-22-48.smt2                        |  68.657s  |  68.657s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-22-49.smt2                        | 123.186s  | 123.186s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-22-50.smt2                        | 108.980s  | 108.980s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-23-48.smt2                        | 176.646s  | 176.646s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-23-49.smt2                        |  89.701s  |  89.701s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-23-50.smt2                        | 204.275s  | 204.275s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-24-48.smt2                        |  72.135s  |  72.135s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-24-49.smt2                        | 155.228s  | 155.228s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-24-50.smt2                        | 178.553s  | 178.553s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-3-48.smt2                         | 232.053s  | 232.053s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-3-49.smt2                         | 324.079s  | 324.079s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-3-50.smt2                         | 293.469s  | 293.469s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-4-48.smt2                         | 291.644s  | 291.644s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-4-49.smt2                         | 511.143s  | 511.143s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-4-50.smt2                         | 138.136s  | 138.136s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-5-48.smt2                         | 358.091s  | 358.091s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-5-49.smt2                         | 341.616s  | 341.616s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-5-50.smt2                         | 188.860s  | 188.860s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-6-48.smt2                         | 156.034s  | 156.034s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-6-49.smt2                         | 245.478s  | 245.478s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-6-50.smt2                         | 600.336s  | 600.336s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-7-48.smt2                         | 233.328s  | 233.328s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-7-49.smt2                         | 358.946s  | 358.946s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-7-50.smt2                         |  50.816s  |  50.816s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-8-48.smt2                         | 210.862s  | 210.862s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-8-49.smt2                         | 121.930s  | 121.930s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-8-50.smt2                         | 300.302s  | 300.302s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-9-48.smt2                         | 130.938s  | 130.938s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-9-49.smt2                         |  52.794s  |  52.794s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/nec-smt/large/user_is_in_group/prp-9-50.smt2                         | 172.699s  | 172.699s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/pb2010/normalized-j3048_8-sat.smt2                                   |   2.776s  |   2.776s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/pb2010/normalized-j308_6-sat.smt2                                    |   2.628s  |   2.628s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-1015084.smt2                              |   6.851s  |   6.851s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-505409.smt2                               |   6.509s  |   6.509s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-517804.smt2                               |   3.001s  |   3.001s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-556171.smt2                               | 600.353s  | 600.353s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-570196.smt2                               |   5.957s  |   5.957s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-579281.smt2                               | 600.370s  | 600.370s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-603294.smt2                               | 600.342s  | 600.342s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-614657.smt2                               | 246.670s  | 246.670s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-642278.smt2                               |   7.019s  |   7.019s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-645054.smt2                               |   7.971s  |   7.971s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-645855.smt2                               | 428.012s  | 428.012s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-649834.smt2                               |   6.053s  |   6.053s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-651478.smt2                               |  17.196s  |  17.196s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-658040.smt2                               | 293.797s  | 293.797s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-679470.smt2                               |   9.099s  |   9.099s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-687179.smt2                               |  83.593s  |  83.593s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-696340.smt2                               | 600.524s  | 600.524s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-703279.smt2                               |   4.459s  |   4.459s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-704423.smt2                               |   3.350s  |   3.350s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-705295.smt2                               |  13.007s  |  13.007s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-715402.smt2                               | 600.577s  | 600.577s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-729964.smt2                               | 126.209s  | 126.209s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-735583.smt2                               | 600.648s  | 600.648s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-737829.smt2                               | 600.730s  | 600.730s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-740637.smt2                               | 600.620s  | 600.620s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-758897.smt2                               |  14.975s  |  14.975s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-762853.smt2                               |  69.303s  |  69.303s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-794687.smt2                               |  12.144s  |  12.144s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-797738.smt2                               | 600.585s  | 600.585s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-851594.smt2                               | 600.786s  | 600.786s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-861420.smt2                               | 600.751s  | 600.751s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-901996.smt2                               |  13.896s  |  13.896s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-906586.smt2                               |  37.536s  |  37.536s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-916807.smt2                               |  11.383s  |  11.383s  |   0.000s  | 0.0%|
|non-incremental/QF_LIA/tropical-matrix/constraint-917322.smt2                               |  16.581s  |  16.581s  |   0.000s  | 0.0%|
</details>
