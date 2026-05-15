# Module FJ45. Finite-Index Formulation Bridge Checkpoint for RB-005

## Status

Completed

## Module type

Theorem map / Attack surface / Literature verification

## Problem

`FJ44` selected `RB-005`, finite-index and virtually compact special
formulation handling, as the next attack packet. The project now needs to
determine which finite-index passage is actually available inside the
repository without collapsing source-version labels.

The problem is not to prove a new finite-index theorem. It is to decide which
finite-index bridge is licensed by the existing source-status ledger, and
what remains blocked before virtual-special or infinite-dihedral route data
can be used proof-sensitively.

## Input

- `FJ12`, first inheritance-properties ledger;
- `FJ24`, CAT(0)-route subtraction and virtual-special warning;
- `FJ27`, version-aware inheritance-route subtraction;
- `FJ39`, Karrass--Solitar finite-presentation bridge and infinite-dihedral
  alternative;
- `FJ44`, `RB-005` attack-packet selection;
- `OQ-032`, `OQ-060`, and `OQ-066`;
- `ledgers/inheritance_properties.md`;
- `ledgers/source_status.md`;
- `ledgers/t001_residual.md`.

## Output target

A version-preserving finite-index bridge decision for `RB-005`:

- which finite-index passage can be used now;
- which passages are not yet recorded in the repository;
- whether any `T-001` residual subtraction follows;
- what the next bounded project move should be.

## Definitions

**Definition.** A full \(\mathcal{FJ}\) finite-index bridge is the
source-verified survey-level row saying that if \(H\leq G\) has finite index
and \(H\in\mathcal{FJ}\), then \(G\in\mathcal{FJ}\).

**Definition.** A coefficient K-theory finite-index bridge would be a
source-verified statement that the K-theoretic Farrell--Jones conjecture with
coefficients in additive categories passes from a finite-index subgroup to
the ambient group.

**Definition.** A CAT(0) finite-extension bridge would be a source-verified
statement that the ambient group of a finite extension fits a recorded
finite-dimensional CAT(0)-group route, or an equivalent route already
accepted by the project.

**Warning.** These bridges are not interchangeable. A full
\(\mathcal{FJ}\) survey row, a coefficient K-theory row, a `FJCw` or `FICwF`
row, and a CAT(0)-group recognition statement must keep their source-version
labels visible until `FJ02` or a source-conventions module reconciles them.

## Main work

### Bridge table

| Candidate bridge | Current repository status | FJ45 decision | Consequence for `RB-005` |
|---|---|---|---|
| Full \(\mathcal{FJ}\) finite-index overgroup bridge | Source-verified survey row in `ledgers/inheritance_properties.md`, inherited from Lueck (2025) and already used in `FJ12` and `FJ27`. | Usable now, but only at the full \(\mathcal{FJ}\) source level. | If \(H\leq G\) has finite index and \(H\in\mathcal{FJ}\) is recorded, then \(G\in\mathcal{FJ}\) may be recorded with the same full-formulation flag. |
| Coefficient K-theory finite-index overgroup bridge | Not recorded as a source-verified row in the current repository. | Not usable in `FJ45`. | A coefficient K-theory statement for a finite-index subgroup may not yet be promoted to the ambient group by this project. |
| Direct CAT(0) finite-extension bridge | Not recorded as a source-verified route in the current repository. | Not usable in `FJ45`. | A virtually compact special group is not automatically a CAT(0)-route subtraction merely because a finite-index subgroup is compact special. |
| `FJCw` or `FICwF` finite-index passage | Not reconciled with the current module vocabulary. | Not usable in `FJ45`. | These labels require a later source-conventions or `FJ02`-adjacent reconciliation before proof-sensitive route use. |

### Route decision

**Source-verified claim.** The only finite-index overgroup passage currently
available in the repository is the full \(\mathcal{FJ}\) survey-level row:
if \(H\leq G\) has finite index and \(H\in\mathcal{FJ}\), then
\(G\in\mathcal{FJ}\) (Lueck, 2025).

**Route decision.** `FJ45` authorizes finite-index route use only in that
source version. It does not authorize a coefficient K-theory finite-index
overgroup step, a direct CAT(0) finite-extension step, or a comparison with
`FJCw`/`FICwF` terminology.

### Consequence for virtually compact special cases

`FJ24` recorded compact finite-dimensional special cube complex groups as
finite-dimensional CAT(0)-route bridge cases. `FJ45` does not extend that
subtraction to every virtually compact special group.

The project may make a full \(\mathcal{FJ}\)-level finite-index inference
only after a finite-index subgroup has already been recorded as lying in
Lueck's full \(\mathcal{FJ}\) class. It may not use the current ledger to
turn a coefficient K-theory/CAT(0)-route statement for a finite-index
subgroup into the same statement for the ambient group.

### Consequence for the Karrass--Solitar infinite-dihedral alternative

