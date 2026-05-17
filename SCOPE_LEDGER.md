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
- `ledgers/payload_execution_queue.md` is governance infrastructure for
  row-by-row callback payload intake. It does not accept the queue in bulk and
  does not create mathematical claims by itself.

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
85. What candidate-intake and exit criteria should govern `T-001` after cycle 003 closed without a live non-routed candidate? Tracked as `OQ-083`; first-pass resolved by `FJ61`.
86. Which active blockers should `FJ62` preserve for `T-001` candidate intake, and which should be moved to deferred or historical status? Tracked as `OQ-084`; first-pass resolved by `FJ62`.
87. Which exact data-acquisition packet should `FJ63` select after active blocker pruning? Tracked as `OQ-085`; first-pass resolved by `FJ63`, selecting `DAP-T001-001`.
88. Can `FJ64` produce a candidate-admissible row from `DAP-T001-001`, or must it record a no-candidate note? Tracked as `OQ-086`; first-pass resolved by `FJ64` with a no-candidate note.
89. Can `FJ65` identify a prior-art blocker object, target-pause recommendation, or target-pivot comparison after the `FJ64` no-candidate note, or must it send the project to the `FJ66` branch checkpoint? Tracked as `OQ-087`; first-pass resolved by `FJ65`, which sends the project to `FJ66`.
90. Should `FJ66` pause `T-001`, create a bounded target-pivot comparison packet, or identify an exact repository object that justifies continuing `T-001`? Tracked as `OQ-088`; first-pass resolved by `FJ66`, which pauses `T-001` as an active proof-target sequence and selects `FJ67`.
91. What criteria should `FJ67` use to compare possible next active targets after the `T-001` pause? Tracked as `OQ-089`; first-pass resolved by `FJ67`, which records `OBL-PIVOT-001` and selects `FJ68`.
92. Which candidate target, if any, should `FJ68` select after applying the `FJ67` target-pivot criteria? Tracked as `OQ-090`; first-pass resolved by `FJ68`, which selects `A-001`, Artin subclass-gap inventory after `FJ18`, as the bounded next target packet.
93. Can `FJ69` produce an Artin subclass-gap inventory from the existing `FJ18` rows without turning into a broad source-summary module? Tracked as `OQ-091`; first-pass resolved by `FJ69`, which creates `ledgers/artin_subclass_gap_inventory.md` and selects `FJ70`.
94. Can `FJ70` produce a Wu clique-reduction candidate from existing Artin gap rows, or must it record no current candidate? Tracked as `OQ-092`; first-pass resolved by `FJ70`, which records no current Wu-filter candidate.
95. What branch decision should follow the no-current-Wu-candidate note? Tracked as `OQ-093`; first-pass resolved by `FJ71`, which pauses the active Artin lane and selects a target-pivot refresh.
96. Which target-pivot input should follow the Artin pause? Tracked as `OQ-094`; first-pass resolved by `FJ72`, which records no group-class target ready and selects foundational open-question triage.
97. Which foundational blocker, if any, should be selected after the target pauses? Tracked as `OQ-095`; first-pass resolved by `FJ73`, which selects `OQ-005` for fixed-point convention cleanup.
98. Should weakly contractible and contractible fixed-point formulations be separated? Tracked as `OQ-005`; first-pass resolved by `FJ74`, which records `FND-CONV-001`.
99. Should Farrell--Jones 1995 be directly verified for the virtually cyclic dichotomy? Tracked as `OQ-006`; first-pass resolved negatively by `FJ75`, which checks DOI metadata but does not access Lemma 2.5 text.
100. Which foundational source-payload item, if any, should follow the `OQ-006` no-promotion result? Tracked as `OQ-096`; first-pass resolved by `FJ76`, which pauses the foundational source queue.
101. Which target-pivot packet, if any, should follow the foundational source-queue pause? Tracked as `OQ-097`; first-pass resolved by `FJ77`, which records no target or source packet ready and selects a cycle-004 closure-readiness audit.
102. How should the remaining cycle-004 module slots be used after the no-target/no-source-ready decision? Tracked as `OQ-098`; first-pass resolved by `FJ78`, which sends the cycle toward handoff and reflection preparation.
103. What handoff table and gate index should prepare `cycle_004` for its final module and reflection? Tracked as `OQ-099`; first-pass resolved by `FJ79`, which creates `ledgers/cycle_004_handoff.md`.
104. Is `cycle_004` ready for reflection after final pre-reflection closure? Tracked as `OQ-100`; first-pass resolved by `FJ80`.
105. What should the cycle-004 reflection select as the next project move after the no-target/no-source-ready closure path? Tracked as `OQ-101`; first-pass resolved by `reflections/cycle_004_reflection.md`, which selects a cycle-005 reactivation gate audit.
106. Which recorded reactivation gate, if any, is satisfied at the start of cycle 005? Tracked as `OQ-102`; first-pass resolved by `FJ81`: no recorded reactivation gate is satisfied.
107. What payload-acquisition protocol or project-pause decision should follow the no-gate-ready audit? Tracked as `OQ-103`; first-pass resolved by `FJ82`, which creates the payload-intake protocol and records a payload-gated pause.
108. Which accepted payload, if any, should instantiate the next numbered module after the payload-gated pause? Tracked as `OQ-104`; first-pass resolved by `FJ83`, which verifies the weaker \(K_0\) / Cohen--Lyndon source payload without promoting full `T-001`.
109. Does any current `T-001` candidate/family satisfy the FJ83 weaker \(K_0\) / Cohen--Lyndon source hypotheses? Tracked as `OQ-105`; first-pass resolved by `FJ84`, which finds no eligible current row.
110. What payload, if any, should follow the FJ84 candidate-hypothesis audit? Tracked as `OQ-106`; first-pass resolved by `FJ85`, which records a governance-only checkpoint.
111. Which accepted payload, if any, should instantiate FJ86? Tracked as `OQ-107`; first-pass resolved by `FJ86`, which records `CAND-T001-004`.
112. Is \(G_{BS23}\) torsion-free? Tracked as `OQ-108`; first-pass resolved by `FJ87`.
113. Is \(G_{BS23}\) already covered by a known route or prior-art theorem? Tracked as `OQ-109`; first-pass resolved by `FJ88`, which routes the row through `ER-015`.
114. Which accepted payload, if any, should instantiate FJ89 after FJ88? Tracked as `OQ-110`; resolved by `FJ89`, which records no-live-candidate blocker `NLC-T001-001`.
115. Which accepted payload, if any, should instantiate FJ90 after FJ89? Tracked as `OQ-111`; resolved by `FJ90`, which adds concrete blocked intake row `CAND-T001-005`.
116. Which accepted payload, if any, should instantiate FJ91 after FJ90? Tracked as `OQ-112`; resolved by `FJ91`, which source-checks torsion-free status for `CAND-T001-005`.
117. Which accepted payload, if any, should instantiate FJ92 after FJ91? Tracked as `OQ-113`; resolved by `FJ92`, which records Brown-positive finite generation for `CAND-T001-005`.
118. Which accepted payload, if any, should instantiate FJ93 after FJ92? Tracked as `OQ-114`; resolved by `FJ93`, which records no known route or prior-art blocker for `CAND-T001-005`.
119. Which accepted payload, if any, should instantiate FJ94 after FJ93? Tracked as `OQ-115`; resolved by `FJ94`, which records `CAND-T001-005` as not FJ83-eligible from current repository data.
120. Which accepted payload, if any, should instantiate FJ95 after FJ94? Tracked as `OQ-116`; resolved by `FJ95`, which demotes `CAND-T001-005` to blocked / inactive proof-target status.
121. Does any live non-routed `T-001` candidate row remain after the FJ95 branch decision? Tracked as `OQ-117`; resolved by `FJ96`, which records post-`FJ95` no-live-candidate blocker `NLC-T001-002`.
122. Does the next queued formulation-safety prompt apply to any active candidate row after FJ96? Tracked as `OQ-118`; resolved by `FJ97`, which records formulation-irrelevant status because no active candidate route remains.
123. What target-pivot readiness status follows the post-FJ97 formulation-irrelevant audit? Tracked as `OQ-119`; resolved by `FJ98`, which records all-targets-paused / no-target-ready status.
124. What cycle-005 strategic status follows the post-FJ98 all-targets-paused checkpoint? Tracked as `OQ-120`; resolved by `FJ99`, which records that cycle 005 made candidate-level progress but is now no-target-ready / governance-only.
125. Should cycle 005 close, continue only with a concrete active payload, or pause after the FJ99 strategic checkpoint? Tracked as `OQ-121`; resolved by `FJ100`, which records `cycle_005` as closure-ready and creates `ledgers/cycle_005_handoff.md`.
126. What prompt-backlog maintenance or review-preparation step should follow the FJ100 cycle-005 closure-readiness audit? Tracked as `OQ-122`; resolved by `reflections/cycle_005_reflection.md`, after Prompt 020 completed the backlog maintenance pass and Prompt 021 created the cycle-005 reflection.
127. What post-100-module strategic review should follow the cycle-005 reflection? Tracked as `OQ-123`; resolved by `reflections/post_100_module_strategic_review.md`.
128. What cycle-006 entry-gate status follows the post-100-module strategic review? Tracked as `OQ-124`; resolved by `ledgers/cycle_006_entry_gate.md`, which records a no-gate-ready state.
129. What payload-acquisition or project-pause decision should follow the cycle-006 no-gate-ready audit? Tracked as `OQ-125`; resolved by `ledgers/cycle_006_payload_decision.md`, which records `C6-PAUSE-001`.
130. Which accepted payload, if any, should exit the cycle-006 payload-gated pause and instantiate the next numbered module? Tracked as `OQ-126`; partially resolved by `FJ101` for queue row `001`, by `FJ102` for queue row `002`, by `FJ103` for queue row `003`, by `FJ104` for queue row `004`, by `FJ105` for queue row `005`, by `FJ106` for queue row `006`, by `FJ107` for queue row `007`, by `FJ108` for queue row `008`, by `FJ109` for queue row `009`, by `FJ110` for queue row `010`, by `FJ111` for queue row `011`, by `FJ112` for queue row `012`, by `FJ113` for queue row `013`, by `FJ114` for queue row `014`, by `FJ115` for queue row `015`, by `FJ116` for queue row `016`, by `FJ117` for queue row `017`, by `FJ118` for queue row `018`, by `FJ119` for queue row `019`, by `FJ120` for queue row `020`, by `FJ121` for queue row `021`, by `FJ122` for queue row `022`, and by `FJ123` for queue row `023` only.
131. Which accepted payload, if any, should act on `CAND-T001-C6-001` after `FJ101`? Tracked as `OQ-127`; open and blocked until a kernel-control, route/prior-art, formulation, route-bridge, or branch payload is accepted.
132. Which accepted payload, if any, should act on `CAND-T001-C6-002` after `FJ102`? Tracked as `OQ-128`; open and blocked until a kernel-control, route/prior-art, formulation, route-bridge, or branch payload is accepted.
133. Which accepted payload, if any, should act on `CAND-T001-C6-003` after `FJ103`? Tracked as `OQ-129`; open and blocked until a kernel-control, route/prior-art, formulation, route-bridge, or branch payload is accepted.
134. Which accepted payload, if any, should act on `CAND-T001-C6-004` after `FJ104`? Tracked as `OQ-130`; open and blocked until a kernel-control, route/prior-art, formulation, route-bridge, or branch payload is accepted.
135. Which accepted payload, if any, should act on `CAND-T001-C6-005` after `FJ105`? Tracked as `OQ-131`; open and blocked until a kernel-control, route/prior-art, formulation, route-bridge, or branch payload is accepted.
136. Which accepted payload, if any, should act on `CAND-T001-C6-006` after `FJ106`? Tracked as `OQ-132`; open and blocked until a kernel-control, route/prior-art, formulation, route-bridge, or branch payload is accepted.
137. Which accepted payload, if any, should act on `CAND-T001-C6-007` after `FJ107`? Tracked as `OQ-133`; open and blocked until a kernel-control, route/prior-art, formulation, route-bridge, or branch payload is accepted.
138. Which accepted payload, if any, should act on `CAND-T001-C6-008` after `FJ108`? Tracked as `OQ-134`; open and blocked until a kernel-control, route/prior-art, formulation, route-bridge, or branch payload is accepted.
139. Which accepted payload, if any, should act on `CAND-T001-C6-009` after `FJ109`? Tracked as `OQ-135`; open and blocked until a kernel-control, route/prior-art, formulation, route-bridge, or branch payload is accepted.
140. Which accepted payload, if any, should act on `CAND-T001-C6-010` after `FJ110`? Tracked as `OQ-136`; open and blocked until a kernel-control, route/prior-art, formulation, route-bridge, or branch payload is accepted.
141. Which accepted payload, if any, should act on `CAND-T001-C6-011` after `FJ111`? Tracked as `OQ-137`; open and blocked until a kernel-control, route/prior-art, formulation, route-bridge, or branch payload is accepted.
142. Which accepted payload, if any, should act on `CAND-T001-C6-012` after `FJ112`? Tracked as `OQ-138`; open and blocked until a kernel-control, route/prior-art, formulation, route-bridge, or branch payload is accepted.
143. Which accepted payload, if any, should act on `CAND-T001-C6-013` after `FJ113`? Tracked as `OQ-139`; open and blocked until a kernel-control, route/prior-art, formulation, route-bridge, or branch payload is accepted.
144. Which accepted payload, if any, should act on `CAND-T001-C6-014` after `FJ114`? Tracked as `OQ-140`; open and blocked until a kernel-control, route/prior-art, formulation, route-bridge, or branch payload is accepted.
145. Which accepted payload, if any, should act on `CAND-T001-C6-015` after `FJ115`? Tracked as `OQ-141`; open and blocked until a kernel-control, route/prior-art, formulation, route-bridge, or branch payload is accepted.
146. Which accepted payload, if any, should act on `CAND-T001-C6-016` after `FJ116`? Tracked as `OQ-142`; open and blocked until a kernel-control, route/prior-art, formulation, route-bridge, or branch payload is accepted.
147. Which accepted payload, if any, should act on `CAND-T001-C6-017` after `FJ117`? Tracked as `OQ-143`; open and blocked until a kernel-control, route/prior-art, formulation, route-bridge, or branch payload is accepted.
148. Which accepted payload, if any, should act on `CAND-T001-C6-018` after `FJ118`? Tracked as `OQ-144`; open and blocked until a kernel-control, route/prior-art, formulation, route-bridge, or branch payload is accepted.
149. Which accepted payload, if any, should act on `CAND-T001-C6-019` after `FJ119`? Tracked as `OQ-145`; open and blocked until a kernel-control, route/prior-art, formulation, route-bridge, or branch payload is accepted.
150. Which accepted payload, if any, should act on `CAND-T001-C6-020` after `FJ120`? Tracked as `OQ-146`; open and blocked until a kernel-control, route/prior-art, formulation, route-bridge, or branch payload is accepted.
151. Which accepted payload, if any, should act on `CAND-T001-C6-021` after `FJ121`? Tracked as `OQ-147`; open and blocked until a kernel-control, route/prior-art, formulation, route-bridge, or branch payload is accepted.
152. Which accepted payload, if any, should act on `CAND-T001-C6-022` after `FJ122`? Tracked as `OQ-148`; open and blocked until a kernel-control, route/prior-art, formulation, route-bridge, or branch payload is accepted.
153. Which accepted payload, if any, should act on `CAND-T001-C6-023` after `FJ123`? Tracked as `OQ-149`; open and blocked until a kernel-control, route/prior-art, formulation, route-bridge, or branch payload is accepted.

