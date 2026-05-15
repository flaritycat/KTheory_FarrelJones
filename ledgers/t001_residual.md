# T-001 Residual Ledger

## Status

First-pass residual ledger created in `FJ28`. First concrete attack surface
selected in `FJ29`. Brown/BNS kernel-recognition route checked in `FJ30`.
First Brown calibration example completed in `FJ31`. Nontrivial next Brown
test case selected in `FJ32`. Concrete \(G_{2,3}\) route bridge completed in
`FJ33`. The \(G_{p,q}\)-family route bridge was completed in `FJ36`, `FJ37`
selected beyond-Brown `RB-004` source selection as the next target, `FJ38`
selected the normal-subgroup source cluster, and `FJ39` verified the
Karrass--Solitar finitely presented-kernel bridge.

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
| RB-005 | Virtually compact special or finite-index bridge cases with formulation gaps | `FJ24` and `FJ27` keep finite-index and version flags separate | OQ-032 |
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

## Next action

Use `FJ40` to select a concrete finitely presented-kernel test case for
`RB-004`, or record that no such test case is source-ready.