`FJ39` records that the infinite-dihedral alternative would require
finite-index or virtually cyclic handling before route use. `FJ45` gives a
limited answer:

- if a finite-index subgroup is recorded in full \(\mathcal{FJ}\), the
  full \(\mathcal{FJ}\) finite-index overgroup row may be used;
- if the intended route is the coefficient K-theory free-by-cyclic route
  from `FJ26`, the needed finite-index passage remains unrecorded;
- if the intended route depends on `FJCw`, `FICwF`, or another convention,
  a source-conventions module is required before use.

## Proposition / Theorem / Conjecture / Example

**Proposition.** The finite-index overgroup bridge usable in `FJ45` is the
full \(\mathcal{FJ}\) bridge recorded from Lueck's survey, and no broader
version-neutral finite-index bridge is available inside the current
repository.

**Proposition.** `FJ45` produces no new `T-001` residual subtraction.

## Proof or verification

For the first proposition, `ledgers/inheritance_properties.md` records a
finite-index overgroup row only under the full \(\mathcal{FJ}\) formulation:
if \(H\leq G\) has finite index and \(H\in\mathcal{FJ}\), then
\(G\in\mathcal{FJ}\). `FJ27` explicitly warns that this row must not be
relabelled as a coefficient K-theory proof without another source. The
coefficient K-theory rows recorded from Bartels and Reich cover pullback and
subgroup inheritance, not a finite-index overgroup passage. Therefore the
usable row remains exactly the full \(\mathcal{FJ}\) finite-index row
(Bartels & Reich, 2007; Lueck, 2025).

For the second proposition, `FJ45` does not check a new group-specific
finite-index subgroup, does not prove a finite-extension CAT(0) recognition
statement, and does not add a coefficient finite-index theorem. It is a
formulation checkpoint only.

## References

No new external source was checked in this module. The following sources are
used through source-status rows already verified in earlier modules:

- Bartels, A., & Reich, H. (2007). Coefficients for the Farrell-Jones
  conjecture. *Advances in Mathematics, 209*(1), 337--362.
  https://doi.org/10.1016/j.aim.2006.05.004
- Lueck, W. (2025). *Survey on the Farrell--Jones conjecture*
  (arXiv:2507.11337). arXiv. https://arxiv.org/abs/2507.11337

Internal references:

- `modules/cycle_001/FJ12_inheritance_properties_ledger.md`
- `modules/cycle_002/FJ24_cat0_route_subtraction.md`
- `modules/cycle_002/FJ27_inheritance_route_subtraction.md`
- `modules/cycle_002/FJ39_normal_subgroup_bridge_source_verification.md`
- `modules/cycle_003/FJ44_residual_bucket_comparison_attack_packet.md`
- `ledgers/inheritance_properties.md`
- `ledgers/source_status.md`
- `ledgers/t001_residual.md`

## Dependencies

This module depends on:

- `FJ12`;
- `FJ24`;
- `FJ27`;
- `FJ39`;
- `FJ44`;
- `OQ-032`;
- `OQ-060`;
- `OQ-066`;
- `ledgers/inheritance_properties.md`;
- `ledgers/source_status.md`;
- `ledgers/t001_residual.md`.

## Results produced

This module produced:

- no established result number;
- a first-pass resolution of `OQ-066`;
- a sharpened status for `OQ-032`: only full \(\mathcal{FJ}\)-level
  finite-index use is currently licensed;
- a sharpened status for `OQ-060`: the infinite-dihedral route remains
  blocked for coefficient-route use unless a compatible finite-index bridge
  is source-verified;
- a new next target, `FJ46`, to decide whether `RB-005` should proceed by
  verifying a coefficient finite-index source or by interrupting for
  `FJ02`/source-convention reconciliation.

## Open questions generated

- `OQ-067`: Should `RB-005` next verify a coefficient K-theory
  finite-index overgroup theorem, or should the project interrupt for
  `FJ02`/source-convention reconciliation?

## Update to ledgers

After completion, update:

- `README.md` and `PROJECT_CHARTER.md` for the completed `FJ45` checkpoint
  and next `FJ46`;
- `SCOPE_LEDGER.md` for the `OQ-066` resolution and new `OQ-067`;
- `NOTATION_LEDGER.md` for the full \(\mathcal{FJ}\) finite-index bridge
  and source-version collapse warning;
- `OPEN_QUESTIONS.md` for `OQ-032`, `OQ-060`, `OQ-066`, and `OQ-067`;
- `BIBLIOGRAPHY.md` and `ledgers/source_status.md` for `FJ45` source use;
- `ledgers/inheritance_properties.md` for `FJ45` route use;
- `ledgers/t001_residual.md` for the `RB-005` checkpoint outcome;
- `ledgers/theorem_dependencies.md` and `ledgers/open_group_classes.md` for
  the completed module status;
- `references/papers_to_read.md` for the next task.
