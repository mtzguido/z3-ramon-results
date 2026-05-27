# .

* SAT 2
* UNSAT 10
* TIMEOUT 3
* UNKNOWN 0

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/UFLRA.tar.zst?download=1 | Source list: benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-UFLRA.tar.zst-down
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: 91205d2f60d0b202a991366149e7fa8f92150f7c
Z3 branch: master
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/UFLRA.tar.zst?download=1
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
|non-incremental/UFLRA/FFT/smtlib.627688.smt2                 |    0.022s | 20.344MiB| unsat | 0 |  |  |
|non-incremental/UFLRA/FFT/smtlib.627457.smt2                 |    0.022s | 20.356MiB| unsat | 0 |  |  |
|non-incremental/UFLRA/FFT/smtlib.620535.smt2                 |    0.023s | 19.956MiB| unsat | 0 |  |  |
|non-incremental/UFLRA/FFT/smtlib.623417.smt2                 |    0.023s | 20.108MiB| unsat | 0 |  |  |
|non-incremental/UFLRA/FFT/smtlib.623597.smt2                 |    0.023s | 20.36MiB| unsat | 0 |  |  |
|non-incremental/UFLRA/FFT/smtlib.627531.smt2                 |    0.023s | 20.104MiB| unsat | 0 |  |  |
|non-incremental/UFLRA/FFT/smtlib.623531.smt2                 |    0.023s | 20.108MiB| unsat | 0 |  |  |
|non-incremental/UFLRA/FFT/smtlib.623474.smt2                 |    0.024s | 20.264MiB| unsat | 0 |  |  |
|non-incremental/UFLRA/FFT/smtlib.620487.smt2                 |    0.024s | 20.36MiB| unsat | 0 |  |  |
|non-incremental/UFLRA/FFT/smtlib.627605.smt2                 |    0.037s | 20.112MiB| unsat | 0 |  |  |
|non-incremental/UFLRA/misc/set16.smt2                        |    1.668s | 33.06MiB| sat | 0 |  |  |
|non-incremental/UFLRA/misc/set9.smt2                         |    2.679s | 39.864MiB| sat | 0 |  |  |
|non-incremental/UFLRA/misc/set14.smt2                        |   20.025s | 143.0MiB| timeout | 0 |  |  |
|non-incremental/UFLRA/misc/set19.smt2                        |   20.029s | 129.0MiB| timeout | 0 |  |  |
|non-incremental/UFLRA/misc/list2.smt2                        |   20.034s | 238.0MiB| timeout | 0 |  |  |
