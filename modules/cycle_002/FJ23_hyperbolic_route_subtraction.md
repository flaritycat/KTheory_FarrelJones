# Module FJ23. Hyperbolic-route subtraction for T-001

## Status

Completed

## Module type

Theorem map / Attack surface / Literature verification

## Problem

Begin subtracting known Farrell--Jones routes from `T-001`, the torsion-free
one-relator residual gap analysis.

The first subtraction should be the hyperbolic route, because `ER-009` already
records hyperbolic groups as a source-verified Farrell--Jones known class, and
`FJ22` records one-relator hierarchy vocabulary that can sometimes certify
hyperbolicity.

## Input

This module uses:

- `ER-009`, the known-cases ledger row for hyperbolic groups;
- `FJ13`, the hyperbolic-groups proof skeleton;
- `ER-012` and `FJ19`, the one-relator status ledger;
- `FJ22`, the one-relator hierarchy vocabulary;
- `OQ-026` and `OQ-029`.

## Output target

A first-pass subtraction table for the hyperbolic route:

- what is removed from `T-001`;
- what is removed only after an independent hyperbolicity bridge is verified;
- what remains in the residual target after this module.

## Definitions

**Definition.** A hyperbolic-route subtraction is a project bookkeeping step:
a torsion-free one-relator group is removed from the active residual target
once the project has a source-verified reason that the group is word-hyperbolic.

**Definition.** The hyperbolic-route residual is the part of `T-001` not yet
removed by the hyperbolic known-case row. It consists of torsion-free
one-relator groups for which the project has not yet recorded a
source-verified hyperbolicity bridge.

**Warning.** The hyperbolic-route residual is not the same as the class of
non-hyperbolic torsion-free one-relator groups. It includes groups whose
hyperbolicity has simply not been verified inside this repository.

**Definition.** A hyperbolicity bridge is a source-verified statement that
places a one-relator group, or a specified one-relator subclass, inside the
class of word-hyperbolic groups.

## Main work

### Route principle

**Source-verified claim.** Hyperbolic groups satisfy the K-theoretic
Farrell--Jones conjecture with coefficients in additive categories in all
degrees, in the Bartels--Lueck--Reich source formulation. This is recorded in
`ER-009` and expanded in `FJ13`.

**Route principle.** Therefore, for `T-001`, any torsion-free one-relator group
that is independently source-verified as word-hyperbolic is removed from the
active residual target.

**Warning.** This route principle uses the project's existing known-case row.
It does not prove hyperbolicity of a one-relator group, and it does not resolve
the global torsion-free one-relator case.

### One-relator hierarchy bridges to hyperbolicity

`FJ22` records the following source-verified bridges from Linton's
*One-relator hierarchies*.

| One-relator condition | Bridge to hyperbolicity | FJ23 action |
|---|---|---|
| \(G\) is already source-verified word-hyperbolic | No additional bridge needed | Subtract by `ER-009`. |
| A one-relator hierarchy is quasi-convex and \(\pi_1(X)\) is hyperbolic | Hyperbolicity is part of the hypothesis | Subtract by `ER-009`; the hierarchy data may be useful later but is not needed for this subtraction. |
| A one-relator hierarchy is acylindrical | Linton's main equivalence gives the hyperbolic/quasi-convex hierarchy condition in the source setting | Subtract after acylindricity is source-verified for the concrete group or subclass. |
| A one-relator hierarchy is \(\mathbb Z\)-stable and \(\pi_1(X)\) contains no Baumslag--Solitar subgroup | Linton's main equivalence gives the hyperbolic/quasi-convex hierarchy condition in the source setting | Subtract after both hypotheses are source-verified. |
| A one-relator complex has negative immersions | Linton's negative-immersions theorem gives hyperbolicity in the source setting | Subtract after the negative-immersion hypothesis is imported with its exact definition. |
| \(G\) is virtually special but no hyperbolicity or CAT(0) bridge has been recorded | Not a hyperbolic-route bridge by itself inside this module | Do not subtract in FJ23; defer to the CAT(0)/virtual-special route. |

### Resulting residual after FJ23

After the hyperbolic route is subtracted, the active residual still includes:

- torsion-free one-relator groups for which no hyperbolicity source has been
  recorded in the project;
