# Module FJ49. CAT(0) Finite-Extension Bridge Check

## Status

Completed

## Module type

Literature verification / Theorem map / Attack surface

## Problem

`FJ48` records that the `FJ47` `FJCw` bridge has no immediate `T-001`
application. The closest remaining `RB-005` obstruction is the virtual compact
special case from `FJ24`: a finite-index subgroup has a compact-special route
into finite-dimensional CAT(0)-groups, but the ambient group still needs a
proof-sensitive finite-index or finite-extension bridge.

The problem is to source-check whether the project can use a direct theorem:

> If \(H\leq G\) has finite index and \(H\) is a finite-dimensional
> CAT(0)-group, then \(G\) is a finite-dimensional CAT(0)-group.

## Input

- `FJ14`, CAT(0)-groups proof skeleton;
- `FJ24`, CAT(0)-route subtraction and virtual-special warning;
- `FJ44`, `RB-005` attack-packet selection;
- `FJ45`, finite-index formulation checkpoint;
- `FJ48`, `FJCw` application audit;
- `OQ-032` and `OQ-070`;
- `ledgers/known_classes.md`;
- `ledgers/source_status.md`;
- `ledgers/t001_residual.md`;
- Ruane (2008), checked through the E-Periodica PDF.

## Output target

A route decision for virtual compact special cases:

- identify whether a direct CAT(0) finite-extension bridge is source-verified;
- state what the checked source actually says;
- decide whether any `T-001` residual subtraction follows;
- select the next bounded project move.

## Definitions

**Definition.** A direct CAT(0) finite-extension bridge is a source-verified
statement that if a finite-index subgroup \(H\leq G\) acts properly,
cocompactly, and isometrically on a finite-dimensional CAT(0)-space, then
\(G\) also acts properly, cocompactly, and isometrically on some
finite-dimensional CAT(0)-space.

**Definition.** In this module, the virtual compact special `RB-005` case is
the case where a finite-index subgroup is recorded as the fundamental group of
a compact finite-dimensional special cube complex, so `FJ24` routes the
subgroup through the finite-dimensional CAT(0)-group known-case row.

**Warning.** A proper isometric action is not enough for the `FJ14`/`FJ24`
CAT(0)-route. The route needs a geometric action: proper and cocompact.

## Main work

### Source check

**Source-verified warning.** Ruane defines a CAT(0) group as a group acting
geometrically on a complete proper geodesic CAT(0)-space, meaning properly
discontinuously and cocompactly by isometries. Ruane observes that finite-index
subgroups of CAT(0) groups are again CAT(0) groups, because cocompactness is
inherited by finite-index subgroups. The finite-extension direction is then
posed as a question: if \(K\) is a finite extension of a CAT(0) group \(G\),
must \(K\) be CAT(0)? Ruane explains that Serre's construction gives a proper
isometric action of the finite extension on a finite product of copies of the
original space, but the missing point is a cocompact convex subspace for the
larger group action (Ruane, 2008).

**Route decision.** `FJ49` does not promote a direct CAT(0)
finite-extension bridge. The checked source treats the exact bridge needed by
`RB-005` as a question rather than as an available theorem.

### Consequence for virtual compact special cases

The virtual compact special path remains blocked in the CAT(0)-route lane.
The project may still use the compact special bridge of `FJ24` for the
finite-index subgroup itself, but it may not promote the ambient virtually
compact special group to the finite-dimensional CAT(0)-group route by a
direct finite-extension argument.

The remaining legal lanes are:

- a full \(\mathcal{FJ}\) finite-index route if the finite-index subgroup is
  recorded in full \(\mathcal{FJ}\);
- an `FJCw` finite-index route if the finite-index subgroup is recorded with
  `FJCw`;
- a future source-specific theorem for the relevant virtually compact special
  one-relator class;
- a candidate-level attack in another residual bucket.

### Route-delta table

