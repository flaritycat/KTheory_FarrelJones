# T-001 Residual Ledger

## Status

First-pass residual ledger created in `FJ28`. First concrete attack surface
selected in `FJ29`. Brown/BNS kernel-recognition route checked in `FJ30`.
First Brown calibration example completed in `FJ31`.

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
| Finite-rank free-kernel recognition over \(\mathbb Z\) | It could turn epimorphism/HNN data into a finite-rank free-by-cyclic route | Brown/BNS or another kernel-finiteness source must be verified before theorem use |
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

## Next action

Use `FJ32` to choose and run a nontrivial Brown test case, preferably one not
already removed by the virtually solvable route.
