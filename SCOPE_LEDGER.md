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
- Consequences such as Whitehead group vanishing and projective class group consequences, after their hypotheses are recorded.
- Candidate unresolved group classes, especially Artin groups and torsion-free one-relator groups, after source verification.

## Out of scope

Unless explicitly imported later:

- Bass--Quillen as a primary path.
- Parshin conjecture as a primary path.
- Beilinson--Soulé vanishing as a primary path.
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

## Established results

- ER-001: For the trivial group \(G=1\), the simplified assembly map in module `FJ01` is the identity on \(K_n(R)\), assuming the black-box normalization of the equivariant homology theory.
- ER-002: Source-verified existence and homotopy characterization of \(E_{\mathcal F}G\) for project-style families of subgroups, using Lueck's Definition 1.8 and Theorem 1.9.
- ER-003: For every group \(G\), \(\mathcal{VCyc}(G)\) is a family of subgroups; infinite virtually cyclic groups are organized into type I/type II by the source-verified dichotomy.
- ER-004: For \(G=\mathbb Z\), the simplified assembly map is the identity under the point model for \(E_{\mathcal{VCyc}}\mathbb Z\), with target \(K_n(R[t,t^{-1}])\).
- ER-005: Source-verified Bass--Heller--Swan decomposition of \(K_n(R[\mathbb Z])\) into \(K_n(R)\), \(K_{n-1}(R)\), and two \(NK_n(R)\)-summands.

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

## Next mathematical move

Proceed to module `FJ08`: the Whitehead-group consequence, with hypotheses checked before any vanishing statement is recorded.
