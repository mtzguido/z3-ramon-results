# .

* SAT 70
* UNSAT 0
* TIMEOUT 0
* UNKNOWN 0

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/QF_SNIA.tar.zst?download=1 | Source list: benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-QF_SNIA.tar.zst-do
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: 881360db5a332d5551b40f75d7d603f55b52760d
Z3 branch: master
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/QF_SNIA.tar.zst?download=1
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
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/2007.corecstrs.readable.smt2 |    0.022s | 20.112MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/2009.corecstrs.readable.smt2 |    0.022s | 20.108MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1574.corecstrs.readable.smt2 |    0.023s | 20.372MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1597.corecstrs.readable.smt2 |    0.023s | 20.128MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1628.corecstrs.readable.smt2 |    0.023s | 20.484MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1575.corecstrs.readable.smt2 |    0.023s | 20.324MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1595.corecstrs.readable.smt2 |    0.024s | 20.364MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1553.corecstrs.readable.smt2 |    0.024s | 20.36MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20200224-Wu-PyExZ3/dddb9cc1f86d5738fd85ffa1b430c4e9df9771c0fffa945b9b414772.smt2 |    0.025s | 20.456MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1572.corecstrs.readable.smt2 |    0.025s | 20.364MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/big/838.corecstrs.readable.smt2 |    0.026s | 20.36MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1551.corecstrs.readable.smt2 |    0.026s | 20.36MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/2010.corecstrs.readable.smt2 |    0.026s | 20.12MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20200224-Wu-PyExZ3/5735c9082c3f9cd487c6376032029bb499ba1f87113dc9ca03adc6bc.smt2 |    0.027s | 20.48MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/big/846.corecstrs.readable.smt2 |    0.027s | 20.388MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/big/823.corecstrs.readable.smt2 |    0.027s | 20.592MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1555.corecstrs.readable.smt2 |    0.027s | 20.16MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1566.corecstrs.readable.smt2 |    0.027s | 20.144MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1550.corecstrs.readable.smt2 |    0.027s | 20.304MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/big/827.corecstrs.readable.smt2 |    0.028s | 20.488MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1588.corecstrs.readable.smt2 |    0.028s | 20.22MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1556.corecstrs.readable.smt2 |    0.028s | 20.324MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1633.corecstrs.readable.smt2 |    0.028s | 20.264MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/big/824.corecstrs.readable.smt2 |    0.029s | 20.832MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/big/845.corecstrs.readable.smt2 |    0.029s | 20.608MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20200224-Wu-PyExZ3/f72b09bc9444f702ad7cdf3a9075754e71d673f3d134d9f485f6608a.smt2 |    0.030s | 20.46MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/big/812.corecstrs.readable.smt2 |    0.030s | 20.288MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/big/808.corecstrs.readable.smt2 |    0.030s | 20.404MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/big/821.corecstrs.readable.smt2 |    0.030s | 20.624MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1589.corecstrs.readable.smt2 |    0.030s | 20.576MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1636.corecstrs.readable.smt2 |    0.030s | 20.324MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20200224-Wu-PyExZ3/e007cfdcf4dd61007107222cbedbb46ad161a945ab5ee0a68d3f585a.smt2 |    0.031s | 20.656MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1907.corecstrs.readable.smt2 |    0.031s | 20.512MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/big/826.corecstrs.readable.smt2 |    0.032s | 20.416MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1596.corecstrs.readable.smt2 |    0.032s | 20.604MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1554.corecstrs.readable.smt2 |    0.040s | 20.216MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/big/822.corecstrs.readable.smt2 |    0.041s | 20.384MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/2008.corecstrs.readable.smt2 |    0.041s | 20.104MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1634.corecstrs.readable.smt2 |    0.041s | 20.372MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1594.corecstrs.readable.smt2 |    0.042s | 20.48MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1884.corecstrs.readable.smt2 |    0.042s | 20.152MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1552.corecstrs.readable.smt2 |    0.042s | 20.4MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1590.corecstrs.readable.smt2 |    0.042s | 20.616MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/big/811.corecstrs.readable.smt2 |    0.043s | 20.352MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1598.corecstrs.readable.smt2 |    0.043s | 20.16MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1557.corecstrs.readable.smt2 |    0.043s | 20.368MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1885.corecstrs.readable.smt2 |    0.044s | 20.128MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1637.corecstrs.readable.smt2 |    0.044s | 20.364MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1627.corecstrs.readable.smt2 |    0.044s | 20.384MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1909.corecstrs.readable.smt2 |    0.044s | 20.432MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/big/825.corecstrs.readable.smt2 |    0.045s | 20.308MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1635.corecstrs.readable.smt2 |    0.045s | 20.2MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1908.corecstrs.readable.smt2 |    0.045s | 20.36MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1910.corecstrs.readable.smt2 |    0.045s | 20.18MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1573.corecstrs.readable.smt2 |    0.045s | 20.52MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20200224-Wu-PyExZ3/bdcb3877984a55b540face066045c4642cba1bc553af78576a41a76e.smt2 |    0.046s | 20.748MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1576.corecstrs.readable.smt2 |    0.046s | 20.224MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1911.corecstrs.readable.smt2 |    0.046s | 20.364MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1626.corecstrs.readable.smt2 |    0.046s | 20.22MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1997.corecstrs.readable.smt2 |    0.047s | 20.448MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1886.corecstrs.readable.smt2 |    0.047s | 20.38MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1567.corecstrs.readable.smt2 |    0.047s | 20.432MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/big/840.corecstrs.readable.smt2 |    0.048s | 20.168MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1568.corecstrs.readable.smt2 |    0.048s | 20.264MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/big/839.corecstrs.readable.smt2 |    0.049s | 20.368MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/big/809.corecstrs.readable.smt2 |    0.049s | 20.632MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/big/849.corecstrs.readable.smt2 |    0.050s | 20.376MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/big/820.corecstrs.readable.smt2 |    0.051s | 20.564MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/big/843.corecstrs.readable.smt2 |    0.051s | 20.428MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/big/851.corecstrs.readable.smt2 |    0.051s | 20.62MiB| sat | 0 |  |  |
