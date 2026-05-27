# .

* SAT 15
* UNSAT 95
* TIMEOUT 150
* UNKNOWN 6

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/UFNIRA.tar.zst?download=1 | Source list: benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-UFNIRA.tar.zst-dow
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: 91205d2f60d0b202a991366149e7fa8f92150f7c
Z3 branch: master
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/UFNIRA.tar.zst?download=1
Z3 commit message: Allow JS/WASM init to accept Deno-friendly wasm load paths (#9621)

The JS bindings currently assume the wasm can be located via the default
Emscripten path resolution, which can force Deno users into
`--allow-read`. This change lets callers provide a custom wasm load path
through `init(...)`, so Deno can resolve the packaged wasm asset without
filesystem reads.

- **Public init API**
- Extend the JS entrypoints (`node` and `browser`) so `init(...)`
accepts optional Emscripten module overrides.
- Surface a typed `Z3ModuleOverrides` shape with explicit support for
`locateFile(path, prefix)`.

- **Low-level initialization**
- Thread module overrides through the generated low-level wrapper
instead of always calling the Emscripten module factory with no
arguments.
  - Keep the default behavior unchanged when no overrides are provided.

- **Docs**
  - Document the Deno usage pattern in the published JS README.
- Clarify the `locateFile` signature and show the intended Deno 2.1+
`import.meta.resolve(...)` flow.

- **Focused coverage**
- Add unit tests for `node` and `browser` init to verify module
overrides are forwarded correctly.

Example:

```ts
import { init } from 'npm:z3-solver';

const api = await init({
  locateFile: (file, _prefix): string =>
    import.meta.resolve(`npm:z3-solver/build/${file}`),
});
```

---------

Co-authored-by: copilot-swe-agent[bot] <198982749+Copilot@users.noreply.github.com>
Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

</pre>


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U20.smt2 |    0.025s | 20.832MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U56_sol1.smt2 |    0.026s | 20.112MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U27_sol1.smt2 |    0.030s | 20.82MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C4_sol1.smt2 |    0.032s | 20.216MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U42_sol1.smt2 |    0.037s | 20.104MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U49_sol2.smt2 |    0.040s | 20.108MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U51.smt2 |    0.040s | 20.896MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U26_sol1.smt2 |    0.042s | 20.592MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U10_sol1.smt2 |    0.044s | 20.62MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U6_sol1.smt2 |    0.044s | 20.576MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U81_sol1.smt2 |    0.044s | 20.364MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C9a_sol1.smt2 |    0.046s | 20.108MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U3_sol1.smt2 |    0.048s | 20.324MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U91_sol2.smt2 |    0.049s | 19.972MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U71_sol1.smt2 |    0.052s | 19.968MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U9_sol1.smt2 |    0.054s | 20.248MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C12_sol1.smt2 |    0.054s | 20.144MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U75.smt2 |    0.055s | 20.524MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U66.smt2 |    0.057s | 20.872MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U24_sol1.smt2 |    0.059s | 20.332MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U20_sol3.smt2 |    0.060s | 19.904MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U71.smt2 |    0.060s | 20.672MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U89.smt2 |    0.061s | 20.868MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U61_sol1.smt2 |    0.062s | 20.88MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U45_sol2.smt2 |    0.062s | 20.152MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U51_sol1.smt2 |    0.062s | 20.376MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U14_sol1.smt2 |    0.062s | 20.62MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U50_sol1.smt2 |    0.062s | 20.156MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U53_sol1.smt2 |    0.063s | 20.108MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U48.smt2 |    0.063s | 20.696MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U62.smt2 |    0.063s | 20.7MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U48_sol2.smt2 |    0.066s | 20.156MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U17_sol1.smt2 |    0.066s | 20.108MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U1.smt2 |    0.066s | 20.972MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U90_sol1.smt2 |    0.067s | 20.188MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U49_sol1.smt2 |    0.067s | 20.02MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U72.smt2 |    0.067s | 20.62MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U68_sol1.smt2 |    0.068s | 20.156MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U23.smt2 |    0.068s | 20.732MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U11_sol1.smt2 |    0.069s | 20.4MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U67_sol1.smt2 |    0.070s | 20.408MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U46.smt2 |    0.070s | 20.568MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C9_sol1.smt2 |    0.071s | 20.408MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C13_sol1.smt2 |    0.071s | 20.088MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U2_sol1.smt2 |    0.071s | 20.16MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U56_sol2.smt2 |    0.073s | 20.164MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C10_sol1.smt2 |    0.074s | 20.148MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U41_sol2.smt2 |    0.076s | 19.928MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U46_sol2.smt2 |    0.076s | 20.168MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U39_sol1.smt2 |    0.077s | 20.256MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U5_sol1.smt2 |    0.078s | 20.604MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C1_sol1.smt2 |    0.079s | 19.94MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U76_sol1.smt2 |    0.079s | 20.648MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U8_sol1.smt2 |    0.079s | 20.164MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U66_sol2.smt2 |    0.081s | 20.116MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U91_sol1.smt2 |    0.081s | 20.104MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U75_sol2.smt2 |    0.081s | 20.152MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U50_sol2.smt2 |    0.082s | 20.22MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C6_sol1.smt2 |    0.083s | 20.332MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U54_sol1.smt2 |    0.083s | 20.712MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U66_sol1.smt2 |    0.084s | 19.944MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U7_sol1.smt2 |    0.085s | 20.12MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U25_sol2.smt2 |    0.085s | 20.104MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U64_sol1.smt2 |    0.086s | 20.1MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U68.smt2 |    0.087s | 20.872MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U46_sol1.smt2 |    0.089s | 20.108MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U48_sol1.smt2 |    0.091s | 20.132MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U81.smt2 |    0.091s | 20.564MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U57.smt2 |    0.091s | 20.408MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U41_sol1.smt2 |    0.092s | 20.268MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U72_sol2.smt2 |    0.092s | 20.096MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U89_sol1.smt2 |    0.092s | 19.9MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U4_sol1.smt2 |    0.093s | 20.696MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U4.smt2 |    0.096s | 21.164MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U79.smt2 |    0.098s | 32.536MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U26_sol2.smt2 |    0.103s | 20.64MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U72_sol1.smt2 |    0.109s | 20.144MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U23_sol1.smt2 |    0.110s | 19.952MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U20_sol2.smt2 |    0.110s | 20.364MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C2_sol1.smt2 |    0.111s | 20.0MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U45_sol1.smt2 |    0.111s | 20.144MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U25_sol1.smt2 |    0.111s | 19.924MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C10.smt2 |    0.111s | 20.024MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U41.smt2 |    0.111s | 20.868MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U87_sol2.smt2 |    0.112s | 20.116MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U41_sol3.smt2 |    0.112s | 20.14MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U54_sol2.smt2 |    0.112s | 20.176MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U13_sol1.smt2 |    0.113s | 19.884MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U75_sol1.smt2 |    0.115s | 19.9MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C3_sol1.smt2 |    0.116s | 19.964MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U87_sol1.smt2 |    0.116s | 20.152MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U92_sol1.smt2 |    0.117s | 20.048MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U57_sol1.smt2 |    0.118s | 20.424MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U20_sol1.smt2 |    0.118s | 20.096MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U26.smt2 |    0.118s | 22.48MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U93_sol1.smt2 |    0.120s | 20.628MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U11.smt2 |    0.121s | 20.372MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U62_sol1.smt2 |    0.128s | 20.076MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U50_sol3.smt2 |    0.128s | 20.132MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U82_sol1.smt2 |    0.130s | 20.356MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U8_sol2.smt2 |    0.134s | 19.904MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C5.smt2 |    0.135s | 20.624MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U17.smt2 |    0.135s | 20.576MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U44_sol1.smt2 |    0.137s | 20.612MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U19_sol1.smt2 |    0.137s | 19.904MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U44_sol2.smt2 |    0.143s | 21.06MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U37_sol1.smt2 |    0.150s | 21.196MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C5_sol1.smt2 |    0.172s | 20.62MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U12_sol1.smt2 |    0.316s | 20.832MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U7.smt2 |    5.621s | 26.536MiB| unknown | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C6.smt2 |    5.860s | 45.376MiB| unknown | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U14.smt2 |    7.478s | 30.464MiB| unknown | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U14.smt2 |    9.577s | 29.6MiB| unknown | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U40_sol1.smt2 |   10.885s | 21.36MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U17.smt2 |   12.016s | 143.0MiB| unknown | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U16_sol1.smt2 |   16.709s | 33.16MiB| unknown | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U27.smt2 |   20.014s | 23.32MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U34.smt2 |   20.021s | 80.368MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U66.smt2 |   20.026s | 32.136MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U44.smt2 |   20.037s | 42.144MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U93.smt2 |   20.040s | 28.268MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C7.smt2 |   20.043s | 27.86MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C9.smt2 |   20.044s | 37.98MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U93.smt2 |   20.045s | 28.156MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U88.smt2 |   20.049s | 36.304MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U76.smt2 |   20.049s | 27.604MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U53.smt2 |   20.049s | 47.764MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U1_sol1.smt2 |   20.052s | 26.504MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U27.smt2 |   20.054s | 25.02MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U11.smt2 |   20.057s | 56.072MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C4.smt2 |   20.057s | 65.808MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C9a.smt2 |   20.058s | 66.732MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U4.smt2 |   20.060s | 336.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C3.smt2 |   20.062s | 87.32MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U87.smt2 |   20.062s | 67.948MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U10.smt2 |   20.063s | 104.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U90.smt2 |   20.064s | 62.552MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U90.smt2 |   20.065s | 94.668MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U33.smt2 |   20.068s | 172.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C7.smt2 |   20.069s | 28.588MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U44.smt2 |   20.069s | 491.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C6.smt2 |   20.070s | 38.364MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U1.smt2 |   20.074s | 24.044MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U6.smt2 |   20.074s | 123.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U7.smt2 |   20.077s | 38.508MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U12.smt2 |   20.079s | 33.752MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C5.smt2 |   20.080s | 22.704MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U30.smt2 |   20.081s | 23.84MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U45.smt2 |   20.090s | 28.388MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C13.smt2 |   20.090s | 144.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U23.smt2 |   20.094s | 50.872MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U9.smt2 |   20.094s | 153.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C7_sol1.smt2 |   20.095s | 31.108MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C9.smt2 |   20.095s | 54.84MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U57.smt2 |   20.101s | 143.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C9a.smt2 |   20.103s | 42.792MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C8_sol1.smt2 |   20.108s | 39.324MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U15_sol1.smt2 |   20.111s | 29.708MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U26.smt2 |   20.115s | 33.428MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U45.smt2 |   20.118s | 212.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C3.smt2 |   20.121s | 64.86MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U53.smt2 |   20.123s | 48.556MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U12.smt2 |   20.124s | 28.856MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C10.smt2 |   20.128s | 260.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U47.smt2 |   20.129s | 28.416MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U76.smt2 |   20.131s | 28.008MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U38.smt2 |   20.138s | 39.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U39.smt2 |   20.148s | 66.108MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U81.smt2 |   20.150s | 57.16MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U39.smt2 |   20.173s | 325.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U33.smt2 |   20.190s | 173.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U68.smt2 |   20.209s | 278.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C4.smt2 |   20.211s | 264.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U16.smt2 |   20.220s | 267.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C13.smt2 |   20.231s | 239.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U72.smt2 |   20.234s | 301.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U33_sol1.smt2 |   20.237s | 534.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U6.smt2 |   20.249s | 192.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U10.smt2 |   20.269s | 262.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U9.smt2 |   20.297s | 284.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U28.smt2 |   20.328s | 455.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C8.smt2 |   20.328s | 480.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U5.smt2 |   20.364s | 686.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C2.smt2 |   20.412s | 565.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U91.smt2 |   20.425s | 614.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U71.smt2 |   20.490s | 643.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U70.smt2 |   20.514s | 619.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U91.smt2 |   20.531s | 1081.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U19.smt2 |   20.545s | 719.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U16.smt2 |   20.643s | 986.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C8.smt2 |   20.708s | 1385.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U92.smt2 |   20.715s | 1277.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U67.smt2 |   20.769s | 1674.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U51.smt2 |   20.847s | 1404.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U29.smt2 |   20.912s | 1726.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U19.smt2 |   20.916s | 1762.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U43.smt2 |   20.943s | 1721.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U87.smt2 |   20.956s | 1800.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U37.smt2 |   21.053s | 2176.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U42.smt2 |   21.065s | 2147.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U43.smt2 |   21.077s | 1904.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U40.smt2 |   21.120s | 2138.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U41.smt2 |   21.124s | 2065.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U67.smt2 |   21.138s | 2179.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U20.smt2 |   21.150s | 2239.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U31.smt2 |   21.158s | 2369.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U61.smt2 |   21.170s | 2356.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U73.smt2 |   21.217s | 2704.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U73_sol1.smt2 |   21.234s | 2762.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U29_sol1.smt2 |   21.250s | 2804.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U64.smt2 |   21.258s | 3149.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U37.smt2 |   21.262s | 2125.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U22.smt2 |   21.274s | 2472.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U48.smt2 |   21.291s | 2381.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U54.smt2 |   21.320s | 2733.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U13.smt2 |   21.325s | 2943.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U24.smt2 |   21.328s | 2648.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U49.smt2 |   21.336s | 2537.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U49.smt2 |   21.337s | 2638.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U29.smt2 |   21.339s | 2281.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U15.smt2 |   21.340s | 2472.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U61.smt2 |   21.344s | 2365.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U21.smt2 |   21.349s | 2664.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U82.smt2 |   21.351s | 2589.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U5.smt2 |   21.361s | 2536.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U15_sol2.smt2 |   21.373s | 2257.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U62.smt2 |   21.389s | 2305.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U50.smt2 |   21.398s | 2593.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C11.smt2 |   21.419s | 2380.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U50.smt2 |   21.424s | 3229.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U2.smt2 |   21.426s | 2779.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U46.smt2 |   21.452s | 2654.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U8.smt2 |   21.463s | 2972.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U56.smt2 |   21.464s | 2869.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U21_sol1.smt2 |   21.505s | 3070.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U65.smt2 |   21.505s | 3264.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U22_sol1.smt2 |   21.510s | 3426.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C11_sol1.smt2 |   21.547s | 3361.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U24.smt2 |   21.570s | 3728.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U2.smt2 |   21.574s | 3673.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U15.smt2 |   21.589s | 2833.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C11.smt2 |   21.606s | 3527.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C1.smt2 |   21.609s | 7289.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U25.smt2 |   21.613s | 2852.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C12.smt2 |   21.619s | 3318.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U40.smt2 |   21.623s | 2888.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U56.smt2 |   21.639s | 2940.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U8.smt2 |   21.648s | 2918.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U3.smt2 |   21.654s | 4225.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C2.smt2 |   21.692s | 3923.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U13.smt2 |   21.696s | 3845.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U22.smt2 |   21.723s | 3525.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U54.smt2 |   21.730s | 3137.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C12.smt2 |   21.743s | 3286.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U42.smt2 |   21.765s | 4781.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U3.smt2 |   21.801s | 3531.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U21.smt2 |   21.802s | 3521.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C1.smt2 |   21.813s | 3847.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U64.smt2 |   21.879s | 3508.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U89.smt2 |   21.882s | 7370.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U73.smt2 |   21.901s | 4414.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U82.smt2 |   21.902s | 3950.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U92.smt2 |   21.915s | 4296.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U75.smt2 |   21.916s | 7559.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U25.smt2 |   21.956s | 4187.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U43_sol1.smt2 |   22.297s | 7646.0MiB| timeout | 0 |  |  |
