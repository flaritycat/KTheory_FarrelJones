# Module FJ24. CAT(0)-route subtraction for T-001

## Status

Completed

## Module type

Theorem map / Attack surface / Literature verification

## Problem

Continue subtracting known Farrell--Jones routes from `T-001`, the
torsion-free one-relator residual gap analysis.

`FJ23` removed groups after a source-verified bridge to word-hyperbolicity.
The next route is the finite-dimensional CAT(0)-group route recorded in
`ER-009` and expanded in `FJ14`.

The delicate point is virtual specialness. `FJ22` records virtual-special
consequences from Linton's hierarchy source, but virtual specialness should not
be treated as a CAT(0) route unless the bridge to the project's exact CAT(0)
known-case hypotheses is recorded.

## Input

This module uses:

- `ER-009`, the known-cases ledger row for finite-dimensional CAT(0)-groups;
- `FJ14`, the CAT(0)-groups proof skeleton;
- `ER-012` and `FJ19`, the one-relator status ledger;
- `FJ22`, the one-relator hierarchy vocabulary;
- `FJ23`, the hyperbolic-route subtraction;
- `OQ-030`;
- Haglund--Wise for special cube complex vocabulary and the CAT(0) cube-complex
  bridge.

## Output target

A first-pass CAT(0)-route subtraction table for `T-001`:

- what is removed directly by a finite-dimensional CAT(0) action;
- what is removed through compact special cube complex data;
- what remains deferred because only virtual specialness, not the precise
  CAT(0) action or finite-index bridge, has been recorded.

## Definitions

**Definition.** A CAT(0)-route subtraction is a project bookkeeping step: a
torsion-free one-relator group is removed from the active residual target once
the project has a source-verified reason that it admits a proper, cocompact,
isometric action on a finite-dimensional CAT(0)-space.

**Definition.** A CAT(0) bridge is a source-verified statement placing a group
or subclass inside the finite-dimensional CAT(0)-group known-case row of
`ER-009`.

**Definition.** A compact special bridge is a source-verified statement that a
group is the fundamental group of a compact finite-dimensional special cube
complex. Since special cube complexes are nonpositively curved cube complexes
in the Haglund--Wise setting, the universal cover gives a CAT(0) cube complex
route.

**Warning.** A virtual-special statement is not automatically used as a
CAT(0)-route subtraction in this module. It must be paired with an exact source
convention, such as "virtually compact special," and with either:

- a verified finite-index-overgroup passage for the relevant Farrell--Jones
  formulation; or
- a verified theorem that the whole group is a finite-dimensional CAT(0)-group.

## Main work

### Route principle

**Source-verified claim.** Finite-dimensional CAT(0)-groups satisfy the
K-theoretic Farrell--Jones conjecture with coefficients in additive categories
in all degrees, in Wegner's source formulation. This is recorded in `ER-009`
and expanded in `FJ14`.

**Route principle.** Therefore, for `T-001`, any torsion-free one-relator group
that is independently source-verified as a finite-dimensional CAT(0)-group is
removed from the active residual target.

**Warning.** This route principle uses the project's known-case row. It does
not construct a CAT(0) action for a one-relator group.

### CAT(0) and special-cube bridges

| One-relator condition | Bridge to the CAT(0) known case | FJ24 action |
|---|---|---|
| \(G\) is source-verified as a finite-dimensional CAT(0)-group | Directly matches the `ER-009` CAT(0) row | Subtract by `ER-009`. |
| \(G\cong\pi_1(Y)\), where \(Y\) is a compact finite-dimensional special cube complex | Haglund--Wise special cube complexes are nonpositively curved cube complexes; the universal cover is a finite-dimensional CAT(0) cube complex and deck transformations give the proper cocompact action | Subtract by the CAT(0) route. |
| \(G\) is virtually compact special | A finite-index subgroup is compact special, but the whole group requires a finite-index bridge before using the CAT(0) row directly | Do not subtract as a pure CAT(0) route until the finite-index-overgroup bridge is recorded; it may be subtractable through the inheritance ledger. |
| Linton's main equivalence gives virtual specialness together with hyperbolicity | Hyperbolicity was already part of the same source theorem and was handled by `FJ23` | No new CAT(0) subtraction is needed for that subclass. |
| A one-relator group is merely suspected to be cubulated or special | No source-verified bridge yet | Keep in the residual target. |

### Interpretation for the T-001 residual

`FJ24` removes only the following from the active residual:

- torsion-free one-relator groups already source-verified as
  finite-dimensional CAT(0)-groups;
- torsion-free one-relator groups source-verified as fundamental groups of
  compact finite-dimensional special cube complexes.

It does not remove:

- every virtually special group, unless the finite-index bridge is supplied;
- every group with a virtual-special consequence that was already removed by
  hyperbolicity in `FJ23`;
