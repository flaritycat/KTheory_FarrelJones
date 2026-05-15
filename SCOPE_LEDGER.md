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
- Cycle reflections are required between 20-module cycles.
- GitHub repository `flaritycat/KTheory_FarrelJones` is intended as the durable archive.

## Open questions

1. Which unresolved group class should become the first serious target? First-pass resolved by `FJ20`: `T-001`, torsion-free one-relator residual gap analysis.
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
19. Which Bartels--Lueck geodesic-flow cover lemmas and Wegner transfer lemmas should be checked directly before `FJ16`--`FJ17` use the CAT(0) proof machinery?
20. Which primary source should be adopted as the canonical project reference for obstruction categories and continuous-control conditions before `FJ17` uses them proof-sensitively?
21. Which Mineyev flow-space results must be checked directly before the project uses hyperbolic flow estimates proof-sensitively?
22. Which transfer-category model should become canonical before the project uses transfer proofs in detail?
23. Which Artin-group subclasses remain outside the `FJ18` verified ledger?
24. Which source should reconcile `FJCw`, `FICwF`, and the project's simplified K-theory formulation?
25. Can Wu's clique-reduction route isolate a tractable Artin target not already covered by the verified rows?
26. Is there a global K-theoretic Farrell--Jones theorem for all torsion-free one-relator groups in a weaker formulation than Full Farrell--Jones?
27. Which one-relator structure theorem should become the canonical reduction tool if one-relator groups become the first serious target? First-pass resolved by `FJ21` source selection and `FJ22` hierarchy-vocabulary selection.
28. Which exact hierarchy theorem should `FJ22` adopt from the selected one-relator source toolkit? First-pass resolved by `FJ22`: Linton's finite one-relator complex hierarchy theorem.
29. Which classical Magnus hierarchy source must be checked for proof-sensitive use?
30. Which torsion-free one-relator groups survive after subtracting hyperbolic, finite-dimensional CAT(0), virtually solvable, and hyperbolic-by-cyclic routes?
31. Which part of `T-001` is already removed by the hyperbolic route once `FJ22` is combined with `ER-009`? First-pass resolved by `FJ23`.
32. Which part of the `T-001` residual is removed by the finite-dimensional CAT(0) route, including any virtual-special bridge? First-pass resolved by `FJ24`.
33. Which part of the `T-001` residual is removed by the virtually solvable route? First-pass resolved by `FJ25`.
34. Which finite-index source should support proof-sensitive use of virtually compact special routes?
35. Which one-relator groups are compact special beyond the hyperbolic route?
36. Which source should classify or recognize the virtually solvable one-relator cases if the project needs enumeration beyond conditional route bookkeeping?
37. Which part of the `T-001` residual is removed by the hyperbolic-by-cyclic/free-by-cyclic route? First-pass resolved by `FJ26`.
38. Which one-relator source should the project verify for recognizing finite-rank free kernels over \(\mathbb Z\)? First-pass source selected by `FJ29`: Brown (1987).
39. Which source-verified inheritance routes remove additional cases from the remaining `T-001` residual? First-pass resolved by `FJ27`.
40. What is the conservative `T-001` residual ledger after subtracting the named routes and version-aware inheritance routes? First-pass resolved by `FJ28`.
41. Which concrete surviving one-relator subclasses should become the next attack surface? First-pass resolved by `FJ29`: `RB-004`, finite-rank free-kernel recognition over \(\mathbb Z\).
42. Which source should be checked first for the selected residual bucket? First-pass resolved by `FJ29`: Brown (1987), without theorem-use status.
43. What exact theorem in Brown (1987), if any, gives a finite-generation or finite-rank free-kernel criterion for one-relator epimorphisms to \(\mathbb Z\)? First-pass resolved by `FJ30`: Brown's Proposition 3.1, Corollary 3.2, and Theorems 4.2--4.4 give a limited two-generator recognition route.
44. Which first two-generator one-relator presentation should be tested with Brown's criterion?
45. Should the original Bieri--Neumann--Strebel normal-subgroup theorem be checked directly before broader use?
46. Which source handles `RB-004` cases outside Brown's two-generator criterion?

## Established results

