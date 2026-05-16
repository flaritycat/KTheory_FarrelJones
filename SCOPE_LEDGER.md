# Scope Ledger

## In scope

- Algebraic \(K\)-theory of group rings \(R[G]\).
- The \(K\)-theoretic Farrell--Jones conjecture.
- Assembly maps.
- Classifying spaces for families of subgroups.
- Virtually cyclic subgroups.
- Equivariant homology theories, introduced initially as black boxes.
- Additive-category coefficients, under the first-pass convention recorded
  in `FJ02`.
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
8. Which source should serve as the main reference for the modern statement of Farrell--Jones? First-pass resolved by `FJ02`, adopting Bartels--Reich (2007) for coefficient K-theory FJC.
9. Which model of nonconnective algebraic \(K\)-theory should be used for the all-integers formulation? Partially resolved by `FJ02`, adopting Bartels--Reich's \(K^{-\infty}\) convention while leaving construction-level details deferred.
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
24. Which source should reconcile `FJCw`, `FICwF`, and the project's simplified K-theory formulation? First-pass resolved by `FJ02`: preserve source labels and do not collapse them without checked comparisons.
25. Can Wu's clique-reduction route isolate a tractable Artin target not already covered by the verified rows?
26. Is there a global K-theoretic Farrell--Jones theorem for all torsion-free one-relator groups in a weaker formulation than Full Farrell--Jones? Tracked as `OQ-024`; flagged by `FJ54` for lower-priority update and selected by `FJ58` for bounded `FJ59` intake, not resolved.
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
44. Which first two-generator one-relator presentation should be tested with Brown's criterion? First-pass resolved by `FJ31`: the commutator presentation \(\langle x,y\mid xyx^{-1}y^{-1}\rangle\) with \(\chi(x)=1\), \(\chi(y)=0\), used as a calibration example.
45. Should the original Bieri--Neumann--Strebel normal-subgroup theorem be checked directly before broader use? Resolved for first-pass theorem use by `FJ41`, which verifies Theorem B1 for normal subgroups with abelian quotient.
46. Which source handles `RB-004` cases outside Brown's two-generator criterion? Tracked as `OQ-044`; first-pass resolved by `FJ38`, which selects the BNS/Bieri--Renz/Bieri/Karrass--Solitar source cluster.
47. Which Brown test case is not already removed by the virtually solvable route? First-pass selection resolved by `FJ32`: use \(G_{2,3}=\langle x,y\mid x^2y^{-3}\rangle\), while keeping route status unclaimed until the required bridges are verified.
48. Which nonabelian two-generator one-relator family should be tested next? First-pass resolved by `FJ32`: the selected next case is \(G_{2,3}\) with \(\chi(x)=3\), \(\chi(y)=2\).
49. Does \(G_{2,3}\) have a source-verified or internally proved target-status bridge for `T-001`? First-pass resolved by `FJ33`: yes, internally, via the \(F_2\rtimes\mathbb Z\) presentation and torsion-freeness check.
50. Can the Brown-positive kernel in \(G_{2,3}\to\mathbb Z\) be identified as a finite-rank free group? First-pass resolved by `FJ33`: yes, \(\ker(\chi)\cong F_2\).
51. Which nearby presentation family should be tested next, for example \(\langle x,y\mid x^p y^{-q}\rangle\) with \(\gcd(p,q)=1\)? First-pass resolved by `FJ34`: test \(G_{p,q}=\langle x,y\mid x^p y^{-q}\rangle\), \(p,q\geq2\), \(\gcd(p,q)=1\).
52. Which parts of the \(G_{2,3}\) proof generalize without importing unverified torus-knot or one-relator classification claims? First-pass resolved by `FJ34`: the epimorphism and Brown finite-generation computation generalize; the finite-rank free-kernel bridge remains unproved for the family.
53. Can \(\ker(\chi_{p,q})\) be identified as a finite-rank free group by an internal Reidemeister--Schreier computation? Tracked as `OQ-051`; first-pass resolved by `FJ36` through a Bass--Serre freeness bridge rather than a direct Reidemeister--Schreier computation.
54. Which source, if any, should be used before the project records a family-level torus-knot or fibered-kernel theorem? Tracked as `OQ-052`; `FJ35` decides that no torus-knot or fibered-knot source is needed for the immediate bridge.
55. Can Serre's *Trees* be verified in the exact Bass--Serre form needed for the \(K_{p,q}\) freeness bridge? Tracked as `OQ-053`; first-pass resolved by `FJ36` using Serre as the canonical reference with auxiliary exact source checks.
56. Which residual `RB-004` family or subgroup should be attacked after the \(G_{p,q}\)-family route bridge? Tracked as `OQ-054`; first-pass resolved by `FJ37`, selecting `OQ-044` as the next source-selection target.
57. Should the exact rank of \(K_{p,q}\) be computed later, or is finite rank sufficient for the route ledger? Tracked as `OQ-055`; deferred by `FJ37` because finite rank is enough for the `FJ26` route.
58. Which concrete non-Brown `RB-004` test case should be used after a broader source is selected? Tracked as `OQ-056`; first-pass resolved negatively by `FJ40`: no new source-ready finitely presented-kernel test case is present in the repository.
59. Which exact hypotheses in Bieri (1976) and Karrass--Solitar (1978) are needed: finitely generated, finitely presented, \(\mathrm{FP}_2\), or another finiteness condition? Tracked as `OQ-057`; first-pass partially resolved by `FJ39` and sharpened by `FJ42`: the checked Karrass--Solitar bridge requires finite presentation, and Bieri is not yet source-verified for theorem use.
60. Does BNS (1987), without Brown's two-generator computation, give a usable finite-generation criterion for any concrete `RB-004` family already in the repository? Tracked as `OQ-058`; partially resolved by `FJ41`: the finite-generation theorem is verified, but no new concrete non-Brown family is produced.
61. Which concrete `RB-004` example has a nontrivial finitely presented kernel of infinite index, if any? Tracked as `OQ-059`; first-pass resolved negatively for the current repository state by `FJ40`.
62. Can the infinite-dihedral alternative in Karrass--Solitar be routed through existing finite-index inheritance rows without changing formulations? Tracked as `OQ-060`; deferred by `FJ40` to a later cycle decision.
63. What should follow the cycle-002 reflection: direct BNS/Bieri verification, finite-index handling for the Karrass--Solitar dihedral alternative, or an interruption for `FJ02` source conventions? Tracked as `OQ-061`; resolved by `reflections/cycle_002_reflection.md`, selecting direct BNS verification in `FJ41`.
64. Which source or computation gives usable BNS-invariant membership outside Brown's checked two-generator one-relator criterion? Tracked as `OQ-062`; generated by `FJ41`.
65. What exact theorem in Bieri (1976) is needed for normal subgroups of cohomological-dimension-\(2\) groups, and what finiteness hypothesis does it require? Tracked as `OQ-063`; partially resolved by `FJ42` as a source-access obstruction: no Bieri theorem is source-verified yet, while comparison sources indicate finite-presentation/type-\(VFP\) hypotheses.
66. Should `RB-004` continue through Bieri--Renz/BNS source verification, or pivot because the current source cluster has not produced a new concrete route? Tracked as `OQ-064`; first-pass resolved by `FJ43`: pause automatic source-cluster continuation until a candidate-ready route, missing bridge, or named residual subtraction is identified.
67. Which residual bucket or attack packet should replace the paused automatic `RB-004` source-cluster continuation? Tracked as `OQ-065`; first-pass resolved by `FJ44`, selecting `RB-005`, finite-index and virtually compact special formulation handling.
68. Which finite-index formulation bridge can be used for `RB-005` without collapsing source-version labels? Tracked as `OQ-066`; first-pass resolved by `FJ45`: only the full \(\mathcal{FJ}\) finite-index overgroup row is currently licensed.
69. Should `RB-005` next verify a coefficient K-theory finite-index overgroup theorem, or interrupt for `FJ02`/source-convention reconciliation? Tracked as `OQ-067`; first-pass resolved by `FJ46`, selecting the `FJ02` source-convention interruption.
70. Which source verifies a coefficient K-theory finite-index overgroup bridge under the `FJ02` convention? Tracked as `OQ-068`; first-pass resolved by `FJ47`: use the `FJCw` finite-index bridge, not a plain coefficient-only bridge.
71. Which `RB-005` cases have source-verified `FJCw` finite-index subgroup input, so that the `FJ47` bridge can be applied? Tracked as `OQ-069`; first-pass resolved by `FJ48`: no current `T-001`/`RB-005` case is `FJCw-ready`.
72. Does the project have a source-verified finite-extension bridge showing that finite extensions of finite-dimensional CAT(0)-groups remain usable in the finite-dimensional CAT(0)-group route? Tracked as `OQ-070`; first-pass resolved by `FJ49`: Ruane records the finite-extension direction as a question, not a theorem.
73. Should `RB-005` be paused after the failed `FJCw` and direct CAT(0) finite-extension application checks, and which attack packet should replace it? Tracked as `OQ-071`; first-pass resolved by `FJ50`: pause `RB-005` and pivot to `RB-006`.
74. Which one-relator cubulation, specialness, or CAT(0)-recognition source can make `RB-006` candidate-ready without duplicating the hyperbolic route? Tracked as `OQ-072`; first-pass resolved by `FJ51`: select Louder--Wilton for a bounded boundary check, not theorem use.
75. Does Louder--Wilton's negative-immersion source produce an `RB-006` compact-special/CAT(0) route delta, or only hyperbolic-route overlap already governed by `FJ23`? Tracked as `OQ-073`; first-pass resolved by `FJ52`: no independent `RB-006` route delta; possible hyperbolic-route overlap through `FJ23`.
76. Should the project record the \(\pi(w)>2\) negative-immersion condition as a hyperbolic-route overlap through `FJ23`, or treat it as already absorbed by the existing negative-immersion route marker? Tracked as `OQ-074`; provisionally addressed by WIP `FJ53`: record it explicitly as hyperbolic-route overlap through `FJ23`, not as `RB-006` progress.
77. Which residual bucket or attack packet should follow the demoted `RB-006` Louder--Wilton path? Tracked as `OQ-075`; first-pass resolved by `FJ54`: select the `RB-003` + `RB-004`/`RB-008` hybrid attack packet.
78. Can Linton-style hierarchy / primitive-extension data be converted into an FJ route, a candidate family, a bridge lemma, or a documented obstruction when paired with kernel-control testing? Tracked as `OQ-076`; first-pass resolved by `FJ55`: no direct hierarchy-to-FJ bridge is currently recorded, so the packet must proceed through explicit route-output and kernel-control obligations.
79. Which repository-supported candidate rows can receive explicit kernel-control data for the `RB-003` + `RB-004`/`RB-008` hybrid packet? Tracked as `OQ-077`; first-pass resolved by `FJ56`: all current concrete rows have explicit kernel-control status but are calibration-only or already routed, and the placeholder is not a candidate.
80. Can `FJ57` promote a repository-supported, non-routed candidate family into the inventory, or should it record the no-candidate obstruction as the current endpoint of the hybrid packet? Tracked as `OQ-078`; first-pass resolved by `FJ57`: no repository-supported non-routed candidate is available, so the selected hybrid packet is blocked at candidate production.
81. Which candidate-production lane, if any, should replace the blocked `RB-003` + `RB-004`/`RB-008` hybrid packet? Tracked as `OQ-079`; first-pass resolved by `FJ58`: no currently named residual lane is candidate-ready as a proof-attempt lane.
82. Can a weaker \(K_0\) / Cohen--Lyndon consequence lane update `T-001` without being misread as a Farrell--Jones route subtraction? Tracked as `OQ-080`; first-pass resolved by `FJ59`: no source payload is currently recorded, so no consequence update is available yet.
83. Which exact source, if any, supplies a weaker \(K_0\) / Cohen--Lyndon payload relevant to `T-001`? Tracked as `OQ-081`; first-pass resolved by `FJ60`: no exact payload is currently available, so the lane is inactive until a source is named.
84. What should the cycle-003 reflection select as the next project move after candidate-production and weaker-consequence lanes both produced obstructions rather than a proof attempt? Tracked as `OQ-082`; first-pass resolved by `reflections/cycle_003_reflection.md`, which selects `FJ61`.
85. What candidate-intake and exit criteria should govern `T-001` after cycle 003 closed without a live non-routed candidate? Tracked as `OQ-083`; generated by `reflections/cycle_003_reflection.md` and selected for `FJ61`.

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
- ER-013: Source-verified additive-category K-theory formulation and source-convention policy, adopting Bartels--Reich's coefficient formulation and preserving source-label distinctions.
- ER-014: Source-verified `FJCw` finite-index overgroup bridge, preserving the finite-wreath-product hypothesis and refusing plain coefficient-only finite-index passage.

