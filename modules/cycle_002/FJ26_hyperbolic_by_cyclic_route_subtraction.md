# Module FJ26. Hyperbolic-by-cyclic route subtraction for T-001

## Status

Completed

## Module type

Theorem map / Attack surface / Literature verification

## Problem

Continue the route-subtraction pass for `T-001`, the torsion-free
one-relator residual gap analysis.

`FJ23` subtracts groups after a source-verified bridge to
word-hyperbolicity. `FJ24` subtracts groups after a source-verified bridge to
the finite-dimensional CAT(0)-group known case. `FJ25` subtracts groups after
a source-verified bridge to virtual solvability.

The next route is the hyperbolic-by-cyclic row recorded in `FJ19` and
`ledgers/known_classes.md`, based on Bestvina, Fujiwara, and Wigglesworth
(2023).

The delicate point is that one-relator groups often come with HNN splittings,
epimorphisms to \(\mathbb Z\), or hierarchy data. These are not automatically
mapping-torus certificates. The project should subtract a group by this route
only after the source hypotheses are actually matched.

## Input

This module uses:

- `ER-012` and `FJ19`, the one-relator status ledger;
- `ledgers/known_classes.md`, the hyperbolic-by-cyclic known-case row;
- `FJ23`, the hyperbolic-route subtraction;
- `FJ24`, the CAT(0)-route subtraction;
- `FJ25`, the virtually solvable-route subtraction;
- `OQ-035`;
- Bestvina--Fujiwara--Wigglesworth as already source-verified in `FJ19`;
- Brown's BNS-invariant paper only as a future source to verify for
  kernel-finiteness recognition, not as a theorem input here.

## Output target

A first-pass hyperbolic-by-cyclic/free-by-cyclic route subtraction table for
`T-001`:

- what is removed by a verified mapping-torus bridge;
- what is removed by a verified finite-rank free-by-cyclic bridge;
- what is not removed merely from an HNN splitting or an epimorphism to
  \(\mathbb Z\);
- what remains deferred to later kernel-recognition and inheritance modules.

## Definitions

**Definition.** In this module, a hyperbolic-by-cyclic group is a group of the
form
\[
H\rtimes_\Phi \mathbb Z
\]
where \(\Phi\colon H\to H\) is an automorphism and \(H\) is virtually
torsion-free hyperbolic.

**Definition.** A finite-rank free-by-cyclic group is a group of the form
\[
F_n\rtimes_\Phi \mathbb Z
\]
where \(F_n\) is a free group of finite rank and
\(\Phi\colon F_n\to F_n\) is an automorphism.

**Definition.** A hyperbolic-by-cyclic bridge is a source-verified statement,
or an internal elementary proof, showing that a group has the form
\(H\rtimes_\Phi\mathbb Z\) with \(H\) virtually torsion-free hyperbolic.

**Definition.** A finite-rank free-by-cyclic bridge is a source-verified
statement, or an internal elementary proof, showing that a group has the form
\(F_n\rtimes_\Phi\mathbb Z\) for \(n<\infty\).

**Definition.** A hyperbolic-by-cyclic route subtraction is a project
bookkeeping step: a torsion-free one-relator group is removed from the active
`T-001` residual once the project has a bridge to the Bestvina--Fujiwara--
Wigglesworth known-case row.

**Warning.** An HNN splitting is not the same thing as a mapping torus. A
general HNN extension identifies subgroups of a base group; the
hyperbolic-by-cyclic route requires a semidirect product by an automorphism of
the whole kernel/base group matching the source hypotheses.

**Warning.** An epimorphism \(G\to\mathbb Z\) is not enough. The kernel must
be identified with a virtually torsion-free hyperbolic group, or in the
finite-rank free-by-cyclic special case with \(F_n\) for \(n<\infty\).

**Warning.** The survey-level inheritance row for extensions with countable
free kernel is not used as the main FJ26 route. It belongs to a later
inheritance-subtraction pass unless a proof-sensitive source is traced.

## Main work

### Route principle

