# Open Questions

## OQ-001. Which unresolved group class should become the first serious target?

### Status

Open inside project.

### Context

The project needs a concrete target after foundational modules. Candidate classes include Artin groups and torsion-free one-relator groups, but their exact known/open status must be source-verified.

### Relevant modules

- FJ11
- FJ18
- FJ19
- FJ20

### Dependencies

Known-cases ledger and inheritance-properties ledger.

### Next action

`FJ18` has produced the Artin-group table. Defer final target selection
until `FJ19` has produced the one-relator group table and `FJ20` compares
the candidate targets.

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

`FJ18` has added Artin-group subclass rows. After `FJ19`, choose the
next known-case expansion based on which inheritance properties are most
useful for the target-selection module.

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

After `FJ19`, decide whether a second Artin-status module is worth
adding before target selection, or whether the current table is enough
for `FJ20`.

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

Do not pursue until after `FJ19` and `FJ20` decide whether the first
target should remain Artin-related or move to one-relator groups.
