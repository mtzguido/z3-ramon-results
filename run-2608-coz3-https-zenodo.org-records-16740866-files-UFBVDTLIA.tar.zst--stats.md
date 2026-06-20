# .

* SAT 0
* UNSAT 24
* TIMEOUT 0
* UNKNOWN 0

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/UFBVDTLIA.tar.zst?download=1 | Source list: benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-UFBVDTLIA.tar.zst-
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: 881360db5a332d5551b40f75d7d603f55b52760d
Z3 branch: master
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/UFBVDTLIA.tar.zst?download=1
Z3 commit message: Fix constant array UNSAT missed for small-domain store chains (#9907)

Z3 incorrectly returns SAT for formulas like `store(store(const(x), i0,
e0), i1, e1) = store(store(const(y), i0, e0), i1, e1) ∧ x ≠ y` when the
index sort has a small finite domain (e.g. `(_ BitVec 2)` = 4 elements).
The quantifier-based encoding of the same constraint correctly returns
UNSAT.

## Changes

### `src/sat/smt/array_solver.cpp` — `add_parent_lambda()`

When a store is added to an array's `m_parent_lambdas` after that array
already has `m_has_default = true` (i.e., a `default(array)` term
already exists in the e-graph), the default axiom for the new store was
silently dropped. This breaks the propagation chain:

```
default(const(x)) = x
  ↓ [via store default axiom]
default(store(const(x), i, v)) = x
  ↓ [via store default axiom]
default(store(store(const(x), ...), ...)) = x
  ↓ [EUF congruence from store equality]
x = y  →  contradiction
```

Fix: push `default_axiom(lambda)` in `add_parent_lambda` when
`m_has_default` is already set, so late-arriving stores still get their
default axioms instantiated.

```cpp
void solver::add_parent_lambda(theory_var v_child, euf::enode* lambda) {
    auto& d = get_var_data(find(v_child));
    ctx.push_vec(d.m_parent_lambdas, lambda);
    if (should_prop_upward(d))
        propagate_select_axioms(d, lambda);
    if (d.m_has_default)           // new: fire default axiom retroactively
        push_axiom(default_axiom(lambda));
}
```

### Known remaining gap

`mk_eq_core` in `array_rewriter.cpp` also has a related issue: the
unconditional store-chain expansion fires only when `domain_size >
num_lhs + num_rhs` (line 893), but the correct threshold is `domain_size
> max(num_lhs, num_rhs)`. With 4-element domain and 2 stores per side,
`2+2 = 4` equals the domain size so the expansion is skipped. The
variant gated by `m_expand_store_eq` already uses `max()` correctly
(line 911); the unconditional path needs the same fix.

---------

Co-authored-by: copilot-swe-agent[bot] <198982749+Copilot@users.noreply.github.com>
Co-authored-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2pa._01.smt2 |    0.023s | 20.076MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2page_entry_perm._01.smt2 |    0.024s | 19.856MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2page_entry_perm._05.smt2 |    0.025s | 20.112MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2page_entry_perm._03.smt2 |    0.028s | 20.124MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2page_entry_perm._04.smt2 |    0.029s | 19.84MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._07.smt2 |    0.029s | 20.128MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.zero_leads_is_empty_page_entry._06.smt2 |    0.029s | 20.052MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTLIA/20241211-verus/verussystems/mimalloc-smt-flagslib_flags.impl_%0.get_retire_expire._01.smt2 |    0.029s | 19.604MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTLIA/20241211-verus/verussystems/mimalloc-smt-flagslib_flags.impl_%0.set_is_committed._01.smt2 |    0.029s | 19.716MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._01.smt2 |    0.030s | 19.88MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._32.smt2 |    0.030s | 20.096MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.zero_leads_is_empty_page_entry._01.smt2 |    0.030s | 20.348MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.zero_leads_is_empty_page_entry._03.smt2 |    0.030s | 20.136MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._16.smt2 |    0.031s | 20.1MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._25.smt2 |    0.032s | 20.88MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._35.smt2 |    0.032s | 21.344MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._06.smt2 |    0.032s | 20.844MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTLIA/20241211-verus/verussystems/mimalloc-smt-flagslib_flags.impl_%0.set_is_committed._02.smt2 |    0.033s | 20.824MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._12.smt2 |    0.034s | 21.124MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTLIA/20241211-verus/verussystems/mimalloc-smt-flagslib_flags.impl_%0.set_is_zero_init._03.smt2 |    0.037s | 20.884MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTLIA/20241211-verus/verussystems/mimalloc-smt-flagslib_flags.impl_%0.set_retire_expire._02.smt2 |    0.037s | 21.152MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTLIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_auto._01.smt2 |    0.038s | 21.392MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTLIA/20241211-verus/verussystems/mimalloc-smt-flagslib_flags.impl_%0.set_in_full._01.smt2 |    0.039s | 20.86MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._05.smt2 |    0.049s | 20.808MiB| unsat | 0 |  |  |