## Established results

- ER-001: For the trivial group \(G=1\), the simplified assembly map in module `FJ01` is the identity on \(K_n(R)\), assuming the black-box normalization of the equivariant homology theory.
- ER-002: Source-verified existence and homotopy characterization of \(E_{\mathcal F}G\) for project-style families of subgroups, using Lueck's Definition 1.8 and Theorem 1.9; `FJ74` records the `FND-CONV-001` convention separating strict readable models from the weakly contractible source criterion.
- ER-003: For every group \(G\), \(\mathcal{VCyc}(G)\) is a family of subgroups; infinite virtually cyclic groups are organized into type I/type II by the checked Lueck--Reich source statement. `FJ75` does not promote Farrell--Jones (1995), Lemma 2.5, to direct theorem-use status.
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
- ER-015: Source-verified graph-of-abelian-groups route for Baumslag--Solitar
  candidates, used in `FJ88` to route `CAND-T001-004` without solving
  global `T-001`.

## Current scope

The active mathematical scope is the K-theoretic Farrell--Jones conjecture,
with the simplified group-ring formulation from `FJ01` treated as a
specialization of the additive-category coefficient convention recorded in
`FJ02`. Here \(R\) is an associative unital ring and \(G\) is a discrete
group unless stated otherwise.

The active project posture is post-`FJ99` strategic-checkpoint gate.
`T-001`,
torsion-free one-relator residual gap analysis, remains unresolved as a
global target. The concrete row `CAND-T001-004` is no longer live as a
non-routed residual candidate, because `FJ88` routes it through `ER-015`.
`FJ90` adds `CAND-T001-005` as a concrete blocked intake row, with
proper-power status and an epimorphism to \(\mathbb Z\) recorded. `FJ91`
source-checks torsion-free status for this row. `FJ92` records
Brown-positive finite generation of the \(\chi\)-kernel, but not
finite-rank freeness. `FJ93` records no known route or prior-art blocker
among the named repository routes. `FJ94` records that the row is not
FJ83-eligible from current repository data. `FJ95` demotes the row to
blocked / inactive proof-target status while retaining it as a concrete row.
`FJ96` records that no current candidate-inventory row is live and
non-routed after that demotion. Route formulation and route promotion
therefore remain blocked. `FJ97` records formulation-irrelevant status for
the current `T-001` inventory because no active candidate route remains.
`FJ98` records that no mathematical target lane has a concrete next object:
`T-001`, the Artin lane, the foundational source queue, automatic /
biautomatic groups, Thompson-type groups, and the WIP / provisional `FJ53`
line remain paused, deferred, WIP / provisional, or payload-blocked. `FJ99`
records that cycle 005 made real candidate-level progress through
`CAND-T001-004` and `CAND-T001-005`, but that the current state is
no-target-ready / governance-only. `FJ100` records that `cycle_005` is
closure-ready, creates `ledgers/cycle_005_handoff.md`, resolves `OQ-121`,
completes `OBL-C5-020`, and creates `OQ-122` and `OBL-C5-021`.
`reflections/cycle_005_reflection.md` closes cycle 005, resolves `OQ-122`,
completes `OBL-C5-021`, creates `OQ-123`, and records `OBL-POST100-001`.
`reflections/post_100_module_strategic_review.md` resolves `OQ-123`,
completes `OBL-POST100-001`, creates `OQ-124`, and records `OBL-C6-001`.
`ledgers/cycle_006_entry_gate.md` resolves `OQ-124`, completes
`OBL-C6-001`, records a no-gate-ready state, creates `OQ-125`, and records
`OBL-C6-002`. The next queued gate is the cycle-006 payload decision in
Prompt 024.
`ledgers/cycle_006_payload_decision.md` resolves `OQ-125`, completes
`OBL-C6-002`, records `C6-PAUSE-001`, creates `OQ-126`, and records
`OBL-C6-003`. It originally selected no `FJ101` module; `FJ101` was later
instantiated only after accepted queue row `PAY-T001-CAND-C6-001-2026-001`
was recorded.

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
- Module `FJ61` completes the T-001 candidate-intake reset. It records
  `OBL-T001-008`, defines candidate-admissible rows and early cycle-004 exit
  criteria, resolves `OQ-083`, and selects `FJ62`, Active Blocker Pruning for
  `T-001`.
