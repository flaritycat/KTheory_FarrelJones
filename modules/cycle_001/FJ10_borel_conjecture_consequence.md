# Module FJ10. Borel conjecture consequence

## Status

Completed, first pass

## Module type

Application / Theorem map / Literature verification

## Problem

Map the implication from Farrell--Jones-type assembly statements to
topological rigidity of closed aspherical manifolds.

This module must not pretend that the Borel conjecture is a purely
K-theoretic consequence. In the source used here, the implication uses:

- low-dimensional K-theory vanishing, including \(\mathrm{Wh}(G)\),
  \(\widetilde K_0(\mathbb Z[G])\), and negative \(K\)-groups;
- the \(L^{\langle -\infty\rangle}\)-theoretic Farrell--Jones assembly
  isomorphism;
- surgery theory.

## Input

- `FJ08`, for the Whitehead-group part of the low-dimensional
  K-theory vanishing package.
- `FJ09`, for the \(\widetilde K_0(\mathbb Z[G])\) part of the same
  package.
- Lueck--Reich, Section 1.5, for the torsion-free
  \(L^{\langle -\infty\rangle}\)-theoretic Farrell--Jones statement
  (Lueck & Reich, 2004).
- Lueck--Reich, Theorem 1.28, for the theorem map from K-theoretic
  vanishing plus \(L\)-theory assembly to the Borel conjecture
  (Lueck & Reich, 2004).

## Output target

A source-verified theorem map recording:

- the Borel conjecture statement used by the source;
- the precise hypotheses in Lueck--Reich's Theorem 1.28;
- the role of K-theory vanishing from `FJ08` and `FJ09`;
- the required \(L\)-theory assembly input;
- a warning that this module imports \(L\)-theory only as a marked
  application dependency.

## Definitions

### Definition: aspherical space

A CW complex or manifold is **aspherical** if its universal cover is
contractible. In that case, if \(\pi_1(X)=G\), the space \(X\) is a model
for \(BG\) (Lueck & Reich, 2004, Section 1.6.1).

### Definition: Borel conjecture, source form

Lueck--Reich state the Borel conjecture as follows: if

\[
f\colon M\to N
\]

is a homotopy equivalence between aspherical closed topological
manifolds, then \(f\) is homotopic to a homeomorphism. In particular,
closed aspherical manifolds with isomorphic fundamental groups are
homeomorphic (Lueck & Reich, 2004, Conjecture 1.27).

### Definition: \(L^{\langle -\infty\rangle}\)-theory assembly

For a torsion-free group \(G\), Lueck--Reich formulate the
\(L\)-theoretic Farrell--Jones statement as the assertion that

\[
H_n(BG;\mathbf L^{\langle -\infty\rangle}(\mathbb Z))
\longrightarrow
L_n^{\langle -\infty\rangle}(\mathbb ZG)
\]

is an isomorphism for all \(n\in\mathbb Z\), using the trivial involution
on \(\mathbb Z\) and the induced involution \(g\mapsto g^{-1}\) on
\(\mathbb ZG\) (Lueck & Reich, 2004, Conjecture 1.19).

This is an \(L\)-theory input, not part of the active K-theory core.

### Definition: topological structure set

For a closed topological manifold \(M\), the topological structure set
\(S^{\mathrm{top}}(M)\) consists of equivalence classes of homotopy
equivalences

\[
f\colon M'\to M
\]

