# The Farrell--Jones Program in Algebraic K-Theory

This repository is an exploratory mathematical research archive focused on the **K-theoretic Farrell--Jones conjecture** for group rings.

## Central aim

Develop a modular research program around the Farrell--Jones conjecture by:

1. stating the conjecture precisely;
2. understanding assembly maps and classifying spaces for families;
3. working through basic examples;
4. cataloging known cases and inheritance principles;
5. identifying concrete unresolved or reducible subclasses of groups;
6. cutting the work into bounded modules.

## Current module cycle

- Active cycle: `cycle_005`.
- Completed cycles: `cycle_001`, `cycle_002`, `cycle_003`, and
  `cycle_004`.
- Completed first-pass modules: `FJ01`, `FJ02`, `FJ03`, `FJ04`, `FJ05`, `FJ06`, `FJ07`, `FJ08`, `FJ09`, `FJ10`, `FJ11`, `FJ12`, `FJ13`, `FJ14`, `FJ15`, `FJ16`, `FJ17`, `FJ18`, `FJ19`, `FJ20`, `FJ21`, `FJ22`, `FJ23`, `FJ24`, `FJ25`, `FJ26`, `FJ27`, `FJ28`, `FJ29`, `FJ30`, `FJ31`, `FJ32`, `FJ33`, `FJ34`, `FJ35`, `FJ36`, `FJ37`, `FJ38`, `FJ39`, `FJ40`, `FJ41`, `FJ42`, `FJ43`, `FJ44`, `FJ45`, `FJ46`, `FJ47`, `FJ48`, `FJ49`, `FJ50`, `FJ51`, `FJ52`, `FJ54`, `FJ55`, `FJ56`, `FJ57`, `FJ58`, `FJ59`, `FJ60`, `FJ61`, `FJ62`, `FJ63`, `FJ64`, `FJ65`, `FJ66`, `FJ67`, `FJ68`, `FJ69`, `FJ70`, `FJ71`, `FJ72`, `FJ73`, `FJ74`, `FJ75`, `FJ76`, `FJ77`, `FJ78`, `FJ79`, `FJ80`, `FJ81`, and `FJ82`.
- `FJ53` is retained as WIP / provisional.
- Completed cycle reflections: `reflections/cycle_001_reflection.md`, `reflections/cycle_002_reflection.md`, `reflections/cycle_003_reflection.md`, and `reflections/cycle_004_reflection.md`.
- Selected first serious target: `T-001`, torsion-free one-relator residual gap analysis.
- Current active project status: `C5-PAUSE-001`, payload-gated pause.
- Current procedural target: no numbered module is selected; instantiate `FJ83` only after an accepted payload is recorded in `ledgers/payload_intake_protocol.md`.

## Current established results

- `ER-001`: the trivial group case of the simplified K-theoretic assembly map.
- `ER-002`: the source-verified existence and homotopy characterization of classifying spaces for project-style families of subgroups, now governed by the `FJ74` convention separating strict readable models from the weakly contractible source criterion.
- `ER-003`: \(\mathcal{VCyc}(G)\) is a family of subgroups, with the infinite virtually cyclic dichotomy recorded through the checked Lueck--Reich source; `FJ75` does not promote Farrell--Jones (1995), Lemma 2.5, to direct theorem-use status.
- `ER-004`: for \(G=\mathbb Z\), the simplified assembly map is the identity under the point model for \(E_{\mathcal{VCyc}}\mathbb Z\), with target \(K_n(R[t,t^{-1}])\).
- `ER-005`: the source-verified Bass--Heller--Swan decomposition of \(K_n(R[\mathbb Z])\), including the two \(NK_n(R)\)-summands.
- `ER-006`: conditional Whitehead-group vanishing from Farrell--Jones for torsion-free groups with regular coefficients.
- `ER-007`: conditional vanishing of \(\widetilde K_0(\mathbb Z[G])\), with the finiteness-obstruction interpretation for finitely presented groups.
- `ER-008`: conditional Borel consequence from low-dimensional K-theory vanishing and \(L^{\langle -\infty\rangle}\)-theory assembly.
- `ER-009`: first source-verified known classes: hyperbolic groups, finite-dimensional CAT(0)-groups, and virtually solvable groups, with version flags and first-pass proof-route maps for hyperbolic and CAT(0)-groups.
- `ER-010`: first source-verified inheritance-properties ledger, separating coefficient K-theory inheritance from survey-level full \(\mathcal{FJ}\) closure properties.
- `ER-011`: first source-verified Artin-group Farrell--Jones subclass ledger, including FC-type Artin groups, even FC-type Artin groups, RAAG-related semidirect products, Wu's even-Artin clique and join constructions, and Roushon's listed finite real, complex, and affine types, all only under their source hypotheses.
- `ER-012`: first source-verified one-relator-group Farrell--Jones status ledger, including conditional routes through hyperbolic, finite-dimensional CAT(0), virtually solvable, and hyperbolic-by-cyclic classes, while keeping the global torsion-free one-relator class unresolved inside the project.
- `ER-013`: source-verified additive-category K-theory formulation and source-convention policy, adopting Bartels--Reich's coefficient formulation as the first-pass project convention.
- `ER-014`: source-verified `FJCw` finite-index overgroup bridge, authorizing finite-index passage only when the finite-index subgroup carries the finite-wreath-product version.

