# Module FJ25. Virtually solvable-route subtraction for T-001

## Status

Completed

## Module type

Theorem map / Attack surface / Literature verification

## Problem

Continue the route-subtraction pass for `T-001`, the torsion-free
one-relator residual gap analysis.

`FJ23` subtracts groups after a source-verified bridge to
word-hyperbolicity. `FJ24` subtracts groups after a source-verified bridge to
the finite-dimensional CAT(0)-group known case. The next route is the
virtually solvable known-case row recorded in `ER-009` and `FJ11`.

The delicate point is that several one-relator structural properties look
linear or cyclic in a loose sense, but do not by themselves prove virtual
solvability. In particular, local indicability, nontrivial abelianization, and
HNN hierarchy data are not virtual-solvability certificates.

## Input

This module uses:

- `ER-009`, the known-cases ledger row for virtually solvable groups;
- `FJ11`, the source verification of Wegner's virtually solvable theorem;
- `ER-012` and `FJ19`, the one-relator status ledger;
- `FJ23`, the hyperbolic-route subtraction;
- `FJ24`, the CAT(0)-route subtraction;
- `OQ-031`;
- Lueck's open-status warning and Howie's Brodskii-theorem source as already
  recorded in `FJ19`.

## Output target

A first-pass virtually solvable-route subtraction table for `T-001`:

- what is removed by a verified virtual-solvability bridge;
- what is not removed merely from local indicability, abelianization, or HNN
  structure;
- what remains deferred because the project has not yet selected a
  classification or recognition source for virtually solvable one-relator
  groups.

## Definitions

**Definition.** A group is virtually solvable if it has a solvable subgroup of
finite index.

**Definition.** A virtually solvable-route subtraction is a project
bookkeeping step: a torsion-free one-relator group is removed from the active
`T-001` residual once the project has a source-verified reason that it is
virtually solvable.

**Definition.** A virtually solvable bridge is a source-verified statement,
or an internal elementary proof, showing that a group has a solvable subgroup
of finite index.

**Definition.** The residual after `FJ25` is the part of `T-001` not yet
removed by the hyperbolic, finite-dimensional CAT(0), or virtually solvable
routes recorded in the project.

**Warning.** Local indicability is not virtual solvability. `FJ19` records
Howie's source for the structural fact that torsion-free one-relator groups
are locally indicable, and it also records Lueck's warning that locally
indicable groups remain open in general for the Full Farrell--Jones
Conjecture.

**Warning.** Nontrivial abelianization is not virtual solvability. A
surjection from \(G\) onto an abelian group gives information about a quotient,
not a finite-index solvable subgroup of \(G\).

**Warning.** A one-relator HNN splitting or hierarchy is not automatically a
virtual-solvability certificate. It may be useful for later hyperbolic,
CAT(0), free-by-cyclic, or inheritance routes, but it is not used as a
virtually solvable bridge without an additional source-verified argument.

## Main work

### Route principle

**Source-verified claim.** Wegner proves that virtually solvable groups
satisfy the K- and L-theoretic Farrell--Jones conjecture with coefficients in
additive categories with respect to \(\mathcal{VCyc}\). This is recorded in
`ER-009` and `FJ11` (Wegner, 2015).

**Route principle.** Therefore, for `T-001`, any torsion-free one-relator
group that is independently source-verified as virtually solvable is removed
from the active residual target.

**Warning.** This route principle uses the project's known-case row. It does
not classify virtually solvable one-relator groups.

### Subtraction table

| One-relator input | Bridge to the virtually solvable known case | FJ25 action |
|---|---|---|
| \(G\) is source-verified as virtually solvable | Directly matches the `ER-009` virtually solvable row | Subtract by `ER-009`. |
| \(G\) is proved internally to have a solvable finite-index subgroup | This is the definition of virtual solvability | Subtract by `ER-009`. |
| \(G\) is solvable, abelian, or finite-rank free abelian by an explicit proof | Solvable groups are virtually solvable, using the group itself as the finite-index subgroup | Subtract by `ER-009`; record overlap if it was already removed by another route. |
| \(G\) is locally indicable | Local indicability gives maps from finitely generated subgroups onto \(\mathbb Z\), not finite-index solvability | Do not subtract. |
| \(G_{\mathrm{ab}}\) is nontrivial or large | This concerns a quotient, not a finite-index solvable subgroup | Do not subtract. |
| \(G\) has a Magnus, HNN, or one-relator hierarchy | A hierarchy is structural data, not a virtual-solvability proof | Do not subtract by this route unless an additional virtual-solvability bridge is recorded. |
| \(G\) was already removed by the hyperbolic or CAT(0) route | The route may overlap with virtual solvability in examples | Do not double-count; keep the earliest or cleanest recorded route. |

