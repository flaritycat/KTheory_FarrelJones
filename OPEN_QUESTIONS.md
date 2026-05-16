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

First-pass resolved by `FJ02`.

### Context

Module `FJ01` uses a simplified ring-coefficient formulation. The stronger additive-category formulation must not be improvised.

### Relevant modules

- FJ01
- FJ02

### Dependencies

A reliable source for the additive-category formulation.

### Next action

Resolved by `FJ02`, which adopts Bartels--Reich (2007) as the first-pass
source for the additive-category coefficient formulation.

## OQ-003. Which model of nonconnective algebraic K-theory should be used?

### Status

Partially resolved by `FJ02`.

### Context

The simplified conjecture in `FJ01` is stated for all \(n\in\mathbb Z\). This requires a nonconnective algebraic \(K\)-theory model, but `FJ01` intentionally treats \(H_n^G(-;\mathbf K_R)\) as a black box.

### Relevant modules

- FJ01
- FJ02

### Dependencies

Source verification for the chosen model of \(\mathbf K_R\).

### Next action

`FJ02` adopts the Bartels--Reich \(K^{-\infty}\) convention for first-pass
project use. Construction-level details of nonconnective K-theory remain
available for a later foundations module if needed.

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

Resolved for first-pass project use by `FJ74`.

### Context

Module `FJ03` uses the readable contractible/empty fixed-point definition for \(E_{\mathcal F}G\). Lueck's Theorem 1.9 states the homotopy characterization using weakly contractible fixed-point spaces for subgroups in the family, together with the isotropy condition.

`FJ73` selects this as the first foundational cleanup after the target
pauses. The reason is boundedness: the source anchor is already recorded in
`FJ03`, and the expected project object is a convention/dependency cleanup,
not a new source survey.

`FJ74` resolves the question by adopting a two-layer convention:
contractible/empty fixed-point spaces form the strict readable model
convention for examples and exposition, while the source-level theorem behind
existence, uniqueness, terminality, and general recognition remains Lueck's
weakly contractible fixed-point plus isotropy formulation as recorded in
`ER-002`.

### Relevant modules

- FJ03
- FJ74
- FJ15
- FJ16

### Dependencies

A later foundations module should decide how much model-category or \(G\)-CW technical detail the project needs.

### Next action

Resolved by `FJ74`. Use `FND-CONV-001` in later classifying-space modules.

## OQ-006. Should Farrell--Jones 1995 be directly verified for the virtually cyclic dichotomy?

### Status

First-pass resolved negatively by `FJ75`; direct Farrell--Jones 1995 theorem
use is not promoted.

### Context

Module `FJ04` uses Lueck--Reich's source-verified statement that an infinite virtually cyclic group maps with finite kernel either onto \(\mathbb Z\) or onto \(D_\infty\). Lueck--Reich cite Farrell--Jones 1995, Lemma 2.5, as the proof source.

`FJ74` selects this as the next bounded foundational item after resolving
`OQ-005`. The target is exact: check Farrell--Jones (1995), Lemma 2.5, or
record that no source-payload promotion is currently available. This is
tracked by `OBL-FND-003`.

`FJ75` checks DOI and metadata records for Farrell--Jones (1995), but does
not access the primary text of Lemma 2.5. The project therefore records
no-promotion status: Farrell--Jones (1995) is located and DOI-checked, but
is not a direct theorem source in this repository. The `FJ04` dichotomy
continues to rest on the checked Lueck--Reich source statement.

### Relevant modules

- FJ04
- FJ75
- FJ07
- FJ11

### Dependencies

Access to Farrell--Jones, *The lower algebraic K-theory of virtually infinite cyclic groups*, K-Theory 9 (1995), 13--30.

### Next action

Resolved negatively by `FJ75`. Do not cite Farrell--Jones (1995), Lemma 2.5,
as source-verified unless the primary text is later accessed and checked.

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

First-pass resolved by `FJ69` for the current repository state.

### Context

Module `FJ18` records source-verified Farrell--Jones rows for several
Artin-group subclasses, including FC-type Artin groups, even FC-type
Artin groups, right-angled Artin semidirect products, Wu's even-Artin
clique and join constructions, and Roushon's listed finite real,
complex, and affine types.

This does not settle all Artin groups inside the project. The remaining
task is to identify which commonly discussed Artin subclasses still
fall outside those verified rows.

`FJ69` creates `ledgers/artin_subclass_gap_inventory.md`. In the current
repository state, the only explicit global Artin gap row is all Artin groups.
No additional named Artin subclass outside the `FJ18` rows is currently
candidate-ready without a new exact subclass name or source payload.

### Relevant modules

- FJ18
- FJ20+

### Dependencies

`FJ18`, `ledgers/known_classes.md`, and future Artin literature checks.

### Next action

First-pass inventory completed by `FJ69`. `FJ70` records no current
Wu-filter candidate. Continue only through bounded Artin packets such as
`FJ71`, not through a broad source survey.

## OQ-022. Which source should reconcile FJCw, FICwF, and the project's simplified K-theory formulation?

### Status

First-pass resolved by `FJ02`.

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

Resolved by `FJ02`: keep `FJCw`, `FICwF`, finite-wreath-product variants,
full \(\mathcal{FJ}\), coefficient K-theory FJC, and simplified
ring-coefficient FJ as separate source labels unless a comparison is checked.

## OQ-023. Can Wu's clique-reduction route isolate a tractable Artin target not already covered by the verified rows?

### Status

Open as a future route question; current repository filter completed
negatively by `FJ70`.

### Context

Wu's source gives a reduction for even Artin groups from clique
subgroups and records a criterion implying FJCw for a structured family
of even Artin groups. This suggests a possible target-selection route:
look for a remaining Artin subclass where the clique subgroups are
tractable, but the full class is not already covered by `FJ18`.

`FJ69` records this as `ART-GAP-003`: possible Wu clique-reduction target not
already covered by `FJ18`, and selected a candidate filter rather than
another summary of Wu's source.

`FJ70` runs that candidate filter and finds no current candidate in the
repository. The available rows are either already covered by `FJ18` or are
global/placeholder gap rows without a named finite graph, graph family,
subclass, and clique-subgroup data.

### Relevant modules

- FJ18
- FJ20+
- FJ70

### Dependencies

Wu (2022), the inheritance ledger, and a future Artin subclass gap
analysis.

### Next action

