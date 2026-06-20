# .

* SAT 0
* UNSAT 1
* TIMEOUT 207
* UNKNOWN 0

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/UFBVLIA.tar.zst?download=1 | Source list: benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-UFBVLIA.tar.zst-do
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: 881360db5a332d5551b40f75d7d603f55b52760d
Z3 branch: master
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/UFBVLIA.tar.zst?download=1
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
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-181.smt2    |    0.352s | 28.944MiB| unsat | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-013.smt2    |   20.019s | 50.676MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-010.smt2    |   20.019s | 48.876MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-042.smt2    |   20.020s | 51.164MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-018.smt2    |   20.022s | 48.724MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-009.smt2    |   20.023s | 50.66MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-201.smt2    |   20.024s | 80.044MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-131.smt2    |   20.025s | 138.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-012.smt2    |   20.027s | 120.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-025.smt2    |   20.028s | 50.9MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-024.smt2    |   20.029s | 50.076MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-197.smt2    |   20.030s | 47.596MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-054.smt2    |   20.030s | 127.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-155.smt2    |   20.031s | 138.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-023.smt2    |   20.031s | 48.592MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-079.smt2    |   20.031s | 60.66MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-041.smt2    |   20.033s | 148.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-177.smt2    |   20.034s | 119.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-120.smt2    |   20.037s | 152.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-109.smt2    |   20.037s | 132.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-059.smt2    |   20.039s | 133.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-072.smt2    |   20.039s | 57.892MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-165.smt2    |   20.040s | 97.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-091.smt2    |   20.042s | 148.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-144.smt2    |   20.043s | 91.808MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-157.smt2    |   20.044s | 100.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-087.smt2    |   20.044s | 58.836MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-060.smt2    |   20.046s | 56.976MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-164.smt2    |   20.047s | 88.34MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-153.smt2    |   20.047s | 97.372MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-162.smt2    |   20.047s | 102.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-002.smt2    |   20.047s | 216.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-075.smt2    |   20.049s | 59.264MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-200.smt2    |   20.050s | 50.508MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-199.smt2    |   20.050s | 48.388MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-187.smt2    |   20.051s | 49.62MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-063.smt2    |   20.051s | 137.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-149.smt2    |   20.051s | 152.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-068.smt2    |   20.052s | 142.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-198.smt2    |   20.052s | 45.728MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-003.smt2    |   20.052s | 52.188MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-168.smt2    |   20.052s | 169.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-001.smt2    |   20.053s | 208.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-127.smt2    |   20.053s | 81.392MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-205.smt2    |   20.053s | 148.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-045.smt2    |   20.054s | 62.512MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-103.smt2    |   20.054s | 81.716MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-030.smt2    |   20.055s | 49.564MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-074.smt2    |   20.055s | 128.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-145.smt2    |   20.055s | 92.656MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-050.smt2    |   20.055s | 54.024MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-179.smt2    |   20.055s | 121.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-064.smt2    |   20.056s | 58.244MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-104.smt2    |   20.056s | 78.896MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-189.smt2    |   20.056s | 119.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-193.smt2    |   20.057s | 124.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-142.smt2    |   20.057s | 77.396MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-186.smt2    |   20.058s | 48.636MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-124.smt2    |   20.058s | 82.092MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-057.smt2    |   20.058s | 52.788MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-178.smt2    |   20.058s | 131.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-028.smt2    |   20.059s | 123.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-152.smt2    |   20.059s | 108.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-102.smt2    |   20.059s | 161.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-077.smt2    |   20.060s | 139.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-110.smt2    |   20.060s | 62.208MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-171.smt2    |   20.060s | 120.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-141.smt2    |   20.061s | 88.892MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-022.smt2    |   20.061s | 143.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-016.smt2    |   20.062s | 126.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-036.smt2    |   20.062s | 126.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-106.smt2    |   20.063s | 151.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-015.smt2    |   20.063s | 121.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-117.smt2    |   20.063s | 81.42MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-088.smt2    |   20.064s | 65.4MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-112.smt2    |   20.065s | 65.132MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-008.smt2    |   20.065s | 48.284MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-093.smt2    |   20.065s | 59.14MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-101.smt2    |   20.065s | 166.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-151.smt2    |   20.066s | 163.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-040.smt2    |   20.068s | 129.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-032.smt2    |   20.068s | 57.008MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-182.smt2    |   20.069s | 82.12MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-137.smt2    |   20.069s | 84.512MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-194.smt2    |   20.069s | 47.764MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-004.smt2    |   20.073s | 113.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-174.smt2    |   20.074s | 195.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-203.smt2    |   20.075s | 124.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-007.smt2    |   20.075s | 47.468MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-051.smt2    |   20.076s | 148.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-133.smt2    |   20.076s | 229.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-196.smt2    |   20.077s | 48.664MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-122.smt2    |   20.079s | 154.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-033.smt2    |   20.081s | 134.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-111.smt2    |   20.081s | 161.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-135.smt2    |   20.081s | 84.664MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-163.smt2    |   20.081s | 103.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-156.smt2    |   20.082s | 138.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-076.smt2    |   20.082s | 59.184MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-037.smt2    |   20.083s | 49.1MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-053.smt2    |   20.084s | 159.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-129.smt2    |   20.084s | 142.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-126.smt2    |   20.084s | 82.628MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-098.smt2    |   20.086s | 81.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-005.smt2    |   20.086s | 48.868MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-055.smt2    |   20.087s | 91.28MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-176.smt2    |   20.087s | 130.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-034.smt2    |   20.087s | 49.704MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-049.smt2    |   20.087s | 49.7MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-140.smt2    |   20.087s | 79.66MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-095.smt2    |   20.088s | 61.308MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-071.smt2    |   20.088s | 146.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-039.smt2    |   20.089s | 56.336MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-011.smt2    |   20.089s | 49.144MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-027.smt2    |   20.089s | 126.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-070.smt2    |   20.090s | 157.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-175.smt2    |   20.091s | 128.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-090.smt2    |   20.091s | 162.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-065.smt2    |   20.091s | 54.676MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-147.smt2    |   20.092s | 168.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-158.smt2    |   20.093s | 92.832MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-166.smt2    |   20.094s | 114.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-108.smt2    |   20.094s | 78.244MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-128.smt2    |   20.094s | 93.688MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-130.smt2    |   20.094s | 88.528MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-021.smt2    |   20.094s | 110.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-113.smt2    |   20.095s | 174.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-159.smt2    |   20.095s | 98.832MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-029.smt2    |   20.096s | 130.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-066.smt2    |   20.097s | 141.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-081.smt2    |   20.097s | 80.364MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-154.smt2    |   20.097s | 132.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-044.smt2    |   20.098s | 78.616MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-082.smt2    |   20.098s | 63.504MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-148.smt2    |   20.098s | 94.48MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-085.smt2    |   20.099s | 61.38MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-173.smt2    |   20.099s | 112.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-080.smt2    |   20.099s | 146.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-069.smt2    |   20.100s | 125.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-206.smt2    |   20.100s | 144.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-143.smt2    |   20.100s | 91.948MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-125.smt2    |   20.101s | 161.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-114.smt2    |   20.101s | 84.536MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-195.smt2    |   20.101s | 128.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-202.smt2    |   20.102s | 126.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-035.smt2    |   20.102s | 129.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-014.smt2    |   20.103s | 111.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-100.smt2    |   20.104s | 126.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-107.smt2    |   20.104s | 140.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-150.smt2    |   20.105s | 94.936MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-026.smt2    |   20.105s | 130.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-052.smt2    |   20.106s | 125.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-061.smt2    |   20.106s | 128.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-170.smt2    |   20.106s | 101.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-019.smt2    |   20.106s | 108.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-185.smt2    |   20.107s | 48.012MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-132.smt2    |   20.107s | 89.14MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-167.smt2    |   20.109s | 90.864MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-056.smt2    |   20.109s | 147.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-116.smt2    |   20.110s | 148.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-062.smt2    |   20.110s | 147.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-139.smt2    |   20.112s | 87.624MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-000.smt2    |   20.112s | 144.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-115.smt2    |   20.113s | 155.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-119.smt2    |   20.113s | 175.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-083.smt2    |   20.113s | 150.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-048.smt2    |   20.113s | 143.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-192.smt2    |   20.114s | 135.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-161.smt2    |   20.114s | 267.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-094.smt2    |   20.115s | 79.976MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-190.smt2    |   20.115s | 200.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-046.smt2    |   20.115s | 144.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-073.smt2    |   20.117s | 63.736MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-017.smt2    |   20.118s | 116.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-084.smt2    |   20.118s | 160.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-191.smt2    |   20.118s | 118.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-169.smt2    |   20.120s | 227.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-136.smt2    |   20.121s | 169.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-067.smt2    |   20.121s | 224.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-172.smt2    |   20.121s | 276.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-020.smt2    |   20.123s | 216.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-089.smt2    |   20.123s | 141.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-183.smt2    |   20.123s | 125.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-078.smt2    |   20.124s | 148.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-099.smt2    |   20.125s | 154.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-038.smt2    |   20.127s | 136.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-121.smt2    |   20.129s | 81.996MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-188.smt2    |   20.130s | 217.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-047.smt2    |   20.130s | 215.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-105.smt2    |   20.133s | 80.836MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-123.smt2    |   20.133s | 172.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-184.smt2    |   20.134s | 123.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-134.smt2    |   20.134s | 95.716MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-118.smt2    |   20.136s | 82.732MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-138.smt2    |   20.139s | 247.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-097.smt2    |   20.152s | 166.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-160.smt2    |   20.152s | 253.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-058.smt2    |   20.153s | 148.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-204.smt2    |   20.154s | 130.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-043.smt2    |   20.154s | 139.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-031.smt2    |   20.154s | 127.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-096.smt2    |   20.154s | 164.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-180.smt2    |   20.154s | 158.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-092.smt2    |   20.158s | 160.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-146.smt2    |   20.159s | 134.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-086.smt2    |   20.163s | 229.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-207.smt2    |   20.178s | 411.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-006.smt2    |   20.284s | 2285.0MiB| timeout | 0 |  |  |