## Current scope

The active mathematical scope is the K-theoretic Farrell--Jones conjecture,
with the simplified group-ring formulation from `FJ01` treated as a
specialization of the additive-category coefficient convention recorded in
`FJ02`. Here \(R\) is an associative unital ring and \(G\) is a discrete
group unless stated otherwise.

The active project target is `T-001`, torsion-free one-relator residual gap analysis.

## What has been established

- The initial project structure and cycle-001 module plan have been defined.
- Module `FJ01` states the simplified conjecture and proves the trivial-group example.
- Module `FJ02` records the first-pass additive-category K-theory formulation and source-convention policy, producing `ER-013`.
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
- Module `FJ31` applies Brown's two-generator criterion to the calibration example \(\langle x,y\mid xyx^{-1}y^{-1}\rangle\), verifies the maximum-count test for both \([\chi]\) and \([-\chi]\), identifies the kernel as \(F_1\), and records that the example is already covered by the virtually solvable route.
- Module `FJ32` selects the nonabelian presentation \(G_{2,3}=\langle x,y\mid x^2y^{-3}\rangle\) as the next Brown test case, records the character \(\chi(x)=3,\chi(y)=2\), verifies a quotient onto \(S_3\), and stores only a preliminary Brown-positive computation pending the full `FJ33` route check.
- Module `FJ33` completes the worked Brown test for \(G_{2,3}\), proves internally that \(G_{2,3}\cong F_2\rtimes\mathbb Z\), verifies torsion-free target status, and records the concrete finite-rank free-by-cyclic route bridge through `FJ26`.
- Module `FJ34` generalizes the Brown maximum-count computation to \(G_{p,q}=\langle x,y\mid x^p y^{-q}\rangle\), \(p,q\geq2\), \(\gcd(p,q)=1\), recording finite generation of \(\ker(\chi_{p,q})\) while leaving the finite-rank free-kernel bridge open for the family.
- Module `FJ35` selects a Bass--Serre freeness bridge, with Serre's *Trees* as the source to verify, as the conservative route from Brown finite generation to finite-rank freeness for \(K_{p,q}\).
- Module `FJ36` verifies the Bass--Serre freeness bridge for \(K_{p,q}\), records a finite-rank free-by-cyclic bridge \(G_{p,q}\cong F_n\rtimes\mathbb Z\), and removes this family from the active `T-001` residual through `FJ26`.
- Module `FJ37` audits the post-\(G_{p,q}\) residual, defers exact rank computation for \(K_{p,q}\), and selects beyond-Brown `RB-004` source selection as the next target.
- Module `FJ38` selects the BNS/Bieri--Renz/Bieri/Karrass--Solitar normal-subgroup source cluster for beyond-Brown `RB-004` work and assigns exact hypothesis verification to `FJ39`.
- Module `FJ39` verifies Karrass--Solitar (1978) as a finitely presented normal-subgroup bridge, keeps BNS direct theorem use open, and records no residual subtraction.
- Module `FJ40` audits source-ready finitely presented-kernel candidates for `RB-004`, selects no new non-Brown example, records no residual subtraction, and closes the module portion of cycle 002.
- `reflections/cycle_002_reflection.md` closes cycle 002 and selects `FJ41`, direct BNS theorem verification for `RB-004`, as the first module of cycle 003.
- Module `FJ41` verifies Bieri--Neumann--Strebel (1987), Theorem B1, as a direct finite-generation theorem for normal subgroups \(N\trianglelefteq G\) with \(G\) finitely generated and \(G/N\) abelian. It records the rank-one quotient consequence for \(\ker(\chi)\) when \(\chi\colon G\to\mathbb Z\), but no BNS-invariant computation, finite-rank free-kernel bridge, or residual subtraction.
- Module `FJ42` checks Bieri (1976) source access and route delta. It verifies Bieri bibliographic metadata but does not directly extract the primary theorem text, so Bieri remains unavailable for source-verified theorem use. Comparison sources point to finite-presentation/type-\(VFP\) hypotheses, and no residual subtraction is made.
- Module `FJ43` completes the route-delta checkpoint for the BNS/Bieri/Karrass--Solitar source cluster. It pauses automatic `RB-004` source-cluster continuation until a candidate-ready route, missing bridge, or named residual subtraction is identified.
- Module `FJ44` compares residual buckets after the `RB-004` pause and selects `RB-005`, finite-index and virtually compact special formulation handling, as the next attack packet. It records no residual subtraction.
- Module `FJ45` completes the finite-index formulation bridge checkpoint for `RB-005`: the full \(\mathcal{FJ}\) finite-index overgroup row is usable only with its full-formulation flag, while coefficient K-theory, direct CAT(0), and `FJCw`/`FICwF` finite-index passages remain unlicensed for proof-sensitive use. No residual subtraction is made.
- Module `FJ46` completes the `RB-005` source-convention decision and selects an interruption for `FJ02` before further proof-sensitive `RB-005` use. It records no residual subtraction.
- Module `FJ02` completes the additive-category/source-convention interruption selected by `FJ46`. It adopts Bartels--Reich Conjecture 3.2 as the first-pass coefficient K-theory formulation, records `ER-013`, and returns `RB-005` to finite-index bridge source selection.
- Module `FJ47` completes the `FJCw` finite-index bridge source selection. It records `ER-014`, authorizes finite-index passage only for finite-wreath-product inputs, and makes no residual subtraction.
- Module `FJ48` completes the `RB-005` `FJCw` application audit. It records that no current `T-001` finite-index cleanup case has source-verified `FJCw` subgroup input, makes no residual subtraction, and selects `FJ49` to check a direct finite-dimensional CAT(0) finite-extension bridge.
- Module `FJ49` completes the direct CAT(0) finite-extension bridge check. It records that Ruane poses finite extensions of CAT(0)-groups as a question and that the product-action construction does not supply cocompactness. No residual subtraction is made.
- Module `FJ50` completes the `RB-005` route-delta checkpoint. It pauses `RB-005` after the finite-index bridge sequence yields no residual subtraction and selects `RB-006` as the next bounded attack packet.
- Module `FJ51` completes the `RB-006` source-selection attack packet. It selects Louder--Wilton as a bounded negative-immersion boundary check for `FJ52`, but imports no theorem and makes no residual subtraction.
- Module `FJ52` completes the Louder--Wilton negative-immersion boundary check. It records the primitivity-rank/negative-immersion bridge and subgroup-structure consequences, but no independent compact-special/CAT(0) route delta and no residual subtraction.
- Module `FJ53` is WIP / provisional as the \(\pi(w)>2\) hyperbolic-overlap checkpoint. It records the Louder--Wilton/Linton source chain as a route criterion through `FJ23`, demotes the current `RB-006` path as provisionally non-subtractive, and makes no concrete residual subtraction.
- Module `FJ54` completes the residual-bucket checkpoint after the `RB-006` demotion. It records the `RB-001`--`RB-008` table, creates `ledgers/t001_candidate_inventory.md`, and selects the `RB-003` + `RB-004`/`RB-008` hybrid as the next primary attack packet.
- Module `FJ55` completes the primitive-extension / hierarchy-to-FJ bridge test. It records `OBL-T001-001`, that no direct hierarchy-to-FJ bridge is currently available, creates `OBL-T001-002` for route-output declarations, and sends the project to `FJ56`.
- Module `FJ56` completes the kernel-control candidate inventory. It records that the current concrete candidate rows are calibration-only or already removed through `FJ26`, creates `OBL-T001-003`, and sends the project to `FJ57`.
- Module `FJ57` completes the candidate-family proof attempt or obstruction record. It records `OBL-T001-004`, that the selected hybrid packet is blocked at candidate production, and sends the project to `FJ58`.
- Module `FJ58` completes the post-hybrid candidate-production checkpoint. It records `OBL-T001-005`, that no active candidate-production lane is currently ready for `T-001`, and sends the project to `FJ59`.
- Module `FJ59` completes the weaker \(K_0\) / Cohen--Lyndon consequence intake gate. It records `OBL-T001-006`, that no source payload for this lane is currently recorded, and sends the project to `FJ60`.
- Module `FJ60` completes the weaker consequence source-payload selection. It records `OBL-T001-007`, that the weaker \(K_0\) / Cohen--Lyndon lane is inactive until an exact payload is named, and sends the project to the cycle-003 reflection.
- `reflections/cycle_003_reflection.md` closes cycle 003. It records that
  `T-001` remains important but is not currently candidate-ready, keeps
  `FJ53` WIP / provisional, and selects `FJ61`, T-001 Candidate-Intake Reset
  and Exit Criteria, as the first cycle-004 move.