Do not continue the Wu lane without the reactivation payload recorded in
`FJ70`. Continue with `FJ71`, Artin Branch Checkpoint After Wu Filter.

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
First build the residual subclass map and run the `RB-003` +
`RB-004`/`RB-008` hybrid attack packet. Later, revisit weaker \(K_0\)-level
or Cohen--Lyndon-style consequences only if they change a bucket, candidate,
proof obligation, or prior-art blocker.

`FJ58` selects this as the next bounded intake lane after recording that no
replacement candidate-production lane is currently ready. `FJ59` resolves the
intake gate negatively for the current repository state: no exact source
payload is recorded. `FJ60` closes the weaker consequence lane as inactive
until a future module names an exact payload. `OQ-024` remains open; no
weaker global theorem is recorded.

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

Partially resolved by `FJ45` and sharpened by `FJ48`; direct CAT(0)
finite-extension use blocked by `FJ49`.

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

`FJ48` records that the `FJ47` `FJCw` finite-index bridge also does not
currently apply to the virtual compact special cases, because the recorded
subgroup input is compact-special/CAT(0) data rather than `FJCw`.

`FJ49` checks the direct CAT(0) finite-extension lane and does not license it:
Ruane records the finite-extension direction for CAT(0)-groups as a question,
with cocompactness missing from the product-action construction.

### Relevant modules

- FJ12
- FJ14
- FJ22
- FJ24
- FJ02
- FJ45
- FJ46
- FJ47
- FJ48
- FJ49

### Dependencies

Finite-index inheritance sources, CAT(0)-group finite-extension sources, or a
source-level convention for virtually compact special groups strong enough for
the project's known-case ledger.

### Next action

Use only the full \(\mathcal{FJ}\) bridge and the `FJ47` `FJCw` bridge in
their exact source lanes. Do not use a direct CAT(0) finite-extension bridge
after `FJ49`. `FJ50` pauses `RB-005`; continue with `OQ-072`/`FJ51` inside
the `RB-006` compact-special/CAT(0)-looking packet.

## OQ-033. Which one-relator groups are compact special beyond the hyperbolic route?

### Status

Open inside project; activated by `FJ50` as part of the `RB-006` pivot.

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
- FJ50

### Dependencies

One-relator cubulation and special-cube-complex sources beyond the first-pass
Haglund--Wise bridge.

### Next action

`FJ51` selects Louder--Wilton for a bounded source-boundary check, `FJ52`
records no independent `RB-006` route delta, and WIP / provisional `FJ53`
records the remaining \(\pi(w)>2\) use as hyperbolic overlap. `FJ54`
demotes `RB-006` pending a genuinely non-hyperbolic bridge and selects the
`RB-003` + `RB-004`/`RB-008` hybrid attack packet; continue with
`OQ-076`/`FJ55`.

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

Partially resolved by `FJ45` and sharpened by `FJ48`; still open for
coefficient-route or compatible finite-index use.

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

`FJ48` records that the `FJ47` `FJCw` bridge does not currently apply either:
the potential finite-index subgroup input is aligned with the `FJ26`
finite-rank free-by-cyclic coefficient route, not with a recorded `FJCw`
row, and no concrete source-ready Karrass--Solitar infinite-dihedral example
is currently selected.

### Relevant modules

- FJ26
- FJ27
- FJ02
- FJ39
- FJ40
- FJ45
- FJ46
- FJ47
- FJ48

### Dependencies

Karrass--Solitar (1978), the `FJ26` route ledger, and version-aware
finite-index inheritance rows from `FJ27`.

### Next action

Do not use the infinite-dihedral alternative as a coefficient-route
subtraction. `FJ48` finds no current `FJCw` subgroup input and no concrete
source-ready example requiring this cleanup. Reopen only after a candidate
or compatible finite-index theorem is selected.

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
checkpoint and `FJ46` selected the `FJ02` source-convention interruption.

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
- FJ46
- FJ02
- FJ47

### Dependencies

`ledgers/inheritance_properties.md`, `ledgers/source_status.md`,
`ledgers/t001_residual.md`, the compact-special bridge from `FJ24`, the
version-aware inheritance rows from `FJ27`, and the finite-index checkpoint
in `FJ45`.

### Next action

Resolved by `FJ45`, with source-convention policy supplied by `FJ02` and the
`FJCw` bridge supplied by `FJ47`. `FJ48` finds no current `FJCw-ready`
application case, and `FJ49` does not supply a direct CAT(0)
finite-extension bridge. `FJ50` pauses `RB-005`; continue with
`OQ-072`/`FJ51`.

## OQ-067. Should RB-005 verify a coefficient finite-index bridge or interrupt for source conventions?

### Status

First-pass resolved by `FJ46`.

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

`FJ46` selects the formulation-reconciliation interruption. The project
should begin `FJ02` before further proof-sensitive `RB-005` use.

### Relevant modules

- FJ02
- FJ12
- FJ24
- FJ27
- FJ39
- FJ44
- FJ45
- FJ46

### Dependencies

`ledgers/inheritance_properties.md`, `ledgers/source_status.md`,
`modules/cycle_003/FJ45_finite_index_formulation_bridge_checkpoint.md`,
`modules/cycle_003/FJ46_source_convention_decision_for_rb005.md`, and any
later source checked for coefficient K-theory finite-index overgroups.

### Next action

Resolved by `FJ46`; the `FJ02` source-convention interruption, `FJ47`
finite-index bridge selection, and `FJ48` application audit are now complete.
`FJ49` also blocks the direct CAT(0) finite-extension shortcut, and `FJ50`
pauses `RB-005`. `FJ51` selects Louder--Wilton for a boundary check; continue
with `OQ-073`/`FJ52`.

## OQ-068. Which source verifies a coefficient finite-index overgroup bridge under FJ02?

### Status

First-pass resolved by `FJ47`.

### Context

`FJ02` supplies the source-convention policy needed after `FJ46`: coefficient
K-theory FJC, full \(\mathcal{FJ}\), `FJCw`, `FICwF`, and the simplified
ring-coefficient formulation remain distinct source labels unless a
comparison is checked. `FJ45` recorded only a full \(\mathcal{FJ}\)
finite-index overgroup bridge. It did not record a coefficient K-theory
finite-index overgroup theorem.

`FJ47` selects a version-preserving answer: the project has a source-verified
finite-index overgroup bridge for `FJCw`, the coefficient formulation with
finite wreath products, but it does not have an unconditional plain
coefficient K-theory finite-index bridge.

### Relevant modules

- FJ02
- FJ12
- FJ24
- FJ27
- FJ45
- FJ46
- FJ47

### Dependencies

`ledgers/inheritance_properties.md`, `ledgers/source_status.md`,
`modules/cycle_001/FJ02_additive_categories.md`, and
`modules/cycle_003/FJ47_fjcw_finite_index_bridge_source_selection.md`.

