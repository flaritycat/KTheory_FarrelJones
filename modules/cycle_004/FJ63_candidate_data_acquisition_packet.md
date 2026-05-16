# Module FJ63. Candidate-Data Acquisition Packet

## Status

Completed

## Module type

Attack surface / Data-acquisition selection / Governance checkpoint

## Problem

`FJ62` records `OBL-T001-009`: this module must select exactly one
data-acquisition packet or record failure to do so. The selected packet must
change a project object and must not become a broad source survey.

The active blocker list after `FJ62` is narrow:

1. no candidate-admissible row;
2. no route data attached to a candidate;
3. no branch decision until one acquisition attempt is made.

`FJ63` must choose the next packet.

## Input

- `FJ61`, T-001 Candidate-Intake Reset and Exit Criteria;
- `FJ62`, Active Blocker Pruning for `T-001`;
- `OQ-085`;
- `OBL-T001-008`;
- `OBL-T001-009`;
- `ledgers/t001_candidate_inventory.md`;
- `ledgers/t001_residual.md`;
- `ledgers/t001_kernel_recognition.md`;
- `ledgers/open_group_classes.md`;
- `PROJECT_CHARTER.md`;
- `AGENTS.md`.

## Output target

A single selected acquisition packet with:

- packet type;
- project object changed;
- required input;
- success criterion;
- failure criterion;
- next module handoff.

## Definitions

**Definition.** A data-acquisition packet is a bounded task that tries to
obtain one exact missing object: a candidate row, bridge lemma, computation,
source payload, prior-art blocker, pause trigger, or pivot-comparison
trigger.

**Definition.** A candidate-row acquisition packet is a data-acquisition
packet whose only allowed success is a candidate-admissible row in
`ledgers/t001_candidate_inventory.md`.

**Warning.** A candidate-row acquisition packet is not permission to
fabricate a family. If no repository-supported candidate row exists, the
correct output is a no-candidate note.

## Main work

### Packet comparison

| Packet type | Current support | Decision |
|---|---|---|
| Candidate-row acquisition | Directly targets the first active blocker from `FJ62`; uses existing candidate and residual ledgers. | selected |
| Bridge-lemma acquisition | No bridge can be selected responsibly without a candidate or named residual case. | not selected |
| Concrete computation acquisition | No computation target exists outside calibration or already routed rows. | not selected |
| Exact source-payload acquisition | `FJ60` records no exact payload; source names alone are insufficient. | not selected |
| Prior-art blocker acquisition | No candidate or theorem payload exists for comparison. | not selected |
| Target-pause trigger | Premature before one candidate-row acquisition attempt. | not selected |
| Target-pivot comparison trigger | Premature before one candidate-row acquisition attempt. | not selected |

### Selected packet

**Selected packet.** Candidate-row acquisition from current repository
records.

This packet asks whether the existing repository contains any row, residual
bucket, or named family that can be promoted into a candidate-admissible row
under the `FJ61` checklist.

The packet is deliberately internal. It should not open a new source search.

### Packet specification

| Field | Specification |
|---|---|
| Packet ID | `DAP-T001-001` |
| Packet type | candidate-row acquisition |
| Project object changed | `ledgers/t001_candidate_inventory.md` |
| Input files | `ledgers/t001_candidate_inventory.md`, `ledgers/t001_residual.md`, `ledgers/t001_kernel_recognition.md`, `ledgers/open_group_classes.md`, and `OPEN_QUESTIONS.md` |
| Allowed success | add one candidate-admissible row, or promote an existing placeholder only if all required fields are supplied |
| Required row fields | candidate identity, target status, residual status, route-output target, required data, formulation safety, prior-art risk, and exit condition |
| Failure condition | no repository-supported non-routed candidate row exists without importing new source content or fabricating a family |
| Non-use warning | do not reuse `CAND-T001-001`, `CAND-T001-002`, or `CAND-T001-003` as new residual candidates |
| Next module | `FJ64`, Candidate Intake Attempt or No-Candidate Note |

### FJ64 instructions

`FJ64` should perform the packet, not redesign it.

It should inspect the current candidate inventory and residual ledger and
then produce exactly one of:

