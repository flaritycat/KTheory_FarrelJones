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

## FJ32 selected next test case

| Presentation | Character | Preliminary Brown result | Kernel bridge | Route status |
|---|---|---|---|---|
| \(G_{2,3}=\langle x,y\mid x^2y^{-3}\rangle\) | \(\chi(x)=3,\ \chi(y)=2\) | \([\chi]\) and \([-\chi]\) preliminarily pass the nonzero-on-both-generators maximum-count test | not yet recorded; `FJ33` must decide whether the kernel is finite-rank free | selected for next worked Brown test |

The `FJ32` row is a selection row, not a completed route row. It may not be
used to invoke the `FJ26` finite-rank free-by-cyclic route until `FJ33` or a
later module records the missing kernel bridge.

## Next action

Use `FJ33` to run the worked Brown test for \(G_{2,3}\) and determine whether
the kernel bridge required by `FJ26` can be recorded.
