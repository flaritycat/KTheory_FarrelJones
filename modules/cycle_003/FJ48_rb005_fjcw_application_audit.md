# Module FJ48. RB-005 FJCw Application Audit

## Status

Completed

## Module type

Attack surface / Theorem map / Literature verification

## Problem

`FJ47` verifies a finite-index overgroup bridge for `FJCw`, the
finite-wreath-product version of the Farrell--Jones conjecture with
coefficients. That bridge is useful only if the finite-index subgroup already
has a source-verified `FJCw` label.

The problem is to audit the concrete `RB-005` cases and decide whether the
`FJ47` bridge can actually be applied now.

## Input

- `FJ24`, CAT(0)-route subtraction and virtual-special warning;
- `FJ26`, hyperbolic-by-cyclic/free-by-cyclic route subtraction;
- `FJ39`, Karrass--Solitar infinite-cyclic/infinite-dihedral alternative;
- `FJ44`, `RB-005` attack-packet selection;
- `FJ45`, finite-index formulation checkpoint;
- `FJ47`, `FJCw` finite-index bridge;
- `OQ-032`, `OQ-060`, and `OQ-069`;
- `ledgers/t001_residual.md`;
- `ledgers/known_classes.md`;
- `ledgers/inheritance_properties.md`;
- `ledgers/source_status.md`.

## Output target

An application audit for `RB-005`:

- identify which current `RB-005` cases have source-verified `FJCw`
  finite-index subgroup input;
- identify which cases remain blocked by source labels;
- decide whether any `T-001` residual subtraction follows;
- choose the next bounded mathematical move.

## Definitions

**Definition.** An `FJCw-ready` finite-index case is a case where the project
has already recorded \(H\leq G\) of finite index and has already recorded
that \(H\) satisfies `FJCw`.

**Definition.** A case is `blocked by source label` if the finite-index
subgroup is recorded only with a different route label, such as coefficient
K-theory FJC, finite-dimensional CAT(0)-group status, full
\(\mathcal{FJ}\), `FICwF`, or an internal structural bridge.

**Warning.** This module does not search for new `FJCw` theorems. It audits
the repository state after `FJ47`.

## Main work

### Repository FJCw inventory

The repository currently records source-verified `FJCw` rows in the
known-classes ledger for Artin-related classes: FC-type Artin groups, even
FC-type Artin groups, normally poly-free groups, and Wu's even-Artin clique
or join/tree classes. These rows are important for the broader project, but
they are not current `T-001`/`RB-005` one-relator residual cases.

The repository does not currently record a `T-001` finite-index subgroup
with `FJCw` as its source label.

### RB-005 application table

| Candidate case | Recorded finite-index subgroup input | `FJ47` bridge applies? | Audit decision |
|---|---|---|---|
| Virtually compact special cases deferred by `FJ24` | A finite-index subgroup may be compact special. `FJ24` routes compact finite-dimensional special cube complex groups through the finite-dimensional CAT(0) route, using Haglund--Wise and Wegner. | No, not from the current repository state. | The subgroup input is CAT(0)/coefficient-route data, not `FJCw`. Use neither the `FJ47` bridge nor a direct CAT(0) finite-extension statement until that statement is source-verified. |
| Karrass--Solitar infinite-dihedral alternative from `FJ39` | A finite-index subgroup would align with the infinite-cyclic extension of a finitely generated free group, hence with the `FJ26` finite-rank free-by-cyclic route if a concrete candidate is available. | No, not from the current repository state. | The available route label is coefficient K-theory via the hyperbolic-by-cyclic/free-by-cyclic route, not `FJCw`; moreover `FJ40` selected no concrete source-ready candidate needing this cleanup. |
| Other finite-index rows in `ledgers/t001_residual.md` | No additional current `RB-005` row records a finite-index subgroup with `FJCw`. | No. | No immediate `FJCw` application is available inside `T-001`. |
| Artin-related `FJCw` rows from `FJ18` | Several Artin subclasses have source-verified `FJCw`. | Potentially in future Artin work, but not for `T-001`/`RB-005`. | Keep as known-class data; do not count as one-relator residual progress. |

### Route delta

`FJ48` gives a negative but useful route delta:

- `FJ47` remains an active inheritance bridge;
- no current `T-001`/`RB-005` case is `FJCw-ready`;
- virtual-special cleanup remains blocked unless a direct CAT(0)
  finite-extension bridge, a full \(\mathcal{FJ}\) subgroup label, or an
  `FJCw` subgroup label is source-verified;
- the Karrass--Solitar infinite-dihedral cleanup remains blocked for the
  coefficient free-by-cyclic route unless the subgroup route is upgraded or a
  compatible finite-index theorem is checked;
- no residual subtraction follows.

### Next route selection

The next bounded move should not be a broad `FJCw` known-case expansion.
For `RB-005`, the closest concrete obstruction is the virtual compact special
case from `FJ24`: a finite-index subgroup has a compact-special/CAT(0) route,
but the ambient group is not yet routed.

