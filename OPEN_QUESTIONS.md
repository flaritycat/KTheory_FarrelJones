# Open Questions

## OQ-001. Which unresolved group class should become the first serious target?

### Status

Resolved for first-pass target selection.

### Context

The project needed a concrete target after foundational modules. Candidate
classes included Artin groups and torsion-free one-relator groups, but their
exact known/open status first had to be source-verified.

`FJ20` selected `T-001`: torsion-free one-relator residual gap analysis.

### Relevant modules

- FJ11
- FJ18
- FJ19
- FJ20

### Dependencies

Known-cases ledger and inheritance-properties ledger.

### Next action

First-pass resolved by `FJ20`. The cycle reflection is now recorded in
`reflections/cycle_001_reflection.md`; use `T-001` to guide cycle 002.

## OQ-002. Which source should serve as the main reference for the modern Farrell--Jones statement?

### Status

Open inside project.

### Context

Module `FJ01` uses a simplified ring-coefficient formulation. The stronger additive-category formulation must not be improvised.

### Relevant modules

- FJ01
- FJ02

### Dependencies

A reliable source for the additive-category formulation.

### Next action

Use module `FJ02` to verify the exact modern statement and record theorem/source status.

## OQ-003. Which model of nonconnective algebraic K-theory should be used?

### Status

Open inside project.

### Context

The simplified conjecture in `FJ01` is stated for all \(n\in\mathbb Z\). This requires a nonconnective algebraic \(K\)-theory model, but `FJ01` intentionally treats \(H_n^G(-;\mathbf K_R)\) as a black box.

### Relevant modules

- FJ01
- FJ02

### Dependencies

Source verification for the chosen model of \(\mathbf K_R\).

### Next action

Resolve during `FJ02` or a later notation/source module.

## OQ-004. What is the most economical first model of \(E_{\mathcal{VCyc}}G\) beyond trivial examples?

### Status

Partially resolved for first pass.

### Context

Module `FJ03` should develop classifying spaces for families with examples before advanced machinery appears and starts wearing a lab coat.

### Relevant modules

- FJ03
- FJ04
- FJ06

### Dependencies

Definitions of families and virtually cyclic groups.

### Next action

Use `FJ04` and `FJ06` to develop virtually cyclic groups and the infinite cyclic example before choosing more complicated models.

## OQ-005. Should weakly contractible and contractible fixed-point formulations be separated?

### Status

Open inside project.

### Context

Module `FJ03` uses the readable contractible/empty fixed-point definition for \(E_{\mathcal F}G\). Lueck's Theorem 1.9 states the homotopy characterization using weakly contractible fixed-point spaces for subgroups in the family, together with the isotropy condition.

### Relevant modules

- FJ03
- FJ15
- FJ16

### Dependencies

A later foundations module should decide how much model-category or \(G\)-CW technical detail the project needs.

### Next action

Defer until the project needs a sharper technical convention.

## OQ-006. Should Farrell--Jones 1995 be directly verified for the virtually cyclic dichotomy?

### Status

Open inside project.

### Context

Module `FJ04` uses Lueck--Reich's source-verified statement that an infinite virtually cyclic group maps with finite kernel either onto \(\mathbb Z\) or onto \(D_\infty\). Lueck--Reich cite Farrell--Jones 1995, Lemma 2.5, as the proof source.

### Relevant modules

- FJ04
- FJ07
- FJ11

### Dependencies

Access to Farrell--Jones, *The lower algebraic K-theory of virtually infinite cyclic groups*, K-Theory 9 (1995), 13--30.

### Next action

Before using the dichotomy in a proof-sensitive way beyond first-pass structure, directly check the original Farrell--Jones 1995 lemma or another primary source with equivalent hypotheses.

## OQ-007. Which source should be used for Bass--Heller--Swan and Nil-terms?

### Status

Resolved for first pass; original-source verification remains optional.

### Context

Module `FJ06` identifies the target for \(G=\mathbb Z\) as \(K_n(R[t,t^{-1}])\), but deliberately does not decompose that group. Module `FJ07` introduces the Bass--Heller--Swan decomposition and Nil-terms.

### Relevant modules

- FJ06
- FJ07

### Dependencies

Weibel's K-book has been selected as the active first-pass theorem source, with Lueck--Reich used for the Farrell--Jones interpretation. The original Bass--Heller--Swan paper has been bibliographically located but not used as the theorem source.

### Next action

Use Weibel (2013) for first-pass theorem statements. Directly check Bass--Heller--Swan (1964) only if the project later needs original-source historical precision.

## OQ-008. Which explicit nonzero Nil example should the project use?

### Status

Open inside project.

### Context

Module `FJ07` records the structural role of Nil-terms, but it does not prove that any particular \(NK_n(R)\) is nonzero.

### Relevant modules

- FJ07
- FJ08
- FJ11

### Dependencies

A reliable source for explicit nonzero \(NK\)-groups over a concrete ring.

### Next action

Defer until a later module needs a concrete obstruction example rather than the structural Bass--Heller--Swan decomposition.

## OQ-009. Should the original Bass--Heller--Swan paper be checked directly?

### Status

Open, low urgency.

### Context

`FJ07` uses Weibel's monograph as the active theorem source. The original paper is historically important but was not needed for the first-pass theorem ledger.

### Relevant modules

- FJ07
- FJ11

### Dependencies

Bass, Heller, and Swan, *The Whitehead group of a polynomial extension*, Publications Mathematiques de l'IHES 22 (1964), 61--79.

### Next action

Check the original paper only if the project later needs historical attribution beyond the APA bibliography entry.

## OQ-010. Which source should be used for geometric Whitehead torsion?

### Status

Open inside project.

### Context

Module `FJ08` uses the algebraic \(K\)-theory cokernel definition of the Whitehead group and records a Farrell--Jones consequence. It does not develop Whitehead torsion, the \(s\)-cobordism theorem, or the geometric applications of \(\mathrm{Wh}(G)\).

### Relevant modules

- FJ08
- FJ10

### Dependencies

A reliable source for Whitehead torsion and the \(s\)-cobordism theorem, preferably a standard monograph or expert survey.

### Next action

Resolve only if `FJ10` or a later topology-facing module needs geometric consequences.

## OQ-011. Should Wall's finiteness obstruction be verified from a primary source?

### Status

Open inside project.

### Context

Module `FJ09` uses Lueck--Reich's survey statement of Wall's finiteness obstruction theorem and its consequence for \(\widetilde K_0(\mathbb Z[G])\). This is enough for first-pass orientation, but a primary or monograph source may be needed if the project later uses the theorem proof-sensitively.

### Relevant modules

- FJ09
- FJ10

### Dependencies

A primary or standard monograph source for Wall's finiteness obstruction theorem.

### Next action

Defer until a topology-facing module needs proof-level detail beyond the Lueck--Reich survey.

## OQ-012. Which source should be used for surgery theory and structure sets?

### Status

Open inside project.

### Context

Module `FJ10` uses Lueck--Reich's theorem map from low-dimensional K-theory vanishing and \(L^{\langle -\infty\rangle}\)-theory assembly to the Borel conjecture. It does not verify the surgery exact sequence or the topological structure set from a primary source.

### Relevant modules

- FJ10

### Dependencies

A standard surgery-theory monograph or expert survey covering topological structure sets and the surgery exact sequence.

### Next action

Resolve only if the project later develops Borel rigidity beyond a source-verified theorem map.

## OQ-013. Should negative K-group vanishing receive its own module?

### Status

Open inside project.

### Context

The Borel consequence in `FJ10` requires \(K_{-i}(\mathbb Z[G])=0\) for \(i\geq 1\). Earlier modules recorded Whitehead and projective class group consequences, but did not isolate negative K-group vanishing as its own result.

### Relevant modules

- FJ08
- FJ09
- FJ10

### Dependencies

Lueck--Reich's low-dimensional K-theory consequence and a source for negative algebraic \(K\)-groups.

### Next action

Consider a later correction or supplemental module if negative K-groups become active in subsequent arguments.

## OQ-014. Which additional known classes should be verified next?

### Status

Open inside project.

### Context

Module `FJ11` records a first-pass known-cases table for hyperbolic
groups, finite-dimensional CAT(0)-groups, and virtually solvable groups.
Many important known classes remain outside the verified ledger.

### Relevant modules

- FJ11
- FJ12
- FJ13
- FJ14
- FJ18
- FJ19

### Dependencies

Primary papers, expert surveys, or monographs for additional known
Farrell--Jones cases, including possible rows for 3-manifold groups,
mapping class groups, lattices in Lie groups, relatively hyperbolic
groups, S-arithmetic groups, Artin-group subclasses, or one-relator
group subclasses.

### Next action

`FJ20` selected the one-relator residual gap analysis as the first serious
target. The next known-case expansion should support that target unless the
cycle reflection identifies a more urgent foundational blocker.

## OQ-015. Which inheritance rows need primary-source tracing?

### Status

Open inside project.

### Context