### Next action

Resolved by `FJ47`; the immediate application audit was completed in `FJ48`.
`FJ49` completed the direct CAT(0) finite-extension check without producing
a bridge. `FJ50` pauses `RB-005`; continue with `OQ-072`/`FJ51`.

## OQ-069. Which RB-005 cases have FJCw finite-index subgroup input?

### Status

First-pass resolved by `FJ48`.

### Context

`FJ47` verifies that `FJCw` passes from finite-index subgroups to
finite-index overgroups. This is useful only when the finite-index subgroup
has already been recorded with the finite-wreath-product version, not merely
with plain coefficient K-theory FJC or a CAT(0)-route label.

The next `RB-005` task is therefore to audit the concrete finite-index
cleanup cases:

- virtual-special cases deferred by `FJ24`;
- the Karrass--Solitar infinite-dihedral alternative from `FJ39`;
- any other finite-index residual row in `ledgers/t001_residual.md`.

`FJ48` performs this audit and records a negative application result: the
current `T-001`/`RB-005` cases are not `FJCw-ready`. The virtual compact
special case has compact-special/CAT(0) subgroup input, not `FJCw`. The
Karrass--Solitar infinite-dihedral cleanup has at most finite-rank
free-by-cyclic coefficient-route input if a concrete candidate is selected,
not `FJCw`.

### Relevant modules

- FJ24
- FJ39
- FJ44
- FJ45
- FJ47
- FJ48

### Dependencies

`ledgers/t001_residual.md`, `ledgers/known_classes.md`,
`ledgers/inheritance_properties.md`, `ledgers/source_status.md`, and
`modules/cycle_003/FJ48_rb005_fjcw_application_audit.md`.

### Next action

Resolved by `FJ48`; the direct finite-dimensional CAT(0) finite-extension
bridge check was completed in `FJ49` and did not produce a usable bridge.
`FJ50` pauses `RB-005`; continue with `OQ-072`/`FJ51`.

## OQ-070. Do finite extensions preserve the finite-dimensional CAT(0) route?

### Status

First-pass resolved by `FJ49`.

### Context

`FJ48` finds no current `T-001`/`RB-005` case with source-verified `FJCw`
finite-index subgroup input. The closest remaining finite-index obstruction
is therefore the virtual compact special case from `FJ24`: a finite-index
subgroup has a compact-special route into finite-dimensional CAT(0)-groups,
but the ambient group still needs a proof-sensitive bridge.

The next task is narrow: source-check whether finite extensions of
finite-dimensional CAT(0)-groups remain usable in the finite-dimensional
CAT(0)-group route recorded by `FJ14` and `FJ24`.

`FJ49` checks Ruane (2008) and records a route-blocking answer. Finite-index
subgroups of CAT(0)-groups are easy, but finite extensions of CAT(0)-groups
are posed there as a question. Serre's product construction gives a proper
isometric action on a finite product of CAT(0)-spaces, but cocompactness is
the missing point. Therefore the desired bridge is not available for current
project route use.

### Relevant modules

- FJ14
- FJ24
- FJ44
- FJ45
- FJ48
- FJ49

### Dependencies

`ledgers/source_status.md`, `ledgers/known_classes.md`,
`ledgers/t001_residual.md`, and
`modules/cycle_003/FJ49_cat0_finite_extension_bridge_check.md`.

### Next action

Resolved by `FJ49`. `FJ50` completed the `RB-005` route-delta checkpoint and
pivoted to `RB-006`; continue with `OQ-072`/`FJ51`.

## OQ-071. Should RB-005 be paused after the finite-index bridge failures?

### Status

First-pass resolved by `FJ50`.

### Context

`RB-005` has now gone through a disciplined sequence:

- `FJ45` found only the full \(\mathcal{FJ}\) finite-index bridge;
- `FJ46` sent the project to `FJ02` for source-convention control;
- `FJ02` supplied the additive-category convention;
- `FJ47` verified the `FJCw` finite-index bridge;
- `FJ48` found no current `T-001` `FJCw-ready` application;
- `FJ49` found no direct CAT(0) finite-extension bridge for current route use.

The next step should not keep adding adjacent source checks unless it selects
a concrete candidate or a new missing bridge. A checkpoint should decide
whether `RB-005` is paused and which attack packet replaces it.

`FJ50` pauses `RB-005` as the immediate attack packet. It records no residual
subtraction, but it prevents the finite-index thread from continuing as
decorative source bookkeeping. The replacement attack packet is `RB-006`,
compact special or CAT(0)-looking one-relator cases beyond the hyperbolic
route.

### Relevant modules

- FJ44
- FJ45
- FJ46
- FJ02
- FJ47
- FJ48
- FJ49
- FJ50

### Dependencies

`ledgers/t001_residual.md`, `reflections/strategic_audit_after_cycle_002.md`,
and the current `RB-005` module sequence.

### Next action

Resolved by `FJ50`. `FJ51` resolved `OQ-072`, `FJ52` resolved `OQ-073`,
WIP / provisional `FJ53` addressed `OQ-074`, `FJ54` resolved `OQ-075`, and
`FJ55` resolved `OQ-076` and `FJ56` resolved `OQ-077`; continue with
`OQ-078`/`FJ57`.

## OQ-072. Which source can make RB-006 candidate-ready?

### Status

First-pass resolved by `FJ51`.

### Context

`FJ50` pauses `RB-005` after its finite-index bridge sequence produces no
residual subtraction. The selected pivot is `RB-006`: compact special or
CAT(0)-looking one-relator cases beyond the hyperbolic route.

The next module should not start a broad cubulation survey. It should decide
whether the repository has, or can narrowly select, a one-relator cubulation,
specialness, or CAT(0)-recognition source that could produce a concrete
candidate or bridge not already absorbed by `FJ23`.

`FJ51` selects Louder--Wilton (2022) as the next bounded source, but only as
a boundary check. No theorem from that source is imported yet.

### Relevant modules

- FJ22
- FJ23
- FJ24
- FJ44
- FJ49
- FJ50
- FJ51

### Dependencies

`ledgers/t001_residual.md`, `ledgers/source_status.md`,
`reflections/strategic_audit_after_cycle_002.md`, and Louder--Wilton (2022)
as a source selected for `FJ52` verification.

### Next action

