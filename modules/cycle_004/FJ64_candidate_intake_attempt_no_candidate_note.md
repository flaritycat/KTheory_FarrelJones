# Module FJ64. Candidate Intake Attempt or No-Candidate Note

## Status

Completed

## Module type

Attack surface / Candidate intake / Obstruction record

## Problem

`FJ63` selects `DAP-T001-001`, candidate-row acquisition from current
repository records. This module must execute that packet. It must either add
one candidate-admissible row to `ledgers/t001_candidate_inventory.md` or
record a no-candidate note explaining why no current row can be promoted
without external source acquisition or fabrication.

This module must not redesign the cycle-004 plan, start a source survey, or
turn a placeholder into a mathematical candidate.

## Input

- `FJ61`, T-001 Candidate-Intake Reset and Exit Criteria;
- `FJ62`, Active Blocker Pruning for `T-001`;
- `FJ63`, Candidate-Data Acquisition Packet;
- `OQ-086`;
- `OBL-T001-010`;
- `ledgers/t001_candidate_inventory.md`;
- `ledgers/t001_residual.md`;
- `ledgers/t001_kernel_recognition.md`;
- `ledgers/open_group_classes.md`;
- `OPEN_QUESTIONS.md`;
- `PROJECT_CHARTER.md`;
- `AGENTS.md`.

## Output target

Exactly one of:

- a new candidate-admissible row satisfying the `FJ61` checklist; or
- a no-candidate note preserving the obstruction and selecting the next
  governance step.

## Definitions

**Definition.** A no-candidate note is a project-state record that the
current repository does not contain a candidate-admissible row for the active
packet. It is not a theorem that no such candidate exists.

**Definition.** A promotable row for `DAP-T001-001` is either an existing row
or an existing named repository family with all fields required by the `FJ61`
candidate-admissible checklist: candidate identity, target status, residual
status, route-output target, required data, formulation safety, prior-art
risk, and exit condition.

**Warning.** The no-candidate note does not solve `T-001`, does not prove a
negative theorem about torsion-free one-relator groups, and does not make a
new Farrell--Jones claim.

## Main work

### Packet execution

`DAP-T001-001` asks whether existing repository records contain any
candidate row, residual bucket, or named family that can be promoted into a
candidate-admissible row without importing a new source or fabricating a
family.

The packet is executed against:

- the current candidate table;
- the residual bucket ledger;
- the kernel-recognition ledger;
- the open group classes ledger;
- the open-question handoff.

### Candidate row audit

| Possible row | Repository support | FJ64 decision |
|---|---|---|
| `CAND-T001-001` | Commutator calibration example with finite-rank free kernel data; already non-residual through the virtually solvable route. | Do not promote. Calibration only. |
| `CAND-T001-002` | \(G_{2,3}\) with Brown data and \(\ker(\chi)\cong F_2\); already removed through `FJ26`. | Do not promote. Already routed. |
| `CAND-T001-003` | \(G_{p,q}\)-family with finite-rank free-kernel route from `FJ36`; already removed through `FJ26`. | Do not promote. Already routed. |
| `TPL-RB003-004-008` | Template placeholder with no presentation, target status, route output, kernel data, or prior-art comparison. | Do not promote. Not a mathematical candidate. |
| `RB-003` hierarchy-only data | Bucket-level structure without a named non-routed presentation or approved route output. | Do not promote. Bucket label only. |
| `RB-004` / `RB-008` kernel or extension data | Kernel-recognition tools are dormant and currently attached only to calibration or routed rows. | Do not promote. No live row. |
| `RB-005` finite-index / `FJCw` lane | No named `T-001` case with `FJCw` subgroup input or formulation-safe finite-index target. | Do not promote. No application case. |
| WIP / provisional `RB-006` lane | \(\pi(w)>2\) is recorded only as hyperbolic-route overlap through `FJ23`; no concrete word is checked. | Do not promote. No non-hyperbolic bridge and no row. |
| `RB-007` virtually solvable-looking lane | Recognition bucket without a named candidate family. | Do not promote. No row. |

### Candidate-admissibility checklist result

No current repository row satisfies the full `FJ61` checklist.

| Checklist field | Current packet result |
|---|---|
| Candidate identity | Concrete rows exist only as calibration or routed examples; the template has no presentation. |
| Target status | Existing concrete rows are not live residual targets; the template has unknown status. |
| Residual status | Existing concrete rows are already removed or non-residual. |
| Route-output target | No non-routed row names a route output. |
| Required data | No bridge lemma, computation, source payload, or prior-art blocker is attached to a live row. |
| Formulation safety | No new formulation-sensitive row exists for comparison. |
| Prior-art risk | No object exists for prior-art comparison. |
| Exit condition | The correct exit is a no-candidate note and a prior-art / branch-readiness checkpoint. |

### No-candidate note

`FJ64` records that `DAP-T001-001` fails to produce a
candidate-admissible row from current repository records.