Module `FJ12` records several closure properties as survey-level
statements about Lueck's full class \(\mathcal{FJ}\). That is enough
for orientation, but proof-sensitive reductions for Artin groups,
one-relator groups, graph products, or extension constructions may
require tracing the survey rows to primary papers or detailed monograph
proofs.

### Relevant modules

- FJ12
- FJ13
- FJ14
- FJ18
- FJ19
- FJ20

### Dependencies

`ledgers/inheritance_properties.md`, Lueck's survey, and the primary
sources cited there for the relevant closure property.

### Next action

Before using a full \(\mathcal{FJ}\) closure row as a proof input,
verify the cited proof source and record the exact hypotheses in the
inheritance ledger.

## OQ-016. Which BLR proof dependencies need direct checking?

### Status

Open inside project.

### Context

Module `FJ13` uses Bartels--Lueck--Reich's hyperbolic-groups paper as
the active source for the proof skeleton. That paper delegates key
hyperbolic input to other sources, including the Rips-complex
background, boundary \(Z\)-set input, Mineyev-style flow technology,
and the equivariant wide-cover theorem.

### Relevant modules

- FJ13
- FJ15
- FJ16
- FJ17

### Dependencies

Bartels--Lueck--Reich (2008), especially the Main Theorem, Theorem
"Axiomatic Formulation", Section 2, and the cited source
`Equivariant covers for hyperbolic groups`.

### Next action

`FJ17` checked the first-pass transfer architecture in
Bartels--Lueck--Reich, including the transfer theorem's right-inverse
role. Before proof-sensitive use, check the detailed Waldhausen-category
transfer proof, stability theorem, and cover-contraction step.

## OQ-017. Which CAT(0) proof dependencies need direct checking?

### Status

Open inside project.

### Context

Module `FJ14` uses Wegner's CAT(0)-groups paper as the active source
for the K-theoretic proof skeleton. The proof route depends on strong
transfer reducibility, strong homotopy actions, controlled domination of
large CAT(0) balls, and the Bartels--Lueck geodesic-flow cover
technology.

### Relevant modules

- FJ14
- FJ15
- FJ16
- FJ17

### Dependencies

Wegner (2012), especially the main theorem, the strong-transfer-
reducibility theorem, and the CAT(0)-group verification; Bartels--Lueck
(2012), especially the flow-space cover results used by Wegner.

### Next action

`FJ17` checked Wegner's strong homotopy action, strong transfer
reducibility, proof-outline diagram, transfer functor, and projection
identity at first-pass level. Before proof-sensitive use, verify the
controlled \(N\)-domination, strong-transfer-cover construction, and
the detailed CAT(0) flow-space cover inputs.

## OQ-018. Which obstruction-category source should become canonical?

### Status

Open inside project.

### Context

Module `FJ15` uses Wegner's obstruction-category review as the active
first-pass source because it directly supports the CAT(0) proof
skeleton in `FJ14`. Wegner cites Bartels--Lueck--Reich for the
obstruction-category reduction, and the source notation differs across
the proof papers.

### Relevant modules

- FJ13
- FJ15
- FJ17
- FJ02

### Dependencies

Wegner (2012), Bartels--Lueck--Reich (2008), and whichever primary
controlled-algebra source is selected for continuous-control
conditions.

### Next action

`FJ17` used Wegner and Bartels--Lueck--Reich source notation for
orientation only. Before proof-sensitive use, choose a canonical
obstruction-category source and record the exact notation, hypotheses,
Karoubi filtrations, and comparison with Wegner's notation.

## OQ-019. Which Mineyev flow-space results need direct checking?

### Status

Open inside project.

### Context

Module `FJ16` records the hyperbolic flow-space route through
Bartels--Lueck--Reich. That source uses Mineyev's flow space and flow
estimates for hyperbolic complexes. FJ16 did not directly verify
Mineyev's construction.

### Relevant modules

- FJ13
- FJ16
- FJ17

### Dependencies

Mineyev (2005), especially the flow-space construction and estimates
cited by Bartels--Lueck--Reich.

### Next action

Before using the hyperbolic flow estimates proof-sensitively, identify
the exact Mineyev statements imported by Bartels--Lueck--Reich and
record their hypotheses in the bibliography and source-status ledger.

## OQ-020. Which transfer-category model should become canonical?

### Status

Open inside project.

### Context

Module `FJ17` records transfer maps using Wegner's notation and the
Bartels--Lueck--Reich hyperbolic transfer architecture. The checked
sources use Waldhausen categories of homotopy finitely dominated chain
complexes, Karoubi quotient categories, diagonal maps, projection maps,
and transfer functors. The project has not yet chosen a canonical
internal model for these categories.

### Relevant modules

- FJ13
- FJ15
- FJ17
- FJ02

### Dependencies

Wegner (2012), Bartels--Lueck--Reich (2008), Bartels--Reich (2005), and
the canonical obstruction-category source still to be chosen in
OQ-018.

### Next action

Before writing proof-level transfer arguments, choose whether the
project follows Wegner's exposition, Bartels--Lueck--Reich's original
transfer construction, or a later consolidated source. Record the exact
category notation and hypotheses in the notation and source-status
ledgers.

## OQ-021. Which Artin-group subclasses remain outside the FJ18 verified ledger?

### Status

Open inside project.

### Context

Module `FJ18` records source-verified Farrell--Jones rows for several
Artin-group subclasses, including FC-type Artin groups, even FC-type
Artin groups, right-angled Artin semidirect products, Wu's even-Artin
clique and join constructions, and Roushon's listed finite real,
complex, and affine types.

This does not settle all Artin groups inside the project. The remaining
task is to identify which commonly discussed Artin subclasses still
fall outside those verified rows.

### Relevant modules

- FJ18
- FJ20+

### Dependencies

`FJ18`, `ledgers/known_classes.md`, and future Artin literature checks.

### Next action

`FJ20` deferred a second Artin-status module. Return to this only after
`T-001` has either produced a residual one-relator target or been abandoned.

## OQ-022. Which source should reconcile FJCw, FICwF, and the project's simplified K-theory formulation?

### Status

Open inside project.

### Context

`FJ18` records source-level formulations such as `FJCw` and `FICwF`.
These are stronger or differently packaged than the simplified
ring-coefficient K-theory statement in `FJ01`, and they involve
coefficients, finite wreath products, and in Roushon's notation also
K-, L-, and A-theory.

### Relevant modules

- FJ01
- FJ02
- FJ12
- FJ18

### Dependencies

A canonical source for the modern additive-category formulation and a
careful comparison of source notation.

### Next action

Resolve during `FJ02` or a dedicated source-conventions module before
using `FJCw` or `FICwF` as proof-level internal hypotheses.

## OQ-023. Can Wu's clique-reduction route isolate a tractable Artin target not already covered by the verified rows?

### Status

Open inside project.

### Context

Wu's source gives a reduction for even Artin groups from clique
subgroups and records a criterion implying FJCw for a structured family
of even Artin groups. This suggests a possible target-selection route:
look for a remaining Artin subclass where the clique subgroups are
tractable, but the full class is not already covered by `FJ18`.

### Relevant modules

- FJ18
- FJ20+

### Dependencies

Wu (2022), the inheritance ledger, and a future Artin subclass gap
analysis.

### Next action

Deferred by `FJ20`. Revisit after the project reconciles `FJCw`, `FICwF`,
and the internal Farrell--Jones formulation, or after `T-001` is no longer
the active target.

## OQ-024. Is there a global K-theoretic Farrell--Jones theorem for all torsion-free one-relator groups in a weaker formulation?

### Status

Open inside project.

### Context

`FJ19` verified that Lueck (2025) lists torsion-free one-relator groups
as open in general for the Full Farrell--Jones Conjecture. This does
not by itself rule out a weaker K-theoretic theorem in the literature,
but no such global theorem has been recorded in the repository.

### Relevant modules

- FJ19
- FJ20+

### Dependencies

One-relator literature and modern Farrell--Jones formulation sources.

### Next action

Promoted by `FJ20` as part of `T-001`, but not as the first proof attempt.
First build the residual subclass map and then decide whether a global weaker
K-theory theorem is plausible or source-supported.

## OQ-025. Which one-relator structure theorem should become the canonical reduction tool?

### Status

Resolved for first-pass source selection.

### Context

`FJ19` records local indicability of torsion-free one-relator groups, but
local indicability alone is not a Farrell--Jones proof route. Future work
needs a source-verified structural framework, such as Magnus hierarchy,
HNN splittings, Brodskii--Howie local indicability, or a modern hierarchy
source, before attempting reductions.

### Relevant modules

- FJ19
- FJ20+

### Dependencies

Howie (2000), one-relator hierarchy literature, and the inheritance
ledger.

### Next action

First-pass resolved by `FJ21` and refined by `FJ22`. Use Linton's
`One-relator hierarchies` as the primary modern hierarchy source and adopt
Linton's finite one-relator complex hierarchy theorem as the first-pass
structure theorem for `T-001`.

## OQ-026. Which torsion-free one-relator groups survive after subtracting known routes?

### Status

Open inside project.

### Context

