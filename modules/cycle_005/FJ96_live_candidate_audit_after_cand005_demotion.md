# Module FJ96. Live-Candidate Audit After CAND-T001-005 Demotion

## Status

Completed

## Module type

Candidate-status verification / Project-governance audit /
Payload-instantiated module

## Problem

`FJ95` demotes `CAND-T001-005` to blocked / inactive proof-target status.
Prompt 014 in `next_prompts.md` asks for a bounded internal audit of whether
any live non-routed `T-001` candidate row remains after that branch decision.

This module must not introduce a new candidate, use external sources, reopen
`CAND-T001-005`, or claim a Farrell--Jones theorem.

## Input

- `FJ56`;
- `FJ57`;
- `FJ84`;
- `FJ89`;
- `FJ90`;
- `FJ91`;
- `FJ92`;
- `FJ93`;
- `FJ94`;
- `FJ95`;
- `next_prompts.md`, Prompt 014;
- `OQ-117`;
- `OBL-C5-016`;
- `OBL-T001-023`;
- `ledgers/t001_candidate_inventory.md`;
- `ledgers/t001_residual.md`.

## Output target

FJ96 should:

- record accepted payload `PAY-T001-LIVE-CAND-AUDIT-AFTER-CAND005-2026-001`;
- classify all current `T-001` candidate-inventory rows as routed,
  calibration-only, placeholder, blocked / inactive, or live;
- decide whether any live non-routed row remains;
- if none remains, record the post-`FJ95` no-live-candidate blocker and
  future payload requirements;
- stop without creating `FJ97`.

## Definitions

**Definition.** A live non-routed `T-001` candidate row is a concrete
torsion-free one-relator candidate or family row which:

- is not already routed by a recorded repository route;
- is not calibration-only;
- is not source-routed or prior-art-blocked;
- is not a template placeholder;
- is not blocked / inactive by a branch decision;
- has a currently actionable proof obligation that can be advanced without
  adding a new payload.

**Definition.** `NLC-T001-002` is the post-`FJ95` no-live-candidate blocker:
after the `FJ95` demotion of `CAND-T001-005`, the current repository has no
live non-routed `T-001` candidate row.

**Warning.** `NLC-T001-002` is a project-state statement. It is not a theorem
about torsion-free one-relator groups and not evidence against
Farrell--Jones.

## Main work

### Accepted payload

| Field | FJ96 record |
| --- | --- |
| Payload ID | `PAY-T001-LIVE-CAND-AUDIT-AFTER-CAND005-2026-001` |
| Payload type | `PAY-T001-BLOCKER` |
| Target gate | Post-`FJ95` gate, `OQ-117`, and `OBL-C5-016` |
| Object | Internal audit of the current `T-001` candidate inventory after the `FJ95` demotion of `CAND-T001-005`. |
| Source status | No new external source checked; internal ledger audit only. |
| Stop condition | Stop after live-candidate audit and ledger update. Do not add a candidate, use external sources, reopen closed rows, or create `FJ97`. |

### Candidate classification table

| Row | FJ96 classification | Live non-routed? | Reason |
| --- | --- | --- | --- |
| `CAND-T001-001` | calibration-only / already non-residual | no | The row is the abelian calibration example already covered by the virtually solvable route; its finite-rank free-kernel data is not a new residual subtraction. |
| `CAND-T001-002` | routed | no | The row is already removed through the `FJ26` finite-rank free-by-cyclic route. |
| `CAND-T001-003` | routed family | no | The family is already removed through the `FJ26` finite-rank free-by-cyclic route after the `FJ34`/`FJ36` kernel-control bridge. |
| `CAND-T001-004` | source-routed / prior-art-blocked | no | `FJ88` routes \(G_{BS23}=BS(2,3)\) through `ER-015`; kernel control remains unnecessary for route status. |
| `CAND-T001-005` | blocked / inactive proof-target row | no | `FJ95` demotes the row after `FJ91`--`FJ94` record torsion-free status, Brown-positive finite generation, no named route/prior-art blocker, and no FJ83 eligibility. |
| `TPL-RB003-004-008` | template placeholder | no | The row has no mathematical candidate, presentation, family, route-output target, or proof obligation. |

### Decision

No current row remains live and non-routed after `FJ95`.

