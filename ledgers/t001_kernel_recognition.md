# T-001 Kernel-Recognition Ledger

## Status

Created in `FJ30`.

## Warning

This ledger records source-verified recognition criteria for selected
`RB-004` cases. It does not claim that every torsion-free one-relator
epimorphism to \(\mathbb Z\) has finitely generated kernel.

## Brown/BNS route

| Item | Project status | Source |
|---|---|---|
| Character-sphere and HNN-valuation formulation | Brown checked at first-pass level | Brown (1987), Sections 3 and 5 |
| Kernel finite-generation criterion for a surjection \(G\to\mathbb Z\) | Brown checked at first-pass level | Brown (1987), Corollary 3.2 |
| Two-generator one-relator computable criterion | Brown checked at first-pass level | Brown (1987), Theorems 4.2--4.4 |
| Original BNS invariant paper | bibliographically located; direct theorem use deferred | Bieri--Neumann--Strebel (1987) |

## Project-facing route criterion

For a torsion-free one-relator group \(G\), a map
\(\chi\colon G\to\mathbb Z\) enters the `FJ26` finite-rank free-by-cyclic
route after all of the following have been recorded:

1. a source-verified presentation compatible with Brown's criterion, currently
   best understood for two-generator one-relator presentations;
2. Brown's criterion verifies both \([\chi]\) and \([-\chi]\);
3. the project records that the resulting kernel is a finite-rank free group;
4. the exact sequence
   \[
   1\to F_n\to G\to \mathbb Z\to 1
   \]
   is written with \(n<\infty\).

## Do not use as

- a global proof for all torsion-free one-relator groups;
- a proof that every epimorphism to \(\mathbb Z\) has finitely generated
  kernel;
- a Farrell--Jones theorem;
- a replacement for the `FJ26` route.

## FJ31 calibration example

| Presentation | Character | Brown result | Kernel bridge | Route status |
|---|---|---|---|---|
| \(\langle x,y\mid xyx^{-1}y^{-1}\rangle\) | \(\chi(x)=1,\ \chi(y)=0\) | \([\chi]\) and \([-\chi]\) pass the zero-on-one-generator maximum-count test | \(\ker(\chi)=\langle y\rangle\cong F_1\), and \(G\cong F_1\rtimes\mathbb Z\) | Calibration only; already removed by the virtually solvable route |

Use of this row is limited to workflow calibration. It verifies that the
Brown test has been translated correctly into project bookkeeping, but it
does not subtract a new residual case from `T-001`.

## Next action

Use `FJ32` to choose a nontrivial Brown test case or small family, preferably
one not already removed by the virtually solvable route.