`FJ19` records verified routes through hyperbolic groups,
finite-dimensional CAT(0)-groups, virtually solvable groups, and
hyperbolic-by-cyclic groups. The target-selection question is to
identify examples or subclasses not already covered by these routes.

### Relevant modules

- FJ19
- FJ20
- FJ21+

### Dependencies

`ledgers/known_classes.md`, `ledgers/open_group_classes.md`, and future
one-relator subclass checks.

### Next action

Continue subtracting known Farrell--Jones routes after the `FJ23`
hyperbolic, `FJ24` CAT(0), `FJ25` virtually solvable, and `FJ26`
hyperbolic-by-cyclic/free-by-cyclic subtractions, beginning with
source-verified inheritance routes in `FJ27`.

## OQ-027. Which exact hierarchy theorem should FJ22 adopt?

### Status

Resolved for first-pass hierarchy vocabulary.

### Context

`FJ21` selected Linton's `One-relator hierarchies` as the primary modern
hierarchy source for `T-001`, but it did not choose a proof-level theorem
statement. `FJ22` adopts Linton's finite one-relator complex hierarchy theorem:
every finite one-relator complex admits a finite one-relator tower whose HNN
splittings identify Magnus subgraphs and whose terminal group is finite cyclic.

### Relevant modules

- FJ21
- FJ22

### Dependencies

Linton's `One-relator hierarchies`, Linton's `Hyperbolic one-relator groups`,
and the classical Magnus--Moldavanskii background sources if Linton's statement
requires classical comparison.

### Next action

First-pass resolved by `FJ22`. Use the theorem map in `FJ22` for `FJ23`,
hyperbolic-route subtraction, and return to Linton's exact source definitions
before computing \(\mathbb Z\)-stable numbers or translating the complex-level
language into presentation-only arguments.

## OQ-028. Which classical Magnus hierarchy source must be checked for proof-sensitive use?

### Status

Open inside project.

### Context

`FJ21` records Lyndon--Schupp and Magnus--Karrass--Solitar as classical
one-relator sources, but neither has been checked directly inside the project.
If later modules need the classical Freiheitssatz or Magnus--Moldavanskii
hierarchy independent of Linton's formulation, the project must choose and
verify the exact classical source.

### Relevant modules

- FJ21
- FJ22+

### Dependencies

Lyndon--Schupp, Magnus--Karrass--Solitar, and possibly Magnus's original
Freiheitssatz paper.

### Next action

Defer for now. `FJ22` is enough for the next hierarchy-vocabulary step, but a
classical source must still be verified before the project replaces Linton's
complex-level framework with a classical presentation-only workflow.

## OQ-029. Which part of T-001 is already removed by the hyperbolic route?

### Status

Resolved for first-pass hyperbolic-route subtraction.

### Context

`FJ22` records Linton's hierarchy vocabulary and main equivalence theorem, and
`ER-009` already records hyperbolic groups as a known Farrell--Jones class.
`FJ23` identifies the conservative subtraction rule: remove a torsion-free
one-relator group from the active residual target only after the project has a
source-verified bridge to word-hyperbolicity.

### Relevant modules

- FJ13
- FJ19
- FJ22
- FJ23

### Dependencies

`ER-009`, `ER-012`, Linton's hierarchy vocabulary, and any source-verified
bridge from one-relator hypotheses to hyperbolicity.

### Next action

First-pass resolved by `FJ23`. `FJ24`, `FJ25`, `FJ26`, and `FJ27` have
completed the next CAT(0), virtually solvable,
hyperbolic-by-cyclic/free-by-cyclic, and inheritance route subtractions;
`FJ28` has assembled the first-pass residual ledger, and `FJ29` has selected
`RB-004` as the next attack surface. `FJ30` has verified Brown's limited
kernel-recognition route, `FJ31` has completed a calibration Brown test
case, `FJ32` has selected \(G_{2,3}\), `FJ33` has completed the worked
Brown test, and `FJ34` has completed the nearby Brown family boundary.
`FJ39` and `FJ40` have completed the normal-subgroup bridge and finitely presented-kernel selection pass for `RB-004`. `reflections/cycle_002_reflection.md` is complete; continue with `FJ46`, source-convention decision for `RB-005`.

## OQ-030. Which part of T-001 is removed by the CAT(0) route?

### Status

Resolved for first-pass CAT(0)-route subtraction.

### Context

`ER-009` records finite-dimensional CAT(0)-groups as a known Farrell--Jones
class. `FJ23` deliberately did not use virtual specialness as a hyperbolic
route by itself. `FJ24` records the conservative CAT(0)-route subtraction:
subtract groups after a source-verified finite-dimensional CAT(0) action, and
subtract compact finite-dimensional special cube complex groups through the
Haglund--Wise cube-complex bridge. Merely virtual-special statements still
require finite-index handling before proof-sensitive use.

### Relevant modules

- FJ14
- FJ19
- FJ22
- FJ23
- FJ24

### Dependencies

`ER-009`, Wegner's CAT(0)-group theorem as recorded in `FJ14`, and any
source-verified bridge from one-relator or virtual-special hypotheses to a
proper cocompact finite-dimensional CAT(0) action.

### Next action

First-pass resolved by `FJ24`. `FJ25`, `FJ26`, and `FJ27` have completed the
virtually solvable, hyperbolic-by-cyclic/free-by-cyclic, and inheritance route
subtractions; `FJ28` has assembled the first-pass residual ledger, and `FJ29`
has selected `RB-004` as the next attack surface. `FJ30` has verified
Brown's limited kernel-recognition route, `FJ31` has completed a calibration
Brown test case, `FJ32` has selected \(G_{2,3}\), `FJ33` has completed
the worked Brown test, and `FJ34` has completed the nearby Brown family
boundary. `FJ39` and `FJ40` have completed the normal-subgroup bridge and finitely presented-kernel selection pass for `RB-004`.
`reflections/cycle_002_reflection.md` is complete; continue with `FJ46`, source-convention decision for `RB-005`.

## OQ-031. Which part of T-001 is removed by the virtually solvable route?

### Status

Resolved for first-pass virtually solvable-route subtraction.

### Context

`ER-009` records virtually solvable groups as a known Farrell--Jones class.
`FJ19` includes virtually solvable one-relator groups as a conditional positive
route. `FJ25` records the conservative subtraction rule: subtract torsion-free
one-relator groups only after a source-verified or internally proved bridge to
virtual solvability.

`FJ25` also records that local indicability, nontrivial abelianization, and HNN
hierarchy structure are not virtual-solvability proofs by themselves.

### Relevant modules

- FJ11
- FJ19
- FJ23
- FJ24
- FJ25

### Dependencies

`ER-009`, Wegner's virtually solvable theorem as recorded in `FJ11`, and any
later source-verified classification or criterion for the virtually solvable
one-relator cases if the project needs enumeration beyond conditional route
bookkeeping.

### Next action

First-pass resolved by `FJ25`. `FJ26` and `FJ27` have completed the
hyperbolic-by-cyclic/free-by-cyclic and inheritance route subtractions.
`FJ28` has assembled the first-pass residual ledger, and `FJ29` has selected
`RB-004` as the next attack surface. `FJ30` has verified Brown's limited
kernel-recognition route, `FJ31` has completed a calibration Brown test
case, `FJ32` has selected \(G_{2,3}\), `FJ33` has completed the worked
Brown test, and `FJ34` has completed the nearby Brown family boundary.
`FJ39` and `FJ40` have completed the normal-subgroup bridge and finitely presented-kernel selection pass for `RB-004`. `reflections/cycle_002_reflection.md` is complete; continue with `FJ46`, source-convention decision for `RB-005`.

## OQ-032. Which finite-index source should support virtually compact special route use?

### Status

Partially resolved by `FJ45`; still open for coefficient K-theory or direct
CAT(0) finite-extension use.

### Context

`FJ24` records compact finite-dimensional special cube complex groups as
CAT(0)-route bridge cases. It does not automatically subtract every virtually
compact special group as a pure CAT(0) route, because the project still needs a
source-verified finite-index-overgroup bridge for the relevant Farrell--Jones
formulation or a theorem placing the whole group in the finite-dimensional
CAT(0)-group class.

`FJ45` records that the currently usable finite-index overgroup bridge is
only the full \(\mathcal{FJ}\) survey-level row. This supports full
\(\mathcal{FJ}\)-level use when the finite-index subgroup is already recorded
in full \(\mathcal{FJ}\), but it does not yet support coefficient K-theory or
direct CAT(0)-route promotion for merely virtually compact special cases.

### Relevant modules

- FJ12
- FJ14
- FJ22
- FJ24
- FJ45

### Dependencies

Finite-index inheritance sources, CAT(0)-group finite-extension sources, or a
source-level convention for virtually compact special groups strong enough for
the project's known-case ledger.

### Next action

Use only the full \(\mathcal{FJ}\) finite-index bridge recorded by `FJ45`.
Continue the coefficient/CAT(0) version issue through `OQ-067` and `FJ46`.

## OQ-033. Which one-relator groups are compact special beyond the hyperbolic route?

### Status

Open inside project.

### Context

