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
Z3 commit: 91205d2f60d0b202a991366149e7fa8f92150f7c
Z3 branch: master
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/UFIDL.tar.zst?download=1
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
|non-incremental/UFIDL/boogie/UnreachableBlocks_Q-vc_nested.smt2 |    0.021s | 19.596MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/heapsucc0_M-infer_eh-vc_local.smt2 |    0.022s | 19.576MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/AssumeEnsures_Caller0-noinfer.smt2 |    0.022s | 19.86MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/loop0_M-infer_e-vc_local.smt2   |    0.022s | 19.612MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/FormulaTerm_less-noinfer_2.smt2 |    0.023s | 20.284MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/QEpres/smtlib.858765.smt2 |    0.024s | 20.22MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns3.smt2                      |    0.024s | 20.332MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/Arrays_Skip0-noinfer.smt2       |    0.024s | 19.564MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/QEpres/smtlib.858929.smt2 |    0.025s | 20.384MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns0.smt2                      |    0.025s | 20.632MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/Arrays_Q1-noinfer.smt2          |    0.025s | 20.368MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/Old_SwapElems-noinfer.smt2      |    0.026s | 20.36MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/QEpres/smtlib.858852.smt2 |    0.027s | 20.9MiB| sat | 0 |  |  |
|non-incremental/UFIDL/boogie/UnreachableBlocks_P-vc_nested.smt2 |    0.027s | 19.524MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/Arrays_Skip1-noinfer.smt2       |    0.027s | 20.356MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/equiv2_M-infer_e-vc_local.smt2  |    0.027s | 19.6MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala3.smt2   |    0.029s | 20.672MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/heapsucc1_M-infer_eh-vc_local.smt2 |    0.031s | 19.596MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns5.smt2                      |    0.032s | 20.368MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns1.smt2                      |    0.032s | 20.412MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/False_Test1-noinfer.smt2        |    0.032s | 19.592MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/FormulaTerm_less-noinfer_1.smt2 |    0.033s | 19.732MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns10.smt2                     |    0.034s | 20.9MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/Passification_Loop-noinfer.smt2 |    0.034s | 19.752MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/Passification_UnreachableBlock-noinfer.smt2 |    0.034s | 19.552MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/NestedVC_P-vc_nested.smt2       |    0.034s | 19.528MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala13.smt2  |    0.036s | 21.364MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns2.smt2                      |    0.036s | 20.384MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns8.smt2                      |    0.036s | 20.436MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala10.smt2  |    0.037s | 20.464MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns13.smt2                     |    0.037s | 21.184MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.675311.smt2 |    0.038s | 20.14MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/QEpres/smtlib.858843.smt2 |    0.038s | 20.92MiB| sat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns12.smt2                     |    0.038s | 20.264MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/False_Test2-noinfer.smt2        |    0.038s | 19.584MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala7.smt2   |    0.040s | 21.488MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns6.smt2                      |    0.040s | 20.924MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns9.smt2                      |    0.040s | 21.08MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns11.smt2                     |    0.040s | 20.412MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns4.smt2                      |    0.041s | 20.916MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala9.smt2   |    0.042s | 20.728MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala0.smt2   |    0.042s | 21.124MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala4.smt2   |    0.044s | 20.756MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/Burns/burns7.smt2                      |    0.046s | 20.416MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala5.smt2   |    0.049s | 21.568MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala6.smt2   |    0.051s | 21.392MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala12.smt2  |    0.054s | 21.892MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/UnreachableBlocks_R-vc_nested.smt2 |    0.056s | 19.516MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala8.smt2   |    0.059s | 21.676MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/equiv3_M-infer_e-vc_local.smt2  |    0.060s | 19.744MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/Call_DifferentFormalNames-noinfer.smt2 |    0.060s | 19.644MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/Call_DifferentFormalNames-noinfer_1.smt2 |    0.060s | 19.988MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala11.smt2  |    0.061s | 22.08MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/FormulaTerm_or-noinfer.smt2     |    0.061s | 20.196MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/Arrays_P1-noinfer.smt2          |    0.063s | 20.344MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/FormulaTerm_LESS-noinfer_3.smt2 |    0.063s | 20.372MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala2.smt2   |    0.065s | 21.78MiB| unsat | 0 |  |  |
|non-incremental/UFIDL/boogie/Call_DifferentFormalNames-noinfer_3.smt2 |   20.029s | 228.0MiB| timeout | 0 |  |  |
|non-incremental/UFIDL/boogie/Call_DifferentFormalNames-noinfer_2.smt2 |   20.030s | 229.0MiB| timeout | 0 |  |  |
|non-incremental/UFIDL/boogie/NestedVC_Q-vc_nested.smt2       |   20.038s | 225.0MiB| timeout | 0 |  |  |
|non-incremental/UFIDL/boogie/Call_Foo-noinfer.smt2           |   20.043s | 229.0MiB| timeout | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.697341.smt2 |   20.276s | 2908.0MiB| timeout | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.683530.smt2 |   20.303s | 2760.0MiB| timeout | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.976292.smt2 |   20.393s | 4085.0MiB| timeout | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.976791.smt2 |   20.393s | 4084.0MiB| timeout | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.968906.smt2 |   20.413s | 4049.0MiB| timeout | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.962381.smt2 |   20.414s | 4087.0MiB| timeout | 0 |  |  |
|non-incremental/UFIDL/sledgehammer/Fundamental_Theorem_Algebra/smtlib.1308248.smt2 |   20.608s | 4986.0MiB| timeout | 0 |  |  |
