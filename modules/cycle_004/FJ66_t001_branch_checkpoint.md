# Module FJ66. T-001 Branch Checkpoint

## Status

Completed

## Module type

Governance checkpoint / Target-pause recommendation / Branch decision

## Problem

`FJ65` records a target-pause trigger for `T-001`: no
candidate-admissible row, no exact source payload, no prior-art blocker
object, and no prepared pivot-comparison object are currently present.

`FJ66` must make the branch decision explicit. It must either pause `T-001`
as an active proof-target sequence, select a bounded target-pivot comparison
packet, or identify an exact repository object that justifies continuing
`T-001`.

This module must not convert the pause trigger into a negative mathematical
claim.

## Input

- `FJ61`, T-001 Candidate-Intake Reset and Exit Criteria;
- `FJ62`, Active Blocker Pruning for `T-001`;
- `FJ63`, Candidate-Data Acquisition Packet;
- `FJ64`, Candidate Intake Attempt or No-Candidate Note;
- `FJ65`, Prior-Art / Branch-Readiness Checkpoint;
- `OQ-088`;
- `OBL-T001-012`;
- `ledgers/t001_candidate_inventory.md`;
- `ledgers/t001_residual.md`;
- `ledgers/t001_kernel_recognition.md`;
- `ledgers/open_group_classes.md`;
- `OPEN_QUESTIONS.md`;
- `PROJECT_CHARTER.md`;
- `AGENTS.md`.

## Output target

A branch decision:

- pause `T-001` as an active proof-target sequence;
- select a bounded target-pivot comparison packet;
- or continue `T-001` only if an exact repository object justifies doing so.

## Definitions

**Definition.** A target-pause recommendation is a project-state decision to
stop active proof-target modules for a target until the repository records
new candidate data, an exact source payload, a bridge, a computation, or a
prior-art object.

**Definition.** A dormant target is an unresolved target retained in the
archive but not eligible for immediate proof-attempt, source-summary, or
route-subtraction modules.

**Definition.** A target-pivot criteria packet is a bounded governance module
that defines how the project should choose or compare possible next active
targets.

**Warning.** Pausing `T-001` is not a theorem that torsion-free one-relator
groups fail Farrell--Jones, and it is not evidence against the conjecture.
It records only that the current repository has no actionable next object.

## Main work

### Branch audit

| Branch option | Current repository support | Decision |
|---|---|---|
| Continue `T-001` through a proof attempt | No candidate-admissible row exists after `FJ64`. | reject |
| Continue `T-001` through a source-verification module | No exact source payload is active after `FJ60`, `FJ64`, and `FJ65`. | reject |
| Continue `T-001` through a bridge or computation | No candidate, bridge, computation, or route-output target is present. | reject |
| Select an immediate new target | `ledgers/open_group_classes.md` lists possible targets, but no pivot criteria are recorded. | reject for now |
| Pause `T-001` as active proof-target sequence | Required by the no-candidate and no-object state. | selected |
| Create target-pivot criteria packet | Needed before choosing another active target. | selected as next module |

### Target-pause recommendation

`FJ66` pauses `T-001` as an active proof-target sequence.

The target remains in scope as an unresolved archived target. It may be
reactivated only if a later module records one of the following:

- a candidate-admissible row;
- an exact source payload with theorem statement, hypotheses, formulation
  level, source status, and project object changed;
- a bridge lemma or computation attached to a named candidate;
- a prior-art blocker object attached to a candidate or theorem payload;
- a target-pivot comparison result that explicitly reselects `T-001`.

### Pivot decision

`FJ66` does not select a new mathematical target immediately.

Reason: `ledgers/open_group_classes.md` contains possible future classes
such as Artin groups, automatic / biautomatic groups, and Thompson-type
groups, but the project has not recorded target-selection criteria for a
post-`T-001` pivot.

The next module should therefore define the pivot criteria before selecting
or comparing targets.

### New proof obligation

**Obligation OBL-T001-013.** Reactivation gate for paused `T-001`.

No future module may reactivate `T-001` as an active proof-target sequence
unless it records one of:

- a candidate-admissible row;
- an exact source payload;
- a bridge lemma;
- a concrete computation;
- a prior-art blocker object;
- a target-pivot comparison result explicitly reselecting `T-001`.

Stop condition: a source name, residual bucket label, or general desire to
continue the target is not enough.

### Next module selection

`FJ66` selects:

```text
FJ67. Target-Pivot Criteria After T-001 Pause
```