`FJ24` records compact finite-dimensional special cube complex groups as
CAT(0)-route bridge cases. Linton's virtual-special consequences recorded in
`FJ22` occur under hypotheses that also give hyperbolicity and were therefore
already eligible for `FJ23`. A later module may need examples or subclasses
that are compact special or CAT(0) without already being removed by the
hyperbolic route.

### Relevant modules

- FJ22
- FJ23
- FJ24

### Dependencies

One-relator cubulation and special-cube-complex sources beyond the first-pass
Haglund--Wise bridge.

### Next action

Defer until after the route-subtraction pass reaches surviving examples.

## OQ-034. Which source should classify or recognize virtually solvable one-relator cases?

### Status

Open inside project.

### Context

`FJ25` supplies a conditional subtraction rule for virtually solvable
one-relator groups, but it does not classify them. If the project later needs
an enumerated list of virtually solvable one-relator examples, it should first
choose a source-verified classification or recognition criterion.

### Relevant modules

- FJ11
- FJ19
- FJ25

### Dependencies

Wegner's virtually solvable theorem as recorded in `FJ11`, plus a future
one-relator-specific source for virtual-solvability recognition if enumeration
becomes necessary.

### Next action

Defer unless the residual analysis needs more than the conditional `FJ25`
route table.

## OQ-035. Which part of T-001 is removed by the hyperbolic-by-cyclic/free-by-cyclic route?

### Status

Resolved for first-pass hyperbolic-by-cyclic/free-by-cyclic route subtraction.

### Context

`FJ19` records the Bestvina--Fujiwara--Wigglesworth theorem as a positive route
for hyperbolic-by-cyclic groups, including finite-rank free-by-cyclic groups
under the source hypotheses. `FJ26` records the conservative subtraction rule:
subtract torsion-free one-relator groups only after a source-verified bridge
to \(H\rtimes_\Phi\mathbb Z\) with \(H\) virtually torsion-free hyperbolic, or
to a finite-rank free-by-cyclic group.

`FJ26` also records that epimorphisms to \(\mathbb Z\), HNN splittings, and
one-relator hierarchy data are not mapping-torus proofs by themselves.

### Relevant modules

- FJ19
- FJ23
- FJ24
- FJ25
- FJ26

### Dependencies

Bestvina--Fujiwara--Wigglesworth (2023), the mapping-torus notation from
`FJ19`, and any later one-relator splitting or kernel-finiteness source used
to identify a group as hyperbolic-by-cyclic or finite-rank free-by-cyclic.

### Next action

First-pass resolved by `FJ26`. `FJ27` has completed the source-verified
inheritance-route subtraction. `FJ28` has assembled the first-pass residual
ledger, `FJ29` has selected `RB-004` as the next attack surface, and `FJ30`
has verified Brown's limited two-generator kernel-recognition route. `FJ31`
has completed a calibration Brown test case, `FJ32` has selected
\(G_{2,3}\), `FJ33` has completed the worked Brown test, and `FJ34` has
completed the nearby Brown family boundary. `FJ39` and `FJ40` have completed the normal-subgroup bridge and finitely presented-kernel selection pass for `RB-004`.
`reflections/cycle_002_reflection.md` is complete; continue with `FJ46`, source-convention decision for `RB-005`.

## OQ-036. Which source should recognize finite-rank free kernels over Z?

### Status

Resolved for first-pass Brown source selection and verification.

### Context

`FJ26` records that a verified exact sequence
\[
1\to F_n\to G\to \mathbb Z\to 1
\]
with \(n<\infty\) gives a finite-rank free-by-cyclic bridge. It does not prove
that any particular one-relator epimorphism has finitely generated free
kernel. `FJ29` selects Brown's BNS-invariant paper as the first source to
verify for this recognition problem, while keeping it out of theorem-use
status until `FJ30`. `FJ30` verifies Brown's Proposition 3.1, Corollary 3.2,
and Theorems 4.2--4.4 as a limited recognition route for selected
two-generator one-relator cases.

### Relevant modules

- FJ21
- FJ26
- FJ29
- FJ30

### Dependencies

Brown (1987), the original Bieri--Neumann--Strebel paper if broader direct
BNS use becomes necessary, and any later source for cases outside Brown's
two-generator criterion.

### Next action

First-pass resolved by `FJ30`. `FJ31` has completed a calibration Brown test
case, `FJ32` has selected \(G_{2,3}\), `FJ33` has completed the worked
Brown test, and `FJ34` has completed the nearby Brown family boundary.
`FJ39` and `FJ40` have completed the normal-subgroup bridge and finitely presented-kernel selection pass for `RB-004`. `reflections/cycle_002_reflection.md` is complete; continue with `FJ46`, source-convention decision for `RB-005`.

## OQ-037. Which inheritance routes remove additional T-001 cases?

### Status

Resolved for first-pass source-verified inheritance-route subtraction.

### Context

`FJ12` records inheritance properties with version flags, including
coefficient K-theory rows, K-theory directed-colimit rows, and survey-level
full \(\mathcal{FJ}\) rows. `FJ27` records the conservative subtraction rule:
subtract a remaining `T-001` case by inheritance only after an exact
inheritance bridge is recorded and the source version flag is preserved.

### Relevant modules

- FJ12
- FJ19
- FJ23
- FJ24
- FJ25
- FJ26
- FJ27

### Dependencies

`ER-010`, `ledgers/inheritance_properties.md`, Bartels--Reich coefficient
inheritance, Bartels--Echterhoff--Lueck directed-colimit inheritance, and
Lueck's survey-level full \(\mathcal{FJ}\) inheritance table.

### Next action

First-pass resolved by `FJ27`. `FJ28` has assembled the residual ledger after
named and inheritance route subtractions, `FJ29` has selected `RB-004` as the
next attack surface, and `FJ30` has verified Brown's limited
kernel-recognition route. `FJ31` has completed a calibration Brown test case,
`FJ32` has selected \(G_{2,3}\), `FJ33` has completed the worked Brown
test, `FJ34` has completed the nearby Brown family boundary, and `FJ36` has
removed the \(G_{p,q}\)-family through the finite-rank free-by-cyclic route.
`FJ39` and `FJ40` have completed the normal-subgroup bridge and finitely presented-kernel selection pass for `RB-004`. `reflections/cycle_002_reflection.md` is complete; continue with `FJ46`, source-convention decision for `RB-005`.

## OQ-038. What remains in T-001 after the route-subtraction pass?

### Status

Resolved for first-pass residual-ledger assembly.

### Context

`FJ23`--`FJ27` record conservative subtraction rules for the named positive
routes and version-aware inheritance routes. `FJ28` creates
`ledgers/t001_residual.md`, recording removed routes, active residual buckets,
and candidate attack surfaces.

This residual should not be described as a class of counterexamples or
non-Farrell--Jones groups. It is only the set of cases not yet removed by the
repository's current source-verified route data.

### Relevant modules

- FJ19
- FJ20
- FJ21
- FJ22
- FJ23
- FJ24
- FJ25
- FJ26
- FJ27
- FJ28

### Dependencies

The route-subtraction tables from `FJ23`--`FJ27`, the open source-recognition
questions generated by those modules, the `T-001` target-selection criteria
from `FJ20`, and `ledgers/t001_residual.md`.

### Next action

First-pass resolved by `FJ28`. `FJ29` has selected `RB-004` as the concrete
residual attack surface, and `FJ30` has verified Brown's limited
kernel-recognition route. `FJ31` has completed a calibration Brown test case,
`FJ32` has selected \(G_{2,3}\), `FJ33` has completed the worked Brown
test, `FJ34` has completed the nearby Brown family boundary, and `FJ36` has
removed the \(G_{p,q}\)-family through the finite-rank free-by-cyclic route.
`FJ39` and `FJ40` have completed the normal-subgroup bridge and finitely presented-kernel selection pass for `RB-004`. `reflections/cycle_002_reflection.md` is complete; continue with `FJ46`, source-convention decision for `RB-005`.

## OQ-039. Which concrete surviving one-relator subclasses should be attacked next?

### Status

Resolved for first-pass attack-surface selection.

### Context

After the residual ledger is assembled, the project should choose a concrete
attack surface rather than continuing to list broad known routes. `FJ29`
selects `RB-004`, finite-rank free-kernel recognition over \(\mathbb Z\), as
the next attack surface. Candidate subclasses must be selected from
repository-recorded residual data, not from unverified memory.

### Relevant modules

- FJ20
- FJ28
- FJ29

### Dependencies

The `FJ28` residual ledger, the source-status ledgers, and the `FJ26`
finite-rank free-by-cyclic route.

### Next action

First-pass resolved by `FJ29`. `FJ30` has verified Brown's limited
kernel-recognition route. `FJ31` has completed a calibration Brown test case,
`FJ32` has selected \(G_{2,3}\), `FJ33` has completed the worked Brown
test, `FJ34` has completed the nearby Brown family boundary, and `FJ36` has
removed the \(G_{p,q}\)-family through the finite-rank free-by-cyclic route.
`FJ39` and `FJ40` have completed the normal-subgroup bridge and finitely presented-kernel selection pass for `RB-004`. `reflections/cycle_002_reflection.md` is complete; continue with `FJ46`, source-convention decision for `RB-005`.