- any group whose cubical geometry is only conjectural or only suggested by
  analogy.

**Warning.** This is a conservative subtraction module. The residual after
`FJ24` is not a class of non-CAT(0) groups; it is the class not yet removed by
the project-recorded CAT(0) route.

## Proposition / Theorem / Conjecture / Example

**Proposition.** Let \(G\) be a torsion-free one-relator group. If the project
has a source-verified bridge showing that \(G\) is a finite-dimensional
CAT(0)-group, then \(G\) is removed from the `T-001` residual by the CAT(0)
route.

**Proof.** The bridge places \(G\) in the finite-dimensional CAT(0)-group row
of `ER-009`. By Wegner's theorem, as recorded in `FJ14`, finite-dimensional
CAT(0)-groups satisfy the K-theoretic Farrell--Jones conjecture with
coefficients in additive categories in all degrees. Hence \(G\) is already
covered by the known-cases ledger and should not remain in the residual
target.

**Proposition.** If \(G\) is source-verified as the fundamental group of a
compact finite-dimensional special cube complex, then \(G\) is removed from
the `T-001` residual by the CAT(0) route.

**Proof.** In the Haglund--Wise framework, special cube complexes are
nonpositively curved cube complexes. Their background section records the link
condition for nonpositive curvature and says that a simply connected
nonpositively curved cube complex is CAT(0). The universal cover of a compact
finite-dimensional special cube complex is therefore a finite-dimensional
CAT(0) cube complex, and the fundamental group acts on it properly and
cocompactly by deck transformations. Thus the group is a finite-dimensional
CAT(0)-group in the sense used in `FJ14`, so the first proposition applies.

**Warning.** The second proposition is intentionally stated for compact
finite-dimensional special cube complexes, not for every use of the words
"virtually special." The virtual case needs a finite-index bridge before it is
used proof-sensitively.

## Proof or verification

This module composes source-verified statements already in the repository with
one newly recorded bridge source.

1. `ER-009` and `FJ14` record Wegner's K-theoretic Farrell--Jones theorem for
   finite-dimensional CAT(0)-groups.
2. `FJ19` records finite-dimensional CAT(0) one-relator groups as a verified
   positive route only when the CAT(0) action is independently known.
3. `FJ22` records virtual specialness as a downstream consequence of Linton's
   hierarchy source under hypotheses that also include hyperbolicity; those
   cases were already eligible for `FJ23`.
4. Haglund--Wise was checked for the special cube complex framework, the
   nonpositive-curvature link condition for cube complexes, and the convention
   that simply connected nonpositively curved cube complexes are CAT(0).

## References

- Haglund, F., & Wise, D. T. (2008). Special cube complexes. *Geometric and
  Functional Analysis, 17*(5), 1551--1620.
  https://doi.org/10.1007/s00039-007-0629-4
- Linton, M. (2024). *One-relator hierarchies* (arXiv:2202.11324v3). arXiv.
  https://arxiv.org/abs/2202.11324
- Wegner, C. (2012). The K-theoretic Farrell-Jones conjecture for
  CAT(0)-groups. *Proceedings of the American Mathematical Society, 140*(3),
  779--793. https://doi.org/10.1090/S0002-9939-2011-11150-X

## Dependencies

This module depends on:

- `ER-009`;
- `FJ14`;
- `ER-012` and `FJ19`;
- `FJ22`;
- `FJ23`;
- `OQ-030`.

## Results produced

This module produced:

- a first-pass resolution of `OQ-030`;
- the CAT(0)-route subtraction table for `T-001`;
- a new bridge-source entry for compact special cube complexes;
- no new `ER-*` result.

## Open questions generated

- Which finite-index-overgroup source should the project use if it wants to
  turn "virtually compact special" into a proof-sensitive CAT(0) or
  Farrell--Jones route?
- Which part of the remaining `T-001` residual is removed by the virtually
  solvable route?
- Which one-relator groups are source-verified as compact special but not
  already removed by the hyperbolic route?

## Update to ledgers

After completion, update:

- `PROJECT_CHARTER.md` for the completed `FJ24` status and next `FJ25`;
- `README.md` for current progress;
- `SCOPE_LEDGER.md` for the CAT(0)-route subtraction and next question;
- `NOTATION_LEDGER.md` for CAT(0)-route and compact-special bridge terms;
- `OPEN_QUESTIONS.md` to mark `OQ-030` first-pass resolved and add the
  virtually solvable route question;
- `BIBLIOGRAPHY.md` and `ledgers/source_status.md` for Haglund--Wise and
  source use in `FJ24`;
- `ledgers/theorem_dependencies.md` for the completed `FJ24` row and next
  dependency row;
- `ledgers/open_group_classes.md` for the updated `T-001` residual status.