`FJ67` should not choose a new target by inertia. It should define criteria
for comparing candidate target classes, including:

- source-readiness;
- chance of candidate-level work;
- likelihood of producing a theorem, obstruction, or useful ledger update;
- risk of decorative bibliography;
- compatibility with the Farrell--Jones program rather than unrelated
  group-theory drift.

## Proposition / Theorem / Conjecture / Example

**Proposition.** In the current repository state, `T-001` should be paused as
an active proof-target sequence, and the next module should define target
pivot criteria before selecting a new active target.

**Proof.** `FJ64` records no candidate-admissible row. `FJ65` records no
exact prior-art blocker object or prepared pivot-comparison object. The
weaker consequence lane is inactive after `FJ60` because no exact source
payload is recorded. The candidate inventory contains only calibration,
already routed, or placeholder rows. Thus no exact repository object
justifies continuing `T-001` through proof work, source verification, or
route subtraction. At the same time, `ledgers/open_group_classes.md` lists
possible future target classes without pivot criteria. Therefore the
responsible branch decision is to pause `T-001` and define target-pivot
criteria next.

**Route decision.** `FJ66` resolves `OQ-088`, completes `OBL-T001-012`,
records `OBL-T001-013`, pauses `T-001` as an active proof-target sequence,
and selects `FJ67`, Target-Pivot Criteria After T-001 Pause.

**Warning.** `FJ66` proves no new Farrell--Jones case, proves no theorem
about torsion-free one-relator groups, finalizes no part of WIP /
provisional `FJ53`, and makes no residual subtraction.

## Proof or verification

Verification was internal to the repository:

1. Checked `FJ65` for the branch-readiness decision.
2. Checked `ledgers/t001_candidate_inventory.md` for candidate rows and
   active proof obligations.
3. Checked `ledgers/t001_residual.md` for active residual objects.
4. Checked `ledgers/t001_kernel_recognition.md` for route-data availability.
5. Checked `ledgers/open_group_classes.md` for possible pivot targets.
6. Checked `OPEN_QUESTIONS.md` for `OQ-088`.
7. No new external source was checked.

## References

No new external source was used in this module.

Internal references:

- `modules/cycle_004/FJ61_t001_candidate_intake_reset_exit_criteria.md`
- `modules/cycle_004/FJ62_active_blocker_pruning_t001.md`
- `modules/cycle_004/FJ63_candidate_data_acquisition_packet.md`
- `modules/cycle_004/FJ64_candidate_intake_attempt_no_candidate_note.md`
- `modules/cycle_004/FJ65_prior_art_branch_readiness_checkpoint.md`
- `OPEN_QUESTIONS.md`
- `ledgers/t001_candidate_inventory.md`
- `ledgers/t001_residual.md`
- `ledgers/t001_kernel_recognition.md`
- `ledgers/open_group_classes.md`
- `PROJECT_CHARTER.md`
- `AGENTS.md`

## Dependencies

This module depends on:

- `FJ65`;
- `OQ-088`;
- `OBL-T001-012`;
- `ledgers/t001_candidate_inventory.md`;
- `ledgers/t001_residual.md`;
- `ledgers/t001_kernel_recognition.md`;
- `ledgers/open_group_classes.md`.

## Results produced

This module produced:

- a first-pass resolution of `OQ-088`;
- completion of `OBL-T001-012`;
- a target-pause recommendation for `T-001`;
- `OBL-T001-013`, the reactivation gate for paused `T-001`;
- selection of `FJ67`, Target-Pivot Criteria After T-001 Pause;
- no new `ER-*` result;
- no new target selection;
- no concrete residual subtraction.

## Open questions generated

- `OQ-089`: What criteria should `FJ67` use to compare possible next active
  targets after the `T-001` pause?

## Update to ledgers

After completion, update:

- `README.md` and `PROJECT_CHARTER.md` for completed `FJ66` and next `FJ67`;
- `SCOPE_LEDGER.md` for the `OQ-088` resolution and new `OQ-089`;
- `OPEN_QUESTIONS.md` for `OQ-088` and `OQ-089`;
- `NOTATION_LEDGER.md` for target-pause terms and `OBL-T001-013`;
- `ledgers/t001_candidate_inventory.md` for the completed branch decision
  and reactivation gate;
- `ledgers/t001_residual.md`, `ledgers/t001_kernel_recognition.md`,
  `ledgers/theorem_dependencies.md`, and `ledgers/open_group_classes.md` for
  the current target update;
- `references/papers_to_read.md` and `AGENTS.md` for the next handoff.