Resolved by `FJ51`. `FJ52` completed the Louder--Wilton boundary check, and
WIP / provisional `FJ53` recorded the remaining \(\pi(w)>2\) use as
hyperbolic overlap; `FJ54` selected the `RB-003` + `RB-004`/`RB-008` hybrid
attack packet before further source work; `FJ55` resolved the hierarchy
bridge test, and `FJ56` resolved the kernel-control inventory; continue with
`OQ-078`/`FJ57`.

## OQ-073. Does Louder--Wilton give an RB-006 route delta?

### Status

First-pass resolved by `FJ52`.

### Context

`FJ51` selects Louder--Wilton (2022) as a bounded source-boundary check for
`RB-006`. The check must separate compact-special/CAT(0)-looking route delta
from hyperbolic overlap. If the source only supplies hyperbolic-route input,
the result should be counted through `FJ23`, not as new `RB-006` progress.

`FJ52` checks the source and records that Louder--Wilton gives the
\(\pi(w)>2\) negative-immersion bridge and subgroup-structure consequences,
but not an independent compact-special/CAT(0) route. Its useful project role
is hyperbolic-route overlap.

### Relevant modules

- FJ22
- FJ23
- FJ24
- FJ50
- FJ51
- FJ52

### Dependencies

Louder--Wilton (2022), Linton's negative-immersion route row from `FJ22`,
`ledgers/source_status.md`, `ledgers/t001_residual.md`, and the stop
condition from `FJ51`.

### Next action

Resolved by `FJ52`. WIP / provisional `FJ53` records the \(\pi(w)>2\)
criterion as hyperbolic-route overlap and demotes the Louder--Wilton
`RB-006` path; `FJ54` selects the `RB-003` + `RB-004`/`RB-008` hybrid
attack packet; `FJ55` resolves `OQ-076` and `FJ56` resolves `OQ-077`;
continue with `OQ-078`/`FJ57`.

## OQ-074. Should pi(w)>2 be recorded as hyperbolic-route overlap?

### Status

WIP / provisional in `FJ53`.

### Context

`FJ52` records that Louder--Wilton (2022) supplies a
\(\pi(w)>2\)-to-negative-immersions bridge and subgroup-structure
consequences. It does not supply an independent compact-special/CAT(0) route.

The only possible immediate route value is through the hyperbolic route:
combine Louder--Wilton's negative-immersion bridge with Linton's
negative-immersion-to-hyperbolicity theorem already recorded in `FJ22`, then
use the `FJ23` hyperbolic route. The project must decide whether to record
that overlap explicitly or treat it as already absorbed by the `FJ23`
negative-immersion route marker.

`FJ53` provisionally records the route explicitly as hyperbolic overlap:
\(\pi(w)>2\Rightarrow\) negative immersions \(\Rightarrow\) hyperbolicity
\(\Rightarrow\) `FJ23`. This is not `RB-006` compact-special/CAT(0) progress,
and it produces no concrete residual subtraction because no specific word
\(w\) is checked. `FJ53` remains WIP / provisional until a later module
explicitly finalizes the route-overlap handoff.

### Relevant modules

- FJ22
- FJ23
- FJ24
- FJ51
- FJ52
- FJ53

### Dependencies

Louder--Wilton (2022), Linton (2024), `ledgers/source_status.md`, and
`ledgers/t001_residual.md`.

### Next action

Provisionally addressed by `FJ53`. `FJ54` resolves the post-`RB-006`
checkpoint, `FJ55` resolves `OQ-076`, and `FJ56` resolves `OQ-077`; continue
with `OQ-078`/`FJ57`.

## OQ-075. Which attack packet follows the demoted RB-006 path?

### Status

First-pass resolved by `FJ54`.

### Context

`FJ43` pauses automatic continuation of the `RB-004`
BNS/Bieri/Karrass--Solitar source cluster. `FJ50` pauses `RB-005` after the
finite-index bridge sequence produces no residual subtraction. WIP /
provisional `FJ53` demotes the Louder--Wilton `RB-006` path as
non-subtractive for compact-special/CAT(0) purposes, preserving only the
hyperbolic-overlap criterion through `FJ23`.

The project now needs a residual-bucket checkpoint rather than another
decorative source-selection step. The next module should compare the remaining
attack surfaces and either select a candidate-ready packet or explicitly
record that the project should pivot to a different kind of work, such as
example construction or a missing-bridge inventory.

`FJ54` resolves this by ranking the residual buckets and selecting the
`RB-003` + `RB-004`/`RB-008` hybrid attack packet. The next step is not a
theorem-source search; it is a primitive-extension / hierarchy-to-FJ bridge
test combined with kernel-control pressure.

### Relevant modules

- FJ43
- FJ50
- FJ51
- FJ52
- FJ53
- FJ54

### Dependencies

`ledgers/t001_residual.md`, `ledgers/open_group_classes.md`,
`reflections/strategic_audit_after_cycle_002.md`, and the route decisions
from `FJ43`, `FJ50`, and `FJ53`.

### Next action

Resolved by `FJ54`. `FJ55` resolves revised `OQ-076`, and `FJ56` resolves
`OQ-077`; continue with `OQ-078`/`FJ57`.

## OQ-076. Can hierarchy / primitive-extension data become a route, candidate, bridge, or obstruction?

### Status

First-pass resolved by `FJ55`.

### Context

`FJ54` selects the primary attack packet:

`RB-003` + `RB-004`/`RB-008` hybrid: primitive-extension / hierarchy
framework combined with explicit kernel-control testing for concrete
torsion-free one-relator candidate families.

`FJ55` tests whether Linton-style hierarchy / primitive-extension
data can be converted into an FJ route, a candidate family, a bridge lemma,
or a documented obstruction. The candidate inventory in
`ledgers/t001_candidate_inventory.md` must be updated only with repository
supported candidates or clearly marked placeholders.

`FJ55` resolves this at first pass by recording a documented obstruction:
there is no direct hierarchy-to-FJ bridge currently licensed in the
repository. Hierarchy data must pass through an approved route output such as
hyperbolicity, finite-dimensional CAT(0), finite-rank free or hyperbolic
kernel extension data, or version-safe inheritance. The proof obligations
are recorded as `OBL-T001-001` and `OBL-T001-002`.

### Relevant modules

- FJ28
- FJ36
- FJ43
- FJ50
- FJ53
- FJ54
- FJ55

### Dependencies

`ledgers/t001_residual.md`, `ledgers/open_group_classes.md`,
`ledgers/t001_kernel_recognition.md`, and
`ledgers/t001_candidate_inventory.md`, and
`reflections/strategic_audit_after_cycle_002.md`.

### Next action

Resolved by `FJ55`. `FJ56` resolves `OQ-077`; continue with
`OQ-078`/`FJ57`.

