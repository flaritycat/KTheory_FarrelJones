# Module FJ20. First target selection

## Status

Completed

## Module type

Reflection / Selection

## Problem

Choose the first serious research target after modules `FJ01`--`FJ19`.

The target should be narrow enough to support source-verified progress, but
not so narrow that the next cycle becomes only bookkeeping. It should also
avoid pretending that a broad open class has been solved by a convenient
subclass theorem.

## Input

This module uses repository-internal results and ledgers:

- `FJ18`, the Artin groups dossier;
- `FJ19`, the torsion-free one-relator groups dossier;
- `ledgers/known_classes.md`;
- `ledgers/open_group_classes.md`;
- `OPEN_QUESTIONS.md`, especially `OQ-001`, `OQ-021`--`OQ-026`;
- `SCOPE_LEDGER.md`.

No new external mathematical source is imported in this module. External
facts are used only through the already recorded source-verified modules and
ledgers.

## Output target

A ranked list of candidate subproblems scored by:

- attack surface;
- originality potential;
- machinery burden;
- source-readiness;
- decision status.

## Definitions

**Definition.** A candidate target is a bounded mathematical program that can
guide the next cycle of modules. It may be a proof attempt, a reduction
program, a gap map, or a source-verification campaign, but it must have an
explicit success condition.

**Definition.** Attack surface means the amount of concrete structure already
available in the repository for making progress on the target.

**Definition.** Originality potential means the chance that the work could
produce a nontrivial reduction, a useful new formulation, or a genuinely
informative negative/gap map, rather than only restating known theorems.

**Definition.** Machinery burden means the amount of technical infrastructure
that must be internalized before proof-sensitive work can begin. In the scoring
table, lower burden is better.

## Main work

### Candidate target table

Scores are first-pass project-management scores from 1 to 5. For attack
surface, originality potential, and source-readiness, 5 is best. For machinery
burden, 1 is easiest and 5 is heaviest.

| Rank | Candidate target | Attack surface | Originality potential | Machinery burden | Source-readiness | Decision |
|---|---|---:|---:|---:|---:|---|
| 1 | `T-001`: torsion-free one-relator residual gap analysis | 5 | 4 | 3 | 4 | Selected |
| 2 | Artin residual subclass analysis beyond `FJ18` | 4 | 3 | 4 | 3 | Defer |
| 3 | Reconcile `FJCw`, `FICwF`, and the project's simplified formulation | 5 | 2 | 4 | 3 | Necessary support work, not the first group target |
| 4 | Expand the known-classes ledger to 3-manifold, relatively hyperbolic, mapping class, lattice, and S-arithmetic groups | 4 | 2 | 3 | 3 | Useful background, but not a first target |
| 5 | Automatic, biautomatic, or Thompson-type groups | 2 | 3 | 4 | 1 | Defer until the known-cases ledger is broader |

### Selected target

**Target `T-001`.** Build a source-verified residual gap analysis for
torsion-free one-relator groups.

The first-cycle conclusion is not that Farrell--Jones is known for all
torsion-free one-relator groups. The selected target is to identify what
survives after removing the cases already covered by:

- hyperbolic groups;
- finite-dimensional CAT(0)-groups;
- virtually solvable groups;
- hyperbolic-by-cyclic and free-by-cyclic routes;
- any source-verified inheritance row that can be used under exact
  hypotheses.

### Success criteria for `T-001`

The next cycle should be considered successful if it produces:

1. a source-verified one-relator structure toolkit;
2. a subclass-by-subclass coverage table showing which torsion-free
   one-relator groups are already covered by known Farrell--Jones routes;
3. at least one explicit surviving subclass or example family that is not
   currently covered in the project;
4. a proof-sensitive dependency list for any attempted reduction;
5. a clear decision whether to attempt a theorem, prove a conditional
   reduction, or abandon this target as too broad.

### Why this target wins

**Reason.** `FJ19` gives a strong enough boundary: the global class remains
unresolved in the project, but several known routes already cover meaningful
subclasses. That makes the next step mathematically honest and concrete:
subtract the known routes and see what remains.

**Reason.** The target has less immediate source-formulation friction than the
Artin route. Artin groups in `FJ18` are entangled with `FJCw`, `FICwF`, finite
wreath products, Helly groups, Garside groups, and normally poly-free
machinery. Those are valuable, but the first new target should not begin by
asking the project to reconcile every source convention at once.

**Warning.** The one-relator target still needs the additive-category
formulation eventually. The selection only says that the first group-theoretic
target should be one-relator residual analysis, not that the foundational
module `FJ02` has become unnecessary.

### Deferred targets

**Deferred Artin target.** Artin groups remain important, but `FJ18` already
records several source-verified positive rows. A later Artin target should
begin only after the project has reconciled `FJCw`, `FICwF`, and the internal
statement.

**Deferred known-classes expansion.** Relatively hyperbolic groups,
3-manifold groups, mapping class groups, lattices, and S-arithmetic groups
should be added to the known-classes ledger later. They are useful background,
but they do not by themselves choose a first unresolved target.

**Deferred automatic/Thompson target.** These classes remain too far from the
current source-verified machinery to be the first serious target.

## Proposition / Theorem / Conjecture / Example

**Selection.** The first serious research target for the next cycle is
`T-001`: torsion-free one-relator residual gap analysis.

**Warning.** This is a project-selection result, not a mathematical theorem.
It should not be recorded in `ESTABLISHED_RESULTS.md`.

## Proof or verification

This module verifies the selection by comparing:

- `FJ18`, where the Artin case has several verified positive subclass rows but
  high source-formulation burden;
- `FJ19`, where the torsion-free one-relator case has a clear unresolved
  global status, explicit positive routes, and concrete residual questions;
- `ledgers/open_group_classes.md`, where torsion-free one-relator groups are
  already marked as a candidate class whose next action is to isolate the
  surviving cases.

The verification is internal to the repository. No new theorem claim is made.

## References

No new external references were used.

Internal references:

- `modules/cycle_001/FJ18_artin_groups_dossier.md`
- `modules/cycle_001/FJ19_one_relator_groups_dossier.md`
- `ledgers/known_classes.md`
- `ledgers/open_group_classes.md`
- `OPEN_QUESTIONS.md`

## Dependencies

This module depends on:

- `FJ18` and `ER-011`;
- `FJ19` and `ER-012`;
- `FJ02`, still deferred, for later source-formulation reconciliation;
- the known-cases and inheritance ledgers.

## Results produced

This module produced:

- `T-001`: selected first serious target, torsion-free one-relator residual
  gap analysis.

No new mathematical established result number is created.

## Open questions generated

No new open questions are needed. This module promotes existing questions:

- `OQ-024`;
- `OQ-025`;
- `OQ-026`.

## Update to ledgers

After completion, update:

- `SCOPE_LEDGER.md` for the selected target and next move;
- `OPEN_QUESTIONS.md` to mark `OQ-001` as resolved for first-pass target
  selection;
- `PROJECT_CHARTER.md` and `README.md` for completed cycle-001 module status;
- `ledgers/open_group_classes.md` and `ledgers/theorem_dependencies.md` for
  the selected target.
