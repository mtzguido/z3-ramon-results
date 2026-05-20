Comparing data and data


# SUMMARY
- LHS tests = 2416
- RHS tests = 2416
- LHS success = 2416  (100.0%)
- RHS success = 2416  (100.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: LRA.tar.zst
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: bc6c38e7d3424b88a505cacba4b268d0774d4547
Z3 branch: master
Z3 options: "-T:20"
Z3 inputs: https://zenodo.org/records/16740866/files/LRA.tar.zst?download=1
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
Job tag: LRA.tar.zst
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: bc6c38e7d3424b88a505cacba4b268d0774d4547
Z3 branch: master
Z3 options: "-T:20"
Z3 inputs: https://zenodo.org/records/16740866/files/LRA.tar.zst?download=1
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
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_001.smt2                             |   0.318s  |   0.318s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_002.smt2                             |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_003.smt2                             |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_004.smt2                             |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_005.smt2                             |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_006.smt2                             |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_007.smt2                             |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_008.smt2                             |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_009.smt2                             |   0.170s  |   0.170s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_010.smt2                             |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_011.smt2                             |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_012.smt2                             |  20.042s  |  20.042s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_013.smt2                             |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_014.smt2                             |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_015.smt2                             |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_016.smt2                             |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_017.smt2                             |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_018.smt2                             |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_019.smt2                             |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_020.smt2                             |   0.231s  |   0.231s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_001.smt2                             |   0.318s  |   0.318s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_002.smt2                             |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_003.smt2                             |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_004.smt2                             |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_005.smt2                             |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_006.smt2                             |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_007.smt2                             |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_008.smt2                             |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_009.smt2                             |   0.170s  |   0.170s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_010.smt2                             |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_011.smt2                             |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_012.smt2                             |  20.042s  |  20.042s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_013.smt2                             |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_014.smt2                             |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_015.smt2                             |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_016.smt2                             |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_017.smt2                             |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_018.smt2                             |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_019.smt2                             |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_020.smt2                             |   0.231s  |   0.231s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_001.smt2                             |   0.318s  |   0.318s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_002.smt2                             |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_003.smt2                             |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_004.smt2                             |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_005.smt2                             |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_006.smt2                             |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_007.smt2                             |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_008.smt2                             |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_009.smt2                             |   0.170s  |   0.170s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_010.smt2                             |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_011.smt2                             |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_012.smt2                             |  20.042s  |  20.042s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_013.smt2                             |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_014.smt2                             |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_015.smt2                             |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_016.smt2                             |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_017.smt2                             |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_018.smt2                             |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_019.smt2                             |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_020.smt2                             |   0.231s  |   0.231s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_001.smt2                             |   0.318s  |   0.318s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_002.smt2                             |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_003.smt2                             |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_004.smt2                             |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_005.smt2                             |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_006.smt2                             |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_007.smt2                             |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_008.smt2                             |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_009.smt2                             |   0.170s  |   0.170s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_010.smt2                             |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_011.smt2                             |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_012.smt2                             |  20.042s  |  20.042s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_013.smt2                             |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_014.smt2                             |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_015.smt2                             |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_016.smt2                             |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_017.smt2                             |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_018.smt2                             |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_019.smt2                             |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_020.smt2                             |   0.231s  |   0.231s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_127.smt2                            |  20.195s |21.808MiB|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_264.smt2                            |  20.194s |21.992MiB|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_158.smt2                            |  20.193s |21.64MiB|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_208.smt2                            |  20.193s |21.852MiB|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_282.smt2                            |  20.170s |21.616MiB|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_113.smt2                            |  20.170s |21.808MiB|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_049.smt2                            |  20.169s |21.72MiB|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_162.smt2                            |  20.168s |21.756MiB|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_097.smt2                            |  20.166s |21.632MiB|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_134.smt2                            |  20.166s |21.38MiB|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_020.smt2                            |  20.164s |21.708MiB|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_074.smt2                            |  20.164s |21.832MiB|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_189.smt2                            |  20.162s |22.072MiB|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_256.smt2                            |  20.161s |21.432MiB|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_275.smt2                            |  20.160s |21.724MiB|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_201.smt2                            |  20.160s |21.964MiB|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_270.smt2                            |  20.158s |21.628MiB|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_116.smt2                            |  20.157s |21.476MiB|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_244.smt2                            |  20.157s |21.812MiB|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_144.smt2                            |  20.155s |21.616MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_127.smt2                            |  20.195s |21.808MiB|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_264.smt2                            |  20.194s |21.992MiB|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_158.smt2                            |  20.193s |21.64MiB|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_208.smt2                            |  20.193s |21.852MiB|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_282.smt2                            |  20.170s |21.616MiB|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_113.smt2                            |  20.170s |21.808MiB|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_049.smt2                            |  20.169s |21.72MiB|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_162.smt2                            |  20.168s |21.756MiB|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_097.smt2                            |  20.166s |21.632MiB|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_134.smt2                            |  20.166s |21.38MiB|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_020.smt2                            |  20.164s |21.708MiB|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_074.smt2                            |  20.164s |21.832MiB|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_189.smt2                            |  20.162s |22.072MiB|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_256.smt2                            |  20.161s |21.432MiB|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_275.smt2                            |  20.160s |21.724MiB|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_201.smt2                            |  20.160s |21.964MiB|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_270.smt2                            |  20.158s |21.628MiB|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_116.smt2                            |  20.157s |21.476MiB|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_244.smt2                            |  20.157s |21.812MiB|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_144.smt2                            |  20.155s |21.616MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_001.smt2                             |21.904MiB|21.904MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_002.smt2                             |21.072MiB|21.072MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_003.smt2                             |21.14MiB|21.14MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_004.smt2                             |20.916MiB|20.916MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_005.smt2                             |20.884MiB|20.884MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_006.smt2                             |19.632MiB|19.632MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_007.smt2                             |20.62MiB|20.62MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_008.smt2                             |20.92MiB|20.92MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_009.smt2                             |21.364MiB|21.364MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_010.smt2                             |21.384MiB|21.384MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_011.smt2                             |20.696MiB|20.696MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_012.smt2                             |24.668MiB|24.668MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_013.smt2                             |21.192MiB|21.192MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_014.smt2                             |20.904MiB|20.904MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_015.smt2                             |21.204MiB|21.204MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_016.smt2                             |21.088MiB|21.088MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_017.smt2                             |21.56MiB|21.56MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_018.smt2                             |21.284MiB|21.284MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_019.smt2                             |21.244MiB|21.244MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_020.smt2                             |21.96MiB|21.96MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_001.smt2                             |21.904MiB|21.904MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_002.smt2                             |21.072MiB|21.072MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_003.smt2                             |21.14MiB|21.14MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_004.smt2                             |20.916MiB|20.916MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_005.smt2                             |20.884MiB|20.884MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_006.smt2                             |19.632MiB|19.632MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_007.smt2                             |20.62MiB|20.62MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_008.smt2                             |20.92MiB|20.92MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_009.smt2                             |21.364MiB|21.364MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_010.smt2                             |21.384MiB|21.384MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_011.smt2                             |20.696MiB|20.696MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_012.smt2                             |24.668MiB|24.668MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_013.smt2                             |21.192MiB|21.192MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_014.smt2                             |20.904MiB|20.904MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_015.smt2                             |21.204MiB|21.204MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_016.smt2                             |21.088MiB|21.088MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_017.smt2                             |21.56MiB|21.56MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_018.smt2                             |21.284MiB|21.284MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_019.smt2                             |21.244MiB|21.244MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_020.smt2                             |21.96MiB|21.96MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_001.smt2                             |21.904MiB|21.904MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_002.smt2                             |21.072MiB|21.072MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_003.smt2                             |21.14MiB|21.14MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_004.smt2                             |20.916MiB|20.916MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_005.smt2                             |20.884MiB|20.884MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_006.smt2                             |19.632MiB|19.632MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_007.smt2                             |20.62MiB|20.62MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_008.smt2                             |20.92MiB|20.92MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_009.smt2                             |21.364MiB|21.364MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_010.smt2                             |21.384MiB|21.384MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_011.smt2                             |20.696MiB|20.696MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_012.smt2                             |24.668MiB|24.668MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_013.smt2                             |21.192MiB|21.192MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_014.smt2                             |20.904MiB|20.904MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_015.smt2                             |21.204MiB|21.204MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_016.smt2                             |21.088MiB|21.088MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_017.smt2                             |21.56MiB|21.56MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_018.smt2                             |21.284MiB|21.284MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_019.smt2                             |21.244MiB|21.244MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_020.smt2                             |21.96MiB|21.96MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_001.smt2                             |21.904MiB|21.904MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_002.smt2                             |21.072MiB|21.072MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_003.smt2                             |21.14MiB|21.14MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_004.smt2                             |20.916MiB|20.916MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_005.smt2                             |20.884MiB|20.884MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_006.smt2                             |19.632MiB|19.632MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_007.smt2                             |20.62MiB|20.62MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_008.smt2                             |20.92MiB|20.92MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_009.smt2                             |21.364MiB|21.364MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_010.smt2                             |21.384MiB|21.384MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_011.smt2                             |20.696MiB|20.696MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_012.smt2                             |24.668MiB|24.668MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_013.smt2                             |21.192MiB|21.192MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_014.smt2                             |20.904MiB|20.904MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_015.smt2                             |21.204MiB|21.204MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_016.smt2                             |21.088MiB|21.088MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_017.smt2                             |21.56MiB|21.56MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_018.smt2                             |21.284MiB|21.284MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_019.smt2                             |21.244MiB|21.244MiB|0B| 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_020.smt2                             |21.96MiB|21.96MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/LRA/20230331-polyv/mithv.smt2                                              |  20.090s |671.0MiB|
|non-incremental/LRA/20230331-polyv/bv7hv.smt2                                              |  20.079s |607.0MiB|
|non-incremental/LRA/20230331-polyv/mithv-miss1v.smt2                                       |  20.074s |555.0MiB|
|non-incremental/LRA/20230331-polyv/bv7hv-miss1v.smt2                                       |  20.074s |506.0MiB|
|non-incremental/LRA/20230331-polyv/bv7hv-miss1h.smt2                                       |  12.556s |465.0MiB|
|non-incremental/LRA/20230331-polyv/h5projh-h4v.smt2                                        |  20.039s |170.0MiB|
|non-incremental/LRA/20230331-polyv/h5projh-h4h.smt2                                        |  20.038s |148.0MiB|
|non-incremental/LRA/20230331-polyv/h5hv.smt2                                               |  20.032s |148.0MiB|
|non-incremental/LRA/20230331-polyv/mit-projhv.smt2                                         |  20.028s |91.796MiB|
|non-incremental/LRA/20230331-polyv/mit-projhv-miss1.smt2                                   |  20.024s |91.636MiB|
|non-incremental/LRA/20230331-polyv/mit-projhh.smt2                                         |  20.025s |77.608MiB|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_66.smt2                                   |   6.730s |62.888MiB|
|non-incremental/LRA/20230331-polyv/mit-checkpred726.smt2                                   |  20.022s |57.724MiB|
|non-incremental/LRA/20230331-polyv/mit-projhh-miss1.smt2                                   |   2.661s |57.632MiB|
|non-incremental/LRA/20230331-polyv/mit-checkpred1.smt2                                     |  20.024s |57.076MiB|
|non-incremental/LRA/20230331-polyv/h5projh3-h4projh3.smt2                                  |  20.019s |52.804MiB|
|non-incremental/LRA/scholl-smt08/RND/RND_6_39.smt2                                         |  20.018s |46.784MiB|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_67.smt2                                   |   0.270s |44.288MiB|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_70.smt2                                   |   1.021s |43.628MiB|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_61.smt2                                   |   2.505s |43.208MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/LRA/20230331-polyv/mithv.smt2                                              |  20.090s |671.0MiB|
|non-incremental/LRA/20230331-polyv/bv7hv.smt2                                              |  20.079s |607.0MiB|
|non-incremental/LRA/20230331-polyv/mithv-miss1v.smt2                                       |  20.074s |555.0MiB|
|non-incremental/LRA/20230331-polyv/bv7hv-miss1v.smt2                                       |  20.074s |506.0MiB|
|non-incremental/LRA/20230331-polyv/bv7hv-miss1h.smt2                                       |  12.556s |465.0MiB|
|non-incremental/LRA/20230331-polyv/h5projh-h4v.smt2                                        |  20.039s |170.0MiB|
|non-incremental/LRA/20230331-polyv/h5projh-h4h.smt2                                        |  20.038s |148.0MiB|
|non-incremental/LRA/20230331-polyv/h5hv.smt2                                               |  20.032s |148.0MiB|
|non-incremental/LRA/20230331-polyv/mit-projhv.smt2                                         |  20.028s |91.796MiB|
|non-incremental/LRA/20230331-polyv/mit-projhv-miss1.smt2                                   |  20.024s |91.636MiB|
|non-incremental/LRA/20230331-polyv/mit-projhh.smt2                                         |  20.025s |77.608MiB|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_66.smt2                                   |   6.730s |62.888MiB|
|non-incremental/LRA/20230331-polyv/mit-checkpred726.smt2                                   |  20.022s |57.724MiB|
|non-incremental/LRA/20230331-polyv/mit-projhh-miss1.smt2                                   |   2.661s |57.632MiB|
|non-incremental/LRA/20230331-polyv/mit-checkpred1.smt2                                     |  20.024s |57.076MiB|
|non-incremental/LRA/20230331-polyv/h5projh3-h4projh3.smt2                                  |  20.019s |52.804MiB|
|non-incremental/LRA/scholl-smt08/RND/RND_6_39.smt2                                         |  20.018s |46.784MiB|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_67.smt2                                   |   0.270s |44.288MiB|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_70.smt2                                   |   1.021s |43.628MiB|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_61.smt2                                   |   2.505s |43.208MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_001.smt2                             |   0.318s  |   0.318s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_002.smt2                             |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_003.smt2                             |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_004.smt2                             |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_005.smt2                             |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_006.smt2                             |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_007.smt2                             |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_008.smt2                             |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_009.smt2                             |   0.170s  |   0.170s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_010.smt2                             |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_011.smt2                             |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_012.smt2                             |  20.042s  |  20.042s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_013.smt2                             |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_014.smt2                             |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_015.smt2                             |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_016.smt2                             |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_017.smt2                             |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_018.smt2                             |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_019.smt2                             |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_020.smt2                             |   0.231s  |   0.231s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_021.smt2                             |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_022.smt2                             |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_023.smt2                             |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_024.smt2                             |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_025.smt2                             |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_026.smt2                             |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_027.smt2                             |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_028.smt2                             |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_029.smt2                             |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_030.smt2                             |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_031.smt2                             |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_032.smt2                             |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_033.smt2                             |   0.187s  |   0.187s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_034.smt2                             |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_035.smt2                             |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_036.smt2                             |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_037.smt2                             |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_038.smt2                             |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_039.smt2                             |   0.171s  |   0.171s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_040.smt2                             |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_041.smt2                             |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_042.smt2                             |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_043.smt2                             |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_044.smt2                             |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_045.smt2                             |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_046.smt2                             |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_047.smt2                             |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_048.smt2                             |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_049.smt2                             |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_050.smt2                             |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_051.smt2                             |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_052.smt2                             |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_053.smt2                             |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_054.smt2                             |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_055.smt2                             |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_056.smt2                             |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_057.smt2                             |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_058.smt2                             |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_059.smt2                             |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_060.smt2                             |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_061.smt2                             |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_062.smt2                             |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_063.smt2                             |   5.837s  |   5.837s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_064.smt2                             |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_065.smt2                             |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_066.smt2                             |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_067.smt2                             |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_068.smt2                             |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_069.smt2                             |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_070.smt2                             |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_071.smt2                             |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_072.smt2                             |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_073.smt2                             |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_074.smt2                             |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_075.smt2                             |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_076.smt2                             |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_077.smt2                             |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_078.smt2                             |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_079.smt2                             |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_080.smt2                             |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_081.smt2                             |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_082.smt2                             |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_083.smt2                             |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_084.smt2                             |   0.488s  |   0.488s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_085.smt2                             |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_086.smt2                             |   0.438s  |   0.438s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_087.smt2                             |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_088.smt2                             |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_089.smt2                             |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_090.smt2                             |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_091.smt2                             |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_092.smt2                             |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_093.smt2                             |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_094.smt2                             |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_095.smt2                             |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_096.smt2                             |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_097.smt2                             |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_098.smt2                             |   0.398s  |   0.398s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_099.smt2                             |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_100.smt2                             |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_101.smt2                             |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_102.smt2                             |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_103.smt2                             |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_104.smt2                             |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_105.smt2                             |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_106.smt2                             |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_107.smt2                             |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_108.smt2                             |   0.200s  |   0.200s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_109.smt2                             |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_110.smt2                             |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_111.smt2                             |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_112.smt2                             |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_113.smt2                             |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_114.smt2                             |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_115.smt2                             |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_116.smt2                             |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_117.smt2                             |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_118.smt2                             |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_119.smt2                             |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_120.smt2                             |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_121.smt2                             |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_122.smt2                             |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_123.smt2                             |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_124.smt2                             |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_125.smt2                             |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_126.smt2                             |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_127.smt2                             |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_128.smt2                             |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_129.smt2                             |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_130.smt2                             |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_131.smt2                             |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_132.smt2                             |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_133.smt2                             |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_134.smt2                             |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_135.smt2                             |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_136.smt2                             |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_137.smt2                             |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_138.smt2                             |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_139.smt2                             |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_140.smt2                             |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_141.smt2                             |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_142.smt2                             |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_143.smt2                             |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_144.smt2                             |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_145.smt2                             |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_146.smt2                             |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_147.smt2                             |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_148.smt2                             |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_149.smt2                             |   0.292s  |   0.292s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_150.smt2                             |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_151.smt2                             |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_152.smt2                             |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_153.smt2                             |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_154.smt2                             |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_155.smt2                             |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_156.smt2                             |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_157.smt2                             |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_158.smt2                             |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_159.smt2                             |   0.182s  |   0.182s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_160.smt2                             |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_161.smt2                             |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_162.smt2                             |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_163.smt2                             |   0.202s  |   0.202s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_164.smt2                             |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_165.smt2                             |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_166.smt2                             |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_167.smt2                             |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_168.smt2                             |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_169.smt2                             |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_170.smt2                             |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_171.smt2                             |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_172.smt2                             |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_173.smt2                             |   0.361s  |   0.361s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_174.smt2                             |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_175.smt2                             |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_176.smt2                             |   0.283s  |   0.283s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_177.smt2                             |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_178.smt2                             |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_179.smt2                             |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_180.smt2                             |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_181.smt2                             |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_182.smt2                             |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_183.smt2                             |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_184.smt2                             |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_185.smt2                             |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_186.smt2                             |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_187.smt2                             |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_188.smt2                             |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_189.smt2                             |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_190.smt2                             |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_191.smt2                             |   0.258s  |   0.258s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_192.smt2                             |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_193.smt2                             |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_194.smt2                             |   0.619s  |   0.619s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_195.smt2                             |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_196.smt2                             |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_197.smt2                             |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_198.smt2                             |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_199.smt2                             |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_200.smt2                             |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_201.smt2                             |   0.186s  |   0.186s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_202.smt2                             |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_203.smt2                             |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_204.smt2                             |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_205.smt2                             |   2.787s  |   2.787s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_206.smt2                             |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_207.smt2                             |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_208.smt2                             |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_209.smt2                             |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_210.smt2                             |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_211.smt2                             |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_212.smt2                             |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_213.smt2                             |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_214.smt2                             |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_215.smt2                             |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_216.smt2                             |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_217.smt2                             |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_218.smt2                             |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_219.smt2                             |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_220.smt2                             |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_221.smt2                             |   0.216s  |   0.216s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_222.smt2                             |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_223.smt2                             |   0.255s  |   0.255s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_224.smt2                             |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_225.smt2                             |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_226.smt2                             |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_227.smt2                             |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_228.smt2                             |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_229.smt2                             |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_230.smt2                             |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_231.smt2                             |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_232.smt2                             |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_233.smt2                             |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_234.smt2                             |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_235.smt2                             |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_236.smt2                             |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_237.smt2                             |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_238.smt2                             |   0.195s  |   0.195s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_239.smt2                             |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_240.smt2                             |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_241.smt2                             |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_242.smt2                             |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_243.smt2                             |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_244.smt2                             |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_245.smt2                             |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_246.smt2                             |   0.417s  |   0.417s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_247.smt2                             |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_248.smt2                             |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_249.smt2                             |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_250.smt2                             |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_251.smt2                             |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_252.smt2                             |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_253.smt2                             |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_254.smt2                             |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_255.smt2                             |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_256.smt2                             |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_257.smt2                             |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_258.smt2                             |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_259.smt2                             |   0.639s  |   0.639s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_260.smt2                             |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_261.smt2                             |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_262.smt2                             |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_263.smt2                             |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_264.smt2                             |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_265.smt2                             |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_266.smt2                             |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_267.smt2                             |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_268.smt2                             |   0.220s  |   0.220s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_269.smt2                             |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_270.smt2                             |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_271.smt2                             |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_272.smt2                             |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_273.smt2                             |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_274.smt2                             |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_275.smt2                             |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_276.smt2                             |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_277.smt2                             |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_278.smt2                             |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_279.smt2                             |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_280.smt2                             |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_281.smt2                             |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_282.smt2                             |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_283.smt2                             |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_284.smt2                             |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_285.smt2                             |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_286.smt2                             |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_287.smt2                             |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_288.smt2                             |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_289.smt2                             |   0.186s  |   0.186s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_290.smt2                             |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_291.smt2                             |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_292.smt2                             |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_293.smt2                             |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_294.smt2                             |   0.235s  |   0.235s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_295.smt2                             |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_296.smt2                             |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_297.smt2                             |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_298.smt2                             |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_299.smt2                             |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir1/formula_300.smt2                             |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_001.smt2                             |   4.643s  |   4.643s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_002.smt2                             |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_003.smt2                             |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_004.smt2                             |   2.343s  |   2.343s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_005.smt2                             |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_006.smt2                             |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_007.smt2                             |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_008.smt2                             |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_009.smt2                             |  20.062s  |  20.062s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_010.smt2                             |  20.023s  |  20.023s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_011.smt2                             |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_012.smt2                             |   0.353s  |   0.353s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_013.smt2                             |  13.211s  |  13.211s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_014.smt2                             |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_015.smt2                             |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_016.smt2                             |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_017.smt2                             |   5.286s  |   5.286s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_018.smt2                             |   0.256s  |   0.256s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_019.smt2                             |   7.821s  |   7.821s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_020.smt2                             |   5.713s  |   5.713s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_021.smt2                             |   0.346s  |   0.346s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_022.smt2                             |   1.472s  |   1.472s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_023.smt2                             |   0.530s  |   0.530s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_024.smt2                             |  15.533s  |  15.533s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_025.smt2                             |  12.816s  |  12.816s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_026.smt2                             |   0.230s  |   0.230s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_027.smt2                             |   0.453s  |   0.453s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_028.smt2                             |   0.904s  |   0.904s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_029.smt2                             |  10.732s  |  10.732s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_030.smt2                             |   5.428s  |   5.428s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_031.smt2                             |  20.018s  |  20.018s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_032.smt2                             |   0.366s  |   0.366s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_033.smt2                             |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_034.smt2                             |   5.512s  |   5.512s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_035.smt2                             |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_036.smt2                             |  20.018s  |  20.018s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_037.smt2                             |   0.367s  |   0.367s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_038.smt2                             |  20.018s  |  20.018s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_039.smt2                             |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_040.smt2                             |  20.012s  |  20.012s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_041.smt2                             |  10.391s  |  10.391s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_042.smt2                             |   0.311s  |   0.311s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_043.smt2                             |   1.324s  |   1.324s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_044.smt2                             |   1.679s  |   1.679s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_045.smt2                             |   3.605s  |   3.605s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_046.smt2                             |   6.442s  |   6.442s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_047.smt2                             |   1.152s  |   1.152s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_048.smt2                             |   4.247s  |   4.247s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_049.smt2                             |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_050.smt2                             |  20.013s  |  20.013s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_051.smt2                             |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_052.smt2                             |  16.692s  |  16.692s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_053.smt2                             |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_054.smt2                             |   2.409s  |   2.409s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_055.smt2                             |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_056.smt2                             |   1.600s  |   1.600s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_057.smt2                             |   0.421s  |   0.421s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_058.smt2                             |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_059.smt2                             |  20.013s  |  20.013s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_060.smt2                             |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_061.smt2                             |   3.651s  |   3.651s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_062.smt2                             |   0.988s  |   0.988s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_063.smt2                             |   4.443s  |   4.443s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_064.smt2                             |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_065.smt2                             |   3.305s  |   3.305s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_066.smt2                             |   0.297s  |   0.297s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_067.smt2                             |  14.554s  |  14.554s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_068.smt2                             |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_069.smt2                             |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_070.smt2                             |   3.434s  |   3.434s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_071.smt2                             |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_072.smt2                             |   1.567s  |   1.567s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_073.smt2                             |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_074.smt2                             |  12.498s  |  12.498s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_075.smt2                             |   0.794s  |   0.794s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_076.smt2                             |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_077.smt2                             |   4.573s  |   4.573s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_078.smt2                             |   0.366s  |   0.366s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_079.smt2                             |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_080.smt2                             |   1.624s  |   1.624s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_081.smt2                             |   7.727s  |   7.727s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_082.smt2                             |  10.535s  |  10.535s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_083.smt2                             |   0.794s  |   0.794s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_084.smt2                             |  20.014s  |  20.014s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_085.smt2                             |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_086.smt2                             |   0.328s  |   0.328s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_087.smt2                             |   7.413s  |   7.413s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_088.smt2                             |   5.973s  |   5.973s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_089.smt2                             |   1.265s  |   1.265s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_090.smt2                             |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_091.smt2                             |   1.369s  |   1.369s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_092.smt2                             |   0.655s  |   0.655s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_093.smt2                             |   2.795s  |   2.795s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_094.smt2                             |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_095.smt2                             |   1.416s  |   1.416s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_096.smt2                             |   5.843s  |   5.843s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_097.smt2                             |   3.925s  |   3.925s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_098.smt2                             |   0.292s  |   0.292s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_099.smt2                             |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_100.smt2                             |   2.091s  |   2.091s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_101.smt2                             |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_102.smt2                             |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_103.smt2                             |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_104.smt2                             |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_105.smt2                             |  20.011s  |  20.011s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_106.smt2                             |   2.078s  |   2.078s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_107.smt2                             |   0.230s  |   0.230s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_108.smt2                             |   4.702s  |   4.702s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_109.smt2                             |   3.648s  |   3.648s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_110.smt2                             |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_111.smt2                             |   6.040s  |   6.040s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_112.smt2                             |  20.034s  |  20.034s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_113.smt2                             |  20.014s  |  20.014s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_114.smt2                             |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_115.smt2                             |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_116.smt2                             |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_117.smt2                             |   0.298s  |   0.298s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_118.smt2                             |   5.846s  |   5.846s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_119.smt2                             |   1.061s  |   1.061s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_120.smt2                             |   7.977s  |   7.977s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_121.smt2                             |   9.030s  |   9.030s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_122.smt2                             |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_123.smt2                             |   0.243s  |   0.243s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_124.smt2                             |   1.901s  |   1.901s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_125.smt2                             |   5.880s  |   5.880s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_126.smt2                             |   0.225s  |   0.225s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_127.smt2                             |   4.879s  |   4.879s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_128.smt2                             |   4.888s  |   4.888s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_129.smt2                             |   4.250s  |   4.250s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_130.smt2                             |   1.667s  |   1.667s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_131.smt2                             |   1.520s  |   1.520s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_132.smt2                             |   2.289s  |   2.289s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_133.smt2                             |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_134.smt2                             |   3.617s  |   3.617s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_135.smt2                             |   2.553s  |   2.553s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_136.smt2                             |   3.376s  |   3.376s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_137.smt2                             |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_138.smt2                             |   2.666s  |   2.666s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_139.smt2                             |   5.854s  |   5.854s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_140.smt2                             |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_141.smt2                             |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_142.smt2                             |   0.595s  |   0.595s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_143.smt2                             |   0.428s  |   0.428s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_144.smt2                             |   0.834s  |   0.834s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_145.smt2                             |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_146.smt2                             |   2.686s  |   2.686s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_147.smt2                             |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_148.smt2                             |   1.605s  |   1.605s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_149.smt2                             |   0.362s  |   0.362s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_150.smt2                             |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_151.smt2                             |  10.290s  |  10.290s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_152.smt2                             |   0.610s  |   0.610s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_153.smt2                             |  10.031s  |  10.031s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_154.smt2                             |   1.174s  |   1.174s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_155.smt2                             |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_156.smt2                             |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_157.smt2                             |  19.864s  |  19.864s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_158.smt2                             |   4.848s  |   4.848s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_159.smt2                             |   8.759s  |   8.759s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_160.smt2                             |   0.217s  |   0.217s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_161.smt2                             |   0.584s  |   0.584s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_162.smt2                             |   0.936s  |   0.936s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_163.smt2                             |   0.677s  |   0.677s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_164.smt2                             |  15.504s  |  15.504s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_165.smt2                             |  20.014s  |  20.014s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_166.smt2                             |  20.022s  |  20.022s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_167.smt2                             |   6.788s  |   6.788s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_168.smt2                             |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_169.smt2                             |   1.556s  |   1.556s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_170.smt2                             |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_171.smt2                             |  20.012s  |  20.012s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_172.smt2                             |  20.020s  |  20.020s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_173.smt2                             |  11.025s  |  11.025s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_174.smt2                             |   4.453s  |   4.453s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_175.smt2                             |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_176.smt2                             |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_177.smt2                             |   1.772s  |   1.772s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_178.smt2                             |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_179.smt2                             |   0.300s  |   0.300s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_180.smt2                             |   3.837s  |   3.837s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_181.smt2                             |   1.417s  |   1.417s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_182.smt2                             |  20.045s  |  20.045s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_183.smt2                             |   0.786s  |   0.786s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_184.smt2                             |   3.501s  |   3.501s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_185.smt2                             |   0.614s  |   0.614s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_186.smt2                             |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_187.smt2                             |  20.020s  |  20.020s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_188.smt2                             |   0.953s  |   0.953s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_189.smt2                             |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_190.smt2                             |   3.531s  |   3.531s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_191.smt2                             |   2.981s  |   2.981s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_192.smt2                             |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_193.smt2                             |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_194.smt2                             |  20.013s  |  20.013s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_195.smt2                             |   1.064s  |   1.064s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_196.smt2                             |   0.456s  |   0.456s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_197.smt2                             |  20.011s  |  20.011s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_198.smt2                             |  15.367s  |  15.367s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_199.smt2                             |   9.692s  |   9.692s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_200.smt2                             |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_201.smt2                             |  20.015s  |  20.015s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_202.smt2                             |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_203.smt2                             |   0.560s  |   0.560s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_204.smt2                             |   6.756s  |   6.756s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_205.smt2                             |   0.365s  |   0.365s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_206.smt2                             |   1.186s  |   1.186s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_207.smt2                             |   1.537s  |   1.537s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_208.smt2                             |   4.733s  |   4.733s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_209.smt2                             |   7.924s  |   7.924s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_210.smt2                             |   0.687s  |   0.687s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_211.smt2                             |  10.970s  |  10.970s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_212.smt2                             |   0.346s  |   0.346s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_213.smt2                             |   0.353s  |   0.353s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_214.smt2                             |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_215.smt2                             |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_216.smt2                             |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_217.smt2                             |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_218.smt2                             |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_219.smt2                             |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_220.smt2                             |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_221.smt2                             |   0.221s  |   0.221s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_222.smt2                             |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_223.smt2                             |   1.331s  |   1.331s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_224.smt2                             |   6.872s  |   6.872s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_225.smt2                             |   0.263s  |   0.263s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_226.smt2                             |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_227.smt2                             |   1.176s  |   1.176s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_228.smt2                             |   0.632s  |   0.632s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_229.smt2                             |   9.539s  |   9.539s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_230.smt2                             |   2.783s  |   2.783s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_231.smt2                             |   0.433s  |   0.433s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_232.smt2                             |   0.218s  |   0.218s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_233.smt2                             |   2.547s  |   2.547s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_234.smt2                             |   6.748s  |   6.748s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_235.smt2                             |   0.503s  |   0.503s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_236.smt2                             |   0.470s  |   0.470s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_237.smt2                             |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_238.smt2                             |   6.481s  |   6.481s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_239.smt2                             |  20.013s  |  20.013s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_240.smt2                             |   8.904s  |   8.904s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_241.smt2                             |   1.034s  |   1.034s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_242.smt2                             |   0.460s  |   0.460s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_243.smt2                             |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_244.smt2                             |   0.744s  |   0.744s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_245.smt2                             |  20.028s  |  20.028s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_246.smt2                             |   9.800s  |   9.800s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_247.smt2                             |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_248.smt2                             |   5.940s  |   5.940s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_249.smt2                             |   2.995s  |   2.995s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_250.smt2                             |   7.780s  |   7.780s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_251.smt2                             |   2.356s  |   2.356s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_252.smt2                             |   1.643s  |   1.643s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_253.smt2                             |   7.951s  |   7.951s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_254.smt2                             |   5.596s  |   5.596s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_255.smt2                             |   0.259s  |   0.259s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_256.smt2                             |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_257.smt2                             |   0.796s  |   0.796s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_258.smt2                             |   1.856s  |   1.856s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_259.smt2                             |  20.016s  |  20.016s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_260.smt2                             |   0.270s  |   0.270s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_261.smt2                             |   1.581s  |   1.581s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_262.smt2                             |   3.847s  |   3.847s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_263.smt2                             |   0.171s  |   0.171s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_264.smt2                             |  20.050s  |  20.050s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_265.smt2                             |  20.035s  |  20.035s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_266.smt2                             |  18.694s  |  18.694s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_267.smt2                             |  20.014s  |  20.014s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_268.smt2                             |   2.727s  |   2.727s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_269.smt2                             |   1.943s  |   1.943s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_270.smt2                             |  20.057s  |  20.057s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_271.smt2                             |  13.823s  |  13.823s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_272.smt2                             |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_273.smt2                             |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_274.smt2                             |   0.267s  |   0.267s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_275.smt2                             |   0.196s  |   0.196s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_276.smt2                             |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_277.smt2                             |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_278.smt2                             |   2.019s  |   2.019s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_279.smt2                             |   6.481s  |   6.481s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_280.smt2                             |   1.437s  |   1.437s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_281.smt2                             |   5.863s  |   5.863s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_282.smt2                             |   1.547s  |   1.547s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_283.smt2                             |   1.317s  |   1.317s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_284.smt2                             |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_285.smt2                             |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_286.smt2                             |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_287.smt2                             |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_288.smt2                             |  10.069s  |  10.069s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_289.smt2                             |   1.413s  |   1.413s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_290.smt2                             |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_291.smt2                             |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_292.smt2                             |   3.150s  |   3.150s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_293.smt2                             |   1.769s  |   1.769s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_294.smt2                             |   1.875s  |   1.875s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_295.smt2                             |   1.389s  |   1.389s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_296.smt2                             |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_297.smt2                             |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_298.smt2                             |   0.951s  |   0.951s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_299.smt2                             |   2.649s  |   2.649s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir2/formula_300.smt2                             |   0.371s  |   0.371s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_001.smt2                             |   1.073s  |   1.073s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_002.smt2                             |   0.181s  |   0.181s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_003.smt2                             |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_004.smt2                             |   0.352s  |   0.352s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_005.smt2                             |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_006.smt2                             |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_007.smt2                             |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_008.smt2                             |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_009.smt2                             |   9.066s  |   9.066s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_010.smt2                             |   1.009s  |   1.009s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_011.smt2                             |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_012.smt2                             |   0.953s  |   0.953s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_013.smt2                             |   8.993s  |   8.993s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_014.smt2                             |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_015.smt2                             |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_016.smt2                             |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_017.smt2                             |   0.360s  |   0.360s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_018.smt2                             |   0.625s  |   0.625s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_019.smt2                             |   8.436s  |   8.436s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_020.smt2                             |  20.055s  |  20.055s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_021.smt2                             |   0.479s  |   0.479s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_022.smt2                             |   5.221s  |   5.221s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_023.smt2                             |  19.369s  |  19.369s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_024.smt2                             |  20.039s  |  20.039s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_025.smt2                             |   2.746s  |   2.746s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_026.smt2                             |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_027.smt2                             |   0.378s  |   0.378s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_028.smt2                             |   0.687s  |   0.687s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_029.smt2                             |   6.546s  |   6.546s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_030.smt2                             |   0.330s  |   0.330s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_031.smt2                             |   0.458s  |   0.458s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_032.smt2                             |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_033.smt2                             |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_034.smt2                             |  20.045s  |  20.045s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_035.smt2                             |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_036.smt2                             |   9.593s  |   9.593s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_037.smt2                             |   0.377s  |   0.377s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_038.smt2                             |   1.053s  |   1.053s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_039.smt2                             |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_040.smt2                             |   9.456s  |   9.456s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_041.smt2                             |   0.758s  |   0.758s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_042.smt2                             |   0.316s  |   0.316s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_043.smt2                             |   4.026s  |   4.026s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_044.smt2                             |   1.975s  |   1.975s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_045.smt2                             |   1.191s  |   1.191s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_046.smt2                             |   0.383s  |   0.383s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_047.smt2                             |   1.009s  |   1.009s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_048.smt2                             |   1.415s  |   1.415s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_049.smt2                             |   0.215s  |   0.215s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_050.smt2                             |  20.045s  |  20.045s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_051.smt2                             |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_052.smt2                             |   4.574s  |   4.574s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_053.smt2                             |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_054.smt2                             |   0.500s  |   0.500s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_055.smt2                             |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_056.smt2                             |   1.680s  |   1.680s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_057.smt2                             |   0.910s  |   0.910s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_058.smt2                             |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_059.smt2                             |   2.394s  |   2.394s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_060.smt2                             |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_061.smt2                             |  20.045s  |  20.045s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_062.smt2                             |   1.899s  |   1.899s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_063.smt2                             |   0.271s  |   0.271s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_064.smt2                             |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_065.smt2                             |   8.587s  |   8.587s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_066.smt2                             |   0.361s  |   0.361s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_067.smt2                             |   3.008s  |   3.008s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_068.smt2                             |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_069.smt2                             |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_070.smt2                             |   1.497s  |   1.497s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_071.smt2                             |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_072.smt2                             |   0.450s  |   0.450s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_073.smt2                             |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_074.smt2                             |   1.645s  |   1.645s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_075.smt2                             |   0.379s  |   0.379s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_076.smt2                             |   1.646s  |   1.646s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_077.smt2                             |   5.324s  |   5.324s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_078.smt2                             |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_079.smt2                             |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_080.smt2                             |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_081.smt2                             |   3.183s  |   3.183s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_082.smt2                             |   0.885s  |   0.885s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_083.smt2                             |   0.239s  |   0.239s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_084.smt2                             |  11.445s  |  11.445s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_085.smt2                             |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_086.smt2                             |   0.238s  |   0.238s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_087.smt2                             |   0.756s  |   0.756s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_088.smt2                             |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_089.smt2                             |   0.280s  |   0.280s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_090.smt2                             |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_091.smt2                             |   0.986s  |   0.986s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_092.smt2                             |   0.359s  |   0.359s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_093.smt2                             |   0.948s  |   0.948s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_094.smt2                             |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_095.smt2                             |   8.294s  |   8.294s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_096.smt2                             |  12.872s  |  12.872s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_097.smt2                             |   0.206s  |   0.206s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_098.smt2                             |   0.729s  |   0.729s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_099.smt2                             |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_100.smt2                             |   1.200s  |   1.200s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_101.smt2                             |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_102.smt2                             |   0.321s  |   0.321s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_103.smt2                             |   0.267s  |   0.267s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_104.smt2                             |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_105.smt2                             |   2.820s  |   2.820s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_106.smt2                             |  20.048s  |  20.048s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_107.smt2                             |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_108.smt2                             |   2.936s  |   2.936s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_109.smt2                             |   6.959s  |   6.959s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_110.smt2                             |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_111.smt2                             |   2.489s  |   2.489s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_112.smt2                             |   6.120s  |   6.120s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_113.smt2                             |   1.364s  |   1.364s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_114.smt2                             |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_115.smt2                             |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_116.smt2                             |   0.242s  |   0.242s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_117.smt2                             |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_118.smt2                             |  20.080s  |  20.080s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_119.smt2                             |   5.070s  |   5.070s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_120.smt2                             |   5.567s  |   5.567s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_121.smt2                             |  17.922s  |  17.922s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_122.smt2                             |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_123.smt2                             |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_124.smt2                             |   0.671s  |   0.671s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_125.smt2                             |   1.739s  |   1.739s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_126.smt2                             |   0.304s  |   0.304s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_127.smt2                             |   1.181s  |   1.181s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_128.smt2                             |  16.851s  |  16.851s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_129.smt2                             |   3.433s  |   3.433s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_130.smt2                             |   3.493s  |   3.493s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_131.smt2                             |   1.704s  |   1.704s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_132.smt2                             |   0.969s  |   0.969s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_133.smt2                             |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_134.smt2                             |  20.044s  |  20.044s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_135.smt2                             |   0.785s  |   0.785s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_136.smt2                             |   9.481s  |   9.481s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_137.smt2                             |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_138.smt2                             |  20.064s  |  20.064s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_139.smt2                             |   3.425s  |   3.425s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_140.smt2                             |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_141.smt2                             |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_142.smt2                             |   1.815s  |   1.815s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_143.smt2                             |   0.842s  |   0.842s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_144.smt2                             |   0.988s  |   0.988s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_145.smt2                             |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_146.smt2                             |   2.197s  |   2.197s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_147.smt2                             |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_148.smt2                             |   1.086s  |   1.086s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_149.smt2                             |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_150.smt2                             |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_151.smt2                             |   0.712s  |   0.712s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_152.smt2                             |   0.808s  |   0.808s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_153.smt2                             |  20.012s  |  20.012s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_154.smt2                             |   1.045s  |   1.045s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_155.smt2                             |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_156.smt2                             |   0.525s  |   0.525s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_157.smt2                             |  12.898s  |  12.898s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_158.smt2                             |   1.372s  |   1.372s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_159.smt2                             |  20.021s  |  20.021s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_160.smt2                             |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_161.smt2                             |   0.434s  |   0.434s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_162.smt2                             |   1.541s  |   1.541s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_163.smt2                             |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_164.smt2                             |   8.918s  |   8.918s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_165.smt2                             |   7.835s  |   7.835s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_166.smt2                             |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_167.smt2                             |   3.028s  |   3.028s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_168.smt2                             |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_169.smt2                             |  18.469s  |  18.469s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_170.smt2                             |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_171.smt2                             |   5.708s  |   5.708s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_172.smt2                             |   5.883s  |   5.883s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_173.smt2                             |   0.996s  |   0.996s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_174.smt2                             |   7.861s  |   7.861s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_175.smt2                             |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_176.smt2                             |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_177.smt2                             |   0.220s  |   0.220s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_178.smt2                             |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_179.smt2                             |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_180.smt2                             |  10.213s  |  10.213s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_181.smt2                             |   5.579s  |   5.579s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_182.smt2                             |  18.474s  |  18.474s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_183.smt2                             |  13.931s  |  13.931s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_184.smt2                             |   3.821s  |   3.821s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_185.smt2                             |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_186.smt2                             |   0.731s  |   0.731s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_187.smt2                             |  20.062s  |  20.062s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_188.smt2                             |   2.798s  |   2.798s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_189.smt2                             |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_190.smt2                             |   0.336s  |   0.336s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_191.smt2                             |  11.485s  |  11.485s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_192.smt2                             |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_193.smt2                             |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_194.smt2                             |   5.058s  |   5.058s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_195.smt2                             |   1.551s  |   1.551s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_196.smt2                             |   0.290s  |   0.290s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_197.smt2                             |  16.922s  |  16.922s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_198.smt2                             |   2.715s  |   2.715s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_199.smt2                             |   3.155s  |   3.155s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_200.smt2                             |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_201.smt2                             |   0.435s  |   0.435s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_202.smt2                             |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_203.smt2                             |   2.453s  |   2.453s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_204.smt2                             |   6.730s  |   6.730s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_205.smt2                             |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_206.smt2                             |   3.282s  |   3.282s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_207.smt2                             |   0.415s  |   0.415s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_208.smt2                             |  20.038s  |  20.038s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_209.smt2                             |  12.460s  |  12.460s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_210.smt2                             |   0.456s  |   0.456s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_211.smt2                             |   4.062s  |   4.062s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_212.smt2                             |   0.393s  |   0.393s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_213.smt2                             |  20.011s  |  20.011s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_214.smt2                             |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_215.smt2                             |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_216.smt2                             |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_217.smt2                             |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_218.smt2                             |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_219.smt2                             |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_220.smt2                             |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_221.smt2                             |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_222.smt2                             |  20.012s  |  20.012s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_223.smt2                             |   0.747s  |   0.747s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_224.smt2                             |   8.540s  |   8.540s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_225.smt2                             |   0.812s  |   0.812s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_226.smt2                             |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_227.smt2                             |   0.629s  |   0.629s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_228.smt2                             |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_229.smt2                             |   1.589s  |   1.589s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_230.smt2                             |   1.186s  |   1.186s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_231.smt2                             |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_232.smt2                             |   0.943s  |   0.943s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_233.smt2                             |   4.275s  |   4.275s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_234.smt2                             |   2.256s  |   2.256s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_235.smt2                             |   0.963s  |   0.963s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_236.smt2                             |   0.253s  |   0.253s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_237.smt2                             |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_238.smt2                             |   0.397s  |   0.397s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_239.smt2                             |   1.252s  |   1.252s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_240.smt2                             |   2.271s  |   2.271s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_241.smt2                             |   0.985s  |   0.985s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_242.smt2                             |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_243.smt2                             |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_244.smt2                             |   2.339s  |   2.339s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_245.smt2                             |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_246.smt2                             |  20.043s  |  20.043s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_247.smt2                             |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_248.smt2                             |   3.266s  |   3.266s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_249.smt2                             |   1.354s  |   1.354s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_250.smt2                             |   4.576s  |   4.576s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_251.smt2                             |  20.050s  |  20.050s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_252.smt2                             |   1.403s  |   1.403s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_253.smt2                             |  13.822s  |  13.822s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_254.smt2                             |   0.514s  |   0.514s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_255.smt2                             |   0.371s  |   0.371s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_256.smt2                             |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_257.smt2                             |   3.394s  |   3.394s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_258.smt2                             |   1.520s  |   1.520s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_259.smt2                             |   8.589s  |   8.589s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_260.smt2                             |   1.799s  |   1.799s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_261.smt2                             |   9.449s  |   9.449s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_262.smt2                             |   1.923s  |   1.923s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_263.smt2                             |   0.322s  |   0.322s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_264.smt2                             |   1.171s  |   1.171s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_265.smt2                             |   0.225s  |   0.225s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_266.smt2                             |   1.232s  |   1.232s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_267.smt2                             |   3.391s  |   3.391s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_268.smt2                             |   2.157s  |   2.157s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_269.smt2                             |   0.627s  |   0.627s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_270.smt2                             |   2.640s  |   2.640s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_271.smt2                             |   1.485s  |   1.485s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_272.smt2                             |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_273.smt2                             |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_274.smt2                             |   0.445s  |   0.445s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_275.smt2                             |   1.134s  |   1.134s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_276.smt2                             |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_277.smt2                             |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_278.smt2                             |   0.604s  |   0.604s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_279.smt2                             |   3.269s  |   3.269s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_280.smt2                             |   0.522s  |   0.522s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_281.smt2                             |   1.633s  |   1.633s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_282.smt2                             |   0.460s  |   0.460s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_283.smt2                             |   1.799s  |   1.799s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_284.smt2                             |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_285.smt2                             |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_286.smt2                             |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_287.smt2                             |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_288.smt2                             |   2.445s  |   2.445s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_289.smt2                             |   5.000s  |   5.000s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_290.smt2                             |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_291.smt2                             |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_292.smt2                             |  12.486s  |  12.486s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_293.smt2                             |   4.689s  |   4.689s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_294.smt2                             |   0.931s  |   0.931s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_295.smt2                             |   0.308s  |   0.308s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_296.smt2                             |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_297.smt2                             |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_298.smt2                             |   0.435s  |   0.435s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_299.smt2                             |   0.487s  |   0.487s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir3/formula_300.smt2                             |   2.876s  |   2.876s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_001.smt2                             |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_002.smt2                             |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_003.smt2                             |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_004.smt2                             |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_005.smt2                             |   0.250s  |   0.250s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_006.smt2                             |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_007.smt2                             |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_008.smt2                             |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_009.smt2                             |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_010.smt2                             |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_011.smt2                             |   3.646s  |   3.646s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_012.smt2                             |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_013.smt2                             |   0.169s  |   0.169s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_014.smt2                             |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_015.smt2                             |   6.800s  |   6.800s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_016.smt2                             |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_017.smt2                             |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_018.smt2                             |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_019.smt2                             |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_020.smt2                             |   3.652s  |   3.652s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_021.smt2                             |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_022.smt2                             |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_023.smt2                             |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_024.smt2                             |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_025.smt2                             |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_026.smt2                             |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_027.smt2                             |  12.238s  |  12.238s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_028.smt2                             |   0.495s  |   0.495s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_029.smt2                             |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_030.smt2                             |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_031.smt2                             |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_032.smt2                             |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_033.smt2                             |   0.662s  |   0.662s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_034.smt2                             |   0.539s  |   0.539s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_035.smt2                             |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_036.smt2                             |   0.621s  |   0.621s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_037.smt2                             |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_038.smt2                             |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_039.smt2                             |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_040.smt2                             |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_041.smt2                             |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_042.smt2                             |   5.305s  |   5.305s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_043.smt2                             |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_044.smt2                             |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_045.smt2                             |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_046.smt2                             |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_047.smt2                             |   5.951s  |   5.951s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_048.smt2                             |   3.770s  |   3.770s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_049.smt2                             |   0.223s  |   0.223s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_050.smt2                             |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_051.smt2                             |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_052.smt2                             |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_053.smt2                             |   0.223s  |   0.223s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_054.smt2                             |   1.619s  |   1.619s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_055.smt2                             |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_056.smt2                             |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_057.smt2                             |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_058.smt2                             |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_059.smt2                             |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_060.smt2                             |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_061.smt2                             |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_062.smt2                             |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_063.smt2                             |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_064.smt2                             |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_065.smt2                             |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_066.smt2                             |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_067.smt2                             |   5.711s  |   5.711s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_068.smt2                             |   0.253s  |   0.253s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_069.smt2                             |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_070.smt2                             |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_071.smt2                             |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_072.smt2                             |   0.174s  |   0.174s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_073.smt2                             |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_074.smt2                             |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_075.smt2                             |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_076.smt2                             |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_077.smt2                             |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_078.smt2                             |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_079.smt2                             |   0.785s  |   0.785s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_080.smt2                             |   4.669s  |   4.669s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_081.smt2                             |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_082.smt2                             |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_083.smt2                             |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_084.smt2                             |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_085.smt2                             |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_086.smt2                             |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_087.smt2                             |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_088.smt2                             |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_089.smt2                             |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_090.smt2                             |   3.821s  |   3.821s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_091.smt2                             |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_092.smt2                             |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_093.smt2                             |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_094.smt2                             |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_095.smt2                             |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_096.smt2                             |   1.012s  |   1.012s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_097.smt2                             |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_098.smt2                             |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_099.smt2                             |   0.186s  |   0.186s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_100.smt2                             |   0.221s  |   0.221s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_101.smt2                             |   7.358s  |   7.358s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_102.smt2                             |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_103.smt2                             |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_104.smt2                             |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_105.smt2                             |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_106.smt2                             |   0.293s  |   0.293s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_107.smt2                             |  13.422s  |  13.422s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_108.smt2                             |   3.146s  |   3.146s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_109.smt2                             |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_110.smt2                             |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_111.smt2                             |   0.622s  |   0.622s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_112.smt2                             |   6.539s  |   6.539s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_113.smt2                             |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_114.smt2                             |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_115.smt2                             |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_116.smt2                             |   0.314s  |   0.314s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_117.smt2                             |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_118.smt2                             |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_119.smt2                             |   0.833s  |   0.833s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_120.smt2                             |   0.166s  |   0.166s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_121.smt2                             |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_122.smt2                             |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_123.smt2                             |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_124.smt2                             |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_125.smt2                             |   1.119s  |   1.119s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_126.smt2                             |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_127.smt2                             |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_128.smt2                             |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_129.smt2                             |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_130.smt2                             |   0.252s  |   0.252s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_131.smt2                             |   4.223s  |   4.223s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_132.smt2                             |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_133.smt2                             |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_134.smt2                             |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_135.smt2                             |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_136.smt2                             |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_137.smt2                             |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_138.smt2                             |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_139.smt2                             |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_140.smt2                             |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_141.smt2                             |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_142.smt2                             |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_143.smt2                             |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_144.smt2                             |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_145.smt2                             |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_146.smt2                             |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_147.smt2                             |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_148.smt2                             |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_149.smt2                             |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_150.smt2                             |   1.503s  |   1.503s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_151.smt2                             |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_152.smt2                             |   0.441s  |   0.441s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_153.smt2                             |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_154.smt2                             |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_155.smt2                             |   0.723s  |   0.723s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_156.smt2                             |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_157.smt2                             |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_158.smt2                             |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_159.smt2                             |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_160.smt2                             |   0.795s  |   0.795s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_161.smt2                             |   0.205s  |   0.205s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_162.smt2                             |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_163.smt2                             |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_164.smt2                             |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_165.smt2                             |   0.663s  |   0.663s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_166.smt2                             |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_167.smt2                             |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_168.smt2                             |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_169.smt2                             |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_170.smt2                             |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_171.smt2                             |   9.175s  |   9.175s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_172.smt2                             |   2.225s  |   2.225s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_173.smt2                             |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_174.smt2                             |   3.823s  |   3.823s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_175.smt2                             |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_176.smt2                             |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_177.smt2                             |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_178.smt2                             |   0.733s  |   0.733s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_179.smt2                             |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_180.smt2                             |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_181.smt2                             |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_182.smt2                             |  10.955s  |  10.955s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_183.smt2                             |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_184.smt2                             |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_185.smt2                             |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_186.smt2                             |   1.228s  |   1.228s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_187.smt2                             |   4.473s  |   4.473s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_188.smt2                             |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_189.smt2                             |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_190.smt2                             |   2.448s  |   2.448s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_191.smt2                             |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_192.smt2                             |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_193.smt2                             |   0.348s  |   0.348s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_194.smt2                             |   1.256s  |   1.256s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_195.smt2                             |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_196.smt2                             |   0.854s  |   0.854s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_197.smt2                             |   0.398s  |   0.398s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_198.smt2                             |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_199.smt2                             |   2.651s  |   2.651s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_200.smt2                             |  17.955s  |  17.955s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_201.smt2                             |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_202.smt2                             |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_203.smt2                             |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_204.smt2                             |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_205.smt2                             |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_206.smt2                             |   1.085s  |   1.085s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_207.smt2                             |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_208.smt2                             |   1.068s  |   1.068s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_209.smt2                             |   0.276s  |   0.276s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_210.smt2                             |   2.237s  |   2.237s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_211.smt2                             |  20.015s  |  20.015s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_212.smt2                             |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_213.smt2                             |   0.762s  |   0.762s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_214.smt2                             |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_215.smt2                             |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_216.smt2                             |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_217.smt2                             |   0.427s  |   0.427s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_218.smt2                             |   3.824s  |   3.824s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_219.smt2                             |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_220.smt2                             |   1.055s  |   1.055s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_221.smt2                             |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_222.smt2                             |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_223.smt2                             |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_224.smt2                             |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_225.smt2                             |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_226.smt2                             |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_227.smt2                             |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_228.smt2                             |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_229.smt2                             |   7.483s  |   7.483s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_230.smt2                             |  10.894s  |  10.894s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_231.smt2                             |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_232.smt2                             |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_233.smt2                             |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_234.smt2                             |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_235.smt2                             |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_236.smt2                             |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_237.smt2                             |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_238.smt2                             |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_239.smt2                             |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_240.smt2                             |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_241.smt2                             |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_242.smt2                             |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_243.smt2                             |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_244.smt2                             |   0.247s  |   0.247s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_245.smt2                             |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_246.smt2                             |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_247.smt2                             |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_248.smt2                             |   2.257s  |   2.257s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_249.smt2                             |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_250.smt2                             |   1.647s  |   1.647s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_251.smt2                             |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_252.smt2                             |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_253.smt2                             |   5.306s  |   5.306s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_254.smt2                             |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_255.smt2                             |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_256.smt2                             |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_257.smt2                             |   8.406s  |   8.406s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_258.smt2                             |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_259.smt2                             |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_260.smt2                             |   4.170s  |   4.170s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_261.smt2                             |   3.347s  |   3.347s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_262.smt2                             |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_263.smt2                             |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_264.smt2                             |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_265.smt2                             |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_266.smt2                             |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_267.smt2                             |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_268.smt2                             |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_269.smt2                             |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_270.smt2                             |   2.529s  |   2.529s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_271.smt2                             |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_272.smt2                             |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_273.smt2                             |   0.738s  |   0.738s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_274.smt2                             |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_275.smt2                             |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_276.smt2                             |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_277.smt2                             |   0.305s  |   0.305s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_278.smt2                             |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_279.smt2                             |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_280.smt2                             |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_281.smt2                             |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_282.smt2                             |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_283.smt2                             |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_284.smt2                             |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_285.smt2                             |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_286.smt2                             |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_287.smt2                             |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_288.smt2                             |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_289.smt2                             |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_290.smt2                             |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_291.smt2                             |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_292.smt2                             |   0.235s  |   0.235s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_293.smt2                             |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_294.smt2                             |   0.928s  |   0.928s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_295.smt2                             |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_296.smt2                             |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_297.smt2                             |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_298.smt2                             |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_299.smt2                             |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir4/formula_300.smt2                             |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_001.smt2                             |  20.013s  |  20.013s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_002.smt2                             |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_003.smt2                             |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_004.smt2                             |   0.463s  |   0.463s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_005.smt2                             |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_006.smt2                             |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_007.smt2                             |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_008.smt2                             |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_009.smt2                             |  20.020s  |  20.020s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_010.smt2                             |  20.011s  |  20.011s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_011.smt2                             |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_012.smt2                             |   1.529s  |   1.529s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_013.smt2                             |  20.015s  |  20.015s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_014.smt2                             |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_015.smt2                             |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_016.smt2                             |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_017.smt2                             |   0.358s  |   0.358s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_018.smt2                             |  18.937s  |  18.937s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_019.smt2                             |  16.884s  |  16.884s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_020.smt2                             |  20.014s  |  20.014s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_021.smt2                             |   0.305s  |   0.305s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_022.smt2                             |   8.635s  |   8.635s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_023.smt2                             |   3.004s  |   3.004s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_024.smt2                             |   7.447s  |   7.447s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_025.smt2                             |  15.488s  |  15.488s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_026.smt2                             |   0.259s  |   0.259s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_027.smt2                             |  14.296s  |  14.296s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_028.smt2                             |  13.419s  |  13.419s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_029.smt2                             |  20.016s  |  20.016s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_030.smt2                             |   0.281s  |   0.281s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_031.smt2                             |   0.529s  |   0.529s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_032.smt2                             |   0.601s  |   0.601s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_033.smt2                             |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_034.smt2                             |  13.549s  |  13.549s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_035.smt2                             |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_036.smt2                             |  20.045s  |  20.045s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_037.smt2                             |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_038.smt2                             |   9.567s  |   9.567s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_039.smt2                             |   0.291s  |   0.291s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_040.smt2                             |  12.743s  |  12.743s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_041.smt2                             |   1.455s  |   1.455s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_042.smt2                             |   0.775s  |   0.775s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_043.smt2                             |  20.013s  |  20.013s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_044.smt2                             |   7.056s  |   7.056s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_045.smt2                             |  19.175s  |  19.175s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_046.smt2                             |   0.658s  |   0.658s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_047.smt2                             |   1.523s  |   1.523s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_048.smt2                             |  20.019s  |  20.019s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_049.smt2                             |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_050.smt2                             |  10.913s  |  10.913s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_051.smt2                             |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_052.smt2                             |  12.637s  |  12.637s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_053.smt2                             |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_054.smt2                             |   3.401s  |   3.401s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_055.smt2                             |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_056.smt2                             |  20.011s  |  20.011s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_057.smt2                             |   1.210s  |   1.210s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_058.smt2                             |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_059.smt2                             |  13.941s  |  13.941s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_060.smt2                             |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_061.smt2                             |  20.015s  |  20.015s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_062.smt2                             |  20.012s  |  20.012s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_063.smt2                             |   1.984s  |   1.984s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_064.smt2                             |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_065.smt2                             |  11.756s  |  11.756s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_066.smt2                             |   0.504s  |   0.504s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_067.smt2                             |  19.817s  |  19.817s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_068.smt2                             |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_069.smt2                             |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_070.smt2                             |   3.122s  |   3.122s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_071.smt2                             |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_072.smt2                             |   1.905s  |   1.905s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_073.smt2                             |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_074.smt2                             |   5.328s  |   5.328s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_075.smt2                             |   7.742s  |   7.742s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_076.smt2                             |  13.937s  |  13.937s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_077.smt2                             |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_078.smt2                             |   0.297s  |   0.297s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_079.smt2                             |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_080.smt2                             |   9.770s  |   9.770s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_081.smt2                             |  15.136s  |  15.136s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_082.smt2                             |  17.381s  |  17.381s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_083.smt2                             |   0.715s  |   0.715s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_084.smt2                             |  18.867s  |  18.867s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_085.smt2                             |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_086.smt2                             |   0.329s  |   0.329s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_087.smt2                             |   3.002s  |   3.002s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_088.smt2                             |   3.430s  |   3.430s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_089.smt2                             |  16.177s  |  16.177s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_090.smt2                             |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_091.smt2                             |   4.886s  |   4.886s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_092.smt2                             |   6.682s  |   6.682s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_093.smt2                             |   1.367s  |   1.367s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_094.smt2                             |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_095.smt2                             |  20.020s  |  20.020s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_096.smt2                             |  19.373s  |  19.373s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_097.smt2                             |   0.355s  |   0.355s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_098.smt2                             |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_099.smt2                             |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_100.smt2                             |   1.401s  |   1.401s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_101.smt2                             |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_102.smt2                             |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_103.smt2                             |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_104.smt2                             |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_105.smt2                             |  20.044s  |  20.044s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_106.smt2                             |  14.081s  |  14.081s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_107.smt2                             |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_108.smt2                             |   5.485s  |   5.485s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_109.smt2                             |  20.020s  |  20.020s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_110.smt2                             |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_111.smt2                             |   2.772s  |   2.772s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_112.smt2                             |  20.015s  |  20.015s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_113.smt2                             |   6.856s  |   6.856s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_114.smt2                             |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_115.smt2                             |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_116.smt2                             |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_117.smt2                             |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_118.smt2                             |  20.018s  |  20.018s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_119.smt2                             |  20.013s  |  20.013s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_120.smt2                             |  17.274s  |  17.274s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_121.smt2                             |  20.013s  |  20.013s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_122.smt2                             |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_123.smt2                             |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_124.smt2                             |   2.174s  |   2.174s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_125.smt2                             |   3.057s  |   3.057s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_126.smt2                             |   0.736s  |   0.736s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_127.smt2                             |   3.798s  |   3.798s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_128.smt2                             |   4.349s  |   4.349s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_129.smt2                             |  15.504s  |  15.504s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_130.smt2                             |  20.034s  |  20.034s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_131.smt2                             |   6.392s  |   6.392s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_132.smt2                             |  20.012s  |  20.012s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_133.smt2                             |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_134.smt2                             |  20.016s  |  20.016s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_135.smt2                             |  11.071s  |  11.071s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_136.smt2                             |  20.015s  |  20.015s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_137.smt2                             |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_138.smt2                             |  11.026s  |  11.026s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_139.smt2                             |   5.055s  |   5.055s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_140.smt2                             |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_141.smt2                             |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_142.smt2                             |   3.226s  |   3.226s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_143.smt2                             |   6.115s  |   6.115s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_144.smt2                             |   0.475s  |   0.475s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_145.smt2                             |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_146.smt2                             |   7.880s  |   7.880s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_147.smt2                             |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_148.smt2                             |   0.787s  |   0.787s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_149.smt2                             |  10.042s  |  10.042s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_150.smt2                             |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_151.smt2                             |   3.614s  |   3.614s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_152.smt2                             |   3.053s  |   3.053s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_153.smt2                             |  20.016s  |  20.016s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_154.smt2                             |   2.023s  |   2.023s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_155.smt2                             |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_156.smt2                             |   1.893s  |   1.893s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_157.smt2                             |  20.018s  |  20.018s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_158.smt2                             |   7.651s  |   7.651s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_159.smt2                             |  20.049s  |  20.049s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_160.smt2                             |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_161.smt2                             |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_162.smt2                             |  13.353s  |  13.353s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_163.smt2                             |   1.002s  |   1.002s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_164.smt2                             |  20.033s  |  20.033s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_165.smt2                             |  20.039s  |  20.039s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_166.smt2                             |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_167.smt2                             |  20.014s  |  20.014s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_168.smt2                             |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_169.smt2                             |  20.013s  |  20.013s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_170.smt2                             |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_171.smt2                             |   6.668s  |   6.668s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_172.smt2                             |  20.013s  |  20.013s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_173.smt2                             |   2.646s  |   2.646s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_174.smt2                             |  20.038s  |  20.038s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_175.smt2                             |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_176.smt2                             |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_177.smt2                             |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_178.smt2                             |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_179.smt2                             |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_180.smt2                             |  20.011s  |  20.011s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_181.smt2                             |  12.499s  |  12.499s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_182.smt2                             |   5.204s  |   5.204s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_183.smt2                             |  15.398s  |  15.398s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_184.smt2                             |  19.074s  |  19.074s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_185.smt2                             |   3.282s  |   3.282s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_186.smt2                             |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_187.smt2                             |  20.018s  |  20.018s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_188.smt2                             |  20.018s  |  20.018s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_189.smt2                             |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_190.smt2                             |   2.820s  |   2.820s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_191.smt2                             |   7.140s  |   7.140s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_192.smt2                             |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_193.smt2                             |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_194.smt2                             |   8.296s  |   8.296s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_195.smt2                             |  20.012s  |  20.012s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_196.smt2                             |   1.109s  |   1.109s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_197.smt2                             |  20.017s  |  20.017s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_198.smt2                             |   9.623s  |   9.623s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_199.smt2                             |  20.040s  |  20.040s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_200.smt2                             |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_201.smt2                             |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_202.smt2                             |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_203.smt2                             |   3.054s  |   3.054s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_204.smt2                             |  20.013s  |  20.013s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_205.smt2                             |   0.364s  |   0.364s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_206.smt2                             |  20.017s  |  20.017s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_207.smt2                             |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_208.smt2                             |  19.604s  |  19.604s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_209.smt2                             |  12.426s  |  12.426s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_210.smt2                             |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_211.smt2                             |  20.012s  |  20.012s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_212.smt2                             |   0.917s  |   0.917s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_213.smt2                             |   0.447s  |   0.447s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_214.smt2                             |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_215.smt2                             |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_216.smt2                             |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_217.smt2                             |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_218.smt2                             |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_219.smt2                             |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_220.smt2                             |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_221.smt2                             |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_222.smt2                             |  20.034s  |  20.034s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_223.smt2                             |   6.383s  |   6.383s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_224.smt2                             |  20.014s  |  20.014s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_225.smt2                             |   0.923s  |   0.923s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_226.smt2                             |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_227.smt2                             |  18.102s  |  18.102s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_228.smt2                             |   0.274s  |   0.274s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_229.smt2                             |  17.578s  |  17.578s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_230.smt2                             |   7.946s  |   7.946s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_231.smt2                             |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_232.smt2                             |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_233.smt2                             |  13.339s  |  13.339s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_234.smt2                             |  20.014s  |  20.014s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_235.smt2                             |   2.216s  |   2.216s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_236.smt2                             |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_237.smt2                             |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_238.smt2                             |   0.563s  |   0.563s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_239.smt2                             |  20.017s  |  20.017s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_240.smt2                             |  20.042s  |  20.042s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_241.smt2                             |   1.716s  |   1.716s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_242.smt2                             |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_243.smt2                             |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_244.smt2                             |   2.979s  |   2.979s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_245.smt2                             |   2.078s  |   2.078s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_246.smt2                             |  20.012s  |  20.012s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_247.smt2                             |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_248.smt2                             |  10.381s  |  10.381s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_249.smt2                             |   2.866s  |   2.866s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_250.smt2                             |  17.719s  |  17.719s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_251.smt2                             |  20.014s  |  20.014s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_252.smt2                             |  11.835s  |  11.835s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_253.smt2                             |  20.017s  |  20.017s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_254.smt2                             |   1.592s  |   1.592s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_255.smt2                             |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_256.smt2                             |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_257.smt2                             |  10.757s  |  10.757s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_258.smt2                             |  14.116s  |  14.116s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_259.smt2                             |   8.944s  |   8.944s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_260.smt2                             |   1.992s  |   1.992s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_261.smt2                             |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_262.smt2                             |  12.097s  |  12.097s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_263.smt2                             |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_264.smt2                             |   1.142s  |   1.142s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_265.smt2                             |   1.203s  |   1.203s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_266.smt2                             |  20.018s  |  20.018s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_267.smt2                             |   6.367s  |   6.367s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_268.smt2                             |   1.384s  |   1.384s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_269.smt2                             |   4.039s  |   4.039s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_270.smt2                             |  13.735s  |  13.735s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_271.smt2                             |  15.545s  |  15.545s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_272.smt2                             |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_273.smt2                             |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_274.smt2                             |   1.675s  |   1.675s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_275.smt2                             |   7.629s  |   7.629s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_276.smt2                             |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_277.smt2                             |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_278.smt2                             |  20.013s  |  20.013s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_279.smt2                             |   5.307s  |   5.307s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_280.smt2                             |  15.834s  |  15.834s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_281.smt2                             |   6.818s  |   6.818s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_282.smt2                             |   1.568s  |   1.568s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_283.smt2                             |  12.064s  |  12.064s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_284.smt2                             |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_285.smt2                             |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_286.smt2                             |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_287.smt2                             |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_288.smt2                             |  15.602s  |  15.602s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_289.smt2                             |   2.942s  |   2.942s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_290.smt2                             |   0.243s  |   0.243s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_291.smt2                             |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_292.smt2                             |  20.046s  |  20.046s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_293.smt2                             |  17.451s  |  17.451s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_294.smt2                             |  14.553s  |  14.553s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_295.smt2                             |   3.392s  |   3.392s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_296.smt2                             |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_297.smt2                             |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_298.smt2                             |   7.190s  |   7.190s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_299.smt2                             |   0.225s  |   0.225s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir5/formula_300.smt2                             |  19.243s  |  19.243s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_001.smt2                             |  20.029s  |  20.029s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_002.smt2                             |   0.201s  |   0.201s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_003.smt2                             |  20.037s  |  20.037s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_004.smt2                             |  20.092s  |  20.092s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_005.smt2                             |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_006.smt2                             |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_007.smt2                             |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_008.smt2                             |   2.689s  |   2.689s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_009.smt2                             |  20.033s  |  20.033s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_010.smt2                             |  20.050s  |  20.050s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_011.smt2                             |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_012.smt2                             |  20.121s  |  20.121s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_013.smt2                             |  20.063s  |  20.063s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_014.smt2                             |   0.175s  |   0.175s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_015.smt2                             |  20.071s  |  20.071s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_016.smt2                             |  20.038s  |  20.038s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_017.smt2                             |  20.022s  |  20.022s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_018.smt2                             |  20.060s  |  20.060s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_019.smt2                             |  20.014s  |  20.014s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_020.smt2                             |  20.164s  |  20.164s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_021.smt2                             |  20.060s  |  20.060s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_022.smt2                             |  20.016s  |  20.016s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_023.smt2                             |  20.018s  |  20.018s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_024.smt2                             |   1.281s  |   1.281s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_025.smt2                             |  20.065s  |  20.065s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_026.smt2                             |  20.015s  |  20.015s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_027.smt2                             |  20.028s  |  20.028s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_028.smt2                             |  20.023s  |  20.023s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_029.smt2                             |  20.058s  |  20.058s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_030.smt2                             |  20.033s  |  20.033s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_031.smt2                             |  20.017s  |  20.017s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_032.smt2                             |  20.071s  |  20.071s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_033.smt2                             |  20.039s  |  20.039s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_034.smt2                             |  20.052s  |  20.052s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_035.smt2                             |  20.045s  |  20.045s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_036.smt2                             |  20.090s  |  20.090s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_037.smt2                             |  20.017s  |  20.017s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_038.smt2                             |  12.010s  |  12.010s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_039.smt2                             |  20.037s  |  20.037s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_040.smt2                             |  20.032s  |  20.032s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_041.smt2                             |  20.044s  |  20.044s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_042.smt2                             |  20.101s  |  20.101s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_043.smt2                             |  20.014s  |  20.014s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_044.smt2                             |  20.152s  |  20.152s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_045.smt2                             |   0.816s  |   0.816s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_046.smt2                             |  20.079s  |  20.079s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_047.smt2                             |  20.102s  |  20.102s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_048.smt2                             |  20.013s  |  20.013s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_049.smt2                             |  20.169s  |  20.169s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_050.smt2                             |  20.013s  |  20.013s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_051.smt2                             |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_052.smt2                             |  20.063s  |  20.063s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_053.smt2                             |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_054.smt2                             |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_055.smt2                             |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_056.smt2                             |  20.096s  |  20.096s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_057.smt2                             |  20.045s  |  20.045s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_058.smt2                             |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_059.smt2                             |  20.050s  |  20.050s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_060.smt2                             |   1.495s  |   1.495s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_061.smt2                             |  20.063s  |  20.063s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_062.smt2                             |  20.028s  |  20.028s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_063.smt2                             |  20.014s  |  20.014s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_064.smt2                             |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_065.smt2                             |  20.055s  |  20.055s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_066.smt2                             |  20.016s  |  20.016s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_067.smt2                             |  20.037s  |  20.037s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_068.smt2                             |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_069.smt2                             |  20.033s  |  20.033s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_070.smt2                             |  20.031s  |  20.031s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_071.smt2                             |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_072.smt2                             |  20.052s  |  20.052s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_073.smt2                             |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_074.smt2                             |  20.164s  |  20.164s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_075.smt2                             |  20.016s  |  20.016s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_076.smt2                             |  20.068s  |  20.068s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_077.smt2                             |  20.022s  |  20.022s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_078.smt2                             |  20.134s  |  20.134s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_079.smt2                             |   0.186s  |   0.186s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_080.smt2                             |  20.065s  |  20.065s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_081.smt2                             |  20.077s  |  20.077s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_082.smt2                             |  20.048s  |  20.048s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_083.smt2                             |  20.018s  |  20.018s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_084.smt2                             |  20.030s  |  20.030s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_085.smt2                             |   6.771s  |   6.771s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_086.smt2                             |  20.092s  |  20.092s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_087.smt2                             |  20.088s  |  20.088s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_088.smt2                             |  20.092s  |  20.092s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_089.smt2                             |  20.084s  |  20.084s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_090.smt2                             |  20.020s  |  20.020s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_091.smt2                             |  20.058s  |  20.058s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_092.smt2                             |  16.264s  |  16.264s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_093.smt2                             |  20.149s  |  20.149s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_094.smt2                             |  20.012s  |  20.012s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_095.smt2                             |  20.039s  |  20.039s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_096.smt2                             |  20.032s  |  20.032s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_097.smt2                             |  20.166s  |  20.166s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_098.smt2                             |  20.046s  |  20.046s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_099.smt2                             |  20.053s  |  20.053s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_100.smt2                             |  20.085s  |  20.085s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_101.smt2                             |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_102.smt2                             |  20.028s  |  20.028s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_103.smt2                             |  20.018s  |  20.018s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_104.smt2                             |  20.056s  |  20.056s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_105.smt2                             |  20.094s  |  20.094s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_106.smt2                             |  20.096s  |  20.096s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_107.smt2                             |  20.091s  |  20.091s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_108.smt2                             |  20.034s  |  20.034s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_109.smt2                             |  20.091s  |  20.091s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_110.smt2                             |  20.041s  |  20.041s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_111.smt2                             |   3.311s  |   3.311s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_112.smt2                             |  20.018s  |  20.018s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_113.smt2                             |  20.170s  |  20.170s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_114.smt2                             |  20.106s  |  20.106s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_115.smt2                             |  12.965s  |  12.965s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_116.smt2                             |  20.157s  |  20.157s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_117.smt2                             |  20.053s  |  20.053s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_118.smt2                             |  20.016s  |  20.016s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_119.smt2                             |  20.021s  |  20.021s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_120.smt2                             |  20.043s  |  20.043s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_121.smt2                             |  20.013s  |  20.013s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_122.smt2                             |  20.049s  |  20.049s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_123.smt2                             |  20.058s  |  20.058s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_124.smt2                             |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_125.smt2                             |  20.094s  |  20.094s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_126.smt2                             |  20.013s  |  20.013s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_127.smt2                             |  20.195s  |  20.195s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_128.smt2                             |  20.071s  |  20.071s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_129.smt2                             |  20.014s  |  20.014s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_130.smt2                             |  20.110s  |  20.110s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_131.smt2                             |  20.067s  |  20.067s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_132.smt2                             |  20.153s  |  20.153s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_133.smt2                             |  20.057s  |  20.057s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_134.smt2                             |  20.166s  |  20.166s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_135.smt2                             |  20.076s  |  20.076s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_136.smt2                             |  20.101s  |  20.101s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_137.smt2                             |  20.017s  |  20.017s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_138.smt2                             |  20.018s  |  20.018s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_139.smt2                             |   5.738s  |   5.738s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_140.smt2                             |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_141.smt2                             |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_142.smt2                             |  20.033s  |  20.033s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_143.smt2                             |  20.056s  |  20.056s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_144.smt2                             |  20.155s  |  20.155s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_145.smt2                             |  20.044s  |  20.044s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_146.smt2                             |  20.028s  |  20.028s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_147.smt2                             |   0.310s  |   0.310s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_148.smt2                             |  20.066s  |  20.066s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_149.smt2                             |  20.058s  |  20.058s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_150.smt2                             |  20.033s  |  20.033s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_151.smt2                             |  20.062s  |  20.062s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_152.smt2                             |  20.068s  |  20.068s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_153.smt2                             |  20.152s  |  20.152s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_154.smt2                             |  20.076s  |  20.076s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_155.smt2                             |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_156.smt2                             |  20.053s  |  20.053s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_157.smt2                             |  20.014s  |  20.014s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_158.smt2                             |  20.193s  |  20.193s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_159.smt2                             |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_160.smt2                             |  20.102s  |  20.102s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_161.smt2                             |   0.217s  |   0.217s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_162.smt2                             |  20.168s  |  20.168s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_163.smt2                             |   2.748s  |   2.748s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_164.smt2                             |  20.057s  |  20.057s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_165.smt2                             |  20.052s  |  20.052s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_166.smt2                             |  20.041s  |  20.041s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_167.smt2                             |  20.029s  |  20.029s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_168.smt2                             |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_169.smt2                             |  20.055s  |  20.055s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_170.smt2                             |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_171.smt2                             |  20.050s  |  20.050s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_172.smt2                             |  20.043s  |  20.043s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_173.smt2                             |  20.018s  |  20.018s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_174.smt2                             |  20.091s  |  20.091s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_175.smt2                             |  20.033s  |  20.033s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_176.smt2                             |  20.096s  |  20.096s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_177.smt2                             |  20.021s  |  20.021s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_178.smt2                             |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_179.smt2                             |  20.023s  |  20.023s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_180.smt2                             |  20.034s  |  20.034s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_181.smt2                             |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_182.smt2                             |  20.051s  |  20.051s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_183.smt2                             |  20.018s  |  20.018s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_184.smt2                             |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_185.smt2                             |  20.049s  |  20.049s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_186.smt2                             |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_187.smt2                             |  20.058s  |  20.058s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_188.smt2                             |  20.012s  |  20.012s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_189.smt2                             |  20.162s  |  20.162s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_190.smt2                             |  20.029s  |  20.029s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_191.smt2                             |  20.056s  |  20.056s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_192.smt2                             |  20.035s  |  20.035s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_193.smt2                             |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_194.smt2                             |  20.015s  |  20.015s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_195.smt2                             |  20.036s  |  20.036s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_196.smt2                             |  20.016s  |  20.016s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_197.smt2                             |  20.055s  |  20.055s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_198.smt2                             |  20.033s  |  20.033s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_199.smt2                             |  20.059s  |  20.059s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_200.smt2                             |  16.999s  |  16.999s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_201.smt2                             |  20.160s  |  20.160s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_202.smt2                             |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_203.smt2                             |  20.039s  |  20.039s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_204.smt2                             |  20.154s  |  20.154s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_205.smt2                             |  20.077s  |  20.077s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_206.smt2                             |  20.047s  |  20.047s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_207.smt2                             |  20.078s  |  20.078s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_208.smt2                             |  20.193s  |  20.193s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_209.smt2                             |  20.013s  |  20.013s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_210.smt2                             |  20.020s  |  20.020s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_211.smt2                             |   4.098s  |   4.098s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_212.smt2                             |  20.051s  |  20.051s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_213.smt2                             |  20.056s  |  20.056s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_214.smt2                             |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_215.smt2                             |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_216.smt2                             |  20.044s  |  20.044s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_217.smt2                             |  20.050s  |  20.050s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_218.smt2                             |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_219.smt2                             |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_220.smt2                             |  20.040s  |  20.040s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_221.smt2                             |  20.036s  |  20.036s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_222.smt2                             |  20.061s  |  20.061s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_223.smt2                             |  20.086s  |  20.086s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_224.smt2                             |  20.096s  |  20.096s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_225.smt2                             |  20.067s  |  20.067s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_226.smt2                             |  20.036s  |  20.036s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_227.smt2                             |  20.053s  |  20.053s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_228.smt2                             |  20.035s  |  20.035s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_229.smt2                             |  20.048s  |  20.048s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_230.smt2                             |  20.077s  |  20.077s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_231.smt2                             |  20.088s  |  20.088s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_232.smt2                             |   0.253s  |   0.253s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_233.smt2                             |  20.051s  |  20.051s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_234.smt2                             |  20.045s  |  20.045s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_235.smt2                             |  20.044s  |  20.044s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_236.smt2                             |  20.035s  |  20.035s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_237.smt2                             |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_238.smt2                             |  20.093s  |  20.093s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_239.smt2                             |  20.018s  |  20.018s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_240.smt2                             |  20.062s  |  20.062s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_241.smt2                             |  20.066s  |  20.066s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_242.smt2                             |  20.054s  |  20.054s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_243.smt2                             |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_244.smt2                             |  20.157s  |  20.157s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_245.smt2                             |  20.046s  |  20.046s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_246.smt2                             |  20.044s  |  20.044s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_247.smt2                             |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_248.smt2                             |  20.031s  |  20.031s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_249.smt2                             |  20.080s  |  20.080s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_250.smt2                             |  20.053s  |  20.053s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_251.smt2                             |  20.055s  |  20.055s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_252.smt2                             |  20.052s  |  20.052s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_253.smt2                             |  20.040s  |  20.040s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_254.smt2                             |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_255.smt2                             |   0.242s  |   0.242s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_256.smt2                             |  20.161s  |  20.161s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_257.smt2                             |  20.020s  |  20.020s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_258.smt2                             |  20.032s  |  20.032s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_259.smt2                             |  20.059s  |  20.059s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_260.smt2                             |  20.055s  |  20.055s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_261.smt2                             |  20.096s  |  20.096s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_262.smt2                             |  20.056s  |  20.056s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_263.smt2                             |  20.017s  |  20.017s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_264.smt2                             |  20.194s  |  20.194s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_265.smt2                             |  20.037s  |  20.037s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_266.smt2                             |  20.093s  |  20.093s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_267.smt2                             |  20.059s  |  20.059s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_268.smt2                             |  20.055s  |  20.055s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_269.smt2                             |   3.407s  |   3.407s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_270.smt2                             |  20.158s  |  20.158s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_271.smt2                             |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_272.smt2                             |  20.058s  |  20.058s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_273.smt2                             |  20.021s  |  20.021s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_274.smt2                             |  20.016s  |  20.016s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_275.smt2                             |  20.160s  |  20.160s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_276.smt2                             |  20.019s  |  20.019s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_277.smt2                             |  20.048s  |  20.048s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_278.smt2                             |  20.076s  |  20.076s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_279.smt2                             |  20.061s  |  20.061s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_280.smt2                             |  20.048s  |  20.048s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_281.smt2                             |  20.058s  |  20.058s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_282.smt2                             |  20.170s  |  20.170s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_283.smt2                             |  20.094s  |  20.094s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_284.smt2                             |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_285.smt2                             |  20.049s  |  20.049s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_286.smt2                             |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_287.smt2                             |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_288.smt2                             |  20.029s  |  20.029s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_289.smt2                             |  20.060s  |  20.060s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_290.smt2                             |  20.030s  |  20.030s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_291.smt2                             |  20.025s  |  20.025s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_292.smt2                             |  20.041s  |  20.041s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_293.smt2                             |  20.013s  |  20.013s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_294.smt2                             |  20.019s  |  20.019s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_295.smt2                             |  20.031s  |  20.031s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_296.smt2                             |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_297.smt2                             |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_298.smt2                             |  20.041s  |  20.041s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_299.smt2                             |  20.057s  |  20.057s  |   0.000s  | 0.0%|
|non-incremental/LRA/2010-Monniaux-QE/mjollnir6/formula_300.smt2                             |  20.148s  |  20.148s  |   0.000s  | 0.0%|
|non-incremental/LRA/20230331-polyv/bv7hv-miss1h.smt2                                        |  12.556s  |  12.556s  |   0.000s  | 0.0%|
|non-incremental/LRA/20230331-polyv/bv7hv-miss1v.smt2                                        |  20.074s  |  20.074s  |   0.000s  | 0.0%|
|non-incremental/LRA/20230331-polyv/bv7hv.smt2                                               |  20.079s  |  20.079s  |   0.000s  | 0.0%|
|non-incremental/LRA/20230331-polyv/cp5hv.smt2                                               |  20.014s  |  20.014s  |   0.000s  | 0.0%|
|non-incremental/LRA/20230331-polyv/cp6hv-miss1h.smt2                                        |  20.019s  |  20.019s  |   0.000s  | 0.0%|
|non-incremental/LRA/20230331-polyv/cp6hv-miss1v.smt2                                        |  12.767s  |  12.767s  |   0.000s  | 0.0%|
|non-incremental/LRA/20230331-polyv/cp6hv.smt2                                               |  20.017s  |  20.017s  |   0.000s  | 0.0%|
|non-incremental/LRA/20230331-polyv/h5hv.smt2                                                |  20.032s  |  20.032s  |   0.000s  | 0.0%|
|non-incremental/LRA/20230331-polyv/h5projh-h4h.smt2                                         |  20.038s  |  20.038s  |   0.000s  | 0.0%|
|non-incremental/LRA/20230331-polyv/h5projh-h4v.smt2                                         |  20.039s  |  20.039s  |   0.000s  | 0.0%|
|non-incremental/LRA/20230331-polyv/h5projh3-h4projh3.smt2                                   |  20.019s  |  20.019s  |   0.000s  | 0.0%|
|non-incremental/LRA/20230331-polyv/mit-checkpred1.smt2                                      |  20.024s  |  20.024s  |   0.000s  | 0.0%|
|non-incremental/LRA/20230331-polyv/mit-checkpred726.smt2                                    |  20.022s  |  20.022s  |   0.000s  | 0.0%|
|non-incremental/LRA/20230331-polyv/mit-projhh-miss1.smt2                                    |   2.661s  |   2.661s  |   0.000s  | 0.0%|
|non-incremental/LRA/20230331-polyv/mit-projhh.smt2                                          |  20.025s  |  20.025s  |   0.000s  | 0.0%|
|non-incremental/LRA/20230331-polyv/mit-projhv-miss1.smt2                                    |  20.024s  |  20.024s  |   0.000s  | 0.0%|
|non-incremental/LRA/20230331-polyv/mit-projhv.smt2                                          |  20.028s  |  20.028s  |   0.000s  | 0.0%|
|non-incremental/LRA/20230331-polyv/mit71-checkpred1.smt2                                    |  20.017s  |  20.017s  |   0.000s  | 0.0%|
|non-incremental/LRA/20230331-polyv/mithv-miss1v.smt2                                        |  20.074s  |  20.074s  |   0.000s  | 0.0%|
|non-incremental/LRA/20230331-polyv/mithv.smt2                                               |  20.090s  |  20.090s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node11645.smt2               |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node11938.smt2               |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node12702.smt2               |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node12911.smt2               |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node13023.smt2               |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node15586.smt2               |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node15800.smt2               |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node16357.smt2               |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node16571.smt2               |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node22058.smt2               |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node22267.smt2               |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node22930.smt2               |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node23139.smt2               |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node2331.smt2                |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node24909.smt2               |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node25118.smt2               |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node25230.smt2               |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node2545.smt2                |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node25994.smt2               |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node26275.smt2               |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node3202.smt2                |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node393141.smt2              |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node394346.smt2              |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node396021.smt2              |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node396678.smt2              |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node396892.smt2              |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node398905.smt2              |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node403143.smt2              |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node403405.smt2              |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node403899.smt2              |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node404096.smt2              |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node404555.smt2              |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node404749.smt2              |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node405951.smt2              |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node406687.smt2              |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node406896.smt2              |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node407008.smt2              |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node408839.smt2              |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node409496.smt2              |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node409710.smt2              |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node412027.smt2              |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node412241.smt2              |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node412898.smt2              |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node419176.smt2              |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node419390.smt2              |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node422040.smt2              |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node422254.smt2              |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node427730.smt2              |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node427939.smt2              |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node428602.smt2              |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node431090.smt2              |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node431299.smt2              |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node431411.smt2              |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node432116.smt2              |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node432325.smt2              |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node432437.smt2              |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node43527.smt2               |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node43741.smt2               |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node44393.smt2               |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node44607.smt2               |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node450267.smt2              |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node450481.smt2              |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node451133.smt2              |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node451347.smt2              |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node453137.smt2              |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node453789.smt2              |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node454003.smt2              |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node459874.smt2              |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node460167.smt2              |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node460926.smt2              |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node461135.smt2              |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node461247.smt2              |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node462599.smt2              |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node462796.smt2              |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node463847.smt2              |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node46397.smt2               |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node464056.smt2              |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node464515.smt2              |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node464724.smt2              |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node464836.smt2              |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node465124.smt2              |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node47049.smt2               |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node47263.smt2               |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node53134.smt2               |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node53427.smt2               |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node54186.smt2               |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node54395.smt2               |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node54507.smt2               |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node5527.smt2                |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node5741.smt2                |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node57616.smt2               |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node58285.smt2               |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node58499.smt2               |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node59054.smt2               |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node62480.smt2               |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node62694.smt2               |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node6298.smt2                |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node63249.smt2               |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node6512.smt2                |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node679020.smt2              |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node679178.smt2              |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node679290.smt2              |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node679466.smt2              |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node679744.smt2              |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node680612.smt2              |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node680821.smt2              |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node680933.smt2              |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node681626.smt2              |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node681835.smt2              |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node681947.smt2              |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node683187.smt2              |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node683401.smt2              |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node683817.smt2              |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node684031.smt2              |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node684597.smt2              |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node688433.smt2              |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node688613.smt2              |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node70716.smt2               |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node70925.smt2               |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node71583.smt2               |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node71792.smt2               |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node733141.smt2              |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node75451.smt2               |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node75660.smt2               |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node75772.smt2               |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node76467.smt2               |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node76579.smt2               |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node80003.smt2               |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node80217.smt2               |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node80787.smt2               |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node81001.smt2               |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node81556.smt2               |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node81770.smt2               |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node84760.smt2               |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node85544.smt2               |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node85758.smt2               |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node86313.smt2               |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node93665.smt2               |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node93874.smt2               |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node94532.smt2               |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node94741.smt2               |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node98400.smt2               |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node98609.smt2               |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node98721.smt2               |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node99416.smt2               |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/intersection-example-simple.proof-node99528.smt2               |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node10155.smt2                                      |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node10156.smt2                                      |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node10186.smt2                                      |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node11755.smt2                                      |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node11756.smt2                                      |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node11781.smt2                                      |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node12555.smt2                                      |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node12556.smt2                                      |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node12581.smt2                                      |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node13854.smt2                                      |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node13855.smt2                                      |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node13885.smt2                                      |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node14878.smt2                                      |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node14879.smt2                                      |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node14909.smt2                                      |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node16055.smt2                                      |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node16056.smt2                                      |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node16086.smt2                                      |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node18157.smt2                                      |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node18158.smt2                                      |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node18188.smt2                                      |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node19175.smt2                                      |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node19176.smt2                                      |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node19206.smt2                                      |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node21140.smt2                                      |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node21141.smt2                                      |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node21166.smt2                                      |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node22228.smt2                                      |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node22229.smt2                                      |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node22259.smt2                                      |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node22289.smt2                                      |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node23030.smt2                                      |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node23031.smt2                                      |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node23061.smt2                                      |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node23091.smt2                                      |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node24597.smt2                                      |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node24598.smt2                                      |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node24628.smt2                                      |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node24658.smt2                                      |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node25618.smt2                                      |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node25619.smt2                                      |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node25649.smt2                                      |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node25679.smt2                                      |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node26754.smt2                                      |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node27653.smt2                                      |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node27654.smt2                                      |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node27679.smt2                                      |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node27709.smt2                                      |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node28519.smt2                                      |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node28520.smt2                                      |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node28793.smt2                                      |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node28794.smt2                                      |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node28824.smt2                                      |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node29291.smt2                                      |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node29292.smt2                                      |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node29317.smt2                                      |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node30102.smt2                                      |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node30103.smt2                                      |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node30133.smt2                                      |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node30158.smt2                                      |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node30869.smt2                                      |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node30870.smt2                                      |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node30895.smt2                                      |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node31000.smt2                                      |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node31001.smt2                                      |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node31031.smt2                                      |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node31056.smt2                                      |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node5019.smt2                                       |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node5020.smt2                                       |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node7173.smt2                                       |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node7174.smt2                                       |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node8198.smt2                                       |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node8199.smt2                                       |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node9350.smt2                                       |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node9351.smt2                                       |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/LRA/keymaera/water_tank-node9381.smt2                                       |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_3_1.smt2                                           |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_3_10.smt2                                          |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_3_11.smt2                                          |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_3_12.smt2                                          |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_3_13.smt2                                          |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_3_14.smt2                                          |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_3_15.smt2                                          |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_3_16.smt2                                          |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_3_17.smt2                                          |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_3_18.smt2                                          |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_3_19.smt2                                          |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_3_2.smt2                                           |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_3_20.smt2                                          |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_3_21.smt2                                          |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_3_22.smt2                                          |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_3_23.smt2                                          |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_3_24.smt2                                          |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_3_25.smt2                                          |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_3_26.smt2                                          |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_3_27.smt2                                          |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_3_28.smt2                                          |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_3_29.smt2                                          |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_3_3.smt2                                           |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_3_30.smt2                                          |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_3_4.smt2                                           |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_3_5.smt2                                           |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_3_6.smt2                                           |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_3_7.smt2                                           |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_3_8.smt2                                           |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_3_9.smt2                                           |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_4_1.smt2                                           |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_4_10.smt2                                          |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_4_11.smt2                                          |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_4_12.smt2                                          |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_4_13.smt2                                          |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_4_14.smt2                                          |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_4_15.smt2                                          |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_4_16.smt2                                          |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_4_17.smt2                                          |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_4_18.smt2                                          |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_4_19.smt2                                          |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_4_2.smt2                                           |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_4_20.smt2                                          |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_4_21.smt2                                          |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_4_22.smt2                                          |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_4_23.smt2                                          |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_4_24.smt2                                          |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_4_25.smt2                                          |   0.541s  |   0.541s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_4_26.smt2                                          |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_4_27.smt2                                          |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_4_28.smt2                                          |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_4_29.smt2                                          |   0.282s  |   0.282s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_4_3.smt2                                           |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_4_30.smt2                                          |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_4_4.smt2                                           |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_4_5.smt2                                           |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_4_6.smt2                                           |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_4_7.smt2                                           |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_4_8.smt2                                           |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_4_9.smt2                                           |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_6_1.smt2                                           |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_6_10.smt2                                          |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_6_11.smt2                                          |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_6_12.smt2                                          |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_6_13.smt2                                          |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_6_14.smt2                                          |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_6_15.smt2                                          |   0.228s  |   0.228s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_6_16.smt2                                          |   0.517s  |   0.517s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_6_17.smt2                                          |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_6_18.smt2                                          |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_6_19.smt2                                          |   0.933s  |   0.933s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_6_2.smt2                                           |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_6_20.smt2                                          |   0.322s  |   0.322s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_6_21.smt2                                          |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_6_22.smt2                                          |   0.810s  |   0.810s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_6_23.smt2                                          |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_6_24.smt2                                          |   0.227s  |   0.227s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_6_25.smt2                                          |  20.021s  |  20.021s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_6_26.smt2                                          |   0.410s  |   0.410s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_6_27.smt2                                          |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_6_28.smt2                                          |   7.853s  |   7.853s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_6_29.smt2                                          |   5.077s  |   5.077s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_6_3.smt2                                           |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_6_30.smt2                                          |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_6_31.smt2                                          |   1.452s  |   1.452s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_6_32.smt2                                          |   8.398s  |   8.398s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_6_33.smt2                                          |   0.458s  |   0.458s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_6_34.smt2                                          |   0.396s  |   0.396s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_6_35.smt2                                          |  20.018s  |  20.018s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_6_36.smt2                                          |   5.753s  |   5.753s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_6_37.smt2                                          |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_6_38.smt2                                          |  20.016s  |  20.016s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_6_39.smt2                                          |  20.018s  |  20.018s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_6_4.smt2                                           |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_6_40.smt2                                          |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_6_5.smt2                                           |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_6_6.smt2                                           |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_6_7.smt2                                           |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_6_8.smt2                                           |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RND/RND_6_9.smt2                                           |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_3_1.smt2                                     |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_3_10.smt2                                    |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_3_11.smt2                                    |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_3_12.smt2                                    |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_3_13.smt2                                    |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_3_14.smt2                                    |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_3_15.smt2                                    |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_3_16.smt2                                    |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_3_17.smt2                                    |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_3_18.smt2                                    |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_3_19.smt2                                    |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_3_2.smt2                                     |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_3_20.smt2                                    |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_3_21.smt2                                    |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_3_22.smt2                                    |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_3_23.smt2                                    |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_3_24.smt2                                    |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_3_25.smt2                                    |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_3_26.smt2                                    |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_3_27.smt2                                    |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_3_28.smt2                                    |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_3_29.smt2                                    |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_3_3.smt2                                     |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_3_30.smt2                                    |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_3_31.smt2                                    |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_3_32.smt2                                    |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_3_33.smt2                                    |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_3_34.smt2                                    |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_3_35.smt2                                    |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_3_36.smt2                                    |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_3_37.smt2                                    |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_3_38.smt2                                    |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_3_39.smt2                                    |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_3_4.smt2                                     |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_3_40.smt2                                    |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_3_41.smt2                                    |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_3_42.smt2                                    |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_3_43.smt2                                    |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_3_44.smt2                                    |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_3_45.smt2                                    |   1.289s  |   1.289s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_3_46.smt2                                    |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_3_47.smt2                                    |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_3_48.smt2                                    |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_3_49.smt2                                    |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_3_5.smt2                                     |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_3_50.smt2                                    |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_3_51.smt2                                    |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_3_52.smt2                                    |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_3_53.smt2                                    |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_3_54.smt2                                    |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_3_55.smt2                                    |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_3_56.smt2                                    |   0.331s  |   0.331s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_3_57.smt2                                    |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_3_58.smt2                                    |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_3_59.smt2                                    |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_3_6.smt2                                     |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_3_60.smt2                                    |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_3_7.smt2                                     |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_3_8.smt2                                     |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_3_9.smt2                                     |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_1.smt2                                     |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_10.smt2                                    |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_11.smt2                                    |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_12.smt2                                    |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_13.smt2                                    |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_14.smt2                                    |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_15.smt2                                    |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_16.smt2                                    |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_17.smt2                                    |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_18.smt2                                    |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_19.smt2                                    |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_2.smt2                                     |   0.218s  |   0.218s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_20.smt2                                    |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_21.smt2                                    |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_22.smt2                                    |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_23.smt2                                    |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_24.smt2                                    |   0.539s  |   0.539s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_25.smt2                                    |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_26.smt2                                    |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_27.smt2                                    |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_28.smt2                                    |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_29.smt2                                    |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_3.smt2                                     |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_30.smt2                                    |   0.529s  |   0.529s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_31.smt2                                    |   0.692s  |   0.692s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_32.smt2                                    |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_33.smt2                                    |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_34.smt2                                    |   0.236s  |   0.236s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_35.smt2                                    |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_36.smt2                                    |   1.811s  |   1.811s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_37.smt2                                    |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_38.smt2                                    |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_39.smt2                                    |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_4.smt2                                     |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_40.smt2                                    |   0.447s  |   0.447s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_41.smt2                                    |   0.961s  |   0.961s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_42.smt2                                    |   0.265s  |   0.265s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_43.smt2                                    |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_44.smt2                                    |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_45.smt2                                    |  13.706s  |  13.706s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_46.smt2                                    |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_47.smt2                                    |   0.337s  |   0.337s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_48.smt2                                    |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_49.smt2                                    |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_5.smt2                                     |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_50.smt2                                    |   0.627s  |   0.627s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_51.smt2                                    |   3.227s  |   3.227s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_52.smt2                                    |   1.150s  |   1.150s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_53.smt2                                    |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_54.smt2                                    |   1.554s  |   1.554s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_55.smt2                                    |   0.233s  |   0.233s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_56.smt2                                    |  20.019s  |  20.019s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_57.smt2                                    |   1.544s  |   1.544s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_58.smt2                                    |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_59.smt2                                    |   1.381s  |   1.381s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_6.smt2                                     |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_60.smt2                                    |   0.198s  |   0.198s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_61.smt2                                    |   2.505s  |   2.505s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_62.smt2                                    |   0.302s  |   0.302s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_63.smt2                                    |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_64.smt2                                    |   1.596s  |   1.596s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_65.smt2                                    |   0.576s  |   0.576s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_66.smt2                                    |   6.730s  |   6.730s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_67.smt2                                    |   0.270s  |   0.270s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_68.smt2                                    |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_69.smt2                                    |   2.177s  |   2.177s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_7.smt2                                     |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_70.smt2                                    |   1.021s  |   1.021s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_8.smt2                                     |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/RNDPRE/RNDPRE_4_9.smt2                                     |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_4_1.smt2                                       |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_4_2.smt2                                       |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_4_3.smt2                                       |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_4_4.smt2                                       |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_4_5.smt2                                       |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_4_6.smt2                                       |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_5_1.smt2                                       |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_5_10.smt2                                      |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_5_11.smt2                                      |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_5_13.smt2                                      |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_5_14.smt2                                      |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_5_16.smt2                                      |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_5_17.smt2                                      |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_5_18.smt2                                      |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_5_19.smt2                                      |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_5_2.smt2                                       |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_5_20.smt2                                      |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_5_21.smt2                                      |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_5_22.smt2                                      |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_5_23.smt2                                      |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_5_24.smt2                                      |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_5_25.smt2                                      |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_5_26.smt2                                      |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_5_28.smt2                                      |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_5_3.smt2                                       |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_5_31.smt2                                      |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_5_33.smt2                                      |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_5_34.smt2                                      |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_5_35.smt2                                      |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_5_36.smt2                                      |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_5_37.smt2                                      |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_5_38.smt2                                      |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_5_39.smt2                                      |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_5_4.smt2                                       |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_5_40.smt2                                      |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_5_41.smt2                                      |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_5_42.smt2                                      |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_5_43.smt2                                      |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_5_44.smt2                                      |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_5_45.smt2                                      |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_5_46.smt2                                      |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_5_47.smt2                                      |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_5_48.smt2                                      |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_5_49.smt2                                      |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_5_5.smt2                                       |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_5_50.smt2                                      |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_5_51.smt2                                      |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_5_52.smt2                                      |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_5_53.smt2                                      |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_5_54.smt2                                      |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_5_55.smt2                                      |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_5_56.smt2                                      |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_5_57.smt2                                      |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_5_58.smt2                                      |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_5_59.smt2                                      |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_5_6.smt2                                       |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_5_60.smt2                                      |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_5_61.smt2                                      |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_5_62.smt2                                      |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_5_63.smt2                                      |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_5_64.smt2                                      |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_5_7.smt2                                       |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_5_8.smt2                                       |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_5_9.smt2                                       |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_1.smt2                                       |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_10.smt2                                      |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_11.smt2                                      |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_12.smt2                                      |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_13.smt2                                      |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_14.smt2                                      |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_15.smt2                                      |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_16.smt2                                      |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_17.smt2                                      |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_18.smt2                                      |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_19.smt2                                      |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_2.smt2                                       |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_20.smt2                                      |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_21.smt2                                      |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_22.smt2                                      |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_23.smt2                                      |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_24.smt2                                      |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_25.smt2                                      |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_26.smt2                                      |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_27.smt2                                      |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_28.smt2                                      |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_29.smt2                                      |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_3.smt2                                       |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_30.smt2                                      |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_31.smt2                                      |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_32.smt2                                      |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_33.smt2                                      |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_34.smt2                                      |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_35.smt2                                      |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_36.smt2                                      |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_37.smt2                                      |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_38.smt2                                      |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_39.smt2                                      |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_4.smt2                                       |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_40.smt2                                      |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_41.smt2                                      |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_42.smt2                                      |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_43.smt2                                      |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_44.smt2                                      |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_45.smt2                                      |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_46.smt2                                      |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_47.smt2                                      |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_48.smt2                                      |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_49.smt2                                      |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_5.smt2                                       |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_50.smt2                                      |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_51.smt2                                      |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_52.smt2                                      |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_53.smt2                                      |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_54.smt2                                      |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_55.smt2                                      |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_56.smt2                                      |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_57.smt2                                      |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_58.smt2                                      |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_59.smt2                                      |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_6.smt2                                       |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_60.smt2                                      |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_61.smt2                                      |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_62.smt2                                      |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_63.smt2                                      |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_64.smt2                                      |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_65.smt2                                      |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_66.smt2                                      |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_67.smt2                                      |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_68.smt2                                      |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_69.smt2                                      |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_7.smt2                                       |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_70.smt2                                      |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_71.smt2                                      |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_72.smt2                                      |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_73.smt2                                      |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_74.smt2                                      |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_75.smt2                                      |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_76.smt2                                      |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_77.smt2                                      |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_78.smt2                                      |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_79.smt2                                      |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_8.smt2                                       |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/LRA/scholl-smt08/model/model_6_80.smt2                                      |   0.039s  |   0.039s  |   0.000s  | 0.0%|
</details>