## OQ-077. Which candidate rows can receive kernel-control data?

### Status

First-pass resolved by `FJ56`.

### Context

`FJ55` records that hierarchy / primitive-extension data is not a direct FJ
route. The selected hybrid packet therefore needs explicit kernel-control
work: for each repository-supported candidate row, identify whether there is
an epimorphism to \(\mathbb Z\), a kernel type, and an extension theorem
candidate.

The existing candidate inventory contains only previously recorded examples
and one template placeholder. `FJ56` must not fabricate new families; it must
populate kernel-control fields where the repository already supports them or
record why no active candidate can be made checkable.

`FJ56` resolves the question by auditing all current rows:

- `CAND-T001-001` has kernel-control data but is calibration-only and already
  covered by the virtually solvable route;
- `CAND-T001-002` has \(\ker(\chi)\cong F_2\) and is already routed through
  `FJ26`;
- `CAND-T001-003` has finite-rank free kernel by the `FJ36` Bass--Serre
  bridge and is already routed through `FJ26`;
- `TPL-RB003-004-008` remains a placeholder, not a mathematical candidate.

Thus the inventory has no live non-routed kernel-control candidate after
`FJ56`. The obstruction is recorded as `OBL-T001-003`.

### Relevant modules

- FJ30
- FJ36
- FJ41
- FJ54
- FJ55
- FJ56

### Dependencies

`ledgers/t001_candidate_inventory.md`,
`ledgers/t001_kernel_recognition.md`, `ledgers/t001_residual.md`, and the
route-output obligations from `FJ55`.

### Next action

Resolved by `FJ56`. Continue with `OQ-078`/`FJ57`.

## OQ-078. Can FJ57 promote a non-routed candidate or record the no-candidate obstruction?

### Status

First-pass resolved by `FJ57`.

### Context

`FJ56` records that all current concrete candidate rows in
`ledgers/t001_candidate_inventory.md` are route-exhausted: they are
calibration-only or already removed through the `FJ26` finite-rank
free-by-cyclic route. The remaining template row is not a mathematical
candidate.

The next module must not repeat the inventory. It must either promote a
repository-supported, non-routed candidate family into the candidate ledger
and attempt its bridge, or record the no-candidate obstruction as the current
endpoint of the `RB-003` + `RB-004`/`RB-008` hybrid packet.

`FJ57` resolves this by recording the obstruction. The project cannot promote
a non-routed candidate from the current repository without fabrication. The
concrete rows are route-exhausted, and the remaining residual lanes lack the
minimum candidate intake data.

### Relevant modules

- FJ30
- FJ36
- FJ41
- FJ54
- FJ55
- FJ56

### Dependencies

`ledgers/t001_candidate_inventory.md`,
`ledgers/t001_kernel_recognition.md`, `ledgers/t001_residual.md`, and
`OBL-T001-003`.

### Next action

Resolved by `FJ57`. Continue with `OQ-079`/`FJ58`.

## OQ-079. Which candidate-production lane should replace the blocked hybrid packet?

### Status

First-pass resolved by `FJ58`.

### Context

`FJ57` closes the current `RB-003` + `RB-004`/`RB-008` hybrid packet as
blocked at candidate production. This is not a theorem-level negative result
and does not abandon `T-001`. It means that another continuation of the same
packet would need a new real candidate, bridge lemma, or prior-art comparison.

The next module should decide which candidate-production lane can be made
legitimate without reopening passive source accumulation. Candidate lanes may
include returning to a paused residual bucket only if a named candidate or
bridge is available, selecting a lower-priority consequence lane only if it
changes a proof obligation, or explicitly pausing `T-001` proof attempts if
no candidate-production lane is ready.

`FJ58` resolves this by recording that no currently named residual lane is
candidate-ready as a proof-attempt lane. The blocked hybrid packet should not
be reactivated without a real candidate, bridge lemma, computation, or
prior-art comparison. `FJ58` records this as `OBL-T001-005` and selects a
bounded weaker \(K_0\) / Cohen--Lyndon consequence intake as the next module.

### Relevant modules

- FJ40
- FJ43
- FJ50
- FJ54
- FJ55
- FJ56
- FJ57

### Dependencies

`ledgers/t001_candidate_inventory.md`, `ledgers/t001_residual.md`,
`ledgers/t001_kernel_recognition.md`, and `OBL-T001-004`.

### Next action

Resolved by `FJ58`. Continue with `OQ-080`/`FJ59`.

## OQ-080. Can a weaker K0 / Cohen--Lyndon consequence lane update T-001 without being misread as a route subtraction?

### Status

First-pass resolved by `FJ59`.

### Context

`FJ58` records that no replacement candidate-production lane is currently
ready after the blocked `RB-003` + `RB-004`/`RB-008` hybrid packet. The only
named lower-priority lane not yet tested is the weaker \(K_0\) /
Cohen--Lyndon update flagged by `FJ54` and related to `OQ-024`.

This lane must be handled conservatively. A weaker \(K_0\)-level,
finiteness-obstruction, or Cohen--Lyndon-style statement may update a
consequence ledger, prior-art blocker, or proof obligation, but it does not
by itself prove the Farrell--Jones conjecture for torsion-free one-relator
groups and does not subtract a residual bucket.

`FJ59` resolves this at the intake level. The existing \(K_0\)-level
consequences in `FJ08` and `FJ09` are conditional on Farrell--Jones; they do
not provide an independent weaker theorem for all torsion-free one-relator
groups. The repository also has no exact Cohen--Lyndon-style source payload
recorded. Thus the lane cannot yet update `T-001` except by selecting or
closing a source-payload check.

### Relevant modules

- FJ08
- FJ09
- FJ24
- FJ54
- FJ57
- FJ58

### Dependencies

`OQ-024`, `ledgers/t001_candidate_inventory.md`,
`ledgers/t001_residual.md`, `ESTABLISHED_RESULTS.md`, and any source selected
by `FJ59` for exact weaker-consequence hypotheses.

### Next action

Resolved by `FJ59`; `FJ60` resolves `OQ-081` by closing the lane inactive.
Continue with the cycle-003 reflection.

## OQ-081. Which exact source supplies a weaker K0 / Cohen--Lyndon payload relevant to T-001?

### Status

First-pass resolved by `FJ60`.

### Context

`FJ59` records `OBL-T001-006`: no weaker \(K_0\) / Cohen--Lyndon source
payload is currently available for `T-001`. A future module may continue this
lane only by selecting an exact source payload or by closing the lane as
inactive until a source is named.

