# Module FJ68. Target-Pivot Candidate Matrix

## Status

Completed

## Module type

Governance checkpoint / Target selection / Attack surface

## Problem

`FJ67` records `OBL-PIVOT-001`: no new active target may be selected after
the `T-001` pause until a target-pivot matrix records source-readiness,
candidate-level object, Farrell--Jones relevance, formulation-safety flags,
known-route overlap, prior-art risk, expected project output, stop condition,
and explicit decision.

`FJ68` must apply that matrix to the possible target inputs already recorded
in the repository. It must either select one bounded target packet or record
that no target is ready.

## Input

- `FJ67`, Target-Pivot Criteria After T-001 Pause;
- `OQ-090`;
- `OBL-PIVOT-001`;
- `FJ18`, Artin Groups Dossier;
- `FJ20`, First Target Selection;
- `ledgers/open_group_classes.md`;
- `ledgers/known_classes.md`;
- `ledgers/source_status.md`;
- `OPEN_QUESTIONS.md`;
- `SCOPE_LEDGER.md`;
- `PROJECT_CHARTER.md`;
- `AGENTS.md`.

## Output target

A target-pivot matrix that:

- compares Artin groups, automatic / biautomatic groups, Thompson-type
  groups, and dormant `T-001`;
- resolves `OQ-090`;
- selects exactly one bounded next target packet if one is ready;
- records why other target inputs are deferred or dormant;
- selects `FJ69` as the next module.

## Definitions

**Definition.** A bounded target packet is a next-module target with a stable
ID, repository anchor, expected project object changed, and stop condition.
It is smaller than a global group-class theorem.

**Definition.** The Artin subclass-gap packet is the bounded target packet
that compares the source-verified Artin rows from `FJ18` and
`ledgers/known_classes.md` against the open Artin questions `OQ-021` and
`OQ-023`.

**Warning.** Selecting the Artin subclass-gap packet is not a claim that the
Farrell--Jones conjecture is known for all Artin groups. It is a decision to
build a gap inventory before any Artin theorem claim or new source hunt.

## Main work

### Target-pivot matrix

| Target ID | Candidate class or subclass | Repository anchor | Source payload present? | Source-readiness rating | Candidate-level object available? | Intended FJ-facing route | Formulation-safety flags | Known-route overlap | Prior-art risk | Expected project output | Stop condition | Decision |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| `TP-ART-001` | Artin subclass-gap analysis after `FJ18` | `FJ18`; `ER-011`; `OQ-021`; `OQ-023`; `ledgers/known_classes.md`; `ledgers/source_status.md` | yes, existing first-pass source-verified rows from `FJ18` | high for an internal gap inventory; medium for new theorem work | yes: subclass-gap inventory and Wu clique-reduction comparison are recorded open objects | source-level `FJCw` / `FICwF` subclass comparison, possible later route packet | preserve `FJCw`, `FICwF`, full \(\mathcal{FJ}\), and coefficient K-theory labels separately | many subclasses already covered by `FJ18`; global all-Artin remains unrecorded | medium, because Artin literature is broad and global novelty language is unsafe | `FJ69` Artin subclass-gap inventory; update `OQ-021` and `OQ-023` status | if no bounded subclass gap or route object can be named from existing records, record no-gap-ready obstruction | select |
| `TP-AUT-001` | Automatic / biautomatic groups | `ledgers/open_group_classes.md` | no exact payload recorded for target-pivot use | low | no bounded candidate object currently recorded | unknown FJ route inside current project | unknown | possible overlap with CAT(0), mapping class, or other known routes not yet inventoried | high | defer until a source-ready packet or known-cases ledger bridge exists | reject for now if the next module would be source accumulation | defer |
| `TP-THO-001` | Thompson-type groups | `ledgers/open_group_classes.md` | no exact payload recorded for target-pivot use | low | no bounded candidate object currently recorded | unknown FJ route inside current project | unknown | no project-verified route comparison recorded | high | defer until a source-ready packet or known-cases ledger bridge exists | reject for now if the next module would be source accumulation | defer |
| `TP-T001-001` | `T-001`, torsion-free one-relator residual gap analysis | `FJ19`--`FJ67`; `ledgers/t001_residual.md`; `ledgers/t001_candidate_inventory.md`; `ledgers/t001_kernel_recognition.md` | extensive archive, but no active candidate payload | low for immediate reactivation despite high archive depth | no live non-routed candidate after `FJ64`--`FJ66` | dormant comparator only unless `OBL-T001-013` is met | preserve full FJ, coefficient, `FJCw`, finite-index, and weaker \(K_0\)-level distinctions | many route removals already recorded; remaining lanes are dormant or blocked | high if reactivated without a new object | keep dormant; no `FJ69` reactivation | reactivation requires candidate-admissible row, exact source payload, bridge, computation, prior-art blocker, or explicit matrix reselection | dormant comparator |