## Selected target

`T-001`: torsion-free one-relator residual gap analysis.

Cycle 002 identified which parts of the torsion-free one-relator target are
removed by verified hyperbolic, finite-dimensional CAT(0), virtually
solvable, hyperbolic-by-cyclic/free-by-cyclic, and source-verified inheritance
routes. The cycle-002 reflection selects direct BNS theorem verification as
the first module of cycle 003.

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
- first Brown calibration example: `FJ31`, using
  \(\langle x,y\mid xyx^{-1}y^{-1}\rangle\) and recording route overlap with
  the virtually solvable subtraction;
- selected nontrivial Brown test case: \(G_{2,3}\), selected by `FJ32`;
- first nontrivial Brown route bridge: \(G_{2,3}\cong F_2\rtimes\mathbb Z\),
  completed by `FJ33`;
- nearby Brown family boundary: \(G_{p,q}\), completed by `FJ34` only up to
  Brown-positive finite generation;
- candidate \(G_{p,q}\) kernel-freeness bridge: Bass--Serre freeness via
  Serre's *Trees*, selected by `FJ35` and verified at first-pass level by
  `FJ36`;
- \(G_{p,q}\)-family route status: removed through the `FJ26` finite-rank
  free-by-cyclic route by `FJ36`;
- post-\(G_{p,q}\) audit: `FJ37` defers exact rank computation and selects
  `OQ-044` as the next `RB-004` source-selection target;
