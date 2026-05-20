Comparing data and data


# SUMMARY
- LHS tests = 1480
- RHS tests = 1480
- LHS success = 1480  (100.0%)
- RHS success = 1480  (100.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: AUFNIRA.tar.zst
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: bc6c38e7d3424b88a505cacba4b268d0774d4547
Z3 branch: master
Z3 options: "-T:20"
Z3 inputs: https://zenodo.org/records/16740866/files/AUFNIRA.tar.zst?download=1
Z3 commit message: [code-simplifier] Simplify `api_ast.cpp` by removing unreachable branch and stray comment (#9570)

This change simplifies recently touched API code in
`src/api/api_ast.cpp` without altering semantics. It removes an
unreachable error path in `Z3_get_index_value` and deletes an empty
comment in `Z3_mk_rec_func_decl`.

- **`Z3_get_index_value`: remove dead branch**
- After validating `a` is non-null and of kind `AST_VAR`, the conversion
to `var*` is already guaranteed by existing AST casting invariants.
- The redundant null-check/error-return branch was removed, leaving a
direct index return.

- **`Z3_mk_rec_func_decl`: remove noise**
  - Deleted a stray empty `//` line.

```cpp
// before
var* va = to_var(_a);
if (va) {
    return va->get_idx();
}
SET_ERROR_CODE(Z3_INVALID_ARG, nullptr);
return 0;

// after
var* va = to_var(_a);
return va->get_idx();
```

---------

Co-authored-by: copilot-swe-agent[bot] <198982749+Copilot@users.noreply.github.com>
Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: AUFNIRA.tar.zst
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: bc6c38e7d3424b88a505cacba4b268d0774d4547
Z3 branch: master
Z3 options: "-T:20"
Z3 inputs: https://zenodo.org/records/16740866/files/AUFNIRA.tar.zst?download=1
Z3 commit message: [code-simplifier] Simplify `api_ast.cpp` by removing unreachable branch and stray comment (#9570)

This change simplifies recently touched API code in
`src/api/api_ast.cpp` without altering semantics. It removes an
unreachable error path in `Z3_get_index_value` and deletes an empty
comment in `Z3_mk_rec_func_decl`.

- **`Z3_get_index_value`: remove dead branch**
- After validating `a` is non-null and of kind `AST_VAR`, the conversion
to `var*` is already guaranteed by existing AST casting invariants.
- The redundant null-check/error-return branch was removed, leaving a
direct index return.

- **`Z3_mk_rec_func_decl`: remove noise**
  - Deleted a stray empty `//` line.

```cpp
// before
var* va = to_var(_a);
if (va) {
    return va->get_idx();
}
SET_ERROR_CODE(Z3_INVALID_ARG, nullptr);
return 0;

// after
var* va = to_var(_a);
return va->get_idx();
```

---------

Co-authored-by: copilot-swe-agent[bot] <198982749+Copilot@users.noreply.github.com>
Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/AUFNIRA/FFT/smtlib.549916.smt2                                              |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.560602.smt2                                              |  20.484s  |  20.484s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.561727.smt2                                              |  20.186s  |  20.186s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.562301.smt2                                              |  22.226s  |  22.226s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.607667.smt2                                              |  20.575s  |  20.575s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.612263.smt2                                              |  20.912s  |  20.912s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.616911.smt2                                              |  20.497s  |  20.497s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.620440.smt2                                              |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.621785.smt2                                              |  20.502s  |  20.502s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.622079.smt2                                              |   0.597s  |   0.597s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.623344.smt2                                              |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.624862.smt2                                              |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.626115.smt2                                              |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.627369.smt2                                              |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.628941.smt2                                              |  22.072s  |  22.072s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.629057.smt2                                              |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.629149.smt2                                              |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.629241.smt2                                              |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.629331.smt2                                              |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.629335.smt2                                              |   0.098s  |   0.098s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/AUFNIRA/FFT/smtlib.549916.smt2                                              |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.560602.smt2                                              |  20.484s  |  20.484s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.561727.smt2                                              |  20.186s  |  20.186s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.562301.smt2                                              |  22.226s  |  22.226s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.607667.smt2                                              |  20.575s  |  20.575s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.612263.smt2                                              |  20.912s  |  20.912s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.616911.smt2                                              |  20.497s  |  20.497s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.620440.smt2                                              |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.621785.smt2                                              |  20.502s  |  20.502s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.622079.smt2                                              |   0.597s  |   0.597s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.623344.smt2                                              |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.624862.smt2                                              |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.626115.smt2                                              |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.627369.smt2                                              |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.628941.smt2                                              |  22.072s  |  22.072s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.629057.smt2                                              |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.629149.smt2                                              |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.629241.smt2                                              |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.629331.smt2                                              |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.629335.smt2                                              |   0.098s  |   0.098s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/AUFNIRA/FFT/smtlib.549916.smt2                                              |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.560602.smt2                                              |  20.484s  |  20.484s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.561727.smt2                                              |  20.186s  |  20.186s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.562301.smt2                                              |  22.226s  |  22.226s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.607667.smt2                                              |  20.575s  |  20.575s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.612263.smt2                                              |  20.912s  |  20.912s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.616911.smt2                                              |  20.497s  |  20.497s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.620440.smt2                                              |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.621785.smt2                                              |  20.502s  |  20.502s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.622079.smt2                                              |   0.597s  |   0.597s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.623344.smt2                                              |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.624862.smt2                                              |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.626115.smt2                                              |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.627369.smt2                                              |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.628941.smt2                                              |  22.072s  |  22.072s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.629057.smt2                                              |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.629149.smt2                                              |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.629241.smt2                                              |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.629331.smt2                                              |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.629335.smt2                                              |   0.098s  |   0.098s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/AUFNIRA/FFT/smtlib.549916.smt2                                              |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.560602.smt2                                              |  20.484s  |  20.484s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.561727.smt2                                              |  20.186s  |  20.186s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.562301.smt2                                              |  22.226s  |  22.226s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.607667.smt2                                              |  20.575s  |  20.575s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.612263.smt2                                              |  20.912s  |  20.912s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.616911.smt2                                              |  20.497s  |  20.497s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.620440.smt2                                              |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.621785.smt2                                              |  20.502s  |  20.502s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.622079.smt2                                              |   0.597s  |   0.597s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.623344.smt2                                              |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.624862.smt2                                              |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.626115.smt2                                              |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.627369.smt2                                              |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.628941.smt2                                              |  22.072s  |  22.072s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.629057.smt2                                              |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.629149.smt2                                              |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.629241.smt2                                              |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.629331.smt2                                              |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.629335.smt2                                              |   0.098s  |   0.098s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/AUFNIRA/FFT/z3.699496.smt2                                                 |  23.742s |3919.0MiB|
|non-incremental/AUFNIRA/FFT/smtlib.933524.smt2                                             |  23.700s |2489.0MiB|
|non-incremental/AUFNIRA/FFT/smtlib.712540.smt2                                             |  23.634s |4508.0MiB|
|non-incremental/AUFNIRA/FFT/smtlib.698113.smt2                                             |  23.604s |2552.0MiB|
|non-incremental/AUFNIRA/FFT/z3.675244.smt2                                                 |  23.595s |3919.0MiB|
|non-incremental/AUFNIRA/FFT/z3.816994.smt2                                                 |  23.579s |2522.0MiB|
|non-incremental/AUFNIRA/FFT/z3.638333.smt2                                                 |  23.564s |2196.0MiB|
|non-incremental/AUFNIRA/FFT/z3.692368.smt2                                                 |  23.514s |2568.0MiB|
|non-incremental/AUFNIRA/FFT/z3.958311.smt2                                                 |  23.506s |4283.0MiB|
|non-incremental/AUFNIRA/FFT/z3.918728.smt2                                                 |  23.458s |2357.0MiB|
|non-incremental/AUFNIRA/FFT/z3.817643.smt2                                                 |  23.453s |2635.0MiB|
|non-incremental/AUFNIRA/FFT/z3.710520.smt2                                                 |  23.450s |2559.0MiB|
|non-incremental/AUFNIRA/FFT/smtlib.653905.smt2                                             |  23.438s |2053.0MiB|
|non-incremental/AUFNIRA/FFT/z3.780093.smt2                                                 |  23.438s |2126.0MiB|
|non-incremental/AUFNIRA/FFT/smtlib.673324.smt2                                             |  23.425s |2287.0MiB|
|non-incremental/AUFNIRA/FFT/z3.774116.smt2                                                 |  23.417s |2160.0MiB|
|non-incremental/AUFNIRA/FFT/smtlib.946545.smt2                                             |  23.415s |2137.0MiB|
|non-incremental/AUFNIRA/FFT/smtlib.714922.smt2                                             |  23.414s |2507.0MiB|
|non-incremental/AUFNIRA/FFT/z3.636136.smt2                                                 |  23.402s |4400.0MiB|
|non-incremental/AUFNIRA/FFT/z3.621866.smt2                                                 |  23.379s |2979.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/AUFNIRA/FFT/z3.699496.smt2                                                 |  23.742s |3919.0MiB|
|non-incremental/AUFNIRA/FFT/smtlib.933524.smt2                                             |  23.700s |2489.0MiB|
|non-incremental/AUFNIRA/FFT/smtlib.712540.smt2                                             |  23.634s |4508.0MiB|
|non-incremental/AUFNIRA/FFT/smtlib.698113.smt2                                             |  23.604s |2552.0MiB|
|non-incremental/AUFNIRA/FFT/z3.675244.smt2                                                 |  23.595s |3919.0MiB|
|non-incremental/AUFNIRA/FFT/z3.816994.smt2                                                 |  23.579s |2522.0MiB|
|non-incremental/AUFNIRA/FFT/z3.638333.smt2                                                 |  23.564s |2196.0MiB|
|non-incremental/AUFNIRA/FFT/z3.692368.smt2                                                 |  23.514s |2568.0MiB|
|non-incremental/AUFNIRA/FFT/z3.958311.smt2                                                 |  23.506s |4283.0MiB|
|non-incremental/AUFNIRA/FFT/z3.918728.smt2                                                 |  23.458s |2357.0MiB|
|non-incremental/AUFNIRA/FFT/z3.817643.smt2                                                 |  23.453s |2635.0MiB|
|non-incremental/AUFNIRA/FFT/z3.710520.smt2                                                 |  23.450s |2559.0MiB|
|non-incremental/AUFNIRA/FFT/smtlib.653905.smt2                                             |  23.438s |2053.0MiB|
|non-incremental/AUFNIRA/FFT/z3.780093.smt2                                                 |  23.438s |2126.0MiB|
|non-incremental/AUFNIRA/FFT/smtlib.673324.smt2                                             |  23.425s |2287.0MiB|
|non-incremental/AUFNIRA/FFT/z3.774116.smt2                                                 |  23.417s |2160.0MiB|
|non-incremental/AUFNIRA/FFT/smtlib.946545.smt2                                             |  23.415s |2137.0MiB|
|non-incremental/AUFNIRA/FFT/smtlib.714922.smt2                                             |  23.414s |2507.0MiB|
|non-incremental/AUFNIRA/FFT/z3.636136.smt2                                                 |  23.402s |4400.0MiB|
|non-incremental/AUFNIRA/FFT/z3.621866.smt2                                                 |  23.379s |2979.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/AUFNIRA/FFT/smtlib.549916.smt2                                              |24.092MiB|24.092MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.560602.smt2                                              |1052.0MiB|1052.0MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.561727.smt2                                              |592.0MiB|592.0MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.562301.smt2                                              |3367.0MiB|3367.0MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.607667.smt2                                              |356.0MiB|356.0MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.612263.smt2                                              |828.0MiB|828.0MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.616911.smt2                                              |324.0MiB|324.0MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.620440.smt2                                              |29.532MiB|29.532MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.621785.smt2                                              |2295.0MiB|2295.0MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.622079.smt2                                              |32.336MiB|32.336MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.623344.smt2                                              |28.448MiB|28.448MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.624862.smt2                                              |20.324MiB|20.324MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.626115.smt2                                              |20.388MiB|20.388MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.627369.smt2                                              |28.808MiB|28.808MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.628941.smt2                                              |2913.0MiB|2913.0MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.629057.smt2                                              |20.12MiB|20.12MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.629149.smt2                                              |19.9MiB|19.9MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.629241.smt2                                              |20.284MiB|20.284MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.629331.smt2                                              |20.412MiB|20.412MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.629335.smt2                                              |20.112MiB|20.112MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/AUFNIRA/FFT/smtlib.549916.smt2                                              |24.092MiB|24.092MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.560602.smt2                                              |1052.0MiB|1052.0MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.561727.smt2                                              |592.0MiB|592.0MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.562301.smt2                                              |3367.0MiB|3367.0MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.607667.smt2                                              |356.0MiB|356.0MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.612263.smt2                                              |828.0MiB|828.0MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.616911.smt2                                              |324.0MiB|324.0MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.620440.smt2                                              |29.532MiB|29.532MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.621785.smt2                                              |2295.0MiB|2295.0MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.622079.smt2                                              |32.336MiB|32.336MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.623344.smt2                                              |28.448MiB|28.448MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.624862.smt2                                              |20.324MiB|20.324MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.626115.smt2                                              |20.388MiB|20.388MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.627369.smt2                                              |28.808MiB|28.808MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.628941.smt2                                              |2913.0MiB|2913.0MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.629057.smt2                                              |20.12MiB|20.12MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.629149.smt2                                              |19.9MiB|19.9MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.629241.smt2                                              |20.284MiB|20.284MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.629331.smt2                                              |20.412MiB|20.412MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.629335.smt2                                              |20.112MiB|20.112MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/AUFNIRA/FFT/smtlib.549916.smt2                                              |24.092MiB|24.092MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.560602.smt2                                              |1052.0MiB|1052.0MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.561727.smt2                                              |592.0MiB|592.0MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.562301.smt2                                              |3367.0MiB|3367.0MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.607667.smt2                                              |356.0MiB|356.0MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.612263.smt2                                              |828.0MiB|828.0MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.616911.smt2                                              |324.0MiB|324.0MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.620440.smt2                                              |29.532MiB|29.532MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.621785.smt2                                              |2295.0MiB|2295.0MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.622079.smt2                                              |32.336MiB|32.336MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.623344.smt2                                              |28.448MiB|28.448MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.624862.smt2                                              |20.324MiB|20.324MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.626115.smt2                                              |20.388MiB|20.388MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.627369.smt2                                              |28.808MiB|28.808MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.628941.smt2                                              |2913.0MiB|2913.0MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.629057.smt2                                              |20.12MiB|20.12MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.629149.smt2                                              |19.9MiB|19.9MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.629241.smt2                                              |20.284MiB|20.284MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.629331.smt2                                              |20.412MiB|20.412MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.629335.smt2                                              |20.112MiB|20.112MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/AUFNIRA/FFT/smtlib.549916.smt2                                              |24.092MiB|24.092MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.560602.smt2                                              |1052.0MiB|1052.0MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.561727.smt2                                              |592.0MiB|592.0MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.562301.smt2                                              |3367.0MiB|3367.0MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.607667.smt2                                              |356.0MiB|356.0MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.612263.smt2                                              |828.0MiB|828.0MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.616911.smt2                                              |324.0MiB|324.0MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.620440.smt2                                              |29.532MiB|29.532MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.621785.smt2                                              |2295.0MiB|2295.0MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.622079.smt2                                              |32.336MiB|32.336MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.623344.smt2                                              |28.448MiB|28.448MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.624862.smt2                                              |20.324MiB|20.324MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.626115.smt2                                              |20.388MiB|20.388MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.627369.smt2                                              |28.808MiB|28.808MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.628941.smt2                                              |2913.0MiB|2913.0MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.629057.smt2                                              |20.12MiB|20.12MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.629149.smt2                                              |19.9MiB|19.9MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.629241.smt2                                              |20.284MiB|20.284MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.629331.smt2                                              |20.412MiB|20.412MiB|0B| 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.629335.smt2                                              |20.112MiB|20.112MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/AUFNIRA/FFT/smtlib.633330.smt2                                             |  22.392s |4679.0MiB|
|non-incremental/AUFNIRA/aviation/return_why.smt2                                           |  22.551s |4592.0MiB|
|non-incremental/AUFNIRA/FFT/smtlib.712540.smt2                                             |  23.634s |4508.0MiB|
|non-incremental/AUFNIRA/FFT/z3.636136.smt2                                                 |  23.402s |4400.0MiB|
|non-incremental/AUFNIRA/FFT/z3.635953.smt2                                                 |  22.357s |4395.0MiB|
|non-incremental/AUFNIRA/FFT/z3.958311.smt2                                                 |  23.506s |4283.0MiB|
|non-incremental/AUFNIRA/FFT/z3.629976.smt2                                                 |  22.375s |4083.0MiB|
|non-incremental/AUFNIRA/FFT/smtlib.700022.smt2                                             |  23.172s |4081.0MiB|
|non-incremental/AUFNIRA/FFT/smtlib.673963.smt2                                             |  22.801s |4081.0MiB|
|non-incremental/AUFNIRA/FFT/z3.699496.smt2                                                 |  23.742s |3919.0MiB|
|non-incremental/AUFNIRA/FFT/z3.675244.smt2                                                 |  23.595s |3919.0MiB|
|non-incremental/AUFNIRA/FFT/z3.699441.smt2                                                 |  23.081s |3797.0MiB|
|non-incremental/AUFNIRA/FFT/z3.675189.smt2                                                 |  22.284s |3797.0MiB|
|non-incremental/AUFNIRA/FFT/smtlib.633611.smt2                                             |  22.294s |3786.0MiB|
|non-incremental/AUFNIRA/FFT/smtlib.647637.smt2                                             |  23.299s |3681.0MiB|
|non-incremental/AUFNIRA/aviation/axiomatic_why.smt2                                        |  22.148s |3559.0MiB|
|non-incremental/AUFNIRA/FFT/smtlib.562301.smt2                                             |  22.226s |3367.0MiB|
|non-incremental/AUFNIRA/FFT/z3.561997.smt2                                                 |  22.226s |3363.0MiB|
|non-incremental/AUFNIRA/FFT/z3.837770.smt2                                                 |  20.902s |3154.0MiB|
|non-incremental/AUFNIRA/FFT/smtlib.672054.smt2                                             |  22.021s |3096.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/AUFNIRA/FFT/smtlib.633330.smt2                                             |  22.392s |4679.0MiB|
|non-incremental/AUFNIRA/aviation/return_why.smt2                                           |  22.551s |4592.0MiB|
|non-incremental/AUFNIRA/FFT/smtlib.712540.smt2                                             |  23.634s |4508.0MiB|
|non-incremental/AUFNIRA/FFT/z3.636136.smt2                                                 |  23.402s |4400.0MiB|
|non-incremental/AUFNIRA/FFT/z3.635953.smt2                                                 |  22.357s |4395.0MiB|
|non-incremental/AUFNIRA/FFT/z3.958311.smt2                                                 |  23.506s |4283.0MiB|
|non-incremental/AUFNIRA/FFT/z3.629976.smt2                                                 |  22.375s |4083.0MiB|
|non-incremental/AUFNIRA/FFT/smtlib.700022.smt2                                             |  23.172s |4081.0MiB|
|non-incremental/AUFNIRA/FFT/smtlib.673963.smt2                                             |  22.801s |4081.0MiB|
|non-incremental/AUFNIRA/FFT/z3.699496.smt2                                                 |  23.742s |3919.0MiB|
|non-incremental/AUFNIRA/FFT/z3.675244.smt2                                                 |  23.595s |3919.0MiB|
|non-incremental/AUFNIRA/FFT/z3.699441.smt2                                                 |  23.081s |3797.0MiB|
|non-incremental/AUFNIRA/FFT/z3.675189.smt2                                                 |  22.284s |3797.0MiB|
|non-incremental/AUFNIRA/FFT/smtlib.633611.smt2                                             |  22.294s |3786.0MiB|
|non-incremental/AUFNIRA/FFT/smtlib.647637.smt2                                             |  23.299s |3681.0MiB|
|non-incremental/AUFNIRA/aviation/axiomatic_why.smt2                                        |  22.148s |3559.0MiB|
|non-incremental/AUFNIRA/FFT/smtlib.562301.smt2                                             |  22.226s |3367.0MiB|
|non-incremental/AUFNIRA/FFT/z3.561997.smt2                                                 |  22.226s |3363.0MiB|
|non-incremental/AUFNIRA/FFT/z3.837770.smt2                                                 |  20.902s |3154.0MiB|
|non-incremental/AUFNIRA/FFT/smtlib.672054.smt2                                             |  22.021s |3096.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/AUFNIRA/FFT/smtlib.549916.smt2                                              |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.560602.smt2                                              |  20.484s  |  20.484s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.561727.smt2                                              |  20.186s  |  20.186s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.562301.smt2                                              |  22.226s  |  22.226s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.607667.smt2                                              |  20.575s  |  20.575s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.612263.smt2                                              |  20.912s  |  20.912s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.616911.smt2                                              |  20.497s  |  20.497s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.620440.smt2                                              |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.621785.smt2                                              |  20.502s  |  20.502s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.622079.smt2                                              |   0.597s  |   0.597s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.623344.smt2                                              |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.624862.smt2                                              |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.626115.smt2                                              |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.627369.smt2                                              |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.628941.smt2                                              |  22.072s  |  22.072s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.629057.smt2                                              |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.629149.smt2                                              |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.629241.smt2                                              |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.629331.smt2                                              |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.629335.smt2                                              |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.629402.smt2                                              |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.630683.smt2                                              |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.632775.smt2                                              |  21.374s  |  21.374s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.633330.smt2                                              |  22.392s  |  22.392s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.633611.smt2                                              |  22.294s  |  22.294s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.635015.smt2                                              |  20.546s  |  20.546s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.635501.smt2                                              |  23.011s  |  23.011s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.635732.smt2                                              |  22.224s  |  22.224s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.635849.smt2                                              |  22.127s  |  22.127s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.637082.smt2                                              |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.637239.smt2                                              |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.637372.smt2                                              |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.637378.smt2                                              |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.637413.smt2                                              |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.638801.smt2                                              |  21.858s  |  21.858s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.638953.smt2                                              |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.640322.smt2                                              |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.644770.smt2                                              |  23.303s  |  23.303s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.645472.smt2                                              |  20.467s  |  20.467s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.645715.smt2                                              |  21.974s  |  21.974s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.645857.smt2                                              |  23.210s  |  23.210s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.647018.smt2                                              |  22.204s  |  22.204s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.647483.smt2                                              |  22.126s  |  22.126s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.647637.smt2                                              |  23.299s  |  23.299s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.647696.smt2                                              |  21.032s  |  21.032s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.652843.smt2                                              |  22.537s  |  22.537s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.653587.smt2                                              |  23.162s  |  23.162s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.653905.smt2                                              |  23.438s  |  23.438s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.654080.smt2                                              |  21.951s  |  21.951s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.656050.smt2                                              |  20.268s  |  20.268s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.657075.smt2                                              |  22.059s  |  22.059s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.659078.smt2                                              |  22.177s  |  22.177s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.659604.smt2                                              |  21.702s  |  21.702s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.659901.smt2                                              |  22.856s  |  22.856s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.660068.smt2                                              |  22.144s  |  22.144s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.661260.smt2                                              |  20.421s  |  20.421s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.661781.smt2                                              |  21.788s  |  21.788s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.662069.smt2                                              |  22.159s  |  22.159s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.662227.smt2                                              |  22.108s  |  22.108s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.664248.smt2                                              |  22.566s  |  22.566s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.665247.smt2                                              |  22.642s  |  22.642s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.665768.smt2                                              |  22.778s  |  22.778s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.670862.smt2                                              |  22.131s  |  22.131s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.671569.smt2                                              |  22.025s  |  22.025s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.671895.smt2                                              |  23.042s  |  23.042s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.672054.smt2                                              |  22.021s  |  22.021s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.673324.smt2                                              |  23.425s  |  23.425s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.673963.smt2                                              |  22.801s  |  22.801s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.674024.smt2                                              |  22.992s  |  22.992s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.674037.smt2                                              |   1.786s  |   1.786s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.675941.smt2                                              |  21.667s  |  21.667s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.681188.smt2                                              |  20.865s  |  20.865s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.682065.smt2                                              |  22.027s  |  22.027s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.688983.smt2                                              |   0.861s  |   0.861s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.696888.smt2                                              |  22.252s  |  22.252s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.697550.smt2                                              |  22.940s  |  22.940s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.697961.smt2                                              |  22.737s  |  22.737s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.698113.smt2                                              |  23.604s  |  23.604s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.699383.smt2                                              |  23.033s  |  23.033s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.700022.smt2                                              |  23.172s  |  23.172s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.700083.smt2                                              |  22.649s  |  22.649s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.700096.smt2                                              |   1.668s  |   1.668s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.701996.smt2                                              |  22.267s  |  22.267s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.707123.smt2                                              |  20.941s  |  20.941s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.710024.smt2                                              |   0.226s  |   0.226s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.711486.smt2                                              |  20.420s  |  20.420s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.712193.smt2                                              |  22.120s  |  22.120s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.712540.smt2                                              |  23.634s  |  23.634s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.714183.smt2                                              |  21.505s  |  21.505s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.714922.smt2                                              |  23.414s  |  23.414s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.742487.smt2                                              |  22.730s  |  22.730s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.743633.smt2                                              |  21.963s  |  21.963s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.746428.smt2                                              |  22.256s  |  22.256s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.747589.smt2                                              |  21.946s  |  21.946s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.750595.smt2                                              |  21.769s  |  21.769s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.751753.smt2                                              |  21.987s  |  21.987s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.754911.smt2                                              |  23.116s  |  23.116s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.756005.smt2                                              |  21.984s  |  21.984s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.759134.smt2                                              |  23.313s  |  23.313s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.760228.smt2                                              |  23.271s  |  23.271s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.763357.smt2                                              |  23.335s  |  23.335s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.764451.smt2                                              |  20.738s  |  20.738s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.767580.smt2                                              |  21.837s  |  21.837s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.768674.smt2                                              |  22.004s  |  22.004s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.772111.smt2                                              |  21.998s  |  21.998s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.776019.smt2                                              |  22.469s  |  22.469s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.777173.smt2                                              |  22.837s  |  22.837s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.780306.smt2                                              |  21.731s  |  21.731s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.781509.smt2                                              |  22.313s  |  22.313s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.784698.smt2                                              |  21.813s  |  21.813s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.785903.smt2                                              |  22.588s  |  22.588s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.788836.smt2                                              |  20.684s  |  20.684s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.789955.smt2                                              |  23.005s  |  23.005s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.792971.smt2                                              |  22.269s  |  22.269s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.794151.smt2                                              |  23.317s  |  23.317s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.797178.smt2                                              |  21.521s  |  21.521s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.798358.smt2                                              |  23.048s  |  23.048s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.801385.smt2                                              |  21.979s  |  21.979s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.802565.smt2                                              |  23.078s  |  23.078s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.805592.smt2                                              |  21.392s  |  21.392s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.806772.smt2                                              |  22.850s  |  22.850s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.809799.smt2                                              |  20.346s  |  20.346s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.810979.smt2                                              |  20.448s  |  20.448s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.813971.smt2                                              |  21.110s  |  21.110s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.817734.smt2                                              |  22.135s  |  22.135s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.818913.smt2                                              |  20.477s  |  20.477s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.821891.smt2                                              |  20.775s  |  20.775s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.822925.smt2                                              |  21.322s  |  21.322s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.823496.smt2                                              |  23.314s  |  23.314s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.825782.smt2                                              |  21.880s  |  21.880s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.826803.smt2                                              |  22.056s  |  22.056s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.827387.smt2                                              |  23.011s  |  23.011s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.829638.smt2                                              |  21.952s  |  21.952s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.830659.smt2                                              |  21.972s  |  21.972s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.831243.smt2                                              |  21.716s  |  21.716s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.833494.smt2                                              |  23.240s  |  23.240s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.834515.smt2                                              |  22.918s  |  22.918s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.835099.smt2                                              |  21.124s  |  21.124s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.837455.smt2                                              |  22.346s  |  22.346s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.838638.smt2                                              |  21.194s  |  21.194s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.845302.smt2                                              |  22.830s  |  22.830s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.846296.smt2                                              |  23.143s  |  23.143s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.849348.smt2                                              |  20.334s  |  20.334s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.850480.smt2                                              |  21.846s  |  21.846s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.853506.smt2                                              |  20.975s  |  20.975s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.854640.smt2                                              |  21.401s  |  21.401s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.857393.smt2                                              |  22.281s  |  22.281s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.858350.smt2                                              |  21.676s  |  21.676s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.858887.smt2                                              |  22.212s  |  22.212s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.860981.smt2                                              |  22.654s  |  22.654s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.861982.smt2                                              |  23.360s  |  23.360s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.864863.smt2                                              |  21.580s  |  21.580s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.865953.smt2                                              |  22.636s  |  22.636s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.868836.smt2                                              |  22.103s  |  22.103s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.869906.smt2                                              |  21.889s  |  21.889s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.872800.smt2                                              |  21.785s  |  21.785s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.873870.smt2                                              |  22.303s  |  22.303s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.876764.smt2                                              |  21.179s  |  21.179s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.877834.smt2                                              |  21.043s  |  21.043s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.880728.smt2                                              |  22.067s  |  22.067s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.881798.smt2                                              |  22.382s  |  22.382s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.908174.smt2                                              |  20.179s  |  20.179s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.912497.smt2                                              |  20.576s  |  20.576s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.916820.smt2                                              |  20.321s  |  20.321s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.921143.smt2                                              |  20.177s  |  20.177s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.925543.smt2                                              |  23.327s  |  23.327s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.929723.smt2                                              |  22.174s  |  22.174s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.933524.smt2                                              |  23.700s  |  23.700s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.938740.smt2                                              |  23.137s  |  23.137s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.939774.smt2                                              |  23.256s  |  23.256s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.940318.smt2                                              |  22.856s  |  22.856s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.940561.smt2                                              |  20.637s  |  20.637s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.942602.smt2                                              |  21.049s  |  21.049s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.943691.smt2                                              |  22.045s  |  22.045s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.944272.smt2                                              |  20.765s  |  20.765s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.946545.smt2                                              |  23.415s  |  23.415s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.950232.smt2                                              |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.954058.smt2                                              |  20.186s  |  20.186s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.955132.smt2                                              |  20.315s  |  20.315s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/smtlib.958319.smt2                                              |  21.783s  |  21.783s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.549864.smt2                                                  |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.560298.smt2                                                  |  20.294s  |  20.294s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.561423.smt2                                                  |  20.254s  |  20.254s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.561997.smt2                                                  |  22.226s  |  22.226s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.607838.smt2                                                  |  21.324s  |  21.324s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.609085.smt2                                                  |  20.234s  |  20.234s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.609741.smt2                                                  |  21.379s  |  21.379s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.610121.smt2                                                  |  20.154s  |  20.154s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.612465.smt2                                                  |  23.002s  |  23.002s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.613729.smt2                                                  |  20.496s  |  20.496s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.614416.smt2                                                  |  20.786s  |  20.786s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.614780.smt2                                                  |  20.332s  |  20.332s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.617112.smt2                                                  |  22.259s  |  22.259s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.618374.smt2                                                  |  20.887s  |  20.887s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.619057.smt2                                                  |  20.552s  |  20.552s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.619415.smt2                                                  |  21.400s  |  21.400s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.620661.smt2                                                  |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.621866.smt2                                                  |  23.379s  |  23.379s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.622405.smt2                                                  |   2.702s  |   2.702s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.622683.smt2                                                  |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.624507.smt2                                                  |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.625933.smt2                                                  |   0.169s  |   0.169s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.627094.smt2                                                  |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.628546.smt2                                                  |   0.174s  |   0.174s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.629976.smt2                                                  |  22.375s  |  22.375s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.630048.smt2                                                  |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.631366.smt2                                                  |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.633492.smt2                                                  |  20.395s  |  20.395s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.633926.smt2                                                  |  23.055s  |  23.055s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.634134.smt2                                                  |  23.141s  |  23.141s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.634210.smt2                                                  |  20.499s  |  20.499s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.634248.smt2                                                  |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.634265.smt2                                                  |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.635554.smt2                                                  |  21.251s  |  21.251s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.635953.smt2                                                  |  22.357s  |  22.357s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.636136.smt2                                                  |  23.402s  |  23.402s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.636226.smt2                                                  |  21.792s  |  21.792s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.637557.smt2                                                  |  16.639s  |  16.639s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.638004.smt2                                                  |   4.001s  |   4.001s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.638194.smt2                                                  |  20.640s  |  20.640s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.638333.smt2                                                  |  23.564s  |  23.564s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.639724.smt2                                                  |  15.795s  |  15.795s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.640149.smt2                                                  |   7.683s  |   7.683s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.640330.smt2                                                  |  23.138s  |  23.138s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.640466.smt2                                                  |  22.965s  |  22.965s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.641708.smt2                                                  |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.646409.smt2                                                  |  22.324s  |  22.324s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.647039.smt2                                                  |  20.482s  |  20.482s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.647252.smt2                                                  |  21.901s  |  21.901s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.647389.smt2                                                  |  23.104s  |  23.104s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.648629.smt2                                                  |  20.275s  |  20.275s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.649061.smt2                                                  |  22.398s  |  22.398s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.649261.smt2                                                  |  23.260s  |  23.260s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.649332.smt2                                                  |  20.675s  |  20.675s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.654657.smt2                                                  |  20.932s  |  20.932s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.655425.smt2                                                  |  23.100s  |  23.100s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.655748.smt2                                                  |  21.929s  |  21.929s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.655977.smt2                                                  |  21.628s  |  21.628s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.658206.smt2                                                  |  22.991s  |  22.991s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.659235.smt2                                                  |  23.099s  |  23.099s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.659732.smt2                                                  |  22.430s  |  22.430s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.659996.smt2                                                  |  20.718s  |  20.718s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.661347.smt2                                                  |  21.662s  |  21.662s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.661728.smt2                                                  |  22.349s  |  22.349s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.661907.smt2                                                  |  23.027s  |  23.027s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.661994.smt2                                                  |  22.134s  |  22.134s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.663327.smt2                                                  |  21.849s  |  21.849s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.663700.smt2                                                  |  22.686s  |  22.686s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.663869.smt2                                                  |  22.130s  |  22.130s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.663953.smt2                                                  |  22.135s  |  22.135s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.666124.smt2                                                  |  21.170s  |  21.170s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.667166.smt2                                                  |  21.612s  |  21.612s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.667685.smt2                                                  |  21.174s  |  21.174s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.667943.smt2                                                  |  20.788s  |  20.788s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.669565.smt2                                                  |  21.459s  |  21.459s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.672518.smt2                                                  |  20.386s  |  20.386s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.673103.smt2                                                  |  22.983s  |  22.983s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.673310.smt2                                                  |  23.100s  |  23.100s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.673421.smt2                                                  |  22.484s  |  22.484s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.674628.smt2                                                  |  21.750s  |  21.750s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.675189.smt2                                                  |  22.284s  |  22.284s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.675244.smt2                                                  |  23.595s  |  23.595s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.675263.smt2                                                  |  20.076s  |  20.076s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.676882.smt2                                                  |   0.225s  |   0.225s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.677614.smt2                                                  |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.677987.smt2                                                  |  21.813s  |  21.813s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.678148.smt2                                                  |  23.067s  |  23.067s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.682088.smt2                                                  |  20.902s  |  20.902s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.682948.smt2                                                  |  20.625s  |  20.625s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.683368.smt2                                                  |  23.203s  |  23.203s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.684910.smt2                                                  |  20.347s  |  20.347s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.685296.smt2                                                  |  21.629s  |  21.629s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.685476.smt2                                                  |  22.921s  |  22.921s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.686904.smt2                                                  |  21.335s  |  21.335s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.687278.smt2                                                  |  22.728s  |  22.728s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.687448.smt2                                                  |  21.917s  |  21.917s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.689469.smt2                                                  |   1.100s  |   1.100s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.691631.smt2                                                  |  20.514s  |  20.514s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.692368.smt2                                                  |  23.514s  |  23.514s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.692734.smt2                                                  |  22.307s  |  22.307s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.692863.smt2                                                  |  20.492s  |  20.492s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.694291.smt2                                                  |  22.614s  |  22.614s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.695009.smt2                                                  |  22.394s  |  22.394s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.695337.smt2                                                  |  22.861s  |  22.861s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.695462.smt2                                                  |  23.259s  |  23.259s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.696723.smt2                                                  |  21.409s  |  21.409s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.697344.smt2                                                  |  21.589s  |  21.589s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.697561.smt2                                                  |  22.813s  |  22.813s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.697673.smt2                                                  |  23.227s  |  23.227s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.698880.smt2                                                  |  22.292s  |  22.292s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.699441.smt2                                                  |  23.081s  |  23.081s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.699496.smt2                                                  |  23.742s  |  23.742s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.699515.smt2                                                  |  20.066s  |  20.066s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.701134.smt2                                                  |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.701866.smt2                                                  |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.702239.smt2                                                  |  21.391s  |  21.391s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.702400.smt2                                                  |  23.378s  |  23.378s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.706191.smt2                                                  |  22.021s  |  22.021s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.706995.smt2                                                  |  20.309s  |  20.309s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.709094.smt2                                                  |   0.242s  |   0.242s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.710520.smt2                                                  |  23.450s  |  23.450s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.711170.smt2                                                  |  22.709s  |  22.709s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.711517.smt2                                                  |  21.695s  |  21.695s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.711639.smt2                                                  |  22.345s  |  22.345s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.713145.smt2                                                  |  22.741s  |  22.741s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.713843.smt2                                                  |  23.056s  |  23.056s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.714184.smt2                                                  |  21.682s  |  21.682s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.714299.smt2                                                  |  20.096s  |  20.096s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.740747.smt2                                                  |  23.001s  |  23.001s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.744873.smt2                                                  |  20.387s  |  20.387s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.746010.smt2                                                  |  22.076s  |  22.076s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.746656.smt2                                                  |  21.455s  |  21.455s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.747041.smt2                                                  |  22.430s  |  22.430s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.749181.smt2                                                  |  21.895s  |  21.895s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.750318.smt2                                                  |  22.525s  |  22.525s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.750959.smt2                                                  |  23.183s  |  23.183s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.751341.smt2                                                  |  22.754s  |  22.754s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.753349.smt2                                                  |  21.751s  |  21.751s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.754420.smt2                                                  |  21.295s  |  21.295s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.755062.smt2                                                  |  22.059s  |  22.059s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.755420.smt2                                                  |  21.653s  |  21.653s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.757428.smt2                                                  |  22.773s  |  22.773s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.758499.smt2                                                  |  22.423s  |  22.423s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.759141.smt2                                                  |  21.651s  |  21.651s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.759499.smt2                                                  |  21.770s  |  21.770s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.761507.smt2                                                  |  21.602s  |  21.602s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.762578.smt2                                                  |  22.978s  |  22.978s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.763220.smt2                                                  |  22.118s  |  22.118s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.763578.smt2                                                  |  21.737s  |  21.737s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.765586.smt2                                                  |  22.875s  |  22.875s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.766657.smt2                                                  |  20.360s  |  20.360s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.767299.smt2                                                  |  22.379s  |  22.379s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.767657.smt2                                                  |  22.218s  |  22.218s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.770035.smt2                                                  |  22.739s  |  22.739s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.774116.smt2                                                  |  23.417s  |  23.417s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.775261.smt2                                                  |  22.389s  |  22.389s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.775888.smt2                                                  |  22.875s  |  22.875s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.776249.smt2                                                  |  22.410s  |  22.410s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.778229.smt2                                                  |  22.018s  |  22.018s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.779430.smt2                                                  |  21.909s  |  21.909s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.780093.smt2                                                  |  23.438s  |  23.438s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.780480.smt2                                                  |  22.451s  |  22.451s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.782459.smt2                                                  |  21.201s  |  21.201s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.783662.smt2                                                  |  21.462s  |  21.462s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.784327.smt2                                                  |  20.538s  |  20.538s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.784716.smt2                                                  |  20.446s  |  20.446s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.786512.smt2                                                  |  22.267s  |  22.267s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.787622.smt2                                                  |  22.934s  |  22.934s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.788234.smt2                                                  |  22.713s  |  22.713s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.788577.smt2                                                  |  22.573s  |  22.573s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.790700.smt2                                                  |  20.556s  |  20.556s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.791875.smt2                                                  |  22.139s  |  22.139s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.792511.smt2                                                  |  22.069s  |  22.069s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.792845.smt2                                                  |  20.436s  |  20.436s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.794968.smt2                                                  |  20.586s  |  20.586s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.796143.smt2                                                  |  21.850s  |  21.850s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.796779.smt2                                                  |  21.620s  |  21.620s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.797113.smt2                                                  |  21.534s  |  21.534s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.799236.smt2                                                  |  22.136s  |  22.136s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.800411.smt2                                                  |  22.411s  |  22.411s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.801047.smt2                                                  |  22.008s  |  22.008s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.801381.smt2                                                  |  21.378s  |  21.378s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.803504.smt2                                                  |  22.249s  |  22.249s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.804679.smt2                                                  |  23.090s  |  23.090s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.805315.smt2                                                  |  22.962s  |  22.962s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.805649.smt2                                                  |  20.472s  |  20.472s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.807772.smt2                                                  |  22.092s  |  22.092s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.808947.smt2                                                  |  23.364s  |  23.364s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.809583.smt2                                                  |  22.875s  |  22.875s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.809917.smt2                                                  |  22.267s  |  22.267s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.811946.smt2                                                  |  20.782s  |  20.782s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.815818.smt2                                                  |  22.091s  |  22.091s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.816994.smt2                                                  |  23.579s  |  23.579s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.817643.smt2                                                  |  23.453s  |  23.453s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.818028.smt2                                                  |  22.338s  |  22.338s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.820023.smt2                                                  |  21.760s  |  21.760s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.821053.smt2                                                  |  22.010s  |  22.010s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.821634.smt2                                                  |  22.720s  |  22.720s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.821986.smt2                                                  |  22.367s  |  22.367s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.823996.smt2                                                  |  21.146s  |  21.146s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.825014.smt2                                                  |  22.161s  |  22.161s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.825598.smt2                                                  |  21.353s  |  21.353s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.825916.smt2                                                  |  20.768s  |  20.768s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.827926.smt2                                                  |  21.876s  |  21.876s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.828944.smt2                                                  |  22.019s  |  22.019s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.829528.smt2                                                  |  21.922s  |  21.922s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.829846.smt2                                                  |  20.266s  |  20.266s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.831856.smt2                                                  |  22.401s  |  22.401s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.832874.smt2                                                  |  22.650s  |  22.650s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.833458.smt2                                                  |  22.095s  |  22.095s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.833776.smt2                                                  |  21.426s  |  21.426s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.835930.smt2                                                  |  20.376s  |  20.376s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.837129.smt2                                                  |  21.894s  |  21.894s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.837770.smt2                                                  |  20.902s  |  20.902s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.838140.smt2                                                  |  22.094s  |  22.094s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.843953.smt2                                                  |  22.025s  |  22.025s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.844945.smt2                                                  |  22.078s  |  22.078s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.845575.smt2                                                  |  23.022s  |  23.022s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.845939.smt2                                                  |  23.139s  |  23.139s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.848054.smt2                                                  |  20.475s  |  20.475s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.849188.smt2                                                  |  21.434s  |  21.434s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.852276.smt2                                                  |  21.371s  |  21.371s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.853412.smt2                                                  |  21.156s  |  21.156s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.856156.smt2                                                  |  20.683s  |  20.683s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.857109.smt2                                                  |  20.610s  |  20.610s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.857642.smt2                                                  |  23.001s  |  23.001s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.857918.smt2                                                  |  22.083s  |  22.083s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.859684.smt2                                                  |  20.726s  |  20.726s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.860677.smt2                                                  |  20.750s  |  20.750s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.861289.smt2                                                  |  22.814s  |  22.814s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.861632.smt2                                                  |  21.753s  |  21.753s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.863623.smt2                                                  |  23.151s  |  23.151s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.864684.smt2                                                  |  22.278s  |  22.278s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.865313.smt2                                                  |  22.057s  |  22.057s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.865646.smt2                                                  |  22.097s  |  22.097s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.867637.smt2                                                  |  23.366s  |  23.366s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.868686.smt2                                                  |  20.677s  |  20.677s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.869313.smt2                                                  |  20.924s  |  20.924s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.869659.smt2                                                  |  21.831s  |  21.831s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.871650.smt2                                                  |  22.773s  |  22.773s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.872699.smt2                                                  |  22.574s  |  22.574s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.873326.smt2                                                  |  22.494s  |  22.494s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.873672.smt2                                                  |  20.564s  |  20.564s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.875663.smt2                                                  |  22.283s  |  22.283s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.876712.smt2                                                  |  22.468s  |  22.468s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.877339.smt2                                                  |  21.794s  |  21.794s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.877685.smt2                                                  |  22.116s  |  22.116s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.879676.smt2                                                  |  22.739s  |  22.739s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.880725.smt2                                                  |  22.226s  |  22.226s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.881352.smt2                                                  |  20.534s  |  20.534s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.881698.smt2                                                  |  22.574s  |  22.574s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.908122.smt2                                                  |  21.801s  |  21.801s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.909292.smt2                                                  |  22.790s  |  22.790s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.909956.smt2                                                  |  22.225s  |  22.225s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.910312.smt2                                                  |  22.765s  |  22.765s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.912508.smt2                                                  |  21.670s  |  21.670s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.913678.smt2                                                  |  23.343s  |  23.343s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.914342.smt2                                                  |  23.128s  |  23.128s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.914698.smt2                                                  |  22.406s  |  22.406s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.916894.smt2                                                  |  21.439s  |  21.439s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.918064.smt2                                                  |  23.305s  |  23.305s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.918728.smt2                                                  |  23.458s  |  23.458s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.919084.smt2                                                  |  21.837s  |  21.837s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.921280.smt2                                                  |  22.068s  |  22.068s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.922450.smt2                                                  |  22.802s  |  22.802s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.923114.smt2                                                  |  22.987s  |  22.987s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.923470.smt2                                                  |  22.777s  |  22.777s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.925667.smt2                                                  |  22.615s  |  22.615s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.926856.smt2                                                  |  23.298s  |  23.298s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.929857.smt2                                                  |  20.571s  |  20.571s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.933657.smt2                                                  |  21.894s  |  21.894s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.938815.smt2                                                  |  20.581s  |  20.581s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.939846.smt2                                                  |  23.347s  |  23.347s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.940390.smt2                                                  |  21.834s  |  21.834s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.940633.smt2                                                  |  22.138s  |  22.138s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.942623.smt2                                                  |  20.162s  |  20.162s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.943708.smt2                                                  |  22.103s  |  22.103s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.944289.smt2                                                  |  21.675s  |  21.675s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.944599.smt2                                                  |  22.073s  |  22.073s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.946559.smt2                                                  |  20.994s  |  20.994s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.947491.smt2                                                  |  20.734s  |  20.734s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.950199.smt2                                                  |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.951208.smt2                                                  |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.951712.smt2                                                  |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.951967.smt2                                                  |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.954082.smt2                                                  |  20.302s  |  20.302s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.955145.smt2                                                  |  21.184s  |  21.184s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.955746.smt2                                                  |  21.611s  |  21.611s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.956070.smt2                                                  |  22.929s  |  22.929s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/FFT/z3.958311.smt2                                                  |  23.506s  |  23.506s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/aviation/array_double_why.smt2                                      |  20.555s  |  20.555s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/aviation/axiomatic_why.smt2                                         |  22.148s  |  22.148s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/aviation/bts0063_why.smt2                                           |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/aviation/bts0071_why.smt2                                           |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/aviation/bts0073_why.smt2                                           |  22.038s  |  22.038s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/aviation/bts0187_why.smt2                                           |  22.006s  |  22.006s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/aviation/bts0199_why.smt2                                           |  21.794s  |  21.794s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/aviation/bts5878_why.smt2                                           |  22.018s  |  22.018s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/aviation/bts6364_why.smt2                                           |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/aviation/bts6453_why.smt2                                           |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/aviation/bug390_why.smt2                                            |  22.166s  |  22.166s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/aviation/clash_alloc_why.smt2                                       |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/aviation/conflict_why.smt2                                          |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/aviation/consts_why.smt2                                            |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/aviation/extern_why.smt2                                            |  21.824s  |  21.824s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/aviation/false2_why.smt2                                            |  21.529s  |  21.529s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/aviation/fs252_why.smt2                                             |  22.048s  |  22.048s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/aviation/jeannin_why.smt2                                           |  22.101s  |  22.101s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/aviation/minusminus_why.smt2                                        |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/aviation/quantified_pointer_why.smt2                                |  22.268s  |  22.268s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/aviation/return_why.smt2                                            |  22.551s  |  22.551s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/cl5_nebula_norm_0003.fof.smt2                     |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/cl5_nebula_norm_0004.fof.smt2                     |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/cl5_nebula_norm_0005.fof.smt2                     |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/cl5_nebula_norm_0006.fof.smt2                     |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/cl5_nebula_norm_0007.fof.smt2                     |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/cl5_nebula_norm_0008.fof.smt2                     |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/cl5_nebula_norm_0009.fof.smt2                     |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/cl5_nebula_norm_0010.fof.smt2                     |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/cl5_nebula_norm_0013.fof.smt2                     |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/cl5_nebula_norm_0014.fof.smt2                     |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0001.fof.smt2                 |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0002.fof.smt2                 |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0003.fof.smt2                 |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0004.fof.smt2                 |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0005.fof.smt2                 |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0006.fof.smt2                 |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0007.fof.smt2                 |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0008.fof.smt2                 |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0009.fof.smt2                 |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0010.fof.smt2                 |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0011.fof.smt2                 |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0012.fof.smt2                 |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0013.fof.smt2                 |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0014.fof.smt2                 |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0015.fof.smt2                 |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0016.fof.smt2                 |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0017.fof.smt2                 |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0018.fof.smt2                 |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0019.fof.smt2                 |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0020.fof.smt2                 |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0021.fof.smt2                 |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0022.fof.smt2                 |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0023.fof.smt2                 |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0024.fof.smt2                 |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0025.fof.smt2                 |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0026.fof.smt2                 |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0027.fof.smt2                 |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0028.fof.smt2                 |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0029.fof.smt2                 |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0030.fof.smt2                 |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0031.fof.smt2                 |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0032.fof.smt2                 |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0033.fof.smt2                 |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0034.fof.smt2                 |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0035.fof.smt2                 |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0036.fof.smt2                 |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0037.fof.smt2                 |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0038.fof.smt2                 |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0039.fof.smt2                 |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0040.fof.smt2                 |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0041.fof.smt2                 |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0042.fof.smt2                 |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0043.fof.smt2                 |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0044.fof.smt2                 |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0045.fof.smt2                 |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0046.fof.smt2                 |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0047.fof.smt2                 |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0048.fof.smt2                 |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0049.fof.smt2                 |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0050.fof.smt2                 |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0051.fof.smt2                 |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0052.fof.smt2                 |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0053.fof.smt2                 |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0054.fof.smt2                 |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0055.fof.smt2                 |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0056.fof.smt2                 |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0057.fof.smt2                 |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0058.fof.smt2                 |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0059.fof.smt2                 |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0060.fof.smt2                 |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0061.fof.smt2                 |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0062.fof.smt2                 |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0063.fof.smt2                 |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0064.fof.smt2                 |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0065.fof.smt2                 |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0066.fof.smt2                 |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0067.fof.smt2                 |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0068.fof.smt2                 |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0069.fof.smt2                 |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0070.fof.smt2                 |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0071.fof.smt2                 |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0072.fof.smt2                 |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0073.fof.smt2                 |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0074.fof.smt2                 |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0075.fof.smt2                 |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0076.fof.smt2                 |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0077.fof.smt2                 |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0078.fof.smt2                 |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0079.fof.smt2                 |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0080.fof.smt2                 |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0081.fof.smt2                 |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0082.fof.smt2                 |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0083.fof.smt2                 |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0084.fof.smt2                 |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0085.fof.smt2                 |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0086.fof.smt2                 |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0087.fof.smt2                 |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0088.fof.smt2                 |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0089.fof.smt2                 |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0090.fof.smt2                 |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0091.fof.smt2                 |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0092.fof.smt2                 |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0093.fof.smt2                 |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0094.fof.smt2                 |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0095.fof.smt2                 |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0096.fof.smt2                 |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0097.fof.smt2                 |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0098.fof.smt2                 |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0099.fof.smt2                 |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0100.fof.smt2                 |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0101.fof.smt2                 |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0102.fof.smt2                 |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0103.fof.smt2                 |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0104.fof.smt2                 |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0105.fof.smt2                 |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0106.fof.smt2                 |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0107.fof.smt2                 |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0108.fof.smt2                 |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0109.fof.smt2                 |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0110.fof.smt2                 |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0111.fof.smt2                 |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0112.fof.smt2                 |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0113.fof.smt2                 |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0114.fof.smt2                 |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0115.fof.smt2                 |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0116.fof.smt2                 |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0117.fof.smt2                 |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0118.fof.smt2                 |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0119.fof.smt2                 |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0120.fof.smt2                 |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0121.fof.smt2                 |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0122.fof.smt2                 |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0123.fof.smt2                 |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0124.fof.smt2                 |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0125.fof.smt2                 |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0126.fof.smt2                 |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0127.fof.smt2                 |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0128.fof.smt2                 |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0129.fof.smt2                 |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0130.fof.smt2                 |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0131.fof.smt2                 |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0132.fof.smt2                 |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0133.fof.smt2                 |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0134.fof.smt2                 |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0135.fof.smt2                 |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0136.fof.smt2                 |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0137.fof.smt2                 |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0138.fof.smt2                 |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0139.fof.smt2                 |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0140.fof.smt2                 |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0141.fof.smt2                 |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0142.fof.smt2                 |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0143.fof.smt2                 |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0144.fof.smt2                 |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0145.fof.smt2                 |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0146.fof.smt2                 |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0147.fof.smt2                 |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0148.fof.smt2                 |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0149.fof.smt2                 |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0150.fof.smt2                 |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0151.fof.smt2                 |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0152.fof.smt2                 |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0153.fof.smt2                 |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0154.fof.smt2                 |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0155.fof.smt2                 |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0156.fof.smt2                 |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0157.fof.smt2                 |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0158.fof.smt2                 |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0159.fof.smt2                 |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0160.fof.smt2                 |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0161.fof.smt2                 |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0162.fof.smt2                 |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0163.fof.smt2                 |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0164.fof.smt2                 |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0165.fof.smt2                 |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0166.fof.smt2                 |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0167.fof.smt2                 |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0168.fof.smt2                 |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0169.fof.smt2                 |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0170.fof.smt2                 |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0171.fof.smt2                 |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0172.fof.smt2                 |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0173.fof.smt2                 |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0174.fof.smt2                 |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0175.fof.smt2                 |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0176.fof.smt2                 |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0177.fof.smt2                 |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0178.fof.smt2                 |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0179.fof.smt2                 |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0180.fof.smt2                 |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0181.fof.smt2                 |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0182.fof.smt2                 |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0183.fof.smt2                 |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0184.fof.smt2                 |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0185.fof.smt2                 |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0186.fof.smt2                 |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0187.fof.smt2                 |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0188.fof.smt2                 |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0189.fof.smt2                 |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0190.fof.smt2                 |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0191.fof.smt2                 |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0192.fof.smt2                 |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0193.fof.smt2                 |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0194.fof.smt2                 |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0195.fof.smt2                 |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0196.fof.smt2                 |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0197.fof.smt2                 |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0198.fof.smt2                 |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0199.fof.smt2                 |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0200.fof.smt2                 |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0201.fof.smt2                 |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0202.fof.smt2                 |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0203.fof.smt2                 |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0204.fof.smt2                 |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0205.fof.smt2                 |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0206.fof.smt2                 |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0207.fof.smt2                 |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0208.fof.smt2                 |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0209.fof.smt2                 |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0210.fof.smt2                 |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0211.fof.smt2                 |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0212.fof.smt2                 |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0213.fof.smt2                 |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0214.fof.smt2                 |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0215.fof.smt2                 |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0216.fof.smt2                 |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0217.fof.smt2                 |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0218.fof.smt2                 |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0219.fof.smt2                 |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0220.fof.smt2                 |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0221.fof.smt2                 |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0222.fof.smt2                 |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0223.fof.smt2                 |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0224.fof.smt2                 |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0225.fof.smt2                 |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0226.fof.smt2                 |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0227.fof.smt2                 |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0228.fof.smt2                 |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0229.fof.smt2                 |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0230.fof.smt2                 |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0231.fof.smt2                 |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0232.fof.smt2                 |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0233.fof.smt2                 |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0234.fof.smt2                 |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0235.fof.smt2                 |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0236.fof.smt2                 |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0237.fof.smt2                 |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0238.fof.smt2                 |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0239.fof.smt2                 |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0240.fof.smt2                 |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0241.fof.smt2                 |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0242.fof.smt2                 |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0243.fof.smt2                 |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0244.fof.smt2                 |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0245.fof.smt2                 |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0246.fof.smt2                 |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0247.fof.smt2                 |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0248.fof.smt2                 |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0249.fof.smt2                 |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0250.fof.smt2                 |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0251.fof.smt2                 |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0252.fof.smt2                 |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0253.fof.smt2                 |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0254.fof.smt2                 |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0255.fof.smt2                 |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0256.fof.smt2                 |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0257.fof.smt2                 |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0258.fof.smt2                 |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0259.fof.smt2                 |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0260.fof.smt2                 |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0261.fof.smt2                 |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0262.fof.smt2                 |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0263.fof.smt2                 |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0264.fof.smt2                 |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0265.fof.smt2                 |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0266.fof.smt2                 |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0267.fof.smt2                 |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0268.fof.smt2                 |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0269.fof.smt2                 |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0270.fof.smt2                 |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0271.fof.smt2                 |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0272.fof.smt2                 |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0273.fof.smt2                 |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0274.fof.smt2                 |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0275.fof.smt2                 |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0276.fof.smt2                 |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0277.fof.smt2                 |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0278.fof.smt2                 |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0279.fof.smt2                 |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0280.fof.smt2                 |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0281.fof.smt2                 |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0282.fof.smt2                 |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0283.fof.smt2                 |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0284.fof.smt2                 |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0285.fof.smt2                 |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0286.fof.smt2                 |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0287.fof.smt2                 |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0288.fof.smt2                 |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0289.fof.smt2                 |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0290.fof.smt2                 |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0291.fof.smt2                 |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0292.fof.smt2                 |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0293.fof.smt2                 |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0294.fof.smt2                 |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0295.fof.smt2                 |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0296.fof.smt2                 |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0297.fof.smt2                 |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0298.fof.smt2                 |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0299.fof.smt2                 |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0300.fof.smt2                 |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0301.fof.smt2                 |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0302.fof.smt2                 |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0303.fof.smt2                 |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0304.fof.smt2                 |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0305.fof.smt2                 |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0306.fof.smt2                 |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0307.fof.smt2                 |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0308.fof.smt2                 |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0309.fof.smt2                 |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0310.fof.smt2                 |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0311.fof.smt2                 |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0312.fof.smt2                 |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0313.fof.smt2                 |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0314.fof.smt2                 |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0315.fof.smt2                 |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0316.fof.smt2                 |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0317.fof.smt2                 |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0318.fof.smt2                 |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0319.fof.smt2                 |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0320.fof.smt2                 |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0321.fof.smt2                 |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0322.fof.smt2                 |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0323.fof.smt2                 |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0324.fof.smt2                 |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0325.fof.smt2                 |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0326.fof.smt2                 |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0327.fof.smt2                 |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0328.fof.smt2                 |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0329.fof.smt2                 |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0330.fof.smt2                 |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0331.fof.smt2                 |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0332.fof.smt2                 |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0333.fof.smt2                 |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0334.fof.smt2                 |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0335.fof.smt2                 |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0336.fof.smt2                 |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0337.fof.smt2                 |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0338.fof.smt2                 |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0339.fof.smt2                 |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0340.fof.smt2                 |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0341.fof.smt2                 |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0342.fof.smt2                 |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0343.fof.smt2                 |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0344.fof.smt2                 |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0345.fof.smt2                 |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0346.fof.smt2                 |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0347.fof.smt2                 |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0348.fof.smt2                 |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0349.fof.smt2                 |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0350.fof.smt2                 |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0351.fof.smt2                 |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0352.fof.smt2                 |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0353.fof.smt2                 |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0354.fof.smt2                 |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0355.fof.smt2                 |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0356.fof.smt2                 |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0357.fof.smt2                 |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0358.fof.smt2                 |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0359.fof.smt2                 |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0360.fof.smt2                 |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0361.fof.smt2                 |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0362.fof.smt2                 |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0363.fof.smt2                 |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0364.fof.smt2                 |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0365.fof.smt2                 |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0366.fof.smt2                 |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0367.fof.smt2                 |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0368.fof.smt2                 |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0369.fof.smt2                 |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0370.fof.smt2                 |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0371.fof.smt2                 |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0372.fof.smt2                 |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0373.fof.smt2                 |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0374.fof.smt2                 |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0375.fof.smt2                 |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0376.fof.smt2                 |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0377.fof.smt2                 |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0378.fof.smt2                 |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0379.fof.smt2                 |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0380.fof.smt2                 |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0381.fof.smt2                 |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0382.fof.smt2                 |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0383.fof.smt2                 |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0384.fof.smt2                 |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0385.fof.smt2                 |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0386.fof.smt2                 |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0387.fof.smt2                 |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0388.fof.smt2                 |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0389.fof.smt2                 |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0390.fof.smt2                 |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/thruster_symm_0153.fof.smt2                       |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/thruster_symm_0158.fof.smt2                       |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify/thruster_symm_0187.fof.smt2                       |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_arithmetics/cl5_nebula_norm_0003.fof.smt2         |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_arithmetics/cl5_nebula_norm_0005.fof.smt2         |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_arithmetics/cl5_nebula_norm_0006.fof.smt2         |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_arithmetics/cl5_nebula_norm_0012.fof.smt2         |   0.225s  |   0.225s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_arithmetics/cl5_nebula_norm_0013.fof.smt2         |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_arithmetics/quaternion_ds1_symm_0001.fof.smt2     |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array/cl5_nebula_norm_0003.fof.smt2               |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array/cl5_nebula_norm_0004.fof.smt2               |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array/cl5_nebula_norm_0007.fof.smt2               |  20.194s  |  20.194s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array/cl5_nebula_norm_0008.fof.smt2               |  20.181s  |  20.181s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array/cl5_nebula_norm_0010.fof.smt2               |  20.106s  |  20.106s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array/cl5_nebula_norm_0011.fof.smt2               |  20.190s  |  20.190s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array/cl5_nebula_norm_0015.fof.smt2               |  20.071s  |  20.071s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array/cl5_nebula_norm_0016.fof.smt2               |  20.191s  |  20.191s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array/cl5_nebula_norm_0023.fof.smt2               |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array/cl5_nebula_norm_0024.fof.smt2               |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array/cl5_nebula_norm_0025.fof.smt2               |  20.214s  |  20.214s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array/cl5_nebula_norm_0027.fof.smt2               |  20.249s  |  20.249s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array/quaternion_ds1_symm_0418.fof.smt2           |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array/quaternion_ds1_symm_0423.fof.smt2           |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array/thruster_symm_0151.fof.smt2                 |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array/thruster_symm_0155.fof.smt2                 |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array/thruster_symm_0160.fof.smt2                 |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array/thruster_symm_0161.fof.smt2                 |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array/thruster_symm_0162.fof.smt2                 |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array/thruster_symm_0164.fof.smt2                 |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array/thruster_symm_0189.fof.smt2                 |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0004.fof.smt2          |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0005.fof.smt2          |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0006.fof.smt2          |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0007.fof.smt2          |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0008.fof.smt2          |  20.095s  |  20.095s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0009.fof.smt2          |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0010.fof.smt2          |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0011.fof.smt2          |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0012.fof.smt2          |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0013.fof.smt2          |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0014.fof.smt2          |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0015.fof.smt2          |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0016.fof.smt2          |  20.096s  |  20.096s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0017.fof.smt2          |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0018.fof.smt2          |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0019.fof.smt2          |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0020.fof.smt2          |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0021.fof.smt2          |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0022.fof.smt2          |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0030.fof.smt2          |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0031.fof.smt2          |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0032.fof.smt2          |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0033.fof.smt2          |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0034.fof.smt2          |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0035.fof.smt2          |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0036.fof.smt2          |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0037.fof.smt2          |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0038.fof.smt2          |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0039.fof.smt2          |  20.089s  |  20.089s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0040.fof.smt2          |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0041.fof.smt2          |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0042.fof.smt2          |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0043.fof.smt2          |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0044.fof.smt2          |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0045.fof.smt2          |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0046.fof.smt2          |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0047.fof.smt2          |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0048.fof.smt2          |  20.054s  |  20.054s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0049.fof.smt2          |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0050.fof.smt2          |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0051.fof.smt2          |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0052.fof.smt2          |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0063.fof.smt2          |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0064.fof.smt2          |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0065.fof.smt2          |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0066.fof.smt2          |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0067.fof.smt2          |  20.048s  |  20.048s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0068.fof.smt2          |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0069.fof.smt2          |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0070.fof.smt2          |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0071.fof.smt2          |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0072.fof.smt2          |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0073.fof.smt2          |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0074.fof.smt2          |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0075.fof.smt2          |  20.016s  |  20.016s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0076.fof.smt2          |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0077.fof.smt2          |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0078.fof.smt2          |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0079.fof.smt2          |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0080.fof.smt2          |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0081.fof.smt2          |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0099.fof.smt2          |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0100.fof.smt2          |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0101.fof.smt2          |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0102.fof.smt2          |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0103.fof.smt2          |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0104.fof.smt2          |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0105.fof.smt2          |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0106.fof.smt2          |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0107.fof.smt2          |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0108.fof.smt2          |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0109.fof.smt2          |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0110.fof.smt2          |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0111.fof.smt2          |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0112.fof.smt2          |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0120.fof.smt2          |  20.115s  |  20.115s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0121.fof.smt2          |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0122.fof.smt2          |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0123.fof.smt2          |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0126.fof.smt2          |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0128.fof.smt2          |  20.024s  |  20.024s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0129.fof.smt2          |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0130.fof.smt2          |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0131.fof.smt2          |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0134.fof.smt2          |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0001.fof.smt2      |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0002.fof.smt2      |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0003.fof.smt2      |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0004.fof.smt2      |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0005.fof.smt2      |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0006.fof.smt2      |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0007.fof.smt2      |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0008.fof.smt2      |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0009.fof.smt2      |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0010.fof.smt2      |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0011.fof.smt2      |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0012.fof.smt2      |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0013.fof.smt2      |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0014.fof.smt2      |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0015.fof.smt2      |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0016.fof.smt2      |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0017.fof.smt2      |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0018.fof.smt2      |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0019.fof.smt2      |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0020.fof.smt2      |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0021.fof.smt2      |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0022.fof.smt2      |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0023.fof.smt2      |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0024.fof.smt2      |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0025.fof.smt2      |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0026.fof.smt2      |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0027.fof.smt2      |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0028.fof.smt2      |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0029.fof.smt2      |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0030.fof.smt2      |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0031.fof.smt2      |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0032.fof.smt2      |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0033.fof.smt2      |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0034.fof.smt2      |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0035.fof.smt2      |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0036.fof.smt2      |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0037.fof.smt2      |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0038.fof.smt2      |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0045.fof.smt2      |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0052.fof.smt2      |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0059.fof.smt2      |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0066.fof.smt2      |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0073.fof.smt2      |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0075.fof.smt2      |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0082.fof.smt2      |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0089.fof.smt2      |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0096.fof.smt2      |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0103.fof.smt2      |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0110.fof.smt2      |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0112.fof.smt2      |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0119.fof.smt2      |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0126.fof.smt2      |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0133.fof.smt2      |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0140.fof.smt2      |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0147.fof.smt2      |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0149.fof.smt2      |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0156.fof.smt2      |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0163.fof.smt2      |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0170.fof.smt2      |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0177.fof.smt2      |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0184.fof.smt2      |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0186.fof.smt2      |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0193.fof.smt2      |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0200.fof.smt2      |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0207.fof.smt2      |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0214.fof.smt2      |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0221.fof.smt2      |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0223.fof.smt2      |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0230.fof.smt2      |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0237.fof.smt2      |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0244.fof.smt2      |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0251.fof.smt2      |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0258.fof.smt2      |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0260.fof.smt2      |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0261.fof.smt2      |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0262.fof.smt2      |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0263.fof.smt2      |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0264.fof.smt2      |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0265.fof.smt2      |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0266.fof.smt2      |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0267.fof.smt2      |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0268.fof.smt2      |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0269.fof.smt2      |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0270.fof.smt2      |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0271.fof.smt2      |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0272.fof.smt2      |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0273.fof.smt2      |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0274.fof.smt2      |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0275.fof.smt2      |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0276.fof.smt2      |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0277.fof.smt2      |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0278.fof.smt2      |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0279.fof.smt2      |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0280.fof.smt2      |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0281.fof.smt2      |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0282.fof.smt2      |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0283.fof.smt2      |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0284.fof.smt2      |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0285.fof.smt2      |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0286.fof.smt2      |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0287.fof.smt2      |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0288.fof.smt2      |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0289.fof.smt2      |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0290.fof.smt2      |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0291.fof.smt2      |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0292.fof.smt2      |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0293.fof.smt2      |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0294.fof.smt2      |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0295.fof.smt2      |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0296.fof.smt2      |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0297.fof.smt2      |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0304.fof.smt2      |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0311.fof.smt2      |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0318.fof.smt2      |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0325.fof.smt2      |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0332.fof.smt2      |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0334.fof.smt2      |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0341.fof.smt2      |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0348.fof.smt2      |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0355.fof.smt2      |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0362.fof.smt2      |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0369.fof.smt2      |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0371.fof.smt2      |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0378.fof.smt2      |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0385.fof.smt2      |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0392.fof.smt2      |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0399.fof.smt2      |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0406.fof.smt2      |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0408.fof.smt2      |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0415.fof.smt2      |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0422.fof.smt2      |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0429.fof.smt2      |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0436.fof.smt2      |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0443.fof.smt2      |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0445.fof.smt2      |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0452.fof.smt2      |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0459.fof.smt2      |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0466.fof.smt2      |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0473.fof.smt2      |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0480.fof.smt2      |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0482.fof.smt2      |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0489.fof.smt2      |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0496.fof.smt2      |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0503.fof.smt2      |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0510.fof.smt2      |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0517.fof.smt2      |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0519.fof.smt2      |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0520.fof.smt2      |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0521.fof.smt2      |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0522.fof.smt2      |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0523.fof.smt2      |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0524.fof.smt2      |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0525.fof.smt2      |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0526.fof.smt2      |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0527.fof.smt2      |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0528.fof.smt2      |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0529.fof.smt2      |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0530.fof.smt2      |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0531.fof.smt2      |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0532.fof.smt2      |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0533.fof.smt2      |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0534.fof.smt2      |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0535.fof.smt2      |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0536.fof.smt2      |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0537.fof.smt2      |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0538.fof.smt2      |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0539.fof.smt2      |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0540.fof.smt2      |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0541.fof.smt2      |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0542.fof.smt2      |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0543.fof.smt2      |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0544.fof.smt2      |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0545.fof.smt2      |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0546.fof.smt2      |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0547.fof.smt2      |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0548.fof.smt2      |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0549.fof.smt2      |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0550.fof.smt2      |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0551.fof.smt2      |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0552.fof.smt2      |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0553.fof.smt2      |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0554.fof.smt2      |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0555.fof.smt2      |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0556.fof.smt2      |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0563.fof.smt2      |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0570.fof.smt2      |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0577.fof.smt2      |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0584.fof.smt2      |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0591.fof.smt2      |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0593.fof.smt2      |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0600.fof.smt2      |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0607.fof.smt2      |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0614.fof.smt2      |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0621.fof.smt2      |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0628.fof.smt2      |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0630.fof.smt2      |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0637.fof.smt2      |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0644.fof.smt2      |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0651.fof.smt2      |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0658.fof.smt2      |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0665.fof.smt2      |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0667.fof.smt2      |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0674.fof.smt2      |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0681.fof.smt2      |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0688.fof.smt2      |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0695.fof.smt2      |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0702.fof.smt2      |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0704.fof.smt2      |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0711.fof.smt2      |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0718.fof.smt2      |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0725.fof.smt2      |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0732.fof.smt2      |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0739.fof.smt2      |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0741.fof.smt2      |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0748.fof.smt2      |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0755.fof.smt2      |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0762.fof.smt2      |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0769.fof.smt2      |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0776.fof.smt2      |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0778.fof.smt2      |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0779.fof.smt2      |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0780.fof.smt2      |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0781.fof.smt2      |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0782.fof.smt2      |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0783.fof.smt2      |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0784.fof.smt2      |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0785.fof.smt2      |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0786.fof.smt2      |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0787.fof.smt2      |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0788.fof.smt2      |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0789.fof.smt2      |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0790.fof.smt2      |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0791.fof.smt2      |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0792.fof.smt2      |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0793.fof.smt2      |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0794.fof.smt2      |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0795.fof.smt2      |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0796.fof.smt2      |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0797.fof.smt2      |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0798.fof.smt2      |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0799.fof.smt2      |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0800.fof.smt2      |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0801.fof.smt2      |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0802.fof.smt2      |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0803.fof.smt2      |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0804.fof.smt2      |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0805.fof.smt2      |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0806.fof.smt2      |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0807.fof.smt2      |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0808.fof.smt2      |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0809.fof.smt2      |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0810.fof.smt2      |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0811.fof.smt2      |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0812.fof.smt2      |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0813.fof.smt2      |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0814.fof.smt2      |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0815.fof.smt2      |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0822.fof.smt2      |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0829.fof.smt2      |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0836.fof.smt2      |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0843.fof.smt2      |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0850.fof.smt2      |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0852.fof.smt2      |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0859.fof.smt2      |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0866.fof.smt2      |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0873.fof.smt2      |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0880.fof.smt2      |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0887.fof.smt2      |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0889.fof.smt2      |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0896.fof.smt2      |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0903.fof.smt2      |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0910.fof.smt2      |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0917.fof.smt2      |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0924.fof.smt2      |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0926.fof.smt2      |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0933.fof.smt2      |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0940.fof.smt2      |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0947.fof.smt2      |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0954.fof.smt2      |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0961.fof.smt2      |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0963.fof.smt2      |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0970.fof.smt2      |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0977.fof.smt2      |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0984.fof.smt2      |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0991.fof.smt2      |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0998.fof.smt2      |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1000.fof.smt2      |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1007.fof.smt2      |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1014.fof.smt2      |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1021.fof.smt2      |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1028.fof.smt2      |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1035.fof.smt2      |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1037.fof.smt2      |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1038.fof.smt2      |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1039.fof.smt2      |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1040.fof.smt2      |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1041.fof.smt2      |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1042.fof.smt2      |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1043.fof.smt2      |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1044.fof.smt2      |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1045.fof.smt2      |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1046.fof.smt2      |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1047.fof.smt2      |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1048.fof.smt2      |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1049.fof.smt2      |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1050.fof.smt2      |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1051.fof.smt2      |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1052.fof.smt2      |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1053.fof.smt2      |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1054.fof.smt2      |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1055.fof.smt2      |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1056.fof.smt2      |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1057.fof.smt2      |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1058.fof.smt2      |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1059.fof.smt2      |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1060.fof.smt2      |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1061.fof.smt2      |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1062.fof.smt2      |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1063.fof.smt2      |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1064.fof.smt2      |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1065.fof.smt2      |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1066.fof.smt2      |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1067.fof.smt2      |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1068.fof.smt2      |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1069.fof.smt2      |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1070.fof.smt2      |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1071.fof.smt2      |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1072.fof.smt2      |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1073.fof.smt2      |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1074.fof.smt2      |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1081.fof.smt2      |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1088.fof.smt2      |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1095.fof.smt2      |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1102.fof.smt2      |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1109.fof.smt2      |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1111.fof.smt2      |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1118.fof.smt2      |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1125.fof.smt2      |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1132.fof.smt2      |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1139.fof.smt2      |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1146.fof.smt2      |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1148.fof.smt2      |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1155.fof.smt2      |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1162.fof.smt2      |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1169.fof.smt2      |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1176.fof.smt2      |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1183.fof.smt2      |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1185.fof.smt2      |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1192.fof.smt2      |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1199.fof.smt2      |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1206.fof.smt2      |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1213.fof.smt2      |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1220.fof.smt2      |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1222.fof.smt2      |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1229.fof.smt2      |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1236.fof.smt2      |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1243.fof.smt2      |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1250.fof.smt2      |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1257.fof.smt2      |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1259.fof.smt2      |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1266.fof.smt2      |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1273.fof.smt2      |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1280.fof.smt2      |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1287.fof.smt2      |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1294.fof.smt2      |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1296.fof.smt2      |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1297.fof.smt2      |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1298.fof.smt2      |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1299.fof.smt2      |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1300.fof.smt2      |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1301.fof.smt2      |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1302.fof.smt2      |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1303.fof.smt2      |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1304.fof.smt2      |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1305.fof.smt2      |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1306.fof.smt2      |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1307.fof.smt2      |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1308.fof.smt2      |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1309.fof.smt2      |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1310.fof.smt2      |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1311.fof.smt2      |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1312.fof.smt2      |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1313.fof.smt2      |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1314.fof.smt2      |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1315.fof.smt2      |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1316.fof.smt2      |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1317.fof.smt2      |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1318.fof.smt2      |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1319.fof.smt2      |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1320.fof.smt2      |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1321.fof.smt2      |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1322.fof.smt2      |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1323.fof.smt2      |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1324.fof.smt2      |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1325.fof.smt2      |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1326.fof.smt2      |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1327.fof.smt2      |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1328.fof.smt2      |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1329.fof.smt2      |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1330.fof.smt2      |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1331.fof.smt2      |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1332.fof.smt2      |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1333.fof.smt2      |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1340.fof.smt2      |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1347.fof.smt2      |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1354.fof.smt2      |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1361.fof.smt2      |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1368.fof.smt2      |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1482.fof.smt2      |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1490.fof.smt2      |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/thruster_symm_1475.fof.smt2            |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/thruster_symm_1537.fof.smt2            |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/thruster_symm_1552.fof.smt2            |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/thruster_symm_1614.fof.smt2            |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/thruster_symm_1620.fof.smt2            |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/thruster_symm_1628.fof.smt2            |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/thruster_symm_1658.fof.smt2            |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/thruster_symm_1689.fof.smt2            |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/thruster_symm_1697.fof.smt2            |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/thruster_symm_1704.fof.smt2            |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/thruster_symm_1735.fof.smt2            |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/thruster_symm_1765.fof.smt2            |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_structure_forall/cl5_nebula_norm_0029.fof.smt2    |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_structure_prop/cl5_nebula_norm_0003.fof.smt2      |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_structure_prop/cl5_nebula_norm_0004.fof.smt2      |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_structure_prop/cl5_nebula_norm_0005.fof.smt2      |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_structure_prop/cl5_nebula_norm_0006.fof.smt2      |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_structure_prop/cl5_nebula_norm_0017.fof.smt2      |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_structure_prop/cl5_nebula_norm_0018.fof.smt2      |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_structure_prop/quaternion_ds1_symm_0001.fof.smt2  |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_structure_prop/quaternion_ds1_symm_0005.fof.smt2  |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_structure_prop/quaternion_ds1_symm_0017.fof.smt2  |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_structure_prop/thruster_symm_0010.fof.smt2        |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_structure_prop/thruster_symm_0013.fof.smt2        |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_structure_prop/thruster_symm_0014.fof.smt2        |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_structure_prop/thruster_symm_0015.fof.smt2        |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_structure_prop/thruster_symm_0016.fof.smt2        |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_structure_prop/thruster_symm_0017.fof.smt2        |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/fol_simplify_structure_prop/thruster_symm_0031.fof.smt2        |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/vc_normalize_subst/cl5_nebula_norm_0004.fof.smt2               |  20.125s  |  20.125s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/vc_normalize_subst/cl5_nebula_norm_0005.fof.smt2               |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/vc_normalize_subst/cl5_nebula_norm_0006.fof.smt2               |  20.075s  |  20.075s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/vc_normalize_subst/cl5_nebula_norm_0010.fof.smt2               |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/vc_normalize_subst/cl5_nebula_norm_0011.fof.smt2               |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/vc_normalize_subst/cl5_nebula_norm_0012.fof.smt2               |  20.144s  |  20.144s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/vc_normalize_subst/cl5_nebula_norm_0013.fof.smt2               |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/vc_normalize_subst/cl5_nebula_norm_0014.fof.smt2               |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/vc_normalize_subst/cl5_nebula_norm_0015.fof.smt2               |  20.309s  |  20.309s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/vc_normalize_subst/cl5_nebula_norm_0016.fof.smt2               |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/vc_normalize_subst/cl5_nebula_norm_0019.fof.smt2               |  20.082s  |  20.082s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/vc_normalize_subst/cl5_nebula_norm_0020.fof.smt2               |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/vc_normalize_subst/cl5_nebula_norm_0021.fof.smt2               |  20.055s  |  20.055s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/vc_normalize_subst/cl5_nebula_norm_0031.fof.smt2               |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/vc_normalize_subst/cl5_nebula_norm_0032.fof.smt2               |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/vc_normalize_subst/cl5_nebula_norm_0036.fof.smt2               |  20.205s  |  20.205s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/vc_normalize_subst/cl5_nebula_norm_0037.fof.smt2               |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/vc_normalize_subst/cl5_nebula_norm_0038.fof.smt2               |  20.183s  |  20.183s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/vc_normalize_subst/cl5_nebula_norm_0039.fof.smt2               |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/vc_normalize_subst/quaternion_ds1_symm_0001.fof.smt2           |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/vc_normalize_subst/quaternion_ds1_symm_0011.fof.smt2           |   0.398s  |   0.398s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/nasa/vc_normalize_subst/thruster_symm_0001.fof.smt2                 |   0.229s  |   0.229s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/why/smtlib14c92b.smt2                                               |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/why/smtlib5966a0.smt2                                               |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/why/smtlib7a3a8e.smt2                                               |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/why/smtlib8e6000.smt2                                               |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/why/smtlibb47bdc.smt2                                               |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/why/smtlibce35b2.smt2                                               |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/why/smtlibd85203.smt2                                               |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/why/smtlibdba7a4.smt2                                               |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/why/smtlibdff996.smt2                                               |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/why/smtlibf37c88.smt2                                               |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/why/smtlibf3ad77.smt2                                               |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|non-incremental/AUFNIRA/why/smtlibfc99e2.smt2                                               |   0.065s  |   0.065s  |   0.000s  | 0.0%|
</details>