### Target decision

`FJ68` selects the bounded target packet:

```text
A-001. Artin subclass-gap inventory after FJ18
```

The packet is selected because it is the only compared target input with:

- source-verified internal anchors already recorded;
- open questions already in the repository;
- a bounded next object smaller than a global theorem claim;
- a clear stop condition against decorative bibliography.

The packet does not license a source hunt yet. The next module should first
build the internal gap inventory from existing rows, then decide whether a
new source payload is needed.

### Deferred target inputs

Automatic / biautomatic groups and Thompson-type groups remain listed in
`ledgers/open_group_classes.md`, but `FJ68` does not select them. Each lacks
an exact source payload and bounded candidate object inside the current
repository.

Dormant `T-001` remains unresolved and archived. `FJ68` does not reactivate
it because `OBL-T001-013` is not satisfied.

### New proof obligation

**Obligation OBL-ARTIN-001.** `FJ69` must produce an Artin subclass-gap
inventory from existing repository records before beginning any new Artin
source-summary lane.

Minimum required fields:

- Artin class or route;
- current source-verified status in `FJ18` / `ledgers/known_classes.md`;
- formulation label: `FJCw`, `FICwF`, full \(\mathcal{FJ}\), coefficient
  K-theory, or unknown;
- already-covered reason, gap reason, or deferred reason;
- relation to `OQ-021` or `OQ-023`;
- next proof obligation or stop condition.

Stop condition: do not claim all Artin groups satisfy Farrell--Jones, and do
not start a broad Artin bibliography module unless the inventory identifies
an exact source payload and project object changed.

### Next module selection

`FJ68` selects:

```text
FJ69. Artin Subclass-Gap Inventory After FJ18
```

Goal: build the first post-`T-001` active target inventory by comparing the
Artin rows already recorded in `FJ18`, `ledgers/known_classes.md`, and
`ledgers/open_group_classes.md`.

Required input:

- `FJ18`;
- `FJ20`;
- `FJ68`;
- `OQ-021`;
- `OQ-023`;
- `OBL-ARTIN-001`;
- `ledgers/known_classes.md`;
- `ledgers/open_group_classes.md`;
- `ledgers/source_status.md`;
- `NOTATION_LEDGER.md`.

Success criterion:

- produce an Artin subclass-gap inventory and select one bounded Artin
  follow-up packet; or
- record that no Artin gap is ready without a new exact source payload.

Failure criterion:

- the module becomes a general Artin literature survey, or it promotes a
  global all-Artin theorem not recorded in the source-verified rows.

Expected output:

- update `OQ-021`;
- sharpen `OQ-023`;
- update `ledgers/open_group_classes.md`;
- either select a bounded `FJ70` Artin packet or record an Artin no-gap-ready
  obstruction.

## Proposition / Theorem / Conjecture / Example

**Proposition.** Under the `FJ67` target-pivot criteria, the next active
bounded target packet should be `A-001`, Artin subclass-gap inventory after
`FJ18`.