- Module `FJ62` completes active blocker pruning for `T-001`. It records
  `OBL-T001-009`, preserves only the candidate-object, route-data, and
  branch-decision blockers as active for the next module, resolves `OQ-084`,
  and selects `FJ63`, Candidate-Data Acquisition Packet.
- Module `FJ63` completes the candidate-data acquisition packet selection.
  It selects `DAP-T001-001`, candidate-row acquisition from current
  repository records, records `OBL-T001-010`, resolves `OQ-085`, and selects
  `FJ64`, Candidate Intake Attempt or No-Candidate Note.
- Module `FJ64` completes the candidate intake attempt by recording a
  no-candidate note. It adds no candidate-admissible row, completes
  `OBL-T001-010`, records `OBL-T001-011`, resolves `OQ-086`, and selects
  `FJ65`, Prior-Art / Branch-Readiness Checkpoint.
- Module `FJ65` completes the prior-art / branch-readiness checkpoint. It
  records that no exact prior-art blocker object or pivot-comparison object
  is available, records the no-candidate state as a target-pause trigger,
  completes `OBL-T001-011`, records `OBL-T001-012`, resolves `OQ-087`, and
  selects `FJ66`, T-001 Branch Checkpoint.
- Module `FJ66` completes the T-001 branch checkpoint. It pauses `T-001` as
  an active proof-target sequence while keeping it unresolved in the archive,
  completes `OBL-T001-012`, records `OBL-T001-013`, resolves `OQ-088`, and
  selects `FJ67`, Target-Pivot Criteria After T-001 Pause.
