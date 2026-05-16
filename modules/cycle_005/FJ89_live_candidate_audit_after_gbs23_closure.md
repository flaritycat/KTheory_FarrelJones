# Module FJ89. Live-Candidate Audit After G_BS23 Closure

## Status

Completed

## Module type

Candidate-status verification / Project-governance audit /
Payload-instantiated module

## Problem

After `FJ88`, the row `CAND-T001-004` for
\[
G_{BS23}=\langle a,t\mid t a^2t^{-1}a^{-3}\rangle=BS(2,3)
\]
was routed through the Gandini--Meinert--Rueping graph-of-abelian-groups
route recorded as `ER-015`.

The accepted payload `PAY-T001-LIVE-CAND-AUDIT-2026-001` asks for a bounded
internal audit: determine whether any currently recorded `T-001` row remains
live, non-routed, and candidate-admissible after that closure. The module
must not introduce a new candidate, reopen \(G_{BS23}\), search externally,
or claim a Farrell--Jones theorem.

## Input

- `FJ54`;
- `FJ56`;
- `FJ57`;
- `FJ84`;
- `FJ86`;
- `FJ87`;
- `FJ88`;
- `OQ-110`;
- `OBL-C5-009`;
- `ledgers/payload_intake_protocol.md`;
- `ledgers/t001_candidate_inventory.md`;
- `ledgers/t001_residual.md`.

## Output target

FJ89 should:

- record the accepted FJ89 payload;
- classify all current `T-001` candidate-inventory rows as routed,
  calibration-only, placeholder, blocked, or live;
- decide whether any live non-routed row remains;
- if none remains, record the no-live-candidate blocker and the next payload
  requirements;
- stop without creating `FJ90`.

## Definitions

**Definition.** A live non-routed `T-001` candidate row is a concrete
torsion-free one-relator candidate or family row which:

- has a recorded presentation or family description;
- is not already routed by hyperbolic, CAT(0), virtually solvable,
  finite-index / `FJCw`, free-by-cyclic / hyperbolic-by-cyclic, or
  source-verified prior-art machinery;
- is not calibration-only;
- is not a template placeholder;
- has a route-output target or proof obligation that can be attacked by a
  bounded next module.

**Definition.** `NLC-T001-001` is the no-live-candidate blocker recorded by
FJ89: after the FJ88 closure of `CAND-T001-004`, the current repository has
no live non-routed `T-001` candidate row.

**Warning.** A no-live-candidate blocker is a project-state statement. It is
not a theorem about torsion-free one-relator groups and not evidence against
Farrell--Jones.

## Main work

### Accepted payload

| Field | FJ89 record |
| --- | --- |
| Payload ID | `PAY-T001-LIVE-CAND-AUDIT-2026-001` |
| Payload type | `PAY-T001-BLOCKER` |
| Target gates | `OQ-110` and `OBL-C5-009` |
| Object | Internal audit of the current `T-001` candidate inventory after the FJ88 route closure for `CAND-T001-004`. |
| Source status | No new external source checked; internal ledger audit only. |
| Repository objects changed | `modules/cycle_005/FJ89_live_candidate_audit_after_gbs23_closure.md`; `ledgers/payload_intake_protocol.md`; `ledgers/t001_candidate_inventory.md`; `ledgers/t001_residual.md`; `OPEN_QUESTIONS.md`; `ledgers/theorem_dependencies.md`; `README.md`; `PROJECT_CHARTER.md`; `SCOPE_LEDGER.md`; `NOTATION_LEDGER.md`. |
| Stop condition | Stop after the live-candidate audit and ledger update. Do not create `FJ90`. Do not search externally. Do not add a new mathematical candidate. |

### Candidate classification table

