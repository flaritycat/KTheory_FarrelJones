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

- Active cycle: `cycle_002`.
- Completed cycle: `cycle_001`.
- Completed first-pass modules: `FJ01`, `FJ03`, `FJ04`, `FJ05`, `FJ06`, `FJ07`, `FJ08`, `FJ09`, `FJ10`, `FJ11`, `FJ12`, `FJ13`, `FJ14`, `FJ15`, `FJ16`, `FJ17`, `FJ18`, `FJ19`, `FJ20`, `FJ21`, `FJ22`, `FJ23`, `FJ24`, `FJ25`, `FJ26`, `FJ27`, `FJ28`, `FJ29`, `FJ30`, `FJ31`, `FJ32`, `FJ33`, `FJ34`, `FJ35`, and `FJ36`.
- Deferred first-milestone module: `FJ02`, the additive-category formulation.
- Completed cycle reflection: `reflections/cycle_001_reflection.md`.
- Selected first serious target: `T-001`, torsion-free one-relator residual gap analysis.
- Current procedural target: begin `FJ37`, post-\(G_{p,q}\) residual audit and next target selection.

## Current established results

- `ER-001`: the trivial group case of the simplified K-theoretic assembly map.
- `ER-002`: the source-verified existence and homotopy characterization of classifying spaces for project-style families of subgroups.
- `ER-003`: \(\mathcal{VCyc}(G)\) is a family of subgroups, with the infinite virtually cyclic dichotomy recorded as source-verified.
- `ER-004`: for \(G=\mathbb Z\), the simplified assembly map is the identity under the point model for \(E_{\mathcal{VCyc}}\mathbb Z\), with target \(K_n(R[t,t^{-1}])\).
- `ER-005`: the source-verified Bass--Heller--Swan decomposition of \(K_n(R[\mathbb Z])\), including the two \(NK_n(R)\)-summands.
- `ER-006`: conditional Whitehead-group vanishing from Farrell--Jones for torsion-free groups with regular coefficients.
- `ER-007`: conditional vanishing of \(\widetilde K_0(\mathbb Z[G])\), with the finiteness-obstruction interpretation for finitely presented groups.
- `ER-008`: conditional Borel consequence from low-dimensional K-theory vanishing and \(L^{\langle -\infty\rangle}\)-theory assembly.
- `ER-009`: first source-verified known classes: hyperbolic groups, finite-dimensional CAT(0)-groups, and virtually solvable groups, with version flags and first-pass proof-route maps for hyperbolic and CAT(0)-groups.
- `ER-010`: first source-verified inheritance-properties ledger, separating coefficient K-theory inheritance from survey-level full \(\mathcal{FJ}\) closure properties.
- `ER-011`: first source-verified Artin-group Farrell--Jones subclass ledger, including FC-type Artin groups, even FC-type Artin groups, RAAG-related semidirect products, Wu's even-Artin clique and join constructions, and Roushon's listed finite real, complex, and affine types, all only under their source hypotheses.
- `ER-012`: first source-verified one-relator-group Farrell--Jones status ledger, including conditional routes through hyperbolic, finite-dimensional CAT(0), virtually solvable, and hyperbolic-by-cyclic classes, while keeping the global torsion-free one-relator class unresolved inside the project.

See `ESTABLISHED_RESULTS.md` for exact statements, hypotheses, proof locations, and source status.

## Current cautions

- The repository has not proved or claimed the Farrell--Jones conjecture in full generality.
- `FJ06` identifies \(R[\mathbb Z]\cong R[t,t^{-1}]\) after choosing a generator, but deliberately does not use the Bass--Heller--Swan decomposition.
- `FJ07` imports Bass--Heller--Swan as a source-verified theorem, not as an internal proof.
- `FJ08` records a conditional Whitehead-group consequence; it does not claim \(\mathrm{Wh}(G)=0\) for groups with torsion.
- `FJ09` uses Lueck--Reich's survey for Wall finiteness obstruction; primary-source verification is deferred.
- `FJ10` imports \(L\)-theory only as an application dependency; it does not make Borel rigidity a K-theory-only result.
- `FJ11` is a first-pass known-cases ledger, not an exhaustive classification of all known Farrell--Jones groups.
- `FJ11` records "with coefficients in additive categories" as a source-level strength flag; the internal additive-category formulation remains deferred to `FJ02`.
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
- The project has not yet chosen a concrete example of a ring with nonzero \(NK_n(R)\).
- All-degree statements continue to use the nonconnective \(K\)-theory convention introduced in `FJ01`.

## Source discipline

External mathematical sources should be cited in APA style where practical and tracked with project source-status labels such as `found`, `to verify`, `partially read`, `verified`, `active reference`, `background only`, and `do not use`.

Internal dependencies may be cited by repository path, module number, result number, or ledger entry.

## Repository map

```text
README.md                         public overview
PROJECT_CHARTER.md                stable project charter
SCOPE_LEDGER.md                   active scope ledger
NOTATION_LEDGER.md                notation ledger
BIBLIOGRAPHY.md                   structured bibliography
OPEN_QUESTIONS.md                 cumulative open questions
ESTABLISHED_RESULTS.md            results proved inside the project
modules/cycle_001/                first 20 modules
modules/cycle_002/                second module cycle, beginning with FJ21
reflections/                      reflection reports after module cycles
ledgers/                          known cases, inheritance, sources, dependencies
ledgers/t001_residual.md          conservative residual ledger for T-001
ledgers/t001_kernel_recognition.md Brown/BNS kernel-recognition ledger for T-001
references/                       reading lists and source notes
diagrams/                         dependency maps
drafts/                           proof attempts, conjecture variants, abandoned paths
```

## Warning

This project is exploratory. It does **not** claim to solve the Farrell--Jones conjecture. Claims are to be labeled as definitions, examples, propositions, theorems, conjectures, heuristics, warnings, open problems, failed attempts, literature claims, or source-verified claims.

## Persistence rule

The repository is the durable archive. Chat-based exploration is temporary unless converted into repository artifacts.