- Module `FJ67` completes the target-pivot criteria checkpoint. It resolves
  `OQ-089`, records `OBL-PIVOT-001`, selects `FJ68`, and does not select a
  new active target.
- Module `FJ68` completes the target-pivot candidate matrix. It resolves
  `OQ-090`, completes `OBL-PIVOT-001` for the current comparison, selects
  `A-001`, records `OBL-ARTIN-001`, selects `FJ69`, and makes no global
  all-Artin theorem claim.
- Module `FJ69` completes the Artin subclass-gap inventory. It creates
  `ledgers/artin_subclass_gap_inventory.md`, resolves `OQ-091`, gives a
  first-pass current-repository answer to `OQ-021`, sharpens `OQ-023`,
  records `OBL-ARTIN-002`, selects `FJ70`, and makes no global all-Artin
  theorem claim.
- Module `FJ70` completes the Wu clique-reduction candidate filter. It
  records no current Wu-filter candidate from existing Artin gap rows,
  resolves `OQ-092`, completes `OBL-ARTIN-002`, records
  `OBL-ARTIN-003`, selects `FJ71`, and makes no global all-Artin theorem
  claim.
- Module `FJ71` completes the Artin branch checkpoint. It pauses the active
  Artin proof/source lane until a named reactivation payload appears,
  resolves `OQ-093`, records `OBL-ARTIN-004` and `OBL-PIVOT-002`, selects
  `A-004`, selects `FJ72`, and makes no global all-Artin theorem claim.
