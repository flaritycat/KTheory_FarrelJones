# Module FJ30. Brown/BNS kernel-recognition verification for T-001

## Status

Completed

## Module type

Literature verification / Theorem map / Attack surface

## Problem

Verify whether Brown (1987), selected in `FJ29`, supplies a usable
finite-generation or finite-rank free-kernel criterion for the `RB-004`
attack surface in `T-001`.

The target bridge is:

\[
1\to F_n\to G\to \mathbb Z\to 1,\qquad n<\infty,
\]

because `FJ26` already records that such a bridge places \(G\) in the
finite-rank free-by-cyclic route.

## Input

This module uses:

- `FJ26`, the finite-rank free-by-cyclic route;
- `FJ29`, the selection of `RB-004`;
- `ledgers/t001_residual.md`;
- `OQ-036` and `OQ-041`;
- Brown's paper, accessed through the EuDML bibliographic record and GDZ full
  text;
- the EuDML bibliographic record for Bieri--Neumann--Strebel (1987), as the
  original source behind the BNS invariant.

## Output target

Produce:

- a source-verified Brown theorem map for kernel recognition;
- a clear statement of what Brown does and does not prove for `RB-004`;
- a reusable kernel-recognition ledger;
- the next project move after FJ30.

## Definitions

**Definition.** In Brown's source setting, the character sphere \(S(G)\) is
formed from nonzero homomorphisms \(\chi\colon G\to\mathbb R\) modulo
positive scalar multiplication.

**Definition.** Brown's BNS/HNN-valuation recognition problem asks whether a
class \([\chi]\in S(G)\) lies in the Bieri--Neumann--Strebel invariant,
equivalently in Brown's HNN-valuation formulation.

**Definition.** For `RB-004`, a Brown-positive kernel-recognition bridge is
a source-verified check that both \([\chi]\) and \([-\chi]\) satisfy Brown's
criterion for the relevant invariant. For a surjection
\(\chi\colon G\to\mathbb Z\), this is the input Brown uses to conclude that
\(\ker(\chi)\) is finitely generated.

**Warning.** Brown (1987) does not give the project a global positive theorem
that every one-relator epimorphism to \(\mathbb Z\) has finitely generated
kernel.

**Warning.** Brown's most explicit one-relator criterion is for two-generator
one-relator presentations. Applying it to an arbitrary torsion-free
one-relator group requires a verified compatible presentation or an additional
source.

## Main work

### Source access and status

The EuDML record identifies Brown's paper as:

Brown, K. S. (1987). *Trees, valuations, and the Bieri--Neumann--Strebel
invariant*. *Inventiones Mathematicae, 90*, 479--504.

The GDZ full text was checked for:

- Section 3, Proposition 3.1 and Corollary 3.2;
- Section 4, Theorems 4.2, 4.3, and 4.4;
- Section 5, Theorem 5.2 and the following finite-generation remark.

### Verified theorem map

**Source-verified claim.** Brown's Proposition 3.1 states, for a finitely
generated group \(G\) and a surjection \(\chi\colon G\to\mathbb Z\), an
equivalence among:

- an ascending HNN decomposition with finitely generated base group and
  associated homomorphism \(\chi\);
- absence of a properly descending HNN decomposition with associated
  homomorphism \(\chi\);
- absence of a nontrivial HNN valuation \(v\) with \(\chi=\chi_v\).

Brown also records that, when these conditions hold, every HNN decomposition
with associated homomorphism \(\chi\) is ascending (Brown, 1987).

**Source-verified claim.** Brown's Corollary 3.2 states that if
\(\chi\colon G\to\mathbb Z\) is a surjection from a finitely generated group,
then \(\ker(\chi)\) is finitely generated if and only if both \(\chi\) and
\(-\chi\) satisfy the conditions of Proposition 3.1 (Brown, 1987).

**Source-verified claim.** Brown's Section 4 gives a computable criterion
for two-generator one-relator groups. For
\[
G=\langle x,y\mid r\rangle
\]
with \(r\) cyclically reduced and nontrivial, Brown's Theorem 4.3 describes
membership in the invariant using the sequence of values \(\chi(s_i)\) on the
proper initial segments \(s_i\) of \(r\). If \(\chi(x)\) and \(\chi(y)\) are
both nonzero, the relevant maximum condition is that the maximum occur exactly
once. If one of the two values is zero, the relevant maximum condition is that
the maximum occur exactly twice (Brown, 1987).

**Source-verified claim.** Brown's Theorem 4.4 restates the two-generator
criterion geometrically using the convex hull of the lattice path traced by
the relator. Non-horizontal/non-vertical characters correspond to supporting
lines meeting the convex hull in a simple vertex; horizontal or vertical
characters correspond to a special edge (Brown, 1987).

**Source-verified claim.** Brown's Theorem 5.2 identifies the invariant
defined through HNN valuations with the Bieri--Neumann--Strebel invariant for
finitely generated groups (Brown, 1987). The Bieri--Neumann--Strebel original
paper is recorded as a source to verify directly before the project uses its
general normal-subgroup theorem outside Brown's restatement.

### Consequence for RB-004

For the project, Brown gives the following usable recognition workflow.