**Proof.** The Artin input has source-verified internal anchors in `FJ18`,
`ER-011`, `ledgers/known_classes.md`, and `ledgers/source_status.md`. It also
has open project questions, `OQ-021` and `OQ-023`, that ask for a bounded
subclass-gap comparison rather than a global theorem. By contrast,
automatic / biautomatic groups and Thompson-type groups have no exact source
payload or bounded candidate object in the current repository, and dormant
`T-001` lacks the reactivation object required by `OBL-T001-013`. Therefore
the Artin subclass-gap packet is the only target input satisfying
`OBL-PIVOT-001` for immediate bounded work.

**Route decision.** `FJ68` resolves `OQ-090`, completes `OBL-PIVOT-001`,
records `OBL-ARTIN-001`, selects `A-001`, and selects `FJ69`, Artin
Subclass-Gap Inventory After FJ18.

**Warning.** This is a target-selection result, not a mathematical theorem.
No new Farrell--Jones case is proved. No global Farrell--Jones theorem for
all Artin groups is claimed.

## Proof or verification

Verification was internal to the repository:

1. Checked `FJ67` for the target-pivot criteria and `OBL-PIVOT-001`.
2. Checked `FJ18` and `ledgers/known_classes.md` for Artin source-verified
   anchors.
3. Checked `ledgers/source_status.md` for Artin source-status rows already
   active in the repository.
4. Checked `ledgers/open_group_classes.md` for possible target inputs.
5. Checked `OPEN_QUESTIONS.md` for `OQ-021`, `OQ-023`, and `OQ-090`.
6. No new external source was checked.

## References

No new external source was used in this module.

Internal references:

- `modules/cycle_001/FJ18_artin_groups_dossier.md`
- `modules/cycle_001/FJ20_first_target_selection.md`
- `modules/cycle_004/FJ67_target_pivot_criteria_after_t001_pause.md`
- `OPEN_QUESTIONS.md`
- `ledgers/known_classes.md`
- `ledgers/open_group_classes.md`
- `ledgers/source_status.md`
- `PROJECT_CHARTER.md`
- `SCOPE_LEDGER.md`
- `AGENTS.md`

## Dependencies

This module depends on:

- `FJ18`;
- `FJ20`;
- `FJ67`;
- `OQ-090`;
- `OBL-PIVOT-001`;
- `ledgers/open_group_classes.md`;
- `ledgers/known_classes.md`;
- `ledgers/source_status.md`.

## Results produced

This module produced:

- a first-pass resolution of `OQ-090`;
- completion of `OBL-PIVOT-001` for the current target comparison;
- target selection `A-001`, Artin subclass-gap inventory after `FJ18`;
- `OBL-ARTIN-001`, the Artin subclass-gap inventory requirement;
- selection of `FJ69`, Artin Subclass-Gap Inventory After FJ18;
- no new `ER-*` result;
- no new Farrell--Jones theorem claim;
- no reactivation of `T-001`.

## Open questions generated

- `OQ-091`: Can `FJ69` produce an Artin subclass-gap inventory from the
  existing `FJ18` rows without turning into a broad source-summary module?

## Update to ledgers

After completion, update:

- `README.md` and `PROJECT_CHARTER.md` for completed `FJ68` and next `FJ69`;
- `SCOPE_LEDGER.md` for the `OQ-090` resolution, `A-001`, and new `OQ-091`;
- `OPEN_QUESTIONS.md` for `OQ-021`, `OQ-023`, `OQ-090`, and `OQ-091`;
- `NOTATION_LEDGER.md` for `A-001`, `TP-ART-001`, and `OBL-ARTIN-001`;
- `ledgers/open_group_classes.md` for target-pivot decisions;
- `ledgers/theorem_dependencies.md` for completed `FJ68` and pending `FJ69`;
- `references/papers_to_read.md` and `AGENTS.md` for the next handoff.