- Module `FJ72` completes the target-pivot refresh after the Artin pause. It
  records that no group-class target is currently ready for active proof or
  source work, resolves `OQ-094`, completes `OBL-PIVOT-002`, records
  `OBL-FND-001`, selects `FND-001`, selects `FJ73`, and makes no
  Farrell--Jones theorem claim.
- Module `FJ73` completes foundational open-question triage. It resolves
  `OQ-095`, completes `OBL-FND-001`, selects `OQ-005` as the bounded
  fixed-point convention blocker, records `OBL-FND-002`, selects `FND-002`,
  selects `FJ74`, and makes no Farrell--Jones theorem claim.
- Module `FJ74` completes fixed-point convention cleanup. It resolves
  `OQ-005` at first pass by recording `FND-CONV-001`, separates the strict
  contractible/empty model convention from the weakly contractible plus
  isotropy source criterion, completes `OBL-FND-002`, records
  `OBL-FND-003`, selects `FND-003`, selects `FJ75`, and makes no
  Farrell--Jones theorem claim.
- Module `FJ75` completes the virtually cyclic dichotomy source-payload
  check. It verifies DOI metadata for Farrell--Jones (1995), records that
  Lemma 2.5 was not accessed or promoted, resolves `OQ-006` negatively at
  first pass, completes `OBL-FND-003`, records `FND-SRC-001`, records
  `OBL-FND-004`, selects `FND-004`, selects `FJ76`, and makes no
  Farrell--Jones theorem claim.
- Module `FJ76` completes the foundational source-queue checkpoint after the
  `OQ-006` no-promotion result. It selects no further foundational source
  payload, records `FND-QUEUE-PAUSE-001`, resolves `OQ-096`, completes
  `OBL-FND-004`, records `OBL-PIVOT-003`, selects `PIVOT-003`, selects
  `FJ77`, and makes no Farrell--Jones theorem claim.
- Module `FJ77` completes target-pivot readiness after the foundational
  source-queue pause. It records no group-class target or foundational source
  packet ready for activation, resolves `OQ-097`, completes
  `OBL-PIVOT-003`, completes `PIVOT-003`, selects `C4-CLOSE-001`, records
  `OBL-C4-001`, selects `FJ78`, and makes no Farrell--Jones theorem claim.
- Module `FJ78` completes the cycle-004 closure-readiness audit. It records
  that the remaining two module slots should be used for handoff and
  reflection preparation, resolves `OQ-098`, completes `OBL-C4-001`,
  completes `C4-CLOSE-001`, selects `C4-HANDOFF-001`, records
  `OBL-C4-002`, selects `FJ79`, and makes no Farrell--Jones theorem claim.
- Module `FJ79` completes the cycle-004 handoff table and gate index. It
  creates `ledgers/cycle_004_handoff.md`, resolves `OQ-099`, completes
  `OBL-C4-002`, completes `C4-HANDOFF-001`, selects `C4-FINAL-001`,
  records `OBL-C4-003`, selects `FJ80`, and makes no Farrell--Jones theorem
  claim.
- Module `FJ80` completes the final pre-reflection closure module. It
  resolves `OQ-100`, completes `OBL-C4-003`, completes `C4-FINAL-001`,
  records that the numbered module portion of `cycle_004` is ready for
  reflection, selects `C4-REFLECT-001`, selects
  `reflections/cycle_004_reflection.md`, and makes no Farrell--Jones theorem
  claim.
- `reflections/cycle_004_reflection.md` closes cycle 004. It records that no
  target or source queue is active, resolves `OQ-101`, selects
  `C5-GATE-001`, records `OBL-C5-001`, selects `FJ81`, and makes no
  Farrell--Jones theorem claim.
- Module `FJ81` completes the cycle-005 reactivation gate audit. It resolves
  `OQ-102`, records that no reactivation gate is satisfied, completes
  `OBL-C5-001` and `C5-GATE-001`, selects `C5-PAYLOAD-001`, records
  `OBL-C5-002`, selects `FJ82`, and makes no Farrell--Jones theorem claim.
- Module `FJ82` completes the payload-acquisition protocol / project-pause
  decision. It resolves `OQ-103`, creates
  `ledgers/payload_intake_protocol.md`, records no immediate accepted
  payload, completes `OBL-C5-002` and `C5-PAYLOAD-001`, records
  `C5-PAUSE-001`, records `OBL-C5-003`, and makes no Farrell--Jones theorem
  claim.
- Module `FJ83` records accepted payload `PAY-T001-K0-CL-2025-001` and
  verifies the weaker \(K_0\) / Cohen--Lyndon source-payload package at
  first-pass level. It makes no full `T-001` claim and no residual
  subtraction.
- Module `FJ84` records accepted payload `PAY-T001-K0-CL-HYP-2026-001` and
  audits current `T-001` candidate rows against the FJ83 source hypotheses.
  It finds no FJ83-eligible current row, makes no full `T-001` claim, and
  makes no residual subtraction.
- Module `FJ85` records accepted governance payload
  `PAY-C5-GOV-NEXT-2026-001`. It resolves `OQ-106` by recording that no
  mathematical payload is currently present after `FJ84`, creates
  `OBL-C5-006`, and makes no Farrell--Jones theorem claim.