## OQ-040. Which source should be checked first for the selected residual bucket?

### Status

Resolved for first-pass source selection.

### Context

`FJ28` lists candidate residual attack surfaces, but each candidate has a
different source-risk profile. After `FJ29` selects a bucket, the project
should choose the first source to verify before making theorem-level claims.
`FJ29` selects Brown (1987) as the first verification source for `RB-004`,
without upgrading it to theorem-use status.

### Relevant modules

- FJ21
- FJ24
- FJ26
- FJ28
- FJ29

### Dependencies

`ledgers/t001_residual.md`, `ledgers/source_status.md`, and the candidate
source queues already recorded for Brown, one-relator cubulation/specialness,
virtually solvable recognition, and hierarchy-to-route extraction.

### Next action

First-pass resolved by `FJ29`. `FJ30` has checked Brown (1987) for exact
statements, hypotheses, and conclusions. `FJ31` has completed a calibration
Brown test case, `FJ32` has selected \(G_{2,3}\), `FJ33` has completed
the worked Brown test, and `FJ34` has completed the nearby Brown family
boundary. `FJ39` and `FJ40` have completed the normal-subgroup bridge and finitely presented-kernel selection pass for `RB-004`.
`reflections/cycle_002_reflection.md` is complete; continue with `FJ46`, source-convention decision for `RB-005`.

## OQ-041. What exact Brown/BNS theorem recognizes finite-rank kernels?

### Status

Resolved for first-pass Brown source verification.

### Context

`FJ29` selects `RB-004` and Brown (1987) as the first source to verify. The
project still needs the exact theorem statement, hypotheses, and conclusion:
whether Brown gives finite generation, freeness, finite rank, a BNS-invariant
criterion, or only a weaker/conditional result. `FJ30` records the answer:
Brown gives a finite-generation criterion via Proposition 3.1 and Corollary
3.2, plus computable two-generator one-relator tests in Theorems 4.2--4.4.
It does not give a global positive theorem for all one-relator epimorphisms.

### Relevant modules

- FJ21
- FJ26
- FJ29
- FJ30

### Dependencies

Brown (1987), the `FJ26` finite-rank free-by-cyclic bridge, and the
project-facing route criterion in `ledgers/t001_kernel_recognition.md`.

### Next action

First-pass resolved by `FJ30`. `FJ31` has completed a calibration Brown test
case, `FJ32` has selected \(G_{2,3}\), `FJ33` has completed the worked
Brown test, and `FJ34` has completed the nearby Brown family boundary.
`FJ39` and `FJ40` have completed the normal-subgroup bridge and finitely presented-kernel selection pass for `RB-004`. `reflections/cycle_002_reflection.md` is complete; continue with `FJ46`, source-convention decision for `RB-005`.

## OQ-042. Which first Brown criterion test case should be used?

### Status

Resolved for first-pass calibration.

### Context

`FJ30` verifies Brown's two-generator one-relator criterion as a usable
kernel-recognition tool. `FJ31` chooses the commutator presentation
\[
G=\langle x,y\mid xyx^{-1}y^{-1}\rangle
\]
with \(\chi(x)=1\) and \(\chi(y)=0\) as the first calibration example.
Brown's zero-on-one-generator maximum-count test passes for both
\([\chi]\) and \([-\chi]\), and the module identifies
\(\ker(\chi)\cong F_1\).

This resolves the first-test-case question only at the calibration level:
the group is \(\mathbb Z^2\), hence already covered by the virtually
solvable route.

### Relevant modules

- FJ26
- FJ29
- FJ30
- FJ31
- FJ32

### Dependencies

Brown (1987), `ledgers/t001_kernel_recognition.md`, and the `FJ26`
finite-rank free-by-cyclic route.

### Next action

First-pass resolved by `FJ31`. `FJ32` has selected \(G_{2,3}\), `FJ33`
has completed the worked Brown test, and `FJ34` has completed the nearby
Brown family boundary. `FJ39` and `FJ40` have completed the normal-subgroup bridge and finitely presented-kernel selection pass for `RB-004`.
`reflections/cycle_002_reflection.md` is complete; continue with `FJ46`, source-convention decision for `RB-005`.

## OQ-043. Should the original BNS normal-subgroup theorem be checked directly?

### Status

Resolved for first-pass theorem use by `FJ41`.

### Context

`FJ30` uses Brown's source for the infinite-cyclic quotient criterion and
records the original Bieri--Neumann--Strebel paper bibliographically. Before
the project uses the general normal-subgroup theorem beyond Brown's
restatement, the original BNS source should be checked directly.

`FJ41` checks Bieri--Neumann--Strebel (1987), Theorem B1, for finitely
generated \(G\) and normal \(N\trianglelefteq G\) with \(G/N\) abelian.

### Relevant modules

- FJ30
- FJ31
- FJ38
- FJ41

### Dependencies

Bieri--Neumann--Strebel (1987).

### Next action

First-pass resolved by `FJ41`. Direct BNS theorem use is now source-verified
for finite generation of normal subgroups with abelian quotient, but a
separate computation of \(\Sigma(G)\) is still needed before any new
`RB-004` family is removed.

## OQ-044. Which source handles RB-004 cases outside Brown's two-generator criterion?

### Status

Resolved for first-pass source selection by `FJ38`; theorem use still
deferred.

### Context

Brown gives a strong computable route for two-generator one-relator
presentations, but `T-001` may contain cases where no compatible
two-generator presentation has been recorded. Those cases need either a
presentation bridge or a separate kernel-recognition source.

`FJ37` selects this question as the next target after the \(G_{p,q}\)-family
route bridge. The reason is conservative: after `FJ36`, the project has a
family bridge inside Brown's checked two-generator setting, but it still has
no broader `RB-004` source for cases outside that setting.

`FJ38` resolves the first source-selection pass by choosing the
Bieri--Neumann--Strebel, Bieri--Renz, Bieri, and Karrass--Solitar
normal-subgroup source cluster for direct verification. Friedl--Tillmann and
Kielak are recorded as background or possible later sources, not as the
immediate route.

### Relevant modules

- FJ29
- FJ30
- FJ31
- FJ37
- FJ38

### Dependencies

Brown (1987), Bieri--Neumann--Strebel (1987), Bieri--Renz (1988), Bieri
(1976), Karrass--Solitar (1978), and one-relator structure sources already
tracked in `FJ21`--`FJ22`.

### Next action

`FJ39` and `FJ40` have completed the normal-subgroup bridge and finitely presented-kernel selection pass. `reflections/cycle_002_reflection.md` is complete; continue with `FJ46`, source-convention decision for `RB-005`, before any new source-cluster continuation.

## OQ-045. Which Brown test case is not already removed by the virtually solvable route?

### Status

Resolved for first-pass selection.

### Context

`FJ31` verifies the Brown workflow on the commutator presentation, but that
example is already removed by the virtually solvable route. The next Brown
case should be selected with route overlap in mind, so the project does not
mistake a calibration example for a new residual subtraction.

`FJ32` selects
\[
G_{2,3}=\langle x,y\mid x^2y^{-3}\rangle
\]
with \(\chi(x)=3\), \(\chi(y)=2\) as the next Brown test case. At the
selection stage this was only a first-pass choice: the repository had not yet
recorded a virtual-solvability bridge, a target-status bridge for `T-001`, or
a finite-rank free-kernel bridge.

`FJ33` records the finite-rank free-by-cyclic bridge
\[
G_{2,3}\cong F_2\rtimes\mathbb Z.
\]

### Relevant modules

- FJ25
- FJ26
- FJ30
- FJ31
- FJ32
- FJ33

### Dependencies

`ledgers/t001_kernel_recognition.md`, `ledgers/t001_residual.md`, Brown
(1987), and the virtually solvable-route warnings from `FJ25`.

### Next action

First-pass selection resolved by `FJ32`; route bridge completed by `FJ33`.

## OQ-046. Which nonabelian two-generator one-relator family should be tested next?

### Status

Resolved for first-pass selection.

### Context

The first Brown test case was abelian. A second test should exercise the
same maximum-count machinery on a nonabelian two-generator one-relator
presentation or small family, while staying within the theorem hypotheses
already recorded from Brown (1987).

`FJ32` selects \(G_{2,3}\). It verifies nonabelianness internally by the
quotient \(G_{2,3}\twoheadrightarrow S_3\) sending \(x\mapsto(12)\) and
\(y\mapsto(123)\).

### Relevant modules

- FJ26
- FJ30
- FJ31
- FJ32
- FJ33

### Dependencies

Brown (1987), `ledgers/t001_kernel_recognition.md`, and any source-verified
presentation or elementary internal computation used to identify the kernel
bridge.

### Next action

First-pass selection resolved by `FJ32`; worked test completed by `FJ33`.

## OQ-047. Does G_{2,3} have a target-status bridge for T-001?

### Status

Resolved for first-pass route bridge.

### Context