- ER-001: For the trivial group \(G=1\), the simplified assembly map in module `FJ01` is the identity on \(K_n(R)\), assuming the black-box normalization of the equivariant homology theory.
- ER-002: Source-verified existence and homotopy characterization of \(E_{\mathcal F}G\) for project-style families of subgroups, using Lueck's Definition 1.8 and Theorem 1.9.
- ER-003: For every group \(G\), \(\mathcal{VCyc}(G)\) is a family of subgroups; infinite virtually cyclic groups are organized into type I/type II by the source-verified dichotomy.
- ER-004: For \(G=\mathbb Z\), the simplified assembly map is the identity under the point model for \(E_{\mathcal{VCyc}}\mathbb Z\), with target \(K_n(R[t,t^{-1}])\).
- ER-005: Source-verified Bass--Heller--Swan decomposition of \(K_n(R[\mathbb Z])\) into \(K_n(R)\), \(K_{n-1}(R)\), and two \(NK_n(R)\)-summands.
- ER-006: Conditional Whitehead-group vanishing from the K-theoretic Farrell--Jones conjecture for torsion-free groups with regular coefficients.
- ER-007: Conditional vanishing of \(\widetilde K_0(\mathbb Z[G])\) from Farrell--Jones, with the finiteness-obstruction interpretation for finitely presented groups.
- ER-008: Conditional Borel consequence from low-dimensional K-theory vanishing and the \(L^{\langle -\infty\rangle}\)-theory assembly isomorphism.
- ER-009: First source-verified known Farrell--Jones classes: hyperbolic groups, finite-dimensional CAT(0)-groups, and virtually solvable groups, with version flags and first-pass proof-route maps for hyperbolic and CAT(0)-groups.
- ER-010: First source-verified inheritance-properties ledger, separating coefficient K-theory inheritance from survey-level closure properties of Lueck's full \(\mathcal{FJ}\) class.
- ER-011: First source-verified Artin-group Farrell--Jones subclass ledger, recording FC-type Artin groups, even FC-type Artin groups, RAAG-related semidirect products, Wu's even-Artin clique and join constructions, and Roushon's listed finite real, complex, and affine types under exact source hypotheses.
- ER-012: First source-verified one-relator-group Farrell--Jones status ledger, recording conditional routes through hyperbolic, finite-dimensional CAT(0), virtually solvable, and hyperbolic-by-cyclic classes, while keeping the global torsion-free one-relator class unresolved inside the project.

## Current scope

The active mathematical scope is the simplified K-theoretic Farrell--Jones conjecture for group rings, with \(R\) an associative unital ring and \(G\) a discrete group.

