Comparing data and data


# SUMMARY
- LHS tests = 363
- RHS tests = 363
- LHS success = 363  (100.0%)
- RHS success = 363  (100.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
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
# RHS
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
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|30_30_18_5_sat.smt2                                                                         |   0.833s  |   0.833s  |   0.000s  | 0.0%|
|50_50_45_12_sat.smt2                                                                        |   1.453s  |   1.453s  |   0.000s  | 0.0%|
|Example_11.txt.smt2                                                                         | 287.649s  | 287.649s  |   0.000s  | 0.0%|
|Example_12.txt.smt2                                                                         |   4.200s  |   4.200s  |   0.000s  | 0.0%|
|Example_16.txt.smt2                                                                         |   2.773s  |   2.773s  |   0.000s  | 0.0%|
|FISCHER11-5-fair.smt2                                                                       |   0.465s  |   0.465s  |   0.000s  | 0.0%|
|FISCHER4-7-fair.smt2                                                                        |   0.346s  |   0.346s  |   0.000s  | 0.0%|
|FISCHER4-8-fair.smt2                                                                        |   0.372s  |   0.372s  |   0.000s  | 0.0%|
|FISCHER4-9-fair.smt2                                                                        |   0.388s  |   0.388s  |   0.000s  | 0.0%|
|FISCHER8-11-fair.smt2                                                                       |   2.044s  |   2.044s  |   0.000s  | 0.0%|
|FISCHER8-7-fair.smt2                                                                        |   0.536s  |   0.536s  |   0.000s  | 0.0%|
|FISCHER9-4-fair.smt2                                                                        |   0.397s  |   0.397s  |   0.000s  | 0.0%|
|FISCHER9-5-fair.smt2                                                                        |   0.446s  |   0.446s  |   0.000s  | 0.0%|
|ParallelPrefixSum_safe_bgmc006.smt2                                                         |   0.426s  |   0.426s  |   0.000s  | 0.0%|
|ParallelPrefixSum_safe_blmc002.smt2                                                         |   0.485s  |   0.485s  |   0.000s  | 0.0%|
|RC-00.smt2                                                                                  |   1.019s  |   1.019s  |   0.000s  | 0.0%|
|RC-01.smt2                                                                                  |   0.730s  |   0.730s  |   0.000s  | 0.0%|
|RC-02.smt2                                                                                  |   1.512s  |   1.512s  |   0.000s  | 0.0%|
|RC-03.smt2                                                                                  |   0.733s  |   0.733s  |   0.000s  | 0.0%|
|RC-04.smt2                                                                                  |   0.646s  |   0.646s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|30_30_18_5_sat.smt2                                                                         |   0.833s  |   0.833s  |   0.000s  | 0.0%|
|50_50_45_12_sat.smt2                                                                        |   1.453s  |   1.453s  |   0.000s  | 0.0%|
|Example_11.txt.smt2                                                                         | 287.649s  | 287.649s  |   0.000s  | 0.0%|
|Example_12.txt.smt2                                                                         |   4.200s  |   4.200s  |   0.000s  | 0.0%|
|Example_16.txt.smt2                                                                         |   2.773s  |   2.773s  |   0.000s  | 0.0%|
|FISCHER11-5-fair.smt2                                                                       |   0.465s  |   0.465s  |   0.000s  | 0.0%|
|FISCHER4-7-fair.smt2                                                                        |   0.346s  |   0.346s  |   0.000s  | 0.0%|
|FISCHER4-8-fair.smt2                                                                        |   0.372s  |   0.372s  |   0.000s  | 0.0%|
|FISCHER4-9-fair.smt2                                                                        |   0.388s  |   0.388s  |   0.000s  | 0.0%|
|FISCHER8-11-fair.smt2                                                                       |   2.044s  |   2.044s  |   0.000s  | 0.0%|
|FISCHER8-7-fair.smt2                                                                        |   0.536s  |   0.536s  |   0.000s  | 0.0%|
|FISCHER9-4-fair.smt2                                                                        |   0.397s  |   0.397s  |   0.000s  | 0.0%|
|FISCHER9-5-fair.smt2                                                                        |   0.446s  |   0.446s  |   0.000s  | 0.0%|
|ParallelPrefixSum_safe_bgmc006.smt2                                                         |   0.426s  |   0.426s  |   0.000s  | 0.0%|
|ParallelPrefixSum_safe_blmc002.smt2                                                         |   0.485s  |   0.485s  |   0.000s  | 0.0%|
|RC-00.smt2                                                                                  |   1.019s  |   1.019s  |   0.000s  | 0.0%|
|RC-01.smt2                                                                                  |   0.730s  |   0.730s  |   0.000s  | 0.0%|
|RC-02.smt2                                                                                  |   1.512s  |   1.512s  |   0.000s  | 0.0%|
|RC-03.smt2                                                                                  |   0.733s  |   0.733s  |   0.000s  | 0.0%|
|RC-04.smt2                                                                                  |   0.646s  |   0.646s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|30_30_18_5_sat.smt2                                                                         |   0.833s  |   0.833s  |   0.000s  | 0.0%|
|50_50_45_12_sat.smt2                                                                        |   1.453s  |   1.453s  |   0.000s  | 0.0%|
|Example_11.txt.smt2                                                                         | 287.649s  | 287.649s  |   0.000s  | 0.0%|
|Example_12.txt.smt2                                                                         |   4.200s  |   4.200s  |   0.000s  | 0.0%|
|Example_16.txt.smt2                                                                         |   2.773s  |   2.773s  |   0.000s  | 0.0%|
|FISCHER11-5-fair.smt2                                                                       |   0.465s  |   0.465s  |   0.000s  | 0.0%|
|FISCHER4-7-fair.smt2                                                                        |   0.346s  |   0.346s  |   0.000s  | 0.0%|
|FISCHER4-8-fair.smt2                                                                        |   0.372s  |   0.372s  |   0.000s  | 0.0%|
|FISCHER4-9-fair.smt2                                                                        |   0.388s  |   0.388s  |   0.000s  | 0.0%|
|FISCHER8-11-fair.smt2                                                                       |   2.044s  |   2.044s  |   0.000s  | 0.0%|
|FISCHER8-7-fair.smt2                                                                        |   0.536s  |   0.536s  |   0.000s  | 0.0%|
|FISCHER9-4-fair.smt2                                                                        |   0.397s  |   0.397s  |   0.000s  | 0.0%|
|FISCHER9-5-fair.smt2                                                                        |   0.446s  |   0.446s  |   0.000s  | 0.0%|
|ParallelPrefixSum_safe_bgmc006.smt2                                                         |   0.426s  |   0.426s  |   0.000s  | 0.0%|
|ParallelPrefixSum_safe_blmc002.smt2                                                         |   0.485s  |   0.485s  |   0.000s  | 0.0%|
|RC-00.smt2                                                                                  |   1.019s  |   1.019s  |   0.000s  | 0.0%|
|RC-01.smt2                                                                                  |   0.730s  |   0.730s  |   0.000s  | 0.0%|
|RC-02.smt2                                                                                  |   1.512s  |   1.512s  |   0.000s  | 0.0%|
|RC-03.smt2                                                                                  |   0.733s  |   0.733s  |   0.000s  | 0.0%|
|RC-04.smt2                                                                                  |   0.646s  |   0.646s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|30_30_18_5_sat.smt2                                                                         |   0.833s  |   0.833s  |   0.000s  | 0.0%|
|50_50_45_12_sat.smt2                                                                        |   1.453s  |   1.453s  |   0.000s  | 0.0%|
|Example_11.txt.smt2                                                                         | 287.649s  | 287.649s  |   0.000s  | 0.0%|
|Example_12.txt.smt2                                                                         |   4.200s  |   4.200s  |   0.000s  | 0.0%|
|Example_16.txt.smt2                                                                         |   2.773s  |   2.773s  |   0.000s  | 0.0%|
|FISCHER11-5-fair.smt2                                                                       |   0.465s  |   0.465s  |   0.000s  | 0.0%|
|FISCHER4-7-fair.smt2                                                                        |   0.346s  |   0.346s  |   0.000s  | 0.0%|
|FISCHER4-8-fair.smt2                                                                        |   0.372s  |   0.372s  |   0.000s  | 0.0%|
|FISCHER4-9-fair.smt2                                                                        |   0.388s  |   0.388s  |   0.000s  | 0.0%|
|FISCHER8-11-fair.smt2                                                                       |   2.044s  |   2.044s  |   0.000s  | 0.0%|
|FISCHER8-7-fair.smt2                                                                        |   0.536s  |   0.536s  |   0.000s  | 0.0%|
|FISCHER9-4-fair.smt2                                                                        |   0.397s  |   0.397s  |   0.000s  | 0.0%|
|FISCHER9-5-fair.smt2                                                                        |   0.446s  |   0.446s  |   0.000s  | 0.0%|
|ParallelPrefixSum_safe_bgmc006.smt2                                                         |   0.426s  |   0.426s  |   0.000s  | 0.0%|
|ParallelPrefixSum_safe_blmc002.smt2                                                         |   0.485s  |   0.485s  |   0.000s  | 0.0%|
|RC-00.smt2                                                                                  |   1.019s  |   1.019s  |   0.000s  | 0.0%|
|RC-01.smt2                                                                                  |   0.730s  |   0.730s  |   0.000s  | 0.0%|
|RC-02.smt2                                                                                  |   1.512s  |   1.512s  |   0.000s  | 0.0%|
|RC-03.smt2                                                                                  |   0.733s  |   0.733s  |   0.000s  | 0.0%|
|RC-04.smt2                                                                                  |   0.646s  |   0.646s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|unbd-sage22.smt2                                                                           | 600.075s |266.0MiB|
|unbd-sage12.smt2                                                                           | 600.072s |267.0MiB|
|unbd-sage0.smt2                                                                            | 600.066s |266.0MiB|
|unbd-sage17.smt2                                                                           | 600.065s |266.0MiB|
|unbd-sage1.smt2                                                                            | 600.062s |267.0MiB|
|prp-29-49.smt2                                                                             | 597.519s |4993.0MiB|
|prp-2-50.smt2                                                                              | 587.836s |4115.0MiB|
|prp-10-49.smt2                                                                             | 476.621s |2520.0MiB|
|prp-47-50.smt2                                                                             | 445.798s |4072.0MiB|
|prp-32-49.smt2                                                                             | 422.229s |4078.0MiB|
|prp-16-49.smt2                                                                             | 372.128s |1884.0MiB|
|prp-18-50.smt2                                                                             | 366.415s |2537.0MiB|
|prp-13-49.smt2                                                                             | 341.897s |2589.0MiB|
|Example_11.txt.smt2                                                                        | 287.649s |446.0MiB|
|prp-33-48.smt2                                                                             | 275.780s |2416.0MiB|
|prp-8-49.smt2                                                                              | 275.040s |2350.0MiB|
|prp-10-47.smt2                                                                             | 249.320s |1759.0MiB|
|prp-46-48.smt2                                                                             | 245.329s |4166.0MiB|
|prp-7-46.smt2                                                                              | 239.793s |2057.0MiB|
|prp-8-47.smt2                                                                              | 212.321s |2021.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|unbd-sage22.smt2                                                                           | 600.075s |266.0MiB|
|unbd-sage12.smt2                                                                           | 600.072s |267.0MiB|
|unbd-sage0.smt2                                                                            | 600.066s |266.0MiB|
|unbd-sage17.smt2                                                                           | 600.065s |266.0MiB|
|unbd-sage1.smt2                                                                            | 600.062s |267.0MiB|
|prp-29-49.smt2                                                                             | 597.519s |4993.0MiB|
|prp-2-50.smt2                                                                              | 587.836s |4115.0MiB|
|prp-10-49.smt2                                                                             | 476.621s |2520.0MiB|
|prp-47-50.smt2                                                                             | 445.798s |4072.0MiB|
|prp-32-49.smt2                                                                             | 422.229s |4078.0MiB|
|prp-16-49.smt2                                                                             | 372.128s |1884.0MiB|
|prp-18-50.smt2                                                                             | 366.415s |2537.0MiB|
|prp-13-49.smt2                                                                             | 341.897s |2589.0MiB|
|Example_11.txt.smt2                                                                        | 287.649s |446.0MiB|
|prp-33-48.smt2                                                                             | 275.780s |2416.0MiB|
|prp-8-49.smt2                                                                              | 275.040s |2350.0MiB|
|prp-10-47.smt2                                                                             | 249.320s |1759.0MiB|
|prp-46-48.smt2                                                                             | 245.329s |4166.0MiB|
|prp-7-46.smt2                                                                              | 239.793s |2057.0MiB|
|prp-8-47.smt2                                                                              | 212.321s |2021.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|30_30_18_5_sat.smt2                                                                         |317.0MiB|317.0MiB|0B| 0.0%|
|50_50_45_12_sat.smt2                                                                        |419.0MiB|419.0MiB|0B| 0.0%|
|Example_11.txt.smt2                                                                         |446.0MiB|446.0MiB|0B| 0.0%|
|Example_12.txt.smt2                                                                         |254.0MiB|254.0MiB|0B| 0.0%|
|Example_16.txt.smt2                                                                         |277.0MiB|277.0MiB|0B| 0.0%|
|FISCHER11-5-fair.smt2                                                                       |239.0MiB|239.0MiB|0B| 0.0%|
|FISCHER4-7-fair.smt2                                                                        |224.0MiB|224.0MiB|0B| 0.0%|
|FISCHER4-8-fair.smt2                                                                        |228.0MiB|228.0MiB|0B| 0.0%|
|FISCHER4-9-fair.smt2                                                                        |228.0MiB|228.0MiB|0B| 0.0%|
|FISCHER8-11-fair.smt2                                                                       |277.0MiB|277.0MiB|0B| 0.0%|
|FISCHER8-7-fair.smt2                                                                        |242.0MiB|242.0MiB|0B| 0.0%|
|FISCHER9-4-fair.smt2                                                                        |229.0MiB|229.0MiB|0B| 0.0%|
|FISCHER9-5-fair.smt2                                                                        |235.0MiB|235.0MiB|0B| 0.0%|
|ParallelPrefixSum_safe_bgmc006.smt2                                                         |247.0MiB|247.0MiB|0B| 0.0%|
|ParallelPrefixSum_safe_blmc002.smt2                                                         |252.0MiB|252.0MiB|0B| 0.0%|
|RC-00.smt2                                                                                  |370.0MiB|370.0MiB|0B| 0.0%|
|RC-01.smt2                                                                                  |337.0MiB|337.0MiB|0B| 0.0%|
|RC-02.smt2                                                                                  |493.0MiB|493.0MiB|0B| 0.0%|
|RC-03.smt2                                                                                  |299.0MiB|299.0MiB|0B| 0.0%|
|RC-04.smt2                                                                                  |303.0MiB|303.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|30_30_18_5_sat.smt2                                                                         |317.0MiB|317.0MiB|0B| 0.0%|
|50_50_45_12_sat.smt2                                                                        |419.0MiB|419.0MiB|0B| 0.0%|
|Example_11.txt.smt2                                                                         |446.0MiB|446.0MiB|0B| 0.0%|
|Example_12.txt.smt2                                                                         |254.0MiB|254.0MiB|0B| 0.0%|
|Example_16.txt.smt2                                                                         |277.0MiB|277.0MiB|0B| 0.0%|
|FISCHER11-5-fair.smt2                                                                       |239.0MiB|239.0MiB|0B| 0.0%|
|FISCHER4-7-fair.smt2                                                                        |224.0MiB|224.0MiB|0B| 0.0%|
|FISCHER4-8-fair.smt2                                                                        |228.0MiB|228.0MiB|0B| 0.0%|
|FISCHER4-9-fair.smt2                                                                        |228.0MiB|228.0MiB|0B| 0.0%|
|FISCHER8-11-fair.smt2                                                                       |277.0MiB|277.0MiB|0B| 0.0%|
|FISCHER8-7-fair.smt2                                                                        |242.0MiB|242.0MiB|0B| 0.0%|
|FISCHER9-4-fair.smt2                                                                        |229.0MiB|229.0MiB|0B| 0.0%|
|FISCHER9-5-fair.smt2                                                                        |235.0MiB|235.0MiB|0B| 0.0%|
|ParallelPrefixSum_safe_bgmc006.smt2                                                         |247.0MiB|247.0MiB|0B| 0.0%|
|ParallelPrefixSum_safe_blmc002.smt2                                                         |252.0MiB|252.0MiB|0B| 0.0%|
|RC-00.smt2                                                                                  |370.0MiB|370.0MiB|0B| 0.0%|
|RC-01.smt2                                                                                  |337.0MiB|337.0MiB|0B| 0.0%|
|RC-02.smt2                                                                                  |493.0MiB|493.0MiB|0B| 0.0%|
|RC-03.smt2                                                                                  |299.0MiB|299.0MiB|0B| 0.0%|
|RC-04.smt2                                                                                  |303.0MiB|303.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|30_30_18_5_sat.smt2                                                                         |317.0MiB|317.0MiB|0B| 0.0%|
|50_50_45_12_sat.smt2                                                                        |419.0MiB|419.0MiB|0B| 0.0%|
|Example_11.txt.smt2                                                                         |446.0MiB|446.0MiB|0B| 0.0%|
|Example_12.txt.smt2                                                                         |254.0MiB|254.0MiB|0B| 0.0%|
|Example_16.txt.smt2                                                                         |277.0MiB|277.0MiB|0B| 0.0%|
|FISCHER11-5-fair.smt2                                                                       |239.0MiB|239.0MiB|0B| 0.0%|
|FISCHER4-7-fair.smt2                                                                        |224.0MiB|224.0MiB|0B| 0.0%|
|FISCHER4-8-fair.smt2                                                                        |228.0MiB|228.0MiB|0B| 0.0%|
|FISCHER4-9-fair.smt2                                                                        |228.0MiB|228.0MiB|0B| 0.0%|
|FISCHER8-11-fair.smt2                                                                       |277.0MiB|277.0MiB|0B| 0.0%|
|FISCHER8-7-fair.smt2                                                                        |242.0MiB|242.0MiB|0B| 0.0%|
|FISCHER9-4-fair.smt2                                                                        |229.0MiB|229.0MiB|0B| 0.0%|
|FISCHER9-5-fair.smt2                                                                        |235.0MiB|235.0MiB|0B| 0.0%|
|ParallelPrefixSum_safe_bgmc006.smt2                                                         |247.0MiB|247.0MiB|0B| 0.0%|
|ParallelPrefixSum_safe_blmc002.smt2                                                         |252.0MiB|252.0MiB|0B| 0.0%|
|RC-00.smt2                                                                                  |370.0MiB|370.0MiB|0B| 0.0%|
|RC-01.smt2                                                                                  |337.0MiB|337.0MiB|0B| 0.0%|
|RC-02.smt2                                                                                  |493.0MiB|493.0MiB|0B| 0.0%|
|RC-03.smt2                                                                                  |299.0MiB|299.0MiB|0B| 0.0%|
|RC-04.smt2                                                                                  |303.0MiB|303.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|30_30_18_5_sat.smt2                                                                         |317.0MiB|317.0MiB|0B| 0.0%|
|50_50_45_12_sat.smt2                                                                        |419.0MiB|419.0MiB|0B| 0.0%|
|Example_11.txt.smt2                                                                         |446.0MiB|446.0MiB|0B| 0.0%|
|Example_12.txt.smt2                                                                         |254.0MiB|254.0MiB|0B| 0.0%|
|Example_16.txt.smt2                                                                         |277.0MiB|277.0MiB|0B| 0.0%|
|FISCHER11-5-fair.smt2                                                                       |239.0MiB|239.0MiB|0B| 0.0%|
|FISCHER4-7-fair.smt2                                                                        |224.0MiB|224.0MiB|0B| 0.0%|
|FISCHER4-8-fair.smt2                                                                        |228.0MiB|228.0MiB|0B| 0.0%|
|FISCHER4-9-fair.smt2                                                                        |228.0MiB|228.0MiB|0B| 0.0%|
|FISCHER8-11-fair.smt2                                                                       |277.0MiB|277.0MiB|0B| 0.0%|
|FISCHER8-7-fair.smt2                                                                        |242.0MiB|242.0MiB|0B| 0.0%|
|FISCHER9-4-fair.smt2                                                                        |229.0MiB|229.0MiB|0B| 0.0%|
|FISCHER9-5-fair.smt2                                                                        |235.0MiB|235.0MiB|0B| 0.0%|
|ParallelPrefixSum_safe_bgmc006.smt2                                                         |247.0MiB|247.0MiB|0B| 0.0%|
|ParallelPrefixSum_safe_blmc002.smt2                                                         |252.0MiB|252.0MiB|0B| 0.0%|
|RC-00.smt2                                                                                  |370.0MiB|370.0MiB|0B| 0.0%|
|RC-01.smt2                                                                                  |337.0MiB|337.0MiB|0B| 0.0%|
|RC-02.smt2                                                                                  |493.0MiB|493.0MiB|0B| 0.0%|
|RC-03.smt2                                                                                  |299.0MiB|299.0MiB|0B| 0.0%|
|RC-04.smt2                                                                                  |303.0MiB|303.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|prp-29-49.smt2                                                                             | 597.519s |4993.0MiB|
|constraint-762853.smt2                                                                     | 186.605s |4361.0MiB|
|prp-46-48.smt2                                                                             | 245.329s |4166.0MiB|
|prp-2-50.smt2                                                                              | 587.836s |4115.0MiB|
|prp-32-49.smt2                                                                             | 422.229s |4078.0MiB|
|prp-47-50.smt2                                                                             | 445.798s |4072.0MiB|
|constraint-729964.smt2                                                                     |  82.364s |3519.0MiB|
|prp-43-47.smt2                                                                             | 123.615s |2899.0MiB|
|prp-13-49.smt2                                                                             | 341.897s |2589.0MiB|
|prp-18-50.smt2                                                                             | 366.415s |2537.0MiB|
|prp-10-49.smt2                                                                             | 476.621s |2520.0MiB|
|prp-44-49.smt2                                                                             | 165.157s |2499.0MiB|
|prp-33-48.smt2                                                                             | 275.780s |2416.0MiB|
|prp-48-49.smt2                                                                             | 201.524s |2370.0MiB|
|prp-8-49.smt2                                                                              | 275.040s |2350.0MiB|
|prp-35-48.smt2                                                                             |  93.652s |2347.0MiB|
|prp-36-48.smt2                                                                             | 110.939s |2346.0MiB|
|prp-31-42.smt2                                                                             |  68.811s |2211.0MiB|
|prp-23-50.smt2                                                                             | 121.182s |2070.0MiB|
|prp-7-46.smt2                                                                              | 239.793s |2057.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|prp-29-49.smt2                                                                             | 597.519s |4993.0MiB|
|constraint-762853.smt2                                                                     | 186.605s |4361.0MiB|
|prp-46-48.smt2                                                                             | 245.329s |4166.0MiB|
|prp-2-50.smt2                                                                              | 587.836s |4115.0MiB|
|prp-32-49.smt2                                                                             | 422.229s |4078.0MiB|
|prp-47-50.smt2                                                                             | 445.798s |4072.0MiB|
|constraint-729964.smt2                                                                     |  82.364s |3519.0MiB|
|prp-43-47.smt2                                                                             | 123.615s |2899.0MiB|
|prp-13-49.smt2                                                                             | 341.897s |2589.0MiB|
|prp-18-50.smt2                                                                             | 366.415s |2537.0MiB|
|prp-10-49.smt2                                                                             | 476.621s |2520.0MiB|
|prp-44-49.smt2                                                                             | 165.157s |2499.0MiB|
|prp-33-48.smt2                                                                             | 275.780s |2416.0MiB|
|prp-48-49.smt2                                                                             | 201.524s |2370.0MiB|
|prp-8-49.smt2                                                                              | 275.040s |2350.0MiB|
|prp-35-48.smt2                                                                             |  93.652s |2347.0MiB|
|prp-36-48.smt2                                                                             | 110.939s |2346.0MiB|
|prp-31-42.smt2                                                                             |  68.811s |2211.0MiB|
|prp-23-50.smt2                                                                             | 121.182s |2070.0MiB|
|prp-7-46.smt2                                                                              | 239.793s |2057.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|30_30_18_5_sat.smt2                                                                         |   0.833s  |   0.833s  |   0.000s  | 0.0%|
|50_50_45_12_sat.smt2                                                                        |   1.453s  |   1.453s  |   0.000s  | 0.0%|
|Example_11.txt.smt2                                                                         | 287.649s  | 287.649s  |   0.000s  | 0.0%|
|Example_12.txt.smt2                                                                         |   4.200s  |   4.200s  |   0.000s  | 0.0%|
|Example_16.txt.smt2                                                                         |   2.773s  |   2.773s  |   0.000s  | 0.0%|
|FISCHER11-5-fair.smt2                                                                       |   0.465s  |   0.465s  |   0.000s  | 0.0%|
|FISCHER4-7-fair.smt2                                                                        |   0.346s  |   0.346s  |   0.000s  | 0.0%|
|FISCHER4-8-fair.smt2                                                                        |   0.372s  |   0.372s  |   0.000s  | 0.0%|
|FISCHER4-9-fair.smt2                                                                        |   0.388s  |   0.388s  |   0.000s  | 0.0%|
|FISCHER8-11-fair.smt2                                                                       |   2.044s  |   2.044s  |   0.000s  | 0.0%|
|FISCHER8-7-fair.smt2                                                                        |   0.536s  |   0.536s  |   0.000s  | 0.0%|
|FISCHER9-4-fair.smt2                                                                        |   0.397s  |   0.397s  |   0.000s  | 0.0%|
|FISCHER9-5-fair.smt2                                                                        |   0.446s  |   0.446s  |   0.000s  | 0.0%|
|ParallelPrefixSum_safe_bgmc006.smt2                                                         |   0.426s  |   0.426s  |   0.000s  | 0.0%|
|ParallelPrefixSum_safe_blmc002.smt2                                                         |   0.485s  |   0.485s  |   0.000s  | 0.0%|
|RC-00.smt2                                                                                  |   1.019s  |   1.019s  |   0.000s  | 0.0%|
|RC-01.smt2                                                                                  |   0.730s  |   0.730s  |   0.000s  | 0.0%|
|RC-02.smt2                                                                                  |   1.512s  |   1.512s  |   0.000s  | 0.0%|
|RC-03.smt2                                                                                  |   0.733s  |   0.733s  |   0.000s  | 0.0%|
|RC-04.smt2                                                                                  |   0.646s  |   0.646s  |   0.000s  | 0.0%|
|RC-05.smt2                                                                                  |   0.887s  |   0.887s  |   0.000s  | 0.0%|
|RC-06.smt2                                                                                  |   0.659s  |   0.659s  |   0.000s  | 0.0%|
|RC-07.smt2                                                                                  |   0.620s  |   0.620s  |   0.000s  | 0.0%|
|RC-09.smt2                                                                                  |   3.273s  |   3.273s  |   0.000s  | 0.0%|
|RC-10.smt2                                                                                  |   0.664s  |   0.664s  |   0.000s  | 0.0%|
|RC-11.smt2                                                                                  |   0.621s  |   0.621s  |   0.000s  | 0.0%|
|RC-12.smt2                                                                                  |   0.709s  |   0.709s  |   0.000s  | 0.0%|
|RC-13.smt2                                                                                  |   0.733s  |   0.733s  |   0.000s  | 0.0%|
|RC-14.smt2                                                                                  |   1.037s  |   1.037s  |   0.000s  | 0.0%|
|RC-15.smt2                                                                                  |   1.067s  |   1.067s  |   0.000s  | 0.0%|
|RF-00.smt2                                                                                  |   0.757s  |   0.757s  |   0.000s  | 0.0%|
|RF-01.smt2                                                                                  |   0.682s  |   0.682s  |   0.000s  | 0.0%|
|RF-02.smt2                                                                                  |   1.078s  |   1.078s  |   0.000s  | 0.0%|
|RF-03.smt2                                                                                  |   0.786s  |   0.786s  |   0.000s  | 0.0%|
|RF-04.smt2                                                                                  |   0.677s  |   0.677s  |   0.000s  | 0.0%|
|RF-05.smt2                                                                                  |   0.727s  |   0.727s  |   0.000s  | 0.0%|
|RF-06.smt2                                                                                  |   1.109s  |   1.109s  |   0.000s  | 0.0%|
|RF-07.smt2                                                                                  |   0.678s  |   0.678s  |   0.000s  | 0.0%|
|RF-08.smt2                                                                                  |   0.649s  |   0.649s  |   0.000s  | 0.0%|
|RF-09.smt2                                                                                  |   0.748s  |   0.748s  |   0.000s  | 0.0%|
|RF-10.smt2                                                                                  |   0.740s  |   0.740s  |   0.000s  | 0.0%|
|RF-11.smt2                                                                                  |   1.589s  |   1.589s  |   0.000s  | 0.0%|
|RF-12.smt2                                                                                  |   1.027s  |   1.027s  |   0.000s  | 0.0%|
|RF-13.smt2                                                                                  |   1.519s  |   1.519s  |   0.000s  | 0.0%|
|RF-14.smt2                                                                                  |   0.742s  |   0.742s  |   0.000s  | 0.0%|
|constraint-178902.smt2                                                                      |   7.456s  |   7.456s  |   0.000s  | 0.0%|
|constraint-187292.smt2                                                                      |   2.994s  |   2.994s  |   0.000s  | 0.0%|
|constraint-283008.smt2                                                                      |  68.038s  |  68.038s  |   0.000s  | 0.0%|
|constraint-390915.smt2                                                                      |   3.861s  |   3.861s  |   0.000s  | 0.0%|
|constraint-396616.smt2                                                                      |   2.167s  |   2.167s  |   0.000s  | 0.0%|
|constraint-463860.smt2                                                                      |   2.428s  |   2.428s  |   0.000s  | 0.0%|
|constraint-649834.smt2                                                                      |   5.119s  |   5.119s  |   0.000s  | 0.0%|
|constraint-679470.smt2                                                                      |   7.560s  |   7.560s  |   0.000s  | 0.0%|
|constraint-729964.smt2                                                                      |  82.364s  |  82.364s  |   0.000s  | 0.0%|
|constraint-762853.smt2                                                                      | 186.605s  | 186.605s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1372.smt2                                                             |   0.531s  |   0.531s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1379.smt2                                                             |   0.544s  |   0.544s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1420.smt2                                                             |   0.585s  |   0.585s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1423.smt2                                                             |   0.582s  |   0.582s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1432.smt2                                                             |   0.640s  |   0.640s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1441.smt2                                                             |   0.584s  |   0.584s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1445.smt2                                                             |   0.619s  |   0.619s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1453.smt2                                                             |   0.574s  |   0.574s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1474.smt2                                                             |   0.888s  |   0.888s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1475.smt2                                                             |   0.704s  |   0.704s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1484.smt2                                                             |   0.719s  |   0.719s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1497.smt2                                                             |   0.732s  |   0.732s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1523.smt2                                                             |   0.777s  |   0.777s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1533.smt2                                                             |   0.909s  |   0.909s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1546.smt2                                                             |   1.032s  |   1.032s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1555.smt2                                                             |   0.944s  |   0.944s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1581.smt2                                                             |   0.997s  |   0.997s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1598.smt2                                                             |   1.054s  |   1.054s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1607.smt2                                                             |   0.973s  |   0.973s  |   0.000s  | 0.0%|
|convert-jpg2gif-query-1609.smt2                                                             |   1.043s  |   1.043s  |   0.000s  | 0.0%|
|p2756.sat.smt2                                                                              |   1.325s  |   1.325s  |   0.000s  | 0.0%|
|prp-0-46.smt2                                                                               |  11.460s  |  11.460s  |   0.000s  | 0.0%|
|prp-0-47.smt2                                                                               |   6.395s  |   6.395s  |   0.000s  | 0.0%|
|prp-0-48.smt2                                                                               |  31.825s  |  31.825s  |   0.000s  | 0.0%|
|prp-1-198.smt2                                                                              |   4.263s  |   4.263s  |   0.000s  | 0.0%|
|prp-1-46.smt2                                                                               |   0.268s  |   0.268s  |   0.000s  | 0.0%|
|prp-1-47.smt2                                                                               | 130.588s  | 130.588s  |   0.000s  | 0.0%|
|prp-1-48.smt2                                                                               |   0.337s  |   0.337s  |   0.000s  | 0.0%|
|prp-1-49.smt2                                                                               |   3.383s  |   3.383s  |   0.000s  | 0.0%|
|prp-1-50.smt2                                                                               |  84.975s  |  84.975s  |   0.000s  | 0.0%|
|prp-10-32.smt2                                                                              |   8.449s  |   8.449s  |   0.000s  | 0.0%|
|prp-10-46.smt2                                                                              | 124.432s  | 124.432s  |   0.000s  | 0.0%|
|prp-10-47.smt2                                                                              | 249.320s  | 249.320s  |   0.000s  | 0.0%|
|prp-10-48.smt2                                                                              |   0.333s  |   0.333s  |   0.000s  | 0.0%|
|prp-10-49.smt2                                                                              | 476.621s  | 476.621s  |   0.000s  | 0.0%|
|prp-10-50.smt2                                                                              |  23.033s  |  23.033s  |   0.000s  | 0.0%|
|prp-11-32.smt2                                                                              |   3.352s  |   3.352s  |   0.000s  | 0.0%|
|prp-11-35.smt2                                                                              |  25.870s  |  25.870s  |   0.000s  | 0.0%|
|prp-11-46.smt2                                                                              |   2.182s  |   2.182s  |   0.000s  | 0.0%|
|prp-11-47.smt2                                                                              |   0.300s  |   0.300s  |   0.000s  | 0.0%|
|prp-11-49.smt2                                                                              |   4.175s  |   4.175s  |   0.000s  | 0.0%|
|prp-11-50.smt2                                                                              |   0.416s  |   0.416s  |   0.000s  | 0.0%|
|prp-12-47.smt2                                                                              |  14.130s  |  14.130s  |   0.000s  | 0.0%|
|prp-12-48.smt2                                                                              |   8.288s  |   8.288s  |   0.000s  | 0.0%|
|prp-12-49.smt2                                                                              |  11.179s  |  11.179s  |   0.000s  | 0.0%|
|prp-12-50.smt2                                                                              |   0.421s  |   0.421s  |   0.000s  | 0.0%|
|prp-13-33.smt2                                                                              |   3.747s  |   3.747s  |   0.000s  | 0.0%|
|prp-13-41.smt2                                                                              |  11.452s  |  11.452s  |   0.000s  | 0.0%|
|prp-13-46.smt2                                                                              |   0.290s  |   0.290s  |   0.000s  | 0.0%|
|prp-13-47.smt2                                                                              |   0.312s  |   0.312s  |   0.000s  | 0.0%|
|prp-13-48.smt2                                                                              |  59.329s  |  59.329s  |   0.000s  | 0.0%|
|prp-13-49.smt2                                                                              | 341.897s  | 341.897s  |   0.000s  | 0.0%|
|prp-14-44.smt2                                                                              |  12.593s  |  12.593s  |   0.000s  | 0.0%|
|prp-14-45.smt2                                                                              |  33.715s  |  33.715s  |   0.000s  | 0.0%|
|prp-14-47.smt2                                                                              |  72.835s  |  72.835s  |   0.000s  | 0.0%|
|prp-14-48.smt2                                                                              |   0.332s  |   0.332s  |   0.000s  | 0.0%|
|prp-14-49.smt2                                                                              |  46.209s  |  46.209s  |   0.000s  | 0.0%|
|prp-14-50.smt2                                                                              |  41.001s  |  41.001s  |   0.000s  | 0.0%|
|prp-15-33.smt2                                                                              |   3.471s  |   3.471s  |   0.000s  | 0.0%|
|prp-15-46.smt2                                                                              |  91.760s  |  91.760s  |   0.000s  | 0.0%|
|prp-15-47.smt2                                                                              |   0.321s  |   0.321s  |   0.000s  | 0.0%|
|prp-15-48.smt2                                                                              |   0.305s  |   0.305s  |   0.000s  | 0.0%|
|prp-16-46.smt2                                                                              |   0.834s  |   0.834s  |   0.000s  | 0.0%|
|prp-16-47.smt2                                                                              |   0.302s  |   0.302s  |   0.000s  | 0.0%|
|prp-16-49.smt2                                                                              | 372.128s  | 372.128s  |   0.000s  | 0.0%|
|prp-16-50.smt2                                                                              |  25.647s  |  25.647s  |   0.000s  | 0.0%|
|prp-17-33.smt2                                                                              |   3.940s  |   3.940s  |   0.000s  | 0.0%|
|prp-17-34.smt2                                                                              |   4.842s  |   4.842s  |   0.000s  | 0.0%|
|prp-17-40.smt2                                                                              |   7.802s  |   7.802s  |   0.000s  | 0.0%|
|prp-17-41.smt2                                                                              |  11.131s  |  11.131s  |   0.000s  | 0.0%|
|prp-17-46.smt2                                                                              |  77.676s  |  77.676s  |   0.000s  | 0.0%|
|prp-17-47.smt2                                                                              |   0.958s  |   0.958s  |   0.000s  | 0.0%|
|prp-18-40.smt2                                                                              |  10.050s  |  10.050s  |   0.000s  | 0.0%|
|prp-18-42.smt2                                                                              |  13.718s  |  13.718s  |   0.000s  | 0.0%|
|prp-18-46.smt2                                                                              |  47.581s  |  47.581s  |   0.000s  | 0.0%|
|prp-18-47.smt2                                                                              |   1.041s  |   1.041s  |   0.000s  | 0.0%|
|prp-18-48.smt2                                                                              |   3.321s  |   3.321s  |   0.000s  | 0.0%|
|prp-18-49.smt2                                                                              |  19.454s  |  19.454s  |   0.000s  | 0.0%|
|prp-18-50.smt2                                                                              | 366.415s  | 366.415s  |   0.000s  | 0.0%|
|prp-19-33.smt2                                                                              |   4.374s  |   4.374s  |   0.000s  | 0.0%|
|prp-19-46.smt2                                                                              |  34.010s  |  34.010s  |   0.000s  | 0.0%|
|prp-19-47.smt2                                                                              |   2.420s  |   2.420s  |   0.000s  | 0.0%|
|prp-19-48.smt2                                                                              |  72.302s  |  72.302s  |   0.000s  | 0.0%|
|prp-19-49.smt2                                                                              |   0.361s  |   0.361s  |   0.000s  | 0.0%|
|prp-19-50.smt2                                                                              |   0.392s  |   0.392s  |   0.000s  | 0.0%|
|prp-2-199.smt2                                                                              |  17.504s  |  17.504s  |   0.000s  | 0.0%|
|prp-2-47.smt2                                                                               |   2.229s  |   2.229s  |   0.000s  | 0.0%|
|prp-2-50.smt2                                                                               | 587.836s  | 587.836s  |   0.000s  | 0.0%|
|prp-20-35.smt2                                                                              |   6.083s  |   6.083s  |   0.000s  | 0.0%|
|prp-20-42.smt2                                                                              |  11.174s  |  11.174s  |   0.000s  | 0.0%|
|prp-20-46.smt2                                                                              |  10.274s  |  10.274s  |   0.000s  | 0.0%|
|prp-20-47.smt2                                                                              |   0.317s  |   0.317s  |   0.000s  | 0.0%|
|prp-20-49.smt2                                                                              |   0.374s  |   0.374s  |   0.000s  | 0.0%|
|prp-20-50.smt2                                                                              |   4.308s  |   4.308s  |   0.000s  | 0.0%|
|prp-21-38.smt2                                                                              |  32.770s  |  32.770s  |   0.000s  | 0.0%|
|prp-21-40.smt2                                                                              |  60.666s  |  60.666s  |   0.000s  | 0.0%|
|prp-21-46.smt2                                                                              |   0.275s  |   0.275s  |   0.000s  | 0.0%|
|prp-21-48.smt2                                                                              |  16.766s  |  16.766s  |   0.000s  | 0.0%|
|prp-21-49.smt2                                                                              |  17.633s  |  17.633s  |   0.000s  | 0.0%|
|prp-22-38.smt2                                                                              |   8.663s  |   8.663s  |   0.000s  | 0.0%|
|prp-22-40.smt2                                                                              |  10.632s  |  10.632s  |   0.000s  | 0.0%|
|prp-22-42.smt2                                                                              |  14.159s  |  14.159s  |   0.000s  | 0.0%|
|prp-22-46.smt2                                                                              |   0.283s  |   0.283s  |   0.000s  | 0.0%|
|prp-22-47.smt2                                                                              |   0.314s  |   0.314s  |   0.000s  | 0.0%|
|prp-22-48.smt2                                                                              |  44.695s  |  44.695s  |   0.000s  | 0.0%|
|prp-22-49.smt2                                                                              | 134.326s  | 134.326s  |   0.000s  | 0.0%|
|prp-22-50.smt2                                                                              |   4.105s  |   4.105s  |   0.000s  | 0.0%|
|prp-23-39.smt2                                                                              |  23.517s  |  23.517s  |   0.000s  | 0.0%|
|prp-23-41.smt2                                                                              |  80.720s  |  80.720s  |   0.000s  | 0.0%|
|prp-23-47.smt2                                                                              |   0.310s  |   0.310s  |   0.000s  | 0.0%|
|prp-23-48.smt2                                                                              |   0.323s  |   0.323s  |   0.000s  | 0.0%|
|prp-23-49.smt2                                                                              |  53.367s  |  53.367s  |   0.000s  | 0.0%|
|prp-23-50.smt2                                                                              | 121.182s  | 121.182s  |   0.000s  | 0.0%|
|prp-24-39.smt2                                                                              |  12.971s  |  12.971s  |   0.000s  | 0.0%|
|prp-24-46.smt2                                                                              |   0.866s  |   0.866s  |   0.000s  | 0.0%|
|prp-24-48.smt2                                                                              |  15.758s  |  15.758s  |   0.000s  | 0.0%|
|prp-24-50.smt2                                                                              |   3.507s  |   3.507s  |   0.000s  | 0.0%|
|prp-25-43.smt2                                                                              |   0.901s  |   0.901s  |   0.000s  | 0.0%|
|prp-25-47.smt2                                                                              |  28.246s  |  28.246s  |   0.000s  | 0.0%|
|prp-25-48.smt2                                                                              |  54.931s  |  54.931s  |   0.000s  | 0.0%|
|prp-25-49.smt2                                                                              |   0.331s  |   0.331s  |   0.000s  | 0.0%|
|prp-25-50.smt2                                                                              |   3.080s  |   3.080s  |   0.000s  | 0.0%|
|prp-26-32.smt2                                                                              |   4.103s  |   4.103s  |   0.000s  | 0.0%|
|prp-26-41.smt2                                                                              |  12.231s  |  12.231s  |   0.000s  | 0.0%|
|prp-26-44.smt2                                                                              |  20.257s  |  20.257s  |   0.000s  | 0.0%|
|prp-26-47.smt2                                                                              |  19.801s  |  19.801s  |   0.000s  | 0.0%|
|prp-27-35.smt2                                                                              |   9.067s  |   9.067s  |   0.000s  | 0.0%|
|prp-27-39.smt2                                                                              |   2.139s  |   2.139s  |   0.000s  | 0.0%|
|prp-27-41.smt2                                                                              |  23.494s  |  23.494s  |   0.000s  | 0.0%|
|prp-27-42.smt2                                                                              |   3.137s  |   3.137s  |   0.000s  | 0.0%|
|prp-27-45.smt2                                                                              |  25.755s  |  25.755s  |   0.000s  | 0.0%|
|prp-27-47.smt2                                                                              |  49.655s  |  49.655s  |   0.000s  | 0.0%|
|prp-28-36.smt2                                                                              |   8.777s  |   8.777s  |   0.000s  | 0.0%|
|prp-28-46.smt2                                                                              |   1.504s  |   1.504s  |   0.000s  | 0.0%|
|prp-29-36.smt2                                                                              |  10.068s  |  10.068s  |   0.000s  | 0.0%|
|prp-29-47.smt2                                                                              |   1.026s  |   1.026s  |   0.000s  | 0.0%|
|prp-29-48.smt2                                                                              |  29.787s  |  29.787s  |   0.000s  | 0.0%|
|prp-29-49.smt2                                                                              | 597.519s  | 597.519s  |   0.000s  | 0.0%|
|prp-29-50.smt2                                                                              |   3.906s  |   3.906s  |   0.000s  | 0.0%|
|prp-3-47.smt2                                                                               |   0.318s  |   0.318s  |   0.000s  | 0.0%|
|prp-3-48.smt2                                                                               |   0.340s  |   0.340s  |   0.000s  | 0.0%|
|prp-3-50.smt2                                                                               |   0.415s  |   0.415s  |   0.000s  | 0.0%|
|prp-30-31.smt2                                                                              |   4.150s  |   4.150s  |   0.000s  | 0.0%|
|prp-30-32.smt2                                                                              |   5.208s  |   5.208s  |   0.000s  | 0.0%|
|prp-30-40.smt2                                                                              |  13.932s  |  13.932s  |   0.000s  | 0.0%|
|prp-30-47.smt2                                                                              |  12.506s  |  12.506s  |   0.000s  | 0.0%|
|prp-30-49.smt2                                                                              |  18.789s  |  18.789s  |   0.000s  | 0.0%|
|prp-31-32.smt2                                                                              |   4.377s  |   4.377s  |   0.000s  | 0.0%|
|prp-31-39.smt2                                                                              |  10.457s  |  10.457s  |   0.000s  | 0.0%|
|prp-31-42.smt2                                                                              |  68.811s  |  68.811s  |   0.000s  | 0.0%|
|prp-31-46.smt2                                                                              |   0.323s  |   0.323s  |   0.000s  | 0.0%|
|prp-31-47.smt2                                                                              |   0.308s  |   0.308s  |   0.000s  | 0.0%|
|prp-31-49.smt2                                                                              |   0.370s  |   0.370s  |   0.000s  | 0.0%|
|prp-32-39.smt2                                                                              |   3.309s  |   3.309s  |   0.000s  | 0.0%|
|prp-32-47.smt2                                                                              |   0.305s  |   0.305s  |   0.000s  | 0.0%|
|prp-32-49.smt2                                                                              | 422.229s  | 422.229s  |   0.000s  | 0.0%|
|prp-33-38.smt2                                                                              |   1.540s  |   1.540s  |   0.000s  | 0.0%|
|prp-33-42.smt2                                                                              |  14.417s  |  14.417s  |   0.000s  | 0.0%|
|prp-33-46.smt2                                                                              |   1.704s  |   1.704s  |   0.000s  | 0.0%|
|prp-33-47.smt2                                                                              |   1.893s  |   1.893s  |   0.000s  | 0.0%|
|prp-33-48.smt2                                                                              | 275.780s  | 275.780s  |   0.000s  | 0.0%|
|prp-34-40.smt2                                                                              |  13.883s  |  13.883s  |   0.000s  | 0.0%|
|prp-35-39.smt2                                                                              |   1.509s  |   1.509s  |   0.000s  | 0.0%|
|prp-35-42.smt2                                                                              |   3.758s  |   3.758s  |   0.000s  | 0.0%|
|prp-35-44.smt2                                                                              |   5.252s  |   5.252s  |   0.000s  | 0.0%|
|prp-35-48.smt2                                                                              |  93.652s  |  93.652s  |   0.000s  | 0.0%|
|prp-35-49.smt2                                                                              |  21.528s  |  21.528s  |   0.000s  | 0.0%|
|prp-36-40.smt2                                                                              |  16.904s  |  16.904s  |   0.000s  | 0.0%|
|prp-36-41.smt2                                                                              |  24.995s  |  24.995s  |   0.000s  | 0.0%|
|prp-36-45.smt2                                                                              |   5.681s  |   5.681s  |   0.000s  | 0.0%|
|prp-36-48.smt2                                                                              | 110.939s  | 110.939s  |   0.000s  | 0.0%|
|prp-37-40.smt2                                                                              |   1.848s  |   1.848s  |   0.000s  | 0.0%|
|prp-37-42.smt2                                                                              |  15.241s  |  15.241s  |   0.000s  | 0.0%|
|prp-37-48.smt2                                                                              |   0.341s  |   0.341s  |   0.000s  | 0.0%|
|prp-37-49.smt2                                                                              |   0.384s  |   0.384s  |   0.000s  | 0.0%|
|prp-38-40.smt2                                                                              |  21.559s  |  21.559s  |   0.000s  | 0.0%|
|prp-38-42.smt2                                                                              |  24.598s  |  24.598s  |   0.000s  | 0.0%|
|prp-38-47.smt2                                                                              |   0.316s  |   0.316s  |   0.000s  | 0.0%|
|prp-39-50.smt2                                                                              |   0.393s  |   0.393s  |   0.000s  | 0.0%|
|prp-4-42.smt2                                                                               |  20.096s  |  20.096s  |   0.000s  | 0.0%|
|prp-4-46.smt2                                                                               |   0.894s  |   0.894s  |   0.000s  | 0.0%|
|prp-4-47.smt2                                                                               |   3.159s  |   3.159s  |   0.000s  | 0.0%|
|prp-4-48.smt2                                                                               |  40.968s  |  40.968s  |   0.000s  | 0.0%|
|prp-4-49.smt2                                                                               |  45.536s  |  45.536s  |   0.000s  | 0.0%|
|prp-4-50.smt2                                                                               |  12.658s  |  12.658s  |   0.000s  | 0.0%|
|prp-40-37.smt2                                                                              |  11.087s  |  11.087s  |   0.000s  | 0.0%|
|prp-40-46.smt2                                                                              |  11.454s  |  11.454s  |   0.000s  | 0.0%|
|prp-40-47.smt2                                                                              |  14.489s  |  14.489s  |   0.000s  | 0.0%|
|prp-40-48.smt2                                                                              |   0.344s  |   0.344s  |   0.000s  | 0.0%|
|prp-41-38.smt2                                                                              |   1.824s  |   1.824s  |   0.000s  | 0.0%|
|prp-41-39.smt2                                                                              |   1.947s  |   1.947s  |   0.000s  | 0.0%|
|prp-41-45.smt2                                                                              |  37.239s  |  37.239s  |   0.000s  | 0.0%|
|prp-41-47.smt2                                                                              |  20.316s  |  20.316s  |   0.000s  | 0.0%|
|prp-41-48.smt2                                                                              |  16.709s  |  16.709s  |   0.000s  | 0.0%|
|prp-41-49.smt2                                                                              |   0.387s  |   0.387s  |   0.000s  | 0.0%|
|prp-42-40.smt2                                                                              |   3.679s  |   3.679s  |   0.000s  | 0.0%|
|prp-42-41.smt2                                                                              |  20.062s  |  20.062s  |   0.000s  | 0.0%|
|prp-42-42.smt2                                                                              |   5.901s  |   5.901s  |   0.000s  | 0.0%|
|prp-42-43.smt2                                                                              |   2.992s  |   2.992s  |   0.000s  | 0.0%|
|prp-42-44.smt2                                                                              |  39.037s  |  39.037s  |   0.000s  | 0.0%|
|prp-42-46.smt2                                                                              |  11.372s  |  11.372s  |   0.000s  | 0.0%|
|prp-43-42.smt2                                                                              |   3.462s  |   3.462s  |   0.000s  | 0.0%|
|prp-43-46.smt2                                                                              |   0.297s  |   0.297s  |   0.000s  | 0.0%|
|prp-43-47.smt2                                                                              | 123.615s  | 123.615s  |   0.000s  | 0.0%|
|prp-43-48.smt2                                                                              |  59.426s  |  59.426s  |   0.000s  | 0.0%|
|prp-43-49.smt2                                                                              |  37.695s  |  37.695s  |   0.000s  | 0.0%|
|prp-43-50.smt2                                                                              |   0.417s  |   0.417s  |   0.000s  | 0.0%|
|prp-44-39.smt2                                                                              |  18.396s  |  18.396s  |   0.000s  | 0.0%|
|prp-44-44.smt2                                                                              |  35.799s  |  35.799s  |   0.000s  | 0.0%|
|prp-44-48.smt2                                                                              |   0.332s  |   0.332s  |   0.000s  | 0.0%|
|prp-44-49.smt2                                                                              | 165.157s  | 165.157s  |   0.000s  | 0.0%|
|prp-45-42.smt2                                                                              |  24.025s  |  24.025s  |   0.000s  | 0.0%|
|prp-46-47.smt2                                                                              |  15.916s  |  15.916s  |   0.000s  | 0.0%|
|prp-46-48.smt2                                                                              | 245.329s  | 245.329s  |   0.000s  | 0.0%|
|prp-47-41.smt2                                                                              |  20.166s  |  20.166s  |   0.000s  | 0.0%|
|prp-47-46.smt2                                                                              |   0.892s  |   0.892s  |   0.000s  | 0.0%|
|prp-47-47.smt2                                                                              |   8.657s  |   8.657s  |   0.000s  | 0.0%|
|prp-47-48.smt2                                                                              |  69.261s  |  69.261s  |   0.000s  | 0.0%|
|prp-47-50.smt2                                                                              | 445.798s  | 445.798s  |   0.000s  | 0.0%|
|prp-48-46.smt2                                                                              |   6.975s  |   6.975s  |   0.000s  | 0.0%|
|prp-48-47.smt2                                                                              |  10.547s  |  10.547s  |   0.000s  | 0.0%|
|prp-48-49.smt2                                                                              | 201.524s  | 201.524s  |   0.000s  | 0.0%|
|prp-48-50.smt2                                                                              |  92.933s  |  92.933s  |   0.000s  | 0.0%|
|prp-49-42.smt2                                                                              |  34.854s  |  34.854s  |   0.000s  | 0.0%|
|prp-49-47.smt2                                                                              |  14.765s  |  14.765s  |   0.000s  | 0.0%|
|prp-49-49.smt2                                                                              |   0.375s  |   0.375s  |   0.000s  | 0.0%|
|prp-5-35.smt2                                                                               |   3.687s  |   3.687s  |   0.000s  | 0.0%|
|prp-5-46.smt2                                                                               |  18.639s  |  18.639s  |   0.000s  | 0.0%|
|prp-5-47.smt2                                                                               |   0.316s  |   0.316s  |   0.000s  | 0.0%|
|prp-5-48.smt2                                                                               |  15.864s  |  15.864s  |   0.000s  | 0.0%|
|prp-5-49.smt2                                                                               |  18.863s  |  18.863s  |   0.000s  | 0.0%|
|prp-5-50.smt2                                                                               |   0.420s  |   0.420s  |   0.000s  | 0.0%|
|prp-51-44.smt2                                                                              |  37.467s  |  37.467s  |   0.000s  | 0.0%|
|prp-51-46.smt2                                                                              |  11.152s  |  11.152s  |   0.000s  | 0.0%|
|prp-51-48.smt2                                                                              |  52.116s  |  52.116s  |   0.000s  | 0.0%|
|prp-52-46.smt2                                                                              |  38.362s  |  38.362s  |   0.000s  | 0.0%|
|prp-52-47.smt2                                                                              |   9.010s  |   9.010s  |   0.000s  | 0.0%|
|prp-52-48.smt2                                                                              |  19.841s  |  19.841s  |   0.000s  | 0.0%|
|prp-52-50.smt2                                                                              |  13.749s  |  13.749s  |   0.000s  | 0.0%|
|prp-53-45.smt2                                                                              |   8.014s  |   8.014s  |   0.000s  | 0.0%|
|prp-53-46.smt2                                                                              |  44.131s  |  44.131s  |   0.000s  | 0.0%|
|prp-53-48.smt2                                                                              |  49.745s  |  49.745s  |   0.000s  | 0.0%|
|prp-53-50.smt2                                                                              |  41.211s  |  41.211s  |   0.000s  | 0.0%|
|prp-54-45.smt2                                                                              |  34.549s  |  34.549s  |   0.000s  | 0.0%|
|prp-54-46.smt2                                                                              |   0.476s  |   0.476s  |   0.000s  | 0.0%|
|prp-54-47.smt2                                                                              |   0.521s  |   0.521s  |   0.000s  | 0.0%|
|prp-54-50.smt2                                                                              |   0.612s  |   0.612s  |   0.000s  | 0.0%|
|prp-55-46.smt2                                                                              |  44.187s  |  44.187s  |   0.000s  | 0.0%|
|prp-55-48.smt2                                                                              |   0.607s  |   0.607s  |   0.000s  | 0.0%|
|prp-55-49.smt2                                                                              |  65.094s  |  65.094s  |   0.000s  | 0.0%|
|prp-55-50.smt2                                                                              |   0.427s  |   0.427s  |   0.000s  | 0.0%|
|prp-56-47.smt2                                                                              |  47.289s  |  47.289s  |   0.000s  | 0.0%|
|prp-57-46.smt2                                                                              |   0.856s  |   0.856s  |   0.000s  | 0.0%|
|prp-57-47.smt2                                                                              |   0.967s  |   0.967s  |   0.000s  | 0.0%|
|prp-57-48.smt2                                                                              |   0.520s  |   0.520s  |   0.000s  | 0.0%|
|prp-57-49.smt2                                                                              |   3.066s  |   3.066s  |   0.000s  | 0.0%|
|prp-58-46.smt2                                                                              |  12.386s  |  12.386s  |   0.000s  | 0.0%|
|prp-58-47.smt2                                                                              |  49.278s  |  49.278s  |   0.000s  | 0.0%|
|prp-58-48.smt2                                                                              |  18.910s  |  18.910s  |   0.000s  | 0.0%|
|prp-58-50.smt2                                                                              |   3.201s  |   3.201s  |   0.000s  | 0.0%|
|prp-59-48.smt2                                                                              |   0.544s  |   0.544s  |   0.000s  | 0.0%|
|prp-6-46.smt2                                                                               |  70.976s  |  70.976s  |   0.000s  | 0.0%|
|prp-6-47.smt2                                                                               |  46.991s  |  46.991s  |   0.000s  | 0.0%|
|prp-6-48.smt2                                                                               |   3.945s  |   3.945s  |   0.000s  | 0.0%|
|prp-60-46.smt2                                                                              |   4.330s  |   4.330s  |   0.000s  | 0.0%|
|prp-60-47.smt2                                                                              |   4.684s  |   4.684s  |   0.000s  | 0.0%|
|prp-60-48.smt2                                                                              |  56.789s  |  56.789s  |   0.000s  | 0.0%|
|prp-61-49.smt2                                                                              |  23.930s  |  23.930s  |   0.000s  | 0.0%|
|prp-62-47.smt2                                                                              |   5.532s  |   5.532s  |   0.000s  | 0.0%|
|prp-62-49.smt2                                                                              |  10.096s  |  10.096s  |   0.000s  | 0.0%|
|prp-62-50.smt2                                                                              |  88.528s  |  88.528s  |   0.000s  | 0.0%|
|prp-63-48.smt2                                                                              |   6.072s  |   6.072s  |   0.000s  | 0.0%|
|prp-63-49.smt2                                                                              |  29.811s  |  29.811s  |   0.000s  | 0.0%|
|prp-63-50.smt2                                                                              |   3.707s  |   3.707s  |   0.000s  | 0.0%|
|prp-64-49.smt2                                                                              |  21.540s  |  21.540s  |   0.000s  | 0.0%|
|prp-64-50.smt2                                                                              |  28.767s  |  28.767s  |   0.000s  | 0.0%|
|prp-65-48.smt2                                                                              |  18.192s  |  18.192s  |   0.000s  | 0.0%|
|prp-67-47.smt2                                                                              |  14.590s  |  14.590s  |   0.000s  | 0.0%|
|prp-67-50.smt2                                                                              |  30.446s  |  30.446s  |   0.000s  | 0.0%|
|prp-7-35.smt2                                                                               |   4.817s  |   4.817s  |   0.000s  | 0.0%|
|prp-7-37.smt2                                                                               |   5.256s  |   5.256s  |   0.000s  | 0.0%|
|prp-7-41.smt2                                                                               |  14.373s  |  14.373s  |   0.000s  | 0.0%|
|prp-7-44.smt2                                                                               |  15.163s  |  15.163s  |   0.000s  | 0.0%|
|prp-7-46.smt2                                                                               | 239.793s  | 239.793s  |   0.000s  | 0.0%|
|prp-7-47.smt2                                                                               | 159.129s  | 159.129s  |   0.000s  | 0.0%|
|prp-7-48.smt2                                                                               |   3.015s  |   3.015s  |   0.000s  | 0.0%|
|prp-7-50.smt2                                                                               |  57.980s  |  57.980s  |   0.000s  | 0.0%|
|prp-73-50.smt2                                                                              |   8.479s  |   8.479s  |   0.000s  | 0.0%|
|prp-75-48.smt2                                                                              |  20.384s  |  20.384s  |   0.000s  | 0.0%|
|prp-8-34.smt2                                                                               |   4.375s  |   4.375s  |   0.000s  | 0.0%|
|prp-8-36.smt2                                                                               |   7.409s  |   7.409s  |   0.000s  | 0.0%|
|prp-8-38.smt2                                                                               |   9.769s  |   9.769s  |   0.000s  | 0.0%|
|prp-8-46.smt2                                                                               |  27.879s  |  27.879s  |   0.000s  | 0.0%|
|prp-8-47.smt2                                                                               | 212.321s  | 212.321s  |   0.000s  | 0.0%|
|prp-8-48.smt2                                                                               |  87.160s  |  87.160s  |   0.000s  | 0.0%|
|prp-8-49.smt2                                                                               | 275.040s  | 275.040s  |   0.000s  | 0.0%|
|prp-8-50.smt2                                                                               |   4.356s  |   4.356s  |   0.000s  | 0.0%|
|prp-81-50.smt2                                                                              |  29.199s  |  29.199s  |   0.000s  | 0.0%|
|prp-9-47.smt2                                                                               |   2.007s  |   2.007s  |   0.000s  | 0.0%|
|prp-9-49.smt2                                                                               |  14.850s  |  14.850s  |   0.000s  | 0.0%|
|prp-9-50.smt2                                                                               |   0.425s  |   0.425s  |   0.000s  | 0.0%|
|terminator_02-1-O0.smt2                                                                     |   0.312s  |   0.312s  |   0.000s  | 0.0%|
|unbd-sage0.smt2                                                                             | 600.066s  | 600.066s  |   0.000s  | 0.0%|
|unbd-sage1.smt2                                                                             | 600.062s  | 600.062s  |   0.000s  | 0.0%|
|unbd-sage12.smt2                                                                            | 600.072s  | 600.072s  |   0.000s  | 0.0%|
|unbd-sage17.smt2                                                                            | 600.065s  | 600.065s  |   0.000s  | 0.0%|
|unbd-sage22.smt2                                                                            | 600.075s  | 600.075s  |   0.000s  | 0.0%|
</details>
