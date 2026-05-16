# Module FJ59. Weaker K0 / Cohen--Lyndon Consequence Intake Gate

## Status

Completed

## Module type

Attack surface / Consequence-lane intake / Obstruction record

## Problem

`FJ58` records `OBL-T001-005`: no active candidate-production lane is
currently ready for `T-001`. It selects a lower-priority intake question:
whether a weaker \(K_0\)-level, finiteness-obstruction, or Cohen--Lyndon-style
consequence lane can update the project without being misread as a
Farrell--Jones route subtraction.

`FJ59` must decide what the repository already supports. It must not import a
classical one-relator theorem from memory, and it must not treat a theorem
name as a source payload.

## Input

- `FJ08`, Whitehead-group consequence;
- `FJ09`, projective class group and finiteness-obstruction consequence;
- `FJ19`, torsion-free one-relator status dossier;
- `FJ54`, residual-bucket checkpoint after `RB-006`;
- `FJ58`, post-hybrid candidate-production checkpoint;
- `OQ-024`;
- `OQ-080`;
- `ledgers/t001_candidate_inventory.md`;
- `ledgers/t001_residual.md`;
- `ESTABLISHED_RESULTS.md`;
- `ledgers/source_status.md`.

## Output target

An intake-gate decision:

- separate already-recorded conditional \(K_0\) consequences from any new
  weaker theorem claim;
- decide whether the repository contains a source payload for a
  Cohen--Lyndon-style update;
- record an obstruction if no payload is present;
- select the next bounded module without claiming a residual subtraction.

## Definitions

**Definition.** A weaker \(K_0\)-level consequence is a statement about
\(K_0(\mathbb Z[G])\), \(\widetilde K_0(\mathbb Z[G])\), Wall finiteness
obstructions, or adjacent low-dimensional \(K\)-theory data that is weaker
than proving the K-theoretic Farrell--Jones conjecture for \(G\).

**Definition.** A Cohen--Lyndon-style payload means an exact, source-checked
statement from one-relator theory whose hypotheses and conclusion can be
connected to a project object: a candidate row, a \(K_0\)-level consequence,
a finiteness-obstruction consequence, a Farrell--Jones formulation, or a
prior-art blocker.

**Definition.** A source payload is not a source name. It consists of the
exact theorem statement, exact hypotheses, source status, and the project row
that would change if the theorem is usable.

**Warning.** The repository currently contains classical one-relator source
names such as Lyndon--Schupp and Magnus--Karrass--Solitar, but these are
marked `found; to verify` for classical theorem use. They are not theorem
payloads for `FJ59`.

## Main work

### Intake table

| Possible weaker lane | Current repository support | Missing input | FJ59 decision |
|---|---|---|---|
| Conditional \(\widetilde K_0(\mathbb Z[G])\)-vanishing from Farrell--Jones | `FJ08`, `FJ09`, and `ER-007` record this consequence with Lueck--Reich hypotheses | a Farrell--Jones proof for a new `T-001` row | already recorded; no new update |
| Wall finiteness-obstruction consequence | `FJ09` records the finitely presented-group interpretation under \(\widetilde K_0\)-vanishing | independent \(\widetilde K_0\)-vanishing for a new one-relator class | already recorded conditionally; no new update |
| Global weaker K-theoretic theorem for all torsion-free one-relator groups | `OQ-024` asks for this; `FJ19` records no such theorem in the repository | exact source theorem and formulation comparison | unresolved; no source payload present |
| Cohen--Lyndon-style one-relator theorem | only flagged as a possible lower-priority lane in `FJ54`, `FJ57`, and `FJ58` | source, theorem statement, hypotheses, and relation to \(K_0\), FJ, finiteness obstruction, candidate production, or prior art | not usable yet |
| Prior-art blocker for candidate production | `FJ58` permits prior-art blockers as lane reactivation data | a candidate or theorem payload to compare | no current blocker |

### Consequence separation

`FJ59` separates two facts that must not be collapsed:

1. The project already has a conditional theorem map:
   Farrell--Jones for a torsion-free group \(G\), with the regular
   integral-coefficient setup used in `FJ08` and `FJ09`, implies
   \(\widetilde K_0(\mathbb Z[G])=0\).
2. The project does not have a recorded theorem saying that all
   torsion-free one-relator groups satisfy that Farrell--Jones hypothesis,
   a weaker global K-theoretic formulation, or a Cohen--Lyndon-style
   substitute for it.

Therefore the weaker lane cannot currently update `ER-007`, cannot resolve
`OQ-024`, and cannot reopen candidate-level proof work.

### Obstruction record

**Obstruction OBL-T001-006.** No weaker \(K_0\) / Cohen--Lyndon source
payload is currently recorded for `T-001`.

To advance this lane, a later module must supply:

- an exact source and APA citation;
- the exact theorem statement and hypotheses;
- the formulation level: full Farrell--Jones, coefficient K-theory FJC,
  `FJCw`, simplified ring-coefficient FJ, \(K_0\)-level only, or purely
  group-theoretic;