The next step must not become a survey of classical one-relator sources. A
source name is insufficient. The selected payload must include a theorem
statement, exact hypotheses, formulation level, and the project object it
would change.

`FJ60` resolves this by selecting no payload. The repository's current
source-status ledger has no exact weaker \(K_0\) / Cohen--Lyndon theorem
payload available: the classical one-relator sources remain `found; to
verify`, and the existing low-dimensional \(K\)-theory consequences remain
conditional on Farrell--Jones. The lane is inactive until a future module
names an exact source, theorem statement, hypotheses, formulation level, and
project object changed.

### Relevant modules

- FJ08
- FJ09
- FJ19
- FJ21
- FJ54
- FJ58
- FJ59
- FJ60

### Dependencies

`ledgers/source_status.md`, `BIBLIOGRAPHY.md`,
`ledgers/t001_candidate_inventory.md`, `OBL-T001-006`, and
`OBL-T001-007`.

### Next action

Resolved by `FJ60`. `reflections/cycle_003_reflection.md` resolves
`OQ-082`; `FJ61` resolves `OQ-083` and selects `OQ-084` / `FJ62`.

## OQ-082. What should the cycle-003 reflection select after the T-001 lanes stalled?

### Status

First-pass resolved by `reflections/cycle_003_reflection.md`.

### Context

Cycle 003 completed the BNS/Bieri/Karrass--Solitar route-delta sequence,
finite-index formulation sequence, `RB-006` boundary check, hybrid
candidate-production packet, and weaker consequence lane. These produced
useful obstructions and source discipline, but no new non-routed candidate
or residual subtraction after the earlier \(G_{p,q}\)-family route.

The reflection decides that `T-001` remains important but is not currently
candidate-ready. It selects `FJ61`, T-001 Candidate-Intake Reset and Exit
Criteria, as the first cycle-004 move. `FJ61` must define candidate-intake
rules and exit criteria rather than restart passive source accumulation.

### Relevant modules

- FJ41--FJ60
- WIP / provisional FJ53
- cycle_002_reflection
- reflections/cycle_003_reflection.md

### Dependencies

`ledgers/t001_candidate_inventory.md`, `ledgers/t001_residual.md`,
`ledgers/t001_kernel_recognition.md`, `SCOPE_LEDGER.md`, and
`PROJECT_CHARTER.md`.

### Next action

Resolved by `reflections/cycle_003_reflection.md`. `FJ61` resolves
`OQ-083` and selects `OQ-084` / `FJ62`.

## OQ-083. What candidate-intake and exit criteria should govern T-001 after cycle 003?

### Status

First-pass resolved by `FJ61`.

### Context

Cycle 003 closed with no live non-routed candidate after the BNS/Bieri route
boundary, finite-index formulation checks, WIP / provisional `FJ53` and
`RB-006` demotion, the blocked `RB-003` + `RB-004`/`RB-008` hybrid packet,
and the inactive weaker \(K_0\) / Cohen--Lyndon lane.

`FJ61` decides this by defining candidate-admissible rows, allowed
route-output targets, and early cycle-004 exit criteria. It records
`OBL-T001-008`, the candidate-intake gate: no cycle-004 `T-001` module may
launch a proof attempt, source verification, or route subtraction unless it
changes a candidate, bridge, computation, source payload, prior-art blocker,
target-pause recommendation, or target-pivot comparison.

### Relevant modules

- FJ54--FJ60
- WIP / provisional FJ53
- reflections/cycle_003_reflection.md

### Dependencies

`ledgers/t001_candidate_inventory.md`, `ledgers/t001_residual.md`,
`ledgers/t001_kernel_recognition.md`, `PROJECT_CHARTER.md`, and `AGENTS.md`.

### Next action

Resolved by `FJ61`. Continue with `OQ-084` and `FJ62`.

## OQ-084. Which active blockers should FJ62 preserve for T-001 candidate intake?

### Status

First-pass resolved by `FJ62`.

### Context

`FJ61` keeps `T-001` active only through an intake gate. The next step is to
prune the accumulated open questions and proof obligations so that early
cycle 004 does not mistake historical trail markers for active blockers.

`FJ62` sorts blockers into:

- active candidate-intake blockers;
- deferred foundations;
- historical trail markers;
- possible target-pivot comparison inputs.

After pruning, the active blockers for the next module are candidate-object
acquisition, route-data acquisition, and the branch decision about whether
the acquisition attempt succeeds.

### Relevant modules

- FJ41--FJ61
- WIP / provisional FJ53
- reflections/cycle_003_reflection.md

### Dependencies

`SCOPE_LEDGER.md`, `OPEN_QUESTIONS.md`,
`ledgers/t001_candidate_inventory.md`, `ledgers/t001_residual.md`,
`ledgers/t001_kernel_recognition.md`, and `PROJECT_CHARTER.md`.

### Next action

Resolved by `FJ62`. Continue with `OQ-085` and `FJ63`.

## OQ-085. Which exact data-acquisition packet should FJ63 select after active blocker pruning?

### Status

First-pass resolved by `FJ63`.

### Context

`FJ62` records `OBL-T001-009`: `FJ63` must select exactly one
data-acquisition packet or record failure to do so. `FJ63` resolves this by
selecting `DAP-T001-001`, candidate-row acquisition from current repository
records.

Allowed packet types are:

- candidate-row acquisition;
- bridge-lemma acquisition;
- concrete computation acquisition;
- exact source-payload acquisition;
- prior-art blocker acquisition;
- target-pause trigger;
- target-pivot comparison trigger.

### Relevant modules

- FJ61
- FJ62
- WIP / provisional FJ53
- reflections/cycle_003_reflection.md

### Dependencies

`ledgers/t001_candidate_inventory.md`, `ledgers/t001_residual.md`,
`ledgers/t001_kernel_recognition.md`, and `PROJECT_CHARTER.md`.

### Next action

Resolved by `FJ63`. Continue with `OQ-086` and `FJ64`.

## OQ-086. Can FJ64 produce a candidate-admissible row from DAP-T001-001?

### Status

First-pass resolved by `FJ64`.

### Context

`FJ63` selects `DAP-T001-001`, candidate-row acquisition from current
repository records. `FJ64` executes that packet and records a no-candidate
note.

The allowed outcomes are:

- add one candidate-admissible row to `ledgers/t001_candidate_inventory.md`;
  or
- record a no-candidate note explaining why no current repository row can be
  promoted without external source acquisition or fabrication.

`FJ64` records the second outcome: the concrete rows are calibration-only or
already routed, the template row is not a mathematical candidate, and no
residual bucket supplies a named non-routed presentation with route data.