- beyond-Brown source cluster: `FJ38` selects Bieri--Neumann--Strebel
  (1987), Bieri--Renz (1988), Bieri (1976), and Karrass--Solitar (1978) for
  verification; `FJ39` first verifies only the Karrass--Solitar
  finite-presentation bridge;
- finitely presented-kernel bridge: `FJ39` verifies Karrass--Solitar (1978)
  under the hypothesis of a nontrivial finitely presented normal subgroup of
  infinite index;
- finitely presented-kernel test selection: `FJ40` records that no new
  non-Brown `RB-004` candidate with a source-ready finitely presented kernel
  is currently available inside the repository;
- cycle-002 reflection: selects direct BNS theorem verification as `FJ41`;
- direct BNS theorem verification: `FJ41` verifies Theorem B1 and records that direct BNS use still needs an invariant computation or another finiteness bridge before it removes a residual bucket;
- Bieri route-delta check: `FJ42` records that Bieri (1976) is not yet source-verified for theorem use and does not bypass the finite-presentation/type-\(VFP\) bottleneck;
- route-delta checkpoint: `FJ43` pauses automatic BNS/Bieri/Bieri--Renz/Karrass--Solitar source-cluster continuation and requires a concrete candidate, missing bridge, or subtraction target before further source-only work;
- residual-bucket comparison: `FJ44` selects `RB-005` as the next attack packet, focused on finite-index and virtually compact special formulation handling;
- finite-index formulation checkpoint: `FJ45` records only the full \(\mathcal{FJ}\) finite-index bridge as currently usable, and marks coefficient-route and CAT(0)-finite-extension uses as still blocked;
- source-convention decision: `FJ46` selects `FJ02` as an interruption before continuing `RB-005`;
- source-convention formulation: `FJ02` supplies the additive-category K-theory convention and source-label policy needed before `RB-005` resumes;
- finite-index bridge source selection: `FJ47` supplies the `FJCw` finite-index overgroup bridge but not a plain coefficient-only bridge;
- `FJCw` application audit: `FJ48` finds no current `T-001`/`RB-005` case with `FJCw` subgroup input and redirects the finite-index attack to a direct CAT(0) finite-extension check;
- CAT(0) finite-extension bridge check: `FJ49` does not license the direct finite-extension route and points to a route-delta checkpoint;
- route-delta checkpoint: `FJ50` pauses `RB-005` and selects `RB-006`, compact special or CAT(0)-looking one-relator cases beyond the hyperbolic route;
- `RB-006` source selection: `FJ51` selects Louder--Wilton for a one-module boundary check, with a stop condition against hyperbolic-route duplication;
- Louder--Wilton boundary check: `FJ52` records no independent `RB-006` route delta and redirects possible use to a hyperbolic-overlap checkpoint;
- \(\pi(w)>2\) hyperbolic-overlap checkpoint: WIP / provisional `FJ53` records the criterion as an explicit `FJ23` route input and demotes the Louder--Wilton `RB-006` path without subtraction;
- residual-bucket checkpoint: `FJ54` selects the `RB-003` + `RB-004`/`RB-008` hybrid and creates the candidate-inventory ledger;
- bridge-test obstruction: `FJ55` records that hierarchy data must pass through an approved route output before any subtraction;
- kernel-control inventory: `FJ56` records that all current concrete candidate rows are route-exhausted and that no live non-routed candidate is present;
- candidate-promotion obstruction: `FJ57` records that the selected hybrid packet cannot currently produce a legitimate proof attempt;
- post-hybrid checkpoint: `FJ58` records that no replacement candidate-production lane is currently ready and selects a bounded weaker \(K_0\) / Cohen--Lyndon consequence intake;
- consequence-lane intake: `FJ59` records that no weaker \(K_0\) / Cohen--Lyndon source payload is currently available for project use, and `FJ60` closes the lane as inactive until a source is named;
- cycle-003 reflection: `reflections/cycle_003_reflection.md` closes the
  third cycle and selects `FJ61` to define candidate-intake and exit criteria
  before any further `T-001` proof-target work;
- bridge source: Linton's `Hyperbolic one-relator groups`;
- orientation source: Linton--Nyberg-Brodda's one-relator survey;
- classical sources to verify before proof-sensitive use:
  Lyndon--Schupp and Magnus--Karrass--Solitar.

## Next mathematical move

Begin `FJ61`, T-001 Candidate-Intake Reset and Exit Criteria.
