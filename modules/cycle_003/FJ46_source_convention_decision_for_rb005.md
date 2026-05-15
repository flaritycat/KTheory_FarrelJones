# Module FJ46. Source-Convention Decision for RB-005

## Status

Completed

## Module type

Attack surface / Reflection / Theorem map

## Problem

`FJ45` completed the finite-index formulation checkpoint for `RB-005`. It
found one usable finite-index overgroup passage, but only at the full
\(\mathcal{FJ}\) source level. Coefficient K-theory finite-index promotion,
direct CAT(0) finite-extension promotion, and `FJCw`/`FICwF` comparisons
remain unavailable for proof-sensitive use.

The problem is to decide whether the project should next verify a narrow
coefficient finite-index source, or interrupt the one-relator route to
complete the deferred `FJ02`/source-convention work.

## Input

- `FJ02`, currently not started;
- `FJ12`, inheritance-properties ledger;
- `FJ24`, CAT(0)-route subtraction and virtual-special warning;
- `FJ27`, version-aware inheritance-route subtraction;
- `FJ39`, Karrass--Solitar infinite-dihedral cleanup issue;
- `FJ45`, finite-index formulation bridge checkpoint;
- `OQ-002`, `OQ-003`, `OQ-022`, `OQ-032`, `OQ-060`, and `OQ-067`;
- `ledgers/inheritance_properties.md`;
- `ledgers/source_status.md`;
- `ledgers/t001_residual.md`.

## Output target

A route decision for `RB-005`:

- continue by verifying a narrow coefficient finite-index source; or
- interrupt for `FJ02`/source-convention reconciliation before more
  proof-sensitive `RB-005` use.

## Definitions

**Definition.** A narrow source-verification step checks one missing theorem
or bridge without changing the project's formulation conventions.

**Definition.** A source-convention interruption pauses the current target
thread and completes a foundations module needed to compare source versions
before further proof-sensitive route use.

**Definition.** A proof-level formulation input is a source formulation whose
exact meaning affects whether a route subtraction is valid.

## Main work

### Decision table

| Option | Benefit | Obstruction | FJ46 decision |
|---|---|---|---|
| Verify a coefficient K-theory finite-index overgroup source next | Could potentially resolve one missing `RB-005` bridge. | Even if found, the project still has not internalized the additive-category formulation or reconciled `FJCw`, `FICwF`, full \(\mathcal{FJ}\), and the simplified ring-coefficient statement. | Do not select as the immediate next step. |
| Continue using only the full \(\mathcal{FJ}\) finite-index bridge | Already source-verified through the existing Lueck row. | Too narrow for the virtual-special and infinite-dihedral coefficient-route questions that caused `RB-005` to be selected. | Keep available, but do not treat as sufficient for `RB-005`. |
| Interrupt for `FJ02`/source conventions | Addresses the exact formulation debt now blocking `RB-005`; also reopens `OQ-002`, `OQ-003`, and `OQ-022` at the right time. | Delays further one-relator residual subtraction. | Select this option. |

### Route decision

**Route decision.** `FJ46` selects a source-convention interruption. The next
project move should be to begin the deferred `FJ02` additive-category and
source-convention module before further proof-sensitive `RB-005` work.

This decision does not say that no coefficient finite-index theorem exists.
It says that checking one such theorem now would not by itself solve the
larger formulation problem already active in the project: coefficient
K-theory, full \(\mathcal{FJ}\), finite wreath product variants, `FJCw`,
`FICwF`, and the simplified ring-coefficient statement are being compared in
route decisions without a completed internal convention.

### Minimum FJ02 payload before RB-005 resumes

The interrupted `FJ02` work should produce at least:

1. a source-verified modern additive-category Farrell--Jones statement;
2. the minimum additive \(G\)-category vocabulary needed to interpret the
   known-cases and inheritance ledgers;