### Relevant modules

- FJ61
- FJ62
- FJ63
- WIP / provisional FJ53

### Dependencies

`ledgers/t001_candidate_inventory.md`, `ledgers/t001_residual.md`,
`ledgers/t001_kernel_recognition.md`, and `OPEN_QUESTIONS.md`.

### Next action

Resolved by `FJ64`. Continue with `OQ-087` and `FJ65`.

## OQ-087. Can FJ65 identify a prior-art blocker or branch object after FJ64?

### Status

First-pass resolved by `FJ65`.

### Context

`FJ64` records a no-candidate note for `DAP-T001-001`. No current repository
row can be promoted to candidate-admissible status without importing a new
source payload or fabricating a family.

`FJ65` checks whether this no-candidate state still leaves any exact prior-art
blocker object, target-pause recommendation, or target-pivot comparison to
record. It records that no exact prior-art blocker object or pivot-comparison
object is currently available. The no-candidate state is a target-pause
trigger, but the final branch decision is deferred to `FJ66`.

Allowed outcomes are:

- record an exact prior-art blocker object already supported by the
  repository;
- record a target-pause recommendation;
- record a target-pivot comparison object; or
- send the project to the `FJ66` branch checkpoint because no such object is
  present.

### Relevant modules

- FJ61
- FJ62
- FJ63
- FJ64
- WIP / provisional FJ53

### Dependencies

`ledgers/t001_candidate_inventory.md`, `ledgers/t001_residual.md`,
`ledgers/t001_kernel_recognition.md`, `ledgers/open_group_classes.md`, and
`OPEN_QUESTIONS.md`.

### Next action

Resolved by `FJ65`. Continue with `OQ-088` and `FJ66`.

## OQ-088. Should FJ66 pause T-001 or select a target-pivot comparison?

### Status

First-pass resolved by `FJ66`.

### Context

`FJ65` completes the prior-art / branch-readiness checkpoint after the
`FJ64` no-candidate note. It records no exact prior-art blocker object and no
prepared target-pivot comparison object. It does record a target-pause
trigger for `T-001`.

`FJ66` makes the branch decision explicit by pausing `T-001` as an active
proof-target sequence while keeping it unresolved in the archive.

Allowed outcomes are:

- pause `T-001` as an active proof-target sequence until new candidate data
  or an exact source payload appears;
- select a bounded target-pivot comparison packet;
- identify an exact repository object that justifies continuing `T-001`.

### Relevant modules

- FJ61
- FJ62
- FJ63
- FJ64
- FJ65
- WIP / provisional FJ53

### Dependencies

`ledgers/t001_candidate_inventory.md`, `ledgers/t001_residual.md`,
`ledgers/t001_kernel_recognition.md`, `ledgers/open_group_classes.md`, and
`PROJECT_CHARTER.md`.

### Next action

Resolved by `FJ66`. Continue with `OQ-089` and `FJ67`.

## OQ-089. What criteria should FJ67 use for target-pivot comparison?

### Status

First-pass resolved by `FJ67`.

### Context

`FJ66` pauses `T-001` as an active proof-target sequence because the current
repository contains no candidate-admissible row, exact source payload,
bridge, computation, prior-art blocker object, or target-pivot comparison
result that justifies continuing it.

`FJ67` does not choose a new target by inertia. It defines criteria for
comparing possible next active targets before a new target is selected.

Criteria should include:

- source-readiness;
- chance of candidate-level work;
- likelihood of producing a theorem, obstruction, or useful ledger update;
- risk of decorative bibliography;
- compatibility with the Farrell--Jones program.

`FJ67` records `OBL-PIVOT-001`: no new active target may be selected until a
target-pivot matrix records source-readiness, candidate-level object,
Farrell--Jones relevance, formulation-safety flags, known-route overlap,
prior-art risk, expected project output, stop condition, and explicit
decision.

### Relevant modules

- FJ61
- FJ62
- FJ63
- FJ64
- FJ65
- FJ66
- WIP / provisional FJ53

### Dependencies

`ledgers/open_group_classes.md`, `SCOPE_LEDGER.md`, `PROJECT_CHARTER.md`,
and `AGENTS.md`.

### Next action

Resolved by `FJ67`. Continue with `OQ-090` and `FJ68`.

## OQ-090. Which candidate target should FJ68 select under the FJ67 criteria?

### Status

First-pass resolved by `FJ68`.

### Context

`FJ67` defines target-pivot criteria but deliberately does not select a new
active target. The next module must apply those criteria to the possible
target inputs already recorded in the repository.

The first matrix should compare at least:

- Artin groups, using the `FJ18` / `ER-011` source-verified subclass ledger
  without claiming a global all-Artin result;
- automatic / biautomatic groups, currently only an open-class ledger input;
- Thompson-type groups, currently only an open-class ledger input;
- dormant `T-001`, only as a comparator unless `OBL-T001-013` explicitly
  reselects it.

The matrix must not become a source summary. It must either select one
bounded target packet or record that no target is ready.

`FJ68` applies the matrix and selects:

```text
A-001. Artin subclass-gap inventory after FJ18
```

Automatic / biautomatic groups and Thompson-type groups are deferred because
no exact source payload or bounded candidate object is recorded for them in
the current repository. Dormant `T-001` is not reactivated because
`OBL-T001-013` is not satisfied.

### Relevant modules

- FJ18
- FJ20
- FJ53, WIP / provisional
- FJ66
- FJ67

### Dependencies

`ledgers/open_group_classes.md`, `ledgers/known_classes.md`,
`ledgers/source_status.md`, `SCOPE_LEDGER.md`, `PROJECT_CHARTER.md`, and
`AGENTS.md`.

### Next action

Resolved by `FJ68`. Continue with `OQ-091` and `FJ69`.

## OQ-091. Can FJ69 produce an Artin subclass-gap inventory without source drift?

### Status

First-pass resolved by `FJ69`.

### Context

`FJ68` selects `A-001`, Artin subclass-gap inventory after `FJ18`, as the
bounded next target packet. The goal is not to prove a global Artin theorem
and not to start a broad Artin bibliography.

`FJ69` should compare existing repository records:

- the source-verified Artin rows in `FJ18`;
- the Artin rows in `ledgers/known_classes.md`;
- the Artin source-status rows in `ledgers/source_status.md`;
- the open Artin questions `OQ-021` and `OQ-023`;
- the source-label policy from `FJ02`.

The output should be an inventory of covered, gap, and deferred Artin
subclasses or route packets, with formulation flags preserved.

