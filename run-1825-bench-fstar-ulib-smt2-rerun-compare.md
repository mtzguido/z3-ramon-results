Comparing data and data


# SUMMARY
- LHS tests = 250
- RHS tests = 250
- LHS success = 19  (7.6%)
- RHS success = 19  (7.6%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: bench-fstar-ulib-smt2-rerun
Runner: rise-runner-2
Z3 repo: CanCebeci/z3
Z3 commit: bc6c38e7d3424b88a505cacba4b268d0774d4547
Z3 branch: bc6c38e7d3424b88a505cacba4b268d0774d4547
Z3 options: "-T:20"
Z3 inputs: inputs/fstar-ulib-smt2
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
Job tag: bench-fstar-ulib-smt2-rerun
Runner: rise-runner-2
Z3 repo: CanCebeci/z3
Z3 commit: bc6c38e7d3424b88a505cacba4b268d0774d4547
Z3 branch: bc6c38e7d3424b88a505cacba4b268d0774d4547
Z3 options: "-T:20"
Z3 inputs: inputs/fstar-ulib-smt2
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
|queries-FStar.Buffer.smt2                                                                   |  20.065s  |  20.065s  |   0.000s  | 0.0%|
|queries-FStar.Endianness.smt2                                                               |  20.134s  |  20.134s  |   0.000s  | 0.0%|
|queries-FStar.Int.smt2                                                                      |  20.105s  |  20.105s  |   0.000s  | 0.0%|
|queries-FStar.Matrix-1.smt2                                                                 |  20.074s  |  20.074s  |   0.000s  | 0.0%|
|queries-FStar.ModifiesGen-3.smt2                                                            |  20.071s  |  20.071s  |   0.000s  | 0.0%|
|queries-FStar.ModifiesGen-5.smt2                                                            |  20.033s  |  20.033s  |   0.000s  | 0.0%|
|queries-FStar.ModifiesGen-7.smt2                                                            |  20.126s  |  20.126s  |   0.000s  | 0.0%|
|queries-FStar.ModifiesGen.smt2                                                              |  20.141s  |  20.141s  |   0.000s  | 0.0%|
|queries-FStar.Sequence.Permutation.smt2                                                     |  20.112s  |  20.112s  |   0.000s  | 0.0%|
|queries-FStar.UInt.smt2                                                                     |  20.113s  |  20.113s  |   0.000s  | 0.0%|
|queries-FStar.UInt128.smt2                                                                  |  20.110s  |  20.110s  |   0.000s  | 0.0%|
|queries-LowStar.Monotonic.Buffer.smt2                                                       |  20.025s  |  20.025s  |   0.000s  | 0.0%|
|queries-LowStar.RVector.smt2                                                                |  20.132s  |  20.132s  |   0.000s  | 0.0%|
|queries-LowStar.Vector.smt2                                                                 |  20.035s  |  20.035s  |   0.000s  | 0.0%|
|queries-Steel.Effect.Atomic.smt2                                                            |  20.120s  |  20.120s  |   0.000s  | 0.0%|
|queries-Steel.Effect.Common.smt2                                                            |  20.142s  |  20.142s  |   0.000s  | 0.0%|
|queries-Steel.Heap.smt2                                                                     |  20.141s  |  20.141s  |   0.000s  | 0.0%|
|queries-Steel.MonotonicHigherReference.smt2                                                 |  20.042s  |  20.042s  |   0.000s  | 0.0%|
|queries-Steel.Semantics.Hoare.MST.smt2                                                      |  20.032s  |  20.032s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|queries-FStar.Buffer.smt2                                                                   |  20.065s  |  20.065s  |   0.000s  | 0.0%|
|queries-FStar.Endianness.smt2                                                               |  20.134s  |  20.134s  |   0.000s  | 0.0%|
|queries-FStar.Int.smt2                                                                      |  20.105s  |  20.105s  |   0.000s  | 0.0%|
|queries-FStar.Matrix-1.smt2                                                                 |  20.074s  |  20.074s  |   0.000s  | 0.0%|
|queries-FStar.ModifiesGen-3.smt2                                                            |  20.071s  |  20.071s  |   0.000s  | 0.0%|
|queries-FStar.ModifiesGen-5.smt2                                                            |  20.033s  |  20.033s  |   0.000s  | 0.0%|
|queries-FStar.ModifiesGen-7.smt2                                                            |  20.126s  |  20.126s  |   0.000s  | 0.0%|
|queries-FStar.ModifiesGen.smt2                                                              |  20.141s  |  20.141s  |   0.000s  | 0.0%|
|queries-FStar.Sequence.Permutation.smt2                                                     |  20.112s  |  20.112s  |   0.000s  | 0.0%|
|queries-FStar.UInt.smt2                                                                     |  20.113s  |  20.113s  |   0.000s  | 0.0%|
|queries-FStar.UInt128.smt2                                                                  |  20.110s  |  20.110s  |   0.000s  | 0.0%|
|queries-LowStar.Monotonic.Buffer.smt2                                                       |  20.025s  |  20.025s  |   0.000s  | 0.0%|
|queries-LowStar.RVector.smt2                                                                |  20.132s  |  20.132s  |   0.000s  | 0.0%|
|queries-LowStar.Vector.smt2                                                                 |  20.035s  |  20.035s  |   0.000s  | 0.0%|
|queries-Steel.Effect.Atomic.smt2                                                            |  20.120s  |  20.120s  |   0.000s  | 0.0%|
|queries-Steel.Effect.Common.smt2                                                            |  20.142s  |  20.142s  |   0.000s  | 0.0%|
|queries-Steel.Heap.smt2                                                                     |  20.141s  |  20.141s  |   0.000s  | 0.0%|
|queries-Steel.MonotonicHigherReference.smt2                                                 |  20.042s  |  20.042s  |   0.000s  | 0.0%|
|queries-Steel.Semantics.Hoare.MST.smt2                                                      |  20.032s  |  20.032s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|queries-FStar.Buffer.smt2                                                                   |  20.065s  |  20.065s  |   0.000s  | 0.0%|
|queries-FStar.Endianness.smt2                                                               |  20.134s  |  20.134s  |   0.000s  | 0.0%|
|queries-FStar.Int.smt2                                                                      |  20.105s  |  20.105s  |   0.000s  | 0.0%|
|queries-FStar.Matrix-1.smt2                                                                 |  20.074s  |  20.074s  |   0.000s  | 0.0%|
|queries-FStar.ModifiesGen-3.smt2                                                            |  20.071s  |  20.071s  |   0.000s  | 0.0%|
|queries-FStar.ModifiesGen-5.smt2                                                            |  20.033s  |  20.033s  |   0.000s  | 0.0%|
|queries-FStar.ModifiesGen-7.smt2                                                            |  20.126s  |  20.126s  |   0.000s  | 0.0%|
|queries-FStar.ModifiesGen.smt2                                                              |  20.141s  |  20.141s  |   0.000s  | 0.0%|
|queries-FStar.Sequence.Permutation.smt2                                                     |  20.112s  |  20.112s  |   0.000s  | 0.0%|
|queries-FStar.UInt.smt2                                                                     |  20.113s  |  20.113s  |   0.000s  | 0.0%|
|queries-FStar.UInt128.smt2                                                                  |  20.110s  |  20.110s  |   0.000s  | 0.0%|
|queries-LowStar.Monotonic.Buffer.smt2                                                       |  20.025s  |  20.025s  |   0.000s  | 0.0%|
|queries-LowStar.RVector.smt2                                                                |  20.132s  |  20.132s  |   0.000s  | 0.0%|
|queries-LowStar.Vector.smt2                                                                 |  20.035s  |  20.035s  |   0.000s  | 0.0%|
|queries-Steel.Effect.Atomic.smt2                                                            |  20.120s  |  20.120s  |   0.000s  | 0.0%|
|queries-Steel.Effect.Common.smt2                                                            |  20.142s  |  20.142s  |   0.000s  | 0.0%|
|queries-Steel.Heap.smt2                                                                     |  20.141s  |  20.141s  |   0.000s  | 0.0%|
|queries-Steel.MonotonicHigherReference.smt2                                                 |  20.042s  |  20.042s  |   0.000s  | 0.0%|
|queries-Steel.Semantics.Hoare.MST.smt2                                                      |  20.032s  |  20.032s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|queries-FStar.Buffer.smt2                                                                   |  20.065s  |  20.065s  |   0.000s  | 0.0%|
|queries-FStar.Endianness.smt2                                                               |  20.134s  |  20.134s  |   0.000s  | 0.0%|
|queries-FStar.Int.smt2                                                                      |  20.105s  |  20.105s  |   0.000s  | 0.0%|
|queries-FStar.Matrix-1.smt2                                                                 |  20.074s  |  20.074s  |   0.000s  | 0.0%|
|queries-FStar.ModifiesGen-3.smt2                                                            |  20.071s  |  20.071s  |   0.000s  | 0.0%|
|queries-FStar.ModifiesGen-5.smt2                                                            |  20.033s  |  20.033s  |   0.000s  | 0.0%|
|queries-FStar.ModifiesGen-7.smt2                                                            |  20.126s  |  20.126s  |   0.000s  | 0.0%|
|queries-FStar.ModifiesGen.smt2                                                              |  20.141s  |  20.141s  |   0.000s  | 0.0%|
|queries-FStar.Sequence.Permutation.smt2                                                     |  20.112s  |  20.112s  |   0.000s  | 0.0%|
|queries-FStar.UInt.smt2                                                                     |  20.113s  |  20.113s  |   0.000s  | 0.0%|
|queries-FStar.UInt128.smt2                                                                  |  20.110s  |  20.110s  |   0.000s  | 0.0%|
|queries-LowStar.Monotonic.Buffer.smt2                                                       |  20.025s  |  20.025s  |   0.000s  | 0.0%|
|queries-LowStar.RVector.smt2                                                                |  20.132s  |  20.132s  |   0.000s  | 0.0%|
|queries-LowStar.Vector.smt2                                                                 |  20.035s  |  20.035s  |   0.000s  | 0.0%|
|queries-Steel.Effect.Atomic.smt2                                                            |  20.120s  |  20.120s  |   0.000s  | 0.0%|
|queries-Steel.Effect.Common.smt2                                                            |  20.142s  |  20.142s  |   0.000s  | 0.0%|
|queries-Steel.Heap.smt2                                                                     |  20.141s  |  20.141s  |   0.000s  | 0.0%|
|queries-Steel.MonotonicHigherReference.smt2                                                 |  20.042s  |  20.042s  |   0.000s  | 0.0%|
|queries-Steel.Semantics.Hoare.MST.smt2                                                      |  20.032s  |  20.032s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|queries-Steel.Effect.Common.smt2                                                           |  20.142s |165.0MiB|
|queries-FStar.ModifiesGen.smt2                                                             |  20.141s |161.0MiB|
|queries-Steel.Heap.smt2                                                                    |  20.141s |189.0MiB|
|queries-FStar.Endianness.smt2                                                              |  20.134s |160.0MiB|
|queries-LowStar.RVector.smt2                                                               |  20.132s |164.0MiB|
|queries-FStar.ModifiesGen-7.smt2                                                           |  20.126s |197.0MiB|
|queries-Steel.Effect.Atomic.smt2                                                           |  20.120s |299.0MiB|
|queries-FStar.UInt.smt2                                                                    |  20.113s |163.0MiB|
|queries-FStar.Sequence.Permutation.smt2                                                    |  20.112s |431.0MiB|
|queries-FStar.UInt128.smt2                                                                 |  20.110s |322.0MiB|
|queries-FStar.Int.smt2                                                                     |  20.105s |177.0MiB|
|queries-FStar.Matrix-1.smt2                                                                |  20.074s |421.0MiB|
|queries-FStar.ModifiesGen-3.smt2                                                           |  20.071s |175.0MiB|
|queries-FStar.Buffer.smt2                                                                  |  20.065s |159.0MiB|
|queries-Steel.MonotonicHigherReference.smt2                                                |  20.042s |340.0MiB|
|queries-LowStar.Vector.smt2                                                                |  20.035s |163.0MiB|
|queries-FStar.ModifiesGen-5.smt2                                                           |  20.033s |188.0MiB|
|queries-Steel.Semantics.Hoare.MST.smt2                                                     |  20.032s |230.0MiB|
|queries-LowStar.Monotonic.Buffer.smt2                                                      |  20.025s |146.0MiB|
|queries-FStar.Math.Fermat.smt2                                                             |  19.716s |151.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|queries-Steel.Effect.Common.smt2                                                           |  20.142s |165.0MiB|
|queries-FStar.ModifiesGen.smt2                                                             |  20.141s |161.0MiB|
|queries-Steel.Heap.smt2                                                                    |  20.141s |189.0MiB|
|queries-FStar.Endianness.smt2                                                              |  20.134s |160.0MiB|
|queries-LowStar.RVector.smt2                                                               |  20.132s |164.0MiB|
|queries-FStar.ModifiesGen-7.smt2                                                           |  20.126s |197.0MiB|
|queries-Steel.Effect.Atomic.smt2                                                           |  20.120s |299.0MiB|
|queries-FStar.UInt.smt2                                                                    |  20.113s |163.0MiB|
|queries-FStar.Sequence.Permutation.smt2                                                    |  20.112s |431.0MiB|
|queries-FStar.UInt128.smt2                                                                 |  20.110s |322.0MiB|
|queries-FStar.Int.smt2                                                                     |  20.105s |177.0MiB|
|queries-FStar.Matrix-1.smt2                                                                |  20.074s |421.0MiB|
|queries-FStar.ModifiesGen-3.smt2                                                           |  20.071s |175.0MiB|
|queries-FStar.Buffer.smt2                                                                  |  20.065s |159.0MiB|
|queries-Steel.MonotonicHigherReference.smt2                                                |  20.042s |340.0MiB|
|queries-LowStar.Vector.smt2                                                                |  20.035s |163.0MiB|
|queries-FStar.ModifiesGen-5.smt2                                                           |  20.033s |188.0MiB|
|queries-Steel.Semantics.Hoare.MST.smt2                                                     |  20.032s |230.0MiB|
|queries-LowStar.Monotonic.Buffer.smt2                                                      |  20.025s |146.0MiB|
|queries-FStar.Math.Fermat.smt2                                                             |  19.716s |151.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|queries-FStar.Buffer.smt2                                                                   |159.0MiB|159.0MiB|0B| 0.0%|
|queries-FStar.Endianness.smt2                                                               |160.0MiB|160.0MiB|0B| 0.0%|
|queries-FStar.Int.smt2                                                                      |177.0MiB|177.0MiB|0B| 0.0%|
|queries-FStar.Matrix-1.smt2                                                                 |421.0MiB|421.0MiB|0B| 0.0%|
|queries-FStar.ModifiesGen-3.smt2                                                            |175.0MiB|175.0MiB|0B| 0.0%|
|queries-FStar.ModifiesGen-5.smt2                                                            |188.0MiB|188.0MiB|0B| 0.0%|
|queries-FStar.ModifiesGen-7.smt2                                                            |197.0MiB|197.0MiB|0B| 0.0%|
|queries-FStar.ModifiesGen.smt2                                                              |161.0MiB|161.0MiB|0B| 0.0%|
|queries-FStar.Sequence.Permutation.smt2                                                     |431.0MiB|431.0MiB|0B| 0.0%|
|queries-FStar.UInt.smt2                                                                     |163.0MiB|163.0MiB|0B| 0.0%|
|queries-FStar.UInt128.smt2                                                                  |322.0MiB|322.0MiB|0B| 0.0%|
|queries-LowStar.Monotonic.Buffer.smt2                                                       |146.0MiB|146.0MiB|0B| 0.0%|
|queries-LowStar.RVector.smt2                                                                |164.0MiB|164.0MiB|0B| 0.0%|
|queries-LowStar.Vector.smt2                                                                 |163.0MiB|163.0MiB|0B| 0.0%|
|queries-Steel.Effect.Atomic.smt2                                                            |299.0MiB|299.0MiB|0B| 0.0%|
|queries-Steel.Effect.Common.smt2                                                            |165.0MiB|165.0MiB|0B| 0.0%|
|queries-Steel.Heap.smt2                                                                     |189.0MiB|189.0MiB|0B| 0.0%|
|queries-Steel.MonotonicHigherReference.smt2                                                 |340.0MiB|340.0MiB|0B| 0.0%|
|queries-Steel.Semantics.Hoare.MST.smt2                                                      |230.0MiB|230.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|queries-FStar.Buffer.smt2                                                                   |159.0MiB|159.0MiB|0B| 0.0%|
|queries-FStar.Endianness.smt2                                                               |160.0MiB|160.0MiB|0B| 0.0%|
|queries-FStar.Int.smt2                                                                      |177.0MiB|177.0MiB|0B| 0.0%|
|queries-FStar.Matrix-1.smt2                                                                 |421.0MiB|421.0MiB|0B| 0.0%|
|queries-FStar.ModifiesGen-3.smt2                                                            |175.0MiB|175.0MiB|0B| 0.0%|
|queries-FStar.ModifiesGen-5.smt2                                                            |188.0MiB|188.0MiB|0B| 0.0%|
|queries-FStar.ModifiesGen-7.smt2                                                            |197.0MiB|197.0MiB|0B| 0.0%|
|queries-FStar.ModifiesGen.smt2                                                              |161.0MiB|161.0MiB|0B| 0.0%|
|queries-FStar.Sequence.Permutation.smt2                                                     |431.0MiB|431.0MiB|0B| 0.0%|
|queries-FStar.UInt.smt2                                                                     |163.0MiB|163.0MiB|0B| 0.0%|
|queries-FStar.UInt128.smt2                                                                  |322.0MiB|322.0MiB|0B| 0.0%|
|queries-LowStar.Monotonic.Buffer.smt2                                                       |146.0MiB|146.0MiB|0B| 0.0%|
|queries-LowStar.RVector.smt2                                                                |164.0MiB|164.0MiB|0B| 0.0%|
|queries-LowStar.Vector.smt2                                                                 |163.0MiB|163.0MiB|0B| 0.0%|
|queries-Steel.Effect.Atomic.smt2                                                            |299.0MiB|299.0MiB|0B| 0.0%|
|queries-Steel.Effect.Common.smt2                                                            |165.0MiB|165.0MiB|0B| 0.0%|
|queries-Steel.Heap.smt2                                                                     |189.0MiB|189.0MiB|0B| 0.0%|
|queries-Steel.MonotonicHigherReference.smt2                                                 |340.0MiB|340.0MiB|0B| 0.0%|
|queries-Steel.Semantics.Hoare.MST.smt2                                                      |230.0MiB|230.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|queries-FStar.Buffer.smt2                                                                   |159.0MiB|159.0MiB|0B| 0.0%|
|queries-FStar.Endianness.smt2                                                               |160.0MiB|160.0MiB|0B| 0.0%|
|queries-FStar.Int.smt2                                                                      |177.0MiB|177.0MiB|0B| 0.0%|
|queries-FStar.Matrix-1.smt2                                                                 |421.0MiB|421.0MiB|0B| 0.0%|
|queries-FStar.ModifiesGen-3.smt2                                                            |175.0MiB|175.0MiB|0B| 0.0%|
|queries-FStar.ModifiesGen-5.smt2                                                            |188.0MiB|188.0MiB|0B| 0.0%|
|queries-FStar.ModifiesGen-7.smt2                                                            |197.0MiB|197.0MiB|0B| 0.0%|
|queries-FStar.ModifiesGen.smt2                                                              |161.0MiB|161.0MiB|0B| 0.0%|
|queries-FStar.Sequence.Permutation.smt2                                                     |431.0MiB|431.0MiB|0B| 0.0%|
|queries-FStar.UInt.smt2                                                                     |163.0MiB|163.0MiB|0B| 0.0%|
|queries-FStar.UInt128.smt2                                                                  |322.0MiB|322.0MiB|0B| 0.0%|
|queries-LowStar.Monotonic.Buffer.smt2                                                       |146.0MiB|146.0MiB|0B| 0.0%|
|queries-LowStar.RVector.smt2                                                                |164.0MiB|164.0MiB|0B| 0.0%|
|queries-LowStar.Vector.smt2                                                                 |163.0MiB|163.0MiB|0B| 0.0%|
|queries-Steel.Effect.Atomic.smt2                                                            |299.0MiB|299.0MiB|0B| 0.0%|
|queries-Steel.Effect.Common.smt2                                                            |165.0MiB|165.0MiB|0B| 0.0%|
|queries-Steel.Heap.smt2                                                                     |189.0MiB|189.0MiB|0B| 0.0%|
|queries-Steel.MonotonicHigherReference.smt2                                                 |340.0MiB|340.0MiB|0B| 0.0%|
|queries-Steel.Semantics.Hoare.MST.smt2                                                      |230.0MiB|230.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|queries-FStar.Buffer.smt2                                                                   |159.0MiB|159.0MiB|0B| 0.0%|
|queries-FStar.Endianness.smt2                                                               |160.0MiB|160.0MiB|0B| 0.0%|
|queries-FStar.Int.smt2                                                                      |177.0MiB|177.0MiB|0B| 0.0%|
|queries-FStar.Matrix-1.smt2                                                                 |421.0MiB|421.0MiB|0B| 0.0%|
|queries-FStar.ModifiesGen-3.smt2                                                            |175.0MiB|175.0MiB|0B| 0.0%|
|queries-FStar.ModifiesGen-5.smt2                                                            |188.0MiB|188.0MiB|0B| 0.0%|
|queries-FStar.ModifiesGen-7.smt2                                                            |197.0MiB|197.0MiB|0B| 0.0%|
|queries-FStar.ModifiesGen.smt2                                                              |161.0MiB|161.0MiB|0B| 0.0%|
|queries-FStar.Sequence.Permutation.smt2                                                     |431.0MiB|431.0MiB|0B| 0.0%|
|queries-FStar.UInt.smt2                                                                     |163.0MiB|163.0MiB|0B| 0.0%|
|queries-FStar.UInt128.smt2                                                                  |322.0MiB|322.0MiB|0B| 0.0%|
|queries-LowStar.Monotonic.Buffer.smt2                                                       |146.0MiB|146.0MiB|0B| 0.0%|
|queries-LowStar.RVector.smt2                                                                |164.0MiB|164.0MiB|0B| 0.0%|
|queries-LowStar.Vector.smt2                                                                 |163.0MiB|163.0MiB|0B| 0.0%|
|queries-Steel.Effect.Atomic.smt2                                                            |299.0MiB|299.0MiB|0B| 0.0%|
|queries-Steel.Effect.Common.smt2                                                            |165.0MiB|165.0MiB|0B| 0.0%|
|queries-Steel.Heap.smt2                                                                     |189.0MiB|189.0MiB|0B| 0.0%|
|queries-Steel.MonotonicHigherReference.smt2                                                 |340.0MiB|340.0MiB|0B| 0.0%|
|queries-Steel.Semantics.Hoare.MST.smt2                                                      |230.0MiB|230.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|queries-FStar.Sequence.Permutation.smt2                                                    |  20.112s |431.0MiB|
|queries-FStar.Matrix-1.smt2                                                                |  20.074s |421.0MiB|
|queries-Steel.MonotonicHigherReference.smt2                                                |  20.042s |340.0MiB|
|queries-FStar.UInt128.smt2                                                                 |  20.110s |322.0MiB|
|queries-Steel.Array.smt2                                                                   |  12.737s |318.0MiB|
|queries-Steel.ST.EphemeralHashtbl.smt2                                                     |  19.664s |312.0MiB|
|queries-Steel.Effect.smt2                                                                  |  14.930s |303.0MiB|
|queries-Steel.Effect.Atomic.smt2                                                           |  20.120s |299.0MiB|
|queries-Steel.ST.Effect.AtomicAndGhost.smt2                                                |   4.272s |256.0MiB|
|queries-Steel.ST.Effect.Ghost.smt2                                                         |   3.528s |256.0MiB|
|queries-Steel.ST.Effect.Atomic.smt2                                                        |   3.079s |256.0MiB|
|queries-Steel.ST.Coercions.smt2                                                            |   2.613s |256.0MiB|
|queries-Steel.Semantics.Hoare.MST.smt2                                                     |  20.032s |230.0MiB|
|queries-Steel.HigherReference.smt2                                                         |  16.868s |215.0MiB|
|queries-Steel.Heap-1.smt2                                                                  |  16.493s |201.0MiB|
|queries-FStar.ModifiesGen-7.smt2                                                           |  20.126s |197.0MiB|
|queries-Steel.Heap.smt2                                                                    |  20.141s |189.0MiB|
|queries-FStar.ModifiesGen-5.smt2                                                           |  20.033s |188.0MiB|
|queries-Steel.Stepper.smt2                                                                 |  12.373s |181.0MiB|
|queries-FStar.Int.smt2                                                                     |  20.105s |177.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|queries-FStar.Sequence.Permutation.smt2                                                    |  20.112s |431.0MiB|
|queries-FStar.Matrix-1.smt2                                                                |  20.074s |421.0MiB|
|queries-Steel.MonotonicHigherReference.smt2                                                |  20.042s |340.0MiB|
|queries-FStar.UInt128.smt2                                                                 |  20.110s |322.0MiB|
|queries-Steel.Array.smt2                                                                   |  12.737s |318.0MiB|
|queries-Steel.ST.EphemeralHashtbl.smt2                                                     |  19.664s |312.0MiB|
|queries-Steel.Effect.smt2                                                                  |  14.930s |303.0MiB|
|queries-Steel.Effect.Atomic.smt2                                                           |  20.120s |299.0MiB|
|queries-Steel.ST.Effect.AtomicAndGhost.smt2                                                |   4.272s |256.0MiB|
|queries-Steel.ST.Effect.Ghost.smt2                                                         |   3.528s |256.0MiB|
|queries-Steel.ST.Effect.Atomic.smt2                                                        |   3.079s |256.0MiB|
|queries-Steel.ST.Coercions.smt2                                                            |   2.613s |256.0MiB|
|queries-Steel.Semantics.Hoare.MST.smt2                                                     |  20.032s |230.0MiB|
|queries-Steel.HigherReference.smt2                                                         |  16.868s |215.0MiB|
|queries-Steel.Heap-1.smt2                                                                  |  16.493s |201.0MiB|
|queries-FStar.ModifiesGen-7.smt2                                                           |  20.126s |197.0MiB|
|queries-Steel.Heap.smt2                                                                    |  20.141s |189.0MiB|
|queries-FStar.ModifiesGen-5.smt2                                                           |  20.033s |188.0MiB|
|queries-Steel.Stepper.smt2                                                                 |  12.373s |181.0MiB|
|queries-FStar.Int.smt2                                                                     |  20.105s |177.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|queries-FStar.Buffer.smt2                                                                   |  20.065s  |  20.065s  |   0.000s  | 0.0%|
|queries-FStar.Endianness.smt2                                                               |  20.134s  |  20.134s  |   0.000s  | 0.0%|
|queries-FStar.Int.smt2                                                                      |  20.105s  |  20.105s  |   0.000s  | 0.0%|
|queries-FStar.Matrix-1.smt2                                                                 |  20.074s  |  20.074s  |   0.000s  | 0.0%|
|queries-FStar.ModifiesGen-3.smt2                                                            |  20.071s  |  20.071s  |   0.000s  | 0.0%|
|queries-FStar.ModifiesGen-5.smt2                                                            |  20.033s  |  20.033s  |   0.000s  | 0.0%|
|queries-FStar.ModifiesGen-7.smt2                                                            |  20.126s  |  20.126s  |   0.000s  | 0.0%|
|queries-FStar.ModifiesGen.smt2                                                              |  20.141s  |  20.141s  |   0.000s  | 0.0%|
|queries-FStar.Sequence.Permutation.smt2                                                     |  20.112s  |  20.112s  |   0.000s  | 0.0%|
|queries-FStar.UInt.smt2                                                                     |  20.113s  |  20.113s  |   0.000s  | 0.0%|
|queries-FStar.UInt128.smt2                                                                  |  20.110s  |  20.110s  |   0.000s  | 0.0%|
|queries-LowStar.Monotonic.Buffer.smt2                                                       |  20.025s  |  20.025s  |   0.000s  | 0.0%|
|queries-LowStar.RVector.smt2                                                                |  20.132s  |  20.132s  |   0.000s  | 0.0%|
|queries-LowStar.Vector.smt2                                                                 |  20.035s  |  20.035s  |   0.000s  | 0.0%|
|queries-Steel.Effect.Atomic.smt2                                                            |  20.120s  |  20.120s  |   0.000s  | 0.0%|
|queries-Steel.Effect.Common.smt2                                                            |  20.142s  |  20.142s  |   0.000s  | 0.0%|
|queries-Steel.Heap.smt2                                                                     |  20.141s  |  20.141s  |   0.000s  | 0.0%|
|queries-Steel.MonotonicHigherReference.smt2                                                 |  20.042s  |  20.042s  |   0.000s  | 0.0%|
</details>
