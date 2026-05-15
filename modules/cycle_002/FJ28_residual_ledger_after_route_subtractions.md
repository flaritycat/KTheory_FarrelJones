# Module FJ28. Residual ledger after route subtractions for T-001

## Status

Completed

## Module type

Attack surface / Reflection / Theorem map

## Problem

Assemble the conservative residual ledger for `T-001`, the torsion-free
one-relator residual gap analysis, after the named route subtractions in
`FJ23`--`FJ26` and the version-aware inheritance-route subtraction in `FJ27`.

The delicate point is interpretation. A group or subclass not removed by the
project's current route tables is not thereby outside Farrell--Jones. It is
only not yet covered by a recorded bridge in this repository.

## Input

This module uses:

- `FJ19`, the one-relator status dossier and Lueck open-status warning;
- `FJ20`, the target-selection module for `T-001`;
- `FJ21`, the one-relator source-toolkit selection;
- `FJ22`, the one-relator hierarchy vocabulary;
- `FJ23`, hyperbolic-route subtraction;
- `FJ24`, finite-dimensional CAT(0)-route subtraction;
- `FJ25`, virtually solvable-route subtraction;
- `FJ26`, hyperbolic-by-cyclic/free-by-cyclic route subtraction;
- `FJ27`, version-aware inheritance-route subtraction;
- `OPEN_QUESTIONS.md` and `ledgers/source_status.md`;
- Lueck's open-status warning as already recorded in `FJ19`;
- Linton's hierarchy source as already recorded in `FJ22`.

## Output target

A reusable residual ledger for `T-001`:

- which cases are removed by recorded routes;
- which residual buckets remain;
- which open questions correspond to those buckets;
- which candidate attack surfaces are plausible for `FJ29`.

## Definitions

**Definition.** The `T-001` residual is the part of the torsion-free
one-relator target not yet removed by the repository's recorded route bridges.

**Definition.** A residual bucket is a bookkeeping category collecting cases
that fail to be removed for the same recorded reason, such as a missing
finite-rank free-kernel source or a missing finite-index formulation bridge.

**Definition.** An attack-surface candidate is a residual bucket that is
specific enough to support the next module's source search or reduction
attempt.

**Warning.** The `T-001` residual is not a theorem-level mathematical class.
It is a project-state object. It may contain groups that are already known to
satisfy Farrell--Jones in the literature but whose bridges have not yet been
recorded in this repository.

## Main work

### Removed route ledger

The route-subtraction pass now has the following first-pass status.

| Route | Removal criterion | Status |
|---|---|---|
| Hyperbolic route | Source-verified bridge to word-hyperbolicity | Completed in `FJ23`. |
| Finite-dimensional CAT(0) route | Source-verified finite-dimensional CAT(0)-group bridge; compact finite-dimensional special cube complex bridge | Completed in `FJ24`. |
| Virtually solvable route | Source-verified or elementary internal bridge to virtual solvability | Completed in `FJ25`. |
| Hyperbolic-by-cyclic/free-by-cyclic route | Source-verified mapping-torus bridge \(H\rtimes_\Phi\mathbb Z\) with \(H\) virtually torsion-free hyperbolic, or finite-rank free-by-cyclic bridge | Completed in `FJ26`. |
| Inheritance routes | Exact inheritance bridge with version flag preserved | Completed in `FJ27`. |

### Residual buckets

The current residual is organized into the following buckets, also recorded in
`ledgers/t001_residual.md`.

| Bucket | Residual theme | Missing bridge or source |
|---|---|---|
| RB-001 | Possible known-route cases with no recorded bridge | Source verification for the relevant route. |
| RB-002 | Locally indicable-only information | A Farrell--Jones route, since local indicability is structural only. |
| RB-003 | One-relator hierarchy-only information | A bridge from hierarchy data to hyperbolic, CAT(0), virtual-solvable, mapping-torus, or inheritance hypotheses. |
| RB-004 | Epimorphisms to \(\mathbb Z\) or HNN splittings with unknown kernel control | A finite-rank free-kernel or virtually torsion-free hyperbolic kernel source. |
| RB-005 | Virtually compact special or finite-index bridge cases | A source-compatible finite-index/formulation bridge. |
| RB-006 | Compact special or CAT(0)-looking cases beyond the hyperbolic route | One-relator cubulation or specialness sources beyond the first-pass bridge. |
| RB-007 | Virtually solvable-looking one-relator cases | A classification or recognition source for virtual solvability. |
| RB-008 | Countable-free-kernel or extension cases | Exact extension data, quotient status, and version-compatible inheritance source use. |

### Candidate attack surfaces for FJ29

The next module should select one of the following as the first concrete
post-subtraction attack surface.

