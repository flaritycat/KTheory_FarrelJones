# Module FJ53. \(\pi(w)>2\) Hyperbolic-Overlap Checkpoint

## Status

Completed

## Module type

Theorem map / Attack surface / Reflection

## Problem

`FJ52` checked Louder--Wilton as the selected `RB-006` boundary source. It
found no independent compact-special or CAT(0) route delta, but it did record
a source-verified bridge from \(\pi(w)>2\) to negative immersions.

The problem is to decide whether to record this bridge explicitly through the
already verified `FJ23` hyperbolic route, or to treat it as already absorbed
by the existing negative-immersion route marker.

## Input

- `FJ22`, one-relator hierarchy vocabulary and Linton negative-immersion
  theorem row;
- `FJ23`, hyperbolic-route subtraction;
- `FJ52`, Louder--Wilton negative-immersion boundary check;
- `OQ-074`;
- Linton (2024);
- Louder--Wilton (2022);
- `ledgers/t001_residual.md`.

## Output target

A route-overlap decision:

- state the source chain from \(\pi(w)>2\) to the hyperbolic route;
- decide whether it is new `RB-006` progress;
- decide whether it removes a concrete residual case;
- choose the next bounded project move.

## Definitions

**Definition.** The \(\pi(w)>2\) hyperbolic-overlap route is the following
source chain:

1. Louder--Wilton identify \(\pi(w)>2\) with negative immersions for the
   natural one-relator presentation complex;
2. Linton's negative-immersions theorem, already recorded in `FJ22`, gives
   hyperbolicity for one-relator complexes with negative immersions;
3. `FJ23` routes source-verified hyperbolic one-relator groups through the
   hyperbolic Farrell--Jones known-case row.

**Definition.** A hyperbolic-overlap checkpoint records that a source check
does not produce an independent CAT(0)/compact-special route, but does
produce a route criterion already governed by the hyperbolic route.

**Warning.** The \(\pi(w)>2\) route is not an `RB-006` compact-special or
CAT(0) route. It is a hyperbolic-route criterion. Any later use must preserve
the source chain and should be counted under `FJ23`.

## Main work

### Source chain

**Source-verified claim.** `FJ52` records from Louder--Wilton that the natural
presentation complex of \(F/\langle\langle w\rangle\rangle\) has negative
immersions exactly when \(\pi(w)>2\) (Louder & Wilton, 2022).

**Source-verified claim.** `FJ22` records from Linton that one-relator
complexes with negative immersions have hyperbolic fundamental groups
(Linton, 2024).

**Route principle.** `FJ23` records that a torsion-free one-relator group is
removed from `T-001` through the hyperbolic route once the project has a
source-verified bridge to word-hyperbolicity.

### Decision

**Route decision.** Record the \(\pi(w)>2\) criterion as an explicit
hyperbolic-route overlap. This is useful because it turns the earlier
negative-immersion route marker into a concrete source-chain checkpoint.

**Non-use warning.** Do not count this as new `RB-006` progress. The compact
special or CAT(0)-looking bucket remains untouched by this criterion except
in the negative sense: the Louder--Wilton source path did not produce the
geometric route delta hoped for by `RB-006`.

**No concrete subtraction.** `FJ53` does not select a specific one-relator
presentation word \(w\) and verify \(\pi(w)>2\) for it. Therefore it records
a route criterion, not a concrete residual subtraction.

### Route-overlap table

| Question | FJ53 answer |
|---|---|
| What is recorded? | A source chain: \(\pi(w)>2\) \(\Rightarrow\) negative immersions \(\Rightarrow\) hyperbolicity \(\Rightarrow\) `FJ23` hyperbolic route. |
| What source supplies \(\pi(w)>2\)? | Louder--Wilton (2022), as checked in `FJ52`. |
| What source supplies hyperbolicity? | Linton (2024), as recorded in `FJ22`. |
| Is this `RB-006` progress? | No. It is hyperbolic-route overlap. |
| Does it remove a concrete case now? | No. No presentation word is checked for \(\pi(w)>2\) in this module. |
| Next decision | Close the Louder--Wilton `RB-006` path and run a residual-bucket checkpoint in `FJ54`. |

## Proposition / Theorem / Conjecture / Example

**Route proposition.** If a torsion-free one-relator group is represented by
a natural one-relator presentation complex whose defining word \(w\) satisfies
the source hypotheses and \(\pi(w)>2\), then the project may route that group
through the `FJ23` hyperbolic route, not through `RB-006`.

**Proposition.** `FJ53` produces no concrete `T-001` residual subtraction.

**Route decision.** The Louder--Wilton `RB-006` path should be closed as an
independent compact-special/CAT(0) path. Its remaining value is the
hyperbolic-overlap criterion above.

## Proof or verification

For the route proposition, combine the two source-verified rows already
recorded in the repository. `FJ52` records Louder--Wilton's equivalence
between \(\pi(w)>2\) and negative immersions for the natural presentation
complex. `FJ22` records Linton's theorem that one-relator complexes with
negative immersions have hyperbolic fundamental groups. `FJ23` then supplies
the project route from source-verified hyperbolicity to the hyperbolic
Farrell--Jones known-case row.

The no-concrete-subtraction proposition follows because `FJ53` checks no
specific word \(w\) and verifies no new example. It only records the route
criterion and its correct bucket.

## References

- Linton, M. (2024). *One-relator hierarchies* (arXiv:2202.11324v3). arXiv.
  https://arxiv.org/abs/2202.11324
- Louder, L., & Wilton, H. (2022). Negative immersions for one-relator groups.
  *Duke Mathematical Journal, 171*(3), 547--594.
  https://doi.org/10.1215/00127094-2021-0024

Internal references:

- `modules/cycle_002/FJ22_one_relator_hierarchy_vocabulary.md`
- `modules/cycle_002/FJ23_hyperbolic_route_subtraction.md`
- `modules/cycle_003/FJ52_louder_wilton_negative_immersion_boundary.md`
- `ledgers/t001_residual.md`

## Dependencies

This module depends on:

- `FJ22`;
- `FJ23`;
- `FJ52`;
- `OQ-074`;
- Linton (2024);
- Louder--Wilton (2022);
- `ledgers/t001_residual.md`.

## Results produced

This module produced:

- a first-pass resolution of `OQ-074`;
- an explicit \(\pi(w)>2\) hyperbolic-overlap route criterion;
- a decision to close the Louder--Wilton `RB-006` path as non-subtractive for
  compact-special/CAT(0) purposes;
- no new `ER-*` result;
- no concrete residual subtraction.

## Open questions generated

- `OQ-075`: Which residual bucket or attack packet should follow the closed
  `RB-006` Louder--Wilton path?

## Update to ledgers

After completion, update:

- `README.md` and `PROJECT_CHARTER.md` for completed `FJ53` and next
  `FJ54`;
- `SCOPE_LEDGER.md` for the `OQ-074` resolution and new `OQ-075`;
- `OPEN_QUESTIONS.md` for `OQ-073`, `OQ-074`, and `OQ-075`;
- `NOTATION_LEDGER.md` for the \(\pi(w)>2\) hyperbolic-overlap route;
- `BIBLIOGRAPHY.md` and `ledgers/source_status.md` for the `FJ53` source-chain
  use;
- `ledgers/t001_residual.md`, `ledgers/theorem_dependencies.md`, and
  `ledgers/open_group_classes.md` for the current target update;
- `references/papers_to_read.md` for the next task.