This failure means:

- no row is added to the candidate inventory;
- `OBL-T001-010` is completed by recording the no-candidate outcome;
- `T-001` remains unresolved;
- no residual bucket is subtracted;
- no source-summary module is licensed by this failure.

### New proof obligation

**Obligation OBL-T001-011.** Prior-art / branch-readiness checkpoint after
no-candidate intake.

`FJ65` must check whether the no-candidate state leaves any exact prior-art
blocker object, target-pause recommendation, or target-pivot comparison to
record. It must not begin external source verification or a proof attempt
unless it identifies a project object changed by that action.

Stop condition: if no candidate, prior-art object, exact source payload,
bridge, computation, or pause / pivot object is present, send the project to
the `FJ66` branch checkpoint rather than opening another source-summary lane.

## Proposition / Theorem / Conjecture / Example

**Proposition.** In the current repository state, `DAP-T001-001` produces a
no-candidate note rather than a candidate-admissible row.

**Proof.** The only concrete rows in `ledgers/t001_candidate_inventory.md`
are `CAND-T001-001`, `CAND-T001-002`, and `CAND-T001-003`. The first is
calibration-only and already non-residual; the second and third are already
removed through the `FJ26` finite-rank free-by-cyclic route. The remaining
template row has no presentation or route data. The residual and
kernel-recognition ledgers record no additional named non-routed row, no
new computation target, and no exact source payload. Therefore no existing
repository object satisfies the `FJ61` candidate-admissible checklist, so the
packet output is a no-candidate note.

**Route decision.** `FJ64` resolves `OQ-086`, completes `OBL-T001-010` by
recording the no-candidate outcome, records `OBL-T001-011`, and selects
`FJ65`, Prior-Art / Branch-Readiness Checkpoint.

**Warning.** `FJ64` proves no new Farrell--Jones case, proves no theorem
about torsion-free one-relator groups, finalizes no part of WIP /
provisional `FJ53`, and makes no residual subtraction.

## Proof or verification

Verification was internal to the repository:

1. Checked the `FJ61` candidate-admissible checklist.
2. Checked the `FJ63` packet specification.
3. Checked `ledgers/t001_candidate_inventory.md` for candidate rows and
   proof obligations.
4. Checked `ledgers/t001_residual.md` for bucket-level candidate data.
5. Checked `ledgers/t001_kernel_recognition.md` for active computation data.
6. Checked `ledgers/open_group_classes.md` and `OPEN_QUESTIONS.md` for the
   current handoff.
7. No new external source was checked.

## References

No new external source was used in this module.

Internal references:

- `modules/cycle_004/FJ61_t001_candidate_intake_reset_exit_criteria.md`
- `modules/cycle_004/FJ62_active_blocker_pruning_t001.md`
- `modules/cycle_004/FJ63_candidate_data_acquisition_packet.md`
- `OPEN_QUESTIONS.md`
- `ledgers/t001_candidate_inventory.md`
- `ledgers/t001_residual.md`
- `ledgers/t001_kernel_recognition.md`
- `ledgers/open_group_classes.md`
- `PROJECT_CHARTER.md`
- `AGENTS.md`

## Dependencies

This module depends on:

- `FJ61`;
- `FJ62`;
- `FJ63`;
- `OQ-086`;
- `OBL-T001-010`;
- `ledgers/t001_candidate_inventory.md`;
- `ledgers/t001_residual.md`;
- `ledgers/t001_kernel_recognition.md`.

## Results produced

This module produced:

- a first-pass resolution of `OQ-086`;
- completion of `OBL-T001-010` by no-candidate note;
- `OBL-T001-011`, the prior-art / branch-readiness checkpoint obligation;
- selection of `FJ65`, Prior-Art / Branch-Readiness Checkpoint;
- no new `ER-*` result;
- no new candidate-admissible row;
- no concrete residual subtraction.

## Open questions generated

- `OQ-087`: Can `FJ65` identify a prior-art blocker object, target-pause
  recommendation, or target-pivot comparison after the `FJ64` no-candidate
  note, or must it send the project to the `FJ66` branch checkpoint?

## Update to ledgers

After completion, update:

- `README.md` and `PROJECT_CHARTER.md` for completed `FJ64` and next `FJ65`;
- `SCOPE_LEDGER.md` for the `OQ-086` resolution and new `OQ-087`;
- `OPEN_QUESTIONS.md` for `OQ-086` and `OQ-087`;
- `NOTATION_LEDGER.md` for no-candidate note and `OBL-T001-011`;
- `ledgers/t001_candidate_inventory.md` for the no-candidate note and new
  obligation;
- `ledgers/t001_residual.md`, `ledgers/t001_kernel_recognition.md`,
  `ledgers/theorem_dependencies.md`, and `ledgers/open_group_classes.md` for
  the current target update;
- `references/papers_to_read.md` and `AGENTS.md` for the next handoff.
