# .

* SAT 0
* UNSAT 248
* TIMEOUT 0
* UNKNOWN 2

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: bench-fstar-ulib-smt2-rerun
Runner: rise-runner-2
Z3 repo: CanCebeci/z3
Z3 commit: bc6c38e7d3424b88a505cacba4b268d0774d4547
Z3 branch: bc6c38e7d3424b88a505cacba4b268d0774d4547
Z3 options: "-T:20"
Z3 inputs: inputs/fstar-ulib-smt2
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
|queries-LowStar.Endianness-1.smt2                            |    0.167s | 25.968MiB| unsat | 1 |  |  |
|queries-Prims.smt2                                           |    0.214s | 23.3MiB| unsat | 1 |  |  |
|queries-FStar.Pervasives.Native.smt2                         |    0.437s | 45.152MiB| unsat | 1 |  |  |
|queries-FStar.Heap.smt2                                      |    0.468s | 74.632MiB| unsat | 1 |  |  |
|queries-FStar.Classical-1.smt2                               |    0.538s | 73.516MiB| unsat | 1 |  |  |
|queries-FStar.Tactics.Effect-1.smt2                          |    0.544s | 74.888MiB| unsat | 1 |  |  |
|queries-FStar.All.smt2                                       |    0.579s | 74.744MiB| unsat | 1 |  |  |
|queries-FStar.TSet-1.smt2                                    |    0.594s | 74.024MiB| unsat | 1 |  |  |
|queries-FStar.Tactics.Common.smt2                            |    0.622s | 73.42MiB| unsat | 1 |  |  |
|queries-FStar.Sequence.Ambient.smt2                          |    0.630s | 73.98MiB| unsat | 1 |  |  |
|queries-FStar.TwoLevelHeap.smt2                              |    0.639s | 74.744MiB| unsat | 1 |  |  |
|queries-FStar.VConfig.smt2                                   |    0.652s | 73.468MiB| unsat | 1 |  |  |
|queries-FStar.PredicateExtensionality.smt2                   |    0.666s | 73.728MiB| unsat | 1 |  |  |
|queries-FStar.Order.smt2                                     |    0.706s | 73.516MiB| unsat | 1 |  |  |
|queries-FStar.Reflection.Types.smt2                          |    0.725s | 73.892MiB| unsat | 1 |  |  |
|queries-FStar.OrdSetProps.smt2                               |    0.759s | 73.98MiB| unsat | 1 |  |  |
|queries-FStar.Option.smt2                                    |    0.769s | 74.932MiB| unsat | 1 |  |  |
|queries-FStar.PropositionalExtensionality.smt2               |    0.780s | 73.508MiB| unsat | 1 |  |  |
|queries-FStar.Monotonic.Pure.smt2                            |    0.780s | 73.464MiB| unsat | 1 |  |  |
|queries-FStar.Relational.Relational.smt2                     |    0.819s | 74.52MiB| unsat | 1 |  |  |
|queries-FStar.Classical.smt2                                 |    0.832s | 73.72MiB| unsat | 1 |  |  |
|queries-FStar.Universe.smt2                                  |    0.847s | 73.468MiB| unsat | 1 |  |  |
|queries-FStar.OrdMapProps.smt2                               |    0.870s | 74.276MiB| unsat | 1 |  |  |
|queries-FStar.TSet-2.smt2                                    |    0.925s | 74.264MiB| unsat | 1 |  |  |
|queries-FStar.Tactics.Effect-2.smt2                          |    0.929s | 74.544MiB| unsat | 1 |  |  |
|queries-FStar.Squash.smt2                                    |    0.945s | 73.472MiB| unsat | 1 |  |  |
|queries-FStar.IndefiniteDescription.smt2                     |    0.950s | 74.26MiB| unsat | 1 |  |  |
|queries-FStar.Algebra.CommMonoid.smt2                        |    0.968s | 73.5MiB| unsat | 1 |  |  |
|queries-FStar.List.Pure.Base.smt2                            |    0.972s | 74.692MiB| unsat | 1 |  |  |
|queries-FStar.IFC.smt2                                       |    0.982s | 73.844MiB| unsat | 1 |  |  |
|queries-FStar.SquashProperties.smt2                          |    0.985s | 74.24MiB| unsat | 1 |  |  |
|queries-FStar.Set.smt2                                       |    0.987s | 73.828MiB| unsat | 1 |  |  |
|queries-Steel.FractionalPermission.smt2                      |    1.026s | 73.736MiB| unsat | 1 |  |  |
|queries-FStar.Tactics.Result.smt2                            |    1.033s | 74.492MiB| unsat | 1 |  |  |
|queries-FStar.Constructive.smt2                              |    1.044s | 73.688MiB| unsat | 1 |  |  |
|queries-FStar.Algebra.CommMonoid.Equiv.smt2                  |    1.062s | 73.752MiB| unsat | 1 |  |  |
|queries-FStar.MRef.smt2                                      |    1.066s | 74.548MiB| unsat | 1 |  |  |
|queries-FStar.Calc.smt2                                      |    1.070s | 73.92MiB| unsat | 1 |  |  |
|queries-FStar.WellFounded.smt2                               |    1.075s | 74.5MiB| unsat | 1 |  |  |
|queries-FStar.Ref.smt2                                       |    1.084s | 74.732MiB| unsat | 1 |  |  |
|queries-FStar.Universe.PCM.smt2                              |    1.101s | 74.684MiB| unsat | 1 |  |  |
|queries-FStar.MSTTotal.smt2                                  |    1.118s | 73.516MiB| unsat | 1 |  |  |
|queries-LowStar.Comment.smt2                                 |    1.125s | 81.212MiB| unsat | 1 |  |  |
|queries-FStar.Ghost.smt2                                     |    1.142s | 73.456MiB| unsat | 1 |  |  |
|queries-FStar.Fin.smt2                                       |    1.144s | 76.884MiB| unsat | 1 |  |  |
|queries-Steel.MonotonicCounter.smt2                          |    1.147s | 77.128MiB| unsat | 1 |  |  |
|queries-FStar.GSet.smt2                                      |    1.179s | 73.992MiB| unsat | 1 |  |  |
|queries-FStar.Char.smt2                                      |    1.194s | 79.412MiB| unsat | 1 |  |  |
|queries-FStar.PartialMap.smt2                                |    1.208s | 73.724MiB| unsat | 1 |  |  |
|queries-FStar.NMSTTotal.smt2                                 |    1.220s | 73.932MiB| unsat | 1 |  |  |
|queries-FStar.IntegerIntervals.smt2                          |    1.270s | 75.076MiB| unsat | 1 |  |  |
|queries-FStar.MST.smt2                                       |    1.271s | 74.04MiB| unsat | 1 |  |  |
|queries-FStar.Util.smt2                                      |    1.316s | 79.936MiB| unsat | 1 |  |  |
|queries-FStar.NMST.smt2                                      |    1.327s | 74.46MiB| unsat | 1 |  |  |
|queries-FStar.String.smt2                                    |    1.332s | 84.332MiB| unsat | 1 |  |  |
|queries-FStar.TSet.smt2                                      |    1.370s | 74.248MiB| unsat | 1 |  |  |
|queries-FStar.Map.smt2                                       |    1.373s | 74.04MiB| unsat | 1 |  |  |
|queries-FStar.Classical.Sugar.smt2                           |    1.406s | 73.724MiB| unsat | 1 |  |  |
|queries-FStar.Matrix2.smt2                                   |    1.412s | 75.432MiB| unsat | 1 |  |  |
|queries-FStar.Tactics.Effect.smt2                            |    1.432s | 74.66MiB| unsat | 1 |  |  |
|queries-FStar.ST.smt2                                        |    1.446s | 74.54MiB| unsat | 1 |  |  |
|queries-FStar.Reflection.Derived.Lemmas.smt2                 |    1.516s | 85.024MiB| unsat | 1 |  |  |
|queries-FStar.Tactics.SyntaxHelpers.smt2                     |    1.520s | 87.356MiB| unsat | 1 |  |  |
|queries-FStar.Algebra.Monoid.smt2                            |    1.545s | 73.776MiB| unsat | 1 |  |  |
|queries-FStar.Monotonic.Map.smt2                             |    1.562s | 85.012MiB| unsat | 1 |  |  |
|queries-FStar.Crypto.smt2                                    |    1.569s | 136.0MiB| unsat | 1 |  |  |
|queries-FStar.FiniteSet.smt2                                 |    1.576s | 76.06MiB| unsat | 1 |  |  |
|queries-FStar.Sequence.Util.smt2                             |    1.578s | 75.228MiB| unsat | 1 |  |  |
|queries-FStar.Sequence.Seq.smt2                              |    1.582s | 79.896MiB| unsat | 1 |  |  |
|queries-FStar.DependentMap.smt2                              |    1.601s | 73.772MiB| unsat | 1 |  |  |
|queries-FStar.Algebra.CommMonoid.Fold.Nested.smt2            |    1.604s | 85.08MiB| unsat | 1 |  |  |
|queries-FStar.Tactics.Util.smt2                              |    1.614s | 75.584MiB| unsat | 1 |  |  |
|queries-FStar.Error.smt2                                     |    1.618s | 87.828MiB| unsat | 1 |  |  |
|queries-FStar.Seq.Permutation-2.smt2                         |    1.667s | 80.668MiB| unsat | 1 |  |  |
|queries-FStar.Monotonic.Witnessed.smt2                       |    1.671s | 73.748MiB| unsat | 1 |  |  |
|queries-FStar.Int.Cast.Full.smt2                             |    1.687s | 134.0MiB| unsat | 1 |  |  |
|queries-LowStar.BufferOps.smt2                               |    1.713s | 135.0MiB| unsat | 1 |  |  |
|queries-FStar.Real.smt2                                      |    1.774s | 73.468MiB| unsat | 1 |  |  |
|queries-FStar.Tactics.Print.smt2                             |    1.784s | 90.22MiB| unsat | 1 |  |  |
|queries-Steel.Effect.M.smt2                                  |    1.792s | 139.0MiB| unsat | 1 |  |  |
|queries-FStar.Classical-2.smt2                               |    1.824s | 73.72MiB| unsat | 1 |  |  |
|queries-FStar.Vector.Properties.smt2                         |    1.827s | 82.196MiB| unsat | 1 |  |  |
|queries-FStar.FunctionalExtensionality.smt2                  |    1.828s | 81.972MiB| unsat | 1 |  |  |
|queries-FStar.PCM.smt2                                       |    1.887s | 74.124MiB| unsat | 1 |  |  |
|queries-FStar.Tactics.CanonCommSwaps.smt2                    |    1.903s | 75.392MiB| unsat | 1 |  |  |
|queries-Steel.PCMMap.smt2                                    |    1.918s | 75.88MiB| unsat | 1 |  |  |
|queries-FStar.List.smt2                                      |    1.935s | 75.588MiB| unsat | 1 |  |  |
|queries-Steel.ST.GhostReference.smt2                         |    1.948s | 154.0MiB| unsat | 1 |  |  |
|queries-FStar.Tactics.Typeclasses.smt2                       |    1.979s | 134.0MiB| unsat | 1 |  |  |
|queries-LowStar.Endianness-2.smt2                            |    1.983s | 136.0MiB| unsat | 1 |  |  |
|queries-LowStar.Regional.smt2                                |    2.079s | 135.0MiB| unsat | 1 |  |  |
|queries-LowStar.BufferCompat.smt2                            |    2.086s | 135.0MiB| unsat | 1 |  |  |
|queries-FStar.WellFoundedRelation.smt2                       |    2.133s | 75.756MiB| unsat | 1 |  |  |
|queries-FStar.Seq.Sorted.smt2                                |    2.143s | 76.64MiB| unsat | 1 |  |  |
|queries-Steel.ST.CancellableSpinLock.smt2                    |    2.155s | 151.0MiB| unsat | 1 |  |  |
|queries-FStar.Math.Lib.smt2                                  |    2.173s | 73.464MiB| unsat | 1 |  |  |
|queries-Steel.Channel.Protocol.smt2                          |    2.183s | 73.512MiB| unsat | 1 |  |  |
|queries-Steel.ST.MonotonicReference.smt2                     |    2.253s | 153.0MiB| unsat | 1 |  |  |
|queries-FStar.Pervasives.smt2                                |    2.257s | 79.984MiB| unsat | 1 |  |  |
|queries-FStar.Seq.Permutation.smt2                           |    2.320s | 80.428MiB| unsat | 1 |  |  |
|queries-FStar.Seq.Equiv.smt2                                 |    2.365s | 82.208MiB| unsat | 1 |  |  |
|queries-FStar.Tcp.smt2                                       |    2.375s | 136.0MiB| unsat | 1 |  |  |
|queries-Steel.Primitive.ForkJoin.smt2                        |    2.392s | 154.0MiB| unsat | 1 |  |  |
|queries-Steel.LockCoupling.smt2                              |    2.398s | 152.0MiB| unsat | 1 |  |  |
|queries-Steel.Closure.smt2                                   |    2.403s | 153.0MiB| unsat | 1 |  |  |
|queries-FStar.LexicographicOrdering.smt2                     |    2.459s | 74.732MiB| unsat | 1 |  |  |
|queries-FStar.Tactics.Simplifier.smt2                        |    2.498s | 134.0MiB| unsat | 1 |  |  |
|queries-FStar.Reflection.Derived.smt2                        |    2.561s | 85.324MiB| unsat | 1 |  |  |
|queries-Steel.ST.Loops.Util.smt2                             |    2.564s | 152.0MiB| unsat | 1 |  |  |
|queries-FStar.Tactics.CanonMonoid.smt2                       |    2.576s | 136.0MiB| unsat | 1 |  |  |
|queries-LowStar.Buffer.smt2                                  |    2.606s | 135.0MiB| unsat | 1 |  |  |
|queries-FStar.WellFounded.Util.smt2                          |    2.606s | 134.0MiB| unsat | 1 |  |  |
|queries-Steel.ST.Coercions.smt2                              |    2.613s | 256.0MiB| unsat | 1 |  |  |
|queries-FStar.InteractiveHelpers.Output.smt2                 |    2.616s | 136.0MiB| unsat | 1 |  |  |
|queries-Steel.ST.Reference.smt2                              |    2.627s | 156.0MiB| unsat | 1 |  |  |
|queries-Steel.Utils.smt2                                     |    2.627s | 153.0MiB| unsat | 1 |  |  |
|queries-Steel.ST.Util.smt2                                   |    2.659s | 154.0MiB| unsat | 1 |  |  |
|queries-FStar.Monotonic.DependentMap.smt2                    |    2.662s | 86.568MiB| unsat | 1 |  |  |
|queries-FStar.Int32.smt2                                     |    2.690s | 83.992MiB| unsat | 1 |  |  |
|queries-FStar.OrdMap.smt2                                    |    2.692s | 74.496MiB| unsat | 1 |  |  |
|queries-Steel.Semantics.Instantiate.smt2                     |    2.705s | 142.0MiB| unsat | 1 |  |  |
|queries-FStar.Pointer.Derived2.smt2                          |    2.721s | 140.0MiB| unsat | 1 |  |  |
|queries-FStar.Math.Euclid-1.smt2                             |    2.737s | 135.0MiB| unsat | 1 |  |  |
|queries-FStar.Algebra.CommMonoid.Fold.smt2                   |    2.765s | 83.74MiB| unsat | 1 |  |  |
|queries-FStar.Int8.smt2                                      |    2.816s | 85.716MiB| unsat | 1 |  |  |
|queries-Steel.Channel.Duplex.smt2                            |    2.840s | 153.0MiB| unsat | 1 |  |  |
|queries-Steel.MonotonicReference.smt2                        |    2.900s | 153.0MiB| unsat | 1 |  |  |
|queries-FStar.Tactics.Logic.smt2                             |    2.975s | 134.0MiB| unsat | 1 |  |  |
|queries-LowStar.Literal.smt2                                 |    2.978s | 145.0MiB| unsat | 1 |  |  |
|queries-FStar.ModifiesGen-6.smt2                             |    2.987s | 155.0MiB| unsat | 1 |  |  |
|queries-Steel.ST.Effect.Atomic.smt2                          |    3.079s | 256.0MiB| unsat | 1 |  |  |
|queries-FStar.Int16.smt2                                     |    3.093s | 85.12MiB| unsat | 1 |  |  |
|queries-FStar.InteractiveHelpers.Base.smt2                   |    3.102s | 135.0MiB| unsat | 1 |  |  |
|queries-LowStar.Monotonic.Buffer-2.smt2                      |    3.108s | 134.0MiB| unsat | 1 |  |  |
|queries-FStar.Vector.Base.smt2                               |    3.201s | 81.316MiB| unsat | 1 |  |  |
|queries-FStar.List.Pure.Properties.smt2                      |    3.217s | 77.184MiB| unsat | 1 |  |  |
|queries-Steel.DisposableInvariant.smt2                       |    3.223s | 156.0MiB| unsat | 1 |  |  |
|queries-Steel.Loops.smt2                                     |    3.225s | 154.0MiB| unsat | 1 |  |  |
|queries-FStar.Int128.smt2                                    |    3.248s | 87.492MiB| unsat | 1 |  |  |
|queries-Steel.ST.SpinLock.smt2                               |    3.250s | 154.0MiB| unsat | 1 |  |  |
|queries-Steel.GhostPCMReference.smt2                         |    3.310s | 153.0MiB| unsat | 1 |  |  |
|queries-FStar.Int64.smt2                                     |    3.360s | 84.884MiB| unsat | 1 |  |  |
|queries-FStar.Reflection.Formula.smt2                        |    3.389s | 90.76MiB| unsat | 1 |  |  |
|queries-FStar.ReflexiveTransitiveClosure.smt2                |    3.424s | 134.0MiB| unsat | 1 |  |  |
|queries-Steel.ST.Loops.smt2                                  |    3.466s | 155.0MiB| unsat | 1 |  |  |
|queries-Steel.ST.GhostPCMReference.smt2                      |    3.512s | 161.0MiB| unsat | 1 |  |  |
|queries-Steel.ST.Effect.Ghost.smt2                           |    3.528s | 256.0MiB| unsat | 1 |  |  |
|queries-Steel.ST.BitVector.smt2                              |    3.549s | 153.0MiB| unsat | 1 |  |  |
|queries-Steel.Preorder.smt2                                  |    3.554s | 87.224MiB| unsat | 1 |  |  |
|queries-FStar.Pointer.Derived3.smt2                          |    3.594s | 141.0MiB| unsat | 1 |  |  |
|queries-FStar.Buffer.Quantifiers.smt2                        |    3.663s | 135.0MiB| unsat | 1 |  |  |
|queries-FStar.Array.smt2                                     |    3.746s | 85.456MiB| unsat | 1 |  |  |
|queries-FStar.BitVector.smt2                                 |    3.799s | 77.38MiB| unsat | 1 |  |  |
|queries-FStar.InteractiveHelpers.ExploreTerm.smt2            |    3.825s | 135.0MiB| unsat | 1 |  |  |
|queries-LowStar.UninitializedBuffer.smt2                     |    3.830s | 135.0MiB| unsat | 1 |  |  |
|queries-FStar.OrdSet.smt2                                    |    3.831s | 78.936MiB| unsat | 1 |  |  |
|queries-FStar.Monotonic.HyperHeap.smt2                       |    3.833s | 79.896MiB| unsat | 1 |  |  |
|queries-FStar.List.Tot.Base.smt2                             |    3.848s | 73.716MiB| unsat | 1 |  |  |
|queries-Steel.SpinLock.smt2                                  |    3.927s | 152.0MiB| unsat | 1 |  |  |
|queries-FStar.Tactics.CanonCommMonoidSimple.smt2             |    3.950s | 135.0MiB| unsat | 1 |  |  |
|queries-FStar.Reflection.Data.smt2                           |    4.078s | 75.436MiB| unsat | 1 |  |  |
|queries-FStar.ConstantTime.Integers.smt2                     |    4.110s | 135.0MiB| unsat | 1 |  |  |
|queries-Steel.Primitive.ForkJoin.Unix.smt2                   |    4.122s | 155.0MiB| unsat | 1 |  |  |
|queries-FStar.BigOps.smt2                                    |    4.130s | 145.0MiB| unsat | 1 |  |  |
|queries-FStar.Printf.smt2                                    |    4.178s | 137.0MiB| unsat | 1 |  |  |
|queries-FStar.InteractiveHelpers.Effectful.smt2              |    4.238s | 136.0MiB| unsat | 1 |  |  |
|queries-Steel.ST.Effect.AtomicAndGhost.smt2                  |    4.272s | 256.0MiB| unsat | 1 |  |  |
|queries-Steel.ST.Effect.smt2                                 |    4.322s | 163.0MiB| unsat | 1 |  |  |
|queries-FStar.Seq.Permutation-3.smt2                         |    4.336s | 89.616MiB| unsat | 1 |  |  |
|queries-FStar.Tactics.CanonCommMonoidSimple.Equiv.smt2       |    4.501s | 136.0MiB| unsat | 1 |  |  |
|queries-LowStar.ImmutableBuffer.smt2                         |    4.591s | 135.0MiB| unsat | 1 |  |  |
|queries-Steel.PCMReference.smt2                              |    4.694s | 153.0MiB| unsat | 1 |  |  |
|queries-FStar.Tactics.Canon.smt2                             |    4.697s | 135.0MiB| unsat | 1 |  |  |
|queries-Steel.ST.Array.smt2                                  |    4.766s | 156.0MiB| unsat | 1 |  |  |
|queries-FStar.InteractiveHelpers.PostProcess.smt2            |    4.898s | 155.0MiB| unsat | 1 |  |  |
|queries-LowStar.Monotonic.Buffer-1.smt2                      |    4.973s | 147.0MiB| unsat | 1 |  |  |
|queries-LowStar.PrefixFreezableBuffer.smt2                   |    4.984s | 136.0MiB| unsat | 1 |  |  |
|queries-FStar.Bytes.smt2                                     |    5.024s | 136.0MiB| unsat | 1 |  |  |
|queries-FStar.Tactics.CanonCommMonoid.smt2                   |    5.124s | 135.0MiB| unsat | 1 |  |  |
|queries-FStar.Reflection.Arith.smt2                          |    5.279s | 134.0MiB| unsat | 1 |  |  |
|queries-LowStar.ConstBuffer.smt2                             |    5.357s | 135.0MiB| unsat | 1 |  |  |
|queries-FStar.Math.Euclid.smt2                               |    5.448s | 135.0MiB| unsat | 1 |  |  |
|queries-FStar.Monotonic.Seq.smt2                             |    5.729s | 155.0MiB| unsat | 1 |  |  |
|queries-FStar.BV.smt2                                        |    5.751s | 84.528MiB| unsat | 1 |  |  |
|queries-LowStar.Regional.Instances.smt2                      |    5.921s | 151.0MiB| unsat | 1 |  |  |
|queries-FStar.UInt8.smt2                                     |    5.999s | 88.616MiB| unsat | 1 |  |  |
|queries-FStar.Seq.Base.smt2                                  |    6.096s | 84.06MiB| unsat | 1 |  |  |
|queries-FStar.Integers.smt2                                  |    6.218s | 134.0MiB| unsat | 1 |  |  |
|queries-LowStar.ToFStarBuffer.smt2                           |    6.237s | 141.0MiB| unsat | 1 |  |  |
|queries-FStar.ModifiesGen-2.smt2                             |    6.263s | 154.0MiB| unsat | 1 |  |  |
|queries-FStar.UInt16.smt2                                    |    6.384s | 91.412MiB| unsat | 1 |  |  |
|queries-FStar.Tactics.BV.smt2                                |    6.451s | 140.0MiB| unsat | 1 |  |  |
|queries-FStar.Tactics.Derived.smt2                           |    6.554s | 134.0MiB| unsat | 1 |  |  |
|queries-LowStar.Printf.smt2                                  |    6.673s | 160.0MiB| unsat | 1 |  |  |
|queries-FStar.UInt32.smt2                                    |    6.939s | 88.444MiB| unsat | 1 |  |  |
|queries-FStar.UInt64.smt2                                    |    7.121s | 91.484MiB| unsat | 1 |  |  |
|queries-LowStar.Endianness.smt2                              |    7.374s | 136.0MiB| unsat | 1 |  |  |
|queries-FStar.Monotonic.Heap.smt2                            |    7.619s | 91.584MiB| unsat | 1 |  |  |
|queries-FStar.Monotonic.HyperStack.smt2                      |    7.694s | 93.156MiB| unsat | 1 |  |  |
|queries-Steel.ST.Array.Util.smt2                             |    7.832s | 157.0MiB| unsat | 1 |  |  |
|queries-FStar.List.Tot.Properties.smt2                       |    7.844s | 84.54MiB| unsat | 1 |  |  |
|queries-FStar.Tactics.PatternMatching.smt2                   |    8.021s | 140.0MiB| unsat | 1 |  |  |
|queries-Steel.Channel.Simplex.smt2                           |    8.310s | 164.0MiB| unsat | 1 |  |  |
|queries-LowStar.BufferView.Up.smt2                           |    8.323s | 140.0MiB| unsat | 1 |  |  |
|queries-FStar.HyperStack.ST.smt2                             |    8.523s | 157.0MiB| unsat | 1 |  |  |
|queries-FStar.TaggedUnion.smt2                               |    8.912s | 147.0MiB| unknown | 1 |  |  |
|queries-LowStar.BufferView.smt2                              |    9.063s | 140.0MiB| unsat | 1 |  |  |
|queries-FStar.Seq.Permutation-1.smt2                         |    9.107s | 162.0MiB| unsat | 1 |  |  |
|queries-FStar.Sequence.Base.smt2                             |    9.492s | 97.312MiB| unsat | 1 |  |  |
|queries-FStar.BufferNG.smt2                                  |    9.686s | 145.0MiB| unsat | 1 |  |  |
|queries-FStar.Pointer.Base.smt2                              |   10.132s | 139.0MiB| unsat | 1 |  |  |
|queries-FStar.Matrix.smt2                                    |   10.133s | 101.0MiB| unsat | 1 |  |  |
|queries-FStar.Tactics.CanonCommSemiring.smt2                 |   10.449s | 141.0MiB| unsat | 1 |  |  |
|queries-FStar.Math.Lemmas.smt2                               |   10.656s | 73.984MiB| unsat | 1 |  |  |
|queries-FStar.Pointer.Derived1.smt2                          |   11.001s | 145.0MiB| unsat | 1 |  |  |
|queries-FStar.ModifiesGen-4.smt2                             |   11.054s | 153.0MiB| unsat | 1 |  |  |
|queries-LowStar.BufferView.Down.smt2                         |   11.545s | 140.0MiB| unsat | 1 |  |  |
|queries-Steel.Stepper.smt2                                   |   12.373s | 181.0MiB| unsat | 1 |  |  |
|queries-Steel.Array.smt2                                     |   12.737s | 318.0MiB| unsat | 1 |  |  |
|queries-Steel.Reference.smt2                                 |   13.055s | 157.0MiB| unsat | 1 |  |  |
|queries-FStar.ModifiesGen-1.smt2                             |   13.399s | 155.0MiB| unsat | 1 |  |  |
|queries-Steel.Memory.smt2                                    |   13.545s | 155.0MiB| unsat | 1 |  |  |
|queries-FStar.Modifies.smt2                                  |   14.807s | 144.0MiB| unsat | 1 |  |  |
|queries-Steel.Effect.smt2                                    |   14.930s | 303.0MiB| unsat | 1 |  |  |
|queries-Steel.Heap-1.smt2                                    |   16.493s | 201.0MiB| unknown | 1 |  |  |
|queries-Steel.FractionalAnchoredPreorder.smt2                |   16.705s | 176.0MiB| unsat | 1 |  |  |
|queries-Steel.HigherReference.smt2                           |   16.868s | 215.0MiB| unsat | 1 |  |  |
|queries-FStar.Int.Cast.smt2                                  |   17.435s | 133.0MiB| unsat | 1 |  |  |
|queries-FStar.Seq.Properties.smt2                            |   17.527s | 157.0MiB| unsat | 1 |  |  |
|queries-Steel.ST.EphemeralHashtbl.smt2                       |   19.664s | 312.0MiB| unsat | 1 |  |  |
|queries-FStar.Math.Fermat.smt2                               |   19.716s | 151.0MiB| unsat | 1 |  |  |
|queries-LowStar.Monotonic.Buffer.smt2                        |   20.025s | 146.0MiB| unsat | 0 |  |  |
|queries-Steel.Semantics.Hoare.MST.smt2                       |   20.032s | 230.0MiB| unsat | 0 |  |  |
|queries-FStar.ModifiesGen-5.smt2                             |   20.033s | 188.0MiB| unsat | 0 |  |  |
|queries-LowStar.Vector.smt2                                  |   20.035s | 163.0MiB| unsat | 0 |  |  |
|queries-Steel.MonotonicHigherReference.smt2                  |   20.042s | 340.0MiB| unsat | 0 |  |  |
|queries-FStar.Buffer.smt2                                    |   20.065s | 159.0MiB| unsat | 0 |  |  |
|queries-FStar.ModifiesGen-3.smt2                             |   20.071s | 175.0MiB| unsat | 0 |  |  |
|queries-FStar.Matrix-1.smt2                                  |   20.074s | 421.0MiB| unsat | 0 |  |  |
|queries-FStar.Int.smt2                                       |   20.105s | 177.0MiB| unsat | 0 |  |  |
|queries-FStar.UInt128.smt2                                   |   20.110s | 322.0MiB| unsat | 0 |  |  |
|queries-FStar.Sequence.Permutation.smt2                      |   20.112s | 431.0MiB| unsat | 0 |  |  |
|queries-FStar.UInt.smt2                                      |   20.113s | 163.0MiB| unsat | 0 |  |  |
|queries-Steel.Effect.Atomic.smt2                             |   20.120s | 299.0MiB| unsat | 0 |  |  |
|queries-FStar.ModifiesGen-7.smt2                             |   20.126s | 197.0MiB| unsat | 0 |  |  |
|queries-LowStar.RVector.smt2                                 |   20.132s | 164.0MiB| unsat | 0 |  |  |
|queries-FStar.Endianness.smt2                                |   20.134s | 160.0MiB| unsat | 0 |  |  |
|queries-FStar.ModifiesGen.smt2                               |   20.141s | 161.0MiB| unsat | 0 |  |  |
|queries-Steel.Heap.smt2                                      |   20.141s | 189.0MiB| unsat | 0 |  |  |
|queries-Steel.Effect.Common.smt2                             |   20.142s | 165.0MiB| unsat | 0 |  |  |
