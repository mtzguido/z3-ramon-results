Comparing data and data


# SUMMARY
- LHS tests = 297
- RHS tests = 297
- LHS success = 293  (98.65319865319866%)
- RHS success = 293  (98.65319865319866%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-60-clausal-lookahead-parallel-qfufnia-unknown
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: f5749502379a3fdecdbae07053f6f188c56c3c3f
Z3 branch: master
Z3 options: "-T:60 -v:2 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify smt)" smt.sls.enable=true smt.sls.parallel=true  model_validate=true sls.arith_use_clausal_lookahead=true"
Z3 inputs: inputs/QF_UFNIA_UNKNOWN
Z3 commit message: fix #7521 (#7531)

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-60-clausal-lookahead-parallel-qfufnia-unknown
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: f5749502379a3fdecdbae07053f6f188c56c3c3f
Z3 branch: master
Z3 options: "-T:60 -v:2 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify smt)" smt.sls.enable=true smt.sls.parallel=true  model_validate=true sls.arith_use_clausal_lookahead=true"
Z3 inputs: inputs/QF_UFNIA_UNKNOWN
Z3 commit message: fix #7521 (#7531)

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|0054.smt2                                                                                   |  71.024s  |  71.024s  |   0.000s  | 0.0%|
|0055.smt2                                                                                   |  57.493s  |  57.493s  |   0.000s  | 0.0%|
|0056.smt2                                                                                   |  92.299s  |  92.299s  |   0.000s  | 0.0%|
|0057.smt2                                                                                   |  41.562s  |  41.562s  |   0.000s  | 0.0%|
|0058.smt2                                                                                   |  83.542s  |  83.542s  |   0.000s  | 0.0%|
|0059.smt2                                                                                   |  78.651s  |  78.651s  |   0.000s  | 0.0%|
|0060.smt2                                                                                   |  61.343s  |  61.343s  |   0.000s  | 0.0%|
|0061.smt2                                                                                   |  74.588s  |  74.588s  |   0.000s  | 0.0%|
|0062.smt2                                                                                   |  59.997s  |  59.997s  |   0.000s  | 0.0%|
|0063.smt2                                                                                   |  80.130s  |  80.130s  |   0.000s  | 0.0%|
|0064.smt2                                                                                   |  88.408s  |  88.408s  |   0.000s  | 0.0%|
|0065.smt2                                                                                   |  70.767s  |  70.767s  |   0.000s  | 0.0%|
|0066.smt2                                                                                   |  68.565s  |  68.565s  |   0.000s  | 0.0%|
|0067.smt2                                                                                   |  72.689s  |  72.689s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |   8.843s  |   8.843s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |   0.757s  |   0.757s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |   3.547s  |   3.547s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |  26.204s  |  26.204s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |   7.751s  |   7.751s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                     |  96.758s  |  96.758s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|0054.smt2                                                                                   |  71.024s  |  71.024s  |   0.000s  | 0.0%|
|0055.smt2                                                                                   |  57.493s  |  57.493s  |   0.000s  | 0.0%|
|0056.smt2                                                                                   |  92.299s  |  92.299s  |   0.000s  | 0.0%|
|0057.smt2                                                                                   |  41.562s  |  41.562s  |   0.000s  | 0.0%|
|0058.smt2                                                                                   |  83.542s  |  83.542s  |   0.000s  | 0.0%|
|0059.smt2                                                                                   |  78.651s  |  78.651s  |   0.000s  | 0.0%|
|0060.smt2                                                                                   |  61.343s  |  61.343s  |   0.000s  | 0.0%|
|0061.smt2                                                                                   |  74.588s  |  74.588s  |   0.000s  | 0.0%|
|0062.smt2                                                                                   |  59.997s  |  59.997s  |   0.000s  | 0.0%|
|0063.smt2                                                                                   |  80.130s  |  80.130s  |   0.000s  | 0.0%|
|0064.smt2                                                                                   |  88.408s  |  88.408s  |   0.000s  | 0.0%|
|0065.smt2                                                                                   |  70.767s  |  70.767s  |   0.000s  | 0.0%|
|0066.smt2                                                                                   |  68.565s  |  68.565s  |   0.000s  | 0.0%|
|0067.smt2                                                                                   |  72.689s  |  72.689s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |   8.843s  |   8.843s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |   0.757s  |   0.757s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |   3.547s  |   3.547s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |  26.204s  |  26.204s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |   7.751s  |   7.751s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                     |  96.758s  |  96.758s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|0054.smt2                                                                                   |  71.024s  |  71.024s  |   0.000s  | 0.0%|
|0055.smt2                                                                                   |  57.493s  |  57.493s  |   0.000s  | 0.0%|
|0056.smt2                                                                                   |  92.299s  |  92.299s  |   0.000s  | 0.0%|
|0057.smt2                                                                                   |  41.562s  |  41.562s  |   0.000s  | 0.0%|
|0058.smt2                                                                                   |  83.542s  |  83.542s  |   0.000s  | 0.0%|
|0059.smt2                                                                                   |  78.651s  |  78.651s  |   0.000s  | 0.0%|
|0060.smt2                                                                                   |  61.343s  |  61.343s  |   0.000s  | 0.0%|
|0061.smt2                                                                                   |  74.588s  |  74.588s  |   0.000s  | 0.0%|
|0062.smt2                                                                                   |  59.997s  |  59.997s  |   0.000s  | 0.0%|
|0063.smt2                                                                                   |  80.130s  |  80.130s  |   0.000s  | 0.0%|
|0064.smt2                                                                                   |  88.408s  |  88.408s  |   0.000s  | 0.0%|
|0065.smt2                                                                                   |  70.767s  |  70.767s  |   0.000s  | 0.0%|
|0066.smt2                                                                                   |  68.565s  |  68.565s  |   0.000s  | 0.0%|
|0067.smt2                                                                                   |  72.689s  |  72.689s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |   8.843s  |   8.843s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |   0.757s  |   0.757s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |   3.547s  |   3.547s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |  26.204s  |  26.204s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |   7.751s  |   7.751s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                     |  96.758s  |  96.758s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|0054.smt2                                                                                   |  71.024s  |  71.024s  |   0.000s  | 0.0%|
|0055.smt2                                                                                   |  57.493s  |  57.493s  |   0.000s  | 0.0%|
|0056.smt2                                                                                   |  92.299s  |  92.299s  |   0.000s  | 0.0%|
|0057.smt2                                                                                   |  41.562s  |  41.562s  |   0.000s  | 0.0%|
|0058.smt2                                                                                   |  83.542s  |  83.542s  |   0.000s  | 0.0%|
|0059.smt2                                                                                   |  78.651s  |  78.651s  |   0.000s  | 0.0%|
|0060.smt2                                                                                   |  61.343s  |  61.343s  |   0.000s  | 0.0%|
|0061.smt2                                                                                   |  74.588s  |  74.588s  |   0.000s  | 0.0%|
|0062.smt2                                                                                   |  59.997s  |  59.997s  |   0.000s  | 0.0%|
|0063.smt2                                                                                   |  80.130s  |  80.130s  |   0.000s  | 0.0%|
|0064.smt2                                                                                   |  88.408s  |  88.408s  |   0.000s  | 0.0%|
|0065.smt2                                                                                   |  70.767s  |  70.767s  |   0.000s  | 0.0%|
|0066.smt2                                                                                   |  68.565s  |  68.565s  |   0.000s  | 0.0%|
|0067.smt2                                                                                   |  72.689s  |  72.689s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |   8.843s  |   8.843s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |   0.757s  |   0.757s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |   3.547s  |   3.547s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |  26.204s  |  26.204s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |   7.751s  |   7.751s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                     |  96.758s  |  96.758s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|n113-0017.smt2                                                                             | 113.827s |250.0MiB|
|n4-0004.smt2                                                                               | 109.151s |200.0MiB|
|n64-0018.smt2                                                                              | 108.369s |213.0MiB|
|n68-0022.smt2                                                                              | 107.573s |307.0MiB|
|44788_1965f0d6d94d5d8054ba_34_QF_UFNIA.smt2                                                | 103.287s |100.0MiB|
|n48-0001.smt2                                                                              | 103.088s |118.0MiB|
|39657_1c7158801cd59dc13f05_44_QF_UFNIA.smt2                                                | 102.610s |165.0MiB|
|n63-0017.smt2                                                                              | 102.418s |228.0MiB|
|n105-0008.smt2                                                                             | 100.804s |161.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFNIA.smt2                                    | 100.784s |131.0MiB|
|93493_4ea6163ed03941199c785278ccc42812_49_QF_UFNIA.smt2                                    | 100.195s |515.0MiB|
|38347_525a1ca0331f2bcbf520_54_QF_UFNIA.smt2                                                |  99.767s |360.0MiB|
|n95-0050.smt2                                                                              |  99.677s |818.0MiB|
|n103-0006.smt2                                                                             |  98.324s |72.668MiB|
|44289_4066055e0f64d96da11a_15_QF_UFNIA.smt2                                                |  97.886s |655.0MiB|
|n62-0016.smt2                                                                              |  97.632s |292.0MiB|
|n8-0008.smt2                                                                               |  97.053s |231.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                    |  96.758s |164.0MiB|
|83314_a702bf8b823398c9e37a_2_UFNIA.smt2                                                    |  96.554s |245.0MiB|
|n23-0030.smt2                                                                              |  96.550s |399.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|n113-0017.smt2                                                                             | 113.827s |250.0MiB|
|n4-0004.smt2                                                                               | 109.151s |200.0MiB|
|n64-0018.smt2                                                                              | 108.369s |213.0MiB|
|n68-0022.smt2                                                                              | 107.573s |307.0MiB|
|44788_1965f0d6d94d5d8054ba_34_QF_UFNIA.smt2                                                | 103.287s |100.0MiB|
|n48-0001.smt2                                                                              | 103.088s |118.0MiB|
|39657_1c7158801cd59dc13f05_44_QF_UFNIA.smt2                                                | 102.610s |165.0MiB|
|n63-0017.smt2                                                                              | 102.418s |228.0MiB|
|n105-0008.smt2                                                                             | 100.804s |161.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFNIA.smt2                                    | 100.784s |131.0MiB|
|93493_4ea6163ed03941199c785278ccc42812_49_QF_UFNIA.smt2                                    | 100.195s |515.0MiB|
|38347_525a1ca0331f2bcbf520_54_QF_UFNIA.smt2                                                |  99.767s |360.0MiB|
|n95-0050.smt2                                                                              |  99.677s |818.0MiB|
|n103-0006.smt2                                                                             |  98.324s |72.668MiB|
|44289_4066055e0f64d96da11a_15_QF_UFNIA.smt2                                                |  97.886s |655.0MiB|
|n62-0016.smt2                                                                              |  97.632s |292.0MiB|
|n8-0008.smt2                                                                               |  97.053s |231.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                    |  96.758s |164.0MiB|
|83314_a702bf8b823398c9e37a_2_UFNIA.smt2                                                    |  96.554s |245.0MiB|
|n23-0030.smt2                                                                              |  96.550s |399.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|0054.smt2                                                                                   |3249.0MiB|3249.0MiB|0B| 0.0%|
|0055.smt2                                                                                   |1405.0MiB|1405.0MiB|0B| 0.0%|
|0056.smt2                                                                                   |249.0MiB|249.0MiB|0B| 0.0%|
|0057.smt2                                                                                   |189.0MiB|189.0MiB|0B| 0.0%|
|0058.smt2                                                                                   |896.0MiB|896.0MiB|0B| 0.0%|
|0059.smt2                                                                                   |814.0MiB|814.0MiB|0B| 0.0%|
|0060.smt2                                                                                   |194.0MiB|194.0MiB|0B| 0.0%|
|0061.smt2                                                                                   |235.0MiB|235.0MiB|0B| 0.0%|
|0062.smt2                                                                                   |2704.0MiB|2704.0MiB|0B| 0.0%|
|0063.smt2                                                                                   |2002.0MiB|2002.0MiB|0B| 0.0%|
|0064.smt2                                                                                   |626.0MiB|626.0MiB|0B| 0.0%|
|0065.smt2                                                                                   |270.0MiB|270.0MiB|0B| 0.0%|
|0066.smt2                                                                                   |2921.0MiB|2921.0MiB|0B| 0.0%|
|0067.smt2                                                                                   |424.0MiB|424.0MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |78.5MiB|78.5MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |66.888MiB|66.888MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |57.924MiB|57.924MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |80.456MiB|80.456MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |74.436MiB|74.436MiB|0B| 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                     |164.0MiB|164.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|0054.smt2                                                                                   |3249.0MiB|3249.0MiB|0B| 0.0%|
|0055.smt2                                                                                   |1405.0MiB|1405.0MiB|0B| 0.0%|
|0056.smt2                                                                                   |249.0MiB|249.0MiB|0B| 0.0%|
|0057.smt2                                                                                   |189.0MiB|189.0MiB|0B| 0.0%|
|0058.smt2                                                                                   |896.0MiB|896.0MiB|0B| 0.0%|
|0059.smt2                                                                                   |814.0MiB|814.0MiB|0B| 0.0%|
|0060.smt2                                                                                   |194.0MiB|194.0MiB|0B| 0.0%|
|0061.smt2                                                                                   |235.0MiB|235.0MiB|0B| 0.0%|
|0062.smt2                                                                                   |2704.0MiB|2704.0MiB|0B| 0.0%|
|0063.smt2                                                                                   |2002.0MiB|2002.0MiB|0B| 0.0%|
|0064.smt2                                                                                   |626.0MiB|626.0MiB|0B| 0.0%|
|0065.smt2                                                                                   |270.0MiB|270.0MiB|0B| 0.0%|
|0066.smt2                                                                                   |2921.0MiB|2921.0MiB|0B| 0.0%|
|0067.smt2                                                                                   |424.0MiB|424.0MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |78.5MiB|78.5MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |66.888MiB|66.888MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |57.924MiB|57.924MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |80.456MiB|80.456MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |74.436MiB|74.436MiB|0B| 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                     |164.0MiB|164.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|0054.smt2                                                                                   |3249.0MiB|3249.0MiB|0B| 0.0%|
|0055.smt2                                                                                   |1405.0MiB|1405.0MiB|0B| 0.0%|
|0056.smt2                                                                                   |249.0MiB|249.0MiB|0B| 0.0%|
|0057.smt2                                                                                   |189.0MiB|189.0MiB|0B| 0.0%|
|0058.smt2                                                                                   |896.0MiB|896.0MiB|0B| 0.0%|
|0059.smt2                                                                                   |814.0MiB|814.0MiB|0B| 0.0%|
|0060.smt2                                                                                   |194.0MiB|194.0MiB|0B| 0.0%|
|0061.smt2                                                                                   |235.0MiB|235.0MiB|0B| 0.0%|
|0062.smt2                                                                                   |2704.0MiB|2704.0MiB|0B| 0.0%|
|0063.smt2                                                                                   |2002.0MiB|2002.0MiB|0B| 0.0%|
|0064.smt2                                                                                   |626.0MiB|626.0MiB|0B| 0.0%|
|0065.smt2                                                                                   |270.0MiB|270.0MiB|0B| 0.0%|
|0066.smt2                                                                                   |2921.0MiB|2921.0MiB|0B| 0.0%|
|0067.smt2                                                                                   |424.0MiB|424.0MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |78.5MiB|78.5MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |66.888MiB|66.888MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |57.924MiB|57.924MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |80.456MiB|80.456MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |74.436MiB|74.436MiB|0B| 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                     |164.0MiB|164.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|0054.smt2                                                                                   |3249.0MiB|3249.0MiB|0B| 0.0%|
|0055.smt2                                                                                   |1405.0MiB|1405.0MiB|0B| 0.0%|
|0056.smt2                                                                                   |249.0MiB|249.0MiB|0B| 0.0%|
|0057.smt2                                                                                   |189.0MiB|189.0MiB|0B| 0.0%|
|0058.smt2                                                                                   |896.0MiB|896.0MiB|0B| 0.0%|
|0059.smt2                                                                                   |814.0MiB|814.0MiB|0B| 0.0%|
|0060.smt2                                                                                   |194.0MiB|194.0MiB|0B| 0.0%|
|0061.smt2                                                                                   |235.0MiB|235.0MiB|0B| 0.0%|
|0062.smt2                                                                                   |2704.0MiB|2704.0MiB|0B| 0.0%|
|0063.smt2                                                                                   |2002.0MiB|2002.0MiB|0B| 0.0%|
|0064.smt2                                                                                   |626.0MiB|626.0MiB|0B| 0.0%|
|0065.smt2                                                                                   |270.0MiB|270.0MiB|0B| 0.0%|
|0066.smt2                                                                                   |2921.0MiB|2921.0MiB|0B| 0.0%|
|0067.smt2                                                                                   |424.0MiB|424.0MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |78.5MiB|78.5MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |66.888MiB|66.888MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |57.924MiB|57.924MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |80.456MiB|80.456MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |74.436MiB|74.436MiB|0B| 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                     |164.0MiB|164.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|0054.smt2                                                                                  |  71.024s |3249.0MiB|
|0066.smt2                                                                                  |  68.565s |2921.0MiB|
|0062.smt2                                                                                  |  59.997s |2704.0MiB|
|0063.smt2                                                                                  |  80.130s |2002.0MiB|
|n29-0036.smt2                                                                              |  54.875s |1717.0MiB|
|n39-0046.smt2                                                                              |  66.024s |1642.0MiB|
|0055.smt2                                                                                  |  57.493s |1405.0MiB|
|n45-0052.smt2                                                                              |  64.500s |1300.0MiB|
|n1-0001.smt2                                                                               |  11.580s |1140.0MiB|
|n111-0015.smt2                                                                             |  95.071s |1099.0MiB|
|n70-0024.smt2                                                                              |  58.692s |1047.0MiB|
|n76-0030.smt2                                                                              |  59.020s |1046.0MiB|
|3106_1c933134166dbad31f79_38_QF_UFNIA.smt2                                                 |  85.124s |1031.0MiB|
|n71-0025.smt2                                                                              |  55.761s |1024.0MiB|
|n20-0026.smt2                                                                              |  89.249s |1006.0MiB|
|n43-0050.smt2                                                                              |  36.969s |979.0MiB|
|n112-0016.smt2                                                                             |  77.551s |962.0MiB|
|n116-0020.smt2                                                                             |  66.440s |958.0MiB|
|0058.smt2                                                                                  |  83.542s |896.0MiB|
|66603_accdadf23a1cf70ae043_72_QF_UFNIA.smt2                                                |  24.639s |828.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|0054.smt2                                                                                  |  71.024s |3249.0MiB|
|0066.smt2                                                                                  |  68.565s |2921.0MiB|
|0062.smt2                                                                                  |  59.997s |2704.0MiB|
|0063.smt2                                                                                  |  80.130s |2002.0MiB|
|n29-0036.smt2                                                                              |  54.875s |1717.0MiB|
|n39-0046.smt2                                                                              |  66.024s |1642.0MiB|
|0055.smt2                                                                                  |  57.493s |1405.0MiB|
|n45-0052.smt2                                                                              |  64.500s |1300.0MiB|
|n1-0001.smt2                                                                               |  11.580s |1140.0MiB|
|n111-0015.smt2                                                                             |  95.071s |1099.0MiB|
|n70-0024.smt2                                                                              |  58.692s |1047.0MiB|
|n76-0030.smt2                                                                              |  59.020s |1046.0MiB|
|3106_1c933134166dbad31f79_38_QF_UFNIA.smt2                                                 |  85.124s |1031.0MiB|
|n71-0025.smt2                                                                              |  55.761s |1024.0MiB|
|n20-0026.smt2                                                                              |  89.249s |1006.0MiB|
|n43-0050.smt2                                                                              |  36.969s |979.0MiB|
|n112-0016.smt2                                                                             |  77.551s |962.0MiB|
|n116-0020.smt2                                                                             |  66.440s |958.0MiB|
|0058.smt2                                                                                  |  83.542s |896.0MiB|
|66603_accdadf23a1cf70ae043_72_QF_UFNIA.smt2                                                |  24.639s |828.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|0054.smt2                                                                                   |  71.024s  |  71.024s  |   0.000s  | 0.0%|
|0055.smt2                                                                                   |  57.493s  |  57.493s  |   0.000s  | 0.0%|
|0056.smt2                                                                                   |  92.299s  |  92.299s  |   0.000s  | 0.0%|
|0057.smt2                                                                                   |  41.562s  |  41.562s  |   0.000s  | 0.0%|
|0058.smt2                                                                                   |  83.542s  |  83.542s  |   0.000s  | 0.0%|
|0059.smt2                                                                                   |  78.651s  |  78.651s  |   0.000s  | 0.0%|
|0060.smt2                                                                                   |  61.343s  |  61.343s  |   0.000s  | 0.0%|
|0061.smt2                                                                                   |  74.588s  |  74.588s  |   0.000s  | 0.0%|
|0062.smt2                                                                                   |  59.997s  |  59.997s  |   0.000s  | 0.0%|
|0063.smt2                                                                                   |  80.130s  |  80.130s  |   0.000s  | 0.0%|
|0064.smt2                                                                                   |  88.408s  |  88.408s  |   0.000s  | 0.0%|
|0065.smt2                                                                                   |  70.767s  |  70.767s  |   0.000s  | 0.0%|
|0066.smt2                                                                                   |  68.565s  |  68.565s  |   0.000s  | 0.0%|
|0067.smt2                                                                                   |  72.689s  |  72.689s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |   8.843s  |   8.843s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |   0.757s  |   0.757s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |   3.547s  |   3.547s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |  26.204s  |  26.204s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |   7.751s  |   7.751s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                     |  96.758s  |  96.758s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFNIA.smt2                                     | 100.784s  | 100.784s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFNIA.smt2                                     |  91.045s  |  91.045s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFNIA.smt2                                     |  82.409s  |  82.409s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFNIA.smt2                                     |  12.062s  |  12.062s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_38_QF_UFNIA.smt2                                                  |  85.124s  |  85.124s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_39_QF_UFNIA.smt2                                                  |  19.295s  |  19.295s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_40_QF_UFNIA.smt2                                                  |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_41_QF_UFNIA.smt2                                                  |   4.428s  |   4.428s  |   0.000s  | 0.0%|
|3106_afb7bc55417e43d7a22790c3576f04fc_37_QF_UFNIA.smt2                                      |  63.746s  |  63.746s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_55_QF_UFNIA.smt2                                                 |  16.126s  |  16.126s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_56_QF_UFNIA.smt2                                                 |   4.808s  |   4.808s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_57_QF_UFNIA.smt2                                                 |  91.874s  |  91.874s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_58_QF_UFNIA.smt2                                                 |   0.696s  |   0.696s  |   0.000s  | 0.0%|
|38347_525a1ca0331f2bcbf520_54_QF_UFNIA.smt2                                                 |  99.767s  |  99.767s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_44_QF_UFNIA.smt2                                                 | 102.610s  | 102.610s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_45_QF_UFNIA.smt2                                                 |  68.577s  |  68.577s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_46_QF_UFNIA.smt2                                                 |  50.188s  |  50.188s  |   0.000s  | 0.0%|
|39657_2866defdd1f2434b69ab_48_QF_UFNIA.smt2                                                 |   1.287s  |   1.287s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_61_QF_UFNIA.smt2                                                 |  41.698s  |  41.698s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_62_QF_UFNIA.smt2                                                 |  72.803s  |  72.803s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_63_QF_UFNIA.smt2                                                 |  88.031s  |  88.031s  |   0.000s  | 0.0%|
|41958_45c688a4814eb926c254_59_QF_UFNIA.smt2                                                 |   3.924s  |   3.924s  |   0.000s  | 0.0%|
|41958_45c688a4814eb926c254_60_QF_UFNIA.smt2                                                 |   0.720s  |   0.720s  |   0.000s  | 0.0%|
|44289_4066055e0f64d96da11a_14_QF_UFNIA.smt2                                                 |   3.662s  |   3.662s  |   0.000s  | 0.0%|
|44289_4066055e0f64d96da11a_15_QF_UFNIA.smt2                                                 |  97.886s  |  97.886s  |   0.000s  | 0.0%|
|44289_b077fc096b3d41cba49f8628caff7fa5_16_QF_UFNIA.smt2                                     |  68.191s  |  68.191s  |   0.000s  | 0.0%|
|44289_e5a2e5c780236919ee6a_17_QF_UFNIA.smt2                                                 |   7.070s  |   7.070s  |   0.000s  | 0.0%|
|44289_e5a2e5c780236919ee6a_18_QF_UFNIA.smt2                                                 |  11.983s  |  11.983s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_34_QF_UFNIA.smt2                                                 | 103.287s  | 103.287s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_35_QF_UFNIA.smt2                                                 |  86.958s  |  86.958s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_36_QF_UFNIA.smt2                                                 |  80.297s  |  80.297s  |   0.000s  | 0.0%|
|52759_af0c476fe3b544b9a8507f3e42472c43_12_QF_UFNIA.smt2                                     |  25.328s  |  25.328s  |   0.000s  | 0.0%|
|52759_af0c476fe3b544b9a8507f3e42472c43_13_QF_UFNIA.smt2                                     |   7.253s  |   7.253s  |   0.000s  | 0.0%|
|52759_bec3a2272267494faeecb6bfaf253e3b_10_QF_UFNIA.smt2                                     |  94.993s  |  94.993s  |   0.000s  | 0.0%|
|52759_bec3a2272267494faeecb6bfaf253e3b_11_QF_UFNIA.smt2                                     |  19.136s  |  19.136s  |   0.000s  | 0.0%|
|63058_55d6bef5390186355f11_26_QF_UFNIA.smt2                                                 |  19.770s  |  19.770s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_22_QF_UFNIA.smt2                                                 |   9.978s  |   9.978s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_23_QF_UFNIA.smt2                                                 |  12.868s  |  12.868s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_24_QF_UFNIA.smt2                                                 |  65.148s  |  65.148s  |   0.000s  | 0.0%|
|63058_aa742630eef64f949de269382c1f9035_25_UFNIA.smt2                                        |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_5_QF_UFNIA.smt2                                                  |  94.727s  |  94.727s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_6_QF_UFNIA.smt2                                                  |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_7_QF_UFNIA.smt2                                                  |  32.634s  |  32.634s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_8_QF_UFNIA.smt2                                                  |   0.632s  |   0.632s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_72_QF_UFNIA.smt2                                                 |  24.639s  |  24.639s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_73_QF_UFNIA.smt2                                                 |  89.194s  |  89.194s  |   0.000s  | 0.0%|
|72658_63104dadde9c6026353f_70_QF_UFNIA.smt2                                                 |  14.452s  |  14.452s  |   0.000s  | 0.0%|
|72658_63104dadde9c6026353f_71_QF_UFNIA.smt2                                                 |  61.129s  |  61.129s  |   0.000s  | 0.0%|
|72771_f9d228efc97cf1458e38_64_QF_UFNIA.smt2                                                 |   1.178s  |   1.178s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_0_UFNIA.smt2                                                     |   0.677s  |   0.677s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_1_UFNIA.smt2                                                     |   7.356s  |   7.356s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_2_UFNIA.smt2                                                     |  96.554s  |  96.554s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_3_UFNIA.smt2                                                     |  94.091s  |  94.091s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_4_UFNIA.smt2                                                     |  53.554s  |  53.554s  |   0.000s  | 0.0%|
|93493_1fdb6cc8eb9c4363b5838af9eb8c7f1f_53_QF_UFNIA.smt2                                     |  91.612s  |  91.612s  |   0.000s  | 0.0%|
|93493_27ab26d56d60426da02e50231269b6ff_51_QF_UFNIA.smt2                                     |  70.426s  |  70.426s  |   0.000s  | 0.0%|
|93493_4ea6163ed03941199c785278ccc42812_49_QF_UFNIA.smt2                                     | 100.195s  | 100.195s  |   0.000s  | 0.0%|
|93493_798593962ee29ad45ac8_52_QF_UFNIA.smt2                                                 |  71.600s  |  71.600s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_29_QF_UFNIA.smt2                                                   |  67.833s  |  67.833s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_30_QF_UFNIA.smt2                                                   |  74.979s  |  74.979s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_31_QF_UFNIA.smt2                                                   |   4.390s  |   4.390s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_32_QF_UFNIA.smt2                                                   |  52.323s  |  52.323s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_33_QF_UFNIA.smt2                                                   |  78.610s  |  78.610s  |   0.000s  | 0.0%|
|int_check_bvsge_bvashr1_rtl.smt2                                                            |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|int_check_bvsge_bvlshr0_ltr_inv_g.smt2                                                      |   0.789s  |   0.789s  |   0.000s  | 0.0%|
|int_check_bvsge_bvlshr0_rtl.smt2                                                            |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|int_check_bvsge_bvneg_ltr_inv_g.smt2                                                        |   0.216s  |   0.216s  |   0.000s  | 0.0%|
|int_check_bvsge_bvudiv1_rtl.smt2                                                            |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|int_check_bvsge_bvurem1_ltr_inv_g.smt2                                                      |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvadd_rtl.smt2                                                              |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvashr0_rtl.smt2                                                            |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvashr1_ltr_inv_g.smt2                                                      |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvlshr0_rtl.smt2                                                            |   0.482s  |   0.482s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvlshr1_rtl.smt2                                                            |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvshl0_ltr_inv_g.smt2                                                       |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvshl0_rtl.smt2                                                             |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvurem0_rtl.smt2                                                            |   0.873s  |   0.873s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvurem1_rtl.smt2                                                            |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|int_check_bvsle_bvadd_ltr_inv_g.smt2                                                        |   1.308s  |   1.308s  |   0.000s  | 0.0%|
|int_check_bvsle_bvashr0_ltr_inv_g.smt2                                                      |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|int_check_bvsle_bvashr0_rtl.smt2                                                            |   0.391s  |   0.391s  |   0.000s  | 0.0%|
|int_check_bvsle_bvashr1_rtl.smt2                                                            |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|int_check_bvsle_bvshl0_ltr_inv_g.smt2                                                       |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|int_check_bvsle_bvudiv0_rtl.smt2                                                            |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|int_check_bvsle_bvurem1_ltr_inv_g.smt2                                                      |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|int_check_bvslt_bvashr0_rtl.smt2                                                            |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|int_check_bvslt_bvashr1_rtl.smt2                                                            |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|int_check_bvslt_bvlshr0_ltr_inv_g.smt2                                                      |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|int_check_bvslt_bvlshr0_rtl.smt2                                                            |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|int_check_bvslt_bvudiv0_ltr_inv_g.smt2                                                      |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|int_check_bvuge_bvashr1_ltr_inv_g.smt2                                                      |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|int_check_bvuge_bvashr1_rtl.smt2                                                            |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|int_check_bvuge_bvshl0_rtl.smt2                                                             |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|int_check_bvuge_bvurem0_rtl.smt2                                                            |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|int_check_bvugt_bvashr0_ltr_inv_g.smt2                                                      |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|int_check_bvugt_bvashr1_ltr_inv_g.smt2                                                      |   0.198s  |   0.198s  |   0.000s  | 0.0%|
|int_check_bvugt_bvashr1_rtl.smt2                                                            |   0.779s  |   0.779s  |   0.000s  | 0.0%|
|int_check_bvugt_bvudiv0_rtl.smt2                                                            |   1.505s  |   1.505s  |   0.000s  | 0.0%|
|int_check_bvugt_bvudiv1_rtl.smt2                                                            |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|int_check_bvugt_bvurem0_rtl.smt2                                                            |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|int_check_bvule_bvneg_ltr_inv_g.smt2                                                        |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|int_check_bvule_bvudiv1_ltr_inv_g.smt2                                                      |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|int_check_bvule_bvurem0_ltr_inv_g.smt2                                                      |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|int_check_bvule_bvurem1_ltr_inv_g.smt2                                                      |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|int_check_bvult_bvashr1_rtl.smt2                                                            |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|int_check_bvult_bvneg_ltr_inv_g.smt2                                                        |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|int_check_bvult_bvurem0_ltr_inv_g.smt2                                                      |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|int_check_bvult_bvurem1_ltr_inv_g.smt2                                                      |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|int_check_eq_bvashr0_rtl.smt2                                                               |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|int_check_eq_bvlshr0_rtl.smt2                                                               |  82.642s  |  82.642s  |   0.000s  | 0.0%|
|int_check_eq_bvudiv0_rtl.smt2                                                               |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|int_check_eq_bvudiv1_rtl.smt2                                                               |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|int_check_eq_bvurem0_ltr_inv_g.smt2                                                         |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|int_check_eq_bvurem0_rtl.smt2                                                               |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|int_check_ne_bvashr0_ltr_inv_g.smt2                                                         |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|int_check_ne_bvashr1_ltr_inv_g.smt2                                                         |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|n0-0000.smt2                                                                                |  72.756s  |  72.756s  |   0.000s  | 0.0%|
|n1-0001.smt2                                                                                |  11.580s  |  11.580s  |   0.000s  | 0.0%|
|n10-0010.smt2                                                                               |  86.365s  |  86.365s  |   0.000s  | 0.0%|
|n100-0003.smt2                                                                              |   5.601s  |   5.601s  |   0.000s  | 0.0%|
|n101-0004.smt2                                                                              |   0.271s  |   0.271s  |   0.000s  | 0.0%|
|n102-0005.smt2                                                                              |   3.374s  |   3.374s  |   0.000s  | 0.0%|
|n103-0006.smt2                                                                              |  98.324s  |  98.324s  |   0.000s  | 0.0%|
|n104-0007.smt2                                                                              |   3.529s  |   3.529s  |   0.000s  | 0.0%|
|n105-0008.smt2                                                                              | 100.804s  | 100.804s  |   0.000s  | 0.0%|
|n106-0009.smt2                                                                              |   1.788s  |   1.788s  |   0.000s  | 0.0%|
|n107-0011.smt2                                                                              |  29.659s  |  29.659s  |   0.000s  | 0.0%|
|n108-0012.smt2                                                                              |   2.605s  |   2.605s  |   0.000s  | 0.0%|
|n109-0013.smt2                                                                              |  76.960s  |  76.960s  |   0.000s  | 0.0%|
|n11-0012.smt2                                                                               |  21.376s  |  21.376s  |   0.000s  | 0.0%|
|n110-0014.smt2                                                                              |   0.977s  |   0.977s  |   0.000s  | 0.0%|
|n111-0015.smt2                                                                              |  95.071s  |  95.071s  |   0.000s  | 0.0%|
|n112-0016.smt2                                                                              |  77.551s  |  77.551s  |   0.000s  | 0.0%|
|n113-0017.smt2                                                                              | 113.827s  | 113.827s  |   0.000s  | 0.0%|
|n114-0018.smt2                                                                              |  62.781s  |  62.781s  |   0.000s  | 0.0%|
|n115-0019.smt2                                                                              |  79.533s  |  79.533s  |   0.000s  | 0.0%|
|n116-0020.smt2                                                                              |  66.440s  |  66.440s  |   0.000s  | 0.0%|
|n117-0021.smt2                                                                              |  82.744s  |  82.744s  |   0.000s  | 0.0%|
|n118-0022.smt2                                                                              |  89.485s  |  89.485s  |   0.000s  | 0.0%|
|n119-0023.smt2                                                                              |  17.999s  |  17.999s  |   0.000s  | 0.0%|
|n12-0013.smt2                                                                               |   9.607s  |   9.607s  |   0.000s  | 0.0%|
|n120-0024.smt2                                                                              |  89.472s  |  89.472s  |   0.000s  | 0.0%|
|n121-0025.smt2                                                                              |  89.276s  |  89.276s  |   0.000s  | 0.0%|
|n122-0026.smt2                                                                              |  63.124s  |  63.124s  |   0.000s  | 0.0%|
|n125-0029.smt2                                                                              |   2.545s  |   2.545s  |   0.000s  | 0.0%|
|n126-0030.smt2                                                                              |  41.438s  |  41.438s  |   0.000s  | 0.0%|
|n127-0031.smt2                                                                              |   8.495s  |   8.495s  |   0.000s  | 0.0%|
|n128-0032.smt2                                                                              |   2.422s  |   2.422s  |   0.000s  | 0.0%|
|n129-0033.smt2                                                                              |   3.533s  |   3.533s  |   0.000s  | 0.0%|
|n13-0015.smt2                                                                               |  68.443s  |  68.443s  |   0.000s  | 0.0%|
|n130-0034.smt2                                                                              |  43.224s  |  43.224s  |   0.000s  | 0.0%|
|n131-0035.smt2                                                                              |   1.699s  |   1.699s  |   0.000s  | 0.0%|
|n132-0036.smt2                                                                              |   5.288s  |   5.288s  |   0.000s  | 0.0%|
|n133-0037.smt2                                                                              |  23.985s  |  23.985s  |   0.000s  | 0.0%|
|n134-0038.smt2                                                                              |   0.293s  |   0.293s  |   0.000s  | 0.0%|
|n135-0039.smt2                                                                              |  25.113s  |  25.113s  |   0.000s  | 0.0%|
|n136-0040.smt2                                                                              |  80.184s  |  80.184s  |   0.000s  | 0.0%|
|n137-0041.smt2                                                                              |   3.368s  |   3.368s  |   0.000s  | 0.0%|
|n16-0019.smt2                                                                               |  67.702s  |  67.702s  |   0.000s  | 0.0%|
|n17-0021.smt2                                                                               |   4.244s  |   4.244s  |   0.000s  | 0.0%|
|n18-0022.smt2                                                                               |   6.223s  |   6.223s  |   0.000s  | 0.0%|
|n19-0024.smt2                                                                               |  76.243s  |  76.243s  |   0.000s  | 0.0%|
|n2-0002.smt2                                                                                |  95.545s  |  95.545s  |   0.000s  | 0.0%|
|n20-0026.smt2                                                                               |  89.249s  |  89.249s  |   0.000s  | 0.0%|
|n21-0027.smt2                                                                               |  84.529s  |  84.529s  |   0.000s  | 0.0%|
|n22-0029.smt2                                                                               |  58.307s  |  58.307s  |   0.000s  | 0.0%|
|n23-0030.smt2                                                                               |  96.550s  |  96.550s  |   0.000s  | 0.0%|
|n24-0031.smt2                                                                               |  58.752s  |  58.752s  |   0.000s  | 0.0%|
|n25-0032.smt2                                                                               |  51.528s  |  51.528s  |   0.000s  | 0.0%|
|n26-0033.smt2                                                                               |   9.494s  |   9.494s  |   0.000s  | 0.0%|
|n27-0034.smt2                                                                               |   6.245s  |   6.245s  |   0.000s  | 0.0%|
|n28-0035.smt2                                                                               |  71.712s  |  71.712s  |   0.000s  | 0.0%|
|n29-0036.smt2                                                                               |  54.875s  |  54.875s  |   0.000s  | 0.0%|
|n3-0003.smt2                                                                                |  68.620s  |  68.620s  |   0.000s  | 0.0%|
|n30-0037.smt2                                                                               |   8.447s  |   8.447s  |   0.000s  | 0.0%|
|n31-0038.smt2                                                                               |   7.564s  |   7.564s  |   0.000s  | 0.0%|
|n32-0039.smt2                                                                               |  77.589s  |  77.589s  |   0.000s  | 0.0%|
|n33-0040.smt2                                                                               |  60.793s  |  60.793s  |   0.000s  | 0.0%|
|n34-0041.smt2                                                                               |  22.281s  |  22.281s  |   0.000s  | 0.0%|
|n35-0042.smt2                                                                               |  15.295s  |  15.295s  |   0.000s  | 0.0%|
|n36-0043.smt2                                                                               |  77.577s  |  77.577s  |   0.000s  | 0.0%|
|n37-0044.smt2                                                                               |   9.110s  |   9.110s  |   0.000s  | 0.0%|
|n38-0045.smt2                                                                               |  31.913s  |  31.913s  |   0.000s  | 0.0%|
|n39-0046.smt2                                                                               |  66.024s  |  66.024s  |   0.000s  | 0.0%|
|n4-0004.smt2                                                                                | 109.151s  | 109.151s  |   0.000s  | 0.0%|
|n40-0047.smt2                                                                               |  82.471s  |  82.471s  |   0.000s  | 0.0%|
|n41-0048.smt2                                                                               |   9.285s  |   9.285s  |   0.000s  | 0.0%|
|n42-0049.smt2                                                                               |  43.303s  |  43.303s  |   0.000s  | 0.0%|
|n43-0050.smt2                                                                               |  36.969s  |  36.969s  |   0.000s  | 0.0%|
|n44-0051.smt2                                                                               |  68.196s  |  68.196s  |   0.000s  | 0.0%|
|n45-0052.smt2                                                                               |  64.500s  |  64.500s  |   0.000s  | 0.0%|
|n46-0053.smt2                                                                               |  35.760s  |  35.760s  |   0.000s  | 0.0%|
|n47-0000.smt2                                                                               |  75.764s  |  75.764s  |   0.000s  | 0.0%|
|n48-0001.smt2                                                                               | 103.088s  | 103.088s  |   0.000s  | 0.0%|
|n49-0002.smt2                                                                               |  67.344s  |  67.344s  |   0.000s  | 0.0%|
|n5-0005.smt2                                                                                |  19.298s  |  19.298s  |   0.000s  | 0.0%|
|n50-0003.smt2                                                                               |  30.952s  |  30.952s  |   0.000s  | 0.0%|
|n51-0004.smt2                                                                               |  84.938s  |  84.938s  |   0.000s  | 0.0%|
|n52-0005.smt2                                                                               |  90.945s  |  90.945s  |   0.000s  | 0.0%|
|n53-0006.smt2                                                                               |  13.332s  |  13.332s  |   0.000s  | 0.0%|
|n54-0007.smt2                                                                               |  55.388s  |  55.388s  |   0.000s  | 0.0%|
|n55-0008.smt2                                                                               |  77.836s  |  77.836s  |   0.000s  | 0.0%|
|n56-0009.smt2                                                                               |  16.335s  |  16.335s  |   0.000s  | 0.0%|
|n57-0010.smt2                                                                               |  10.161s  |  10.161s  |   0.000s  | 0.0%|
|n58-0011.smt2                                                                               |   6.310s  |   6.310s  |   0.000s  | 0.0%|
|n59-0012.smt2                                                                               |  93.452s  |  93.452s  |   0.000s  | 0.0%|
|n6-0006.smt2                                                                                |  92.561s  |  92.561s  |   0.000s  | 0.0%|
|n60-0014.smt2                                                                               |  70.195s  |  70.195s  |   0.000s  | 0.0%|
|n61-0015.smt2                                                                               |  15.870s  |  15.870s  |   0.000s  | 0.0%|
|n62-0016.smt2                                                                               |  97.632s  |  97.632s  |   0.000s  | 0.0%|
|n63-0017.smt2                                                                               | 102.418s  | 102.418s  |   0.000s  | 0.0%|
|n64-0018.smt2                                                                               | 108.369s  | 108.369s  |   0.000s  | 0.0%|
|n65-0019.smt2                                                                               |   3.251s  |   3.251s  |   0.000s  | 0.0%|
|n66-0020.smt2                                                                               |  77.050s  |  77.050s  |   0.000s  | 0.0%|
|n67-0021.smt2                                                                               |  93.889s  |  93.889s  |   0.000s  | 0.0%|
|n68-0022.smt2                                                                               | 107.573s  | 107.573s  |   0.000s  | 0.0%|
|n69-0023.smt2                                                                               |  81.238s  |  81.238s  |   0.000s  | 0.0%|
|n7-0007.smt2                                                                                |  86.472s  |  86.472s  |   0.000s  | 0.0%|
|n70-0024.smt2                                                                               |  58.692s  |  58.692s  |   0.000s  | 0.0%|
|n71-0025.smt2                                                                               |  55.761s  |  55.761s  |   0.000s  | 0.0%|
|n72-0026.smt2                                                                               |  72.755s  |  72.755s  |   0.000s  | 0.0%|
|n73-0027.smt2                                                                               |  18.397s  |  18.397s  |   0.000s  | 0.0%|
|n74-0028.smt2                                                                               |  60.677s  |  60.677s  |   0.000s  | 0.0%|
|n75-0029.smt2                                                                               |  93.717s  |  93.717s  |   0.000s  | 0.0%|
|n76-0030.smt2                                                                               |  59.020s  |  59.020s  |   0.000s  | 0.0%|
|n77-0031.smt2                                                                               |  55.299s  |  55.299s  |   0.000s  | 0.0%|
|n78-0032.smt2                                                                               |  92.650s  |  92.650s  |   0.000s  | 0.0%|
|n79-0033.smt2                                                                               |  79.711s  |  79.711s  |   0.000s  | 0.0%|
|n8-0008.smt2                                                                                |  97.053s  |  97.053s  |   0.000s  | 0.0%|
|n80-0034.smt2                                                                               |  83.946s  |  83.946s  |   0.000s  | 0.0%|
|n81-0035.smt2                                                                               |  50.460s  |  50.460s  |   0.000s  | 0.0%|
|n82-0036.smt2                                                                               |  61.805s  |  61.805s  |   0.000s  | 0.0%|
|n83-0037.smt2                                                                               |  90.623s  |  90.623s  |   0.000s  | 0.0%|
|n84-0038.smt2                                                                               |  68.173s  |  68.173s  |   0.000s  | 0.0%|
|n85-0039.smt2                                                                               |  76.782s  |  76.782s  |   0.000s  | 0.0%|
|n86-0040.smt2                                                                               |   0.937s  |   0.937s  |   0.000s  | 0.0%|
|n87-0041.smt2                                                                               |  24.856s  |  24.856s  |   0.000s  | 0.0%|
|n88-0042.smt2                                                                               |  65.527s  |  65.527s  |   0.000s  | 0.0%|
|n89-0044.smt2                                                                               |  94.830s  |  94.830s  |   0.000s  | 0.0%|
|n9-0009.smt2                                                                                |  19.746s  |  19.746s  |   0.000s  | 0.0%|
|n90-0045.smt2                                                                               |   5.873s  |   5.873s  |   0.000s  | 0.0%|
|n91-0046.smt2                                                                               |  27.383s  |  27.383s  |   0.000s  | 0.0%|
|n92-0047.smt2                                                                               |   1.664s  |   1.664s  |   0.000s  | 0.0%|
|n93-0048.smt2                                                                               |  76.281s  |  76.281s  |   0.000s  | 0.0%|
|n94-0049.smt2                                                                               |  58.501s  |  58.501s  |   0.000s  | 0.0%|
|n95-0050.smt2                                                                               |  99.677s  |  99.677s  |   0.000s  | 0.0%|
|n96-0051.smt2                                                                               |  16.037s  |  16.037s  |   0.000s  | 0.0%|
|n97-0000.smt2                                                                               |  44.650s  |  44.650s  |   0.000s  | 0.0%|
|n98-0001.smt2                                                                               |  67.497s  |  67.497s  |   0.000s  | 0.0%|
|qf_AddSub_1165_values_0.smt2                                                                |   0.487s  |   0.487s  |   0.000s  | 0.0%|
|qf_AddSub_1574_values_0.smt2                                                                |   0.378s  |   0.378s  |   0.000s  | 0.0%|
|qf_AddSub_1619_values_0.smt2                                                                |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|qf_AndOrXor_1869_values_0.smt2                                                              |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|qf_AndOrXor_1894_values_0.smt2                                                              |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|qf_AndOrXor_210_values_0.smt2                                                               |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|qf_AndOrXor_230_values_0.smt2                                                               |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|qf_AndOrXor_2443_values_0.smt2                                                              |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|qf_AndOrXor_290_values_7.smt2                                                               |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|qf_AndOrXor_794_values_121.smt2                                                             |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|qf_InstCombineShift497a_values_0.smt2                                                       |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|qf_InstCombineShift497b_values_0.smt2                                                       |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|qf_InstCombineShift497c_values_0.smt2                                                       |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|qf_InstCombineShift497d_values_0.smt2                                                       |  48.318s  |  48.318s  |   0.000s  | 0.0%|
|qf_Select_510_values_0.smt2                                                                 |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|qf_Select_575a_values_0.smt2                                                                |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|qf_Select_575b_values_0.smt2                                                                |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|qf_Select_700_values_123.smt2                                                               |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|qf_Select_705_values_0.smt2                                                                 |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|qf_Select_727_values_0.smt2                                                                 |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|qf_muldivrem_152_values_0.smt2                                                              |  24.917s  |  24.917s  |   0.000s  | 0.0%|
|qf_muldivrem_229_values_0.smt2                                                              |  78.453s  |  78.453s  |   0.000s  | 0.0%|
|qf_muldivrem_239_values_0.smt2                                                              |  93.265s  |  93.265s  |   0.000s  | 0.0%|
</details>
