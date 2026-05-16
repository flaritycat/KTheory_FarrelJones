# Module FJ62. Active Blocker Pruning for T-001

## Status

Completed

## Module type

Governance checkpoint / Blocker triage / Attack surface

## Problem

`FJ61` records `OBL-T001-008`, the candidate-intake gate for `T-001`. The
next task is to prune the accumulated open questions, residual buckets, and
proof obligations so that early cycle 004 has a small active blocker list
rather than a long historical archive.

`FJ62` must not verify a new external source. It should decide which
blockers are active for candidate intake, which are deferred, which are
historical trail markers, and which may matter only if the project reaches a
target-pivot comparison.

## Input

- `FJ61`, T-001 Candidate-Intake Reset and Exit Criteria;
- `OQ-084`;
- `OPEN_QUESTIONS.md`;
- `SCOPE_LEDGER.md`;
- `ledgers/t001_candidate_inventory.md`;
- `ledgers/t001_residual.md`;
- `ledgers/t001_kernel_recognition.md`;
- `ledgers/open_group_classes.md`;
- `AGENTS.md`;
- `PROJECT_CHARTER.md`.

## Output target

A pruned blocker map:

- preserve only the blockers that can change cycle-004 candidate intake;
- move source-only or no-application items to deferred status;
- mark resolved route decisions as historical trail markers;
- identify possible pivot-comparison inputs without pivoting yet;
- create the next exact data-acquisition obligation for `FJ63`.

## Definitions

**Definition.** An active candidate-intake blocker is a missing item that
prevents the next bounded module from selecting a candidate, bridge,
computation, source payload, prior-art blocker, pause recommendation, or
pivot comparison.

**Definition.** A deferred foundation is a real mathematical or source
question that should not drive the next module because it has no
candidate-admissible row or exact project object attached.

**Definition.** A historical trail marker is a resolved or superseded
open-question or proof-obligation item preserved for provenance, not for
immediate action.

**Definition.** A pivot-comparison input is a project fact that may matter if
`T-001` is paused at a later branch checkpoint, but does not itself justify a
target pivot now.

**Warning.** Moving a blocker to deferred or historical status is not a
mathematical solution. It only records that the blocker is not actionable for
the next candidate-intake module.

## Main work

### Active blockers preserved for FJ63

| Active blocker | Source | Why it remains active | FJ63 requirement |
|---|---|---|---|
| No candidate-admissible row | `FJ56`, `FJ57`, `FJ61`, `OBL-T001-003`, `OBL-T001-004`, `OBL-T001-008` | Without a named non-routed presentation or family, `T-001` cannot become a proof attempt. | Select one data-acquisition packet aimed at a candidate row, or record that no such packet exists. |
| No exact bridge or computation target | `FJ43`, `FJ55`, `FJ58`, `OBL-T001-001`, `OBL-T001-002`, `OBL-T001-005` | Hierarchy, BNS, kernel, finite-index, and geometric lanes remain unusable without a checkable route-output target. | Name one bridge or computation target, or keep the lane inactive. |
| No exact source payload | `FJ59`, `FJ60`, `OBL-T001-006`, `OBL-T001-007` | A source name cannot reopen the weaker consequence lane or support a route claim. | Name an exact theorem payload only if it changes a project object; otherwise do not select a source task. |
| No prior-art comparison object | `FJ57`, `FJ58`, `FJ61` | Novelty language is blocked because there is no candidate or theorem payload to compare. | Preserve prior-art checking as a required field, not as a standalone source module. |
| No branch-ready target decision | `reflections/cycle_003_reflection.md`, `FJ61` | `T-001` should not be paused or pivoted before the intake gate is tested once. | Send the project to candidate-data acquisition before pivot comparison. |

### Deferred foundations

| Deferred item | Source | Deferral reason | Reactivation condition |
|---|---|---|---|
| Bieri theorem-use upgrade | `FJ42`, `OQ-063` | No candidate currently needs a Bieri theorem statement; primary theorem text remains unchecked. | Reactivate only with a candidate or finiteness bridge requiring the exact theorem. |
| Karrass--Solitar infinite-dihedral cleanup | `FJ39`, `FJ40`, `OQ-060` | No source-ready finitely presented-kernel candidate currently needs the cleanup. | Reactivate only with an application case. |
| `RB-005` finite-index / `FJCw` application | `FJ47`--`FJ50`, `OQ-069`--`OQ-071` | The bridge exists only for `FJCw`, and no `T-001` case is `FJCw-ready`. | Reactivate only with a named finite-index subgroup case and version-safe input. |
| `RB-006` compact-special / CAT(0)-looking lane | WIP / provisional `FJ53`, `FJ54` | Current Louder--Wilton path is hyperbolic-overlap only. | Reactivate only with a genuinely non-hyperbolic compact-special, CAT(0), or FJ bridge. |
| `RB-007` virtually solvable recognition | `FJ25`, `FJ58` | No concrete virtually-solvable-looking family is attached to a candidate row. | Reactivate only with a named family or recognition theorem payload. |
| Weaker \(K_0\) / Cohen--Lyndon lane | `FJ59`, `FJ60`, `OQ-024`, `OQ-081` | No exact source payload is recorded. | Reactivate only with theorem statement, hypotheses, formulation level, source status, and project object changed. |

### Historical trail markers

| Historical item | Reason |
|---|---|
| `OQ-064`--`OQ-071` | These record the `RB-004` and `RB-005` route-delta decisions already made in cycle 003. |
| `OQ-072`--`OQ-075` | These record the `RB-006` source-boundary and demotion sequence. |
| `OQ-076`--`OQ-079` | These record the hybrid packet selection and its candidate-production obstruction. |
| `OQ-080`--`OQ-081` | These record the inactive weaker consequence lane. |
| `OQ-082`--`OQ-083` | These record the cycle-003 reflection and `FJ61` intake reset handoff. |
| `CAND-T001-001`--`CAND-T001-003` | These remain useful calibration or routed examples, not active residual candidates. |
| `TPL-RB003-004-008` | This remains a template placeholder and not a mathematical candidate. |

