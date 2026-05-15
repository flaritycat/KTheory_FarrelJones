# Project Charter

## Project title

**The Farrell--Jones Program in Algebraic K-Theory**

## Central aim

Develop a modular research program around the **K-theoretic Farrell--Jones conjecture**, beginning with the simplified group-ring formulation.

The goal is not to solve the full conjecture immediately. The goal is to build a rigorous, source-disciplined research archive that can eventually identify a concrete unresolved group class or reducible subcase where new progress may be possible.

## In-scope topics

- Algebraic \(K\)-theory of group rings \(R[G]\).
- The K-theoretic Farrell--Jones conjecture.
- Assembly maps.
- Classifying spaces for families of subgroups.
- Virtually cyclic subgroups.
- Equivariant homology theories, introduced only as needed.
- Known cases of Farrell--Jones.
- Inheritance properties.
- Consequences such as Whitehead group vanishing, projective class group consequences, and Borel-type rigidity, when their hypotheses are stated carefully.
- Candidate unresolved group classes, especially Artin groups and torsion-free one-relator groups, subject to source verification.

## Out-of-scope topics

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

## Standing assumptions

- \(R\) denotes an associative unital ring unless explicitly stated otherwise.
- \(G\) denotes a discrete group unless explicitly stated otherwise.
- A family of subgroups is closed under conjugation and passage to subgroups.
- The first working formulation is the simplified ring-coefficient version.
- The stronger additive-category formulation is deferred to module `FJ02`.
- \(L\)-theory is not active until explicitly introduced in an application module.

## Proof standard

Every serious mathematical claim should eventually be traceable to one of:

1. a proof inside the repository;
2. a cited theorem;
3. a labeled conjecture;
4. a labeled heuristic;
5. a labeled open problem;
6. a labeled failed attempt;
7. a source-verified literature statement.

A heuristic is not a proof. A conjecture is not a theorem. A literature theorem must be stated with hypotheses and source status.

## Citation standard

External sources should be recorded in APA style where practical, while preserving the project's additional source-status fields such as `found`, `to verify`, `partially read`, `verified`, `active reference`, `background only`, and `do not use`.

Internal repository dependencies may be cited by module or ledger path.

## Module-cycle protocol

The project proceeds in cycles:

```text
20 modules -> reflection -> 20 modules -> reflection -> ...
```

After 100 modules, perform a larger review.

Each module should produce a reusable artifact: a definition, proposition, proof, worked example, comparison table, bibliography entry, dependency diagram, known-cases ledger, source-status update, open problem, or correction.

## First milestone

Complete first-pass modules `FJ01`--`FJ07`, establishing:

1. the minimal K-theoretic statement;
2. the family \(\mathcal{VCyc}\);
3. classifying spaces \(E_{\mathcal{VCyc}}G\);
4. the trivial group example;
5. the infinite cyclic group example;
6. the role of Bass--Heller--Swan;
7. the reason Nil phenomena force virtually cyclic subgroups.

Current status: first-pass coverage has been completed for `FJ01` and
`FJ03`--`FJ07`. Module `FJ02`, the additive-category formulation, is
intentionally deferred until the project is ready to choose a precise
modern source and notation convention.

## Second milestone

Proceed through modules `FJ08`--`FJ12`, establishing:

1. carefully sourced consequences for Whitehead groups;
2. projective class group consequences, with exact hypotheses;
3. Borel-type consequences, without importing \(L\)-theory prematurely;
4. a known-classes ledger;
5. an inheritance-properties ledger.

Current status: `FJ08` and `FJ09` have first-pass coverage as
conditional theorem maps from Farrell--Jones to Whitehead-group
vanishing and to vanishing of \(\widetilde K_0(\mathbb Z[G])\),
including the finiteness-obstruction interpretation for finitely
presented groups.

## GitHub persistence policy

The GitHub repository `flaritycat/KTheory_FarrelJones` is the durable archive and source of truth.

Do not claim that something has been saved, committed, pushed, or updated in GitHub unless that action has actually occurred and been verified.