- one-relator groups with hierarchy data whose acylindricity,
  \(\mathbb Z\)-stability, Baumslag--Solitar exclusion, or negative-immersion
  hypotheses have not yet been verified;
- groups that may be covered by finite-dimensional CAT(0), virtually solvable,
  hyperbolic-by-cyclic, free-by-cyclic, or inheritance routes, but not by the
  hyperbolic route alone.

**Warning.** This residual is deliberately conservative. It is a research
to-do list, not a claim that the remaining groups are counterexamples,
non-hyperbolic, or outside Farrell--Jones.

## Proposition / Theorem / Conjecture / Example

**Proposition.** Let \(G\) be a torsion-free one-relator group represented, in
the source setting when needed, by a finite one-relator complex \(X\). If the
project has a source-verified hyperbolicity bridge for \(G\), then \(G\) is
removed from the `T-001` residual by the hyperbolic route.

**Proof.** A source-verified hyperbolicity bridge places \(G\) in the class of
word-hyperbolic groups. By `ER-009`, using Bartels--Lueck--Reich, hyperbolic
groups satisfy the K-theoretic Farrell--Jones conjecture with coefficients in
additive categories in all degrees. Therefore, within the project's known-case
ledger, \(G\) is already covered and should not remain in the residual target.

**Warning.** This proposition is a theorem map and project-subtraction rule. It
does not assert that every torsion-free one-relator group has a hyperbolicity
bridge.

## Proof or verification

This module introduces no new external theorem source. It composes
source-verified statements already recorded in the repository.

1. `ER-009` and `FJ13` record Bartels--Lueck--Reich's theorem for hyperbolic
   groups in the K-theoretic Farrell--Jones formulation with coefficients.
2. `FJ19` records that the global torsion-free one-relator class remains
   unresolved inside the project and that hyperbolic one-relator groups are a
   verified positive route only when hyperbolicity is independently known.
3. `FJ22` records Linton's hierarchy theorem and main equivalence theorem,
   including the acylindrical and \(\mathbb Z\)-stable/no-Baumslag--Solitar
   bridges to the hyperbolic/quasi-convex hierarchy condition.
4. `FJ22` also records Linton's negative-immersions theorem route as a future
   hyperbolicity bridge, while warning that negative immersions are not yet an
   active project definition.

## References

- Bartels, A., Lueck, W., & Reich, H. (2008). The K-theoretic
  Farrell-Jones conjecture for hyperbolic groups. *Inventiones Mathematicae,
  172*(1), 29--70. https://doi.org/10.1007/s00222-007-0093-7
- Linton, M. (2024). *One-relator hierarchies* (arXiv:2202.11324v3). arXiv.
  https://arxiv.org/abs/2202.11324
- Lueck, W. (2025). *Survey on the Farrell-Jones conjecture*
  (arXiv:2507.11337). arXiv. https://arxiv.org/abs/2507.11337

## Dependencies

This module depends on:

- `ER-009`;
- `FJ13`;
- `ER-012` and `FJ19`;
- `FJ22`;
- `OQ-026` and `OQ-029`.

## Results produced

This module produced:

- a first-pass resolution of `OQ-029`;
- the hyperbolic-route subtraction table for `T-001`;
- no new `ER-*` result.

## Open questions generated

- Which part of the `T-001` residual is removed by the finite-dimensional
  CAT(0) route, including any source-verified bridge from virtual specialness
  to finite-dimensional CAT(0)-group status?
- Which concrete one-relator examples should be used to test the
  \(\mathbb Z\)-stable/no-Baumslag--Solitar criterion?
- When should the project import the exact definition of negative immersions?

## Update to ledgers

After completion, update:

- `PROJECT_CHARTER.md` for the completed `FJ23` status and next `FJ24`;
- `README.md` for current progress;
- `SCOPE_LEDGER.md` for the hyperbolic-route subtraction and next question;
- `OPEN_QUESTIONS.md` to mark `OQ-029` first-pass resolved and add the CAT(0)
  route question;
- `BIBLIOGRAPHY.md` and `ledgers/source_status.md` for source use in `FJ23`;
- `ledgers/theorem_dependencies.md` for the completed `FJ23` row and next
  dependency row;
- `ledgers/open_group_classes.md` for the updated `T-001` residual status.
