# Payload Intake Protocol

## Status

Created by `FJ82`.

No external source was checked for this ledger.

## Use rules

- Do not start a numbered module from a source name, target name, residual
  bucket label, or general preference to continue.
- Accept a payload only when it names the changed repository object and a stop
  condition.
- Preserve formulation labels: simplified ring-coefficient FJ, coefficient
  K-theory FJC, full \(\mathcal{FJ}\), `FJCw`, and `FICwF` are not
  interchangeable without a checked comparison.
- Do not count hyperbolic, CAT(0), virtually solvable, finite-index,
  free-by-cyclic, or hyperbolic-by-cyclic overlap as a new residual
  subtraction.
- Do not finalize WIP / provisional `FJ53` without a genuinely non-hyperbolic
  CAT(0), compact-special, or FJ bridge, or another recorded subtractive
  payload.

## Accepted payload types

| Payload type | Minimum content | Changed project object | Stop condition |
| --- | --- | --- | --- |
| `PAY-T001-CAND` | A candidate-admissible `T-001` row with presentation, relator status, torsion-free status, residual bucket, route-output target, formulation-safety note, prior-art risk, and next proof obligation | `ledgers/t001_candidate_inventory.md` | Stop if the row is a placeholder, calibration example, already routed case, or lacks a route-output target. |
| `PAY-T001-BRIDGE` | Exact bridge lemma, computation, or source theorem that changes a `T-001` candidate, residual bucket, or route-output status | `ledgers/t001_candidate_inventory.md`, `ledgers/t001_residual.md`, or `ledgers/t001_kernel_recognition.md` | Stop if hypotheses, formulation level, or prior-art comparison are missing. |
| `PAY-ARTIN` | Named Artin graph, graph family, subclass, source theorem, bridge object, formulation label, prior-art-overlap note, and changed project object | `ledgers/artin_subclass_gap_inventory.md` or `ledgers/open_group_classes.md` | Stop if the item is merely "all Artin groups" or an unnamed outside subclass. |
| `PAY-FND` | Exact foundational source payload with current proof/candidate/route need, changed project object, source status, and stop condition | `NOTATION_LEDGER.md`, `ledgers/theorem_dependencies.md`, or a module depending on the convention | Stop if the item is broad background or a bibliography-only task. |
| `PAY-FORM` | Exact formulation-comparison payload for coefficient K-theory, full \(\mathcal{FJ}\), `FJCw`, `FICwF`, or finite-index inheritance | `NOTATION_LEDGER.md`, `ledgers/inheritance_properties.md`, or `ledgers/theorem_dependencies.md` | Stop if the comparison would be used without exact hypotheses. |
| `PAY-FJ53-RB006` | A genuinely non-hyperbolic CAT(0), compact-special, or FJ bridge for the `RB-006` line, or another recorded reason the route is subtractive | `modules/cycle_003/FJ53_pi_w_hyperbolic_overlap_checkpoint.md`, `ledgers/t001_residual.md`, or `ledgers/t001_candidate_inventory.md` | Stop if the payload only repeats hyperbolic-route overlap. |
| `PAY-PRIOR` | Exact prior-art blocker or comparison object tied to a candidate, route claim, or target-pivot decision | The relevant candidate, route, or open-question ledger | Stop if no candidate, theorem payload, or route claim is named. |

## Rejected payload forms

| Rejected form | Reason |
| --- | --- |
| Source title only | Does not identify exact theorem, hypotheses, formulation level, or changed project object. |
| Target name only | Does not satisfy a reactivation gate. |
| Residual bucket label only | Does not provide candidate, bridge, computation, source payload, or obstruction. |
| Broad source summary | Risks decorative bibliography without mathematical progress. |
| Theorem name without statement and hypotheses | Not proof-sensitive enough for route use. |
| Hyperbolic-overlap restatement for `RB-006` | Not a new residual subtraction. |
| Placeholder candidate row | Not a mathematical candidate. |

## Intake record template

Use this template before instantiating a future numbered module.

| Field | Entry |
| --- | --- |
| Payload ID |  |
| Date recorded |  |
| Payload type |  |
| Target gate |  |
| Candidate, source, bridge, computation, or blocker |  |
| Exact statement or object |  |
| APA citation if external source is used |  |
| Source-status label |  |
| Hypotheses and formulation level |  |
| Repository object changed |  |
| Success criterion |  |
| Failure criterion |  |
| Stop condition |  |
| Accepted? |  |
| Follow-up module if accepted |  |

## Current payload inventory

| Payload ID | Type | Status | Reason |
| --- | --- | --- | --- |
| `PAYLOAD-NONE-001` | none | no accepted payload | `FJ82` checks the current repository state after `FJ81` and finds no candidate, source, bridge, computation, formulation comparison, prior-art blocker, or non-hyperbolic `RB-006` bridge satisfying this protocol. |

## Current project state

The project is in `C5-PAUSE-001`, a payload-gated pause.

No `FJ83` module is selected. A future `FJ83` may be created only after an
accepted payload row is added above or an equivalent accepted payload is
recorded in the relevant target ledger.