## Selected target

Current active project status: post-`FJ85` payload gate. `FJ85` was
instantiated by accepted governance payload `PAY-C5-GOV-NEXT-2026-001`; no
new numbered module is selected after FJ85.

Previous first serious target: `T-001`, torsion-free one-relator residual
gap analysis. After `FJ66`--`FJ68`, `T-001` is dormant rather than active. It
remains the archived first serious target, but a later module may reactivate
`T-001` only through `OBL-T001-013`.

The Artin lane is paused after `FJ71`. It remains unresolved and archived,
but a later module may reactivate it only through `OBL-ARTIN-004`: a named
graph, graph family, subclass, source theorem, bridge object, formulation
label, prior-art-overlap note, and changed project object.

No group-class target is currently active. No numbered module is currently
selected. Future numbered work requires a new accepted payload under
`ledgers/payload_intake_protocol.md`.

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
- candidate-intake reset: `FJ61` keeps `T-001` active only through intake
  governance until a candidate, bridge, computation, source payload,
  prior-art blocker, pause recommendation, or pivot comparison is recorded;
- blocker pruning: `FJ62` moves source-only and no-application items to
  deferred status and requires `FJ63` to choose one exact data-acquisition
  packet;
- data-acquisition packet: `FJ63` selects `DAP-T001-001`, candidate-row
  acquisition from current repository records, as the next required test;
- no-candidate note: `FJ64` executes `DAP-T001-001` and records that no
  current repository row can be promoted without new source acquisition or
  fabrication;
- branch-readiness checkpoint: `FJ65` records no prior-art blocker object
  and sends the target to `FJ66` for an explicit pause-or-pivot decision;
- branch decision: `FJ66` pauses `T-001` as an active proof-target sequence
  and requires pivot criteria before a new active target is selected;
- target-pivot criteria: `FJ67` records `OBL-PIVOT-001` and requires `FJ68`
  to apply a matrix before selecting any new active target;
- target-pivot matrix: `FJ68` selects `A-001`, Artin subclass-gap inventory
  after `FJ18`, and sends the project to `FJ69`;
- Artin subclass-gap inventory: `FJ69` creates
  `ledgers/artin_subclass_gap_inventory.md`, selects `A-002`, and sends the
  project to `FJ70`;
- Wu candidate filter: `FJ70` records no current Wu-filter candidate from
  existing Artin gap rows;
- Artin branch checkpoint: `FJ71` pauses the active Artin proof/source lane
  and sends the project to target-pivot refresh;
- target-pivot refresh after Artin pause: `FJ72` records no group-class
  target ready and selects foundational open-question triage;
- foundational triage: `FJ73` selects `OQ-005` as the first bounded
  foundational blocker after target pauses;
- fixed-point convention cleanup: `FJ74` records `FND-CONV-001`, keeping
  strict contractible/empty fixed-point models separate from Lueck's weakly
  contractible plus isotropy source criterion;
- selected foundational source-payload check: `FJ75` addressed `OQ-006`, the
  direct Farrell--Jones (1995) virtually cyclic dichotomy source check;
- virtually cyclic original-source access: `FJ75` records `FND-SRC-001`,
  DOI-checked but no-promotion status for Farrell--Jones (1995), Lemma 2.5;
- foundational source queue: `FJ76` decides that no further exact
  application-tethered source payload is ready and pauses the queue;
- foundational queue pause: `FJ76` records `FND-QUEUE-PAUSE-001`; a future
  foundations source module requires an exact payload, changed project
  object, current proof/candidate/route need, and stop condition;
- target-pivot readiness: `FJ77` applies `OBL-PIVOT-003`, records no target
  or source packet ready, and selects cycle-004 closure-readiness audit;
- cycle-004 closure readiness: `FJ78` applies `OBL-C4-001`, records that the
  remaining slots should prepare handoff and reflection, and selects
  `FJ79`;
- cycle-004 handoff: `FJ79` applies `OBL-C4-002` by building a compact
  handoff table and gate index in `ledgers/cycle_004_handoff.md`;
- cycle-004 final closure: `FJ80` applies `OBL-C4-003` by checking that the
  numbered module portion of the cycle is ready for
  `reflections/cycle_004_reflection.md`;
- cycle-004 reflection: `reflections/cycle_004_reflection.md` decides the
  next project posture from the recorded gates and handoff ledger;
- cycle-005 gate audit: `FJ81` applies `OBL-C5-001` by checking whether any
  recorded reactivation gate is satisfied from repository data and records a
  no-gate-ready state;
- payload-protocol decision: `FJ82` applies `OBL-C5-002` by defining a
  bounded payload-acquisition protocol and recording a payload-gated pause;
- payload-gated pause: `OBL-C5-003` blocked `FJ83` until an accepted payload
  row was recorded;
- K0 Cohen--Lyndon payload verification: `FJ83` records accepted payload
  `PAY-T001-K0-CL-2025-001`, verifies Jaikin-Zapirain--Linton--Sanchez-Peralta
  (2025) as a weaker \(K_0\) / Cohen--Lyndon source payload, updates
  `OQ-081`, resolves `OQ-104`, creates `OBL-T001-014` and `OBL-C5-004`, and
  makes no residual subtraction;
- K0 Cohen--Lyndon candidate hypothesis audit: `FJ84` records accepted
  payload `PAY-T001-K0-CL-HYP-2026-001`, checks the current `T-001`
  candidate inventory against the FJ83 source hypotheses, finds no eligible
  current row, resolves `OQ-105`, creates `OBL-T001-015` and `OBL-C5-005`,
  and makes no residual subtraction;
