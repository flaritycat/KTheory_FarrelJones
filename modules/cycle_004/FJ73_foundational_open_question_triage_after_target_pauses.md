# Module FJ73. Foundational Open-Question Triage After Target Pauses

## Status

Completed

## Module type

Governance checkpoint / Foundational triage / Attack surface

## Problem

`FJ72` records that no group-class target is currently ready for active proof
or source work. It selects `FND-001`, foundational open-question triage after
target pauses, and records `OBL-FND-001`.

`FJ73` must compare existing foundational blockers and select at most one
for bounded action. It must not become a general foundations survey.

## Input

- `FJ02`, additive-category/source-convention module;
- `FJ03`, classifying spaces for families;
- `FJ12`, inheritance properties ledger;
- `FJ15`, controlled topology primer;
- `FJ17`, transfers primer;
- `FJ72`, Target-Pivot Refresh After Artin Pause;
- `OQ-005`;
- `OQ-015`;
- `OQ-018`;
- `OQ-020`;
- `OQ-095`;
- `OBL-FND-001`;
- `OPEN_QUESTIONS.md`;
- `SCOPE_LEDGER.md`;
- `NOTATION_LEDGER.md`;
- `ledgers/theorem_dependencies.md`;
- `AGENTS.md`.

## Output target

A foundational triage artifact that:

- resolves `OQ-095`;
- completes `OBL-FND-001`;
- selects at most one foundational blocker for immediate action;
- records the exact project object changed by the next module;
- records a stop condition against broad source accumulation;
- selects `FJ74` only if a bounded blocker is available.

## Definitions

**Definition.** A foundational blocker selection is a project-state decision
that an existing foundational open question is concrete enough to support
one bounded module.

**Definition.** A source-light cleanup is a module that uses an already
recorded source anchor or internal convention to sharpen project wording,
notation, or dependency status. It is not a new literature survey.

**Definition.** A source-heavy foundations packet is a module that would need
new source comparison across multiple proof papers before it can change a
project convention.

## Main work

### Foundational blocker matrix

| Blocker ID | Open question | Repository anchor | Current source readiness | Project object changed | Risk | Decision |
|---|---|---|---|---|---|---|
| `FND-BLK-001` | `OQ-005`, weakly contractible versus contractible fixed-point formulations | `FJ03`; `ER-002`; `ledgers/theorem_dependencies.md` | high for triage: `FJ03` already records Lueck Definition 1.8 and Theorem 1.9 as the source anchor | convention note for classifying spaces, `OQ-005`, notation/dependency ledgers | low; bounded cleanup, not a theorem hunt | select |
| `FND-BLK-002` | `OQ-003`, construction-level nonconnective K-theory model | `FJ02`; `FJ01`; `ER-013` | medium; first-pass convention already adopted | possible later foundations module | medium; construction-level details may expand quickly | defer |
| `FND-BLK-003` | `OQ-015`, primary-source tracing for inheritance rows | `FJ12`; `ledgers/inheritance_properties.md` | low without an active application row | inheritance ledger | high; likely source-heavy without a selected route application | defer |
| `FND-BLK-004` | `OQ-018`, canonical obstruction-category source | `FJ15`; `FJ13`; `FJ17` | low for immediate cleanup | obstruction-category convention | high; requires comparing proof-paper notation | defer |
| `FND-BLK-005` | `OQ-020`, canonical transfer-category model | `FJ17`; `OQ-018` | low; depends on obstruction-category source choice | transfer-category convention | high; depends on `OQ-018` | defer |
| `FND-BLK-006` | `OQ-006`, direct original-source check for virtually cyclic dichotomy | `FJ04`; theorem-dependency ledger | medium for source location, low for immediate need | virtually cyclic source status | medium; not blocking current modules | defer |

### Selection decision

`FJ73` selects `FND-BLK-001`, the `OQ-005` fixed-point convention cleanup.

Reasons:

- it has an exact repository anchor in `FJ03`;
- the source anchor is already recorded in the project;
- it can change a concrete object: the convention around `E_{\mathcal F}G`
  and the open-question/dependency ledgers;
- it does not require a new broad source search;
- it improves foundational precision before later proof-technology modules
  lean on classifying-space language.

### Deferred blockers

`OQ-015`, `OQ-018`, and `OQ-020` remain important, but each is source-heavy
unless the project first identifies a proof-sensitive application. They
should not be selected merely because group-class targets are paused.