- the specific project object changed by the theorem: `OQ-024`, `OQ-080`, a
  candidate row, a proof obligation, a consequence ledger, or a prior-art
  blocker;
- an explicit non-use warning if the theorem is only group-theoretic.

### Selected next bounded module

The next module should be:

`FJ60`: Weaker Consequence Source-Payload Selection.

`FJ60` should not summarize several classical sources. It should either
select one exact source payload for a follow-up check or close the weaker
consequence lane as inactive until a source is named.

## Proposition / Theorem / Conjecture / Example

**Proposition.** In the current repository state, the weaker \(K_0\) /
Cohen--Lyndon lane has no usable source payload for `T-001`.

**Proof.** `FJ08` and `FJ09` record conditional \(K_0\)-level consequences
from Farrell--Jones, not an independent proof of those consequences for all
torsion-free one-relator groups. `FJ19` records `OQ-024` as open inside the
project. `FJ54`, `FJ57`, and `FJ58` mention the weaker \(K_0\) /
Cohen--Lyndon lane only as a lower-priority possible update, not as a
source-verified theorem. `ledgers/source_status.md` records Lyndon--Schupp
and Magnus--Karrass--Solitar only as `found; to verify` classical sources,
not as checked Cohen--Lyndon payloads. Hence there is no theorem payload
available for immediate use.

**Route decision.** `FJ59` first-pass resolves `OQ-080` by recording
`OBL-T001-006` and selecting `FJ60`, Weaker Consequence Source-Payload
Selection.

**Warning.** `FJ59` proves no new Farrell--Jones case, proves no new
\(K_0\)-level theorem for torsion-free one-relator groups, and makes no
residual subtraction.

## Proof or verification

Verification was internal to the repository:

1. Checked `FJ08` and `FJ09` for the existing conditional \(K_0\)-level
   consequence.
2. Checked `FJ19` and `OQ-024` for the current one-relator open-status
   warning.
3. Checked `FJ54`, `FJ57`, and `FJ58` for the weaker \(K_0\) /
   Cohen--Lyndon lane handoff.
4. Checked `ledgers/source_status.md` for whether a Cohen--Lyndon-style
   source payload is currently recorded.
5. No new external source was checked.

## References

No new external source was checked in this module.

Existing APA-style sources used only through prior repository verification:

- Lueck, W. (2025). *Survey on the Farrell--Jones conjecture*
  (arXiv:2507.11337). arXiv. https://arxiv.org/abs/2507.11337
- Lueck, W., & Reich, H. (2004). *The Baum-Connes and the Farrell-Jones
  conjectures in K- and L-theory* (arXiv:math/0402405). arXiv.
  https://arxiv.org/abs/math/0402405

Internal references:

- `modules/cycle_001/FJ08_whitehead_group_consequence.md`
- `modules/cycle_001/FJ09_projective_class_group_consequence.md`
- `modules/cycle_001/FJ19_one_relator_groups_dossier.md`
- `modules/cycle_003/FJ54_residual_bucket_checkpoint_after_rb006.md`
- `modules/cycle_003/FJ57_candidate_family_proof_attempt_or_obstruction_record.md`
- `modules/cycle_003/FJ58_post_hybrid_candidate_production_checkpoint.md`
- `ledgers/source_status.md`
- `ledgers/t001_candidate_inventory.md`
- `ledgers/t001_residual.md`

## Dependencies

This module depends on:

- `FJ08`;
- `FJ09`;
- `FJ19`;
- `FJ54`;
- `FJ58`;
- `OQ-024`;
- `OQ-080`;
- `ledgers/source_status.md`;
- `ledgers/t001_candidate_inventory.md`;
- `ledgers/t001_residual.md`.

## Results produced

This module produced:

- a first-pass resolution of `OQ-080`;
- `OBL-T001-006`, recording that no weaker \(K_0\) / Cohen--Lyndon source
  payload is currently recorded for `T-001`;
- a decision to continue with `FJ60`, Weaker Consequence Source-Payload
  Selection;
- no new `ER-*` result;
- no concrete residual subtraction.

## Open questions generated

- `OQ-081`: Which exact source, if any, supplies a weaker \(K_0\) /
  Cohen--Lyndon payload relevant to `T-001`?

## Update to ledgers

After completion, update:

- `README.md` and `PROJECT_CHARTER.md` for completed `FJ59` and next `FJ60`;
- `SCOPE_LEDGER.md` for the `OQ-080` resolution and new `OQ-081`;
- `OPEN_QUESTIONS.md` for `OQ-080` and `OQ-081`;
- `NOTATION_LEDGER.md` for source payload and `OBL-T001-006`;
- `ledgers/t001_candidate_inventory.md` for the new obstruction;
- `ledgers/t001_residual.md`, `ledgers/t001_kernel_recognition.md`,
  `ledgers/theorem_dependencies.md`, and `ledgers/open_group_classes.md` for
  the current target update;
- `references/papers_to_read.md` for the next task.