1. Start with a source-verified one-relator presentation and an epimorphism
   \(\chi\colon G\to\mathbb Z\).
2. If the presentation is two-generator, use Brown's Theorem 4.3 or 4.4 to
   test both \([\chi]\) and \([-\chi]\).
3. If both pass Brown's criterion, Brown's Corollary 3.2 gives that
   \(\ker(\chi)\) is finitely generated.
4. In the one-relator HNN setup reviewed by Brown, the two-sided ascending
   situation gives a free kernel; if the kernel is also finitely generated,
   it is a finite-rank free group.
5. A verified finite-rank free kernel gives the exact bridge required by
   `FJ26`.

Thus Brown is a genuine positive tool for selected `RB-004` cases. It is not
a global solution to the torsion-free one-relator target.

### Non-results and cautions

Brown does not provide, by itself:

- a theorem that every torsion-free one-relator group maps to
  \(\mathbb Z\);
- a theorem that every such map has finitely generated kernel;
- a Farrell--Jones theorem;
- a replacement for the `FJ26` finite-rank free-by-cyclic route;
- a proof that an arbitrary one-relator presentation is compatible with the
  two-generator criterion.

## Proposition / Theorem / Conjecture / Example

**Proposition.** Brown (1987) gives a source-verified kernel-recognition
criterion usable for `RB-004` in the following limited sense: for a
source-verified two-generator one-relator presentation and an epimorphism
\(\chi\colon G\to\mathbb Z\), Brown's criteria can be used to test whether
\(\ker(\chi)\) is finitely generated; when the one-relator HNN setup gives a
free kernel, this yields a finite-rank free-by-cyclic bridge into `FJ26`.

**Proof.** Brown's Corollary 3.2 reduces finite generation of
\(\ker(\chi)\), for a finitely generated group and surjection to
\(\mathbb Z\), to checking both \(\chi\) and \(-\chi\) against Proposition
3.1. Brown's Theorems 4.3 and 4.4 give explicit tests for the relevant
invariant in two-generator one-relator groups. The one-relator HNN discussion
in Brown's Section 3 supplies the free-kernel interpretation in the two-sided
ascending case. Therefore a case passing Brown's two-sided test supplies the
finite-rank free-kernel bridge required by `FJ26`.

**Warning.** The proposition is a theorem map, not a new Farrell--Jones
result. It should not receive an `ER-*` number.

## Proof or verification

Verification steps completed:

1. Checked the EuDML record for Brown (1987) and the GDZ full text linked
   from EuDML.
2. Checked Brown's Proposition 3.1 and Corollary 3.2 for the ascending HNN
   and finite-kernel-generation criterion.
3. Checked Brown's Theorems 4.2--4.4 for the two-generator one-relator
   computation.
4. Checked Brown's Theorem 5.2 for the identification with the
   Bieri--Neumann--Strebel invariant.
5. Created `ledgers/t001_kernel_recognition.md` to store the project-facing
   route criterion.

## References

- Bieri, R., Neumann, W. D., & Strebel, R. (1987). A geometric invariant of
  discrete groups. *Inventiones Mathematicae, 90*, 451--478.
  https://doi.org/10.1007/BF01389175
- Brown, K. S. (1987). Trees, valuations, and the
  Bieri--Neumann--Strebel invariant. *Inventiones Mathematicae, 90*, 479--504.
  https://doi.org/10.1007/BF01389176

Internal references:

- `modules/cycle_002/FJ26_hyperbolic_by_cyclic_route_subtraction.md`
- `modules/cycle_002/FJ29_residual_attack_surface_selection.md`
- `ledgers/t001_residual.md`

## Dependencies

This module depends on:

- `FJ26`;
- `FJ29`;
- Brown (1987);
- EuDML/GDZ access to Brown's full text;
- the Bieri--Neumann--Strebel original paper as background for the invariant,
  not yet as an independently checked theorem source.

## Results produced

This module produced:

- a first-pass resolution of `OQ-041`;
- a Brown/BNS kernel-recognition theorem map for `RB-004`;
- `ledgers/t001_kernel_recognition.md`;
- no new `ER-*` result.

## Open questions generated

- Which first two-generator one-relator presentation should be tested with
  Brown's criterion?
- Should the original Bieri--Neumann--Strebel normal-subgroup theorem be
  checked directly before the project uses Brown beyond infinite-cyclic
  quotients?
- Which source handles `RB-004` cases that do not admit a suitable
  two-generator presentation?

## Update to ledgers

After completion, update:

- `PROJECT_CHARTER.md` for the completed `FJ30` status and next `FJ31`;
- `README.md` for current progress;
- `SCOPE_LEDGER.md` for the Brown criterion and new open questions;
- `NOTATION_LEDGER.md` for Brown/BNS terms;
- `OPEN_QUESTIONS.md` to mark `OQ-041` first-pass resolved and generate next
  questions;
- `BIBLIOGRAPHY.md` and `ledgers/source_status.md` for Brown and
  Bieri--Neumann--Strebel;
- `ledgers/t001_residual.md` and `ledgers/t001_kernel_recognition.md`;
- `ledgers/open_group_classes.md` and `ledgers/theorem_dependencies.md`;
- `references/papers_to_read.md`.