- payload-authorship governance checkpoint: `FJ85` records accepted
  governance payload `PAY-C5-GOV-NEXT-2026-001`, resolves `OQ-106`, creates
  `OBL-C5-006`, and records that no mathematical `FJ86` is selected;
- candidate-intake audit: `FJ86` records accepted payload
  `PAY-T001-CAND-BS23-2026-001` and adds `CAND-T001-004` for
  \(G_{BS23}=\langle a,t\mid ta^2t^{-1}a^{-3}\rangle\), but records no
  Farrell--Jones route and no residual subtraction;
- torsion-free / HNN check: `FJ87` records accepted payload
  `PAY-T001-BS23-TF-HNN-2026-001` and verifies the torsion-free status of
  `CAND-T001-004` at first pass, without computing kernel control or route
  status;
- known-route / prior-art blocker audit: `FJ88` records accepted payload
  `PAY-T001-BS23-ROUTE-PRIORART-2026-001` and verifies that
  `CAND-T001-004`, \(G_{BS23}=BS(2,3)\), is already routed by the
  Gandini--Meinert--Rueping graph-of-abelian-groups theorem; this closes the
  candidate as a live residual row but does not solve global `T-001`;
- live-candidate audit: `FJ89` records accepted payload
  `PAY-T001-LIVE-CAND-AUDIT-2026-001` and verifies internally that no current
  `T-001` candidate-inventory row remains live and non-routed after the FJ88
  closure; it records `NLC-T001-001`, resolves `OQ-110`, completes
  `OBL-C5-009`, creates `OBL-C5-010` and `OQ-111`, and makes no
  Farrell--Jones theorem claim;
- candidate-intake audit after no-live-candidate blocker: `FJ90` records
  accepted payload `PAY-T001-CAND-FJ90-2026-001` and adds `CAND-T001-005` as
  a concrete blocked intake row; it resolves `OQ-111`, completes
  `OBL-C5-010`, creates `OBL-T001-018`, `OBL-C5-011`, and `OQ-112`, and
  makes no Farrell--Jones theorem claim;
- torsion-free source check for `CAND-T001-005`: `FJ91` records accepted
  payload `PAY-T001-CAND005-TF-2026-001` and verifies torsion-free status at
  first-pass candidate-ledger level using Putman's statement of the
  Karrass--Magnus--Solitar one-relator torsion theorem; it resolves
  `OQ-112`, completes `OBL-C5-011`, partially completes `OBL-T001-018`,
  creates `OBL-T001-019`, `OBL-C5-012`, and `OQ-113`, and makes no
  Farrell--Jones route claim;
- Brown/BNS kernel-control computation for `CAND-T001-005`: `FJ92` records
  accepted payload `PAY-T001-CAND005-BROWN-BNS-2026-001`, verifies
  Brown-positive finite generation of \(\ker(\chi)\) for
  \(\chi(a)=0,\chi(b)=1\), resolves `OQ-113`, completes `OBL-C5-012`,
  partially completes `OBL-T001-019`, creates `OBL-T001-020`,
  `OBL-C5-013`, and `OQ-114`, and makes no Farrell--Jones route claim;
- known-route / prior-art blocker audit for `CAND-T001-005`: `FJ93` records
  accepted payload `PAY-T001-CAND005-ROUTE-PRIORART-2026-001`, finds no
  recorded route or prior-art blocker among the named repository routes,
  resolves `OQ-114`, completes `OBL-C5-013`, completes the route/prior-art
  part of `OBL-T001-020`, creates `OBL-T001-021`, `OBL-C5-014`, and
  `OQ-115`, and makes no Farrell--Jones route claim;
- FJ83 weaker \(K_0\) / Cohen--Lyndon hypothesis audit for
  `CAND-T001-005`: `FJ94` records accepted payload
  `PAY-T001-CAND005-K0-CL-HYP-2026-001`, finds the row not FJ83-eligible
  from current repository data, resolves `OQ-115`, completes `OBL-C5-014`,
  completes the FJ83-hypothesis part of `OBL-T001-021`, creates
  `OBL-T001-022`, `OBL-C5-015`, and `OQ-116`, and makes no weaker \(K_0\)
  or Farrell--Jones claim;
- branch checkpoint for `CAND-T001-005`: `FJ95` records accepted governance
  payload `PAY-T001-CAND005-BRANCH-2026-001`, demotes the row to blocked /
  inactive proof-target status, resolves `OQ-116`, completes `OBL-C5-015`
  and `OBL-T001-022`, creates `OBL-T001-023`, `OBL-C5-016`, and `OQ-117`,
  and makes no route, weaker \(K_0\), Farrell--Jones, or residual-subtraction
  claim;
- live-candidate audit after `CAND-T001-005` demotion: `FJ96` records
  accepted payload `PAY-T001-LIVE-CAND-AUDIT-AFTER-CAND005-2026-001`, finds
  no live non-routed `T-001` candidate row after `FJ95`, records
  `NLC-T001-002`, resolves `OQ-117`, completes `OBL-C5-016`, creates
  `OBL-C5-017` and `OQ-118`, and makes no route, source, candidate, or
  theorem claim;
- formulation-safety audit after no-live-candidate state: `FJ97` records
  accepted payload `PAY-FORMULATION-SAFETY-AUDIT-2026-001`, finds no active
  candidate route requiring formulation classification, records
  formulation-irrelevant status, resolves `OQ-118`, completes `OBL-C5-017`,
  creates `OBL-C5-018` and `OQ-119`, and makes no formulation promotion,
  route, source, candidate, or theorem claim;