`OQ-003` remains partially resolved by `FJ02`; construction-level
nonconnective K-theory details are still deferred.

`OQ-006` remains open but is not currently blocking a module.

### New proof obligation

**Obligation OBL-FND-002.** `FJ74` must perform a fixed-point convention
cleanup for classifying spaces for families. It should decide how the
project separates:

- the readable contractible/empty fixed-point definition used in `FJ03`;
- Lueck's weakly contractible fixed-point characterization recorded in
  `FJ03`;
- the isotropy condition for \(G\)-CW complexes;
- any notation or dependency-ledger wording that should be sharpened.

Stop condition: do not turn `FJ74` into a general model-category or
classifying-space survey. Use the source anchor already recorded in `FJ03`
unless an exact wording check is needed.

### Next module selection

`FJ73` selects:

```text
FJ74. Fixed-Point Convention Cleanup for Classifying Spaces
```

Goal: resolve or sharpen `OQ-005` by separating the readable
contractible/empty formulation from the weakly contractible source
characterization.

Required input:

- `FJ03`;
- `OQ-005`;
- `ER-002`;
- `NOTATION_LEDGER.md`;
- `ledgers/theorem_dependencies.md`;
- the existing source anchor recorded in `FJ03`.

Success criterion:

- record a precise project convention and update `OQ-005` and the relevant
  ledgers.

Failure criterion:

- the module expands into a general survey of classifying spaces, model
  categories, or equivariant homotopy theory.

Expected output:

- updated `OQ-005`;
- updated notation/dependency wording;
- no new group-class Farrell--Jones theorem claim.

## Proposition / Theorem / Conjecture / Example

**Proposition.** Among the current foundational blockers, `OQ-005` is the
only one ready for immediate bounded action without broad source
accumulation.

## Proof or verification

**Proof.** `OQ-005` has a concrete repository anchor in `FJ03`, and `FJ03`
already records the relevant source distinction: the module uses a readable
contractible/empty fixed-point definition, while the source-verified theorem
records weakly contractible fixed points together with the isotropy condition.
Thus the next module can sharpen a specific convention.

By contrast, `OQ-015` requires choosing inheritance rows and tracing primary
proof sources; `OQ-018` and `OQ-020` require comparing proof-technology
notation across sources; `OQ-003` is already partially resolved by `FJ02`;
and `OQ-006` is not blocking the current handoff. Therefore `OQ-005` is the
bounded foundational blocker to select.

No external source was checked for this triage.

## References

No new external source was used in this module.

Internal references:

- `modules/cycle_001/FJ03_classifying_spaces_for_families.md`
- `modules/cycle_004/FJ72_target_pivot_refresh_after_artin_pause.md`
- `OPEN_QUESTIONS.md`
- `SCOPE_LEDGER.md`
- `NOTATION_LEDGER.md`
- `ledgers/theorem_dependencies.md`
- `AGENTS.md`

## Dependencies

This module depends on:

- `FJ03`;
- `FJ72`;
- `OQ-005`;
- `OQ-095`;
- `OBL-FND-001`;
- `ledgers/theorem_dependencies.md`.

## Results produced

This module produced:

- a first-pass resolution of `OQ-095`;
- completion of `OBL-FND-001`;
- selection of `FND-BLK-001`, the `OQ-005` fixed-point convention blocker;
- `OBL-FND-002`, the fixed-point convention cleanup obligation;
- selection of `FND-002`, fixed-point convention cleanup for classifying
  spaces;
- selection of `FJ74`, Fixed-Point Convention Cleanup for Classifying Spaces;
- no new `ER-*` result;
- no group-class Farrell--Jones theorem claim.

## Open questions generated

No new open question is generated. `FJ74` continues with existing `OQ-005`.

## Update to ledgers

After completion, update:

- `README.md` and `PROJECT_CHARTER.md` for completed `FJ73` and next `FJ74`;
- `SCOPE_LEDGER.md` for the `OQ-095` resolution, `FND-002`, and
  `OBL-FND-002`;
- `OPEN_QUESTIONS.md` for `OQ-005` and `OQ-095`;
- `NOTATION_LEDGER.md` for `FND-BLK-001`, `FND-002`, and `OBL-FND-002`;
- `ledgers/theorem_dependencies.md` for completed `FJ73` and pending `FJ74`;
- `references/papers_to_read.md` and `AGENTS.md` for the next handoff.
