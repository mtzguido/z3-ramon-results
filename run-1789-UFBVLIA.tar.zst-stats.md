# .

* SAT 0
* UNSAT 1
* TIMEOUT 187
* UNKNOWN 0

* UNSET 20

* ERROR 20

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: UFBVLIA.tar.zst
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: bc6c38e7d3424b88a505cacba4b268d0774d4547
Z3 branch: master
Z3 options: "-T:20"
Z3 inputs: https://zenodo.org/records/16740866/files/UFBVLIA.tar.zst?download=1
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


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-181.smt2    |    0.370s | 28.816MiB| unsat | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-071.smt2    |    2.279s | 54.948MiB| unset | 139 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-147.smt2    |    2.373s | 99.0MiB| unset | 114 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-115.smt2    |    2.442s | 89.132MiB| unset | 114 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-122.smt2    |    2.550s | 61.956MiB| unset | 114 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-099.smt2    |    2.738s | 79.948MiB| unset | 139 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-052.smt2    |    2.972s | 54.312MiB| unset | 114 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-136.smt2    |    3.407s | 90.996MiB| unset | 114 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-120.smt2    |    4.046s | 84.404MiB| unset | 114 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-125.smt2    |    5.362s | 64.208MiB| unset | 139 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-174.smt2    |    5.393s | 102.0MiB| unset | 139 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-036.smt2    |    5.545s | 53.08MiB| unset | 114 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-138.smt2    |    6.838s | 92.22MiB| unset | 139 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-113.smt2    |    6.888s | 97.12MiB| unset | 139 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-095.smt2    |    7.139s | 63.344MiB| unset | 139 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-143.smt2    |    8.425s | 93.62MiB| unset | 139 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-111.smt2    |   11.106s | 128.0MiB| unset | 139 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-066.smt2    |   12.362s | 58.976MiB| unset | 114 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-154.smt2    |   14.690s | 89.94MiB| unset | 114 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-169.smt2    |   16.323s | 98.0MiB| unset | 114 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-133.smt2    |   18.783s | 85.184MiB| unset | 114 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-060.smt2    |   20.018s | 57.808MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-129.smt2    |   20.025s | 141.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-038.smt2    |   20.027s | 146.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-170.smt2    |   20.028s | 103.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-079.smt2    |   20.029s | 151.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-166.smt2    |   20.030s | 115.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-091.smt2    |   20.030s | 156.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-177.smt2    |   20.033s | 120.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-042.smt2    |   20.035s | 52.388MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-005.smt2    |   20.035s | 51.924MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-040.smt2    |   20.040s | 130.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-106.smt2    |   20.045s | 149.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-193.smt2    |   20.048s | 135.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-189.smt2    |   20.048s | 123.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-001.smt2    |   20.049s | 213.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-146.smt2    |   20.055s | 93.5MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-112.smt2    |   20.063s | 80.936MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-161.smt2    |   20.063s | 109.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-179.smt2    |   20.063s | 350.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-046.smt2    |   20.065s | 136.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-072.smt2    |   20.066s | 60.792MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-061.smt2    |   20.067s | 58.444MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-016.smt2    |   20.068s | 221.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-184.smt2    |   20.070s | 231.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-182.smt2    |   20.070s | 84.02MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-075.smt2    |   20.070s | 58.964MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-010.smt2    |   20.070s | 49.32MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-077.smt2    |   20.071s | 60.6MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-148.smt2    |   20.072s | 146.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-049.smt2    |   20.074s | 54.216MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-045.smt2    |   20.075s | 123.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-123.smt2    |   20.075s | 93.284MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-098.smt2    |   20.076s | 62.116MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-145.smt2    |   20.077s | 93.172MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-195.smt2    |   20.077s | 49.556MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-163.smt2    |   20.077s | 104.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-054.smt2    |   20.078s | 58.66MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-158.smt2    |   20.080s | 97.468MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-124.smt2    |   20.081s | 83.412MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-055.smt2    |   20.082s | 99.504MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-007.smt2    |   20.082s | 49.84MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-064.smt2    |   20.083s | 56.836MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-014.smt2    |   20.083s | 112.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-100.smt2    |   20.084s | 138.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-135.smt2    |   20.085s | 86.476MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-088.smt2    |   20.085s | 152.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-196.smt2    |   20.085s | 112.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-032.smt2    |   20.086s | 58.32MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-078.smt2    |   20.087s | 151.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-093.smt2    |   20.087s | 59.284MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-197.smt2    |   20.088s | 51.904MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-187.smt2    |   20.088s | 48.672MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-024.smt2    |   20.089s | 53.928MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-114.smt2    |   20.089s | 85.508MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-108.smt2    |   20.090s | 172.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-144.smt2    |   20.090s | 89.292MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-073.smt2    |   20.090s | 61.748MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-019.smt2    |   20.090s | 115.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-165.smt2    |   20.091s | 106.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-175.smt2    |   20.091s | 127.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-050.smt2    |   20.091s | 112.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-037.smt2    |   20.091s | 124.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-164.smt2    |   20.092s | 87.404MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-074.smt2    |   20.092s | 139.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-149.smt2    |   20.092s | 155.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-109.smt2    |   20.093s | 122.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-206.smt2    |   20.093s | 237.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-156.smt2    |   20.094s | 93.42MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-103.smt2    |   20.094s | 83.136MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-199.smt2    |   20.094s | 50.628MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-013.smt2    |   20.095s | 52.184MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-186.smt2    |   20.095s | 46.4MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-018.smt2    |   20.095s | 115.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-121.smt2    |   20.096s | 81.58MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-194.smt2    |   20.097s | 47.724MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-067.smt2    |   20.097s | 156.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-090.smt2    |   20.097s | 163.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-011.smt2    |   20.098s | 127.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-028.smt2    |   20.098s | 140.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-004.smt2    |   20.098s | 117.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-023.smt2    |   20.098s | 50.512MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-157.smt2    |   20.099s | 98.72MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-020.smt2    |   20.099s | 129.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-043.smt2    |   20.100s | 134.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-085.smt2    |   20.100s | 61.432MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-192.smt2    |   20.100s | 139.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-058.smt2    |   20.100s | 152.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-057.smt2    |   20.100s | 57.316MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-087.smt2    |   20.100s | 62.036MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-104.smt2    |   20.102s | 79.54MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-119.smt2    |   20.102s | 169.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-082.smt2    |   20.102s | 63.32MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-204.smt2    |   20.103s | 130.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-142.smt2    |   20.103s | 78.912MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-012.smt2    |   20.103s | 144.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-053.smt2    |   20.103s | 126.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-069.smt2    |   20.103s | 60.9MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-008.smt2    |   20.104s | 50.784MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-110.smt2    |   20.104s | 62.924MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-056.smt2    |   20.104s | 149.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-107.smt2    |   20.104s | 115.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-041.smt2    |   20.105s | 141.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-198.smt2    |   20.105s | 48.98MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-203.smt2    |   20.106s | 208.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-084.smt2    |   20.106s | 156.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-139.smt2    |   20.106s | 90.808MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-168.smt2    |   20.106s | 169.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-102.smt2    |   20.106s | 155.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-105.smt2    |   20.108s | 64.752MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-044.smt2    |   20.108s | 57.628MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-188.smt2    |   20.108s | 217.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-081.smt2    |   20.109s | 81.136MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-000.smt2    |   20.109s | 149.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-172.smt2    |   20.109s | 270.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-118.smt2    |   20.110s | 81.356MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-171.smt2    |   20.110s | 121.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-176.smt2    |   20.111s | 132.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-025.smt2    |   20.111s | 140.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-180.smt2    |   20.111s | 245.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-076.smt2    |   20.111s | 139.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-153.smt2    |   20.112s | 95.672MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-026.smt2    |   20.112s | 136.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-131.smt2    |   20.112s | 142.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-035.smt2    |   20.112s | 144.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-083.smt2    |   20.112s | 157.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-126.smt2    |   20.112s | 81.48MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-092.smt2    |   20.113s | 160.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-034.smt2    |   20.113s | 50.928MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-065.smt2    |   20.113s | 139.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-033.smt2    |   20.114s | 145.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-017.smt2    |   20.114s | 134.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-117.smt2    |   20.115s | 80.26MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-140.smt2    |   20.115s | 80.984MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-130.smt2    |   20.116s | 88.792MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-185.smt2    |   20.116s | 51.272MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-207.smt2    |   20.117s | 211.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-096.smt2    |   20.117s | 237.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-173.smt2    |   20.117s | 114.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-039.smt2    |   20.118s | 126.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-137.smt2    |   20.118s | 84.048MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-027.smt2    |   20.118s | 131.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-152.smt2    |   20.119s | 105.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-128.smt2    |   20.120s | 95.692MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-150.smt2    |   20.120s | 94.7MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-155.smt2    |   20.120s | 252.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-003.smt2    |   20.120s | 52.276MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-022.smt2    |   20.120s | 116.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-062.smt2    |   20.121s | 141.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-021.smt2    |   20.122s | 110.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-134.smt2    |   20.122s | 96.328MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-063.smt2    |   20.122s | 141.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-047.smt2    |   20.123s | 140.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-132.smt2    |   20.123s | 90.616MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-070.smt2    |   20.125s | 152.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-200.smt2    |   20.125s | 145.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-205.smt2    |   20.125s | 226.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-183.smt2    |   20.125s | 138.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-048.smt2    |   20.125s | 145.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-086.smt2    |   20.126s | 153.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-101.smt2    |   20.126s | 165.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-031.smt2    |   20.127s | 129.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-015.smt2    |   20.127s | 124.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-116.smt2    |   20.127s | 151.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-029.smt2    |   20.127s | 135.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-178.smt2    |   20.127s | 131.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-059.smt2    |   20.128s | 133.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-202.smt2    |   20.128s | 150.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-097.smt2    |   20.129s | 168.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-151.smt2    |   20.129s | 262.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-094.smt2    |   20.129s | 150.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-051.smt2    |   20.129s | 148.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-167.smt2    |   20.130s | 90.304MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-191.smt2    |   20.132s | 49.464MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-009.smt2    |   20.132s | 123.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-068.smt2    |   20.133s | 150.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-159.smt2    |   20.133s | 256.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-002.smt2    |   20.134s | 208.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-127.smt2    |   20.135s | 81.38MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-160.smt2    |   20.137s | 253.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-089.smt2    |   20.138s | 140.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-162.smt2    |   20.139s | 99.676MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-141.smt2    |   20.142s | 90.908MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-030.smt2    |   20.143s | 153.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-201.smt2    |   20.143s | 127.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-190.smt2    |   20.145s | 206.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-080.smt2    |   20.145s | 167.0MiB| timeout | 0 |  |  |
|non-incremental/UFBVLIA/20210106-Schett/uso/ebso-006.smt2    |   20.279s | 2448.0MiB| timeout | 0 |  |  |