See `ESTABLISHED_RESULTS.md` for exact statements, hypotheses, proof locations, and source status.

## Current cautions

- The repository has not proved or claimed the Farrell--Jones conjecture in full generality.
- `FJ02` is now a first-pass source-convention module. It adopts Bartels--Reich's additive-category K-theory formulation, but it does not identify `FJCw`, `FICwF`, full \(\mathcal{FJ}\), and simplified ring-coefficient statements without checked comparison data.
- `FJ47` verifies a finite-index overgroup bridge only for `FJCw`. It does not authorize plain coefficient K-theory finite-index passage.
- `FJ48` audits current `RB-005` cases and finds no `T-001` finite-index subgroup input already recorded with `FJCw`; the `FJ47` bridge therefore produces no immediate residual subtraction.
- `FJ49` source-checks the direct CAT(0) finite-extension bridge and does not promote it: Ruane records the finite-extension direction as a question, with cocompactness as the unresolved point.
- `FJ50` pauses `RB-005` after its finite-index bridge sequence produces no residual subtraction and selects `RB-006` as the next bounded attack packet.
- `FJ51` selects Louder--Wilton only as a bounded `RB-006` source-boundary check; no theorem from that source is imported yet.
- `FJ52` checks Louder--Wilton and records no independent `RB-006` compact-special/CAT(0) route delta; its useful output is hyperbolic-route overlap through `FJ23`.
- `FJ53` is WIP / provisional: it records \(\pi(w)>2\) as a hyperbolic-overlap route criterion through `FJ23`, but the Louder--Wilton `RB-006` path is only demoted / provisionally non-subtractive pending a genuinely non-hyperbolic bridge.
- `FJ54` records the residual-bucket checkpoint after the `RB-006` demotion and selects the primary `RB-003` + `RB-004`/`RB-008` hybrid attack packet.
- `FJ55` records that hierarchy / primitive-extension data alone is not an FJ route in the current repository; it creates proof obligations `OBL-T001-001` and `OBL-T001-002` and sends the project to kernel-control candidate inventory.
- `FJ56` records that the current concrete kernel-control candidate rows are calibration-only or already removed through `FJ26`; it creates `OBL-T001-003` and sends the project to a candidate-family proof attempt or obstruction record.
- `FJ57` records that no repository-supported non-routed candidate can be promoted for the selected hybrid packet without fabrication; it creates `OBL-T001-004` and sends the project to a post-hybrid candidate-production checkpoint.
- `FJ58` records that no replacement candidate-production lane is currently ready after the blocked hybrid packet; it creates `OBL-T001-005` and sends the project to a bounded weaker \(K_0\) / Cohen--Lyndon consequence intake gate.
- `FJ59` records that no weaker \(K_0\) / Cohen--Lyndon source payload is currently present in the repository; it creates `OBL-T001-006` and sends the project to a one-module source-payload selection or closure step.
- `FJ60` records that no exact weaker \(K_0\) / Cohen--Lyndon source payload is available for selection, closes that consequence lane as inactive via `OBL-T001-007`, and sends the project to the cycle-003 reflection.
- `reflections/cycle_003_reflection.md` closes cycle 003 and selects `FJ61`, T-001 Candidate-Intake Reset and Exit Criteria, as the first cycle-004 move. `T-001` remains important but is not currently candidate-ready.
- `FJ61` completes the candidate-intake reset for `T-001`: it defines candidate-admissible rows, allowed route-output targets, early cycle-004 exit criteria, and `OBL-T001-008`; the next move is `FJ62`, Active Blocker Pruning for `T-001`.
- `FJ62` completes active blocker pruning for `T-001`: it preserves only candidate-object acquisition, route-data acquisition, and branch-decision blockers as active for early cycle 004, records `OBL-T001-009`, and selects `FJ63`, Candidate-Data Acquisition Packet.
- `FJ63` selects exactly one data-acquisition packet: `DAP-T001-001`, candidate-row acquisition from current repository records. It records `OBL-T001-010` and sends the project to `FJ64`, Candidate Intake Attempt or No-Candidate Note.
- `FJ64` executes `DAP-T001-001` and records a no-candidate note: no current repository row can be promoted to candidate-admissible status without external source acquisition or fabrication. It completes `OBL-T001-010`, records `OBL-T001-011`, and sends the project to `FJ65`, Prior-Art / Branch-Readiness Checkpoint.
- `FJ65` completes the prior-art / branch-readiness checkpoint: no exact prior-art blocker object or pivot-comparison object is available, but the no-candidate state is a target-pause trigger. It records `OBL-T001-012` and sends the project to `FJ66`, T-001 Branch Checkpoint.
- `FJ66` pauses `T-001` as an active proof-target sequence, while keeping it unresolved in the archive. It records `OBL-T001-013`, the reactivation gate, and sends the project to `FJ67`, Target-Pivot Criteria After T-001 Pause.
- `FJ67` completes the target-pivot criteria checkpoint: it records `OBL-PIVOT-001`, requires a target-pivot matrix before any new active target is selected, keeps `T-001` dormant unless `OBL-T001-013` is met, and sends the project to `FJ68`, Target-Pivot Candidate Matrix.
- `FJ68` completes the target-pivot candidate matrix: it selects `A-001`, Artin subclass-gap inventory after `FJ18`, as the bounded next target packet; it defers automatic / biautomatic and Thompson-type groups, keeps `T-001` dormant, records `OBL-ARTIN-001`, and sends the project to `FJ69`, Artin Subclass-Gap Inventory After FJ18.
- `FJ69` completes the Artin subclass-gap inventory: it creates `ledgers/artin_subclass_gap_inventory.md`, normalizes two `FJ18` source-verified rows into `ledgers/known_classes.md`, gives a first-pass current-repository answer to `OQ-021`, sharpens `OQ-023`, records `OBL-ARTIN-002`, and sends the project to `FJ70`, Wu Clique-Reduction Candidate Filter for Artin Gap Rows.
- `FJ70` completes the Wu clique-reduction candidate filter: it records no current Wu-filter candidate from existing Artin gap rows, completes `OBL-ARTIN-002`, records `OBL-ARTIN-003`, and sends the project to `FJ71`, Artin Branch Checkpoint After Wu Filter.
- `FJ71` completes the Artin branch checkpoint: it pauses the active Artin proof/source lane until a named reactivation payload appears, records `OBL-ARTIN-004` and `OBL-PIVOT-002`, selects `A-004`, and sends the project to `FJ72`, Target-Pivot Refresh After Artin Pause.
- `FJ72` completes the target-pivot refresh after the Artin pause: it records that no group-class target is currently ready for active proof or source work, completes `OBL-PIVOT-002`, records `OBL-FND-001`, selects `FND-001`, and sends the project to `FJ73`, Foundational Open-Question Triage After Target Pauses.
- `FJ73` completes foundational open-question triage: it selects `OQ-005`, weakly contractible versus contractible fixed-point formulations, as the bounded blocker for immediate action, records `OBL-FND-002`, selects `FND-002`, and sends the project to `FJ74`, Fixed-Point Convention Cleanup for Classifying Spaces.
- `FJ74` completes the fixed-point convention cleanup: it resolves `OQ-005` at first pass by separating the strict contractible/empty model convention from the weakly contractible plus isotropy source-level criterion, records `FND-CONV-001`, completes `OBL-FND-002`, records `OBL-FND-003`, selects `FND-003`, and sends the project to `FJ75`, Virtually Cyclic Dichotomy Source-Payload Check.
- `FJ75` completes the virtually cyclic dichotomy source-payload check: it verifies the Farrell--Jones (1995) DOI metadata but does not access the primary Lemma 2.5 text, records no-promotion status `FND-SRC-001`, completes `OBL-FND-003`, records `OBL-FND-004`, and sends the project to `FJ76`, Foundational Source-Queue Checkpoint After `OQ-006` No-Promotion.
- `FJ76` completes the foundational source-queue checkpoint: it selects no further foundational source payload, pauses the queue through `FND-QUEUE-PAUSE-001`, completes `OBL-FND-004`, records `OBL-PIVOT-003`, and sends the project to `FJ77`, Target-Pivot Readiness After Foundational Queue Pause.
- `FJ77` completes target-pivot readiness after the foundational queue pause: it records no target or source packet ready for activation, completes `OBL-PIVOT-003`, selects `C4-CLOSE-001`, records `OBL-C4-001`, and sends the project to `FJ78`, Cycle-004 Closure-Readiness Audit.
- `FJ78` completes the cycle-004 closure-readiness audit: it records that the remaining cycle slots should be used for handoff and reflection preparation, completes `OBL-C4-001`, selects `C4-HANDOFF-001`, records `OBL-C4-002`, and sends the project to `FJ79`, Cycle-004 Handoff Table and Gate Index.
- `FJ79` completes the cycle-004 handoff table and gate index: it creates `ledgers/cycle_004_handoff.md`, resolves `OQ-099`, completes `OBL-C4-002`, selects `C4-FINAL-001`, records `OBL-C4-003`, and sends the project to `FJ80`, Final Pre-Reflection Closure Module.
- `FJ80` completes the final pre-reflection closure module: it resolves `OQ-100`, completes `OBL-C4-003`, completes `C4-FINAL-001`, selects `C4-REFLECT-001`, and sends the project to `reflections/cycle_004_reflection.md`.
- `reflections/cycle_004_reflection.md` closes cycle 004: it records that `T-001`, the Artin lane, deferred group classes, and the foundational source queue remain gated, resolves `OQ-101`, selects `C5-GATE-001`, records `OBL-C5-001`, and sends the project to `FJ81`, Cycle-005 Reactivation Gate Audit.
- `FJ81` completes the cycle-005 reactivation gate audit: it resolves `OQ-102` by recording that no recorded reactivation gate is satisfied, completes `OBL-C5-001` and `C5-GATE-001`, selects `C5-PAYLOAD-001`, records `OBL-C5-002`, and sends the project to `FJ82`, Payload Acquisition Protocol or Project-Pause Decision.
- `FJ82` completes the payload-acquisition protocol / project-pause decision: it creates `ledgers/payload_intake_protocol.md`, resolves `OQ-103`, completes `OBL-C5-002` and `C5-PAYLOAD-001`, records `C5-PAUSE-001`, records `OBL-C5-003`, and selects no `FJ83` until an accepted payload is recorded.
- `FJ06` identifies \(R[\mathbb Z]\cong R[t,t^{-1}]\) after choosing a generator, but deliberately does not use the Bass--Heller--Swan decomposition.
- `FJ07` imports Bass--Heller--Swan as a source-verified theorem, not as an internal proof.
- `FJ08` records a conditional Whitehead-group consequence; it does not claim \(\mathrm{Wh}(G)=0\) for groups with torsion.
- `FJ09` uses Lueck--Reich's survey for Wall finiteness obstruction; primary-source verification is deferred.
- `FJ10` imports \(L\)-theory only as an application dependency; it does not make Borel rigidity a K-theory-only result.
- `FJ11` is a first-pass known-cases ledger, not an exhaustive classification of all known Farrell--Jones groups.
- `FJ11` records "with coefficients in additive categories" as a source-level strength flag now governed by the first-pass `FJ02` convention.
- `FJ12` records inheritance properties with version flags. Pullback and subgroup inheritance are source-verified for the coefficient K-theoretic formulation; several broader closure rows are recorded as survey-level statements about Lueck's full class \(\mathcal{FJ}\).
- `FJ13` is a proof-skeleton map for hyperbolic groups, not an internal reconstruction of the Bartels--Lueck--Reich proof.
- `FJ14` is a proof-skeleton map for CAT(0)-groups, not an internal reconstruction of Wegner's proof or the Bartels--Lueck flow-space cover technology.
- `FJ15` is a controlled-algebra vocabulary primer for obstruction categories and gain-control strategy; it does not introduce controlled h-cobordism or prove obstruction-category vanishing.
- `FJ16` is a flow-spaces primer for hyperbolic and CAT(0) proof technology; it records cover theorem routes but does not prove Mineyev flow estimates or long-cover theorems internally.
- `FJ17` is a transfers primer; it records the source-level transfer diagrams and strong-transfer-reducibility route, but it does not reconstruct the Waldhausen/Karoubi machinery, stability theorem, or obstruction-category vanishing proofs internally.
- `FJ18` is an Artin groups dossier; it records source-verified subclasses and method routes, but it does not claim the Farrell--Jones conjecture for all Artin groups.
- `FJ19` is a one-relator groups dossier; it records source-verified conditional routes and the Brodskii--Howie local-indicability structure theorem, but it does not claim Farrell--Jones for all torsion-free one-relator groups.
- `FJ20` selects `T-001`, torsion-free one-relator residual gap analysis, as the first serious target. This is a project-selection result, not a mathematical theorem.
- `reflections/cycle_001_reflection.md` closes cycle 001 and proposes the next twenty-module cycle. It is a reflection artifact, not a theorem source.
- `FJ21` selects the first-pass one-relator source toolkit: Linton's hierarchy work as the modern spine, Linton's hyperbolic one-relator paper as a bridge source, and classical Magnus/Lyndon-Schupp sources as items to verify before proof-sensitive use. This is a source-selection result, not a theorem.
- `FJ22` adopts Linton's finite one-relator complex hierarchy theorem as the first-pass hierarchy theorem for `T-001`, and records the vocabulary of one-relator complexes, Magnus subgraphs, one-relator towers, one-relator hierarchies, \(\mathbb Z\)-stable hierarchies, quasi-convex hierarchies, and acylindrical hierarchies. This is a theorem map and vocabulary module, not a new Farrell--Jones result.
- `FJ23` subtracts the hyperbolic route from `T-001`: torsion-free one-relator groups are removed from the active residual target once the project has a source-verified bridge to word-hyperbolicity. It does not claim that all remaining groups are non-hyperbolic or outside Farrell--Jones.
- `FJ24` subtracts the finite-dimensional CAT(0) route from `T-001`. Compact finite-dimensional special cube complex groups are recorded as CAT(0)-route bridge cases, but merely virtual-special statements still require finite-index handling before proof-sensitive use.
- `FJ25` subtracts the virtually solvable route from `T-001`: torsion-free one-relator groups are removed from the active residual target only once the project records a virtual-solvability bridge. Local indicability, nontrivial abelianization, and one-relator HNN hierarchy data are not treated as virtual-solvability proofs.
- `FJ26` subtracts the hyperbolic-by-cyclic/free-by-cyclic route from `T-001`: torsion-free one-relator groups are removed from the active residual target only once the project records a mapping-torus bridge matching the Bestvina--Fujiwara--Wigglesworth hypotheses, or a finite-rank free-by-cyclic bridge. Epimorphisms to \(\mathbb Z\), HNN splittings, and hierarchy data are not treated as mapping-torus proofs by themselves.
- `FJ27` subtracts source-verified inheritance routes from `T-001` only when the exact inheritance bridge is recorded and the version flag is preserved. Coefficient K-theory rows and Lueck's full \(\mathcal{FJ}\) survey rows are not merged into one unlabeled closure principle.
- `FJ28` assembles the conservative `T-001` residual ledger after the named and inheritance route subtractions. The residual ledger records missing project bridges, not counterexamples or negative Farrell--Jones results.
- `FJ29` selects `RB-004`, finite-rank free-kernel recognition over \(\mathbb Z\), as the next attack surface and Brown (1987) as the first source to verify. It does not use Brown as a theorem source yet.
- `FJ30` verifies Brown (1987) as a first-pass kernel-recognition source for selected `RB-004` cases. Brown gives a computable criterion for two-generator one-relator groups, but not a global positive theorem for every one-relator epimorphism to \(\mathbb Z\).
- `FJ31` runs Brown's criterion on the calibration example \(\langle x,y\mid xyx^{-1}y^{-1}\rangle\) with \(\chi(x)=1\), \(\chi(y)=0\). The example verifies the Brown workflow and gives a finite-rank free-by-cyclic bridge, but it is already covered by the virtually solvable route and is not a new residual removal.
- `FJ32` selects \(G_{2,3}=\langle x,y\mid x^2y^{-3}\rangle\), \(\chi(x)=3\), \(\chi(y)=2\), as the next nonabelian Brown test case. It records a preliminary Brown-positive maximum-count computation, but does not yet claim a finite-rank free-kernel bridge or a new Farrell--Jones route subtraction.
- `FJ33` completes the worked Brown test for \(G_{2,3}\), rewrites it as \(F_2\rtimes\mathbb Z\), verifies target status as a torsion-free one-relator group, and records a concrete finite-rank free-by-cyclic route bridge through `FJ26`.
- `FJ34` proves the Brown-positive finite-generation statement for \(G_{p,q}=\langle x,y\mid x^p y^{-q}\rangle\), \(p,q\geq2\), \(\gcd(p,q)=1\), while leaving the finite-rank free-kernel bridge open at that stage.
- `FJ35` selects a Bass--Serre freeness bridge, sourced from Serre's *Trees*, as the clean route from Brown finite generation to finite-rank freeness for \(K_{p,q}=\ker(\chi_{p,q})\), without invoking `FJ26` at that stage.
- `FJ36` verifies the Bass--Serre freeness bridge for \(K_{p,q}\), records \(G_{p,q}\cong F_n\rtimes\mathbb Z\) for some finite \(n\), and removes this family through the `FJ26` finite-rank free-by-cyclic route.
- `FJ37` audits the residual after the \(G_{p,q}\)-family route bridge, defers exact rank computation for \(K_{p,q}\), and selects `OQ-044` as the next target: source selection for `RB-004` cases outside Brown's checked two-generator criterion.
- `FJ38` selects the BNS/Bieri--Renz/Bieri/Karrass--Solitar normal-subgroup source cluster for beyond-Brown `RB-004` work. It is source selection only; `FJ39` checks the Karrass--Solitar bridge first and leaves direct BNS theorem use open.
- `FJ39` verifies Karrass--Solitar (1978) as a finitely presented normal-subgroup bridge: the checked theorem requires a nontrivial finitely presented normal subgroup of infinite index. It does not upgrade BNS finite-generation statements to direct theorem use and does not remove a residual bucket.
- `FJ40` audits finitely presented-kernel candidates for `RB-004` and does not select a new non-Brown source-ready example. The known source-ready finite-rank free kernels are already calibration or \(G_{p,q}\)-family route cases, so it closes the module portion of cycle 002.
- `reflections/cycle_002_reflection.md` closes cycle 002 and selects `FJ41`, direct BNS theorem verification for `RB-004`, as the first move of cycle 003.
- `FJ41` verifies Bieri--Neumann--Strebel (1987), Theorem B1, as a direct finite-generation criterion for normal subgroups \(N\trianglelefteq G\) with \(G\) finitely generated and \(G/N\) abelian. For a surjection \(G\to\mathbb Z\), it gives the two-sided \([\chi]\), \([-\chi]\) criterion. It does not compute the BNS invariant for a new one-relator family, does not prove freeness or finite rank of the kernel, and makes no residual subtraction.
- `FJ42` checks Bieri (1976) source access and route impact. The Bieri article metadata is verified, but the primary theorem text was not directly extractable in this run, so no Bieri theorem is promoted to source-verified use. Later comparison sources point to finite-presentation or type-`VFP` hypotheses rather than mere finite generation, so `FJ42` records no residual subtraction and sends the project to a route-delta checkpoint.
- `FJ43` completes the route-delta checkpoint for the BNS/Bieri/Karrass--Solitar source cluster. It pauses automatic continuation of `RB-004` source verification until a candidate-ready route, missing bridge, or named residual subtraction is identified, and selects `FJ44` for residual-bucket comparison and attack-packet selection.
- `FJ44` compares residual buckets after the `RB-004` source-cluster pause and selects `RB-005`, finite-index and virtually compact special formulation handling, as the next attack packet. It records no route subtraction and sets `FJ45` as a finite-index formulation bridge checkpoint.
- `FJ45` completes the finite-index formulation bridge checkpoint for `RB-005`. The only finite-index overgroup passage currently licensed by the repository is Lueck's full \(\mathcal{FJ}\) survey-level row; no coefficient K-theory finite-index overgroup bridge or direct CAT(0) finite-extension bridge is promoted to use, and no residual subtraction is made.
- `FJ46` resolves the `RB-005` source-convention decision by selecting an interruption for `FJ02` rather than a narrow coefficient finite-index source hunt. It records the minimum `FJ02` payload needed before `RB-005` resumes and makes no residual subtraction.
- `FJ02` completes the source-convention interruption selected by `FJ46`: it adopts Bartels--Reich Conjecture 3.2 as the first-pass coefficient K-theory formulation, records the additive-category notation, and sends `RB-005` back to a narrower finite-index bridge source-selection task.
- `FJ47` verifies the `FJCw` finite-index overgroup bridge from Bartels--Lueck--Reich--Rueping, while recording from Wang that plain coefficient finite-index closure is not imported as an unconditional theorem. It makes no residual subtraction.
- `FJ48` completes the `RB-005` `FJCw` application audit: virtual compact special and Karrass--Solitar infinite-dihedral cleanup cases are not currently `FJCw-ready`, so no residual subtraction is made; `FJ49` is selected to check a direct CAT(0) finite-extension bridge.
- `FJ49` checks the direct finite-dimensional CAT(0) finite-extension bridge and records it as unavailable for project route use: Ruane treats finite extensions of CAT(0)-groups as a question, not a theorem. No residual subtraction is made.
- `FJ50` completes the `RB-005` route-delta checkpoint: `RB-005` is paused, no residual subtraction is made, and `FJ51` is selected to prepare an `RB-006` compact-special/CAT(0)-looking attack packet.
- `FJ51` completes the `RB-006` source-selection attack packet: Louder--Wilton is selected for `FJ52` as a negative-immersion boundary check, with a stop condition against duplicating the hyperbolic route. No residual subtraction is made.
- `FJ52` completes the Louder--Wilton boundary check: \(\pi(w)>2\) characterizes negative immersions, but the source does not itself prove hyperbolicity, compact specialness, or CAT(0) status. No `RB-006` subtraction is made.
- `FJ53` is retained as WIP / provisional: the \(\pi(w)>2\) criterion is recorded only as a route through `FJ23`, not as `RB-006` progress, and no concrete presentation word is subtracted from the residual.
- `FJ54` completes the post-`RB-006` residual-bucket checkpoint: `RB-006` is demoted pending a genuinely non-hyperbolic bridge, and the project selects the `RB-003` + `RB-004`/`RB-008` hybrid as the next primary attack packet.
- `FJ55` completes the primitive-extension / hierarchy-to-FJ bridge test: no direct hierarchy-to-FJ bridge is recorded, so the hybrid packet must proceed through explicit route-output and kernel-control obligations.
- `FJ56` completes the kernel-control candidate inventory: existing concrete rows have explicit kernel-control data but are route-exhausted, and no live non-routed candidate is currently present.
- `FJ57` completes the candidate-family proof-attempt check by recording a no-candidate obstruction, not by inventing a new family.
- `FJ58` completes the post-hybrid candidate-production checkpoint: all currently named residual lanes remain dormant or blocked as proof-attempt lanes, so the next step is a bounded weaker \(K_0\) / Cohen--Lyndon intake, not a residual subtraction.
- `FJ59` completes that intake gate: existing \(K_0\)-level consequences are only conditional on Farrell--Jones, and no Cohen--Lyndon-style source payload is recorded yet.
- `FJ60` completes the source-payload selection step by closing the weaker consequence lane as inactive until a future module names an exact payload; no new source is checked and no residual case is removed.
- `reflections/cycle_003_reflection.md` completes the third cycle reflection: the next cycle begins with candidate-intake governance, not source accumulation.
- `FJ61` completes the first cycle-004 governance module: `T-001` remains active only through intake and blocker pruning until a candidate, bridge, computation, source payload, prior-art blocker, pause recommendation, or pivot comparison is recorded.
- `FJ62` completes the blocker-pruning module: most route-delta questions from cycle 003 are historical or deferred, and `FJ63` must select exactly one data-acquisition packet or record failure to do so.
- `FJ63` completes the packet-selection step: the next module must execute candidate-row acquisition from existing repository records and either add one candidate-admissible row or record a no-candidate note.
- `FJ64` completes that candidate-row acquisition attempt with a no-candidate note. `T-001` remains unresolved and active only through a prior-art / branch-readiness checkpoint, not through source accumulation.
- `FJ65` completes the prior-art / branch-readiness checkpoint by sending `T-001` to an explicit branch decision in `FJ66`.
- `FJ66` completes the branch decision: `T-001` is paused as an active proof-target sequence, and the next step is to define target-pivot criteria before selecting a new active target.
- `FJ67` completes the target-pivot criteria step: no new active target is selected yet, and `FJ68` must apply the matrix before any pivot.
- `FJ68` selects the bounded Artin subclass-gap packet `A-001` for `FJ69`; this is not a global all-Artin Farrell--Jones theorem claim.
- `FJ69` creates the Artin subclass-gap inventory and selects `A-002`, a Wu clique-reduction candidate filter, for `FJ70`; this is still not a global all-Artin theorem claim.
- `FJ70` records that the current repository has no Wu-filter candidate beyond already covered rows and placeholder gap rows; the Wu lane now requires a named reactivation payload or an Artin branch decision.
- The project has not yet chosen a concrete example of a ring with nonzero \(NK_n(R)\).
- All-degree statements now use the nonconnective \(K\)-theory convention source-checked in `FJ02`, while preserving the `FJ01` black-box normalization for simplified examples.

