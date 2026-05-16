# T-001 Residual Ledger

## Status

First-pass residual ledger created in `FJ28`. First concrete attack surface
selected in `FJ29`. Brown/BNS kernel-recognition route checked in `FJ30`.
First Brown calibration example completed in `FJ31`. Nontrivial next Brown
test case selected in `FJ32`. Concrete \(G_{2,3}\) route bridge completed in
`FJ33`. The \(G_{p,q}\)-family route bridge was completed in `FJ36`, `FJ37`
selected beyond-Brown `RB-004` source selection as the next target, `FJ38`
selected the normal-subgroup source cluster, and `FJ39` verified the
Karrass--Solitar finitely presented-kernel bridge. `FJ40` audits that
subroute and selects no new non-Brown source-ready test case. `FJ41` verifies
the original BNS finite-generation criterion but makes no residual
subtraction. `FJ43` pauses automatic `RB-004` source-cluster continuation,
`FJ44` selects `RB-005` as the next attack packet, `FJ45` records that only
the full \(\mathcal{FJ}\) finite-index bridge is currently usable, and
`FJ46` selects an `FJ02` source-convention interruption before further
proof-sensitive `RB-005` work. `FJ02` completes that source-convention
interruption and returns `RB-005` to finite-index bridge source selection.
`FJ47` verifies the `FJCw` finite-index overgroup bridge, but not a plain
coefficient-only bridge. `FJ48` audits `RB-005` and records that no current
`T-001` finite-index cleanup case is `FJCw-ready`. `FJ49` checks the direct
CAT(0) finite-extension lane and records it as unavailable for route use.

## Warning

This ledger does not identify counterexamples, negative Farrell--Jones
results, or groups outside the Farrell--Jones conjecture. It records only the
cases not yet removed by the repository's current source-verified route data.

## Removed by recorded routes

| Route | Removal criterion | Module |
|---|---|---|
| Hyperbolic route | A source-verified bridge to word-hyperbolicity is recorded. | FJ23 |
| Finite-dimensional CAT(0) route | A source-verified finite-dimensional CAT(0)-group bridge is recorded; compact finite-dimensional special cube complex groups are recorded as CAT(0)-route bridge cases. | FJ24 |
| Virtually solvable route | A source-verified or elementary internal bridge to virtual solvability is recorded. | FJ25 |
| Hyperbolic-by-cyclic/free-by-cyclic route | A source-verified bridge to \(H\rtimes_\Phi\mathbb Z\), with \(H\) virtually torsion-free hyperbolic, or to \(F_n\rtimes_\Phi\mathbb Z\) with \(n<\infty\), is recorded. | FJ26 |
| Inheritance routes | A source-verified inheritance bridge is recorded and the source version flag is preserved. | FJ27 |

## Active residual buckets

| Bucket | Description | Why not removed yet | Related open questions |
|---|---|---|---|
| RB-001 | Groups that may be hyperbolic, CAT(0), virtually solvable, hyperbolic-by-cyclic, or inherited from known cases, but no bridge is recorded | The route exists only after the bridge is source-verified or proved internally | OQ-026, OQ-038 |
| RB-002 | Locally indicable-only torsion-free one-relator data | Local indicability is structural and is not a Farrell--Jones theorem route in the project | OQ-026 |
| RB-003 | One-relator hierarchy-only data from the Linton vocabulary | A hierarchy is not automatically a bridge to hyperbolicity, CAT(0), virtual solvability, a mapping torus, or an inheritance row | OQ-038, OQ-039 |
| RB-004 | Epimorphisms to \(\mathbb Z\) or HNN splittings with unknown kernel control | `FJ26` requires a mapping-torus bridge or a finite-rank free-by-cyclic bridge | OQ-036 |
| RB-005 | Virtually compact special or finite-index bridge cases with formulation gaps | `FJ48` finds no current `T-001` case with `FJCw` subgroup input; `FJ49` does not license a direct CAT(0) finite-extension route; the bucket now needs a route-delta checkpoint before more source work | OQ-032, OQ-068, OQ-069, OQ-070, OQ-071 |
| RB-006 | Compact special or CAT(0)-looking one-relator cases beyond the hyperbolic route | The project needs a source-verified bridge not already absorbed by `FJ23` | OQ-033 |
| RB-007 | Virtually solvable-looking one-relator cases without a recognition source | `FJ25` deliberately does not classify virtually solvable one-relator groups | OQ-034 |
| RB-008 | Countable-free-kernel or extension cases without exact inheritance data | `FJ27` requires the exact sequence, quotient status, and source version flag | OQ-037 |

