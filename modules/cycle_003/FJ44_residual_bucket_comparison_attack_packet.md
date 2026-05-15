# Module FJ44. Residual-Bucket Comparison and RB-005 Attack Packet

## Status

Completed

## Module type

Attack surface / Reflection / Theorem map

## Problem

`FJ43` paused automatic continuation of the `RB-004`
BNS/Bieri--Renz/Bieri/Karrass--Solitar source cluster. The project now needs
a candidate-ready next move: either return to `RB-004` with a concrete
candidate, pivot to another residual bucket, or write a no-candidate note.

The problem is to compare the remaining residual buckets and select the next
bounded attack packet without importing new theorem content.

## Input

- `FJ24`, CAT(0)-route subtraction and virtual-special warning;
- `FJ27`, version-aware inheritance-route subtraction;
- `FJ28`, first-pass `T-001` residual ledger;
- `FJ39`, Karrass--Solitar finitely presented normal-subgroup bridge;
- `FJ43`, route-delta checkpoint pausing automatic `RB-004` source-cluster
  continuation;
- `reflections/strategic_audit_after_cycle_002.md`;
- `OQ-032`, `OQ-060`, and `OQ-065`;
- `ledgers/t001_residual.md`.

## Output target

Select the next attack packet after the `RB-004` source-cluster pause.

The selected packet should specify:

- the residual bucket;
- why it is not already removed;
- what source data is already recorded;
- the missing bridge;
- the decision criterion;
- the stop condition.

## Definitions

**Definition.** In this module, an `attack packet` is a bounded project
artifact containing a candidate bucket, known route data, missing bridge,
decision criterion, and stop condition.

**Definition.** `RB-005` is the residual bucket of virtually compact special
or finite-index bridge cases with formulation gaps, as recorded in
`ledgers/t001_residual.md`.

**Definition.** A `finite-index formulation bridge` is a source-verified or
project-approved passage from a finite-index subgroup with a recorded
Farrell--Jones status to the ambient group, preserving the source version
label.

## Main work

### Bucket comparison

| Bucket or route | Current status | Main obstruction | FJ44 decision |
|---|---|---|---|
| `RB-004` finite-rank free-kernel recognition | productive but paused by `FJ43` | no new candidate-ready BNS/Bieri/Bieri--Renz route | pause until a concrete candidate or missing bridge appears |
| `RB-005` finite-index / virtually compact special handling | directly tied to `FJ24`, `FJ27`, and the Karrass--Solitar dihedral cleanup issue | formulation/version mismatch for finite-index passage | select as next attack packet |
| `RB-006` compact special or CAT(0)-looking cases | potentially geometric | needs a cubulation/specialness source search before a bounded candidate exists | defer |
| `RB-007` virtually solvable recognition | could make `FJ25` more concrete | no classification or recognition source is selected inside the repository | defer |
| `RB-003` hierarchy-to-route extraction | uses Linton hierarchy vocabulary already adopted | hierarchy language is not itself a Farrell--Jones route | defer until a specific bridge source is selected |
| `RB-008` countable-free-kernel or extension cases | may interact with inheritance rows | no exact extension data and version-compatible quotient status are selected | defer |

### Selection

**Route decision.** `FJ44` selects `RB-005`, finite-index and virtually
compact special formulation handling, as the next attack packet.

This selection is conservative. It does not say that all virtually compact
special one-relator groups are removed from `T-001`. It says that the next
bounded project task is to determine exactly which finite-index passage can
be used, under which source formulation.

### Attack packet

```markdown
# Attack Packet. RB-005 finite-index formulation bridge

## Candidate

`RB-005`: virtually compact special or finite-index bridge cases with
formulation gaps.

## Why this is not already removed

`FJ24` subtracts compact finite-dimensional special cube complex groups through
the CAT(0) route, but it does not automatically subtract every virtually
compact special group. `FJ27` records finite-index overgroup inheritance only
with the source-level version flag preserved.

## Known source data

- `FJ24`: compact finite-dimensional special cube complex groups enter the
  finite-dimensional CAT(0) route.
- `FJ27`: full \(\mathcal{FJ}\) finite-index overgroup inheritance is recorded
  as a survey-level route with version flags.
- `FJ39`: the Karrass--Solitar infinite-dihedral alternative would require a
  finite-index or virtually cyclic passage before route use.

## Missing bridge

An exact finite-index/formulation statement saying which of the following is
available inside the project:

- coefficient K-theory finite-index overgroup inheritance;
- full \(\mathcal{FJ}\) finite-index overgroup inheritance only;
- a direct finite-dimensional CAT(0) bridge for the ambient group;
- or a formulation mismatch that forces an `FJ02` interruption.

## Decision criterion

If the source-verified finite-index bridge matches the desired route version,
record the version-flagged subtraction rule. If it does not, mark `FJ02` or a
source-conventions module as a blocker before using virtual-special or
dihedral finite-index data proof-sensitively.

## Stop condition

After one finite-index formulation check, either:

- record a usable version-flagged finite-index bridge;
- record that only full \(\mathcal{FJ}\)-level inheritance is currently
  available;
- or declare formulation debt active and route the next step to `FJ02`.
```