The repository still records unresolved global `T-001` work, but the current
candidate inventory does not contain a live proof target. Future `T-001`
candidate work requires a new accepted payload supplying one of:

- a concrete torsion-free one-relator candidate or family;
- finite-rank free-kernel identification for an existing row;
- a source-verified route bridge;
- new FJ83 weaker \(K_0\) / Cohen--Lyndon hypothesis data;
- a formulation comparison tied to a named candidate route;
- a prior-art object;
- an explicit reopening or target-pivot decision with a changed project
  object.

## Proposition

**Proposition.** After the `FJ95` demotion of `CAND-T001-005`, the current
repository contains no live non-routed `T-001` candidate row.

This is a finite internal ledger audit, not a Farrell--Jones theorem.

## Proof or verification

The verification is a finite check of the current candidate inventory.

`CAND-T001-001` is calibration-only and already covered by the virtually
solvable route. `CAND-T001-002` is routed through `FJ26`. `CAND-T001-003` is
routed through `FJ26` using the recorded `FJ34`/`FJ36` bridge.
`CAND-T001-004` is source-routed and prior-art-blocked by `FJ88` through
`ER-015`. `CAND-T001-005` is blocked / inactive by the `FJ95` branch
decision. `TPL-RB003-004-008` is a placeholder rather than a mathematical
candidate.

These are all current rows in `ledgers/t001_candidate_inventory.md`.
Therefore no live non-routed `T-001` candidate row remains.

## References

No external source was used in this module.

Internal references:

- `modules/cycle_003/FJ56_kernel_control_candidate_inventory.md`;
- `modules/cycle_003/FJ57_candidate_family_proof_attempt_or_obstruction_record.md`;
- `modules/cycle_005/FJ84_k0_cohen_lyndon_candidate_hypothesis_audit.md`;
- `modules/cycle_005/FJ89_live_candidate_audit_after_gbs23_closure.md`;
- `modules/cycle_005/FJ90_t001_candidate_intake_after_no_live_candidate.md`;
- `modules/cycle_005/FJ91_cand005_torsion_free_source_check.md`;
- `modules/cycle_005/FJ92_cand005_brown_bns_kernel_control.md`;
- `modules/cycle_005/FJ93_cand005_known_route_prior_art_audit.md`;
- `modules/cycle_005/FJ94_cand005_k0_cohen_lyndon_hypothesis_audit.md`;
- `modules/cycle_005/FJ95_cand005_branch_checkpoint_after_fj94.md`;
- `ledgers/t001_candidate_inventory.md`;
- `ledgers/t001_residual.md`;
- `ledgers/payload_intake_protocol.md`.

## Dependencies

This module depends on:

- `FJ56`;
- `FJ57`;
- `FJ84`;
- `FJ89`;
- `FJ90`;
- `FJ91`;
- `FJ92`;
- `FJ93`;
- `FJ94`;
- `FJ95`;
- `OQ-117`;
- `OBL-C5-016`;
- `OBL-T001-023`;
- `next_prompts.md`, Prompt 014.

## Results produced

This module produced:

- accepted payload record `PAY-T001-LIVE-CAND-AUDIT-AFTER-CAND005-2026-001`;
- completion of Prompt 014 in `next_prompts.md`;
- resolution of `OQ-117`;
- completion of `OBL-C5-016`;
- post-`FJ95` no-live-candidate blocker `NLC-T001-002`;
- new payload gate `OBL-C5-017`;
- new open question `OQ-118`;
- no new candidate row;
- no external source check;
- no residual subtraction;
- no global `T-001` theorem.

## Open questions generated

- `OQ-118`: Does the next queued formulation-safety prompt apply to any
  active candidate row after the post-`FJ95` no-live-candidate audit?

## Update to ledgers

After completion, update:

- `README.md`;
- `PROJECT_CHARTER.md`;
- `SCOPE_LEDGER.md`;
- `NOTATION_LEDGER.md`;
- `OPEN_QUESTIONS.md`;
- `ledgers/theorem_dependencies.md`;
- `ledgers/payload_intake_protocol.md`;
- `ledgers/t001_candidate_inventory.md`;
- `ledgers/t001_residual.md`;
- `AGENTS.md`;
- `next_prompts.md`.