## Candidate next attack surfaces

| Candidate | Reason to consider | Main dependency risk |
|---|---|---|
| Finite-rank free-kernel recognition over \(\mathbb Z\) | It could turn epimorphism/HNN data into a finite-rank free-by-cyclic route | Brown/BNS or the `FJ38` normal-subgroup source cluster must be verified before theorem use |
| Finite-index and virtually compact special handling | It could unlock virtual-special cases not cleanly handled by the compact CAT(0) bridge | Version reconciliation between full \(\mathcal{FJ}\), coefficient K-theory, and CAT(0) route language |
| Compact special or CAT(0) cases beyond hyperbolicity | It targets a concrete geometric bridge bucket left open by `FJ24` | Needs one-relator cubulation/specialness sources beyond the first-pass Haglund--Wise bridge |
| Virtually solvable one-relator recognition | It could convert `FJ25` from a conditional row into a more explicit example ledger | Needs a classification or recognition source |
| Hierarchy-to-route extraction | It uses the adopted Linton hierarchy vocabulary to search for route bridges | Must not treat hierarchy language as a Farrell--Jones route without an additional source |

## FJ29 selected attack surface

Selected bucket: `RB-004`, epimorphisms to \(\mathbb Z\) or HNN splittings
with unknown kernel control.

Selected first source to verify: Brown (1987), *Trees, valuations, and the
Bieri--Neumann--Strebel invariant*.

Reason for selection: a verified finite-rank free-kernel bridge would feed
directly into the `FJ26` finite-rank free-by-cyclic route, while the source
verification task is narrow enough for a single module.

Non-use warning: `FJ29` did not use Brown (1987) as a theorem source and did
not assert that any one-relator epimorphism has finitely generated kernel.
`FJ30` below records the later limited verification.

## FJ30 Brown/BNS verification update

Brown (1987) is now checked at first-pass level for selected `RB-004` cases.
The usable project criterion is stored in `ledgers/t001_kernel_recognition.md`.

Scope of use:

- Brown gives a finite-generation criterion for kernels of surjections
  \(G\to\mathbb Z\) via Proposition 3.1 and Corollary 3.2.
- Brown gives a computable two-generator one-relator criterion via Theorems
  4.2--4.4.
- Brown does not give a global positive theorem for every one-relator
  epimorphism to \(\mathbb Z\).

## FJ31 Brown calibration update

`FJ31` applies the Brown criterion to
\(\langle x,y\mid xyx^{-1}y^{-1}\rangle\) with
\(\chi(x)=1\) and \(\chi(y)=0\).

Outcome:

- both \([\chi]\) and \([-\chi]\) pass Brown's zero-on-one-generator
  maximum-count test;
- \(\ker(\chi)=\langle y\rangle\cong F_1\);
- the example supplies a finite-rank free-by-cyclic bridge;
- the example is already removed by the virtually solvable route and should
  not be counted as a new residual subtraction.

## FJ32 nontrivial Brown selection update

`FJ32` selects
\[
G_{2,3}=\langle x,y\mid x^2y^{-3}\rangle,\qquad
\chi(x)=3,\quad \chi(y)=2
\]
as the next Brown test case.

Project status:

- the presentation is nonabelian by an internal quotient map to \(S_3\);
- preliminary Brown initial-segment values pass in both directions;
- no virtual-solvability bridge has been recorded;
- no target-status bridge for `T-001` has been recorded;
- no finite-rank free-kernel bridge has been recorded.

## FJ33 worked bridge update

`FJ33` completes the \(G_{2,3}\) worked example.

Outcome:

- both \([\chi]\) and \([-\chi]\) pass Brown's maximum-count test;
- \(G_{2,3}\cong F_2\rtimes_\varphi\mathbb Z\);
- \(\ker(\chi)\cong F_2\);
- \(G_{2,3}\) is internally verified as a torsion-free one-relator group;
- the concrete example is removed by the `FJ26` finite-rank
  free-by-cyclic route.