**Source-verified claim.** Bestvina, Fujiwara, and Wigglesworth prove the
K- and L-theoretic Farrell--Jones conjectures, in their source formulation
with coefficients in additive categories, for hyperbolic-by-cyclic groups
\(H\rtimes_\Phi\mathbb Z\) with \(H\) virtually torsion-free hyperbolic. This
is recorded in `FJ19` and `ledgers/known_classes.md` (Bestvina et al., 2023).

**Route principle.** Therefore, for `T-001`, any torsion-free one-relator
group that is independently source-verified as such a mapping torus is
removed from the active residual target.

**Route principle.** Finite-rank free-by-cyclic groups are included in this
route as recorded in `FJ19`, provided the project has a verified bridge to the
finite-rank free-by-cyclic form.

**Warning.** This route principle does not classify one-relator groups that
fiber over \(\mathbb Z\), and it does not decide whether a given epimorphism
has finitely generated free kernel.

### Subtraction table

| One-relator input | Bridge to the known case | FJ26 action |
|---|---|---|
| \(G\cong H\rtimes_\Phi\mathbb Z\), with \(H\) source-verified virtually torsion-free hyperbolic | Directly matches the Bestvina--Fujiwara--Wigglesworth row | Subtract by the hyperbolic-by-cyclic route. |
| \(G\cong F_n\rtimes_\Phi\mathbb Z\), with \(n<\infty\) | Recorded in `FJ19` as a finite-rank free-by-cyclic special case of the hyperbolic-by-cyclic route | Subtract by the hyperbolic-by-cyclic/free-by-cyclic route. |
| An exact sequence \(1\to F_n\to G\to\mathbb Z\to 1\), with \(n<\infty\), is proved or source-verified | The sequence splits over \(\mathbb Z\), giving \(G\cong F_n\rtimes\mathbb Z\) | Subtract by the finite-rank free-by-cyclic route. |
| \(G\to\mathbb Z\) is known, but the kernel is not identified | No bridge to a hyperbolic-by-cyclic source hypothesis | Do not subtract. |
| \(G\) has a one-relator HNN splitting | HNN structure is not by itself a semidirect product over \(\mathbb Z\) | Do not subtract unless the splitting is upgraded to a verified mapping-torus bridge. |
| \(G\) has countable free kernel over a quotient in Lueck's \(\mathcal{FJ}\) | This is an inheritance route from `FJ12`, not the Bestvina--Fujiwara--Wigglesworth mapping-torus row | Defer to the inheritance-route module. |
| \(G\) was already removed by the hyperbolic, CAT(0), or virtually solvable route | The routes may overlap in examples | Do not double-count; keep the cleanest recorded route. |

### Interpretation for the T-001 residual

`FJ26` removes only torsion-free one-relator groups whose
hyperbolic-by-cyclic or finite-rank free-by-cyclic structure is actually
recorded.

It does not remove:

- every group admitting a map onto \(\mathbb Z\);
- every locally indicable group;
- every one-relator HNN extension;
- every hierarchy group;
- groups whose free-by-cyclic status depends on an unverified BNS or kernel
  finiteness theorem.

**Warning.** The residual after `FJ26` is not a class of
non-hyperbolic-by-cyclic groups. It is the class not yet removed by the
project-recorded hyperbolic-by-cyclic/free-by-cyclic route.

## Proposition / Theorem / Conjecture / Example

**Proposition.** Let \(G\) be a torsion-free one-relator group. If the project
has a source-verified bridge showing that
\[
G\cong H\rtimes_\Phi\mathbb Z
\]
with \(H\) virtually torsion-free hyperbolic, then \(G\) is removed from the
`T-001` residual by the hyperbolic-by-cyclic route.

**Proof.** The bridge places \(G\) in the hyperbolic-by-cyclic row recorded in
`FJ19` and `ledgers/known_classes.md`. Bestvina, Fujiwara, and Wigglesworth
prove the relevant K- and L-theoretic Farrell--Jones statements in their
source formulation for such groups. Hence \(G\) is already covered by the
known-cases ledger and should not remain in the active residual target.

**Proposition.** Let \(G\) be a torsion-free one-relator group. If the project
has a source-verified exact sequence
\[
1\to F_n\to G\xrightarrow{p}\mathbb Z\to 1
\]
with \(n<\infty\), then \(G\) is removed from the `T-001` residual by the
finite-rank free-by-cyclic route.