3. a comparison policy for source labels including coefficient K-theory,
   full \(\mathcal{FJ}\), `FJCw`, `FICwF`, and simplified ring coefficients;
4. a rule for when a source-level theorem may be used as a route subtraction
   in `T-001`;
5. a list of finite-index bridge questions that remain after the convention
   is fixed.

## Proposition / Theorem / Conjecture / Example

**Proposition.** After `FJ45`, the correct next project move is a
source-convention interruption through `FJ02`, not a narrow coefficient
finite-index theorem search.

**Proposition.** `FJ46` produces no new `T-001` residual subtraction.

## Proof or verification

For the first proposition, `FJ45` showed that the only currently licensed
finite-index overgroup passage is the full \(\mathcal{FJ}\) row recorded
from Lueck's survey. It also showed that the desired `RB-005` uses require
coefficient K-theory, CAT(0), `FJCw`, or `FICwF` formulation control beyond
that row. The project charter already says to interrupt for `FJ02` if these
source-level formulations become proof-level inputs. Therefore the
source-convention interruption is the disciplined next step (Bartels &
Reich, 2007; Lueck, 2025).

For the second proposition, `FJ46` verifies no new group-specific bridge,
checks no new external theorem, and records no new group as lying in a
known Farrell--Jones class. It only selects the next foundations task.

## References

No new external source was checked in this module. The following sources are
used through source-status rows already verified in earlier modules:

- Bartels, A., & Reich, H. (2007). Coefficients for the Farrell-Jones
  conjecture. *Advances in Mathematics, 209*(1), 337--362.
  https://doi.org/10.1016/j.aim.2006.05.004
- Lueck, W. (2025). *Survey on the Farrell--Jones conjecture*
  (arXiv:2507.11337). arXiv. https://arxiv.org/abs/2507.11337

Internal references:

- `modules/cycle_001/FJ02_additive_categories.md`
- `modules/cycle_001/FJ12_inheritance_properties_ledger.md`
- `modules/cycle_002/FJ24_cat0_route_subtraction.md`
- `modules/cycle_002/FJ27_inheritance_route_subtraction.md`
- `modules/cycle_002/FJ39_normal_subgroup_bridge_source_verification.md`
- `modules/cycle_003/FJ45_finite_index_formulation_bridge_checkpoint.md`
- `ledgers/inheritance_properties.md`
- `ledgers/source_status.md`
- `ledgers/t001_residual.md`

## Dependencies

This module depends on:

- `FJ02`;
- `FJ12`;
- `FJ24`;
- `FJ27`;
- `FJ39`;
- `FJ45`;
- `OQ-002`;
- `OQ-003`;
- `OQ-022`;
- `OQ-032`;
- `OQ-060`;
- `OQ-067`.

## Results produced

This module produced:

- no established result number;
- a first-pass resolution of `OQ-067`;
- a decision to interrupt the `T-001`/`RB-005` route and begin `FJ02`;
- a minimum payload for `FJ02` before `RB-005` resumes.

## Open questions generated

- None. `FJ46` reactivates existing questions `OQ-002`, `OQ-003`, and
  `OQ-022` as the next foundations target.

## Update to ledgers

After completion, update:

- `README.md` and `PROJECT_CHARTER.md` for the completed `FJ46` decision
  and the `FJ02` interruption;
- `SCOPE_LEDGER.md` for the `OQ-067` resolution and current move;
- `OPEN_QUESTIONS.md` for `OQ-002`, `OQ-003`, `OQ-022`, `OQ-032`,
  `OQ-060`, and `OQ-067`;
- `NOTATION_LEDGER.md` for the source-convention interruption term;
- `BIBLIOGRAPHY.md` and `ledgers/source_status.md` for `FJ46` source use;
- `ledgers/t001_residual.md`, `ledgers/t001_kernel_recognition.md`,
  `ledgers/theorem_dependencies.md`, and `ledgers/open_group_classes.md`;
- `references/papers_to_read.md` for the next task.