## FJ34 nearby family boundary update

`FJ34` tests the family
\[
G_{p,q}=\langle x,y\mid x^p y^{-q}\rangle,\qquad p,q\geq2,\quad
\gcd(p,q)=1,
\]
with \(\chi_{p,q}(x)=q\) and \(\chi_{p,q}(y)=p\).

Outcome:

- both \([\chi_{p,q}]\) and \([-\chi_{p,q}]\) pass Brown's
  maximum-count test;
- Brown gives finite generation of \(\ker(\chi_{p,q})\);
- no finite-rank free-kernel bridge is recorded for the family;
- no family-level `FJ26` subtraction is made.

## FJ35 source-selection update

`FJ35` selects the candidate Bass--Serre bridge for the \(G_{p,q}\)-family.
The intended route is:

- use the presentation-level cyclic-amalgam shape
  \(\langle x\rangle *_{\langle z\rangle}\langle y\rangle\);
- observe that \(K_{p,q}=\ker(\chi_{p,q})\) intersects all conjugates of the
  cyclic vertex groups trivially;
- verify in Serre's *Trees* that this implies \(K_{p,q}\) is free;
- combine with Brown finite generation from `FJ34`.

No residual subtraction is made yet. The Bass--Serre theorem statement still
needs exact source verification.

## FJ36 route-subtraction update

`FJ36` verifies the Bass--Serre freeness bridge for the \(G_{p,q}\)-family.
The resulting project-state route is:

- the cyclic-amalgam presentation gives a Bass--Serre tree \(T_{p,q}\) with
  vertex stabilizers conjugate to \(\langle x\rangle\) or
  \(\langle y\rangle\);
- \(K_{p,q}=\ker(\chi_{p,q})\) intersects all those conjugates trivially;
- \(K_{p,q}\) acts freely on \(T_{p,q}\), hence is free;
- Brown finite generation from `FJ34` makes \(K_{p,q}\cong F_n\) for finite
  \(n\);
- \(\chi_{p,q}\) splits because \(\gcd(p,q)=1\), so
  \(G_{p,q}\cong F_n\rtimes\mathbb Z\);
- the \(G_{p,q}\)-family is removed from the active residual through the
  `FJ26` finite-rank free-by-cyclic route.

This subtraction is family-specific. It does not prove the Farrell--Jones
conjecture for all torsion-free one-relator groups and does not compute the
rank \(n\).

## FJ37 residual-audit update

`FJ37` audits the residual after the \(G_{p,q}\)-family subtraction.

Outcome:

- the exact rank of \(K_{p,q}\) is not route-critical, because `FJ36` already
  gives finite-rank freeness;
- no additional \(G_{p,q}\)-family computation is needed before moving on;
- `RB-004` remains active because Brown's checked route is limited to
  compatible two-generator one-relator presentations;
- `OQ-044`, source selection for `RB-004` cases outside Brown's checked
  two-generator criterion, is selected as the next target.

This audit keeps the \(G_{p,q}\)-family bridge separate from any global
kernel-recognition theorem.

## FJ38 beyond-Brown source-selection update

`FJ38` selects a source cluster for `RB-004` cases outside Brown's checked
two-generator one-relator criterion.

Selected for `FJ39` verification:

- Bieri--Neumann--Strebel (1987), for direct BNS finite-generation context;
- Bieri--Renz (1988), as secondary finiteness-property context;
- Bieri (1976), for normal subgroups in duality/CD2 settings;
- Karrass--Solitar (1978), for one-relator groups with finitely presented
  normal subgroups.

Background only at this stage:

- Friedl--Tillmann (2020), Brown-adjacent two-generator marked-polytope
  context;
- Kielak (2020), possible later BNS/Newton-polytope context with specialized
  hypotheses.

No residual bucket is removed by `FJ38`. It selects sources; it does not
verify theorem hypotheses or record a new free-kernel bridge.

## FJ39 source-verification update

`FJ39` verifies the main Karrass--Solitar bridge for one-relator groups with a
nontrivial finitely presented normal subgroup of infinite index.

Outcome:

- the checked bridge requires finite presentation of the normal subgroup;
- finite generation alone is not enough for this bridge;
- the output is an infinite cyclic or infinite dihedral extension of a
  finitely generated free group;
