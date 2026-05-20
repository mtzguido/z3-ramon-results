Comparing data and data


# SUMMARY
- LHS tests = 1008
- RHS tests = 1008
- LHS success = 1008  (100.0%)
- RHS success = 1008  (100.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: UFDTNIA.tar.zst
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: bc6c38e7d3424b88a505cacba4b268d0774d4547
Z3 branch: master
Z3 options: "-T:20"
Z3 inputs: https://zenodo.org/records/16740866/files/UFDTNIA.tar.zst?download=1
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
Job tag: UFDTNIA.tar.zst
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: bc6c38e7d3424b88a505cacba4b268d0774d4547
Z3 branch: master
Z3 options: "-T:20"
Z3 inputs: https://zenodo.org/records/16740866/files/UFDTNIA.tar.zst?download=1
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
|non-incremental/UFDTNIA/2019-Gleiss/non-interference/10-ni-rsa-exponentiation.spec.smt2     |  20.280s  |  20.280s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20230314-Jaroslav-Bendik-Certora/52759_b3ecd2335fd16ec2eee2_9_UFDTNIA.smt2  |  20.033s  |  20.033s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__ResizableUniformSizedSeq_v.4.smt2  |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__ResizableUniformSizedSeq_v.7.smt2  |   0.235s  |   0.235s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__ResizableUniformSizedSeq_v.9.smt2  |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__UniformSizedSeq_v.1.smt2  |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__UniformSizedSeq_v.2.smt2  |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__UniformSizedSeq_v.4.smt2  |   0.222s  |   0.222s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__UniformSizedSeq_v.5.smt2  |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__UniformSizedSeq_v.6.smt2  |   0.367s  |   0.367s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__math_v.smt2        |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__math_vlib_marshalling.math_v.distribute_left._01.smt2  |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.10.smt2  |   5.277s  |   5.277s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.15.smt2  |   9.602s  |   9.602s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.20.smt2  |   4.318s  |   4.318s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.23.smt2  |   9.135s  |   9.135s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.4.smt2  |   0.512s  |   0.512s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.7.smt2  |   0.542s  |   0.542s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.8.smt2  |   0.653s  |   0.653s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/define.16.smt2                            |   0.057s  |   0.057s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/UFDTNIA/2019-Gleiss/non-interference/10-ni-rsa-exponentiation.spec.smt2     |  20.280s  |  20.280s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20230314-Jaroslav-Bendik-Certora/52759_b3ecd2335fd16ec2eee2_9_UFDTNIA.smt2  |  20.033s  |  20.033s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__ResizableUniformSizedSeq_v.4.smt2  |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__ResizableUniformSizedSeq_v.7.smt2  |   0.235s  |   0.235s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__ResizableUniformSizedSeq_v.9.smt2  |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__UniformSizedSeq_v.1.smt2  |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__UniformSizedSeq_v.2.smt2  |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__UniformSizedSeq_v.4.smt2  |   0.222s  |   0.222s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__UniformSizedSeq_v.5.smt2  |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__UniformSizedSeq_v.6.smt2  |   0.367s  |   0.367s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__math_v.smt2        |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__math_vlib_marshalling.math_v.distribute_left._01.smt2  |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.10.smt2  |   5.277s  |   5.277s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.15.smt2  |   9.602s  |   9.602s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.20.smt2  |   4.318s  |   4.318s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.23.smt2  |   9.135s  |   9.135s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.4.smt2  |   0.512s  |   0.512s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.7.smt2  |   0.542s  |   0.542s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.8.smt2  |   0.653s  |   0.653s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/define.16.smt2                            |   0.057s  |   0.057s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/UFDTNIA/2019-Gleiss/non-interference/10-ni-rsa-exponentiation.spec.smt2     |  20.280s  |  20.280s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20230314-Jaroslav-Bendik-Certora/52759_b3ecd2335fd16ec2eee2_9_UFDTNIA.smt2  |  20.033s  |  20.033s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__ResizableUniformSizedSeq_v.4.smt2  |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__ResizableUniformSizedSeq_v.7.smt2  |   0.235s  |   0.235s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__ResizableUniformSizedSeq_v.9.smt2  |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__UniformSizedSeq_v.1.smt2  |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__UniformSizedSeq_v.2.smt2  |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__UniformSizedSeq_v.4.smt2  |   0.222s  |   0.222s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__UniformSizedSeq_v.5.smt2  |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__UniformSizedSeq_v.6.smt2  |   0.367s  |   0.367s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__math_v.smt2        |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__math_vlib_marshalling.math_v.distribute_left._01.smt2  |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.10.smt2  |   5.277s  |   5.277s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.15.smt2  |   9.602s  |   9.602s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.20.smt2  |   4.318s  |   4.318s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.23.smt2  |   9.135s  |   9.135s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.4.smt2  |   0.512s  |   0.512s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.7.smt2  |   0.542s  |   0.542s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.8.smt2  |   0.653s  |   0.653s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/define.16.smt2                            |   0.057s  |   0.057s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/UFDTNIA/2019-Gleiss/non-interference/10-ni-rsa-exponentiation.spec.smt2     |  20.280s  |  20.280s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20230314-Jaroslav-Bendik-Certora/52759_b3ecd2335fd16ec2eee2_9_UFDTNIA.smt2  |  20.033s  |  20.033s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__ResizableUniformSizedSeq_v.4.smt2  |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__ResizableUniformSizedSeq_v.7.smt2  |   0.235s  |   0.235s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__ResizableUniformSizedSeq_v.9.smt2  |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__UniformSizedSeq_v.1.smt2  |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__UniformSizedSeq_v.2.smt2  |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__UniformSizedSeq_v.4.smt2  |   0.222s  |   0.222s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__UniformSizedSeq_v.5.smt2  |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__UniformSizedSeq_v.6.smt2  |   0.367s  |   0.367s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__math_v.smt2        |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__math_vlib_marshalling.math_v.distribute_left._01.smt2  |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.10.smt2  |   5.277s  |   5.277s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.15.smt2  |   9.602s  |   9.602s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.20.smt2  |   4.318s  |   4.318s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.23.smt2  |   9.135s  |   9.135s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.4.smt2  |   0.512s  |   0.512s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.7.smt2  |   0.542s  |   0.542s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.8.smt2  |   0.653s  |   0.653s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/define.16.smt2                            |   0.057s  |   0.057s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/UFDTNIA/2019-Gleiss/non-interference/10-ni-rsa-exponentiation.spec.smt2    |  20.280s |2166.0MiB|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-multilog__setup_v.6.smt2 |  20.158s |801.0MiB|
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__idt__def.4.smt2                       |  20.130s |309.0MiB|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/pagetable__pagetable_spec_impl.1.smt2    |  20.129s |332.0MiB|
|non-incremental/UFDTNIA/20241211-verus/verismo/security__monitor.15.smt2                   |  20.116s |202.0MiB|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-commit_mask.31.smt2            |  20.106s |752.0MiB|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l2_refinement.3.smt2 |  20.104s |96.508MiB|
|non-incremental/UFDTNIA/20241211-verus/verismo/security__monitor.12.smt2                   |  20.103s |280.0MiB|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-segment__segment_page_clear.smt2 |  20.093s |121.0MiB|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-multilog__append_v.2.smt2 |  20.080s |97.576MiB|
|non-incremental/UFDTNIA/20241211-verus/verismo/security__secret.13.smt2                    |  20.079s |274.0MiB|
|non-incremental/UFDTNIA/20241211-verus/verismo/linkedlist.4.smt2                           |  20.077s |144.0MiB|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-queues__page_queue_push_back.smt2 |  20.075s |124.0MiB|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__vmsa.2.smt2                       |  20.071s |529.0MiB|
|non-incremental/UFDTNIA/20241211-verus/verismo/security__monitor.24.smt2                   |  20.068s |153.0MiB|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-queues__page_queue_push.smt2   |  20.065s |119.0MiB|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l2_impl__PT.18.smt2  |  20.062s |99.0MiB|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-definitions_ulib_definitions_u.impl_%3.lemma_entry_sizes_aligned._02.smt2 |  20.062s |28.236MiB|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-multilog__multilogimpl_v.5.smt2 |  20.050s |83.56MiB|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l2_refinement.4.smt2 |  20.047s |81.144MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/UFDTNIA/2019-Gleiss/non-interference/10-ni-rsa-exponentiation.spec.smt2    |  20.280s |2166.0MiB|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-multilog__setup_v.6.smt2 |  20.158s |801.0MiB|
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__idt__def.4.smt2                       |  20.130s |309.0MiB|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/pagetable__pagetable_spec_impl.1.smt2    |  20.129s |332.0MiB|
|non-incremental/UFDTNIA/20241211-verus/verismo/security__monitor.15.smt2                   |  20.116s |202.0MiB|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-commit_mask.31.smt2            |  20.106s |752.0MiB|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l2_refinement.3.smt2 |  20.104s |96.508MiB|
|non-incremental/UFDTNIA/20241211-verus/verismo/security__monitor.12.smt2                   |  20.103s |280.0MiB|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-segment__segment_page_clear.smt2 |  20.093s |121.0MiB|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-multilog__append_v.2.smt2 |  20.080s |97.576MiB|
|non-incremental/UFDTNIA/20241211-verus/verismo/security__secret.13.smt2                    |  20.079s |274.0MiB|
|non-incremental/UFDTNIA/20241211-verus/verismo/linkedlist.4.smt2                           |  20.077s |144.0MiB|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-queues__page_queue_push_back.smt2 |  20.075s |124.0MiB|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__vmsa.2.smt2                       |  20.071s |529.0MiB|
|non-incremental/UFDTNIA/20241211-verus/verismo/security__monitor.24.smt2                   |  20.068s |153.0MiB|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-queues__page_queue_push.smt2   |  20.065s |119.0MiB|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l2_impl__PT.18.smt2  |  20.062s |99.0MiB|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-definitions_ulib_definitions_u.impl_%3.lemma_entry_sizes_aligned._02.smt2 |  20.062s |28.236MiB|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-multilog__multilogimpl_v.5.smt2 |  20.050s |83.56MiB|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l2_refinement.4.smt2 |  20.047s |81.144MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/UFDTNIA/2019-Gleiss/non-interference/10-ni-rsa-exponentiation.spec.smt2     |2166.0MiB|2166.0MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20230314-Jaroslav-Bendik-Certora/52759_b3ecd2335fd16ec2eee2_9_UFDTNIA.smt2  |41.972MiB|41.972MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__ResizableUniformSizedSeq_v.4.smt2  |23.332MiB|23.332MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__ResizableUniformSizedSeq_v.7.smt2  |25.68MiB|25.68MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__ResizableUniformSizedSeq_v.9.smt2  |25.388MiB|25.388MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__UniformSizedSeq_v.1.smt2  |22.668MiB|22.668MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__UniformSizedSeq_v.2.smt2  |22.576MiB|22.576MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__UniformSizedSeq_v.4.smt2  |23.06MiB|23.06MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__UniformSizedSeq_v.5.smt2  |22.668MiB|22.668MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__UniformSizedSeq_v.6.smt2  |24.896MiB|24.896MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__math_v.smt2        |20.828MiB|20.828MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__math_vlib_marshalling.math_v.distribute_left._01.smt2  |21.356MiB|21.356MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.10.smt2  |48.772MiB|48.772MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.15.smt2  |70.224MiB|70.224MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.20.smt2  |46.488MiB|46.488MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.23.smt2  |72.848MiB|72.848MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.4.smt2  |29.372MiB|29.372MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.7.smt2  |30.392MiB|30.392MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.8.smt2  |30.428MiB|30.428MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/define.16.smt2                            |19.852MiB|19.852MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/UFDTNIA/2019-Gleiss/non-interference/10-ni-rsa-exponentiation.spec.smt2     |2166.0MiB|2166.0MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20230314-Jaroslav-Bendik-Certora/52759_b3ecd2335fd16ec2eee2_9_UFDTNIA.smt2  |41.972MiB|41.972MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__ResizableUniformSizedSeq_v.4.smt2  |23.332MiB|23.332MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__ResizableUniformSizedSeq_v.7.smt2  |25.68MiB|25.68MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__ResizableUniformSizedSeq_v.9.smt2  |25.388MiB|25.388MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__UniformSizedSeq_v.1.smt2  |22.668MiB|22.668MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__UniformSizedSeq_v.2.smt2  |22.576MiB|22.576MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__UniformSizedSeq_v.4.smt2  |23.06MiB|23.06MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__UniformSizedSeq_v.5.smt2  |22.668MiB|22.668MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__UniformSizedSeq_v.6.smt2  |24.896MiB|24.896MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__math_v.smt2        |20.828MiB|20.828MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__math_vlib_marshalling.math_v.distribute_left._01.smt2  |21.356MiB|21.356MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.10.smt2  |48.772MiB|48.772MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.15.smt2  |70.224MiB|70.224MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.20.smt2  |46.488MiB|46.488MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.23.smt2  |72.848MiB|72.848MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.4.smt2  |29.372MiB|29.372MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.7.smt2  |30.392MiB|30.392MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.8.smt2  |30.428MiB|30.428MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/define.16.smt2                            |19.852MiB|19.852MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/UFDTNIA/2019-Gleiss/non-interference/10-ni-rsa-exponentiation.spec.smt2     |2166.0MiB|2166.0MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20230314-Jaroslav-Bendik-Certora/52759_b3ecd2335fd16ec2eee2_9_UFDTNIA.smt2  |41.972MiB|41.972MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__ResizableUniformSizedSeq_v.4.smt2  |23.332MiB|23.332MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__ResizableUniformSizedSeq_v.7.smt2  |25.68MiB|25.68MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__ResizableUniformSizedSeq_v.9.smt2  |25.388MiB|25.388MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__UniformSizedSeq_v.1.smt2  |22.668MiB|22.668MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__UniformSizedSeq_v.2.smt2  |22.576MiB|22.576MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__UniformSizedSeq_v.4.smt2  |23.06MiB|23.06MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__UniformSizedSeq_v.5.smt2  |22.668MiB|22.668MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__UniformSizedSeq_v.6.smt2  |24.896MiB|24.896MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__math_v.smt2        |20.828MiB|20.828MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__math_vlib_marshalling.math_v.distribute_left._01.smt2  |21.356MiB|21.356MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.10.smt2  |48.772MiB|48.772MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.15.smt2  |70.224MiB|70.224MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.20.smt2  |46.488MiB|46.488MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.23.smt2  |72.848MiB|72.848MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.4.smt2  |29.372MiB|29.372MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.7.smt2  |30.392MiB|30.392MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.8.smt2  |30.428MiB|30.428MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/define.16.smt2                            |19.852MiB|19.852MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/UFDTNIA/2019-Gleiss/non-interference/10-ni-rsa-exponentiation.spec.smt2     |2166.0MiB|2166.0MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20230314-Jaroslav-Bendik-Certora/52759_b3ecd2335fd16ec2eee2_9_UFDTNIA.smt2  |41.972MiB|41.972MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__ResizableUniformSizedSeq_v.4.smt2  |23.332MiB|23.332MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__ResizableUniformSizedSeq_v.7.smt2  |25.68MiB|25.68MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__ResizableUniformSizedSeq_v.9.smt2  |25.388MiB|25.388MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__UniformSizedSeq_v.1.smt2  |22.668MiB|22.668MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__UniformSizedSeq_v.2.smt2  |22.576MiB|22.576MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__UniformSizedSeq_v.4.smt2  |23.06MiB|23.06MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__UniformSizedSeq_v.5.smt2  |22.668MiB|22.668MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__UniformSizedSeq_v.6.smt2  |24.896MiB|24.896MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__math_v.smt2        |20.828MiB|20.828MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__math_vlib_marshalling.math_v.distribute_left._01.smt2  |21.356MiB|21.356MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.10.smt2  |48.772MiB|48.772MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.15.smt2  |70.224MiB|70.224MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.20.smt2  |46.488MiB|46.488MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.23.smt2  |72.848MiB|72.848MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.4.smt2  |29.372MiB|29.372MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.7.smt2  |30.392MiB|30.392MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.8.smt2  |30.428MiB|30.428MiB|0B| 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/define.16.smt2                            |19.852MiB|19.852MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/UFDTNIA/2019-Gleiss/non-interference/10-ni-rsa-exponentiation.spec.smt2    |  20.280s |2166.0MiB|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-multilog__setup_v.6.smt2 |  20.158s |801.0MiB|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-commit_mask.31.smt2            |  20.106s |752.0MiB|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__vmsa.2.smt2                       |  20.071s |529.0MiB|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/pagetable__pagetable_spec_impl.1.smt2    |  20.129s |332.0MiB|
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__idt__def.4.smt2                       |  20.130s |309.0MiB|
|non-incremental/UFDTNIA/20241211-verus/verismo/security__pcr.5.smt2                        |  16.338s |286.0MiB|
|non-incremental/UFDTNIA/20241211-verus/verismo/security__monitor.12.smt2                   |  20.103s |280.0MiB|
|non-incremental/UFDTNIA/20241211-verus/verismo/security__secret.13.smt2                    |  20.079s |274.0MiB|
|non-incremental/UFDTNIA/20241211-verus/verismo/pgtable_e__pte.22.smt2                      |  10.471s |267.0MiB|
|non-incremental/UFDTNIA/20241211-verus/verismo/security__mem.38.smt2                       |   6.446s |264.0MiB|
|non-incremental/UFDTNIA/20241211-verus/verismo/mshyper__wakeup.7.smt2                      |  14.561s |263.0MiB|
|non-incremental/UFDTNIA/20241211-verus/verismo/security__monitor.15.smt2                   |  20.116s |202.0MiB|
|non-incremental/UFDTNIA/20241211-verus/verismo/mshyper.19.smt2                             |  15.091s |198.0MiB|
|non-incremental/UFDTNIA/20241211-verus/verismo/vbox__vbox.3.smt2                           |  10.281s |191.0MiB|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__vmsa.1.smt2                       |  10.343s |187.0MiB|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.140.smt2              |   8.643s |182.0MiB|
|non-incremental/UFDTNIA/20241211-verus/verismo/security__monitor.14.smt2                   |  20.046s |180.0MiB|
|non-incremental/UFDTNIA/20241211-verus/verismo/security__monitor.16.smt2                   |  20.037s |180.0MiB|
|non-incremental/UFDTNIA/20241211-verus/verismo/security__monitor.10.smt2                   |  20.039s |175.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/UFDTNIA/2019-Gleiss/non-interference/10-ni-rsa-exponentiation.spec.smt2    |  20.280s |2166.0MiB|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-multilog__setup_v.6.smt2 |  20.158s |801.0MiB|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-commit_mask.31.smt2            |  20.106s |752.0MiB|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__vmsa.2.smt2                       |  20.071s |529.0MiB|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/pagetable__pagetable_spec_impl.1.smt2    |  20.129s |332.0MiB|
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__idt__def.4.smt2                       |  20.130s |309.0MiB|
|non-incremental/UFDTNIA/20241211-verus/verismo/security__pcr.5.smt2                        |  16.338s |286.0MiB|
|non-incremental/UFDTNIA/20241211-verus/verismo/security__monitor.12.smt2                   |  20.103s |280.0MiB|
|non-incremental/UFDTNIA/20241211-verus/verismo/security__secret.13.smt2                    |  20.079s |274.0MiB|
|non-incremental/UFDTNIA/20241211-verus/verismo/pgtable_e__pte.22.smt2                      |  10.471s |267.0MiB|
|non-incremental/UFDTNIA/20241211-verus/verismo/security__mem.38.smt2                       |   6.446s |264.0MiB|
|non-incremental/UFDTNIA/20241211-verus/verismo/mshyper__wakeup.7.smt2                      |  14.561s |263.0MiB|
|non-incremental/UFDTNIA/20241211-verus/verismo/security__monitor.15.smt2                   |  20.116s |202.0MiB|
|non-incremental/UFDTNIA/20241211-verus/verismo/mshyper.19.smt2                             |  15.091s |198.0MiB|
|non-incremental/UFDTNIA/20241211-verus/verismo/vbox__vbox.3.smt2                           |  10.281s |191.0MiB|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__vmsa.1.smt2                       |  10.343s |187.0MiB|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.140.smt2              |   8.643s |182.0MiB|
|non-incremental/UFDTNIA/20241211-verus/verismo/security__monitor.14.smt2                   |  20.046s |180.0MiB|
|non-incremental/UFDTNIA/20241211-verus/verismo/security__monitor.16.smt2                   |  20.037s |180.0MiB|
|non-incremental/UFDTNIA/20241211-verus/verismo/security__monitor.10.smt2                   |  20.039s |175.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/UFDTNIA/2019-Gleiss/non-interference/10-ni-rsa-exponentiation.spec.smt2     |  20.280s  |  20.280s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20230314-Jaroslav-Bendik-Certora/52759_b3ecd2335fd16ec2eee2_9_UFDTNIA.smt2  |  20.033s  |  20.033s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__ResizableUniformSizedSeq_v.4.smt2  |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__ResizableUniformSizedSeq_v.7.smt2  |   0.235s  |   0.235s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__ResizableUniformSizedSeq_v.9.smt2  |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__UniformSizedSeq_v.1.smt2  |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__UniformSizedSeq_v.2.smt2  |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__UniformSizedSeq_v.4.smt2  |   0.222s  |   0.222s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__UniformSizedSeq_v.5.smt2  |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__UniformSizedSeq_v.6.smt2  |   0.367s  |   0.367s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__math_v.smt2        |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__math_vlib_marshalling.math_v.distribute_left._01.smt2  |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.10.smt2  |   5.277s  |   5.277s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.15.smt2  |   9.602s  |   9.602s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.20.smt2  |   4.318s  |   4.318s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.23.smt2  |   9.135s  |   9.135s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.4.smt2  |   0.512s  |   0.512s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.7.smt2  |   0.542s  |   0.542s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.8.smt2  |   0.653s  |   0.653s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/define.16.smt2                            |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/define.19.smt2                            |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/define.20.smt2                            |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/define.22.smt2                            |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/define.23.smt2                            |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/define.29.smt2                            |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/define.33.smt2                            |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/define.37.smt2                            |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/define.39.smt2                            |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/define.43.smt2                            |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/define.44.smt2                            |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/kernel__create_and_map_pages.1.smt2       |   0.952s  |   0.952s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/kernel__create_and_map_pages.6.smt2       |   1.093s  |   1.093s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/kernel__create_and_share_pages.3.smt2     |   2.916s  |   2.916s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/kernel__create_and_share_pages.4.smt2     |   0.935s  |   0.935s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/kernel__mem_util.2.smt2                   |   0.818s  |   0.818s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/kernel__schedule_idle_cpu.smt2            |   1.081s  |   1.081s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/kernel__syscall_new_proc.smt2             |  16.497s  |  16.497s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/kernel__syscall_receive_empty.2.smt2      |   1.790s  |   1.790s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/kernel__syscall_send_endpoint.smt2        |   4.053s  |   4.053s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/kernel__syscall_send_pages.smt2           |   8.372s  |   8.372s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/lemma__lemma_u.1.smt2                     |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/lemma__lemma_u.2.smt2                     |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/memory_manager__spec_impl.12.smt2         |   0.561s  |   0.561s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/memory_manager__spec_impl.2.smt2          |   0.258s  |   0.258s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/memory_manager__spec_impl.5.smt2          |   0.697s  |   0.697s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/memory_manager__spec_impl.8.smt2          |   0.223s  |   0.223s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/memory_manager__spec_impl.9.smt2          |   0.222s  |   0.222s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/pagetable__pagetable_spec_impl.1.smt2     |  20.129s  |  20.129s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/pagetable__pagetable_spec_impl.10.smt2    |   0.296s  |   0.296s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/pagetable__pagetable_spec_impl.11.smt2    |   0.328s  |   0.328s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/pagetable__pagetable_spec_impl.5.smt2     |   1.184s  |   1.184s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/pagetable__pagetable_spec_impl.6.smt2     |   0.369s  |   0.369s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/pagetable__pagetable_spec_impl.7.smt2     |   0.532s  |   0.532s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/process_manager__spec_impl.1.smt2         |   0.340s  |   0.340s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/process_manager__spec_impl.12.smt2        |   0.281s  |   0.281s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/process_manager__spec_impl.13.smt2        |   0.330s  |   0.330s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/process_manager__spec_impl.14.smt2        |   0.325s  |   0.325s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/process_manager__spec_impl.19.smt2        |   0.354s  |   0.354s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/process_manager__spec_impl.2.smt2         |   0.236s  |   0.236s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/process_manager__spec_impl.20.smt2        |   0.336s  |   0.336s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/process_manager__spec_impl.21.smt2        |   0.309s  |   0.309s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/process_manager__spec_impl.24.smt2        |   0.323s  |   0.323s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/process_manager__spec_impl.26.smt2        |   1.539s  |   1.539s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/process_manager__spec_impl.3.smt2         |   0.413s  |   0.413s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/process_manager__spec_impl.33.smt2        |   1.531s  |   1.531s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/process_manager__spec_impl.6.smt2         |   0.293s  |   0.293s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/process_manager__spec_impl.7.smt2         |   0.300s  |   0.300s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/process_manager__spec_impl.8.smt2         |   0.402s  |   0.402s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/util__page_ptr_util_u.13.smt2             |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/util__page_ptr_util_u.14.smt2             |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/util__page_ptr_util_u.8.smt2              |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/atmosphere/va_range.2.smt2                           |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/splinterdb/marshalling__KVPairFormat_v.1.smt2        |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/splinterdb/marshalling__KVPairFormat_v.3.smt2        |   0.673s  |   0.673s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/splinterdb/marshalling__KVPairFormat_v.7.smt2        |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/splinterdb/marshalling__ResizableUniformSizedSeq_v.10.smt2  |   0.312s  |   0.312s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/splinterdb/marshalling__ResizableUniformSizedSeq_v.3.smt2  |   0.196s  |   0.196s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/splinterdb/marshalling__ResizableUniformSizedSeq_v.9.smt2  |   0.182s  |   0.182s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/splinterdb/marshalling__UniformSizedSeq_v.2.smt2     |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/splinterdb/marshalling__UniformSizedSeq_v.5.smt2     |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/splinterdb/marshalling__math_v.smt2                  |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/splinterdb/marshalling__math_vlib_marshalling.math_v.distribute_left._01.smt2  |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/ironkv-smt-verus_extra__seq_lib_v.15.smt2    |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/ironkv-smt-verus_extra__seq_lib_v.5.smt2     |   0.505s  |   0.505s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/ironkv-smt-verus_extra__seq_lib_vlib_verus_extra.seq_lib_v.lemma_seq_fold_left_sum_le._01.smt2  |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-alloc_fast.3.smt2               |   0.464s  |   0.464s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-alloc_fast.4.smt2               |   0.219s  |   0.219s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-alloc_generic.2.smt2            |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-alloc_generic.5.smt2            |   1.618s  |   1.618s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-alloc_generic.9.smt2            |   0.401s  |   0.401s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-alloc_generic__page_free_list_extendlib_alloc_generic.page_free_list_extend._03.smt2  |   0.263s  |   0.263s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-alloc_generic__page_free_list_extendlib_alloc_generic.page_free_list_extend._04.smt2  |   0.228s  |   0.228s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-alloc_generic__page_free_list_extendlib_alloc_generic.page_free_list_extend._05.smt2  |   0.243s  |   0.243s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-alloc_generic__page_free_list_extendlib_alloc_generic.page_free_list_extend._06.smt2  |   0.289s  |   0.289s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-alloc_generic__page_free_list_extendlib_alloc_generic.page_free_list_extend._07.smt2  |   0.202s  |   0.202s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-alloc_generic__page_free_list_extendlib_alloc_generic.page_free_list_extend._09.smt2  |   0.219s  |   0.219s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-bin_sizes.1.smt2                |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-bin_sizes.10.smt2               |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-bin_sizes.12.smt2               |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-bin_sizes.14.smt2               |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-bin_sizes.19.smt2               |   0.204s  |   0.204s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-bin_sizes.30.smt2               |   0.228s  |   0.228s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-bin_sizes.31.smt2               |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-bin_sizes.33.smt2               |   0.733s  |   0.733s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-bin_sizes.35.smt2               |   0.208s  |   0.208s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-bin_sizes.40.smt2               |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-bin_sizes.41.smt2               |   0.224s  |   0.224s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-bin_sizes.42.smt2               |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-bin_sizes.45.smt2               |   0.813s  |   0.813s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-bin_sizes.47.smt2               |   0.473s  |   0.473s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-bin_sizeslib_bin_sizes.lemma_div_is_ordered._01.smt2  |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-bin_sizeslib_bin_sizes.mod8._01.smt2  |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-commit_mask.1.smt2              |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-commit_mask.11.smt2             |   3.834s  |   3.834s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-commit_mask.13.smt2             |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-commit_mask.17.smt2             |   0.170s  |   0.170s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-commit_mask.2.smt2              |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-commit_mask.23.smt2             |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-commit_mask.27.smt2             |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-commit_mask.31.smt2             |  20.106s  |  20.106s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-commit_mask.35.smt2             |   0.306s  |   0.306s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-commit_mask.4.smt2              |   0.201s  |   0.201s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-commit_mask.5.smt2              |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-commit_mask.6.smt2              |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-commit_segment.1.smt2           |   2.877s  |   2.877s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-commit_segment.6.smt2           |   0.746s  |   0.746s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-config.15.smt2                  |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-config.17.smt2                  |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-config.18.smt2                  |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-config.21.smt2                  |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-config.22.smt2                  |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-config.23.smt2                  |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-config.24.smt2                  |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-config.27.smt2                  |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-config.28.smt2                  |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-config.32.smt2                  |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-config.36.smt2                  |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-config.38.smt2                  |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-free.3.smt2                     |   1.490s  |   1.490s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-free.6.smt2                     |   1.504s  |   1.504s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-init.1.smt2                     |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-init.10.smt2                    |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-init.11.smt2                    |   0.257s  |   0.257s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-init.12.smt2                    |   0.275s  |   0.275s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-init.13.smt2                    |   1.254s  |   1.254s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-layout.12.smt2                  |   0.169s  |   0.169s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-layout.13.smt2                  |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-layout.17.smt2                  |   0.281s  |   0.281s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-layout.19.smt2                  |   0.247s  |   0.247s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-layout.21.smt2                  |   0.517s  |   0.517s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-layout.22.smt2                  |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-layout.26.smt2                  |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-layout.27.smt2                  |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-layout.4.smt2                   |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-layout.6.smt2                   |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-layout__align_down.smt2         |   0.217s  |   0.217s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-layout__align_downlib_layout.align_down._02.smt2  |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-layout__align_downlib_layout.align_down._03.smt2  |  10.546s  |  10.546s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-layout__block_ptr_aligned_to_word.smt2  |   4.241s  |   4.241s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-layout__two_mul_with_bit1.smt2  |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-layout__two_mul_with_bit1lib_layout.two_mul_with_bit1._01.smt2  |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-layoutlib_layout.align_up._02.smt2  |   2.242s  |   2.242s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-layoutlib_layout.bitand_with_mask_gives_rounding._09.smt2  |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-layoutlib_layout.calculate_page_block_at._02.smt2  |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-layoutlib_layout.calculate_slice_page_ptr_from_block._01.smt2  |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-linked_list.11.smt2             |   0.274s  |   0.274s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-linked_list.13.smt2             |   1.112s  |   1.112s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-linked_list.14.smt2             |   0.719s  |   0.719s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-linked_list.16.smt2             |   0.497s  |   0.497s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-linked_list.21.smt2             |   0.604s  |   0.604s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-linked_list.22.smt2             |   0.663s  |   0.663s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-linked_list.24.smt2             |   0.244s  |   0.244s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-linked_list.26.smt2             |   0.193s  |   0.193s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-linked_list.3.smt2              |   0.700s  |   0.700s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-linked_list.32.smt2             |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-linked_list.39.smt2             |   0.198s  |   0.198s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-linked_list.4.smt2              |   0.421s  |   0.421s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-linked_list.9.smt2              |   0.235s  |   0.235s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-linked_listlib_linked_list.impl_%2.prepend_contiguous_blocks._03.smt2  |   0.209s  |   0.209s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-linked_listlib_linked_list.impl_%2.prepend_contiguous_blocks._05.smt2  |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-linked_listlib_linked_list.impl_%2.prepend_contiguous_blocks._06.smt2  |   0.262s  |   0.262s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-linked_listlib_linked_list.impl_%2.prepend_contiguous_blocks._08.smt2  |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-linked_listlib_linked_list.impl_%2.prepend_contiguous_blocks._09.smt2  |   0.191s  |   0.191s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-os_alloc.3.smt2                 |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-os_alloc.6.smt2                 |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-os_alloc.8.smt2                 |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-os_commit.2.smt2                |   0.534s  |   0.534s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-os_mem_util.10.smt2             |   0.601s  |   0.601s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-os_mem_util.11.smt2             |   0.262s  |   0.262s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-os_mem_util.15.smt2             |   0.312s  |   0.312s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-os_mem_util.16.smt2             |   0.500s  |   0.500s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-os_mem_util.19.smt2             |   0.538s  |   0.538s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-os_mem_util.2.smt2              |   0.475s  |   0.475s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-os_mem_util.3.smt2              |   0.220s  |   0.220s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-os_mem_util.5.smt2              |   0.225s  |   0.225s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-os_mem_util.9.smt2              |   0.539s  |   0.539s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-os_mem_utillib_os_mem_util.preserves_mem_chunk_good_except._01.smt2  |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-os_mem_utillib_os_mem_util.preserves_mem_chunk_good_on_transfer_to_capacity._02.smt2  |   0.242s  |   0.242s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-page.15.smt2                    |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-page.16.smt2                    |   0.812s  |   0.812s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-page.8.smt2                     |   0.298s  |   0.298s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-page_organization__PageOrg.16.smt2  |   0.501s  |   0.501s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-page_organization__PageOrg.19.smt2  |   0.427s  |   0.427s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-page_organization__PageOrg.22.smt2  |   0.439s  |   0.439s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-page_organization__PageOrg.25.smt2  |   0.527s  |   0.527s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-page_organization__PageOrg.28.smt2  |   0.322s  |   0.322s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-page_organization__PageOrg.29.smt2  |   0.947s  |   0.947s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-page_organization__PageOrg.32.smt2  |   0.282s  |   0.282s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-page_organization__PageOrg.33.smt2  |   0.251s  |   0.251s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-page_organization__PageOrg.35.smt2  |   1.293s  |   1.293s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-page_organization__PageOrg.39.smt2  |   0.930s  |   0.930s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-page_organization__PageOrg.40.smt2  |   0.275s  |   0.275s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-page_organization__PageOrg.45.smt2  |   1.490s  |   1.490s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-page_organization__PageOrg.5.smt2  |   0.571s  |   0.571s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-page_organization__PageOrg.51.smt2  |   0.444s  |   0.444s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-page_organization__PageOrg.56.smt2  |   0.516s  |   0.516s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-page_organization__PageOrg.60.smt2  |   2.359s  |   2.359s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-page_organization__PageOrg.64.smt2  |   0.387s  |   0.387s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-page_organization__PageOrg.65.smt2  |   1.197s  |   1.197s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-page_organization__PageOrg.67.smt2  |   0.654s  |   0.654s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-page_organization__PageOrg.68.smt2  |   0.443s  |   0.443s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-page_organization__PageOrg.7.smt2  |   0.657s  |   0.657s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-page_organization__PageOrg.71.smt2  |   0.347s  |   0.347s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-page_organization__PageOrg.78.smt2  |   0.424s  |   0.424s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-page_organization__PageOrg.79.smt2  |   2.331s  |   2.331s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-page_organization__PageOrg.8.smt2  |   0.221s  |   0.221s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-page_organization__PageOrg.83.smt2  |   0.454s  |   0.454s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-page_organization__PageOrg.88.smt2  |   0.479s  |   0.479s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-page_organization__PageOrg.94.smt2  |   0.912s  |   0.912s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-pagelib_page.page_init._01.smt2  |   0.536s  |   0.536s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-pagelib_page.page_init._02.smt2  |   0.234s  |   0.234s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-queues.3.smt2                   |   0.831s  |   0.831s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-queues__page_queue_push.smt2    |  20.065s  |  20.065s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-queues__page_queue_push_back.smt2  |  20.075s  |  20.075s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-root.smt2                       |   1.942s  |   1.942s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-segment.5.smt2                  |   0.367s  |   0.367s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-segment__segment_alloclib_segment.segment_alloc._02.smt2  |   0.313s  |   0.313s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-segment__segment_page_clear.smt2  |  20.093s  |  20.093s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-segment__segment_slice_split.smt2  |  20.022s  |  20.022s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-segment__segment_span_allocate.1.smt2  |   0.506s  |   0.506s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-segment__segment_span_free_coalesce_before.smt2  |  20.031s  |  20.031s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-segment__segments_page_find_and_allocate.3.smt2  |   0.260s  |   0.260s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-tokens__Mim.1.smt2              |   1.040s  |   1.040s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-tokens__Mim.11.smt2             |   0.365s  |   0.365s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-tokens__Mim.16.smt2             |   0.792s  |   0.792s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-tokens__Mim.19.smt2             |   0.343s  |   0.343s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-tokens__Mim.20.smt2             |   0.881s  |   0.881s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-tokens__Mim.26.smt2             |   1.259s  |   1.259s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-tokens__Mim.27.smt2             |   0.268s  |   0.268s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-tokens__Mim.3.smt2              |   0.272s  |   0.272s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-tokens__Mim.31.smt2             |   0.317s  |   0.317s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-tokens__Mim.32.smt2             |   0.512s  |   0.512s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-tokens__Mim.39.smt2             |   1.175s  |   1.175s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-tokens__Mim.40.smt2             |   0.352s  |   0.352s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-tokens__Mim.47.smt2             |   0.432s  |   0.432s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-tokens__Mim.5.smt2              |   0.263s  |   0.263s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-tokens__Mim.51.smt2             |   0.304s  |   0.304s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-tokens__Mim.52.smt2             |   0.331s  |   0.331s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-tokens__Mim.53.smt2             |   0.416s  |   0.416s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-tokens__Mim.54.smt2             |   0.367s  |   0.367s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-tokens__Mim.55.smt2             |   0.532s  |   0.532s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-tokens__Mim.56.smt2             |   0.369s  |   0.369s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-tokens__Mim.6.smt2              |   0.919s  |   0.919s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-types.11.smt2                   |   0.263s  |   0.263s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-types.15.smt2                   |   0.263s  |   0.263s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-types.18.smt2                   |   0.285s  |   0.285s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-types.19.smt2                   |   0.271s  |   0.271s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-types.2.smt2                    |   0.256s  |   0.256s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-types.23.smt2                   |   0.229s  |   0.229s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-types.24.smt2                   |   0.249s  |   0.249s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-types.3.smt2                    |   0.273s  |   0.273s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-types.30.smt2                   |   0.553s  |   0.553s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-types.35.smt2                   |   0.270s  |   0.270s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-types.36.smt2                   |   0.326s  |   0.326s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-types.37.smt2                   |   0.744s  |   0.744s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-types.4.smt2                    |   0.169s  |   0.169s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-types.42.smt2                   |   0.256s  |   0.256s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-types.44.smt2                   |   0.338s  |   0.338s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-types.45.smt2                   |   1.296s  |   1.296s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-types.51.smt2                   |   0.243s  |   0.243s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-constants.3.smt2                 |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-constants.6.smt2                 |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-constants.8.smt2                 |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-exec.1.smt2                      |   0.284s  |   0.284s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-exec.3.smt2                      |   0.282s  |   0.282s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-exec.4.smt2                      |   0.224s  |   0.224s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-exec__log.1.smt2                 |   0.251s  |   0.251s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-exec__log.10.smt2                |   0.712s  |   0.712s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-exec__log.14.smt2                |   0.292s  |   0.292s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-exec__log.16.smt2                |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-exec__log.20.smt2                |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-exec__log.3.smt2                 |   0.303s  |   0.303s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-exec__log.7.smt2                 |   0.197s  |   0.197s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-exec__log.8.smt2                 |   0.250s  |   0.250s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-exec__replica.1.smt2             |   0.223s  |   0.223s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-exec__replica.11.smt2            |   0.795s  |   0.795s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-exec__replica.12.smt2            |   0.271s  |   0.271s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-exec__replica.13.smt2            |   0.500s  |   0.500s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-exec__replica.19.smt2            |   0.196s  |   0.196s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-exec__replica.4.smt2             |   0.277s  |   0.277s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-exec__replica.6.smt2             |   0.297s  |   0.297s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-root.5.smt2                      |   0.259s  |   0.259s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-spec__cyclicbuffer.4.smt2        |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-spec__cyclicbuffer.5.smt2        |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-spec__cyclicbuffer__CyclicBuffer.1.smt2  |   0.653s  |   0.653s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-spec__cyclicbuffer__CyclicBuffer.10.smt2  |   0.688s  |   0.688s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-spec__cyclicbuffer__CyclicBuffer.11.smt2  |   0.186s  |   0.186s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-spec__cyclicbuffer__CyclicBuffer.16.smt2  |   0.174s  |   0.174s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-spec__cyclicbuffer__CyclicBuffer.17.smt2  |   0.780s  |   0.780s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-spec__cyclicbuffer__CyclicBuffer.22.smt2  |   0.228s  |   0.228s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-spec__cyclicbuffer__CyclicBuffer.23.smt2  |   0.422s  |   0.422s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-spec__cyclicbuffer__CyclicBuffer.28.smt2  |   0.250s  |   0.250s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-spec__cyclicbuffer__CyclicBuffer.3.smt2  |   0.258s  |   0.258s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-spec__cyclicbuffer__CyclicBuffer.30.smt2  |   0.192s  |   0.192s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-spec__cyclicbuffer__CyclicBuffer.32.smt2  |   0.204s  |   0.204s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-spec__cyclicbuffer__CyclicBuffer.5.smt2  |   0.203s  |   0.203s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-spec__cyclicbuffer__CyclicBuffer.6.smt2  |   0.558s  |   0.558s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-spec__cyclicbufferlib_spec.cyclicbuffer.log_entry_alive_value_wrap_around._01.smt2  |   0.262s  |   0.262s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-definitions_t.11.smt2         |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-definitions_t.13.smt2         |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-definitions_t.15.smt2         |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-definitions_t.18.smt2         |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-definitions_t.20.smt2         |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-definitions_t.22.smt2         |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-definitions_t.24.smt2         |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-definitions_t.25.smt2         |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-definitions_u.1.smt2          |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-definitions_u.11.smt2         |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-definitions_ulib_definitions_u.impl_%2.entry_base._01.smt2  |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-definitions_ulib_definitions_u.impl_%2.index_for_vaddr._01.smt2  |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-definitions_ulib_definitions_u.impl_%2.next_entry_base._01.smt2  |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-definitions_ulib_definitions_u.impl_%2.next_entry_base._02.smt2  |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-definitions_ulib_definitions_u.impl_%3.lemma_entry_sizes_aligned._02.smt2  |  20.062s  |  20.062s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-definitions_ulib_definitions_u.impl_%3.lemma_entry_sizes_increase._01.smt2  |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-definitions_ulib_definitions_u.overflow_bounds._02.smt2  |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-definitions_ulib_definitions_u.x86_arch_inv._01.smt2  |   0.404s  |   0.404s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-extra.1.smt2                  |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-extra.3.smt2                  |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-extra.7.smt2                  |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-extra.8.smt2                  |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-extralib_extra.aligned_transitive._02.smt2  |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-extralib_extra.lemma_aligned_iff_eq_mul_div._01.smt2  |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-extralib_extra.lemma_aligned_iff_eq_mul_div._02.smt2  |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-extralib_extra.mod_less_eq._01.smt2  |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-extralib_extra.mod_mult_zero_implies_mod_zero._01.smt2  |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-extralib_extra.mul_commute._01.smt2  |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-extralib_extra.mult_leq_mono2._01.smt2  |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-extralib_extra.mult_leq_mono_both._01.smt2  |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-extralib_extra.mult_less_mono_both2._01.smt2  |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__indexinglib_impl_u.indexing.lemma_entry_base_from_index._01.smt2  |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__indexinglib_impl_u.indexing.lemma_entry_base_from_index._05.smt2  |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__indexinglib_impl_u.indexing.lemma_entry_base_from_index_support._02.smt2  |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__indexinglib_impl_u.indexing.lemma_index_from_base_and_addr._01.smt2  |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l0.14.smt2            |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l0.15.smt2            |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l0.19.smt2            |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l0.23.smt2            |   0.166s  |   0.166s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l0.24.smt2            |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l0.5.smt2             |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l0.6.smt2             |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l1.10.smt2            |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l1.12.smt2            |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l1.13.smt2            |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l1.20.smt2            |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l1.22.smt2            |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l1.27.smt2            |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l1.3.smt2             |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l1.33.smt2            |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l1.34.smt2            |   1.178s  |   1.178s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l1.35.smt2            |   0.326s  |   0.326s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l1.41.smt2            |   0.418s  |   0.418s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l1.42.smt2            |   0.289s  |   0.289s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l1.45.smt2            |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l1.47.smt2            |  16.591s  |  16.591s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l1.53.smt2            |   0.516s  |   0.516s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l1.7.smt2             |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l1__impl_%1__lemma_interp_of_entry_contains_mapping_implies_interp_aux_contains_mapping.smt2  |   2.315s  |   2.315s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l1__impl_%1__lemma_no_mapping_in_interp_of_entry_implies_no_mapping_in_interp.smt2  |  14.883s  |  14.883s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l1__impl_%1__lemma_resolve_refines.smt2  |   1.476s  |   1.476s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l1lib_impl_u.l1.impl_%1.lemma_interp_of_entries_disjoint._04.smt2  |   0.263s  |   0.263s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l1lib_impl_u.l1.impl_%1.lemma_ranges_disjoint_interp_aux_interp_of_entry._01.smt2  |   0.169s  |   0.169s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l2_impl.1.smt2        |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l2_impl.10.smt2       |   1.413s  |   1.413s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l2_impl.14.smt2       |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l2_impl.5.smt2        |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l2_impl__PT.1.smt2    |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l2_impl__PT.10.smt2   |   0.338s  |   0.338s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l2_impl__PT.15.smt2   |   0.751s  |   0.751s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l2_impl__PT.18.smt2   |  20.062s  |  20.062s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l2_impl__PT.28.smt2   |  20.023s  |  20.023s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l2_impl__PT.5.smt2    |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l2_impl__PT.8.smt2    |   0.222s  |   0.222s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l2_refinement.1.smt2  |   0.296s  |   0.296s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l2_refinement.3.smt2  |  20.104s  |  20.104s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l2_refinement.4.smt2  |  20.047s  |  20.047s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l2_refinement.5.smt2  |   0.747s  |   0.747s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__os_refinement.1.smt2  |   0.385s  |   0.385s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__os_refinement.10.smt2  |  19.403s  |  19.403s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-spec_t__hardware.1.smt2       |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-spec_t__hardware.17.smt2      |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-spec_t__hardware.19.smt2      |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-spec_t__hardware.2.smt2       |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-spec_t__hardware.21.smt2      |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-spec_t__hardware.4.smt2       |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-spec_t__hardware.6.smt2       |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-spec_t__hardware.7.smt2       |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-logimpl_v.10.smt2  |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-logimpl_v.15.smt2  |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-logimpl_v.17.smt2  |   0.195s  |   0.195s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-logimpl_v.18.smt2  |   0.487s  |   0.487s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-logimpl_v.24.smt2  |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-logimpl_v.32.smt2  |   0.364s  |   0.364s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-logimpl_v.33.smt2  |   0.378s  |   0.378s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-logimpl_v.34.smt2  |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-logimpl_v.37.smt2  |  11.092s  |  11.092s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-logimpl_v.38.smt2  |   0.200s  |   0.200s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-logimpl_v.42.smt2  |   0.212s  |   0.212s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-logimpl_v.50.smt2  |   9.423s  |   9.423s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-logimpl_v.51.smt2  |   0.195s  |   0.195s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-main_t.4.smt2  |   0.169s  |   0.169s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-main_t.7.smt2  |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-math.10.smt2  |   0.230s  |   0.230s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-math.15.smt2  |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-math.16.smt2  |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-math.18.smt2  |   0.413s  |   0.413s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-math.2.smt2  |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-math.20.smt2  |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-math.28.smt2  |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-math.5.smt2  |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-math.7.smt2  |   0.306s  |   0.306s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-mathmain_math.lemma_fundamental_div_mod_converse_helper_1._01.smt2  |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-mathmain_math.lemma_fundamental_div_mod_converse_helper_2._01.smt2  |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-mathmain_math.lemma_mul_div_equal._01.smt2  |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-mathmain_math.lemma_mul_is_associative._01.smt2  |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-mathmain_math.lemma_mul_is_distributive._01.smt2  |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-mathmain_math.lemma_mul_is_distributive_add._01.smt2  |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-mathmain_math.lemma_mul_is_distributive_sub_other_way._01.smt2  |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-mathmain_math.lemma_mul_left_inequality._01.smt2  |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-mathmain_math.lemma_mul_one_to_one._01.smt2  |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-mathmain_math.lemma_small_mod._01.smt2  |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-root.smt2  |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-log__inv_v.1.smt2  |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-log__inv_v.12.smt2  |   1.996s  |   1.996s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-log__inv_v.15.smt2  |   6.573s  |   6.573s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-log__inv_v.16.smt2  |   0.317s  |   0.317s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-log__inv_v.17.smt2  |   1.259s  |   1.259s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-log__inv_v.7.smt2  |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-log__layout_v.26.smt2  |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-log__layout_v.27.smt2  |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-log__layout_v.30.smt2  |   0.840s  |   0.840s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-log__logimpl_v.10.smt2  |   0.781s  |   0.781s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-log__logimpl_v.12.smt2  |   0.224s  |   0.224s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-log__logimpl_v.3.smt2  |   0.791s  |   0.791s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-log__logimpl_v.4.smt2  |   4.372s  |   4.372s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-log__logimpl_v.7.smt2  |   0.562s  |   0.562s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-log__logimpl_v.9.smt2  |   2.963s  |   2.963s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-log__start_v.2.smt2  |   2.078s  |   2.078s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-multilog__append_v.2.smt2  |  20.080s  |  20.080s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-multilog__inv_v.10.smt2  |   0.338s  |   0.338s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-multilog__inv_v.15.smt2  |   2.463s  |   2.463s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-multilog__inv_v.18.smt2  |   2.436s  |   2.436s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-multilog__inv_v.2.smt2  |   0.968s  |   0.968s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-multilog__inv_v.3.smt2  |   1.103s  |   1.103s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-multilog__inv_v.9.smt2  |   0.942s  |   0.942s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-multilog__layout_v.30.smt2  |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-multilog__layout_v.31.smt2  |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-multilog__layout_v.32.smt2  |   0.239s  |   0.239s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-multilog__multilogimpl_v.1.smt2  |   0.236s  |   0.236s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-multilog__multilogimpl_v.12.smt2  |   0.401s  |   0.401s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-multilog__multilogimpl_v.5.smt2  |  20.050s  |  20.050s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-multilog__multilogimpl_v.9.smt2  |   0.734s  |   0.734s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-multilog__setup_v.6.smt2  |  20.158s  |  20.158s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-pmem__pmcopy_t.3.smt2  |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/addr_e__addr_interface.10.smt2               |   0.240s  |   0.240s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/addr_e__addr_interface.11.smt2               |   0.198s  |   0.198s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/addr_e__addr_interface.13.smt2               |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/addr_e__addr_interface.16.smt2               |   0.375s  |   0.375s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/addr_e__addr_interface.2.smt2                |   0.386s  |   0.386s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/addr_e__addr_interface.3.smt2                |   0.328s  |   0.328s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/addr_e__exe.1.smt2                           |   0.424s  |   0.424s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/addr_e__range_interface.10.smt2              |   0.330s  |   0.330s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/addr_e__range_interface.13.smt2              |   0.383s  |   0.383s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/addr_e__range_interface.14.smt2              |   0.815s  |   0.815s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/addr_e__range_interface.15.smt2              |   0.458s  |   0.458s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/addr_e__range_interface.17.smt2              |   1.336s  |   1.336s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/addr_e__range_interface.5.smt2               |   0.343s  |   0.343s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/addr_e__range_interface.7.smt2               |   0.222s  |   0.222s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/allocator__bit_p.smt2                        |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/allocator__buddy.11.smt2                     |  17.766s  |  17.766s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/allocator__buddy.13.smt2                     |  20.031s  |  20.031s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/allocator__buddy.15.smt2                     |  16.826s  |  16.826s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/allocator__buddy.2.smt2                      |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/allocator__buddy.3.smt2                      |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/allocator__buddy.4.smt2                      |   2.679s  |   2.679s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/allocator__buddy.6.smt2                      |   0.596s  |   0.596s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/allocator__buddy.7.smt2                      |   4.831s  |   4.831s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/allocator__buddy.9.smt2                      |   8.620s  |   8.620s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/allocator__linkedlist.10.smt2                |   8.320s  |   8.320s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/allocator__linkedlist.11.smt2                |   0.871s  |   0.871s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/allocator__linkedlist.13.smt2                |   1.182s  |   1.182s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/allocator__linkedlist.3.smt2                 |   0.655s  |   0.655s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/allocator__linkedlist.6.smt2                 |   6.702s  |   6.702s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/allocator__locked.1.smt2                     |   5.236s  |   5.236s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/arch__addr_s__def_s.3.smt2                   |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/arch__addr_s__def_s.8.smt2                   |   0.248s  |   0.248s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/arch__addr_s__page.1.smt2                    |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/arch__addr_s__page.6.smt2                    |   0.357s  |   0.357s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/arch__mem__mem_p.11.smt2                     |   1.106s  |   1.106s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/arch__mem__mem_p.13.smt2                     |   2.098s  |   2.098s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/arch__mem__mem_p.16.smt2                     |   1.089s  |   1.089s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/arch__mem__mem_p.4.smt2                      |   3.898s  |   3.898s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/arch__pgtable__entry_p.3.smt2                |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/arch__pgtable__entry_p.4.smt2                |   0.502s  |   0.502s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/arch__pgtable__entry_p.7.smt2                |   0.207s  |   0.207s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/arch__pgtable__memmap_p.3.smt2               |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/arch__pgtable__memmap_p.5.smt2               |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/arch__ptram__ptram_p.10.smt2                 |   0.455s  |   0.455s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/arch__ptram__ptram_p.6.smt2                  |   0.707s  |   0.707s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/arch__ptram__ptram_s.smt2                    |   0.195s  |   0.195s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/arch__ptram__ptram_u.smt2                    |   0.207s  |   0.207s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/arch__vram__vram_p.1.smt2                    |   0.867s  |   0.867s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/arch__vram__vram_p.12.smt2                   |   0.347s  |   0.347s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/arch__vram__vram_p.15.smt2                   |   1.011s  |   1.011s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/arch__vram__vram_p.18.smt2                   |   0.658s  |   0.658s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/arch__vram__vram_p.2.smt2                    |   1.196s  |   1.196s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/arch__vram__vram_p.21.smt2                   |   0.697s  |   0.697s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/arch__vram__vram_p.22.smt2                   |   0.659s  |   0.659s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/arch__vram__vram_p.26.smt2                   |   0.471s  |   0.471s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/arch__vram__vram_p.28.smt2                   |   1.131s  |   1.131s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/arch__vram__vram_p.7.smt2                    |   1.003s  |   1.003s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/arch__vram__vram_p.9.smt2                    |  14.235s  |  14.235s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/arch__x64__x64_p.2.smt2                      |   3.234s  |   3.234s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__idt__def.3.smt2                        |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__idt__def.4.smt2                        |  20.130s  |  20.130s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__idt__dummy.2.smt2                      |   0.316s  |   0.316s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__idt__dummy.3.smt2                      |   0.818s  |   0.818s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__idt__dummy.5.smt2                      |   0.764s  |   0.764s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__init__init_e.2.smt2                    |   1.130s  |   1.130s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__init__init_s.smt2                      |   4.516s  |   4.516s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__init__mshv_alloc.3.smt2                |   1.194s  |   1.194s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__init__mshv_fmt.1.smt2                  |   0.667s  |   0.667s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__linux.1.smt2                           |   0.820s  |   0.820s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__linux.11.smt2                          |   0.908s  |   0.908s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__linux.13.smt2                          |   2.361s  |   2.361s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__linux.17.smt2                          |   4.413s  |   4.413s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__linux.20.smt2                          |   0.939s  |   0.939s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__linux.22.smt2                          |   0.945s  |   0.945s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__linux.30.smt2                          |   1.045s  |   1.045s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__linux.34.smt2                          |   0.833s  |   0.833s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__linux.35.smt2                          |   0.994s  |   0.994s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__linux.36.smt2                          |   0.708s  |   0.708s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__linux.37.smt2                          |   1.020s  |   1.020s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__linux.40.smt2                          |   0.878s  |   0.878s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__linux.43.smt2                          |   1.128s  |   1.128s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__linux.44.smt2                          |   1.091s  |   1.091s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__linux.8.smt2                           |   0.899s  |   0.899s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__monitor_params.smt2                    |   1.051s  |   1.051s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__mshyper__param_e.1.smt2                |   0.531s  |   0.531s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__mshyper__param_e.5.smt2                |   0.435s  |   0.435s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__params.12.smt2                         |   0.556s  |   0.556s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__params.14.smt2                         |   0.871s  |   0.871s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__params.16.smt2                         |   1.133s  |   1.133s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__params.23.smt2                         |   0.449s  |   0.449s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__params.5.smt2                          |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__params.8.smt2                          |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/debug__ghcb_print.10.smt2                    |   0.625s  |   0.625s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/debug__ghcb_print.12.smt2                    |   3.482s  |   3.482s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/debug__ghcb_print.2.smt2                     |   0.674s  |   0.674s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/debug__ghcb_print.23.smt2                    |   1.027s  |   1.027s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/debug__ghcb_print.25.smt2                    |   1.003s  |   1.003s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/debug__ghcb_print.26.smt2                    |   1.029s  |   1.029s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/debug__ghcb_print.28.smt2                    |   0.539s  |   0.539s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/debug__ghcb_print.5.smt2                     |   3.950s  |   3.950s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/debug__ghcb_print.6.smt2                     |   0.523s  |   0.523s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/debug__ghcb_print.7.smt2                     |   0.757s  |   0.757s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/debug__ghcb_print.8.smt2                     |  11.112s  |  11.112s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/debug__slice_print.3.smt2                    |   0.701s  |   0.701s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/linkedlist.11.smt2                           |   0.421s  |   0.421s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/linkedlist.12.smt2                           |  14.201s  |  14.201s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/linkedlist.13.smt2                           |  12.470s  |  12.470s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/linkedlist.14.smt2                           |   0.963s  |   0.963s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/linkedlist.16.smt2                           |   0.645s  |   0.645s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/linkedlist.4.smt2                            |  20.077s  |  20.077s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/linkedlist.6.smt2                            |  19.371s  |  19.371s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/linkedlist.7.smt2                            |   4.003s  |   4.003s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/linkedlist.9.smt2                            |   8.440s  |   8.440s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/lock__spin_perm_s.3.smt2                     |   4.608s  |   4.608s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/lock__spincell_e.1.smt2                      |   0.354s  |   0.354s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/lock__spincell_e.5.smt2                      |   2.236s  |   2.236s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/lock__spincell_e.6.smt2                      |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/mshyper.1.smt2                               |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/mshyper.11.smt2                              |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/mshyper.14.smt2                              |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/mshyper.15.smt2                              |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/mshyper.17.smt2                              |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/mshyper.19.smt2                              |  15.091s  |  15.091s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/mshyper.5.smt2                               |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/mshyper.6.smt2                               |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/mshyper.7.smt2                               |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/mshyper__hypercall.2.smt2                    |   0.898s  |   0.898s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/mshyper__wakeup.1.smt2                       |   0.919s  |   0.919s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/mshyper__wakeup.5.smt2                       |   2.070s  |   2.070s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/mshyper__wakeup.7.smt2                       |  14.561s  |  14.561s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/pgtable_e__def.16.smt2                       |   2.113s  |   2.113s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/pgtable_e__def.20.smt2                       |   0.251s  |   0.251s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/pgtable_e__def.26.smt2                       |   0.269s  |   0.269s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/pgtable_e__def.31.smt2                       |   2.343s  |   2.343s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/pgtable_e__def.32.smt2                       |   0.385s  |   0.385s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/pgtable_e__def.34.smt2                       |   0.383s  |   0.383s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/pgtable_e__def.36.smt2                       |   1.699s  |   1.699s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/pgtable_e__def.39.smt2                       |   1.835s  |   1.835s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/pgtable_e__def.42.smt2                       |   0.262s  |   0.262s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/pgtable_e__def.44.smt2                       |   0.361s  |   0.361s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/pgtable_e__def.7.smt2                        |   0.312s  |   0.312s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/pgtable_e__pte.11.smt2                       |   0.929s  |   0.929s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/pgtable_e__pte.16.smt2                       |   1.012s  |   1.012s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/pgtable_e__pte.2.smt2                        |   0.479s  |   0.479s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/pgtable_e__pte.22.smt2                       |  10.471s  |  10.471s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/pgtable_e__pte.23.smt2                       |   7.777s  |   7.777s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/pgtable_e__pte.25.smt2                       |   1.899s  |   1.899s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/pgtable_e__pte.26.smt2                       |   0.506s  |   0.506s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/pgtable_e__pte.29.smt2                       |   0.738s  |   0.738s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/pgtable_e__pte.3.smt2                        |   0.508s  |   0.508s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/pgtable_e__pte.7.smt2                        |   0.911s  |   0.911s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/pgtable_e__pte.8.smt2                        |   0.812s  |   0.812s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/pgtable_e__pte.9.smt2                        |   0.593s  |   0.593s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/primitives_e__seq.2.smt2                     |   0.262s  |   0.262s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/primitives_e__vec.1.smt2                     |   0.247s  |   0.247s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/primitives_e__vec.2.smt2                     |   0.243s  |   0.243s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/ptr__def_s.smt2                              |   2.425s  |   2.425s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/ptr__ptr_e.9.smt2                            |   1.264s  |   1.264s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/ptr__raw_ptr_s.1.smt2                        |   0.813s  |   0.813s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/ptr__raw_ptr_s.3.smt2                        |   1.359s  |   1.359s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/ptr__snp__rmp__rmp_e.3.smt2                  |  13.307s  |  13.307s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/ptr__snp__rmp__rmp_e.5.smt2                  |   5.686s  |   5.686s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/ptr__snp__rmp__rmp_e.7.smt2                  |   4.825s  |   4.825s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/ptr__snp__rmp__rmp_t.2.smt2                  |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/ptr__snp__rmp__rmp_t.5.smt2                  |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/ptr__snp__rmp__rmp_t.6.smt2                  |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/ptr__snp__rmp__rmp_t.7.smt2                  |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/ptr__snp__rmp__rmp_t.8.smt2                  |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/ptr__snp__snp_s.smt2                         |   0.699s  |   0.699s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/ptr__snp__snp_u.13.smt2                      |   0.330s  |   0.330s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/ptr__snp__snp_u.15.smt2                      |   0.305s  |   0.305s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/ptr__snp__snp_u.16.smt2                      |   0.436s  |   0.436s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/ptr__snp__snp_u.2.smt2                       |   0.271s  |   0.271s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/ptr__snp__snp_u.8.smt2                       |   0.333s  |   0.333s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/registers__msr_t.11.smt2                     |   0.175s  |   0.175s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/registers__msr_t.2.smt2                      |   0.224s  |   0.224s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/registers__msr_t.3.smt2                      |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/registers__msr_t.7.smt2                      |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/security.10.smt2                             |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/security.11.smt2                             |   0.434s  |   0.434s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/security.12.smt2                             |   0.583s  |   0.583s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/security.18.smt2                             |   0.584s  |   0.584s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/security.19.smt2                             |   0.498s  |   0.498s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/security.2.smt2                              |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/security.21.smt2                             |   0.500s  |   0.500s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/security.3.smt2                              |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/security.6.smt2                              |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/security.9.smt2                              |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/security__mem.10.smt2                        |   1.251s  |   1.251s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/security__mem.20.smt2                        |   1.163s  |   1.163s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/security__mem.25.smt2                        |   0.872s  |   0.872s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/security__mem.27.smt2                        |   1.568s  |   1.568s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/security__mem.28.smt2                        |   0.982s  |   0.982s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/security__mem.37.smt2                        |   6.415s  |   6.415s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/security__mem.38.smt2                        |   6.446s  |   6.446s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/security__mem.42.smt2                        |   1.227s  |   1.227s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/security__mem.45.smt2                        |   1.576s  |   1.576s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/security__mem.49.smt2                        |   0.788s  |   0.788s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/security__mem.50.smt2                        |   1.192s  |   1.192s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/security__monitor.1.smt2                     |   0.193s  |   0.193s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/security__monitor.10.smt2                    |  20.039s  |  20.039s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/security__monitor.12.smt2                    |  20.103s  |  20.103s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/security__monitor.14.smt2                    |  20.046s  |  20.046s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/security__monitor.15.smt2                    |  20.116s  |  20.116s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/security__monitor.16.smt2                    |  20.037s  |  20.037s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/security__monitor.17.smt2                    |   1.905s  |   1.905s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/security__monitor.24.smt2                    |  20.068s  |  20.068s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/security__monitor.25.smt2                    |   1.280s  |   1.280s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/security__monitor.5.smt2                     |   0.986s  |   0.986s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/security__monitor.6.smt2                     |   1.226s  |   1.226s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/security__monitor.9.smt2                     |   1.386s  |   1.386s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/security__pcr.2.smt2                         |   0.962s  |   0.962s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/security__pcr.5.smt2                         |  16.338s  |  16.338s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/security__pcr.8.smt2                         |   0.550s  |   0.550s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/security__secret.1.smt2                      |   0.742s  |   0.742s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/security__secret.13.smt2                     |  20.079s  |  20.079s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/security__secret.17.smt2                     |   0.729s  |   0.729s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/security__secret.18.smt2                     |   1.470s  |   1.470s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/security__secret.22.smt2                     |   1.350s  |   1.350s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/security__secret.24.smt2                     |   1.226s  |   1.226s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/security__secret.6.smt2                      |   1.270s  |   1.270s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/security__secret.9.smt2                      |   0.965s  |   0.965s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__gdt.13.smt2                        |   0.225s  |   0.225s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__gdt.17.smt2                        |   0.209s  |   0.209s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__gdt.19.smt2                        |   2.536s  |   2.536s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__gdt.2.smt2                         |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__gdt.20.smt2                        |   0.242s  |   0.242s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__gdt.21.smt2                        |   0.315s  |   0.315s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__gdt.26.smt2                        |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__gdt.27.smt2                        |   0.659s  |   0.659s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__gdt.34.smt2                        |   0.343s  |   0.343s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__gdt.38.smt2                        |   0.316s  |   0.316s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__gdt.39.smt2                        |   0.389s  |   0.389s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__gdt.4.smt2                         |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__gdt.40.smt2                        |   1.725s  |   1.725s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__gdt.41.smt2                        |   0.298s  |   0.298s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__gdt.42.smt2                        |   1.479s  |   1.479s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__gdt.45.smt2                        |   0.260s  |   0.260s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__gdt.48.smt2                        |   1.036s  |   1.036s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__gdt.49.smt2                        |   0.321s  |   0.321s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__gdt.5.smt2                         |   0.841s  |   0.841s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__gdt.53.smt2                        |   0.308s  |   0.308s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__gdt.57.smt2                        |   0.328s  |   0.328s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__gdt.6.smt2                         |   0.244s  |   0.244s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__gdt.60.smt2                        |   0.196s  |   0.196s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__gdt.61.smt2                        |   0.195s  |   0.195s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__gdt.63.smt2                        |   0.657s  |   0.657s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__gdt.66.smt2                        |   0.229s  |   0.229s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__vmsa.1.smt2                        |  10.343s  |  10.343s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__vmsa.10.smt2                       |   1.160s  |   1.160s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__vmsa.11.smt2                       |   0.916s  |   0.916s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__vmsa.12.smt2                       |   0.962s  |   0.962s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__vmsa.13.smt2                       |   1.017s  |   1.017s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__vmsa.14.smt2                       |   1.053s  |   1.053s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__vmsa.18.smt2                       |   1.951s  |   1.951s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__vmsa.2.smt2                        |  20.071s  |  20.071s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__vmsa.28.smt2                       |   0.561s  |   0.561s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__vmsa.31.smt2                       |   0.813s  |   0.813s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__vmsa.32.smt2                       |   2.133s  |   2.133s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__vmsa.37.smt2                       |   1.150s  |   1.150s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__vmsa.38.smt2                       |   1.549s  |   1.549s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__vmsa.4.smt2                        |   1.146s  |   1.146s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__vmsa.44.smt2                       |   2.258s  |   2.258s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__vmsa.49.smt2                       |   1.843s  |   1.843s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__vmsa.5.smt2                        |   1.005s  |   1.005s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__vmsa.50.smt2                       |   1.813s  |   1.813s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__vmsa.58.smt2                       |   0.919s  |   0.919s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__vmsa.64.smt2                       |   0.887s  |   0.887s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__vmsa.7.smt2                        |   0.825s  |   0.825s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpuid.11.smt2                           |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpuid.13.smt2                           |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpuid.14.smt2                           |   0.667s  |   0.667s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpuid.16.smt2                           |   0.508s  |   0.508s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpuid.2.smt2                            |   0.222s  |   0.222s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpuid.5.smt2                            |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__def_s.2.smt2                      |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_e.12.smt2                   |   0.544s  |   0.544s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_e.13.smt2                   |   0.339s  |   0.339s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_e.15.smt2                   |   0.549s  |   0.549s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_e.18.smt2                   |   5.123s  |   5.123s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_e.19.smt2                   |   1.528s  |   1.528s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_e.2.smt2                    |   0.558s  |   0.558s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_e.20.smt2                   |   0.619s  |   0.619s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_impl.10.smt2                |   1.727s  |   1.727s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_impl.11.smt2                |   0.994s  |   0.994s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_impl.13.smt2                |   1.211s  |   1.211s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_impl.15.smt2                |   5.884s  |   5.884s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_impl.17.smt2                |   0.686s  |   0.686s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_impl.20.smt2                |   1.724s  |   1.724s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_impl.21.smt2                |   1.413s  |   1.413s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_impl.22.smt2                |   1.727s  |   1.727s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_impl.25.smt2                |   1.107s  |   1.107s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_impl.26.smt2                |   1.928s  |   1.928s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_impl.27.smt2                |   1.045s  |   1.045s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_impl.28.smt2                |   1.282s  |   1.282s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_impl.4.smt2                 |   1.197s  |   1.197s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_impl.6.smt2                 |   1.163s  |   1.163s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_impl.7.smt2                 |   1.177s  |   1.177s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_impl__internal.2.smt2       |   5.497s  |   5.497s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.10.smt2                |   0.974s  |   0.974s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.102.smt2               |   1.255s  |   1.255s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.103.smt2               |   1.189s  |   1.189s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.104.smt2               |   1.417s  |   1.417s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.107.smt2               |   1.029s  |   1.029s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.110.smt2               |   1.343s  |   1.343s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.112.smt2               |   1.404s  |   1.404s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.117.smt2               |   0.971s  |   0.971s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.121.smt2               |   0.660s  |   0.660s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.126.smt2               |   1.262s  |   1.262s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.127.smt2               |   1.270s  |   1.270s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.134.smt2               |   2.957s  |   2.957s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.138.smt2               |   1.004s  |   1.004s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.14.smt2                |   0.866s  |   0.866s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.140.smt2               |   8.643s  |   8.643s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.16.smt2                |   1.222s  |   1.222s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.18.smt2                |   1.003s  |   1.003s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.19.smt2                |   1.154s  |   1.154s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.2.smt2                 |   0.952s  |   0.952s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.26.smt2                |   1.170s  |   1.170s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.27.smt2                |   0.743s  |   0.743s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.30.smt2                |   0.892s  |   0.892s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.31.smt2                |   1.298s  |   1.298s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.32.smt2                |   2.035s  |   2.035s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.34.smt2                |   0.879s  |   0.879s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.38.smt2                |   1.123s  |   1.123s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.4.smt2                 |   1.254s  |   1.254s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.41.smt2                |   1.685s  |   1.685s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.44.smt2                |   0.708s  |   0.708s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.48.smt2                |   1.649s  |   1.649s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.63.smt2                |   1.364s  |   1.364s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.66.smt2                |   1.878s  |   1.878s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.67.smt2                |   1.336s  |   1.336s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.68.smt2                |   1.300s  |   1.300s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.69.smt2                |   1.149s  |   1.149s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.70.smt2                |   0.993s  |   0.993s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.71.smt2                |   1.020s  |   1.020s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.73.smt2                |   1.191s  |   1.191s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.8.smt2                 |   1.311s  |   1.311s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.81.smt2                |   1.282s  |   1.282s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.83.smt2                |   1.270s  |   1.270s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.85.smt2                |   1.517s  |   1.517s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.88.smt2                |   1.216s  |   1.216s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.89.smt2                |   1.078s  |   1.078s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.91.smt2                |   1.297s  |   1.297s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.93.smt2                |   0.889s  |   0.889s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.94.smt2                |   1.388s  |   1.388s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.96.smt2                |   1.508s  |   1.508s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.98.smt2                |   1.744s  |   1.744s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_s.10.smt2                   |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_s.13.smt2                   |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_s.18.smt2                   |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_s.2.smt2                    |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_s.22.smt2                   |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_s.23.smt2                   |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_s.24.smt2                   |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_s.25.smt2                   |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_s.26.smt2                   |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_s.27.smt2                   |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_s.3.smt2                    |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_s.31.smt2                   |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_s.41.smt2                   |   0.289s  |   0.289s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_s.43.smt2                   |   0.203s  |   0.203s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_s.5.smt2                    |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_s.9.smt2                    |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__trackedcore__snpmulticore.1.smt2        |   1.001s  |   1.001s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/trusted_hacl__stub.7.smt2                    |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__cast.2.smt2                           |   0.191s  |   0.191s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__cast.4.smt2                           |   0.244s  |   0.244s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__cast.5.smt2                           |   0.261s  |   0.261s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__cast.6.smt2                           |   0.261s  |   0.261s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__cast.7.smt2                           |   0.286s  |   0.286s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__math__align_s.5.smt2                  |   1.566s  |   1.566s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.proof_align_down._01.smt2  |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__math__bits_p.4.smt2                   |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__math__bits_p.7.smt2                   |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__math__bits_p.8.smt2                   |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__math__bits_p.9.smt2                   |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__math__integer.2.smt2                  |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__math__integer.8.smt2                  |   0.279s  |   0.279s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__math__pow_p.1.smt2                    |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.102.smt2            |   0.317s  |   0.317s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.106.smt2            |   0.331s  |   0.331s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.108.smt2            |   0.263s  |   0.263s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.109.smt2            |   0.254s  |   0.254s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.115.smt2            |   0.274s  |   0.274s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.119.smt2            |   0.409s  |   0.409s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.121.smt2            |   0.460s  |   0.460s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.122.smt2            |   0.369s  |   0.369s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.124.smt2            |   0.396s  |   0.396s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.130.smt2            |   0.249s  |   0.249s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.138.smt2            |   0.950s  |   0.950s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.140.smt2            |   0.377s  |   0.377s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.144.smt2            |   0.574s  |   0.574s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.148.smt2            |   0.662s  |   0.662s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.149.smt2            |   0.521s  |   0.521s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.151.smt2            |   0.328s  |   0.328s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.152.smt2            |   0.394s  |   0.394s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.155.smt2            |   0.348s  |   0.348s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.162.smt2            |   0.420s  |   0.420s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.165.smt2            |   0.304s  |   0.304s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.168.smt2            |   0.522s  |   0.522s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.17.smt2             |   0.444s  |   0.444s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.172.smt2            |   0.350s  |   0.350s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.175.smt2            |   0.472s  |   0.472s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.176.smt2            |   0.433s  |   0.433s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.178.smt2            |   0.418s  |   0.418s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.183.smt2            |   0.593s  |   0.593s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.184.smt2            |   0.420s  |   0.420s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.186.smt2            |   0.426s  |   0.426s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.193.smt2            |   0.330s  |   0.330s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.196.smt2            |   0.340s  |   0.340s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.198.smt2            |   0.353s  |   0.353s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.199.smt2            |   0.357s  |   0.357s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.20.smt2             |   0.537s  |   0.537s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.201.smt2            |   0.398s  |   0.398s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.202.smt2            |   0.599s  |   0.599s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.206.smt2            |   0.471s  |   0.471s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.208.smt2            |   0.579s  |   0.579s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.209.smt2            |   0.421s  |   0.421s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.213.smt2            |   0.349s  |   0.349s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.216.smt2            |   0.350s  |   0.350s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.220.smt2            |   0.345s  |   0.345s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.221.smt2            |   0.505s  |   0.505s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.222.smt2            |   0.641s  |   0.641s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.225.smt2            |   0.532s  |   0.532s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.226.smt2            |   0.505s  |   0.505s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.231.smt2            |   0.417s  |   0.417s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.233.smt2            |   0.471s  |   0.471s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.235.smt2            |   0.415s  |   0.415s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.237.smt2            |   0.657s  |   0.657s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.239.smt2            |   0.471s  |   0.471s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.240.smt2            |   0.553s  |   0.553s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.256.smt2            |   0.436s  |   0.436s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.26.smt2             |   0.405s  |   0.405s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.261.smt2            |   0.355s  |   0.355s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.265.smt2            |   0.585s  |   0.585s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.27.smt2             |   0.294s  |   0.294s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.274.smt2            |   0.653s  |   0.653s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.281.smt2            |   0.381s  |   0.381s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.282.smt2            |   0.483s  |   0.483s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.283.smt2            |   0.576s  |   0.576s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.286.smt2            |   0.416s  |   0.416s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.297.smt2            |   0.311s  |   0.311s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.30.smt2             |   0.653s  |   0.653s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.306.smt2            |   0.547s  |   0.547s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.307.smt2            |   0.305s  |   0.305s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.308.smt2            |   0.443s  |   0.443s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.309.smt2            |   0.656s  |   0.656s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.32.smt2             |   0.191s  |   0.191s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.321.smt2            |   0.789s  |   0.789s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.324.smt2            |   0.416s  |   0.416s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.325.smt2            |   0.623s  |   0.623s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.328.smt2            |   0.603s  |   0.603s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.329.smt2            |   0.405s  |   0.405s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.336.smt2            |   0.546s  |   0.546s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.338.smt2            |   0.491s  |   0.491s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.341.smt2            |   0.656s  |   0.656s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.342.smt2            |   0.662s  |   0.662s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.346.smt2            |   0.786s  |   0.786s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.348.smt2            |   0.539s  |   0.539s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.350.smt2            |   0.364s  |   0.364s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.362.smt2            |   0.735s  |   0.735s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.363.smt2            |   0.557s  |   0.557s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.364.smt2            |   0.397s  |   0.397s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.366.smt2            |   0.386s  |   0.386s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.368.smt2            |   0.708s  |   0.708s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.370.smt2            |   0.547s  |   0.547s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.371.smt2            |   0.566s  |   0.566s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.372.smt2            |   0.731s  |   0.731s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.38.smt2             |   0.517s  |   0.517s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.380.smt2            |   0.545s  |   0.545s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.381.smt2            |   0.651s  |   0.651s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.388.smt2            |   0.520s  |   0.520s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.389.smt2            |   0.742s  |   0.742s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.39.smt2             |   0.288s  |   0.288s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.390.smt2            |   0.751s  |   0.751s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.391.smt2            |   0.589s  |   0.589s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.392.smt2            |   0.780s  |   0.780s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.393.smt2            |   0.478s  |   0.478s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.394.smt2            |   0.588s  |   0.588s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.395.smt2            |   0.668s  |   0.668s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.398.smt2            |   0.563s  |   0.563s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.40.smt2             |   0.278s  |   0.278s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.403.smt2            |   0.313s  |   0.313s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.408.smt2            |   0.540s  |   0.540s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.412.smt2            |   0.740s  |   0.740s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.413.smt2            |   0.303s  |   0.303s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.414.smt2            |   0.657s  |   0.657s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.415.smt2            |   0.544s  |   0.544s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.417.smt2            |   0.756s  |   0.756s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.418.smt2            |   0.590s  |   0.590s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.423.smt2            |   0.544s  |   0.544s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.45.smt2             |   0.414s  |   0.414s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.46.smt2             |   0.483s  |   0.483s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.48.smt2             |   0.218s  |   0.218s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.49.smt2             |   0.350s  |   0.350s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.5.smt2              |   0.391s  |   0.391s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.50.smt2             |   0.294s  |   0.294s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.51.smt2             |   0.284s  |   0.284s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.56.smt2             |   0.592s  |   0.592s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.58.smt2             |   0.499s  |   0.499s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.6.smt2              |   0.315s  |   0.315s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.69.smt2             |   0.464s  |   0.464s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.72.smt2             |   0.258s  |   0.258s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.73.smt2             |   0.478s  |   0.478s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.77.smt2             |   0.631s  |   0.631s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.8.smt2              |   0.348s  |   0.348s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.81.smt2             |   0.386s  |   0.386s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.85.smt2             |   0.396s  |   0.396s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.86.smt2             |   0.531s  |   0.531s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.9.smt2              |   0.276s  |   0.276s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.91.smt2             |   0.442s  |   0.442s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.95.smt2             |   0.349s  |   0.349s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.97.smt2             |   0.270s  |   0.270s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.98.smt2             |   0.227s  |   0.227s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.99.smt2             |   0.386s  |   0.386s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype_test.1.smt2         |   0.245s  |   0.245s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype_test.5.smt2         |   0.725s  |   0.725s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype_test.8.smt2         |   0.252s  |   0.252s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__setlib.11.smt2                        |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__setlib.12.smt2                        |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__size_s.4.smt2                         |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__stream__basic.1.smt2                  |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__stream__basic.2.smt2                  |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec_e__math__align_e.1.smt2                |   0.600s  |   0.600s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec_e__math__bits_e.1.smt2                 |   0.240s  |   0.240s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec_e__math__bits_e.3.smt2                 |   0.527s  |   0.527s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec_e__math__bits_e.5.smt2                 |   0.485s  |   0.485s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec_e__math__bits_e.8.smt2                 |   0.363s  |   0.363s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec_e__size_e.smt2                         |   0.206s  |   0.206s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/vbox__vbox.2.smt2                            |   3.967s  |   3.967s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/vbox__vbox.3.smt2                            |  10.281s  |  10.281s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/vbox__vbox.6.smt2                            |   3.250s  |   3.250s  |   0.000s  | 0.0%|
|non-incremental/UFDTNIA/20241211-verus/verismo/vbox__vbox.7.smt2                            |   9.424s  |   9.424s  |   0.000s  | 0.0%|
</details>
