# .

* SAT 1205
* UNSAT 550
* TIMEOUT 558
* UNKNOWN 0

* UNSET 0

* ERROR 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-parallel-separate-searchtree-no-conflict-sharing
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: e140965b90431c3ac3bd1ea6a21192901340cb80
Z3 branch: ilana
Z3 options: "-T:30 tactic.default_tactic=smt smt.threads=4 smt_parallel.searchtree=true smt_parallel.share_conflicts=false smt_parallel.share_units=false"
Z3 inputs: inputs/QF_NIA_small
Z3 commit message: Parallel solving (#7860)

* very basic setup

* ensure solve_eqs is fully disabled when smt.solve_eqs=false, #7743

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* respect smt configuration parameter in elim_unconstrained simplifier

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* indentation

* add bash files for test runs

* add option to selectively disable variable solving for only ground expressions

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* remove verbose output

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* fix #7745

axioms for len(substr(...)) escaped due to nested rewriting

* ensure atomic constraints are processed by arithmetic solver

* #7739 optimization

add simplification rule for at(x, offset) = ""

Introducing j just postpones some rewrites that prevent useful simplifications. Z3 already uses common sub-expressions.
The example highlights some opportunities for simplification, noteworthy at(..) = "".
The example is solved in both versions after adding this simplification.

* fix unsound len(substr) axiom

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* FreshConst is_sort (#7748)

* #7750

add pre-processing simplification

* Add parameter validation for selected API functions

* updates to ac-plugin

fix incrementality bugs by allowing destructive updates during saturation at the cost of redoing saturation after a pop.

* enable passive, add check for bloom up-to-date

* add top-k fixed-sized min-heap priority queue for top scoring literals

* set up worker thread batch manager for multithreaded batch cubes paradigm, need to debug as I am getting segfault still

* fix bug in parallel solving batch setup

* fix bug

* allow for internalize implies

* disable pre-processing during cubing

* debugging

* remove default constructor

* remove a bunch of string copies

* Update euf_ac_plugin.cpp

include reduction rules in forward simplification

* Update euf_completion.cpp

try out restricting scope of equalities added by instantation

* Update smt_parallel.cpp

Drop non-relevant units from shared structures.

* process cubes as lists of individual lits

* merge

* Add support for Algebraic Datatypes in JavaScript/TypeScript bindings (#7734)

* Initial plan

* Add datatype type definitions to types.ts (work in progress)

Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

* Complete datatype type definitions with working TypeScript compilation

Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

* Implement core datatype functionality with TypeScript compilation success

Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

* Complete datatype implementation with full Context integration and tests

Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

---------

Co-authored-by: copilot-swe-agent[bot] <198982749+Copilot@users.noreply.github.com>
Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

* chipping away at the new code structure

* comments

* debug infinite recursion and split cubes on existing split atoms that aren't in the cube

* share lemmas, learn from unsat core, try to debug a couple of things, there was a subtle bug that i have a hard time repro'ing

* merge

* fix #7603: race condition in Ctrl-C handling (#7755)

* fix #7603: race condition in Ctrl-C handling

* fix race in cancel_eh

* fix build

* add arithemtic saturation

* add an option to register callback on quantifier instantiation

Suppose a user propagator encodes axioms using quantifiers and uses E-matching for instantiation. If it wants to implement a custom priority scheme or drop some instances based on internal checks it can register a callback with quantifier instantiation

* missing new closure

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* add Z3_solver_propagate_on_binding to ml callback declarations

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* add python file

Signed-off-by: Lev Nachmanson <levnach@Levs-MacBook-Pro.local>

* debug under defined calls

Signed-off-by: Lev Nachmanson <levnach@hotmail.com>

* more untangle params

Signed-off-by: Lev Nachmanson <levnach@hotmail.com>

* precalc parameters to define the eval order

Signed-off-by: Lev Nachmanson <levnach@hotmail.com>

* remove a printout

Signed-off-by: Lev Nachmanson <levnach@hotmail.com>

* rename a Python file

Signed-off-by: Lev Nachmanson <levnach@hotmail.com>

* add on_binding callbacks across APIs

update release notes,
add to Java, .Net, C++

* use jboolean in Native interface

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* register on_binding attribute

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* fix java build for java bindings

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* avoid interferring side-effects in function calls

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* remove theory_str and classes that are only used by it

* remove automata from python build

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* remove ref to theory_str

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* get the finest factorizations before project

Signed-off-by: Lev Nachmanson <levnach@hotmail.com>

* rename add_lcs to add_lc

Signed-off-by: Lev Nachmanson <levnach@hotmail.com>

* resolve bad bug about l2g and g2l translators using wrong global context. add some debug prints

* initial attempt at dynamically switching from greedy to frugal splitting strategy in return_cubes. need to test. also there is some bug where the threads take forever to cancel?

* Update RELEASE_NOTES.md

* resolve bug about not translating managers correctly for the second phase of the greedy cubing, and the frugal fallback

* remove unused square-free check

Signed-off-by: Lev Nachmanson <levnach@hotmail.com>

* add some debug prints and impelement internal polynomial fix

* restore the square-free check

Signed-off-by: Lev Nachmanson <levnach@hotmail.com>

* add some comments and debug m_assumptions_used

* redo greedy->frugal strategy so we don't split on existing cubes in frugal at all (eliminate the incorrect/wasteful step by processing current batch first)

* set up initial scaffolding for sharing clauses between threads and batch manager. needs some reworking/debug still

* Add .github/copilot-instructions.md with comprehensive Z3 development guide (#7766)

* Initial plan

* Add comprehensive .github/copilot-instructions.md with validated build commands and timing

Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

* Remove test_example binary file from repository

Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

---------

Co-authored-by: copilot-swe-agent[bot] <198982749+Copilot@users.noreply.github.com>
Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

* Bump actions/checkout from 4 to 5 (#7773)

Bumps [actions/checkout](https://github.com/actions/checkout) from 4 to 5.
- [Release notes](https://github.com/actions/checkout/releases)
- [Changelog](https://github.com/actions/checkout/blob/main/CHANGELOG.md)
- [Commits](https://github.com/actions/checkout/compare/v4...v5)

---
updated-dependencies:
- dependency-name: actions/checkout
  dependency-version: '5'
  dependency-type: direct:production
  update-type: version-update:semver-major
...

Signed-off-by: dependabot[bot] <support@github.com>
Co-authored-by: dependabot[bot] <49699333+dependabot[bot]@users.noreply.github.com>

* turn off logging at level 0 for testing

* add max thread conflicts backoff

* Parallel solving (#7775)

* very basic setup

* very basic setup (#7741)

* add score access and reset

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* added notes

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* Update PARALLEL_PROJECT_NOTES.md

* Update PARALLEL_PROJECT_NOTES.md

* Update PARALLEL_PROJECT_NOTES.md

* add bash files for test runs

* fix compilation

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* more notes

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* Update PARALLEL_PROJECT_NOTES.md

* Update PARALLEL_PROJECT_NOTES.md

* Update PARALLEL_PROJECT_NOTES.md

* Update PARALLEL_PROJECT_NOTES.md

* Update PARALLEL_PROJECT_NOTES.md

* Update PARALLEL_PROJECT_NOTES.md

* Update PARALLEL_PROJECT_NOTES.md

* Update PARALLEL_PROJECT_NOTES.md

* Update PARALLEL_PROJECT_NOTES.md

* add top-k fixed-sized min-heap priority queue for top scoring literals

* fixed-size min-heap for tracking top-k literals (#7752)

* very basic setup

* ensure solve_eqs is fully disabled when smt.solve_eqs=false, #7743

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* respect smt configuration parameter in elim_unconstrained simplifier

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* indentation

* add bash files for test runs

* add option to selectively disable variable solving for only ground expressions

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* remove verbose output

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* fix #7745

axioms for len(substr(...)) escaped due to nested rewriting

* ensure atomic constraints are processed by arithmetic solver

* #7739 optimization

add simplification rule for at(x, offset) = ""

Introducing j just postpones some rewrites that prevent useful simplifications. Z3 already uses common sub-expressions.
The example highlights some opportunities for simplification, noteworthy at(..) = "".
The example is solved in both versions after adding this simplification.

* fix unsound len(substr) axiom

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* FreshConst is_sort (#7748)

* #7750

add pre-processing simplification

* Add parameter validation for selected API functions

* updates to ac-plugin

fix incrementality bugs by allowing destructive updates during saturation at the cost of redoing saturation after a pop.

* enable passive, add check for bloom up-to-date

* add top-k fixed-sized min-heap priority queue for top scoring literals

---------

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>
Co-authored-by: Nikolaj Bjorner <nbjorner@microsoft.com>
Co-authored-by: humnrdble <83878671+humnrdble@users.noreply.github.com>

* set up worker thread batch manager for multithreaded batch cubes paradigm, need to debug as I am getting segfault still

* fix bug in parallel solving batch setup

* fix bug

* debugging

* process cubes as lists of individual lits

* Parallel solving (#7756)

* very basic setup

* ensure solve_eqs is fully disabled when smt.solve_eqs=false, #7743

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* respect smt configuration parameter in elim_unconstrained simplifier

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* indentation

* add bash files for test runs

* add option to selectively disable variable solving for only ground expressions

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* remove verbose output

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* fix #7745

axioms for len(substr(...)) escaped due to nested rewriting

* ensure atomic constraints are processed by arithmetic solver

* #7739 optimization

add simplification rule for at(x, offset) = ""

Introducing j just postpones some rewrites that prevent useful simplifications. Z3 already uses common sub-expressions.
The example highlights some opportunities for simplification, noteworthy at(..) = "".
The example is solved in both versions after adding this simplification.

* fix unsound len(substr) axiom

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* FreshConst is_sort (#7748)

* #7750

add pre-processing simplification

* Add parameter validation for selected API functions

* updates to ac-plugin

fix incrementality bugs by allowing destructive updates during saturation at the cost of redoing saturation after a pop.

* enable passive, add check for bloom up-to-date

* add top-k fixed-sized min-heap priority queue for top scoring literals

* set up worker thread batch manager for multithreaded batch cubes paradigm, need to debug as I am getting segfault still

* fix bug in parallel solving batch setup

* fix bug

* allow for internalize implies

* disable pre-processing during cubing

* debugging

* process cubes as lists of individual lits

---------

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>
Co-authored-by: Nikolaj Bjorner <nbjorner@microsoft.com>
Co-authored-by: humnrdble <83878671+humnrdble@users.noreply.github.com>

* snapshot

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* pair programming

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* pair programming

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* merge

* chipping away at the new code structure

* Parallel solving (#7758)

* very basic setup

* ensure solve_eqs is fully disabled when smt.solve_eqs=false, #7743

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* respect smt configuration parameter in elim_unconstrained simplifier

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* indentation

* add bash files for test runs

* add option to selectively disable variable solving for only ground expressions

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* remove verbose output

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* fix #7745

axioms for len(substr(...)) escaped due to nested rewriting

* ensure atomic constraints are processed by arithmetic solver

* #7739 optimization

add simplification rule for at(x, offset) = ""

Introducing j just postpones some rewrites that prevent useful simplifications. Z3 already uses common sub-expressions.
The example highlights some opportunities for simplification, noteworthy at(..) = "".
The example is solved in both versions after adding this simplification.

* fix unsound len(substr) axiom

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* FreshConst is_sort (#7748)

* #7750

add pre-processing simplification

* Add parameter validation for selected API functions

* updates to ac-plugin

fix incrementality bugs by allowing destructive updates during saturation at the cost of redoing saturation after a pop.

* enable passive, add check for bloom up-to-date

* add top-k fixed-sized min-heap priority queue for top scoring literals

* set up worker thread batch manager for multithreaded batch cubes paradigm, need to debug as I am getting segfault still

* fix bug in parallel solving batch setup

* fix bug

* allow for internalize implies

* disable pre-processing during cubing

* debugging

* remove default constructor

* remove a bunch of string copies

* Update euf_ac_plugin.cpp

include reduction rules in forward simplification

* Update euf_completion.cpp

try out restricting scope of equalities added by instantation

* Update smt_parallel.cpp

Drop non-relevant units from shared structures.

* process cubes as lists of individual lits

* merge

* Add support for Algebraic Datatypes in JavaScript/TypeScript bindings (#7734)

* Initial plan

* Add datatype type definitions to types.ts (work in progress)

Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

* Complete datatype type definitions with working TypeScript compilation

Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

* Implement core datatype functionality with TypeScript compilation success

Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

* Complete datatype implementation with full Context integration and tests

Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

---------

Co-authored-by: copilot-swe-agent[bot] <198982749+Copilot@users.noreply.github.com>
Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

* chipping away at the new code structure

---------

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>
Co-authored-by: Nikolaj Bjorner <nbjorner@microsoft.com>
Co-authored-by: humnrdble <83878671+humnrdble@users.noreply.github.com>
Co-authored-by: Nuno Lopes <nuno.lopes@tecnico.ulisboa.pt>
Co-authored-by: Copilot <198982749+Copilot@users.noreply.github.com>
Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

* updates

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* comments

* debug infinite recursion and split cubes on existing split atoms that aren't in the cube

* share lemmas, learn from unsat core, try to debug a couple of things, there was a subtle bug that i have a hard time repro'ing

* Parallel solving (#7759)

* very basic setup

* ensure solve_eqs is fully disabled when smt.solve_eqs=false, #7743

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* respect smt configuration parameter in elim_unconstrained simplifier

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* indentation

* add bash files for test runs

* add option to selectively disable variable solving for only ground expressions

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* remove verbose output

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* fix #7745

axioms for len(substr(...)) escaped due to nested rewriting

* ensure atomic constraints are processed by arithmetic solver

* #7739 optimization

add simplification rule for at(x, offset) = ""

Introducing j just postpones some rewrites that prevent useful simplifications. Z3 already uses common sub-expressions.
The example highlights some opportunities for simplification, noteworthy at(..) = "".
The example is solved in both versions after adding this simplification.

* fix unsound len(substr) axiom

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* FreshConst is_sort (#7748)

* #7750

add pre-processing simplification

* Add parameter validation for selected API functions

* updates to ac-plugin

fix incrementality bugs by allowing destructive updates during saturation at the cost of redoing saturation after a pop.

* enable passive, add check for bloom up-to-date

* add top-k fixed-sized min-heap priority queue for top scoring literals

* set up worker thread batch manager for multithreaded batch cubes paradigm, need to debug as I am getting segfault still

* fix bug in parallel solving batch setup

* fix bug

* allow for internalize implies

* disable pre-processing during cubing

* debugging

* remove default constructor

* remove a bunch of string copies

* Update euf_ac_plugin.cpp

include reduction rules in forward simplification

* Update euf_completion.cpp

try out restricting scope of equalities added by instantation

* Update smt_parallel.cpp

Drop non-relevant units from shared structures.

* process cubes as lists of individual lits

* merge

* Add support for Algebraic Datatypes in JavaScript/TypeScript bindings (#7734)

* Initial plan

* Add datatype type definitions to types.ts (work in progress)

Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

* Complete datatype type definitions with working TypeScript compilation

Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

* Implement core datatype functionality with TypeScript compilation success

Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

* Complete datatype implementation with full Context integration and tests

Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

---------

Co-authored-by: copilot-swe-agent[bot] <198982749+Copilot@users.noreply.github.com>
Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

* chipping away at the new code structure

* comments

* debug infinite recursion and split cubes on existing split atoms that aren't in the cube

* share lemmas, learn from unsat core, try to debug a couple of things, there was a subtle bug that i have a hard time repro'ing

---------

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>
Co-authored-by: Nikolaj Bjorner <nbjorner@microsoft.com>
Co-authored-by: humnrdble <83878671+humnrdble@users.noreply.github.com>
Co-authored-by: Nuno Lopes <nuno.lopes@tecnico.ulisboa.pt>
Co-authored-by: Copilot <198982749+Copilot@users.noreply.github.com>
Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

* updates

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* simplify output

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* merge

* resolve bad bug about l2g and g2l translators using wrong global context. add some debug prints

* initial attempt at dynamically switching from greedy to frugal splitting strategy in return_cubes. need to test. also there is some bug where the threads take forever to cancel?

* Parallel solving (#7769)

* very basic setup

* ensure solve_eqs is fully disabled when smt.solve_eqs=false, #7743

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* respect smt configuration parameter in elim_unconstrained simplifier

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* indentation

* add bash files for test runs

* add option to selectively disable variable solving for only ground expressions

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* remove verbose output

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* fix #7745

axioms for len(substr(...)) escaped due to nested rewriting

* ensure atomic constraints are processed by arithmetic solver

* #7739 optimization

add simplification rule for at(x, offset) = ""

Introducing j just postpones some rewrites that prevent useful simplifications. Z3 already uses common sub-expressions.
The example highlights some opportunities for simplification, noteworthy at(..) = "".
The example is solved in both versions after adding this simplification.

* fix unsound len(substr) axiom

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* FreshConst is_sort (#7748)

* #7750

add pre-processing simplification

* Add parameter validation for selected API functions

* updates to ac-plugin

fix incrementality bugs by allowing destructive updates during saturation at the cost of redoing saturation after a pop.

* enable passive, add check for bloom up-to-date

* add top-k fixed-sized min-heap priority queue for top scoring literals

* set up worker thread batch manager for multithreaded batch cubes paradigm, need to debug as I am getting segfault still

* fix bug in parallel solving batch setup

* fix bug

* allow for internalize implies

* disable pre-processing during cubing

* debugging

* remove default constructor

* remove a bunch of string copies

* Update euf_ac_plugin.cpp

include reduction rules in forward simplification

* Update euf_completion.cpp

try out restricting scope of equalities added by instantation

* Update smt_parallel.cpp

Drop non-relevant units from shared structures.

* process cubes as lists of individual lits

* merge

* Add support for Algebraic Datatypes in JavaScript/TypeScript bindings (#7734)

* Initial plan

* Add datatype type definitions to types.ts (work in progress)

Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

* Complete datatype type definitions with working TypeScript compilation

Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

* Implement core datatype functionality with TypeScript compilation success

Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

* Complete datatype implementation with full Context integration and tests

Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

---------

Co-authored-by: copilot-swe-agent[bot] <198982749+Copilot@users.noreply.github.com>
Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

* chipping away at the new code structure

* comments

* debug infinite recursion and split cubes on existing split atoms that aren't in the cube

* share lemmas, learn from unsat core, try to debug a couple of things, there was a subtle bug that i have a hard time repro'ing

* merge

* resolve bad bug about l2g and g2l translators using wrong global context. add some debug prints

* initial attempt at dynamically switching from greedy to frugal splitting strategy in return_cubes. need to test. also there is some bug where the threads take forever to cancel?

---------

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>
Co-authored-by: Nikolaj Bjorner <nbjorner@microsoft.com>
Co-authored-by: humnrdble <83878671+humnrdble@users.noreply.github.com>
Co-authored-by: Nuno Lopes <nuno.lopes@tecnico.ulisboa.pt>
Co-authored-by: Copilot <198982749+Copilot@users.noreply.github.com>
Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

* resolve bug about not translating managers correctly for the second phase of the greedy cubing, and the frugal fallback

* Parallel solving (#7771)

* very basic setup

* ensure solve_eqs is fully disabled when smt.solve_eqs=false, #7743

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* respect smt configuration parameter in elim_unconstrained simplifier

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* indentation

* add bash files for test runs

* add option to selectively disable variable solving for only ground expressions

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* remove verbose output

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* fix #7745

axioms for len(substr(...)) escaped due to nested rewriting

* ensure atomic constraints are processed by arithmetic solver

* #7739 optimization

add simplification rule for at(x, offset) = ""

Introducing j just postpones some rewrites that prevent useful simplifications. Z3 already uses common sub-expressions.
The example highlights some opportunities for simplification, noteworthy at(..) = "".
The example is solved in both versions after adding this simplification.

* fix unsound len(substr) axiom

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* FreshConst is_sort (#7748)

* #7750

add pre-processing simplification

* Add parameter validation for selected API functions

* updates to ac-plugin

fix incrementality bugs by allowing destructive updates during saturation at the cost of redoing saturation after a pop.

* enable passive, add check for bloom up-to-date

* add top-k fixed-sized min-heap priority queue for top scoring literals

* set up worker thread batch manager for multithreaded batch cubes paradigm, need to debug as I am getting segfault still

* fix bug in parallel solving batch setup

* fix bug

* allow for internalize implies

* disable pre-processing during cubing

* debugging

* remove default constructor

* remove a bunch of string copies

* Update euf_ac_plugin.cpp

include reduction rules in forward simplification

* Update euf_completion.cpp

try out restricting scope of equalities added by instantation

* Update smt_parallel.cpp

Drop non-relevant units from shared structures.

* process cubes as lists of individual lits

* merge

* Add support for Algebraic Datatypes in JavaScript/TypeScript bindings (#7734)

* Initial plan

* Add datatype type definitions to types.ts (work in progress)

Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

* Complete datatype type definitions with working TypeScript compilation

Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

* Implement core datatype functionality with TypeScript compilation success

Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

* Complete datatype implementation with full Context integration and tests

Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

---------

Co-authored-by: copilot-swe-agent[bot] <198982749+Copilot@users.noreply.github.com>
Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

* chipping away at the new code structure

* comments

* debug infinite recursion and split cubes on existing split atoms that aren't in the cube

* share lemmas, learn from unsat core, try to debug a couple of things, there was a subtle bug that i have a hard time repro'ing

* merge

* fix #7603: race condition in Ctrl-C handling (#7755)

* fix #7603: race condition in Ctrl-C handling

* fix race in cancel_eh

* fix build

* add arithemtic saturation

* add an option to register callback on quantifier instantiation

Suppose a user propagator encodes axioms using quantifiers and uses E-matching for instantiation. If it wants to implement a custom priority scheme or drop some instances based on internal checks it can register a callback with quantifier instantiation

* missing new closure

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* add Z3_solver_propagate_on_binding to ml callback declarations

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* add python file

Signed-off-by: Lev Nachmanson <levnach@Levs-MacBook-Pro.local>

* debug under defined calls

Signed-off-by: Lev Nachmanson <levnach@hotmail.com>

* more untangle params

Signed-off-by: Lev Nachmanson <levnach@hotmail.com>

* precalc parameters to define the eval order

Signed-off-by: Lev Nachmanson <levnach@hotmail.com>

* remove a printout

Signed-off-by: Lev Nachmanson <levnach@hotmail.com>

* rename a Python file

Signed-off-by: Lev Nachmanson <levnach@hotmail.com>

* add on_binding callbacks across APIs

update release notes,
add to Java, .Net, C++

* use jboolean in Native interface

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* register on_binding attribute

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* fix java build for java bindings

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* avoid interferring side-effects in function calls

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* remove theory_str and classes that are only used by it

* remove automata from python build

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* remove ref to theory_str

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* get the finest factorizations before project

Signed-off-by: Lev Nachmanson <levnach@hotmail.com>

* rename add_lcs to add_lc

Signed-off-by: Lev Nachmanson <levnach@hotmail.com>

* resolve bad bug about l2g and g2l translators using wrong global context. add some debug prints

* initial attempt at dynamically switching from greedy to frugal splitting strategy in return_cubes. need to test. also there is some bug where the threads take forever to cancel?

* Update RELEASE_NOTES.md

* resolve bug about not translating managers correctly for the second phase of the greedy cubing, and the frugal fallback

---------

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>
Signed-off-by: Lev Nachmanson <levnach@Levs-MacBook-Pro.local>
Signed-off-by: Lev Nachmanson <levnach@hotmail.com>
Co-authored-by: Nikolaj Bjorner <nbjorner@microsoft.com>
Co-authored-by: humnrdble <83878671+humnrdble@users.noreply.github.com>
Co-authored-by: Nuno Lopes <nuno.lopes@tecnico.ulisboa.pt>
Co-authored-by: Copilot <198982749+Copilot@users.noreply.github.com>
Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>
Co-authored-by: Lev Nachmanson <levnach@hotmail.com>

* code and notes

* add some debug prints and impelement internal polynomial fix

* add some comments and debug m_assumptions_used

* redo greedy->frugal strategy so we don't split on existing cubes in frugal at all (eliminate the incorrect/wasteful step by processing current batch first)

* set up initial scaffolding for sharing clauses between threads and batch manager. needs some reworking/debug still

* Parallel solving (#7774)

* very basic setup

* ensure solve_eqs is fully disabled when smt.solve_eqs=false, #7743

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* respect smt configuration parameter in elim_unconstrained simplifier

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* indentation

* add bash files for test runs

* add option to selectively disable variable solving for only ground expressions

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* remove verbose output

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* fix #7745

axioms for len(substr(...)) escaped due to nested rewriting

* ensure atomic constraints are processed by arithmetic solver

* #7739 optimization

add simplification rule for at(x, offset) = ""

Introducing j just postpones some rewrites that prevent useful simplifications. Z3 already uses common sub-expressions.
The example highlights some opportunities for simplification, noteworthy at(..) = "".
The example is solved in both versions after adding this simplification.

* fix unsound len(substr) axiom

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* FreshConst is_sort (#7748)

* #7750

add pre-processing simplification

* Add parameter validation for selected API functions

* updates to ac-plugin

fix incrementality bugs by allowing destructive updates during saturation at the cost of redoing saturation after a pop.

* enable passive, add check for bloom up-to-date

* add top-k fixed-sized min-heap priority queue for top scoring literals

* set up worker thread batch manager for multithreaded batch cubes paradigm, need to debug as I am getting segfault still

* fix bug in parallel solving batch setup

* fix bug

* allow for internalize implies

* disable pre-processing during cubing

* debugging

* remove default constructor

* remove a bunch of string copies

* Update euf_ac_plugin.cpp

include reduction rules in forward simplification

* Update euf_completion.cpp

try out restricting scope of equalities added by instantation

* Update smt_parallel.cpp

Drop non-relevant units from shared structures.

* process cubes as lists of individual lits

* merge

* Add support for Algebraic Datatypes in JavaScript/TypeScript bindings (#7734)

* Initial plan

* Add datatype type definitions to types.ts (work in progress)

Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

* Complete datatype type definitions with working TypeScript compilation

Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

* Implement core datatype functionality with TypeScript compilation success

Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

* Complete datatype implementation with full Context integration and tests

Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

---------

Co-authored-by: copilot-swe-agent[bot] <198982749+Copilot@users.noreply.github.com>
Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

* chipping away at the new code structure

* comments

* debug infinite recursion and split cubes on existing split atoms that aren't in the cube

* share lemmas, learn from unsat core, try to debug a couple of things, there was a subtle bug that i have a hard time repro'ing

* merge

* fix #7603: race condition in Ctrl-C handling (#7755)

* fix #7603: race condition in Ctrl-C handling

* fix race in cancel_eh

* fix build

* add arithemtic saturation

* add an option to register callback on quantifier instantiation

Suppose a user propagator encodes axioms using quantifiers and uses E-matching for instantiation. If it wants to implement a custom priority scheme or drop some instances based on internal checks it can register a callback with quantifier instantiation

* missing new closure

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* add Z3_solver_propagate_on_binding to ml callback declarations

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* add python file

Signed-off-by: Lev Nachmanson <levnach@Levs-MacBook-Pro.local>

* debug under defined calls

Signed-off-by: Lev Nachmanson <levnach@hotmail.com>

* more untangle params

Signed-off-by: Lev Nachmanson <levnach@hotmail.com>

* precalc parameters to define the eval order

Signed-off-by: Lev Nachmanson <levnach@hotmail.com>

* remove a printout

Signed-off-by: Lev Nachmanson <levnach@hotmail.com>

* rename a Python file

Signed-off-by: Lev Nachmanson <levnach@hotmail.com>

* add on_binding callbacks across APIs

update release notes,
add to Java, .Net, C++

* use jboolean in Native interface

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* register on_binding attribute

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* fix java build for java bindings

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* avoid interferring side-effects in function calls

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* remove theory_str and classes that are only used by it

* remove automata from python build

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* remove ref to theory_str

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* get the finest factorizations before project

Signed-off-by: Lev Nachmanson <levnach@hotmail.com>

* rename add_lcs to add_lc

Signed-off-by: Lev Nachmanson <levnach@hotmail.com>

* resolve bad bug about l2g and g2l translators using wrong global context. add some debug prints

* initial attempt at dynamically switching from greedy to frugal splitting strategy in return_cubes. need to test. also there is some bug where the threads take forever to cancel?

* Update RELEASE_NOTES.md

* resolve bug about not translating managers correctly for the second phase of the greedy cubing, and the frugal fallback

* remove unused square-free check

Signed-off-by: Lev Nachmanson <levnach@hotmail.com>

* add some debug prints and impelement internal polynomial fix

* add some comments and debug m_assumptions_used

* redo greedy->frugal strategy so we don't split on existing cubes in frugal at all (eliminate the incorrect/wasteful step by processing current batch first)

* set up initial scaffolding for sharing clauses between threads and batch manager. needs some reworking/debug still

---------

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>
Signed-off-by: Lev Nachmanson <levnach@Levs-MacBook-Pro.local>
Signed-off-by: Lev Nachmanson <levnach@hotmail.com>
Co-authored-by: Nikolaj Bjorner <nbjorner@microsoft.com>
Co-authored-by: humnrdble <83878671+humnrdble@users.noreply.github.com>
Co-authored-by: Nuno Lopes <nuno.lopes@tecnico.ulisboa.pt>
Co-authored-by: Copilot <198982749+Copilot@users.noreply.github.com>
Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>
Co-authored-by: Lev Nachmanson <levnach@hotmail.com>

* sign of life

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* add notes on parameter tuning

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* add notes on parameter tuning

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* add notes on parameter tuning

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* add notes on parameter tuning

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* turn off logging at level 0 for testing

* add max thread conflicts backoff

---------

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>
Signed-off-by: Lev Nachmanson <levnach@Levs-MacBook-Pro.local>
Signed-off-by: Lev Nachmanson <levnach@hotmail.com>
Co-authored-by: Nikolaj Bjorner <nbjorner@microsoft.com>
Co-authored-by: humnrdble <83878671+humnrdble@users.noreply.github.com>
Co-authored-by: Nuno Lopes <nuno.lopes@tecnico.ulisboa.pt>
Co-authored-by: Copilot <198982749+Copilot@users.noreply.github.com>
Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>
Co-authored-by: Lev Nachmanson <levnach@hotmail.com>

* fix #7776

* add > operator as shorthand for Array

* updates to euf completion

* resolve bug about not popping local ctx to base level before collecting shared lits

* Add virtual translate method to solver_factory class (#7780)

* Initial plan

* Add virtual translate method to solver_factory base class and all implementations

Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

* Add documentation for the translate method in solver_factory

Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

---------

Co-authored-by: copilot-swe-agent[bot] <198982749+Copilot@users.noreply.github.com>
Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

* put return_cubes under lock

* Revert "resolve bug about not popping local ctx to base level before collecting shared lits"

This reverts commit bba1111e1b11cd14c0e266af6c5b0bd549f081a6.

* Update seq_rewriter.cpp

* fix releaseNotesSource to inline

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* Use solver factory translate method in Z3_solver_translate (#7782)

* Initial plan

* Fix Z3_solver_translate to use solver factory translate method

Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

---------

Co-authored-by: copilot-swe-agent[bot] <198982749+Copilot@users.noreply.github.com>
Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

* Revert "Parallel solving (#7775)" (#7777)

This reverts commit c8e866f5682ed4d01a54ae714ceedf50670f09ca.

* remove upload artifact for azure-pipeline

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* Fix compilation warning: add missing is_passive_eq case to switch statement (#7785)

* Initial plan

* Fix compilation warning: add missing is_passive_eq case to switch statement

Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

---------

Co-authored-by: copilot-swe-agent[bot] <198982749+Copilot@users.noreply.github.com>
Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

* Remove NugetPublishNightly stage from nightly.yaml (#7787)

* Initial plan

* Remove NugetPublishNightly stage from nightly.yaml

Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

---------

Co-authored-by: copilot-swe-agent[bot] <198982749+Copilot@users.noreply.github.com>
Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

* add more params

* enable pypi public

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* Fix nullptr dereference in pp_symbol when handling null symbol names (#7790)

* Initial plan

* Fix nullptr dereference in pp_symbol with null symbol names

Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

---------

Co-authored-by: copilot-swe-agent[bot] <198982749+Copilot@users.noreply.github.com>
Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

* add option to control epsilon #7791

#7791 reports on using model values during lex optimization that break soft constraints.
This is an artifact of using optimization where optimal values can be arbitrarily close to a rational.
In a way it is by design, but we give the user now an option to control the starting point for epsilon when converting infinitesimals into rationals.

* update on euf

* check for internalized in solve_for

* fix #7792

add missing revert operations

* update version number to 4.15.4

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* fix #7753

* fix #7796

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* Create centralized version management with VERSION.txt (#7802)

* Initial plan

* Create VERSION.txt and update CMakeLists.txt to read version from file

Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

* Complete centralized version management system

Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

* Fix version update script and finalize implementation

Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

* Create centralized version management with VERSION.txt

Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

---------

Co-authored-by: copilot-swe-agent[bot] <198982749+Copilot@users.noreply.github.com>
Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

* read version from VERSION.txt

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* fix version parse

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* fix parsing of version

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* add param tuning experiment in python

* Fix Azure Pipeline PyPI package builds by including VERSION.txt in source distribution (#7808)

* Initial plan

* Fix Azure Pipeline PyPI package builds by including VERSION.txt in source distribution

Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

---------

Co-authored-by: copilot-swe-agent[bot] <198982749+Copilot@users.noreply.github.com>
Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

* Update nightly.yaml to match release.yml NuGet tool installer changes (#7810)

* Initial plan

* Update nightly.yaml to match release.yml NuGet tool installer changes

Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

---------

Co-authored-by: copilot-swe-agent[bot] <198982749+Copilot@users.noreply.github.com>
Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

* Attempt at adding the README to the NuGet package (#7807)

* Attempt at adding README to NuGet package

* Forgot to enable publishing

* add resources

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* remove resources directive again

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* Document how to use system-installed Z3 with CMake projects (#7809)

* Initial plan

* Add documentation for using system-installed Z3 with CMake

Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

---------

Co-authored-by: copilot-swe-agent[bot] <198982749+Copilot@users.noreply.github.com>
Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

* Fix Julia bindings linker errors on Windows MSVC (#7794)

* Initial plan

* Fix Julia bindings linker errors on Windows MSVC

Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

* Complete Julia bindings fix validation and testing

Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

* Fix Julia bindings linker errors on Windows MSVC

Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

---------

Co-authored-by: copilot-swe-agent[bot] <198982749+Copilot@users.noreply.github.com>
Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

* add print for version file

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* add more logging to setup.py

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* try diferennt dirs

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* try src_dir_repo

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* try other dir

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* remove extra characters

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* more output

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* print dirs

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* copy VERSION from SRC_DIR

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* Move VERSION.txt to scripts directory and update all references (#7811)

* Initial plan

* Move VERSION.txt to scripts/ and update all references

Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

---------

Co-authored-by: copilot-swe-agent[bot] <198982749+Copilot@users.noreply.github.com>
Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

* clean up a little of the handling of VERSION.txt

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* add implementation and toggleable param for splitting frugal + choosing deepest cubes only

* remove priority queue for top-k lits and replace with simple linear scan. the PQ implementation backend still remains in case we want to switch back

* Add new configurations for SMT parallel settings

* Bugfix: post-build sanity check when an old version of ocaml-z3 is installed (#7815)

* fix: add generating META for ocamlfind.

* Patch macos. We need to keep the `@rpath` and use environment var to enable the test because we need to leave it to be fixed by package managers.

* Trigger CI.

* Debug.

* Debug.

* Debug.

* Debug.

* Debug.

* Debug.

* Hacky fix for ocaml building warning.

* Fix typo and rename variables.

* Fix cmake for ocaml test, using local libz3 explicit.

* Rename configuration from 'shareconflicts' to 'depthsplitting'

* Fix configuration for depth splitting in notes

* rename variables

* remove double tweak versioning

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

* attempting to add backbone code, it does not work. still debugging the error: ASSERTION VIOLATION
File: /home/t-ilshapiro/z3/src/ast/ast.cpp
Line: 388
UNEXPECTED CODE WAS REACHED. I left a comment on the line where it's crashing

* depth splitting now applies to greedy+frugal unless specified otherwise

* debug the backbone crash (it was references not being counted)

* iterative deepening experiment (no PQ yet). the hardness heuristic is still naive!

* fix iterative deepening bug: unsolved cube needs to get re-enqueued even if we don't split it further

* debug iterative deepening some more and add first attempt at PQ (untested)

* fix some bugs and the PQ approach is working for now. the depth sets approach is actually unsound, but I am going to focus on the PQ approach for now since it has more potential for SAT problems with the right hardness metric

* add new attempt at hardness function

* attempt to add different hardness functions including heule schur and march, need to re-examine/debug/evaluate

* implement march and heule schur hardness functions based on sat_lookahead.cpp implementations. they seem to be buggy, need to revisit. also set up experimental params for running on polytest

* add a lot of debug prints that need to be removed. some bugs are resolved but others remain

* debug in progress

* remove the incorrect preselection functions for march and heule-schur. update explicit-hardness with bugfixes. now it works but i am not sure there is a good perf increase based on my handpicked examples. i tried several variations of hardness ratios as you can see commented out. there are debug prints still commented out. also return_cubes now takes in a single cube instead of a list C_worker to align with the single-cube hardness/should_split metrics, it doesn't change anything bc we only pass in 1 cube to begin with

* debug a couple of things and change the hardness function

* tree version in progress

* cube tree data structure version for sharing maximal solver context. it compiles but segfaults immediately so it needs a lot of debugging

* slowly debugging (committing for saving progress)

* debugged get_next_cube to align with how we're storing the prev_cube and active status. other things are still wrong

* debug manager translation problem

* don't actually prune tree for UNSAT, too risky with multithreads. instead marks all such 'removed' nodes as inactive

* it runs! but then crashes after a while

* add optimization (or what is hopefully an optimization) about threads only working in the frontier determined by their split atoms, and only overlapping frontiers once they've exhausted their own

* debug some things. exhausting the cube tree should return unsat now, not crash. also fix a couple of things in get_next_cube. also, setting k=1 for split atoms might be better, not sure

* fix small bug about making sure we're searching in the thread's frontier when we just started a new frontier (like if we're at the empty cube at the root)

* debug big problem about incorrectly deepcopying children when assining new frontier nodes. i think it works now?? it's still not as fast as I would want
also, there are a lot of messy debug prints i will need to remove

* clean up comments and fix bug in cubetree about when subcube tautologies are UNSAT, the entire formula is UNSAT

* clean up short redundant code

* iterative deepening with cubetree, early set unsat if the entire tree is found closed by a thread, and finally multiple threads can work on the same cube if it's the only active leaf

* fix small bug about cubetree node removal

* cubetree is now a per-thread subtree, still needs cleaning but all the ugly 'frontier' logic is now gone

---------

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>
Signed-off-by: Lev Nachmanson <levnach@Levs-MacBook-Pro.local>
Signed-off-by: Lev Nachmanson <levnach@hotmail.com>
Signed-off-by: dependabot[bot] <support@github.com>
Co-authored-by: Nikolaj Bjorner <nbjorner@microsoft.com>
Co-authored-by: humnrdble <83878671+humnrdble@users.noreply.github.com>
Co-authored-by: Nuno Lopes <nuno.lopes@tecnico.ulisboa.pt>
Co-authored-by: Copilot <198982749+Copilot@users.noreply.github.com>
Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>
Co-authored-by: Lev Nachmanson <levnach@hotmail.com>
Co-authored-by: dependabot[bot] <49699333+dependabot[bot]@users.noreply.github.com>
Co-authored-by: Solal Pirelli <SolalPirelli@users.noreply.github.com>
Co-authored-by: Shiwei Weng 翁士伟 <arbipher@gmail.com>

</pre>


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|aproveSMT7377887083439038055.smt2                            |    0.069s | 89.808MiB| sat | 0 |  |  |
|ChenFlurMukhopadhyay-SAS2012-Ex3.10_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2 |    0.073s | 89.884MiB| unsat | 0 |  |  |
|aproveSMT2477805317391230600.smt2                            |    0.074s | 90.704MiB| sat | 0 |  |  |
|aproveSMT4626738710431749334.smt2                            |    0.074s | 89.88MiB| unsat | 0 |  |  |
|From_T2__slayer-n2.t2__p23222_terminationG_0.smt2            |    0.077s | 91.416MiB| unsat | 0 |  |  |
|aproveSMT5205173846890464046.smt2                            |    0.078s | 89.116MiB| sat | 0 |  |  |
|aproveSMT3082703823983150903.smt2                            |    0.083s | 89.376MiB| unsat | 0 |  |  |
|problem-005140.cvc.1.smt2                                    |    0.083s | 89.624MiB| sat | 0 |  |  |
|aproveSMT5236930360453082734.smt2                            |    0.083s | 89.624MiB| sat | 0 |  |  |
|aproveSMT4894552965501289252.smt2                            |    0.084s | 90.652MiB| sat | 0 |  |  |
|aproveSMT655469581631834278.smt2                             |    0.085s | 89.416MiB| sat | 0 |  |  |
|aproveSMT4004559194265078508.smt2                            |    0.085s | 89.368MiB| sat | 0 |  |  |
|aproveSMT2844713893974801294.smt2                            |    0.086s | 90.136MiB| sat | 0 |  |  |
|From_T2__simple.t2__p21460_terminationG_0.smt2               |    0.086s | 90.088MiB| unsat | 0 |  |  |
|aproveSMT8524404391338204488.smt2                            |    0.087s | 90.904MiB| sat | 0 |  |  |
|problem-002563.cvc.1.smt2                                    |    0.087s | 89.368MiB| sat | 0 |  |  |
|problem-000019.cvc.1.smt2                                    |    0.087s | 89.624MiB| sat | 0 |  |  |
|aproveSMT2631357328519238424.smt2                            |    0.087s | 90.904MiB| sat | 0 |  |  |
|aproveSMT6753330551938377858.smt2                            |    0.087s | 90.04MiB| sat | 0 |  |  |
|From_T2__loop3.t2__term_unfeasibility_39_0.smt2              |    0.087s | 89.624MiB| unsat | 0 |  |  |
|aproveSMT7141115503836990123.smt2                            |    0.087s | 90.648MiB| sat | 0 |  |  |
|aproveSMT2322179511678559502.smt2                            |    0.088s | 90.904MiB| sat | 0 |  |  |
|problem-006526.cvc.1.smt2                                    |    0.088s | 89.624MiB| unsat | 0 |  |  |
|aproveSMT955385929993658388.smt2                             |    0.088s | 91.604MiB| unsat | 0 |  |  |
|problem-002619.cvc.1.smt2                                    |    0.088s | 89.636MiB| sat | 0 |  |  |
|aproveSMT9169917326916030775.smt2                            |    0.088s | 91.304MiB| unsat | 0 |  |  |
|aproveSMT2080970443407093756.smt2                            |    0.088s | 90.888MiB| sat | 0 |  |  |
|aproveSMT1022543817592849705.smt2                            |    0.088s | 89.368MiB| sat | 0 |  |  |
|74.smt2                                                      |    0.088s | 95.808MiB| sat | 0 |  |  |
|aproveSMT1261041288686639410.smt2                            |    0.089s | 89.372MiB| sat | 0 |  |  |
|From_T2__consts4nt.t2_fixed__p18266_terminationG_0.smt2      |    0.089s | 91.42MiB| unsat | 0 |  |  |
|aproveSMT4553505495713257009.smt2                            |    0.089s | 89.34MiB| sat | 0 |  |  |
|From_T2__ex40.t2__p32196_terminationG_0.smt2                 |    0.089s | 91.16MiB| unsat | 0 |  |  |
|From_T2__ex36.t2__p28763_safety_0.smt2                       |    0.089s | 93.664MiB| sat | 0 |  |  |
|problem-000008.cvc.1.smt2                                    |    0.089s | 90.276MiB| sat | 0 |  |  |
|aproveSMT3305912493296657311.smt2                            |    0.089s | 91.196MiB| sat | 0 |  |  |
|aproveSMT2632098249079857042.smt2                            |    0.089s | 89.368MiB| sat | 0 |  |  |
|1805.smt2                                                    |    0.089s | 94.532MiB| unsat | 0 |  |  |
|aproveSMT4726660327701427.smt2                               |    0.089s | 89.284MiB| sat | 0 |  |  |
|problem-002949.cvc.1.smt2                                    |    0.089s | 89.368MiB| unsat | 0 |  |  |
|problem-002871.cvc.1.smt2                                    |    0.090s | 89.624MiB| unsat | 0 |  |  |
|370.smt2                                                     |    0.090s | 95.26MiB| sat | 0 |  |  |
|aproveSMT2934397244559601587.smt2                            |    0.090s | 89.376MiB| sat | 0 |  |  |
|aproveSMT4525776783561378911.smt2                            |    0.090s | 89.88MiB| sat | 0 |  |  |
|aproveSMT3970517148307051183.smt2                            |    0.090s | 89.624MiB| sat | 0 |  |  |
|From_T2__acqrel-fail.t2__p15388_terminationG_0.smt2          |    0.090s | 92.188MiB| unsat | 0 |  |  |
|aproveSMT3611058756933534688.smt2                            |    0.090s | 89.624MiB| sat | 0 |  |  |
|From_AProVE_2014__NO_13.jar-obl-8__p11407_edge_closing_0.smt2 |    0.090s | 92.056MiB| unsat | 0 |  |  |
|From_T2__small35.t2__p23984_terminationG_0.smt2              |    0.090s | 90.652MiB| unsat | 0 |  |  |
|aproveSMT525791599825112152.smt2                             |    0.090s | 90.392MiB| unsat | 0 |  |  |
|From_T2__ex36.t2_fixed__p23746_safety_0.smt2                 |    0.091s | 91.676MiB| sat | 0 |  |  |
|1767.smt2                                                    |    0.091s | 95.516MiB| sat | 0 |  |  |
|problem-005897.cvc.1.smt2                                    |    0.091s | 89.88MiB| sat | 0 |  |  |
|aproveSMT5775190440758349853.smt2                            |    0.091s | 89.368MiB| sat | 0 |  |  |
|aproveSMT5348320449423401087.smt2                            |    0.091s | 89.624MiB| sat | 0 |  |  |
|From_T2__brockschmidt_1.t2__p17389_terminationG_0.smt2       |    0.092s | 94.972MiB| sat | 0 |  |  |
|aproveSMT8866413736567330792.smt2                            |    0.092s | 89.624MiB| sat | 0 |  |  |
|PastaA6_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2 |    0.092s | 90.18MiB| unsat | 0 |  |  |
|From_T2__ex36.t2__p29769_safety_0.smt2                       |    0.092s | 93.472MiB| sat | 0 |  |  |
|problem-006538.cvc.1.smt2                                    |    0.092s | 91.016MiB| sat | 0 |  |  |
|aproveSMT1444998859697836742.smt2                            |    0.092s | 89.368MiB| sat | 0 |  |  |
|aproveSMT4940364873027923219.smt2                            |    0.092s | 90.548MiB| sat | 0 |  |  |
|701.smt2                                                     |    0.092s | 93.132MiB| sat | 0 |  |  |
|problem-006535.cvc.1.smt2                                    |    0.092s | 89.624MiB| unsat | 0 |  |  |
|problem-001268.cvc.1.smt2                                    |    0.093s | 90.136MiB| unsat | 0 |  |  |
|problem-000131.cvc.1.smt2                                    |    0.093s | 89.624MiB| sat | 0 |  |  |
|problem-000019.cvc.2.smt2                                    |    0.093s | 90.176MiB| sat | 0 |  |  |
|aproveSMT3264265901512371238.smt2                            |    0.093s | 90.652MiB| sat | 0 |  |  |
|aproveSMT7081278616493440418.smt2                            |    0.093s | 90.392MiB| sat | 0 |  |  |
|377.smt2                                                     |    0.093s | 95.26MiB| sat | 0 |  |  |
|From_AProVE_2014__whileNestedOffset_rec.jar-obl-9__p14936_terminationG_0.smt2 |    0.093s | 90.904MiB| unsat | 0 |  |  |
|aproveSMT6549179037310304786.smt2                            |    0.093s | 90.648MiB| sat | 0 |  |  |
|From_T2__heidy6.t2__terminationQ_1_0.smt2                    |    0.093s | 91.08MiB| unsat | 0 |  |  |
|problem-005952.cvc.1.smt2                                    |    0.093s | 90.648MiB| sat | 0 |  |  |
|problem-002617.cvc.1.smt2                                    |    0.093s | 90.912MiB| sat | 0 |  |  |
|problem-006501.cvc.1.smt2                                    |    0.093s | 89.88MiB| unsat | 0 |  |  |
|problem-000441.cvc.1.smt2                                    |    0.094s | 89.368MiB| unsat | 0 |  |  |
|aproveSMT6054561478528727566.smt2                            |    0.094s | 90.392MiB| unsat | 0 |  |  |
|aproveSMT144364303553946193.smt2                             |    0.094s | 90.364MiB| sat | 0 |  |  |
|problem-000025.cvc.2.smt2                                    |    0.095s | 90.908MiB| unsat | 0 |  |  |
|problem-006547.cvc.1.smt2                                    |    0.095s | 92.44MiB| sat | 0 |  |  |
|From_T2__consts5nt.t2_fixed__p18371_terminationG_0.smt2      |    0.095s | 92.184MiB| sat | 0 |  |  |
|From_T2__small03.t2__p23517_terminationG_0.smt2              |    0.095s | 89.88MiB| unsat | 0 |  |  |
|aproveSMT7823144654332746343.smt2                            |    0.095s | 90.904MiB| unsat | 0 |  |  |
|problem-001265.cvc.1.smt2                                    |    0.095s | 90.136MiB| unsat | 0 |  |  |
|485.smt2                                                     |    0.095s | 92.98MiB| sat | 0 |  |  |
|aproveSMT6155317075733447430.smt2                            |    0.096s | 90.904MiB| sat | 0 |  |  |
|b.04_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2 |    0.096s | 89.856MiB| unsat | 0 |  |  |
|Stroeder_15__Marbie1.c__p24189_terminationG_0.smt2           |    0.096s | 91.16MiB| unsat | 0 |  |  |
|424.smt2                                                     |    0.096s | 92.696MiB| sat | 0 |  |  |
|Stroeder_15__Ex04.c__p22755_terminationG_0.smt2              |    0.096s | 90.784MiB| unsat | 0 |  |  |
|aproveSMT4610599926347927445.smt2                            |    0.096s | 90.692MiB| sat | 0 |  |  |
|problem-000124.cvc.1.smt2                                    |    0.096s | 90.648MiB| unsat | 0 |  |  |
|aproveSMT5046440760903487310.smt2                            |    0.096s | 90.904MiB| sat | 0 |  |  |
|aproveSMT8666199152065483741.smt2                            |    0.096s | 90.904MiB| unsat | 0 |  |  |
|From_T2__slayer-n2-filtered.t2__p23173_terminationG_0.smt2   |    0.096s | 92.696MiB| sat | 0 |  |  |
|aproveSMT2881315380892242955.smt2                            |    0.096s | 90.136MiB| unsat | 0 |  |  |
|673.smt2                                                     |    0.097s | 92.952MiB| sat | 0 |  |  |
|203.smt2                                                     |    0.097s | 91.16MiB| sat | 0 |  |  |
|aproveSMT2180393309678538513.smt2                            |    0.097s | 90.396MiB| sat | 0 |  |  |
|From_AProVE_2014__EvenOdd.jar-obl-8__p29030_terminationG_0.smt2 |    0.097s | 91.176MiB| unsat | 0 |  |  |
|PastaC7_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2 |    0.097s | 89.88MiB| unsat | 0 |  |  |
|866.smt2                                                     |    0.097s | 92.44MiB| sat | 0 |  |  |
|aproveSMT405002793410787217.smt2                             |    0.097s | 90.96MiB| sat | 0 |  |  |
|From_T2__small01.t2__terminationQ_3_0.smt2                   |    0.097s | 90.136MiB| unsat | 0 |  |  |
|From_T2__s1.t2_fixed__p17765_safety_0.smt2                   |    0.097s | 91.416MiB| sat | 0 |  |  |
|problem-006542.cvc.1.smt2                                    |    0.097s | 89.892MiB| unsat | 0 |  |  |
|problem-000080.cvc.1.smt2                                    |    0.098s | 89.88MiB| unsat | 0 |  |  |
|term-XoKPE3.smt2                                             |    0.098s | 95.032MiB| sat | 0 |  |  |
|term-e0uxKl.smt2                                             |    0.098s | 91.672MiB| sat | 0 |  |  |
|aproveSMT5829491630698138486.smt2                            |    0.098s | 90.904MiB| sat | 0 |  |  |
|From_T2__small16.t2__p23821_edge_closing_0.smt2              |    0.098s | 91.096MiB| unsat | 0 |  |  |
|aproveSMT1105246329636558105.smt2                            |    0.098s | 91.012MiB| unsat | 0 |  |  |
|From_T2__ex36.t2_fixed__p22848_safety_0.smt2                 |    0.098s | 91.684MiB| sat | 0 |  |  |
|From_AProVE_2014__sunset_rec.jar-obl-8__term_unfeasibility_0_0.smt2 |    0.098s | 91.416MiB| unsat | 0 |  |  |
|From_AProVE_2014__even_rec.jar-obl-8__p29058_terminationG_0.smt2 |    0.099s | 91.16MiB| unsat | 0 |  |  |
|From_T2__ex36.t2_fixed__p23302_safety_0.smt2                 |    0.099s | 92.44MiB| sat | 0 |  |  |
|aproveSMT944940066259205664.smt2                             |    0.099s | 92.264MiB| sat | 0 |  |  |
|From_T2__s1.t2_fixed__p16656_safety_0.smt2                   |    0.099s | 91.672MiB| sat | 0 |  |  |
|888.smt2                                                     |    0.099s | 93.716MiB| sat | 0 |  |  |
|aproveSMT3612851711724526218.smt2                            |    0.099s | 91.16MiB| sat | 0 |  |  |
|From_T2__consts2nt.t2_fixed__p18017_terminationG_0.smt2      |    0.099s | 92.184MiB| unsat | 0 |  |  |
|93.smt2                                                      |    0.099s | 92.444MiB| sat | 0 |  |  |
|127.smt2                                                     |    0.099s | 92.184MiB| sat | 0 |  |  |
|From_T2__apchild-live.t2_fixed__p16501_safety_0.smt2         |    0.099s | 91.416MiB| unsat | 0 |  |  |
|From_T2__ex36.t2_fixed__p23573_safety_0.smt2                 |    0.099s | 91.888MiB| sat | 0 |  |  |
|496.smt2                                                     |    0.099s | 93.352MiB| sat | 0 |  |  |
|aproveSMT691472806777450769.smt2                             |    0.099s | 89.372MiB| sat | 0 |  |  |
|599.smt2                                                     |    0.099s | 91.396MiB| sat | 0 |  |  |
|aproveSMT1697563446985587562.smt2                            |    0.099s | 89.112MiB| sat | 0 |  |  |
|Pure3Phase_true-termination.c_Iteration5_Loop+nonterminationTemplate_0.smt2 |    0.099s | 91.528MiB| unsat | 0 |  |  |
|1895.smt2                                                    |    0.099s | 92.7MiB| sat | 0 |  |  |
|23.smt2                                                      |    0.099s | 90.816MiB| sat | 0 |  |  |
|From_T2__ex36.t2__p25279_safety_0.smt2                       |    0.099s | 94.488MiB| sat | 0 |  |  |
|From_T2__n-13.t2__p3488_terminationG_0.smt2                  |    0.100s | 90.648MiB| unsat | 0 |  |  |
|From_T2__ex36.t2__p28593_safety_0.smt2                       |    0.100s | 94.228MiB| sat | 0 |  |  |
|aproveSMT1076852626867582761.smt2                            |    0.100s | 90.392MiB| sat | 0 |  |  |
|Stroeder_15__NonTermination4_false-termination.c__p24980_edge_closing_0.smt2 |    0.100s | 92.696MiB| sat | 0 |  |  |
|Stroeder_15__NonTermination1_false-termination.c__p24836_terminationG_0.smt2 |    0.100s | 91.16MiB| unsat | 0 |  |  |
|aproveSMT5038173880269306850.smt2                            |    0.100s | 92.184MiB| sat | 0 |  |  |
|711.smt2                                                     |    0.100s | 94.232MiB| sat | 0 |  |  |
|problem-002452.cvc.1.smt2                                    |    0.100s | 89.372MiB| unsat | 0 |  |  |
|From_T2__ex36.t2__p31417_safety_0.smt2                       |    0.100s | 95.0MiB| sat | 0 |  |  |
|From_T2__fun11.t2_fixed__p437_terminationG_0.smt2            |    0.100s | 92.44MiB| unsat | 0 |  |  |
|aproveSMT3807494294977005803.smt2                            |    0.100s | 89.368MiB| sat | 0 |  |  |
|1662.smt2                                                    |    0.100s | 98.36MiB| sat | 0 |  |  |
|34.smt2                                                      |    0.101s | 93.208MiB| sat | 0 |  |  |
|From_AProVE_2014__Velroyen08-alternatingIncr.jar-obl-8__p13182_terminationG_0.smt2 |    0.101s | 92.716MiB| unsat | 0 |  |  |
|term-0Hb4yp.smt2                                             |    0.101s | 92.204MiB| sat | 0 |  |  |
|Stroeder_15__Velroyen_false-termination.c__p26334_terminationG_0.smt2 |    0.101s | 91.16MiB| unsat | 0 |  |  |
|From_T2__compress.t2__p17860_terminationG_0.smt2             |    0.102s | 91.928MiB| unsat | 0 |  |  |
|aproveSMT7610852511450248253.smt2                            |    0.102s | 91.428MiB| sat | 0 |  |  |
|264.smt2                                                     |    0.102s | 95.0MiB| sat | 0 |  |  |
|From_T2__s1.t2_fixed__p16901_safety_0.smt2                   |    0.102s | 91.412MiB| sat | 0 |  |  |
|aproveSMT2807471946702649636.smt2                            |    0.102s | 91.16MiB| sat | 0 |  |  |
|500.smt2                                                     |    0.102s | 93.208MiB| sat | 0 |  |  |
|211.smt2                                                     |    0.102s | 91.672MiB| sat | 0 |  |  |
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24246_terminationG_0.smt2 |    0.102s | 92.184MiB| unsat | 0 |  |  |
|aproveSMT6007639960281434719.smt2                            |    0.103s | 94.156MiB| sat | 0 |  |  |
|722.smt2                                                     |    0.103s | 94.744MiB| sat | 0 |  |  |
|From_T2__s1.t2_fixed__p16947_safety_0.smt2                   |    0.103s | 91.424MiB| sat | 0 |  |  |
|aproveSMT1166681508436419880.smt2                            |    0.103s | 89.852MiB| sat | 0 |  |  |
|From_T2__ex36.t2__p29667_safety_0.smt2                       |    0.103s | 95.312MiB| sat | 0 |  |  |
|From_T2__zlib-adler32.c.t2__p26007_safety_0.smt2             |    0.103s | 93.22MiB| sat | 0 |  |  |
|aproveSMT4504963179470263546.smt2                            |    0.103s | 92.696MiB| unsat | 0 |  |  |
|322.smt2                                                     |    0.103s | 92.184MiB| sat | 0 |  |  |
|aproveSMT4177797293206130085.smt2                            |    0.103s | 91.164MiB| unsat | 0 |  |  |
|1901.smt2                                                    |    0.104s | 93.72MiB| sat | 0 |  |  |
|From_T2__polyrank5.t2__p7550_terminationG_0.smt2             |    0.104s | 94.752MiB| sat | 0 |  |  |
|From_T2__ex36.t2__p28445_safety_0.smt2                       |    0.104s | 93.208MiB| sat | 0 |  |  |
|aproveSMT901847787721299507.smt2                             |    0.104s | 90.68MiB| sat | 0 |  |  |
|310.smt2                                                     |    0.104s | 91.672MiB| sat | 0 |  |  |
|149.smt2                                                     |    0.104s | 93.464MiB| sat | 0 |  |  |
|From_T2__consts3nt.t2_fixed__p18120_terminationG_0.smt2      |    0.104s | 91.416MiB| sat | 0 |  |  |
|507.smt2                                                     |    0.104s | 94.236MiB| sat | 0 |  |  |
|From_T2__ex36.t2__p26154_safety_0.smt2                       |    0.104s | 94.048MiB| sat | 0 |  |  |
|From_T2__1.t2__p15279_safety_0.smt2                          |    0.104s | 93.72MiB| sat | 0 |  |  |
|aproveSMT5219933089216354552.smt2                            |    0.104s | 92.3MiB| sat | 0 |  |  |
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27052_terminationG_0.smt2 |    0.104s | 93.464MiB| sat | 0 |  |  |
|From_AProVE_2014__Velroyen08-ex04.jar-obl-8__p13648_terminationG_0.smt2 |    0.104s | 92.7MiB| unsat | 0 |  |  |
|1689.smt2                                                    |    0.105s | 92.952MiB| sat | 0 |  |  |
|1884.smt2                                                    |    0.105s | 95.008MiB| sat | 0 |  |  |
|aproveSMT2217993778086906389.smt2                            |    0.105s | 90.552MiB| sat | 0 |  |  |
|1728.smt2                                                    |    0.105s | 94.232MiB| sat | 0 |  |  |
|Stroeder_15__LogMult.c__p24141_terminationG_0.smt2           |    0.105s | 92.188MiB| unsat | 0 |  |  |
|From_AProVE_2014__Et4-rec.jar-obl-8__p28955_terminationG_0.smt2 |    0.105s | 97.116MiB| sat | 0 |  |  |
|aproveSMT2271093326661303672.smt2                            |    0.105s | 91.928MiB| unsat | 0 |  |  |
|269.smt2                                                     |    0.105s | 95.004MiB| sat | 0 |  |  |
|aproveSMT4830702979511545177.smt2                            |    0.105s | 91.932MiB| sat | 0 |  |  |
|From_T2__slayer-3-new.t2__p22063_safety_0.smt2               |    0.105s | 96.536MiB| sat | 0 |  |  |
|From_AProVE_2014__Velroyen08-convLower.jar-obl-8__p13465_terminationG_0.smt2 |    0.105s | 91.676MiB| unsat | 0 |  |  |
|707.smt2                                                     |    0.106s | 94.488MiB| sat | 0 |  |  |
|From_T2__s1-striped.t2_fixed__p10316_safety_0.smt2           |    0.106s | 92.664MiB| sat | 0 |  |  |
|From_T2__consts1nt.t2__p17940_terminationG_0.smt2            |    0.106s | 91.596MiB| unsat | 0 |  |  |
|From_T2__consts4nt.t2_fixed__p18220_terminationG_0.smt2      |    0.106s | 91.912MiB| sat | 0 |  |  |
|aproveSMT8366476055690990863.smt2                            |    0.106s | 92.184MiB| unsat | 0 |  |  |
|aproveSMT4764278413219307912.smt2                            |    0.106s | 90.392MiB| sat | 0 |  |  |
|1924.smt2                                                    |    0.106s | 94.488MiB| sat | 0 |  |  |
|aproveSMT1045293394610378205.smt2                            |    0.106s | 89.12MiB| sat | 0 |  |  |
|498.smt2                                                     |    0.106s | 93.468MiB| sat | 0 |  |  |
|From_AProVE_2014__Choose.jar-obl-8__p27802_terminationG_0.smt2 |    0.106s | 91.416MiB| unsat | 0 |  |  |
|From_T2__ex36.t2__p26688_safety_0.smt2                       |    0.107s | 94.232MiB| sat | 0 |  |  |
|aproveSMT1510730073127582778.smt2                            |    0.107s | 90.148MiB| sat | 0 |  |  |
|aproveSMT6242888656932764676.smt2                            |    0.107s | 89.368MiB| sat | 0 |  |  |
|From_T2__wrong_loop.t2_fixed__p25712_edge_closing_0.smt2     |    0.107s | 91.928MiB| sat | 0 |  |  |
|term-tEmpby.smt2                                             |    0.107s | 91.932MiB| sat | 0 |  |  |
|946.smt2                                                     |    0.107s | 97.772MiB| sat | 0 |  |  |
|From_T2__wrong_loop.t2__p25728_terminationG_0.smt2           |    0.107s | 96.536MiB| sat | 0 |  |  |
|aproveSMT8813034472200507181.smt2                            |    0.107s | 92.492MiB| sat | 0 |  |  |
|From_T2__ex36.t2_fixed__p23260_safety_0.smt2                 |    0.107s | 92.44MiB| sat | 0 |  |  |
|From_T2__consts5nt.t2__p18414_terminationG_0.smt2            |    0.107s | 95.256MiB| sat | 0 |  |  |
|1089.smt2                                                    |    0.107s | 98.904MiB| sat | 0 |  |  |
|1270.smt2                                                    |    0.108s | 96.792MiB| sat | 0 |  |  |
|From_T2__ex36.t2__p26896_safety_0.smt2                       |    0.108s | 95.22MiB| sat | 0 |  |  |
|From_T2__edn.t2__p20154_safety_0.smt2                        |    0.108s | 93.608MiB| unsat | 0 |  |  |
|1757.smt2                                                    |    0.108s | 94.744MiB| sat | 0 |  |  |
|514.smt2                                                     |    0.108s | 94.488MiB| sat | 0 |  |  |
|1586.smt2                                                    |    0.108s | 96.28MiB| sat | 0 |  |  |
|Stroeder_15__Lobnya-Boolean-Reordered_true-termination.c__p24120_terminationG_0.smt2 |    0.108s | 94.744MiB| sat | 0 |  |  |
|250.smt2                                                     |    0.108s | 95.344MiB| sat | 0 |  |  |
|167.smt2                                                     |    0.108s | 94.744MiB| sat | 0 |  |  |
|1152.smt2                                                    |    0.109s | 100.0MiB| sat | 0 |  |  |
|From_T2__ex36.t2_fixed__p22718_safety_0.smt2                 |    0.109s | 92.456MiB| sat | 0 |  |  |
|aproveSMT8739079467798956217.smt2                            |    0.109s | 90.968MiB| unsat | 0 |  |  |
|aproveSMT3039391242675517681.smt2                            |    0.109s | 91.172MiB| unsat | 0 |  |  |
|732.smt2                                                     |    0.109s | 95.256MiB| sat | 0 |  |  |
|535.smt2                                                     |    0.109s | 95.592MiB| sat | 0 |  |  |
|From_T2__ex36.t2__p25402_safety_0.smt2                       |    0.109s | 95.256MiB| sat | 0 |  |  |
|From_T2__zlib-adler32.c.t2__p26355_safety_0.smt2             |    0.109s | 94.232MiB| sat | 0 |  |  |
|891.smt2                                                     |    0.109s | 93.732MiB| sat | 0 |  |  |
|From_T2__n-3.t2__p4196_terminationG_0.smt2                   |    0.109s | 91.928MiB| unsat | 0 |  |  |
|From_T2__edn.t2__p20360_safety_0.smt2                        |    0.110s | 92.916MiB| unsat | 0 |  |  |
|aproveSMT8282187318664889653.smt2                            |    0.110s | 93.464MiB| sat | 0 |  |  |
|aproveSMT1154766035975480809.smt2                            |    0.110s | 90.916MiB| sat | 0 |  |  |
|257.smt2                                                     |    0.110s | 93.98MiB| sat | 0 |  |  |
|aproveSMT1619938986991890573.smt2                            |    0.110s | 90.66MiB| sat | 0 |  |  |
|1582.smt2                                                    |    0.110s | 95.848MiB| sat | 0 |  |  |
|aproveSMT5493191018463992513.smt2                            |    0.110s | 91.684MiB| unsat | 0 |  |  |
|aproveSMT8204649684904954337.smt2                            |    0.110s | 90.612MiB| sat | 0 |  |  |
|179.smt2                                                     |    0.110s | 95.512MiB| sat | 0 |  |  |
|From_T2__apchild-live.t2_fixed__p16582_safety_0.smt2         |    0.110s | 91.16MiB| unsat | 0 |  |  |
|aproveSMT3778692042252886508.smt2                            |    0.111s | 90.656MiB| sat | 0 |  |  |
|527.smt2                                                     |    0.111s | 95.0MiB| sat | 0 |  |  |
|From_T2__ex36.t2__p29417_safety_0.smt2                       |    0.111s | 95.256MiB| sat | 0 |  |  |
|From_T2__n-15.t2__p3596_terminationG_0.smt2                  |    0.111s | 92.184MiB| unsat | 0 |  |  |
|1934.smt2                                                    |    0.111s | 95.34MiB| unsat | 0 |  |  |
|367.smt2                                                     |    0.111s | 95.52MiB| sat | 0 |  |  |
|From_T2__s1.t2_fixed__p16158_safety_0.smt2                   |    0.111s | 92.44MiB| sat | 0 |  |  |
|aproveSMT8677323562739420602.smt2                            |    0.111s | 90.656MiB| sat | 0 |  |  |
|From_AProVE_2014__Test7.jar-obl-11__p12919_safety_0.smt2     |    0.111s | 92.94MiB| unsat | 0 |  |  |
|From_AProVE_2014__AlternatingGrowReduceRec2.jar-obl-9__term_unfeasibility_1_0.smt2 |    0.111s | 93.208MiB| unsat | 0 |  |  |
|1741.smt2                                                    |    0.111s | 94.74MiB| sat | 0 |  |  |
|From_T2__ex36.t2_fixed__p23504_safety_0.smt2                 |    0.111s | 92.952MiB| sat | 0 |  |  |
|1607.smt2                                                    |    0.112s | 97.304MiB| sat | 0 |  |  |
|551.smt2                                                     |    0.112s | 96.752MiB| sat | 0 |  |  |
|281.smt2                                                     |    0.112s | 96.788MiB| sat | 0 |  |  |
|aproveSMT743198230882528455.smt2                             |    0.112s | 90.904MiB| sat | 0 |  |  |
|364.smt2                                                     |    0.112s | 95.256MiB| sat | 0 |  |  |
|1898.smt2                                                    |    0.112s | 93.18MiB| sat | 0 |  |  |
|544.smt2                                                     |    0.112s | 96.032MiB| sat | 0 |  |  |
|307.smt2                                                     |    0.112s | 93.3MiB| sat | 0 |  |  |
|From_T2__ex36.t2__p30852_safety_0.smt2                       |    0.112s | 93.72MiB| sat | 0 |  |  |
|75.smt2                                                      |    0.112s | 95.624MiB| sat | 0 |  |  |
|199.smt2                                                     |    0.112s | 96.412MiB| sat | 0 |  |  |
|1112.smt2                                                    |    0.112s | 98.0MiB| sat | 0 |  |  |
|From_T2__ex36.t2_fixed__p24595_safety_0.smt2                 |    0.113s | 93.308MiB| sat | 0 |  |  |
|1574.smt2                                                    |    0.113s | 94.744MiB| sat | 0 |  |  |
|aproveSMT1008289700543544835.smt2                            |    0.113s | 89.632MiB| sat | 0 |  |  |
|192.smt2                                                     |    0.113s | 95.3MiB| sat | 0 |  |  |
|1283.smt2                                                    |    0.113s | 95.768MiB| sat | 0 |  |  |
|From_AProVE_2014__Test7.jar-obl-11__p12888_terminationG_0.smt2 |    0.113s | 94.492MiB| sat | 0 |  |  |
|aproveSMT7334875128895402176.smt2                            |    0.113s | 90.648MiB| sat | 0 |  |  |
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24243_terminationG_0.smt2 |    0.113s | 94.228MiB| sat | 0 |  |  |
|From_T2__ex36.t2__p31769_safety_0.smt2                       |    0.113s | 94.604MiB| sat | 0 |  |  |
|From_AProVE_2014__Test2.jar-obl-8__term_unfeasibility_0_0.smt2 |    0.113s | 93.208MiB| unsat | 0 |  |  |
|From_T2__ex36.t2__p30283_safety_0.smt2                       |    0.113s | 95.128MiB| sat | 0 |  |  |
|aproveSMT7608975121595496463.smt2                            |    0.114s | 90.648MiB| sat | 0 |  |  |
|aproveSMT3342367565143444747.smt2                            |    0.114s | 90.904MiB| sat | 0 |  |  |
|aproveSMT1133405555645861684.smt2                            |    0.114s | 91.928MiB| sat | 0 |  |  |
|1776.smt2                                                    |    0.114s | 95.512MiB| sat | 0 |  |  |
|From_T2__ex36.t2__p28143_safety_0.smt2                       |    0.114s | 94.488MiB| sat | 0 |  |  |
|From_T2__zlib-adler32.c.t2__p26214_safety_0.smt2             |    0.114s | 94.096MiB| sat | 0 |  |  |
|aproveSMT4439607947222714793.smt2                            |    0.115s | 90.692MiB| sat | 0 |  |  |
|From_T2__ppblock.t2__p7691_terminationG_0.smt2               |    0.115s | 93.208MiB| unsat | 0 |  |  |
|187.smt2                                                     |    0.115s | 95.512MiB| sat | 0 |  |  |
|1917.smt2                                                    |    0.115s | 95.0MiB| sat | 0 |  |  |
|From_T2__e-acqrel-succeed.t2__p19620_safety_0.smt2           |    0.115s | 91.928MiB| unsat | 0 |  |  |
|625.smt2                                                     |    0.115s | 99.096MiB| sat | 0 |  |  |
|From_T2__insertsort.t2_fixed__p1846_terminationG_0.smt2      |    0.115s | 91.928MiB| unsat | 0 |  |  |
|1287.smt2                                                    |    0.115s | 96.28MiB| sat | 0 |  |  |
|750.smt2                                                     |    0.115s | 96.28MiB| sat | 0 |  |  |
|aproveSMT1256079449125527892.smt2                            |    0.115s | 90.648MiB| sat | 0 |  |  |
|From_T2__ex36.t2__p28282_safety_0.smt2                       |    0.116s | 94.744MiB| sat | 0 |  |  |
|aproveSMT8797788573757816721.smt2                            |    0.116s | 93.98MiB| sat | 0 |  |  |
|aproveSMT4812740542900327077.smt2                            |    0.116s | 90.936MiB| sat | 0 |  |  |
|aproveSMT5625725354797588883.smt2                            |    0.116s | 91.936MiB| sat | 0 |  |  |
|From_T2__ex36.t2_fixed__p23071_safety_0.smt2                 |    0.116s | 93.64MiB| sat | 0 |  |  |
|From_T2__zlib-adler32.c.t2__p26281_safety_0.smt2             |    0.116s | 94.748MiB| sat | 0 |  |  |
|term-Kkefdl.smt2                                             |    0.116s | 94.372MiB| sat | 0 |  |  |
|From_T2__n-6.t2__p4803_terminationG_0.smt2                   |    0.116s | 94.228MiB| sat | 0 |  |  |
|1303.smt2                                                    |    0.116s | 97.308MiB| sat | 0 |  |  |
|From_T2__ex36.t2_fixed__p24469_safety_0.smt2                 |    0.116s | 95.0MiB| sat | 0 |  |  |
|aproveSMT2142784755099170345.smt2                            |    0.116s | 90.648MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30674_safety_0.smt2 |    0.116s | 98.0MiB| sat | 0 |  |  |
|1594.smt2                                                    |    0.116s | 97.676MiB| sat | 0 |  |  |
|359.smt2                                                     |    0.116s | 94.744MiB| sat | 0 |  |  |
|1768.smt2                                                    |    0.117s | 95.864MiB| sat | 0 |  |  |
|aproveSMT2409578890815829527.smt2                            |    0.117s | 90.648MiB| sat | 0 |  |  |
|706.smt2                                                     |    0.117s | 94.956MiB| sat | 0 |  |  |
|From_T2__ex36.t2__p30570_safety_0.smt2                       |    0.117s | 95.036MiB| sat | 0 |  |  |
|aproveSMT2256159023721325971.smt2                            |    0.117s | 90.392MiB| sat | 0 |  |  |
|From_AProVE_2014__FibSLR.jar-obl-8__p29342_terminationG_0.smt2 |    0.117s | 97.048MiB| sat | 0 |  |  |
|1809.smt2                                                    |    0.117s | 98.0MiB| unsat | 0 |  |  |
|940.smt2                                                     |    0.117s | 97.304MiB| sat | 0 |  |  |
|1933.smt2                                                    |    0.117s | 96.536MiB| sat | 0 |  |  |
|107.smt2                                                     |    0.117s | 97.304MiB| sat | 0 |  |  |
|709.smt2                                                     |    0.117s | 95.756MiB| sat | 0 |  |  |
|Stroeder_15__WhileNestedOffset.c__p26451_terminationG_0.smt2 |    0.118s | 92.192MiB| unsat | 0 |  |  |
|From_T2__p-43-terminate.t2__p6637_terminationG_0.smt2        |    0.118s | 98.84MiB| sat | 0 |  |  |
|624.smt2                                                     |    0.118s | 98.324MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4408_safety_0.smt2 |    0.118s | 97.56MiB| sat | 0 |  |  |
|1410.smt2                                                    |    0.118s | 97.816MiB| sat | 0 |  |  |
|From_T2__ex36.t2__p32131_safety_0.smt2                       |    0.118s | 96.444MiB| sat | 0 |  |  |
|1085.smt2                                                    |    0.118s | 98.0MiB| unsat | 0 |  |  |
|909.smt2                                                     |    0.118s | 95.144MiB| sat | 0 |  |  |
|From_T2__edn.t2__terminationS_2_0.smt2                       |    0.118s | 93.48MiB| unsat | 0 |  |  |
|aproveSMT8038578912200818680.smt2                            |    0.118s | 90.392MiB| sat | 0 |  |  |
|1644.smt2                                                    |    0.118s | 99.352MiB| sat | 0 |  |  |
|aproveSMT4068876412031045354.smt2                            |    0.118s | 91.16MiB| sat | 0 |  |  |
|From_T2__ex36.t2__p26310_safety_0.smt2                       |    0.119s | 95.34MiB| sat | 0 |  |  |
|aproveSMT5541044923638316164.smt2                            |    0.119s | 90.904MiB| sat | 0 |  |  |
|1104.smt2                                                    |    0.119s | 99.356MiB| sat | 0 |  |  |
|From_T2__ex36.t2__p29339_safety_0.smt2                       |    0.119s | 95.12MiB| sat | 0 |  |  |
|1775.smt2                                                    |    0.119s | 96.536MiB| sat | 0 |  |  |
|From_T2__ex36.t2__p30909_safety_0.smt2                       |    0.119s | 95.512MiB| sat | 0 |  |  |
|aproveSMT2158114964317463984.smt2                            |    0.120s | 90.816MiB| sat | 0 |  |  |
|From_T2__ex36.t2__p29075_safety_0.smt2                       |    0.120s | 94.492MiB| sat | 0 |  |  |
|From_T2__eric1.t2__p22014_edge_closing_0.smt2                |    0.120s | 93.02MiB| unsat | 0 |  |  |
|aproveSMT1709482801492808359.smt2                            |    0.120s | 91.672MiB| sat | 0 |  |  |
|781.smt2                                                     |    0.120s | 97.816MiB| sat | 0 |  |  |
|aproveSMT8423039779088334472.smt2                            |    0.120s | 93.052MiB| unsat | 0 |  |  |
|From_T2__ex36.t2__p30378_safety_0.smt2                       |    0.120s | 95.892MiB| sat | 0 |  |  |
|aproveSMT8739447481320129819.smt2                            |    0.120s | 94.368MiB| sat | 0 |  |  |
|1785.smt2                                                    |    0.120s | 97.304MiB| sat | 0 |  |  |
|1324.smt2                                                    |    0.121s | 98.84MiB| sat | 0 |  |  |
|1268.smt2                                                    |    0.121s | 96.096MiB| sat | 0 |  |  |
|aproveSMT1059628807158111792.smt2                            |    0.122s | 94.036MiB| unsat | 0 |  |  |
|From_T2__ex36.t2__p25532_safety_0.smt2                       |    0.122s | 96.28MiB| sat | 0 |  |  |
|1425.smt2                                                    |    0.122s | 98.584MiB| sat | 0 |  |  |
|520.smt2                                                     |    0.122s | 94.744MiB| sat | 0 |  |  |
|1090.smt2                                                    |    0.122s | 98.84MiB| sat | 0 |  |  |
|aproveSMT4606013414596055049.smt2                            |    0.122s | 90.648MiB| sat | 0 |  |  |
|947.smt2                                                     |    0.122s | 97.312MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3144_safety_0.smt2 |    0.122s | 99.0MiB| sat | 0 |  |  |
|From_T2__ex36.t2__p30450_safety_0.smt2                       |    0.122s | 95.704MiB| sat | 0 |  |  |
|1850.smt2                                                    |    0.123s | 98.588MiB| sat | 0 |  |  |
|aproveSMT4163246385735196737.smt2                            |    0.123s | 92.184MiB| sat | 0 |  |  |
|aproveSMT2992043958700127833.smt2                            |    0.123s | 90.664MiB| sat | 0 |  |  |
|From_T2__oct_vs_subpoly.t2__p6309_terminationG_0.smt2        |    0.123s | 92.496MiB| unsat | 0 |  |  |
|aproveSMT8878736820157791946.smt2                            |    0.123s | 90.656MiB| sat | 0 |  |  |
|aproveSMT2493881658895874595.smt2                            |    0.123s | 92.32MiB| unsat | 0 |  |  |
|1468.smt2                                                    |    0.123s | 101.0MiB| sat | 0 |  |  |
|aproveSMT2180870078806303650.smt2                            |    0.123s | 90.916MiB| sat | 0 |  |  |
|1640.smt2                                                    |    0.123s | 99.096MiB| sat | 0 |  |  |
|aproveSMT778144120697107907.smt2                             |    0.123s | 92.184MiB| sat | 0 |  |  |
|From_AProVE_2014__Velroyen08-whileSum.jar-obl-8__p14857_terminationG_0.smt2 |    0.123s | 98.0MiB| sat | 0 |  |  |
|83.smt2                                                      |    0.124s | 99.236MiB| unsat | 0 |  |  |
|aproveSMT3090147554356497231.smt2                            |    0.124s | 90.648MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9227_safety_0.smt2 |    0.124s | 97.0MiB| sat | 0 |  |  |
|1858.smt2                                                    |    0.124s | 99.612MiB| sat | 0 |  |  |
|aproveSMT8012602079643276968.smt2                            |    0.124s | 92.44MiB| sat | 0 |  |  |
|aproveSMT5697460246608014240.smt2                            |    0.124s | 92.696MiB| sat | 0 |  |  |
|From_AProVE_2014__Et4.jar-obl-8__p28888_terminationG_0.smt2  |    0.124s | 99.068MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7814_safety_0.smt2 |    0.124s | 97.56MiB| sat | 0 |  |  |
|1677.smt2                                                    |    0.124s | 98.84MiB| sat | 0 |  |  |
|aproveSMT5210438168892578988.smt2                            |    0.124s | 92.176MiB| sat | 0 |  |  |
|aproveSMT2200431342265122737.smt2                            |    0.124s | 92.956MiB| sat | 0 |  |  |
|aproveSMT4005477226838207398.smt2                            |    0.124s | 93.168MiB| sat | 0 |  |  |
|1304.smt2                                                    |    0.125s | 98.992MiB| sat | 0 |  |  |
|1176.smt2                                                    |    0.125s | 101.0MiB| sat | 0 |  |  |
|From_T2__slayer-3.t2_fixed__p22141_safety_0.smt2             |    0.125s | 98.328MiB| sat | 0 |  |  |
|1126.smt2                                                    |    0.125s | 98.0MiB| sat | 0 |  |  |
|aproveSMT2423766902024488209.smt2                            |    0.125s | 94.444MiB| sat | 0 |  |  |
|From_T2__ex36.t2_fixed__p23881_safety_0.smt2                 |    0.125s | 96.28MiB| sat | 0 |  |  |
|aproveSMT1909899370567820557.smt2                            |    0.126s | 92.44MiB| sat | 0 |  |  |
|1308.smt2                                                    |    0.126s | 98.028MiB| sat | 0 |  |  |
|aproveSMT8120783453179243473.smt2                            |    0.126s | 92.184MiB| unsat | 0 |  |  |
|652.smt2                                                     |    0.126s | 97.0MiB| sat | 0 |  |  |
|1567.smt2                                                    |    0.126s | 98.0MiB| sat | 0 |  |  |
|Stroeder_15__svcomp_ex3b.c__p26046_terminationG_0.smt2       |    0.126s | 93.784MiB| unsat | 0 |  |  |
|From_T2__ex36.t2__p29291_safety_0.smt2                       |    0.126s | 95.292MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6433_safety_0.smt2 |    0.127s | 99.0MiB| sat | 0 |  |  |
|1794.smt2                                                    |    0.127s | 99.364MiB| sat | 0 |  |  |
|From_AProVE_2014__CyclicalListDuplicate.jar-obl-9__p28410_terminationG_0.smt2 |    0.127s | 96.792MiB| sat | 0 |  |  |
|828.smt2                                                     |    0.127s | 99.0MiB| sat | 0 |  |  |
|aproveSMT1207857789260966146.smt2                            |    0.127s | 93.26MiB| sat | 0 |  |  |
|From_AProVE_2014__NestedLoop.jar-obl-10__p11151_terminationG_0.smt2 |    0.127s | 95.564MiB| sat | 0 |  |  |
|1693.smt2                                                    |    0.127s | 99.608MiB| sat | 0 |  |  |
|term-rGohwx.smt2                                             |    0.127s | 97.576MiB| sat | 0 |  |  |
|1668.smt2                                                    |    0.127s | 98.336MiB| sat | 0 |  |  |
|From_T2__edn.t2__p20458_safety_0.smt2                        |    0.128s | 93.988MiB| unsat | 0 |  |  |
|1734.smt2                                                    |    0.128s | 95.768MiB| sat | 0 |  |  |
|1422.smt2                                                    |    0.128s | 99.608MiB| sat | 0 |  |  |
|1021.smt2                                                    |    0.128s | 98.0MiB| sat | 0 |  |  |
|From_T2__java_Recursions.c.t2__p2534_terminationG_0.smt2     |    0.128s | 96.812MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9099_safety_0.smt2 |    0.128s | 98.072MiB| sat | 0 |  |  |
|From_T2__ex36.t2_fixed__p22611_safety_0.smt2                 |    0.129s | 94.232MiB| sat | 0 |  |  |
|From_T2__Prim_4.t2__p8014_terminationG_0.smt2                |    0.129s | 96.8MiB| sat | 0 |  |  |
|aproveSMT8377786446909921993.smt2                            |    0.129s | 92.54MiB| unsat | 0 |  |  |
|From_T2__fun11.t2__p467_terminationG_0.smt2                  |    0.129s | 92.34MiB| unsat | 0 |  |  |
|1460.smt2                                                    |    0.130s | 98.0MiB| sat | 0 |  |  |
|aproveSMT6658278851923446624.smt2                            |    0.130s | 94.748MiB| sat | 0 |  |  |
|1488.smt2                                                    |    0.130s | 97.0MiB| sat | 0 |  |  |
|788.smt2                                                     |    0.130s | 98.0MiB| sat | 0 |  |  |
|1430.smt2                                                    |    0.131s | 97.0MiB| sat | 0 |  |  |
|1092.smt2                                                    |    0.131s | 98.936MiB| sat | 0 |  |  |
|1458.smt2                                                    |    0.131s | 98.0MiB| sat | 0 |  |  |
|455.smt2                                                     |    0.131s | 98.0MiB| sat | 0 |  |  |
|1113.smt2                                                    |    0.131s | 98.0MiB| sat | 0 |  |  |
|1484.smt2                                                    |    0.131s | 99.096MiB| sat | 0 |  |  |
|From_T2__edn.t2__p19956_safety_0.smt2                        |    0.131s | 94.488MiB| unsat | 0 |  |  |
|aproveSMT325795488857285297.smt2                             |    0.131s | 97.552MiB| sat | 0 |  |  |
|824.smt2                                                     |    0.132s | 98.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32746_safety_0.smt2 |    0.132s | 97.304MiB| sat | 0 |  |  |
|1631.smt2                                                    |    0.132s | 99.872MiB| sat | 0 |  |  |
|From_AProVE_2014__Velroyen08-complInterv.jar-obl-8__p13409_terminationG_0.smt2 |    0.132s | 92.936MiB| unsat | 0 |  |  |
|400.smt2                                                     |    0.132s | 99.276MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29923_safety_0.smt2 |    0.133s | 100.0MiB| sat | 0 |  |  |
|From_T2__ppblocktermbug.t2__p7811_terminationG_0.smt2        |    0.133s | 94.236MiB| unsat | 0 |  |  |
|1448.smt2                                                    |    0.133s | 99.092MiB| sat | 0 |  |  |
|1354.smt2                                                    |    0.133s | 100.0MiB| sat | 0 |  |  |
|449.smt2                                                     |    0.133s | 98.0MiB| sat | 0 |  |  |
|From_T2__zlib-crc32-BYFOUR.c.t2__p26531_safety_0.smt2        |    0.134s | 99.888MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4800_safety_0.smt2 |    0.134s | 99.0MiB| sat | 0 |  |  |
|798.smt2                                                     |    0.134s | 99.0MiB| sat | 0 |  |  |
|1018.smt2                                                    |    0.134s | 97.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30895_safety_0.smt2 |    0.135s | 100.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5807_safety_0.smt2 |    0.135s | 99.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7691_safety_0.smt2 |    0.135s | 97.0MiB| sat | 0 |  |  |
|term-nKoz7d.smt2                                             |    0.136s | 97.032MiB| sat | 0 |  |  |
|From_T2__ex36.t2__p29995_safety_0.smt2                       |    0.136s | 96.536MiB| sat | 0 |  |  |
|1132.smt2                                                    |    0.136s | 99.0MiB| sat | 0 |  |  |
|Stroeder_15__MirrorIntervSim.c__terminationS_0_0.smt2        |    0.136s | 91.912MiB| unsat | 0 |  |  |
|466.smt2                                                     |    0.136s | 99.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1989_safety_0.smt2 |    0.136s | 98.0MiB| sat | 0 |  |  |
|Stroeder_15__aaron3_true-termination.c__p20349_terminationG_0.smt2 |    0.136s | 98.0MiB| sat | 0 |  |  |
|aproveSMT4589478066325636629.smt2                            |    0.137s | 96.016MiB| sat | 0 |  |  |
|808.smt2                                                     |    0.137s | 101.0MiB| sat | 0 |  |  |
|From_T2__s1-striped.t2__p13960_safety_0.smt2                 |    0.137s | 103.0MiB| sat | 0 |  |  |
|677.smt2                                                     |    0.137s | 98.0MiB| sat | 0 |  |  |
|1649.smt2                                                    |    0.138s | 101.0MiB| unsat | 0 |  |  |
|1148.smt2                                                    |    0.138s | 99.0MiB| sat | 0 |  |  |
|From_T2__ppblockterm.t2__p7890_terminationG_0.smt2           |    0.138s | 94.24MiB| unsat | 0 |  |  |
|aproveSMT6871796204961549893.smt2                            |    0.138s | 93.092MiB| sat | 0 |  |  |
|1344.smt2                                                    |    0.138s | 101.0MiB| sat | 0 |  |  |
|1648.smt2                                                    |    0.138s | 101.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32596_safety_0.smt2 |    0.139s | 100.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4467_safety_0.smt2 |    0.139s | 100.0MiB| sat | 0 |  |  |
|aproveSMT2123657877861531207.smt2                            |    0.139s | 96.272MiB| sat | 0 |  |  |
|1511.smt2                                                    |    0.139s | 101.0MiB| sat | 0 |  |  |
|From_T2__ex36.t2__p28396_safety_0.smt2                       |    0.139s | 95.752MiB| sat | 0 |  |  |
|From_T2__ex36.t2__p32037_safety_0.smt2                       |    0.139s | 93.464MiB| unsat | 0 |  |  |
|821.smt2                                                     |    0.139s | 98.0MiB| sat | 0 |  |  |
|From_T2__zlib-adler32.c.t2__p25952_safety_0.smt2             |    0.140s | 96.444MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8209_safety_0.smt2 |    0.140s | 97.0MiB| sat | 0 |  |  |
|460.smt2                                                     |    0.140s | 99.0MiB| sat | 0 |  |  |
|Stroeder_15__aaron3_true-termination.c__p20354_terminationG_0.smt2 |    0.140s | 98.0MiB| sat | 0 |  |  |
|1500.smt2                                                    |    0.140s | 101.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30649_safety_0.smt2 |    0.140s | 99.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9177_safety_0.smt2 |    0.140s | 99.744MiB| sat | 0 |  |  |
|From_AProVE_2014__Velroyen08-marbie2.jar-obl-8__p14171_terminationG_0.smt2 |    0.141s | 93.592MiB| unsat | 0 |  |  |
|From_T2__ex36.t2_fixed__p24259_safety_0.smt2                 |    0.141s | 94.488MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1624_safety_0.smt2 |    0.141s | 100.0MiB| sat | 0 |  |  |
|From_T2__n-12.t2__p3470_edge_closing_0.smt2                  |    0.141s | 93.584MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5023_safety_0.smt2 |    0.141s | 99.0MiB| sat | 0 |  |  |
|From_AProVE_2014__Samefringe.jar-obl-10__p11956_terminationG_0.smt2 |    0.142s | 99.108MiB| sat | 0 |  |  |
|1361.smt2                                                    |    0.142s | 101.0MiB| sat | 0 |  |  |
|20.smt2                                                      |    0.142s | 103.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7493_safety_0.smt2 |    0.142s | 99.0MiB| sat | 0 |  |  |
|From_T2__consts1nt.t2_fixed__p17918_terminationG_0.smt2      |    0.142s | 92.696MiB| unsat | 0 |  |  |
|Stroeder_15__Ex04.c__p22751_terminationG_0.smt2              |    0.142s | 92.156MiB| unsat | 0 |  |  |
|1034.smt2                                                    |    0.142s | 101.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2744_safety_0.smt2 |    0.142s | 99.0MiB| sat | 0 |  |  |
|From_T2__fun10.t2__p405_terminationG_0.smt2                  |    0.142s | 98.964MiB| sat | 0 |  |  |
|From_T2__slayer-3-new.t2_fixed__p21832_safety_0.smt2         |    0.142s | 102.0MiB| sat | 0 |  |  |
|From_AProVE_2014__MainDelete.jar-obl-10__p10459_terminationG_0.smt2 |    0.142s | 96.828MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6345_safety_0.smt2 |    0.143s | 101.0MiB| sat | 0 |  |  |
|From_T2__slayer-5-filtered.t2__p22746_terminationG_0.smt2    |    0.143s | 105.0MiB| sat | 0 |  |  |
|aproveSMT2926330432023427683.smt2                            |    0.143s | 92.184MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6750_safety_0.smt2 |    0.143s | 99.0MiB| sat | 0 |  |  |
|From_T2__s1-striped.t2__p13813_safety_0.smt2                 |    0.143s | 103.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1696_safety_0.smt2 |    0.143s | 100.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5427_safety_0.smt2 |    0.144s | 100.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32268_safety_0.smt2 |    0.144s | 100.0MiB| sat | 0 |  |  |
|From_AProVE_2014__narrowing_rec.jar-obl-8__p11055_terminationG_0.smt2 |    0.144s | 98.0MiB| sat | 0 |  |  |
|From_T2__disj_nightmare.t2__p18920_terminationG_0.smt2       |    0.144s | 101.0MiB| sat | 0 |  |  |
|From_AProVE_2014__NO_10.jar-obl-8__p11301_terminationG_0.smt2 |    0.144s | 93.2MiB| unsat | 0 |  |  |
|From_T2__s1-striped.t2_fixed__p10907_safety_0.smt2           |    0.145s | 102.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32413_safety_0.smt2 |    0.145s | 100.0MiB| sat | 0 |  |  |
|From_AProVE_2014__Exc2.jar-obl-8__p29261_edge_closing_0.smt2 |    0.145s | 92.968MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2813_safety_0.smt2 |    0.145s | 100.0MiB| sat | 0 |  |  |
|aproveSMT2846862246352958329.smt2                            |    0.145s | 94.232MiB| sat | 0 |  |  |
|aproveSMT2912633883485370336.smt2                            |    0.145s | 103.0MiB| sat | 0 |  |  |
|aproveSMT522772885303483707.smt2                             |    0.146s | 91.928MiB| unsat | 0 |  |  |
|1349.smt2                                                    |    0.146s | 100.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateGet.jar-obl-11__p1105_safety_0.smt2 |    0.146s | 99.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3204_safety_0.smt2 |    0.146s | 99.0MiB| sat | 0 |  |  |
|aproveSMT3400215009548742987.smt2                            |    0.147s | 92.04MiB| unsat | 0 |  |  |
|849.smt2                                                     |    0.147s | 101.0MiB| sat | 0 |  |  |
|From_T2__slayer-3-new.t2_fixed__p21855_safety_0.smt2         |    0.147s | 100.0MiB| sat | 0 |  |  |
|From_T2__s1-striped.t2__p12976_safety_0.smt2                 |    0.148s | 104.0MiB| sat | 0 |  |  |
|From_T2__consts4nt.t2_fixed__p18242_terminationG_0.smt2      |    0.148s | 94.864MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30433_safety_0.smt2 |    0.148s | 101.0MiB| sat | 0 |  |  |
|443.smt2                                                     |    0.148s | 98.0MiB| sat | 0 |  |  |
|From_T2__s1.t2__p19576_safety_0.smt2                         |    0.148s | 103.0MiB| sat | 0 |  |  |
|1198.smt2                                                    |    0.149s | 104.0MiB| sat | 0 |  |  |
|From_T2__s1-striped.t2_fixed__p11010_safety_0.smt2           |    0.149s | 103.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8623_safety_0.smt2 |    0.149s | 99.864MiB| sat | 0 |  |  |
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26990_terminationG_0.smt2 |    0.149s | 93.832MiB| unsat | 0 |  |  |
|From_T2__small15.t2__p23750_terminationG_0.smt2              |    0.150s | 93.464MiB| unsat | 0 |  |  |
|1190.smt2                                                    |    0.150s | 102.0MiB| sat | 0 |  |  |
|1516.smt2                                                    |    0.150s | 104.0MiB| sat | 0 |  |  |
|From_T2__small18.t2__p23872_edge_closing_0.smt2              |    0.150s | 92.956MiB| unsat | 0 |  |  |
|1188.smt2                                                    |    0.150s | 103.0MiB| sat | 0 |  |  |
|From_T2__s1-striped.t2_fixed__p10066_safety_0.smt2           |    0.150s | 103.0MiB| sat | 0 |  |  |
|1192.smt2                                                    |    0.150s | 103.0MiB| sat | 0 |  |  |
|1221.smt2                                                    |    0.151s | 104.0MiB| sat | 0 |  |  |
|989.smt2                                                     |    0.151s | 109.0MiB| sat | 0 |  |  |
|From_T2__s1.t2__p18830_safety_0.smt2                         |    0.151s | 103.0MiB| sat | 0 |  |  |
|From_T2__s1.t2__p19424_safety_0.smt2                         |    0.151s | 104.0MiB| sat | 0 |  |  |
|843.smt2                                                     |    0.151s | 101.0MiB| sat | 0 |  |  |
|1371.smt2                                                    |    0.151s | 103.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3339_safety_0.smt2 |    0.151s | 101.0MiB| sat | 0 |  |  |
|1296.smt2                                                    |    0.152s | 99.916MiB| sat | 0 |  |  |
|From_T2__s1.t2__p18239_safety_0.smt2                         |    0.152s | 104.0MiB| sat | 0 |  |  |
|1521.smt2                                                    |    0.152s | 106.0MiB| sat | 0 |  |  |
|aproveSMT4159349101604568985.smt2                            |    0.152s | 91.94MiB| unsat | 0 |  |  |
|1367.smt2                                                    |    0.152s | 101.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30625_safety_0.smt2 |    0.153s | 103.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5284_safety_0.smt2 |    0.153s | 102.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29899_safety_0.smt2 |    0.153s | 99.0MiB| sat | 0 |  |  |
|From_T2__s1.t2_fixed__p16626_safety_0.smt2                   |    0.153s | 102.0MiB| sat | 0 |  |  |
|From_T2__s1.t2_fixed__p17133_safety_0.smt2                   |    0.153s | 106.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7836_safety_0.smt2 |    0.154s | 100.0MiB| sat | 0 |  |  |
|1082.smt2                                                    |    0.154s | 109.0MiB| sat | 0 |  |  |
|aproveSMT3306677380446705919.smt2                            |    0.155s | 92.144MiB| sat | 0 |  |  |
|From_T2__small14.t2__p23679_terminationG_0.smt2              |    0.155s | 95.172MiB| unsat | 0 |  |  |
|From_T2__s1-striped.t2__p12942_safety_0.smt2                 |    0.155s | 104.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2710_safety_0.smt2 |    0.155s | 100.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2836_safety_0.smt2 |    0.155s | 103.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4509_safety_0.smt2 |    0.156s | 100.0MiB| sat | 0 |  |  |
|1244.smt2                                                    |    0.157s | 106.0MiB| sat | 0 |  |  |
|From_T2__s1-striped.t2__p14256_safety_0.smt2                 |    0.157s | 104.0MiB| sat | 0 |  |  |
|From_T2__s1-striped.t2_fixed__p11206_safety_0.smt2           |    0.157s | 102.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8136_safety_0.smt2 |    0.157s | 104.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32079_safety_0.smt2 |    0.157s | 103.0MiB| sat | 0 |  |  |
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26907_terminationG_0.smt2 |    0.157s | 92.696MiB| unsat | 0 |  |  |
|From_T2__ex36.t2__p31964_safety_0.smt2                       |    0.158s | 93.72MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2974_safety_0.smt2 |    0.158s | 101.0MiB| sat | 0 |  |  |
|aproveSMT1832939841447591359.smt2                            |    0.158s | 96.66MiB| sat | 0 |  |  |
|From_T2__s1.t2__p20628_safety_0.smt2                         |    0.158s | 103.0MiB| sat | 0 |  |  |
|From_T2__janne_complex.t2_fixed__terminationS_1_0.smt2       |    0.159s | 95.384MiB| unsat | 0 |  |  |
|1852.smt2                                                    |    0.159s | 98.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31260_safety_0.smt2 |    0.159s | 102.0MiB| sat | 0 |  |  |
|841.smt2                                                     |    0.159s | 104.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3316_safety_0.smt2 |    0.160s | 102.0MiB| sat | 0 |  |  |
|From_T2__ex10.t2__p22103_terminationG_0.smt2                 |    0.160s | 92.952MiB| unsat | 0 |  |  |
|Ton_Chanh_15__2Nested_false-termination.c__p26555_terminationG_0.smt2 |    0.160s | 92.952MiB| unsat | 0 |  |  |
|1520.smt2                                                    |    0.160s | 106.0MiB| sat | 0 |  |  |
|From_T2__reverse_seg_cyclic.t2_fixed__term_unfeasibility_2_0.smt2 |    0.160s | 103.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7961_safety_0.smt2 |    0.161s | 99.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5160_safety_0.smt2 |    0.161s | 99.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5857_safety_0.smt2 |    0.161s | 104.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7334_safety_0.smt2 |    0.161s | 103.0MiB| sat | 0 |  |  |
|From_T2__fun5.t2_fixed__p1011_edge_closing_0.smt2            |    0.161s | 101.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29854_safety_0.smt2 |    0.162s | 103.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7928_safety_0.smt2 |    0.162s | 102.0MiB| sat | 0 |  |  |
|From_AProVE_2014__NO_11.jar-obl-8__p11329_terminationG_0.smt2 |    0.163s | 93.464MiB| unsat | 0 |  |  |
|From_T2__s1-striped.t2__p12812_safety_0.smt2                 |    0.164s | 104.0MiB| sat | 0 |  |  |
|From_T2__reverse_div4.t2__p8604_safety_0.smt2                |    0.164s | 98.0MiB| sat | 0 |  |  |
|From_T2__fun9.t2__p1280_edge_closing_0.smt2                  |    0.165s | 99.0MiB| sat | 0 |  |  |
|aproveSMT5335778151184305698.smt2                            |    0.166s | 98.936MiB| sat | 0 |  |  |
|1063.smt2                                                    |    0.166s | 105.0MiB| sat | 0 |  |  |
|From_T2__s1-striped.t2_fixed__p10555_safety_0.smt2           |    0.166s | 104.0MiB| sat | 0 |  |  |
|1514.smt2                                                    |    0.167s | 104.0MiB| sat | 0 |  |  |
|From_T2__ex36.t2__p28669_safety_0.smt2                       |    0.167s | 98.964MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5552_safety_0.smt2 |    0.167s | 105.0MiB| sat | 0 |  |  |
|From_T2__s1-striped.t2_fixed__p10430_safety_0.smt2           |    0.167s | 108.0MiB| sat | 0 |  |  |
|From_AProVE_2014__Et3-rec.jar-obl-8__p28848_terminationG_0.smt2 |    0.168s | 93.476MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6767_safety_0.smt2 |    0.168s | 100.0MiB| sat | 0 |  |  |
|From_T2__edn.t2__p20672_safety_0.smt2                        |    0.168s | 97.816MiB| sat | 0 |  |  |
|From_T2__n-7.t2_fixed__p4887_terminationG_0.smt2             |    0.169s | 93.464MiB| unsat | 0 |  |  |
|Ton_Chanh_15__Gothenburg_v2_true-termination.c__p26878_terminationG_0.smt2 |    0.169s | 94.488MiB| unsat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8104_safety_0.smt2 |    0.169s | 106.0MiB| sat | 0 |  |  |
|aproveSMT2316535250821506157.smt2                            |    0.170s | 113.0MiB| sat | 0 |  |  |
|From_T2__edn.t2__p21455_safety_0.smt2                        |    0.170s | 94.804MiB| unsat | 0 |  |  |
|aproveSMT342988194676879281.smt2                             |    0.170s | 96.488MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5665_safety_0.smt2 |    0.171s | 105.0MiB| sat | 0 |  |  |
|aproveSMT1750284694627347091.smt2                            |    0.172s | 94.444MiB| unsat | 0 |  |  |
|From_T2__ex36.t2__p27937_safety_0.smt2                       |    0.172s | 96.784MiB| unsat | 0 |  |  |
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24089_terminationG_0.smt2 |    0.173s | 92.868MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30088_safety_0.smt2 |    0.173s | 101.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31318_safety_0.smt2 |    0.174s | 103.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30588_safety_0.smt2 |    0.175s | 102.0MiB| sat | 0 |  |  |
|From_T2__s1-striped.t2__p14138_safety_0.smt2                 |    0.175s | 109.0MiB| sat | 0 |  |  |
|Stroeder_15__Et4.c__p22639_terminationG_0.smt2               |    0.176s | 93.632MiB| unsat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8652_safety_0.smt2 |    0.176s | 99.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4595_safety_0.smt2 |    0.176s | 106.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5725_safety_0.smt2 |    0.177s | 103.0MiB| sat | 0 |  |  |
|From_T2__slayer-n5-filtered.t2__p23305_safety_0.smt2         |    0.177s | 99.612MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31530_safety_0.smt2 |    0.177s | 99.0MiB| sat | 0 |  |  |
|From_T2__slayer-n5-filtered.t2__p23379_safety_0.smt2         |    0.178s | 97.0MiB| sat | 0 |  |  |
|From_AProVE_2014__MainCopy.jar-obl-10__p10342_terminationG_0.smt2 |    0.178s | 103.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8765_safety_0.smt2 |    0.178s | 99.0MiB| sat | 0 |  |  |
|1536.smt2                                                    |    0.179s | 109.0MiB| sat | 0 |  |  |
|1557.smt2                                                    |    0.179s | 111.0MiB| sat | 0 |  |  |
|From_AProVE_2014__Velroyen08-gauss.jar-obl-8__p14028_terminationG_0.smt2 |    0.179s | 93.196MiB| unsat | 0 |  |  |
|From_T2__s1-striped.t2_fixed__p10737_safety_0.smt2           |    0.179s | 110.0MiB| sat | 0 |  |  |
|From_T2__afagp-fail.t2_fixed__p15428_terminationG_0.smt2     |    0.179s | 97.02MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4616_safety_0.smt2 |    0.181s | 109.0MiB| sat | 0 |  |  |
|From_T2__afagp-fail.t2__terminationQ_9_0.smt2                |    0.182s | 100.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__DivMinus.jar-obl-11__p28519_terminationG_0.smt2 |    0.182s | 109.0MiB| sat | 0 |  |  |
|1199.smt2                                                    |    0.182s | 107.0MiB| sat | 0 |  |  |
|1008.smt2                                                    |    0.183s | 116.0MiB| sat | 0 |  |  |
|aproveSMT6071606564644554507.smt2                            |    0.183s | 106.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7676_safety_0.smt2 |    0.183s | 105.0MiB| sat | 0 |  |  |
|aproveSMT1656844573245055412.smt2                            |    0.184s | 93.208MiB| unsat | 0 |  |  |
|aproveSMT6405258831427788557.smt2                            |    0.184s | 97.988MiB| sat | 0 |  |  |
|From_T2__zlib-adler32.c.t2_fixed__terminationS_0_0.smt2      |    0.184s | 97.0MiB| unsat | 0 |  |  |
|1010.smt2                                                    |    0.185s | 115.0MiB| sat | 0 |  |  |
|Stroeder_15__NonTerminationSimple9_false-termination.c__p25203_terminationG_0.smt2 |    0.185s | 94.684MiB| unsat | 0 |  |  |
|From_T2__polyrank6.t2__p7590_terminationG_0.smt2             |    0.186s | 98.0MiB| sat | 0 |  |  |
|Stroeder_15__NonTermination1_false-termination.c__p24842_terminationG_0.smt2 |    0.186s | 92.696MiB| unsat | 0 |  |  |
|From_AProVE_2014__ex01_rec.jar-obl-8__p29091_terminationG_0.smt2 |    0.186s | 92.952MiB| unsat | 0 |  |  |
|From_T2__edn.t2__p19844_safety_0.smt2                        |    0.187s | 95.512MiB| unsat | 0 |  |  |
|1547.smt2                                                    |    0.187s | 111.0MiB| sat | 0 |  |  |
|aproveSMT5476436532372645500.smt2                            |    0.187s | 97.544MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4929_safety_0.smt2 |    0.187s | 104.0MiB| sat | 0 |  |  |
|From_AProVE_2014__ex04_rec.jar-obl-8__p29187_terminationG_0.smt2 |    0.188s | 94.488MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5528_safety_0.smt2 |    0.189s | 100.0MiB| sat | 0 |  |  |
|From_AProVE_2014__whileNested_rec.jar-obl-9__p14975_terminationG_0.smt2 |    0.189s | 93.216MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32285_safety_0.smt2 |    0.191s | 105.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8867_safety_0.smt2 |    0.191s | 107.0MiB| sat | 0 |  |  |
|From_T2__slayer-3.t2__p22367_safety_0.smt2                   |    0.192s | 114.0MiB| sat | 0 |  |  |
|aproveSMT1524169612101880749.smt2                            |    0.194s | 98.156MiB| sat | 0 |  |  |
|From_T2__zlib-adler32.c.t2__p26088_safety_0.smt2             |    0.194s | 93.212MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30935_safety_0.smt2 |    0.194s | 101.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5140_safety_0.smt2 |    0.196s | 108.0MiB| sat | 0 |  |  |
|aaron3_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2 |    0.196s | 93.224MiB| unsat | 0 |  |  |
|From_T2__s1.t2__p20287_safety_0.smt2                         |    0.196s | 93.048MiB| unsat | 0 |  |  |
|From_T2__s1-striped.t2_fixed__p9943_safety_0.smt2            |    0.197s | 109.0MiB| sat | 0 |  |  |
|From_T2__collatz.t2_fixed__terminationS_2_0.smt2             |    0.197s | 93.884MiB| unsat | 0 |  |  |
|aproveSMT3496695621216907819.smt2                            |    0.197s | 92.756MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31475_safety_0.smt2 |    0.198s | 105.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5754_safety_0.smt2 |    0.199s | 102.0MiB| sat | 0 |  |  |
|995.smt2                                                     |    0.201s | 117.0MiB| sat | 0 |  |  |
|aproveSMT6285895805497343865.smt2                            |    0.201s | 94.108MiB| unsat | 0 |  |  |
|From_T2__fun9.t2__p1334_edge_closing_0.smt2                  |    0.201s | 100.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8561_safety_0.smt2 |    0.202s | 116.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7772_safety_0.smt2 |    0.202s | 99.0MiB| sat | 0 |  |  |
|1258.smt2                                                    |    0.202s | 112.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9110_safety_0.smt2 |    0.202s | 116.0MiB| sat | 0 |  |  |
|From_AProVE_2014__MainFind.jar-obl-10__p10595_terminationG_0.smt2 |    0.203s | 99.4MiB| sat | 0 |  |  |
|Stroeder_15__PastaC1.c__p25352_terminationG_0.smt2           |    0.204s | 96.92MiB| sat | 0 |  |  |
|From_AProVE_2014__DivMinus.jar-obl-11__p28485_terminationG_0.smt2 |    0.204s | 124.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30861_safety_0.smt2 |    0.205s | 101.0MiB| sat | 0 |  |  |
|From_T2__ex36.t2__p30669_safety_0.smt2                       |    0.205s | 98.348MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2694_safety_0.smt2 |    0.209s | 103.0MiB| sat | 0 |  |  |
|From_T2__fun9.t2__p1302_edge_closing_0.smt2                  |    0.209s | 103.0MiB| sat | 0 |  |  |
|java_AG313-alloca_true-termination.c.i_Iteration2_Lasso+nonterminationTemplate.smt2 |    0.210s | 92.44MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32488_safety_0.smt2 |    0.211s | 107.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8256_safety_0.smt2 |    0.211s | 113.0MiB| sat | 0 |  |  |
|From_T2__s1-striped.t2__p14431_safety_0.smt2                 |    0.211s | 93.208MiB| unsat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9464_safety_0.smt2 |    0.211s | 111.0MiB| sat | 0 |  |  |
|1260.smt2                                                    |    0.212s | 121.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30522_safety_0.smt2 |    0.212s | 102.0MiB| sat | 0 |  |  |
|From_T2__s1.t2__p19829_safety_0.smt2                         |    0.214s | 108.0MiB| sat | 0 |  |  |
|1541.smt2                                                    |    0.215s | 111.0MiB| sat | 0 |  |  |
|aproveSMT3417012265546351137.smt2                            |    0.215s | 99.812MiB| sat | 0 |  |  |
|From_AProVE_2014__MainFind.jar-obl-10__p10620_edge_closing_0.smt2 |    0.215s | 99.732MiB| sat | 0 |  |  |
|term-BjWYcv.smt2                                             |    0.216s | 95.22MiB| sat | 0 |  |  |
|Stroeder_15__Fibonacci.c__p22871_terminationG_0.smt2         |    0.217s | 95.056MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5675_safety_0.smt2 |    0.218s | 105.0MiB| sat | 0 |  |  |
|From_AProVE_2014__Velroyen08-whileIncrPart.jar-obl-8__p14730_terminationG_0.smt2 |    0.219s | 93.296MiB| unsat | 0 |  |  |
|From_T2__s1.t2__p18691_safety_0.smt2                         |    0.220s | 112.0MiB| sat | 0 |  |  |
|From_T2__s1.t2__p19287_safety_0.smt2                         |    0.220s | 112.0MiB| sat | 0 |  |  |
|From_T2__s1-striped.t2__p14353_safety_0.smt2                 |    0.221s | 109.0MiB| sat | 0 |  |  |
|From_T2__edn.t2__p19908_safety_0.smt2                        |    0.224s | 95.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__KnapsackDP.jar-obl-11__p9927_safety_0.smt2 |    0.224s | 95.0MiB| unsat | 0 |  |  |
|From_T2__s1.t2__p19953_safety_0.smt2                         |    0.224s | 105.0MiB| sat | 0 |  |  |
|From_T2__s1.t2_fixed__p17590_safety_0.smt2                   |    0.224s | 93.368MiB| unsat | 0 |  |  |
|From_AProVE_2014__Velroyen08-whileBreak.jar-obl-8__p14672_terminationG_0.smt2 |    0.224s | 93.048MiB| unsat | 0 |  |  |
|From_T2__s1-striped.t2__p13759_safety_0.smt2                 |    0.225s | 107.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31371_safety_0.smt2 |    0.226s | 103.0MiB| sat | 0 |  |  |
|From_T2__matmult.t2__p2669_terminationG_0.smt2               |    0.227s | 99.608MiB| sat | 0 |  |  |
|From_T2__apchild-live.t2__p16675_safety_0.smt2               |    0.228s | 93.664MiB| unsat | 0 |  |  |
|Stroeder_15__PastaC10.c__p25335_terminationG_0.smt2          |    0.231s | 95.396MiB| unsat | 0 |  |  |
|aproveSMT7315824316795347455.smt2                            |    0.231s | 102.0MiB| sat | 0 |  |  |
|From_AProVE_2014__Velroyen08-ex06.jar-obl-8__p13693_terminationG_0.smt2 |    0.231s | 94.744MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30762_safety_0.smt2 |    0.231s | 102.0MiB| sat | 0 |  |  |
|From_T2__s1.t2__p19619_safety_0.smt2                         |    0.231s | 107.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6792_safety_0.smt2 |    0.232s | 102.0MiB| sat | 0 |  |  |
|From_T2__s1-striped.t2__p13135_safety_0.smt2                 |    0.235s | 93.536MiB| unsat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7947_safety_0.smt2 |    0.236s | 106.0MiB| sat | 0 |  |  |
|From_T2__s1-striped.t2__p13677_safety_0.smt2                 |    0.238s | 108.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31417_safety_0.smt2 |    0.240s | 102.0MiB| sat | 0 |  |  |
|From_AProVE_2014__PastaB11.jar-obl-8__terminationS_0_0.smt2  |    0.245s | 94.612MiB| unsat | 0 |  |  |
|From_AProVE_2014__sumGeneric_rec.jar-obl-8__p12350_terminationG_0.smt2 |    0.246s | 94.64MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7535_safety_0.smt2 |    0.246s | 108.0MiB| sat | 0 |  |  |
|1555.smt2                                                    |    0.246s | 119.0MiB| sat | 0 |  |  |
|From_T2__edn.t2__p20765_safety_0.smt2                        |    0.246s | 95.26MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5640_safety_0.smt2 |    0.251s | 125.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8339_safety_0.smt2 |    0.252s | 110.0MiB| sat | 0 |  |  |
|From_T2__fun7.t2__terminationQ_0_0.smt2                      |    0.255s | 120.0MiB| unsat | 0 |  |  |
|From_T2__n-46.t2__p4370_terminationG_0.smt2                  |    0.256s | 94.98MiB| unsat | 0 |  |  |
|From_T2__apchild-accepted-fail.t2_fixed__p15876_safety_0.smt2 |    0.256s | 93.72MiB| unsat | 0 |  |  |
|From_T2__s1.t2__p19772_safety_0.smt2                         |    0.256s | 115.0MiB| sat | 0 |  |  |
|From_T2__n-7.t2_fixed__terminationQ_15_0.smt2                |    0.257s | 95.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31890_safety_0.smt2 |    0.257s | 102.0MiB| sat | 0 |  |  |
|From_T2__s1.t2__p21013_safety_0.smt2                         |    0.259s | 115.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8929_safety_0.smt2 |    0.259s | 113.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7512_safety_0.smt2 |    0.259s | 105.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7407_safety_0.smt2 |    0.260s | 106.0MiB| sat | 0 |  |  |
|aproveSMT3981927164583947462.smt2                            |    0.263s | 95.436MiB| unsat | 0 |  |  |
|From_T2__n-18.t2__p3712_terminationG_0.smt2                  |    0.265s | 93.5MiB| unsat | 0 |  |  |
|From_AProVE_2014__AProVE12-cyclic-Visit.jar-obl-9__p27675_terminationG_0.smt2 |    0.265s | 99.0MiB| sat | 0 |  |  |
|From_T2__s1-striped.t2_fixed__p11854_safety_0.smt2           |    0.266s | 93.208MiB| unsat | 0 |  |  |
|From_T2__n-7.t2_fixed__p4938_terminationG_0.smt2             |    0.266s | 96.204MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30071_safety_0.smt2 |    0.267s | 103.0MiB| sat | 0 |  |  |
|From_T2__s1.t2__p18864_safety_0.smt2                         |    0.267s | 128.0MiB| sat | 0 |  |  |
|From_AProVE_2014__RSA.jar-obl-17__p11920_terminationG_0.smt2 |    0.269s | 103.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6000_safety_0.smt2 |    0.270s | 115.0MiB| sat | 0 |  |  |
|Stroeder_15__Ex04.c__p22756_terminationG_0.smt2              |    0.270s | 93.152MiB| unsat | 0 |  |  |
|aproveSMT2355004445894478329.smt2                            |    0.271s | 97.424MiB| sat | 0 |  |  |
|From_T2__edn.t2__p20225_safety_0.smt2                        |    0.273s | 95.22MiB| unsat | 0 |  |  |
|From_T2__ex36.t2__p28528_safety_0.smt2                       |    0.274s | 98.0MiB| sat | 0 |  |  |
|From_T2__s1-striped.t2_fixed__p10133_safety_0.smt2           |    0.274s | 94.232MiB| unsat | 0 |  |  |
|Stroeder_15__Fibonacci.c__p22867_terminationG_0.smt2         |    0.275s | 97.0MiB| sat | 0 |  |  |
|From_AProVE_2014__Flatten.jar-obl-10__p29393_safety_0.smt2   |    0.275s | 96.508MiB| unsat | 0 |  |  |
|From_T2__apchild-live.t2_fixed__term_unfeasibility_2_0.smt2  |    0.278s | 119.0MiB| unsat | 0 |  |  |
|Stroeder_15__svcomp_c.01-no-inv.c__p25768_terminationG_0.smt2 |    0.278s | 99.332MiB| sat | 0 |  |  |
|Stroeder_15__Factorial.c__p22852_terminationG_0.smt2         |    0.279s | 96.832MiB| unsat | 0 |  |  |
|From_T2__fun9.t2__p1483_edge_closing_0.smt2                  |    0.280s | 104.0MiB| sat | 0 |  |  |
|From_T2__byron-4.t2__p17578_terminationG_0.smt2              |    0.281s | 95.548MiB| unsat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9137_safety_0.smt2 |    0.281s | 116.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4834_safety_0.smt2 |    0.283s | 107.0MiB| sat | 0 |  |  |
|From_T2__slayer-4-filtered.t2__p22442_terminationG_0.smt2    |    0.284s | 131.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32305_safety_0.smt2 |    0.286s | 109.0MiB| sat | 0 |  |  |
|aproveSMT880649614033826505.smt2                             |    0.287s | 102.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30454_safety_0.smt2 |    0.289s | 107.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5200_safety_0.smt2 |    0.291s | 106.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7661_safety_0.smt2 |    0.291s | 122.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8731_safety_0.smt2 |    0.292s | 127.0MiB| sat | 0 |  |  |
|1.smt2                                                       |    0.293s | 122.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateLastIndexOf.jar-obl-16__term_unfeasibility_4_0.smt2 |    0.293s | 112.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4576_safety_0.smt2 |    0.294s | 108.0MiB| sat | 0 |  |  |
|From_T2__zlib-adler32.c.t2__p25903_terminationG_0.smt2       |    0.295s | 121.0MiB| sat | 0 |  |  |
|From_T2__s1.t2__p20147_safety_0.smt2                         |    0.299s | 106.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6519_terminationG_0.smt2 |    0.300s | 127.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8174_safety_0.smt2 |    0.300s | 111.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32157_safety_0.smt2 |    0.302s | 129.0MiB| sat | 0 |  |  |
|From_AProVE_2014__NonPeriodicNonterm2.jar-obl-8__terminationS_0_0.smt2 |    0.303s | 94.064MiB| unsat | 0 |  |  |
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20216_terminationG_0.smt2 |    0.304s | 101.0MiB| sat | 0 |  |  |
|From_T2__ex36.t2_fixed__p23612_safety_0.smt2                 |    0.306s | 99.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3247_safety_0.smt2 |    0.307s | 111.0MiB| sat | 0 |  |  |
|aproveSMT7070426067875134896.smt2                            |    0.307s | 93.604MiB| unsat | 0 |  |  |
|From_T2__slayer-n5-filtered.t2__p23340_safety_0.smt2         |    0.307s | 102.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4901_safety_0.smt2 |    0.308s | 121.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31389_safety_0.smt2 |    0.310s | 126.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31946_safety_0.smt2 |    0.310s | 128.0MiB| sat | 0 |  |  |
|From_T2__s1.t2__p18399_safety_0.smt2                         |    0.312s | 93.736MiB| unsat | 0 |  |  |
|From_T2__n-21.t2__p3904_terminationG_0.smt2                  |    0.317s | 96.296MiB| unsat | 0 |  |  |
|From_T2__slayer-5-filtered.t2__p22827_terminationG_0.smt2    |    0.318s | 119.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateContains.jar-obl-16__term_unfeasibility_9_0.smt2 |    0.319s | 105.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8376_safety_0.smt2 |    0.319s | 124.0MiB| sat | 0 |  |  |
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__fixed_safety_0_0.smt2 |    0.320s | 113.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31214_safety_0.smt2 |    0.321s | 120.0MiB| sat | 0 |  |  |
|From_AProVE_2014__TaylorSeriesIte.jar-obl-13__p12467_terminationG_0.smt2 |    0.321s | 133.0MiB| sat | 0 |  |  |
|604.smt2                                                     |    0.324s | 145.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__Velroyen08-upAndDown.jar-obl-8__terminationS_1_0.smt2 |    0.326s | 98.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__NO_23.jar-obl-8__p11498_terminationG_0.smt2 |    0.327s | 96.464MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31906_safety_0.smt2 |    0.327s | 121.0MiB| sat | 0 |  |  |
|From_T2__ex36.t2__p25811_safety_0.smt2                       |    0.328s | 100.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31458_safety_0.smt2 |    0.328s | 106.0MiB| sat | 0 |  |  |
|From_T2__select.t2__p21345_terminationG_0.smt2               |    0.330s | 135.0MiB| sat | 0 |  |  |
|From_T2__ppblocktermbug.t2__p7828_edge_closing_0.smt2        |    0.330s | 109.0MiB| sat | 0 |  |  |
|From_T2__ppblockterm.t2__p7907_edge_closing_0.smt2           |    0.331s | 109.0MiB| sat | 0 |  |  |
|From_T2__s1.t2__p18901_safety_0.smt2                         |    0.332s | 95.084MiB| unsat | 0 |  |  |
|From_T2__ex36.t2__p31869_safety_0.smt2                       |    0.333s | 99.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9281_safety_0.smt2 |    0.336s | 110.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2610_safety_0.smt2 |    0.337s | 108.0MiB| sat | 0 |  |  |
|aproveSMT2313612983845754801.smt2                            |    0.338s | 104.0MiB| sat | 0 |  |  |
|From_AProVE_2014__Graph.jar-obl-17__p29767_edge_closing_0.smt2 |    0.339s | 105.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1904_safety_0.smt2 |    0.341s | 108.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8641_safety_0.smt2 |    0.343s | 112.0MiB| sat | 0 |  |  |
|From_T2__byron-4.t2__p17628_terminationG_0.smt2              |    0.343s | 97.916MiB| unsat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7995_safety_0.smt2 |    0.344s | 133.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4675_safety_0.smt2 |    0.344s | 108.0MiB| sat | 0 |  |  |
|aproveSMT6201299735749963496.smt2                            |    0.345s | 109.0MiB| sat | 0 |  |  |
|From_T2__slayer-3-new.t2__p22104_safety_0.smt2               |    0.346s | 121.0MiB| sat | 0 |  |  |
|aproveSMT8801446599485295192.smt2                            |    0.347s | 107.0MiB| sat | 0 |  |  |
|From_T2__qrdcmp.c.i.qrdcmp.pl.t2.fixed.t2__term_unfeasibility_1_0.smt2 |    0.348s | 102.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3111_safety_0.smt2 |    0.350s | 105.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30020_safety_0.smt2 |    0.351s | 105.0MiB| sat | 0 |  |  |
|From_T2__n-6.t2__p4838_terminationG_0.smt2                   |    0.353s | 96.92MiB| unsat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9067_safety_0.smt2 |    0.354s | 115.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7719_safety_0.smt2 |    0.355s | 135.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5984_safety_0.smt2 |    0.356s | 106.0MiB| sat | 0 |  |  |
|From_AProVE_2014__ConvertRec.jar-obl-9__p28041_edge_closing_0.smt2 |    0.357s | 97.048MiB| unsat | 0 |  |  |
|From_AProVE_2014__upAndDownIneq_rec.jar-obl-8__terminationS_4_0.smt2 |    0.361s | 99.388MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29982_safety_0.smt2 |    0.362s | 113.0MiB| sat | 0 |  |  |
|From_T2__byron-4.t2__p17679_terminationG_0.smt2              |    0.363s | 99.436MiB| unsat | 0 |  |  |
|From_AProVE_2014__Matrix.jar-obl-16__term_unfeasibility_4_0.smt2 |    0.365s | 97.316MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30713_safety_0.smt2 |    0.366s | 137.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31837_safety_0.smt2 |    0.366s | 108.0MiB| sat | 0 |  |  |
|966.smt2                                                     |    0.367s | 100.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3067_safety_0.smt2 |    0.367s | 105.0MiB| sat | 0 |  |  |
|From_AProVE_2014__FlattenTreeListRec.jar-obl-10__p29555_safety_0.smt2 |    0.368s | 100.0MiB| sat | 0 |  |  |
|From_T2__walk.t2__p25539_terminationG_0.smt2                 |    0.370s | 98.032MiB| unsat | 0 |  |  |
|From_T2__consts5.t2__p18494_terminationG_0.smt2              |    0.371s | 96.292MiB| unsat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9081_safety_0.smt2 |    0.371s | 116.0MiB| sat | 0 |  |  |
|From_T2__s1.t2__p18741_safety_0.smt2                         |    0.371s | 128.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6085_safety_0.smt2 |    0.373s | 128.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9017_safety_0.smt2 |    0.373s | 112.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9165_safety_0.smt2 |    0.375s | 112.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8753_safety_0.smt2 |    0.376s | 122.0MiB| sat | 0 |  |  |
|Stroeder_15__GCD.c__terminationS_5_0.smt2                    |    0.383s | 99.476MiB| unsat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateRemoveAt.jar-obl-10__term_unfeasibility_3_0.smt2 |    0.384s | 101.0MiB| unsat | 0 |  |  |
|From_T2__s1-striped.t2_fixed__p11249_safety_0.smt2           |    0.384s | 111.0MiB| sat | 0 |  |  |
|From_T2__mc91.t2__p2932_edge_closing_0.smt2                  |    0.386s | 104.0MiB| sat | 0 |  |  |
|From_AProVE_2014__Count.jar-obl-10__p28177_edge_closing_0.smt2 |    0.387s | 98.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32139_safety_0.smt2 |    0.387s | 102.0MiB| sat | 0 |  |  |
|From_T2__n-40.t2__p4322_edge_closing_0.smt2                  |    0.388s | 117.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9188_safety_0.smt2 |    0.388s | 117.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4452_safety_0.smt2 |    0.388s | 109.0MiB| sat | 0 |  |  |
|From_T2__n-7.t2__p5084_terminationG_0.smt2                   |    0.388s | 97.0MiB| unsat | 0 |  |  |
|From_T2__slayer-n1.t2_fixed__p22991_safety_0.smt2            |    0.389s | 101.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9579_terminationG_0.smt2 |    0.390s | 127.0MiB| sat | 0 |  |  |
|From_T2__n-7.t2__p5034_terminationG_0.smt2                   |    0.392s | 96.608MiB| unsat | 0 |  |  |
|aproveSMT9118077011737449494.smt2                            |    0.392s | 113.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2047_safety_0.smt2 |    0.392s | 109.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30536_safety_0.smt2 |    0.394s | 143.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7234_safety_0.smt2 |    0.394s | 110.0MiB| sat | 0 |  |  |
|aproveSMT9073350781778038452.smt2                            |    0.395s | 94.724MiB| unsat | 0 |  |  |
|From_T2__agafp.t2__terminationQ_12_0.smt2                    |    0.396s | 107.0MiB| sat | 0 |  |  |
|From_T2__ex36.t2__p29189_safety_0.smt2                       |    0.397s | 100.0MiB| sat | 0 |  |  |
|From_T2__polyrank2.t2__p7393_terminationG_0.smt2             |    0.398s | 95.324MiB| unsat | 0 |  |  |
|aproveSMT8349063162874178644.smt2                            |    0.401s | 101.0MiB| sat | 0 |  |  |
|From_T2__ppblockbug.t2__p7669_terminationG_0.smt2            |    0.401s | 97.868MiB| unsat | 0 |  |  |
|574.smt2                                                     |    0.405s | 176.0MiB| sat | 0 |  |  |
|From_T2__s1.t2__p19051_safety_0.smt2                         |    0.405s | 96.372MiB| unsat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9514_safety_0.smt2 |    0.407s | 117.0MiB| sat | 0 |  |  |
|From_AProVE_2014__AlternatingGrowReduce2.jar-obl-9__terminationS_1_0.smt2 |    0.408s | 96.712MiB| unsat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8186_safety_0.smt2 |    0.408s | 117.0MiB| sat | 0 |  |  |
|572.smt2                                                     |    0.410s | 176.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8666_safety_0.smt2 |    0.411s | 116.0MiB| sat | 0 |  |  |
|From_T2__small35.t2__p24034_terminationG_0.smt2              |    0.414s | 94.436MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5840_safety_0.smt2 |    0.418s | 109.0MiB| sat | 0 |  |  |
|From_T2__s1-striped.t2__p13216_safety_0.smt2                 |    0.419s | 96.116MiB| unsat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8803_safety_0.smt2 |    0.422s | 118.0MiB| sat | 0 |  |  |
|573.smt2                                                     |    0.426s | 176.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31568_safety_0.smt2 |    0.426s | 140.0MiB| sat | 0 |  |  |
|From_T2__ex36.t2__p31717_safety_0.smt2                       |    0.426s | 100.0MiB| sat | 0 |  |  |
|From_T2__slayer-3-filtered.t2__p21738_safety_0.smt2          |    0.426s | 107.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8231_safety_0.smt2 |    0.428s | 110.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9294_safety_0.smt2 |    0.429s | 128.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30114_safety_0.smt2 |    0.429s | 113.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32246_safety_0.smt2 |    0.434s | 145.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7706_safety_0.smt2 |    0.436s | 115.0MiB| sat | 0 |  |  |
|From_T2__ex2.t2__p22462_terminationG_0.smt2                  |    0.437s | 96.4MiB| unsat | 0 |  |  |
|Stroeder_15__svcomp_ex2.c__terminationS_0_0.smt2             |    0.440s | 99.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8478_safety_0.smt2 |    0.442s | 115.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8312_safety_0.smt2 |    0.442s | 111.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31858_terminationG_0.smt2 |    0.446s | 137.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8043_safety_0.smt2 |    0.451s | 114.0MiB| sat | 0 |  |  |
|From_AProVE_2014__Velroyen08-middle.jar-obl-8__p14221_terminationG_0.smt2 |    0.452s | 95.428MiB| unsat | 0 |  |  |
|From_T2__small04.t2__p23554_terminationG_0.smt2              |    0.455s | 95.888MiB| unsat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9121_safety_0.smt2 |    0.455s | 143.0MiB| sat | 0 |  |  |
|From_T2__ex36.t2__p30341_safety_0.smt2                       |    0.459s | 102.0MiB| sat | 0 |  |  |
|From_T2__n-21.t2__p4004_terminationG_0.smt2                  |    0.460s | 97.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8124_safety_0.smt2 |    0.461s | 122.0MiB| sat | 0 |  |  |
|aproveSMT4776473963623431246.smt2                            |    0.463s | 114.0MiB| unsat | 0 |  |  |
|From_T2__1394complete-fail.t2__p15161_safety_0.smt2          |    0.463s | 123.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5586_terminationG_0.smt2 |    0.466s | 139.0MiB| sat | 0 |  |  |
|aproveSMT629665582926508878.smt2                             |    0.468s | 99.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30359_safety_0.smt2 |    0.469s | 106.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6918_safety_0.smt2 |    0.469s | 116.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__terminationS_0_0.smt2 |    0.471s | 116.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30477_safety_0.smt2 |    0.473s | 110.0MiB| sat | 0 |  |  |
|From_T2__ex36.t2__p29585_safety_0.smt2                       |    0.475s | 100.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9214_safety_0.smt2 |    0.476s | 120.0MiB| sat | 0 |  |  |
|Stroeder_15__NO_12.c__terminationS_0_0.smt2                  |    0.476s | 96.64MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1596_safety_0.smt2 |    0.476s | 110.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30993_safety_0.smt2 |    0.477s | 107.0MiB| sat | 0 |  |  |
|From_AProVE_2014__NO_13.jar-obl-8__terminationQ_1_0.smt2     |    0.481s | 96.64MiB| unsat | 0 |  |  |
|From_T2__slayer-4-filtered.t2__p22534_terminationG_0.smt2    |    0.483s | 141.0MiB| sat | 0 |  |  |
|From_T2__slayer-n5-filtered.t2__p23267_safety_0.smt2         |    0.487s | 101.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32695_safety_0.smt2 |    0.488s | 107.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32511_safety_0.smt2 |    0.489s | 100.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6125_safety_0.smt2 |    0.490s | 113.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateRemoveLastOccurrence.jar-obl-16__term_unfeasibility_9_0.smt2 |    0.490s | 111.0MiB| unsat | 0 |  |  |
|From_T2__ex36.t2__p28953_safety_0.smt2                       |    0.491s | 105.0MiB| sat | 0 |  |  |
|From_AProVE_2014__alternDivWidening_rec.jar-obl-8__p27568_terminationG_0.smt2 |    0.492s | 114.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8326_safety_0.smt2 |    0.493s | 113.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8489_safety_0.smt2 |    0.496s | 132.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4962_safety_0.smt2 |    0.500s | 110.0MiB| sat | 0 |  |  |
|From_T2__dumper.t2__terminationS_1_0.smt2                    |    0.501s | 116.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__MainDelete.jar-obl-10__p10518_edge_closing_0.smt2 |    0.503s | 99.0MiB| sat | 0 |  |  |
|aproveSMT2958125353683346121.smt2                            |    0.504s | 107.0MiB| sat | 0 |  |  |
|From_T2__n-7.t2__p5134_terminationG_0.smt2                   |    0.505s | 100.0MiB| unsat | 0 |  |  |
|Ton_Chanh_15__Benghazi_nondet_true-termination.c__p26678_terminationG_0.smt2 |    0.506s | 98.168MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7758_safety_0.smt2 |    0.507s | 127.0MiB| sat | 0 |  |  |
|From_T2__slayer-4-filtered.t2__p22597_safety_0.smt2          |    0.508s | 112.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9306_safety_0.smt2 |    0.510s | 134.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8024_safety_0.smt2 |    0.521s | 126.0MiB| sat | 0 |  |  |
|aproveSMT2059890911796961568.smt2                            |    0.522s | 97.4MiB| sat | 0 |  |  |
|From_T2__florian_sumit.t2__terminationQ_0_0.smt2             |    0.525s | 103.0MiB| unsat | 0 |  |  |
|From_T2__destroy_seg_leak.t2_fixed__p18843_safety_0.smt2     |    0.529s | 103.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7826_safety_0.smt2 |    0.530s | 112.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8917_safety_0.smt2 |    0.530s | 113.0MiB| sat | 0 |  |  |
|From_T2__ex36.t2__p31283_safety_0.smt2                       |    0.530s | 107.0MiB| sat | 0 |  |  |
|From_T2__n-6.t2_fixed__p4794_edge_closing_0.smt2             |    0.531s | 97.388MiB| sat | 0 |  |  |
|From_AProVE_2014__Convert.jar-obl-9__p27975_edge_closing_0.smt2 |    0.535s | 98.752MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2424_safety_0.smt2 |    0.536s | 117.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8791_safety_0.smt2 |    0.542s | 118.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5263_safety_0.smt2 |    0.544s | 150.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8840_safety_0.smt2 |    0.552s | 145.0MiB| sat | 0 |  |  |
|From_T2__fun9.t2__p1346_edge_closing_0.smt2                  |    0.553s | 106.0MiB| sat | 0 |  |  |
|From_T2__ex36.t2__p27260_safety_0.smt2                       |    0.554s | 101.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8741_safety_0.smt2 |    0.556s | 129.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4816_safety_0.smt2 |    0.559s | 119.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7055_safety_0.smt2 |    0.562s | 112.0MiB| sat | 0 |  |  |
|From_T2__edn.t2__p20924_safety_0.smt2                        |    0.563s | 98.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6722_safety_0.smt2 |    0.569s | 128.0MiB| sat | 0 |  |  |
|From_T2__spctrm.c.i.spctrm.pl.t2.fixed.t2__term_unfeasibility_10_0.smt2 |    0.571s | 117.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8705_safety_0.smt2 |    0.571s | 119.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31198_safety_0.smt2 |    0.578s | 106.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8513_safety_0.smt2 |    0.583s | 116.0MiB| sat | 0 |  |  |
|aproveSMT6456513912671766647.smt2                            |    0.584s | 101.0MiB| unsat | 0 |  |  |
|From_T2__fun1.t2_fixed__term_unfeasibility_0_0.smt2          |    0.585s | 137.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7794_safety_0.smt2 |    0.586s | 117.0MiB| sat | 0 |  |  |
|From_T2__ex36.t2__p27736_safety_0.smt2                       |    0.586s | 99.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4524_safety_0.smt2 |    0.587s | 132.0MiB| sat | 0 |  |  |
|From_T2__s1-striped.t2__p12752_safety_0.smt2                 |    0.588s | 125.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30786_safety_0.smt2 |    0.590s | 109.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6363_safety_0.smt2 |    0.592s | 125.0MiB| sat | 0 |  |  |
|From_T2__s1.t2_fixed__p15883_safety_0.smt2                   |    0.596s | 131.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5099_safety_0.smt2 |    0.598s | 129.0MiB| sat | 0 |  |  |
|From_T2__apchild-accepted-fail.t2_fixed__p15852_terminationG_0.smt2 |    0.605s | 157.0MiB| sat | 0 |  |  |
|From_AProVE_2014__mirrorInterv_rec.jar-obl-8__p10912_terminationG_0.smt2 |    0.606s | 123.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1650_safety_0.smt2 |    0.606s | 107.0MiB| sat | 0 |  |  |
|From_T2__s1-striped.t2__p13467_safety_0.smt2                 |    0.608s | 139.0MiB| sat | 0 |  |  |
|Stroeder_15__svcomp_ex2.c__p25846_terminationG_0.smt2        |    0.609s | 109.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32114_safety_0.smt2 |    0.611s | 130.0MiB| sat | 0 |  |  |
|From_AProVE_2014__Velroyen08-lcm.jar-obl-10__p14098_terminationG_0.smt2 |    0.611s | 97.844MiB| unsat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8294_safety_0.smt2 |    0.613s | 114.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1718_terminationG_0.smt2 |    0.617s | 148.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5362_safety_0.smt2 |    0.619s | 121.0MiB| sat | 0 |  |  |
|From_T2__zlib-crc32-BYFOUR.c.t2_fixed__p26393_terminationG_0.smt2 |    0.620s | 131.0MiB| sat | 0 |  |  |
|From_T2__slayer-3-filtered.t2__p21714_safety_0.smt2          |    0.621s | 108.0MiB| sat | 0 |  |  |
|From_T2__mc91test.t2__p3001_terminationG_0.smt2              |    0.623s | 121.0MiB| sat | 0 |  |  |
|From_T2__ex36.t2_fixed__p22547_terminationG_0.smt2           |    0.623s | 100.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9267_safety_0.smt2 |    0.624s | 124.0MiB| sat | 0 |  |  |
|From_T2__slayer-3-filtered.t2__p21762_safety_0.smt2          |    0.624s | 105.0MiB| sat | 0 |  |  |
|b.07-alloca_true-termination.c.i_Iteration2_Lasso+nonterminationTemplate.smt2 |    0.625s | 95.768MiB| unsat | 0 |  |  |
|From_T2__s1-striped.t2_fixed__p10777_safety_0.smt2           |    0.629s | 135.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32037_safety_0.smt2 |    0.632s | 109.0MiB| sat | 0 |  |  |
|From_T2__janne_complex.t2__p2024_terminationG_0.smt2         |    0.632s | 107.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6933_safety_0.smt2 |    0.636s | 113.0MiB| sat | 0 |  |  |
|From_T2__walk.t2__p25613_edge_closing_0.smt2                 |    0.637s | 103.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9322_safety_0.smt2 |    0.639s | 130.0MiB| sat | 0 |  |  |
|From_T2__s1-striped.t2__p13288_safety_0.smt2                 |    0.643s | 140.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8574_safety_0.smt2 |    0.644s | 118.0MiB| sat | 0 |  |  |
|From_T2__zlib-adler32.c.t2_fixed__p25859_safety_0.smt2       |    0.644s | 96.096MiB| unsat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7885_safety_0.smt2 |    0.649s | 166.0MiB| sat | 0 |  |  |
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13925_edge_closing_0.smt2 |    0.649s | 107.0MiB| sat | 0 |  |  |
|From_T2__slayer-n5-filtered.t2__p23413_safety_0.smt2         |    0.650s | 106.0MiB| sat | 0 |  |  |
|From_T2__walk.t2__p25598_terminationG_0.smt2                 |    0.653s | 98.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7359_safety_0.smt2 |    0.659s | 118.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5790_safety_0.smt2 |    0.659s | 110.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2274_safety_0.smt2 |    0.660s | 107.0MiB| sat | 0 |  |  |
|From_T2__polyrank4.t2__p7499_terminationG_0.smt2             |    0.661s | 100.0MiB| sat | 0 |  |  |
|From_T2__ex2.t2_fixed__p22449_terminationG_0.smt2            |    0.666s | 96.076MiB| unsat | 0 |  |  |
|From_AProVE_2014__Velroyen08-upAndDown.jar-obl-8__p14597_terminationG_0.smt2 |    0.667s | 98.0MiB| sat | 0 |  |  |
|From_T2__zeroconf.t2__terminationS_2_0.smt2                  |    0.670s | 115.0MiB| unsat | 0 |  |  |
|From_T2__ex1.t2__p22351_terminationG_0.smt2                  |    0.671s | 99.0MiB| unsat | 0 |  |  |
|From_T2__apchild-accepted-fail.t2__term_unfeasibility_2_0.smt2 |    0.672s | 136.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8778_safety_0.smt2 |    0.672s | 122.0MiB| sat | 0 |  |  |
|aproveSMT233295163504864559.smt2                             |    0.678s | 125.0MiB| unsat | 0 |  |  |
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9252_edge_closing_0.smt2 |    0.685s | 136.0MiB| sat | 0 |  |  |
|aproveSMT902782301342505505.smt2                             |    0.689s | 101.0MiB| sat | 0 |  |  |
|aproveSMT6461796824751951221.smt2                            |    0.692s | 105.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9028_safety_0.smt2 |    0.694s | 136.0MiB| sat | 0 |  |  |
|From_T2__ex16.t2_fixed__p22165_terminationG_0.smt2           |    0.694s | 98.104MiB| unsat | 0 |  |  |
|From_T2__eric2.t2__terminationQ_0_0.smt2                     |    0.695s | 136.0MiB| sat | 0 |  |  |
|aproveSMT1296180034830538453.smt2                            |    0.697s | 104.0MiB| sat | 0 |  |  |
|From_T2__streamserver.bug.t2_fixed__terminationS_2_0.smt2    |    0.703s | 111.0MiB| unsat | 0 |  |  |
|From_T2__s1-striped.t2__p14171_safety_0.smt2                 |    0.705s | 141.0MiB| sat | 0 |  |  |
|aproveSMT4817399800518468578.smt2                            |    0.706s | 99.0MiB| sat | 0 |  |  |
|From_T2__ex36.t2__p30487_safety_0.smt2                       |    0.706s | 102.0MiB| sat | 0 |  |  |
|From_AProVE_2014__Test13Loops.jar-obl-10__p12672_terminationG_0.smt2 |    0.710s | 116.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8419_safety_0.smt2 |    0.710s | 141.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30234_safety_0.smt2 |    0.713s | 113.0MiB| sat | 0 |  |  |
|From_T2__fun9.t2__p1376_edge_closing_0.smt2                  |    0.716s | 110.0MiB| sat | 0 |  |  |
|From_T2__n-21.t2__p3954_terminationG_0.smt2                  |    0.716s | 97.892MiB| unsat | 0 |  |  |
|From_T2__ex36.t2_fixed__p23187_safety_0.smt2                 |    0.719s | 98.812MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5085_safety_0.smt2 |    0.720s | 116.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31079_safety_0.smt2 |    0.723s | 158.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8386_safety_0.smt2 |    0.723s | 170.0MiB| sat | 0 |  |  |
|aproveSMT993796237976442048.smt2                             |    0.724s | 101.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8694_safety_0.smt2 |    0.725s | 112.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8544_safety_0.smt2 |    0.725s | 148.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5318_safety_0.smt2 |    0.727s | 120.0MiB| sat | 0 |  |  |
|From_T2__eric.t2__p22069_terminationG_0.smt2                 |    0.734s | 103.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8406_safety_0.smt2 |    0.735s | 119.0MiB| sat | 0 |  |  |
|From_T2__s1.t2__p18716_safety_0.smt2                         |    0.738s | 141.0MiB| sat | 0 |  |  |
|From_T2__n-40.t2__p4267_terminationG_0.smt2                  |    0.739s | 98.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6179_safety_0.smt2 |    0.739s | 160.0MiB| sat | 0 |  |  |
|From_AProVE_2014__NO_13.jar-obl-8__p11445_edge_closing_0.smt2 |    0.742s | 99.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6833_safety_0.smt2 |    0.743s | 130.0MiB| sat | 0 |  |  |
|From_T2__consts5nt.t2__p18444_edge_closing_0.smt2            |    0.744s | 115.0MiB| sat | 0 |  |  |
|From_T2__s1-striped.t2__p12904_safety_0.smt2                 |    0.747s | 141.0MiB| sat | 0 |  |  |
|From_AProVE_2014__SortCount.jar-obl-10__terminationQ_3_0.smt2 |    0.756s | 134.0MiB| sat | 0 |  |  |
|From_T2__n-46.t2__p4421_terminationG_0.smt2                  |    0.759s | 98.3MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3015_safety_0.smt2 |    0.759s | 135.0MiB| sat | 0 |  |  |
|From_AProVE_2014__Et4.jar-obl-8__p28936_terminationG_0.smt2  |    0.762s | 103.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5483_safety_0.smt2 |    0.770s | 151.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5117_safety_0.smt2 |    0.770s | 163.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8717_safety_0.smt2 |    0.772s | 131.0MiB| sat | 0 |  |  |
|From_T2__apchildlive-succeed.t2_fixed__term_unfeasibility_1_0.smt2 |    0.773s | 145.0MiB| unsat | 0 |  |  |
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27021_terminationG_0.smt2 |    0.775s | 99.0MiB| sat | 0 |  |  |
|From_T2__s1.t2__p19160_safety_0.smt2                         |    0.778s | 141.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1578_safety_0.smt2 |    0.778s | 100.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9392_safety_0.smt2 |    0.779s | 168.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30154_safety_0.smt2 |    0.781s | 129.0MiB| sat | 0 |  |  |
|From_T2__edn.t2__p19793_safety_0.smt2                        |    0.782s | 106.0MiB| sat | 0 |  |  |
|From_T2__n-40.t2_fixed__p4233_terminationG_0.smt2            |    0.785s | 97.816MiB| unsat | 0 |  |  |
|Stroeder_15__MirrorIntervSim.c__p24483_terminationG_0.smt2   |    0.786s | 96.384MiB| unsat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7784_safety_0.smt2 |    0.792s | 117.0MiB| sat | 0 |  |  |
|Stroeder_15__Et1.c__p22595_terminationG_0.smt2               |    0.793s | 104.0MiB| sat | 0 |  |  |
|From_AProVE_2014__alternKonv_rec.jar-obl-8__p27639_edge_closing_0.smt2 |    0.799s | 98.328MiB| unsat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8465_safety_0.smt2 |    0.801s | 177.0MiB| sat | 0 |  |  |
|From_T2__db3.t2__terminationS_26_0.smt2                      |    0.806s | 141.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32438_safety_0.smt2 |    0.810s | 124.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4727_safety_0.smt2 |    0.812s | 113.0MiB| sat | 0 |  |  |
|From_T2__s1.t2__p21118_safety_0.smt2                         |    0.815s | 142.0MiB| sat | 0 |  |  |
|From_T2__mc91test.t2__p3031_terminationG_0.smt2              |    0.816s | 143.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32340_safety_0.smt2 |    0.821s | 115.0MiB| sat | 0 |  |  |
|From_AProVE_2014__sunset_rec.jar-obl-8__p12391_terminationG_0.smt2 |    0.824s | 103.0MiB| sat | 0 |  |  |
|From_T2__edn.t2__p20050_safety_0.smt2                        |    0.826s | 104.0MiB| sat | 0 |  |  |
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26899_terminationG_0.smt2 |    0.829s | 101.0MiB| sat | 0 |  |  |
|From_T2__p.t2__terminationS_3_0.smt2                         |    0.830s | 112.0MiB| unsat | 0 |  |  |
|aproveSMT3935457195847984314.smt2                            |    0.831s | 99.0MiB| unsat | 0 |  |  |
|From_T2__ex36.t2__p31596_safety_0.smt2                       |    0.837s | 98.736MiB| unsat | 0 |  |  |
|From_T2__s1.t2_fixed__p17067_safety_0.smt2                   |    0.837s | 141.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8977_safety_0.smt2 |    0.838s | 133.0MiB| sat | 0 |  |  |
|From_T2__s1.t2__p19317_safety_0.smt2                         |    0.843s | 141.0MiB| sat | 0 |  |  |
|From_AProVE_2014__KnapsackDP.jar-obl-11__terminationQ_4_0.smt2 |    0.845s | 102.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5710_safety_0.smt2 |    0.846s | 112.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2794_safety_0.smt2 |    0.846s | 113.0MiB| sat | 0 |  |  |
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__p32684_safety_0.smt2 |    0.849s | 99.62MiB| unsat | 0 |  |  |
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__term_unfeasibility_1_0.smt2 |    0.850s | 144.0MiB| sat | 0 |  |  |
|From_T2__db3.t2_fixed__terminationS_21_0.smt2                |    0.851s | 122.0MiB| unsat | 0 |  |  |
|From_T2__db2.t2__terminationS_20_0.smt2                      |    0.853s | 135.0MiB| unsat | 0 |  |  |
|flag-alloca_true-termination.c.i_Iteration1_Lasso+nonterminationTemplate.smt2 |    0.854s | 98.584MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5566_safety_0.smt2 |    0.856s | 157.0MiB| sat | 0 |  |  |
|aproveSMT7145338241152838632.smt2                            |    0.862s | 121.0MiB| sat | 0 |  |  |
|aproveSMT2315623815142209104.smt2                            |    0.867s | 102.0MiB| unsat | 0 |  |  |
|From_T2__streamserver.bug.t2__terminationS_0_0.smt2          |    0.869s | 113.0MiB| unsat | 0 |  |  |
|From_T2__s1-striped.t2_fixed__p10168_safety_0.smt2           |    0.871s | 137.0MiB| sat | 0 |  |  |
|From_T2__ex36.t2__p31932_safety_0.smt2                       |    0.877s | 97.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2952_safety_0.smt2 |    0.879s | 118.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6207_safety_0.smt2 |    0.881s | 127.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4423_safety_0.smt2 |    0.881s | 155.0MiB| sat | 0 |  |  |
|From_AProVE_2014__Velroyen08-flip2.jar-obl-8__p13963_edge_closing_0.smt2 |    0.888s | 103.0MiB| sat | 0 |  |  |
|From_AProVE_2014__MainMove.jar-obl-11__p10751_edge_closing_0.smt2 |    0.896s | 104.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8053_safety_0.smt2 |    0.899s | 120.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30611_safety_0.smt2 |    0.901s | 119.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31302_safety_0.smt2 |    0.902s | 136.0MiB| sat | 0 |  |  |
|From_T2__s1-striped.t2_fixed__p11816_safety_0.smt2           |    0.909s | 115.0MiB| unsat | 0 |  |  |
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26981_terminationG_0.smt2 |    0.909s | 103.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31023_safety_0.smt2 |    0.911s | 130.0MiB| sat | 0 |  |  |
|From_T2__s1-striped.t2_fixed__p10604_safety_0.smt2           |    0.912s | 141.0MiB| sat | 0 |  |  |
|From_T2__db2.t2_fixed__terminationS_18_0.smt2                |    0.915s | 129.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6071_safety_0.smt2 |    0.915s | 123.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7913_safety_0.smt2 |    0.921s | 123.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7846_safety_0.smt2 |    0.921s | 140.0MiB| sat | 0 |  |  |
|From_T2__mc91.t2__p2810_terminationG_0.smt2                  |    0.923s | 103.0MiB| unsat | 0 |  |  |
|From_T2__ex36.t2__p30759_safety_0.smt2                       |    0.929s | 116.0MiB| sat | 0 |  |  |
|From_T2__non_term.t2__p6235_terminationG_0.smt2              |    0.931s | 99.36MiB| unsat | 0 |  |  |
|From_T2__opt-tree.c.t2__terminationS_1_0.smt2                |    0.935s | 144.0MiB| unsat | 0 |  |  |
|From_T2__s1-striped.t2__p13058_safety_0.smt2                 |    0.942s | 146.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3177_safety_0.smt2 |    0.943s | 117.0MiB| sat | 0 |  |  |
|From_T2__s1.t2__p18964_safety_0.smt2                         |    0.947s | 140.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8353_safety_0.smt2 |    0.947s | 121.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6858_terminationG_0.smt2 |    0.949s | 145.0MiB| sat | 0 |  |  |
|aproveSMT7861215804091976133.smt2                            |    0.953s | 99.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30178_terminationG_0.smt2 |    0.956s | 145.0MiB| sat | 0 |  |  |
|Stroeder_15__NonTerminationSimple8_false-termination.c__p25188_edge_closing_0.smt2 |    0.958s | 103.0MiB| sat | 0 |  |  |
|From_T2__apchild-live.t2__terminationS_1_0.smt2              |    0.962s | 169.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9447_safety_0.smt2 |    0.970s | 174.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31555_safety_0.smt2 |    0.971s | 100.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5245_safety_0.smt2 |    0.977s | 136.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2587_safety_0.smt2 |    0.977s | 132.0MiB| sat | 0 |  |  |
|From_T2__apchild-live.t2_fixed__p16518_safety_0.smt2         |    0.978s | 99.276MiB| unsat | 0 |  |  |
|From_T2__apchild-live.t2__terminationS_4_0.smt2              |    0.979s | 169.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5220_safety_0.smt2 |    0.981s | 119.0MiB| sat | 0 |  |  |
|From_T2__slayer-4-filtered.t2__p22647_safety_0.smt2          |    0.981s | 112.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7804_safety_0.smt2 |    0.983s | 139.0MiB| sat | 0 |  |  |
|Stroeder_15__Pure3Phase_true-termination.c__p25518_terminationG_0.smt2 |    0.986s | 118.0MiB| sat | 0 |  |  |
|From_T2__ex36.t2__p31824_safety_0.smt2                       |    0.994s | 102.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30418_safety_0.smt2 |    0.996s | 101.0MiB| unsat | 0 |  |  |
|From_T2__zlib-adler32.c.t2_fixed__p25815_safety_0.smt2       |    0.996s | 98.0MiB| unsat | 0 |  |  |
|From_T2__randomwalk.t2__p8459_edge_closing_0.smt2            |    1.007s | 136.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2292_safety_0.smt2 |    1.008s | 126.0MiB| sat | 0 |  |  |
|From_AProVE_2014__Velroyen08-complxStruc.jar-obl-8__terminationQ_0_0.smt2 |    1.011s | 103.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9149_safety_0.smt2 |    1.012s | 138.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8365_safety_0.smt2 |    1.021s | 136.0MiB| sat | 0 |  |  |
|From_T2__s1.t2__p19123_safety_0.smt2                         |    1.022s | 144.0MiB| sat | 0 |  |  |
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27220_terminationG_0.smt2 |    1.024s | 116.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8241_safety_0.smt2 |    1.032s | 120.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4490_safety_0.smt2 |    1.036s | 126.0MiB| sat | 0 |  |  |
|From_T2__s1-striped.t2_fixed__p9567_safety_0.smt2            |    1.038s | 142.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6477_safety_0.smt2 |    1.038s | 170.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29877_safety_0.smt2 |    1.043s | 101.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30967_safety_0.smt2 |    1.044s | 138.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7255_safety_0.smt2 |    1.050s | 139.0MiB| sat | 0 |  |  |
|From_T2__randomwalk.t2__p8420_terminationG_0.smt2            |    1.051s | 114.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8945_safety_0.smt2 |    1.052s | 141.0MiB| sat | 0 |  |  |
|From_AProVE_2014__Test13Loops.jar-obl-10__p12748_edge_closing_0.smt2 |    1.052s | 116.0MiB| sat | 0 |  |  |
|From_T2__slayer-n1.t2_fixed__p23010_safety_0.smt2            |    1.054s | 115.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5922_safety_0.smt2 |    1.054s | 140.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9255_safety_0.smt2 |    1.058s | 134.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2019_safety_0.smt2 |    1.059s | 101.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5884_safety_0.smt2 |    1.063s | 122.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__terminationS_2_0.smt2 |    1.064s | 112.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8219_safety_0.smt2 |    1.064s | 133.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9241_safety_0.smt2 |    1.066s | 137.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3228_safety_0.smt2 |    1.072s | 103.0MiB| unsat | 0 |  |  |
|From_T2__Prim_4.t2__p8088_edge_closing_0.smt2                |    1.077s | 119.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__terminationS_1_0.smt2 |    1.078s | 120.0MiB| unsat | 0 |  |  |
|From_T2__slayer-5-filtered.t2__p22860_terminationG_0.smt2    |    1.081s | 145.0MiB| sat | 0 |  |  |
|From_T2__s1-striped.t2__p14737_safety_0.smt2                 |    1.084s | 116.0MiB| unsat | 0 |  |  |
|From_T2__mc91test.t2__p3167_terminationG_0.smt2              |    1.085s | 151.0MiB| sat | 0 |  |  |
|From_AProVE_2014__Velroyen08-ex02.jar-obl-8__p13595_terminationG_0.smt2 |    1.085s | 104.0MiB| sat | 0 |  |  |
|From_T2__curious.t2__p18703_terminationG_0.smt2              |    1.086s | 98.644MiB| unsat | 0 |  |  |
|From_T2__db2.t2__terminationS_6_0.smt2                       |    1.088s | 151.0MiB| unsat | 0 |  |  |
|From_T2__s1.t2_fixed__p16586_safety_0.smt2                   |    1.093s | 101.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__Velroyen08-plait.jar-obl-8__p14480_terminationG_0.smt2 |    1.094s | 118.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8012_safety_0.smt2 |    1.097s | 203.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32658_safety_0.smt2 |    1.102s | 121.0MiB| sat | 0 |  |  |
|From_T2__n-3.t2__p4212_terminationG_0.smt2                   |    1.106s | 98.0MiB| unsat | 0 |  |  |
|From_T2__s1-striped.t2__p13547_safety_0.smt2                 |    1.110s | 150.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8266_safety_0.smt2 |    1.119s | 133.0MiB| sat | 0 |  |  |
|From_T2__s1-striped.t2__p13600_safety_0.smt2                 |    1.120s | 145.0MiB| sat | 0 |  |  |
|From_T2__s1-striped.t2_fixed__p11134_safety_0.smt2           |    1.123s | 144.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9409_safety_0.smt2 |    1.124s | 121.0MiB| sat | 0 |  |  |
|From_T2__polling.bug.t2__term_unfeasibility_0_0.smt2         |    1.126s | 167.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8446_safety_0.smt2 |    1.128s | 122.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32619_safety_0.smt2 |    1.129s | 123.0MiB| sat | 0 |  |  |
|Stroeder_15__svcomp_ex2.c__p25847_terminationG_0.smt2        |    1.133s | 137.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6393_safety_0.smt2 |    1.137s | 129.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6638_safety_0.smt2 |    1.145s | 139.0MiB| sat | 0 |  |  |
|aproveSMT3571876635740058861.smt2                            |    1.149s | 106.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7870_safety_0.smt2 |    1.151s | 145.0MiB| sat | 0 |  |  |
|From_AProVE_2014__TaylorSeriesIte.jar-obl-13__terminationS_12_0.smt2 |    1.151s | 125.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5068_safety_0.smt2 |    1.153s | 119.0MiB| sat | 0 |  |  |
|From_T2__edn.t2__p20506_safety_0.smt2                        |    1.153s | 101.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__terminationS_2_0.smt2 |    1.153s | 127.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__Velroyen08-factorial.jar-obl-8__p13819_terminationG_0.smt2 |    1.159s | 100.0MiB| unsat | 0 |  |  |
|From_T2__ex16.t2_fixed__p22190_terminationG_0.smt2           |    1.169s | 98.0MiB| unsat | 0 |  |  |
|From_T2__db3.t2__terminationS_40_0.smt2                      |    1.170s | 150.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8680_safety_0.smt2 |    1.171s | 179.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7974_safety_0.smt2 |    1.171s | 207.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7858_safety_0.smt2 |    1.172s | 137.0MiB| sat | 0 |  |  |
|From_T2__spctrm.t2__term_unfeasibility_5_0.smt2              |    1.175s | 137.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9426_safety_0.smt2 |    1.181s | 159.0MiB| sat | 0 |  |  |
|aproveSMT8213728202959413718.smt2                            |    1.185s | 110.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30251_safety_0.smt2 |    1.193s | 101.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__LessLeaves.jar-obl-10__p9986_terminationG_0.smt2 |    1.193s | 112.0MiB| sat | 0 |  |  |
|From_AProVE_2014__Velroyen08-lcm.jar-obl-10__p14129_edge_closing_0.smt2 |    1.194s | 113.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9373_terminationG_0.smt2 |    1.195s | 162.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6247_safety_0.smt2 |    1.203s | 144.0MiB| sat | 0 |  |  |
|From_T2__mc91test.t2__p3304_terminationG_0.smt2              |    1.205s | 151.0MiB| sat | 0 |  |  |
|From_T2__s1.t2__p19467_safety_0.smt2                         |    1.207s | 99.124MiB| unsat | 0 |  |  |
|From_T2__st88b-fail.t2__p24138_terminationG_0.smt2           |    1.207s | 104.0MiB| sat | 0 |  |  |
|aproveSMT5989587704234446991.smt2                            |    1.211s | 123.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6811_safety_0.smt2 |    1.211s | 176.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__terminationS_0_0.smt2 |    1.215s | 119.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8814_safety_0.smt2 |    1.217s | 137.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7733_safety_0.smt2 |    1.219s | 122.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32579_safety_0.smt2 |    1.220s | 117.0MiB| sat | 0 |  |  |
|From_T2__edn.t2__p21367_safety_0.smt2                        |    1.224s | 115.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8988_safety_0.smt2 |    1.226s | 135.0MiB| sat | 0 |  |  |
|From_T2__slayer-4-filtered.t2__p22580_terminationG_0.smt2    |    1.227s | 182.0MiB| sat | 0 |  |  |
|From_T2__small03.t2__p23533_terminationG_0.smt2              |    1.228s | 99.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31062_safety_0.smt2 |    1.229s | 117.0MiB| sat | 0 |  |  |
|From_AProVE_2014__Velroyen08-middle.jar-obl-8__p14201_terminationG_0.smt2 |    1.231s | 111.0MiB| sat | 0 |  |  |
|From_T2__s1-striped.t2_fixed__p10512_safety_0.smt2           |    1.231s | 148.0MiB| sat | 0 |  |  |
|From_T2__edn.t2__p21066_safety_0.smt2                        |    1.234s | 105.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4694_safety_0.smt2 |    1.239s | 140.0MiB| sat | 0 |  |  |
|From_T2__afagp-fail.t2__p15470_terminationG_0.smt2           |    1.242s | 98.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3037_safety_0.smt2 |    1.246s | 137.0MiB| sat | 0 |  |  |
|From_T2__slayer-3-filtered.t2__p21547_terminationG_0.smt2    |    1.246s | 119.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__List.jar-obl-12__p10211_edge_closing_0.smt2 |    1.252s | 108.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30132_safety_0.smt2 |    1.257s | 175.0MiB| sat | 0 |  |  |
|From_T2__ex36.t2__p29508_safety_0.smt2                       |    1.259s | 101.0MiB| sat | 0 |  |  |
|From_T2__pgarch.t2__p7265_terminationG_0.smt2                |    1.260s | 184.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2229_safety_0.smt2 |    1.262s | 101.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2565_safety_0.smt2 |    1.263s | 126.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8278_safety_0.smt2 |    1.263s | 142.0MiB| sat | 0 |  |  |
|From_T2__s1-striped.t2__p13097_safety_0.smt2                 |    1.268s | 152.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2501_safety_0.smt2 |    1.275s | 129.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8197_safety_0.smt2 |    1.279s | 127.0MiB| sat | 0 |  |  |
|From_T2__s1-striped.t2_fixed__p11971_safety_0.smt2           |    1.281s | 144.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30699_safety_0.smt2 |    1.283s | 103.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4544_terminationG_0.smt2 |    1.285s | 158.0MiB| sat | 0 |  |  |
|From_T2__apchild-live.t2_fixed__p16558_terminationG_0.smt2   |    1.289s | 201.0MiB| sat | 0 |  |  |
|From_T2__ex36.t2__p31483_safety_0.smt2                       |    1.293s | 108.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7898_safety_0.smt2 |    1.295s | 132.0MiB| sat | 0 |  |  |
|From_T2__db2.t2_fixed__terminationS_28_0.smt2                |    1.298s | 130.0MiB| unsat | 0 |  |  |
|aproveSMT8137047330849691949.smt2                            |    1.303s | 110.0MiB| unsat | 0 |  |  |
|Stroeder_15__Et1.c__p22590_terminationG_0.smt2               |    1.306s | 110.0MiB| sat | 0 |  |  |
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_7_0.smt2 |    1.307s | 152.0MiB| unsat | 0 |  |  |
|From_T2__slayer-4-filtered.t2__terminationS_3_0.smt2         |    1.320s | 130.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9599_safety_0.smt2 |    1.323s | 160.0MiB| sat | 0 |  |  |
|From_AProVE_2014__Distances.jar-obl-19__terminationS_12_0.smt2 |    1.326s | 152.0MiB| unsat | 0 |  |  |
|From_T2__s1-striped.t2_fixed__p10987_safety_0.smt2           |    1.337s | 97.848MiB| unsat | 0 |  |  |
|From_AProVE_2014__DivTernary2.jar-obl-9__p28622_terminationG_0.smt2 |    1.338s | 103.0MiB| unsat | 0 |  |  |
|583.smt2                                                     |    1.344s | 255.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5896_safety_0.smt2 |    1.346s | 150.0MiB| sat | 0 |  |  |
|From_T2__ex36.t2__p31535_safety_0.smt2                       |    1.352s | 107.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32102_safety_0.smt2 |    1.360s | 106.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13879_terminationG_0.smt2 |    1.369s | 106.0MiB| unsat | 0 |  |  |
|From_T2__s1-striped.t2__p14001_safety_0.smt2                 |    1.372s | 149.0MiB| sat | 0 |  |  |
|From_AProVE_2014__Graph.jar-obl-17__terminationQ_2_0.smt2    |    1.376s | 103.0MiB| unsat | 0 |  |  |
|From_T2__edn.t2__p20696_safety_0.smt2                        |    1.377s | 107.0MiB| sat | 0 |  |  |
|From_T2__neg-acqrel-fail.t2__p5620_terminationG_0.smt2       |    1.379s | 98.0MiB| unsat | 0 |  |  |
|From_T2__heidy1.t2__p1531_terminationG_0.smt2                |    1.386s | 99.14MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31502_safety_0.smt2 |    1.387s | 103.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__terminationS_1_0.smt2 |    1.408s | 123.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31631_safety_0.smt2 |    1.410s | 103.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31705_safety_0.smt2 |    1.410s | 118.0MiB| sat | 0 |  |  |
|From_T2__slayer-4-filtered.t2__p22710_safety_0.smt2          |    1.411s | 121.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2200_safety_0.smt2 |    1.420s | 104.0MiB| unsat | 0 |  |  |
|From_T2__slayer-3-new.t2__p21887_terminationG_0.smt2         |    1.428s | 160.0MiB| unsat | 0 |  |  |
|From_T2__Prim_4.t2__p7965_terminationG_0.smt2                |    1.430s | 124.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31816_safety_0.smt2 |    1.431s | 130.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32526_safety_0.smt2 |    1.433s | 102.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__mirrorInterv_rec.jar-obl-8__p10946_edge_closing_0.smt2 |    1.435s | 130.0MiB| sat | 0 |  |  |
|From_T2__pentagon.t2__p7043_edge_closing_0.smt2              |    1.439s | 102.0MiB| unsat | 0 |  |  |
|From_T2__s1.t2__p20227_safety_0.smt2                         |    1.441s | 156.0MiB| sat | 0 |  |  |
|From_T2__s1.t2_fixed__p17686_safety_0.smt2                   |    1.445s | 151.0MiB| sat | 0 |  |  |
|Hanoi_plus_false-termination.c_Iteration1_Lasso+nonterminationTemplate_0.smt2 |    1.445s | 101.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1749_safety_0.smt2 |    1.446s | 102.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2336_safety_0.smt2 |    1.447s | 143.0MiB| sat | 0 |  |  |
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_14_0.smt2  |    1.447s | 161.0MiB| unsat | 0 |  |  |
|Ton_Chanh_15__Mysore_false-termination.c__p27288_edge_closing_0.smt2 |    1.449s | 109.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31280_safety_0.smt2 |    1.450s | 167.0MiB| sat | 0 |  |  |
|From_T2__s1.t2_fixed__p16526_safety_0.smt2                   |    1.455s | 99.448MiB| unsat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9199_safety_0.smt2 |    1.460s | 146.0MiB| sat | 0 |  |  |
|From_T2__edn.t2__p20322_safety_0.smt2                        |    1.461s | 103.0MiB| sat | 0 |  |  |
|From_T2__pentagon.t2__p7126_edge_closing_0.smt2              |    1.465s | 101.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30804_safety_0.smt2 |    1.465s | 139.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4946_safety_0.smt2 |    1.468s | 174.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8067_safety_0.smt2 |    1.470s | 177.0MiB| sat | 0 |  |  |
|From_T2__slayer-5-filtered.t2__p22780_safety_0.smt2          |    1.470s | 115.0MiB| sat | 0 |  |  |
|From_T2__slayer-n1.t2_fixed__p23091_safety_0.smt2            |    1.471s | 117.0MiB| sat | 0 |  |  |
|Stroeder_15__NO_10.c__p24670_terminationG_0.smt2             |    1.475s | 98.0MiB| unsat | 0 |  |  |
|aproveSMT5858552346124402853.smt2                            |    1.489s | 102.0MiB| unsat | 0 |  |  |
|aproveSMT5606410117877393489.smt2                            |    1.489s | 129.0MiB| sat | 0 |  |  |
|From_T2__s1-striped.t2_fixed__p10708_safety_0.smt2           |    1.494s | 98.548MiB| unsat | 0 |  |  |
|From_AProVE_2014__Velroyen08-whileNestedOffset.jar-obl-8__p14810_edge_closing_0.smt2 |    1.507s | 105.0MiB| sat | 0 |  |  |
|From_T2__slayer-3.t2_fixed__terminationS_13_0.smt2           |    1.510s | 190.0MiB| unsat | 0 |  |  |
|From_T2__ex36.t2__p27854_safety_0.smt2                       |    1.515s | 120.0MiB| sat | 0 |  |  |
|Stroeder_15__NonTermination2_false-termination.c__p24928_edge_closing_0.smt2 |    1.524s | 149.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30308_safety_0.smt2 |    1.542s | 104.0MiB| unsat | 0 |  |  |
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8875_terminationG_0.smt2 |    1.542s | 137.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29941_safety_0.smt2 |    1.561s | 139.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32061_safety_0.smt2 |    1.561s | 105.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32455_safety_0.smt2 |    1.563s | 150.0MiB| sat | 0 |  |  |
|From_T2__n-15a.t2__p3581_terminationG_0.smt2                 |    1.565s | 108.0MiB| sat | 0 |  |  |
|From_T2__slayer-3.t2__p22188_terminationG_0.smt2             |    1.566s | 167.0MiB| unsat | 0 |  |  |
|aproveSMT9190658207098859112.smt2                            |    1.574s | 202.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6620_safety_0.smt2 |    1.577s | 139.0MiB| sat | 0 |  |  |
|From_T2__consts3nt.t2__p18179_terminationG_0.smt2            |    1.591s | 101.0MiB| unsat | 0 |  |  |
|From_T2__bakery.t2__p17068_terminationG_0.smt2               |    1.612s | 106.0MiB| unsat | 0 |  |  |
|From_T2__firewire.t2__terminationS_27_0.smt2                 |    1.615s | 157.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30215_safety_0.smt2 |    1.616s | 105.0MiB| unsat | 0 |  |  |
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_56_0.smt2 |    1.619s | 160.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31238_safety_0.smt2 |    1.624s | 104.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__DivTernary.jar-obl-10__terminationS_23_0.smt2 |    1.627s | 171.0MiB| unsat | 0 |  |  |
|From_T2__s1-striped.t2__term_unfeasibility_1_0.smt2          |    1.628s | 125.0MiB| sat | 0 |  |  |
|From_AProVE_2014__Graph.jar-obl-17__p29751_terminationG_0.smt2 |    1.631s | 107.0MiB| unsat | 0 |  |  |
|From_T2__rlft3.t2__p9095_terminationG_0.smt2                 |    1.642s | 114.0MiB| unsat | 0 |  |  |
|From_T2__mc91.t2__p2861_terminationG_0.smt2                  |    1.642s | 106.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__upAndDown_rec.jar-obl-8__terminationS_3_0.smt2 |    1.651s | 108.0MiB| unsat | 0 |  |  |
|From_T2__rlft3.t2__p9044_terminationG_0.smt2                 |    1.653s | 112.0MiB| unsat | 0 |  |  |
|From_T2__s1.t2_fixed__p16485_safety_0.smt2                   |    1.654s | 101.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p374_safety_0.smt2 |    1.665s | 162.0MiB| sat | 0 |  |  |
|586.smt2                                                     |    1.667s | 297.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateEquals.jar-obl-13__term_unfeasibility_5_0.smt2 |    1.680s | 121.0MiB| unsat | 0 |  |  |
|From_T2__n-5.t2__p4701_edge_closing_0.smt2                   |    1.689s | 129.0MiB| sat | 0 |  |  |
|From_T2__n-48.t2__p4500_terminationG_0.smt2                  |    1.689s | 101.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2859_safety_0.smt2 |    1.698s | 105.0MiB| unsat | 0 |  |  |
|From_T2__oct_vs_subpoly.t2__p6291_terminationG_0.smt2        |    1.710s | 129.0MiB| unsat | 0 |  |  |
|From_T2__ndes.t2_fixed__term_unfeasibility_2_0.smt2          |    1.715s | 122.0MiB| sat | 0 |  |  |
|From_T2__n-9.t2__p5277_terminationG_0.smt2                   |    1.730s | 132.0MiB| unsat | 0 |  |  |
|From_T2__ex36.t2_fixed__p24107_safety_0.smt2                 |    1.735s | 98.0MiB| sat | 0 |  |  |
|From_T2__edn.t2__p20262_safety_0.smt2                        |    1.742s | 104.0MiB| sat | 0 |  |  |
|Stroeder_15__ComplxStruc.c__p22350_terminationG_0.smt2       |    1.744s | 105.0MiB| unsat | 0 |  |  |
|Stroeder_15__Ex04.c__p22757_terminationG_0.smt2              |    1.753s | 100.0MiB| unsat | 0 |  |  |
|From_T2__Prim_4.t2__p7940_terminationG_0.smt2                |    1.761s | 119.0MiB| sat | 0 |  |  |
|From_T2__firewire.t2__terminationQ_1_0.smt2                  |    1.761s | 176.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8531_safety_0.smt2 |    1.765s | 231.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4770_safety_0.smt2 |    1.774s | 130.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6414_safety_0.smt2 |    1.775s | 139.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8959_safety_0.smt2 |    1.780s | 135.0MiB| sat | 0 |  |  |
|From_AProVE_2014__Test4.jar-obl-10__terminationS_38_0.smt2   |    1.800s | 194.0MiB| unsat | 0 |  |  |
|Stroeder_15__AlternKonv.c__p20685_terminationG_0.smt2        |    1.803s | 115.0MiB| sat | 0 |  |  |
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__p12559_terminationG_0.smt2 |    1.804s | 136.0MiB| sat | 0 |  |  |
|From_T2__s1-striped.t2__p13843_safety_0.smt2                 |    1.804s | 98.0MiB| unsat | 0 |  |  |
|aproveSMT4786517774271864296.smt2                            |    1.816s | 118.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p396_safety_0.smt2 |    1.827s | 106.0MiB| unsat | 0 |  |  |
|From_T2__ex36.t2__p31057_safety_0.smt2                       |    1.837s | 115.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30285_safety_0.smt2 |    1.843s | 106.0MiB| unsat | 0 |  |  |
|From_T2__ex36.t2__p29903_safety_0.smt2                       |    1.846s | 112.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32011_safety_0.smt2 |    1.848s | 106.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31987_safety_0.smt2 |    1.859s | 191.0MiB| sat | 0 |  |  |
|From_AProVE_2014__ex08_rec.jar-obl-8__terminationS_4_0.smt2  |    1.861s | 107.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5045_safety_0.smt2 |    1.867s | 167.0MiB| sat | 0 |  |  |
|aproveSMT8328864454385468275.smt2                            |    1.869s | 122.0MiB| sat | 0 |  |  |
|From_T2__slayer-3-filtered.t2__p21597_terminationG_0.smt2    |    1.877s | 128.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__LinkedList.jar-obl-10__p10080_terminationG_0.smt2 |    1.878s | 110.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31933_safety_0.smt2 |    1.878s | 141.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7184_safety_0.smt2 |    1.881s | 131.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9478_terminationG_0.smt2 |    1.882s | 156.0MiB| sat | 0 |  |  |
|From_T2__ex36.t2_fixed__p23679_safety_0.smt2                 |    1.897s | 104.0MiB| sat | 0 |  |  |
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__terminationS_11_0.smt2 |    1.909s | 126.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__cousot_rec.jar-obl-8__p28267_terminationG_0.smt2 |    1.911s | 110.0MiB| unsat | 0 |  |  |
|aproveSMT4843513687534854491.smt2                            |    1.915s | 112.0MiB| sat | 0 |  |  |
|From_AProVE_2014__Velroyen08-upAndDownIneq.jar-obl-8__terminationS_1_0.smt2 |    1.920s | 104.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30915_safety_0.smt2 |    1.926s | 107.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2529_safety_0.smt2 |    1.933s | 107.0MiB| unsat | 0 |  |  |
|From_T2__s1.t2__p19523_safety_0.smt2                         |    1.941s | 159.0MiB| sat | 0 |  |  |
|From_AProVE_2014__TestJulia7.jar-obl-8__p12986_terminationG_0.smt2 |    1.960s | 113.0MiB| unsat | 0 |  |  |
|From_T2__bakery.t2__p17029_terminationG_0.smt2               |    1.988s | 169.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2469_terminationG_0.smt2 |    1.995s | 198.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1543_terminationG_0.smt2 |    2.010s | 197.0MiB| sat | 0 |  |  |
|aproveSMT6500048596873196244.smt2                            |    2.017s | 111.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6603_safety_0.smt2 |    2.026s | 152.0MiB| sat | 0 |  |  |
|From_T2__edn.t2__p20799_safety_0.smt2                        |    2.041s | 118.0MiB| sat | 0 |  |  |
|From_T2__rlft3.t2__p9145_terminationG_0.smt2                 |    2.064s | 138.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p423_safety_0.smt2 |    2.065s | 107.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__DivTernary2.jar-obl-9__p28634_edge_closing_0.smt2 |    2.072s | 131.0MiB| sat | 0 |  |  |
|From_T2__slayer-5-filtered.t2__p22796_safety_0.smt2          |    2.083s | 123.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32174_safety_0.smt2 |    2.087s | 106.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7593_safety_0.smt2 |    2.088s | 184.0MiB| sat | 0 |  |  |
|From_T2__s1-striped.t2_fixed__p11070_safety_0.smt2           |    2.098s | 102.0MiB| unsat | 0 |  |  |
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8744_terminationG_0.smt2 |    2.108s | 113.0MiB| unsat | 0 |  |  |
|From_T2__edn.t2__p20738_safety_0.smt2                        |    2.114s | 112.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1794_safety_0.smt2 |    2.120s | 108.0MiB| unsat | 0 |  |  |
|aproveSMT3334656614075774306.smt2                            |    2.127s | 102.0MiB| sat | 0 |  |  |
|From_T2__opt-tree.c.t2__p6338_terminationG_0.smt2            |    2.144s | 149.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6028_safety_0.smt2 |    2.145s | 151.0MiB| sat | 0 |  |  |
|From_T2__s1-striped.t2_fixed__p11092_safety_0.smt2           |    2.152s | 122.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__terminationS_9_0.smt2 |    2.157s | 132.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31649_safety_0.smt2 |    2.162s | 146.0MiB| sat | 0 |  |  |
|From_T2__pgarch.t2_fixed__terminationS_25_0.smt2             |    2.165s | 227.0MiB| unsat | 0 |  |  |
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24056_edge_closing_0.smt2 |    2.170s | 103.0MiB| sat | 0 |  |  |
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__terminationQ_1_0.smt2 |    2.206s | 120.0MiB| unsat | 0 |  |  |
|aproveSMT6301725928280158574.smt2                            |    2.207s | 108.0MiB| sat | 0 |  |  |
|From_T2__n-6.t2__p4866_edge_closing_0.smt2                   |    2.229s | 129.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6579_safety_0.smt2 |    2.249s | 147.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30268_safety_0.smt2 |    2.261s | 108.0MiB| unsat | 0 |  |  |
|From_T2__s1-striped.t2_fixed__p10685_safety_0.smt2           |    2.263s | 101.0MiB| unsat | 0 |  |  |
|aproveSMT6033388866962201290.smt2                            |    2.270s | 146.0MiB| sat | 0 |  |  |
|From_T2__polyrank4.t2__p7519_terminationG_0.smt2             |    2.299s | 161.0MiB| sat | 0 |  |  |
|From_T2__s1.t2__p17926_terminationG_0.smt2                   |    2.320s | 197.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9536_terminationG_0.smt2 |    2.324s | 203.0MiB| sat | 0 |  |  |
|From_T2__fun1.t2_fixed__p703_terminationG_0.smt2             |    2.333s | 190.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8152_safety_0.smt2 |    2.337s | 226.0MiB| sat | 0 |  |  |
|From_T2__slayer-3.t2__p22243_terminationG_0.smt2             |    2.338s | 195.0MiB| unsat | 0 |  |  |
|From_T2__s1-striped.t2__p14281_safety_0.smt2                 |    2.375s | 170.0MiB| sat | 0 |  |  |
|From_T2__s1.t2__p19670_safety_0.smt2                         |    2.376s | 106.0MiB| unsat | 0 |  |  |
|From_T2__fun1b.t2__terminationS_15_0.smt2                    |    2.384s | 235.0MiB| unsat | 0 |  |  |
|aproveSMT9054136929086877877.smt2                            |    2.386s | 125.0MiB| sat | 0 |  |  |
|aproveSMT9030607454323718032.smt2                            |    2.394s | 137.0MiB| sat | 0 |  |  |
|From_T2__streamserver-succeed.t2__p24825_edge_closing_0.smt2 |    2.397s | 149.0MiB| sat | 0 |  |  |
|From_AProVE_2014__Test4.jar-obl-10__terminationS_29_0.smt2   |    2.400s | 202.0MiB| unsat | 0 |  |  |
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21749_edge_closing_0.smt2 |    2.437s | 124.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p7011_safety_0.smt2 |    2.437s | 106.0MiB| unsat | 0 |  |  |
|Stroeder_15__svcomp_ex2.c__p25886_terminationG_0.smt2        |    2.478s | 124.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__Test13Loops.jar-obl-10__p12728_edge_closing_0.smt2 |    2.481s | 139.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7744_safety_0.smt2 |    2.525s | 270.0MiB| sat | 0 |  |  |
|From_T2__s1.t2__p19894_safety_0.smt2                         |    2.528s | 98.0MiB| unsat | 0 |  |  |
|From_T2__n-5.t2_fixed__p4569_terminationG_0.smt2             |    2.545s | 124.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5945_safety_0.smt2 |    2.569s | 152.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIteratorKeyLoop.jar-obl-12__p3705_safety_0.smt2 |    2.570s | 112.0MiB| unsat | 0 |  |  |
|Stroeder_15__svcomp_ex2.c__p25983_terminationG_0.smt2        |    2.573s | 151.0MiB| unsat | 0 |  |  |
|From_T2__pgarch.t2_fixed__terminationS_16_0.smt2             |    2.584s | 226.0MiB| unsat | 0 |  |  |
|From_T2__java_DivMinus2.c.t2__p2415_terminationG_0.smt2      |    2.592s | 173.0MiB| sat | 0 |  |  |
|aproveSMT8205772230016192248.smt2                            |    2.593s | 113.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31764_safety_0.smt2 |    2.604s | 202.0MiB| sat | 0 |  |  |
|From_T2__Prim_4.t2__p8036_terminationG_0.smt2                |    2.606s | 164.0MiB| sat | 0 |  |  |
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_32_0.smt2 |    2.668s | 157.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6102_safety_0.smt2 |    2.677s | 159.0MiB| sat | 0 |  |  |
|From_AProVE_2014__TriTas.jar-obl-12__p13043_edge_closing_0.smt2 |    2.680s | 114.0MiB| sat | 0 |  |  |
|From_T2__slayer-3.t2__p22301_terminationG_0.smt2             |    2.684s | 205.0MiB| unsat | 0 |  |  |
|From_T2__mc91.t2__p2911_terminationG_0.smt2                  |    2.695s | 114.0MiB| unsat | 0 |  |  |
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__terminationS_2_0.smt2 |    2.695s | 152.0MiB| unsat | 0 |  |  |
|From_T2__slayer-4-filtered.t2__p22618_safety_0.smt2          |    2.721s | 122.0MiB| unsat | 0 |  |  |
|From_T2__ppblock.t2__p7759_edge_closing_0.smt2               |    2.744s | 121.0MiB| sat | 0 |  |  |
|From_T2__mc91.t2__p2764_terminationG_0.smt2                  |    2.747s | 185.0MiB| sat | 0 |  |  |
|From_T2__slayer-4-filtered.t2__p22554_safety_0.smt2          |    2.754s | 156.0MiB| sat | 0 |  |  |
|From_T2__apchild-accepted.t2__terminationQ_9_0.smt2          |    2.765s | 208.0MiB| sat | 0 |  |  |
|From_AProVE_2014__sumGeneric2_rec.jar-obl-8__p12293_terminationG_0.smt2 |    2.770s | 109.0MiB| unsat | 0 |  |  |
|From_T2__polyrank4.t2__p7472_terminationG_0.smt2             |    2.775s | 155.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6161_safety_0.smt2 |    2.781s | 175.0MiB| sat | 0 |  |  |
|From_AProVE_2014__FlattenRTA.jar-obl-10__p29425_safety_0.smt2 |    2.791s | 133.0MiB| sat | 0 |  |  |
|From_T2__apchildlive-succeed.t2__terminationS_33_0.smt2      |    2.812s | 179.0MiB| unsat | 0 |  |  |
|From_T2__queens.t2__p8372_terminationG_0.smt2                |    2.831s | 147.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9355_terminationG_0.smt2 |    2.831s | 187.0MiB| sat | 0 |  |  |
|From_T2__ex16.t2__p22228_terminationG_0.smt2                 |    2.875s | 109.0MiB| unsat | 0 |  |  |
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32585_terminationG_0.smt2 |    2.878s | 134.0MiB| sat | 0 |  |  |
|From_T2__slayer-3-new.t2__p21938_terminationG_0.smt2         |    2.900s | 185.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__SortCount.jar-obl-10__terminationS_4_0.smt2 |    2.907s | 144.0MiB| unsat | 0 |  |  |
|From_T2__p-43-terminate.t2_fixed__p6628_terminationG_0.smt2  |    2.913s | 212.0MiB| sat | 0 |  |  |
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14280_terminationG_0.smt2 |    2.923s | 153.0MiB| sat | 0 |  |  |
|From_T2__fun9.t2__p1258_edge_closing_0.smt2                  |    2.927s | 162.0MiB| sat | 0 |  |  |
|From_T2__compress.t2__p17884_terminationG_0.smt2             |    2.936s | 118.0MiB| unsat | 0 |  |  |
|From_T2__tqli.t2_fixed__terminationQ_2_0.smt2                |    2.952s | 180.0MiB| sat | 0 |  |  |
|From_AProVE_2014__cousot_rec.jar-obl-8__p28367_terminationG_0.smt2 |    2.967s | 121.0MiB| unsat | 0 |  |  |
|From_T2__prime.t2__p8294_terminationG_0.smt2                 |    2.971s | 107.0MiB| unsat | 0 |  |  |
|term-WG086A.smt2                                             |    2.995s | 140.0MiB| sat | 0 |  |  |
|From_AProVE_2014__Domino.jar-obl-27__terminationS_4_0.smt2   |    2.997s | 188.0MiB| unsat | 0 |  |  |
|From_T2__apchild-accepted.t2_fixed__p16142_safety_0.smt2     |    3.000s | 114.0MiB| unsat | 0 |  |  |
|From_T2__s1-striped.t2__p14418_safety_0.smt2                 |    3.034s | 103.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2769_safety_0.smt2 |    3.037s | 113.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8432_safety_0.smt2 |    3.042s | 250.0MiB| sat | 0 |  |  |
|From_T2__slayer-3-new.t2__p21988_terminationG_0.smt2         |    3.049s | 200.0MiB| unsat | 0 |  |  |
|From_T2__s1.t2__p20268_safety_0.smt2                         |    3.068s | 102.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__DivTernary.jar-obl-10__terminationS_14_0.smt2 |    3.072s | 183.0MiB| unsat | 0 |  |  |
|Stroeder_15__svcomp_ex2.c__p25816_terminationG_0.smt2        |    3.083s | 185.0MiB| sat | 0 |  |  |
|From_T2__ex16.t2__p22253_terminationG_0.smt2                 |    3.095s | 107.0MiB| unsat | 0 |  |  |
|From_T2__zlib-adler32.c.t2__p26045_safety_0.smt2             |    3.106s | 103.0MiB| unsat | 0 |  |  |
|Stroeder_15__Ex08.c__p22819_terminationG_0.smt2              |    3.158s | 132.0MiB| sat | 0 |  |  |
|aproveSMT4790304217385820014.smt2                            |    3.171s | 114.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1808_safety_0.smt2 |    3.219s | 153.0MiB| sat | 0 |  |  |
|From_T2__n-5.t2__p4656_terminationG_0.smt2                   |    3.229s | 142.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2650_safety_0.smt2 |    3.259s | 175.0MiB| sat | 0 |  |  |
|From_T2__slayer-4-filtered.t2__p22668_safety_0.smt2          |    3.263s | 203.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29960_safety_0.smt2 |    3.268s | 180.0MiB| sat | 0 |  |  |
|aproveSMT5992389869070970435.smt2                            |    3.288s | 112.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6313_safety_0.smt2 |    3.292s | 113.0MiB| unsat | 0 |  |  |
|From_T2__small35.t2__p24000_terminationG_0.smt2              |    3.293s | 124.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5625_safety_0.smt2 |    3.296s | 188.0MiB| sat | 0 |  |  |
|From_AProVE_2014__Matrix.jar-obl-16__p10847_edge_closing_0.smt2 |    3.307s | 167.0MiB| sat | 0 |  |  |
|From_AProVE_2014__Count.jar-obl-10-2__terminationS_9_0.smt2  |    3.329s | 153.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7104_safety_0.smt2 |    3.383s | 116.0MiB| unsat | 0 |  |  |
|From_T2__apchild-accepted-fail.t2_fixed__terminationS_11_0.smt2 |    3.412s | 236.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14299_edge_closing_0.smt2 |    3.413s | 142.0MiB| sat | 0 |  |  |
|From_AProVE_2014__Main.jar-obl-11__terminationS_13_0.smt2    |    3.415s | 180.0MiB| unsat | 0 |  |  |
|aproveSMT7278800282732675654.smt2                            |    3.430s | 183.0MiB| sat | 0 |  |  |
|From_AProVE_2014__Test1.jar-obl-8__p12793_terminationG_0.smt2 |    3.461s | 126.0MiB| sat | 0 |  |  |
|From_T2__Prim_4.t2__p7990_terminationG_0.smt2                |    3.467s | 140.0MiB| sat | 0 |  |  |
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8941_terminationG_0.smt2 |    3.496s | 175.0MiB| unsat | 0 |  |  |
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__term_unfeasibility_1_0.smt2 |    3.504s | 174.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8584_safety_0.smt2 |    3.510s | 265.0MiB| sat | 0 |  |  |
|From_T2__mc91test.t2__p2968_terminationG_0.smt2              |    3.525s | 164.0MiB| sat | 0 |  |  |
|From_T2__broydn.t2_fixed__term_unfeasibility_3_0.smt2        |    3.528s | 151.0MiB| sat | 0 |  |  |
|From_AProVE_2014__Velroyen08-sunset.jar-obl-8__p14515_edge_closing_0.smt2 |    3.539s | 117.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6656_safety_0.smt2 |    3.541s | 178.0MiB| sat | 0 |  |  |
|From_AProVE_2014__List.jar-obl-12__p10189_terminationG_0.smt2 |    3.551s | 126.0MiB| sat | 0 |  |  |
|From_T2__florian_sas2.t2__p32378_terminationG_0.smt2         |    3.572s | 145.0MiB| sat | 0 |  |  |
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_5_0.smt2   |    3.574s | 173.0MiB| unsat | 0 |  |  |
|From_T2__tqli.t2__terminationQ_2_0.smt2                      |    3.576s | 194.0MiB| sat | 0 |  |  |
|From_AProVE_2014__MirrorBinTreeRec.jar-obl-9__terminationS_8_0.smt2 |    3.589s | 154.0MiB| unsat | 0 |  |  |
|From_T2__slayer-4-filtered.t2__p22693_safety_0.smt2          |    3.592s | 145.0MiB| sat | 0 |  |  |
|From_T2__svdcmp.t2__term_unfeasibility_10_0.smt2             |    3.601s | 157.0MiB| sat | 0 |  |  |
|From_T2__s1-striped.t2__p15078_safety_0.smt2                 |    3.610s | 179.0MiB| sat | 0 |  |  |
|aproveSMT7917963829768768087.smt2                            |    3.631s | 131.0MiB| unsat | 0 |  |  |
|From_T2__edn.t2__p20628_safety_0.smt2                        |    3.649s | 132.0MiB| sat | 0 |  |  |
|From_T2__pgarch.t2_fixed__terminationS_3_0.smt2              |    3.656s | 218.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__Alternate.jar-obl-10__terminationS_8_0.smt2 |    3.671s | 153.0MiB| unsat | 0 |  |  |
|Stroeder_15__collatz.c__p22222_edge_closing_0.smt2           |    3.687s | 114.0MiB| sat | 0 |  |  |
|From_AProVE_2014__Main.jar-obl-11__terminationS_27_0.smt2    |    3.693s | 182.0MiB| unsat | 0 |  |  |
|From_T2__mc91test.t2__p3367_terminationG_0.smt2              |    3.695s | 135.0MiB| sat | 0 |  |  |
|From_T2__polyrank5.t2__p7566_terminationG_0.smt2             |    3.756s | 153.0MiB| sat | 0 |  |  |
|aproveSMT1222406278700673783.smt2                            |    3.756s | 133.0MiB| unsat | 0 |  |  |
|From_T2__fun9.t2__p1407_edge_closing_0.smt2                  |    3.783s | 133.0MiB| sat | 0 |  |  |
|From_T2__apchildlive-succeed.t2__p16429_terminationG_0.smt2  |    3.837s | 369.0MiB| sat | 0 |  |  |
|From_AProVE_2014__Test6.jar-obl-13__terminationS_43_0.smt2   |    3.879s | 219.0MiB| unsat | 0 |  |  |
|aproveSMT8264792885821091201.smt2                            |    3.886s | 134.0MiB| sat | 0 |  |  |
|From_T2__apchild-live.t2__p16660_terminationG_0.smt2         |    3.939s | 290.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2903_safety_0.smt2 |    3.996s | 177.0MiB| sat | 0 |  |  |
|aproveSMT7144269790757830415.smt2                            |    4.014s | 124.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8828_safety_0.smt2 |    4.023s | 257.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32397_safety_0.smt2 |    4.035s | 172.0MiB| sat | 0 |  |  |
|aproveSMT4015411381612320072.smt2                            |    4.069s | 126.0MiB| sat | 0 |  |  |
|From_T2__fun6.t2_fixed__p1064_edge_closing_0.smt2            |    4.076s | 250.0MiB| sat | 0 |  |  |
|From_T2__janne_complex.t2__p2254_terminationG_0.smt2         |    4.116s | 192.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7124_safety_0.smt2 |    4.220s | 175.0MiB| sat | 0 |  |  |
|From_T2__svdcmp.t2_fixed__term_unfeasibility_10_0.smt2       |    4.239s | 163.0MiB| sat | 0 |  |  |
|From_T2__fun1.t2__terminationS_3_0.smt2                      |    4.240s | 257.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9495_safety_0.smt2 |    4.282s | 233.0MiB| sat | 0 |  |  |
|From_AProVE_2014__Flatten.jar-obl-10__p29372_safety_0.smt2   |    4.330s | 125.0MiB| sat | 0 |  |  |
|From_T2__sas2.t2__terminationQ_1_0.smt2                      |    4.343s | 140.0MiB| sat | 0 |  |  |
|From_AProVE_2014__Test6.jar-obl-13__term_unfeasibility_4_0.smt2 |    4.359s | 181.0MiB| sat | 0 |  |  |
|From_T2__polyrank3.t2__p7436_terminationG_0.smt2             |    4.377s | 168.0MiB| sat | 0 |  |  |
|From_T2__fun9.t2__p1462_edge_closing_0.smt2                  |    4.408s | 140.0MiB| sat | 0 |  |  |
|From_T2__s1-striped.t2__p12349_safety_0.smt2                 |    4.417s | 199.0MiB| sat | 0 |  |  |
|From_T2__efegp.t2_fixed__p21941_edge_closing_0.smt2          |    4.418s | 138.0MiB| sat | 0 |  |  |
|From_AProVE_2014__mirrorInterv_rec.jar-obl-8__p10930_terminationG_0.smt2 |    4.428s | 115.0MiB| unsat | 0 |  |  |
|From_T2__consts2nt.t2__p18050_terminationG_0.smt2            |    4.432s | 129.0MiB| unsat | 0 |  |  |
|aproveSMT334180970798087384.smt2                             |    4.471s | 125.0MiB| sat | 0 |  |  |
|aproveSMT3057256999514663885.smt2                            |    4.476s | 174.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p359_safety_0.smt2 |    4.506s | 204.0MiB| sat | 0 |  |  |
|From_AProVE_2014__SortCount.jar-obl-10__p12188_terminationG_0.smt2 |    4.523s | 349.0MiB| sat | 0 |  |  |
|From_AProVE_2014__narrowing_rec.jar-obl-8__p11071_edge_closing_0.smt2 |    4.544s | 167.0MiB| sat | 0 |  |  |
|From_T2__compress.t2_fixed__p17801_edge_closing_0.smt2       |    4.564s | 125.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30742_safety_0.smt2 |    4.580s | 190.0MiB| sat | 0 |  |  |
|From_T2__db3.t2_fixed__terminationS_0_0.smt2                 |    4.625s | 162.0MiB| unsat | 0 |  |  |
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8813_terminationG_0.smt2 |    4.632s | 162.0MiB| unsat | 0 |  |  |
|aproveSMT4293993713008672806.smt2                            |    4.714s | 158.0MiB| sat | 0 |  |  |
|From_AProVE_2014__Test6.jar-obl-13__terminationS_25_0.smt2   |    4.796s | 208.0MiB| unsat | 0 |  |  |
|aproveSMT1747479424109945297.smt2                            |    4.822s | 121.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__Velroyen08-alternDiv.jar-obl-8__p13204_edge_closing_0.smt2 |    4.850s | 114.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__Distances.jar-obl-19__terminationS_4_0.smt2 |    4.855s | 172.0MiB| unsat | 0 |  |  |
|From_T2__polling.bug.t2_fixed__term_unfeasibility_1_0.smt2   |    4.860s | 214.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__cousot_rec.jar-obl-8__p28317_terminationG_0.smt2 |    4.863s | 127.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__FlattenTreeListRec.jar-obl-10__p29573_safety_0.smt2 |    4.869s | 163.0MiB| sat | 0 |  |  |
|From_T2__bakery.t2__p17118_terminationG_0.smt2               |    4.878s | 135.0MiB| unsat | 0 |  |  |
|From_T2__Prim_4.t2__p8056_terminationG_0.smt2                |    4.963s | 200.0MiB| sat | 0 |  |  |
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__term_unfeasibility_2_0.smt2 |    4.996s | 159.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30401_safety_0.smt2 |    4.997s | 190.0MiB| sat | 0 |  |  |
|From_AProVE_2014__FlattenRTA.jar-obl-10__p29448_safety_0.smt2 |    5.055s | 159.0MiB| sat | 0 |  |  |
|From_T2__ppblock.t2__p7742_edge_closing_0.smt2               |    5.055s | 134.0MiB| sat | 0 |  |  |
|aproveSMT2880696731965229413.smt2                            |    5.059s | 205.0MiB| sat | 0 |  |  |
|From_AProVE_2014__Test4.jar-obl-10__terminationS_6_0.smt2    |    5.090s | 217.0MiB| unsat | 0 |  |  |
|Stroeder_15__svcomp_ex2.c__p25822_terminationG_0.smt2        |    5.109s | 248.0MiB| sat | 0 |  |  |
|aproveSMT7048666801337573956.smt2                            |    5.129s | 135.0MiB| sat | 0 |  |  |
|aproveSMT9210831631031619938.smt2                            |    5.154s | 178.0MiB| sat | 0 |  |  |
|From_T2__ud.t2__p25362_terminationG_0.smt2                   |    5.174s | 175.0MiB| sat | 0 |  |  |
|From_T2__edn.t2__p20296_safety_0.smt2                        |    5.174s | 146.0MiB| sat | 0 |  |  |
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14264_terminationG_0.smt2 |    5.208s | 143.0MiB| sat | 0 |  |  |
|From_T2__slayer-3-new.t2__p22040_safety_0.smt2               |    5.225s | 192.0MiB| sat | 0 |  |  |
|From_T2__slayer-3-filtered.t2__p21647_terminationG_0.smt2    |    5.251s | 136.0MiB| unsat | 0 |  |  |
|From_T2__firewire.t2__terminationS_9_0.smt2                  |    5.267s | 206.0MiB| unsat | 0 |  |  |
|aproveSMT1575921927310304758.smt2                            |    5.274s | 132.0MiB| sat | 0 |  |  |
|From_T2__fun4-alt.t2__p884_terminationG_0.smt2               |    5.297s | 114.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__Test6.jar-obl-13__terminationS_34_0.smt2   |    5.329s | 225.0MiB| unsat | 0 |  |  |
|From_T2__db3.t2_fixed__terminationS_3_0.smt2                 |    5.330s | 167.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8880_safety_0.smt2 |    5.398s | 286.0MiB| sat | 0 |  |  |
|Stroeder_15__GCD.c__p23173_terminationG_0.smt2               |    5.399s | 196.0MiB| sat | 0 |  |  |
|aproveSMT4380061691498964684.smt2                            |    5.442s | 157.0MiB| sat | 0 |  |  |
|From_AProVE_2014__DivTernary2.jar-obl-9__p28644_edge_closing_0.smt2 |    5.479s | 166.0MiB| sat | 0 |  |  |
|aproveSMT5521985939949569030.smt2                            |    5.559s | 127.0MiB| sat | 0 |  |  |
|From_T2__florian_sumit.t2__p32442_edge_closing_0.smt2        |    5.570s | 164.0MiB| sat | 0 |  |  |
|aproveSMT6744625072979146355.smt2                            |    5.602s | 164.0MiB| sat | 0 |  |  |
|Stroeder_15__WhileIncr.c__p26382_terminationG_0.smt2         |    5.604s | 122.0MiB| unsat | 0 |  |  |
|From_T2__s1.t2__p20015_safety_0.smt2                         |    5.678s | 205.0MiB| sat | 0 |  |  |
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9218_terminationG_0.smt2 |    5.706s | 155.0MiB| unsat | 0 |  |  |
|From_T2__slayer-3-new.t2_fixed__terminationS_29_0.smt2       |    5.770s | 220.0MiB| unsat | 0 |  |  |
|From_T2__n-1c.t2__p3754_edge_closing_0.smt2                  |    5.820s | 172.0MiB| sat | 0 |  |  |
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_2_0.smt2 |    5.907s | 169.0MiB| unsat | 0 |  |  |
|From_T2__mc91test.t2__p3229_terminationG_0.smt2              |    5.913s | 156.0MiB| sat | 0 |  |  |
|From_T2__s1-striped.t2_fixed__p10632_safety_0.smt2           |    5.928s | 203.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__terminationQ_0_0.smt2 |    6.008s | 139.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8999_safety_0.smt2 |    6.020s | 231.0MiB| sat | 0 |  |  |
|From_T2__firewire.t2__p32277_terminationG_0.smt2             |    6.158s | 141.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8855_safety_0.smt2 |    6.190s | 277.0MiB| sat | 0 |  |  |
|From_AProVE_2014__SortCount.jar-obl-10__p12086_terminationG_0.smt2 |    6.226s | 219.0MiB| sat | 0 |  |  |
|From_AProVE_2014__NO_11.jar-obl-8__p11345_terminationG_0.smt2 |    6.282s | 120.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2442_safety_0.smt2 |    6.289s | 204.0MiB| sat | 0 |  |  |
|From_T2__slayer-3.t2_fixed__terminationS_32_0.smt2           |    6.291s | 233.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__Test4.jar-obl-10__terminationS_10_0.smt2   |    6.322s | 224.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4979_safety_0.smt2 |    6.362s | 215.0MiB| sat | 0 |  |  |
|Stroeder_15__svcomp_ex2.c__p25837_terminationG_0.smt2        |    6.376s | 254.0MiB| sat | 0 |  |  |
|aproveSMT82980353335522103.smt2                              |    6.439s | 145.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9553_safety_0.smt2 |    6.531s | 275.0MiB| sat | 0 |  |  |
|From_T2__ex17.t2__p22290_terminationG_0.smt2                 |    6.561s | 120.0MiB| unsat | 0 |  |  |
|aproveSMT2598777028614012130.smt2                            |    6.767s | 158.0MiB| sat | 0 |  |  |
|From_T2__db2.t2__terminationS_33_0.smt2                      |    6.769s | 346.0MiB| unsat | 0 |  |  |
|From_T2__fun1b.t2__p596_terminationG_0.smt2                  |    6.775s | 534.0MiB| sat | 0 |  |  |
|From_T2__bakery.t2__p17168_terminationG_0.smt2               |    6.786s | 168.0MiB| unsat | 0 |  |  |
|aproveSMT7425096829426664326.smt2                            |    6.792s | 137.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7312_safety_0.smt2 |    6.794s | 126.0MiB| unsat | 0 |  |  |
|From_T2__n-7.t2_fixed__p4954_terminationG_0.smt2             |    6.823s | 121.0MiB| unsat | 0 |  |  |
|From_T2__agafp.t2__p15616_terminationG_0.smt2                |    6.849s | 184.0MiB| unsat | 0 |  |  |
|From_T2__ppblocktermbug.t2__p7777_terminationG_0.smt2        |    6.881s | 137.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__Test4.jar-obl-10__terminationS_1_0.smt2    |    6.881s | 231.0MiB| unsat | 0 |  |  |
|From_T2__ppblockterm.t2__p7856_terminationG_0.smt2           |    6.891s | 138.0MiB| unsat | 0 |  |  |
|From_T2__weakness.t2__p25671_terminationG_0.smt2             |    6.941s | 175.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5002_safety_0.smt2 |    6.951s | 213.0MiB| sat | 0 |  |  |
|From_AProVE_2014__Matrix.jar-obl-16__p10783_safety_0.smt2    |    6.973s | 165.0MiB| sat | 0 |  |  |
|From_AProVE_2014__SharingPair.jar-obl-8__p12030_edge_closing_0.smt2 |    7.059s | 164.0MiB| sat | 0 |  |  |
|From_AProVE_2014__MainGet.jar-obl-10__p10683_edge_closing_0.smt2 |    7.079s | 159.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32231_safety_0.smt2 |    7.096s | 248.0MiB| sat | 0 |  |  |
|From_T2__n-5.t2_fixed__p4590_terminationG_0.smt2             |    7.132s | 197.0MiB| sat | 0 |  |  |
|From_AProVE_2014__RandomHard.jar-obl-10__p11832_safety_0.smt2 |    7.177s | 191.0MiB| sat | 0 |  |  |
|term-cTfKvw.smt2                                             |    7.312s | 150.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30328_safety_0.smt2 |    7.419s | 226.0MiB| sat | 0 |  |  |
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9264_edge_closing_0.smt2 |    7.420s | 194.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6290_safety_0.smt2 |    7.421s | 247.0MiB| sat | 0 |  |  |
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_64_0.smt2 |    7.434s | 182.0MiB| unsat | 0 |  |  |
|From_T2__n-5.t2__p4677_terminationG_0.smt2                   |    7.480s | 231.0MiB| sat | 0 |  |  |
|From_T2__s1.t2__p21153_safety_0.smt2                         |    7.596s | 226.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7477_safety_0.smt2 |    7.782s | 135.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__DivTernary.jar-obl-10__p28667_terminationG_0.smt2 |    7.848s | 357.0MiB| sat | 0 |  |  |
|From_T2__streamserver-succeed.t2_fixed__terminationS_25_0.smt2 |    7.877s | 138.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__Kernel93.jar-obl-9__p9885_terminationG_0.smt2 |    7.987s | 167.0MiB| unsat | 0 |  |  |
|From_T2__florian_sumit.t2__p32424_terminationG_0.smt2        |    8.021s | 205.0MiB| sat | 0 |  |  |
|From_T2__fun9.t2__p1248_edge_closing_0.smt2                  |    8.061s | 177.0MiB| sat | 0 |  |  |
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23481_edge_closing_0.smt2 |    8.262s | 174.0MiB| sat | 0 |  |  |
|From_T2__slayer-4-filtered.t2__p22506_safety_0.smt2          |    8.319s | 248.0MiB| sat | 0 |  |  |
|From_T2__fun1b.t2__p666_terminationG_0.smt2                  |    8.341s | 529.0MiB| sat | 0 |  |  |
|From_T2__nakata.t2__terminationQ_6_0.smt2                    |    8.389s | 210.0MiB| sat | 0 |  |  |
|From_T2__mc91.t2__p2711_terminationG_0.smt2                  |    8.446s | 151.0MiB| sat | 0 |  |  |
|From_T2__mc91test.t2__p3099_terminationG_0.smt2              |    8.454s | 150.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31615_safety_0.smt2 |    8.509s | 203.0MiB| sat | 0 |  |  |
|From_AProVE_2014__MysteriousProgram.jar-obl-12__terminationS_12_0.smt2 |    8.536s | 190.0MiB| unsat | 0 |  |  |
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_36_0.smt2 |    8.595s | 192.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__Test6.jar-obl-13__terminationS_16_0.smt2   |    8.809s | 235.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7143_safety_0.smt2 |    8.837s | 131.0MiB| unsat | 0 |  |  |
|From_T2__broydn.c.i.broydn.pl.t2.fixed.t2_fixed__term_unfeasibility_10_0.smt2 |    8.910s | 126.0MiB| sat | 0 |  |  |
|From_T2__n-7.t2_fixed__p4903_terminationG_0.smt2             |    9.111s | 148.0MiB| unsat | 0 |  |  |
|From_T2__pentagon.t2__p7186_edge_closing_0.smt2              |    9.191s | 134.0MiB| unsat | 0 |  |  |
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_0_0.smt2 |    9.238s | 173.0MiB| unsat | 0 |  |  |
|From_T2__firewire.t2__terminationS_18_0.smt2                 |    9.252s | 243.0MiB| unsat | 0 |  |  |
|From_T2__apchild-accepted-fail.t2_fixed__terminationS_5_0.smt2 |    9.255s | 281.0MiB| unsat | 0 |  |  |
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_28_0.smt2 |    9.300s | 169.0MiB| unsat | 0 |  |  |
|aproveSMT4408268044216253595.smt2                            |    9.411s | 121.0MiB| sat | 0 |  |  |
|From_AProVE_2014__Domino.jar-obl-27__terminationS_10_0.smt2  |    9.509s | 194.0MiB| unsat | 0 |  |  |
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_11_0.smt2 |    9.788s | 212.0MiB| unsat | 0 |  |  |
|From_T2__slayer-3.t2_fixed__terminationS_6_0.smt2            |    9.825s | 217.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__complxStruc_rec.jar-obl-8__terminationS_0_0.smt2 |    9.873s | 150.0MiB| unsat | 0 |  |  |
|From_T2__slayer-n1.t2_fixed__p23057_safety_0.smt2            |    9.969s | 177.0MiB| sat | 0 |  |  |
|From_T2__streamserver-succeed.t2__p24703_terminationG_0.smt2 |   10.068s | 161.0MiB| unsat | 0 |  |  |
|From_T2__hqr.t2__terminationS_28_0.smt2                      |   10.208s | 177.0MiB| unsat | 0 |  |  |
|From_T2__n_firewire_instrumented-PP.t2__terminationQ_3_0.smt2 |   10.270s | 177.0MiB| sat | 0 |  |  |
|From_T2__streamserver-succeed.t2__p24810_terminationG_0.smt2 |   10.283s | 321.0MiB| unsat | 0 |  |  |
|Stroeder_15__svcomp_ex2.c__p25853_terminationG_0.smt2        |   10.514s | 313.0MiB| sat | 0 |  |  |
|From_T2__brp_withassume.t2__terminationS_17_0.smt2           |   10.543s | 234.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7163_safety_0.smt2 |   10.574s | 288.0MiB| sat | 0 |  |  |
|From_AProVE_2014__Velroyen08-alternDivWidening.jar-obl-8__p13246_terminationG_0.smt2 |   10.686s | 146.0MiB| unsat | 0 |  |  |
|Stroeder_15__MirrorInterv.c__p24423_edge_closing_0.smt2      |   10.709s | 167.0MiB| sat | 0 |  |  |
|From_T2__apchild-accepted.t2__p16319_terminationG_0.smt2     |   10.794s | 353.0MiB| sat | 0 |  |  |
|From_AProVE_2014__SortCount.jar-obl-10__p12162_terminationG_0.smt2 |   11.038s | 260.0MiB| sat | 0 |  |  |
|From_T2__hqr.t2_fixed__term_unfeasibility_1_0.smt2           |   11.268s | 197.0MiB| sat | 0 |  |  |
|From_T2__s1-striped.t2_fixed__p9297_terminationG_0.smt2      |   11.275s | 222.0MiB| sat | 0 |  |  |
|From_T2__hqr.t2__terminationS_18_0.smt2                      |   11.351s | 195.0MiB| unsat | 0 |  |  |
|From_T2__slayer-3-new.t2_fixed__p21801_terminationG_0.smt2   |   11.352s | 361.0MiB| sat | 0 |  |  |
|From_T2__ppblock.t2__p7707_terminationG_0.smt2               |   11.370s | 209.0MiB| unsat | 0 |  |  |
|From_T2__brp_withassume.t2__terminationS_26_0.smt2           |   11.386s | 212.0MiB| unsat | 0 |  |  |
|From_T2__streamserver-succeed.t2__p24755_terminationG_0.smt2 |   11.408s | 210.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__MainDelete.jar-obl-10__p10430_safety_0.smt2 |   11.476s | 146.0MiB| unsat | 0 |  |  |
|Stroeder_15__Ex08.c__p22824_edge_closing_0.smt2              |   11.517s | 166.0MiB| sat | 0 |  |  |
|From_AProVE_2014__Queen.jar-obl-10__p11807_terminationG_0.smt2 |   11.829s | 237.0MiB| unsat | 0 |  |  |
|From_T2__brp_withassume.t2__terminationS_5_0.smt2            |   11.841s | 233.0MiB| unsat | 0 |  |  |
|aproveSMT5598217329789101375.smt2                            |   11.878s | 124.0MiB| sat | 0 |  |  |
|From_T2__slayer-3.t2_fixed__terminationS_22_0.smt2           |   11.903s | 257.0MiB| unsat | 0 |  |  |
|aproveSMT3060102017506592639.smt2                            |   11.904s | 199.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8903_safety_0.smt2 |   12.119s | 334.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31792_safety_0.smt2 |   12.196s | 266.0MiB| sat | 0 |  |  |
|term-AwuLMZ.smt2                                             |   12.204s | 161.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4889_safety_0.smt2 |   12.359s | 141.0MiB| unsat | 0 |  |  |
|From_T2__apchild-accepted.t2_fixed__p16109_terminationG_0.smt2 |   12.379s | 390.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5177_safety_0.smt2 |   12.479s | 151.0MiB| unsat | 0 |  |  |
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_21_0.smt2 |   12.527s | 198.0MiB| unsat | 0 |  |  |
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_39_0.smt2 |   12.564s | 188.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p334_safety_0.smt2 |   12.737s | 262.0MiB| sat | 0 |  |  |
|From_T2__slayer-3-new.t2_fixed__terminationS_1_0.smt2        |   13.093s | 212.0MiB| unsat | 0 |  |  |
|From_T2__s1.t2_fixed__p15180_terminationG_0.smt2             |   13.118s | 740.0MiB| sat | 0 |  |  |
|From_T2__small35.t2__p24050_terminationG_0.smt2              |   13.459s | 157.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__Domino.jar-obl-27__p28689_terminationG_0.smt2 |   13.496s | 794.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4783_safety_0.smt2 |   13.855s | 156.0MiB| unsat | 0 |  |  |
|From_T2__florian_sas2.t2__terminationS_2_0.smt2              |   14.176s | 176.0MiB| unsat | 0 |  |  |
|From_T2__hqr.t2__terminationS_68_0.smt2                      |   14.199s | 178.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__Velroyen08-middle.jar-obl-8__p14237_terminationG_0.smt2 |   14.253s | 148.0MiB| unsat | 0 |  |  |
|From_T2__p-5.t2__p6860_edge_closing_0.smt2                   |   14.500s | 344.0MiB| sat | 0 |  |  |
|From_T2__fun1b.t2_fixed__p494_terminationG_0.smt2            |   14.619s | 249.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32475_safety_0.smt2 |   14.767s | 339.0MiB| sat | 0 |  |  |
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_57_0.smt2 |   14.867s | 193.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__MysteriousProgram.jar-obl-12__terminationS_6_0.smt2 |   14.879s | 231.0MiB| unsat | 0 |  |  |
|aproveSMT5555859573725551605.smt2                            |   14.945s | 142.0MiB| sat | 0 |  |  |
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_37_0.smt2 |   15.049s | 215.0MiB| unsat | 0 |  |  |
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_24_0.smt2  |   15.338s | 214.0MiB| unsat | 0 |  |  |
|From_T2__fun6.t2__p1084_terminationG_0.smt2                  |   15.430s | 564.0MiB| sat | 0 |  |  |
|From_T2__hqr.t2_fixed__terminationS_27_0.smt2                |   15.524s | 198.0MiB| unsat | 0 |  |  |
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27226_terminationG_0.smt2 |   15.661s | 243.0MiB| sat | 0 |  |  |
|From_AProVE_2014__BMOG_CAV_12_MarkingGraphVisitor.jar-obl-11__p27764_terminationG_0.smt2 |   15.672s | 288.0MiB| unsat | 0 |  |  |
|aproveSMT1530191844080893274.smt2                            |   15.752s | 230.0MiB| sat | 0 |  |  |
|From_T2__slayer-n1.t2_fixed__p22972_safety_0.smt2            |   15.821s | 242.0MiB| sat | 0 |  |  |
|From_T2__fun9.t2__p1196_terminationG_0.smt2                  |   15.999s | 342.0MiB| sat | 0 |  |  |
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_18_0.smt2 |   16.021s | 198.0MiB| unsat | 0 |  |  |
|From_T2__fun1.t2__p831_terminationG_0.smt2                   |   16.037s | 466.0MiB| sat | 0 |  |  |
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_44_0.smt2 |   16.041s | 179.0MiB| unsat | 0 |  |  |
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_28_0.smt2 |   16.049s | 216.0MiB| unsat | 0 |  |  |
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_18_0.smt2 |   16.149s | 224.0MiB| unsat | 0 |  |  |
|From_T2__n-7.t2__p4999_terminationG_0.smt2                   |   16.525s | 185.0MiB| unsat | 0 |  |  |
|From_T2__hqr.t2__terminationS_58_0.smt2                      |   16.747s | 185.0MiB| unsat | 0 |  |  |
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_20_0.smt2 |   16.784s | 217.0MiB| unsat | 0 |  |  |
|From_T2__hqr.t2_fixed__terminationS_38_0.smt2                |   16.828s | 181.0MiB| unsat | 0 |  |  |
|From_T2__hqr.t2_fixed__terminationS_48_0.smt2                |   16.951s | 177.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13936_edge_closing_0.smt2 |   17.018s | 278.0MiB| sat | 0 |  |  |
|From_AProVE_2014__MainCopy.jar-obl-10__p10364_edge_closing_0.smt2 |   17.404s | 294.0MiB| sat | 0 |  |  |
|From_T2__janne_complex.t2__p2230_terminationG_0.smt2         |   17.437s | 298.0MiB| sat | 0 |  |  |
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_48_0.smt2 |   17.632s | 192.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__Distances.jar-obl-19__p28453_terminationG_0.smt2 |   18.058s | 293.0MiB| sat | 0 |  |  |
|From_T2__apchild-accepted-fail.t2__p16010_terminationG_0.smt2 |   18.275s | 374.0MiB| sat | 0 |  |  |
|From_T2__streamserver-succeed.t2__p24667_terminationG_0.smt2 |   18.293s | 491.0MiB| sat | 0 |  |  |
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_47_0.smt2 |   18.353s | 193.0MiB| unsat | 0 |  |  |
|From_T2__ndes.t2__p5373_terminationG_0.smt2                  |   18.449s | 292.0MiB| sat | 0 |  |  |
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_19_0.smt2 |   18.668s | 196.0MiB| unsat | 0 |  |  |
|From_T2__fun5.t2__p1026_terminationG_0.smt2                  |   18.684s | 319.0MiB| unsat | 0 |  |  |
|Stroeder_15__svcomp_ex2.c__p25831_terminationG_0.smt2        |   18.688s | 309.0MiB| sat | 0 |  |  |
|From_T2__n_firewire_instrumented-PP.t2__terminationS_6_0.smt2 |   18.809s | 179.0MiB| unsat | 0 |  |  |
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_27_0.smt2 |   18.913s | 223.0MiB| unsat | 0 |  |  |
|From_T2__zlib-adler32.c.t2__p26305_terminationG_0.smt2       |   19.868s | 366.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7445_terminationG_0.smt2 |   19.968s | 258.0MiB| sat | 0 |  |  |
|From_AProVE_2014__RandomHard.jar-obl-10__p11849_terminationG_0.smt2 |   20.001s | 242.0MiB| unsat | 0 |  |  |
|From_T2__fun1.t2__terminationQ_0_0.smt2                      |   20.144s | 414.0MiB| unsat | 0 |  |  |
|From_T2__sas2.t2__p21305_terminationG_0.smt2                 |   20.435s | 224.0MiB| sat | 0 |  |  |
|aproveSMT1705398915961754594.smt2                            |   20.481s | 276.0MiB| sat | 0 |  |  |
|From_AProVE_2014__SortCount.jar-obl-10__p12138_terminationG_0.smt2 |   20.544s | 621.0MiB| sat | 0 |  |  |
|aproveSMT1067631316961394932.smt2                            |   21.022s | 258.0MiB| sat | 0 |  |  |
|From_T2__foo.t2__terminationS_12_0.smt2                      |   21.222s | 623.0MiB| unsat | 0 |  |  |
|From_T2__zlib-crc32.c.t2__p26616_edge_closing_0.smt2         |   21.649s | 323.0MiB| sat | 0 |  |  |
|From_T2__zeroconf.t2__p25773_terminationG_0.smt2             |   21.665s | 230.0MiB| unsat | 0 |  |  |
|From_T2__small15.t2__p23766_terminationG_0.smt2              |   21.969s | 265.0MiB| unsat | 0 |  |  |
|From_T2__fun9.t2__p1292_edge_closing_0.smt2                  |   22.075s | 321.0MiB| sat | 0 |  |  |
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_54_0.smt2 |   22.533s | 204.0MiB| unsat | 0 |  |  |
|From_T2__slayer-3-new.t2_fixed__terminationS_39_0.smt2       |   22.541s | 235.0MiB| unsat | 0 |  |  |
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_53_0.smt2 |   22.901s | 240.0MiB| unsat | 0 |  |  |
|Stroeder_15__NO_12.c__p24712_terminationG_0.smt2             |   23.476s | 272.0MiB| unsat | 0 |  |  |
|aproveSMT2121292005079447352.smt2                            |   23.823s | 244.0MiB| sat | 0 |  |  |
|From_T2__hqr.t2__terminationS_38_0.smt2                      |   24.328s | 180.0MiB| unsat | 0 |  |  |
|aproveSMT8573084889555001775.smt2                            |   24.418s | 438.0MiB| unsat | 0 |  |  |
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_43_0.smt2 |   24.867s | 183.0MiB| unsat | 0 |  |  |
|From_T2__fun9.t2__p1366_edge_closing_0.smt2                  |   25.251s | 359.0MiB| sat | 0 |  |  |
|From_AProVE_2014__LessLeaves.jar-obl-10__p10012_edge_closing_0.smt2 |   25.588s | 248.0MiB| sat | 0 |  |  |
|From_T2__fun1.t2_fixed__p728_terminationG_0.smt2             |   25.845s | 616.0MiB| sat | 0 |  |  |
|From_AProVE_2014__CountMetaList.jar-obl-9__p28209_edge_closing_0.smt2 |   26.287s | 265.0MiB| sat | 0 |  |  |
|From_T2__hqr.t2_fixed__terminationS_57_0.smt2                |   26.351s | 239.0MiB| unsat | 0 |  |  |
|From_T2__fun9.t2__p1314_edge_closing_0.smt2                  |   26.460s | 401.0MiB| sat | 0 |  |  |
|From_T2__janne_complex.t2__p2099_terminationG_0.smt2         |   26.630s | 590.0MiB| sat | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_12_0.smt2 |   26.733s | 555.0MiB| unsat | 0 |  |  |
|aproveSMT3033966919233248917.smt2                            |   27.054s | 206.0MiB| unsat | 0 |  |  |
|From_T2__broydn.t2__term_unfeasibility_11_0.smt2             |   27.955s | 219.0MiB| unsat | 0 |  |  |
|From_T2__n-6.t2__p4854_terminationG_0.smt2                   |   28.113s | 279.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__Round3.jar-obl-8__p11893_terminationG_0.smt2 |   28.258s | 219.0MiB| unsat | 0 |  |  |
|From_AProVE_2014__SortCount.jar-obl-10__p12246_terminationG_0.smt2 |   29.512s | 402.0MiB| unsat | 0 |  |  |
|From_T2__fun1b.t2_fixed__p519_terminationG_0.smt2            |   30.011s | 575.0MiB| sat | 0 |  |  |
|From_T2__ex1.t2__p22367_terminationG_0.smt2                  |   30.031s | 182.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__sumGeneric_rec.jar-obl-8__p12326_terminationG_0.smt2 |   30.032s | 207.0MiB| timeout | 0 |  |  |
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32621_safety_0.smt2 |   30.032s | 184.0MiB| timeout | 0 |  |  |
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27382_terminationG_0.smt2 |   30.033s | 212.0MiB| timeout | 0 |  |  |
|Stroeder_15__Sunset.c__p25623_terminationG_0.smt2            |   30.036s | 199.0MiB| timeout | 0 |  |  |
|From_T2__rlft3.t2__p9127_terminationG_0.smt2                 |   30.037s | 158.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__NO_12.jar-obl-8__p11383_terminationG_0.smt2 |   30.037s | 197.0MiB| timeout | 0 |  |  |
|From_T2__byron-4.t2__p17644_terminationG_0.smt2              |   30.038s | 190.0MiB| timeout | 0 |  |  |
|From_T2__consts5nt.t2_fixed__p18393_terminationG_0.smt2      |   30.038s | 188.0MiB| timeout | 0 |  |  |
|From_T2__refine_disj_problem.t2__p8550_terminationG_0.smt2   |   30.039s | 220.0MiB| timeout | 0 |  |  |
|Stroeder_15__NO_13.c__p24749_terminationG_0.smt2             |   30.039s | 231.0MiB| timeout | 0 |  |  |
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_46_0.smt2 |   30.039s | 224.0MiB| timeout | 0 |  |  |
|From_T2__s1-striped.t2__p13711_safety_0.smt2                 |   30.039s | 175.0MiB| timeout | 0 |  |  |
|aproveSMT5056627952338669338.smt2                            |   30.040s | 207.0MiB| timeout | 0 |  |  |
|From_T2__w2_nt.t2__p25384_safety_0.smt2                      |   30.040s | 260.0MiB| timeout | 0 |  |  |
|Stroeder_15__NonTermination4_false-termination.c__p24955_terminationG_0.smt2 |   30.041s | 211.0MiB| timeout | 0 |  |  |
|From_T2__rlft3.t2__p9077_terminationG_0.smt2                 |   30.042s | 153.0MiB| timeout | 0 |  |  |
|aproveSMT8384181922198476260.smt2                            |   30.042s | 139.0MiB| timeout | 0 |  |  |
|ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2 |   30.042s | 116.0MiB| timeout | 0 |  |  |
|From_T2__s1-striped.t2__p13336_safety_0.smt2                 |   30.044s | 176.0MiB| timeout | 0 |  |  |
|From_T2__rlft3.t2__p9177_terminationG_0.smt2                 |   30.045s | 152.0MiB| timeout | 0 |  |  |
|From_T2__zlib-adler32.c.t2__p26143_safety_0.smt2             |   30.045s | 162.0MiB| timeout | 0 |  |  |
|From_T2__s1.t2_fixed__p16042_safety_0.smt2                   |   30.045s | 170.0MiB| timeout | 0 |  |  |
|From_T2__consts1.t2__p17980_terminationG_0.smt2              |   30.045s | 225.0MiB| timeout | 0 |  |  |
|Ton_Chanh_15__Mysore_false-termination.c__p27269_terminationG_0.smt2 |   30.046s | 189.0MiB| timeout | 0 |  |  |
|aproveSMT1802082844053698751.smt2                            |   30.046s | 209.0MiB| timeout | 0 |  |  |
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27381_terminationG_0.smt2 |   30.047s | 184.0MiB| timeout | 0 |  |  |
|From_T2__n-6a.t2_fixed__p4722_safety_0.smt2                  |   30.047s | 231.0MiB| timeout | 0 |  |  |
|From_T2__s1.t2_fixed__p16093_safety_0.smt2                   |   30.047s | 176.0MiB| timeout | 0 |  |  |
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8915_terminationG_0.smt2 |   30.047s | 188.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1666_safety_0.smt2 |   30.047s | 298.0MiB| timeout | 0 |  |  |
|Stroeder_15__NonTermination2_false-termination.c__p24940_edge_closing_0.smt2 |   30.048s | 202.0MiB| timeout | 0 |  |  |
|aproveSMT3101880129747917873.smt2                            |   30.048s | 186.0MiB| timeout | 0 |  |  |
|From_T2__s1.t2_fixed__p17181_safety_0.smt2                   |   30.048s | 234.0MiB| timeout | 0 |  |  |
|term-iQK4Ty.smt2                                             |   30.048s | 322.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__Velroyen08-cousot.jar-obl-8__p13488_terminationG_0.smt2 |   30.048s | 208.0MiB| timeout | 0 |  |  |
|From_T2__hand7.t2__p1503_terminationG_0.smt2                 |   30.048s | 180.0MiB| timeout | 0 |  |  |
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8853_terminationG_0.smt2 |   30.048s | 162.0MiB| timeout | 0 |  |  |
|aproveSMT6116422603960968616.smt2                            |   30.048s | 152.0MiB| timeout | 0 |  |  |
|From_T2__refine_disj_problem.t2_fixed__p8508_terminationG_0.smt2 |   30.048s | 176.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__ChooseLife.jar-obl-8__p27825_terminationG_0.smt2 |   30.049s | 195.0MiB| timeout | 0 |  |  |
|From_T2__non_term.t2__p6251_terminationG_0.smt2              |   30.049s | 171.0MiB| timeout | 0 |  |  |
|From_T2__s1.t2__p20088_safety_0.smt2                         |   30.049s | 193.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__ex04_rec.jar-obl-8__p29168_terminationG_0.smt2 |   30.049s | 209.0MiB| timeout | 0 |  |  |
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32601_terminationG_0.smt2 |   30.049s | 163.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__LoopingNonterm.jar-obl-8__p10312_terminationG_0.smt2 |   30.049s | 236.0MiB| timeout | 0 |  |  |
|Ton_Chanh_15__Bangalore_false-termination.c__p26582_terminationG_0.smt2 |   30.049s | 212.0MiB| timeout | 0 |  |  |
|aproveSMT8056030040600901039.smt2                            |   30.050s | 172.0MiB| timeout | 0 |  |  |
|aproveSMT1329540615731828670.smt2                            |   30.050s | 165.0MiB| timeout | 0 |  |  |
|aproveSMT6771738228131904044.smt2                            |   30.050s | 203.0MiB| timeout | 0 |  |  |
|From_T2__n-21.t2_fixed__p3838_terminationG_0.smt2            |   30.050s | 181.0MiB| timeout | 0 |  |  |
|From_T2__dead.neg-st88b-succeed.t2__p18802_terminationG_0.smt2 |   30.050s | 208.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__Matrix.jar-obl-16__p10797_safety_0.smt2    |   30.050s | 179.0MiB| timeout | 0 |  |  |
|From_T2__s1.t2_fixed__p16834_safety_0.smt2                   |   30.050s | 178.0MiB| timeout | 0 |  |  |
|From_T2__n-46.t2__p4352_terminationG_0.smt2                  |   30.050s | 203.0MiB| timeout | 0 |  |  |
|From_T2__n-16a.t2__p3627_terminationG_0.smt2                 |   30.050s | 210.0MiB| timeout | 0 |  |  |
|From_T2__s1-striped.t2__p14371_safety_0.smt2                 |   30.051s | 175.0MiB| timeout | 0 |  |  |
|From_T2__s1-striped.t2__p14919_safety_0.smt2                 |   30.051s | 240.0MiB| timeout | 0 |  |  |
|aproveSMT1437438160177275586.smt2                            |   30.051s | 233.0MiB| timeout | 0 |  |  |
|From_T2__small05.t2__p23592_terminationG_0.smt2              |   30.051s | 213.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7205_safety_0.smt2 |   30.051s | 316.0MiB| timeout | 0 |  |  |
|From_T2__s1.t2_fixed__p17167_safety_0.smt2                   |   30.051s | 198.0MiB| timeout | 0 |  |  |
|From_T2__mc91test.t2__p3189_terminationG_0.smt2              |   30.051s | 385.0MiB| timeout | 0 |  |  |
|From_T2__small01.t2__p23469_terminationG_0.smt2              |   30.051s | 215.0MiB| timeout | 0 |  |  |
|From_T2__s1-striped.t2__p14996_safety_0.smt2                 |   30.051s | 178.0MiB| timeout | 0 |  |  |
|From_T2__fun9.t2__p1430_edge_closing_0.smt2                  |   30.051s | 264.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__Velroyen08-complInterv3.jar-obl-8__p13363_terminationG_0.smt2 |   30.051s | 180.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__Velroyen08-mirrorIntervSim.jar-obl-8__p14328_terminationG_0.smt2 |   30.051s | 204.0MiB| timeout | 0 |  |  |
|From_T2__cfg.t2__p17716_terminationG_0.smt2                  |   30.051s | 255.0MiB| timeout | 0 |  |  |
|From_T2__streamserver-succeed.t2_fixed__p24587_edge_closing_0.smt2 |   30.052s | 241.0MiB| timeout | 0 |  |  |
|From_T2__streamserver-succeed.t2__p24737_terminationG_0.smt2 |   30.052s | 285.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__Velroyen08-ex08.jar-obl-8__p13746_terminationG_0.smt2 |   30.052s | 204.0MiB| timeout | 0 |  |  |
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8786_terminationG_0.smt2 |   30.052s | 198.0MiB| timeout | 0 |  |  |
|Stroeder_15__Cousot.c__p22437_terminationG_0.smt2            |   30.052s | 218.0MiB| timeout | 0 |  |  |
|aproveSMT3320813910319868151.smt2                            |   30.052s | 233.0MiB| timeout | 0 |  |  |
|From_T2__n-46.t2__p4403_terminationG_0.smt2                  |   30.052s | 194.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7295_safety_0.smt2 |   30.052s | 191.0MiB| timeout | 0 |  |  |
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24251_edge_closing_0.smt2 |   30.052s | 184.0MiB| timeout | 0 |  |  |
|From_T2__s1-striped.t2__p12568_safety_0.smt2                 |   30.052s | 186.0MiB| timeout | 0 |  |  |
|From_T2__s1-striped.t2_fixed__p9728_safety_0.smt2            |   30.052s | 293.0MiB| timeout | 0 |  |  |
|From_T2__s1-striped.t2_fixed__p10216_safety_0.smt2           |   30.053s | 170.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__cousot_rec.jar-obl-8__p28249_terminationG_0.smt2 |   30.053s | 298.0MiB| timeout | 0 |  |  |
|From_T2__fun9.t2__p1472_edge_closing_0.smt2                  |   30.053s | 238.0MiB| timeout | 0 |  |  |
|From_T2__agafp.t2_fixed__p15572_edge_closing_0.smt2          |   30.053s | 175.0MiB| timeout | 0 |  |  |
|From_T2__edn.t2__p20879_safety_0.smt2                        |   30.053s | 224.0MiB| timeout | 0 |  |  |
|From_T2__n-21.t2__p3970_terminationG_0.smt2                  |   30.053s | 232.0MiB| timeout | 0 |  |  |
|Stroeder_15__Even.c__p22673_terminationG_0.smt2              |   30.053s | 178.0MiB| timeout | 0 |  |  |
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27439_terminationG_0.smt2 |   30.053s | 206.0MiB| timeout | 0 |  |  |
|From_T2__s1.t2__p19702_safety_0.smt2                         |   30.053s | 193.0MiB| timeout | 0 |  |  |
|From_T2__agafp.t2__p15648_terminationG_0.smt2                |   30.053s | 215.0MiB| timeout | 0 |  |  |
|From_T2__s1.t2__p18422_safety_0.smt2                         |   30.053s | 245.0MiB| timeout | 0 |  |  |
|term-unsat-02.smt2                                           |   30.053s | 204.0MiB| timeout | 0 |  |  |
|From_T2__s1-striped.t2__p13195_safety_0.smt2                 |   30.054s | 208.0MiB| timeout | 0 |  |  |
|Stroeder_15__Cousot.c__p22441_terminationG_0.smt2            |   30.054s | 227.0MiB| timeout | 0 |  |  |
|Stroeder_15__Choose.c__p22179_terminationG_0.smt2            |   30.054s | 197.0MiB| timeout | 0 |  |  |
|From_T2__edn.t2__p21132_safety_0.smt2                        |   30.054s | 220.0MiB| timeout | 0 |  |  |
|Stroeder_15__NonTerminationSimple6_false-termination.c__p25121_terminationG_0.smt2 |   30.054s | 183.0MiB| timeout | 0 |  |  |
|From_T2__small35.t2__p24016_terminationG_0.smt2              |   30.054s | 214.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__Velroyen08-even.jar-obl-9__p13541_terminationG_0.smt2 |   30.054s | 200.0MiB| timeout | 0 |  |  |
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__p32660_terminationG_0.smt2 |   30.054s | 217.0MiB| timeout | 0 |  |  |
|From_T2__compress.t2__p17837_safety_0.smt2                   |   30.054s | 290.0MiB| timeout | 0 |  |  |
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25050_edge_closing_0.smt2 |   30.054s | 309.0MiB| sat | 0 |  |  |
|From_T2__n-4.t2__p4556_edge_closing_0.smt2                   |   30.054s | 269.0MiB| timeout | 0 |  |  |
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21028_terminationG_0.smt2 |   30.054s | 219.0MiB| timeout | 0 |  |  |
|term-fu8ErM.smt2                                             |   30.054s | 209.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5336_safety_0.smt2 |   30.054s | 358.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__Velroyen08-narrowKonv.jar-obl-8__p14411_terminationG_0.smt2 |   30.054s | 262.0MiB| timeout | 0 |  |  |
|From_T2__ex36.t2__p31189_safety_0.smt2                       |   30.054s | 223.0MiB| timeout | 0 |  |  |
|Ton_Chanh_15__2Nested_false-termination.c__p26547_terminationG_0.smt2 |   30.054s | 239.0MiB| timeout | 0 |  |  |
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__p24940_edge_closing_0.smt2 |   30.054s | 235.0MiB| timeout | 0 |  |  |
|From_T2__janne_complex.t2__p2132_terminationG_0.smt2         |   30.055s | 232.0MiB| timeout | 0 |  |  |
|From_T2__p-46.t2__p6685_terminationG_0.smt2                  |   30.055s | 270.0MiB| timeout | 0 |  |  |
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_42_0.smt2  |   30.055s | 226.0MiB| timeout | 0 |  |  |
|From_T2__rlft3.t2__p9024_terminationG_0.smt2                 |   30.055s | 222.0MiB| timeout | 0 |  |  |
|From_T2__s1-striped.t2_fixed__p11279_safety_0.smt2           |   30.055s | 208.0MiB| timeout | 0 |  |  |
|Stroeder_15__UpAndDown.c__p26202_terminationG_0.smt2         |   30.055s | 247.0MiB| timeout | 0 |  |  |
|From_T2__ppblocktermbug.t2__p7793_terminationG_0.smt2        |   30.055s | 252.0MiB| timeout | 0 |  |  |
|From_T2__s1.t2__p20857_safety_0.smt2                         |   30.055s | 200.0MiB| timeout | 0 |  |  |
|From_T2__n-46.t2__p4386_terminationG_0.smt2                  |   30.055s | 205.0MiB| timeout | 0 |  |  |
|From_T2__ex19.t2__p22325_terminationG_0.smt2                 |   30.056s | 222.0MiB| timeout | 0 |  |  |
|From_T2__fun9.t2__p1420_edge_closing_0.smt2                  |   30.056s | 268.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__NO_12.jar-obl-8__p11367_terminationG_0.smt2 |   30.056s | 226.0MiB| timeout | 0 |  |  |
|From_T2__st88.bug.t2_fixed__p24181_terminationG_0.smt2       |   30.056s | 224.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__upAndDownIneq_rec.jar-obl-8__p13122_edge_closing_0.smt2 |   30.056s | 234.0MiB| timeout | 0 |  |  |
|From_T2__s1-striped.t2_fixed__p11660_safety_0.smt2           |   30.056s | 190.0MiB| timeout | 0 |  |  |
|aproveSMT5913022081957613825.smt2                            |   30.056s | 286.0MiB| timeout | 0 |  |  |
|From_T2__fun9.t2__p1270_edge_closing_0.smt2                  |   30.056s | 369.0MiB| timeout | 0 |  |  |
|11.smt2                                                      |   30.056s | 240.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__TriTas.jar-obl-12__p13025_terminationG_0.smt2 |   30.056s | 267.0MiB| timeout | 0 |  |  |
|From_T2__n-21.t2__p3936_terminationG_0.smt2                  |   30.057s | 261.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__MainDelete.jar-obl-10__p10491_safety_0.smt2 |   30.057s | 177.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1762_safety_0.smt2 |   30.057s | 246.0MiB| timeout | 0 |  |  |
|From_T2__ex36.t2__p31649_safety_0.smt2                       |   30.057s | 213.0MiB| timeout | 0 |  |  |
|From_T2__janne_complex.t2_fixed__p1996_terminationG_0.smt2   |   30.057s | 215.0MiB| timeout | 0 |  |  |
|From_T2__n-21.t2__p3920_terminationG_0.smt2                  |   30.057s | 225.0MiB| timeout | 0 |  |  |
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26854_edge_closing_0.smt2 |   30.057s | 211.0MiB| timeout | 0 |  |  |
|From_T2__2.t2__p15344_terminationG_0.smt2                    |   30.057s | 238.0MiB| timeout | 0 |  |  |
|aproveSMT6030602863271290399.smt2                            |   30.057s | 294.0MiB| timeout | 0 |  |  |
|From_T2__ex36.t2__p30140_safety_0.smt2                       |   30.057s | 250.0MiB| timeout | 0 |  |  |
|Stroeder_15__ComplxStruc.c__p22342_terminationG_0.smt2       |   30.057s | 231.0MiB| timeout | 0 |  |  |
|Ton_Chanh_15__Mysore_false-termination.c__p27264_terminationG_0.smt2 |   30.057s | 205.0MiB| timeout | 0 |  |  |
|From_T2__agafp.t2_fixed__p15554_terminationG_0.smt2          |   30.058s | 395.0MiB| timeout | 0 |  |  |
|term-0BB4ks.smt2                                             |   30.058s | 231.0MiB| timeout | 0 |  |  |
|Stroeder_15__WhileNestedOffset.c__p26458_terminationG_0.smt2 |   30.058s | 223.0MiB| timeout | 0 |  |  |
|From_T2__edn.t2__p20405_safety_0.smt2                        |   30.058s | 296.0MiB| timeout | 0 |  |  |
|aproveSMT578728211229400351.smt2                             |   30.058s | 367.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__Velroyen08-cousot.jar-obl-8__p13504_terminationG_0.smt2 |   30.058s | 227.0MiB| timeout | 0 |  |  |
|From_T2__edn.t2__p19669_safety_0.smt2                        |   30.058s | 255.0MiB| timeout | 0 |  |  |
|Ton_Chanh_15__2Nested_false-termination.c__p26557_terminationG_0.smt2 |   30.058s | 189.0MiB| timeout | 0 |  |  |
|From_T2__n-6.t2_fixed__p4771_terminationG_0.smt2             |   30.058s | 247.0MiB| timeout | 0 |  |  |
|From_T2__s1-striped.t2_fixed__p10804_safety_0.smt2           |   30.058s | 230.0MiB| timeout | 0 |  |  |
|From_T2__ppblockterm.t2__p7872_terminationG_0.smt2           |   30.059s | 252.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__cousot_rec.jar-obl-8__p28349_terminationG_0.smt2 |   30.059s | 278.0MiB| timeout | 0 |  |  |
|From_T2__slayer-n2-filtered.t2__p23194_terminationG_0.smt2   |   30.059s | 215.0MiB| timeout | 0 |  |  |
|From_T2__fun4.t2__p994_terminationG_0.smt2                   |   30.059s | 282.0MiB| timeout | 0 |  |  |
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2 |   30.059s | 244.0MiB| timeout | 0 |  |  |
|From_T2__fun9.t2__p1397_edge_closing_0.smt2                  |   30.059s | 291.0MiB| timeout | 0 |  |  |
|From_T2__fun9.t2__p1452_edge_closing_0.smt2                  |   30.059s | 311.0MiB| timeout | 0 |  |  |
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9200_terminationG_0.smt2 |   30.059s | 383.0MiB| timeout | 0 |  |  |
|From_T2__d.t2__p19043_terminationG_0.smt2                    |   30.059s | 253.0MiB| timeout | 0 |  |  |
|From_T2__janne_complex.t2__p2214_terminationG_0.smt2         |   30.059s | 244.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__FlattenTreeRec.jar-obl-9__p29631_edge_closing_0.smt2 |   30.059s | 255.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__NO_10.jar-obl-8__p11278_terminationG_0.smt2 |   30.059s | 223.0MiB| timeout | 0 |  |  |
|02.smt2                                                      |   30.059s | 360.0MiB| timeout | 0 |  |  |
|From_T2__hqr.t2__terminationS_48_0.smt2                      |   30.059s | 197.0MiB| timeout | 0 |  |  |
|From_T2__edn.t2__p19879_safety_0.smt2                        |   30.059s | 243.0MiB| timeout | 0 |  |  |
|From_T2__n-7.t2__p5066_terminationG_0.smt2                   |   30.059s | 285.0MiB| timeout | 0 |  |  |
|From_T2__n-46.t2__p4437_terminationG_0.smt2                  |   30.059s | 250.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__KnapsackDP.jar-obl-11__p9942_edge_closing_0.smt2 |   30.059s | 244.0MiB| timeout | 0 |  |  |
|From_T2__s1-striped.t2_fixed__p9772_safety_0.smt2            |   30.059s | 227.0MiB| timeout | 0 |  |  |
|From_T2__n-33.t2__p4083_terminationG_0.smt2                  |   30.059s | 247.0MiB| timeout | 0 |  |  |
|From_T2__n-5.t2_fixed__p4609_edge_closing_0.smt2             |   30.059s | 477.0MiB| timeout | 0 |  |  |
|From_T2__small15.t2__p23788_edge_closing_0.smt2              |   30.059s | 245.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__KnapsackDP.jar-obl-11__p9911_terminationG_0.smt2 |   30.059s | 216.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__ex08_rec.jar-obl-8__p29227_terminationG_0.smt2 |   30.059s | 239.0MiB| timeout | 0 |  |  |
|From_T2__ex36.t2__p28710_safety_0.smt2                       |   30.059s | 223.0MiB| timeout | 0 |  |  |
|From_T2__janne_complex.t2__p2157_terminationG_0.smt2         |   30.060s | 267.0MiB| timeout | 0 |  |  |
|Stroeder_15__ComplxStruc.c__p22352_terminationG_0.smt2       |   30.060s | 248.0MiB| timeout | 0 |  |  |
|From_T2__pentagon.t2__p7002_edge_closing_0.smt2              |   30.060s | 265.0MiB| timeout | 0 |  |  |
|From_T2__slayer-3-filtered.t2__p21681_safety_0.smt2          |   30.060s | 251.0MiB| timeout | 0 |  |  |
|From_T2__tqli.t2_fixed__p25199_edge_closing_0.smt2           |   30.060s | 287.0MiB| timeout | 0 |  |  |
|From_T2__consts4.t2__p18338_terminationG_0.smt2              |   30.060s | 273.0MiB| timeout | 0 |  |  |
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__p24898_edge_closing_0.smt2 |   30.060s | 240.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__DivMinus.jar-obl-11__p28547_terminationG_0.smt2 |   30.061s | 276.0MiB| timeout | 0 |  |  |
|From_T2__mc91test.t2__p3388_edge_closing_0.smt2              |   30.061s | 394.0MiB| timeout | 0 |  |  |
|From_T2__dummy.t2__p19098_terminationG_0.smt2                |   30.061s | 202.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__Norm.jar-obl-9__p11588_terminationG_0.smt2 |   30.061s | 428.0MiB| timeout | 0 |  |  |
|From_T2__ex36.t2__p31375_safety_0.smt2                       |   30.061s | 246.0MiB| timeout | 0 |  |  |
|From_T2__s1-striped.t2_fixed__p11700_safety_0.smt2           |   30.061s | 273.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32674_safety_0.smt2 |   30.061s | 347.0MiB| timeout | 0 |  |  |
|From_T2__ppblock.t2__p7723_terminationG_0.smt2               |   30.061s | 238.0MiB| timeout | 0 |  |  |
|From_T2__s1.t2_fixed__p15640_safety_0.smt2                   |   30.061s | 234.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__Et1-rec.jar-obl-8__p28758_terminationG_0.smt2 |   30.061s | 299.0MiB| timeout | 0 |  |  |
|Stroeder_15__Factorial.c__p22854_terminationG_0.smt2         |   30.061s | 277.0MiB| timeout | 0 |  |  |
|From_T2__pentagon.t2__p7145_edge_closing_0.smt2              |   30.061s | 257.0MiB| timeout | 0 |  |  |
|From_T2__s1-striped.t2_fixed__p10273_safety_0.smt2           |   30.061s | 282.0MiB| timeout | 0 |  |  |
|From_T2__s1.t2__p20179_safety_0.smt2                         |   30.061s | 181.0MiB| timeout | 0 |  |  |
|From_T2__n-21.t2__p3986_terminationG_0.smt2                  |   30.062s | 233.0MiB| timeout | 0 |  |  |
|From_T2__s1.t2__p19014_safety_0.smt2                         |   30.062s | 263.0MiB| timeout | 0 |  |  |
|From_T2__p-5.t2_fixed__p6778_terminationG_0.smt2             |   30.062s | 301.0MiB| timeout | 0 |  |  |
|Stroeder_15__DoubleNeg.c__p22532_terminationG_0.smt2         |   30.062s | 195.0MiB| timeout | 0 |  |  |
|From_T2__n-6.t2__p4819_terminationG_0.smt2                   |   30.062s | 253.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__Velroyen08-alternDivWidening.jar-obl-8__p13266_edge_closing_0.smt2 |   30.062s | 234.0MiB| timeout | 0 |  |  |
|From_T2__n-3a.t2_fixed__p4168_edge_closing_0.smt2            |   30.062s | 309.0MiB| timeout | 0 |  |  |
|From_T2__byron-4.t2__p17559_terminationG_0.smt2              |   30.062s | 289.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__cousot_rec.jar-obl-8__p28283_terminationG_0.smt2 |   30.062s | 238.0MiB| timeout | 0 |  |  |
|From_T2__n-7.t2__p5050_terminationG_0.smt2                   |   30.062s | 241.0MiB| timeout | 0 |  |  |
|From_T2__mc91.t2__p2877_terminationG_0.smt2                  |   30.063s | 297.0MiB| timeout | 0 |  |  |
|From_T2__edn.t2__p20828_safety_0.smt2                        |   30.063s | 273.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__Velroyen08-whileNested.jar-obl-8__p14763_terminationG_0.smt2 |   30.063s | 266.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__cousot_rec.jar-obl-8__p28299_terminationG_0.smt2 |   30.063s | 260.0MiB| timeout | 0 |  |  |
|From_T2__s1.t2__p20781_safety_0.smt2                         |   30.063s | 255.0MiB| timeout | 0 |  |  |
|From_T2__edn.t2__p19978_safety_0.smt2                        |   30.063s | 228.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__upAndDown_rec.jar-obl-8__p13155_edge_closing_0.smt2 |   30.063s | 277.0MiB| timeout | 0 |  |  |
|From_T2__walk.t2__p25580_terminationG_0.smt2                 |   30.064s | 310.0MiB| timeout | 0 |  |  |
|From_T2__small04.t2__p23571_terminationG_0.smt2              |   30.064s | 276.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2318_safety_0.smt2 |   30.064s | 346.0MiB| timeout | 0 |  |  |
|From_T2__byron-4.t2__p17543_terminationG_0.smt2              |   30.064s | 297.0MiB| timeout | 0 |  |  |
|aproveSMT7201733644041072759.smt2                            |   30.064s | 290.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__ListContent.jar-obl-9__p10107_terminationG_0.smt2 |   30.064s | 259.0MiB| timeout | 0 |  |  |
|From_T2__fun9.t2__p1442_edge_closing_0.smt2                  |   30.064s | 359.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__cousot_rec.jar-obl-8__p28383_terminationG_0.smt2 |   30.064s | 300.0MiB| timeout | 0 |  |  |
|From_T2__n-7.t2__p5015_terminationG_0.smt2                   |   30.064s | 268.0MiB| timeout | 0 |  |  |
|From_T2__bakery.t2__p17084_terminationG_0.smt2               |   30.064s | 250.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__MysteriousProgram.jar-obl-12__p11042_safety_0.smt2 |   30.065s | 280.0MiB| timeout | 0 |  |  |
|From_T2__n-1.t2__p3816_terminationG_0.smt2                   |   30.065s | 314.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__Test7.jar-obl-11__p12938_edge_closing_0.smt2 |   30.065s | 299.0MiB| timeout | 0 |  |  |
|From_T2__n-7.t2_fixed__p4919_terminationG_0.smt2             |   30.065s | 279.0MiB| timeout | 0 |  |  |
|From_T2__spiral.t2__p24127_edge_closing_0.smt2               |   30.065s | 276.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13911_terminationG_0.smt2 |   30.065s | 365.0MiB| timeout | 0 |  |  |
|From_T2__s1-striped.t2__p13884_safety_0.smt2                 |   30.065s | 205.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__flip_rec.jar-obl-8__p29677_terminationG_0.smt2 |   30.065s | 289.0MiB| timeout | 0 |  |  |
|term-K5O3aH.smt2                                             |   30.065s | 303.0MiB| timeout | 0 |  |  |
|From_T2__ex36.t2__p28843_safety_0.smt2                       |   30.065s | 283.0MiB| timeout | 0 |  |  |
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_33_0.smt2  |   30.066s | 335.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31599_safety_0.smt2 |   30.066s | 318.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__Velroyen08-ex09half.jar-obl-8__p13773_terminationG_0.smt2 |   30.066s | 318.0MiB| timeout | 0 |  |  |
|From_T2__slayer-n1.t2_fixed__p22950_safety_0.smt2            |   30.066s | 330.0MiB| timeout | 0 |  |  |
|From_T2__n-7.t2__p5116_terminationG_0.smt2                   |   30.066s | 294.0MiB| timeout | 0 |  |  |
|04.smt2                                                      |   30.066s | 250.0MiB| timeout | 0 |  |  |
|From_T2__byron-4.t2__p17594_terminationG_0.smt2              |   30.066s | 247.0MiB| timeout | 0 |  |  |
|From_T2__byron-4.t2__p17610_terminationG_0.smt2              |   30.066s | 329.0MiB| timeout | 0 |  |  |
|From_T2__n-7.t2__p5100_terminationG_0.smt2                   |   30.067s | 311.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7378_safety_0.smt2 |   30.067s | 343.0MiB| timeout | 0 |  |  |
|From_T2__fourn.t2__p32736_edge_closing_0.smt2                |   30.067s | 305.0MiB| timeout | 0 |  |  |
|From_T2__pentagon.t2__p7021_edge_closing_0.smt2              |   30.067s | 336.0MiB| timeout | 0 |  |  |
|From_T2__n-40.t2_fixed__p4249_terminationG_0.smt2            |   30.067s | 262.0MiB| timeout | 0 |  |  |
|From_T2__tqli.t2_fixed__p25131_terminationG_0.smt2           |   30.067s | 300.0MiB| timeout | 0 |  |  |
|From_T2__n-7.t2__p5150_terminationG_0.smt2                   |   30.067s | 247.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30040_safety_0.smt2 |   30.067s | 333.0MiB| timeout | 0 |  |  |
|From_T2__edn.t2__p20182_safety_0.smt2                        |   30.067s | 341.0MiB| timeout | 0 |  |  |
|From_T2__walk.t2__p25562_terminationG_0.smt2                 |   30.068s | 300.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__Test13Loops.jar-obl-10__p12688_terminationG_0.smt2 |   30.068s | 295.0MiB| timeout | 0 |  |  |
|aproveSMT7440630011441673394.smt2                            |   30.068s | 388.0MiB| timeout | 0 |  |  |
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__p1697_terminationG_0.smt2 |   30.068s | 382.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1939_safety_0.smt2 |   30.068s | 471.0MiB| timeout | 0 |  |  |
|From_T2__slayer-3.t2_fixed__p22165_safety_0.smt2             |   30.068s | 294.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__Velroyen08-factorial.jar-obl-8__p13835_terminationG_0.smt2 |   30.068s | 324.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__Et3.jar-obl-9__p28807_terminationG_0.smt2  |   30.068s | 280.0MiB| timeout | 0 |  |  |
|From_T2__s1-striped.t2_fixed__p11293_safety_0.smt2           |   30.069s | 217.0MiB| timeout | 0 |  |  |
|From_T2__weakness.t2__p25648_terminationG_0.smt2             |   30.069s | 295.0MiB| timeout | 0 |  |  |
|From_T2__queens.t2_fixed__p8358_terminationG_0.smt2          |   30.069s | 334.0MiB| timeout | 0 |  |  |
|Stroeder_15__NO_12.c__p24727_terminationG_0.smt2             |   30.069s | 327.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__Test13Loops.jar-obl-10__p12774_edge_closing_0.smt2 |   30.069s | 366.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__Velroyen08-factorial.jar-obl-8__p13800_terminationG_0.smt2 |   30.069s | 528.0MiB| timeout | 0 |  |  |
|From_T2__tqli.t2__p25267_edge_closing_0.smt2                 |   30.070s | 303.0MiB| timeout | 0 |  |  |
|From_T2__edn.t2__p20573_safety_0.smt2                        |   30.070s | 333.0MiB| timeout | 0 |  |  |
|From_T2__janne_complex.t2__p2182_terminationG_0.smt2         |   30.070s | 356.0MiB| timeout | 0 |  |  |
|From_T2__sudoku.t2__p24872_terminationG_0.smt2               |   30.070s | 365.0MiB| timeout | 0 |  |  |
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9234_terminationG_0.smt2 |   30.070s | 347.0MiB| timeout | 0 |  |  |
|From_T2__bakery.t2__p17184_terminationG_0.smt2               |   30.070s | 435.0MiB| timeout | 0 |  |  |
|From_T2__rev_nt2.t2_fixed__p8634_safety_0.smt2               |   30.070s | 380.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__p12576_terminationG_0.smt2 |   30.070s | 360.0MiB| timeout | 0 |  |  |
|From_T2__n_firewire_instrumented-PP.t2__p6187_terminationG_0.smt2 |   30.070s | 512.0MiB| timeout | 0 |  |  |
|From_T2__n-1d.t2_fixed__p3770_edge_closing_0.smt2            |   30.070s | 335.0MiB| timeout | 0 |  |  |
|From_T2__mc91.t2__p2826_terminationG_0.smt2                  |   30.070s | 278.0MiB| timeout | 0 |  |  |
|From_T2__nakata.t2__terminationS_3_0.smt2                    |   30.070s | 309.0MiB| timeout | 0 |  |  |
|From_T2__efegp.t2__p21964_edge_closing_0.smt2                |   30.070s | 303.0MiB| timeout | 0 |  |  |
|From_T2__bakery.t2__p17049_terminationG_0.smt2               |   30.071s | 318.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__Velroyen08-narrowing.jar-obl-8__p14385_terminationG_0.smt2 |   30.071s | 263.0MiB| timeout | 0 |  |  |
|From_T2__slayer-3-filtered.t2__p21613_terminationG_0.smt2    |   30.071s | 380.0MiB| timeout | 0 |  |  |
|From_T2__fun9.t2__p1324_edge_closing_0.smt2                  |   30.071s | 418.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2624_safety_0.smt2 |   30.072s | 387.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__NO_05.jar-obl-9__p11244_edge_closing_0.smt2 |   30.072s | 306.0MiB| timeout | 0 |  |  |
|From_T2__agafp.t2__p15632_terminationG_0.smt2                |   30.072s | 316.0MiB| timeout | 0 |  |  |
|From_T2__fun10b.t2__p340_terminationG_0.smt2                 |   30.072s | 370.0MiB| timeout | 0 |  |  |
|From_T2__janne_complex.t2__p2040_terminationG_0.smt2         |   30.072s | 505.0MiB| timeout | 0 |  |  |
|From_T2__rlft3.t2__p9161_terminationG_0.smt2                 |   30.072s | 368.0MiB| timeout | 0 |  |  |
|From_T2__pentagon.t2__p7164_edge_closing_0.smt2              |   30.072s | 345.0MiB| timeout | 0 |  |  |
|From_T2__small35.t2__p24066_terminationG_0.smt2              |   30.072s | 250.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13857_terminationG_0.smt2 |   30.073s | 354.0MiB| timeout | 0 |  |  |
|From_T2__n-37.t2__p4149_terminationG_0.smt2                  |   30.073s | 306.0MiB| timeout | 0 |  |  |
|From_T2__slayer-3-filtered.t2__p21663_terminationG_0.smt2    |   30.073s | 426.0MiB| timeout | 0 |  |  |
|From_T2__s1.t2_fixed__p15597_safety_0.smt2                   |   30.073s | 291.0MiB| timeout | 0 |  |  |
|From_T2__slayer-n1.t2__p23156_terminationG_0.smt2            |   30.073s | 353.0MiB| timeout | 0 |  |  |
|From_T2__mc91test.t2__p3343_terminationG_0.smt2              |   30.073s | 385.0MiB| timeout | 0 |  |  |
|Stroeder_15__svcomp_ex2.c__p25963_terminationG_0.smt2        |   30.073s | 335.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__FlattenTree.jar-obl-9__p29513_terminationG_0.smt2 |   30.073s | 315.0MiB| timeout | 0 |  |  |
|From_T2__slayer-n1.t2_fixed__p23107_safety_0.smt2            |   30.074s | 331.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__FlattenRTA.jar-obl-10__p29475_terminationG_0.smt2 |   30.074s | 318.0MiB| timeout | 0 |  |  |
|From_T2__n_firewire_instrumented-PP.t2__p6221_edge_closing_0.smt2 |   30.074s | 363.0MiB| timeout | 0 |  |  |
|Stroeder_15__svcomp_ex2.c__p25867_terminationG_0.smt2        |   30.074s | 367.0MiB| timeout | 0 |  |  |
|From_T2__nakata.t2__p5324_terminationG_0.smt2                |   30.074s | 311.0MiB| timeout | 0 |  |  |
|From_T2__slayer-5-filtered.t2__p22891_terminationG_0.smt2    |   30.074s | 335.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__NO_05.jar-obl-9__p11209_safety_0.smt2      |   30.074s | 293.0MiB| timeout | 0 |  |  |
|Stroeder_15__svcomp_ex2.c__p25929_terminationG_0.smt2        |   30.074s | 402.0MiB| timeout | 0 |  |  |
|From_T2__apchild-accepted.t2_fixed__terminationS_4_0.smt2    |   30.074s | 404.0MiB| timeout | 0 |  |  |
|From_T2__s1-striped.t2__p12025_terminationG_0.smt2           |   30.074s | 414.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__Graph.jar-obl-17__p29778_edge_closing_0.smt2 |   30.075s | 317.0MiB| timeout | 0 |  |  |
|From_T2__fun9.t2__p1356_edge_closing_0.smt2                  |   30.075s | 360.0MiB| timeout | 0 |  |  |
|From_T2__pentagon.t2__p7100_edge_closing_0.smt2              |   30.075s | 337.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__Test13Loops.jar-obl-10__p12705_edge_closing_0.smt2 |   30.075s | 309.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30379_safety_0.smt2 |   30.075s | 344.0MiB| timeout | 0 |  |  |
|From_T2__dumper.t2__p19133_terminationG_0.smt2               |   30.075s | 331.0MiB| timeout | 0 |  |  |
|35.smt2                                                      |   30.075s | 448.0MiB| timeout | 0 |  |  |
|From_T2__byron-4.t2__p17661_terminationG_0.smt2              |   30.075s | 310.0MiB| timeout | 0 |  |  |
|124.smt2                                                     |   30.076s | 384.0MiB| timeout | 0 |  |  |
|From_T2__n-40.t2__p4288_terminationG_0.smt2                  |   30.076s | 402.0MiB| timeout | 0 |  |  |
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__p1718_edge_closing_0.smt2 |   30.077s | 603.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7426_safety_0.smt2 |   30.077s | 408.0MiB| timeout | 0 |  |  |
|From_T2__afagp-fail.t2__p15486_terminationG_0.smt2           |   30.077s | 354.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31120_safety_0.smt2 |   30.077s | 593.0MiB| timeout | 0 |  |  |
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32640_edge_closing_0.smt2 |   30.078s | 370.0MiB| timeout | 0 |  |  |
|From_T2__mc91test.t2__p3121_terminationG_0.smt2              |   30.078s | 401.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32319_safety_0.smt2 |   30.078s | 559.0MiB| timeout | 0 |  |  |
|Stroeder_15__svcomp_ex2.c__p25903_terminationG_0.smt2        |   30.078s | 348.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__Test6.jar-obl-13__p12864_terminationG_0.smt2 |   30.078s | 329.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31162_safety_0.smt2 |   30.078s | 505.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5299_safety_0.smt2 |   30.078s | 373.0MiB| timeout | 0 |  |  |
|177.smt2                                                     |   30.078s | 363.0MiB| timeout | 0 |  |  |
|From_T2__mc91test.t2__p3205_terminationG_0.smt2              |   30.079s | 414.0MiB| timeout | 0 |  |  |
|From_T2__firewire.t2__p32294_terminationG_0.smt2             |   30.079s | 453.0MiB| timeout | 0 |  |  |
|From_T2__mc91.t2__p2893_terminationG_0.smt2                  |   30.079s | 456.0MiB| timeout | 0 |  |  |
|aproveSMT6674842082078899004.smt2                            |   30.079s | 313.0MiB| timeout | 0 |  |  |
|From_T2__fun9.t2__p1386_edge_closing_0.smt2                  |   30.079s | 366.0MiB| timeout | 0 |  |  |
|From_T2__db2.t2_fixed__p18729_edge_closing_0.smt2            |   30.079s | 497.0MiB| timeout | 0 |  |  |
|From_T2__randomwalk.t2__p8440_terminationG_0.smt2            |   30.080s | 416.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__Power.jar-obl-10__p11792_terminationG_0.smt2 |   30.080s | 434.0MiB| timeout | 0 |  |  |
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__p24885_terminationG_0.smt2 |   30.080s | 416.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6451_safety_0.smt2 |   30.080s | 460.0MiB| timeout | 0 |  |  |
|aproveSMT2279546529930018049.smt2                            |   30.080s | 418.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31977_safety_0.smt2 |   30.080s | 443.0MiB| timeout | 0 |  |  |
|From_T2__p_armc.t2__p6954_edge_closing_0.smt2                |   30.081s | 617.0MiB| timeout | 0 |  |  |
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__p1650_edge_closing_0.smt2 |   30.081s | 419.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31433_safety_0.smt2 |   30.081s | 591.0MiB| timeout | 0 |  |  |
|From_T2__janne_complex.t2__p2276_terminationG_0.smt2         |   30.082s | 712.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7555_safety_0.smt2 |   30.082s | 439.0MiB| timeout | 0 |  |  |
|From_T2__brp_withassume.t2__term_unfeasibility_1_0.smt2      |   30.082s | 375.0MiB| timeout | 0 |  |  |
|65.smt2                                                      |   30.082s | 538.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__cousot_rec.jar-obl-8__p28333_terminationG_0.smt2 |   30.082s | 387.0MiB| timeout | 0 |  |  |
|From_T2__florian_sas2.t2__p32410_terminationG_0.smt2         |   30.082s | 474.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30951_safety_0.smt2 |   30.083s | 461.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3088_safety_0.smt2 |   30.083s | 456.0MiB| timeout | 0 |  |  |
|From_T2__n_firewire_instrumented-PP.t2__p6203_terminationG_0.smt2 |   30.083s | 432.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1881_safety_0.smt2 |   30.083s | 405.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5380_safety_0.smt2 |   30.083s | 387.0MiB| timeout | 0 |  |  |
|From_T2__pentagon.t2__p7069_edge_closing_0.smt2              |   30.084s | 342.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2164_safety_0.smt2 |   30.084s | 458.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31678_safety_0.smt2 |   30.084s | 412.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__DivMinus.jar-obl-11__p28566_edge_closing_0.smt2 |   30.084s | 362.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31139_safety_0.smt2 |   30.084s | 514.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__TaylorSeriesIte.jar-obl-13__p12483_terminationG_0.smt2 |   30.084s | 386.0MiB| timeout | 0 |  |  |
|58.smt2                                                      |   30.084s | 519.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2398_safety_0.smt2 |   30.085s | 501.0MiB| timeout | 0 |  |  |
|From_T2__mc91test.t2__p3075_terminationG_0.smt2              |   30.085s | 370.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13895_terminationG_0.smt2 |   30.085s | 437.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_21_0.smt2 |   30.085s | 517.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31103_safety_0.smt2 |   30.085s | 455.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2999_safety_0.smt2 |   30.085s | 477.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32715_safety_0.smt2 |   30.085s | 527.0MiB| timeout | 0 |  |  |
|From_T2__streamserver-succeed.t2__p24787_terminationG_0.smt2 |   30.086s | 432.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5452_safety_0.smt2 |   30.086s | 500.0MiB| timeout | 0 |  |  |
|From_T2__mc91test.t2__p3256_terminationG_0.smt2              |   30.086s | 393.0MiB| timeout | 0 |  |  |
|From_T2__rlft3.t2__p9061_terminationG_0.smt2                 |   30.087s | 397.0MiB| timeout | 0 |  |  |
|From_T2__small14.t2__p23695_terminationG_0.smt2              |   30.087s | 502.0MiB| timeout | 0 |  |  |
|From_T2__slayer-3-filtered.t2__p21513_terminationG_0.smt2    |   30.087s | 459.0MiB| timeout | 0 |  |  |
|98.smt2                                                      |   30.087s | 460.0MiB| timeout | 0 |  |  |
|From_T2__n-21.t2__p3885_terminationG_0.smt2                  |   30.087s | 297.0MiB| timeout | 0 |  |  |
|Stroeder_15__svcomp_ex2.c__p25913_terminationG_0.smt2        |   30.087s | 492.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32548_safety_0.smt2 |   30.087s | 472.0MiB| timeout | 0 |  |  |
|From_T2__destroy_seg_leak.t2__p18873_terminationG_0.smt2     |   30.088s | 372.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2138_safety_0.smt2 |   30.088s | 558.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7074_safety_0.smt2 |   30.088s | 535.0MiB| timeout | 0 |  |  |
|From_T2__fun1b.t2_fixed__p577_terminationG_0.smt2            |   30.089s | 542.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2547_safety_0.smt2 |   30.089s | 519.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3295_safety_0.smt2 |   30.089s | 509.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__SortCount.jar-obl-10__p12217_terminationG_0.smt2 |   30.089s | 386.0MiB| timeout | 0 |  |  |
|From_T2__mc91.t2__p2790_terminationG_0.smt2                  |   30.089s | 550.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6269_safety_0.smt2 |   30.089s | 507.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4855_safety_0.smt2 |   30.089s | 454.0MiB| timeout | 0 |  |  |
|From_T2__select.t2_fixed__p21326_terminationG_0.smt2         |   30.089s | 438.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p440_terminationG_0.smt2 |   30.089s | 468.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3276_safety_0.smt2 |   30.089s | 541.0MiB| timeout | 0 |  |  |
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8833_terminationG_0.smt2 |   30.090s | 452.0MiB| timeout | 0 |  |  |
|From_T2__fun6.t2__p1105_edge_closing_0.smt2                  |   30.090s | 509.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__Matrix.jar-obl-16__p10817_safety_0.smt2    |   30.090s | 536.0MiB| timeout | 0 |  |  |
|From_T2__rlft3.t2__p9006_terminationG_0.smt2                 |   30.090s | 561.0MiB| timeout | 0 |  |  |
|From_T2__rlft3.t2__p9111_terminationG_0.smt2                 |   30.090s | 418.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6048_safety_0.smt2 |   30.091s | 471.0MiB| timeout | 0 |  |  |
|aproveSMT3839584170547805483.smt2                            |   30.091s | 558.0MiB| timeout | 0 |  |  |
|From_T2__bakery.t2__p17200_terminationG_0.smt2               |   30.091s | 665.0MiB| timeout | 0 |  |  |
|From_T2__zlib-crc32-BYFOUR.c.t2__p26457_safety_0.smt2        |   30.091s | 553.0MiB| timeout | 0 |  |  |
|From_T2__afagp-fail.t2__p15502_terminationG_0.smt2           |   30.091s | 506.0MiB| timeout | 0 |  |  |
|99.smt2                                                      |   30.091s | 554.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5509_safety_0.smt2 |   30.091s | 569.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4746_safety_0.smt2 |   30.092s | 555.0MiB| timeout | 0 |  |  |
|40.smt2                                                      |   30.092s | 481.0MiB| timeout | 0 |  |  |
|73.smt2                                                      |   30.092s | 494.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_30_0.smt2 |   30.093s | 510.0MiB| timeout | 0 |  |  |
|54.smt2                                                      |   30.094s | 513.0MiB| timeout | 0 |  |  |
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8764_terminationG_0.smt2 |   30.094s | 573.0MiB| timeout | 0 |  |  |
|From_T2__mc91test.t2__p3059_terminationG_0.smt2              |   30.094s | 417.0MiB| timeout | 0 |  |  |
|From_T2__s1-striped.t2_fixed__p9315_terminationG_0.smt2      |   30.094s | 487.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3355_safety_0.smt2 |   30.094s | 512.0MiB| timeout | 0 |  |  |
|From_T2__bakery.t2__p17100_terminationG_0.smt2               |   30.094s | 430.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6498_terminationG_0.smt2 |   30.094s | 521.0MiB| timeout | 0 |  |  |
|From_T2__mc91.t2__p2842_terminationG_0.smt2                  |   30.094s | 437.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30565_safety_0.smt2 |   30.095s | 527.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__FlattenTreeListRec.jar-obl-10__p29595_terminationG_0.smt2 |   30.095s | 434.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__SortCount.jar-obl-10__p12110_terminationG_0.smt2 |   30.095s | 448.0MiB| timeout | 0 |  |  |
|From_T2__slayer-3-filtered.t2__p21529_terminationG_0.smt2    |   30.096s | 761.0MiB| timeout | 0 |  |  |
|From_T2__bakery.t2__p17150_terminationG_0.smt2               |   30.096s | 604.0MiB| timeout | 0 |  |  |
|From_T2__streamserver-succeed.t2__p24720_terminationG_0.smt2 |   30.096s | 567.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6950_safety_0.smt2 |   30.096s | 445.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2106_safety_0.smt2 |   30.096s | 483.0MiB| timeout | 0 |  |  |
|From_T2__n-7.t2__p5166_terminationG_0.smt2                   |   30.096s | 759.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30879_safety_0.smt2 |   30.097s | 578.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4635_safety_0.smt2 |   30.097s | 528.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31041_safety_0.smt2 |   30.097s | 537.0MiB| timeout | 0 |  |  |
|From_T2__sas2.t2__p21288_terminationG_0.smt2                 |   30.097s | 439.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31747_safety_0.smt2 |   30.097s | 591.0MiB| timeout | 0 |  |  |
|140.smt2                                                     |   30.097s | 555.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7576_safety_0.smt2 |   30.097s | 580.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3156_safety_0.smt2 |   30.098s | 625.0MiB| timeout | 0 |  |  |
|aproveSMT6023062156836720896.smt2                            |   30.098s | 471.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31339_safety_0.smt2 |   30.098s | 551.0MiB| timeout | 0 |  |  |
|From_T2__florian_sas2.t2__p32394_terminationG_0.smt2         |   30.100s | 473.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30491_terminationG_0.smt2 |   30.102s | 572.0MiB| timeout | 0 |  |  |
|From_T2__zlib-crc32-BYFOUR.c.t2__p26484_terminationG_0.smt2  |   30.102s | 762.0MiB| timeout | 0 |  |  |
|From_T2__zlib-crc32-BYFOUR.c.t2__p26555_edge_closing_0.smt2  |   30.103s | 545.0MiB| timeout | 0 |  |  |
|From_T2__mc91test.t2__p3327_terminationG_0.smt2              |   30.103s | 443.0MiB| timeout | 0 |  |  |
|From_T2__slayer-3-filtered.t2__p21563_terminationG_0.smt2    |   30.103s | 455.0MiB| timeout | 0 |  |  |
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__p1619_terminationG_0.smt2 |   30.104s | 622.0MiB| timeout | 0 |  |  |
|From_T2__db3.t2_fixed__p18755_terminationG_0.smt2            |   30.104s | 639.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7280_safety_0.smt2 |   30.105s | 640.0MiB| timeout | 0 |  |  |
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__p25078_terminationG_0.smt2 |   30.105s | 819.0MiB| timeout | 0 |  |  |
|Stroeder_15__svcomp_ex2.c__p25863_terminationG_0.smt2        |   30.105s | 524.0MiB| timeout | 0 |  |  |
|From_T2__fun9.t2__p1232_edge_closing_0.smt2                  |   30.106s | 680.0MiB| timeout | 0 |  |  |
|From_T2__agafp.t2_fixed__p15538_terminationG_0.smt2          |   30.106s | 706.0MiB| timeout | 0 |  |  |
|From_T2__ex36.t2__p25650_safety_0.smt2                       |   30.107s | 687.0MiB| timeout | 0 |  |  |
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__p25099_edge_closing_0.smt2 |   30.107s | 765.0MiB| timeout | 0 |  |  |
|From_T2__apchild-live.t2__p16624_terminationG_0.smt2         |   30.107s | 742.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32365_safety_0.smt2 |   30.107s | 684.0MiB| timeout | 0 |  |  |
|From_T2__tqli.t2_fixed__p25153_terminationG_0.smt2           |   30.108s | 806.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2923_safety_0.smt2 |   30.108s | 812.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32763_safety_0.smt2 |   30.109s | 689.0MiB| timeout | 0 |  |  |
|From_T2__ex36.t2__p24638_terminationG_0.smt2                 |   30.109s | 675.0MiB| timeout | 0 |  |  |
|From_T2__n-40.t2__p4304_terminationG_0.smt2                  |   30.110s | 638.0MiB| timeout | 0 |  |  |
|From_T2__pentagon.t2__p6980_terminationG_0.smt2              |   30.110s | 521.0MiB| timeout | 0 |  |  |
|From_T2__agafp.t2__p15598_terminationG_0.smt2                |   30.110s | 641.0MiB| timeout | 0 |  |  |
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8895_terminationG_0.smt2 |   30.111s | 721.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6967_safety_0.smt2 |   30.111s | 477.0MiB| timeout | 0 |  |  |
|From_T2__slayer-3.t2__p22348_safety_0.smt2                   |   30.112s | 638.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_19_0.smt2 |   30.112s | 771.0MiB| timeout | 0 |  |  |
|From_T2__streamserver-succeed.t2__p24621_terminationG_0.smt2 |   30.112s | 686.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32635_safety_0.smt2 |   30.113s | 663.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30820_safety_0.smt2 |   30.113s | 672.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__Matrix.jar-obl-16__p10831_terminationG_0.smt2 |   30.114s | 679.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_28_0.smt2 |   30.114s | 752.0MiB| timeout | 0 |  |  |
|From_T2__fun1b.t2__p616_terminationG_0.smt2                  |   30.114s | 712.0MiB| timeout | 0 |  |  |
|From_T2__nakata.t2__p5341_terminationG_0.smt2                |   30.114s | 663.0MiB| timeout | 0 |  |  |
|From_T2__apchild-accepted-fail.t2__p15947_terminationG_0.smt2 |   30.115s | 750.0MiB| timeout | 0 |  |  |
|From_T2__apchild-accepted.t2__p16354_terminationG_0.smt2     |   30.117s | 822.0MiB| timeout | 0 |  |  |
|From_T2__zlib-adler32.c.t2__p26165_terminationG_0.smt2       |   30.117s | 708.0MiB| timeout | 0 |  |  |
|From_T2__streamserver-succeed.t2__p24771_terminationG_0.smt2 |   30.117s | 756.0MiB| timeout | 0 |  |  |
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__p1682_edge_closing_0.smt2 |   30.118s | 700.0MiB| timeout | 0 |  |  |
|From_T2__hqr.t2_fixed__p1737_terminationG_0.smt2             |   30.118s | 736.0MiB| timeout | 0 |  |  |
|From_T2__slayer-3-filtered.t2__p21786_safety_0.smt2          |   30.118s | 589.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_0_0.smt2 |   30.119s | 771.0MiB| timeout | 0 |  |  |
|From_T2__foo.t2__terminationS_30_0.smt2                      |   30.119s | 716.0MiB| timeout | 0 |  |  |
|From_T2__tqli.t2_fixed__p25176_terminationG_0.smt2           |   30.120s | 949.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32196_safety_0.smt2 |   30.121s | 656.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6223_safety_0.smt2 |   30.121s | 792.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31726_safety_0.smt2 |   30.121s | 711.0MiB| timeout | 0 |  |  |
|From_T2__slayer-3.t2__p22398_safety_0.smt2                   |   30.121s | 762.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3125_safety_0.smt2 |   30.121s | 591.0MiB| timeout | 0 |  |  |
|From_T2__hqr.t2__p1776_terminationG_0.smt2                   |   30.125s | 852.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4657_safety_0.smt2 |   30.125s | 828.0MiB| timeout | 0 |  |  |
|From_T2__slayer-3-filtered.t2__p21629_terminationG_0.smt2    |   30.126s | 757.0MiB| timeout | 0 |  |  |
|From_T2__nakata.t2__p5306_terminationG_0.smt2                |   30.126s | 844.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2674_safety_0.smt2 |   30.127s | 764.0MiB| timeout | 0 |  |  |
|From_T2__agafp.t2__p15582_terminationG_0.smt2                |   30.127s | 798.0MiB| timeout | 0 |  |  |
|From_T2__fun7.t2__p1142_terminationG_0.smt2                  |   30.128s | 788.0MiB| timeout | 0 |  |  |
|From_T2__fun1.t2_fixed__p754_terminationG_0.smt2             |   30.128s | 802.0MiB| timeout | 0 |  |  |
|From_T2__polling.t2_fixed__p7336_terminationG_0.smt2         |   30.128s | 758.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__Alternate.jar-obl-10__p27480_terminationG_0.smt2 |   30.131s | 828.0MiB| timeout | 0 |  |  |
|From_T2__apchild-live.t2_fixed__p16480_terminationG_0.smt2   |   30.131s | 894.0MiB| timeout | 0 |  |  |
|From_T2__fun1b.t2__p685_terminationG_0.smt2                  |   30.132s | 753.0MiB| timeout | 0 |  |  |
|From_T2__fun1b.t2_fixed__p544_terminationG_0.smt2            |   30.132s | 804.0MiB| timeout | 0 |  |  |
|From_T2__slayer-3-filtered.t2__p21579_terminationG_0.smt2    |   30.132s | 708.0MiB| timeout | 0 |  |  |
|From_T2__bs.t2_fixed__p17456_terminationG_0.smt2             |   30.133s | 794.0MiB| timeout | 0 |  |  |
|From_T2__pgarch.t2__p7297_terminationG_0.smt2                |   30.135s | 890.0MiB| timeout | 0 |  |  |
|From_T2__bakery.t2__p17134_terminationG_0.smt2               |   30.137s | 903.0MiB| timeout | 0 |  |  |
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25030_terminationG_0.smt2 |   30.138s | 974.0MiB| timeout | 0 |  |  |
|From_T2__slayer-3-new.t2__p21904_terminationG_0.smt2         |   30.138s | 873.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__Main.jar-obl-11__p10718_edge_closing_0.smt2 |   30.138s | 917.0MiB| timeout | 0 |  |  |
|From_T2__apchildlive-succeed.t2__p16446_terminationG_0.smt2  |   30.138s | 882.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9619_terminationG_0.smt2 |   30.139s | 872.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6990_safety_0.smt2 |   30.140s | 889.0MiB| timeout | 0 |  |  |
|From_T2__apchild-accepted-fail.t2_fixed__p15778_terminationG_0.smt2 |   30.140s | 1043.0MiB| timeout | 0 |  |  |
|From_T2__brp_withassume.t2__p17426_terminationG_0.smt2       |   30.142s | 938.0MiB| timeout | 0 |  |  |
|From_T2__foo.t2__terminationS_21_0.smt2                      |   30.143s | 759.0MiB| timeout | 0 |  |  |
|From_T2__tqli.t2__p25231_terminationG_0.smt2                 |   30.144s | 966.0MiB| timeout | 0 |  |  |
|From_T2__apchild-live.t2_fixed__p16538_terminationG_0.smt2   |   30.144s | 1021.0MiB| timeout | 0 |  |  |
|From_T2__slayer-4-filtered.t2__p22466_safety_0.smt2          |   30.145s | 871.0MiB| timeout | 0 |  |  |
|From_T2__disj_nightmare.t2__p18946_edge_closing_0.smt2       |   30.146s | 956.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__LessLeavesRec.jar-obl-10__p10045_terminationG_0.smt2 |   30.146s | 967.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__MirrorBinTreeRec.jar-obl-9__p10900_terminationG_0.smt2 |   30.146s | 950.0MiB| timeout | 0 |  |  |
|From_T2__slayer-3-new.t2__p21954_terminationG_0.smt2         |   30.147s | 909.0MiB| timeout | 0 |  |  |
|From_T2__p.t2__p8315_terminationG_0.smt2                     |   30.150s | 975.0MiB| timeout | 0 |  |  |
|From_T2__slayer-3.t2__p22280_terminationG_0.smt2             |   30.150s | 1018.0MiB| timeout | 0 |  |  |
|From_T2__apchild-accepted.t2__p16279_terminationG_0.smt2     |   30.151s | 1096.0MiB| timeout | 0 |  |  |
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25005_terminationG_0.smt2 |   30.152s | 785.0MiB| timeout | 0 |  |  |
|From_T2__s1.t2_fixed__p15164_terminationG_0.smt2             |   30.153s | 965.0MiB| timeout | 0 |  |  |
|From_T2__slayer-3.t2__p22262_terminationG_0.smt2             |   30.154s | 973.0MiB| timeout | 0 |  |  |
|From_T2__db3.t2__terminationQ_0_0.smt2                       |   30.155s | 1022.0MiB| timeout | 0 |  |  |
|From_T2__db3.t2__p18773_terminationG_0.smt2                  |   30.156s | 1214.0MiB| timeout | 0 |  |  |
|From_T2__slayer-3-new.t2__p22004_terminationG_0.smt2         |   30.157s | 1078.0MiB| timeout | 0 |  |  |
|From_T2__slayer-3.t2__p22206_terminationG_0.smt2             |   30.158s | 983.0MiB| timeout | 0 |  |  |
|From_T2__apchild-live.t2__p16640_terminationG_0.smt2         |   30.158s | 1030.0MiB| timeout | 0 |  |  |
|From_T2__apchild-accepted-fail.t2__p15972_terminationG_0.smt2 |   30.159s | 1064.0MiB| timeout | 0 |  |  |
|From_T2__slayer-4-filtered.t2__p22485_terminationG_0.smt2    |   30.161s | 1050.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7615_edge_closing_0.smt2 |   30.161s | 1057.0MiB| timeout | 0 |  |  |
|From_T2__mc91test.t2__p3279_terminationG_0.smt2              |   30.161s | 1051.0MiB| timeout | 0 |  |  |
|From_T2__slayer-3-new.t2__p21920_terminationG_0.smt2         |   30.161s | 1096.0MiB| timeout | 0 |  |  |
|From_T2__slayer-3.t2__p22223_terminationG_0.smt2             |   30.163s | 1126.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__Count.jar-obl-10-2__p28122_terminationG_0.smt2 |   30.164s | 1035.0MiB| timeout | 0 |  |  |
|From_T2__curious4.t2__p18665_edge_closing_0.smt2             |   30.167s | 1134.0MiB| timeout | 0 |  |  |
|From_T2__apchildlive-succeed.t2_fixed__p16388_terminationG_0.smt2 |   30.167s | 1199.0MiB| timeout | 0 |  |  |
|From_T2__slayer-3.t2__p22317_terminationG_0.smt2             |   30.172s | 946.0MiB| timeout | 0 |  |  |
|From_T2__slayer-3-new.t2__p21970_terminationG_0.smt2         |   30.178s | 1249.0MiB| timeout | 0 |  |  |
|From_T2__apchild-live.t2_fixed__p16596_terminationG_0.smt2   |   30.178s | 1067.0MiB| timeout | 0 |  |  |
|From_T2__db2.t2__p18746_edge_closing_0.smt2                  |   30.180s | 1079.0MiB| timeout | 0 |  |  |
|From_T2__fun1b.t2__p639_terminationG_0.smt2                  |   30.183s | 1300.0MiB| timeout | 0 |  |  |
|From_T2__fun1.t2__p806_terminationG_0.smt2                   |   30.184s | 1294.0MiB| timeout | 0 |  |  |
|From_T2__mc91test.t2__p3143_terminationG_0.smt2              |   30.188s | 1048.0MiB| timeout | 0 |  |  |
|From_T2__apchild-accepted-fail.t2_fixed__p15806_terminationG_0.smt2 |   30.196s | 1420.0MiB| timeout | 0 |  |  |
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5394_edge_closing_0.smt2 |   30.199s | 1488.0MiB| timeout | 0 |  |  |
|From_T2__apchildlive-succeed.t2__p16461_edge_closing_0.smt2  |   30.204s | 1500.0MiB| timeout | 0 |  |  |
|181.smt2                                                     |   30.220s | 1502.0MiB| timeout | 0 |  |  |
|From_T2__nakata.t2__p5353_edge_closing_0.smt2                |   30.255s | 1511.0MiB| timeout | 0 |  |  |
|From_T2__apchild-accepted-fail.t2_fixed__p15906_edge_closing_0.smt2 |   30.255s | 1814.0MiB| timeout | 0 |  |  |
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2           |   30.280s | 2138.0MiB| timeout | 0 |  |  |
|182.smt2                                                     |   30.280s | 2047.0MiB| timeout | 0 |  |  |
|From_T2__pgarch.t2_fixed__p7218_edge_closing_0.smt2          |   30.347s | 2271.0MiB| timeout | 0 |  |  |
|183.smt2                                                     |   30.374s | 2154.0MiB| timeout | 0 |  |  |
|From_T2__cover.t2__p18610_edge_closing_0.smt2                |   30.438s | 3285.0MiB| timeout | 0 |  |  |
|185.smt2                                                     |   30.475s | 3732.0MiB| timeout | 0 |  |  |
|From_T2__apchild-accepted.t2_fixed__p16184_edge_closing_0.smt2 |   30.481s | 3257.0MiB| timeout | 0 |  |  |