`FJ69` creates `ledgers/artin_subclass_gap_inventory.md`, completes
`OBL-ARTIN-001`, gives a first-pass current-repository answer to `OQ-021`,
sharpens `OQ-023`, and records `OBL-ARTIN-002`.

### Relevant modules

- FJ02
- FJ18
- FJ20
- FJ68

### Dependencies

`ledgers/known_classes.md`, `ledgers/open_group_classes.md`,
`ledgers/source_status.md`, `NOTATION_LEDGER.md`, and `AGENTS.md`.

### Next action

Resolved by `FJ69`. Continue with `OQ-092` and `FJ70`.

## OQ-092. Can FJ70 produce a Wu clique-reduction candidate from current Artin gap rows?

### Status

First-pass resolved by `FJ70` for the current repository state.

### Context

`FJ69` records `ART-GAP-003`, possible Wu clique-reduction target not already
covered by `FJ18`. The project has a source-verified Wu route row from
`FJ18`, but the current repository does not yet name a concrete noncovered
Artin graph or subclass whose clique subgroups are all covered.

`FJ70` was required to run a candidate filter, not a broad source survey.

Allowed outcomes:

- name a concrete candidate row from existing repository records;
- identify an exact source payload required before a candidate can be tested;
- record no current Wu-filter candidate.

`FJ70` records the third outcome. No current repository row names a
noncovered Artin graph, graph family, or subclass with the clique-subgroup
data required for a bounded Wu-filter candidate.

### Relevant modules

- FJ18
- FJ68
- FJ69
- FJ70

### Dependencies

`ledgers/artin_subclass_gap_inventory.md`, `ledgers/known_classes.md`,
`ledgers/open_group_classes.md`, and `ledgers/source_status.md`.

### Next action

Resolved by `FJ70`. Continue with `OQ-093` and `FJ71`.

## OQ-093. What branch decision should follow the no-current-Wu-candidate note?

### Status

First-pass resolved by `FJ71`.

### Context

`FJ70` completes the Wu clique-reduction candidate filter and records no
current candidate from existing Artin gap rows. The result is a
repository-state obstruction, not a theorem about Artin groups or Wu's
method.

`FJ71` makes the branch decision for the active Artin lane. The active Artin
proof/source lane is paused because the current repository has no named
graph, graph family, subclass, source theorem, bridge object, or changed
project row that could support a bounded continuation.

The pause is a repository-state decision, not a theorem about Artin groups.
It keeps `ART-GAP-001`, all Artin groups, unresolved inside the project.

The checked branch outcomes were:

- pause the active Artin packet until an exact source payload appears;
- select a bounded exact source-payload acquisition task with a named graph
  or subclass;
- return to target-pivot comparison using the `FJ67` criteria;
- identify a concrete repository object that changes the Artin inventory.

`FJ71` selects the pause branch and sends the project to a target-pivot
refresh.

### Relevant modules

- FJ18
- FJ68
- FJ69
- FJ70

### Dependencies

`ledgers/artin_subclass_gap_inventory.md`, `ledgers/open_group_classes.md`,
`ledgers/source_status.md`, and `OBL-ARTIN-003`.

### Next action

Resolved by `FJ71`. Continue with `OQ-094` and `FJ72`.

## OQ-094. Which target-pivot input should follow the Artin pause?

### Status

First-pass resolved by `FJ72`.

### Context

`FJ66` pauses `T-001` as an active proof-target sequence. `FJ71` now pauses
the active Artin proof/source lane. The project should not select another
target by inertia or begin source accumulation without a concrete repository
object.

`FJ72` reapplies the `FJ67` target-pivot criteria after the Artin pause.

The module records that no group-class target is currently ready for active
proof or source work:

- dormant `T-001` lacks the `OBL-T001-013` reactivation object;
- paused Artin groups lack the `OBL-ARTIN-004` reactivation payload;
- automatic / biautomatic groups lack a source-ready packet or bounded
  candidate object;
- Thompson-type groups lack a source-ready packet or bounded candidate
  object.

The selected next packet is the non-group packet `FND-001`, foundational
open-question triage after target pauses.

### Relevant modules

- FJ66
- FJ67
- FJ68
- FJ69
- FJ70
- FJ71
- FJ72

### Dependencies

`ledgers/open_group_classes.md`, `ledgers/artin_subclass_gap_inventory.md`,
`ledgers/t001_candidate_inventory.md`, `SCOPE_LEDGER.md`, and
`OBL-PIVOT-002`.

### Next action

Resolved by `FJ72`. Continue with `OQ-095` and `FJ73`.

## OQ-095. Which foundational blocker, if any, should be selected after the target pauses?

### Status

First-pass resolved by `FJ73`.

### Context

`FJ72` records that no group-class target is currently ready for active proof
or source work. The project still has many concrete foundational open
questions and theorem-dependency rows, but the next step must not become a
broad foundations survey.

`FJ73` compares existing foundational blockers and selects `OQ-005`, the
fixed-point convention issue for classifying spaces for families. The
selected next packet is `FND-002`, fixed-point convention cleanup for
classifying spaces.

Other foundational blockers remain deferred because they are source-heavy or
not currently tied to a proof-sensitive application.

### Relevant modules

- FJ02
- FJ03
- FJ12
- FJ15
- FJ17
- FJ67
- FJ72

### Dependencies

`OPEN_QUESTIONS.md`, `SCOPE_LEDGER.md`, `NOTATION_LEDGER.md`,
`ledgers/theorem_dependencies.md`, and `OBL-FND-001`.

### Next action

Resolved by `FJ73`. Continue with `OQ-005` and `FJ74`.

## OQ-096. Which foundational source-payload item, if any, should follow the OQ-006 no-promotion result?

### Status

Open inside project; selected by `FJ75` for `FJ76`.

### Context

`FJ75` records a no-promotion result for Farrell--Jones (1995), Lemma 2.5:
the DOI and metadata are checked, but the primary lemma text is not accessed.
The foundational queue should not drift into source accumulation merely
because one exact payload could not be promoted.

`FJ76` must decide whether another exact foundational source-payload item is
ready, or whether the foundational source queue should pause and return to
target-pivot comparison.

### Relevant modules

- FJ73
- FJ74
- FJ75

### Dependencies

`OPEN_QUESTIONS.md`, `SCOPE_LEDGER.md`, `NOTATION_LEDGER.md`,
`ledgers/source_status.md`, `ledgers/theorem_dependencies.md`, and
`OBL-FND-004`.

### Next action

Begin `FJ76`, Foundational Source-Queue Checkpoint After `OQ-006`
No-Promotion.
