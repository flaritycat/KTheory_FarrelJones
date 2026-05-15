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

## Established results

- ER-001: For the trivial group \(G=1\), the simplified assembly map in module `FJ01` is the identity on \(K_n(R)\), assuming the black-box normalization of the equivariant homology theory.
- ER-002: Source-verified existence and homotopy characterization of \(E_{\mathcal F}G\) for project-style families of subgroups, using Lueck's Definition 1.8 and Theorem 1.9.

## Current scope

The active mathematical scope is the simplified K-theoretic Farrell--Jones conjecture for group rings, with \(R\) an associative unital ring and \(G\) a discrete group.

## What has been established

- The initial project structure and cycle-001 module plan have been defined.
- Module `FJ01` states the simplified conjecture and proves the trivial-group example.
- Module `FJ03` defines classifying spaces for families, records the source-verified homotopy characterization, and connects \(E_{\mathcal{VCyc}}G\to\mathrm{pt}\) back to the simplified assembly map.

## Next mathematical move

Proceed to module `FJ04`: virtually cyclic groups, keeping the discussion structural and source-checked.
