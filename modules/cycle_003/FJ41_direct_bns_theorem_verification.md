# Module FJ41. Direct BNS theorem verification for RB-004

## Status

Completed

## Module type

Literature verification / Theorem map / Attack surface

## Problem

Cycle 002 ended with a beyond-Brown source gap. Brown (1987) gives a
computable two-generator one-relator route for selected kernels, and
Karrass--Solitar (1978) gives a bridge when a nontrivial normal subgroup is
already finitely presented. The remaining question is whether the original
Bieri--Neumann--Strebel source itself gives a directly usable
finite-generation criterion for `RB-004` cases outside Brown's checked
two-generator computation.

This module verifies the original BNS theorem statement and hypotheses before
the project uses the BNS invariant as a theorem source.

## Input

This module uses:

- `FJ30`, Brown/BNS kernel-recognition verification;
- `FJ38`, beyond-Brown source-cluster selection;
- `FJ39`, normal-subgroup bridge verification;
- `FJ40`, finitely presented-kernel test selection;
- `reflections/cycle_002_reflection.md`;
- `ledgers/t001_kernel_recognition.md`;
- `ledgers/t001_residual.md`;
- `OQ-058`;
- Bieri--Neumann--Strebel (1987), pages 451--452;
- Brown (1987), as the already checked comparison source.

## Output target

Produce:

- a source-verified statement of the original BNS finite-generation theorem;
- a project-facing consequence for epimorphisms \(G\to\mathbb Z\);
- a decision on whether direct BNS use removes a current `RB-004` residual
  bucket;
- updates to the source, notation, open-question, residual, and
  kernel-recognition ledgers.

## Definitions

**Definition.** For a finitely generated group \(G\), the BNS character sphere
\(S(G)\) is the set of nonzero homomorphisms \(G\to\mathbb R\), modulo
multiplication by positive real scalars (Bieri, Neumann, & Strebel, 1987,
p. 451).

**Definition.** If \(H\leq G\), define
\[
S(G,H)=\{[\chi]\in S(G):\chi(H)=0\}.
\]
Bieri--Neumann--Strebel define this subset before Theorem B on page 452
(Bieri et al., 1987).

**Definition.** In this module, \(\Sigma(G)\) denotes the original BNS
invariant in the sense of Bieri--Neumann--Strebel (1987). The project may
later reconcile this notation with modern \(\Sigma^1(G)\) conventions, but
this module uses the original source only for the finite-generation theorem.

**Warning.** Direct BNS theorem use is not the same as a computation of
\(\Sigma(G)\). The theorem gives a criterion once the relevant character
rays are known to lie in the invariant.

## Main work

### Source access and status

The EuDML/GDZ record identifies the source as:

Bieri, R., Neumann, W. D., & Strebel, R. (1987). *A geometric invariant of
discrete groups*. *Inventiones Mathematicae, 90*, 451--478.

GDZ full text for pages 451--452 was checked. Page 451 gives the definition
of \(S(G)\) and introduces the invariant as a subset of \(S(G)\). Page 452
states Theorem B and Theorem B1.

### Verified theorem map