- direct BNS theorem use remains open;
- Bieri (1976) is recorded only as a cited dependency inside the
  Karrass--Solitar proof until the primary source is checked;
- no residual bucket is removed yet.

## FJ40 finitely presented-kernel test-selection update

`FJ40` audits the current repository for source-ready finitely
presented-kernel candidates.

Outcome:

- the commutator calibration example is not a non-Brown residual test case;
- \(G_{2,3}\) is already removed through the `FJ26` route;
- the \(G_{p,q}\)-family is already removed through the `FJ26` route after
  the `FJ36` Bass--Serre bridge;
- no new beyond-Brown `RB-004` example currently has a recorded nontrivial
  finitely presented normal subgroup of infinite index;
- the Karrass--Solitar bridge remains a cleanup theorem, not an example
  generator;
- no residual bucket is removed by `FJ40`.

## FJ41 direct BNS verification update

`FJ41` verifies Bieri--Neumann--Strebel (1987), Theorem B1, as a direct
finite-generation theorem for normal subgroups with abelian quotient.

Outcome:

- for finitely generated \(G\), normal \(N\trianglelefteq G\), and \(G/N\)
  abelian, \(N\) is finitely generated if and only if
  \(S(G,N)\subseteq\Sigma(G)\);
- for a surjection \(\chi\colon G\twoheadrightarrow\mathbb Z\), this becomes
  the two-sided \([\chi]\), \([-\chi]\) criterion for finite generation of
  \(\ker(\chi)\);
- BNS theorem use is now source-verified for finite generation;
- no new BNS-invariant computation is recorded;
- no finite-rank free-kernel bridge is recorded;
- no residual bucket is removed by `FJ41`.

## FJ42 Bieri route-delta update

`FJ42` checks Bieri (1976) source access and route impact.

Outcome:

- Bieri (1976) bibliographic and ScienceDirect/Elsevier metadata are checked;
- the primary theorem text is not directly extractable in this environment;
- comparison sources report finite-presentation or type-\(VFP\) hypotheses,
  not mere finite generation;
- Bieri is not promoted to source-verified theorem use;
- the finite-presentation bottleneck from `FJ39` remains;
- no residual bucket is removed by `FJ42`.

## FJ43 route-delta checkpoint update

`FJ43` audits the BNS/Bieri--Renz/Bieri/Karrass--Solitar source cluster after
`FJ39`--`FJ42`.

Outcome:

- the direct BNS theorem map remains available, but no new
  \(\Sigma(G)\)-membership computation is recorded;
- the Karrass--Solitar bridge remains available only after a nontrivial
  finitely presented normal subgroup of infinite index is source-ready;
- Bieri (1976) remains unavailable for theorem use until the primary theorem
  text is checked directly;
- Bieri--Renz (1988) is not selected as the next automatic source check,
  because no concrete higher-finiteness need is attached to a candidate;
- automatic `RB-004` source-cluster continuation is paused;
- no residual bucket is removed by `FJ43`.

## FJ44 residual-bucket comparison update

`FJ44` compares the remaining residual buckets after the `RB-004` pause.

Outcome:

- `RB-004` remains recorded but is not continued automatically;
- `RB-005`, finite-index and virtually compact special formulation handling,
  is selected as the next attack packet;
- `RB-006`, `RB-007`, hierarchy-to-route extraction, and `RB-008` are
  deferred until a more bounded source or candidate is selected;
- the selected `RB-005` packet is tied to `FJ24` virtual-special cautions,
  `FJ27` version-aware finite-index inheritance, and the Karrass--Solitar
  infinite-dihedral cleanup issue from `FJ39`;
- no residual bucket is removed by `FJ44`.

## Next action

Begin `FJ45`, finite-index formulation bridge checkpoint for `RB-005`.

## FJ45 finite-index formulation bridge update

`FJ45` completes the first finite-index checkpoint for `RB-005`.

Outcome:

- the full \(\mathcal{FJ}\) finite-index overgroup row from
  `ledgers/inheritance_properties.md` is usable only with its full-formulation
  flag;
- no coefficient K-theory finite-index overgroup bridge is recorded in the
  repository;