| Question | FJ49 answer |
|---|---|
| What theorem was sought? | A direct finite-extension closure theorem for finite-dimensional CAT(0)-groups. |
| What source was checked? | Ruane (2008), *Two CAT(0) group questions*. |
| What hypothesis would it have supplied? | Ambient group \(G\) finite over a finite-dimensional CAT(0)-group \(H\). |
| What was actually found? | The finite-extension direction is posed as a question; the product-action construction gives proper isometric action but leaves cocompactness unresolved. |
| Residual bucket affected | `RB-005`, virtual compact special finite-index handling. |
| Does this remove a case? | No. |
| Next decision | Pause `RB-005` as not presently yielding a route subtraction, and write a checkpoint selecting the next attack packet or pivot. |

## Proposition / Theorem / Conjecture / Example

**Source-verified warning.** The direct finite-extension CAT(0)-group bridge
needed by `RB-005` is not source-verified by Ruane (2008); it is recorded
there as a question.

**Proposition.** `FJ49` produces no `T-001` residual subtraction.

**Route decision.** The next module should be `FJ50`, an `RB-005`
route-delta checkpoint deciding whether to pause `RB-005` and pivot to a new
attack packet.

## Proof or verification

The source-verified warning follows from Ruane's discussion. The source
separates the easy finite-index subgroup direction from the finite-extension
direction and explicitly asks whether finite extensions of CAT(0) groups are
again CAT(0). It also identifies the precise obstruction relevant here:
Serre's product construction gives a proper isometric action on a finite
product of CAT(0)-spaces, but cocompactness is not obtained from that
construction.

The no-subtraction proposition follows because the `FJ14`/`FJ24` CAT(0)
route requires a finite-dimensional CAT(0)-group input for the ambient group.
`FJ49` does not supply that input and checks no new group-specific
finite-index subgroup in full \(\mathcal{FJ}\) or `FJCw`.

## References

- Ruane, K. (2008). Two CAT(0) group questions. *L'Enseignement
  Mathematique, 54*(1-2), 159--161. https://doi.org/10.5169/seals-109925

Existing project references used through source-status rows:

- Haglund, F., & Wise, D. T. (2008). Special cube complexes. *Geometric and
  Functional Analysis, 17*(5), 1551--1620.
  https://doi.org/10.1007/s00039-007-0629-4
- Wegner, C. (2012). The K-theoretic Farrell-Jones conjecture for
  CAT(0)-groups. *Proceedings of the American Mathematical Society, 140*(3),
  779--793. https://doi.org/10.1090/S0002-9939-2011-11150-X

Internal references:

- `modules/cycle_001/FJ14_cat0_groups_case.md`
- `modules/cycle_002/FJ24_cat0_route_subtraction.md`
- `modules/cycle_003/FJ48_rb005_fjcw_application_audit.md`
- `ledgers/known_classes.md`
- `ledgers/source_status.md`
- `ledgers/t001_residual.md`

## Dependencies

This module depends on:

- `FJ14`;
- `FJ24`;
- `FJ44`;
- `FJ45`;
- `FJ48`;
- `OQ-032`;
- `OQ-070`;
- Ruane (2008);
- `ledgers/known_classes.md`;
- `ledgers/source_status.md`;
- `ledgers/t001_residual.md`.

## Results produced

This module produced:

- a first-pass resolution of `OQ-070`;
- a source-verified warning that the desired direct CAT(0)
  finite-extension bridge is not available from Ruane (2008);
- no new `ER-*` result;
- no residual subtraction;
- a next target, `FJ50`, an `RB-005` route-delta checkpoint and pivot
  decision.

## Open questions generated

- `OQ-071`: Should `RB-005` be paused after the failed `FJCw` and direct
  CAT(0) finite-extension application checks, and which attack packet should
  replace it?

## Update to ledgers

After completion, update:

- `README.md` and `PROJECT_CHARTER.md` for completed `FJ49` and next
  `FJ50`;
- `SCOPE_LEDGER.md` for `OQ-070`, `OQ-071`, and the route-blocking result;
- `OPEN_QUESTIONS.md` for `OQ-032`, `OQ-070`, and `OQ-071`;
- `BIBLIOGRAPHY.md` and `ledgers/source_status.md` for Ruane (2008);
- `NOTATION_LEDGER.md` for the direct CAT(0) finite-extension bridge term;
- `ledgers/t001_residual.md` for the `RB-005` checkpoint result;
- `ledgers/theorem_dependencies.md` and `ledgers/open_group_classes.md` for
  the completed module status;
- `references/papers_to_read.md` for the next task.
