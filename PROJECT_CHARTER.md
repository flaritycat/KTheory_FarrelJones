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
- Additive-category coefficients, under the first-pass convention recorded
  in `FJ02`.
- Known cases of Farrell--Jones.
- Inheritance properties.
- Consequences such as Whitehead group vanishing, projective class group consequences, and Borel-type rigidity, when their hypotheses are stated carefully.
- Candidate unresolved group classes, especially Artin groups and torsion-free one-relator groups, subject to source verification.

## Out-of-scope topics

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

## Standing assumptions

- \(R\) denotes an associative unital ring unless explicitly stated otherwise.
- \(G\) denotes a discrete group unless explicitly stated otherwise.
- A family of subgroups is closed under conjugation and passage to subgroups.
- The first working formulation was the simplified ring-coefficient version
  in `FJ01`.
- The first-pass additive-category formulation and source-convention policy
  are recorded in `FJ02`.
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

Current status: first-pass coverage has been completed for `FJ01`--`FJ07`.
Module `FJ02`, the additive-category formulation, was intentionally deferred
until cycle 003 and is now completed as the project's first-pass
source-convention module.

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

Current status: `FJ10` has first-pass coverage as a conditional Borel
theorem map. It imports \(L\)-theory only as a marked application
dependency and does not treat Borel rigidity as a K-theory-only result.

Current status: `FJ11` starts the known-classes ledger. It records
source-verified first-pass rows for hyperbolic groups,
finite-dimensional CAT(0)-groups, and virtually solvable groups,
separating K-theory, L-theory, and coefficient flags.

Current status: `FJ12` gives first-pass coverage of inheritance
properties. It separates coefficient K-theory pullback and subgroup
inheritance from survey-level closure properties of Lueck's full
\(\mathcal{FJ}\) class, and records the distinction in
`ledgers/inheritance_properties.md`.

## Third milestone

Proceed through modules `FJ13`--`FJ17`, developing proof-technology
orientation for the verified known cases:

1. hyperbolic groups case;
2. CAT(0)-groups case;
3. controlled topology primer;
4. flow spaces primer;
5. transfers primer.

Current status: `FJ13` has first-pass coverage as a proof-strategy map
for hyperbolic groups. It records the Bartels--Lueck--Reich main
theorem, the axiomatic reduction, and the Rips-complex verification,
while leaving obstruction categories, wide covers, and transfers for
the later proof-technology modules.

Current status: `FJ14`, the CAT(0)-groups case, has first-pass coverage
as a proof-strategy map. It records Wegner's K-theory theorem, the route
through strong transfer reducibility, the role of strong homotopy
actions and CAT(0) flow-space covers, and a comparison with the
hyperbolic proof skeleton from `FJ13`.

Current status: `FJ15`, the controlled topology primer, has first-pass
coverage as a controlled-algebra vocabulary bridge. It explains control
spaces, obstruction categories, controlled morphisms, the gain-control
strategy, and the reason the source proofs replace the point by metric
spaces. It explicitly leaves controlled h-cobordism and proof-level
obstruction-category vanishing outside the active scope.

Current status: `FJ16`, the flow spaces primer, has first-pass coverage.
It explains flows, flow spaces, open \(\mathcal F\)-covers, long
covers in the flow direction, hyperbolic equivariant covers, CAT(0)
flow-space covers, and the way flow spaces support gain-control
arguments. It records theorem routes but does not prove Mineyev flow
estimates or long-cover theorems internally.

Current status: `FJ17`, the transfers primer, has first-pass coverage.
It explains the transfer mechanism that moves obstruction-category
classes from the point into larger controlled spaces, records the
source-level transfer diagrams in the hyperbolic and CAT(0) proof
routes, and marks Waldhausen/Karoubi details, stability, and
obstruction-category vanishing as deferred proof dependencies.

## Fourth milestone

Proceed through modules `FJ18`--`FJ20`, turning the foundation and
proof-technology ledgers toward target selection:

1. Artin groups dossier;
2. one-relator groups dossier;
3. first target selection.

Current status: `FJ18`, the Artin groups dossier, has first-pass
coverage as a source-verified subclass ledger. It records FC-type Artin
groups, even FC-type Artin groups, right-angled Artin semidirect
products, Wu's even-Artin clique and join constructions, and Roushon's
listed finite real, complex, and affine types, always under the exact
source hypotheses. It does not claim the Farrell--Jones conjecture for
all Artin groups.

Current status: `FJ19`, the one-relator groups dossier, has first-pass
coverage as a source-verified status ledger. It records that the global
class of torsion-free one-relator groups remains unresolved inside the
project, because Lueck's 2025 survey lists it as open in general for
Full Farrell--Jones. It also records conditional positive routes through
hyperbolic, finite-dimensional CAT(0), virtually solvable, and
hyperbolic-by-cyclic classes, plus the structural local-indicability
theorem as non-Farrell--Jones input.

Current status: `FJ20`, first target selection, has first-pass coverage.
It selects `T-001`, torsion-free one-relator residual gap analysis, as
the first serious target for the next module cycle. Artin groups remain
important but are deferred because `FJ18` already records many positive
subclass rows and because proof-sensitive Artin work first requires
reconciling `FJCw`, `FICwF`, finite wreath products, and the project's
internal formulation.

Current procedural status: the `cycle_001` module list is now complete,
including the later `FJ02` source-convention interruption. The cycle
reflection has been written in `reflections/cycle_001_reflection.md`.

## Cycle 001 reflection

Current status: `reflections/cycle_001_reflection.md` closes the first
twenty-module cycle. Its main conclusion is that the next cycle should
begin with `T-001`, torsion-free one-relator residual gap analysis, and
that the first concrete step should be `FJ21`, one-relator structure
source selection.

The reflection recorded that `FJ02` remained deferred but not forgotten.
`FJ46` later made it urgent, and `FJ02` now supplies the first-pass
additive-category/source-convention policy for source-level coefficient
statements, finite-wreath-product variants, `FJCw`, and `FICwF`.

## Fifth milestone

Begin cycle 002 with modules `FJ21`--`FJ40`, guided by `T-001`.

The provisional cycle-002 plan is:

1. select a canonical one-relator structure source;
2. record the one-relator hierarchy vocabulary needed for reductions;
3. subtract known Farrell--Jones routes from the torsion-free one-relator
   class;
4. isolate any surviving subclass or example family;
5. decide whether the target supports a theorem, a conditional reduction,
   or a clearly labeled abandoned path.