| Row | FJ89 classification | Live non-routed? | Reason |
| --- | --- | --- | --- |
| `CAND-T001-001` | calibration-only / already non-residual | no | The row is the abelian calibration example already covered by the virtually solvable route; `FJ26` data is redundant for residual subtraction. |
| `CAND-T001-002` | routed | no | The row is already removed through the `FJ26` finite-rank free-by-cyclic route. |
| `CAND-T001-003` | routed family | no | The family is already removed through the `FJ26` finite-rank free-by-cyclic route after the `FJ34`/`FJ36` kernel-control bridge. |
| `CAND-T001-004` | source-routed / prior-art-blocked | no | `FJ88` routes \(G_{BS23}=BS(2,3)\) through `ER-015`; kernel control is uncomputed but unnecessary for this route status. |
| `TPL-RB003-004-008` | template placeholder | no | The row has no mathematical candidate, presentation, family, route-output target, or proof obligation. |

### Decision

No current row remains live and non-routed after `FJ88`.

The repository may still contain unresolved global work on `T-001`, but the
current candidate inventory does not contain a concrete row that can support
the next proof module. A future module may be created only after a new
accepted payload supplies one of the following:

- a concrete torsion-free one-relator candidate or family;
- an exact bridge lemma with hypotheses and a changed project object;
- a concrete computation for an existing row that changes its route status;
- an exact source theorem or formulation comparison;
- a prior-art object that changes a candidate, residual bucket, open
  question, or proof obligation.

## Proposition / Theorem / Conjecture / Example

**Proposition.** After the FJ88 closure of `CAND-T001-004`, the current
repository contains no live non-routed `T-001` candidate row.

This is a finite internal ledger audit, not a Farrell--Jones theorem.

## Proof or verification

The verification is a finite check of the current candidate inventory.

`CAND-T001-001` is calibration-only and already covered by the virtually
solvable route. `CAND-T001-002` is routed through `FJ26`. `CAND-T001-003`
is routed through `FJ26` using the recorded `FJ34`/`FJ36` bridge.
`CAND-T001-004` is source-routed and prior-art-blocked by `FJ88` through
`ER-015`. `TPL-RB003-004-008` is a placeholder rather than a mathematical
candidate.

These are all current rows in `ledgers/t001_candidate_inventory.md`.
Therefore no live non-routed `T-001` candidate row remains.

## References

No external source was used in this module.

Internal references:

- `modules/cycle_003/FJ54_residual_bucket_checkpoint_after_rb006.md`;
- `modules/cycle_003/FJ56_kernel_control_candidate_inventory.md`;
- `modules/cycle_003/FJ57_candidate_family_proof_attempt_or_obstruction_record.md`;
- `modules/cycle_005/FJ84_k0_cohen_lyndon_candidate_hypothesis_audit.md`;
- `modules/cycle_005/FJ86_t001_candidate_intake_audit.md`;
- `modules/cycle_005/FJ87_gbs23_torsion_free_hnn_check.md`;
- `modules/cycle_005/FJ88_gbs23_known_route_prior_art_audit.md`;
- `ledgers/t001_candidate_inventory.md`;
- `ledgers/t001_residual.md`;
- `ledgers/payload_intake_protocol.md`.

## Dependencies

This module depends on:

- `FJ54`;
- `FJ56`;
- `FJ57`;
- `FJ84`;
- `FJ86`;
- `FJ87`;
- `FJ88`;
- `OQ-110`;
- `OBL-C5-009`.

## Results produced

This module produced:

- accepted payload record `PAY-T001-LIVE-CAND-AUDIT-2026-001`;
- first-pass resolution of `OQ-110`;
- completion of `OBL-C5-009` for FJ89;
- no-live-candidate blocker `NLC-T001-001`;
- proof obligation `OBL-C5-010`, blocking `FJ90` until a new accepted
  payload is recorded;
- open question `OQ-111`, asking which accepted payload, if any, should
  instantiate `FJ90`;
- no new candidate row;
- no external source check;
- no residual subtraction;
- no global `T-001` theorem.

## Open questions generated

- `OQ-111`: Which accepted payload, if any, should instantiate `FJ90` after
  the FJ89 no-live-candidate audit?

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
- `ledgers/t001_residual.md`.