**Proof.** Choose \(t\in G\) with \(p(t)=1\in\mathbb Z\). The assignment
\(1\mapsto t\) defines a section \(\mathbb Z\to G\). Since \(F_n=\ker(p)\) is
normal, conjugation by \(t\) defines an automorphism
\(\Phi\colon F_n\to F_n\). Every \(g\in G\) can be written uniquely as
\(ft^k\) with \(f\in F_n\) and \(k\in\mathbb Z\), so
\[
G\cong F_n\rtimes_\Phi\mathbb Z.
\]
This is a finite-rank free-by-cyclic group, which `FJ19` records as covered
by the Bestvina--Fujiwara--Wigglesworth route. Therefore the first proposition
applies.

**Warning.** The second proposition requires the finite-rank free-kernel
hypothesis. It does not say that every epimorphism from a torsion-free
one-relator group to \(\mathbb Z\) has finitely generated free kernel.

## Proof or verification

This module composes source-verified statements already in the repository
with the elementary splitting observation for extensions over \(\mathbb Z\).

1. `FJ19` records the Bestvina--Fujiwara--Wigglesworth theorem for
   hyperbolic-by-cyclic groups and records finite-rank free-by-cyclic groups
   as included in that route.
2. `FJ23`, `FJ24`, and `FJ25` remain the previous route subtractions.
   `FJ26` only changes the residual by the mapping-torus criteria above.
3. `FJ21` records Brown's BNS-invariant paper as a future source for
   kernel-finiteness and free-by-cyclic recognition, but this module does not
   use Brown as a theorem source.
4. `FJ12` and `FJ19` record survey-level inheritance rows for countable free
   kernels. `FJ26` does not use those rows as proof-sensitive mapping-torus
   subtractions.

## References

- Bestvina, M., Fujiwara, K., & Wigglesworth, D. (2023). The Farrell--Jones
  conjecture for hyperbolic-by-cyclic groups. *International Mathematics
  Research Notices, 2023*(7), 5887--5904.
  https://doi.org/10.1093/imrn/rnac012
- Brown, K. S. (1987). Trees, valuations, and the Bieri--Neumann--Strebel
  invariant. *Inventiones Mathematicae, 90*, 479--504.
  https://doi.org/10.1007/BF01389176
- Lueck, W. (2025). *Survey on the Farrell--Jones conjecture*
  (arXiv:2507.11337). arXiv. https://arxiv.org/abs/2507.11337

## Dependencies

This module depends on:

- `ER-012` and `FJ19`;
- `ledgers/known_classes.md`;
- `FJ23`;
- `FJ24`;
- `FJ25`;
- `OQ-035`.

## Results produced

This module produced:

- a first-pass resolution of `OQ-035`;
- the hyperbolic-by-cyclic/free-by-cyclic route subtraction table for
  `T-001`;
- a conservative warning that epimorphisms to \(\mathbb Z\), HNN splittings,
  and hierarchy data are not mapping-torus bridges by themselves;
- no new `ER-*` result.

## Open questions generated

- Which one-relator source should the project verify for recognizing
  finite-rank free kernels over \(\mathbb Z\)?
- Which source-verified inheritance routes should now be subtracted from the
  remaining `T-001` residual?

## Update to ledgers

After completion, update:

- `PROJECT_CHARTER.md` for the completed `FJ26` status and next `FJ27`;
- `README.md` for current progress;
- `SCOPE_LEDGER.md` for the hyperbolic-by-cyclic/free-by-cyclic route
  subtraction and next question;
- `NOTATION_LEDGER.md` for hyperbolic-by-cyclic route terms;
- `OPEN_QUESTIONS.md` to mark `OQ-035` first-pass resolved and add the next
  route questions;
- `BIBLIOGRAPHY.md` and `ledgers/source_status.md` for `FJ26` source use;
- `ledgers/known_classes.md` for the `FJ26` use of the
  hyperbolic-by-cyclic row;
- `ledgers/theorem_dependencies.md` for the completed `FJ26` row and next
  dependency row;
- `ledgers/open_group_classes.md` for the updated `T-001` residual status.