`T-001` concerns torsion-free one-relator residual gap analysis. `FJ32`
selects \(G_{2,3}=\langle x,y\mid x^2y^{-3}\rangle\) as a Brown test case,
but it does not yet record a source-verified or internally proved
target-status bridge placing this presentation inside the active
torsion-free one-relator target rather than merely inside the Brown-workflow
examples.

`FJ33` resolves this by rewriting
\[
G_{2,3}\cong F_2\rtimes\mathbb Z.
\]
The original presentation is one-relator, and the semidirect-product form
gives an internal torsion-freeness check.

### Relevant modules

- FJ19
- FJ20
- FJ30
- FJ32
- FJ33

### Dependencies

The `T-001` target definition from `FJ20`, the one-relator status warnings
from `FJ19`, and any later source or internal proof used to verify
torsion-free target status.

### Next action

First-pass resolved by `FJ33`.

## OQ-048. Can the Brown-positive kernel for G_{2,3} be identified as finite-rank free?

### Status

Resolved for first-pass route bridge.

### Context

Brown's Corollary 3.2 gives finite generation of the kernel after both
\([\chi]\) and \([-\chi]\) pass. The `FJ26` route, however, needs a
finite-rank free-kernel bridge. `FJ32` records only the preliminary
Brown-positive computation for \(G_{2,3}\), not the full kernel
identification.

`FJ33` identifies the kernel internally:
\[
\ker(\chi)\cong F_2.
\]
It uses a change to the braid presentation and then an explicit
semidirect-product presentation.

### Relevant modules

- FJ26
- FJ30
- FJ32
- FJ33

### Dependencies

Brown (1987), `ledgers/t001_kernel_recognition.md`, and a future internal
kernel computation or source for the kernel structure.

### Next action

First-pass resolved by `FJ33`. The `FJ26` route can be invoked for this
concrete example.

## OQ-049. Which nearby Brown family should be tested next?

### Status

Resolved for first-pass family selection and Brown computation.

### Context

`FJ33` proves the finite-rank free-by-cyclic bridge for
\(G_{2,3}=\langle x,y\mid x^2y^{-3}\rangle\). A natural next question is
whether nearby presentations
\[
\langle x,y\mid x^p y^{-q}\rangle
\]
with \(\gcd(p,q)=1\) admit a similar Brown computation and semidirect-product
bridge. This should be tested directly rather than imported as torus-knot
folklore.

`FJ34` resolves the selection part by testing
\[
G_{p,q}=\langle x,y\mid x^p y^{-q}\rangle,\qquad p,q\geq2,\quad
\gcd(p,q)=1,
\]
with \(\chi_{p,q}(x)=q\) and \(\chi_{p,q}(y)=p\). It proves the
Brown-positive finite-generation statement for \(\ker(\chi_{p,q})\), but it
does not identify the kernel as finite-rank free.

### Relevant modules

- FJ30
- FJ32
- FJ33
- FJ34

### Dependencies

Brown (1987), the explicit \(G_{2,3}\) computation in `FJ33`, and any later
source or internal proof used for the family-level kernel bridge.

### Next action

First-pass resolved by `FJ34`; the family-level bridge is now completed by
`FJ36`. `FJ39` and `FJ40` have completed the normal-subgroup bridge and
finitely presented-kernel selection pass for `RB-004`. Continue with the
cycle-002 reflection.

## OQ-050. Which parts of the G_{2,3} proof generalize without new sources?

### Status

Resolved for first-pass boundary.

### Context

The `FJ33` proof has several distinct ingredients: the Brown
initial-segment computation, the braid-presentation change, the explicit
semidirect-product rewrite, and the torsion-free target-status check. A later
module should separate which pieces are formal in \(p,q\), which are special
to \(2,3\), and which require a source before theorem-level use.

`FJ34` records that the epimorphism and Brown maximum-count computation
generalize to \(G_{p,q}\). It does not generalize the braid-presentation
change, the explicit semidirect-product rewrite, the finite-rank free-kernel
identification, or the torsion-free target-status bridge for the whole
family.

### Relevant modules

- FJ30
- FJ33
- FJ34

### Dependencies

The internal proof in `FJ33`, Brown (1987), and any family-level presentation
or kernel-recognition source selected later.

### Next action

First-pass resolved by `FJ34`; `FJ36` records the missing Bass--Serre bridge
for the \(G_{p,q}\)-family. `FJ39` has completed normal-subgroup bridge
source verification for `RB-004`. `reflections/cycle_002_reflection.md` is complete; continue with `FJ46`, source-convention decision for `RB-005`.

## OQ-051. Can \(\ker(\chi_{p,q})\) be identified as finite-rank free?

### Status

Resolved for first-pass family route by `FJ36`.

### Context

`FJ34` proves that \(\ker(\chi_{p,q})\) is finitely generated for
\[
G_{p,q}=\langle x,y\mid x^p y^{-q}\rangle,\qquad p,q\geq2,\quad
\gcd(p,q)=1.
\]
The `FJ26` finite-rank free-by-cyclic route needs more: the kernel must be
identified as a finite-rank free group, or a source-verified theorem must
provide an equivalent bridge.

`FJ36` provides that bridge. It views \(G_{p,q}\) as the cyclic amalgam
\[
G_{p,q}\cong \langle x\rangle *_{\langle z\rangle}\langle y\rangle,
\qquad z\mapsto x^p,\quad z\mapsto y^q,
\]
uses the associated Bass--Serre tree \(T_{p,q}\), proves that \(K_{p,q}\)
intersects all conjugates of the cyclic vertex groups trivially, and concludes
that \(K_{p,q}\) acts freely on \(T_{p,q}\). The source-verified free-action
bridge then gives that \(K_{p,q}\) is free; Brown finite generation from
`FJ34` makes it finite-rank free.

### Relevant modules

- FJ26
- FJ30
- FJ33
- FJ34
- FJ35
- FJ36

### Dependencies

Brown (1987), Serre (1980), Carrasco--Mackay (2022),
Chiswell--Mueller (2012), Margalit (2017), the \(G_{2,3}\) computation in
`FJ33`, and the \(G_{p,q}\) setup from `FJ34`.

`FJ35` selects a Bass--Serre freeness bridge instead of a direct
Reidemeister--Schreier computation. `FJ36` verifies that bridge. The argument
views
\[
G_{p,q}\cong \langle x\rangle *_{\langle z\rangle}\langle y\rangle
\]
and notes that \(K_{p,q}=\ker(\chi_{p,q})\) intersects all conjugates of the
cyclic vertex groups trivially. The exact rank is not computed.

### Next action

First-pass resolved by `FJ36`; `FJ37` decides that the exact rank is not
route-critical and keeps it deferred.

## OQ-052. Which source should support a family-level torus-knot or fibered-kernel theorem?

### Status

Open but deferred for the immediate route.

### Context

The presentation \(G_{p,q}=\langle x,y\mid x^p y^{-q}\rangle\) resembles a
standard torus-knot group presentation, but `FJ34` deliberately does not use
that interpretation. Before the project records a family-level fibered-kernel
or torus-knot theorem, it needs a source with exact hypotheses and a
project-compatible conclusion.

### Relevant modules

- FJ21
- FJ26
- FJ30
- FJ34
- FJ35
- FJ36

### Dependencies

Future source selection for torus-knot groups, fibered knots, or direct
one-relator kernel computations.

`FJ35` decides that the immediate \(G_{p,q}\) kernel bridge should not use a
torus-knot or fibered-knot theorem. `FJ36` completes the immediate route by
Bass--Serre freeness, using Serre's *Trees* as the canonical reference with
auxiliary exact source checks.

### Next action

Defer torus-knot or fibered-knot source selection unless a later module needs
the geometric interpretation. It is no longer needed for the immediate
\(G_{p,q}\)-family bridge.

## OQ-053. Can Serre's Trees verify the Bass--Serre freeness bridge for K_{p,q}?

### Status

Resolved for first-pass bridge by `FJ36`.

### Context

`FJ35` identifies a conditional route from Brown finite generation to
finite-rank freeness: use the cyclic-amalgam shape of
\[
G_{p,q}=\langle x,y\mid x^p=y^q\rangle
\]
and show that \(K_{p,q}=\ker(\chi_{p,q})\) acts freely on the associated
Bass--Serre tree. The missing proof-sensitive step is a source-verified
statement that the relevant amalgam acts on a tree with vertex stabilizers
conjugate to the two cyclic factors, and that a subgroup acting freely on a
tree is free. `FJ36` records Serre as the canonical Bass--Serre reference and
uses Carrasco--Mackay, Chiswell--Mueller, and Margalit for accessible exact
checks of the stabilizer and free-action statements.

### Relevant modules

- FJ26
- FJ34
- FJ35
- FJ36

### Dependencies

Serre (1980), Carrasco--Mackay (2022), Chiswell--Mueller (2012),
Margalit (2017), Brown (1987), and the \(G_{p,q}\) setup from `FJ34`.

### Next action

First-pass resolved by `FJ36`; `FJ39` and `FJ40` have completed the
normal-subgroup bridge and finitely presented-kernel selection pass for
`RB-004`. `reflections/cycle_002_reflection.md` is complete; continue with `FJ46`, source-convention decision for `RB-005`.