- a new candidate-admissible row satisfying the `FJ61` checklist; or
- a no-candidate note explaining why the current repository has no row that
  can be promoted without external source acquisition or fabrication.

If the second outcome occurs, `FJ64` should preserve `T-001` as unresolved
and send the project toward prior-art blocker handling or a branch
checkpoint, rather than starting a source survey by default.

### New proof obligation

**Obligation OBL-T001-010.** Candidate-row acquisition packet.

`FJ64` must execute `DAP-T001-001`. It must either add one
candidate-admissible row to `ledgers/t001_candidate_inventory.md` or record a
no-candidate note. It must not select a new external source, bridge,
computation, or target pivot unless the candidate-row packet itself produces
the required object.

Stop condition: if no row satisfies the `FJ61` checklist, do not promote a
placeholder or routed example. Record the failure and preserve the blocker.

## Proposition / Theorem / Conjecture / Example

**Proposition.** The next valid acquisition packet for `T-001` is
candidate-row acquisition from current repository records.

**Proof.** `FJ62` reduces the active blockers to candidate-object
acquisition, route-data acquisition, and branch decision. Route-data
acquisition requires a candidate or named residual case; the current
repository has none outside calibration, routed rows, or placeholders.
Source-payload acquisition is blocked by `FJ60`, and prior-art comparison has
no object to compare. A pause or pivot is premature before the intake gate is
tested once. Therefore candidate-row acquisition is the only packet that can
directly test the first active blocker without importing a new source or
fabricating a family.

**Route decision.** `FJ63` resolves `OQ-085`, records `OBL-T001-010`, and
selects `FJ64`, Candidate Intake Attempt or No-Candidate Note.

**Warning.** `FJ63` proves no new Farrell--Jones case, proves no theorem
about torsion-free one-relator groups, finalizes no part of WIP /
provisional `FJ53`, and makes no residual subtraction.

## Proof or verification

Verification was internal to the repository:

1. Checked `FJ61` for the candidate-admissible row checklist.
2. Checked `FJ62` for the pruned active blocker list.
3. Checked `ledgers/t001_candidate_inventory.md` for existing rows and
   proof obligations.
4. Checked `ledgers/t001_residual.md` and `ledgers/t001_kernel_recognition.md`
   for dormant route-data lanes.
5. Checked `OPEN_QUESTIONS.md` for `OQ-085`.
6. No new external source was checked.

## References

No new external source was used in this module.

Internal references:

- `modules/cycle_004/FJ61_t001_candidate_intake_reset_exit_criteria.md`
- `modules/cycle_004/FJ62_active_blocker_pruning_t001.md`
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
- `OQ-085`;
- `OBL-T001-008`;
- `OBL-T001-009`;
- `ledgers/t001_candidate_inventory.md`;
- `ledgers/t001_residual.md`;
- `ledgers/t001_kernel_recognition.md`.

## Results produced

This module produced:

- a first-pass resolution of `OQ-085`;
- selected packet `DAP-T001-001`, candidate-row acquisition from current
  repository records;
- `OBL-T001-010`, requiring `FJ64` to execute the packet;
- selection of `FJ64`, Candidate Intake Attempt or No-Candidate Note;
- no new `ER-*` result;
- no concrete residual subtraction.

## Open questions generated

- `OQ-086`: Can `FJ64` produce a candidate-admissible row from
  `DAP-T001-001`, or must it record a no-candidate note?

## Update to ledgers

After completion, update:

- `README.md` and `PROJECT_CHARTER.md` for completed `FJ63` and next `FJ64`;
- `SCOPE_LEDGER.md` for the `OQ-085` resolution and new `OQ-086`;
- `OPEN_QUESTIONS.md` for `OQ-085` and `OQ-086`;
- `NOTATION_LEDGER.md` for data-acquisition packet, `DAP-T001-001`, and
  `OBL-T001-010`;
- `ledgers/t001_candidate_inventory.md` for the selected packet and new
  obligation;
- `ledgers/t001_residual.md`, `ledgers/t001_kernel_recognition.md`,
  `ledgers/theorem_dependencies.md`, and `ledgers/open_group_classes.md` for
  the current target update;
- `references/papers_to_read.md` and `AGENTS.md` for the next handoff.
