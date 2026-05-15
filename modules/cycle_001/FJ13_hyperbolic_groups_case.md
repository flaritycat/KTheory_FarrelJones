# Module FJ13. Hyperbolic groups case

## Status

Completed

## Module type

Proof skeleton / Literature verification / Theorem map

## Problem

Understand the source-verified hyperbolic-groups case without importing
the full controlled-algebra proof as if it had been reconstructed
inside this repository.

## Input

This module uses:

- `FJ01` for the simplified K-theoretic assembly map.
- `FJ03` for classifying spaces for families.
- `FJ04` for \(\mathcal{VCyc}(G)\).
- `FJ11` for the known-cases row recording hyperbolic groups.
- `FJ12` for inheritance flags.

## Output target

A proof-strategy artifact for the hyperbolic-groups theorem:

- exact source-level theorem statement;
- the axiomatic reduction used by Bartels--Lueck--Reich;
- the hyperbolic verification via Rips complexes and boundary
  compactifications;
- the controlled-algebra proof architecture;
- warnings about what remains deferred to later modules.

## Definitions

### Definition. Hyperbolic group

In this module, "hyperbolic group" means word-hyperbolic group in the
sense of Gromov, following the convention stated by Bartels--Lueck--Reich
(Bartels, Lueck, & Reich, 2008, introduction). This module does not
develop the \(\delta\)-hyperbolic metric-space definition.

### Definition. Rips complex \(P_d(G)\)

For a finitely generated word-hyperbolic group \(G\) with a word
metric, Bartels--Lueck--Reich choose \(d>4\delta+6\) and use the Rips
complex \(P_d(G)\) as the simplicial \(G\)-space \(X\) in their
axiomatic theorem.

### Definition. Boundary compactification

For \(X=P_d(G)\), the source takes

\[
\overline X = X\cup \partial X
\]

to be the Gromov compactification used in the hyperbolic-group proof.

### Definition. Open \(\mathcal F\)-cover

For a \(G\)-space \(Y\) and a family \(\mathcal F\), an open
\(\mathcal F\)-cover is a \(G\)-invariant open cover whose translates
are either equal or disjoint and whose set stabilizers lie in
\(\mathcal F\). The wide-cover condition in Bartels--Lueck--Reich is a
strengthened form used with \(\mathcal F=\mathcal{VCyc}\).

### Warning. Proof-technology boundary

This module records a source-verified proof skeleton. It does not
construct the obstruction category, the transfer, the wide covers, or
the stability equivalence inside the repository. Those are deliberately
deferred to `FJ15`, `FJ16`, and `FJ17`.

## Main work

### The theorem to use

Bartels--Lueck--Reich prove that if \(G\) is hyperbolic, then \(G\)
satisfies the K-theoretic Farrell--Jones conjecture with coefficients:
for every additive category \(\mathcal A\) with right \(G\)-action and
every \(n\in\mathbb Z\), the assembly map

\[
H_n^G(E_{\mathcal{VCyc}}G;\mathbf K_{\mathcal A})
\longrightarrow
H_n^G(\mathrm{pt};\mathbf K_{\mathcal A})
\cong K_n(\mathcal A *_G \mathrm{pt})
\]

is an isomorphism. The source states that this implies the ordinary
K-theoretic Farrell--Jones conjecture for hyperbolic groups with
coefficients in an arbitrary associative unital ring \(R\) (Bartels,
Lueck, & Reich, 2008, Main Theorem).

### Axiomatic reduction

The source proves a general theorem for a finitely generated group
\(G\), a family \(\mathcal F\), and an additive category
\(\mathcal A\) with right \(G\)-action. If there are \(G\)-spaces
\(X\subseteq \overline X\) such that:

- \(X\) is the realization of an abstract simplicial complex;
- \(\overline X\) is compact, metrizable, and contractible;
- \(X\subseteq\overline X\) satisfies the source's weak \(Z\)-set
  condition;
- the source's wide-cover assumption holds for \(\mathcal F\);