Therefore `FJ48` selects `FJ49`: source-check a direct finite-extension
bridge for finite-dimensional CAT(0)-groups, with the narrow question
whether a finite extension of a finite-dimensional CAT(0)-group is again
usable in the project's finite-dimensional CAT(0)-group route.

## Proposition / Theorem / Conjecture / Example

**Proposition.** No current `T-001`/`RB-005` finite-index case in the
repository has source-verified `FJCw` finite-index subgroup input.

**Proposition.** `FJ48` produces no new `T-001` residual subtraction.

**Route decision.** The next bounded `RB-005` move is `FJ49`, a direct
finite-extension bridge check for finite-dimensional CAT(0)-groups.

## Proof or verification

For the first proposition, inspect the current ledgers. The `FJCw` entries in
`ledgers/known_classes.md` are Artin-related rows from `FJ18`, not
`T-001` one-relator residual rows. The `RB-005` rows in
`ledgers/t001_residual.md` point instead to:

- virtually compact special cases, where `FJ24` records a compact-special
  subgroup route through finite-dimensional CAT(0)-groups;
- the Karrass--Solitar infinite-dihedral alternative, where `FJ39` gives a
  structural finite-index problem and `FJ26` supplies only a coefficient
  hyperbolic-by-cyclic/free-by-cyclic route when the subgroup is identified.

Neither input is recorded as `FJCw`. Hence the `FJ47` bridge cannot yet be
applied to the active `T-001` residual.

The no-subtraction proposition follows because this module verifies no new
group-specific subgroup input and imports no new finite-extension theorem. It
only audits whether the already verified `FJ47` bridge has an immediate
target.

## References

No new external source was checked in this module. The following sources are
used through already recorded project source-status rows:

- Bartels, A., Lueck, W., Reich, H., & Rueping, H. (2014). K- and L-theory
  of group rings over \(GL_n(\mathbb Z)\). *Publications Mathematiques de
  l'IHES, 119*, 97--125. https://doi.org/10.1007/s10240-013-0055-0
- Bestvina, M., Fujiwara, K., & Wigglesworth, D. (2023). The Farrell-Jones
  conjecture for hyperbolic-by-cyclic groups. *International Mathematics
  Research Notices, 2023*(7), 5887--5904.
  https://doi.org/10.1093/imrn/rnac012
- Haglund, F., & Wise, D. T. (2008). Special cube complexes. *Geometric and
  Functional Analysis, 17*(5), 1551--1620.
  https://doi.org/10.1007/s00039-007-0629-4
- Karrass, A., & Solitar, D. (1978). One relator groups having a finitely
  presented normal subgroup. *Proceedings of the American Mathematical
  Society, 69*, 219--222.
  https://doi.org/10.1090/S0002-9939-1978-0466323-3
- Wegner, C. (2012). The K-theoretic Farrell-Jones conjecture for
  CAT(0)-groups. *Proceedings of the American Mathematical Society, 140*(3),
  779--793. https://doi.org/10.1090/S0002-9939-2011-11150-X

Internal references:

- `modules/cycle_002/FJ24_cat0_route_subtraction.md`
- `modules/cycle_002/FJ26_hyperbolic_by_cyclic_route_subtraction.md`
- `modules/cycle_002/FJ39_normal_subgroup_bridge_source_verification.md`
- `modules/cycle_003/FJ47_fjcw_finite_index_bridge_source_selection.md`
- `ledgers/t001_residual.md`
- `ledgers/known_classes.md`
- `ledgers/inheritance_properties.md`
- `ledgers/source_status.md`

## Dependencies

This module depends on:

- `FJ24`;
- `FJ26`;
- `FJ39`;
- `FJ44`;
- `FJ45`;
- `FJ47`;
- `OQ-032`;
- `OQ-060`;
- `OQ-069`;
- `ledgers/t001_residual.md`;
- `ledgers/known_classes.md`;
- `ledgers/inheritance_properties.md`;
- `ledgers/source_status.md`.

## Results produced

This module produced:

- a first-pass resolution of `OQ-069`;
- a negative application audit: no current `T-001`/`RB-005` case is
  `FJCw-ready`;
- no new `ER-*` result;
- no residual subtraction;
- a next target, `FJ49`, direct finite-extension bridge check for
  finite-dimensional CAT(0)-groups.

## Open questions generated

- `OQ-070`: Does the project have a source-verified finite-extension bridge
  showing that finite extensions of finite-dimensional CAT(0)-groups remain
  usable in the finite-dimensional CAT(0)-group route?

## Update to ledgers

After completion, update:

- `README.md` and `PROJECT_CHARTER.md` for completed `FJ48` and next
  `FJ49`;
- `SCOPE_LEDGER.md` for the `OQ-069` resolution and `OQ-070`;
- `OPEN_QUESTIONS.md` for `OQ-032`, `OQ-060`, `OQ-069`, and `OQ-070`;
- `ledgers/t001_residual.md` for the `FJCw` application audit;
- `ledgers/t001_kernel_recognition.md` for the infinite-dihedral cleanup
  status;
- `ledgers/theorem_dependencies.md` for `FJ48` and `FJ49`;
- `ledgers/open_group_classes.md` for the current `T-001` status;
- `references/papers_to_read.md` for the next task.