## Source discipline

External mathematical sources should be cited in APA style where practical and tracked with project source-status labels such as `found`, `to verify`, `partially read`, `verified`, `active reference`, `background only`, and `do not use`.

Internal dependencies may be cited by repository path, module number, result number, or ledger entry.

## Repository map

```text
README.md                         public overview
PROJECT_CHARTER.md                stable project charter
AGENTS.md                         persistent instructions for future Codex runs
SCOPE_LEDGER.md                   active scope ledger
NOTATION_LEDGER.md                notation ledger
BIBLIOGRAPHY.md                   structured bibliography
OPEN_QUESTIONS.md                 cumulative open questions
ESTABLISHED_RESULTS.md            results proved inside the project
modules/cycle_001/                first 20 modules
modules/cycle_002/                second module cycle, beginning with FJ21
modules/cycle_003/                third module cycle, beginning with FJ41
modules/cycle_004/                fourth module cycle, beginning with FJ61
modules/cycle_005/                fifth module cycle, beginning with FJ81
reflections/                      reflection reports after module cycles
ledgers/                          known cases, inheritance, sources, dependencies
ledgers/artin_subclass_gap_inventory.md Artin covered/gap/deferred inventory
ledgers/t001_residual.md          conservative residual ledger for T-001
ledgers/t001_kernel_recognition.md Brown/BNS kernel-recognition ledger for T-001
ledgers/t001_candidate_inventory.md candidate inventory for the T-001 hybrid attack packet
ledgers/cycle_004_handoff.md      cycle-004 handoff table and gate index
ledgers/payload_intake_protocol.md payload intake rules after the FJ82 pause
references/                       reading lists and source notes
diagrams/                         dependency maps
drafts/                           proof attempts, conjecture variants, abandoned paths
```

## Warning

This project is exploratory. It does **not** claim to solve the Farrell--Jones conjecture. Claims are to be labeled as definitions, examples, propositions, theorems, conjectures, heuristics, warnings, open problems, failed attempts, literature claims, or source-verified claims.

## Persistence rule

The repository is the durable archive. Chat-based exploration is temporary unless converted into repository artifacts.
