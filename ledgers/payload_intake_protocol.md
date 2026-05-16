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
| `PAYLOAD-NONE-001` | none | historical no-payload record | `FJ82` checked the current repository state after `FJ81` and found no candidate, source, bridge, computation, formulation comparison, prior-art blocker, or non-hyperbolic `RB-006` bridge satisfying this protocol. |
| `PAY-T001-K0-CL-2025-001` | `PAY-T001-BRIDGE` | accepted for `FJ83` only | Exact weaker \(K_0\) / Cohen--Lyndon source payload located for `OBL-C5-003`, `OBL-T001-013`, `OQ-081`, and `OBL-T001-007`; accepted only for source-hypothesis verification and not for full `T-001` or residual subtraction. |

## Accepted intake records

### `PAY-T001-K0-CL-2025-001`

| Field | Entry |
| --- | --- |
| Payload ID | `PAY-T001-K0-CL-2025-001` |
| Date recorded | 2026-05-16 |
| Payload type | `PAY-T001-BRIDGE` |
| Target gate | `OBL-C5-003` and `OBL-T001-013`, with specific connection to the inactive weaker \(K_0\) / Cohen--Lyndon lane from `OQ-081` and `OBL-T001-007`. |
| Candidate, source, bridge, computation, or blocker | Jaikin-Zapirain, A., Linton, M., & Sanchez-Peralta, P. (2025). *Group pairs, coherence and Farrell-Jones Conjecture for K0*. arXiv:2510.23518. |
| Exact statement or object | Source-level payload for the claim that groups admitting a Cohen--Lyndon presentation satisfy the source's Farrell--Jones Conjecture for \(K_0\). FJ83 must check Conjecture 1, Theorem 1.7, the more general group-pair K0 theorem, their hypotheses, and the relation to the project's `T-001` weaker-consequence lane. |
| APA citation if external source is used | Jaikin-Zapirain, A., Linton, M., & Sanchez-Peralta, P. (2025). *Group pairs, coherence and Farrell-Jones Conjecture for K0* (arXiv:2510.23518v2). arXiv. https://arxiv.org/abs/2510.23518. https://doi.org/10.48550/arXiv.2510.23518. |
| Source-status label | external source located; exact theorem and hypotheses checked at first-pass level in `FJ83`; not promoted to established result. |
| Hypotheses and formulation level | Weaker \(K_0\)-level Farrell--Jones / projective-class-group formulation only. Do not treat as coefficient K-theory FJC, full FJ, `FJCw`, `FICwF`, or a `T-001` residual subtraction. FJ83 must verify torsion-free, regular-ring, Cohen--Lyndon presentation, group-pair, normalizer, finite cohomological dimension, and coherent group-ring hypotheses before any ledger promotion. |
| Repository object changed | `ledgers/payload_intake_protocol.md`; `OPEN_QUESTIONS.md`, `OQ-081` and `OQ-104`; `ledgers/t001_candidate_inventory.md`; `ledgers/t001_residual.md`; `ledgers/source_status.md`; `ledgers/theorem_dependencies.md`; `BIBLIOGRAPHY.md`; `references/papers_to_read.md`; `README.md`; `PROJECT_CHARTER.md`; `SCOPE_LEDGER.md`; `NOTATION_LEDGER.md`; `AGENTS.md`. |
| Success criterion | FJ83 verifies the source statement, hypotheses, and formulation level, then records that `OQ-081` changes from "no exact source payload available" to exact weaker \(K_0\) / Cohen--Lyndon source payload first-pass verified. If promoted later, the project must record explicitly that this is not full `T-001` and not a residual subtraction. |
| Failure criterion | FJ83 cannot verify the exact theorem text, cannot connect the K0 group-pair theorem to the project's `T-001` weaker-consequence lane, finds missing hypotheses, or finds that the result is only a broad source summary with no project-object change. |
| Stop condition | Stop after the source-hypothesis audit and ledger update. Do not start a new general one-relator survey. Do not claim Farrell--Jones for all torsion-free one-relator groups. Do not create `FJ84` unless a new accepted payload is recorded. |
| Accepted? | Yes, for FJ83 source-payload verification only. |
| Follow-up module if accepted | `modules/cycle_005/FJ83_k0_cohen_lyndon_payload_verification.md` |

## Rejected intake attempts

| Intake ID | Date recorded | Request or object | Status | Reason | Follow-up |
| --- | --- | --- | --- | --- | --- |
| `REJECTED-PAYLOAD-001` | 2026-05-16 | "Continue the project charter." | rejected / not an accepted payload | The request gives a general preference to continue but does not name a candidate, exact source theorem, bridge lemma, computation, formulation comparison, prior-art blocker, changed repository object, or stop condition. | Historical record: this request did not instantiate `FJ83`; later accepted payload `PAY-T001-K0-CL-2025-001` did. |
| `REJECTED-PAYLOAD-002` | 2026-05-16 | "Continue" | rejected / not an accepted payload | After `FJ83`, this request gives only a general preference to continue. It does not name a new accepted payload, changed repository object, success criterion, failure criterion, or stop condition. | Keep `OQ-105` open; do not instantiate `FJ84`. |
| `REJECTED-PAYLOAD-003` | 2026-05-16 | "Continue" | rejected / not an accepted payload | Repeated generic continuation request after `REJECTED-PAYLOAD-002`; still no new accepted payload, changed repository object, success criterion, failure criterion, or stop condition. | Keep `OQ-105` open; do not instantiate `FJ84`. |
| `REJECTED-PAYLOAD-004` | 2026-05-16 | "Continue" | rejected / not an accepted payload | Repeated generic continuation request after `REJECTED-PAYLOAD-003`; still no new accepted payload, changed repository object, success criterion, failure criterion, or stop condition. | Keep `OQ-105` open; do not instantiate `FJ84`. |
| `REJECTED-PAYLOAD-005` | 2026-05-16 | "Continue" | rejected / not an accepted payload | Repeated generic continuation request after `REJECTED-PAYLOAD-004`; still no new accepted payload, changed repository object, success criterion, failure criterion, or stop condition. | Keep `OQ-105` open; do not instantiate `FJ84`. |
| `REJECTED-PAYLOAD-006` | 2026-05-16 | "Continue" | rejected / not an accepted payload | Repeated generic continuation request after `REJECTED-PAYLOAD-005`; still no new accepted payload, changed repository object, success criterion, failure criterion, or stop condition. | Keep `OQ-105` open; do not instantiate `FJ84`. |
| `REJECTED-PAYLOAD-007` | 2026-05-16 | "Continue" | rejected / not an accepted payload | Repeated generic continuation request after `REJECTED-PAYLOAD-006`; still no new accepted payload, changed repository object, success criterion, failure criterion, or stop condition. | Keep `OQ-105` open; do not instantiate `FJ84`. |

## Current project state

`C5-PAUSE-001` was exited for the accepted payload
`PAY-T001-K0-CL-2025-001`, which instantiated `FJ83`.

After `FJ83`, no `FJ84` module is selected. A future `FJ84` may be created
only after a new accepted payload row is added above or an equivalent
accepted payload is recorded in the relevant target ledger.

The latest intake attempt, `REJECTED-PAYLOAD-007`, does not change this
state.