### Interpretation for the T-001 residual

`FJ25` removes only torsion-free one-relator groups whose virtual solvability
is actually recorded.

It does not remove:

- all locally indicable torsion-free one-relator groups;
- all groups with nontrivial abelianization;
- all groups that split as HNN extensions;
- all one-relator hierarchy groups;
- any group merely expected to be virtually solvable.

**Warning.** The residual after `FJ25` is not a class of non-virtually-solvable
groups. It is the class not yet removed by the project-recorded virtually
solvable route.

## Proposition / Theorem / Conjecture / Example

**Proposition.** Let \(G\) be a torsion-free one-relator group. If the project
has a source-verified bridge showing that \(G\) is virtually solvable, then
\(G\) is removed from the `T-001` residual by the virtually solvable route.

**Proof.** The bridge places \(G\) in the virtually solvable group row of
`ER-009`. By Wegner's theorem, as recorded in `FJ11`, virtually solvable
groups satisfy the K-theoretic Farrell--Jones conjecture with coefficients in
additive categories in all degrees. Hence \(G\) is already covered by the
known-cases ledger and should not remain in the active residual target.

**Example.** The group
\[
G=\langle a,b\mid aba^{-1}b^{-1}\rangle
\]
is isomorphic to \(\mathbb Z^2\), since the single relator imposes the
commutation relation \([a,b]=1\). It is abelian, hence solvable, hence
virtually solvable. Therefore it is removed by the virtually solvable route if
it has not already been removed by an earlier route.

**Warning.** The example is illustrative and intentionally elementary. It is
not a classification of virtually solvable one-relator groups.

## Proof or verification

This module composes source-verified statements already in the repository.

1. `ER-009` and `FJ11` record Wegner's K- and L-theoretic Farrell--Jones
   theorem for virtually solvable groups with coefficients in additive
   categories.
2. `FJ19` records virtually solvable one-relator groups as a positive route
   only when virtual solvability is independently known.
3. `FJ19` records Howie's Brodskii-theorem source for local indicability of
   torsion-free one-relator groups and Lueck's open-status warning for locally
   indicable groups in the Full Farrell--Jones setting.
4. `FJ23` and `FJ24` remain the previously completed route subtractions.
   `FJ25` only changes the residual by the virtual-solvability criterion
   above.

## References

- Howie, J. (2000). A short proof of a theorem of Brodskii. *Publicacions
  Matematiques, 44*(2), 613--647. http://eudml.org/doc/41412
- Lueck, W. (2025). *Survey on the Farrell--Jones conjecture*
  (arXiv:2507.11337). arXiv. https://arxiv.org/abs/2507.11337
- Wegner, C. (2015). The Farrell-Jones conjecture for virtually solvable
  groups. *Journal of Topology, 8*(4), 975--1016.
  https://doi.org/10.1112/jtopol/jtv026

## Dependencies

This module depends on:

- `ER-009`;
- `FJ11`;
- `ER-012` and `FJ19`;
- `FJ23`;
- `FJ24`;
- `OQ-031`.

## Results produced

This module produced:

- a first-pass resolution of `OQ-031`;
- the virtually solvable-route subtraction table for `T-001`;
- a conservative warning that local indicability, abelianization, and HNN
  hierarchy data are not virtual-solvability bridges;
- no new `ER-*` result.

## Open questions generated

- Which source should the project use if it later needs a classification or
  recognition criterion for virtually solvable one-relator groups?
- Which part of the remaining `T-001` residual is removed by the
  hyperbolic-by-cyclic/free-by-cyclic route?

## Update to ledgers

After completion, update:

- `PROJECT_CHARTER.md` for the completed `FJ25` status and next `FJ26`;
- `README.md` for current progress;
- `SCOPE_LEDGER.md` for the virtually solvable-route subtraction and next
  question;
- `NOTATION_LEDGER.md` for virtually solvable-route terms;
- `OPEN_QUESTIONS.md` to mark `OQ-031` first-pass resolved and add the next
  route questions;
- `BIBLIOGRAPHY.md` and `ledgers/source_status.md` for `FJ25` source use;
- `ledgers/known_classes.md` for the `FJ25` use of the virtually solvable row;
- `ledgers/theorem_dependencies.md` for the completed `FJ25` row and next
  dependency row;
- `ledgers/open_group_classes.md` for the updated `T-001` residual status.
