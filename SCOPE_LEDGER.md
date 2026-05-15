# Scope Ledger

## In scope

- Algebraic \(K\)-theory of group rings \(R[G]\).
- The \(K\)-theoretic Farrell--Jones conjecture.
- Assembly maps.
- Classifying spaces for families of subgroups.
- Virtually cyclic subgroups.
- Equivariant homology theories, introduced initially as black boxes.
- Known cases of Farrell--Jones, after source verification.
- Inheritance properties, after source verification.
- Consequences such as Whitehead group vanishing, projective class group consequences, and Borel-type rigidity, after their hypotheses are recorded.
- Candidate unresolved group classes, especially Artin groups and torsion-free one-relator groups, after source verification.

## Out of scope

Unless explicitly imported later:

- Bass--Quillen as a primary path.
- Parshin conjecture as a primary path.
- Beilinson--Soule vanishing as a primary path.
- Arithmetic computation of \(K_n(\mathbb Z)\) as a primary path.
- Topological \(K\)-theory as a primary subject.
- \(C^*\)-algebra \(K\)-theory as a primary subject.
- Operator-algebra \(K\)-theory except for comparisons.
- Physics or materials-science applications.
- Mathematical content from previous chats.
- Any unsupported claim that Farrell--Jones is solved in full generality.

## Imported assumptions

- General rigor standards.
- Clear status labels.
- Careful notation.
- Explicit assumptions.
- Source checking for known theorems and open status.
- APA-style external citations, while preserving project source-status labels.
- \(L\)-theory may appear only as a clearly marked application dependency, as in `FJ10`.
- No hidden dependence on previous conversations.
- Algebraic \(K\)-theory is the chosen branch.
- Farrell--Jones is the chosen primary path.
- The project uses cycles of 20 modules.
- GitHub repository `flaritycat/KTheory_FarrelJones` is intended as the durable archive.

## Open questions

1. Which unresolved group class should become the first serious target?
2. How much \(L\)-theory should be introduced early?
3. How soon should spectra and equivariant homology be developed?
4. Can inheritance properties produce a useful new reduction?
5. Can we isolate a tractable Artin-group subclass not covered by existing known cases?
6. Can torsion-free one-relator groups be decomposed into known Farrell--Jones classes in useful cases?
7. Which modules produce original mathematical output rather than only literature organization?
8. Which source should serve as the main reference for the modern statement of Farrell--Jones?
9. Which model of nonconnective algebraic \(K\)-theory should be used for the all-integers formulation?
10. Which explicit example of nonzero \(NK_n(R)\) should be used if the project needs a concrete Nil obstruction?
11. Should the original Bass--Heller--Swan paper be checked directly, or is Weibel's monograph sufficient for the first-pass theorem ledger?
12. Which source should be used for geometric Whitehead torsion if later modules need topology-facing consequences?
13. Should Wall's finiteness obstruction theorem be verified from a primary or monograph source?
14. Which source should be used for surgery theory and topological structure sets if Borel rigidity becomes active beyond a theorem map?
15. Should negative \(K\)-group vanishing receive its own module?
16. Which additional known Farrell--Jones classes should be verified next after the first-pass `FJ11` table?
17. Which survey-level full \(\mathcal{FJ}\) inheritance rows from `FJ12` should be traced to primary proof sources before use in proof-sensitive reductions?
18. Which Bartels--Lueck--Reich proof dependencies should be checked directly before `FJ15`--`FJ17` develop obstruction categories, wide covers, and transfers?

## Established results

- ER-001: For the trivial group \(G=1\), the simplified assembly map in module `FJ01` is the identity on \(K_n(R)\), assuming the black-box normalization of the equivariant homology theory.
- ER-002: Source-verified existence and homotopy characterization of \(E_{\mathcal F}G\) for project-style families of subgroups, using Lueck's Definition 1.8 and Theorem 1.9.
- ER-003: For every group \(G\), \(\mathcal{VCyc}(G)\) is a family of subgroups; infinite virtually cyclic groups are organized into type I/type II by the source-verified dichotomy.
- ER-004: For \(G=\mathbb Z\), the simplified assembly map is the identity under the point model for \(E_{\mathcal{VCyc}}\mathbb Z\), with target \(K_n(R[t,t^{-1}])\).
- ER-005: Source-verified Bass--Heller--Swan decomposition of \(K_n(R[\mathbb Z])\) into \(K_n(R)\), \(K_{n-1}(R)\), and two \(NK_n(R)\)-summands.
- ER-006: Conditional Whitehead-group vanishing from the K-theoretic Farrell--Jones conjecture for torsion-free groups with regular coefficients.
- ER-007: Conditional vanishing of \(\widetilde K_0(\mathbb Z[G])\) from Farrell--Jones, with the finiteness-obstruction interpretation for finitely presented groups.
- ER-008: Conditional Borel consequence from low-dimensional K-theory vanishing and the \(L^{\langle -\infty\rangle}\)-theory assembly isomorphism.
- ER-009: First source-verified known Farrell--Jones classes: hyperbolic groups, finite-dimensional CAT(0)-groups, and virtually solvable groups, with version flags.
- ER-010: First source-verified inheritance-properties ledger, separating coefficient K-theory inheritance from survey-level closure properties of Lueck's full \(\mathcal{FJ}\) class.

## Current scope

The active mathematical scope is the simplified K-theoretic Farrell--Jones conjecture for group rings, with \(R\) an associative unital ring and \(G\) a discrete group.

## What has been established

- The initial project structure and cycle-001 module plan have been defined.
- Module `FJ01` states the simplified conjecture and proves the trivial-group example.
- Module `FJ03` defines classifying spaces for families, records the source-verified homotopy characterization, and connects \(E_{\mathcal{VCyc}}G\to\mathrm{pt}\) back to the simplified assembly map.
- Module `FJ04` records the finite/infinite and type I/type II structure of virtually cyclic groups, and proves that \(\mathcal{VCyc}(G)\) is a family.
- Module `FJ05` gives a standalone worked proof of the trivial-group example, expanding ER-001 without creating a duplicate result number.
- Module `FJ06` gives a standalone worked proof for \(G=\mathbb Z\), identifying \(R[\mathbb Z]\cong R[t,t^{-1}]\) after choosing a generator while deferring Bass--Heller--Swan to `FJ07`.
- Module `FJ07` records the Bass--Heller--Swan split exact sequence, introduces \(NK_n(R)\), and explains why Nil-terms force the virtually cyclic family for arbitrary coefficient rings.
- Module `FJ08` records the conditional Whitehead-group consequence of Farrell--Jones for torsion-free groups with regular coefficients.
- Module `FJ09` records the conditional projective class group consequence and the Wall finiteness-obstruction interpretation.
- Module `FJ10` records the Borel conjecture consequence as a source-verified theorem map requiring both K-theory vanishing and \(L^{\langle -\infty\rangle}\)-theory assembly.
- Module `FJ11` starts the known-classes ledger with source-verified rows for hyperbolic groups, finite-dimensional CAT(0)-groups, and virtually solvable groups.
- Module `FJ12` starts the inheritance-properties ledger with source-verified pullback, subgroup, and directed-colimit rows, plus survey-level full \(\mathcal{FJ}\) closure rows marked by version.
- Module `FJ13` records the hyperbolic-groups proof skeleton from Bartels--Lueck--Reich: main theorem, axiomatic reduction, Rips-complex verification, and controlled-algebra architecture.

## Next mathematical move

Proceed to module `FJ14`: the CAT(0)-groups case, using the version flags in `FJ11` and `FJ12` and deferring detailed proof machinery unless the source theorem requires it.
