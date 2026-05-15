# Module FJ12. Inheritance properties ledger

## Status

Completed

## Module type

Theorem map / Literature verification

## Problem

Catalog closure properties of Farrell--Jones groups without treating
all formulations of the conjecture as interchangeable.

## Input

This module uses the cycle-001 standing conventions:

- \(R\) is an associative unital ring unless otherwise specified.
- \(G\) is a discrete group.
- \(\mathcal{VCyc}(G)\) is the family of virtually cyclic subgroups.
- The internal additive-category formulation remains deferred to `FJ02`.

## Output target

A first inheritance-properties ledger for:

- pullbacks along group homomorphisms;
- subgroups;
- directed colimits;
- finite direct products;
- extensions;
- free products;
- finite-index overgroups;
- graph products, recorded only as a survey-level row.

## Definitions

### Definition. Pullback family

Let \(\Phi\colon K\to G\) be a group homomorphism and let
\(\mathcal F\) be a family of subgroups of \(G\). The pullback family is

\[
\Phi^*\mathcal F
=
\{H\leq K:\Phi(H)\in\mathcal F\}.
\]

This is the notation used by Bartels and Reich in their inheritance
section for the coefficient version of the Farrell--Jones conjecture
(Bartels & Reich, 2007, Section 4).

### Definition. Source-specific class \(\mathcal{FJ}\)

In Lueck's survey, a Farrell--Jones group is a group satisfying the
Full Farrell--Jones Conjecture, and \(\mathcal{FJ}\) denotes the class
of those groups (Lueck, 2025, Definition "Farrell-Jones group"). The
source's full formulation includes finite wreath products and the
K-theoretic, L-theoretic, and higher-categorical coefficient versions.

### Warning. Version flag

The project has not yet adopted the full additive-category formulation
internally. Therefore rows in this module have a version column. A row
marked "coefficients" may be used only after its coefficient hypotheses
are satisfied. A row marked "full \(\mathcal{FJ}\)" is a source-level
survey statement about Lueck's full class, not a proof inside this
repository.

## Main work

The source check separates three kinds of inheritance information.

1. Bartels and Reich prove a pullback principle for the Farrell--Jones
   conjecture with coefficients in additive categories: if the assembly
   map for \(G\) over a family \(\mathcal F\) is injective or
   surjective for every additive category with \(G\)-action, then the
   corresponding assembly map for \(K\) over \(\Phi^*\mathcal F\) has
   the same injectivity or surjectivity property for every additive
   category with \(K\)-action (Bartels & Reich, 2007, Section 4,
   Corollary `cor:Inheritance-for-group-homoeomorphisms`).

2. Bartels and Reich derive subgroup inheritance for the coefficient
   K-theoretic Farrell--Jones conjecture: if the coefficient assembly
   statement for \(G\) over \(\mathcal{VCyc}\) is injective or
   surjective for every additive category with \(G\)-action, then the
   corresponding statement holds for every subgroup \(H\leq G\) and
   every additive category with \(H\)-action (Bartels & Reich, 2007,
   Section 4, Theorem `thm:FJ-w-C-passes-to-subgroups-alg-K`).

3. Bartels, Echterhoff, and Lueck prove directed-colimit inheritance
   for the K-theoretic Farrell--Jones assembly in a form that must be
   read carefully. The source allows a ring \(R\) with the induced
   group actions and writes targets as \(K_n(R\rtimes H)\). For
   arbitrary directed systems, they assume the assembly isomorphism for
   all subgroups of every \(G_i\) and conclude it for every subgroup of
   the colimit. If all structure maps are injective, it is enough to
   assume the assembly isomorphism for each \(G_i\), and then the
   colimit group satisfies it (Bartels, Echterhoff, & Lueck, 2007,
   Theorem "Inheritance under colimits").

Lueck's 2025 survey records a compact list of inheritance properties
for the full class \(\mathcal{FJ}\): subgroups, finite direct products,
extensions under a specified preimage condition for infinite cyclic
subgroups, directed colimits with arbitrary structure maps, free
products, finite-index overgroups, and graph products (Lueck, 2025,
Theorem "Status of the Full Farrell-Jones Conjecture").

The machine-readable project ledger is `ledgers/inheritance_properties.md`.

## Proposition / Theorem / Conjecture / Example

### Source-verified claim. Pullback and subgroup inheritance with coefficients

For the K-theoretic Farrell--Jones conjecture with coefficients in
additive categories, Bartels--Reich's pullback theorem implies
subgroup inheritance. The injective and surjective parts are inherited
separately.

### Source-verified claim. Directed colimit inheritance

For the K-theoretic Farrell--Jones assembly considered by Bartels,
Echterhoff, and Lueck, with the source's \(R\rtimes H\) target
convention, directed colimits are inherited with the following caution:

- arbitrary structure maps require hypotheses for all subgroups of the
  source groups;
- injective structure maps allow the simpler hypothesis for the source
  groups themselves.

### Literature claim. Full \(\mathcal{FJ}\) closure table

Lueck's survey states that the full class \(\mathcal{FJ}\) is closed
under the rows recorded in `ledgers/inheritance_properties.md`. The
project records this as a source-verified survey statement, while
leaving primary-source proof tracing open for later modules.

## Proof or verification

The module does not prove the inheritance theorems. It verifies and
records their hypotheses from the cited sources.

- Bartels--Reich Section 4 was checked for the definition of
  \(\Phi^*\mathcal F\), the equivalence of assembly maps under
  induction/restriction, the pullback corollary, and the subgroup
  theorem for K-theory with coefficients.
- Bartels--Echterhoff--Lueck's theorem "Inheritance under colimits" was
  checked for the distinction between arbitrary directed systems and
  injective directed systems.
- Lueck's 2025 survey was checked for the definition of the full class
  \(\mathcal{FJ}\) and the list of inheritance properties in the
  theorem "Status of the Full Farrell-Jones Conjecture."

No external theorem is restated here without its version flag.

## References

- Bartels, A., Echterhoff, S., & Lueck, W. (2007). *Inheritance of
  isomorphism conjectures under colimits* (arXiv:math/0702460). arXiv.
  https://arxiv.org/abs/math/0702460
- Bartels, A., & Reich, H. (2007). Coefficients for the Farrell-Jones
  conjecture. *Advances in Mathematics, 209*(1), 337--362.
  https://doi.org/10.1016/j.aim.2006.05.004
- Lueck, W. (2025). *Survey on the Farrell-Jones conjecture*
  (arXiv:2507.11337). arXiv. https://arxiv.org/abs/2507.11337

## Dependencies

This module depends on:

- `FJ01` for the simplified assembly-map target.
- `FJ03` for classifying spaces for families.
- `FJ04` for the family \(\mathcal{VCyc}(G)\).
- `FJ11` for the known-cases ledger and version-flag convention.

## Results produced

This module produced:

- `ER-010`: first source-verified inheritance-properties ledger.
- Updated `ledgers/inheritance_properties.md`.

## Open questions generated

- Should the survey-level full \(\mathcal{FJ}\) closure rows be
  traced to primary sources before they are used in proof-sensitive
  reductions for Artin groups or one-relator groups?

## Update to ledgers

After completion, update:

- `SCOPE_LEDGER.md` if scope changed;
- `NOTATION_LEDGER.md` if new notation was introduced;
- `ESTABLISHED_RESULTS.md` if a result was proved;
- `OPEN_QUESTIONS.md` if new open questions were created;
- `BIBLIOGRAPHY.md` if new sources were used;
- `ledgers/source_status.md` if source status changed.
