Comparing data and data


# SUMMARY
- LHS tests = 2313
- RHS tests = 2313
- LHS success = 0  (0.0%)
- RHS success = 0  (0.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: qf-nia-small-pr9391-sandwich
Runner: rise-runner-1
Z3 repo: 1arie1/z3
Z3 commit: e1e6ee3efabdfbd2ba63742a8656a12cb42b45a9
Z3 branch: ag/mono-sandwich
Z3 options: "-T:30 arith.nl.monomial_sandwich=true"
Z3 inputs: inputs/QF_NIA_small
Z3 commit message: Add McCormick box-corner tangent points (Opportunity 2 from ord-binom doc)

When enabled via arith.nl.tangents.box_corners (default off, sub-flag of
arith.nl.tangents), tangent_imp::get_points selects m_a, m_b at the corners
of the bound box [x_lo, x_hi] × [y_lo, y_hi] instead of the model-centered
points val(x) ± delta. The selection follows the classical McCormick
under/over envelope:

  - m_below=true (under-approximation):
      m_a = (x_lo, y_lo),  m_b = (x_hi, y_hi)
  - m_below=false (over-approximation):
      m_a = (x_lo, y_hi),  m_b = (x_hi, y_lo)

The existing generate_plane already produces the McCormick linear form
xy ≷ pl.y·x + pl.x·y − pl.x·pl.y at any chosen point pl. push_point is
skipped in box-corner mode: corners are extremes, so doubling the offset
moves out of the box and would invalidate the McCormick property.

Falls back to the existing model-driven point selection when either factor
has an unbounded side or the box is degenerate (single-point in a
dimension).

Soundness — non-strict inequality at corners. The classical model-driven
flow uses pl strictly in the interior of the box, so generate_plane emits
xy > T (strict). At the box corners the tangent meets the surface along
the box's edges (xy = T when x = pl.x or y = pl.y), so the strict
inequality is violated by any model with x at the box boundary. A new
m_pl_strict_interior member, set false on a successful set_box_corners(),
switches generate_plane's emission to ≥/≤ (non-strict). The model-driven
path keeps strict — its push_point + plane_is_correct_cut chain already
guarantees pl is interior.

Validated via smt.arith.validate=true: 0 validate_conflict() failures
across the 32-leaf test corpus with box_corners=true.

Co-Authored-By: Claude Opus 4.7 (1M context) <noreply@anthropic.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: qf-nia-small-pr9391-sandwich
Runner: rise-runner-1
Z3 repo: 1arie1/z3
Z3 commit: e1e6ee3efabdfbd2ba63742a8656a12cb42b45a9
Z3 branch: ag/mono-sandwich
Z3 options: "-T:30 arith.nl.monomial_sandwich=true"
Z3 inputs: inputs/QF_NIA_small
Z3 commit message: Add McCormick box-corner tangent points (Opportunity 2 from ord-binom doc)

When enabled via arith.nl.tangents.box_corners (default off, sub-flag of
arith.nl.tangents), tangent_imp::get_points selects m_a, m_b at the corners
of the bound box [x_lo, x_hi] × [y_lo, y_hi] instead of the model-centered
points val(x) ± delta. The selection follows the classical McCormick
under/over envelope:

  - m_below=true (under-approximation):
      m_a = (x_lo, y_lo),  m_b = (x_hi, y_hi)
  - m_below=false (over-approximation):
      m_a = (x_lo, y_hi),  m_b = (x_hi, y_lo)

The existing generate_plane already produces the McCormick linear form
xy ≷ pl.y·x + pl.x·y − pl.x·pl.y at any chosen point pl. push_point is
skipped in box-corner mode: corners are extremes, so doubling the offset
moves out of the box and would invalidate the McCormick property.

Falls back to the existing model-driven point selection when either factor
has an unbounded side or the box is degenerate (single-point in a
dimension).

Soundness — non-strict inequality at corners. The classical model-driven
flow uses pl strictly in the interior of the box, so generate_plane emits
xy > T (strict). At the box corners the tangent meets the surface along
the box's edges (xy = T when x = pl.x or y = pl.y), so the strict
inequality is violated by any model with x at the box boundary. A new
m_pl_strict_interior member, set false on a successful set_box_corners(),
switches generate_plane's emission to ≥/≤ (non-strict). The model-driven
path keeps strict — its push_point + plane_is_correct_cut chain already
guarantees pl is interior.

Validated via smt.arith.validate=true: 0 validate_conflict() failures
across the 32-leaf test corpus with box_corners=true.

Co-Authored-By: Claude Opus 4.7 (1M context) <noreply@anthropic.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|aproveSMT2180870078806303650.smt2                                                          |   0.046s |1616.0KiB|
|aproveSMT3496695621216907819.smt2                                                          |   0.039s |1864.0KiB|
|Stroeder_15__Lobnya-Boolean-Reordered_true-termination.c__p24120_terminationG_0.smt2       |   0.036s |1620.0KiB|
|From_T2__apchild-live.t2_fixed__p16480_terminationG_0.smt2                                 |   0.022s |1864.0KiB|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2859_safety_0.smt2                   |   0.021s |1620.0KiB|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__p1682_edge_closing_0.smt2             |   0.018s |1860.0KiB|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5085_safety_0.smt2                          |   0.018s |1564.0KiB|
|aproveSMT5056627952338669338.smt2                                                          |   0.016s |1664.0KiB|
|1689.smt2                                                                                  |   0.016s |1664.0KiB|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26531_safety_0.smt2                                      |   0.015s |1572.0KiB|
|From_T2__s1-striped.t2__p13058_safety_0.smt2                                               |   0.014s |1468.0KiB|
|From_AProVE_2014__Main.jar-obl-11__terminationS_13_0.smt2                                  |   0.014s |1652.0KiB|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7163_safety_0.smt2                      |   0.014s |1492.0KiB|
|From_T2__s1-striped.t2_fixed__p11293_safety_0.smt2                                         |   0.013s |1616.0KiB|
|989.smt2                                                                                   |   0.013s |1612.0KiB|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_28_0.smt2                          |   0.013s |1616.0KiB|
|181.smt2                                                                                   |   0.013s |1648.0KiB|
|364.smt2                                                                                   |   0.013s |1656.0KiB|
|aproveSMT7048666801337573956.smt2                                                          |   0.013s |1540.0KiB|
|1188.smt2                                                                                  |   0.013s |1616.0KiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|aproveSMT2180870078806303650.smt2                                                          |   0.046s |1616.0KiB|
|aproveSMT3496695621216907819.smt2                                                          |   0.039s |1864.0KiB|
|Stroeder_15__Lobnya-Boolean-Reordered_true-termination.c__p24120_terminationG_0.smt2       |   0.036s |1620.0KiB|
|From_T2__apchild-live.t2_fixed__p16480_terminationG_0.smt2                                 |   0.022s |1864.0KiB|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2859_safety_0.smt2                   |   0.021s |1620.0KiB|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__p1682_edge_closing_0.smt2             |   0.018s |1860.0KiB|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5085_safety_0.smt2                          |   0.018s |1564.0KiB|
|aproveSMT5056627952338669338.smt2                                                          |   0.016s |1664.0KiB|
|1689.smt2                                                                                  |   0.016s |1664.0KiB|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26531_safety_0.smt2                                      |   0.015s |1572.0KiB|
|From_T2__s1-striped.t2__p13058_safety_0.smt2                                               |   0.014s |1468.0KiB|
|From_AProVE_2014__Main.jar-obl-11__terminationS_13_0.smt2                                  |   0.014s |1652.0KiB|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7163_safety_0.smt2                      |   0.014s |1492.0KiB|
|From_T2__s1-striped.t2_fixed__p11293_safety_0.smt2                                         |   0.013s |1616.0KiB|
|989.smt2                                                                                   |   0.013s |1612.0KiB|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_28_0.smt2                          |   0.013s |1616.0KiB|
|181.smt2                                                                                   |   0.013s |1648.0KiB|
|364.smt2                                                                                   |   0.013s |1656.0KiB|
|aproveSMT7048666801337573956.smt2                                                          |   0.013s |1540.0KiB|
|1188.smt2                                                                                  |   0.013s |1616.0KiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14280_terminationG_0.smt2            |   0.005s |1912.0KiB|
|From_AProVE_2014__ListContent.jar-obl-9__p10107_terminationG_0.smt2                        |   0.006s |1908.0KiB|
|From_T2__db3.t2_fixed__p18755_terminationG_0.smt2                                          |   0.004s |1904.0KiB|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24251_edge_closing_0.smt2          |   0.004s |1896.0KiB|
|1126.smt2                                                                                  |   0.004s |1896.0KiB|
|From_T2__small35.t2__p23984_terminationG_0.smt2                                            |   0.007s |1892.0KiB|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_14_0.smt2                                |   0.006s |1888.0KiB|
|From_T2__rlft3.t2__p9111_terminationG_0.smt2                                               |   0.009s |1884.0KiB|
|From_AProVE_2014__sumGeneric_rec.jar-obl-8__p12350_terminationG_0.smt2                     |   0.005s |1884.0KiB|
|From_T2__firewire.t2__p32294_terminationG_0.smt2                                           |   0.005s |1884.0KiB|
|aproveSMT5521985939949569030.smt2                                                          |   0.007s |1880.0KiB|
|aproveSMT4726660327701427.smt2                                                             |   0.006s |1876.0KiB|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32548_safety_0.smt2            |   0.006s |1872.0KiB|
|term-0BB4ks.smt2                                                                           |   0.011s |1868.0KiB|
|aproveSMT3496695621216907819.smt2                                                          |   0.039s |1864.0KiB|
|From_T2__apchild-live.t2_fixed__p16480_terminationG_0.smt2                                 |   0.022s |1864.0KiB|
|185.smt2                                                                                   |   0.012s |1864.0KiB|
|From_T2__n_firewire_instrumented-PP.t2__terminationS_6_0.smt2                              |   0.006s |1864.0KiB|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26899_terminationG_0.smt2                  |   0.006s |1864.0KiB|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7280_safety_0.smt2                      |   0.006s |1864.0KiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14280_terminationG_0.smt2            |   0.005s |1912.0KiB|
|From_AProVE_2014__ListContent.jar-obl-9__p10107_terminationG_0.smt2                        |   0.006s |1908.0KiB|
|From_T2__db3.t2_fixed__p18755_terminationG_0.smt2                                          |   0.004s |1904.0KiB|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24251_edge_closing_0.smt2          |   0.004s |1896.0KiB|
|1126.smt2                                                                                  |   0.004s |1896.0KiB|
|From_T2__small35.t2__p23984_terminationG_0.smt2                                            |   0.007s |1892.0KiB|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_14_0.smt2                                |   0.006s |1888.0KiB|
|From_T2__rlft3.t2__p9111_terminationG_0.smt2                                               |   0.009s |1884.0KiB|
|From_AProVE_2014__sumGeneric_rec.jar-obl-8__p12350_terminationG_0.smt2                     |   0.005s |1884.0KiB|
|From_T2__firewire.t2__p32294_terminationG_0.smt2                                           |   0.005s |1884.0KiB|
|aproveSMT5521985939949569030.smt2                                                          |   0.007s |1880.0KiB|
|aproveSMT4726660327701427.smt2                                                             |   0.006s |1876.0KiB|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32548_safety_0.smt2            |   0.006s |1872.0KiB|
|term-0BB4ks.smt2                                                                           |   0.011s |1868.0KiB|
|aproveSMT3496695621216907819.smt2                                                          |   0.039s |1864.0KiB|
|From_T2__apchild-live.t2_fixed__p16480_terminationG_0.smt2                                 |   0.022s |1864.0KiB|
|185.smt2                                                                                   |   0.012s |1864.0KiB|
|From_T2__n_firewire_instrumented-PP.t2__terminationS_6_0.smt2                              |   0.006s |1864.0KiB|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26899_terminationG_0.smt2                  |   0.006s |1864.0KiB|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7280_safety_0.smt2                      |   0.006s |1864.0KiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>
