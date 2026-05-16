# Module FJ67. Target-Pivot Criteria After T-001 Pause

## Status

Completed

## Module type

Governance checkpoint / Target-pivot criteria / Attack surface

## Problem

`FJ66` pauses `T-001`, torsion-free one-relator residual gap analysis, as an
active proof-target sequence. The repository still contains possible future
target classes, especially Artin groups, automatic / biautomatic groups, and
Thompson-type groups, but it has not yet recorded criteria for comparing
those targets.

`FJ67` must define the criteria before selecting a new active target. It
must not convert the `T-001` pause into a negative theorem, and it must not
replace one candidate-free source lane with another.

## Input

- `FJ66`, T-001 Branch Checkpoint;
- `OQ-089`;
- `OBL-T001-013`;
- `README.md`;
- `PROJECT_CHARTER.md`;
- `SCOPE_LEDGER.md`;
- `OPEN_QUESTIONS.md`;
- `NOTATION_LEDGER.md`;
- `AGENTS.md`;
- `ledgers/open_group_classes.md`;
- `ledgers/known_classes.md`;
- `ledgers/source_status.md`;
- `ledgers/theorem_dependencies.md`.

## Output target

A first-pass target-pivot criteria packet:

- resolve `OQ-089`;
- record a target-pivot matrix requirement;
- prevent immediate target selection by inertia;
- select `FJ68`, Target-Pivot Candidate Matrix, as the next module;
- keep `T-001` dormant unless the `OBL-T001-013` reactivation gate is met.

## Definitions

**Definition.** A target-pivot matrix is a table comparing possible next
active targets against recorded project criteria before any target is
selected for proof work, source verification, or route subtraction.

**Definition.** Source-readiness means that the repository already records an
exact source payload or source-ready internal object: theorem statement,
hypotheses, formulation level, source status, and the project object that
would change.

**Definition.** Candidate-level attackability means that a target has a named
class, subclass, group family, bridge lemma, computation, or obstruction
object that can drive a bounded module. A broad class name alone is not
candidate-level attackability.

**Definition.** Decorative bibliography risk is the risk that a module
accumulates source names or general background without changing a candidate
inventory, residual-bucket status, open-question status, proof obligation,
prior-art blocker list, or theorem-dependency row.

**Warning.** `FJ67` selects no new active mathematical target. It records the
criteria needed before that selection can be made.

## Main work

### Pivot criteria

| Criterion | Required evidence | Rejection signal |
|---|---|---|
| Source-readiness | Exact source payload, or existing source-verified repository row, with hypotheses and formulation level recorded. | A source name, reputation marker, or broad bibliography theme. |
| Candidate-level attackability | Named class, subclass, candidate family, bridge lemma, computation, or obstruction object. | A global class with no bounded next object. |
| Farrell--Jones relevance | Clear path to an FJ route, formulation bridge, K-theory consequence, inheritance comparison, or prior-art blocker. | Pure group-theory background with no FJ-facing obligation. |
| Formulation safety | Explicit distinction between full Farrell--Jones, `FJCw`, `FICwF`, coefficient versions, finite-index passage, and weaker \(K_0\)-level statements. | Treating source formulations as interchangeable. |
| Existing repository leverage | Uses current modules, ledgers, or source-status rows rather than starting from a blank source hunt. | A new source sequence that bypasses accumulated blockers. |
| Prior-art control | Records whether the likely output is already known, likely known, unknown inside the project, or blocked by a source gap. | Novelty language without a comparison object. |
| Expected project output | Names the exact project object to change: candidate inventory, residual bucket, open question, proof obligation, prior-art blocker, or theorem-dependency row. | A module whose only output is a narrative summary. |
| Stop condition | States what would make the target fail the next module. | Open-ended reading without a failure mode. |

### Preliminary target inputs

This table does not select a target. It records which inputs `FJ68` should
compare under the pivot criteria.

| Possible target input | Current repository anchor | Readiness estimate | Main risk | Role in `FJ68` |
|---|---|---|---|---|
| Artin groups | `FJ18`, `ER-011`, `ledgers/known_classes.md`, `ledgers/open_group_classes.md` | medium to high for a bounded subclass-gap comparison | confusing verified subclasses with a global all-Artin result | eligible for target-pivot matrix; not selected yet |
| Automatic / biautomatic groups | `ledgers/open_group_classes.md` | low to medium | broad source accumulation before a source-ready packet exists | compare only if the matrix records an exact first object or rejects it as not ready |
| Thompson-type groups | `ledgers/open_group_classes.md` | low | broad background without an FJ-facing bridge | compare only as an open-class ledger entry unless a source-ready packet exists |
| `T-001`, torsion-free one-relator groups | `FJ19`--`FJ66`, `ledgers/t001_*` | dormant; extensive archive but no active candidate | reactivating the target without satisfying `OBL-T001-013` | include only as a dormant comparator unless explicitly reselected by the matrix |

### Matrix template for FJ68

`FJ68` should use at least the following fields:

| Field | Required entry |
|---|---|
| Target ID | Stable label for the candidate target or target input. |
| Candidate class or subclass | Exact group class, subclass, family, or candidate object. |
| Repository anchor | Existing module, ledger row, source-status row, or open question. |
| Source payload present? | yes / no / partial, with exact pointer if yes or partial. |
| Source-readiness rating | high / medium / low, with reason. |
| Candidate-level object available? | candidate row, bridge, computation, obstruction, prior-art blocker, or none. |
| Intended FJ-facing route | hyperbolic, CAT(0), virtually solvable, extension, finite-index, additive-category formulation, consequence lane, or other named route. |
| Formulation-safety flags | full FJ / coefficient K-theory / `FJCw` / `FICwF` / \(K_0\)-level / unknown. |
| Known-route overlap | Which existing known route might already absorb the target. |
| Prior-art risk | low / medium / high, with recorded comparison object if available. |
| Expected project output | Exact ledger, module, open question, proof obligation, or blocker to change. |
| Stop condition | What makes the target fail the pivot step. |
| Decision | select / defer / reject for now / dormant comparator. |