Current status: `FJ21`, one-relator structure source selection, has
first-pass coverage. It selects Linton's `One-relator hierarchies` as
the primary modern hierarchy source for `T-001`, Linton's `Hyperbolic
one-relator groups` as a bridge source, and Linton--Nyberg-Brodda as an
orientation survey. It records Lyndon--Schupp and
Magnus--Karrass--Solitar as classical sources to verify before
proof-sensitive use.

Current status: `FJ22`, one-relator hierarchy vocabulary, has first-pass
coverage. It adopts Linton's finite one-relator complex hierarchy theorem
as the canonical hierarchy theorem for `T-001`, records the source-level
vocabulary of one-relator complexes, Magnus subgraphs, one-relator
towers, one-relator hierarchies, \(\mathbb Z\)-stable hierarchies,
quasi-convex hierarchies, and acylindrical hierarchies, and keeps the
result as a group-theoretic theorem map rather than a new Farrell--Jones
claim.

The next step after `FJ22` was `FJ23`, hyperbolic-route subtraction for
`T-001`. Its task was to combine the `ER-009` hyperbolic known-case row
with the one-relator hierarchy vocabulary from `FJ22`, while keeping any
virtual-special, CAT(0), and negative-immersion bridges source-checked
before use.

Current status: `FJ23`, hyperbolic-route subtraction for `T-001`, has
first-pass coverage. It records that torsion-free one-relator groups are
removed from the active residual target once the project has a
source-verified bridge to word-hyperbolicity. The module uses `ER-009`
and `FJ13` for the Farrell--Jones known case and uses `FJ22` only for
one-relator hierarchy bridges to hyperbolicity. It deliberately keeps
the hyperbolic-route residual conservative.

The next step after `FJ23` was `FJ24`, CAT(0)-route subtraction for
`T-001`. Its task was to determine which remaining one-relator groups
are removed by the finite-dimensional CAT(0) known-case row, and to
decide whether any virtual-special consequence from the one-relator
hierarchy sources can be used only after a source-verified bridge to the
project's CAT(0) known-case hypotheses.

Current status: `FJ24`, CAT(0)-route subtraction for `T-001`, has
first-pass coverage. It records that torsion-free one-relator groups are
removed from the active residual target once the project has a
source-verified bridge to a proper cocompact isometric action on a
finite-dimensional CAT(0)-space. It also records compact
finite-dimensional special cube complex groups as CAT(0)-route bridge
cases, while keeping merely virtual-special statements conditional until
finite-index handling is sourced.

The next step after `FJ24` was `FJ25`, virtually solvable route
subtraction for `T-001`. Its task was to determine which remaining
one-relator groups are removed by the virtually solvable known-case row,
without treating local indicability, nontrivial abelianization, or
one-relator HNN hierarchy data as a virtual-solvability proof.

Current status: `FJ25`, virtually solvable route subtraction for
`T-001`, has first-pass coverage. It records that torsion-free
one-relator groups are removed from the active residual target once the
project has a source-verified bridge to virtual solvability. It also
records that local indicability, abelianization data, and one-relator
hierarchy structure are not virtual-solvability certificates.

The next step after `FJ25` was `FJ26`,
hyperbolic-by-cyclic/free-by-cyclic route subtraction for `T-001`. Its
task was to determine which remaining one-relator groups are removed by
the Bestvina--Fujiwara--Wigglesworth known-case row and related
free-by-cyclic bridge data, without using an HNN splitting or an
epimorphism to \(\mathbb Z\) as a mapping-torus proof unless the
required hypotheses are source-verified.

Current status: `FJ26`, hyperbolic-by-cyclic/free-by-cyclic route
subtraction for `T-001`, has first-pass coverage. It records that
torsion-free one-relator groups are removed from the active residual
target once the project has a source-verified bridge to
\(H\rtimes_\Phi\mathbb Z\) with \(H\) virtually torsion-free hyperbolic,
or to a finite-rank free-by-cyclic group. It also records that bare HNN
splittings, epimorphisms to \(\mathbb Z\), and hierarchy data are not
mapping-torus certificates by themselves.

The next step after `FJ26` was `FJ27`, source-verified
inheritance-route subtraction for `T-001`. Its task was to decide which
remaining one-relator cases can be removed by the inheritance rows
already recorded in `FJ12`, while keeping version flags separate
between coefficient K-theory rows and Lueck's full \(\mathcal{FJ}\)
survey class.

Current status: `FJ27`, source-verified inheritance-route subtraction
for `T-001`, has first-pass coverage. It records that inheritance rows
subtract a torsion-free one-relator group only when the project has an
inheritance bridge matching the exact source hypotheses and preserving
the version flag. It keeps coefficient K-theory inheritance rows,
K-theory directed-colimit rows, and full \(\mathcal{FJ}\) survey rows
separate.

The next step after `FJ27` was `FJ28`, residual ledger after named and
inheritance route subtractions for `T-001`. Its task was to assemble the
conservative remaining attack surface after `FJ23`--`FJ27`, without
reclassifying groups as unsolved merely because the project has not yet
recorded a bridge.

Current status: `FJ28`, residual ledger after named and inheritance
route subtractions for `T-001`, has first-pass coverage. It creates
`ledgers/t001_residual.md`, records the cases removed by the named
routes and version-aware inheritance rows, and organizes the unremoved
project-state residual into source-recognition buckets. It explicitly
records that the residual is not a class of counterexamples or negative
Farrell--Jones results.

The next step after `FJ28` was `FJ29`, concrete residual attack-surface
selection for `T-001`. Its task was to choose one residual bucket from
`FJ28` for the next source-verification or reduction attempt, with
finite-rank free-kernel recognition, finite-index/virtually compact
special handling, compact-special/CAT(0) cases beyond hyperbolicity,
virtually solvable recognition, and hierarchy-to-route extraction as
candidate directions.

Current status: `FJ29`, residual attack-surface selection for `T-001`,
has first-pass coverage. It selects `RB-004`, finite-rank
free-kernel recognition for epimorphisms to \(\mathbb Z\), as the next
attack surface because it feeds directly into the `FJ26`
finite-rank free-by-cyclic route if the kernel bridge is verified. It
selects Brown (1987) as the first source to verify, without upgrading
Brown to theorem-use status.

The next step after `FJ29` was `FJ30`, Brown/BNS kernel-recognition
verification for `T-001`. Its task was to check Brown (1987) for exact
hypotheses and conclusions about one-relator epimorphisms, BNS data,
finitely generated kernels, and finite-rank free-kernel bridges.

Current status: `FJ30`, Brown/BNS kernel-recognition verification for
`T-001`, has first-pass coverage. It verifies Brown's Proposition 3.1,
Corollary 3.2, and Theorems 4.2--4.4 as a source-checked kernel
recognition tool for selected `RB-004` cases. The output is limited:
Brown gives a computable criterion for two-generator one-relator
presentations, not a global theorem that all one-relator epimorphisms to
\(\mathbb Z\) have finitely generated kernel.

The next step after `FJ30` was `FJ31`, first Brown criterion test case
for `T-001`. Its task was to choose a concrete two-generator
one-relator presentation or small test family and apply the Brown
criterion carefully enough to decide whether it supplies a finite-rank
free-by-cyclic bridge into `FJ26`.

Current status: `FJ31` has first-pass coverage as a Brown criterion
calibration example. It tests
\(\langle x,y\mid xyx^{-1}y^{-1}\rangle\) with
\(\chi(x)=1\) and \(\chi(y)=0\), verifies Brown's maximum-count
condition for both \([\chi]\) and \([-\chi]\), identifies
\(\ker(\chi)\cong F_1\), and records the split
finite-rank free-by-cyclic bridge. It also records that the example is
already covered by the virtually solvable route, so it is not a new
residual removal.

The next step after `FJ31` was `FJ32`, nontrivial Brown test-family
selection for `T-001`. Its task was to choose a Brown-compatible
two-generator one-relator example or small family that is less
redundant than the abelian calibration case, preferably one not already
removed by the virtually solvable route.

Current status: `FJ32` has first-pass coverage as a nontrivial Brown
test-family selection module. It selects
\[
G_{2,3}=\langle x,y\mid x^2y^{-3}\rangle
\]
with \(\chi(x)=3\) and \(\chi(y)=2\) as the next worked Brown case. The
module verifies internally that the selected presentation is nonabelian
by mapping onto \(S_3\), and it records a preliminary maximum-count
computation indicating that both \([\chi]\) and \([-\chi]\) pass the
Brown test. It does not yet record a finite-rank free-kernel bridge or a
new residual subtraction.

The next step after `FJ32` was `FJ33`, worked Brown test for the
selected \(G_{2,3}\) presentation. Its task was to turn the preliminary
`FJ32` selection into a full route-checking module: verify the Brown
test, decide what can be concluded about \(\ker(\chi)\), and determine
what additional proof or citation is needed before the `FJ26`
finite-rank free-by-cyclic route can be used.

Current status: `FJ33` has first-pass coverage as a worked Brown test
and route-bridge module. It verifies Brown's maximum-count test for
\(G_{2,3}\), changes presentation to \(\langle a,b\mid aba=bab\rangle\),
then rewrites the group as
\[
F(p,q)\rtimes_\varphi\mathbb Z,\qquad
\varphi(p)=q,\quad \varphi(q)=p^{-1}q.
\]
Thus \(\ker(\chi)\cong F_2\), and the concrete group is removed from the
active `T-001` residual by the finite-rank free-by-cyclic route from
`FJ26`. This is a single example bridge, not a theorem for all
two-generator one-relator groups.

The next step after `FJ33` was `FJ34`, nearby Brown family
generalization. Its task was to test how much of the \(G_{2,3}\) bridge
extends to presentations of the form
\(\langle x,y\mid x^p y^{-q}\rangle\), while avoiding any unverified
torus-knot or one-relator classification claims.

Current status: `FJ34` has first-pass coverage as a conservative family
boundary module. For \(p,q\geq2\) with \(\gcd(p,q)=1\), it defines
\[
G_{p,q}=\langle x,y\mid x^p y^{-q}\rangle,\qquad
\chi_{p,q}(x)=q,\quad \chi_{p,q}(y)=p,
\]
and verifies Brown's maximum-count condition for both \([\chi_{p,q}]\)
and \([-\chi_{p,q}]\). Brown therefore gives finite generation of
\(\ker(\chi_{p,q})\). The module does not record a family-level
finite-rank free-kernel bridge, so the `FJ26` route is not invoked for
the full \(G_{p,q}\)-family.

The next step after `FJ34` was `FJ35`, kernel bridge source selection for
the \(G_{p,q}\)-family. It records
\[
K_{p,q}=\ker(\chi_{p,q})
\]
and identifies a conservative route from Brown finite generation to
finite-rank freeness: view
\[
G_{p,q}\cong \langle x\rangle *_{\langle z\rangle}\langle y\rangle
\]
with \(z\mapsto x^p\) and \(z\mapsto y^q\), then verify through
Bass--Serre theory that a subgroup intersecting all conjugates of the
vertex groups trivially is free. The character \(\chi_{p,q}\) is nonzero
on every nontrivial element of those cyclic vertex groups, so
\(K_{p,q}\) has the required trivial-intersection property.

At the `FJ35` stage, Serre's *Trees*, especially "Trees and Amalgams," was
selected as the source to verify for the Bass--Serre freeness bridge. That
module deliberately did not use torus-knot or fibered-knot classification
claims, and it did not yet remove the full \(G_{p,q}\)-family through
`FJ26`.

The next step after `FJ35` was `FJ36`, Bass--Serre source verification
for the \(G_{p,q}\)-family kernel bridge. It verifies the needed
Bass--Serre freeness bridge using Serre's *Trees* as the canonical
reference, with auxiliary accessible source checks for the graph-of-groups
stabilizer formulation and the theorem that a group acting freely on a
tree is free.

Current status: `FJ36` promotes the conditional `FJ35` bridge. The cyclic
amalgam
\[
G_{p,q}\cong \langle x\rangle *_{\langle z\rangle}\langle y\rangle,
\qquad z\mapsto x^p,\quad z\mapsto y^q
\]
has a Bass--Serre tree whose vertex stabilizers are conjugates of the two
cyclic factors. Since \(K_{p,q}=\ker(\chi_{p,q})\) intersects all those
conjugates trivially, it acts freely on the tree and is free. Brown
finite generation from `FJ34` then makes \(K_{p,q}\cong F_n\) for some
finite \(n\). The epimorphism to \(\mathbb Z\) splits, so
\[
G_{p,q}\cong F_n\rtimes\mathbb Z.
\]
Therefore the \(G_{p,q}\)-family is removed from the active `T-001`
residual by the finite-rank free-by-cyclic route in `FJ26`.

The next step after `FJ36` was `FJ37`, post-\(G_{p,q}\) residual audit
and next target selection. It checks that the exact rank of \(K_{p,q}\)
is not needed for the active `FJ26` route, because `FJ36` already proves
finite rank. It also records that the \(G_{p,q}\)-family bridge does not
exhaust `RB-004`: Brown's checked source route remains limited to
compatible two-generator one-relator presentations.

Current status: `FJ37` defers the exact-rank computation for \(K_{p,q}\)
and selects `OQ-044` as the next active target. The next step after `FJ37`
was `FJ38`, `RB-004` beyond-Brown source selection. Its task was to identify
the next source or source cluster for kernel-recognition cases outside
Brown's checked two-generator criterion, without using any unverified theorem
as route input.

Current status: `FJ38` has first-pass coverage as a source-selection module.
It selects the Bieri--Neumann--Strebel, Bieri--Renz, Bieri, and
Karrass--Solitar normal-subgroup source cluster for `RB-004` beyond Brown's
checked two-generator one-relator criterion. Friedl--Tillmann and Kielak are
recorded as background or possible later sources, not as the immediate
beyond-Brown route. This selection led to `FJ39`, normal-subgroup bridge
source verification for `RB-004`, whose task was to check exact theorem
statements and exact finiteness hypotheses before any route subtraction.

The next step after `FJ38` was `FJ39`, normal-subgroup bridge source
verification for `RB-004`. Its task was to determine which part of the
selected source cluster can actually be used as a theorem source, and whether
the needed hypothesis is finite generation, finite presentation,
\(\mathrm{FP}_2\), or another finiteness condition.

Current status: `FJ39` has first-pass coverage as a source-verification
module. It verifies Karrass--Solitar (1978) as a narrow but genuine
finitely presented normal-subgroup bridge: a one-relator group with a
nontrivial finitely presented normal subgroup of infinite index is an
infinite cyclic or infinite dihedral extension of a finitely generated free
group, with the relation between the subgroup and the free kernel specified
in the source. This does not apply to kernels known only to be finitely
generated. BNS remains selected for direct theorem verification, Bieri--Renz
remains higher-finiteness context, and Bieri (1976) is recorded only as a
dependency cited by Karrass--Solitar until the primary text is checked. The
next module is `FJ40`, finitely presented-kernel test selection for `RB-004`.

The next step after `FJ39` was `FJ40`, finitely presented-kernel test
selection for `RB-004`. Its task was to decide whether the repository already
contains a non-Brown one-relator test case with a source-ready nontrivial
finitely presented normal subgroup of infinite index.

Current status: `FJ40` completes the twentieth module of cycle 002. It audits
the commutator calibration example, \(G_{2,3}\), and the \(G_{p,q}\)-family.
All source-ready finitely presented kernels currently recorded in the
repository are already calibration cases or already removed through the
`FJ26` finite-rank free-by-cyclic route. `FJ40` therefore does not select a
new non-Brown `RB-004` test case and does not remove a residual bucket. It
records the Karrass--Solitar bridge as a cleanup theorem to use only after a
finite-presentation input is verified. This led to the cycle-002 reflection
before any `FJ41` module work.

## Cycle 002 reflection

Current status: `reflections/cycle_002_reflection.md` closes the second
twenty-module cycle. Its main conclusion is that cycle 002 produced a
source-disciplined one-relator residual ledger, a concrete \(G_{p,q}\)-family
route subtraction, and a clear beyond-Brown source gap.

The reflection keeps `T-001` active and selects `FJ41`, direct
Bieri--Neumann--Strebel theorem verification for `RB-004`, as the first
module of cycle 003. The goal is to verify the original theorem statement and
exact hypotheses before using BNS beyond Brown's checked two-generator
criterion.

## Sixth milestone

Begin cycle 003 with modules `FJ41`--`FJ60`, guided by `T-001` and the
cycle-002 reflection.

The provisional cycle-003 plan is:

1. verify the original Bieri--Neumann--Strebel theorem statement for direct
   `RB-004` use;
2. check Bieri (1976) and Bieri--Renz (1988) only if their exact finiteness
   hypotheses become route-relevant;
3. handle the Karrass--Solitar infinite-dihedral alternative only after the
   needed finite-index and inheritance formulation is checked;
4. select a new concrete beyond-Brown candidate only after the source
   hypotheses are verified;
5. interrupt for `FJ02` if source-level coefficient, finite-wreath-product,
   `FJCw`, or `FICwF` formulations become proof-level inputs.

Current status: `FJ41` has first-pass coverage as direct
Bieri--Neumann--Strebel theorem verification for `RB-004`. It checks Theorem
B1 from Bieri--Neumann--Strebel (1987): for finitely generated \(G\) and
normal \(N\trianglelefteq G\) with \(G/N\) abelian, finite generation of
\(N\) is equivalent to \(S(G,N)\subseteq\Sigma(G)\). For a surjection
\(G\to\mathbb Z\), this becomes the two-sided \([\chi]\), \([-\chi]\)
criterion. The module does not compute \(\Sigma(G)\) for a new one-relator
family, does not prove freeness or finite rank of a kernel, and makes no
residual subtraction.

Current status: `FJ42` has first-pass coverage as Bieri source-access and
route-delta verification. It checks Bieri (1976) bibliographic and
ScienceDirect/Elsevier metadata, but the primary theorem text was not
directly extractable in this environment. Therefore no Bieri theorem is
promoted to source-verified theorem use. Comparison sources indicate that
the visible Bieri hypotheses remain finite presentation or type \(VFP\), not
mere finite generation, so `FJ42` records no residual subtraction.

Current status: `FJ43` has first-pass coverage as the route-delta checkpoint
for the BNS/Bieri/Karrass--Solitar source cluster. It records that the
cluster has produced useful route boundaries, but no new candidate-ready
route: Karrass--Solitar remains a finitely presented normal-subgroup cleanup
bridge, direct BNS still needs a \(\Sigma(G)\)-membership computation, Bieri
is not source-verified for theorem use, and Bieri--Renz is not yet attached
to a concrete higher-finiteness need.

The route decision after `FJ43` is to pause automatic `RB-004` source-cluster
continuation. This does not abandon `RB-004`; it prevents a fourth
source-only continuation without a candidate, bridge, or subtraction target.

Current status: `FJ44` has first-pass coverage as residual-bucket comparison
and attack-packet selection after the `RB-004` source-cluster pause. It
selects `RB-005`, finite-index and virtually compact special formulation
handling, because that bucket is already tied to concrete cautions from
`FJ24`, `FJ27`, and the Karrass--Solitar infinite-dihedral cleanup issue.

The route decision after `FJ44` is to test the finite-index formulation
bridge before using any virtual-special or dihedral finite-index route
proof-sensitively. This does not subtract a residual case. It makes the next
obstruction precise: either the project has a version-compatible finite-index
bridge, or `FJ02`/source-convention debt becomes active.

The next step after `FJ44` was `FJ45`, finite-index formulation bridge
checkpoint for `RB-005`.

Current status: `FJ45` has first-pass coverage as the finite-index
formulation bridge checkpoint for `RB-005`. It records that the only
finite-index overgroup bridge currently licensed by the repository is the
full \(\mathcal{FJ}\) survey-level row from Lueck's source-status entry:
if \(H\leq G\) has finite index and \(H\in\mathcal{FJ}\), then
\(G\in\mathcal{FJ}\). The checkpoint does not promote a coefficient
K-theory finite-index overgroup theorem, a direct CAT(0) finite-extension
theorem, or an `FJCw`/`FICwF` comparison to project use.

The route decision after `FJ45` is deliberately narrow. Full
\(\mathcal{FJ}\)-level finite-index inferences may be recorded only when
the finite-index subgroup is itself recorded in full \(\mathcal{FJ}\).
Virtual-special and Karrass--Solitar infinite-dihedral cases remain blocked
for coefficient-route use until a version-compatible finite-index bridge is
source-verified or the source-convention debt around `FJ02` is addressed.

The next step after `FJ45` was `FJ46`: decide whether `RB-005` should proceed
by verifying a coefficient K-theory finite-index source, or by interrupting
the current one-relator route for `FJ02`/source-convention reconciliation.

Current status: `FJ46` has first-pass coverage as the source-convention
decision for `RB-005`. It selects the interruption route: the project should
begin the deferred `FJ02` additive-category/source-convention module before
any further proof-sensitive `RB-005` use. This is because `FJ45` made
coefficient K-theory, full \(\mathcal{FJ}\), CAT(0)-route, `FJCw`, and
`FICwF` distinctions into active proof-level inputs.

The route decision after `FJ46` is that a narrow coefficient finite-index
source search is not the immediate next step. Even a positive coefficient
finite-index theorem would not by itself reconcile the project's source
labels. `FJ02` should now provide the minimum additive-category formulation,
source-label comparison policy, and route-use rule needed before `RB-005`
resumes.

The historical next step after `FJ46` was to interrupt cycle 003 and begin
`FJ02`.

Current status: `FJ02` has first-pass coverage as the additive-category and
source-convention formulation module. It adopts Bartels--Reich Conjecture
3.2 as the project's canonical coefficient K-theory Farrell--Jones
formulation for now: additive categories with right \(G\)-action,
\(\mathcal A *_G T\), the Or\(G\)-spectrum \(K_{\mathcal A}\), and the
assembly map over \(E_{\mathcal{VCyc}}G\). It also records the policy that
coefficient K-theory FJC, full \(\mathcal{FJ}\), `FJCw`, `FICwF`, and the
simplified ring-coefficient statement remain distinct unless a source
comparison is checked.

The route decision after `FJ02` was to return to `RB-005` with the source
labels now under control. The historical next step was `FJ47`, a coefficient
finite-index bridge source-selection module under the `FJ02` convention.

Current status: `FJ47` has first-pass coverage as the finite-index bridge
source-selection module after `FJ02`. It verifies a usable finite-index
overgroup bridge for the finite-wreath-product version `FJCw`, using
Bartels--Lueck--Reich--Rueping Remark 6.2, and records Wang's finite-index
paper as evidence that plain coefficient K-theory finite-index closure is
not imported as an unconditional theorem.

The route decision after `FJ47` is version-preserving: if a finite-index
subgroup has source-verified `FJCw`, then the ambient group may be routed
through `FJCw` and hence through coefficient K-theory under the `FJ02`
convention. A plain coefficient K-theory statement for the subgroup still
does not by itself pass to the ambient group inside this project.

The historical next step after `FJ47` was `FJ48`, an `RB-005` application
audit: identify which virtual-special or finite-index cleanup cases actually
have the `FJCw` subgroup input required by `FJ47`.

Current status: `FJ48` has first-pass coverage as the `RB-005` `FJCw`
application audit. It records that the current `T-001` finite-index cleanup
cases are not `FJCw-ready`: the virtual compact special path has
compact-special/CAT(0) subgroup input, and the Karrass--Solitar
infinite-dihedral path has at most a finite-rank free-by-cyclic coefficient
route if a concrete candidate is selected. Neither is recorded with the
finite-wreath-product source label required by `FJ47`.

The route decision after `FJ48` is negative but useful: do not apply the
`FJ47` bridge to the current `T-001` residual. The next concrete obstruction
is not another abstract `FJCw` inventory; it is whether the virtual compact
special case can be routed directly through finite-dimensional CAT(0)-group
closure under finite extensions.

The historical next step after `FJ48` was `FJ49`, a source check for a
direct finite-extension bridge for finite-dimensional CAT(0)-groups.

Current status: `FJ49` has first-pass coverage as the direct CAT(0)
finite-extension bridge check for `RB-005`. It checks Ruane's CAT(0)-group
question source and records that finite-index subgroups of CAT(0)-groups are
easy, but finite extensions are posed as a question. The available product
construction gives a proper isometric action on a finite product of CAT(0)
spaces, but it does not supply the cocompact geometric action needed by the
`FJ14`/`FJ24` route.

The route decision after `FJ49` is to keep the virtual compact special case
blocked in the direct CAT(0) lane. After `FJ47`, `FJ48`, and `FJ49`,
`RB-005` has produced useful source discipline but no residual subtraction.

The historical next step after `FJ49` was `FJ50`, an `RB-005` route-delta
checkpoint and pivot decision: decide whether to pause `RB-005` and select
the next attack packet.

Current status: `FJ50` has first-pass coverage as the `RB-005` route-delta
checkpoint. It records that `RB-005` produced useful formulation control but
no `T-001` residual subtraction: the full \(\mathcal{FJ}\) lane is too
narrow for the current cases, the `FJCw` bridge has no current `T-001`
application, and the direct CAT(0) finite-extension lane is blocked by
`FJ49`.

The route decision after `FJ50` is to pause `RB-005` as the immediate attack
packet. This is not a mathematical negative result; it is a governance
decision that another finite-index source check now needs a new concrete
candidate or named bridge.

The historical next step after `FJ50` was `FJ51`, an `RB-006`
compact-special/CAT(0)-looking source-selection and attack-packet module.
Its job was to determine whether there is a bounded one-relator cubulation,
specialness, or CAT(0)-recognition source to check without duplicating the
hyperbolic route or reopening the finite-index shortcut blocked in `FJ49`.

Current status: `FJ51` has first-pass coverage as the `RB-006`
source-selection and attack-packet module. It does not import a new theorem.
It selects Louder--Wilton's negative-immersion source only as a boundary
check: the next module must determine whether that source gives any compact
special or CAT(0) route delta beyond the hyperbolic route already governed by
`FJ23`.

The route decision after `FJ51` is intentionally narrow. Do not begin a broad
cubulation literature survey. Check Louder--Wilton once for exact hypotheses,
route output, and overlap with `FJ23`. If the output is only hyperbolic-route
input, record the overlap and pause this `RB-006` path rather than drifting
into adjacent sources.

The historical next step after `FJ51` was `FJ52`, a Louder--Wilton
negative-immersion boundary check for `RB-006`.

Current status: `FJ52` has first-pass coverage as the Louder--Wilton
negative-immersion boundary check. It verifies that Louder--Wilton supplies
the primitivity-rank/negative-immersion bridge and subgroup-structure
consequences, but not a compact-special, virtually compact special, direct
CAT(0), or hyperbolicity theorem. Hyperbolicity of negative-immersion
one-relator groups belongs to the Linton source row already recorded in
`FJ22`.

The route decision after `FJ52` is that Louder--Wilton does not give an
independent `RB-006` compact-special/CAT(0) route delta. Its useful project
role is hyperbolic-route overlap: paired with Linton's negative-immersion
theorem, the condition \(\pi(w)>2\) may feed the `FJ23` hyperbolic route, but
that should be recorded as hyperbolic overlap rather than as new `RB-006`
progress.

The historical next step after `FJ52` was `FJ53`, a \(\pi(w)>2\)
hyperbolic-overlap checkpoint.

Current status: `FJ53` is WIP / provisional as the \(\pi(w)>2\)
hyperbolic-overlap checkpoint. It records the source chain
\(\pi(w)>2\Rightarrow\) negative immersions \(\Rightarrow\) hyperbolicity
\(\Rightarrow\) the `FJ23` hyperbolic route, but it does not finalize an
independent `RB-006` compact-special/CAT(0) closure. It makes no concrete
residual subtraction.

The route decision after `FJ53` is to demote the Louder--Wilton `RB-006` path
as provisionally non-subtractive. Louder--Wilton remains useful for the
recorded hyperbolic-overlap criterion, but the project should not continue
the same source lane unless a genuinely non-hyperbolic CAT(0),
compact-special, or FJ bridge is selected.

The historical next step after `FJ53` was `FJ54`, a residual-bucket
checkpoint after the demoted Louder--Wilton `RB-006` path.

Current status: `FJ54` has first-pass coverage as the post-`RB-006`
residual-bucket checkpoint. It records the full `RB-001`--`RB-008` table,
demotes `RB-006` pending a genuinely non-hyperbolic bridge, and selects the
`RB-003` + `RB-004`/`RB-008` hybrid as the next primary attack packet. It
makes no residual subtraction and does not close the `T-001` target.

The route decision after `FJ54` is to test whether primitive-extension /
hierarchy data can be converted into an FJ route, candidate family, bridge
lemma, or documented obstruction when paired with explicit kernel-control
work.

Current status: `FJ55` has first-pass coverage as the Primitive-Extension /
Hierarchy-to-FJ Bridge Test. It records that hierarchy existence, HNN
structure, and primitive-extension shorthand are not direct Farrell--Jones
routes in the current repository. Their project use must pass through an
approved route output: hyperbolicity, finite-dimensional CAT(0), virtual
solvability, finite-rank free or hyperbolic kernel extension, or
version-safe inheritance.

The route decision after `FJ55` is to stop the hierarchy-only lane and move
to explicit kernel-control candidate inventory. The module creates
`OBL-T001-001` and `OBL-T001-002` in
`ledgers/t001_candidate_inventory.md` and makes no residual subtraction.

Current status: `FJ56` has first-pass coverage as the Kernel-Control
Candidate Inventory. It audits the repository-supported candidate rows for
the selected `RB-003` + `RB-004`/`RB-008` hybrid packet. The commutator
calibration row, \(G_{2,3}\), and the \(G_{p,q}\)-family all have explicit
kernel-control data, but they are calibration-only or already removed through
the `FJ26` finite-rank free-by-cyclic route.

The route decision after `FJ56` is that there is no live non-routed
kernel-control candidate in the current inventory. The module creates
`OBL-T001-003` in `ledgers/t001_candidate_inventory.md` and makes no residual
subtraction.

Current status: `FJ57` has first-pass coverage as the Candidate Family Proof
Attempt or Obstruction Record. It tries to promote a repository-supported
non-routed candidate for the selected hybrid packet and records that no such
candidate is currently available. The named rows are calibration-only or
already routed, and the remaining residual lanes lack the presentation,
route-output target, kernel data, or prior-art comparison required by the
candidate intake checklist.

The route decision after `FJ57` is to close the current `RB-003` +
`RB-004`/`RB-008` hybrid packet as blocked, not abandoned. The module creates
`OBL-T001-004` in `ledgers/t001_candidate_inventory.md` and makes no residual
subtraction.

Current status: `FJ58` has first-pass coverage as the Post-Hybrid
Candidate-Production Checkpoint. It audits the plausible replacement lanes
after the blocked hybrid packet and records that none is presently
candidate-ready as a proof-attempt lane: `RB-004` remains paused without a new
candidate or BNS computation, `RB-005` remains paused without an application
case, WIP / provisional `RB-006` remains hyperbolic-overlap only, and
`RB-007` remains a recognition bucket without a selected family.

The route decision after `FJ58` is to record `OBL-T001-005`: no active
candidate-production lane is currently ready for `T-001`. This is not a
mathematical nonexistence theorem and not a retreat from `T-001`; it is a
stop condition against fabricated proof attempts.

Current status: `FJ59` has first-pass coverage as the Weaker \(K_0\) /
Cohen--Lyndon Consequence Intake Gate. It separates the already recorded
conditional \(K_0\)-level consequence from `FJ08` and `FJ09` from any new
weaker theorem claim. It records that the repository has no current
Cohen--Lyndon-style source payload: no exact source theorem, hypotheses,
formulation level, or project object changed by such a theorem has been
recorded.

The route decision after `FJ59` is to record `OBL-T001-006`: no weaker
\(K_0\) / Cohen--Lyndon source payload is currently available for `T-001`.
The lane may continue only as a bounded source-payload selection, not as a
proof attempt or residual subtraction.

Current status: `FJ60` has first-pass coverage as Weaker Consequence
Source-Payload Selection. It checks the repository's bibliography, source
status ledger, and candidate inventory for an exact weaker \(K_0\) /
Cohen--Lyndon payload. No payload is available for selection: the existing
\(K_0\)-level statements remain conditional on Farrell--Jones, and the
classical one-relator sources are still only located or queued for later
verification in this lane.

The route decision after `FJ60` is to record `OBL-T001-007`: the weaker
\(K_0\) / Cohen--Lyndon consequence lane is inactive until a future module
names an exact source, theorem statement, hypotheses, formulation level, and
project object changed. This makes no residual subtraction and does not
resolve `OQ-024`.

`FJ60` closes the module portion of cycle 003. At that point, the next step
was `reflections/cycle_003_reflection.md`.

## Cycle 003 reflection

Current status: `reflections/cycle_003_reflection.md` closes the third
numbered module cycle. Its main conclusion is that cycle 003 produced useful
route boundaries and formulation control, but no new live non-routed
candidate after the earlier \(G_{p,q}\)-family route.

The reflection keeps `FJ53` WIP / provisional, keeps `T-001` unresolved, and
records that `T-001` is not currently candidate-ready. The weaker
\(K_0\) / Cohen--Lyndon consequence lane remains inactive under
`OBL-T001-007` until an exact source payload is named.

The reflection selects `FJ61`, T-001 Candidate-Intake Reset and Exit
Criteria, as the first move of cycle 004. The purpose of `FJ61` is not to
verify another source. It must define the candidate-intake and exit criteria
that decide whether `T-001` continues as an active proof-target cycle, pauses
pending new candidate data, or pivots to another target comparison.

## Seventh milestone

Begin cycle 004 with modules `FJ61`--`FJ80`, guided by the cycle-003
reflection.

The provisional cycle-004 posture is:

1. do not begin with another external source summary;
2. consolidate active `T-001` blockers and proof obligations;
3. define what counts as a legitimate new candidate row;
4. require route-output, formulation-safety, and prior-art fields before a
   candidate can drive proof work;
5. pause or pivot from `T-001` if the project cannot name a candidate,
   bridge, computation, or exact source payload within the early cycle.

At this point, the next step was `FJ61`, T-001 Candidate-Intake Reset and
Exit Criteria.

## FJ61 candidate-intake reset

Current status: `FJ61` has first-pass coverage as the T-001
Candidate-Intake Reset and Exit Criteria module. It defines a
candidate-admissible row, allowed route-output targets, and early cycle-004
exit criteria. It records `OBL-T001-008`, the candidate-intake gate for
`T-001`.

The route decision after `FJ61` is to keep `T-001` active only through
bounded intake governance. No proof attempt, source verification, or route
subtraction should begin unless it identifies a candidate-admissible row or
an exact bridge, computation, source payload, prior-art blocker, target
pause, or target-pivot comparison.

At this point, the next step was `FJ62`, Active Blocker Pruning for `T-001`.

## FJ62 active blocker pruning

Current status: `FJ62` has first-pass coverage as the Active Blocker Pruning
module for `T-001`. It sorts accumulated blockers into active
candidate-intake blockers, deferred foundations, historical trail markers,
and possible pivot-comparison inputs.

The route decision after `FJ62` is that only three blocker classes remain
active for the next module: candidate-object acquisition, route-data
acquisition, and the branch decision about whether acquisition succeeds. The
module records `OBL-T001-009`, requiring `FJ63` to select exactly one
data-acquisition packet or record failure to do so.

At this point, the next step was `FJ63`, Candidate-Data Acquisition Packet.

## FJ63 candidate-data acquisition packet

Current status: `FJ63` has first-pass coverage as the Candidate-Data
Acquisition Packet module. It compares the allowed packet types from `FJ62`
and selects exactly one: `DAP-T001-001`, candidate-row acquisition from
current repository records.

The route decision after `FJ63` is that `FJ64` must execute this packet. It
must either add one candidate-admissible row to
`ledgers/t001_candidate_inventory.md` or record a no-candidate note. It must
not select a new external source, bridge, computation, or target pivot unless
the candidate-row packet itself produces the required object.

At this point, the next step was `FJ64`, Candidate Intake Attempt or
No-Candidate Note.

## FJ64 candidate intake attempt

Current status: `FJ64` has first-pass coverage as the Candidate Intake
Attempt or No-Candidate Note module. It executes `DAP-T001-001` against the
current candidate inventory, residual ledger, kernel-recognition ledger, open
group classes ledger, and open questions.

The route decision after `FJ64` is a no-candidate note: no current repository
row can be promoted to a candidate-admissible row without importing a new
source payload or fabricating a family. The concrete rows remain calibration
or already routed, the template row remains non-mathematical, and no residual
bucket supplies a named non-routed presentation with route data.

`FJ64` completes `OBL-T001-010`, records `OBL-T001-011`, and selects `FJ65`,
Prior-Art / Branch-Readiness Checkpoint. The next step must decide whether a
prior-art blocker object, target-pause recommendation, or target-pivot
comparison can be recorded, without beginning another source-summary lane.

At this point, the next step was `FJ65`, Prior-Art / Branch-Readiness
Checkpoint.

## FJ65 prior-art / branch-readiness checkpoint

Current status: `FJ65` has first-pass coverage as the Prior-Art /
Branch-Readiness Checkpoint module. It audits the `FJ64` no-candidate state
for an exact prior-art blocker object, target-pause recommendation, or
target-pivot comparison object.

The route decision after `FJ65` is that no exact prior-art blocker object or
pivot-comparison object is present. Prior-art checking has no candidate or
theorem payload to compare. The no-candidate state is recorded as a
target-pause trigger, but the actual pause-or-pivot decision is deferred to
the branch checkpoint.

`FJ65` completes `OBL-T001-011`, records `OBL-T001-012`, and selects `FJ66`,
T-001 Branch Checkpoint. `FJ66` must either pause `T-001`, select a bounded
target-pivot comparison packet, or identify an exact repository object that
justifies continuing `T-001`.

At this point, the next step was `FJ66`, T-001 Branch Checkpoint.

## FJ66 T-001 branch checkpoint

Current status: `FJ66` has first-pass coverage as the T-001 Branch
Checkpoint module. It makes the branch decision required after the
no-candidate and no-prior-art-object sequence from `FJ64` and `FJ65`.

The route decision after `FJ66` is to pause `T-001` as an active
proof-target sequence. This is not a theorem about torsion-free one-relator
groups and not evidence against Farrell--Jones. It records only that the
current repository has no candidate-admissible row, exact source payload,
bridge, computation, prior-art blocker object, or pivot-comparison result
that justifies continuing `T-001` now.

`T-001` remains an unresolved archived target. `FJ66` records
`OBL-T001-013`, the reactivation gate: future modules may reactivate `T-001`
only with a candidate-admissible row, exact source payload, bridge lemma,
concrete computation, prior-art blocker object, or target-pivot comparison
result explicitly reselecting it.

At this point, the next step was `FJ67`, Target-Pivot Criteria After T-001
Pause.

## FJ67 target-pivot criteria after T-001 pause

Current status: `FJ67` has first-pass coverage as the Target-Pivot Criteria
After T-001 Pause module. It records the criteria that must be checked before
the project selects any new active target after the `T-001` pause.

The route decision after `FJ67` is not to select a new active target yet.
Instead, `FJ67` records `OBL-PIVOT-001`: no new active target may be selected
until a target-pivot matrix records source-readiness, candidate-level object,
Farrell--Jones relevance, formulation-safety flags, known-route overlap,
prior-art risk, expected project output, stop condition, and explicit
decision.

`T-001` remains dormant unless the `OBL-T001-013` reactivation gate is
satisfied. Artin groups, automatic / biautomatic groups, Thompson-type
groups, and dormant `T-001` are possible inputs to the next comparison, but
none is selected by `FJ67`.

At this point, the next step was `FJ68`, Target-Pivot Candidate Matrix.

## FJ68 target-pivot candidate matrix

Current status: `FJ68` has first-pass coverage as the Target-Pivot Candidate
Matrix module. It applies `OBL-PIVOT-001` to the currently recorded possible
targets: Artin groups, automatic / biautomatic groups, Thompson-type groups,
and dormant `T-001`.

The route decision after `FJ68` is to select exactly one bounded target
packet:

```text
A-001. Artin subclass-gap inventory after FJ18
```

This is a project-selection result, not a mathematical theorem. It does not
claim the Farrell--Jones conjecture for all Artin groups. It records only
that Artin subclass-gap work is currently the only compared target with
source-verified internal anchors, open project questions, and a bounded next
object.

`FJ68` defers automatic / biautomatic groups and Thompson-type groups because
no exact source payload or bounded candidate object is recorded for them in
the current repository. `T-001` remains dormant because the `OBL-T001-013`
reactivation gate is not satisfied.

`FJ68` records `OBL-ARTIN-001`: `FJ69` must produce an Artin subclass-gap
inventory from existing repository records before beginning any new Artin
source-summary lane.

At this point, the next step was `FJ69`, Artin Subclass-Gap Inventory After
FJ18.

## FJ69 Artin subclass-gap inventory after FJ18

Current status: `FJ69` has first-pass coverage as the Artin Subclass-Gap
Inventory After FJ18 module. It creates
`ledgers/artin_subclass_gap_inventory.md`, using only existing repository
records.

The route decision after `FJ69` is that the repository now has a first-pass
Artin covered/gap/deferred inventory. In the current repository state, the
only explicit global Artin gap row is all Artin groups. No additional named
Artin subclass outside the `FJ18` rows is currently candidate-ready.

`FJ69` gives a first-pass current-repository answer to `OQ-021`, sharpens
`OQ-023`, completes `OBL-ARTIN-001`, records `OBL-ARTIN-002`, and normalizes
two `FJ18` source-verified rows into `ledgers/known_classes.md`. It makes no
new external source check and no global all-Artin theorem claim.

The next step after `FJ69` was `FJ70`, Wu Clique-Reduction Candidate Filter
for Artin Gap Rows. Its task was to test whether `ART-GAP-003` could produce
a bounded candidate from existing records, or record that no current
Wu-filter candidate exists.

## FJ70 Wu clique-reduction candidate filter

Current status: `FJ70` has first-pass coverage as the Wu Clique-Reduction
Candidate Filter for Artin Gap Rows module. It uses only existing
repository records and does not re-check Wu's source.

The route decision after `FJ70` is that the current repository has no
Wu-filter candidate. The already recorded Wu rows are covered under `FJ18`;
the remaining Artin gap rows are global or placeholder rows and do not name a
finite graph, graph family, or subclass with clique-subgroup data.

`FJ70` resolves `OQ-092`, updates `OQ-023`, completes `OBL-ARTIN-002`,
records `OBL-ARTIN-003`, and makes no global all-Artin theorem claim. The
Wu lane may be reactivated only with a named source payload: graph/subclass,
finite positive-even hypotheses, clique data, formulation safety, and
prior-art-overlap notes.

The next step after `FJ70` was `FJ71`, Artin Branch Checkpoint After Wu
Filter. Its task was to decide whether to pause the active Artin packet,
select a named source-payload acquisition task, return to target-pivot
comparison, or continue through a concrete repository object.

## FJ71 Artin branch checkpoint after Wu filter

Current status: `FJ71` has first-pass coverage as the Artin Branch
Checkpoint After Wu Filter module. It uses only existing repository records
and does not check any new external source.

The branch decision after `FJ71` is to pause the active Artin proof/source
lane. The current repository has no named Artin graph, graph family,
subclass, source theorem, or bridge object that could support a bounded
continuation after the no-current-Wu-candidate note from `FJ70`.

This pause is not a mathematical theorem. It does not claim the
Farrell--Jones conjecture for all Artin groups, and it does not claim that no
future Artin subclass can become candidate-ready. It records only that the
current Artin lane should not continue without a named reactivation payload
that changes a project object.

`FJ71` resolves `OQ-093`, records `OBL-ARTIN-004`, records
`OBL-PIVOT-002`, selects target packet `A-004`, and makes no global
all-Artin theorem claim.

The next step after `FJ71` was `FJ72`, Target-Pivot Refresh After Artin
Pause. Its task was to reapply the `FJ67` target-pivot criteria after both
dormant `T-001` and the paused Artin lane, and either select one bounded
next packet with a concrete repository object or record that no target is
ready.

## FJ72 target-pivot refresh after Artin pause

Current status: `FJ72` has first-pass coverage as the Target-Pivot Refresh
After Artin Pause module. It uses only existing repository records and does
not check any new external source.

The pivot decision after `FJ72` is that no group-class target is currently
ready for active proof or source work. `T-001` remains dormant under
`OBL-T001-013`; the Artin lane remains paused under `OBL-ARTIN-004`;
automatic / biautomatic groups and Thompson-type groups remain deferred
because the repository records no exact source payload or bounded candidate
object for them.

The selected next packet is non-group-theoretic:

```text
FND-001. Foundational Open-Question Triage After Target Pauses
```

This packet is bounded by existing repository objects: open foundational
questions and theorem-dependency rows. It must not become a broad foundations
survey.

`FJ72` resolves `OQ-094`, completes `OBL-PIVOT-002`, records
`OBL-FND-001`, selects `FND-001`, and makes no Farrell--Jones theorem claim.

The next step after `FJ72` was `FJ73`, Foundational Open-Question Triage
After Target Pauses. Its task was to select at most one foundational blocker
for bounded action, or record that no foundational blocker was ready.

## FJ73 foundational open-question triage after target pauses

Current status: `FJ73` has first-pass coverage as the Foundational
Open-Question Triage After Target Pauses module. It uses only existing
repository records and does not check any new external source.

The triage decision after `FJ73` is to select `OQ-005`, the weakly
contractible versus contractible fixed-point formulation issue, as the next
bounded foundational blocker. This is selected because `FJ03` already
records the relevant source anchor and the issue can sharpen a concrete
project convention without opening a broad foundations survey.

Deferred foundational blockers include primary-source tracing for broad
inheritance rows, canonical obstruction-category source selection, and
transfer-category model selection. Those remain important but source-heavy
unless a later module identifies a proof-sensitive application.

`FJ73` resolves `OQ-095`, completes `OBL-FND-001`, records `OBL-FND-002`,
selects `FND-002`, and makes no Farrell--Jones theorem claim.

The next step after `FJ73` was `FJ74`, Fixed-Point Convention Cleanup for
Classifying Spaces. Its task was to resolve or sharpen `OQ-005` by
separating the readable contractible/empty formulation from the weakly
contractible source characterization recorded in `FJ03`.

## FJ74 fixed-point convention cleanup for classifying spaces

Current status: `FJ74` has first-pass coverage as the Fixed-Point
Convention Cleanup for Classifying Spaces module. It uses Lueck's
classifying-spaces survey only through the source anchor already recorded in
`FJ03`; it does not check a new external source.

The convention decision after `FJ74` is to use a two-layer formulation for
models of \(E_{\mathcal F}G\). The contractible/empty fixed-point condition
is retained as a strict readable model convention for examples and
exposition. The source-level theorem behind existence, uniqueness,
terminality, and general recognition remains Lueck's weakly contractible
fixed-point plus isotropy formulation as recorded in `ER-002`.

This is a convention cleanup, not a new theorem. It does not create a new
Farrell--Jones route, and it does not replace weak contractibility by
contractibility in source-verified claims.

`FJ74` resolves `OQ-005` at first pass, completes `OBL-FND-002`, records
`FND-CONV-001`, completes `FND-002`, records `OBL-FND-003`, selects
`FND-003`, and makes no Farrell--Jones theorem claim.

The next step after `FJ74` was `FJ75`, Virtually Cyclic Dichotomy
Source-Payload Check. Its task was to address `OQ-006` by checking
Farrell--Jones (1995), Lemma 2.5, or by recording that the source payload
could not yet be promoted.

## FJ75 virtually cyclic dichotomy source-payload check

Current status: `FJ75` has first-pass coverage as the Virtually Cyclic
Dichotomy Source-Payload Check module. It performs a bounded source-access
audit for Farrell--Jones (1995), Lemma 2.5.

The source decision after `FJ75` is no-promotion. Crossref and OpenAlex
metadata verify the article record and DOI `10.1007/BF00965457`, but the
primary Lemma 2.5 text was not accessible in this environment. The Springer
route returned a client challenge rather than article text, and no open
full-text route was found.

Therefore Farrell--Jones (1995) is now DOI-checked and metadata-checked, but
it is not a direct theorem source inside this repository. The usable
first-pass source for the infinite virtually cyclic dichotomy remains the
already checked Lueck--Reich survey statement from `FJ04`.

`FJ75` resolves `OQ-006` negatively for first-pass project use, completes
`OBL-FND-003`, records `FND-SRC-001`, records `OBL-FND-004`, selects
`FND-004`, and makes no Farrell--Jones theorem claim.

The next step after `FJ75` was `FJ76`, Foundational Source-Queue Checkpoint
After `OQ-006` No-Promotion. Its task was to decide whether another exact
foundational source-payload item was ready, or whether the foundational queue
should pause.

## FJ76 foundational source-queue checkpoint after OQ-006 no-promotion

Current status: `FJ76` has first-pass coverage as the Foundational
Source-Queue Checkpoint After `OQ-006` No-Promotion module. It uses only
current repository records and does not check a new external source.

The source-queue decision after `FJ76` is to select no further foundational
source payload. The remaining foundational items are either already adequate
for first-pass use, closed for the current state, or too source-heavy without
a current proof-sensitive application. Continuing the queue would risk
literature bookkeeping without mathematical progress.

`FJ76` records `FND-QUEUE-PAUSE-001`: the foundational source queue is
paused until a later module names an exact source payload, the project object
changed by checking it, the current proof/candidate/route need, and a stop
condition.

`FJ76` resolves `OQ-096`, completes `OBL-FND-004`, completes `FND-004`,
records `OBL-PIVOT-003`, selects `PIVOT-003`, and makes no Farrell--Jones
theorem claim.

The next step after `FJ76` was `FJ77`, Target-Pivot Readiness After
Foundational Queue Pause. Its task was to select one bounded next packet with
a concrete project object, or record that no target was ready and name the
next governance action.

## FJ77 target-pivot readiness after foundational queue pause

Current status: `FJ77` has first-pass coverage as the Target-Pivot Readiness
After Foundational Queue Pause module. It uses only current repository
records and does not check a new external source.

The pivot-readiness decision after `FJ77` is that no group-class target and
no foundational source packet is ready for immediate activation. `T-001`
remains dormant under `OBL-T001-013`; the Artin lane remains paused under
`OBL-ARTIN-004`; automatic / biautomatic groups and Thompson-type groups
remain deferred; and the foundational source queue remains paused under
`FND-QUEUE-PAUSE-001`.

This is a project-state decision, not a mathematical theorem about any group
class.

`FJ77` resolves `OQ-097`, completes `OBL-PIVOT-003`, completes
`PIVOT-003`, records a no-target/no-source-ready decision, selects
`C4-CLOSE-001`, records `OBL-C4-001`, and makes no Farrell--Jones theorem
claim.

The next step after `FJ77` was `FJ78`, Cycle-004 Closure-Readiness Audit.
Its task was to audit active obligations, open questions, paused target
gates, the foundational source-queue pause, and remaining cycle-004 module
slots before selecting the next packet.

## FJ78 cycle-004 closure-readiness audit

Current status: `FJ78` has first-pass coverage as the Cycle-004
Closure-Readiness Audit module. It uses only current repository records and
does not check a new external source.

The closure-readiness decision after `FJ78` is that `cycle_004` should not
reactivate a mathematical target or restart the foundational source queue.
The remaining two numbered module slots, `FJ79` and `FJ80`, should be used
for handoff preparation and final pre-reflection closure.

`FJ78` resolves `OQ-098`, completes `OBL-C4-001`, completes
`C4-CLOSE-001`, records a closure-ready cycle-state decision, selects
`C4-HANDOFF-001`, records `OBL-C4-002`, and makes no Farrell--Jones theorem
claim.

The next step after `FJ78` was `FJ79`, Cycle-004 Handoff Table and Gate
Index. Its task was to assemble the paused target gates, source-queue pause
data, open-question clusters, proof-obligation status, remaining cycle slots,
and inputs needed for the final pre-reflection module.

## FJ79 cycle-004 handoff table and gate index

Current status: `FJ79` has first-pass coverage as the Cycle-004 Handoff
Table and Gate Index module. It uses only current repository records and does
not check a new external source.

The handoff decision after `FJ79` is that no target or source lane should be
reactivated in the final numbered module of `cycle_004`. `T-001` remains
dormant under `OBL-T001-013`; the Artin lane remains paused under
`OBL-ARTIN-004`; automatic / biautomatic groups and Thompson-type groups
remain deferred; the foundational source queue remains paused under
`FND-QUEUE-PAUSE-001`; and WIP / provisional `FJ53` remains provisional.

`FJ79` creates `ledgers/cycle_004_handoff.md` as the reusable handoff
artifact for `FJ80` and the cycle reflection. It resolves `OQ-099`,
completes `OBL-C4-002`, completes `C4-HANDOFF-001`, selects
`C4-FINAL-001`, records `OBL-C4-003`, and makes no Farrell--Jones theorem
claim.

The next step after `FJ79` was `FJ80`, Final Pre-Reflection Closure Module.
Its task was to verify that `cycle_004` has enough handoff data for
`reflections/cycle_004_reflection.md`, select that reflection if no blocker
remains, and avoid starting any new target or source lane.

## FJ80 final pre-reflection closure module

Current status: `FJ80` has first-pass coverage as the Final Pre-Reflection
Closure Module. It uses only current repository records and does not check a
new external source.

The final closure decision after `FJ80` is that the numbered module portion
of `cycle_004` is ready for reflection. `FJ80` confirms that `OQ-099` is
resolved, `OBL-C4-002` is complete, `C4-HANDOFF-001` is complete,
`OBL-C4-003` is active for this module, and the paused target/source gates
remain unsatisfied.

`FJ80` resolves `OQ-100`, completes `OBL-C4-003`, completes
`C4-FINAL-001`, records a reflection-ready cycle state for the numbered
module portion of `cycle_004`, selects `C4-REFLECT-001`, and makes no
Farrell--Jones theorem claim.

The next artifact after `FJ80` was `reflections/cycle_004_reflection.md`.
Its task was to close cycle 004 by recording what the cycle accomplished,
what remains gated or paused, and what posture should govern the next cycle.

## Cycle 004 reflection

Current status: `reflections/cycle_004_reflection.md` has first-pass
coverage as the cycle-004 reflection. It uses only current repository records
and does not check a new external source.

The reflection decision after cycle 004 is that the project should not
reactivate a target, restart the foundational source queue, or finalize WIP /
provisional `FJ53` merely because a new cycle begins. The cycle closed with
`T-001` dormant under `OBL-T001-013`, the Artin lane paused under
`OBL-ARTIN-004`, deferred group classes still deferred, and the foundational
source queue paused under `FND-QUEUE-PAUSE-001`.

The reflection resolves `OQ-101`, selects `C5-GATE-001`, records
`OBL-C5-001`, selects `FJ81`, and makes no Farrell--Jones theorem claim.

The next step after the reflection was `FJ81`, Cycle-005 Reactivation Gate
Audit. Its task was to test whether any recorded reactivation gate was
currently satisfiable from repository data.

## FJ81 cycle-005 reactivation gate audit

Current status: `FJ81` has first-pass coverage as the Cycle-005
Reactivation Gate Audit module. It uses only current repository records and
does not check a new external source.

The audit decision after `FJ81` is that no recorded reactivation gate is
satisfied at the start of cycle 005. `T-001` remains dormant under
`OBL-T001-013`; the Artin lane remains paused under `OBL-ARTIN-004`; the
foundational source queue remains paused under `FND-QUEUE-PAUSE-001`;
automatic / biautomatic groups and Thompson-type groups remain deferred; and
WIP / provisional `FJ53` remains provisional.

This is a project-state decision, not a mathematical theorem about any group
class. It does not prove a Farrell--Jones result, reactivate `T-001`, reopen
the Artin lane, or finalize `FJ53`.

`FJ81` resolves `OQ-102`, completes `OBL-C5-001`, completes
`C5-GATE-001`, records the no-gate-ready cycle-005 state, selects
`C5-PAYLOAD-001`, records `OBL-C5-002`, selects `FJ82`, and makes no
Farrell--Jones theorem claim.

The next step is `FJ82`, Payload Acquisition Protocol or Project-Pause
Decision. It should define a bounded payload-acquisition protocol, including
allowable payload types, the project object changed, and a stop condition, or
record a project-pause decision if no such protocol can be made precise.

## FJ82 payload acquisition protocol or project-pause decision

Current status: `FJ82` has first-pass coverage as the Payload Acquisition
Protocol or Project-Pause Decision module. It uses only current repository
records and does not check a new external source.

The decision after `FJ82` is to create `ledgers/payload_intake_protocol.md`
and place the project in a payload-gated pause. The protocol records which
payloads can restart mathematical work: candidate-admissible `T-001` rows,
exact `T-001` bridge or computation payloads, named Artin payloads, exact
foundational source payloads, formulation-comparison payloads, non-hyperbolic
`RB-006` bridge payloads, and exact prior-art blockers. It rejects source
names, target names, broad class labels, and residual bucket labels by
themselves.

No immediate payload is accepted by `FJ82`. Therefore no `FJ83` module is
selected at that point. A future `FJ83` may be instantiated only after an
accepted payload is recorded under `ledgers/payload_intake_protocol.md` or in
the relevant target ledger.

`FJ82` resolves `OQ-103`, completes `OBL-C5-002`, completes
`C5-PAYLOAD-001`, records `C5-PAUSE-001`, records `OBL-C5-003`, records
`OQ-104`, and makes no Farrell--Jones theorem claim.

The next project move after `FJ82` was payload intake under the `FJ82`
protocol, not a numbered module. An accepted payload later appeared and
instantiated `FJ83` from its exact target, changed project object, and stop
condition.

## FJ83 K0 Cohen--Lyndon payload verification

Current status: `FJ83` has first-pass coverage as the K0 Cohen--Lyndon
Payload Verification module. It checks one external source and records the
result only at weaker \(K_0\)-level.

`FJ83` records accepted payload `PAY-T001-K0-CL-2025-001`, sourced to
Jaikin-Zapirain, Linton, and Sanchez-Peralta (2025), *Group pairs, coherence
and Farrell-Jones Conjecture for K0*. The source metadata, Conjecture 1, the
introductory K0 theorem, and the technical group-pair K0 theorem are checked
at first-pass level.

The FJ83 decision is conservative. The payload changes `OQ-081` from no
exact weaker \(K_0\) / Cohen--Lyndon source payload available to exact source
payload located and first-pass verified. It resolves `OQ-104` by identifying
FJ83 as the payload-instantiated module. It does not prove full `T-001`, does
not claim coefficient K-theory FJC, `FJCw`, `FICwF`, or full
\(\mathcal{FJ}\), and does not remove a residual bucket.

`FJ83` completes `OBL-C5-003`, records `OBL-T001-014` for any future
candidate/family-level use of the source, records `OBL-C5-004` blocking
`FJ84` without a new accepted payload, and makes no Farrell--Jones theorem
claim.

The next project move after `FJ83` was not automatic continuation. It became
`FJ84` only after accepted payload `PAY-T001-K0-CL-HYP-2026-001` was
recorded under the payload protocol.

## FJ84 K0 Cohen--Lyndon candidate hypothesis audit

Current status: `FJ84` has first-pass coverage as the K0 Cohen--Lyndon
Candidate Hypothesis Audit module. It checks no new external source; it uses
the source-hypothesis package already verified in `FJ83`.

`FJ84` records accepted payload `PAY-T001-K0-CL-HYP-2026-001`, whose object
is to determine whether any currently recorded `T-001` candidate/family
satisfies the FJ83 weaker \(K_0\) / Cohen--Lyndon source hypotheses.

The FJ84 decision is conservative. The current candidate rows
`CAND-T001-001`, `CAND-T001-002`, and `CAND-T001-003` are not FJ83-eligible
from repository records, and `TPL-RB003-004-008` remains only a placeholder.
The audit therefore records no candidate promotion, no full `T-001` theorem,
no coefficient K-theory FJC, no `FJCw`, no `FICwF`, no full
\(\mathcal{FJ}\), and no residual subtraction.

`FJ84` resolves `OQ-105`, completes `OBL-C5-004` for FJ84, completes
`OBL-T001-014` for the current inventory, records `OBL-T001-015` for any
future FJ83-payload use, records `OBL-C5-005` blocking `FJ85` without a new
accepted payload, and creates `OQ-106`.

The next project move after `FJ84` was not a mathematical module. It became
`FJ85` only after accepted governance payload `PAY-C5-GOV-NEXT-2026-001`
was recorded.

## FJ85 payload authorship checkpoint after FJ84

Current status: `FJ85` has first-pass coverage as the Payload Authorship
Checkpoint After FJ84 module. It checks no external source and makes no
mathematical claim.

`FJ85` records accepted payload `PAY-C5-GOV-NEXT-2026-001`, whose object is
to interpret the instruction "paste the next payload, then continue" without
inventing a candidate, source theorem, bridge lemma, computation,
formulation comparison, prior-art blocker, or residual-bucket route.

The FJ85 decision is procedural. The only repository-supported next payload
after `FJ84` is governance-only. It can update gate and handoff records, but
it cannot reactivate `T-001`, prove any Farrell--Jones statement, promote
the FJ83 weaker \(K_0\) source to a candidate result, or remove a residual
bucket.

`FJ85` resolves `OQ-106`, completes `OBL-C5-005` for FJ85, records the
payload type `PAY-GOV`, records `OBL-C5-006` blocking `FJ86` without a new
accepted payload, and creates `OQ-107`.

The next project move after `FJ85` was not automatic. It became `FJ86` only
after accepted candidate payload `PAY-T001-CAND-BS23-2026-001` was recorded
under the payload protocol.

## FJ86 T-001 candidate intake audit for G_BS23

Current status: `FJ86` has first-pass coverage as the T-001 Candidate Intake
Audit for \(G_{BS23}\). It checks no external source and makes no
Farrell--Jones theorem claim.

`FJ86` records accepted payload `PAY-T001-CAND-BS23-2026-001`, whose object
is the Baumslag--Solitar-type one-relator presentation
\[
G_{BS23}=\langle a,t\mid ta^2t^{-1}a^{-3}\rangle.
\]

The FJ86 decision is conservative. The payload supplies a concrete
one-relator candidate and an epimorphism to \(\mathbb Z\), but the repository
does not yet source-verify torsion-free status, compute Brown/BNS or kernel
control data, identify a hyperbolic/CAT(0)/virtually solvable/finite-index
route, or record prior-art comparison. FJ86 therefore records
`CAND-T001-004` as a concrete blocked intake row, not as an active proof
success row.

`FJ86` resolves `OQ-107`, completes `OBL-C5-006` for FJ86, records
`OBL-T001-016` for any later use of `CAND-T001-004`, records `OBL-C5-007`
blocking `FJ87` without a new accepted payload, creates `OQ-108`, and makes
no full `T-001` claim, no coefficient FJC claim, no `FJCw` or `FICwF` claim,
and no residual subtraction.

The next project move after `FJ86` was not automatic. It became `FJ87` only
after accepted torsion-free / HNN payload
`PAY-T001-BS23-TF-HNN-2026-001` was recorded under the payload protocol.

## FJ87 G_BS23 torsion-free HNN check

Current status: `FJ87` has first-pass coverage as the \(G_{BS23}\)
Torsion-Free HNN Check. It uses the Bass--Serre source package already
recorded in `FJ36` and checks no new external source.

`FJ87` records accepted payload `PAY-T001-BS23-TF-HNN-2026-001`, whose object
is to check whether
\[
G_{BS23}=\langle a,t\mid ta^2t^{-1}a^{-3}\rangle
\]
is torsion-free.

The FJ87 decision is bounded. The group is the HNN extension of
\(\langle a\rangle\cong\mathbb Z\) identifying \(\langle a^2\rangle\) with
\(\langle a^3\rangle\). Its Bass--Serre tree has vertex stabilizers conjugate
to \(\langle a\rangle\). Any finite-order element fixes a vertex of that
tree and is therefore conjugate into \(\langle a\rangle\), so it is trivial.
Thus `CAND-T001-004` is first-pass verified as torsion-free.

This does not identify the kernel of \(\chi(t)=1,\chi(a)=0\), does not
compute Brown/BNS data, does not identify a hyperbolic, CAT(0), virtually
solvable, finite-index, or FJ83 weaker \(K_0\) route, and does not record a
prior-art comparison.

`FJ87` resolves `OQ-108`, completes `OBL-C5-007` for FJ87, partially
completes `OBL-T001-016` only for the torsion-free-status component, records
`OBL-T001-017` for any later route use of `CAND-T001-004`, records
`OBL-C5-008` blocking `FJ88` without a new accepted payload, creates
`OQ-109`, and makes no full `T-001` claim, no coefficient FJC claim, no
`FJCw` or `FICwF` claim, and no residual subtraction.

The next project move after `FJ87` was not automatic. It became `FJ88` only
after accepted known-route / prior-art blocker payload
`PAY-T001-BS23-ROUTE-PRIORART-2026-001` was recorded under the payload
protocol.

## FJ88 G_BS23 known-route / prior-art blocker audit

Current status: `FJ88` has first-pass coverage as the \(G_{BS23}\)
Known-Route and Prior-Art Blocker Audit.

`FJ88` records accepted payload
`PAY-T001-BS23-ROUTE-PRIORART-2026-001`, whose object is to determine
whether
\[
G_{BS23}=\langle a,t\mid ta^2t^{-1}a^{-3}\rangle
\]
is already removed from the `T-001` residual bucket by a source-verified
route or prior-art theorem.

The FJ88 decision is source-driven. The group is \(BS(2,3)\). Gandini--
Meinert--Rueping (2015) prove that fundamental groups of graphs of abelian
groups lie in their finite-wreath-product, additive-category K- and
L-theoretic Farrell--Jones class \(C\), and they explicitly include all
Baumslag--Solitar groups as a corollary. Thus `CAND-T001-004` is already
covered by a source-verified route.

This is a route closure for one candidate row, not a global theorem for all
torsion-free one-relator groups. `FJ88` does not compute the kernel of
\(\chi(t)=1,\chi(a)=0\), does not compute Brown/BNS data, and does not claim
that the project has solved `T-001`.

`FJ88` resolves `OQ-109`, completes `OBL-C5-008` for FJ88, completes
`OBL-T001-017` for the known-route / prior-art audit of `CAND-T001-004`,
records `ER-015`, records `OBL-C5-009` blocking `FJ89` without a new
accepted payload, creates `OQ-110`, and makes no full `T-001` claim.

The next project move after `FJ88` was not automatic. It became `FJ89` only
after accepted internal live-candidate audit payload
`PAY-T001-LIVE-CAND-AUDIT-2026-001` was recorded under the payload protocol.

## FJ89 live-candidate audit after G_BS23 closure

Current status: `FJ89` has first-pass coverage as the Live-Candidate Audit
After \(G_{BS23}\) Closure.

`FJ89` records accepted payload `PAY-T001-LIVE-CAND-AUDIT-2026-001`, whose
object is to audit the current `T-001` candidate inventory after the FJ88
route closure of `CAND-T001-004`.

The FJ89 decision is internal and finite. The current rows are classified as
follows:

- `CAND-T001-001`: calibration-only / already non-residual;
- `CAND-T001-002`: routed through `FJ26`;
- `CAND-T001-003`: routed through `FJ26` after the recorded
  `FJ34`/`FJ36` bridge;
- `CAND-T001-004`: source-routed / prior-art-blocked by `FJ88` through
  `ER-015`;
- `TPL-RB003-004-008`: template placeholder only.

Thus no current `T-001` candidate row is live and non-routed. This is a
project-state blocker, not a theorem about torsion-free one-relator groups.
`FJ89` does not add a candidate, search externally, reopen \(G_{BS23}\), or
claim any Farrell--Jones theorem.

`FJ89` resolves `OQ-110`, completes `OBL-C5-009`, records the
no-live-candidate blocker `NLC-T001-001`, creates `OBL-C5-010` blocking
`FJ90` without a new accepted payload, creates `OQ-111`, and makes no full
`T-001` claim.

The next project move after `FJ89` was not automatic. It became `FJ90` only
after accepted candidate-intake payload `PAY-T001-CAND-FJ90-2026-001` was
recorded under the payload protocol.

## FJ90 T-001 candidate intake after no-live-candidate blocker

Current status: `FJ90` has first-pass coverage as the candidate-intake audit
for `CAND-T001-005`.

`FJ90` records accepted payload `PAY-T001-CAND-FJ90-2026-001`, whose object
is the concrete one-relator candidate
\[
G_{FJ90}=\langle a,b\mid a b a^{-1} b^2 a b^{-3}\rangle.
\]

The FJ90 decision is conservative. The relator is first-pass checked as not
a proper power by the abelianization vector \((1,0)\), and the epimorphism
\(\chi(a)=0,\chi(b)=1\) is recorded. However, FJ90 does not source-verify
torsion-free status, does not compute Brown/BNS or kernel data, does not
identify a known Farrell--Jones route, and does not perform a prior-art
comparison.

Thus `CAND-T001-005` is a concrete blocked intake row, not a live proof
target, not a route result, and not a residual subtraction.

`FJ90` resolves `OQ-111`, completes `OBL-C5-010`, records
`CAND-T001-005`, creates `OBL-T001-018` for any later use of the candidate,
creates `OBL-C5-011` blocking `FJ91` without a new accepted payload, creates
`OQ-112`, and makes no full `T-001` claim.

At the close of `FJ90`, the next project move was not a numbered module. The
later accepted payload `PAY-T001-CAND005-TF-2026-001` instantiated `FJ91`.

## FJ91 CAND-T001-005 torsion-free source check

Current status: `FJ91` has first-pass coverage as the torsion-free
source-check for `CAND-T001-005`.

`FJ91` records accepted payload `PAY-T001-CAND005-TF-2026-001`, whose object
is to decide whether the `FJ90` non-proper-power check combines with a
source-checked one-relator torsion theorem.

The source decision is bounded. Putman's notes state the
Karrass--Magnus--Solitar torsion theorem and the corollary that
\(\langle S\mid r\rangle\) is torsion-free when \(r\in F(S)\) is not a
proper power. `FJ91` applies this to
\[
G_{FJ90}=\langle a,b\mid a b a^{-1} b^2 a b^{-3}\rangle
\]
using the `FJ90` abelianization check that the relator is not a proper power.

Thus `CAND-T001-005` is torsion-free at first-pass candidate-ledger level.
This is not a Farrell--Jones route, not kernel control, not a prior-art
audit, and not a residual subtraction.

`FJ91` resolves `OQ-112`, completes `OBL-C5-011`, partially completes
`OBL-T001-018` for torsion-free status, creates `OBL-T001-019` for the
remaining route/prior-art question, creates `OBL-C5-012` blocking `FJ92`
without a new accepted payload, creates `OQ-113`, and makes no full `T-001`
claim.

At the close of `FJ91`, the next project move was not a numbered module. The
later accepted payload `PAY-T001-CAND005-BROWN-BNS-2026-001` instantiated
`FJ92`.

## FJ92 CAND-T001-005 Brown/BNS kernel-control computation

Current status: `FJ92` has first-pass coverage as the Brown/BNS
kernel-control computation for `CAND-T001-005`.

`FJ92` records accepted payload `PAY-T001-CAND005-BROWN-BNS-2026-001`, whose
object is to decide whether the character
\[
\chi(a)=0,\qquad \chi(b)=1
\]
has finitely generated kernel under the Brown/BNS framework already recorded
in the repository.

The computation is bounded. For \(\chi\), the Brown initial-segment values
are
\[
0,0,1,1,2,3,3,2,1,
\]
so the maximum \(3\) occurs exactly twice. For \(-\chi\), the values are
\[
0,0,-1,-1,-2,-3,-3,-2,-1,
\]
so the maximum \(0\) occurs exactly twice. In the zero-on-one-generator case
recorded from Brown, both directions pass the maximum-count test.

Thus `FJ92` records that \(\ker(\chi)\) is finitely generated. It does not
identify the kernel as finite-rank free, does not invoke the `FJ26`
finite-rank free-by-cyclic route, does not perform a known-route / prior-art
audit, and does not subtract a residual bucket.

`FJ92` resolves `OQ-113`, completes `OBL-C5-012`, partially completes
`OBL-T001-019` for Brown-positive finite generation, creates
`OBL-T001-020` for the remaining route/prior-art question, creates
`OBL-C5-013` blocking `FJ93` without a new accepted payload, creates
`OQ-114`, and makes no full `T-001` claim.

At the close of `FJ92`, the next project move was not a numbered module.
`FJ93` was later instantiated only after a new accepted payload was recorded
under `ledgers/payload_intake_protocol.md` or in the relevant target ledger.

## FJ93 CAND-T001-005 known-route / prior-art blocker audit

Current status: `FJ93` has first-pass coverage as the known-route /
prior-art blocker audit for `CAND-T001-005`.

`FJ93` records accepted payload `PAY-T001-CAND005-ROUTE-PRIORART-2026-001`,
whose object is to decide whether the current repository already routes
\[
G_{FJ90}=\langle a,b\mid a b a^{-1} b^2 a b^{-3}\rangle
\]
through a named route or prior-art theorem.

The audit is bounded. It checks only recorded repository routes: hyperbolic,
CAT(0), virtually solvable, finite-index/`FJCw`, finite-rank free-by-cyclic,
hyperbolic-by-cyclic, graph-of-abelian-groups, inheritance, and weaker
\(K_0\) / Cohen--Lyndon. No source-verified bridge for any of those routes is
recorded for `CAND-T001-005`.

Thus `CAND-T001-005` remains a concrete torsion-free one-relator candidate
object with Brown-positive finite generation of one kernel, but it is still
route-blocked. This is not a Farrell--Jones route, not a prior-art closure,
and not a residual subtraction.

`FJ93` resolves `OQ-114`, completes `OBL-C5-013`, completes the
route/prior-art-audit part of `OBL-T001-020`, creates `OBL-T001-021` for
any later route promotion or branch decision, creates `OBL-C5-014`, creates
`OQ-115`, and makes no full `T-001` claim.

At the close of `FJ93`, the next project move was not a numbered module.
`FJ94` was later instantiated only after a new accepted payload was recorded
under `ledgers/payload_intake_protocol.md` or in the relevant target ledger.

## FJ94 CAND-T001-005 K0 Cohen--Lyndon hypothesis audit

Current status: `FJ94` has first-pass coverage as the FJ83 weaker \(K_0\) /
Cohen--Lyndon hypothesis audit for `CAND-T001-005`.

`FJ94` records accepted payload `PAY-T001-CAND005-K0-CL-HYP-2026-001`, whose
object is to decide whether the current repository has enough row-level data
to apply the FJ83 source payload to
\[
G_{FJ90}=\langle a,b\mid a b a^{-1} b^2 a b^{-3}\rangle.
\]

The audit is bounded. It uses the FJ83 source package already verified for
Jaikin-Zapirain--Linton--Sanchez-Peralta (2025), and checks only whether the
candidate row records the needed Cohen--Lyndon presentation or group pair,
matching quotient, normalizer data, finite cohomological dimension data,
coherent group-ring hypotheses, and formulation-safety bridge.

The row is concrete and torsion-free, but it does not record the
Cohen--Lyndon/group-pair package required for FJ83 use. Thus
`CAND-T001-005` is not FJ83-eligible from current repository data.

This is not a weaker \(K_0\) consequence, not a Farrell--Jones route, not a
prior-art closure, and not a residual subtraction.

`FJ94` resolves `OQ-115`, completes `OBL-C5-014`, completes the
FJ83-hypothesis-audit part of `OBL-T001-021`, creates `OBL-T001-022` for any
later route promotion or branch decision, creates `OBL-C5-015`, creates
`OQ-116`, and makes no full `T-001` claim.

At the close of `FJ94`, the next project move was not a numbered module.
`FJ95` was later instantiated only after accepted governance payload
`PAY-T001-CAND005-BRANCH-2026-001` was recorded.

## FJ95 CAND-T001-005 branch checkpoint after FJ94

Current status: `FJ95` has first-pass coverage as the governance branch
checkpoint for `CAND-T001-005` after the bounded `FJ90`--`FJ94` audits.

`FJ95` records accepted governance payload
`PAY-T001-CAND005-BRANCH-2026-001`, whose object is to decide whether the
current repository should keep
\[
G_{FJ90}=\langle a,b\mid a b a^{-1} b^2 a b^{-3}\rangle
\]
as a live proof target, route it, demote it to blocked, convert it into a
calibration/prior-art example, or close it as non-actionable.

The checkpoint is bounded. It uses only repository ledgers and adds no source,
theorem, computation, or candidate.

The branch decision is:

- keep the row as a concrete torsion-free one-relator candidate object;
- demote it to blocked / inactive proof-target status;
- do not treat it as routed, prior-art-blocked, FJ83-eligible, weaker
  \(K_0\)-positive, or residual-subtractive.

This is not a Farrell--Jones route, not a weaker \(K_0\) consequence, not a
prior-art closure, and not a residual subtraction.

`FJ95` resolves `OQ-116`, completes `OBL-C5-015`, completes `OBL-T001-022`
by branch decision, creates `OBL-T001-023` for any later reopening, creates
`OBL-C5-016`, creates `OQ-117`, and makes no full `T-001` claim.

At the close of `FJ95`, the next bounded project move was the post-`FJ95`
live-candidate audit queued in `next_prompts.md`, Prompt 014. `FJ96` was
later instantiated from that queued payload.

## FJ96 live-candidate audit after CAND-T001-005 demotion

Current status: `FJ96` has first-pass coverage as the internal
live-candidate audit after the `FJ95` demotion of `CAND-T001-005`.

`FJ96` records accepted payload
`PAY-T001-LIVE-CAND-AUDIT-AFTER-CAND005-2026-001`, whose object is to audit
`ledgers/t001_candidate_inventory.md` and `ledgers/t001_residual.md` after
the latest `CAND-T001-005` branch decision.

The audit is bounded. It adds no candidate, checks no external source, and
does not reopen `CAND-T001-005`.

The audit result is:

- `CAND-T001-001` is calibration-only / already non-residual;
- `CAND-T001-002` is routed through `FJ26`;
- `CAND-T001-003` is a routed family through `FJ26`;
- `CAND-T001-004` is source-routed / prior-art-blocked through `ER-015`;
- `CAND-T001-005` is blocked / inactive after `FJ95`;
- `TPL-RB003-004-008` is a placeholder.

Thus no current candidate-inventory row is live and non-routed after `FJ95`.
This records post-`FJ95` no-live-candidate blocker `NLC-T001-002`.

This is not a Farrell--Jones theorem, not a weaker \(K_0\) consequence, and
not a residual subtraction.

`FJ96` resolves `OQ-117`, completes `OBL-C5-016`, creates `OBL-C5-017`,
creates `OQ-118`, and makes no full `T-001` claim.

At the close of `FJ96`, the next bounded project move was the
formulation-safety audit queued in `next_prompts.md`, Prompt 016. `FJ97` was
later instantiated from that queued prompt.

## FJ97 formulation-safety audit after no-live-candidate state

Current status: `FJ97` has first-pass coverage as a formulation-safety audit
after the post-`FJ96` no-live-candidate state.

`FJ97` records accepted payload `PAY-FORMULATION-SAFETY-AUDIT-2026-001`,
whose object is to check whether any active candidate route needs
formulation-safety classification after `FJ96`.

The audit is bounded. It adds no candidate, checks no external source, does
not reopen `CAND-T001-005`, and does not collapse simplified ring-coefficient
FJ, coefficient K-theory FJC, full \(\mathcal{FJ}\), `FJCw`, `FICwF`, or
weaker \(K_0\)-level statements.

The audit result is that no active candidate route remains after `FJ96`.
Therefore the Prompt 016 formulation-safety audit is formulation-irrelevant
for the current `T-001` candidate inventory. This is a project-ledger
classification, not a theorem about any group and not permission to ignore
formulation labels in later modules.

`FJ97` resolves `OQ-118`, completes `OBL-C5-017`, creates `OBL-C5-018`,
creates `OQ-119`, and makes no full `T-001` claim, no formulation promotion,
and no residual subtraction.

At the close of `FJ97`, the next bounded project move was the target-pivot
readiness checkpoint queued in `next_prompts.md`, Prompt 017. `FJ98` was
later instantiated from that queued prompt.

## FJ98 target-pivot readiness after formulation audit

Current status: `FJ98` has first-pass coverage as a target-pivot readiness
checkpoint after the post-`FJ97` formulation-irrelevant state.

`FJ98` records accepted payload `PAY-PIVOT-READINESS-2026-001`, whose object
is to compare whether `T-001`, the Artin lane, the foundational source queue,
automatic / biautomatic groups, Thompson-type groups, or the WIP /
provisional `FJ53` line has a concrete next object.

The audit is bounded. It checks no external source, adds no candidate,
reactivates no target, and starts no proof attempt.

The audit result is that no recorded mathematical target lane has a concrete
next object after `FJ97`. `T-001`, the Artin lane, the foundational source
queue, automatic / biautomatic groups, Thompson-type groups, and WIP /
provisional `FJ53` remain paused, deferred, WIP / provisional, or
payload-blocked.

`FJ98` resolves `OQ-119`, completes `OBL-C5-018`, creates `OBL-C5-019`,
creates `OQ-120`, and makes no full `T-001` claim, no target reactivation,
no source claim, and no residual subtraction.

At the close of `FJ98`, the next bounded project move was the cycle-005
strategic checkpoint queued in `next_prompts.md`, Prompt 018. `FJ99` was
later instantiated from that queued prompt.

## FJ99 cycle-005 strategic checkpoint

Current status: `FJ99` has first-pass coverage as the cycle-005 strategic
checkpoint after the post-`FJ98` all-targets-paused state.

`FJ99` records accepted payload `PAY-C5-STRATEGIC-CHECKPOINT-2026-001`,
whose object is to audit cycle-005 modules from `FJ81` onward and decide
whether the project is still making candidate-level progress or has returned
to decorative bookkeeping.

The audit is bounded. It checks no external source, adds no candidate,
reactivates no target, and starts no proof attempt.

The audit result is mixed but precise: cycle 005 did make real
candidate-level progress through `CAND-T001-004` and `CAND-T001-005`, but
the current post-`FJ98` state is no-target-ready / governance-only. Further
numbered modules that only summarize sources, restate paused targets, or
repeat gate checks would be decorative bookkeeping.

`FJ99` resolves `OQ-120`, completes `OBL-C5-019`, creates `OBL-C5-020`,
creates `OQ-121`, and makes no full `T-001` claim, no target reactivation,
no source claim, and no residual subtraction.

The next bounded project move is the cycle-005 closure-readiness audit queued
in `next_prompts.md`, Prompt 019. It should decide whether cycle 005 should
close, continue only with a concrete active payload, or pause, without
creating a reflection before a handoff table and exact unresolved gates are
recorded.

## FJ100 cycle-005 closure-readiness audit

Current status: `FJ100` has first-pass coverage as the cycle-005
closure-readiness audit after the `FJ99` strategic checkpoint.

`FJ100` records accepted payload `PAY-C5-CLOSURE-READINESS-2026-001`, whose
object is to determine whether `cycle_005` should close, continue with a
concrete active payload, or pause.

The audit is bounded. It checks no external source, adds no candidate,
reactivates no target, starts no proof attempt, and creates no reflection
directly.

The audit result is that `cycle_005` is closure-ready. `FJ100` records the
handoff table and exact unresolved gates in `ledgers/cycle_005_handoff.md`.
`FJ81`--`FJ100` now form the completed numbered span of `cycle_005`.

`FJ100` resolves `OQ-121`, completes `OBL-C5-020`, creates `OQ-122`, creates
`OBL-C5-021`, and makes no full `T-001` claim, no target reactivation, no
source claim, no proof attempt, and no residual subtraction.

The next bounded project move is the prompt-backlog maintenance pass queued
in `next_prompts.md`, Prompt 020. After handoff and backlog maintenance, the
project should prepare the cycle-005 reflection or larger post-100-module
review unless a higher-priority accepted payload is recorded.

## Cycle 005 reflection

Current status: `reflections/cycle_005_reflection.md` closes `cycle_005`.

The reflection records that cycle 005 made real candidate-level progress
under payload discipline. It verified a weaker \(K_0\) / Cohen--Lyndon source
payload at first-pass level, tested two concrete `T-001` candidate rows, and
closed with no live non-routed candidate row.

The reflection is bounded. It checks no external source, adds no candidate,
reactivates no target, starts no proof attempt, and creates no theorem claim.

The reflection decision is that `cycle_005` is closed and the next project
move should be a post-100-module strategic review before any `cycle_006`
target is opened.

The reflection resolves `OQ-122`, completes `OBL-C5-021`, creates
`OQ-123`, records `OBL-POST100-001`, and selects
`PAY-POST100-REVIEW-2026-001` as the next queued governance payload.

The next bounded project move was `next_prompts.md`, Prompt 022: a
post-100-module strategic review of `FJ01` through `FJ100`. That review is
now recorded in `reflections/post_100_module_strategic_review.md`.

## Post-100-module strategic review

Current status: `reflections/post_100_module_strategic_review.md` completes
the post-100-module strategic review required after the cycle-005 reflection.

The review is bounded. It checks no external source, adds no candidate,
reactivates no target, starts no proof attempt, and creates no theorem claim.

The review decision is that the project has a useful source-disciplined
archive after `FJ100`, but `cycle_006` should not open as a mathematical
proof cycle until an entry-gate audit checks whether any recorded lane has a
gate-satisfying payload.

The review resolves `OQ-123`, completes `OBL-POST100-001`, creates
`OQ-124`, records `OBL-C6-001`, and selects `PAY-C6-GATE-2026-001` as the
next queued governance payload.

The next bounded project move is `next_prompts.md`, Prompt 023: a cycle-006
entry-gate audit.

## Cycle 006 entry-gate audit

Current status: `ledgers/cycle_006_entry_gate.md` completes the cycle-006
entry-gate audit required by the post-100-module strategic review.

The audit is bounded. It checks no external source, adds no candidate,
reactivates no target, starts no proof attempt, creates no numbered module,
and creates no theorem claim.

The audit decision is that no recorded lane currently has a gate-satisfying
payload for cycle 006. `T-001`, `CAND-T001-005`, the Artin lane, the
foundational source queue, deferred group-class lines, and WIP / provisional
`FJ53` all remain gated.

The audit resolves `OQ-124`, completes `OBL-C6-001`, creates `OQ-125`,
records `OBL-C6-002`, and selects `PAY-C6-PAYLOAD-2026-001` as the next
queued governance payload.

The next bounded project move is `next_prompts.md`, Prompt 024: a cycle-006
payload acquisition or project-pause decision.

## Cycle 006 payload decision

Current status: `ledgers/cycle_006_payload_decision.md` completes the
cycle-006 payload acquisition / project-pause decision after the no-gate-ready
entry audit.

The decision is bounded. It checks no external source, adds no candidate,
reactivates no target, starts no proof attempt, creates no numbered module,
and creates no theorem claim.

The decision is that no concrete accepted payload exists for the next
numbered module. Prompt 025 and later backlog entries are templates, not
executable payloads until their placeholders are concretely filled and
accepted under `ledgers/payload_intake_protocol.md`.

The decision resolves `OQ-125`, completes `OBL-C6-002`, records
`C6-PAUSE-001`, creates `OQ-126`, records `OBL-C6-003`, and selects no
`FJ101` module.

This was the pre-`FJ101` state. `FJ101` was later instantiated only after
accepted callback-queue row `PAY-T001-CAND-C6-001-2026-001` was recorded.
Template prompts still do not count as accepted payloads.

## Current state handoff after cycle-006 pause

Current status: `C6-PAUSE-001` has been exited only for accepted row-001
candidate intake in `FJ101`, accepted row-002 candidate intake in `FJ102`,
accepted row-003 candidate intake in `FJ103`, and accepted row-004 candidate
intake in `FJ104`, accepted row-005 candidate intake in `FJ105`, and
accepted row-006 candidate intake in `FJ106`, and accepted row-007 candidate
intake in `FJ107`, accepted row-008 candidate intake in `FJ108`, and
accepted row-009 candidate intake in `FJ109`, and accepted row-010 candidate
intake in `FJ110`, and accepted row-011 candidate intake in `FJ111`. The
cycle has also been exited for accepted row-012 candidate intake in `FJ112`,
accepted row-013 candidate intake in `FJ113`, accepted row-014 candidate
intake in `FJ114`, accepted row-015 candidate intake in `FJ115`, and
accepted row-016 candidate intake in `FJ116`, accepted row-017 candidate
intake in `FJ117`, accepted row-018 candidate intake in `FJ118`, and
accepted row-019 candidate intake in `FJ119`, and accepted row-020 candidate
intake in `FJ120`, accepted row-021 candidate intake in `FJ121`, and
accepted row-022 candidate intake in `FJ122`, and accepted row-023 candidate
intake in `FJ123`, accepted row-024 candidate intake in `FJ124`, and
accepted row-025 candidate intake in `FJ125`, accepted row-026 candidate
intake in `FJ126`, accepted row-027 candidate intake in `FJ127`, accepted
row-028 candidate intake in `FJ128`, accepted row-029 candidate intake in
`FJ129`, accepted row-030 candidate intake in `FJ130`, accepted row-031
candidate intake in `FJ131`, and accepted row-032 candidate intake in
`FJ132`, accepted row-033 candidate intake in `FJ133`, and accepted row-034
candidate intake in `FJ134`, and accepted row-035 candidate intake in `FJ135`, and accepted row-036 candidate intake in `FJ136`, and accepted row-037 candidate intake in `FJ137`.
It remains payload-gated for all later numbered work.

The public README and this charter now record the same current project
position:

- `FJ01`--`FJ137` are the completed numbered module archive, with `FJ53`
  retained as WIP / provisional;
- `cycle_005` is closed;
- the post-100 strategic review is complete;
- the cycle-006 entry-gate audit found no gate-satisfying payload;
- the cycle-006 payload decision originally selected no `FJ101` module;
- `FJ101` later consumed `PAY-T001-CAND-C6-001-2026-001` from
  `ledgers/payload_execution_queue.md` and added `CAND-T001-C6-001` as a
  candidate-admissible but route-unresolved row;
- `FJ102` later consumed `PAY-T001-CAND-C6-002-2026-001` from
  `ledgers/payload_execution_queue.md` and added `CAND-T001-C6-002` as a
  candidate-admissible but route-unresolved row;
- `FJ103` later consumed `PAY-T001-CAND-C6-003-2026-001` from
  `ledgers/payload_execution_queue.md` and added `CAND-T001-C6-003` as a
  candidate-admissible but route-unresolved row;
- `FJ104` later consumed `PAY-T001-CAND-C6-004-2026-001` from
  `ledgers/payload_execution_queue.md` and added `CAND-T001-C6-004` as a
  candidate-admissible but route-unresolved row;
- `FJ105` later consumed `PAY-T001-CAND-C6-005-2026-001` from
  `ledgers/payload_execution_queue.md` and added `CAND-T001-C6-005` as a
  candidate-admissible but route-unresolved row;
- `FJ106` later consumed `PAY-T001-CAND-C6-006-2026-001` from
  `ledgers/payload_execution_queue.md` and added `CAND-T001-C6-006` as a
  candidate-admissible but route-unresolved row;
- `FJ107` later consumed `PAY-T001-CAND-C6-007-2026-001` from
  `ledgers/payload_execution_queue.md` and added `CAND-T001-C6-007` as a
  candidate-admissible but route-unresolved row;
- `FJ108` later consumed `PAY-T001-CAND-C6-008-2026-001` from
  `ledgers/payload_execution_queue.md` and added `CAND-T001-C6-008` as a
  candidate-admissible but route-unresolved row;
- `FJ109` later consumed `PAY-T001-CAND-C6-009-2026-001` from
  `ledgers/payload_execution_queue.md` and added `CAND-T001-C6-009` as a
  candidate-admissible but route-unresolved row;
- `FJ110` later consumed `PAY-T001-CAND-C6-010-2026-001` from
  `ledgers/payload_execution_queue.md` and added `CAND-T001-C6-010` as a
  candidate-admissible but route-unresolved row;
- `FJ111` later consumed `PAY-T001-CAND-C6-011-2026-001` from
  `ledgers/payload_execution_queue.md` and added `CAND-T001-C6-011` as a
  candidate-admissible but route-unresolved row;
- `FJ112` later consumed `PAY-T001-CAND-C6-012-2026-001` from
  `ledgers/payload_execution_queue.md` and added `CAND-T001-C6-012` as a
  candidate-admissible but route-unresolved row;
- `FJ113` later consumed `PAY-T001-CAND-C6-013-2026-001` from
  `ledgers/payload_execution_queue.md` and added `CAND-T001-C6-013` as a
  candidate-admissible but route-unresolved row;
- `FJ114` later consumed `PAY-T001-CAND-C6-014-2026-001` from
  `ledgers/payload_execution_queue.md` and added `CAND-T001-C6-014` as a
  candidate-admissible but route-unresolved row;
- `FJ115` later consumed `PAY-T001-CAND-C6-015-2026-001` from
  `ledgers/payload_execution_queue.md` and added `CAND-T001-C6-015` as a
  candidate-admissible but route-unresolved row;
- `FJ116` later consumed `PAY-T001-CAND-C6-016-2026-001` from
  `ledgers/payload_execution_queue.md` and added `CAND-T001-C6-016` as a
  candidate-admissible but route-unresolved row;
- `FJ117` later consumed `PAY-T001-CAND-C6-017-2026-001` from
  `ledgers/payload_execution_queue.md` and added `CAND-T001-C6-017` as a
  candidate-admissible but route-unresolved row;
- `FJ118` later consumed `PAY-T001-CAND-C6-018-2026-001` from
  `ledgers/payload_execution_queue.md` and added `CAND-T001-C6-018` as a
  candidate-admissible but route-unresolved row;
- `FJ119` later consumed `PAY-T001-CAND-C6-019-2026-001` from
  `ledgers/payload_execution_queue.md` and added `CAND-T001-C6-019` as a
  candidate-admissible but route-unresolved row;
- `FJ120` later consumed `PAY-T001-CAND-C6-020-2026-001` from
  `ledgers/payload_execution_queue.md` and added `CAND-T001-C6-020` as a
  candidate-admissible but route-unresolved row;
- `FJ121` later consumed `PAY-T001-CAND-C6-021-2026-001` from
  `ledgers/payload_execution_queue.md` and added `CAND-T001-C6-021` as a
  candidate-admissible but route-unresolved row;
- `FJ122` later consumed `PAY-T001-CAND-C6-022-2026-001` from
  `ledgers/payload_execution_queue.md` and added `CAND-T001-C6-022` as a
  candidate-admissible but route-unresolved row;
- `FJ123` later consumed `PAY-T001-CAND-C6-023-2026-001` from
  `ledgers/payload_execution_queue.md` and added `CAND-T001-C6-023` as a
  candidate-admissible but route-unresolved row;
- `FJ124` later consumed `PAY-T001-CAND-C6-024-2026-001` from
  `ledgers/payload_execution_queue.md` and added `CAND-T001-C6-024` as a
  candidate-admissible but route-unresolved row;
- `FJ125` later consumed `PAY-T001-CAND-C6-025-2026-001` from
  `ledgers/payload_execution_queue.md` and added `CAND-T001-C6-025` as a
  candidate-admissible but route-unresolved row;
- `FJ126` later consumed `PAY-T001-CAND-C6-026-2026-001` from
  `ledgers/payload_execution_queue.md` and added `CAND-T001-C6-026` as a
  candidate-admissible but route-unresolved row;
- `FJ127` later consumed `PAY-T001-CAND-C6-027-2026-001` from
  `ledgers/payload_execution_queue.md` and added `CAND-T001-C6-027` as a
  candidate-admissible but route-unresolved row;
- `FJ128` later consumed `PAY-T001-CAND-C6-028-2026-001` from
  `ledgers/payload_execution_queue.md` and added `CAND-T001-C6-028` as a
  candidate-admissible but route-unresolved row;
- `FJ129` later consumed `PAY-T001-CAND-C6-029-2026-001` from
  `ledgers/payload_execution_queue.md` and added `CAND-T001-C6-029` as a
  candidate-admissible but route-unresolved row;
- `FJ130` later consumed `PAY-T001-CAND-C6-030-2026-001` from
  `ledgers/payload_execution_queue.md` and added `CAND-T001-C6-030` as a
  candidate-admissible but route-unresolved row;
- `FJ131` later consumed `PAY-T001-CAND-C6-031-2026-001` from
  `ledgers/payload_execution_queue.md` and added `CAND-T001-C6-031` as a
  candidate-admissible but route-unresolved row;
- `FJ132` later consumed `PAY-T001-CAND-C6-032-2026-001` from
  `ledgers/payload_execution_queue.md` and added `CAND-T001-C6-032` as a
  candidate-admissible but route-unresolved row;
- `FJ133` later consumed `PAY-T001-CAND-C6-033-2026-001` from
  `ledgers/payload_execution_queue.md` and added `CAND-T001-C6-033` as a
  candidate-admissible but route-unresolved row;
- `FJ134` later consumed `PAY-T001-CAND-C6-034-2026-001` from
  `ledgers/payload_execution_queue.md` and added `CAND-T001-C6-034` as a
  candidate-admissible but route-unresolved row;
- `FJ135` later consumed `PAY-T001-CAND-C6-035-2026-001` from
  `ledgers/payload_execution_queue.md` and added `CAND-T001-C6-035` as a
  candidate-admissible but route-unresolved row;
- `FJ136` later consumed `PAY-T001-CAND-C6-036-2026-001` from
  `ledgers/payload_execution_queue.md` and added `CAND-T001-C6-036` as a
  candidate-admissible but route-unresolved row;
- `FJ137` later consumed `PAY-T001-CAND-C6-037-2026-001` from
  `ledgers/payload_execution_queue.md` and added `CAND-T001-C6-037` as a
  candidate-admissible but route-unresolved row;
- `OQ-126` is resolved only for rows 001--037, while `OQ-127` /
  `OBL-C6-004` govern follow-up work on `CAND-T001-C6-001`, `OQ-128` /
  `OBL-C6-005` govern follow-up work on `CAND-T001-C6-002`, `OQ-129` /
  `OBL-C6-006` govern follow-up work on `CAND-T001-C6-003`, and `OQ-130` /
  `OBL-C6-007` govern follow-up work on `CAND-T001-C6-004`, and `OQ-131` /
  `OBL-C6-008` govern follow-up work on `CAND-T001-C6-005`, and `OQ-132` /
  `OBL-C6-009` govern follow-up work on `CAND-T001-C6-006`, and `OQ-133` /
  `OBL-C6-010` govern follow-up work on `CAND-T001-C6-007`, and `OQ-134` /
  `OBL-C6-011` govern follow-up work on `CAND-T001-C6-008`, and `OQ-135` /
  `OBL-C6-012` govern follow-up work on `CAND-T001-C6-009`, and `OQ-136` /
  `OBL-C6-013` govern follow-up work on `CAND-T001-C6-010`, and `OQ-137` /
  `OBL-C6-014` govern follow-up work on `CAND-T001-C6-011`, and `OQ-138` /
  `OBL-C6-015` govern follow-up work on `CAND-T001-C6-012`, and `OQ-139` /
  `OBL-C6-016` govern follow-up work on `CAND-T001-C6-013`, and `OQ-140` /
  `OBL-C6-017` govern follow-up work on `CAND-T001-C6-014`, and `OQ-141` /
  `OBL-C6-018` govern follow-up work on `CAND-T001-C6-015`, and `OQ-142` /
  `OBL-C6-019` govern follow-up work on `CAND-T001-C6-016`, and `OQ-143` /
  `OBL-C6-020` govern follow-up work on `CAND-T001-C6-017`, and `OQ-144` /
  `OBL-C6-021` govern follow-up work on `CAND-T001-C6-018`, and `OQ-145` /
  `OBL-C6-022` govern follow-up work on `CAND-T001-C6-019`, and `OQ-146` /
  `OBL-C6-023` govern follow-up work on `CAND-T001-C6-020`, and `OQ-147` /
  `OBL-C6-024` govern follow-up work on `CAND-T001-C6-021`, and `OQ-148` /
  `OBL-C6-025` govern follow-up work on `CAND-T001-C6-022`, and `OQ-149` /
  `OBL-C6-026` govern follow-up work on `CAND-T001-C6-023`, and `OQ-150` /
  `OBL-C6-027` govern follow-up work on `CAND-T001-C6-024`, and `OQ-151` /
  `OBL-C6-028` govern follow-up work on `CAND-T001-C6-025`, and `OQ-152` /
  `OBL-C6-029` govern follow-up work on `CAND-T001-C6-026`, and `OQ-153` /
  `OBL-C6-030` govern follow-up work on `CAND-T001-C6-027`, and `OQ-154` /
  `OBL-C6-031` govern follow-up work on `CAND-T001-C6-028`, and `OQ-155` /
  `OBL-C6-032` govern follow-up work on `CAND-T001-C6-029`, and `OQ-156` /
  `OBL-C6-033` govern follow-up work on `CAND-T001-C6-030`, and `OQ-157` /
  `OBL-C6-034` govern follow-up work on `CAND-T001-C6-031`, and `OQ-158` /
  `OBL-C6-035` govern follow-up work on `CAND-T001-C6-032`, and `OQ-159` /
  `OBL-C6-036` govern follow-up work on `CAND-T001-C6-033`, `OQ-160` /
  `OBL-C6-037` govern follow-up work on `CAND-T001-C6-034`, and
  `OQ-161` / `OBL-C6-038` govern follow-up work on `CAND-T001-C6-035`, and
  `OQ-162` / `OBL-C6-039` govern follow-up work on `CAND-T001-C6-036`, and
  `OQ-163` / `OBL-C6-040` govern follow-up work on `CAND-T001-C6-037`;
- no mathematical target lane is active beyond bounded payload-gated
  candidate intake;
- template prompts are not executable until concretely filled and accepted
  under `ledgers/payload_intake_protocol.md`;
- future numbered work requires a concrete accepted payload.

The completed governance/alignment prompts in `the 15-next-steps.md`,
including the README/charter alignment pass, do not create mathematical
progress by themselves. They are permitted only to clarify status, preserve
payload discipline, and prevent accidental theorem promotion, target
  reactivation, source-summary drift, or creation of later numbered work
  without a gate-satisfying payload.

## Continue payload workflow

`ledgers/payload_execution_queue.md` is the current callback queue. The exact
user prompt `Continue payload` selects the first row marked
`Ready for intake`, expands the row using the common inherited fields in that
file, applies `ledgers/payload_intake_protocol.md`, and consumes at most one
row per run.

Rows in the queue are not accepted in bulk. A selected row must be marked
`Completed`, `Rejected`, or `Blocked` with a short reason before stopping.
Generic continuation language does not trigger this workflow.

## GitHub persistence policy

The GitHub repository `flaritycat/KTheory_FarrelJones` is the durable archive and source of truth.

Do not claim that something has been saved, committed, pushed, or updated in GitHub unless that action has actually occurred and been verified.
