# Module FJ09. Projective class group consequence

## Status

Completed, first pass

## Module type

Application / Theorem map / Literature verification

## Problem

Explain the projective class group consequence of the K-theoretic
Farrell--Jones conjecture, and separate it from the Whitehead-group
consequence recorded in `FJ08`.

In this module, the main algebraic object is

\[
\widetilde K_0(\mathbb Z[G]).
\]

The main geometric interpretation is Wall's finiteness obstruction for
finitely dominated CW complexes.

## Input

- `FJ08`, for the conditional vanishing of
  \(\mathrm{Wh}_0^R(G)\) and its specialization
  \(\mathrm{Wh}_0^{\mathbb Z}(G)=\widetilde K_0(\mathbb Z[G])\).
- Lueck--Reich, Section 1.1, for the definition of reduced algebraic
  \(K\)-groups and the low-dimensional Farrell--Jones consequences
  (Lueck & Reich, 2004).
- Lueck--Reich, Section 1.2.2, for the finiteness obstruction
  interpretation of \(\widetilde K_0(\mathbb Z[G])\) (Lueck & Reich,
  2004).

## Output target

A source-verified theorem map recording:

- the definition of \(\widetilde K_0(\mathbb Z[G])\);
- the conditional Farrell--Jones consequence
  \(\widetilde K_0(\mathbb Z[G])=0\);
- the finiteness-obstruction interpretation for finitely presented
  groups;
- the distinction between this consequence and the classical Whitehead
  group \(\mathrm{Wh}(G)\).

## Definitions

### Definition: reduced algebraic \(K\)-group

For a ring \(A\), Lueck--Reich define the reduced algebraic \(K\)-group
\(\widetilde K_n(A)\) as the cokernel of the natural map

\[
K_n(\mathbb Z)\longrightarrow K_n(A).
\]

For \(A=\mathbb Z[G]\), this gives

\[
\widetilde K_0(\mathbb Z[G])
=
\operatorname{coker}\bigl(K_0(\mathbb Z)\to K_0(\mathbb Z[G])\bigr).
\]

In the notation of `FJ08`, this group is

\[
\mathrm{Wh}_0^{\mathbb Z}(G).
\]

This module calls \(\widetilde K_0(\mathbb Z[G])\) the **reduced
projective class group** of \(\mathbb Z[G]\), following the project
convention. If a later module needs a competing convention for
projective class groups, it must record the difference explicitly.

### Definition: finitely dominated CW complex

A CW complex \(X\) is **finitely dominated** if there is a finite CW
complex \(Y\) and maps

\[
X\to Y\to X
\]

whose composite is homotopic to the identity on \(X\).

Lueck--Reich use this notion in their discussion of Wall's finiteness
obstruction (Lueck & Reich, 2004, Section 1.2.2).

### Definition: finiteness obstruction

For a finitely dominated CW complex \(X\), Wall's finiteness obstruction
is an element

\[
o(X)\in \widetilde K_0(\mathbb Z[\pi_1(X)]).
\]

Lueck--Reich state that \(X\) is homotopy equivalent to a finite CW
complex if and only if \(o(X)=0\), and that every element of
\(\widetilde K_0(\mathbb Z[G])\) is realized as a finiteness obstruction
provided \(G\) is finitely presented (Lueck & Reich, 2004, Theorem 1.8).

## Main work

### Algebraic consequence

By `FJ08`, if \(G\) is torsion free, \(R\) is regular, and the relevant
K-theoretic Farrell--Jones statement holds, then

\[
\mathrm{Wh}_0^R(G)=0.
\]

Taking \(R=\mathbb Z\), which is regular in Lueck--Reich's sense, gives

\[
\mathrm{Wh}_0^{\mathbb Z}(G)=0.
\]

Using the identification

\[
\mathrm{Wh}_0^{\mathbb Z}(G)=\widetilde K_0(\mathbb Z[G]),
\]

we obtain

\[
\widetilde K_0(\mathbb Z[G])=0.
\]

This is the projective class group consequence.

### Geometric interpretation

Let \(G\) be finitely presented. Lueck--Reich state that the vanishing of
\(\widetilde K_0(\mathbb Z[G])\) is equivalent to the assertion that every
finitely dominated CW complex \(X\) with