### Pivot-comparison inputs

| Pivot input | Current status | Non-use warning |
|---|---|---|
| Artin groups | Partially mapped in `FJ18`; deferred by `FJ20` | Do not pivot by inertia; require deliberate target-selection criteria. |
| Automatic / biautomatic groups | Listed in the open group classes ledger | No current source-verified target packet is recorded. |
| Thompson-type groups | Listed in the open group classes ledger | No current source-verified target packet is recorded. |
| Pause `T-001` | Allowed by `FJ61` if intake fails | A pause is not a negative theorem and not a solution of `T-001`. |

### Pruned active blocker list

After pruning, early cycle 004 has only three active blocker classes:

1. candidate object blocker: no candidate-admissible row is present;
2. route-data blocker: no exact bridge, computation, or source payload is
   attached to a candidate or residual lane;
3. decision blocker: no pause or pivot comparison should occur until the
   candidate-data acquisition packet has been tried.

This is narrow enough for the next module.

### New proof obligation

**Obligation OBL-T001-009.** Exact data-acquisition packet requirement.

`FJ63` must select exactly one of the following as its output target:

- candidate-row acquisition;
- bridge-lemma acquisition;
- concrete computation acquisition;
- exact source-payload acquisition;
- prior-art blocker acquisition;
- target-pause trigger;
- target-pivot comparison trigger.

The selected packet must state the project object changed and the failure
condition. A broad source survey does not satisfy this obligation.

## Proposition / Theorem / Conjecture / Example

**Proposition.** After the `FJ62` pruning, the only active `T-001` blockers
for the next module are candidate-object acquisition, route-data acquisition,
and the branch decision about whether the acquisition attempt succeeds.

**Proof.** The remaining `T-001` route work after `FJ61` is controlled by
`OBL-T001-008`. Existing concrete candidates are calibration-only or already
routed. The Bieri, Karrass--Solitar, finite-index, `RB-006`, virtually
solvable, and weaker-consequence lanes have no candidate-admissible row or
exact source payload attached. The route-delta questions from cycle 003 have
already been resolved as pauses, demotions, or obstructions. Thus only the
choice of an exact data-acquisition packet remains active for `FJ63`.

**Route decision.** `FJ62` resolves `OQ-084`, records `OBL-T001-009`, and
selects `FJ63`, Candidate-Data Acquisition Packet.

**Warning.** `FJ62` proves no new Farrell--Jones case, proves no theorem
about torsion-free one-relator groups, does not finalize WIP / provisional
`FJ53`, and makes no residual subtraction.

## Proof or verification

Verification was internal to the repository:

1. Checked `OPEN_QUESTIONS.md` and `SCOPE_LEDGER.md` for the active
   `OQ-084` handoff and the resolved cycle-003 questions.
2. Checked `ledgers/t001_candidate_inventory.md` for `OBL-T001-001` through
   `OBL-T001-008` and current candidate rows.
3. Checked `ledgers/t001_residual.md` for dormant residual buckets.
4. Checked `ledgers/t001_kernel_recognition.md` for dormant Brown/BNS
   computation status.
5. Checked `AGENTS.md` and `PROJECT_CHARTER.md` for the anti-source-summary
   instruction.
6. No new external source was checked.

## References

No new external source was used in this module.

Internal references:

- `modules/cycle_004/FJ61_t001_candidate_intake_reset_exit_criteria.md`
- `OPEN_QUESTIONS.md`
- `SCOPE_LEDGER.md`
- `ledgers/t001_candidate_inventory.md`
- `ledgers/t001_residual.md`
- `ledgers/t001_kernel_recognition.md`
- `ledgers/open_group_classes.md`
- `AGENTS.md`
- `PROJECT_CHARTER.md`

## Dependencies

This module depends on:

- `FJ61`;
- `OQ-084`;
- `OBL-T001-008`;
- `OPEN_QUESTIONS.md`;
- `SCOPE_LEDGER.md`;
- `ledgers/t001_candidate_inventory.md`;
- `ledgers/t001_residual.md`;
- `ledgers/t001_kernel_recognition.md`.

## Results produced

This module produced:

- a first-pass resolution of `OQ-084`;
- a pruned active-blocker list for early cycle 004;
- `OBL-T001-009`, the exact data-acquisition packet requirement for `FJ63`;
- selection of `FJ63`, Candidate-Data Acquisition Packet;
- no new `ER-*` result;
- no concrete residual subtraction.

## Open questions generated

- `OQ-085`: Which exact data-acquisition packet should `FJ63` select after
  active blocker pruning?

## Update to ledgers

After completion, update:

- `README.md` and `PROJECT_CHARTER.md` for completed `FJ62` and next `FJ63`;
- `SCOPE_LEDGER.md` for the `OQ-084` resolution and new `OQ-085`;
- `OPEN_QUESTIONS.md` for `OQ-084` and `OQ-085`;
- `NOTATION_LEDGER.md` for blocker-pruning terms and `OBL-T001-009`;
- `ledgers/t001_candidate_inventory.md` for the new obligation;
- `ledgers/t001_residual.md`, `ledgers/t001_kernel_recognition.md`,
  `ledgers/theorem_dependencies.md`, and `ledgers/open_group_classes.md` for
  the current target update;
- `references/papers_to_read.md` and `AGENTS.md` for the next handoff.
