# Module FJ57. Candidate Family Proof Attempt or Obstruction Record

## Status

Completed

## Module type

Failed attempt / Obstruction record / Route decision

## Problem

`FJ56` records `OBL-T001-003`: the current candidate inventory has no live
non-routed kernel-control candidate for the selected `RB-003` +
`RB-004`/`RB-008` hybrid packet.

`FJ57` must decide whether the repository can promote a non-routed candidate
family into the inventory and attempt its route bridge, or whether the
honest output is a no-candidate obstruction. It must not fabricate a new
group family.

## Input

- `FJ40`, finitely presented-kernel test selection;
- `FJ43`, route-delta checkpoint for the BNS/Bieri/Karrass--Solitar source
  cluster;
- `FJ48`, `FJCw` application audit;
- `FJ50`, `RB-005` route-delta checkpoint;
- `FJ53`, WIP / provisional \(\pi(w)>2\) hyperbolic-overlap checkpoint;
- `FJ54`, residual-bucket checkpoint after `RB-006`;
- `FJ55`, hierarchy-to-FJ bridge test;
- `FJ56`, kernel-control candidate inventory;
- `OQ-078`;
- `ledgers/t001_candidate_inventory.md`;
- `ledgers/t001_kernel_recognition.md`;
- `ledgers/t001_residual.md`.

## Output target

A proof-attempt decision:

- either promote one repository-supported non-routed candidate and state its
  proof obligation;
- or record a precise obstruction explaining why no candidate-family proof
  attempt can be made honestly now;
- update the candidate and residual ledgers;
- identify the next module without reopening a passive source-summary lane.

## Definitions

**Definition.** A candidate-promotion attempt is a bounded check asking
whether existing repository data already contains a named group, named
family, or named bridge lemma that can be moved into
`ledgers/t001_candidate_inventory.md` as a live non-routed candidate.

**Definition.** A no-candidate endpoint is a project-state obstruction: the
selected attack packet has reached the point where further proof work would
require a new candidate, a new bridge lemma, or a new prior-art comparison.
It is not a mathematical nonexistence theorem.

**Warning.** A template row is not a candidate. A source cluster is not a
candidate. A residual bucket is not a candidate unless it contains a named
presentation, family, or bridge obligation whose hypotheses can be tested.

## Main work

### Candidate-promotion audit

| Possible promotion source | Repository support | Missing input | FJ57 decision |
|---|---|---|---|
| `CAND-T001-001` | recorded kernel \(F_1\) and calibration role in `FJ31`/`FJ56` | none, but already non-residual | do not promote; calibration only |
| `CAND-T001-002` | \(G_{2,3}\), Brown-positive check, and \(\ker(\chi)\cong F_2\) in `FJ33`/`FJ56` | none, but already routed through `FJ26` | do not promote; already routed |
| `CAND-T001-003` | \(G_{p,q}\)-family with finite-rank free kernel by `FJ36`/`FJ56` | none, but already routed through `FJ26` | do not promote; already routed |
| `TPL-RB003-004-008` | template row only | presentation, torsion-free status, route output, kernel data, prior-art comparison | do not promote; not a candidate |
| Non-Brown finitely presented-kernel lane | `FJ40` audits the lane | no source-ready non-Brown finitely presented normal kernel | do not promote |
| Direct BNS lane | `FJ41` verifies the theorem map; `FJ43` pauses source-cluster continuation | no \(\Sigma(G)\)-membership computation for a non-routed candidate | do not promote |
| Karrass--Solitar infinite-dihedral cleanup | `FJ39` verifies the bridge source; `FJ48` finds no current application | no concrete source-ready candidate and no formulation-safe finite-index route for a row | do not promote |
| `RB-005` finite-index / `FJCw` lane | `FJ50` pauses the lane after `FJ47`--`FJ49` | no named `FJCw`-ready or direct CAT(0)-finite-extension candidate | do not promote |
| `RB-006` Louder--Wilton lane | WIP / provisional `FJ53` records only hyperbolic overlap | no concrete word \(w\) checked and no non-hyperbolic bridge | do not promote |
| Weaker \(K_0\) / Cohen--Lyndon lane | flagged by `FJ54` as lower priority | no candidate row and no repository-verified theorem payload | do not promote in `FJ57` |

### Failed attempt

**Failed attempt.** Try to promote a candidate family for a proof attempt
from the current repository state.

**Failure reason.** Every available named candidate is already route-exhausted,
and every remaining residual lane lacks the minimum data required by the
candidate intake checklist: a presentation or family, route-output target,
kernel or bridge data, and prior-art risk statement.

This is a useful failure. It prevents the project from pretending that a
proof attempt exists when the missing object is a candidate.

### Obstruction record

**Obstruction OBL-T001-004.** The selected `RB-003` + `RB-004`/`RB-008`
hybrid packet is blocked at the candidate-production stage.

To reactivate the packet, a later module must supply at least one of:

- a repository-supported non-routed presentation or family;
- a concrete BNS or Brown computation outside the already routed rows;
- a source-verified bridge lemma producing a route-output target for a named
  residual row;
- a prior-art comparison showing that a candidate is not already absorbed by
  hyperbolic, finite-dimensional CAT(0), virtually solvable, finite-index /
  `FJCw`, or finite-rank free-by-cyclic machinery.

### Route decision

`FJ57` closes the current hybrid packet as blocked, not abandoned. The
candidate inventory remains active as an intake ledger, but the next module
should not continue the same packet unless it can name a new candidate or
bridge.

The next useful module is:

`FJ58`: Post-Hybrid Candidate-Production Checkpoint.

Its job should be to decide which candidate-production lane, if any, can be
made legitimate without violating the stop conditions from `FJ54`--`FJ57`.

## Proposition / Theorem / Conjecture / Example

**Proposition.** In the current repository state, `FJ57` cannot honestly
perform a candidate-family proof attempt for the selected hybrid packet.

**Proof.** `FJ56` proves that all current candidate-inventory rows are either
route-exhausted or placeholders. The promotion audit above checks the
remaining repository lanes that could supply a candidate. `FJ40` supplies no
non-Brown source-ready finitely presented-kernel example. `FJ43` leaves the
BNS/Bieri source cluster paused until a candidate-ready route appears.
`FJ48` and `FJ50` leave the finite-index lane without an application case.
WIP / provisional `FJ53` leaves the Louder--Wilton lane as hyperbolic
overlap with no concrete word checked. Therefore no repository-supported
non-routed candidate is available for a proof attempt.

**Route decision.** `FJ57` resolves `OQ-078` by recording `OBL-T001-004` and
sending the project to `FJ58`, Post-Hybrid Candidate-Production Checkpoint.

**Warning.** This is not a theorem that no such candidate exists. It is a
repository-state obstruction.

## Proof or verification

Verification was internal to the repository:

1. Checked the candidate inventory after `FJ56`.
2. Checked the current residual ledger handoff.
3. Checked the no-candidate decisions from `FJ40`, `FJ43`, `FJ48`, `FJ50`,
   and WIP / provisional `FJ53`.
4. Checked that no current row satisfies the candidate intake checklist.
5. No new external source was checked.

## References

No new external source was checked in this module.

Internal references:

- `modules/cycle_002/FJ40_finitely_presented_kernel_test_selection.md`
- `modules/cycle_003/FJ43_route_delta_checkpoint.md`
- `modules/cycle_003/FJ48_rb005_fjcw_application_audit.md`
- `modules/cycle_003/FJ50_rb005_route_delta_checkpoint.md`
- `modules/cycle_003/FJ53_pi_w_hyperbolic_overlap_checkpoint.md`
- `modules/cycle_003/FJ54_residual_bucket_checkpoint_after_rb006.md`
- `modules/cycle_003/FJ55_primitive_extension_hierarchy_to_fj_bridge_test.md`
- `modules/cycle_003/FJ56_kernel_control_candidate_inventory.md`
- `ledgers/t001_candidate_inventory.md`
- `ledgers/t001_kernel_recognition.md`
- `ledgers/t001_residual.md`

## Dependencies

This module depends on:

- `FJ40`;
- `FJ43`;
- `FJ48`;
- `FJ50`;
- `FJ53`;
- `FJ54`;
- `FJ55`;
- `FJ56`;
- `OQ-078`;
- `ledgers/t001_candidate_inventory.md`;
- `ledgers/t001_residual.md`.

## Results produced

This module produced:

- a first-pass resolution of `OQ-078`;
- `OBL-T001-004`, the candidate-production obstruction for the selected
  hybrid packet;
- a route decision to close the current `RB-003` + `RB-004`/`RB-008` hybrid
  packet as blocked until a real candidate or bridge appears;
- a decision to continue with `FJ58`, Post-Hybrid Candidate-Production
  Checkpoint;
- no new `ER-*` result;
- no concrete residual subtraction.

## Open questions generated

- `OQ-079`: Which candidate-production lane, if any, should replace the
  blocked `RB-003` + `RB-004`/`RB-008` hybrid packet?

## Update to ledgers

After completion, update:

- `README.md` and `PROJECT_CHARTER.md` for completed `FJ57` and next `FJ58`;
- `SCOPE_LEDGER.md` for the `OQ-078` resolution and new `OQ-079`;
- `OPEN_QUESTIONS.md` for `OQ-078` and `OQ-079`;
- `NOTATION_LEDGER.md` for no-candidate endpoint and `OBL-T001-004`;
- `ledgers/t001_candidate_inventory.md` for the `FJ57` obstruction;
- `ledgers/t001_residual.md`, `ledgers/t001_kernel_recognition.md`,
  `ledgers/theorem_dependencies.md`, and `ledgers/open_group_classes.md` for
  the current target update;
- `references/papers_to_read.md` for the next task.
