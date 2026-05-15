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

Current procedural status: the `cycle_001` module list is complete
except for the intentionally deferred `FJ02`. The cycle reflection has
been written in `reflections/cycle_001_reflection.md`.

## Cycle 001 reflection

Current status: `reflections/cycle_001_reflection.md` closes the first
twenty-module cycle. Its main conclusion is that the next cycle should
begin with `T-001`, torsion-free one-relator residual gap analysis, and
that the first concrete step should be `FJ21`, one-relator structure
source selection.

The reflection also records that `FJ02` remains deferred but not
forgotten. It becomes urgent before the project uses source-level
coefficient statements, finite-wreath-product variants, `FJCw`, or
`FICwF` as internal proof hypotheses.

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
and selects `OQ-044` as the next active target. The next module is
`FJ38`, `RB-004` beyond-Brown source selection. Its task is to identify
or verify the next source for kernel-recognition cases outside Brown's
checked two-generator criterion, without using any unverified theorem as
route input.

## GitHub persistence policy

The GitHub repository `flaritycat/KTheory_FarrelJones` is the durable archive and source of truth.

Do not claim that something has been saved, committed, pushed, or updated in GitHub unless that action has actually occurred and been verified.
