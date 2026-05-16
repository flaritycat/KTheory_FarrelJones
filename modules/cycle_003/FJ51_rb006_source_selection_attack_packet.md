# Module FJ51. RB-006 Source Selection and Attack Packet

## Status

Completed

## Module type

Attack surface / Source selection / Theorem map

## Problem

`FJ50` paused `RB-005` and selected `RB-006`, compact special or CAT(0)-looking
one-relator cases beyond the hyperbolic route, as the next attack packet.

The problem is to decide whether the repository already contains a bounded
source candidate for `RB-006`, without turning the module into a broad
cubulation survey and without re-counting cases already removed by the
hyperbolic route in `FJ23`.

## Input

- `FJ22`, one-relator hierarchy vocabulary;
- `FJ23`, hyperbolic-route subtraction;
- `FJ24`, CAT(0)-route subtraction and compact-special bridge;
- `FJ50`, `RB-005` route-delta checkpoint;
- `OQ-033` and `OQ-072`;
- `BIBLIOGRAPHY.md`;
- `ledgers/source_status.md`;
- `ledgers/t001_residual.md`;
- `reflections/strategic_audit_after_cycle_002.md`.

## Output target

An `RB-006` attack packet:

- identify candidate sources already present in the repository;
- decide whether one source is bounded enough for the next module;
- state how to avoid duplicating the hyperbolic route;
- state the stop condition for the next source check.

## Definitions

**Definition.** `RB-006` is the residual bucket of compact special or
CAT(0)-looking one-relator cases beyond the hyperbolic route.

**Definition.** An `RB-006-ready source` is a source that could plausibly
provide one of the following, with exact hypotheses:

- a compact special bridge for a one-relator group or subclass not already
  removed by `FJ23`;
- a direct finite-dimensional CAT(0)-group recognition theorem for a
  one-relator group or subclass not already removed by `FJ23`;
- a negative answer showing that the currently selected source only overlaps
  already recorded routes.

**Definition.** A `hyperbolic-overlap source` is a source whose likely route
output is hyperbolicity, or virtual specialness attached to hypotheses that
also imply hyperbolicity, so that any Farrell--Jones use is already governed
by `FJ23`.

**Warning.** A source that proves hyperbolicity and virtual specialness is
not automatically a new `RB-006` source. If hyperbolicity is already part of
the same checked hypothesis package, the project should count it in the
hyperbolic route unless a separate compact-special or CAT(0) bridge is
source-verified.

## Main work

### Candidate source table

| Candidate source | Current repository status | Possible RB-006 value | FJ51 decision |
|---|---|---|---|
| Haglund--Wise, *Special cube complexes* | Active bridge reference from `FJ24`. | Gives the compact-special-to-CAT(0) bridge once compact specialness is already known. | Not enough by itself; it is a bridge source, not a one-relator recognition source. |
| Linton, *One-relator hierarchies* | Active reference from `FJ22`--`FJ24`. | Provides hierarchy-to-hyperbolicity/virtual-special consequences under checked hypotheses. | Do not select as a new `RB-006` source; the recorded route is already hyperbolic-overlap for current purposes. |
| Linton--Nyberg-Brodda survey | Active orientation source from `FJ21`. | Could point to future cubulation sources. | Do not use as proof source; keep as orientation only. |
| Louder--Wilton, *Negative immersions for one-relator groups* | Found source in `FJ21`; not yet theorem-verified. | Could clarify the exact negative-immersion route and whether it gives any compact-special/CAT(0) route delta beyond hyperbolic overlap. | Select for the next bounded boundary check, not for immediate theorem use. |
| Lyndon--Schupp and Magnus--Karrass--Solitar | Classical background sources found in `FJ21`. | Useful for classical one-relator theorem background. | Too broad for `RB-006` as the immediate next step. |

### Attack packet

```markdown
# Attack Packet. RB-006 negative-immersion boundary check

## Candidate

Louder--Wilton, *Negative immersions for one-relator groups*, checked only
for whether it supplies an `RB-006` route delta.

## Why this is not already removed

`FJ23` already removes source-verified hyperbolic cases. `FJ24` already
removes source-verified compact finite-dimensional special cube complex
groups through the finite-dimensional CAT(0) route. `FJ49` blocks the direct
finite-extension shortcut for virtual compact special cases.

Therefore the source check must not count a theorem as new `RB-006` progress
if its useful output is only hyperbolicity, or virtual specialness packaged
with hyperbolicity.

## Known source data

- `FJ22` records Linton's negative-immersion route marker but does not import
  the exact definition as an active project definition.
- `FJ23` treats negative-immersion input as a future hyperbolicity bridge.
- `FJ24` records the compact-special-to-CAT(0) bridge through Haglund--Wise.
- `FJ21` located Louder--Wilton as a downstream source for negative
  immersions, primitivity rank, and Baumslag--Solitar obstructions.

## Missing bridge

An exact source-verified theorem saying whether Louder--Wilton supplies:

- a compact special or CAT(0) route not already covered by hyperbolicity;
- only a hyperbolic/subgroup route already governed by `FJ23`;
- or no bounded `RB-006` route input for the current project.

## Decision criterion

If Louder--Wilton gives only hyperbolic-route input, record the overlap and
pause this `RB-006` source path. If it supplies a compact-special or direct
CAT(0) recognition bridge with exact hypotheses, create the next theorem-use
module for those hypotheses.

## Stop condition

One source-boundary check only. If no `RB-006` route delta appears, write a
no-candidate or pivot artifact rather than continuing into adjacent
cubulation literature.
```