| Candidate | Reason to consider | Risk |
|---|---|---|
| Finite-rank free-kernel recognition over \(\mathbb Z\) | It could convert epimorphism/HNN data into the `FJ26` finite-rank free-by-cyclic route. | Brown's BNS source, or an alternative, must be verified before theorem use. |
| Finite-index and virtually compact special handling | It addresses a concrete gap left by `FJ24` and `FJ27`. | The project must keep coefficient K-theory, CAT(0), and full \(\mathcal{FJ}\) formulations separate. |
| Compact special or CAT(0) cases beyond hyperbolicity | It could identify geometric one-relator cases not already removed by `FJ23`. | Requires one-relator cubulation/specialness sources beyond the first-pass Haglund--Wise bridge. |
| Virtually solvable one-relator recognition | It could make the `FJ25` route more explicit. | Requires a reliable classification or recognition source. |
| Hierarchy-to-route extraction | It makes direct use of the Linton hierarchy vocabulary selected in `FJ22`. | Must not turn hierarchy language into an unstated Farrell--Jones theorem. |

**Selection pressure.** The finite-rank free-kernel recognition candidate is
currently the most natural first attack surface because it directly addresses
an open bridge between one-relator splitting data and the `FJ26` route.
However, `FJ28` does not select it as the next target; that selection belongs
to `FJ29`.

## Proposition / Theorem / Conjecture / Example

**Proposition.** The `T-001` residual after `FJ28` is a project-state ledger,
not a class of groups known to fail the Farrell--Jones conjecture.

**Proof.** By construction, the residual contains groups and subclasses for
which the repository has not yet recorded a route bridge through `FJ23`--
`FJ27`. Each route module explicitly warns that its residual is conservative:
unremoved cases may later be removed by new source verification, a different
known-case row, or a refined inheritance bridge. Therefore the residual
records absence of a project bridge, not a negative mathematical result.

**Remark.** This proposition is a bookkeeping fact internal to the project.
It should not be recorded as a new `ER-*` result.

## Proof or verification

Verification steps completed in this module:

1. Read the current route-subtraction modules `FJ23`--`FJ27`.
2. Compared their warnings and residual statements with `OQ-038`.
3. Created `ledgers/t001_residual.md` to store the first-pass residual
   buckets and candidate attack surfaces.
4. Preserved the Lueck open-status warning from `FJ19`: the project has not
   proved all torsion-free one-relator groups satisfy Farrell--Jones.
5. Preserved the Linton hierarchy caution from `FJ22`: hierarchy vocabulary is
   useful structure, not automatically a Farrell--Jones route.

## References

- Linton, M. (2024). *One-relator hierarchies* (arXiv:2202.11324v3). arXiv.
  https://arxiv.org/abs/2202.11324
- Lueck, W. (2025). *Survey on the Farrell--Jones conjecture*
  (arXiv:2507.11337). arXiv. https://arxiv.org/abs/2507.11337

Internal references:

- `modules/cycle_001/FJ19_one_relator_groups_dossier.md`
- `modules/cycle_001/FJ20_first_target_selection.md`
- `modules/cycle_002/FJ21_one_relator_structure_source_selection.md`
- `modules/cycle_002/FJ22_one_relator_hierarchy_vocabulary.md`
- `modules/cycle_002/FJ23_hyperbolic_route_subtraction.md`
- `modules/cycle_002/FJ24_cat0_route_subtraction.md`
- `modules/cycle_002/FJ25_virtually_solvable_route_subtraction.md`
- `modules/cycle_002/FJ26_hyperbolic_by_cyclic_route_subtraction.md`
- `modules/cycle_002/FJ27_inheritance_route_subtraction.md`

## Dependencies

This module depends on:

- `FJ19`;
- `FJ20`;
- `FJ21`;
- `FJ22`;
- `FJ23`;
- `FJ24`;
- `FJ25`;
- `FJ26`;
- `FJ27`;
- `OQ-038`.

## Results produced

This module produced:

- a first-pass resolution of `OQ-038`;
- `ledgers/t001_residual.md`;
- a candidate attack-surface table for `FJ29`;
- no new `ER-*` result.

## Open questions generated

- Which candidate residual bucket should `FJ29` select as the next concrete
  attack surface?
- Which source should be checked first for the selected bucket?

## Update to ledgers

After completion, update:

- `PROJECT_CHARTER.md` for the completed `FJ28` status and next `FJ29`;
- `README.md` for current progress;
- `SCOPE_LEDGER.md` for the residual ledger and next selection question;
- `NOTATION_LEDGER.md` for residual-ledger terms;
- `OPEN_QUESTIONS.md` to mark `OQ-038` first-pass resolved and focus `OQ-039`
  on `FJ29`;
- `BIBLIOGRAPHY.md` and `ledgers/source_status.md` for `FJ28` source use;
- `ledgers/open_group_classes.md` for the updated `T-001` residual status;
- `ledgers/theorem_dependencies.md` for the completed `FJ28` row and next
  dependency row;
- `references/papers_to_read.md` for the `FJ29` reading task.
