# .

* SAT 5
* UNSAT 12
* TIMEOUT 0
* UNKNOWN 0

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/QF_AUFNIA.tar.zst?download=1 | Source list: benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-QF_AUFNIA.tar.zst-
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: 881360db5a332d5551b40f75d7d603f55b52760d
Z3 branch: master
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/QF_AUFNIA.tar.zst?download=1
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
|non-incremental/QF_AUFNIA/UltimateAutomizer/s3_clnt.blast.03_false-unreach-call.i.cil.c_71.smt2 |    0.045s | 23.18MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFNIA/UltimateAutomizer/s3_srvr.blast.07_false-unreach-call.i.cil.c_0.smt2 |    0.046s | 22.9MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFNIA/UltimateAutomizer/s3_srvr.blast.10_true-unreach-call.i.cil.c_0.smt2 |    0.057s | 24.336MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFNIA/UltimateAutomizer/s3_clnt.blast.01_false-unreach-call.i.cil.c_57.smt2 |    0.059s | 23.164MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFNIA/UltimateAutomizer/s3_clnt.blast.02_false-unreach-call.i.cil.c_71.smt2 |    0.060s | 22.412MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFNIA/UltimateAutomizer/s3_srvr.blast.14_true-unreach-call.i.cil.c_959.smt2 |    0.079s | 26.832MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFNIA/UltimateAutomizer/s3_srvr.blast.15_true-unreach-call.i.cil.c_1173.smt2 |    0.080s | 26.608MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFNIA/UltimateAutomizer/s3_srvr.blast.08_true-unreach-call.i.cil.c_1140.smt2 |    0.083s | 25.312MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFNIA/UltimateAutomizer/s3_srvr.blast.16_true-unreach-call.i.cil.c_2036.smt2 |    0.090s | 27.668MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFNIA/UltimateAutomizer/s3_srvr.blast.12_true-unreach-call.i.cil.c_0.smt2 |    0.110s | 26.824MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFNIA/UltimateAutomizer/s3_srvr.blast.06_true-unreach-call.i.cil.c.smt2 |    0.113s | 29.824MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFNIA/UltimateAutomizer/s3_srvr.blast.06_true-unreach-call.i.cil.c_2803.smt2 |    0.115s | 28.756MiB| unsat | 0 |  |  |
|non-incremental/QF_AUFNIA/UltimateAutomizer/s3_srvr.blast.01_false-unreach-call.i.cil.c_0.smt2 |    0.440s | 27.792MiB| sat | 0 |  |  |
|non-incremental/QF_AUFNIA/UltimateAutomizer/s3_srvr.blast.04_false-unreach-call.i.cil.c_0.smt2 |    0.458s | 26.724MiB| sat | 0 |  |  |
|non-incremental/QF_AUFNIA/UltimateAutomizer/s3_srvr.blast.02_false-unreach-call.i.cil.c_0.smt2 |    0.493s | 26.784MiB| sat | 0 |  |  |
|non-incremental/QF_AUFNIA/UltimateAutomizer/s3_srvr.blast.11_false-unreach-call.i.cil.c_0.smt2 |    1.687s | 34.876MiB| sat | 0 |  |  |
|non-incremental/QF_AUFNIA/UltimateAutomizer/s3_clnt.blast.01_false-unreach-call.i.cil.c_0.smt2 |   14.480s | 51.768MiB| sat | 0 |  |  |