**Source-verified claim.** Bieri--Neumann--Strebel Theorem B1 has the
following project-facing form. Let \(G\) be finitely generated, and let
\(N\trianglelefteq G\) be a normal subgroup such that \(G/N\) is abelian.
Then \(N\) is finitely generated if and only if
\[
S(G,N)\subseteq \Sigma(G).
\]
In particular, \(G'\) is finitely generated if and only if
\(\Sigma(G)=S(G)\) (Bieri et al., 1987, p. 452).

**Consequence.** If \(\chi\colon G\twoheadrightarrow \mathbb Z\) is a
surjection from a finitely generated group, then
\[
S(G,\ker\chi)=\{[\chi],[-\chi]\}.
\]
Thus BNS Theorem B1 gives:
\[
\ker(\chi)\text{ is finitely generated}
\quad\Longleftrightarrow\quad
[\chi]\in\Sigma(G)\text{ and }[-\chi]\in\Sigma(G).
\]

This recovers the same two-sided finite-generation shape used in Brown's
Corollary 3.2, but the original BNS theorem does not by itself provide
Brown's two-generator one-relator computation of membership in the invariant.

### Consequence for RB-004

Direct BNS use is now theorem-available for finite-generation checks of
normal subgroups with abelian quotient. For `RB-004`, this is valuable but
not yet a route subtraction:

- it applies to finitely generated ambient groups \(G\);
- it applies to normal \(N\) with \(G/N\) abelian;
- for epimorphisms \(G\to\mathbb Z\), it gives the two-sided
  \([\chi]\), \([-\chi]\) criterion;
- it does not compute \(\Sigma(G)\) for any new one-relator family;
- it does not prove that a finitely generated kernel is free;
- it does not prove finite rank unless a separate freeness or finite-rank
  bridge is recorded.

Therefore direct BNS theorem verification resolves the source-status part of
`OQ-058`, but it does not produce a concrete new non-Brown `RB-004` family
from the current repository state.

### Next source pressure

The next useful step should not be another broad claim that "BNS applies."
The project now needs either:

- a source or computation of \(\Sigma(G)\) outside Brown's checked
  two-generator one-relator criterion; or
- a primary-source check of Bieri (1976) or Bieri--Renz (1988) if a
  finite-presentation or \(\mathrm{FP}_2\) bridge becomes route-relevant.

The cycle-003 plan already names Bieri (1976) and Bieri--Renz (1988) as the
next possible normal-subgroup finiteness sources. This module selects Bieri
(1976) as the next verification target because `FJ39` used it only as a cited
dependency inside Karrass--Solitar.

## Proposition / Theorem / Conjecture / Example

**Proposition.** Bieri--Neumann--Strebel (1987) is now verified as a direct
finite-generation theorem source for normal subgroups \(N\trianglelefteq G\)
with \(G\) finitely generated and \(G/N\) abelian. For a surjection
\(\chi\colon G\to\mathbb Z\), it gives finite generation of \(\ker(\chi)\)
exactly when both \([\chi]\) and \([-\chi]\) lie in the BNS invariant.

**Proof.** The first sentence is BNS Theorem B1 as checked on page 452. If
\(\chi\colon G\twoheadrightarrow\mathbb Z\), then a nonzero character
\(\psi\colon G\to\mathbb R\) vanishes on \(\ker(\chi)\) exactly when it
factors through \(G/\ker(\chi)\cong\mathbb Z\). Up to positive scalar
multiplication there are exactly two nonzero real characters of
\(\mathbb Z\): the positive and negative directions. Hence
\(S(G,\ker\chi)=\{[\chi],[-\chi]\}\), and Theorem B1 gives the stated
criterion.

**Warning.** This proposition is a source-verified theorem map, not a new
Farrell--Jones theorem and not a residual subtraction.

## Proof or verification

Verification steps completed:

1. Checked the EuDML bibliographic record for Bieri--Neumann--Strebel
   (1987).
2. Checked GDZ full text for the article range and page 451 definition of
   \(S(G)\).
3. Checked GDZ full text page 452 for Theorem B1 and its exact hypotheses:
   \(G\) finitely generated, \(N\trianglelefteq G\), and \(G/N\) abelian.
4. Derived the rank-one quotient consequence for
   \(\chi\colon G\twoheadrightarrow\mathbb Z\).
5. Compared the result with the Brown route already recorded in `FJ30`,
   without expanding Brown's theorem-use scope.

## References

- Bieri, R., Neumann, W. D., & Strebel, R. (1987). A geometric invariant of
  discrete groups. *Inventiones Mathematicae, 90*, 451--478.
  https://doi.org/10.1007/BF01389175
- Brown, K. S. (1987). Trees, valuations, and the
  Bieri--Neumann--Strebel invariant. *Inventiones Mathematicae, 90*, 479--504.
  https://doi.org/10.1007/BF01389176

Internal references:

- `modules/cycle_002/FJ30_brown_bns_kernel_recognition.md`
- `modules/cycle_002/FJ38_rb004_beyond_brown_source_selection.md`
- `modules/cycle_002/FJ39_normal_subgroup_bridge_source_verification.md`
- `modules/cycle_002/FJ40_finitely_presented_kernel_test_selection.md`
- `reflections/cycle_002_reflection.md`
- `ledgers/t001_kernel_recognition.md`
- `ledgers/t001_residual.md`

## Dependencies

This module depends on:

- `FJ30`;
- `FJ38`;
- `FJ39`;
- `FJ40`;
- `OQ-058`;
- Bieri--Neumann--Strebel (1987);
- Brown (1987), only as a checked comparison source.

## Results produced

This module produced:

- direct source verification of BNS Theorem B1 for project use;
- a rank-one quotient consequence for kernels of surjections to
  \(\mathbb Z\);
- a notation update for \(S(G,N)\) and \(\Sigma(G)\);
- a partial resolution of `OQ-058`: direct BNS theorem use is available, but
  no concrete new non-Brown family is produced;
- no new `ER-*` result;
- no residual subtraction.

## Open questions generated

- Which source or computation gives usable BNS-invariant membership outside
  Brown's checked two-generator one-relator criterion?
- What exact theorem in Bieri (1976) is needed for normal subgroups of
  cohomological-dimension-\(2\) groups, and does it require finite generation,
  finite presentation, \(\mathrm{FP}_2\), or another finiteness property?

## Update to ledgers

After completion, update:

- `PROJECT_CHARTER.md` for completed `FJ41` and next `FJ42`;
- `README.md` for current progress;
- `SCOPE_LEDGER.md` for `OQ-058`, the new source-computation question, and
  next procedural target;
- `NOTATION_LEDGER.md` for \(S(G,N)\) and \(\Sigma(G)\);
- `OPEN_QUESTIONS.md`;
- `BIBLIOGRAPHY.md`;
- `ledgers/source_status.md`;
- `ledgers/t001_kernel_recognition.md`;
- `ledgers/t001_residual.md`;
- `ledgers/open_group_classes.md`;
- `ledgers/theorem_dependencies.md`;
- `references/papers_to_read.md`.