then the assembly map over \(E_{\mathcal F}G\) is an isomorphism in
all degrees (Bartels, Lueck, & Reich, 2008, Theorem "Axiomatic
Formulation").

### Hyperbolic verification

For a word-hyperbolic group \(G\), Bartels--Lueck--Reich verify the
axiomatic hypotheses for \(\mathcal F=\mathcal{VCyc}\):

- choose \(X=P_d(G)\), a Rips complex for \(d>4\delta+6\);
- use the Gromov compactification \(\overline X=X\cup\partial X\);
- use the boundary \(Z\)-set input cited from Bestvina--Mess for the
  weak \(Z\)-set condition;
- use their equivariant-covers work for the wide-cover assumption.

With these ingredients, the hyperbolic-groups main theorem follows
from the axiomatic theorem (Bartels, Lueck, & Reich, 2008, Section 2).

### Controlled proof architecture

The source's proof outline can be read as the following chain:

1. Reformulate assembly as a continuous-controlled forget-control map.
2. Identify the homotopy fiber with the \(K\)-theory of an obstruction
   category.
3. Make the obstruction category functorial enough in metric
   \(G\)-spaces to vary the control space.
4. Use a transfer to replace \(G\) by \(G\times\overline X\), where
   \(\overline X\) is the compactified Rips complex.
5. Use \(G\)-invariant open covers of \(G\times\overline X\) and
   associated contracting maps.
6. Compensate for expansion in the \(\overline X\)-coordinate by the
   small-control gain supplied by the transfer.
7. Apply a stability theorem for the obstruction category to show that
   the obstruction vanishes.

The source explicitly says that this approach avoids the hard foliated
control theory while retaining transfers and a replacement for
geodesic-flow ideas through Mineyev-style flow technology and open
covers.

### Project-use conclusion

For this project, the safe use of `FJ13` is:

- `ER-009` remains the established known-cases result for hyperbolic
  groups;
- `FJ13` supplies a proof-skeleton expansion of that result;
- inheritance beyond hyperbolic groups should be routed through
  `FJ12`, not inferred informally from the introduction of the
  hyperbolic-groups paper;
- detailed controlled topology, flow-space/open-cover, and transfer
  mechanisms remain future modules.

## Proposition / Theorem / Conjecture / Example

### Source-verified claim. Hyperbolic groups satisfy K-theoretic Farrell--Jones with coefficients

Let \(G\) be a hyperbolic group. Then \(G\) satisfies the
K-theoretic Farrell--Jones conjecture with coefficients in additive
categories in all degrees, in the sense of Bartels--Lueck--Reich.

### Literature claim. Proof skeleton

The source proof proceeds by reducing the assembly isomorphism to an
axiomatic controlled-algebra theorem, verifying the axioms for
hyperbolic groups using Rips complexes, boundary compactifications,
weak \(Z\)-set input, and equivariant wide covers, and then proving the
axiomatic theorem through obstruction categories, transfers,
contracting maps, and stability.

## Proof or verification

This module does not prove the theorem internally. It verifies the
following source locations:

- Main Theorem: the coefficient K-theoretic Farrell--Jones statement
  for hyperbolic groups.
- Introduction, "A rough outline of the proof": obstruction category,
  transfer, open covers, contracting maps, and stability.
- Theorem "Axiomatic Formulation": the reduction from geometric control
  hypotheses to the assembly isomorphism.
- Section 2, "The case of a hyperbolic group": verification of the
  axiomatic hypotheses using the Rips complex \(P_d(G)\), the
  compactification \(X\cup\partial X\), the weak \(Z\)-set input, and
  the wide-cover theorem.

The proof dependency `Equivariant covers for hyperbolic groups` was
located through arXiv, but its Theorem 1.2 has not yet been checked
directly in this repository.

## References

- Bartels, A., Lueck, W., & Reich, H. (2008). The K-theoretic
  Farrell-Jones conjecture for hyperbolic groups. *Inventiones
  Mathematicae, 172*(1), 29--70.
  https://doi.org/10.1007/s00222-007-0093-7
- Bartels, A., Lueck, W., & Reich, H. (2006). *Equivariant covers for
  hyperbolic groups* (arXiv:math/0609685). arXiv.
  https://arxiv.org/abs/math/0609685

## Dependencies

This module depends on:

- `FJ01`: assembly-map target and nonconnective \(K\)-theory convention.
- `FJ03`: classifying spaces for families.
- `FJ04`: \(\mathcal{VCyc}(G)\).
- `FJ11`: known-cases ledger, especially `ER-009`.
- `FJ12`: inheritance-property version flags.

## Results produced

This module produced:

- No new established result number. This module expands the
  hyperbolic-groups row of `ER-009` with a proof-strategy map.

## Open questions generated

- Should `Equivariant covers for hyperbolic groups` be checked directly
  before `FJ16` uses wide covers?
- Which exact version of the obstruction category should `FJ15` adopt
  from Bartels--Lueck--Reich?

## Update to ledgers

After completion, update:

- `SCOPE_LEDGER.md` if scope changed;
- `NOTATION_LEDGER.md` if new notation was introduced;
- `ESTABLISHED_RESULTS.md` if a result was proved;
- `OPEN_QUESTIONS.md` if new open questions were created;
- `BIBLIOGRAPHY.md` if new sources were used;
- `ledgers/source_status.md` if source status changed.