### Route decision

**Route decision.** `FJ51` selects Louder--Wilton (2022) for `FJ52`, but only
as a source-boundary check for `RB-006`.

This is deliberately weaker than selecting the source as theorem input. The
next module must first determine whether the source produces an `RB-006`
route delta at all, and must separate that from the hyperbolic route already
controlled by `FJ23`.

### Route delta

| Question | FJ51 answer |
|---|---|
| What route is affected? | `RB-006`, compact special or CAT(0)-looking one-relator cases beyond the hyperbolic route. |
| What source is selected? | Louder--Wilton (2022), as a boundary check only. |
| What does this enable? | A bounded `FJ52` source check. |
| What does it not enable? | No theorem use, no compact-special bridge, no CAT(0) recognition theorem, and no residual subtraction. |
| Next decision | Begin `FJ52`, checking whether Louder--Wilton gives an `RB-006` route delta or only hyperbolic overlap. |

## Proposition / Theorem / Conjecture / Example

**Selection.** `FJ51` selects Louder--Wilton (2022) as the next bounded source
to check for `RB-006`, with the explicit non-use warning that no theorem from
that source is imported yet.

**Proposition.** `FJ51` produces no new `T-001` residual subtraction.

## Proof or verification

The selection follows from the repository source-status ledger. Haglund--Wise
already supplies the compact-special-to-CAT(0) bridge, but not a one-relator
recognition theorem. Linton's hierarchy source is already active, but the
currently recorded virtual-special consequences are coupled to hyperbolic
route data and should not be counted again as `RB-006` progress. The only
remaining source already located in the repository and close to the
negative-immersion/cubical boundary is Louder--Wilton (2022), whose exact
theorems have not yet been checked.

The no-subtraction proposition follows because `FJ51` checks no new external
theorem and records no new group or subclass as compact special,
finite-dimensional CAT(0), or Farrell--Jones.

## References

No new external source was checked in this module. The following sources are
used through existing project source-status rows:

- Haglund, F., & Wise, D. T. (2008). Special cube complexes. *Geometric and
  Functional Analysis, 17*(5), 1551--1620.
  https://doi.org/10.1007/s00039-007-0629-4
- Linton, M. (2024). *One-relator hierarchies* (arXiv:2202.11324v3). arXiv.
  https://arxiv.org/abs/2202.11324
- Louder, L., & Wilton, H. (2022). Negative immersions for one-relator groups.
  *Duke Mathematical Journal, 171*(3), 547--594.
  https://doi.org/10.1215/00127094-2021-0024

Internal references:

- `modules/cycle_002/FJ22_one_relator_hierarchy_vocabulary.md`
- `modules/cycle_002/FJ23_hyperbolic_route_subtraction.md`
- `modules/cycle_002/FJ24_cat0_route_subtraction.md`
- `modules/cycle_003/FJ50_rb005_route_delta_checkpoint.md`
- `ledgers/source_status.md`
- `ledgers/t001_residual.md`

## Dependencies

This module depends on:

- `FJ22`;
- `FJ23`;
- `FJ24`;
- `FJ50`;
- `OQ-033`;
- `OQ-072`;
- `ledgers/source_status.md`;
- `ledgers/t001_residual.md`.

## Results produced

This module produced:

- a first-pass resolution of `OQ-072`;
- an `RB-006` attack packet;
- a source-boundary target for `FJ52`, Louder--Wilton (2022);
- no new `ER-*` result;
- no residual subtraction.

## Open questions generated

- `OQ-073`: Does Louder--Wilton's negative-immersion source produce an
  `RB-006` compact-special/CAT(0) route delta, or only hyperbolic-route
  overlap already governed by `FJ23`?

## Update to ledgers

After completion, update:

- `README.md` and `PROJECT_CHARTER.md` for completed `FJ51` and next
  `FJ52`;
- `SCOPE_LEDGER.md` for the `OQ-072` resolution and new `OQ-073`;
- `OPEN_QUESTIONS.md` for `OQ-033`, `OQ-072`, and `OQ-073`;
- `NOTATION_LEDGER.md` for `RB-006-ready source` and `hyperbolic-overlap
  source`;
- `BIBLIOGRAPHY.md` and `ledgers/source_status.md` for the Louder--Wilton
  source-selection status;
- `ledgers/t001_residual.md`, `ledgers/t001_kernel_recognition.md`,
  `ledgers/theorem_dependencies.md`, and `ledgers/open_group_classes.md` for
  the current target update;
- `references/papers_to_read.md` for the next task.