- no direct CAT(0) finite-extension bridge is recorded in the repository;
- no `FJCw` or `FICwF` comparison is available for proof-sensitive use;
- virtually compact special cases remain blocked for coefficient/CAT(0)
  route subtraction unless a version-compatible finite-index bridge is
  verified;
- the Karrass--Solitar infinite-dihedral alternative remains blocked for the
  coefficient free-by-cyclic route unless a compatible finite-index passage
  is verified;
- no residual bucket is removed by `FJ45`.

## Historical next action after FJ45

Begin `FJ46`, deciding whether `RB-005` proceeds by source-verifying a
coefficient K-theory finite-index bridge or by interrupting for
`FJ02`/source-convention reconciliation.

## FJ46 source-convention decision update

`FJ46` resolves the next-move decision after the finite-index checkpoint.

Outcome:

- do not continue `RB-005` by a narrow coefficient finite-index theorem
  search as the immediate next step;
- interrupt for `FJ02`, because source-level coefficient, full
  \(\mathcal{FJ}\), CAT(0)-route, `FJCw`, and `FICwF` labels are now
  proof-level inputs;
- keep the full \(\mathcal{FJ}\) finite-index bridge available only with its
  full-formulation flag;
- make no residual bucket subtraction.

## Historical next action after FJ46

Begin `FJ02`, the additive-category/source-convention formulation module.

## FJ02 source-convention interruption update

`FJ02` completes the source-convention interruption selected by `FJ46`.

Outcome:

- Bartels--Reich Conjecture 3.2 is adopted as the first-pass project
  formulation for coefficient K-theory FJC;
- source labels remain separated: coefficient K-theory FJC, full
  \(\mathcal{FJ}\), `FJCw`, `FICwF`, and simplified ring-coefficient FJ are
  not collapsed without a checked comparison;
- `RB-005` can resume, but it still lacks a coefficient K-theory
  finite-index overgroup bridge;
- no residual bucket is removed by `FJ02`.

## FJ02 handoff resolved by FJ47

The `FJ02` handoff to finite-index bridge source selection was completed in
`FJ47`; the active follow-up is now the `FJ48` audit of which `RB-005`
cases carry source-verified `FJCw` subgroup input.

## FJ47 FJCw finite-index bridge update

`FJ47` completes the finite-index bridge source-selection pass after `FJ02`.

Outcome:

- the finite-wreath-product version `FJCw` passes to finite-index
  overgroups, source-verified from Bartels--Lueck--Reich--Rueping
  Remark 6.2;
- plain coefficient K-theory finite-index overgroup passage remains
  unauthorized inside the project;
- the bridge can be applied only when the finite-index subgroup has
  source-verified `FJCw` input;
- no residual bucket is removed by `FJ47`.

## FJ48 FJCw application audit update

`FJ48` audits whether the `FJ47` bridge has an immediate `T-001` target.

Outcome:

- no current `T-001`/`RB-005` finite-index case is recorded with
  source-verified `FJCw` subgroup input;
- the virtual compact special path has compact-special/CAT(0) subgroup input,
  not `FJCw`;
- the Karrass--Solitar infinite-dihedral path has at most a
  finite-rank-free-by-cyclic coefficient route if a concrete candidate is
  selected, not `FJCw`;
- Artin-related `FJCw` rows remain available in the broader project but do
  not count as `T-001` residual progress;
- no residual bucket is removed by `FJ48`;
- the next `RB-005` move is `FJ49`, direct CAT(0) finite-extension source
  checking.

## FJ49 CAT(0) finite-extension bridge update

`FJ49` checks the direct CAT(0) finite-extension lane for virtual compact
special cases.

Outcome:

- finite-index subgroups of CAT(0)-groups are again CAT(0)-groups, but this
  is the wrong direction for `RB-005`;
- Ruane records finite extensions of CAT(0)-groups as a question, not a
  theorem;
- the Serre product construction supplies a proper isometric action on a
  finite product of CAT(0)-spaces, but cocompactness remains missing;
- the virtual compact special path is not removed by a direct CAT(0)
  finite-extension bridge;
- no residual bucket is removed by `FJ49`;
- the next move is `FJ50`, a checkpoint deciding whether to pause `RB-005`
  and pivot to another attack packet.

## Next action

Begin `FJ50`, an `RB-005` route-delta checkpoint and pivot decision.