### New proof obligation

**Obligation OBL-PIVOT-001.** No new active target may be selected after the
`T-001` pause until a target-pivot matrix records:

- source-readiness;
- candidate-level object;
- Farrell--Jones relevance;
- formulation-safety flags;
- known-route overlap;
- prior-art risk;
- expected project output;
- stop condition;
- explicit decision.

Stop condition: a class name, source name, or sense that a topic is
interesting is not enough to select an active target.

### Next module selection

`FJ67` selects:

```text
FJ68. Target-Pivot Candidate Matrix
```

Goal: apply the `FJ67` criteria to the currently recorded possible targets,
especially Artin groups, automatic / biautomatic groups, Thompson-type
groups, and dormant `T-001`.

Required input:

- `FJ67`;
- `OBL-PIVOT-001`;
- `ledgers/open_group_classes.md`;
- `ledgers/known_classes.md`;
- `ledgers/source_status.md`;
- `OPEN_QUESTIONS.md`;
- `PROJECT_CHARTER.md`.

Success criterion:

- select one bounded target packet; or
- record that no target is ready, with exact missing objects and stop
  conditions.

Failure criterion:

- the module becomes a source summary without changing a target decision,
  open question, proof obligation, or ledger row.

Expected output:

- a target-pivot matrix;
- a decision row for each compared target input;
- either a selected `FJ69` target packet or a documented no-target-ready
  obstruction.

## Proposition / Theorem / Conjecture / Example

**Proposition.** In the current repository state, the project should not
select a new active target before completing a target-pivot matrix satisfying
`OBL-PIVOT-001`.

**Proof.** `FJ66` pauses `T-001` because the repository contains no
candidate-admissible row, exact source payload, bridge, computation,
prior-art blocker object, or pivot-comparison result justifying continued
active work on that target. `ledgers/open_group_classes.md` lists possible
future classes, but those entries do not themselves record target-selection
criteria. The project rules require source discipline, formulation safety,
and a changed project object for new modules. Therefore a target-pivot
matrix is required before any new active target is selected.

**Route decision.** `FJ67` resolves `OQ-089`, records `OBL-PIVOT-001`,
selects `FJ68`, and makes no new mathematical theorem claim.

**Warning.** `FJ67` does not claim that `T-001` is solved, false, or
unimportant. It also does not claim Farrell--Jones for all Artin groups,
automatic / biautomatic groups, or Thompson-type groups.

## Proof or verification

Verification was internal to the repository:

1. Checked `FJ66` for the `T-001` branch decision and `OBL-T001-013`.
2. Checked `ledgers/open_group_classes.md` for possible target inputs.
3. Checked `ledgers/known_classes.md` and `ledgers/source_status.md` for
   source-readiness anchors.
4. Checked `OPEN_QUESTIONS.md` for `OQ-089`.
5. Checked `PROJECT_CHARTER.md`, `SCOPE_LEDGER.md`, and `AGENTS.md` for the
   current procedural handoff.
6. No new external source was checked.

## References

No new external source was used in this module.

Internal references:

- `modules/cycle_004/FJ66_t001_branch_checkpoint.md`
- `ledgers/open_group_classes.md`
- `ledgers/known_classes.md`
- `ledgers/source_status.md`
- `OPEN_QUESTIONS.md`
- `PROJECT_CHARTER.md`
- `SCOPE_LEDGER.md`
- `AGENTS.md`

## Dependencies

This module depends on:

- `FJ66`;
- `OQ-089`;
- `OBL-T001-013`;
- `ledgers/open_group_classes.md`;
- `ledgers/known_classes.md`;
- `ledgers/source_status.md`.

## Results produced

This module produced:

- a first-pass resolution of `OQ-089`;
- `OBL-PIVOT-001`, the target-pivot matrix requirement;
- a target-pivot criteria table;
- a target-pivot matrix template for `FJ68`;
- selection of `FJ68`, Target-Pivot Candidate Matrix;
- no new `ER-*` result;
- no new active target selection;
- no residual subtraction.

## Open questions generated

- `OQ-090`: Which candidate target, if any, should `FJ68` select after
  applying the `FJ67` target-pivot criteria?

## Update to ledgers

After completion, update:

- `README.md` and `PROJECT_CHARTER.md` for completed `FJ67` and next `FJ68`;
- `SCOPE_LEDGER.md` for the `OQ-089` resolution and new `OQ-090`;
- `OPEN_QUESTIONS.md` for `OQ-089` and `OQ-090`;
- `NOTATION_LEDGER.md` for target-pivot matrix terms and `OBL-PIVOT-001`;
- `ledgers/open_group_classes.md` for target-pivot next actions;
- `ledgers/theorem_dependencies.md` for the completed `FJ67` row and pending
  `FJ68`;
- `ledgers/t001_candidate_inventory.md`, `ledgers/t001_residual.md`, and
  `ledgers/t001_kernel_recognition.md` for the dormant `T-001` handoff;
- `references/papers_to_read.md` and `AGENTS.md` for the next handoff.
