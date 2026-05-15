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

The next module is `FJ27`, source-verified inheritance-route
subtraction for `T-001`. Its task is to decide which remaining
one-relator cases can be removed by the inheritance rows already
recorded in `FJ12`, while keeping version flags separate between
coefficient K-theory rows and Lueck's full \(\mathcal{FJ}\) survey
class.

## GitHub persistence policy

The GitHub repository `flaritycat/KTheory_FarrelJones` is the durable archive and source of truth.

Do not claim that something has been saved, committed, pushed, or updated in GitHub unless that action has actually occurred and been verified.