- target-pivot readiness after formulation audit: `FJ98` records accepted
  payload `PAY-PIVOT-READINESS-2026-001`, finds no mathematical target lane
  with a concrete next object, records all-targets-paused /
  no-target-ready status, resolves `OQ-119`, completes `OBL-C5-018`, creates
  `OBL-C5-019` and `OQ-120`, and makes no source, route, candidate,
  proof-attempt, or theorem claim;
- cycle-005 strategic checkpoint: `FJ99` records accepted payload
  `PAY-C5-STRATEGIC-CHECKPOINT-2026-001`, audits `FJ81` onward, records
  that cycle 005 made candidate-level progress but is now no-target-ready /
  governance-only, resolves `OQ-120`, completes `OBL-C5-019`, creates
  `OBL-C5-020` and `OQ-121`, and makes no source, route, candidate,
  proof-attempt, target-reactivation, or theorem claim;
- cycle-005 closure-readiness audit: `FJ100` records accepted payload
  `PAY-C5-CLOSURE-READINESS-2026-001`, records `cycle_005` as
  closure-ready, creates `ledgers/cycle_005_handoff.md`, resolves
  `OQ-121`, completes `OBL-C5-020`, creates `OQ-122` and `OBL-C5-021`, and
  makes no source, route, candidate, proof-attempt, target-reactivation, or
  theorem claim;
- cycle-005 reflection: `reflections/cycle_005_reflection.md` closes
  `cycle_005`, records that the cycle produced real candidate-level progress
  but no theorem or residual subtraction, resolves `OQ-122`, completes
  `OBL-C5-021`, creates `OQ-123`, records `OBL-POST100-001`, and selects
  Prompt 022, the post-100-module strategic review;
- post-100-module strategic review:
  `reflections/post_100_module_strategic_review.md` resolves `OQ-123`,
  completes `OBL-POST100-001`, creates `OQ-124`, records `OBL-C6-001`, and
  selects Prompt 023, the cycle-006 entry-gate audit;
- cycle-006 entry-gate audit: `ledgers/cycle_006_entry_gate.md` resolves
  `OQ-124`, completes `OBL-C6-001`, records a no-gate-ready state, creates
  `OQ-125`, records `OBL-C6-002`, and selects Prompt 024, the cycle-006
  payload acquisition / project-pause decision;
- cycle-006 payload decision: `ledgers/cycle_006_payload_decision.md`
  resolves `OQ-125`, completes `OBL-C6-002`, records `C6-PAUSE-001`, creates
  `OQ-126`, records `OBL-C6-003`, and originally selects no `FJ101` module;
- continue-payload queue and FJ101--FJ123 intake: `FJ101` consumes only row
  `001`, `FJ102` consumes only row `002`, `FJ103` consumes only row `003`,
  `FJ104` consumes only row `004`, `FJ105` consumes only row `005`, and
  `FJ106` consumes only row `006`, `FJ107` consumes only row `007`, and
  `FJ108` consumes only row `008`, `FJ109` consumes only row `009`, and
  `FJ110` consumes only row `010`, `FJ111` consumes only row `011`, and
  `FJ112` consumes only row `012`, `FJ113` consumes only row `013`, and
  `FJ114` consumes only row `014`, `FJ115` consumes only row `015`,
  `FJ116` consumes only row `016`, `FJ117` consumes only row `017`,
  `FJ118` consumes only row `018`, `FJ119` consumes only row `019`,
  `FJ120` consumes only row `020`, `FJ121` consumes only row `021`,
  `FJ122` consumes only row `022`, and `FJ123` consumes only row `023` of
  `ledgers/payload_execution_queue.md`, adding `CAND-T001-C6-001` through
  `CAND-T001-C6-023` as
  candidate-admissible but route-unresolved rows, creating `OQ-127` /
  `OBL-C6-004`, `OQ-128` / `OBL-C6-005`, `OQ-129` / `OBL-C6-006`,
  `OQ-130` / `OBL-C6-007`, `OQ-131` / `OBL-C6-008`, and `OQ-132` /
  `OBL-C6-009`, `OQ-133` / `OBL-C6-010`, `OQ-134` / `OBL-C6-011`, and
  `OQ-135` / `OBL-C6-012`, `OQ-136` / `OBL-C6-013`, and `OQ-137` /
  `OBL-C6-014`, and `OQ-138` / `OBL-C6-015`, and `OQ-139` /
  `OBL-C6-016`, and `OQ-140` / `OBL-C6-017`, and `OQ-141` /
  `OBL-C6-018`, and `OQ-142` / `OBL-C6-019`, and `OQ-143` /
  `OBL-C6-020`, and `OQ-144` / `OBL-C6-021`, and `OQ-145` /
  `OBL-C6-022`, and `OQ-146` / `OBL-C6-023`, and `OQ-147` /
  `OBL-C6-024`, and `OQ-148` / `OBL-C6-025`, and `OQ-149` /
  `OBL-C6-026`, and making no
  Farrell--Jones theorem claim or residual subtraction;
- bridge source: Linton's `Hyperbolic one-relator groups`;
- orientation source: Linton--Nyberg-Brodda's one-relator survey;
- classical sources to verify before proof-sensitive use:
  Lyndon--Schupp and Magnus--Karrass--Solitar.

## Next mathematical move

The project is in a cycle-006 payload-gated callback posture.
`ledgers/payload_execution_queue.md` rows `001`--`023` have been completed by
`FJ101`--`FJ123`; the next mathematical move requires either the exact
callback phrase `Continue payload` to consume the next `Ready for intake`
queue row, or a separately supplied concrete accepted payload under
`ledgers/payload_intake_protocol.md`.
Template prompts in `next_prompts.md` are not executable until concretely
filled.