## OQ-054. Which residual RB-004 family or subgroup should be attacked after the G_{p,q} bridge?

### Status

Resolved for first-pass next-target selection by `FJ37`.

### Context

`FJ36` removes the \(G_{p,q}\)-family from the active residual by verifying a
finite-rank free-by-cyclic bridge. The project still has no global theorem for
all torsion-free one-relator groups, and the `RB-004` bucket remains only a
selected attack surface, not an exhausted classification.

`FJ37` inspects `ledgers/t001_residual.md` and
`ledgers/t001_kernel_recognition.md`. It selects `OQ-044` as the next target:
source selection for `RB-004` cases outside Brown's checked two-generator
criterion.

### Relevant modules

- FJ28
- FJ29
- FJ36
- FJ37

### Dependencies

The residual ledger, the kernel-recognition ledger, Brown (1987), and any
source selected by `FJ38` and verified by `FJ39`.

### Next action

First-pass resolved by `FJ37`; source selection completed by `FJ38`, and
`FJ39` and `FJ40` have completed the normal-subgroup bridge and finitely
presented-kernel selection pass for `RB-004`. Continue with the cycle-002
reflection.

## OQ-055. Should the exact rank of K_{p,q} be computed?

### Status

Deferred by `FJ37`; open only as an optional later computation.

### Context

`FJ36` proves \(K_{p,q}\cong F_n\) for some finite \(n\). This is enough for
the `FJ26` finite-rank free-by-cyclic route, so the exact value of \(n\) is
not needed for the current Farrell--Jones route subtraction.

A later module may compute the rank if it would clarify the kernel-recognition
ledger, provide a useful calibration example, or help compare the Bass--Serre
method with a Reidemeister--Schreier computation.

`FJ37` decides not to make the rank computation the next module, because
finite rank is already enough for the active `FJ26` route.

### Relevant modules

- FJ26
- FJ34
- FJ36
- FJ37

### Dependencies

The Bass--Serre bridge in `FJ36` and any later rank-computation method.

### Next action

Keep deferred. `FJ39` and `FJ40` have completed the normal-subgroup bridge and finitely presented-kernel selection pass for `RB-004`.
`reflections/cycle_002_reflection.md` is complete; continue with `FJ46`, source-convention decision for `RB-005`.

## OQ-056. Which concrete non-Brown RB-004 test case should follow broader source selection?

### Status

Resolved negatively for the current repository state by `FJ40`.

### Context

`FJ37` selects source selection for `RB-004` beyond Brown's checked
two-generator criterion as the next module. After `FJ38` chooses a broader
source cluster, the project will need a concrete test case or subfamily to
avoid keeping the discussion purely bibliographic.

`FJ38` chooses the BNS/Bieri--Renz/Bieri/Karrass--Solitar source cluster.
`FJ39` verifies the Karrass--Solitar finitely presented normal-subgroup bridge
as the usable first subroute, while leaving direct BNS theorem use open.

`FJ40` audits the source-ready finitely presented kernels currently present
in the repository. The commutator calibration example, \(G_{2,3}\), and the
\(G_{p,q}\)-family are already routed or non-residual. No new non-Brown
source-ready test case is selected.

### Relevant modules

- FJ30
- FJ37
- FJ38
- FJ39
- FJ40

### Dependencies

The Karrass--Solitar bridge verified by `FJ39`, plus the still-open direct
BNS verification question.

### Next action

Closed for cycle 002. Reopen only if a new source-ready finitely presented
kernel candidate is imported or proved.

## OQ-057. What exact normal-subgroup bridge hypotheses are needed?

### Status

Partially resolved by `FJ39` and sharpened by `FJ42`; still open for direct
Bieri (1976) theorem use and for any Bieri--Renz (1988) theorem use.

### Context

`FJ38` selects Bieri (1976) and Karrass--Solitar (1978) as candidate bridge
sources from normal-subgroup finiteness data to one-relator or
cohomological-dimension-\(2\) structure. The project must not blur finitely
generated, finitely presented, \(\mathrm{FP}_2\), and other finiteness
hypotheses.

`FJ39` verifies the Karrass--Solitar bridge under the hypothesis that the
normal subgroup is nontrivial, finitely presented, and of infinite index. It
does not verify a Bieri (1976) primary theorem directly, and it does not turn
finite generation alone into a bridge.

`FJ42` checks Bieri (1976) source access. The bibliographic metadata is
verified, but the primary theorem text is not directly extracted in the
current environment. Later comparison sources point toward finite
presentation or type \(VFP\), not mere finite generation. Therefore Bieri is
not upgraded to theorem-use status, and no residual subtraction is made.

### Relevant modules

- FJ38
- FJ39
- FJ42

### Dependencies

Karrass--Solitar (1978), Bieri (1976), Osajda (2021), Margolis (2026), and
any later source-verified one-relator or cohomological-dimension-\(2\) bridge.

### Next action

For the immediate subroute, use the finite-presentation hypothesis recorded
from Karrass--Solitar. Keep Bieri's primary theorem and any \(\mathrm{FP}_2\)
variant open until the primary theorem text is checked directly. `FJ43` has
paused automatic continuation of this source cluster, and `FJ44` has selected
`RB-005` as the next attack packet. Continue with `FJ46`, source-convention decision for `RB-005`.

## OQ-058. Does direct BNS use give a concrete non-Brown RB-004 family?

### Status

Partially resolved by `FJ41`.

### Context

Brown's checked route gives a computable criterion for compatible
two-generator one-relator presentations. `FJ38` selects the original
Bieri--Neumann--Strebel source for direct verification, but the project still
needs to know whether that source, without Brown's two-generator computation,
actually produces a usable finite-generation criterion for a concrete
`RB-004` family already in the repository.

`FJ39` checks BNS only at orientation level and does not verify the exact
normal-subgroup theorem from the original paper.

`FJ40` does not use direct BNS theorem input. It records that no non-Brown
finitely presented-kernel candidate is source-ready inside the current
repository state.

`FJ41` verifies the original BNS Theorem B1 as a finite-generation criterion:
for finitely generated \(G\), normal \(N\trianglelefteq G\), and \(G/N\)
abelian, \(N\) is finitely generated if and only if \(S(G,N)\subseteq
\Sigma(G)\). For \(\chi\colon G\twoheadrightarrow\mathbb Z\), this becomes
the two-sided \([\chi]\), \([-\chi]\) criterion. However, the theorem does
not compute \(\Sigma(G)\) for a new one-relator family and therefore does
not remove a residual bucket.

### Relevant modules

- FJ30
- FJ37
- FJ38
- FJ39
- FJ40
- FJ41

### Dependencies

Bieri--Neumann--Strebel (1987), Brown (1987), and the residual/kernel
recognition ledgers.

### Next action

First-pass partially resolved by `FJ41`: direct BNS theorem use is verified,
but no concrete non-Brown `RB-004` family is produced. `FJ42` adds no Bieri
theorem-use upgrade or residual subtraction. `FJ43` pauses automatic
source-cluster continuation, and `FJ44` selects `RB-005` as the next attack
packet. Continue with `FJ46`, source-convention decision for `RB-005`.

## OQ-059. Which RB-004 example has a finitely presented kernel?

### Status

Resolved negatively for the current repository state by `FJ40`.

### Context

`FJ39` verifies Karrass--Solitar (1978) as a bridge for one-relator groups
with a nontrivial finitely presented normal subgroup of infinite index. To use
this bridge constructively, the project needs a concrete `RB-004` example or
subfamily where the kernel is known, internally or by source, to be finitely
presented.

`FJ40` checks the current repository candidates and finds no new non-Brown
source-ready example. This is not a mathematical nonexistence claim.

### Relevant modules

- FJ38
- FJ39
- FJ40

### Dependencies

Karrass--Solitar (1978), the `RB-004` residual ledger, and any source or
internal computation proving finite presentation of a kernel.

### Next action

Closed for cycle 002. Reopen only if a later source or internal computation
proves finite presentation for a new residual kernel.

## OQ-060. How should the infinite-dihedral Karrass--Solitar alternative be routed?

### Status

Partially resolved by `FJ45`; still open for coefficient-route use.

### Context

Karrass--Solitar allows the ambient one-relator group to be an infinite
cyclic or infinite dihedral extension of a finitely generated free group. The
infinite cyclic case aligns directly with the `FJ26` finite-rank
free-by-cyclic route. The infinite dihedral case would require a finite-index
or virtually cyclic extension step, and the project must preserve the version
discipline from `FJ27`.

`FJ45` gives the finite-index answer currently available inside the project:
the full \(\mathcal{FJ}\) finite-index overgroup row can be used only when
the finite-index subgroup has full \(\mathcal{FJ}\) status. It does not
license the coefficient K-theory free-by-cyclic route for the infinite
dihedral alternative.

### Relevant modules

- FJ26
- FJ27
- FJ39
- FJ40
- FJ45

### Dependencies

Karrass--Solitar (1978), the `FJ26` route ledger, and version-aware
finite-index inheritance rows from `FJ27`.