The active project target is `T-001`, torsion-free one-relator residual gap analysis.

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
- Module `FJ14` records the CAT(0)-groups proof skeleton from Wegner: K-theory theorem, strong transfer reducibility route, strong homotopy actions, CAT(0) flow-space-cover dependency, and comparison with the hyperbolic case.
- Module `FJ15` records a controlled-algebra vocabulary primer: control spaces, obstruction categories, controlled morphisms, controlled maps, and the gain-control strategy behind the proof skeletons.
- Module `FJ16` records a flow-spaces primer: flows, flow spaces, open \(\mathcal F\)-covers, long covers in the flow direction, hyperbolic equivariant covers, and CAT(0) flow-space covers.
- Module `FJ17` records a transfers primer: transfer maps, strong homotopy actions, strong transfer reducibility, contracting transfers, and the projection identity that lets transferred control information return to the original obstruction class.
- Module `FJ18` records an Artin groups dossier: source-verified Farrell--Jones subclass rows, method routes through Helly groups and normally poly-free groups, Roushon's corrected finite/affine/complex-type list, and remaining Artin-gap questions.
- Module `FJ19` records a torsion-free one-relator groups dossier: a source-verified warning that the global class remains open for Full Farrell--Jones, the structural local-indicability theorem, verified conditional routes through known classes, and the remaining one-relator target-selection questions.
- Module `FJ20` selects `T-001`, torsion-free one-relator residual gap analysis, as the first serious target. This is a project-selection result rather than a mathematical theorem.
- `reflections/cycle_001_reflection.md` closes the first twenty-module cycle and sets `FJ21`, one-relator structure source selection, as the next mathematical move.
- Module `FJ21` selects the first-pass one-relator structure source toolkit for `T-001`: Linton's one-relator hierarchy work, Linton's hyperbolic one-relator bridge source, and a classical-source verification queue.
- Module `FJ22` records the first-pass one-relator hierarchy vocabulary for `T-001` and adopts Linton's finite one-relator complex hierarchy theorem as the canonical structure theorem for the next residual-gap modules.
- Module `FJ23` records the first-pass hyperbolic-route subtraction for `T-001`: torsion-free one-relator groups are removed from the active residual target once a source-verified bridge to word-hyperbolicity is available.
- Module `FJ24` records the first-pass finite-dimensional CAT(0)-route subtraction for `T-001`, including compact finite-dimensional special cube complex groups as bridge cases and leaving merely virtual-special statements conditional on finite-index handling.
- Module `FJ25` records the first-pass virtually solvable-route subtraction for `T-001`, subtracting only groups with a source-verified or internally proved virtual-solvability bridge and rejecting local indicability, abelianization data, and HNN hierarchy structure as insufficient by themselves.
- Module `FJ26` records the first-pass hyperbolic-by-cyclic/free-by-cyclic route subtraction for `T-001`, subtracting only groups with a source-verified mapping-torus bridge or finite-rank free-by-cyclic bridge and rejecting bare epimorphisms to \(\mathbb Z\), HNN splittings, and hierarchy data as insufficient by themselves.
- Module `FJ27` records the first-pass source-verified inheritance-route subtraction for `T-001`, subtracting only groups with exact inheritance bridges and preserving the distinction between coefficient K-theory rows, K-theory directed-colimit rows, and full \(\mathcal{FJ}\) survey rows.
- Module `FJ28` records the first-pass conservative residual ledger for `T-001`, creating `ledgers/t001_residual.md` and organizing unremoved project-state cases into source-recognition buckets rather than negative Farrell--Jones classes.
- Module `FJ29` selects `RB-004`, finite-rank free-kernel recognition over \(\mathbb Z\), as the next concrete attack surface for `T-001`, and selects Brown (1987) as the first source to verify without treating it as theorem input yet.
- Module `FJ30` verifies Brown (1987) as a first-pass Brown/BNS kernel-recognition source for selected `RB-004` cases and creates `ledgers/t001_kernel_recognition.md`; it records that Brown supplies a computable two-generator one-relator criterion, not a global positive theorem for all one-relator epimorphisms.

## Selected target

`T-001`: torsion-free one-relator residual gap analysis.

The next mathematical cycle should identify which torsion-free one-relator
groups remain after subtracting the verified hyperbolic, finite-dimensional
CAT(0), virtually solvable, hyperbolic-by-cyclic/free-by-cyclic, and
source-verified inheritance routes.

Current source toolkit:

- primary modern hierarchy source: Linton's `One-relator hierarchies`;
- adopted first-pass hierarchy theorem: Linton's finite one-relator complex
  hierarchy theorem from `One-relator hierarchies`;
- route subtractions completed: hyperbolic route in `FJ23`,
  finite-dimensional CAT(0) route in `FJ24`, and virtually solvable route in
  `FJ25`, hyperbolic-by-cyclic/free-by-cyclic route in `FJ26`, and
  version-aware inheritance route in `FJ27`;
- residual ledger: `ledgers/t001_residual.md`, created by `FJ28`;
- selected residual attack surface: `RB-004`, finite-rank free-kernel
  recognition over \(\mathbb Z\), selected by `FJ29`;
- kernel-recognition source: Brown (1987), verified at first-pass level by
  `FJ30` for the limited two-generator criterion;
- kernel-recognition ledger: `ledgers/t001_kernel_recognition.md`;
- bridge source: Linton's `Hyperbolic one-relator groups`;
- orientation source: Linton--Nyberg-Brodda's one-relator survey;
- classical sources to verify before proof-sensitive use:
  Lyndon--Schupp and Magnus--Karrass--Solitar.

## Next mathematical move

Begin `FJ31`, first Brown criterion test case for `T-001`.