from closed topological manifolds \(M'\), where equivalence is by
homeomorphism over \(M\) up to homotopy. Lueck--Reich recall that, for a
closed aspherical manifold, the Borel conjecture is equivalent to
\(S^{\mathrm{top}}(M)\) being a singleton (Lueck & Reich, 2004, Section
1.6.1).

## Main work

### Source-verified theorem map

Lueck--Reich's Theorem 1.28 states the following implication.

Let \(G\) be torsion free. Suppose:

1. \(\mathrm{Wh}(G)=0\);
2. \(\widetilde K_0(\mathbb Z[G])=0\);
3. \(K_{-i}(\mathbb Z[G])=0\) for all \(i\geq 1\);
4. the assembly map

   \[
   H_n(BG;\mathbf L^{\langle -\infty\rangle}(\mathbb Z))
   \longrightarrow
   L_n^{\langle -\infty\rangle}(\mathbb ZG)
   \]

   is an isomorphism for all \(n\).

Then the Borel conjecture holds for all orientable closed aspherical
topological manifolds of dimension at least \(5\) whose fundamental group
is \(G\) (Lueck & Reich, 2004, Theorem 1.28).

### Relation to earlier modules

Modules `FJ08` and `FJ09` record the first two K-theoretic inputs as
conditional Farrell--Jones consequences:

\[
\mathrm{Wh}(G)=0
\]

and

\[
\widetilde K_0(\mathbb Z[G])=0.
\]

The negative \(K\)-group vanishing

\[
K_{-i}(\mathbb Z[G])=0\quad (i\geq 1)
\]

is part of Lueck--Reich's low-dimensional K-theory package, but this
project has not yet given it its own module. This module therefore lists
negative \(K\)-group vanishing as a required K-theoretic input, not as an
internally established result.

The \(L^{\langle -\infty\rangle}\)-theory assembly isomorphism is a
separate input. It is imported here only as a source-verified application
dependency.

### Surgery-theoretic bridge

Lueck--Reich explain that the Borel conjecture can be reformulated as
the assertion that \(S^{\mathrm{top}}(M)\) is a singleton for an
aspherical closed topological manifold \(M\). The surgery exact sequence
relates this structure set to normal invariants and \(L\)-groups.

Under the K-theoretic vanishing hypotheses, the relevant \(L\)-theory
decorations can be compared. Under the
\(L^{\langle -\infty\rangle}\)-assembly isomorphism, the surgery
obstruction maps have the injectivity and bijectivity properties needed
to force \(S^{\mathrm{top}}(M)\) to be a singleton. This is the
source-verified bridge from Farrell--Jones-type assembly statements to
Borel rigidity.

No surgery-theory proof is attempted in this repository at this stage.

## Proposition / Theorem / Conjecture / Example

### Source-verified theorem map: Borel consequence

Let \(G\) be torsion free. Assume:

- \(\mathrm{Wh}(G)=0\);
- \(\widetilde K_0(\mathbb Z[G])=0\);
- \(K_{-i}(\mathbb Z[G])=0\) for all \(i\geq 1\);
- the \(L^{\langle -\infty\rangle}\)-theory assembly map for
  \(\mathbb ZG\) is an isomorphism in all degrees.

Then the Borel conjecture holds for all orientable closed aspherical
topological manifolds of dimension at least \(5\) with fundamental group
\(G\).

### Warning: not a K-only consequence

This module does not establish Borel rigidity from the K-theoretic
Farrell--Jones conjecture alone. It records that K-theory supplies
low-dimensional vanishing inputs, while \(L\)-theory and surgery supply
the rigidity mechanism.

## Proof or verification

The theorem map is verified from Lueck--Reich, Theorem 1.28. Their
statement explicitly assumes torsion-freeness, vanishing of
\(\mathrm{Wh}(G)\), \(\widetilde K_0(\mathbb Z[G])\), and negative
\(K\)-groups, plus the \(L^{\langle -\infty\rangle}\)-theory assembly
isomorphism in all degrees. Their conclusion is the Borel conjecture for
orientable manifolds of dimension at least \(5\) with fundamental group
\(G\).

The relationship between this theorem map and the topological structure
set is also verified from Lueck--Reich's discussion following Theorem
1.28.

## References

- Lueck, W., & Reich, H. (2004). *The Baum-Connes and the Farrell-Jones
  conjectures in K- and L-theory* (arXiv:math/0402405). arXiv.
  https://arxiv.org/abs/math/0402405

No new external source beyond Lueck--Reich is used in this module.

## Dependencies

This module depends on:

- `FJ08`, for the conditional Whitehead-group vanishing input;
- `FJ09`, for the conditional projective class group vanishing input;
- Lueck--Reich (2004), Conjecture 1.19, Conjecture 1.27, Proposition
  1.23, and Theorem 1.28.

## Results produced

This module produced:

- ER-008: source-verified Borel consequence theorem map, conditional on
  low-dimensional K-theory vanishing and \(L^{\langle -\infty\rangle}\)
  assembly.

## Open questions generated

- Which source should be used for a proof-level account of the surgery
  exact sequence and topological structure set?
- Should negative \(K\)-group vanishing for \(\mathbb Z[G]\) receive its
  own module before later topology applications?

## Update to ledgers

After completion, update:

- `SCOPE_LEDGER.md`: record completion of `FJ10` and move the next target
  to `FJ11`.
- `NOTATION_LEDGER.md`: add \(BG\), \(S^{\mathrm{top}}(M)\), and
  \(L_n^{\langle -\infty\rangle}(\mathbb ZG)\).
- `ESTABLISHED_RESULTS.md`: add ER-008.
- `OPEN_QUESTIONS.md`: add surgery-source and negative-\(K\) questions.
- `BIBLIOGRAPHY.md`: update the Lueck--Reich usage note.
- `ledgers/source_status.md`: update Lueck--Reich source status for
  `FJ10`.
