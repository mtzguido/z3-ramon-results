# .

* SAT 2
* UNSAT 55
* TIMEOUT 11
* UNKNOWN 0

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/UFIDL.tar.zst?download=1 | Source list: benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-UFIDL.tar.zst-down
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: 881360db5a332d5551b40f75d7d603f55b52760d
Z3 branch: master
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/UFIDL.tar.zst?download=1
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
|non-incremental/UFIDL/boogie/NestedVC_P-vc_nested.smt2       |    0.021s | 19.856MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/Passification_UnreachableBlock-noinfer.smt2 |    0.022s | 19.896MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns8.smt2                      |    0.025s | 20.372MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/equiv3_M-infer_e-vc_local.smt2  |    0.025s | 19.672MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/Arrays_Q1-noinfer.smt2          |    0.025s | 20.608MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/UnreachableBlocks_R-vc_nested.smt2 |    0.025s | 19.592MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns12.smt2                     |    0.026s | 20.62MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns7.smt2                      |    0.027s | 20.62MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns6.smt2                      |    0.027s | 20.984MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/Arrays_P1-noinfer.smt2          |    0.028s | 20.46MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/FormulaTerm_or-noinfer.smt2     |    0.028s | 20.612MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns9.smt2                      |    0.029s | 21.408MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/QEpres/smtlib.858929.smt2 |    0.031s | 20.592MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala9.smt2   |    0.032s | 20.888MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala3.smt2   |    0.035s | 20.7MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/Arrays_Skip0-noinfer.smt2       |    0.035s | 19.812MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.675311.smt2 |    0.036s | 20.28MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala10.smt2  |    0.037s | 20.496MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/loop0_M-infer_e-vc_local.smt2   |    0.046s | 19.86MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/Call_DifferentFormalNames-noinfer.smt2 |    0.047s | 19.828MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/False_Test2-noinfer.smt2        |    0.047s | 19.812MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/AssumeEnsures_Caller0-noinfer.smt2 |    0.047s | 20.112MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/Call_DifferentFormalNames-noinfer_1.smt2 |    0.047s | 19.628MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/QEpres/smtlib.858765.smt2 |    0.048s | 20.156MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala8.smt2   |    0.048s | 21.716MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala2.smt2   |    0.049s | 22.112MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala5.smt2   |    0.049s | 21.672MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/heapsucc1_M-infer_eh-vc_local.smt2 |    0.049s | 19.9MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns5.smt2                      |    0.050s | 20.612MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/False_Test1-noinfer.smt2        |    0.050s | 19.86MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/QEpres/smtlib.858852.smt2 |    0.052s | 20.752MiB| sat | 0 |  |  |
|non-incremental/UFIDL/boogie/FormulaTerm_less-noinfer_1.smt2 |    0.052s | 19.828MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala0.smt2   |    0.053s | 20.664MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/UnreachableBlocks_P-vc_nested.smt2 |    0.053s | 19.84MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns13.smt2                     |    0.054s | 21.292MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/FormulaTerm_less-noinfer_2.smt2 |    0.054s | 20.4MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns0.smt2                      |    0.055s | 20.368MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/Passification_Loop-noinfer.smt2 |    0.055s | 19.56MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/heapsucc0_M-infer_eh-vc_local.smt2 |    0.055s | 19.952MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/equiv2_M-infer_e-vc_local.smt2  |    0.055s | 19.96MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala13.smt2  |    0.056s | 21.264MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns2.smt2                      |    0.056s | 20.4MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns1.smt2                      |    0.056s | 20.612MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns11.smt2                     |    0.056s | 20.396MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns3.smt2                      |    0.056s | 20.328MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/FormulaTerm_LESS-noinfer_3.smt2 |    0.056s | 20.26MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/Old_SwapElems-noinfer.smt2      |    0.056s | 20.376MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/UnreachableBlocks_Q-vc_nested.smt2 |    0.056s | 19.868MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/QEpres/smtlib.858843.smt2 |    0.058s | 21.012MiB| sat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns4.smt2                      |    0.058s | 20.88MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/Arrays_Skip1-noinfer.smt2       |    0.059s | 20.36MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala4.smt2   |    0.060s | 20.652MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns10.smt2                     |    0.061s | 20.984MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala6.smt2   |    0.071s | 21.464MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala7.smt2   |    0.072s | 21.64MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala12.smt2  |    0.076s | 21.672MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala11.smt2  |    0.086s | 22.072MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/Call_DifferentFormalNames-noinfer_2.smt2 |   20.057s | 230.0MiB| timeout | 0 |  |  |
|non-incremental/UFIDL/boogie/Call_Foo-noinfer.smt2           |   20.057s | 229.0MiB| timeout | 0 |  |  |
|non-incremental/UFIDL/boogie/Call_DifferentFormalNames-noinfer_3.smt2 |   20.060s | 228.0MiB| timeout | 0 |  |  |
|non-incremental/UFIDL/boogie/NestedVC_Q-vc_nested.smt2       |   20.060s | 225.0MiB| timeout | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.683530.smt2 |   20.322s | 2703.0MiB| timeout | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.697341.smt2 |   20.323s | 2802.0MiB| timeout | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.968906.smt2 |   20.435s | 4027.0MiB| timeout | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.976791.smt2 |   20.442s | 3852.0MiB| timeout | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.962381.smt2 |   20.453s | 4066.0MiB| timeout | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.976292.smt2 |   20.463s | 3853.0MiB| timeout | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/Fundamental_Theorem_Algebra/smtlib.1308248.smt2 |   20.521s | 4022.0MiB| timeout | 0 |  |  |
