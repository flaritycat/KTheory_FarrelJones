# Module FJ11. Known classes ledger

## Status

Completed, first pass

## Module type

Literature verification / Known-cases ledger

## Problem

Build the first source-verified table of group classes known to satisfy
Farrell--Jones, while keeping the version of the conjecture visible:

- K-theory versus L-theory;
- all degrees versus restricted degrees;
- ordinary ring coefficients versus coefficients in additive categories;
- exact group-class hypotheses.

This module is a ledger artifact, not a proof module.

## Input

- `FJ01`, for the simplified K-theoretic group-ring assembly map.
- `FJ03`, for \(E_{\mathcal{VCyc}}G\) and assembly as the map induced by
  \(E_{\mathcal{VCyc}}G\to\mathrm{pt}\).
- Bartels--Lueck--Reich's hyperbolic-groups theorem for K-theory with
  coefficients (Bartels et al., 2008).
- Bartels--Lueck's Annals paper for the class \(\mathcal B\), including
  hyperbolic groups and finite-dimensional CAT(0)-groups, and its
  L-theoretic assembly theorem (Bartels & Lueck, 2012).
- Wegner's CAT(0)-groups theorem for full K-theory with coefficients
  (Wegner, 2012).
- Wegner's virtually solvable groups theorem for K- and L-theory with
  coefficients (Wegner, 2015).

## Output target

A first-pass known-cases table in `ledgers/known_classes.md` recording:

- hyperbolic groups;
- finite-dimensional CAT(0)-groups;
- virtually solvable groups.

Each row must say exactly what has been source-verified and what remains
outside this first pass.

## Definitions

### Definition: source-verified known case

In this module, a **source-verified known case** is a group class for which
the project has checked a theorem statement in a source and recorded:

- the group-class hypothesis;
- whether the theorem is K-theoretic, L-theoretic, or both;
- whether coefficients in additive categories are included;
- the family of subgroups used in the statement, when stated in the
  source;
- the source and source-status label.

The row is usable only under the recorded hypotheses.

### Definition: coefficients flag

Several sources state results "with coefficients in additive categories."
This module records that phrase as a source-level strength flag. It does
not develop the additive-category formulation internally; that remains
deferred to `FJ02`.

### Definition: finite-dimensional CAT(0)-group

Following Bartels--Lueck and Wegner, this module uses
**finite-dimensional CAT(0)-group** for a group admitting a proper,
cocompact, isometric action on a finite-dimensional CAT(0)-space
(Bartels & Lueck, 2012; Wegner, 2012).

## Main work

### Source-verified table

| Group class | K-theory status | L-theory status | Coefficients | Source-verified claim | Notes |
|---|---|---|---|---|---|
| Hyperbolic groups | yes, all degrees | yes, all degrees | additive categories | Bartels--Lueck--Reich prove K-theoretic Farrell--Jones with coefficients for hyperbolic groups; Bartels--Lueck's class \(\mathcal B\) contains hyperbolic groups and satisfies the L-theoretic assembly theorem with coefficients. | K-theory source is stronger for all degrees; L-theory source is Bartels--Lueck Theorem B. |
| Finite-dimensional CAT(0)-groups | yes, all degrees | yes, all degrees | additive categories | Wegner proves full K-theoretic Farrell--Jones with coefficients for CAT(0)-groups; Bartels--Lueck's class \(\mathcal B\) contains finite-dimensional CAT(0)-groups and satisfies the L-theoretic assembly theorem with coefficients. | Bartels--Lueck alone gives only restricted K-theory for class \(\mathcal B\); Wegner supplies full K-theory. |
| Virtually solvable groups | yes, all degrees | yes, all degrees | additive categories | Wegner proves the K- and L-theoretic Farrell--Jones conjecture with coefficients in additive categories for virtually solvable groups, with respect to \(\mathcal{VCyc}\). | This row is already stronger than the earlier placeholder "virtually solvable" line. |

### Verification notes

For hyperbolic groups, Bartels--Lueck--Reich state as their main theorem
that if \(G\) is hyperbolic and \(\mathcal A\) is an additive category
with right \(G\)-action, then for every \(n\in\mathbb Z\) the
K-theoretic assembly map from \(E_{\mathcal{VCyc}}G\) to
\(\mathrm{pt}\) is an isomorphism. They also state that this implies the
ordinary Farrell--Jones conjecture with coefficients in an arbitrary
coefficient ring (Bartels et al., 2008).

For finite-dimensional CAT(0)-groups, Wegner states that the
K-theoretic Farrell--Jones conjecture with coefficients says that the
K-theoretic assembly map

\[
H_m^G(E_{\mathcal{VCyc}}G;\mathbf K_{\mathcal A})
\longrightarrow
H_m^G(\mathrm{pt};\mathbf K_{\mathcal A})
\]