\[
\pi_1(X)\cong G
\]

is homotopy equivalent to a finite CW complex (Lueck & Reich, 2004,
Consequence 1.9).

Thus, if \(G\) is torsion free, finitely presented, and satisfies the
relevant K-theoretic Farrell--Jones statement with \(R=\mathbb Z\), then
every finitely dominated CW complex with fundamental group \(G\) has the
homotopy type of a finite CW complex.

### Warning: this is not \(\mathrm{Wh}(G)\)

The group \(\widetilde K_0(\mathbb Z[G])\) is the \(K_0\)-level reduced
projective class group. The classical Whitehead group \(\mathrm{Wh}(G)\)
lives at \(K_1\)-level and was treated in `FJ08`.

Both vanish under the same torsion-free regular-coefficient
Farrell--Jones hypotheses, but they control different phenomena:

- \(\mathrm{Wh}(G)\) is tied to Whitehead torsion and \(s\)-cobordism;
- \(\widetilde K_0(\mathbb Z[G])\) is tied to Wall finiteness
  obstruction.

## Proposition / Theorem / Conjecture / Example

### Source-verified theorem map: projective class group consequence

Let \(G\) be torsion free. Assume the K-theoretic Farrell--Jones assembly
statement in the torsion-free regular-ring form used by Lueck--Reich for
\(R=\mathbb Z\). Then

\[
\widetilde K_0(\mathbb Z[G])=0.
\]

If, in addition, \(G\) is finitely presented, then every finitely
dominated CW complex \(X\) with \(\pi_1(X)\cong G\) is homotopy
equivalent to a finite CW complex.

### Warning: conditional status

This is a theorem map, not a proof that all torsion-free groups satisfy
Farrell--Jones. The group must be known to satisfy the relevant
K-theoretic Farrell--Jones statement before this consequence may be used.

## Proof or verification

The algebraic part follows from `FJ08`: under the stated torsion-free and
regularity hypotheses, Farrell--Jones implies
\(\mathrm{Wh}_0^R(G)=0\). Setting \(R=\mathbb Z\) and using the
source-verified identification

\[
\mathrm{Wh}_0^{\mathbb Z}(G)=\widetilde K_0(\mathbb Z[G])
\]

gives the claimed projective class group vanishing.

The finiteness-obstruction consequence follows from Lueck--Reich's
Consequence 1.9, which states the equivalence between
\(\widetilde K_0(\mathbb Z[G])=0\) and finite CW homotopy type for
finitely dominated CW complexes with finitely presented fundamental group
\(G\).

No direct proof of Wall's finiteness obstruction theorem is attempted in
this module.

## References

- Lueck, W., & Reich, H. (2004). *The Baum-Connes and the Farrell-Jones
  conjectures in K- and L-theory* (arXiv:math/0402405). arXiv.
  https://arxiv.org/abs/math/0402405

No new external source beyond Lueck--Reich is used in this module.

## Dependencies

This module depends on:

- `FJ08`, for the \(\mathrm{Wh}_0^R(G)\) theorem map;
- Lueck--Reich (2004), Section 1.1 for reduced algebraic \(K\)-groups;
- Lueck--Reich (2004), Theorem 1.8 and Consequence 1.9 for Wall
  finiteness obstruction.

## Results produced

This module produced:

- ER-007: conditional vanishing of \(\widetilde K_0(\mathbb Z[G])\)
  from Farrell--Jones, with the finiteness-obstruction interpretation for
  finitely presented groups.

## Open questions generated

- Should the project later verify Wall's finiteness obstruction theorem
  from a primary or monograph source, rather than relying on the
  Lueck--Reich survey?

## Update to ledgers

After completion, update:

- `SCOPE_LEDGER.md`: record completion of `FJ09` and move the next target
  to `FJ10`.
- `NOTATION_LEDGER.md`: add \(\widetilde K_n(A)\), \(o(X)\), and
  finitely dominated CW complex notation.
- `ESTABLISHED_RESULTS.md`: add ER-007.
- `OPEN_QUESTIONS.md`: add the Wall finiteness obstruction source
  question.
- `BIBLIOGRAPHY.md`: update the Lueck--Reich usage note.
- `ledgers/source_status.md`: update Lueck--Reich source status for
  `FJ09`.
