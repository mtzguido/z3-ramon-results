# .

* SAT 167
* UNSAT 191
* TIMEOUT 5
* UNKNOWN 0

* UNSET 0

* ERROR 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-8-QF_LIA_hard-timeout10min-bb2
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: 7096c78fe0ae3a28e61b6fb0ae837cba65848d42
Z3 branch: fmcad26_artifact
Z3 options: "-T:600 -v:0 smt.threads=8 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_global_bb_batch_threads=2"
Z3 inputs: https://zenodo.org/records/16740866/files/QF_LIA.tar.zst?download=1
Z3 commit message: Final version of parallel architecture for FMCAD26 submission (#9475)

* setting up new backbone experiment

* fix phase scores bug

* debug crash from negated atoms

* backbone thread/global backbones in progress, does NOT compile yet

* debug, still need to add backbones worker as a new thread

* setting up complicated condition variable thing for backbones worker thread

* debug

* debug lock contention

* it's a little messy, but change how i'm checking backbones by initiating with batch check

* don't split on global backbones, share global backbones once detected. still need to prune search tree with backbones

* close global backbone branches in search tree

* fix backbone ranking (take average of bb age over cubes and incorporate hits/num cubes the bb appears in

* add stats to backbone experiment

* gate the backbones experiment by local vs global

* update stats and fix bug about unsat core size=1 means global backbone

* phase negation ablation

* unforce phase ablation

* reset ablations

* add todo notes

* fix backbone aging

* first draft of Janota Alg 7

* process exactly 10 bb candidates in each batch

* fixing the Janota algorithm

* add backbone stats for Janota algorithm

* fix bug about global backbones not being checked unless local is also true

* hopefully fix bug about closing global backbones in search tree

* fix another bug in janota alg

* report random seed for debug

* print random seed for debug

* refactor janota alg code, still can't repro the crash

* fix some bugs in the janota algorithm

* try to fix weird memory leak thing with ramon/linux

* revert fix, it didn't work

* add second backbones thread

* increase chunk size when undef

* fix how the 2 backbone threads work on batches (they each race to finish the same batch). this was very complicated to code due to thread synchronization and while it runs there may be bugs

* update how we report stats for backbones

* first draft of doing the bb threads in neg and pos mode, needs revising

* fix some bugs in the positive version of the bb check, still need to review

* debug some more things in the positive bb worker

* keep bb candidates sorted, increase batch and chunk size

* try to resolve a couple of bugs

* fix very bad bug about backbones workers not doing anything

* ablate positive backbone thread

* fix how we record backbones in positive mode (shouldn't impact previous run)

* clarify code about adding found backbones

* add back the positive bb thread

* try to fix the random segfault bug + ablate the postiive bb thread again

* clean up logs

* share clauses with bb threads

* fixes

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* resolve deadlock

* add comment about SAT bb case

* todo comments

* complete TODOs in code, still need to debug bb threads

* debug bb threads, add bb_positive thread back in

* ablate bb_positive thread

* style

* configure num bb threads as param

* enable sat and unsat mode

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* updates

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* remove while true

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* updates

* try to fix rewriter_exception bug

* possibly reduce code under lock when only 1 bb thread

* add some copilot-suggested optimizations

* add copilot suggestions to fix condition variable synchronization with bb threads

* revert changes that are too messy with the code

* ablate collect clauses

* ablate condition variable logic changes

* ablate reset batch

* revert ablation

* remove m_batch_in_progress that makes the bb threads wait until both have exited the batch after one signals cancel (can be long if one is stuck in ctx check)

* sharing theory lemmas

* finish setup for search tree thread modes, and fix local bb setup to pull from the global pool

* variable renames

* update bb hyperparams after copilot (hopefully??) ran tuning experiments

* fix possible AST manager bug

* ablate collect clauses

* remove bb collect shared clauses

* fix local bb experiment bug and reinstate collect clauses for global bb

* local bb cands are thread-local ablation

* remove thread-local local bb ablation

* fix bug in nonthread-local bb experiment

* fix more nonthreadlocal bb bugs

* try to fix local bb bug

* AST manager mismatch bugfix

* attempt to fix another canonicalization bug

* try another bugfix

* try another bugfix

* try yet another bugfix

* thread local bb ablation

* ablate force phase

* ablate set activity

* undo ablations since apparently it's not forcing phase or boosting activities

* remove old experiments

* try guarding m_birthdate size

* try to fix several bugs including with m_birthdate initialization and how we're storing original phases

* one more bugfix

* remove local bb experiment after negative signals on experiments, and change bb ranking to VSIDS scores as opposed to phase

* select bb polarity based on phase, not VSIDS

* first attempt with codex. Codex notes:
What changed:

  - Each tree node now tracks:
      - active worker count
      - lease epoch
      - cancel epoch
  - get_cube() now hands each worker an explicit lease: (node, epoch, cancel_epoch).
  - try_split() and backtrack() now operate on that lease, and the batch manager releases the worker’s lease under the tree lock before mutating the
    node.
  - If another worker closes the leased node or subtree, the batch manager cancels only the workers whose current leased nodes are now closed.
  - Workers detect canceled leases after check(), reset their local cancel flag, abandon the stale lease, and continue instead of turning that into a
    global exception.
  - The “reopen immediately into the open queue” policy is preserved. I did not add a barrier waiting for all workers on a node to finish.
  - Active-worker accounting is now separate from the open/active/closed scheduling status, so reopening a node no longer erases the fact that other
    workers are still on it.

  I also updated search_tree bookkeeping so:

  - closure bumps node cancel/lease epochs
  - active-node counting uses actual active-worker presence, not just status == active

* fix smts bugfix git merge issues with backtrack

* fix(parallel-smt): gate split/backtrack by lease epoch

What it changes:

  - util/search_tree.h
      - bumps node epoch on split
      - threads epoch through should_split(...) and try_split(...)
      - always records effort, but only split/reopen if the lease epoch still matches
  - smt/smt_parallel.cpp
      - requires is_lease_valid(..., lease.epoch) before backtrack(...)
      - passes lease.epoch into m_search_tree.try_split(...)

* clean up code and add some comments

* fix bug about backtracking condition being too strict: The epoch guard should not block backtrack(...) the same way it blocks try_split(...). A stale worker that proves UNSAT for n should still be able to
  close n, and that closure should then cancel the other workers on n and its subtree.

  I changed smt/smt_parallel.cpp accordingly:

  - try_split(...) still uses epoch to reject stale structural splits
  - backtrack(...) no longer requires is_lease_valid(..., epoch); it only requires that the lease is not already canceled

  So the intended asymmetry is now restored:

  - stale split: reject
  - stale unsat/backtrack: allow closure, then cancel affected workers

* ablate to no backtracking on stale leases

* fix merge

* revert codex change about exception handling

* fix linux bugs

* ablate backtrack gating

* attempt to fix linux crashes

* ablate backtracking on global bb

* the rare bb bug appears to be from creating the synthetic lease for a bb node and then backtracking on the synthetic lease. this is an attempt to fix it

* clean up code

* try to fix bug about active worker counts/lease accounting. current policy should hold: - stale leases: release/decrement
  - canceled leases: do not release/decrement (just ignore since we have an invariant that canceled leases mean closed nodes that are never revisited

* delay premature root activation

* fix major semantic bug about threads continually choosing the root if their lease is reset

* fix cancellation to unknown status

* fix very bad bug about all threads needing to start at the root

* ablate active ranking: now nodes are only reopened if they are truly inactive (active worker count is 0)

* fix some bugs about leases

* ablate adding static effort only

* fix some bugs about leases

* don't explode effort for portfolio nodes

* fix: still accumulate per-node effort, but don't over-accumulate on portfolio solves

* restore dynamically scaled effort

* clean up merge from cherry pick

* tighten which nodes we detect for proven global bb closure (only detect nonclosed nodes)

* fix cancel to unknown exception on bb code

* lease cancellation doens't touch rlimit now, it just sets max conflicts to 0. also fix a VERY BAD BUG about effort never being updated until all leases are done on a node, which meant we never left the root

* cross-thread modification of max conflicts is unsafe, so create an atomic lease canceled variable that's ch
ecked in ctx where max conflicts is also checked

* move atomic lease check in the context to the more global get_cancel_flag function

* Fix new SIGSEV. issue: The root cause: get_cancel_flag() is called from within propagation loops (mid-BCP, mid-equality-propagation, mid-atom-propagation). When it returns true there, the solver exits early and leaves the context in an intermediate state —
  propagation queues partially processed, theory state potentially inconsistent with boolean state.

  For the global cancel (m.limit().cancel()), this is harmless: the worker exits entirely and the context is destroyed. Intermediate state doesn't matter.

  For a lease cancel, the context is reused — the worker gets a new cube and calls ctx->check() again on the same context object. Re-entering check() on a context interrupted mid-propagation causes it to access that corrupted intermediate
  state → SIGSEGV.

  The m_max_conflicts check is the only checkpoint that's safe for re-entry: it only fires post-conflict-resolution, pre-decision, when propagation queues are empty and theory state is consistent.

  Fix: Remove m_lease_canceled from get_cancel_flag(). Keep it only at safe, between-phase checkpoints where the context is in a known-consistent state. The result is two safe checkpoints for m_lease_canceled: after each conflict (post-resolution, queues empty) and before each theory final check (not yet entered the theory). Neither interrupts the solver mid-mutation. The SIGSEGV should be
   gone, and NIA performance should improve because long theory final checks (where NIA burns most time) are now preemptable before they start.

* fix new inconsistent theory bug: The problem is returning FC_GIVEUP from inside final_check() after some theories have already run final_check_eh() and pushed propagations into the queue. Those pending propagations reference context state that gets invalidated on the next check() call → SIGSEGV. The fix: check m_lease_canceled before entering final_check() in bounded_search(), never from inside it. That way the context is always in a clean pre-final-check state when we bail out. This is safe: decide() returned false (all variables assigned, no pending propagations), theories haven't been touched yet, context is in a fully consistent state. For NIA, this is still a meaningful win — we avoid entering expensive arithmetic final checks entirely when the lease is already canceled.

* ablate lease cancel check in ctx final theory check due to crash (??)

* gate bb-specific code behind param

* try some possible bugfixes for the sigsev

* ablate some bugfixes

* remove second lease cancel check in smt_context, not sure it's safe. only check where we do the max conflicts check

* restore exception handling logic to master branch

* restore reslimit cancels since the bug appears to be latent

* add bookkeeping for race condition of multiple lease cancels on a single node (messes with reslimit)

* restore unrelated code to master

* restore local bb experiment

* ablate restore local bb phase/activity after search

* undo local bb ablation about resetting phase/activities, and reinstate the shared lemmas of length 2 and 3 experiment

* re-ablate restore local bb phase/activity after search, due to positive experimental signal on smt comp LIA

* change split policy from lightweight proof skeleton to VSIDS. NOTE: enabling local bb will mess with this since we aren't restoring activities right now

* backtrack more aggressively in search tree: close matching external targets (i.e. repeat literals on other branches)

* find_shallowest_timed_out_leaf_depth is now shallowest_unsolved_leaf_depth and is based on num activations > 0, not effort > 0

* fix soundness bug about closing external targets with nontrivial cores

* epoch is no longer needed, just cancel epoch. remove epoch

* core minimize draft, and fix bug in tree expansion policy about shallowest leaf depth needing to be timed out

* core minimization thread (remove search tree worker core min since it was blocking)

* collect shared clauses in core min thread

* bugfixes in core min algorithm

* fix more bugs in core min algorithm

* more core min bugfixes based on feedback and increase m_core_minimize_conflict_budget to 5000 (might need to increase it more for harder SMT COMP problems)

* fix bug in backtrack_unlocked

* fix compiler error

* more core min bugfix from nikolaj

* clean up

* failed literal probe collects shared clauses

* core min thread shares units

* failed literal thread now tests the top 500 global bb cands each round, instead of scanning everything. on QF_LIA/Sz128_2823.smt2 this got us from 51->75 discovered backbones

* remove core minimizer unit sharing (experimentally showed no effect)

* core minimization thread candidate cores are ranked first by depth (deepest->shallowest) then by size (largest->smallest). also, the core's node is set to the deepest node in the core which is not necessarily the search node (slightly semantically stronger). finally, clean up bb/failed literal params

* failed literal probe runs continuously

* fix a lot of things about the FL thread and how bb cands are being processed. also re-add the local bb experiment for ablations

* ablate continuous run on FL thread (up to the max BM examples

* ablate m_max_failed_literal_prioritized_size back to 100

* redesign FL probe again

* ablate FL continuous probe

* reinstate continuous FL probe after positive NIA signal, but also re-add the BM maintaining 1000 bb cands and these are used a
s backups instead of just looping over the top 100 all the time

* change FL thread scheduling to attempt to do less duplicate checks

* restore some old FL behavior

* batch manager dedups global bb cands by atoms, not literals. if we have 2 of the same atom, the polarity with higher rank is kept for the stored bb candidate literal.

* ablations

* reinstate FL check for new batch with epochs, before merge, this is a temp branch

* undo comment out cv call

* restore old changes

* bb batch mode is continuous, with checks for new candidates after the first round

* separate FL probe into 2 threads for pos and neg mode

* attempt to add unit-based bb detection in chunking mode

* add bb detection via workers' units. also rename some variables

* modify the fallback policies for bb detection in batch mode but also in FL mode

* ablate continuous checking for batch bb mode

* major refactor for bb code. we share units and collect them as pruning bb's in all threads now (including core min and bb threads). we always check for units in batch mode now. finally, the batch mode fallback is now FL probing

* bb candidates are atoms, not literals, since we currently test both polarities in parallel.
batch mode retry terminates if we made zero progress after a retry round to avoid resource stress
fix bug about bb ranking being backwards for how we process them

* fix polarity bug for FL mode dedup

* restore polarity-sensitive bb candidate ranking via lits

* ablate sharing non-worker units

* ablate share unit as bb

* ablate incomplete-theory give-up paths

* restore unit sharing as bb collection on workers

* restore incomplete-theory give-up paths

* clean up code

* clean up code

* clean up code

---------

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>
Co-authored-by: Ilana Shapiro <ilanashapiro@Ilanas-MacBook-Pro.local>
Co-authored-by: Ilana Shapiro <ilanashapiro@Ilanas-MBP.lan1>
Co-authored-by: Nikolaj Bjorner <nbjorner@microsoft.com>
Co-authored-by: Ilana Shapiro <ilanashapiro@Mac.localdomain>
Co-authored-by: Ilana Shapiro <ilanashapiro@Ilanas-MBP.localdomain>
Co-authored-by: Ilana Shapiro <ilanashapiro@Mac.lan1>

</pre>


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|prp-1-46.smt2                                                |    0.268s | 208.0MiB| unsat | 0 |  |  |
|prp-21-46.smt2                                               |    0.275s | 208.0MiB| unsat | 0 |  |  |
|prp-22-46.smt2                                               |    0.283s | 209.0MiB| unsat | 0 |  |  |
|prp-13-46.smt2                                               |    0.290s | 208.0MiB| unsat | 0 |  |  |
|prp-43-46.smt2                                               |    0.297s | 208.0MiB| unsat | 0 |  |  |
|prp-11-47.smt2                                               |    0.300s | 208.0MiB| unsat | 0 |  |  |
|prp-16-47.smt2                                               |    0.302s | 208.0MiB| unsat | 0 |  |  |
|prp-15-48.smt2                                               |    0.305s | 208.0MiB| unsat | 0 |  |  |
|prp-32-47.smt2                                               |    0.305s | 208.0MiB| unsat | 0 |  |  |
|prp-31-47.smt2                                               |    0.308s | 208.0MiB| unsat | 0 |  |  |
|prp-23-47.smt2                                               |    0.310s | 208.0MiB| unsat | 0 |  |  |
|prp-13-47.smt2                                               |    0.312s | 208.0MiB| unsat | 0 |  |  |
|terminator_02-1-O0.smt2                                      |    0.312s | 235.0MiB| sat | 0 |  |  |
|prp-22-47.smt2                                               |    0.314s | 208.0MiB| unsat | 0 |  |  |
|prp-5-47.smt2                                                |    0.316s | 208.0MiB| unsat | 0 |  |  |
|prp-38-47.smt2                                               |    0.316s | 208.0MiB| unsat | 0 |  |  |
|prp-20-47.smt2                                               |    0.317s | 208.0MiB| unsat | 0 |  |  |
|prp-3-47.smt2                                                |    0.318s | 208.0MiB| unsat | 0 |  |  |
|prp-15-47.smt2                                               |    0.321s | 208.0MiB| unsat | 0 |  |  |
|prp-23-48.smt2                                               |    0.323s | 209.0MiB| unsat | 0 |  |  |
|prp-31-46.smt2                                               |    0.323s | 208.0MiB| unsat | 0 |  |  |
|prp-25-49.smt2                                               |    0.331s | 210.0MiB| unsat | 0 |  |  |
|prp-14-48.smt2                                               |    0.332s | 208.0MiB| unsat | 0 |  |  |
|prp-44-48.smt2                                               |    0.332s | 209.0MiB| unsat | 0 |  |  |
|prp-10-48.smt2                                               |    0.333s | 209.0MiB| unsat | 0 |  |  |
|prp-1-48.smt2                                                |    0.337s | 209.0MiB| unsat | 0 |  |  |
|prp-3-48.smt2                                                |    0.340s | 209.0MiB| unsat | 0 |  |  |
|prp-37-48.smt2                                               |    0.341s | 209.0MiB| unsat | 0 |  |  |
|prp-40-48.smt2                                               |    0.344s | 208.0MiB| unsat | 0 |  |  |
|FISCHER4-7-fair.smt2                                         |    0.346s | 224.0MiB| unsat | 0 |  |  |
|prp-19-49.smt2                                               |    0.361s | 209.0MiB| unsat | 0 |  |  |
|prp-31-49.smt2                                               |    0.370s | 209.0MiB| unsat | 0 |  |  |
|FISCHER4-8-fair.smt2                                         |    0.372s | 228.0MiB| unsat | 0 |  |  |
|prp-20-49.smt2                                               |    0.374s | 208.0MiB| unsat | 0 |  |  |
|prp-49-49.smt2                                               |    0.375s | 208.0MiB| unsat | 0 |  |  |
|prp-37-49.smt2                                               |    0.384s | 209.0MiB| unsat | 0 |  |  |
|prp-41-49.smt2                                               |    0.387s | 209.0MiB| unsat | 0 |  |  |
|FISCHER4-9-fair.smt2                                         |    0.388s | 228.0MiB| sat | 0 |  |  |
|prp-19-50.smt2                                               |    0.392s | 209.0MiB| unsat | 0 |  |  |
|prp-39-50.smt2                                               |    0.393s | 210.0MiB| unsat | 0 |  |  |
|FISCHER9-4-fair.smt2                                         |    0.397s | 229.0MiB| unsat | 0 |  |  |
|prp-3-50.smt2                                                |    0.415s | 210.0MiB| unsat | 0 |  |  |
|prp-11-50.smt2                                               |    0.416s | 210.0MiB| unsat | 0 |  |  |
|prp-43-50.smt2                                               |    0.417s | 209.0MiB| unsat | 0 |  |  |
|prp-5-50.smt2                                                |    0.420s | 210.0MiB| unsat | 0 |  |  |
|prp-12-50.smt2                                               |    0.421s | 210.0MiB| unsat | 0 |  |  |
|prp-9-50.smt2                                                |    0.425s | 209.0MiB| unsat | 0 |  |  |
|ParallelPrefixSum_safe_bgmc006.smt2                          |    0.426s | 247.0MiB| sat | 0 |  |  |
|prp-55-50.smt2                                               |    0.427s | 209.0MiB| unsat | 0 |  |  |
|FISCHER9-5-fair.smt2                                         |    0.446s | 235.0MiB| unsat | 0 |  |  |
|FISCHER11-5-fair.smt2                                        |    0.465s | 239.0MiB| unsat | 0 |  |  |
|prp-54-46.smt2                                               |    0.476s | 212.0MiB| unsat | 0 |  |  |
|ParallelPrefixSum_safe_blmc002.smt2                          |    0.485s | 252.0MiB| unsat | 0 |  |  |
|prp-57-48.smt2                                               |    0.520s | 212.0MiB| unsat | 0 |  |  |
|prp-54-47.smt2                                               |    0.521s | 212.0MiB| unsat | 0 |  |  |
|convert-jpg2gif-query-1372.smt2                              |    0.531s | 262.0MiB| sat | 0 |  |  |
|FISCHER8-7-fair.smt2                                         |    0.536s | 242.0MiB| unsat | 0 |  |  |
|convert-jpg2gif-query-1379.smt2                              |    0.544s | 263.0MiB| sat | 0 |  |  |
|prp-59-48.smt2                                               |    0.544s | 212.0MiB| unsat | 0 |  |  |
|convert-jpg2gif-query-1453.smt2                              |    0.574s | 274.0MiB| sat | 0 |  |  |
|convert-jpg2gif-query-1423.smt2                              |    0.582s | 272.0MiB| sat | 0 |  |  |
|convert-jpg2gif-query-1441.smt2                              |    0.584s | 273.0MiB| sat | 0 |  |  |
|convert-jpg2gif-query-1420.smt2                              |    0.585s | 272.0MiB| sat | 0 |  |  |
|prp-55-48.smt2                                               |    0.607s | 212.0MiB| unsat | 0 |  |  |
|prp-54-50.smt2                                               |    0.612s | 213.0MiB| unsat | 0 |  |  |
|convert-jpg2gif-query-1445.smt2                              |    0.619s | 274.0MiB| sat | 0 |  |  |
|RC-07.smt2                                                   |    0.620s | 309.0MiB| sat | 0 |  |  |
|RC-11.smt2                                                   |    0.621s | 309.0MiB| sat | 0 |  |  |
|convert-jpg2gif-query-1432.smt2                              |    0.640s | 273.0MiB| sat | 0 |  |  |
|RC-04.smt2                                                   |    0.646s | 303.0MiB| sat | 0 |  |  |
|RF-08.smt2                                                   |    0.649s | 299.0MiB| sat | 0 |  |  |
|RC-06.smt2                                                   |    0.659s | 307.0MiB| sat | 0 |  |  |
|RC-10.smt2                                                   |    0.664s | 301.0MiB| sat | 0 |  |  |
|RF-04.smt2                                                   |    0.677s | 308.0MiB| sat | 0 |  |  |
|RF-07.smt2                                                   |    0.678s | 299.0MiB| sat | 0 |  |  |
|RF-01.smt2                                                   |    0.682s | 303.0MiB| sat | 0 |  |  |
|convert-jpg2gif-query-1475.smt2                              |    0.704s | 281.0MiB| sat | 0 |  |  |
|RC-12.smt2                                                   |    0.709s | 315.0MiB| unsat | 0 |  |  |
|convert-jpg2gif-query-1484.smt2                              |    0.719s | 288.0MiB| sat | 0 |  |  |
|RF-05.smt2                                                   |    0.727s | 327.0MiB| sat | 0 |  |  |
|RC-01.smt2                                                   |    0.730s | 337.0MiB| sat | 0 |  |  |
|convert-jpg2gif-query-1497.smt2                              |    0.732s | 290.0MiB| sat | 0 |  |  |
|RC-03.smt2                                                   |    0.733s | 299.0MiB| unsat | 0 |  |  |
|RC-13.smt2                                                   |    0.733s | 332.0MiB| sat | 0 |  |  |
|RF-10.smt2                                                   |    0.740s | 318.0MiB| unsat | 0 |  |  |
|RF-14.smt2                                                   |    0.742s | 330.0MiB| sat | 0 |  |  |
|RF-09.smt2                                                   |    0.748s | 300.0MiB| unsat | 0 |  |  |
|RF-00.smt2                                                   |    0.757s | 328.0MiB| sat | 0 |  |  |
|convert-jpg2gif-query-1523.smt2                              |    0.777s | 300.0MiB| sat | 0 |  |  |
|RF-03.smt2                                                   |    0.786s | 345.0MiB| sat | 0 |  |  |
|30_30_18_5_sat.smt2                                          |    0.833s | 317.0MiB| sat | 0 |  |  |
|prp-16-46.smt2                                               |    0.834s | 224.0MiB| unsat | 0 |  |  |
|prp-57-46.smt2                                               |    0.856s | 223.0MiB| unsat | 0 |  |  |
|prp-24-46.smt2                                               |    0.866s | 224.0MiB| unsat | 0 |  |  |
|RC-05.smt2                                                   |    0.887s | 334.0MiB| unsat | 0 |  |  |
|convert-jpg2gif-query-1474.smt2                              |    0.888s | 281.0MiB| sat | 0 |  |  |
|prp-47-46.smt2                                               |    0.892s | 224.0MiB| unsat | 0 |  |  |
|prp-4-46.smt2                                                |    0.894s | 224.0MiB| unsat | 0 |  |  |
|prp-25-43.smt2                                               |    0.901s | 253.0MiB| unsat | 0 |  |  |
|convert-jpg2gif-query-1533.smt2                              |    0.909s | 303.0MiB| sat | 0 |  |  |
|convert-jpg2gif-query-1555.smt2                              |    0.944s | 307.0MiB| sat | 0 |  |  |
|prp-17-47.smt2                                               |    0.958s | 227.0MiB| unsat | 0 |  |  |
|prp-57-47.smt2                                               |    0.967s | 228.0MiB| unsat | 0 |  |  |
|convert-jpg2gif-query-1607.smt2                              |    0.973s | 313.0MiB| sat | 0 |  |  |
|convert-jpg2gif-query-1581.smt2                              |    0.997s | 311.0MiB| sat | 0 |  |  |
|RC-00.smt2                                                   |    1.019s | 370.0MiB| sat | 0 |  |  |
|prp-29-47.smt2                                               |    1.026s | 227.0MiB| unsat | 0 |  |  |
|RF-12.smt2                                                   |    1.027s | 375.0MiB| sat | 0 |  |  |
|convert-jpg2gif-query-1546.smt2                              |    1.032s | 308.0MiB| sat | 0 |  |  |
|RC-14.smt2                                                   |    1.037s | 372.0MiB| sat | 0 |  |  |
|prp-18-47.smt2                                               |    1.041s | 227.0MiB| unsat | 0 |  |  |
|convert-jpg2gif-query-1609.smt2                              |    1.043s | 314.0MiB| sat | 0 |  |  |
|convert-jpg2gif-query-1598.smt2                              |    1.054s | 312.0MiB| sat | 0 |  |  |
|RC-15.smt2                                                   |    1.067s | 365.0MiB| sat | 0 |  |  |
|RF-02.smt2                                                   |    1.078s | 462.0MiB| unsat | 0 |  |  |
|RF-06.smt2                                                   |    1.109s | 366.0MiB| sat | 0 |  |  |
|p2756.sat.smt2                                               |    1.325s | 384.0MiB| sat | 0 |  |  |
|50_50_45_12_sat.smt2                                         |    1.453s | 419.0MiB| sat | 0 |  |  |
|prp-28-46.smt2                                               |    1.504s | 278.0MiB| sat | 0 |  |  |
|prp-35-39.smt2                                               |    1.509s | 288.0MiB| unsat | 0 |  |  |
|RC-02.smt2                                                   |    1.512s | 493.0MiB| sat | 0 |  |  |
|RF-13.smt2                                                   |    1.519s | 560.0MiB| sat | 0 |  |  |
|prp-33-38.smt2                                               |    1.540s | 305.0MiB| unsat | 0 |  |  |
|RF-11.smt2                                                   |    1.589s | 518.0MiB| sat | 0 |  |  |
|prp-33-46.smt2                                               |    1.704s | 281.0MiB| sat | 0 |  |  |
|prp-41-38.smt2                                               |    1.824s | 312.0MiB| unsat | 0 |  |  |
|prp-37-40.smt2                                               |    1.848s | 304.0MiB| unsat | 0 |  |  |
|prp-33-47.smt2                                               |    1.893s | 292.0MiB| unsat | 0 |  |  |
|prp-41-39.smt2                                               |    1.947s | 321.0MiB| unsat | 0 |  |  |
|prp-9-47.smt2                                                |    2.007s | 358.0MiB| sat | 0 |  |  |
|FISCHER8-11-fair.smt2                                        |    2.044s | 277.0MiB| unsat | 0 |  |  |
|prp-27-39.smt2                                               |    2.139s | 323.0MiB| unsat | 0 |  |  |
|constraint-396616.smt2                                       |    2.167s | 654.0MiB| sat | 0 |  |  |
|prp-11-46.smt2                                               |    2.182s | 345.0MiB| unsat | 0 |  |  |
|prp-2-47.smt2                                                |    2.229s | 376.0MiB| sat | 0 |  |  |
|prp-19-47.smt2                                               |    2.420s | 372.0MiB| unsat | 0 |  |  |
|constraint-463860.smt2                                       |    2.428s | 769.0MiB| sat | 0 |  |  |
|Example_16.txt.smt2                                          |    2.773s | 277.0MiB| sat | 0 |  |  |
|prp-42-43.smt2                                               |    2.992s | 377.0MiB| unsat | 0 |  |  |
|constraint-187292.smt2                                       |    2.994s | 546.0MiB| sat | 0 |  |  |
|prp-7-48.smt2                                                |    3.015s | 390.0MiB| unsat | 0 |  |  |
|prp-57-49.smt2                                               |    3.066s | 335.0MiB| sat | 0 |  |  |
|prp-25-50.smt2                                               |    3.080s | 339.0MiB| sat | 0 |  |  |
|prp-27-42.smt2                                               |    3.137s | 360.0MiB| unsat | 0 |  |  |
|prp-4-47.smt2                                                |    3.159s | 403.0MiB| unsat | 0 |  |  |
|prp-58-50.smt2                                               |    3.201s | 332.0MiB| sat | 0 |  |  |
|RC-09.smt2                                                   |    3.273s | 787.0MiB| unsat | 0 |  |  |
|prp-32-39.smt2                                               |    3.309s | 385.0MiB| unsat | 0 |  |  |
|prp-18-48.smt2                                               |    3.321s | 404.0MiB| unsat | 0 |  |  |
|prp-11-32.smt2                                               |    3.352s | 358.0MiB| sat | 0 |  |  |
|prp-1-49.smt2                                                |    3.383s | 337.0MiB| sat | 0 |  |  |
|prp-43-42.smt2                                               |    3.462s | 350.0MiB| unsat | 0 |  |  |
|prp-15-33.smt2                                               |    3.471s | 356.0MiB| sat | 0 |  |  |
|prp-24-50.smt2                                               |    3.507s | 396.0MiB| unsat | 0 |  |  |
|prp-42-40.smt2                                               |    3.679s | 422.0MiB| sat | 0 |  |  |
|prp-5-35.smt2                                                |    3.687s | 366.0MiB| sat | 0 |  |  |
|prp-63-50.smt2                                               |    3.707s | 354.0MiB| unsat | 0 |  |  |
|prp-13-33.smt2                                               |    3.747s | 391.0MiB| sat | 0 |  |  |
|prp-35-42.smt2                                               |    3.758s | 406.0MiB| unsat | 0 |  |  |
|constraint-390915.smt2                                       |    3.861s | 796.0MiB| sat | 0 |  |  |
|prp-29-50.smt2                                               |    3.906s | 379.0MiB| unsat | 0 |  |  |
|prp-17-33.smt2                                               |    3.940s | 411.0MiB| sat | 0 |  |  |
|prp-6-48.smt2                                                |    3.945s | 406.0MiB| unsat | 0 |  |  |
|prp-26-32.smt2                                               |    4.103s | 403.0MiB| sat | 0 |  |  |
|prp-22-50.smt2                                               |    4.105s | 424.0MiB| unsat | 0 |  |  |
|prp-30-31.smt2                                               |    4.150s | 410.0MiB| unsat | 0 |  |  |
|prp-11-49.smt2                                               |    4.175s | 420.0MiB| unsat | 0 |  |  |
|Example_12.txt.smt2                                          |    4.200s | 254.0MiB| sat | 0 |  |  |
|prp-1-198.smt2                                               |    4.263s | 669.0MiB| unsat | 0 |  |  |
|prp-20-50.smt2                                               |    4.308s | 397.0MiB| unsat | 0 |  |  |
|prp-60-46.smt2                                               |    4.330s | 238.0MiB| unsat | 0 |  |  |
|prp-8-50.smt2                                                |    4.356s | 340.0MiB| unsat | 0 |  |  |
|prp-19-33.smt2                                               |    4.374s | 406.0MiB| sat | 0 |  |  |
|prp-8-34.smt2                                                |    4.375s | 401.0MiB| sat | 0 |  |  |
|prp-31-32.smt2                                               |    4.377s | 428.0MiB| sat | 0 |  |  |
|prp-60-47.smt2                                               |    4.684s | 263.0MiB| unsat | 0 |  |  |
|prp-7-35.smt2                                                |    4.817s | 396.0MiB| sat | 0 |  |  |
|prp-17-34.smt2                                               |    4.842s | 436.0MiB| sat | 0 |  |  |
|constraint-649834.smt2                                       |    5.119s | 1242.0MiB| sat | 0 |  |  |
|prp-30-32.smt2                                               |    5.208s | 484.0MiB| sat | 0 |  |  |
|prp-35-44.smt2                                               |    5.252s | 431.0MiB| unsat | 0 |  |  |
|prp-7-37.smt2                                                |    5.256s | 415.0MiB| sat | 0 |  |  |
|prp-62-47.smt2                                               |    5.532s | 263.0MiB| unsat | 0 |  |  |
|prp-36-45.smt2                                               |    5.681s | 414.0MiB| unsat | 0 |  |  |
|prp-42-42.smt2                                               |    5.901s | 452.0MiB| unsat | 0 |  |  |
|prp-63-48.smt2                                               |    6.072s | 266.0MiB| unsat | 0 |  |  |
|prp-20-35.smt2                                               |    6.083s | 466.0MiB| sat | 0 |  |  |
|prp-0-47.smt2                                                |    6.395s | 499.0MiB| unsat | 0 |  |  |
|prp-48-46.smt2                                               |    6.975s | 558.0MiB| unsat | 0 |  |  |
|prp-8-36.smt2                                                |    7.409s | 456.0MiB| sat | 0 |  |  |
|constraint-178902.smt2                                       |    7.456s | 558.0MiB| sat | 0 |  |  |
|constraint-679470.smt2                                       |    7.560s | 1428.0MiB| sat | 0 |  |  |
|prp-17-40.smt2                                               |    7.802s | 464.0MiB| sat | 0 |  |  |
|prp-53-45.smt2                                               |    8.014s | 523.0MiB| unsat | 0 |  |  |
|prp-12-48.smt2                                               |    8.288s | 458.0MiB| sat | 0 |  |  |
|prp-10-32.smt2                                               |    8.449s | 498.0MiB| unsat | 0 |  |  |
|prp-73-50.smt2                                               |    8.479s | 304.0MiB| unsat | 0 |  |  |
|prp-47-47.smt2                                               |    8.657s | 535.0MiB| unsat | 0 |  |  |
|prp-22-38.smt2                                               |    8.663s | 534.0MiB| sat | 0 |  |  |
|prp-28-36.smt2                                               |    8.777s | 570.0MiB| sat | 0 |  |  |
|prp-52-47.smt2                                               |    9.010s | 614.0MiB| unsat | 0 |  |  |
|prp-27-35.smt2                                               |    9.067s | 576.0MiB| sat | 0 |  |  |
|prp-8-38.smt2                                                |    9.769s | 479.0MiB| sat | 0 |  |  |
|prp-18-40.smt2                                               |   10.050s | 495.0MiB| sat | 0 |  |  |
|prp-29-36.smt2                                               |   10.068s | 719.0MiB| sat | 0 |  |  |
|prp-62-49.smt2                                               |   10.096s | 479.0MiB| unsat | 0 |  |  |
|prp-20-46.smt2                                               |   10.274s | 571.0MiB| sat | 0 |  |  |
|prp-31-39.smt2                                               |   10.457s | 583.0MiB| sat | 0 |  |  |
|prp-48-47.smt2                                               |   10.547s | 967.0MiB| unsat | 0 |  |  |
|prp-22-40.smt2                                               |   10.632s | 614.0MiB| sat | 0 |  |  |
|prp-40-37.smt2                                               |   11.087s | 449.0MiB| unsat | 0 |  |  |
|prp-17-41.smt2                                               |   11.131s | 540.0MiB| sat | 0 |  |  |
|prp-51-46.smt2                                               |   11.152s | 594.0MiB| unsat | 0 |  |  |
|prp-20-42.smt2                                               |   11.174s | 565.0MiB| sat | 0 |  |  |
|prp-12-49.smt2                                               |   11.179s | 472.0MiB| sat | 0 |  |  |
|prp-42-46.smt2                                               |   11.372s | 585.0MiB| unsat | 0 |  |  |
|prp-13-41.smt2                                               |   11.452s | 535.0MiB| sat | 0 |  |  |
|prp-40-46.smt2                                               |   11.454s | 628.0MiB| unsat | 0 |  |  |
|prp-0-46.smt2                                                |   11.460s | 619.0MiB| unsat | 0 |  |  |
|prp-26-41.smt2                                               |   12.231s | 655.0MiB| sat | 0 |  |  |
|prp-58-46.smt2                                               |   12.386s | 654.0MiB| unsat | 0 |  |  |
|prp-30-47.smt2                                               |   12.506s | 642.0MiB| sat | 0 |  |  |
|prp-14-44.smt2                                               |   12.593s | 682.0MiB| sat | 0 |  |  |
|prp-4-50.smt2                                                |   12.658s | 672.0MiB| unsat | 0 |  |  |
|prp-24-39.smt2                                               |   12.971s | 718.0MiB| sat | 0 |  |  |
|prp-18-42.smt2                                               |   13.718s | 623.0MiB| sat | 0 |  |  |
|prp-52-50.smt2                                               |   13.749s | 736.0MiB| unsat | 0 |  |  |
|prp-34-40.smt2                                               |   13.883s | 682.0MiB| sat | 0 |  |  |
|prp-30-40.smt2                                               |   13.932s | 734.0MiB| sat | 0 |  |  |
|prp-12-47.smt2                                               |   14.130s | 769.0MiB| sat | 0 |  |  |
|prp-22-42.smt2                                               |   14.159s | 695.0MiB| sat | 0 |  |  |
|prp-7-41.smt2                                                |   14.373s | 622.0MiB| sat | 0 |  |  |
|prp-33-42.smt2                                               |   14.417s | 645.0MiB| sat | 0 |  |  |
|prp-40-47.smt2                                               |   14.489s | 702.0MiB| sat | 0 |  |  |
|prp-67-47.smt2                                               |   14.590s | 704.0MiB| unsat | 0 |  |  |
|prp-49-47.smt2                                               |   14.765s | 778.0MiB| unsat | 0 |  |  |
|prp-9-49.smt2                                                |   14.850s | 666.0MiB| sat | 0 |  |  |
|prp-7-44.smt2                                                |   15.163s | 620.0MiB| sat | 0 |  |  |
|prp-37-42.smt2                                               |   15.241s | 630.0MiB| sat | 0 |  |  |
|prp-24-48.smt2                                               |   15.758s | 849.0MiB| sat | 0 |  |  |
|prp-5-48.smt2                                                |   15.864s | 728.0MiB| sat | 0 |  |  |
|prp-46-47.smt2                                               |   15.916s | 637.0MiB| unsat | 0 |  |  |
|prp-41-48.smt2                                               |   16.709s | 767.0MiB| sat | 0 |  |  |
|prp-21-48.smt2                                               |   16.766s | 826.0MiB| sat | 0 |  |  |
|prp-36-40.smt2                                               |   16.904s | 712.0MiB| sat | 0 |  |  |
|prp-2-199.smt2                                               |   17.504s | 1323.0MiB| sat | 0 |  |  |
|prp-21-49.smt2                                               |   17.633s | 788.0MiB| sat | 0 |  |  |
|prp-65-48.smt2                                               |   18.192s | 802.0MiB| unsat | 0 |  |  |
|prp-44-39.smt2                                               |   18.396s | 791.0MiB| unsat | 0 |  |  |
|prp-5-46.smt2                                                |   18.639s | 852.0MiB| unsat | 0 |  |  |
|prp-30-49.smt2                                               |   18.789s | 917.0MiB| sat | 0 |  |  |
|prp-5-49.smt2                                                |   18.863s | 813.0MiB| sat | 0 |  |  |
|prp-58-48.smt2                                               |   18.910s | 748.0MiB| unsat | 0 |  |  |
|prp-18-49.smt2                                               |   19.454s | 928.0MiB| sat | 0 |  |  |
|prp-26-47.smt2                                               |   19.801s | 803.0MiB| unsat | 0 |  |  |
|prp-52-48.smt2                                               |   19.841s | 820.0MiB| unsat | 0 |  |  |
|prp-42-41.smt2                                               |   20.062s | 651.0MiB| unsat | 0 |  |  |
|prp-4-42.smt2                                                |   20.096s | 736.0MiB| sat | 0 |  |  |
|prp-47-41.smt2                                               |   20.166s | 842.0MiB| unsat | 0 |  |  |
|prp-26-44.smt2                                               |   20.257s | 802.0MiB| sat | 0 |  |  |
|prp-41-47.smt2                                               |   20.316s | 826.0MiB| unsat | 0 |  |  |
|prp-75-48.smt2                                               |   20.384s | 800.0MiB| unsat | 0 |  |  |
|prp-35-49.smt2                                               |   21.528s | 978.0MiB| sat | 0 |  |  |
|prp-64-49.smt2                                               |   21.540s | 844.0MiB| unsat | 0 |  |  |
|prp-38-40.smt2                                               |   21.559s | 659.0MiB| unsat | 0 |  |  |
|prp-10-50.smt2                                               |   23.033s | 950.0MiB| sat | 0 |  |  |
|prp-27-41.smt2                                               |   23.494s | 773.0MiB| sat | 0 |  |  |
|prp-23-39.smt2                                               |   23.517s | 1184.0MiB| unsat | 0 |  |  |
|prp-61-49.smt2                                               |   23.930s | 970.0MiB| sat | 0 |  |  |
|prp-45-42.smt2                                               |   24.025s | 1094.0MiB| unsat | 0 |  |  |
|prp-38-42.smt2                                               |   24.598s | 964.0MiB| sat | 0 |  |  |
|prp-36-41.smt2                                               |   24.995s | 970.0MiB| sat | 0 |  |  |
|prp-16-50.smt2                                               |   25.647s | 1135.0MiB| sat | 0 |  |  |
|prp-27-45.smt2                                               |   25.755s | 914.0MiB| sat | 0 |  |  |
|prp-11-35.smt2                                               |   25.870s | 880.0MiB| unsat | 0 |  |  |
|prp-8-46.smt2                                                |   27.879s | 1008.0MiB| unsat | 0 |  |  |
|prp-25-47.smt2                                               |   28.246s | 813.0MiB| unsat | 0 |  |  |
|prp-64-50.smt2                                               |   28.767s | 892.0MiB| unsat | 0 |  |  |
|prp-81-50.smt2                                               |   29.199s | 912.0MiB| unsat | 0 |  |  |
|prp-29-48.smt2                                               |   29.787s | 855.0MiB| unsat | 0 |  |  |
|prp-63-49.smt2                                               |   29.811s | 887.0MiB| unsat | 0 |  |  |
|prp-67-50.smt2                                               |   30.446s | 935.0MiB| unsat | 0 |  |  |
|prp-0-48.smt2                                                |   31.825s | 749.0MiB| sat | 0 |  |  |
|prp-21-38.smt2                                               |   32.770s | 1039.0MiB| unsat | 0 |  |  |
|prp-14-45.smt2                                               |   33.715s | 1017.0MiB| sat | 0 |  |  |
|prp-19-46.smt2                                               |   34.010s | 1190.0MiB| sat | 0 |  |  |
|prp-54-45.smt2                                               |   34.549s | 1224.0MiB| unsat | 0 |  |  |
|prp-49-42.smt2                                               |   34.854s | 1388.0MiB| unsat | 0 |  |  |
|prp-44-44.smt2                                               |   35.799s | 1401.0MiB| unsat | 0 |  |  |
|prp-41-45.smt2                                               |   37.239s | 1066.0MiB| sat | 0 |  |  |
|prp-51-44.smt2                                               |   37.467s | 1062.0MiB| unsat | 0 |  |  |
|prp-43-49.smt2                                               |   37.695s | 1105.0MiB| unsat | 0 |  |  |
|prp-52-46.smt2                                               |   38.362s | 1127.0MiB| unsat | 0 |  |  |
|prp-42-44.smt2                                               |   39.037s | 1351.0MiB| unsat | 0 |  |  |
|prp-4-48.smt2                                                |   40.968s | 1226.0MiB| sat | 0 |  |  |
|prp-14-50.smt2                                               |   41.001s | 1101.0MiB| sat | 0 |  |  |
|prp-53-50.smt2                                               |   41.211s | 954.0MiB| unsat | 0 |  |  |
|prp-53-46.smt2                                               |   44.131s | 891.0MiB| unsat | 0 |  |  |
|prp-55-46.smt2                                               |   44.187s | 1178.0MiB| unsat | 0 |  |  |
|prp-22-48.smt2                                               |   44.695s | 1003.0MiB| unsat | 0 |  |  |
|prp-4-49.smt2                                                |   45.536s | 1140.0MiB| sat | 0 |  |  |
|prp-14-49.smt2                                               |   46.209s | 1173.0MiB| sat | 0 |  |  |
|prp-6-47.smt2                                                |   46.991s | 1142.0MiB| sat | 0 |  |  |
|prp-56-47.smt2                                               |   47.289s | 1504.0MiB| unsat | 0 |  |  |
|prp-18-46.smt2                                               |   47.581s | 1157.0MiB| sat | 0 |  |  |
|prp-58-47.smt2                                               |   49.278s | 1511.0MiB| unsat | 0 |  |  |
|prp-27-47.smt2                                               |   49.655s | 1500.0MiB| sat | 0 |  |  |
|prp-53-48.smt2                                               |   49.745s | 1456.0MiB| unsat | 0 |  |  |
|prp-51-48.smt2                                               |   52.116s | 1611.0MiB| unsat | 0 |  |  |
|prp-23-49.smt2                                               |   53.367s | 1475.0MiB| sat | 0 |  |  |
|prp-25-48.smt2                                               |   54.931s | 1637.0MiB| unsat | 0 |  |  |
|prp-60-48.smt2                                               |   56.789s | 1848.0MiB| unsat | 0 |  |  |
|prp-7-50.smt2                                                |   57.980s | 1516.0MiB| sat | 0 |  |  |
|prp-13-48.smt2                                               |   59.329s | 1691.0MiB| unsat | 0 |  |  |
|prp-43-48.smt2                                               |   59.426s | 1710.0MiB| unsat | 0 |  |  |
|prp-21-40.smt2                                               |   60.666s | 1196.0MiB| unsat | 0 |  |  |
|prp-55-49.smt2                                               |   65.094s | 1683.0MiB| unsat | 0 |  |  |
|constraint-283008.smt2                                       |   68.038s | 942.0MiB| sat | 0 |  |  |
|prp-31-42.smt2                                               |   68.811s | 2211.0MiB| unsat | 0 |  |  |
|prp-47-48.smt2                                               |   69.261s | 1554.0MiB| sat | 0 |  |  |
|prp-6-46.smt2                                                |   70.976s | 1257.0MiB| sat | 0 |  |  |
|prp-19-48.smt2                                               |   72.302s | 1909.0MiB| unsat | 0 |  |  |
|prp-14-47.smt2                                               |   72.835s | 1214.0MiB| sat | 0 |  |  |
|prp-17-46.smt2                                               |   77.676s | 1547.0MiB| sat | 0 |  |  |
|unbd-sage23.smt2                                             |   79.110s | 263.0MiB| sat | 0 |  |  |
|prp-23-41.smt2                                               |   80.720s | 1248.0MiB| unsat | 0 |  |  |
|constraint-729964.smt2                                       |   82.364s | 3519.0MiB| sat | 0 |  |  |
|prp-1-50.smt2                                                |   84.975s | 1720.0MiB| sat | 0 |  |  |
|prp-8-48.smt2                                                |   87.160s | 1727.0MiB| unsat | 0 |  |  |
|prp-62-50.smt2                                               |   88.528s | 1629.0MiB| unsat | 0 |  |  |
|prp-15-46.smt2                                               |   91.760s | 1515.0MiB| sat | 0 |  |  |
|prp-48-50.smt2                                               |   92.933s | 1687.0MiB| sat | 0 |  |  |
|prp-35-48.smt2                                               |   93.652s | 2347.0MiB| sat | 0 |  |  |
|prp-36-48.smt2                                               |  110.939s | 2346.0MiB| sat | 0 |  |  |
|prp-23-50.smt2                                               |  121.182s | 2070.0MiB| sat | 0 |  |  |
|prp-43-47.smt2                                               |  123.615s | 2899.0MiB| unsat | 0 |  |  |
|prp-10-46.smt2                                               |  124.432s | 1833.0MiB| sat | 0 |  |  |
|prp-1-47.smt2                                                |  130.588s | 1811.0MiB| sat | 0 |  |  |
|prp-22-49.smt2                                               |  134.326s | 1606.0MiB| sat | 0 |  |  |
|prp-7-47.smt2                                                |  159.129s | 1733.0MiB| unsat | 0 |  |  |
|prp-44-49.smt2                                               |  165.157s | 2499.0MiB| sat | 0 |  |  |
|constraint-762853.smt2                                       |  186.605s | 4361.0MiB| sat | 0 |  |  |
|prp-48-49.smt2                                               |  201.524s | 2370.0MiB| unsat | 0 |  |  |
|prp-8-47.smt2                                                |  212.321s | 2021.0MiB| unsat | 0 |  |  |
|prp-7-46.smt2                                                |  239.793s | 2057.0MiB| sat | 0 |  |  |
|prp-46-48.smt2                                               |  245.329s | 4166.0MiB| unsat | 0 |  |  |
|prp-10-47.smt2                                               |  249.320s | 1759.0MiB| unsat | 0 |  |  |
|prp-8-49.smt2                                                |  275.040s | 2350.0MiB| unsat | 0 |  |  |
|prp-33-48.smt2                                               |  275.780s | 2416.0MiB| unsat | 0 |  |  |
|Example_11.txt.smt2                                          |  287.649s | 446.0MiB| sat | 0 |  |  |
|prp-13-49.smt2                                               |  341.897s | 2589.0MiB| sat | 0 |  |  |
|prp-18-50.smt2                                               |  366.415s | 2537.0MiB| sat | 0 |  |  |
|prp-16-49.smt2                                               |  372.128s | 1884.0MiB| unsat | 0 |  |  |
|prp-32-49.smt2                                               |  422.229s | 4078.0MiB| unsat | 0 |  |  |
|prp-47-50.smt2                                               |  445.798s | 4072.0MiB| unsat | 0 |  |  |
|prp-10-49.smt2                                               |  476.621s | 2520.0MiB| unsat | 0 |  |  |
|prp-2-50.smt2                                                |  587.836s | 4115.0MiB| unsat | 0 |  |  |
|prp-29-49.smt2                                               |  597.519s | 4993.0MiB| unsat | 0 |  |  |
|unbd-sage1.smt2                                              |  600.062s | 267.0MiB| timeout | 0 |  |  |
|unbd-sage17.smt2                                             |  600.065s | 266.0MiB| timeout | 0 |  |  |
|unbd-sage0.smt2                                              |  600.066s | 266.0MiB| timeout | 0 |  |  |
|unbd-sage12.smt2                                             |  600.072s | 267.0MiB| timeout | 0 |  |  |
|unbd-sage22.smt2                                             |  600.075s | 266.0MiB| timeout | 0 |  |  |