is an isomorphism for all \(m\in\mathbb Z\) and every additive category
\(\mathcal A\) with a strict right \(G\)-action. Wegner's main theorem,
combined with the theorem that every CAT(0)-group in his sense is
strongly transfer reducible over \(\mathcal{VCyc}\), gives the full
K-theoretic result for CAT(0)-groups (Wegner, 2012).

For L-theory of hyperbolic and finite-dimensional CAT(0)-groups,
Bartels--Lueck define a class \(\mathcal B\) containing hyperbolic
groups and groups acting properly, cocompactly, and isometrically on a
finite-dimensional CAT(0)-space. Their Theorem B states that, for
\(G\in\mathcal B\), the L-theoretic Farrell--Jones assembly map with
coefficients in any additive \(G\)-category with involution is an
isomorphism. The same theorem gives only restricted K-theory for
\(\mathcal B\), so this module uses separate K-theory sources for the
full all-degree K-theoretic entries (Bartels & Lueck, 2012).

For virtually solvable groups, Wegner states as the main theorem that a
virtually solvable group satisfies the K- and L-theoretic
Farrell--Jones conjecture with coefficients in additive categories with
respect to the family of virtually cyclic subgroups (Wegner, 2015).

### Warning: not exhaustive

This first-pass ledger does not yet verify every known class. In
particular, it does not yet record source-verified rows for mapping class
groups, 3-manifold groups, lattices in Lie groups, relatively hyperbolic
groups, S-arithmetic groups, or Artin-group subclasses.

### Warning: source versions differ

The sources use stronger formulations than `FJ01`, especially
coefficients in additive categories and, for L-theory, additive
categories with involution. This module records those source strengths,
but it does not replace the project's deferred `FJ02` foundations.

## Proposition / Theorem / Conjecture / Example

### Source-verified claim: first known classes

The following group classes are source-verified known cases for the
versions stated in the table above:

1. hyperbolic groups;
2. finite-dimensional CAT(0)-groups;
3. virtually solvable groups.

This is a literature claim, not an internal proof.

## Proof or verification

The verification is by direct theorem lookup:

- Bartels--Lueck--Reich, main theorem: K-theoretic Farrell--Jones with
  coefficients for hyperbolic groups in all degrees.
- Bartels--Lueck, definition of \(\mathcal B\) and Theorem B:
  hyperbolic groups and finite-dimensional CAT(0)-groups lie in
  \(\mathcal B\), and the L-theoretic assembly map with coefficients is
  an isomorphism for groups in \(\mathcal B\).
- Wegner, CAT(0)-groups paper: full K-theoretic Farrell--Jones with
  coefficients for CAT(0)-groups.
- Wegner, virtually solvable groups paper: K- and L-theoretic
  Farrell--Jones with coefficients for virtually solvable groups.

No proof of these theorems is reproduced here.

## References

- Bartels, A., Lueck, W., & Reich, H. (2008). The K-theoretic
  Farrell-Jones conjecture for hyperbolic groups. *Inventiones
  Mathematicae, 172*(1), 29--70. https://doi.org/10.1007/s00222-007-0093-7

- Bartels, A., & Lueck, W. (2012). The Borel conjecture for hyperbolic
  and CAT(0)-groups. *Annals of Mathematics, 175*(2), 631--689.
  https://doi.org/10.4007/annals.2012.175.2.5

- Wegner, C. (2012). The K-theoretic Farrell-Jones conjecture for
  CAT(0)-groups. *Proceedings of the American Mathematical Society,
  140*(3), 779--793. https://doi.org/10.1090/S0002-9939-2011-11150-X

- Wegner, C. (2015). The Farrell-Jones conjecture for virtually
  solvable groups. *Journal of Topology, 8*(4), 975--1016.
  https://doi.org/10.1112/jtopol/jtv026

## Dependencies

This module depends on:

- `FJ01`, for the simplified K-theoretic assembly target;
- `FJ03`, for the family \(\mathcal{VCyc}\) and assembly map source;
- the four source-verified theorem statements listed above.

## Results produced

This module produced:

- ER-009: first source-verified known-cases ledger for hyperbolic
  groups, finite-dimensional CAT(0)-groups, and virtually solvable
  groups.

## Open questions generated

- Which additional known classes should be verified next: 3-manifold
  groups, mapping class groups, lattices, relatively hyperbolic groups,
  S-arithmetic groups, or an Artin-group subclass?

## Update to ledgers

After completion, update:

- `SCOPE_LEDGER.md`: record completion of `FJ11` and move the next
  target to `FJ12`.
- `ESTABLISHED_RESULTS.md`: add ER-009.
- `OPEN_QUESTIONS.md`: add the next-known-classes verification question.
- `BIBLIOGRAPHY.md`: update or add source entries for Bartels--Lueck,
  Bartels--Lueck--Reich, and Wegner.
- `ledgers/source_status.md`: update source status for the four sources.
- `ledgers/known_classes.md`: replace placeholders with the
  source-verified first-pass table.