### Next action

Do not use the infinite-dihedral alternative as a coefficient-route
subtraction until `OQ-067` is resolved or a version-compatible finite-index
bridge is source-verified.

## OQ-061. What should follow the cycle-002 reflection?

### Status

Resolved by `reflections/cycle_002_reflection.md`.

### Context

`FJ40` closes the module portion of cycle 002 without selecting a new
non-Brown finitely presented-kernel test case. The next step was the
cycle-002 reflection, whose role was to decide whether the next cycle
continues `RB-004` by direct BNS/Bieri verification, handles the
Karrass--Solitar infinite-dihedral finite-index issue, or interrupts the
one-relator thread with the deferred additive-category/source-conventions
work around `FJ02`.

`reflections/cycle_002_reflection.md` selects direct Bieri--Neumann--Strebel
theorem verification as `FJ41`. The finite-index Karrass--Solitar issue and
`FJ02` remain important but are not the first cycle-003 move.

### Relevant modules

- FJ02
- FJ39
- FJ40

### Dependencies

The cycle-002 module record, `OQ-002`, `OQ-022`, `OQ-058`, and `OQ-060`.

### Next action

First-pass resolved. `FJ41` has completed direct BNS theorem verification,
`FJ42` has completed the Bieri source-access check, and `FJ43` has completed
the route-delta checkpoint. `FJ44` has selected `RB-005` as the next attack
packet. Continue with `FJ46`, source-convention decision for `RB-005`.

## OQ-062. Which source computes BNS membership beyond Brown's checked route?

### Status

Open inside project; generated by `FJ41`.

### Context

`FJ41` verifies Bieri--Neumann--Strebel Theorem B1 as a direct
finite-generation criterion, but the theorem is conditional on knowing
whether the relevant character rays lie in \(\Sigma(G)\). Brown (1987)
already supplies a computable two-generator one-relator criterion for the
cases checked in `FJ30`--`FJ34`.

The remaining problem is to find a source or computation that determines
BNS-invariant membership for a new `RB-004` family outside Brown's checked
two-generator route.

### Relevant modules

- FJ30
- FJ38
- FJ41

### Dependencies

Bieri--Neumann--Strebel (1987), Brown (1987), and any future BNS computation
source, such as a source in the Bieri--Renz, Friedl--Tillmann, or Kielak
direction if its hypotheses match the project target.

### Next action

Keep open. Do not use BNS as a residual subtraction until the invariant is
computed or a source-verified membership theorem is recorded.

## OQ-063. What exact Bieri (1976) normal-subgroup theorem is needed?

### Status

Partially resolved by `FJ42`; primary theorem text still not directly checked.

### Context

`FJ39` records Bieri (1976) only as a cited dependency inside the
Karrass--Solitar proof. `FJ41` verifies finite generation through BNS but
does not provide a finite-presentation or finite-rank free-kernel bridge.

The next source-sensitive question is what Bieri (1976) actually states for
normal subgroups in duality groups and groups of cohomological dimension
\(2\), and whether the relevant hypothesis is finite generation, finite
presentation, \(\mathrm{FP}_2\), or something else.

`FJ42` verifies only metadata/source-access status for Bieri (1976), not the
primary theorem text. Osajda (2021) reports a CD-\(2\) theorem with a
finitely presented normal-subgroup hypothesis, and Margolis (2026) reports a
duality-group theorem with a type-\(VFP\) normal-subgroup hypothesis. These
remain `Literature claim` inputs until Bieri's primary text is checked.

### Relevant modules

- FJ38
- FJ39
- FJ41
- FJ42

### Dependencies

Bieri (1976), Karrass--Solitar (1978), and the `RB-004` kernel-recognition
ledger.

### Next action

Do not use Bieri (1976) as a theorem source yet. `FJ43` has paused automatic
Bieri--Renz/BNS source-cluster continuation until a candidate-ready route is
identified, and `FJ44` has selected `RB-005` as the next attack packet.
Continue with `FJ46`, source-convention decision for `RB-005`.

## OQ-064. Should RB-004 continue through the current source cluster?

### Status

First-pass resolved by `FJ43`.

### Context

The strategic audit after cycle 002 requires source modules to produce a
route-delta table. `FJ41` verifies direct BNS finite-generation theorem use,
but does not compute \(\Sigma(G)\) for a new family. `FJ42` checks Bieri
source access and records that Bieri (1976) is not yet source-verified for
theorem use; the comparison sources do not bypass the finite-presentation or
type-\(VFP\) bottleneck.

`FJ43` makes the explicit decision: pause automatic `RB-004`
source-cluster continuation. Further Bieri--Renz/BNS work must be attached
to a concrete candidate, missing bridge, or named residual subtraction.

### Relevant modules

- FJ39
- FJ40
- FJ41
- FJ42
- FJ43

### Dependencies

The strategic audit after cycle 002, the `T-001` residual ledger, the
kernel-recognition ledger, Bieri--Neumann--Strebel (1987), Bieri (1976),
Bieri--Renz (1988), and Karrass--Solitar (1978).

### Next action

Resolved by `FJ43`. `FJ44` selected `RB-005` as the next attack packet, and
`FJ45` completed its first finite-index formulation checkpoint. Continue
with `FJ46`, source-convention decision for `RB-005`.

## OQ-065. Which residual bucket or attack packet should follow the RB-004 source-cluster pause?

### Status

First-pass resolved by `FJ44`.

### Context

`FJ43` pauses automatic continuation of the BNS/Bieri--Renz/Bieri/Karrass--
Solitar source cluster. `FJ44` compares the residual buckets and selects
`RB-005`, finite-index and virtually compact special formulation handling, as
the next attack packet.

### Relevant modules

- FJ28
- FJ37
- FJ43
- FJ44

### Dependencies

The strategic audit after cycle 002, `ledgers/t001_residual.md`,
`ledgers/t001_kernel_recognition.md`, `SCOPE_LEDGER.md`, and the open
residual-bucket rows generated by `FJ28`.

### Next action

Resolved by `FJ44`; `FJ45` completed the finite-index formulation
checkpoint. Begin `FJ46`, source-convention decision for `RB-005`.

## OQ-066. Which finite-index formulation bridge can be used for RB-005?

### Status

First-pass resolved by `FJ45`.

### Context

`RB-005` contains virtually compact special or finite-index bridge cases with
formulation gaps. `FJ24` records compact finite-dimensional special cube
complex groups as CAT(0)-route bridge cases, but keeps virtual-special data
out of the CAT(0) route until a finite-index bridge is recorded. `FJ27`
records finite-index overgroup inheritance only with source-version labels
preserved. `FJ39` records that the Karrass--Solitar infinite-dihedral
alternative would also need finite-index or virtually cyclic handling before
route use.

The task was to determine which finite-index passage can be used without
collapsing coefficient K-theory, full \(\mathcal{FJ}\), CAT(0), `FJCw`, or
other source-specific formulations into one unlabeled claim.

`FJ45` determines that only the full \(\mathcal{FJ}\) finite-index overgroup
row is currently usable. It explicitly does not promote a coefficient
K-theory finite-index overgroup theorem, direct CAT(0) finite-extension
bridge, or `FJCw`/`FICwF` comparison to project use.

### Relevant modules

- FJ02
- FJ12
- FJ24
- FJ27
- FJ39
- FJ44
- FJ45

### Dependencies

`ledgers/inheritance_properties.md`, `ledgers/source_status.md`,
`ledgers/t001_residual.md`, the compact-special bridge from `FJ24`, the
version-aware inheritance rows from `FJ27`, and the finite-index checkpoint
in `FJ45`.

### Next action

Resolved by `FJ45`. Continue with `FJ46`, deciding whether `RB-005` should
source-verify a coefficient K-theory finite-index bridge or interrupt for
`FJ02`/source-convention reconciliation.

## OQ-067. Should RB-005 verify a coefficient finite-index bridge or interrupt for source conventions?

### Status

Open inside project; generated by `FJ45` and selected for `FJ46`.

### Context

`FJ45` records only one currently licensed finite-index overgroup passage:
the full \(\mathcal{FJ}\) survey-level row from Lueck's source-status entry.
That is enough for full-formulation finite-index use when the finite-index
subgroup is already recorded in full \(\mathcal{FJ}\), but it does not by
itself support coefficient K-theory finite-index promotion, direct CAT(0)
finite-extension promotion, or comparisons with `FJCw`/`FICwF` terminology.

The next step must choose between a narrow source-verification task and a
formulation-reconciliation interruption. Continuing `RB-005` productively
requires either a version-compatible finite-index source for the desired
route, or a project-level convention explaining how the competing source
versions are allowed to interact.

### Relevant modules

- FJ02
- FJ12
- FJ24
- FJ27
- FJ39
- FJ44
- FJ45

### Dependencies

`ledgers/inheritance_properties.md`, `ledgers/source_status.md`,
`modules/cycle_003/FJ45_finite_index_formulation_bridge_checkpoint.md`, and
any later source checked for coefficient K-theory finite-index overgroups.

### Next action

Begin `FJ46`, source-convention decision for `RB-005`.