## Proposition / Theorem / Conjecture / Example

**Proposition.** `FJ44` selects `RB-005` as the next attack packet after the
`RB-004` source-cluster pause.

**Proposition.** `FJ44` produces no new `T-001` residual subtraction.

## Proof or verification

The first proposition follows from the bucket comparison. `RB-004` remains a
valid recorded bucket, but `FJ43` paused automatic source-cluster
continuation until a candidate-ready route is identified. `RB-006`,
`RB-007`, `RB-003`, and `RB-008` all require broader source selection before
they become bounded attack packets. By contrast, `RB-005` already has a
specific project obstruction: finite-index and source-formulation handling
for virtual-special and dihedral cleanup routes.

The second proposition follows because `FJ44` checks no new external theorem,
proves no group-specific bridge, and records no new membership in a known
Farrell--Jones class. It is a selection module only.

## References

No new external source was checked in this module. The following external
sources are inherited through earlier project modules and are listed here only
to identify the source-status rows involved:

- Bartels, A., & Reich, H. (2007). Coefficients for the Farrell-Jones
  conjecture. *Advances in Mathematics, 209*(1), 337--362.
  https://doi.org/10.1016/j.aim.2006.05.004
- Haglund, F., & Wise, D. T. (2008). Special cube complexes. *Geometric and
  Functional Analysis, 17*(5), 1551--1620.
  https://doi.org/10.1007/s00039-007-0629-4
- Karrass, A., & Solitar, D. (1978). One relator groups having a finitely
  presented normal subgroup. *Proceedings of the American Mathematical
  Society, 69*, 219--222. https://doi.org/10.1090/S0002-9939-1978-0466323-3
- Lueck, W. (2025). *Survey on the Farrell--Jones conjecture*
  (arXiv:2507.11337). arXiv. https://arxiv.org/abs/2507.11337
- Wegner, C. (2012). The K-theoretic Farrell-Jones conjecture for
  CAT(0)-groups. *Proceedings of the American Mathematical Society, 140*(3),
  779--793. https://doi.org/10.1090/S0002-9939-2011-11150-X

Internal references:

- `modules/cycle_002/FJ24_cat0_route_subtraction.md`
- `modules/cycle_002/FJ27_inheritance_route_subtraction.md`
- `modules/cycle_002/FJ28_residual_ledger_after_route_subtractions.md`
- `modules/cycle_002/FJ39_normal_subgroup_bridge_source_verification.md`
- `modules/cycle_003/FJ43_route_delta_checkpoint.md`
- `ledgers/t001_residual.md`

## Dependencies

This module depends on:

- `FJ24`;
- `FJ27`;
- `FJ28`;
- `FJ39`;
- `FJ43`;
- `OQ-032`;
- `OQ-060`;
- `OQ-065`.

## Results produced

This module produced:

- no established result number;
- a first-pass resolution of `OQ-065`;
- an attack packet selecting `RB-005`;
- a new next target: `FJ45`, finite-index formulation bridge checkpoint for
  `RB-005`.

## Open questions generated

- `OQ-066`: Which finite-index formulation bridge can be used for `RB-005`
  without collapsing source-version labels?

## Update to ledgers

After completion, update:

- `README.md` and `PROJECT_CHARTER.md` for the new current target;
- `SCOPE_LEDGER.md` for the `OQ-065` decision and `OQ-066`;
- `OPEN_QUESTIONS.md` for `OQ-032`, `OQ-060`, `OQ-065`, and `OQ-066`;
- `ledgers/t001_residual.md` for the `RB-005` attack packet;
- `ledgers/theorem_dependencies.md` for `FJ44` and `FJ45`;
- `references/papers_to_read.md` for the next task.
